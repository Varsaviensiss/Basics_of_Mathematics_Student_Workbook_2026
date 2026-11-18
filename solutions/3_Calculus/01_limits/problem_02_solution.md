# Exercise 2. Different Growth Rates

## Question

Compute the following limits:

1. $\displaystyle \lim_{n\to\infty}\frac{3n+1}{n^2+4}$
2. $\displaystyle \lim_{n\to\infty}\frac{2n^3-n}{5n^2+1}$

Compare the two results and explain how the degrees and the signs of the leading terms determine the behavior of each expression.

## Solution

### 1. First Limit

Divide the numerator and denominator by $n^2$:

$$
\lim_{n\to\infty}\frac{3n+1}{n^2+4}
=
\lim_{n\to\infty}\frac{3/n+1/n^2}{1+4/n^2}
=
\frac{0}{1}
=
\boxed{0}.
$$

The denominator has degree $2$, while the numerator has degree $1$. The denominator grows faster, so the ratio approaches zero.

### 2. Second Limit

Divide the numerator and denominator by $n^2$:

$$
\lim_{n\to\infty}\frac{2n^3-n}{5n^2+1}
=
\lim_{n\to\infty}\frac{2n-1/n}{5+1/n^2}
=
\boxed{+\infty}.
$$

The numerator $2n-1/n$ tends to $+\infty$, and the denominator $5+1/n^2$ tends to the positive constant $5$.

### Comparison

The first ratio approaches $0$ because the numerator has lower degree than the denominator. In the second ratio, the numerator has degree $3$ and the denominator has degree $2$, so the ratio grows in magnitude. Both leading coefficients, $2$ and $5$, are positive, so it grows toward $+\infty$.
