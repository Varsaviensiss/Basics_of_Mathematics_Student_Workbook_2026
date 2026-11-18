# Exercise 1. Dominant Terms in a Sequence

## Question

Evaluate the limit

$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}.
$$

Identify the dominant terms in the numerator and denominator, and explain why they determine the limit.

## Solution

The dominant terms are $4n^2$ in the numerator and $2n^2$ in the denominator. Divide both by $n^2$:

$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}
=
\lim_{n\to\infty}\frac{4-3/n+1/n^2}{2+5/n-7/n^2}.
$$

As $n\to\infty$, both $1/n$ and $1/n^2$ tend to zero. Thus, after division by $n^2$, the lower-degree terms vanish and only the leading coefficients remain. Since the denominator tends to $2\ne 0$, the limit is

$$
\frac{4}{2}=\boxed{2}.
$$
