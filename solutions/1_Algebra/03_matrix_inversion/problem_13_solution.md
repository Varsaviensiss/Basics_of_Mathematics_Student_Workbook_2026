# Exercise 13. Undoing a Composite Transformation

Given:

$$
S=\begin{pmatrix}2&0\\0&1\end{pmatrix},
\qquad
H=\begin{pmatrix}1&1\\0&1\end{pmatrix}
$$

The composite transformation is:

$$
T=HS
$$

## Method 1. Compute \(T\), then find its inverse

First:

$$
T=HS
=
\begin{pmatrix}1&1\\0&1\end{pmatrix}
\begin{pmatrix}2&0\\0&1\end{pmatrix}
$$

Therefore:

$$
T=\begin{pmatrix}2&1\\0&1\end{pmatrix}
$$

Its determinant is:

$$
\det(T)=2\cdot1-1\cdot0=2
$$

Using the \(2\times2\) inverse formula:

$$
T^{-1}
=\frac12\begin{pmatrix}1&-1\\0&2\end{pmatrix}
$$

Hence:

$$
\boxed{
T^{-1}=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}
}
$$

## Method 2. Use the inverse-of-a-product property

The rule is:

$$
(HS)^{-1}=S^{-1}H^{-1}
$$

First calculate:

$$
S^{-1}=\begin{pmatrix}\frac12&0\\0&1\end{pmatrix}
$$

and

$$
H^{-1}=\begin{pmatrix}1&-1\\0&1\end{pmatrix}
$$

Multiply in reverse order:

$$
S^{-1}H^{-1}
=
\begin{pmatrix}\frac12&0\\0&1\end{pmatrix}
\begin{pmatrix}1&-1\\0&1\end{pmatrix}
$$

Thus:

$$
\boxed{
S^{-1}H^{-1}=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}
}
$$

Both methods give the same answer.

## Step 3. Check the incorrect order

Calculate:

$$
H^{-1}S^{-1}
=
\begin{pmatrix}1&-1\\0&1\end{pmatrix}
\begin{pmatrix}\frac12&0\\0&1\end{pmatrix}
$$

$$
\boxed{
H^{-1}S^{-1}=
\begin{pmatrix}\frac12&-1\\0&1\end{pmatrix}
}
$$

This differs from the correct inverse:

$$
H^{-1}S^{-1}\neq T^{-1}
$$

## Conclusion

Since \(T=HS\), the transformation \(S\) is applied first and \(H\) second. To undo the composition, we must undo \(H\) first and then \(S\).

Therefore:

$$
\boxed{(HS)^{-1}=S^{-1}H^{-1}}
$$

The order of the factors is reversed when taking the inverse of a product.
