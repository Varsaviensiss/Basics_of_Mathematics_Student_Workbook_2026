# Exercise 3: Swapping Two Rows

## Problem

Given the matrix

\[
A=\begin{pmatrix}
1 & 2 & 0\\
0 & 3 & 1\\
2 & 1 & 1
\end{pmatrix}
\]

Calculate \(\det(A)\). Then construct a matrix \(B\) by swapping the first and second rows of \(A\). Predict \(\det(B)\) using a determinant property and verify the result by calculation.

## 1. Calculate the Determinant of A

Using the formula for a \(3\times3\) determinant:

\[
\begin{aligned}
\det(A)
&=1(3\cdot1-1\cdot1)\\
&\quad-2(0\cdot1-1\cdot2)\\
&\quad+0(0\cdot1-3\cdot2)\\
&=2-2(-2)\\
&=2+4\\
&=6
\end{aligned}
\]

Therefore,

\[
\boxed{\det(A)=6}
\]

## 2. Construct Matrix B

Swap the first and second rows of \(A\):

\[
R_1\leftrightarrow R_2
\]

The resulting matrix is

\[
B=\begin{pmatrix}
0 & 3 & 1\\
1 & 2 & 0\\
2 & 1 & 1
\end{pmatrix}
\]

## 3. Predict the Determinant of B

A determinant property states that swapping two rows changes the sign of the determinant.

Therefore,

\[
\det(B)=-\det(A)
\]

Since \(\det(A)=6\),

\[
\boxed{\det(B)=-6}
\]

## 4. Verify by Direct Calculation

Calculate the determinant of \(B\):

\[
\begin{aligned}
\det(B)
&=0(2\cdot1-0\cdot1)\\
&\quad-3(1\cdot1-0\cdot2)\\
&\quad+1(1\cdot1-2\cdot2)\\
&=0-3+(1-4)\\
&=-3-3\\
&=-6
\end{aligned}
\]

Thus,

\[
\boxed{\det(B)=-6}
\]

## 5. Results

| Matrix | Determinant |
|:--|--:|
| \(A\) | \(6\) |
| \(B\) | \(-6\) |

The direct calculation confirms the prediction.

## Conclusion

Swapping two rows of a matrix changes the sign of its determinant. In this example, the determinant changes from \(6\) to \(-6\), confirming the row-swapping property.


