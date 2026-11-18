# Exercise 13. A Recurrence Written in Matrix Form

Given

```math
F=\begin{pmatrix}1&1\\1&0\end{pmatrix},
```

compute $F^2$, $F^3$, $F^4$, and $F^5$. Explain how their entries relate to the Fibonacci sequence, and show what happens when $F$ multiplies the column vector $(a,b)^T$.

## 1. Compute the Powers Row by Column

Each entry is the dot product of a row of the left matrix with a column of $F$.

```math
F^2=FF
=\begin{pmatrix}
1\cdot1+1\cdot1 & 1\cdot1+1\cdot0\\
1\cdot1+0\cdot1 & 1\cdot1+0\cdot0
\end{pmatrix}
=\begin{pmatrix}2&1\\1&1\end{pmatrix}.
```

```math
F^3=F^2F
=\begin{pmatrix}
2\cdot1+1\cdot1 & 2\cdot1+1\cdot0\\
1\cdot1+1\cdot1 & 1\cdot1+1\cdot0
\end{pmatrix}
=\begin{pmatrix}3&2\\2&1\end{pmatrix}.
```

```math
F^4=F^3F
=\begin{pmatrix}
3\cdot1+2\cdot1 & 3\cdot1+2\cdot0\\
2\cdot1+1\cdot1 & 2\cdot1+1\cdot0
\end{pmatrix}
=\begin{pmatrix}5&3\\3&2\end{pmatrix}.
```

```math
F^5=F^4F
=\begin{pmatrix}
5\cdot1+3\cdot1 & 5\cdot1+3\cdot0\\
3\cdot1+2\cdot1 & 3\cdot1+2\cdot0
\end{pmatrix}
=\begin{pmatrix}8&5\\5&3\end{pmatrix}.
```

## 2. Explain the Fibonacci Pattern

The Fibonacci sequence starts with $F_0=0$ and $F_1=1$. Each subsequent term is the sum of the previous two. In each matrix product above, a row $(p,q)$ becomes $(p+q,p)$: its sum becomes the first entry, and its old first entry shifts to the second position.

The rows of $F$ are $(F_2,F_1)$ and $(F_1,F_0)$. Each multiplication on the right by $F$ advances both pairs by one Fibonacci step. Therefore, for $n\geq1$,

```math
F^n=\begin{pmatrix}
F_{n+1}&F_n\\
F_n&F_{n-1}
\end{pmatrix}.
```

## 3. Multiply by a Column Vector

```math
F\begin{pmatrix}a\\b\end{pmatrix}
=\begin{pmatrix}
1\cdot a+1\cdot b\\
1\cdot a+0\cdot b
\end{pmatrix}
=\begin{pmatrix}a+b\\a\end{pmatrix}.
```

If $a$ is the current Fibonacci term and $b$ is the preceding term, the first component $a+b$ is the next term and the second component $a$ keeps the current term. Repeated multiplication by $F$ repeats this add-and-shift step.
