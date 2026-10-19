# Exercise 10. Detecting Dependence

Given the matrix

$$
A=
\begin{pmatrix}
1 & 2 & 3\\
2 & 4 & 6\\
0 & 1 & 5
\end{pmatrix}
$$

We need to explain why \(\det(A)=0\) without carrying out a full determinant calculation.

## 1. Identify the Dependence Between the Rows

The rows of \(A\) are

$$
R_1=(1,2,3)
$$

$$
R_2=(2,4,6)
$$

$$
R_3=(0,1,5)
$$

Notice that the second row is twice the first row:

$$
R_2=2R_1
$$

Indeed,

$$
2(1,2,3)=(2,4,6)
$$

Therefore, the rows of \(A\) are linearly dependent.

## 2. Connect Row Dependence to the Determinant

**Property:** If the rows of a square matrix are linearly dependent, its determinant is zero.

Since \(R_2=2R_1\), two rows are proportional. Therefore,

$$
\boxed{\det(A)=0}
$$

No full determinant calculation is necessary.

## 3. Explain Why the Matrix Is Not Invertible

A square matrix is invertible if and only if its determinant is nonzero:

$$
A\text{ is invertible}
\iff
\det(A)\neq 0
$$

However, we have established that

$$
\det(A)=0
$$

Therefore,

$$
\boxed{A\text{ is not invertible}}
$$

The linear dependence between the rows means that the matrix is singular and has no inverse.

## Final Answer

The second row is twice the first row:

$$
\boxed{R_2=2R_1}
$$

Thus, the rows are linearly dependent, which implies

$$
\boxed{\det(A)=0}
$$

Consequently, \(A\) is a singular matrix and is not invertible.
