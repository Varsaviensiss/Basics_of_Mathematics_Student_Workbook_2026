# Problem 9. Minimizing the Material Used for a Can

## Question

A closed cylinder has fixed volume $V$.

1. Write the volume constraint.
2. Eliminate one of the variables.
3. Express the surface area as a function of the radius $r$.
4. Find the relation between the height $h$ and the radius $r$ for which the material usage is minimal.

Interpret the obtained relation geometrically.

## Solution

### 1. Write the volume constraint

Let $r>0$ be the radius, $h>0$ the height, and $V>0$ the fixed volume. The volume constraint is

$$
\pi r^2h=V.
$$

### 2. Eliminate the height

Solving the volume constraint for $h$ gives

$$
h=\frac{V}{\pi r^2}.
$$

For every $r>0$, this formula gives a positive height.

### 3. Express the surface area as a function of the radius

The two circular ends contribute $2\pi r^2$, and the curved side contributes $2\pi rh$. Substituting the expression for $h$ gives

$$
S(r)=2\pi r^2+2\pi rh
=2\pi r^2+\frac{2V}{r},
\qquad r>0.
$$

### 4. Find and justify the minimum

Differentiating and setting the derivative equal to zero gives

$$
S'(r)=4\pi r-\frac{2V}{r^2}=0
\quad\Longrightarrow\quad
r^3=\frac{V}{2\pi}.
$$

Therefore, the optimal radius is $r_*=\sqrt[3]{V/(2\pi)}$. Since

$$
S''(r)=4\pi+\frac{4V}{r^3}>0
\qquad\text{for every }r>0,
$$

the surface area is strictly convex, so this stationary point is the unique global minimum. At the minimum, $V=2\pi r_*^3$, and the volume constraint gives

$$
h_*=\frac{V}{\pi r_*^2}=2r_*.
$$

### Geometric interpretation

The closed cylinder uses the least material when its height equals its diameter.
