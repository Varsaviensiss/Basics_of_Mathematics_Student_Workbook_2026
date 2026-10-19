# Exercise 2. Addition and Scalar Multiplication

Given:

$$
A=\begin{pmatrix}
1 & 2\\
-1 & 3
\end{pmatrix},
\qquad
B=\begin{pmatrix}
4 & -2\\
0 & 5
\end{pmatrix}
$$

## 1. Compute \(A+B\)

Matrix addition is performed by adding corresponding entries.

$$
A+B=
\begin{pmatrix}
1 & 2\\
-1 & 3
\end{pmatrix}
+
\begin{pmatrix}
4 & -2\\
0 & 5
\end{pmatrix}
$$

Add the corresponding entries:

$$
A+B=
\begin{pmatrix}
1+4 & 2+(-2)\\
-1+0 & 3+5
\end{pmatrix}
$$

Simplify:

$$
A+B=
\begin{pmatrix}
5 & 0\\
-1 & 8
\end{pmatrix}
$$

Therefore:

$$
\boxed{A+B=\begin{pmatrix}
5 & 0\\
-1 & 8
\end{pmatrix}}
$$

## 2. Compute \(A-B\)

Matrix subtraction is performed by subtracting corresponding entries.

$$
A-B=
\begin{pmatrix}
1 & 2\\
-1 & 3
\end{pmatrix}
-
\begin{pmatrix}
4 & -2\\
0 & 5
\end{pmatrix}
$$

Subtract the corresponding entries:

$$
A-B=
\begin{pmatrix}
1-4 & 2-(-2)\\
-1-0 & 3-5
\end{pmatrix}
$$

Simplify:

$$
A-B=
\begin{pmatrix}
-3 & 4\\
-1 & -2
\end{pmatrix}
$$

Therefore:

$$
\boxed{A-B=\begin{pmatrix}
-3 & 4\\
-1 & -2
\end{pmatrix}}
$$

## 3. Compute \(3A-2B\)

First, multiply every entry of \(A\) by \(3\):

$$
3A=3\begin{pmatrix}
1 & 2\\
-1 & 3
\end{pmatrix}
$$

$$
3A=\begin{pmatrix}
3(1) & 3(2)\\
3(-1) & 3(3)
\end{pmatrix}
$$

$$
3A=\begin{pmatrix}
3 & 6\\
-3 & 9
\end{pmatrix}
$$

Next, multiply every entry of \(B\) by \(2\):

$$
2B=2\begin{pmatrix}
4 & -2\\
0 & 5
\end{pmatrix}
$$

$$
2B=\begin{pmatrix}
2(4) & 2(-2)\\
2(0) & 2(5)
\end{pmatrix}
$$

$$
2B=\begin{pmatrix}
8 & -4\\
0 & 10
\end{pmatrix}
$$

Now subtract the matrices:

$$
3A-2B=
\begin{pmatrix}
3 & 6\\
-3 & 9
\end{pmatrix}
-
\begin{pmatrix}
8 & -4\\
0 & 10
\end{pmatrix}
$$

Subtract the corresponding entries:

$$
3A-2B=
\begin{pmatrix}
3-8 & 6-(-4)\\
-3-0 & 9-10
\end{pmatrix}
$$

Simplify:

$$
3A-2B=
\begin{pmatrix}
-5 & 10\\
-3 & -1
\end{pmatrix}
$$

Therefore:

$$
\boxed{3A-2B=\begin{pmatrix}
-5 & 10\\
-3 & -1
\end{pmatrix}}
$$

## 4. Why Must Matrices Have the Same Size for Addition?

Matrix addition is defined by adding entries in the same positions.

For example, if

$$
A=(a_{ij}),\qquad B=(b_{ij}),
$$

then their sum is defined by

$$
(A+B)_{ij}=a_{ij}+b_{ij}
$$

Each entry of \(A\) must have a corresponding entry in the same position in \(B\).

Therefore, the matrices must have the same number of rows and the same number of columns.

In this exercise:

$$
\operatorname{size}(A)=2\times2
$$

$$
\operatorname{size}(B)=2\times2
$$

Since both matrices have the same size, addition and subtraction are possible.

If the matrices had different sizes, some entries would have no corresponding entries to add or subtract.

Thus:

$$
\boxed{\text{Matrix addition and subtraction require equal dimensions.}}
$$

## Final Answers

$$
\boxed{A+B=\begin{pmatrix}
5 & 0\\
-1 & 8
\end{pmatrix}}
$$

$$
\boxed{A-B=\begin{pmatrix}
-3 & 4\\
-1 & -2
\end{pmatrix}}
$$

$$
\boxed{3A-2B=\begin{pmatrix}
-5 & 10\\
-3 & -1
\end{pmatrix}}
$$

Matrix addition and subtraction are possible only when both matrices have the same number of rows and columns, because corresponding entries must be paired.



