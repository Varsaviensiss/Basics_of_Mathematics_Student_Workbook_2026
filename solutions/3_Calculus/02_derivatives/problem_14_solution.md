```

# Problem 14. Continuity and Differentiability

Given the piecewise function:

\[
f(x)=
\begin{cases}
x^2, & x\geq 0\\
ax, & x<0
\end{cases}
\]

Determine the value of \(a\) for which the function is continuous and differentiable at \(x=0\).

## Step 1: Check Continuity at \(x=0\)

A function is continuous at \(x=0\) if:

\[
\lim_{x\to 0}f(x)=f(0)
\]

Since \(x\geq 0\), we use \(f(x)=x^2\) to find \(f(0)\):

\[
f(0)=0^2=0
\]

Now calculate the left-hand limit:

\[
\lim_{x\to 0^-}f(x)=\lim_{x\to 0^-}ax=0
\]

Calculate the right-hand limit:

\[
\lim_{x\to 0^+}f(x)=\lim_{x\to 0^+}x^2=0
\]

Both limits equal the function value:

\[
\lim_{x\to 0^-}f(x)
=
\lim_{x\to 0^+}f(x)
=
f(0)=0
\]

Therefore, the function is continuous at \(x=0\) **for every real value of \(a\)**.

\[
\boxed{a\in\mathbb{R}}
\]

## Step 2: Check Differentiability at \(x=0\)

A function is differentiable at \(x=0\) if its left-hand and right-hand derivatives are equal.

### Left-hand derivative

For \(x<0\):

\[
f(x)=ax
\]

Differentiating gives:

\[
f'(x)=a
\]

Therefore:

\[
\boxed{f'_-(0)=a}
\]

### Right-hand derivative

For \(x\geq 0\):

\[
f(x)=x^2
\]

Differentiating gives:

\[
f'(x)=2x
\]

At \(x=0\):

\[
\boxed{f'_+(0)=2(0)=0}
\]

## Step 3: Set the Derivatives Equal

For differentiability, the two one-sided derivatives must agree:

\[
f'_-(0)=f'_+(0)
\]

Substitute their values:

\[
a=0
\]

Thus, the function is differentiable at \(x=0\) only when:

\[
\boxed{a=0}
\]

## Step 4: Interpret the Result

- **Continuity:** The two pieces meet at \((0,0)\) for every real \(a\).
- **Differentiability:** The slopes must also match at \(x=0\). The left-hand slope is \(a\), while the right-hand slope is \(0\). They match only when \(a=0\).

## Final Answer

**For continuity:**

\[
\boxed{a\in\mathbb{R}}
\]

**For differentiability:**

\[
\boxed{a=0}
\]

**Key idea:** Differentiability implies continuity, but continuity does not necessarily imply differentiability. A function can be continuous while having different slopes on its two sides.

```
