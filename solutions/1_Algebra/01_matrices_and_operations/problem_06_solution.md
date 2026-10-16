# Exercise 6. Transpose

Given:

$$
A=\begin{pmatrix}1&2&3\\4&5&6\end{pmatrix},
\qquad
B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix}
$$

## 1. Compute \(A^T\)

The transpose is obtained by switching rows and columns.

$$
\boxed{
A^T=\begin{pmatrix}1&4\\2&5\\3&6\end{pmatrix}
}
$$

## 2. Compute \(B^T\)

Switching the rows and columns of \(B\) gives

$$
\boxed{
B^T=\begin{pmatrix}1&2&-1\\0&1&3\end{pmatrix}
}
$$

## 3. Compute \(AB\)

$$
AB=
\begin{pmatrix}1&2&3\\4&5&6\end{pmatrix}
\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix}
$$

Calculating each entry:

$$
AB=\begin{pmatrix}
1+4-3&0+2+9\\
4+10-6&0+5+18
\end{pmatrix}
$$

Therefore,

$$
\boxed{AB=\begin{pmatrix}2&11\\8&23\end{pmatrix}}
$$

## 4. Verify that \((AB)^T=B^TA^T\)

First, transpose the product \(AB\):

$$
(AB)^T=\begin{pmatrix}2&8\\11&23\end{pmatrix}
$$

Now calculate \(B^TA^T\):

$$
B^TA^T=
\begin{pmatrix}1&2&-1\\0&1&3\end{pmatrix}
\begin{pmatrix}1&4\\2&5\\3&6\end{pmatrix}
$$

Multiplying the matrices gives

$$
B^TA^T=
\begin{pmatrix}
1+4-3&4+10-6\\
0+2+9&0+5+18
\end{pmatrix}
$$

Thus,

$$
B^TA^T=\begin{pmatrix}2&8\\11&23\end{pmatrix}
$$

Both results are equal:

$$
\boxed{(AB)^T=B^TA^T}
$$

## Conclusion

This example verifies the transpose property of matrix multiplication: the transpose of a product equals the product of the transposes in reverse order. In general, \((AB)^T=B^TA^T\).
