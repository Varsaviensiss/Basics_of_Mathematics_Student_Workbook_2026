# Exercise 11. An n-th Root

We need to compute

\[
L=\lim_{n\to\infty}\sqrt[n]{5n+2n}.
\]

**Step 1: Simplify the expression**

Inside the root,

\[
5n+2n=7n.
\]

Therefore,

\[
L=\lim_{n\to\infty}\sqrt[n]{7n}.
\]

**Step 2: Separate the factors**

Using the property of roots,

\[
L=\lim_{n\to\infty}\sqrt[n]{7}\cdot\sqrt[n]{n}.
\]

As \(n\to\infty\),

\[
\sqrt[n]{7}\to1
\quad\text{and}\quad
\sqrt[n]{n}\to1.
\]

Therefore,

\[
L=1\cdot1.
\]

**Final Answer:**

\[
\boxed{L=1}
\]

**Explanation:**

The \(n\)-th root grows more slowly than the expression inside it. Even though \(5n+2n=7n\) increases without bound, taking the \(n\)-th root makes the expression approach \(1\).

Unlike a quotient of polynomials, where we compare the highest powers, here we use the behavior of \(n\)-th roots as \(n\) approaches infinity.
