# Exercise 13. Determinant by Elimination

Given the matrix

$$
A=
\begin{pmatrix}
1 & 2 & 3\\
2 & 5 & 7\\
1 & 0 & 2
\end{pmatrix}
$$

We will compute \(\det(A)\) using row operations and record the effect of each operation on the determinant.

## Step 1: Eliminate the entry below the first pivot

Apply the row operation

$$
R_2\leftarrow R_2-2R_1
$$

**Effect on the determinant:** Adding a multiple of one row to another row does not change the determinant.

Calculate the new second row:

$$
R_2=(2,5,7)-2(1,2,3)
$$

$$
R_2=(2,5,7)-(2,4,6)
$$

$$
R_2=(0,1,1)
$$

The resulting matrix is

$$
A_1=
\begin{pmatrix}
1 & 2 & 3\\
0 & 1 & 1\\
1 & 0 & 2
\end{pmatrix}
$$

Therefore,

$$
\det(A_1)=\det(A)
$$

## Step 2: Eliminate the entry below the first pivot in the third row

Apply the row operation

$$
R_3\leftarrow R_3-R_1
$$

**Effect on the determinant:** Adding a multiple of one row to another row does not change the determinant.

Calculate the new third row:

$$
R_3=(1,0,2)-(1,2,3)
$$

$$
R_3=(0,-2,-1)
$$

The resulting matrix is

$$
A_2=
\begin{pmatrix}
1 & 2 & 3\\
0 & 1 & 1\\
0 & -2 & -1
\end{pmatrix}
$$

Therefore,

$$
\det(A_2)=\det(A_1)=\det(A)
$$

## Step 3: Eliminate the entry below the second pivot

Apply the row operation

$$
R_3\leftarrow R_3+2R_2
$$

**Effect on the determinant:** Adding a multiple of one row to another row does not change the determinant.

Calculate the new third row:

$$
R_3=(0,-2,-1)+2(0,1,1)
$$

$$
R_3=(0,-2,-1)+(0,2,2)
$$

$$
R_3=(0,0,1)
$$

The resulting upper triangular matrix is

$$
A_3=
\begin{pmatrix}
1 & 2 & 3\\
0 & 1 & 1\\
0 & 0 & 1
\end{pmatrix}
$$

Thus,

$$
\det(A_3)=\det(A)
$$

## Step 4: Calculate the determinant of the triangular matrix

**Property:** The determinant of a triangular matrix equals the product of its diagonal entries.

Therefore,

$$
\det(A_3)=(1)(1)(1)
$$

$$
\det(A_3)=1
$$

Since none of the row operations changed the determinant,

$$
\det(A)=\det(A_3)
$$

Hence,

$$
\boxed{\det(A)=1}
$$

## Summary of Row Operations

| Row operation | Effect on determinant |
|---|---|
| \(R_2\leftarrow R_2-2R_1\) | Unchanged |
| \(R_3\leftarrow R_3-R_1\) | Unchanged |
| \(R_3\leftarrow R_3+2R_2\) | Unchanged |

All three operations add a multiple of one row to another, so the determinant remains unchanged throughout the elimination.

## Final Answer

$$
\boxed{\det(A)=1}
$$
