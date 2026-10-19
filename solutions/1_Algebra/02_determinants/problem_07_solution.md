# Exercise 7. Using Properties Instead of Recomputing

Given a \(3\times3\) matrix \(A\) such that

$$
\det(A)=-4
$$

We need to compute

$$
\det(2A),\quad \det(A^T),\quad \det(A^2),\quad \det(-A).
$$

## 1. Compute \(\det(2A)\)

**Property:** If \(A\) is an \(n\times n\) matrix and \(c\) is a scalar, then

$$
\det(cA)=c^n\det(A)
$$

Since \(A\) is a \(3\times3\) matrix, \(n=3\). Therefore,

$$
\det(2A)=2^3\det(A)
$$

Substitute \(\det(A)=-4\):

$$
\det(2A)=8(-4)
$$

$$
\boxed{\det(2A)=-32}
$$

## 2. Compute \(\det(A^T)\)

**Property:** The determinant of a matrix equals the determinant of its transpose.

$$
\det(A^T)=\det(A)
$$

Since \(\det(A)=-4\),

$$
\boxed{\det(A^T)=-4}
$$

## 3. Compute \(\det(A^2)\)

**Property:** The determinant of a product is the product of the determinants.

$$
\det(AB)=\det(A)\det(B)
$$

Since \(A^2=AA\),

$$
\det(A^2)=\det(AA)
$$

$$
\det(A^2)=\det(A)\det(A)
$$

Substitute \(\det(A)=-4\):

$$
\det(A^2)=(-4)(-4)
$$

$$
\boxed{\det(A^2)=16}
$$

## 4. Compute \(\det(-A)\)

**Property:** For an \(n\times n\) matrix,

$$
\det(cA)=c^n\det(A)
$$

Here, \(c=-1\) and \(n=3\). Therefore,

$$
\det(-A)=(-1)^3\det(A)
$$

$$
\det(-A)=(-1)(-4)
$$

$$
\boxed{\det(-A)=4}
$$

## Final Answers

| Determinant | Property used | Result |
|---|---|---:|
| \(\det(2A)\) | \(\det(cA)=c^3\det(A)\) | \(\boxed{-32}\) |
| \(\det(A^T)\) | \(\det(A^T)=\det(A)\) | \(\boxed{-4}\) |
| \(\det(A^2)\) | \(\det(AB)=\det(A)\det(B)\) | \(\boxed{16}\) |
| \(\det(-A)\) | \(\det(cA)=c^3\det(A)\) | \(\boxed{4}\) |
