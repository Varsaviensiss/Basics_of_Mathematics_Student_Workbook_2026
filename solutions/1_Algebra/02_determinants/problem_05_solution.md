# Exercise 5. Row Operations

Given:

$$
A=
\begin{pmatrix}
1 & 2 & 3\\
2 & 1 & 0\\
-1 & 4 & 2
\end{pmatrix}
$$

We need to find \(\det(A)\) by simplifying the matrix using row operations and tracking how each operation affects the determinant.

## 1. Write the Original Matrix

$$
A=
\begin{pmatrix}
1 & 2 & 3\\
2 & 1 & 0\\
-1 & 4 & 2
\end{pmatrix}
$$

The determinant is initially

$$
\det(A)
$$

## 2. Eliminate the First Entry in the Second Row

Apply the row operation

$$
R_2\leftarrow R_2-2R_1
$$

Calculate the new second row:

$$
(2,1,0)-2(1,2,3)
$$

$$
=(2,1,0)-(2,4,6)
$$

$$
=(0,-3,-6)
$$

The new matrix is

$$
A_1=
\begin{pmatrix}
1 & 2 & 3\\
0 & -3 & -6\\
-1 & 4 & 2
\end{pmatrix}
$$

**Effect on the determinant:** Adding a multiple of one row to another row does not change the determinant.

Therefore,

$$
\boxed{\det(A_1)=\det(A)}
$$

## 3. Eliminate the First Entry in the Third Row

Apply the row operation

$$
R_3\leftarrow R_3+R_1
$$

Calculate the new third row:

$$
(-1,4,2)+(1,2,3)
$$

$$
=(0,6,5)
$$

The new matrix is

$$
A_2=
\begin{pmatrix}
1 & 2 & 3\\
0 & -3 & -6\\
0 & 6 & 5
\end{pmatrix}
$$

**Effect on the determinant:** Adding one row to another row does not change the determinant.

Therefore,

$$
\boxed{\det(A_2)=\det(A_1)=\det(A)}
$$

## 4. Eliminate the Second Entry in the Third Row

We want to eliminate the \(6\) below the diagonal entry \(-3\).

Apply the row operation

$$
R_3\leftarrow R_3+2R_2
$$

Calculate the new third row:

$$
(0,6,5)+2(0,-3,-6)
$$

$$
=(0,6,5)+(0,-6,-12)
$$

$$
=(0,0,-7)
$$

The resulting matrix is upper triangular:

$$
A_3=
\begin{pmatrix}
1 & 2 & 3\\
0 & -3 & -6\\
0 & 0 & -7
\end{pmatrix}
$$

**Effect on the determinant:** Adding a multiple of one row to another row does not change the determinant.

Therefore,

$$
\boxed{\det(A_3)=\det(A_2)=\det(A)}
$$

## 5. Calculate the Determinant

The determinant of an upper triangular matrix equals the product of its main diagonal entries.

Thus,

$$
\det(A_3)=1\cdot(-3)\cdot(-7)
$$

$$
\det(A_3)=(-3)(-7)
$$

$$
\det(A_3)=21
$$

Since none of the row operations changed the determinant,

$$
\det(A)=\det(A_1)=\det(A_2)=\det(A_3)
$$

Therefore,

$$
\boxed{\det(A)=21}
$$

## 6. Summary of the Row Operations

| Row operation | Effect on determinant |
|---|---|
| \(R_2\leftarrow R_2-2R_1\) | No change |
| \(R_3\leftarrow R_3+R_1\) | No change |
| \(R_3\leftarrow R_3+2R_2\) | No change |

All three operations add a multiple of one row to another row, so the determinant remains unchanged throughout the calculation.

## Final Answer

The matrix is reduced to an upper triangular matrix:

$$
\begin{pmatrix}
1 & 2 & 3\\
0 & -3 & -6\\
0 & 0 & -7
\end{pmatrix}
$$

Its determinant is the product of the diagonal entries:

$$
\det(A)=1\cdot(-3)\cdot(-7)
$$

$$
\boxed{\det(A)=21}
$$
