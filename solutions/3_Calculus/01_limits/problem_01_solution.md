## Given

\[
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}
\]

### 1. Divide by the Highest Power

The highest power of \(n\) in both the numerator and denominator is \(n^2\). Divide every term by \(n^2\):

\[
\lim_{n\to\infty}
\frac{4-\frac3n+\frac1{n^2}}
{2+\frac5n-\frac7{n^2}}
\]

### 2. Evaluate the Limit

As \(n\to\infty\),

\[
\frac1n\to0,\qquad \frac1{n^2}\to0
\]

Therefore,

\[
L=\frac{4-0+0}{2+0-0}
=\frac42=2
\]

### 3. Why Do the Highest-Degree Terms Determine the Result?

For large \(n\), the terms \(4n^2\) and \(2n^2\) dominate the lower-degree terms. The lower-degree terms become insignificant compared with \(n^2\).

### Final Answer

\[
\boxed{L=2}
\]

For rational functions whose numerator and denominator have the same degree, the limit at infinity equals the ratio of their leading coefficients.
