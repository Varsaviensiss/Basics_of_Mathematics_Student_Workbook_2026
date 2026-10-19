# Exercise 15. Combining Determinant Properties

Given invertible \(2\times2\) matrices \(A\) and \(B\), where

$$
\det(A)=-2,\qquad \det(B)=3
$$

We need to compute

$$
\det(B^{-1}A^TB)
$$

without finding the entries of the matrices.

## Step 1: Apply the determinant of a product property

**Property 1:** The determinant of a product is the product of the determinants.

$$
\det(XYZ)=\det(X)\det(Y)\det(Z)
$$

Therefore,

$$
\det(B^{-1}A^TB)
=
\det(B^{-1})\det(A^T)\det(B)
$$

## Step 2: Use the determinant of an inverse

**Property 2:** For an invertible matrix \(B\),

$$
\det(B^{-1})=\frac{1}{\det(B)}
$$

Since \(\det(B)=3\),

$$
\det(B^{-1})=\frac{1}{3}
$$

Substitute this value:

$$
\det(B^{-1}A^TB)
=
\frac{1}{3}\det(A^T)\det(B)
$$

## Step 3: Use the determinant of a transpose

**Property 3:** The determinant of a matrix equals the determinant of its transpose.

$$
\det(A^T)=\det(A)
$$

Since \(\det(A)=-2\),

$$
\det(A^T)=-2
$$

Substitute the known values:

$$
\det(B^{-1}A^TB)
=
\frac{1}{3}(-2)(3)
$$

## Step 4: Simplify

$$
\det(B^{-1}A^TB)
=
\left(\frac{1}{3}\cdot3\right)(-2)
$$

$$
=1\cdot(-2)
$$

Therefore,

$$
\boxed{\det(B^{-1}A^TB)=-2}
$$

## Why Do the Factors Involving \(B\) Cancel?

The determinant contributions from \(B^{-1}\) and \(B\) are

$$
\det(B^{-1})\det(B)
=
\frac{1}{\det(B)}\det(B)
$$

Since \(\det(B)=3\neq0\),

$$
\frac{1}{3}\cdot3=1
$$

Thus, these two factors cancel, leaving only \(\det(A^T)=\det(A)=-2\).

## Final Answer

$$
\boxed{\det(B^{-1}A^TB)=-2}
$$

The properties used, in order, are:

1. **Product property:** \(\det(XYZ)=\det(X)\det(Y)\det(Z)\).
2. **Inverse property:** \(\det(B^{-1})=1/\det(B)\).
3. **Transpose property:** \(\det(A^T)=\det(A)\).

The factors involving \(B\) multiply to \(1\), so the final determinant equals \(\det(A)=-2\).
