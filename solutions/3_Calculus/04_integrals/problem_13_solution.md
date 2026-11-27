# Problem 13. An Integral Depending on the Upper Limit

## Question

Let

$$
F(x)=\int_0^x(t^2+1)\,dt.
$$

Determine $F(x)$, compute $F'(x)$, and compare the result with the integrand. Explain in your own words why the height of the function describes the local rate of increase of the accumulated area.

## Solution

### 1. Evaluate the integral

An antiderivative of $t^2+1$ is $t^3/3+t$. Evaluating at the upper and lower limits gives

$$
F(x)=\left[\frac{t^3}{3}+t\right]_0^x
=\frac{x^3}{3}+x.
$$

### 2. Differentiate and compare

Differentiating the result gives

$$
F'(x)=\frac{d}{dx}\left(\frac{x^3}{3}+x\right)=x^2+1.
$$

This is the original integrand evaluated at the upper limit $t=x$. It agrees with the Fundamental Theorem of Calculus because the integrand is continuous.

### 3. Explain the accumulated area geometrically

Let $f(t)=t^2+1$. Moving the upper limit from $x$ to $x+h$ changes the accumulated area by

$$
F(x+h)-F(x)=\int_x^{x+h}f(t)\,dt.
$$

For small positive $h$, this adds a thin strip of width $h$. Because $f$ is continuous, the height throughout that strip is close to $f(x)$. Its area is therefore approximately $h f(x)$. For negative $h$, a strip is removed, giving the same signed approximation.

Dividing by $h$ gives the average height over the strip. As $h\to0$, that average approaches the height at the boundary:

$$
\lim_{h\to0}\frac{F(x+h)-F(x)}{h}
=f(x)=x^2+1.
$$

Thus the graph's height at the moving upper limit is the local rate at which the signed area accumulates.
