# Exercise 11. Shortening the Calculation with Row Operations

Given the matrix

$$
A=
\begin{pmatrix}
1 & 2 & 3\\
1 & 3 & 4\\
1 & 4 & 6
\end{pmatrix}
$$

We will use row operations to create as many zeros as possible and simplify the determinant calculation.

## Step 1: Create zeros in the first column

Apply the row operation

$$
R_2\leftarrow R_2-R_1
$$

**Effect on the determinant:** Adding a multiple of one row to another row does not change the determinant.

Calculate the new second row:

$$
R_2=(1,3,4)-(1,2,3)
$$

$$
R_2=(0,1,1)
$$

The matrix becomes

$$
A_1=
\begin{pmatrix}
1 & 2 & 3\\
0 & 1 & 1\\
1 & 4 & 6
\end{pmatrix}
$$

Next, apply

$$
R_3\leftarrow R_3-R_1
$$

**Effect on the determinant:** This operation also does not change the determinant.

Calculate the new third row:

$$
R_3=(1,4,6)-(1,2,3)
$$

$$
R_3=(0,2,3)
$$

The resulting matrix is

$$
A_2=
\begin{pmatrix}
1 & 2 & 3\\
0 & 1 & 1\\
0 & 2 & 3
\end{pmatrix}
$$

Therefore,

$$
\det(A)=\det(A_2)
$$

## Step 2: Create another zero

Apply the row operation

$$
R_3\leftarrow R_3-2R_2
$$

**Effect on the determinant:** This operation does not change the determinant.

Calculate the new third row:

$$
R_3=(0,2,3)-2(0,1,1)
$$

$$
R_3=(0,2,3)-(0,2,2)
$$

$$
R_3=(0,0,1)
$$

The matrix is now upper triangular:

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
\det(A)=\det(A_3)
$$

## Step 3: Calculate the determinant

**Property:** The determinant of a triangular matrix equals the product of its diagonal entries.

Therefore,

$$
\det(A_3)=(1)(1)(1)
$$

$$
\det(A_3)=1
$$

Since all the row operations preserved the determinant,

$$
\boxed{\det(A)=1}
$$

## Summary of Row Operations

| Row operation | Effect on determinant |
|---|---|
| \(R_2\leftarrow R_2-R_1\) | Unchanged |
| \(R_3\leftarrow R_3-R_1\) | Unchanged |
| \(R_3\leftarrow R_3-2R_2\) | Unchanged |

Each operation adds a multiple of one row to another row, so none changes the determinant.

## Final Answer

$$
\boxed{\det(A)=1}
$$
