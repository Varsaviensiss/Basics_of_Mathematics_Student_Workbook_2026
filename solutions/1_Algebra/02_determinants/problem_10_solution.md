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

## 1. Identify the dependence between the rows

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

Therefore, two rows are linearly dependent.

## 2. Connect
