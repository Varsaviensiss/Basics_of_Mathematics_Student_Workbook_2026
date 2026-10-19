# Exercise 12. A Parameter Revealed by a Row Operation

Given the matrix

$$
A(t)=
\begin{pmatrix}
1 & 2 & 3\\
2 & 4 & t\\
0 & 1 & 1
\end{pmatrix}
$$

We need to find the values of \(t\) for which the matrix is not invertible.

## Step 1: Perform the required row operation

Apply

$$
R_2\leftarrow R_2-2R_1
$$

The new second row is

$$
R_2=(2,4,t)-2(1,2,3)
$$

$$
R_2=(2,4,t)-(2,4,6)
$$

$$
R_2=(0,0,t-6)
$$

The resulting matrix is

$$
A_1(t)=
\begin{pmatrix}
1 & 2 & 3\\
0 & 0 & t-6\\
0 & 1 & 1
\end{pmatrix}
$$

**Effect on the determinant:** Adding a multiple of one row to another does not change the determinant. Therefore,

$$
\det(A_1(t))=\det(A(t))
$$

## Step 2: Use the resulting structure to compute the determinant

Expanding along the second row of \(A_1(t)\), which contains two zeros, gives

$$
\det(A_1(t))
=(t-6)(-1)^{2+3}
\begin{vmatrix}
1 & 2\\
0 & 1
\end{vmatrix}
$$

Since

$$
(-1)^{2+3}=-1
$$

and

$$
\begin{vmatrix}
1 & 2\\
0 & 1
\end{vmatrix}
=(1)(1)-(2)(0)=1
$$

we obtain

$$
\det(A_1(t))=-(t-6)(1)
$$

$$
\det(A_1(t))=6-t
$$

Thus,

$$
\boxed{\det(A(t))=6-t}
$$

## Step 3: Find when the matrix is not invertible

A square matrix is not invertible if and only if its determinant is zero.

Therefore,

$$
\det(A(t))=0
$$

$$
6-t=0
$$

$$
\boxed{t=6}
$$

## Step 4: Explain what happens to the rows when \(t=6\)

Substitute \(t=6\) into the original matrix:

$$
A(6)=
\begin{pmatrix}
1 & 2 & 3\\
2 & 4 & 6\\
0 & 1 & 1
\end{pmatrix}
$$

Notice that the second row is twice the first row:

$$
R_2=(2,4,6)=2(1,2,3)=2R_1
$$

Therefore, the first and second rows are linearly dependent.

Equivalently, after the row operation,

$$
R_2\leftarrow R_2-2R_1
$$

the second row becomes a zero row when \(t=6\):

$$
R_2=(0,0,6-6)=(0,0,0)
$$

A zero row indicates that the rows are linearly dependent, so the determinant is zero and the matrix is not invertible.

## Final Answer

The matrix is not invertible precisely when

$$
\boxed{t=6}
$$

For this value, the second row is twice the first row, and the required row operation produces a zero row. Hence, the rows are linearly dependent and

$$
\boxed{\det(A(6))=0}
$$
