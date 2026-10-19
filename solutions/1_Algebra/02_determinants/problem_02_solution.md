# Exercise 2. Determinant of a 3×3 Matrix

Given:

$$
A=
\begin{pmatrix}
1 & 2 & -1\\
0 & 3 & 4\\
2 & 1 & 5
\end{pmatrix}
$$

We need to compute \(\det(A)\) using Sarrus' rule and verify the result using a property of determinants.

## 1. Compute \(\det(A)\) Using Sarrus' Rule

For a \(3\times3\) matrix

$$
A=
\begin{pmatrix}
a & b & c\\
d & e & f\\
g & h & i
\end{pmatrix},
$$

Sarrus' rule gives

$$
\det(A)=aei+bfg+cdh-ceg-bdi-afh.
$$

For the given matrix,

$$
a=1,\quad b=2,\quad c=-1
$$

$$
d=0,\quad e=3,\quad f=4
$$

$$
g=2,\quad h=1,\quad i=5
$$

Calculate the three positive diagonal products:

$$
aei=(1)(3)(5)=15
$$

$$
bfg=(2)(4)(2)=16
$$

$$
cdh=(-1)(0)(1)=0
$$

Add them:

$$
15+16+0=31
$$

Calculate the three negative diagonal products:

$$
ceg=(-1)(3)(2)=-6
$$

$$
bdi=(2)(0)(5)=0
$$

$$
afh=(1)(4)(1)=4
$$

Add these products:

$$
-6+0+4=-2
$$

Subtract the sum of the negative diagonal products from the sum of the positive diagonal products:

$$
\det(A)=31-(-2)
$$

$$
\det(A)=31+2
$$

Therefore,

$$
\boxed{\det(A)=33}
$$

## 2. Check Using a Property of Determinants

A determinant does not change when a multiple of one row is added to another row.

Apply the row operation

$$
R_3\leftarrow R_3-2R_1
$$

The third row becomes:

$$
(2,1,5)-2(1,2,-1)
$$

$$
=(2,1,5)-(2,4,-2)
$$

$$
=(0,-3,7)
$$

The resulting matrix is

$$
A'=
\begin{pmatrix}
1 & 2 & -1\\
0 & 3 & 4\\
0 & -3 & 7
\end{pmatrix}
$$

Since adding a multiple of one row to another does not change the determinant,

$$
\det(A')=\det(A)
$$

Expand \(\det(A')\) along the first column, which contains two zeros:

$$
\det(A')=
1\begin{vmatrix}
3 & 4\\
-3 & 7
\end{vmatrix}
$$

Calculate the \(2\times2\) determinant:

$$
\det(A')=1\big((3)(7)-(4)(-3)\big)
$$

$$
\det(A')=21+12
$$

$$
\det(A')=33
$$

Thus,

$$
\boxed{\det(A')=\det(A)=33}
$$

The check confirms the result.

## Final Answer

Using Sarrus' rule:

$$
\boxed{\det(A)=33}
$$

Verification using a row operation that preserves the determinant:

$$
\boxed{\det(A')=33=\det(A)}
$$

