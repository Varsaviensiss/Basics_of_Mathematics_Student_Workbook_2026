# Exercise 6. From a Sequence to a Function — Limit at Infinity

## Question

Compute the limit

$$
\lim_{x\to\infty}\frac{3x^2-x+1}{5x^2+4x-2}.
$$

Compare your method with Exercise 1. Explain why the same method works and how a function limit as the real variable $x$ tends to infinity differs from a sequence limit as the integer index $n$ tends to infinity.

## Solution

The highest power of $x$ in both the numerator and denominator is $x^2$. Dividing every term by $x^2$ gives

$$
\lim_{x\to\infty}\frac{3x^2-x+1}{5x^2+4x-2}
=
\lim_{x\to\infty}\frac{3-\frac{1}{x}+\frac{1}{x^2}}{5+\frac{4}{x}-\frac{2}{x^2}}.
$$

As $x\to\infty$, both $1/x$ and $1/x^2$ tend to zero. The denominator tends to $5\ne0$, so

$$
\lim_{x\to\infty}\frac{3x^2-x+1}{5x^2+4x-2}
=\frac{3-0+0}{5+0-0}
=\boxed{\frac{3}{5}}.
$$

### Comparison with Exercise 1

In both exercises, dividing by the highest power makes the lower-degree terms tend to zero. The ratio of the leading coefficients gives $4/2=2$ in Exercise 1 and $3/5$ here.

In Exercise 1, $n$ takes positive integer values. Here, $x$ ranges over real values, and the limit must hold for all sufficiently large real $x$. The same method works because $1/x$ and $1/x^2$ tend to zero over the real numbers as well.
