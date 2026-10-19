# Exercise 11. Parameter and Invertibility

Given:

$$
A(t)=\begin{pmatrix}1&t\\t&1\end{pmatrix}
$$

## Step 1. Find the determinant

$$
\det(A(t))=1\cdot1-t\cdot t
$$

$$
\boxed{\det(A(t))=1-t^2}
$$

A matrix is invertible if and only if its determinant is nonzero.

Therefore:

$$
1-t^2\neq0
$$

$$
t^2\neq1
$$

$$
\boxed{t\neq1,\qquad t\neq-1}
$$

## Step 2. Find the inverse

For a \(2\times2\) matrix:

$$
\begin{pmatrix}a&b\\c&d\end{pmatrix}^{-1}
=
\frac1{ad-bc}
\begin{pmatrix}d&-b\\-c&a\end{pmatrix}
$$

Applying this formula:

$$
A(t)^{-1}
=
\frac1{1-t^2}
\begin{pmatrix}1&-t\\-t&1\end{pmatrix}
$$

Thus, for \(t\neq\pm1\):

$$
\boxed{
A(t)^{-1}
=
\frac1{1-t^2}
\begin{pmatrix}1&-t\\-t&1\end{pmatrix}
}
$$

## Step 3. Explain the excluded values

When \(t=1\):

$$
A(1)=\begin{pmatrix}1&1\\1&1\end{pmatrix}
$$

The rows are identical, so the matrix is singular.

When \(t=-1\):

$$
A(-1)=\begin{pmatrix}1&-1\\-1&1\end{pmatrix}
$$

The second row is the negative of the first row, so the rows are linearly dependent.

In both cases, the determinant is zero:

$$
1-(\pm1)^2=0
$$

The inverse formula has a zero denominator at these values, so the inverse does not exist.
