# Exercise 2. Formula for a \(2\times2\) Matrix

Given:

$$
A=\begin{pmatrix}3&2\\5&4\end{pmatrix}
$$

We use the inverse formula for a \(2\times2\) matrix.

For a matrix

$$
A=\begin{pmatrix}a&b\\c&d\end{pmatrix},
$$

the determinant is

$$
\det(A)=ad-bc.
$$

If \(\det(A)\neq0\), then

$$
A^{-1}=\frac{1}{ad-bc}
\begin{pmatrix}d&-b\\-c&a\end{pmatrix}.
$$

## Step 1. Calculate the determinant

For the given matrix,

$$
a=3,\quad b=2,\quad c=5,\quad d=4.
$$

Therefore,

$$
\det(A)=3\cdot4-2\cdot5
$$

$$
\det(A)=12-10
$$

$$
\boxed{\det(A)=2}
$$

Since \(\det(A)\neq0\), the inverse exists.

## Step 2. Apply the inverse formula

$$
A^{-1}=\frac{1}{2}
\begin{pmatrix}4&-2\\-5&3\end{pmatrix}
$$

Multiply every entry by \(\frac12\):

$$
\boxed{
A^{-1}=
\begin{pmatrix}
2&-1\\
-\frac52&\frac32
\end{pmatrix}
}
$$

## Step 3. Verify by multiplication

We check that \(AA^{-1}=I\).

$$
AA^{-1}=
\begin{pmatrix}3&2\\5&4\end{pmatrix}
\begin{pmatrix}2&-1\\-\frac52&\frac32\end{pmatrix}
$$

Multiply the rows of the first matrix by the columns of the second matrix:

$$
AA^{-1}=
\begin{pmatrix}
3(2)+2\left(-\frac52\right)&3(-1)+2\left(\frac32\right)\\
5(2)+4\left(-\frac52\right)&5(-1)+4\left(\frac32\right)
\end{pmatrix}
$$

Simplify each entry:

$$
AA^{-1}=
\begin{pmatrix}
6-5&-3+3\\
10-10&-5+6
\end{pmatrix}
$$

Therefore,

$$
AA^{-1}=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I
$$

## Conclusion

The determinant is nonzero, so the matrix is invertible. The inverse is

$$
\boxed{
A^{-1}=
\begin{pmatrix}
2&-1\\
-\frac52&\frac32
\end{pmatrix}
}
$$

The verification \(AA^{-1}=I\) confirms that the result is correct.
