# Exercise 12. Formula for a Matrix Power

Given

```math
A=\begin{pmatrix}1&1\\0&1\end{pmatrix},
```

compute $A^2$, $A^3$, and $A^4$. Use the pattern to conjecture a formula for $A^n$ and prove it by induction.

## 1. Compute the First Powers

Each entry is the dot product of a row of the left matrix with a column of the right matrix.

```math
A^2=AA
=\begin{pmatrix}
1\cdot1+1\cdot0 & 1\cdot1+1\cdot1\\
0\cdot1+1\cdot0 & 0\cdot1+1\cdot1
\end{pmatrix}
=\begin{pmatrix}1&2\\0&1\end{pmatrix}.
```

```math
A^3=A^2A
=\begin{pmatrix}
1\cdot1+2\cdot0 & 1\cdot1+2\cdot1\\
0\cdot1+1\cdot0 & 0\cdot1+1\cdot1
\end{pmatrix}
=\begin{pmatrix}1&3\\0&1\end{pmatrix}.
```

```math
A^4=A^3A
=\begin{pmatrix}
1\cdot1+3\cdot0 & 1\cdot1+3\cdot1\\
0\cdot1+1\cdot0 & 0\cdot1+1\cdot1
\end{pmatrix}
=\begin{pmatrix}1&4\\0&1\end{pmatrix}.
```

## 2. Formulate the Conjecture

The diagonal entries stay at $1$, the lower-left entry stays at $0$, and the upper-right entry equals the exponent. This suggests that

```math
A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}
```

for every positive integer $n$.

## 3. Prove the Formula by Induction

**Base case.** For $n=1$, the formula gives $A^1=A$.

**Inductive step.** Assume $A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}$ for some positive integer $n$. Multiplying by $A$ on the right gives

```math
A^{n+1}=A^nA
=\begin{pmatrix}1&n\\0&1\end{pmatrix}
 \begin{pmatrix}1&1\\0&1\end{pmatrix}
=\begin{pmatrix}
1\cdot1+n\cdot0 & 1\cdot1+n\cdot1\\
0\cdot1+1\cdot0 & 0\cdot1+1\cdot1
\end{pmatrix}
=\begin{pmatrix}1&n+1\\0&1\end{pmatrix}.
```

Only the upper-right entry increases by one. The other three entries remain $1$, $0$, and $1$. This proves the formula for $n+1$, so by induction it holds for every positive integer $n$.
