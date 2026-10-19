# Exercise 6. Solving a System Using the Inverse

Given:

$$
A=\begin{pmatrix}2&1\\1&3\end{pmatrix},
\qquad
b=\begin{pmatrix}5\\7\end{pmatrix}
$$

We solve \(Ax=b\) using:

$$
x=A^{-1}b
$$

## Step 1. Find the inverse

For a \(2\times2\) matrix:

$$
A^{-1}=\frac{1}{ad-bc}
\begin{pmatrix}d&-b\\-c&a\end{pmatrix}
$$

Calculate the determinant:

$$
\det(A)=2\cdot3-1\cdot1=5
$$

Therefore:

$$
A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix}
$$

## Step 2. Calculate \(x=A^{-1}b\)

$$
x=\frac15
\begin{pmatrix}3&-1\\-1&2\end{pmatrix}
\begin{pmatrix}5\\7\end{pmatrix}
$$

$$
x=\frac15
\begin{pmatrix}
3(5)-7\\
-5+2(7)
\end{pmatrix}
$$

$$
x=\frac15\begin{pmatrix}8\\9\end{pmatrix}
$$

Hence:

$$
\boxed{x=\begin{pmatrix}\frac85\\[2pt]\frac95\end{pmatrix}}
$$

## Step 3. Verify by substitution

Check the first equation:

$$
2\left(\frac85\right)+\frac95
=\frac{16}{5}+\frac95
=\frac{25}{5}=5
$$

Check the second equation:

$$
\frac85+3\left(\frac95\right)
=\frac85+\frac{27}{5}
=\frac{35}{5}=7
$$

Thus:

$$
A x=\begin{pmatrix}5\\7\end{pmatrix}=b
$$

The solution is correct.
