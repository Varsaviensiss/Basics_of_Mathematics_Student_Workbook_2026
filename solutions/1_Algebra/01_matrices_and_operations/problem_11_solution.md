# Exercise 11. When Do Matrices Commute?

Given

```math
A=\begin{pmatrix}1&1\\0&1\end{pmatrix},
\qquad
B=\begin{pmatrix}a&b\\c&d\end{pmatrix},
```

find the conditions on $a,b,c,d$ for which $AB=BA$.

## 1. Compute AB

Each entry is the dot product of a row of $A$ with a column of $B$.

```math
AB=
\begin{pmatrix}
1\cdot a+1\cdot c & 1\cdot b+1\cdot d\\
0\cdot a+1\cdot c & 0\cdot b+1\cdot d
\end{pmatrix}
=
\begin{pmatrix}
a+c & b+d\\
c & d
\end{pmatrix}.
```

## 2. Compute BA

Now take the dot product of each row of $B$ with each column of $A$.

```math
BA=
\begin{pmatrix}
a\cdot1+b\cdot0 & a\cdot1+b\cdot1\\
c\cdot1+d\cdot0 & c\cdot1+d\cdot1
\end{pmatrix}
=
\begin{pmatrix}
a & a+b\\
c & c+d
\end{pmatrix}.
```

## 3. Compare Corresponding Entries

| Entry | Equality | Condition |
|---|---|---|
| $(1,1)$ | $a+c=a$ | $c=0$ |
| $(1,2)$ | $b+d=a+b$ | $d=a$ |
| $(2,1)$ | $c=c$ | Always true |
| $(2,2)$ | $d=c+d$ | $c=0$ |

Thus, $AB=BA$ if and only if $c=0$ and $d=a$. Under these conditions, all four entries agree. Therefore, the matrices that commute with $A$ have the form

```math
B=\begin{pmatrix}a&b\\0&a\end{pmatrix},
\qquad a,b\in\mathbb{R}.
