# Exercise 10. Columns of a Matrix Product

Given:

$$
A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix},
\qquad
B=\begin{pmatrix}1&2\\-1&0\\3&1\end{pmatrix}
$$

The columns of \(B\) are

$$
b_1=\begin{pmatrix}1\\-1\\3\end{pmatrix},
\qquad
b_2=\begin{pmatrix}2\\0\\1\end{pmatrix}
$$

## 1. Compute \(Ab_1\) and \(Ab_2\)

First, calculate \(Ab_1\):

$$
Ab_1=
\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix}
\begin{pmatrix}1\\-1\\3\end{pmatrix}
$$

$$
Ab_1=
\begin{pmatrix}
1(1)+2(-1)+0(3)\\
0(1)+1(-1)+1(3)
\end{pmatrix}
=\boxed{\begin{pmatrix}-1\\2\end{pmatrix}}
$$

Next, calculate \(Ab_2\):

$$
Ab_2=
\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix}
\begin{pmatrix}2\\0\\1\end{pmatrix}
$$

$$
Ab_2=
\begin{pmatrix}
1(2)+2(0)+0(1)\\
0(2)+1(0)+1(1)
\end{pmatrix}
=\boxed{\begin{pmatrix}2\\1\end{pmatrix}}
$$

## 2. Compute the Matrix \(AB\)

Multiply matrix \(A\) by matrix \(B\):

$$
AB=
\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix}
\begin{pmatrix}1&2\\-1&0\\3&1\end{pmatrix}
$$

Calculating each entry:

$$
AB=
\begin{pmatrix}
1-2+0&2+0+0\\
0-1+3&0+0+1
\end{pmatrix}
$$

Therefore,

$$
\boxed{AB=\begin{pmatrix}-1&2\\2&1\end{pmatrix}}
$$

## 3. Compare the Results

We obtained

$$
Ab_1=\begin{pmatrix}-1\\2\end{pmatrix},
\qquad
Ab_2=\begin{pmatrix}2\\1\end{pmatrix}
$$

These vectors are exactly the first and second columns of \(AB\):

$$
AB=\begin{pmatrix}
|&|\\
Ab_1&Ab_2\\
|&|
\end{pmatrix}
=\begin{pmatrix}-1&2\\2&1\end{pmatrix}
$$

This happens because matrix multiplication applies \(A\) to each column of \(B\) separately. The first column of \(AB\) is \(Ab_1\), and the second column is \(Ab_2\).

## Conclusion

The columns of the matrix product \(AB\) are obtained by multiplying \(A\) by each column of \(B\). This shows how matrix multiplication extends the idea of multiplying a matrix by a vector.
