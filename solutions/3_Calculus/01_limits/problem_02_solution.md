**Exercise 2. Different Growth Rates**

**1. Compute:**

\[
\lim_{n\to\infty}\frac{3n+1}{n^2+4}
\]

Divide the numerator and denominator by \(n^2\):

\[
=\lim_{n\to\infty}\frac{\frac{3}{n}+\frac{1}{n^2}}{1+\frac{4}{n^2}}
\]

As \(n\to\infty\), all fractions approach \(0\).

\[
=\frac{0+0}{1+0}=\boxed{0}
\]

**2. Compute:**

\[
\lim_{n\to\infty}\frac{2n^3-n^5}{n^2+1}
\]

Divide the numerator and denominator by \(n^5\):

\[
=\lim_{n\to\infty}\frac{\frac{2}{n^2}-1}{\frac{1}{n^3}+\frac{1}{n^5}}
\]

As \(n\to\infty\), the numerator approaches \(-1\), while the denominator approaches \(0\) through positive values.

Therefore,

\[
\boxed{-\infty}
\]

**General Observation:**

If the degree of the numerator is smaller than the degree of the denominator, the limit is \(0\). If the degree of the numerator is greater, the limit may approach positive or negative infinity, depending on the signs of the leading terms.
