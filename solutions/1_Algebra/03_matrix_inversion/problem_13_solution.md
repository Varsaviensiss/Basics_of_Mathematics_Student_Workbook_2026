# Exercise 13. Undoing a Composite Transformation

## Question

Given

```math
S=\begin{pmatrix}2&0\\0&1\end{pmatrix},
\qquad
H=\begin{pmatrix}1&1\\0&1\end{pmatrix},
\qquad
T=HS,
```

find $T^{-1}$ by first computing $T$ and then by using the inverse-of-a-product rule. Compute $H^{-1}S^{-1}$ for comparison and explain the order in which the transformations are undone.

## Solution

### Method 1. Compute T and Invert It

Multiply each row of $H$ by each column of $S$:

```math
T=HS
=\begin{pmatrix}
1\cdot2+1\cdot0 & 1\cdot0+1\cdot1\\
0\cdot2+1\cdot0 & 0\cdot0+1\cdot1
\end{pmatrix}
=\begin{pmatrix}2&1\\0&1\end{pmatrix}.
```

Since $\det T=2\cdot1-1\cdot0=2$, the $2\times2$ inverse formula gives

```math
T^{-1}
=\frac12\begin{pmatrix}1&-1\\0&2\end{pmatrix}
=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}.
```

### Method 2. Use the Inverse-of-a-Product Rule

The inverse of a diagonal matrix with nonzero diagonal entries is obtained by taking the reciprocal of each diagonal entry. For $H$, the determinant is $1\cdot1-1\cdot0=1$, so the $2\times2$ inverse formula gives

```math
S^{-1}=\begin{pmatrix}\frac12&0\\0&1\end{pmatrix},
\qquad
H^{-1}=\frac{1}{1\cdot1-1\cdot0}\begin{pmatrix}1&-1\\0&1\end{pmatrix}
=\begin{pmatrix}1&-1\\0&1\end{pmatrix}.
```

Now compute $S^{-1}H^{-1}$ row by column:

```math
S^{-1}H^{-1}
=\begin{pmatrix}
\frac12\cdot1+0\cdot0 & \frac12\cdot(-1)+0\cdot1\\
0\cdot1+1\cdot0 & 0\cdot(-1)+1\cdot1
\end{pmatrix}
=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}
=T^{-1}.
```

### Compare with the Other Order

```math
H^{-1}S^{-1}
=\begin{pmatrix}
1\cdot\frac12+(-1)\cdot0 & 1\cdot0+(-1)\cdot1\\
0\cdot\frac12+1\cdot0 & 0\cdot0+1\cdot1
\end{pmatrix}
=\begin{pmatrix}\frac12&-1\\0&1\end{pmatrix}.
```

The upper-right entries of $HS$, $S^{-1}H^{-1}$, and $H^{-1}S^{-1}$ are $1$, $-\frac12$, and $-1$, respectively. Thus the two products of inverses give different matrices.

On a column vector, $HS$ applies $S$ first and then $H$. To undo this composition, apply $H^{-1}$ first and then $S^{-1}$. This gives $(HS)^{-1}=S^{-1}H^{-1}$.
