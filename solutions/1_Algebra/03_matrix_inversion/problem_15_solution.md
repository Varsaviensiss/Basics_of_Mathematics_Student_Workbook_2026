# 📘 Linear Algebra — Exercise 15
## Two Methods for Solving the Same System

---

### 🎯 Objective

Solve the linear system \(Ax=b\) using two different methods:

1. **Inverse Matrix Method** — \(x=A^{-1}b\)
2. **Gaussian Elimination** — row operations on an augmented matrix

Finally, compare the solutions, the essential steps, and the simplicity of each method.

---

### 🧮 Given System

We are given

\[
A=\begin{pmatrix}
2&1\\
1&3
\end{pmatrix},
\qquad
b=\begin{pmatrix}
7\\
8
\end{pmatrix}
\]

The equation \(Ax=b\) corresponds to the system

\[
\begin{cases}
2x+y=7\\
x+3y=8
\end{cases}
\]

Our goal is to find the vector

\[
x=\begin{pmatrix}x\\y\end{pmatrix}
\]

that satisfies both equations.

---

## 🔹 Method 1 — Using the Inverse Matrix

### Step 1: Find \(A^{-1}\)

For a \(2\times2\) matrix,

\[
A^{-1}=\frac{1}{ad-bc}
\begin{pmatrix}
d&-b\\
-c&a
\end{pmatrix}
\]

First, calculate the determinant:

\[
\det(A)=(2)(3)-(1)(1)=6-1=5
\]

Since \(\det(A)=5\neq0\), the inverse exists.

Therefore,

\[
A^{-1}=\frac15
\begin{pmatrix}
3&-1\\
-1&2
\end{pmatrix}
\]

### Step 2: Calculate \(x=A^{-1}b\)

Using the formula \(x=A^{-1}b\),

\[
x=\frac15
\begin{pmatrix}
3&-1\\
-1&2
\end{pmatrix}
\begin{pmatrix}
7\\
8
\end{pmatrix}
\]

Multiply the matrix by the vector:

\[
x=\frac15
\begin{pmatrix}
3(7)-1(8)\\
-1(7)+2(8)
\end{pmatrix}
\]

Simplifying:

\[
x=\frac15
\begin{pmatrix}
21-8\\
-7+16
\end{pmatrix}
=\frac15
\begin{pmatrix}
13\\
9
\end{pmatrix}
\]

Thus,

\[
\boxed{
x=\begin{pmatrix}
\frac{13}{5}\\[4pt]
\frac95
\end{pmatrix}
}
\]

The solution is

\[
\boxed{x=\frac{13}{5},\qquad y=\frac95}
\]

---

## 🔹 Method 2 — Gaussian Elimination

Gaussian elimination solves the system using elementary row operations, without calculating the inverse matrix.

### Step 1: Construct the augmented matrix

Write the coefficients and the right-hand side in one matrix:

\[
\left[
\begin{array}{cc|c}
2&1&7\\
1&3&8
\end{array}
\right]
\]

### Step 2: Eliminate the first variable from the second row

To avoid fractions, swap the rows first:

\[
R_1\leftrightarrow R_2
\]

This gives

\[
\left[
\begin{array}{cc|c}
1&3&8\\
2&1&7
\end{array}
\right]
\]

Now apply the row operation

\[
R_2\leftarrow R_2-2R_1
\]

The result is

\[
\left[
\begin{array}{cc|c}
1&3&8\\
0&-5&-9
\end{array}
\right]
\]

The second row represents

\[
-5y=-9
\]

Therefore,

\[
\boxed{y=\frac95}
\]

### Step 3: Find the remaining variable

From the first row,

\[
x+3y=8
\]

Substitute \(y=\frac95\):

\[
x+3\left(\frac95\right)=8
\]

\[
x+\frac{27}{5}=\frac{40}{5}
\]

\[
x=\frac{40}{5}-\frac{27}{5}
\]

Therefore,

\[
\boxed{x=\frac{13}{5}}
\]

The final solution is

\[
\boxed{
x=\begin{pmatrix}
\frac{13}{5}\\[4pt]
\frac95
\end{pmatrix}
}
\]

---

## ✅ Step 3 — Verify the Solution

Substitute the values into the original system.

| Equation | Verification | Result |
|:---|:---|:---:|
| \(2x+y=7\) | \(2(\frac{13}{5})+\frac95=\frac{35}{5}\) | \(7=7\) ✅ |
| \(x+3y=8\) | \(\frac{13}{5}+3(\frac95)=\frac{40}{5}\) | \(8=8\) ✅ |

Both equations are satisfied, so the solution is correct.

---

## 📊 Step 4 — Compare the Two Methods

| Comparison | Inverse Matrix | Gaussian Elimination |
|:---|:---|:---|
| Main technique | Calculate \(A^{-1}\), then multiply by \(b\) | Transform the augmented matrix |
| Essential steps | Find determinant, construct inverse, multiply by vector | Swap rows, eliminate a variable, use back-substitution |
| Main advantage | Direct and systematic for small invertible matrices | Avoids calculating the full inverse |
| Main drawback | Requires finding the inverse first | Requires careful row operations |
| Result | \((\frac{13}{5},\frac95)\) | \((\frac{13}{5},\frac95)\) |

### 🔍 Which Method Was Simpler?

For this particular example, **Gaussian elimination is slightly simpler** because it avoids calculating the entire inverse matrix. Only a few row operations and one substitution are needed.

The inverse matrix method is also straightforward for this small system, especially because the \(2\times2\) inverse formula is easy to apply.

For larger systems, Gaussian elimination is generally more practical than explicitly calculating the inverse when the goal is to solve a single system.

---

## 🏆 Final Conclusion

Both methods produce the same solution:

\[
\boxed{
x=\begin{pmatrix}
\frac{13}{5}\\[4pt]
\frac95
\end{pmatrix}
}
\]

Equivalently,

\[
\boxed{x=\frac{13}{5},\qquad y=\frac95}
\]

The results agree, confirming that both methods solve the original system correctly.

> **Key takeaway:** The inverse matrix method uses \(x=A^{-1}b\), while Gaussian elimination uses row operations. For this example, Gaussian elimination requires fewer intermediate calculations and is the simpler approach.

---

*📚 Topic: Linear Algebra · Systems of Linear Equations · Inverse Matrices · Gaussian Elimination*
