# Exercise 1. Dominant Terms in a Sequence

## Given

Compute the following limit and explain why the highest-degree terms determine the result.

\[
L=\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}
\]

## 1. Identify the Highest-Degree Terms

The numerator and denominator are both polynomials of degree \(2\).

- The numerator is \(4n^2-3n+1\), whose highest-degree term is \(4n^2\).
- The denominator is \(2n^2+5n-7\), whose highest-degree term is \(2n^2\).

As \(n\to\infty\), the quadratic terms grow faster than the linear and constant terms. Therefore, the highest-degree terms determine the limit.

## 2. Divide by the Highest Power of \(n\)

The highest power is \(n^2\). Divide every term in the numerator and denominator by \(n^2\):

\[
L=\lim_{n\to\infty}
\frac{\frac{4n^2}{n^2}-\frac{3n}{n^2}+\frac1{n^2}}
{\frac{2n^2}{n^2}+\frac{5n}{n^2}-\frac7{n^2}}
\]

Simplifying gives

\[
L=\lim_{n\to\infty}
\frac{4-\frac3n+\frac1{n^2}}
{2+\frac5n-\frac7{n^2}}
\]

## 3. Evaluate the Limit

As \(n\to\infty\), we know that

\[
\lim_{n\to\infty}\frac1n=0
\]

and

\[
\lim_{n\to\infty}\frac1{n^2}=0
\]

Substituting these limits into the expression, we obtain

\[
L=\frac{4-3(0)+0}{2+5(0)-7(0)}
\]

Therefore,

\[
L=\frac42=2
\]

Hence,

\[
\boxed{\displaystyle
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}=2}
\]

## 4. Numerical Verification

To observe the behaviour of the sequence, we can calculate several terms.

| \(n\) | \(a_n=\frac{4n^2-3n+1}{2n^2+5n-7}\) |
|---:|---:|
| 2 | 1.0000 |
| 5 | 1.7059 |
| 10 | 1.8659 |
| 50 | 1.9711 |
| 100 | 1.9853 |
| 1000 | 1.9985 |

The numerical values approach \(2\) as \(n\) increases. This supports the result obtained algebraically.

## 5. Why Do the Highest-Degree Terms Determine the Result?

For large values of \(n\), the terms \(4n^2\) and \(2n^2\) become much larger than the remaining terms. The contributions of the linear and constant terms become negligible compared with \(n^2\).

Consequently, the fraction behaves approximately like

\[
\frac{4n^2}{2n^2}=\frac42=2
\]

More generally, if the numerator and denominator are polynomials of the same degree, their ratio approaches the ratio of their leading coefficients, provided the denominator's leading coefficient is nonzero.

The numerical table illustrates this behaviour, while the algebraic calculation establishes the limit mathematically.

## Final Answer

\[
\boxed{L=2}
\]

The limit equals \(2\) because the numerator and denominator have the same highest degree, and the ratio of their leading coefficients is \(\frac42=2\).
