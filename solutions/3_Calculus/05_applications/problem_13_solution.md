# Problem 13. Optimal Pipeline Routing Across Water and Land (Enrichment)

## Question

An offshore platform $P$ is $6$ km from the nearest point $A$ on a straight coastline. A refinery $R$ is $10$ km along the coast from $A$. A pipeline runs underwater from $P$ to a landing point $B$ on the segment $AR$, then continues along the coast to $R$.

The underwater pipeline costs USD 500,000 per kilometer, and the land pipeline costs USD 300,000 per kilometer. Find the landing point that minimizes construction cost, compute the minimum cost, and explain the analogy with Snell’s law.

## Solution

### 1. Build the cost function

Let $x=AB$ be the distance in kilometers from $A$ to $B$ toward $R$. The domain is $0\le x\le10$. By the Pythagorean theorem, the underwater segment has length $PB=\sqrt{x^2+36}$ km. The land segment has length $BR=10-x$ km.

Measuring cost in units of USD 100,000 gives

$$
C(x)=5\sqrt{x^2+36}+3(10-x).
$$

### 2. Find the global minimum

Differentiating gives

$$
C'(x)=\frac{5x}{\sqrt{x^2+36}}-3.
$$

Setting $C'(x)=0$ gives $5x=3\sqrt{x^2+36}$. Both sides are nonnegative on the domain, so squaring and simplifying gives

$$
25x^2=9(x^2+36)
\quad\Longrightarrow\quad
16x^2=324
\quad\Longrightarrow\quad
x_*=4.5\ \mathrm{km}.
$$

This critical point lies inside the domain. Moreover,

$$
C''(x)=\frac{180}{(x^2+36)^{3/2}}>0
$$

throughout the interval, so the cost is strictly convex and $x_*$ is the unique global minimizer.

### 3. Compute the route and cost

The optimal underwater length is $\sqrt{4.5^2+36}=7.5$ km. The remaining land length is $10-4.5=5.5$ km. The minimum cost is

$$
500{,}000(7.5)+300{,}000(5.5)=5{,}400{,}000\ \mathrm{USD}.
$$

| Landing distance $x$ (km) | Total cost (USD, nearest dollar) | Above minimum (USD) |
|---:|---:|---:|
| 0.0 | 6,000,000 | 600,000 |
| 2.0 | 5,562,278 | 162,278 |
| 4.0 | 5,405,551 | 5,551 |
| **4.5** | **5,400,000** | **0** |
| 5.0 | 5,405,125 | 5,125 |
| 7.0 | 5,509,772 | 109,772 |
| 10.0 | 5,830,952 | 430,952 |

### 4. Explain the analogy with Snell’s law

Let $\theta$ be the angle between the underwater segment and the normal to the shoreline. The right triangle $PAB$ gives $\sin\theta=x/\sqrt{x^2+36}$.

At the optimum, the marginal increase in underwater cost balances the marginal decrease in land cost. If $c_1$ and $c_2$ are the underwater and land costs per kilometer, this condition is $c_1\sin\theta=c_2$. It has the form of Snell’s law with cost per kilometer playing the role of travel time per kilometer and the shoreline segment making a $90^\circ$ angle with the normal:

$$
c_1\sin\theta=c_2\sin 90^\circ.
$$

Here $\sin\theta=300{,}000/500{,}000=4.5/7.5=3/5$, so $\theta\approx36.87^\circ$.
