# Problem 11. Choosing an Integration Method

## Question

For each integral below, choose a suitable method, explain your choice, and evaluate the integral. Verify each result by differentiation.

1. $\displaystyle \int \sin(3x)\,dx$
2. $\displaystyle \int x\ln x\,dx$
3. $\displaystyle \int \frac{x}{\sqrt{x^2+1}}\,dx$

## Solution

### 1. Integrate $\sin(3x)$

Use substitution because the inner function $3x$ has a constant derivative. Let $u=3x$. Then $du=3\,dx$, so

$$
\int\sin(3x)\,dx
=\frac13\int\sin u\,du
=-\frac13\cos u+C
=-\frac13\cos(3x)+C.
$$

By the chain rule,

$$
\frac{d}{dx}\left[-\frac13\cos(3x)+C\right]
=-\frac13\bigl[-3\sin(3x)\bigr]
=\sin(3x).
$$

### 2. Integrate $x\ln x$

For $x>0$, use integration by parts. Differentiating $\ln x$ gives $1/x$, which simplifies the remaining integral. Choose $u=\ln x$ and $dv=x\,dx$. Then $du=\frac1x\,dx$ and $v=\frac{x^2}{2}$.

$$
\begin{aligned}
\int x\ln x\,dx
&=\frac{x^2}{2}\ln x
-\int\frac{x^2}{2}\cdot\frac1x\,dx\\
&=\frac{x^2}{2}\ln x-\frac12\int x\,dx\\
&=\frac{x^2}{2}\ln x-\frac{x^2}{4}+C.
\end{aligned}
$$

By the product rule,

$$
\frac{d}{dx}\left[\frac{x^2}{2}\ln x-\frac{x^2}{4}+C\right]
=x\ln x+\frac{x}{2}-\frac{x}{2}
=x\ln x.
$$

### 3. Integrate $\frac{x}{\sqrt{x^2+1}}$

Use substitution because the numerator $x$ is half the derivative of the expression $x^2+1$ inside the square root. Let $u=x^2+1$. Then $du=2x\,dx$, so $x\,dx=\frac12\,du$. Using the power rule gives

$$
\begin{aligned}
\int\frac{x}{\sqrt{x^2+1}}\,dx
&=\frac12\int u^{-1/2}\,du\\
&=\frac12\cdot\frac{u^{1/2}}{1/2}+C\\
&=\sqrt{x^2+1}+C.
\end{aligned}
$$

By the chain rule,

$$
\frac{d}{dx}\left[\sqrt{x^2+1}+C\right]
=\frac{1}{2\sqrt{x^2+1}}\cdot 2x
=\frac{x}{\sqrt{x^2+1}}.
$$

### Comparison

| Integral | Method | Reason |
|---|---|---|
| $\int\sin(3x)\,dx$ | Substitution | The inner derivative is the constant $3$. |
| $\int x\ln x\,dx$ | Integration by parts | Differentiating $\ln x$ gives $1/x$, which simplifies the remaining product. |
| $\int\frac{x}{\sqrt{x^2+1}}\,dx$ | Substitution | The numerator is half the derivative of $x^2+1$, leaving a power integral in $u$. |
