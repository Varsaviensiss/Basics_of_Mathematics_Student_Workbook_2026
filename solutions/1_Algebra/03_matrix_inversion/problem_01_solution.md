## Exercise 1: Definition of the Inverse

### Given Matrices

Let

\[
A=\begin{pmatrix}
2 & 1\\
1 & 1
\end{pmatrix},
\qquad
B=\begin{pmatrix}
1 & -1\\
-1 & 2
\end{pmatrix}
\]

We want to determine whether \(B=A^{-1}\) **without using the inverse formula**.

### 1. Compute \(AB\)

Multiply matrix \(A\) by matrix \(B\):

\[
AB=
\begin{pmatrix}
2 & 1\\
1 & 1
\end{pmatrix}
\begin{pmatrix}
1 & -1\\
-1 & 2
\end{pmatrix}
\]

Using row-by-column multiplication, we obtain

\[
AB=
\begin{pmatrix}
2(1)+1(-1) & 2(-1)+1(2)\\
1(1)+1(-1) & 1(-1)+1(2)
\end{pmatrix}
\]

Simplifying each entry gives

\[
AB=
\begin{pmatrix}
1 & 0\\
0 & 1
\end{pmatrix}
=I
\]

Thus, \(AB=I\).

### 2. Compute \(BA\)

Now multiply matrix \(B\) by matrix \(A\):

\[
BA=
\begin{pmatrix}
1 & -1\\
-1 & 2
\end{pmatrix}
\begin{pmatrix}
2 & 1\\
1 & 1
\end{pmatrix}
\]

Again, using row-by-column multiplication,

\[
BA=
\begin{pmatrix}
1(2)+(-1)(1) & 1(1)+(-1)(1)\\
(-1)(2)+2(1) & (-1)(1)+2(1)
\end{pmatrix}
\]

Simplifying gives

\[
BA=
\begin{pmatrix}
1 & 0\\
0 & 1
\end{pmatrix}
=I
\]

Thus, \(BA=I\).

### 3. Relate the Results to the Definition

The inverse of a square matrix \(A\) is a matrix \(B\) satisfying both conditions

\[
AB=BA=I
\]

where \(I\) is the identity matrix.

In this exercise, we have shown directly that

\[
AB=I
\qquad\text{and}\qquad
BA=I
\]

Therefore, both conditions in the definition of the inverse are satisfied.

### Final Answer

\[
\boxed{B=A^{-1}}
\]

**Conclusion:** Matrix \(B\) is the inverse of matrix \(A\). This is verified directly by matrix multiplication, without using any inverse formula or computational method.

\[
\boxed{B=A^{-1}}
\]

Therefore, \(B\) is the inverse of \(A\), verified directly through matrix multiplication without using an inverse formula.
