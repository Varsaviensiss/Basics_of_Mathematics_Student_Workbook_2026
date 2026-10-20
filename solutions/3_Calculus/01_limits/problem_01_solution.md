# Exercise 1. Dominant Terms in a Sequence

## Problem

Compute the limit

\[
L=\lim_{n\to\infty}
\frac{4n^2-3n+1}{2n^2+5n-7}
\]

Explain why the highest-degree terms determine the result.

## 1. Solution Using Algebra

The given sequence is

\[
a_n=\frac{4n^2-3n+1}{2n^2+5n-7}.
\]

Divide both the numerator and the denominator by \(n^2\):

\[
a_n=
\frac{4-\frac{3}{n}+\frac{1}{n^2}}
{2+\frac{5}{n}-\frac{7}{n^2}}.
\]

As \(n\to\infty\),

\[
\lim_{n\to\infty}\frac1n=0,
\qquad
\lim_{n\to\infty}\frac1{n^2}=0.
\]

Therefore,

\[
\begin{aligned}
L
&=\frac{4-3(0)+0}{2+5(0)-7(0)}\\[4pt]
&=\frac42\\[4pt]
&=\boxed{2}.
\end{aligned}
\]

Thus, the limit of the sequence is \(2\).

## 2. Numerical Table

To observe the behaviour of the sequence, calculate several terms:

\[
a_n=\frac{4n^2-3n+1}{2n^2+5n-7}.
\]

| \(n\) | \(a_n\), approximately |
|---:|---:|
| 2 | 1.0000 |
| 5 | 1.7059 |
| 10 | 1.8659 |
| 50 | 1.9711 |
| 100 | 1.9853 |
| 1000 | 1.9985 |

The values approach \(2\) as \(n\) increases.

## 3. Why Do the Highest-Degree Terms Determine the Limit?

The numerator and denominator are both polynomials of degree \(2\). Their highest-degree terms are \(4n^2\) and \(2n^2\).

For large values of \(n\), the lower-degree terms become insignificant compared with \(n^2\). Therefore, the fraction behaves approximately like

\[
\frac{4n^2}{2n^2}=\frac42=2.
\]

More generally, if the numerator and denominator are polynomials of the same degree, the limit at infinity equals the ratio of their leading coefficients.

## Conclusion

Both the algebraic calculation and the numerical table show that

\[
\boxed{\displaystyle
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}=2
}.
\]

The numerical table supports our intuition, while the algebraic calculation proves the result.



