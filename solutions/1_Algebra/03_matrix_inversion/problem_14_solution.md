# Exercise 14. A Matrix That Is Its Own Inverse

Assume that a square matrix \(A\) satisfies:

$$
A^2=I
$$

By definition:

$$
A^2=AA
$$

Therefore:

$$
AA=I
$$

The matrix \(A\) multiplied by itself gives the identity matrix. Hence, \(A\) is the inverse of itself:

$$
\boxed{A^{-1}=A}
$$

## Example

Consider the matrix:

$$
A=\begin{pmatrix}1&0\\0&-1\end{pmatrix}
$$

This matrix is different from both \(I\) and \(-I\).

## Verification

Calculate \(A^2\):

$$
A^2=
\begin{pmatrix}1&0\\0&-1\end{pmatrix}
\begin{pmatrix}1&0\\0&-1\end{pmatrix}
$$

$$
A^2=
\begin{pmatrix}
1\cdot1+0\cdot0&1\cdot0+0\cdot(-1)\\
0\cdot1+(-1)\cdot0&0\cdot0+(-1)(-1)
\end{pmatrix}
$$

Therefore:

$$
A^2=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I
$$

Thus:

$$
\boxed{A^{-1}=A}
$$

The example satisfies the condition \(A^2=I\), so it is its own inverse.
