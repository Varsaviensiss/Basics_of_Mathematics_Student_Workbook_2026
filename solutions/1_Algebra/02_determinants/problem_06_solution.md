# Exercise 6. Parameter and Invertibility

Given the matrix

$$
A(t)=
\begin{pmatrix}
t & 1\\
2 & t
\end{pmatrix}
$$

We need to find all values of \(t\) for which \(A(t)\) is **not invertible**.

## Step 1: Find the determinant

For a \(2\times2\) matrix

$$
A=
\begin{pmatrix}
a & b\\
c & d
\end{pmatrix}
$$

the determinant is

$$
\det(A)=ad-bc
$$

For the given matrix,

$$
a=t,\qquad b=1,\qquad c=2,\qquad d=t
$$

Substituting these values gives

$$
\det(A(t))=t\cdot t-1\cdot 2
$$

$$
\det(A(t))=t^2-2
$$

## Step 2: Apply the condition for non-invertibility

A square matrix is not invertible if and only if its determinant is zero.

Therefore,

$$
\det(A(t))=0
$$

Substitute the determinant expression:

$$
t^2-2=0
$$

Add \(2\) to both sides:

$$
t^2=2
$$

Take the square root of both sides:

$$
t=\pm\sqrt{2}
$$

Thus, the two possible values are

$$
t=\sqrt{2}
\qquad\text{or}\qquad
t=-\sqrt{2}
$$

## Step 3: Verify the result

For \(t=\sqrt{2}\),

$$
\det(A(\sqrt{2}))=(\sqrt{2})^2-2
$$

$$
=2-2=0
$$

For \(t=-\sqrt{2}\),

$$
\det(A(-\sqrt{2}))=(-\sqrt{2})^2-2
$$

$$
=2-2=0
$$

In both cases, the determinant equals zero, so the matrix is not invertible.

## Final Answer

$$
\boxed{t=\pm\sqrt{2}}
$$

The matrix \(A(t)\) is not invertible when \(t=\sqrt{2}\) or \(t=-\sqrt{2}\).

**Explanation:** A square matrix is invertible if and only if its determinant is nonzero. When the determinant is zero, the matrix is singular and has no inverse. Since

$$
\det(A(t))=t^2-2,
$$

the matrix is not invertible precisely when \(t^2-2=0\), which gives \(t=\pm\sqrt{2}\).
