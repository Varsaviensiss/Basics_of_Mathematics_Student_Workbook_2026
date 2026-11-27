# Problem 2. Powers, Roots, and the Domain

## Question

Find the antiderivative of

$$
\int \left(2\sqrt{x}+\frac{3}{x^2}-x^{1/3}\right)\,dx.
$$

Rewrite the terms as powers, determine the domain of the original integrand, and verify the result by differentiation.

## Solution

### 1. Rewrite the integrand and determine its domain

The square root requires $x\ge 0$, and the denominator $x^2$ excludes $x=0$. The cube root $x^{1/3}$ is defined for every real $x$. Combining these conditions gives the domain $(0,\infty)$.

For $x>0$, the integrand in power form is

$$
2x^{1/2}+3x^{-2}-x^{1/3}.
$$

### 2. Integrate term by term

Using the power rule $\int x^p\,dx=\frac{x^{p+1}}{p+1}+C$ for $p\ne-1$, we obtain

$$
\begin{aligned}
\int \left(2x^{1/2}+3x^{-2}-x^{1/3}\right)\,dx
&=2\frac{x^{3/2}}{3/2}+3\frac{x^{-1}}{-1}
-\frac{x^{4/3}}{4/3}+C\\
&=\frac43x^{3/2}-\frac3x-\frac34x^{4/3}+C,
\qquad C\in\mathbb{R}.
\end{aligned}
$$

### 3. Verify by differentiation

Differentiating the result gives

$$
\begin{aligned}
F'(x)
&=\frac43\cdot\frac32 x^{1/2}
+3x^{-2}
-\frac34\cdot\frac43x^{1/3}\\
&=2\sqrt{x}+\frac3{x^2}-x^{1/3}.
\end{aligned}
$$

This matches the assigned integrand for every $x>0$.
