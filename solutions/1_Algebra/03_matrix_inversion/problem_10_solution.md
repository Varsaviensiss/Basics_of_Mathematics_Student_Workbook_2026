# Exercise 10. Inverse of a Diagonal Matrix

Given:

$$
D=\begin{pmatrix}2&0&0\\0&-3&0\\0&0&5\end{pmatrix},
\qquad
E=\begin{pmatrix}2&0&0\\0&0&0\\0&0&5\end{pmatrix}
$$

## Step 1. Determine which matrix is invertible

A diagonal matrix is invertible if and only if every diagonal entry is nonzero.

For \(D\), the diagonal entries are \(2,-3,5\), all nonzero. Therefore, \(D\) is invertible.

For \(E\), one diagonal entry is zero. Therefore, \(E\) is not invertible.

Equivalently:

$$
\det(D)=2(-3)(5)=-30\neq0
$$

$$
\det(E)=2(0)(5)=0
$$

Thus:

$$
\boxed{D\text{ is invertible; }E\text{ is not invertible}}
$$

## Step 2. Find \(D^{-1}\)

Take the reciprocal of each diagonal entry:

$$
\boxed{
D^{-1}=\begin{pmatrix}
\frac12&0&0\\
0&-\frac13&0\\
0&0&\frac15
\end{pmatrix}
}
$$

## Step 3. Verify by multiplication

$$
DD^{-1}
=
\begin{pmatrix}2&0&0\\0&-3&0\\0&0&5\end{pmatrix}
\begin{pmatrix}\frac12&0&0\\0&-\frac13&0\\0&0&\frac15\end{pmatrix}
$$

$$
DD^{-1}=
\begin{pmatrix}
2\cdot\frac12&0&0\\
0&(-3)\left(-\frac13\right)&0\\
0&0&5\cdot\frac15
\end{pmatrix}
$$

$$
\boxed{DD^{-1}=I_3}
$$

The inverse is correct. Matrix \(E\) has no inverse because its determinant is zero.
