# Exercise 11. An n-th Root

## Question

Evaluate the limit

$$
\lim_{n\to\infty}\sqrt[n]{5^n+2^n}.
$$

Explain why the larger exponential base determines the limit, and compare this with the role of the highest degree in polynomial expressions.

## Solution

Factor out $5^n$, the term with the larger exponential base:

$$
\sqrt[n]{5^n+2^n}
=
\sqrt[n]{5^n\left(1+\left(\frac25\right)^n\right)}
=
5\left(1+\left(\frac25\right)^n\right)^{1/n}.
$$

For every positive integer $n$, we have $0<\left(\frac25\right)^n<1$. Therefore,

$$
5\leq\sqrt[n]{5^n+2^n}\leq5\cdot2^{1/n}.
$$

Since $2^{1/n}\to1$, both bounds approach $5$. By the Squeeze Theorem,

$$
\boxed{\lim_{n\to\infty}\sqrt[n]{5^n+2^n}=5}.
$$

## Comparison with Polynomial Expressions

For the exponentials, the ratio of the smaller term to the larger term is $(2/5)^n$, which tends to zero. The remaining dominant factor is $5^n$, whose $n$-th root is $5$.

In a polynomial, dividing by the highest power of $n$ makes the lower-degree terms tend to zero. In both cases, factoring out the fastest-growing term reveals what determines the limit. For exponentials with the same exponent $n$, the base determines which term grows faster. For polynomial terms, the degree determines which term grows faster.
