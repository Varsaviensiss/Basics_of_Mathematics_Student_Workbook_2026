# Exercise 8. A Square Root in a Function Limit

We need to compute

\[
L=\lim_{x\to4}\frac{\sqrt{x}-2}{x-4}.
\]

**Step 1: Substitute \(x=4\)**

\[
\frac{\sqrt4-2}{4-4}
=\frac{2-2}{0}
=\frac00.
\]

This is an indeterminate form, so we rationalize the numerator.

**Step 2: Multiply by the conjugate**

The conjugate of \(\sqrt{x}-2\) is \(\sqrt{x}+2\). We multiply the numerator and denominator by this expression:

\[
L=\lim_{x\to4}
\frac{\sqrt{x}-2}{x-4}
\cdot\frac{\sqrt{x}+2}{\sqrt{x}+2}.
\]

Therefore,

\[
L=\lim_{x\to4}
\frac{(\sqrt{x}-2)(\sqrt{x}+2)}
{(x-4)(\sqrt{x}+2)}.
\]

**Step 3: Simplify the expression**

Using the identity

\[
(a-b)(a+b)=a^2-b^2,
\]

we obtain

\[
(\sqrt{x}-2)(\sqrt{x}+2)=x-4.
\]

Thus,

\[
L=\lim_{x\to4}
\frac{x-4}{(x-4)(\sqrt{x}+2)}.
\]

For \(x\ne4\), we cancel the common factor \(x-4\):

\[
L=\lim_{x\to4}\frac{1}{\sqrt{x}+2}.
\]

**Step 4: Calculate the limit**

Now we substitute \(x=4\):

\[
L=\frac{1}{\sqrt4+2}
=\frac{1}{2+2}
=\frac14.
\]

Therefore, the final answer is

\[
\boxed{L=\frac14}.
\]

**Comparison with Exercise 3**

In Exercise 3, we used the same rationalization technique to calculate a sequence limit involving a square root. Here, we use it for a function limit.

In both exercises, we multiply by the conjugate to remove the square root from a difference and simplify the expression. The main difference is that Exercise 3 uses the variable \(n\), which takes integer values, while Exercise 8 uses the real variable \(x\), which approaches \(4\).

The algebraic technique is the same in both cases.

