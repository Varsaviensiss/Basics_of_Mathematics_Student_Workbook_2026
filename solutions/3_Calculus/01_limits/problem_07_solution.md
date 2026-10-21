# Exercise 7. Limit at a Point and Canceling a Factor

We need to compute

\[
L=\lim_{x\to3}\frac{x^2-4x+3}{x-3}.
\]

**Step 1: Substitute \(x=3\)**

Substituting \(x=3\) gives

\[
\frac{3^2-4(3)+3}{3-3}
=\frac{9-12+3}{0}
=\frac00.
\]

This is an indeterminate form, so we need to simplify the expression.

**Step 2: Factor the numerator**

We factor \(x^2-4x+3\):

\[
x^2-4x+3=(x-1)(x-3).
\]

Therefore,

\[
L=\lim_{x\to3}\frac{(x-1)(x-3)}{x-3}.
\]

**Step 3: Cancel the common factor**

For \(x\ne3\), we can cancel the factor \(x-3\):

\[
L=\lim_{x\to3}(x-1).
\]

**Step 4: Calculate the limit**

Now we substitute \(x=3\):

\[
L=3-1=2.
\]

Therefore, the final answer is

\[
\boxed{\lim_{x\to3}\frac{x^2-4x+3}{x-3}=2}.
\]

**Explanation: Why is the value of the function at \(x=3\) not needed?**

The limit describes the value that the function approaches as \(x\) gets closer to \(3\), not necessarily the value of the function at \(x=3\).

The original function is undefined at \(x=3\) because its denominator is zero. However, for values of \(x\) near \(3\), with \(x\ne3\), the expression simplifies to \(x-1\). As \(x\) approaches \(3\), this expression approaches \(2\).

Therefore, the function does not need to be defined at \(x=3\) for its limit to exist.

