# Exercise 15. Associativity of Multiplication and Different Calculation Paths

Given

```math
A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix},
\qquad
B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix},
\qquad
C=\begin{pmatrix}2&1\\0&-1\end{pmatrix},
```

compute $(AB)C$ and $A(BC)$, then compare the results and the two calculation paths.

## 1. Compute (AB)C

Each entry is the dot product of a row of the left matrix with a column of the right matrix. First compute $AB$:

```math
AB=
\begin{pmatrix}
1\cdot1+2\cdot2+0\cdot(-1) & 1\cdot0+2\cdot1+0\cdot3\\
0\cdot1+1\cdot2+1\cdot(-1) & 0\cdot0+1\cdot1+1\cdot3
\end{pmatrix}
=\begin{pmatrix}5&2\\1&4\end{pmatrix}.
```

Then multiply by $C$ on the right:

```math
(AB)C=
\begin{pmatrix}
5\cdot2+2\cdot0 & 5\cdot1+2\cdot(-1)\\
1\cdot2+4\cdot0 & 1\cdot1+4\cdot(-1)
\end{pmatrix}
=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.
```

## 2. Compute A(BC)

First compute $BC$:

```math
BC=
\begin{pmatrix}
1\cdot2+0\cdot0 & 1\cdot1+0\cdot(-1)\\
2\cdot2+1\cdot0 & 2\cdot1+1\cdot(-1)\\
(-1)\cdot2+3\cdot0 & (-1)\cdot1+3\cdot(-1)
\end{pmatrix}
=\begin{pmatrix}2&1\\4&1\\-2&-4\end{pmatrix}.
```

Then multiply by $A$ on the left:

```math
A(BC)=
\begin{pmatrix}
1\cdot2+2\cdot4+0\cdot(-2) & 1\cdot1+2\cdot1+0\cdot(-4)\\
0\cdot2+1\cdot4+1\cdot(-2) & 0\cdot1+1\cdot1+1\cdot(-4)
\end{pmatrix}
=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.
```

## 3. Compare the Calculation Paths

Both paths give the same result:

```math
(AB)C=A(BC)=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.
```

Each path uses two matrix multiplications. The intermediate matrix $AB$ is $2\times2$, while $BC$ is $3\times2$. Counting every scalar multiplication and addition in the displayed dot products, including terms with zero, gives:

| Path | Scalar multiplications | Scalar additions |
|---|---:|---:|
| $(AB)C$ | $12+8=20$ | $8+4=12$ |
| $A(BC)$ | $12+12=24$ | $6+8=14$ |

Associativity allows us to change the grouping of the factors while keeping their order as $A,B,C$. In this example, both groupings give the same matrix, and computing $AB$ first uses fewer scalar operations.
