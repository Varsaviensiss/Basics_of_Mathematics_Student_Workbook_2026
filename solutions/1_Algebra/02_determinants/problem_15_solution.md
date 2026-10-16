# Exercise 15 — Combining Determinant Properties

## Problem

Let \(A\) and \(B\) be invertible \(2\times2\) matrices satisfying

\[
\det(A)=-2,\qquad \det(B)=3.
\]

Without calculating the entries of the matrices, determine

\[
\boxed{\det(B^{-1}A^TB)}
\]

using determinant properties. Explain why the factors involving \(B\) cancel.

---

## Step 1 — Apply the Product Property

For square matrices of the same size, the determinant of a product equals the product of their determinants:

\[
\det(XY)=\det(X)\det(Y).
\]

Applying this property to the given expression, we obtain

\[
\det(B^{-1}A^TB)
=\det(B^{-1})\det(A^T)\det(B).
\]

## Step 2 — Use the Inverse and Transpose Properties

Two important determinant properties are:

**Inverse property**

\[
\det(B^{-1})=\frac{1}{\det(B)}
\]

Since \(\det(B)=3\),

\[
\det(B^{-1})=\frac13.
\]

**Transpose property**

\[
\det(A^T)=\det(A)
\]

Since \(\det(A)=-2\),

\[
\det(A^T)=-2.
\]

Substituting these values gives

\[
\det(B^{-1}A^TB)
=\frac13\cdot(-2)\cdot3.
\]

## Step 3 — Simplify and Explain the Cancellation

The factors involving \(B\) cancel because

\[
\det(B^{-1})\det(B)
=\frac{1}{\det(B)}\det(B)=1.
\]

This is valid because \(B\) is invertible, so its determinant is nonzero.

Therefore, the expression simplifies to

\[
\begin{aligned}
\det(B^{-1}A^TB)
&=\frac13\cdot(-2)\cdot3\\[6pt]
&=\frac{3}{3}\cdot(-2)\\[6pt]
&=-2.
\end{aligned}
\]

---

## Final Answer

\[
\boxed{\det(B^{-1}A^TB)=-2}
\]

### Properties Used

1. **Product property:** \(\det(XY)=\det(X)\det(Y)\).
2. **Inverse property:** \(\det(B^{-1})=1/\det(B)\).
3. **Transpose property:** \(\det(A^T)=\det(A)\).

**Conclusion:** The determinant factors involving \(B\) multiply to \(1\), leaving only \(\det(A^T)=\det(A)=-2\). Thus, the result is independent of the particular entries of \(B\), provided that \(B\) is invertible.
