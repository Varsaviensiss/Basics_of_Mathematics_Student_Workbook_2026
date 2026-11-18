# Exercise 7. Inverse of a Product

## Question

Given

```math
A=\begin{pmatrix}1&1\\0&1\end{pmatrix},
\qquad
B=\begin{pmatrix}2&0\\0&3\end{pmatrix},
```

compute $(AB)^{-1}$ and $B^{-1}A^{-1}$. Compare the results and explain why the order is reversed when taking the inverse of a product.

## Solution

### 1. Compute AB Row by Column

```math
AB=
\begin{pmatrix}
1\cdot2+1\cdot0 & 1\cdot0+1\cdot3\\
0\cdot2+1\cdot0 & 0\cdot0+1\cdot3
\end{pmatrix}
=
\begin{pmatrix}2&3\\0&3\end{pmatrix}.
```

### 2. Find the Inverses

For a matrix with entries $a,b,c,d$ and nonzero determinant $ad-bc$, the $2\times2$ inverse formula is

```math
\begin{pmatrix}a&b\\c&d\end{pmatrix}^{-1}
=
\frac{1}{ad-bc}\begin{pmatrix}d&-b\\-c&a\end{pmatrix}.
```

Since $\det(AB)=2\cdot3-3\cdot0=6$,

```math
(AB)^{-1}
=\frac16\begin{pmatrix}3&-3\\0&2\end{pmatrix}
=\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}.
```

Similarly, $\det A=1\cdot1-1\cdot0=1$ and $\det B=2\cdot3-0\cdot0=6$, so the same formula gives

```math
A^{-1}=\frac11\begin{pmatrix}1&-1\\0&1\end{pmatrix}
=\begin{pmatrix}1&-1\\0&1\end{pmatrix},
\qquad
B^{-1}=\frac16\begin{pmatrix}3&0\\0&2\end{pmatrix}
=\begin{pmatrix}\frac12&0\\0&\frac13\end{pmatrix}.
```

### 3. Compute B Inverse Times A Inverse Row by Column

```math
B^{-1}A^{-1}
=
\begin{pmatrix}
\frac12\cdot1+0\cdot0 & \frac12\cdot(-1)+0\cdot1\\
0\cdot1+\frac13\cdot0 & 0\cdot(-1)+\frac13\cdot1
\end{pmatrix}
=
\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}
=(AB)^{-1}.
```

### 4. Explain the Order

On a column vector, $AB$ applies $B$ first and then $A$. To undo the composition, apply $A^{-1}$ first and then $B^{-1}$. This is the action of $B^{-1}A^{-1}$. The order also follows from the multiplication check:

```math
(AB)(B^{-1}A^{-1})
=A(BB^{-1})A^{-1}
=AA^{-1}
=I.
```
