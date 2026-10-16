# Exercise 5. Matrix Times Vector

Given:

$$
A=\begin{pmatrix}2&-1\\1&3\end{pmatrix},
\qquad
x=\begin{pmatrix}4\\2\end{pmatrix}
$$

## 1. Compute Ax

We multiply each row of matrix \(A\) by the vector \(x\).

$$
Ax=
\begin{pmatrix}2&-1\\1&3\end{pmatrix}
\begin{pmatrix}4\\2\end{pmatrix}
$$

Calculating each entry:

$$
2(4)+(-1)(2)=8-2=6
$$

$$
1(4)+3(2)=4+6=10
$$

Therefore,

$$
\boxed{Ax=\begin{pmatrix}6\\10\end{pmatrix}}
$$

## 2. Express Ax as a Linear Combination of the Columns of A

The columns of matrix \(A\) are

$$
a_1=\begin{pmatrix}2\\1\end{pmatrix},
\qquad
a_2=\begin{pmatrix}-1\\3\end{pmatrix}
$$

The vector \(x\) contains the coefficients \(4\) and \(2\). Therefore,

$$
Ax=4a_1+2a_2
$$

Substituting the column vectors:

$$
Ax=4\begin{pmatrix}2\\1\end{pmatrix}
+2\begin{pmatrix}-1\\3\end{pmatrix}
$$

Multiplying and adding:

$$
Ax=\begin{pmatrix}8\\4\end{pmatrix}
+\begin{pmatrix}-2\\6\end{pmatrix}
=\begin{pmatrix}6\\10\end{pmatrix}
$$

## 3. Conclusion

The result is

$$
\boxed{Ax=\begin{pmatrix}6\\10\end{pmatrix}}
$$

This example shows that multiplying a matrix by a vector is equivalent to taking a linear combination of the columns of the matrix. The entries of the vector provide the coefficients for the linear combination.
