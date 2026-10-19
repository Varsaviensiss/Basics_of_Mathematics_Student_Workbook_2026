# Exercise 8. Inverse of a Transformation

Given the scaling matrix:

$$
S=\begin{pmatrix}2&0\\0&\frac12\end{pmatrix}
$$

The transformation multiplies the \(x\)-coordinate by \(2\) and the \(y\)-coordinate by \(\frac12\).

## Step 1. Find \(S^{-1}\)

For a diagonal matrix with nonzero diagonal entries, the inverse is obtained by taking the reciprocal of each diagonal entry.

Therefore:

$$
\boxed{
S^{-1}=\begin{pmatrix}\frac12&0\\0&2\end{pmatrix}
}
$$

## Step 2. Check the inverse

$$
SS^{-1}
=
\begin{pmatrix}2&0\\0&\frac12\end{pmatrix}
\begin{pmatrix}\frac12&0\\0&2\end{pmatrix}
$$

$$
SS^{-1}
=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I
$$

Similarly:

$$
S^{-1}S=I
$$

## Step 3. Geometric interpretation

The original transformation doubles the horizontal coordinate and halves the vertical coordinate.

The inverse transformation halves the horizontal coordinate and doubles the vertical coordinate. It undoes the original scaling.

## Step 4. Check a vector

Choose:

$$
v=\begin{pmatrix}2\\4\end{pmatrix}
$$

Apply \(S\):

$$
Sv=
\begin{pmatrix}2&0\\0&\frac12\end{pmatrix}
\begin{pmatrix}2\\4\end{pmatrix}
=
\begin{pmatrix}4\\2\end{pmatrix}
$$

Now apply \(S^{-1}\):

$$
S^{-1}(Sv)=
\begin{pmatrix}\frac12&0\\0&2\end{pmatrix}
\begin{pmatrix}4\\2\end{pmatrix}
$$

$$
S^{-1}(Sv)=\begin{pmatrix}2\\4\end{pmatrix}=v
$$

The original vector is recovered, confirming that \(S^{-1}\) undoes \(S\).
