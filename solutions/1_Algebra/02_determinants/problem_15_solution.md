# Exercise 15: Combining Determinant Properties

## Given

Let \(A\) and \(B\) be invertible \(2\times2\) matrices such that

\[
\det(A)=-2,\qquad \det(B)=3.
\]

We need to calculate

\[
\det(B^{-1}A^TB)
\]

without finding the entries of the matrices.

## Solution

**Step 1: Apply the product property.**

For square matrices of the same size,

\[
\det(XYZ)=\det(X)\det(Y)\det(Z).
\]

Therefore,

\[
\det(B^{-1}A^TB)
=\det(B^{-1})\det(A^T)\det(B).
\]

**Step 2: Apply the inverse and transpose properties.**

The determinant of an inverse matrix is the reciprocal of the original determinant:

\[
\det(B^{-1})=\frac{1}{\det(B)}=\frac13.
\]

The determinant of a transpose equals the determinant of the original matrix:

\[
\det(A^T)=\det(A)=-2.
\]

Also,

\[
\det(B)=3.
\]

**Step 3: Substitute and simplify.**

Combining these results gives

\[
\begin{aligned}
\det(B^{-1}A^TB)
&=\frac13\cdot(-2)\cdot3\\
&=-2.
\end{aligned}
\]

The factors involving \(B\) cancel because

\[
\det(B^{-1})\det(B)
=\frac{1}{\det(B)}\det(B)=1.
\]

This cancellation is valid because \(B\) is invertible, so \(\det(B)\neq0\).

## Final Answer

\[
\boxed{\det(B^{-1}A^TB)=-2}
\]

**Properties used, in order:**

1. Multiplicativity: \(\det(XY)=\det(X)\det(Y)\).
2. Inverse property: \(\det(B^{-1})=1/\det(B)\).
3. Transpose property: \(\det(A^T)=\det(A)\).

Thus, the determinant depends only on \(\det(A)\), while the determinant factors involving \(B\) cancel each other.
