**Exercise 3. A Square Root and Removing an Indeterminate Form**

Given:

\[
\lim_{n\to\infty}(\sqrt{n^2+5n}-n)
\]

**Solution:**

Multiply and divide by the conjugate expression:

\[
=\lim_{n\to\infty}
\frac{(\sqrt{n^2+5n}-n)(\sqrt{n^2+5n}+n)}
{\sqrt{n^2+5n}+n}
\]

Using the identity \((a-b)(a+b)=a^2-b^2\):

\[
=\lim_{n\to\infty}\frac{n^2+5n-n^2}{\sqrt{n^2+5n}+n}
\]

Simplify:

\[
=\lim_{n\to\infty}\frac{5n}{\sqrt{n^2+5n}+n}
\]

Divide the numerator and denominator by \(n\):

\[
=\lim_{n\to\infty}\frac{5}{\sqrt{1+\frac{5}{n}}+1}
\]

As \(n\to\infty\), \(\frac{5}{n}\to0\).

Therefore,

\[
=\frac{5}{\sqrt{1+0}+1}
=\frac{5}{2}
\]

**Final Answer:**

\[
\boxed{\frac{5}{2}}
\]

**Explanation:**

The conjugate expression removes the square root by using the difference of squares identity. This simplifies the expression and allows us to calculate the limit directly.
