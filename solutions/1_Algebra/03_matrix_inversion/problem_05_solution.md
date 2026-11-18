# Exercise 5. Inverse of a 3 × 3 Matrix

## Question

Find the inverse of the matrix below using Gauss–Jordan elimination on $[A\mid I]$. Explain why the right block becomes $A^{-1}$ and verify the result by multiplication.

```math
A=\begin{pmatrix}1&1&0\\0&1&1\\1&0&1\end{pmatrix}.
```

## Solution

### 1. Row-Reduce the Augmented Matrix

Start with $[A\mid I]$ and eliminate the first two entries of row 3:

```math
\left[\begin{array}{ccc|ccc}
1&1&0&1&0&0\\
0&1&1&0&1&0\\
1&0&1&0&0&1
\end{array}\right]
\xrightarrow{R_3\leftarrow R_3-R_1}
\left[\begin{array}{ccc|ccc}
1&1&0&1&0&0\\
0&1&1&0&1&0\\
0&-1&1&-1&0&1
\end{array}\right]
\xrightarrow{R_3\leftarrow R_3+R_2}
\left[\begin{array}{ccc|ccc}
1&1&0&1&0&0\\
0&1&1&0&1&0\\
0&0&2&-1&1&1
\end{array}\right].
```

Make the third pivot equal to $1$ and clear the entry above it in row 2:

```math
\left[\begin{array}{ccc|ccc}
1&1&0&1&0&0\\
0&1&1&0&1&0\\
0&0&2&-1&1&1
\end{array}\right]
\xrightarrow{R_3\leftarrow R_3/2}
\left[\begin{array}{ccc|ccc}
1&1&0&1&0&0\\
0&1&1&0&1&0\\
0&0&1&-\frac12&\frac12&\frac12
\end{array}\right]
\xrightarrow{R_2\leftarrow R_2-R_3}
\left[\begin{array}{ccc|ccc}
1&1&0&1&0&0\\
0&1&0&\frac12&\frac12&-\frac12\\
0&0&1&-\frac12&\frac12&\frac12
\end{array}\right].
```

Finally, apply $R_1\leftarrow R_1-R_2$:

```math
\left[\begin{array}{ccc|ccc}
1&0&0&\frac12&-\frac12&\frac12\\
0&1&0&\frac12&\frac12&-\frac12\\
0&0&1&-\frac12&\frac12&\frac12
\end{array}\right].
```

### 2. Explain Why the Right Block Is the Inverse

Let $E$ be the product of the elementary matrices representing these row operations. Applying the same operations to both blocks gives $[EA\mid EI]=[I\mid E]$. The left block shows that $EA=I$. Since $E$ is invertible, $A=E^{-1}$, so the right block $E$ equals $A^{-1}$:

```math
A^{-1}=\frac12
\begin{pmatrix}
1&-1&1\\
1&1&-1\\
-1&1&1
\end{pmatrix}.
```

### 3. Verify by Multiplication

Taking the dot product of each row of $A$ with each column of the displayed integer matrix gives the following entries. Terms multiplied by zero are omitted.

```math
AA^{-1}
=\frac12
\begin{pmatrix}
1+1&-1+1&1-1\\
1-1&1+1&-1+1\\
1-1&-1+1&1+1
\end{pmatrix}
=\frac12
\begin{pmatrix}
2&0&0\\
0&2&0\\
0&0&2
\end{pmatrix}
=I.
```

The product is the identity, which verifies the inverse relation.
