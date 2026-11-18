# Exercise 1. Verifying an Inverse by Definition

## Question

Given

```math
A=\begin{pmatrix}2&1\\1&1\end{pmatrix},
\qquad
B=\begin{pmatrix}1&-1\\-1&2\end{pmatrix},
```

compute $AB$ and $BA$ entry by entry. Use the definition of an inverse to determine whether $B=A^{-1}$, without using an inverse formula.

## Solution

Compute $AB$ by multiplying each row of $A$ by each column of $B$:

```math
AB=
\begin{pmatrix}
2\cdot1+1\cdot(-1) & 2\cdot(-1)+1\cdot2\\
1\cdot1+1\cdot(-1) & 1\cdot(-1)+1\cdot2
\end{pmatrix}
=
\begin{pmatrix}1&0\\0&1\end{pmatrix}
=I.
```

Compute $BA$ by multiplying each row of $B$ by each column of $A$:

```math
BA=
\begin{pmatrix}
1\cdot2+(-1)\cdot1 & 1\cdot1+(-1)\cdot1\\
(-1)\cdot2+2\cdot1 & (-1)\cdot1+2\cdot1
\end{pmatrix}
=
\begin{pmatrix}1&0\\0&1\end{pmatrix}
=I.
```

Since $AB=BA=I$, the definition of an inverse gives $B=A^{-1}$.
