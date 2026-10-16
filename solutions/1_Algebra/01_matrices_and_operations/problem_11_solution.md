# Exercise 11. When Do Matrices Commute?

Given:

$$
A=\begin{pmatrix}1&1\\0&1\end{pmatrix},
\qquad
B=\begin{pmatrix}a&b\\c&d\end{pmatrix}
$$

We want to find the conditions under which \(AB=BA\).

## 1. Compute \(AB\)

$$
AB=
\begin{pmatrix}1&1\\0&1\end{pmatrix}
\begin{pmatrix}a&b\\c&d\end{pmatrix}
$$

Multiplying the matrices gives

$$
AB=\begin{pmatrix}a+c&b+d\\c&d\end{pmatrix}
$$

## 2. Compute \(BA\)

$$
BA=
\begin{pmatrix}a&b\\c&d\end{pmatrix}
\begin{pmatrix}1&1\\0&1\end{pmatrix}
$$

Multiplying the matrices gives

$$
BA=\begin{pmatrix}a&a+b\\c&c+d\end{pmatrix}
$$

## 3. Find the Conditions for \(AB=BA\)

For the matrices to be equal, their corresponding entries must be equal:

$$
\begin{pmatrix}a+c&b+d\\c&d\end{pmatrix}
=
\begin{pmatrix}a&a+b\\c&c+d\end{pmatrix}
$$

Comparing entries gives

$$
a+c=a \quad\Rightarrow\quad c=0
$$

$$
b+d=a+b \quad\Rightarrow\quad d=a
$$

The remaining equations give the same conditions.

Therefore, the required conditions are

$$
\boxed{c=0,\qquad d=a}
$$

## 4. General Form of \(B\)

Substituting these conditions into \(B\), we obtain

$$
\boxed{B=\begin{pmatrix}a&b\\0&a\end{pmatrix}}
$$

where \(a\) and \(b\) can be any real numbers.

## Conclusion

The matrices \(A\) and \(B\) commute if and only if \(c=0\) and \(d=a\). Thus, all matrices that commute with \(A\) have the form

$$
B=\begin{pmatrix}a&b\\0&a\end{pmatrix}
$$

This example shows that although matrix multiplication is not commutative in general, certain matrices do commute when specific conditions are satisfied.
