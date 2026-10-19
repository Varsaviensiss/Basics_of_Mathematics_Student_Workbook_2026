# Exercise 9. Matrix Equation

Given:

$$
A=\begin{pmatrix}1&2\\0&1\end{pmatrix},
\qquad
B=\begin{pmatrix}3&1\\2&4\end{pmatrix}
$$

We need to solve:

$$
AX=B
$$

## Step 1. Determine which side to multiply

Since \(A\) multiplies \(X\) on the left, multiply both sides by \(A^{-1}\) on the left:

$$
A^{-1}(AX)=A^{-1}B
$$

Using associativity:

$$
(A^{-1}A)X=A^{-1}B
$$

Since \(A^{-1}A=I\):

$$
IX=A^{-1}B
$$

Therefore:

$$
\boxed{X=A^{-1}B}
$$

## Step 2. Find \(A^{-1}\)

$$
A^{-1}=\begin{pmatrix}1&-2\\0&1\end{pmatrix}
$$

## Step 3. Calculate \(X\)

$$
X=
\begin{pmatrix}1&-2\\0&1\end{pmatrix}
\begin{pmatrix}3&1\\2&4\end{pmatrix}
$$

$$
X=
\begin{pmatrix}
3-4&1-8\\
2&4
\end{pmatrix}
$$

Hence:

$$
\boxed{X=\begin{pmatrix}-1&-7\\2&4\end{pmatrix}}
$$

## Step 4. Verify by computing \(AX\)

$$
AX=
\begin{pmatrix}1&2\\0&1\end{pmatrix}
\begin{pmatrix}-1&-7\\2&4\end{pmatrix}
$$

$$
AX=
\begin{pmatrix}
-1+4&-7+8\\
2&4
\end{pmatrix}
$$

$$
AX=\begin{pmatrix}3&1\\2&4\end{pmatrix}=B
$$

The solution is correct.
