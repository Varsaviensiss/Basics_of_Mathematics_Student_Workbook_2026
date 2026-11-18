# Exercise 9. Composing Transformations

Given

```math
S=\begin{pmatrix}2 & 0 \\ 0 & 1\end{pmatrix},\qquad
R=\begin{pmatrix}0 & -1 \\ 1 & 0\end{pmatrix},\qquad
x=(1,2)^T,
```

compute $RSx$ and $SRx$, compare the results, and explain why the order matters.

## 1. Compute RSx

First apply $S$ to $x$. Each component is the dot product of one row of $S$ with $x$.

```math
Sx=(2\cdot1+0\cdot2,\;0\cdot1+1\cdot2)^T=(2,2)^T.
```

Then apply $R$ to $Sx$.

```math
RSx=R(Sx)=(0\cdot2-1\cdot2,\;1\cdot2+0\cdot2)^T=(-2,2)^T.
```

## 2. Compute SRx

First apply $R$ to $x$.

```math
Rx=(0\cdot1-1\cdot2,\;1\cdot1+0\cdot2)^T=(-2,1)^T.
```

Then apply $S$ to $Rx$.

```math
SRx=S(Rx)=(2\cdot(-2)+0\cdot1,\;0\cdot(-2)+1\cdot1)^T=(-4,1)^T.
```

## 3. Compare and Explain

The results are different, so $RSx\ne SRx$.

The matrix $S$ doubles the horizontal coordinate, and $R$ rotates the vector $90^\circ$ counterclockwise. Scaling first doubles the original horizontal coordinate, which becomes the vertical coordinate after rotation. Rotating first makes the negative of the original vertical coordinate the new horizontal coordinate, which $S$ then doubles. This explains why the order matters.
