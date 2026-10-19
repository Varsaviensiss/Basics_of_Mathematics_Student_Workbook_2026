# Exercise 8. Determinant of a Product

Given square matrices \(A\) and \(B\) such that

$$
\det(A)=3,\qquad \det(B)=-5
$$

We need to compute \(\det(AB)\), \(\det(BA)\), and \(\det(A^{-1}B)\), if it exists.

## 1. Compute \(\det(AB)\)

**Property:** The determinant of a product equals the product of the determinants.

$$
\det(AB)=\det(A)\det(B)
$$

Substitute the given values:

$$
\det(AB)=3(-5)
$$

$$
\boxed{\det(AB)=-15}
$$

## 2. Compute \(\det(BA)\)

Using the same property,

$$
\det(BA)=\det(B)\det(A)
$$

Substitute the given values:

$$
\det(BA)=(-5)(3)
$$

$$
\boxed{\det(BA)=-15}
$$

Therefore,

$$
\det(AB)=\det(BA)=-15
$$

## 3. Compute \(\det(A^{-1}B)\)

First, check whether \(A^{-1}\) exists.

A square matrix is invertible if and only if its determinant is nonzero. Since

$$
\det(A)=3\neq0,
$$

the inverse \(A^{-1}\) exists.

**Property:** The determinant of an inverse matrix is the reciprocal of the original determinant.

$$
\det(A^{-1})=\frac{1}{\det(A)}
$$

Therefore,

$$
\det(A^{-1})=\frac{1}{3}
$$

Now apply the product property:

$$
\det(A^{-1}B)=\det(A^{-1})\det(B)
$$

Substitute the known values:

$$
\det(A^{-1}B)=\frac{1}{3}(-5)
$$

$$
\boxed{\det(A^{-1}B)=-\frac{5}{3}}
$$

## 4. Why are \(\det(AB)\) and \(\det(BA)\) equal?

In general, matrix multiplication is not commutative:

$$
AB\neq BA
$$

However, the determinant of a product satisfies

$$
\det(AB)=\det(A)\det(B)
$$

and

$$
\det(BA)=\det(B)\det(A)
$$

Since ordinary scalar multiplication is commutative,

$$
\det(A)\det(B)=\det(B)\det(A)
$$

It follows that

$$
\boxed{\det(AB)=\det(BA)}
$$

Thus, \(AB\) and \(BA\) can be different matrices while having the same determinant.

## Final Answers

$$
\boxed{\det(AB)=-15}
$$

$$
\boxed{\det(BA)=-15}
$$

$$
\boxed{\det(A^{-1}B)=-\frac{5}{3}}
$$

All three determinants are defined because \(A\) and \(B\) are square matrices of the same size, and \(A^{-1}\) exists since \(\det(A)=3\neq0\).
