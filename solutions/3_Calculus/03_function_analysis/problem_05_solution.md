# Problem 5. An Exponential Function with a Maximum

## Question

Analyze the monotonicity and extrema of

$$
f(x)=xe^{-x}.
$$

Also examine the behavior as $x\to\infty$ and explain how the limit affects the shape of the graph on the right-hand side.

## Solution

### 1. Domain

The exponential function $e^{-x}$ is defined for every real $x$, so the domain is $\mathbb{R}$.

### 2. Derivative and Monotonicity

Using the product rule gives

$$
f'(x)=e^{-x}-xe^{-x}=e^{-x}(1-x).
$$

Since $e^{-x}>0$ for every real $x$, the sign of $f'(x)$ depends on $1-x$. The derivative vanishes only at $x=1$.

- For $x<1$, $f'(x)>0$, so $f$ is increasing on $(-\infty,1)$.
- For $x>1$, $f'(x)<0$, so $f$ is decreasing on $(1,\infty)$.

### 3. Extrema

The function increases up to $x=1$ and decreases afterward, so its global maximum occurs at $x=1$. Since $f(1)=1/e$, the maximum point is $(1,1/e)$.

As $x\to-\infty$, we have $e^{-x}\to+\infty$ and $x\to-\infty$, so $xe^{-x}\to-\infty$. The function has no minimum.

### 4. Limit and Shape of the Graph on the Right

Rewrite $f(x)=x/e^x$. As $x\to\infty$, both the numerator and denominator tend to $+\infty$, so L'Hôpital's rule gives

$$
\lim_{x\to\infty}xe^{-x}
=\lim_{x\to\infty}\frac{x}{e^x}
=\lim_{x\to\infty}\frac{1}{e^x}
=0.
$$

Thus $y=0$ is the horizontal asymptote on the right. After the maximum at $(1,1/e)$, the graph decreases toward the $x$-axis from above because $xe^{-x}>0$ for $x>0$.
