# Exercise 13. Intersection of a Sphere and a Plane

## Question

Find the intersection of the sphere $x^2+y^2+z^2=25$ with the plane $z=3$. Identify the intersection curve and give its center and radius. Then replace $z=3$ with $z=c$ and describe the intersection for all real values of $c$.

## Solution

### 1. Intersection at $z=3$

Substituting $z=3$ into the sphere equation gives

$$
x^2+y^2+3^2=25
\quad\Longrightarrow\quad
x^2+y^2=16.
$$

The intersection is a circle in the plane $z=3$, centered at $(0,0,3)$ with radius $\sqrt{16}=4$.

### 2. Intersection at $z=c$

Substituting $z=c$ gives

$$
x^2+y^2=25-c^2.
$$

- If $|c|<5$, the intersection is a circle centered at $(0,0,c)$ with radius $\sqrt{25-c^2}$.
- If $|c|=5$, the right-hand side is zero, so the intersection is the single point $(0,0,c)$.
- If $|c|>5$, the right-hand side is negative. Since $x^2+y^2$ is nonnegative, there is no real intersection.

The radius is largest at $c=0$ and decreases to zero as $|c|$ approaches $5$.
