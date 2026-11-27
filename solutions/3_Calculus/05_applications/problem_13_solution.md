# Solution to Problem 13: Capstone Synthesis & Advanced Optimization (Enrichment)

## 1. Problem Statement

### 1.1 Curriculum Structure Note
In the official course syllabus (`exercises/3_Calculus/05_applications_en.md`), the required core problem set for module **05. Applications of Differential and Integral Calculus** intentionally concludes with **Problem 12** (*Complete Model and Computer Verification*), as this module is designed to be cross-sectional and synthetic. 

To ensure complete coverage, consistency across the 15-problem workbook template, and advanced enrichment for university examinations, this document provides the formal analysis for an advanced capstone application: **Optimal Pipeline Routing Across Heterogeneous Media (Snell's Law of Economic Transport)**.

---

### 1.2 Problem Formulation
An offshore production platform $P$ is located $6\ \mathrm{km}$ out at sea from the nearest point $A$ on a straight coastline. An oil refinery $R$ is located on the coast, $10\ \mathrm{km}$ downshore from point $A$. 

A pipeline is to be constructed connecting the platform $P$ to the refinery $R$. The pipeline runs underwater in a straight line from $P$ to an intermediate coastal terminal point $B$ situated between $A$ and $R$, and then proceeds on land in a straight line along the coastline from $B$ to $R$.

The construction costs per unit distance are:
- Underwater pipeline: $\$500\,000\ \text{per km}$ ($5$ units of $\$100\,000$).
- Terrestrial coastal pipeline: $\$300\,000\ \text{per km}$ ($3$ units of $\$100\,000$).

Find the optimal landing location of point $B$ that minimizes the total construction cost, determine the minimum total cost, and verify the physical analogy to Snell's Law of refraction.

---

## 2. Theoretical Background and Concepts

### 2.1 Optimization on a Compact Interval
Let $C(x)$ be continuous on $[a, b]$ and differentiable on $(a, b)$. By the Extreme Value Theorem:
1. Critical points in $(a, b)$ are found by solving $C'(x) = 0$.
2. The absolute minimum is determined by evaluating $C(x)$ at all critical points and at the boundary endpoints $x = a$ and $x = b$.

### 2.2 Convexity and Global Extrema
If $C''(x) > 0$ for all $x \in [a, b]$, the cost function is strictly convex. Any interior critical point $x^* \in (a, b)$ is therefore the unique, strict global minimum on $[a, b]$.

### 2.3 Fermat's Principle and Snell's Law Analogy
In geometric optics, Fermat's Principle states that light travels along the path that minimizes travel time. In heterogeneous media with wave propagation speeds $v_1$ and $v_2$, the optimal path obeys Snell's Law:
$$
\frac{\sin\theta_1}{v_1} = \frac{\sin\theta_2}{v_2}.
$$
In economic routing, unit costs $c_1$ and $c_2$ play the role of inverse velocities $1/v_1$ and $1/v_2$. The cost-optimal angle of incidence $\theta$ satisfies:
$$
\sin\theta = \frac{c_2}{c_1}.
$$

---

## 3. Detailed Step-by-Step Solution

### Step 1: Geometric Setup and Coordinate Assignment
We set up a Cartesian coordinate system along the coastline:
- Let the coastline lie on the $x$-axis.
- Let $A = (0, 0)$ be the point on the shoreline closest to the platform $P$.
- The platform is located at $P = (0, 6)$ in kilometers.
- The refinery is located at $R = (10, 0)$ in kilometers.
- The intermediate shore terminal $B$ has coordinates $(x, 0)$, where $x \in [0, 10]$.

```
   P (0, 6) [Offshore Platform]
   | \
   |  \  Underwater segment
6 km  \   L_1 = sqrt(x^2 + 36)
   |    \
   |     \
   A------B-------------------------R
  (0,0)  (x,0)                    (10,0)
   <--x--> <-------- 10 - x ------->
              Land segment L_2
```

The geometric lengths of the two segments are:
- Underwater segment:
  $$
  L_1(x) = \sqrt{x^2 + 6^2} = \sqrt{x^2 + 36}\quad [\mathrm{km}].
  $$
- Terrestrial coastal segment:
  $$
  L_2(x) = 10 - x\quad [\mathrm{km}].
  $$

### Step 2: Formulation of the Total Cost Function
Let cost be expressed in units of $\$100\,000$:
- Unit cost underwater: $c_1 = 5$ (i.e., $\$500\,000/\mathrm{km}$).
- Unit cost on land: $c_2 = 3$ (i.e., $\$300\,000/\mathrm{km}$).

The total cost function $C(x)$ is:
$$
C(x) = 5 L_1(x) + 3 L_2(x) = 5\sqrt{x^2 + 36} + 3(10 - x), \qquad x \in [0, 10].
$$

### Step 3: Computation of the First Derivative
Using the chain rule to differentiate the square root:
$$
\frac{d}{dx}\left(\sqrt{x^2 + 36}\right) = \frac{2x}{2\sqrt{x^2 + 36}} = \frac{x}{\sqrt{x^2 + 36}}.
$$
Thus:
$$
C'(x) = \frac{5x}{\sqrt{x^2 + 36}} - 3.
$$

### Step 4: Finding the Critical Point
Setting $C'(x) = 0$:
$$
\frac{5x}{\sqrt{x^2 + 36}} = 3 \iff 5x = 3\sqrt{x^2 + 36}.
$$
Since $x \ge 0$, both sides are non-negative. Squaring both sides:
$$
(5x)^2 = 9(x^2 + 36) \implies 25x^2 = 9x^2 + 324.
$$
Subtracting $9x^2$ from both sides:
$$
16x^2 = 324 \implies x^2 = \frac{324}{16} = \frac{81}{4}.
$$
Taking the positive square root:
$$
x^* = \sqrt{\frac{81}{4}} = \frac{9}{2} = 4.5\ \mathrm{km}.
$$
Since $4.5 \in [0, 10]$, $x^* = 4.5\ \mathrm{km}$ is a physically feasible interior critical point.

### Step 5: Verification of Convexity and Global Minimum
We differentiate $C'(x)$ to find the second derivative:
$$
C''(x) = \frac{d}{dx}\left(5x(x^2 + 36)^{-1/2} - 3\right) = 5\left[(x^2 + 36)^{-1/2} - x^2(x^2 + 36)^{-3/2}\right].
$$
Combining terms over a common denominator:
$$
C''(x) = 5 \cdot \frac{(x^2 + 36) - x^2}{(x^2 + 36)^{3/2}} = \frac{180}{(x^2 + 36)^{3/2}}.
$$
Because $(x^2 + 36)^{3/2} > 0$ for all real $x$:
$$
C''(x) > 0 \quad \text{for all } x \in [0, 10].
$$
The function $C(x)$ is strictly convex on $[0, 10]$. Therefore, $x^* = 4.5\ \mathrm{km}$ is the unique, strict global minimum.

### Step 6: Calculation of Optimal Route and Minimum Cost
At $x^* = 4.5\ \mathrm{km}$:
- Length of underwater pipeline:
  $$
  L_1(4.5) = \sqrt{(4.5)^2 + 6^2} = \sqrt{20.25 + 36} = \sqrt{56.25} = 7.5\ \mathrm{km}.
  $$
- Length of land pipeline:
  $$
  L_2(4.5) = 10 - 4.5 = 5.5\ \mathrm{km}.
  $$
- Total optimal cost (in $\$100\,000$ units):
  $$
  C(4.5) = 5(7.5) + 3(5.5) = 37.5 + 16.5 = 54.0.
  $$
In currency units:
$$
\text{Total Minimum Cost} = 54 \times \$100\,000 = \$5\,400\,000.
$$

---

## 4. Verification and Consistency Checks

### 4.1 Boundary Value and Competitor Route Comparison
We evaluate the cost function at the endpoints and intermediate sample values:

| Strategy | Shore Landing $x$ ($\mathrm{km}$) | Underwater Length $L_1$ ($\mathrm{km}$) | Land Length $L_2$ ($\mathrm{km}$) | Total Cost ($\$$) | Difference from Optimum |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **Direct to $A$ (Min Sea)** | $0.0$ | $6.000$ | $10.000$ | $\$6\,000\,000$ | $+\$600\,000$ |
| Intermediate | $2.0$ | $\sqrt{40} \approx 6.325$ | $8.000$ | $\$5\,562\,278$ | $+\$162\,278$ |
| Intermediate | $4.0$ | $\sqrt{52} \approx 7.211$ | $6.000$ | $\$5\,405\,552$ | $+\$5\,552$ |
| **Optimal Route** | **$4.5$** | **$7.500$** | **$5.500$** | **$\$5\,400\,000$** | **$\$0$ (GLOBAL MIN)** |
| Intermediate | $5.0$ | $\sqrt{61} \approx 7.810$ | $5.000$ | $\$5\,405\,125$ | $+\$5\,125$ |
| Intermediate | $7.0$ | $\sqrt{85} \approx 9.220$ | $3.000$ | $\$5\,509\,782$ | $+\$109\,782$ |
| **Straight to $R$ (Direct)**| $10.0$ | $\sqrt{136} \approx 11.662$ | $0.000$ | $\$5\,830\,952$ | $+\$430\,952$ |

The numerical table confirms that:
1. Minimizing sea distance ($x = 0$) results in an excessive land distance, costing $\$6.0\ \mathrm{M}$.
2. Direct connection to the refinery ($x = 10$) incurs excessive sea costs, costing $\$5.831\ \mathrm{M}$.
3. The compromise point $x = 4.5\ \mathrm{km}$ saves up to $\$600\,000$.

### 4.2 Economic Snell's Law Verification
Let $\theta$ be the angle between the underwater pipeline $PB$ and the normal to the shoreline ($PA$):
$$
\sin\theta = \frac{AB}{PB} = \frac{x^*}{\sqrt{(x^*)^2 + 6^2}} = \frac{4.5}{7.5} = \frac{9}{15} = \frac{3}{5} = 0.6.
$$
The ratio of terrestrial unit cost to underwater unit cost is:
$$
\frac{c_2}{c_1} = \frac{300\,000}{500\,000} = \frac{3}{5} = 0.6.
$$
Thus:
$$
\sin\theta = \frac{c_2}{c_1} \iff \theta = \arcsin(0.6) \approx 36.87^\circ.
$$
This demonstrates that the mathematical optimization condition $C'(x^*) = 0$ is completely identical to the physical refraction law governing wave propagation across two media.
