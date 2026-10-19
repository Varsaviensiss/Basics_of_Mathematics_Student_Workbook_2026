# Exercise 4. Triangular Matrix

Given the upper triangular matrix

$$
A=
\begin{pmatrix}
2 & 4 & 1\\
0 & -3 & 5\\
0 & 0 & 7
\end{pmatrix}
$$

We need to compute \(\det(A)\) without expanding the determinant, state the general rule for triangular matrices, and explain the rule using this example.

## 1. Compute the Determinant Without Expansion

A triangular matrix has all entries either above or below its main diagonal equal to zero.

For an upper triangular matrix, the entries below the main diagonal are zero.

The determinant of a triangular matrix equals the product of its main diagonal entries.

The main diagonal entries of \(A\) are

$$
a_{11}=2,\qquad a_{22}=-3,\qquad a_{33}=7
$$

Multiply these entries:

$$
\det(A)=2\cdot(-3)\cdot7
$$

$$
\det(A)=(-6)\cdot7
$$

Therefore,

$$
\boxed{\det(A)=-42}
$$

## 2. State the General Rule

For any \(n\times n\) triangular matrix \(T\), whether upper triangular or lower triangular, the determinant is the product of its main diagonal entries:

$$
\boxed{\det(T)=\prod_{i=1}^{n}t_{ii}}
$$

Equivalently,

$$
\det(T)=t_{11}t_{22}\cdots t_{nn}
$$

## 3. Explain the Rule Using This Example

The given matrix is upper triangular because every entry below the main diagonal is zero:

$$
A=
\begin{pmatrix}
\boxed{2} & 4 & 1\\
0 & \boxed{-3} & 5\\
0 & 0 & \boxed{7}
\end{pmatrix}
$$

The diagonal entries are \(2\), \(-3\), and \(7\).

All entries below the main diagonal are zero, so the determinant simplifies to the product of the diagonal entries.

$$
\det(A)=2\cdot(-3)\cdot7
$$

$$
\boxed{\det(A)=-42}
$$

This property allows us to find the determinant directly without expanding it into multiple terms.

## Final Answer

$$
\boxed{\det(A)=-42}
$$

**General rule:** The determinant of any square triangular matrix is the product of its main diagonal entries.

$$
\boxed{\det(T)=t_{11}t_{22}\cdots t_{nn}}
$$
