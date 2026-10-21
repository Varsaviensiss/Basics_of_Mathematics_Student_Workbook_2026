```

# Problem 12: Compare Two Definite Integrals

Compare the following integrals and explain why they have different values.

\[
\int_{-2}^{2}x\,dx
\qquad \text{and} \qquad
\int_{-2}^{2}|x|\,dx
\]

## Part 1: Evaluate \(\int_{-2}^{2}x\,dx\)

### Step 1: Find the Antiderivative

\[
\int x\,dx=\frac{x^2}{2}+C
\]

### Step 2: Apply the Limits

\[
\int_{-2}^{2}x\,dx
=\left[\frac{x^2}{2}\right]_{-2}^{2}
\]

Substitute the upper and lower limits:

\[
=\frac{2^2}{2}-\frac{(-2)^2}{2}
\]

\[
=\frac42-\frac42
\]

Therefore,

\[
\boxed{\int_{-2}^{2}x\,dx=0}
\]

### Why Is the Result Zero?

The function \(f(x)=x\) is an **odd function**, meaning

\[
f(-x)=-f(x)
\]

Its graph is symmetric about the origin.

- From \(x=-2\) to \(x=0\), the graph forms a triangle below the \(x\)-axis.
- From \(x=0\) to \(x=2\), it forms an equal triangle above the \(x\)-axis.

The left triangle contributes \(-2\), and the right triangle contributes \(+2\).

These signed areas cancel:

\[
-2+2=0
\]

---

## Part 2: Evaluate \(\int_{-2}^{2}|x|\,dx\)

### Step 1: Understand the Absolute Value

The absolute value function is defined as

\[
|x|=
\begin{cases}
-x, & x<0\\
x, & x\geq 0
\end{cases}
\]

This means negative values of \(x\) become positive.

Therefore,

\[
\int_{-2}^{2}|x|\,dx
=\int_{-2}^{0}(-x)\,dx+\int_{0}^{2}x\,dx
\]

### Step 2: Integrate Each Part

For the first part:

\[
\int_{-2}^{0}(-x)\,dx
=\left[-\frac{x^2}{2}\right]_{-2}^{0}
\]

\[
=0-\left(-\frac42\right)=2
\]

For the second part:

\[
\int_{0}^{2}x\,dx
=\left[\frac{x^2}{2}\right]_{0}^{2}
\]

\[
=\frac42-0=2
\]

### Step 3: Add the Results

\[
\int_{-2}^{2}|x|\,dx=2+2
\]

Therefore,

\[
\boxed{\int_{-2}^{2}|x|\,dx=4}
\]

---

## Final Comparison

\[
\boxed{\int_{-2}^{2}x\,dx=0}
\]

\[
\boxed{\int_{-2}^{2}|x|\,dx=4}
\]

The first integral is zero because the positive and negative signed areas cancel. The second integral is \(4\) because the absolute value makes the entire graph lie on or above the \(x\)-axis.

## Key Idea: Symmetry

For an odd function \(f\), over a symmetric interval,

\[
\int_{-a}^{a}f(x)\,dx=0
\]

For this problem, \(x\) is odd, so its integral is zero.

However, \(|x|\) is an even function, since

\[
|-x|=|x|
\]

Its two halves contribute equal positive areas rather than canceling each other.

**Remember:** A definite integral measures signed area. Taking the absolute value of the function changes negative contributions into positive ones.

```
