# Exercise 4. Matrix Multiplication and Noncommutativity

Given the matrices

$$
A=\begin{pmatrix}1&2\\0&1\end{pmatrix},
\qquad
B=\begin{pmatrix}2&0\\3&1\end{pmatrix}
$$

## 1. Calculate AB

To calculate \(AB\), we multiply each row of matrix \(A\) by each column of matrix \(B\).

$$
AB=
\begin{pmatrix}1&2\\0&1\end{pmatrix}
\begin{pmatrix}2&0\\3&1\end{pmatrix}
$$

Calculating each entry:

- First row, first column: \(1(2)+2(3)=2+6=8\)
- First row, second column: \(1(0)+2(1)=0+2=2\)
- Second row, first column: \(0(2)+1(3)=0+3=3\)
- Second row, second column: \(0(0)+1(1)=0+1=1\)

Therefore,

$$
\boxed{AB=\begin{pmatrix}8&2\\3&1\end{pmatrix}}
$$

## 2. Calculate BA

Now we reverse the order and multiply matrix \(B\) by matrix \(A\).

$$
BA=
\begin{pmatrix}2&0\\3&1\end{pmatrix}
\begin{pmatrix}1&2\\0&1\end{pmatrix}
$$

Calculating each entry:

- First row, first column: \(2(1)+0(0)=2\)
- First row, second column: \(2(2)+0(1)=4\)
- Second row, first column: \(3(1)+1(0)=3\)
- Second row, second column: \(3(2)+1(1)=6+1=7\)

Therefore,

$$
\boxed{BA=\begin{pmatrix}2&4\\3&7\end{pmatrix}}
$$

## 3. Is AB = BA?

No, \(AB\ne BA\), because the corresponding entries of the two matrices are different.

$$
AB=\begin{pmatrix}8&2\\3&1\end{pmatrix}
$$

$$
BA=\begin{pmatrix}2&4\\3&7\end{pmatrix}
$$

For example, the top-left entries are different: \(8\ne2\). Therefore, the two matrix products are not equal.

## 4. Explanation of Noncommutativity

Matrix multiplication is called **noncommutative** because changing the order of the matrices can change the result. In general, \(AB\ne BA\).

In this example, multiplying \(A\) by \(B\) gives a different result from multiplying \(B\) by \(A\). This is an important difference between matrix multiplication and ordinary multiplication of numbers. For ordinary numbers, changing the order does not change the product, but for matrices, the order usually matters.

Therefore, this example demonstrates that matrix multiplication is not commutative.
