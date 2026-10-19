### Exercise 1. Definition of the Inverse

Given

\[
A=\begin{pmatrix}2&1\\1&1\end{pmatrix},
\qquad
B=\begin{pmatrix}1&-1\\-1&2\end{pmatrix}
\]

To check whether \(B=A^{-1}\), we compute \(AB\) and \(BA\).

**1. Compute \(AB\)**

\[
AB=
\begin{pmatrix}2&1\\1&1\end{pmatrix}
\begin{pmatrix}1&-1\\-1&2\end{pmatrix}
\]

\[
AB=
\begin{pmatrix}
2(1)+1(-1) & 2(-1)+1(2)\\
1(1)+1(-1) & 1(-1)+1(2)
\end{pmatrix}
\]

\[
AB=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I
\]

**2. Compute \(BA\)**

\[
BA=
\begin{pmatrix}1&-1\\-1&2\end{pmatrix}
\begin{pmatrix}2&1\\1&1\end{pmatrix}
\]

\[
BA=
\begin{pmatrix}
1(2)+(-1)(1) & 1(1)+(-1)(1)\\
(-1)(2)+2(1) & (-1)(1)+2(1)
\end{pmatrix}
\]

\[
BA=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I
\]

**3. Conclusion**

By definition, a matrix \(B\) is the inverse of \(A\) if both \(AB=I\) and \(BA=I\), where \(I\) is the identity matrix.

Since both products equal the identity matrix, we conclude that

\[
\boxed{B=A^{-1}}
\]

Therefore, \(B\) is the inverse of \(A\), verified directly through matrix multiplication without using an inverse formula.
