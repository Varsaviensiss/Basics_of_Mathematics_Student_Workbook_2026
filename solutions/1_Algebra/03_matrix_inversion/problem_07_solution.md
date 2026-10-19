# Exercise 7. Inverse of a Product

Given:

$$
A=\begin{pmatrix}1&1\\0&1\end{pmatrix},
\qquad
B=\begin{pmatrix}2&0\\0&3\end{pmatrix}
$$

We compare \((AB)^{-1}\) with \(B^{-1}A^{-1}\).

## Step 1. Compute \(AB\)

$$
AB=
\begin{pmatrix}1&1\\0&1\end{pmatrix}
\begin{pmatrix}2&0\\0&3\end{pmatrix}
$$

$$
AB=\begin{pmatrix}2&3\\0&3\end{pmatrix}
$$

## Step 2. Find \((AB)^{-1}\)

For a \(2\times2\) matrix:

$$
\begin{pmatrix}a&b\\c&d\end{pmatrix}^{-1}
=
\frac1{ad-bc}
\begin{pmatrix}d&-b\\-c&a\end{pmatrix}
$$

The determinant is:

$$
\det(AB)=2\cdot3-3\cdot0=6
$$

Therefore:

$$
(AB)^{-1}
=\frac16\begin{pmatrix}3&-3\\0&2\end{pmatrix}
$$

$$
\boxed{
(AB)^{-1}=
\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}
}
$$

## Step 3. Compute \(B^{-1}A^{-1}\)

First:

$$
A^{-1}=\begin{pmatrix}1&-1\\0&1\end{pmatrix}
$$

and

$$
B^{-1}=\begin{pmatrix}\frac12&0\\0&\frac13\end{pmatrix}
$$

Multiply in the stated order:

$$
B^{-1}A^{-1}
=
\begin{pmatrix}\frac12&0\\0&\frac13\end{pmatrix}
\begin{pmatrix}1&-1\\0&1\end{pmatrix}
$$

$$
\boxed{
B^{-1}A^{-1}
=\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}
}
$$

Thus:

$$
\boxed{(AB)^{-1}=B^{-1}A^{-1}}
$$

## Conclusion

The inverse of a product reverses the order of the factors:

$$
\boxed{(AB)^{-1}=B^{-1}A^{-1}}
$$

The factor \(B\) is undone first, followed by \(A\). This is why the order is reversed.
