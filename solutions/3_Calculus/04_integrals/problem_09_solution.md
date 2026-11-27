# Problem 9. Definite Integral and Geometric Area

## Question

Compute

$$
\int_{-1}^{2}x\,dx.
$$

Then separately compute the areas of the parts of the graph below and above the $x$-axis and explain the difference between the definite integral and geometric area.

## Solution

### 1. Compute the definite integral

An antiderivative of $x$ is $x^2/2$. By the Fundamental Theorem of Calculus,

$$
\int_{-1}^{2}x\,dx
=\left[\frac{x^2}{2}\right]_{-1}^{2}
=\frac{2^2}{2}-\frac{(-1)^2}{2}
=2-\frac12
=\frac32.
$$

### 2. Find the two geometric areas

The graph of $y=x$ crosses the $x$-axis at the origin. The line and the $x$-axis form a triangle on each side of the origin over the given interval.

- On $[-1,0]$, the triangle lies below the $x$-axis. Its base is $1$ and its height is $|f(-1)|=1$, so its area is $\frac12\cdot1\cdot1=\frac12$.
- On $[0,2]$, the triangle lies above the $x$-axis. Its base is $2$ and its height is $f(2)=2$, so its area is $\frac12\cdot2\cdot2=2$.

### 3. Compare the integral and the total area

The definite integral counts the area below the axis negatively and the area above it positively:

$$
-\frac12+2=\frac32.
$$

The total geometric area counts both triangles positively:

$$
\frac12+2=\frac52.
$$
