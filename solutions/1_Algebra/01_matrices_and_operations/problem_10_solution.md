# Exercise 10. Columns of a Matrix Product

Given

```math
A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix},
\qquad
B=\begin{pmatrix}1&2\\-1&0\\3&1\end{pmatrix},
```

compute $Ab_1$, $Ab_2$, and $AB$, where $b_1=(1,-1,3)^T$ and $b_2=(2,0,1)^T$ are the columns of $B$. Explain how the two vectors appear in $AB$.

## 1. Compute the Column Products

Taking the dot product of each row of $A$ with $b_1$ gives

```math
Ab_1=
\begin{pmatrix}
1\cdot1+2\cdot(-1)+0\cdot3\\
0\cdot1+1\cdot(-1)+1\cdot3
\end{pmatrix}
=
\begin{pmatrix}-1\\2\end{pmatrix}.
```

Taking the dot product of each row of $A$ with $b_2$ gives

```math
Ab_2=
\begin{pmatrix}
1\cdot2+2\cdot0+0\cdot1\\
0\cdot2+1\cdot0+1\cdot1
\end{pmatrix}
=
\begin{pmatrix}2\\1\end{pmatrix}.
```

## 2. Compute AB Row by Column

```math
AB=
\begin{pmatrix}
1\cdot1+2\cdot(-1)+0\cdot3 & 1\cdot2+2\cdot0+0\cdot1\\
0\cdot1+1\cdot(-1)+1\cdot3 & 0\cdot2+1\cdot0+1\cdot1
\end{pmatrix}
=
\begin{pmatrix}-1&2\\2&1\end{pmatrix}.
```

## 3. Compare the Results

The first column of $AB$ is $Ab_1=(-1,2)^T$, and the second is $Ab_2=(2,1)^T$. This follows because entry $(i,j)$ of $AB$ is the dot product of row $i$ of $A$ with column $j$ of $B$. For a fixed $j$, those dot products are exactly the entries of $Ab_j$.
