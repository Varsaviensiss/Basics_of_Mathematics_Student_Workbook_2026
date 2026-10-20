### Exercise 1. Dominant Terms in a Sequence

Compute:

\[
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}
\]

**Solution:**

Divide the numerator and denominator by \(n^2\):

\[
\lim_{n\to\infty}
\frac{4-\frac{3}{n}+\frac{1}{n^2}}
{2+\frac{5}{n}-\frac{7}{n^2}}
\]

As \(n\to\infty\), we have

\[
\frac1n\to0,\qquad \frac1{n^2}\to0.
\]

Therefore,

\[
\lim_{n\to\infty}
\frac{4-\frac{3}{n}+\frac{1}{n^2}}
{2+\frac{5}{n}-\frac{7}{n^2}}
=\frac42=\boxed{2}.
\]

**Explanation:**

The highest-degree terms determine the limit because \(n^2\) grows faster than \(n\) and constant terms as \(n\to\infty\). Thus, the ratio of the leading coefficients, \(4/2\), determines the result.


