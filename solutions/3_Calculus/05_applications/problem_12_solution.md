# Problem 12. Complete Model and Computer Verification

## Question

A museum wants to create a rectangular exhibition room next to an existing straight wall. The side along the wall does not need to be built. The two sides perpendicular to the wall cost $300\ \mathrm{PLN/m}$ each, while the side parallel to the wall costs $500\ \mathrm{PLN/m}$. The budget is $30{,}000\ \mathrm{PLN}$.

Build a model that maximizes the area of the room and prepare a complete analysis containing:

- definition of variables and units,
- mathematical model,
- domain resulting from the problem statement,
- computation of the derivative,
- determination and verification of the optimum,
- interpretation of the result,
- graph of the objective function,
- numerical verification of several values near the optimum found.

Finally, indicate which part of the solution required modeling the problem and which part was only the execution of the calculation. Produce the graph and computer calculations only after completing the mathematical solution, and treat them as verification.

## Solution

### 1. Define the variables and build the model

Let $x$ be the length of each side perpendicular to the wall and $y$ the length of the side parallel to the wall. Both lengths are measured in meters. The area is $A=xy$.

Only three sides are built, so the total cost is $600x+500y$. At the maximum the full budget is used. If any budget remained, we could increase $y$ while keeping $x>0$ fixed, which would increase the area. Therefore,

$$
600x+500y=30{,}000
\qquad\Longrightarrow\qquad
y=60-1.2x.
$$

Substituting into the area formula gives

$$
A(x)=x(60-1.2x)=60x-1.2x^2.
$$

### 2. Determine the physical domain

The room must have two positive side lengths. Thus $x>0$ and $y=60-1.2x>0$, which gives

$$
0<x<50.
$$

### 3. Find and verify the maximum analytically

Differentiating gives

$$
A'(x)=60-2.4x,
\qquad
A''(x)=-2.4.
$$

Solving $A'(x)=0$ gives $x=25$, which lies in the physical domain. Since $A''(x)<0$ throughout the domain, the stationary point is the unique global maximum.

The other dimension is $y=60-1.2(25)=30$ m. The maximum area is $A(25)=25\cdot30=750\ \mathrm{m}^2$. The cost is

$$
2(300)(25)+500(30)=15{,}000+15{,}000=30{,}000\ \mathrm{PLN}.
$$

Thus each side perpendicular to the wall should be **25 m** long, and the constructed side parallel to the wall should be **30 m** long.

### 4. Verify with a graph and computer calculations

The objective function is a downward-opening parabola. Its vertex is $(25,750)$. The open circles mark the excluded endpoints, where the rectangle would have zero area.

```text
A(x) (m²)
  ^
750 |                  ╭──●──╮
    |              ╭───╯     ╰───╮
    |           ╭──╯             ╰──╮
    |        ╭──╯                   ╰──╮
    |     ╭──╯                         ╰──╮
    |   ╭─╯                               ╰─╮
  0 ○─────────────────────┬─────────────────○──> x (m)
    0                    25                50

                         ● (25, 750)
```

The following values check the area near the analytical optimum.

| $x$ (m) | $A(x)$ (m²) |
|---:|---:|
| 24.0 | 748.80 |
| 24.5 | 749.70 |
| 25.0 | 750.00 |
| 25.5 | 749.70 |
| 26.0 | 748.80 |

This Python code reproduces the values and plots the objective function:

```python
import matplotlib.pyplot as plt

def area(x):
    return x * (60 - 1.2 * x)

for x in [24, 24.5, 25, 25.5, 26]:
    print(f"x = {x:4.1f} m, A(x) = {area(x):.2f} m²")

x_values = [i / 10 for i in range(1, 500)]
plt.plot(x_values, [area(x) for x in x_values])
plt.scatter([0, 50], [0, 0], facecolors="none", edgecolors="black")
plt.scatter([25], [area(25)], color="black")
plt.annotate("(25, 750)", (25, 750), xytext=(8, -15),
             textcoords="offset points")
plt.xlabel("x (m)")
plt.ylabel("A(x) (m²)")
plt.show()
```

The graph and nearby values agree with the maximum proved analytically.

### 5. Distinguish modeling from calculation

Modeling required choosing the side lengths as variables, counting the three constructed sides, using their different costs, justifying full use of the budget, and restricting the domain to positive dimensions. Once the model was established, differentiating $A(x)$, solving $A'(x)=0$, and checking $A''(x)$ were the calculation steps.
