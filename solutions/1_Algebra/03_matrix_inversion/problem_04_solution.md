# Exercise 4. Gauss–Jordan Elimination

## Question

Find the inverse of the matrix below by applying Gauss–Jordan elimination to $[A\mid I]$. Explain why the right block becomes $A^{-1}$ when the left block becomes $I$, then verify your result by multiplication.

```math
A=\begin{pmatrix}1&2\\3&5\end{pmatrix}.
```

## Solution

### 1. Row-Reduce the Augmented Matrix

```math
\left[\begin{array}{cc|cc}
1&2&1&0\\
3&5&0&1
\end{array}\right]
\xrightarrow{R_2\leftarrow R_2-3R_1}
\left[\begin{array}{cc|cc}
1&2&1&0\\
0&-1&-3&1
\end{array}\right]
\xrightarrow{R_2\leftarrow -R_2}
\left[\begin{array}{cc|cc}
1&2&1&0\\
0&1&3&-1
\end{array}\right]
\xrightarrow{R_1\leftarrow R_1-2R_2}
\left[\begin{array}{cc|cc}
1&0&-5&2\\
0&1&3&-1
\end{array}\right].
```

### 2. Explain Why the Right Block Is the Inverse

Each elementary row operation is equivalent to left-multiplication by an invertible elementary matrix. Let $E$ be the product of those matrices in the order that carries out the three row operations. Applying them to the augmented matrix gives

```math
E[A\mid I]=[EA\mid EI]=[I\mid E].
```

The left block gives $EA=I$. Since $E$ is invertible, multiplying by $E^{-1}$ on the left gives $A=E^{-1}$, so $E=A^{-1}$. The right block is $EI=E$, hence

```math
A^{-1}=\begin{pmatrix}-5&2\\3&-1\end{pmatrix}.
```

### 3. Verify by Multiplication

```math
AA^{-1}
=
\begin{pmatrix}1&2\\3&5\end{pmatrix}
\begin{pmatrix}-5&2\\3&-1\end{pmatrix}
=
\begin{pmatrix}
-5+6&2-2\\
-15+15&6-5
\end{pmatrix}
=
\begin{pmatrix}1&0\\0&1\end{pmatrix}
=I.
```
