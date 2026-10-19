# Exercise 3. When Does the Inverse Not Exist?

Given:

$$
A=\begin{pmatrix}2&4\\1&2\end{pmatrix}
$$

We will show in two ways that \(A^{-1}\) does not exist:

1. Using the determinant.
2. Using the dependence between the rows.

## Step 1. Check the determinant

For a \(2\times2\) matrix

$$
A=\begin{pmatrix}a&b\\c&d\end{pmatrix},
$$

the determinant is

$$
\det(A)=ad-bc.
$$

For the given matrix,

$$
a=2,\quad b=4,\quad c=1,\quad d=2.
$$

Therefore,

$$
\det(A)=2\cdot2-4\cdot1
$$

$$
\det(A)=4-4
$$

$$
\boxed{\det(A)=0}
$$

A square matrix is invertible if and only if its determinant is nonzero.

Since

$$
\det(A)=0,
$$

the inverse does not exist:

$$
\boxed{A^{-1}\text{ does not exist}}
$$

## Step 2. Check the dependence between the rows

The rows of \(A\) are

$$
R_1=(2,4),\qquad R_2=(1,2).
$$

Notice that

$$
R_1=2R_2.
$$

Indeed,

$$
2(1,2)=(2,4).
$$

Therefore, the two rows are linearly dependent.

A square matrix with linearly dependent rows is singular and cannot have an inverse.

Hence,

$$
\boxed{A^{-1}\text{ does not exist}}
$$

## Conclusion

Both methods give the same result:

- The determinant is zero.
- The rows are linearly dependent.

Therefore, the matrix is singular and has no inverse.

$$
\boxed{\det(A)=0\implies A^{-1}\text{ does not exist}}
$$
