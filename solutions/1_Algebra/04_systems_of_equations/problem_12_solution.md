# Exercise 12. Finding Inverses Without Starting from Scratch

Given:

$$
A^{-1}=\begin{pmatrix}2&-1\\-3&2\end{pmatrix}
$$

We will compute \((3A)^{-1}\), \((A^T)^{-1}\), and \((A^2)^{-1}\) without finding \(A\).

## 1. Compute \((3A)^{-1}\)

For any nonzero scalar \(k\):

$$
(kA)^{-1}=\frac1kA^{-1}
$$

Therefore:

$$
(3A)^{-1}=\frac13A^{-1}
$$

Substitute the given inverse:

$$
(3A)^{-1}
=\frac13\begin{pmatrix}2&-1\\-3&2\end{pmatrix}
$$

Hence:

$$
\boxed{
(3A)^{-1}=
\begin{pmatrix}
\frac23&-\frac13\\
-1&\frac23
\end{pmatrix}
}
$$

## 2. Compute \((A^T)^{-1}\)

The transpose property is:

$$
(A^T)^{-1}=(A^{-1})^T
$$

Therefore:

$$
(A^T)^{-1}
=
\begin{pmatrix}2&-1\\-3&2\end{pmatrix}^T
$$

Thus:

$$
\boxed{
(A^T)^{-1}=
\begin{pmatrix}2&-3\\-1&2\end{pmatrix}
}
$$

## 3. Compute \((A^2)^{-1}\)

The inverse of a product satisfies:

$$
(AB)^{-1}=B^{-1}A^{-1}
$$

Taking \(B=A\):

$$
(A^2)^{-1}=(A^{-1})^2
$$

Therefore:

$$
(A^2)^{-1}
=
\begin{pmatrix}2&-1\\-3&2\end{pmatrix}
\begin{pmatrix}2&-1\\-3&2\end{pmatrix}
$$

Multiply:

$$
(A^2)^{-1}
=
\begin{pmatrix}
4+3&-2-2\\
-6-6&3+4
\end{pmatrix}
$$

Hence:

$$
\boxed{
(A^2)^{-1}=
\begin{pmatrix}7&-4\\-12&7\end{pmatrix}
}
$$

All three results follow directly from the standard properties of inverse matrices.
