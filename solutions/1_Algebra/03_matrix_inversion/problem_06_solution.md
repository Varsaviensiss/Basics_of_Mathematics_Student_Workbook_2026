# Exercise 6. Solving a System Using the Inverse

## Question

Solve $Ax=b$ using the inverse of $A$. Explain why the method works and verify the solution in both original equations.

```math
A=\begin{pmatrix}2&1\\1&3\end{pmatrix},
\qquad
b=\begin{pmatrix}5\\7\end{pmatrix}.
```

## Solution

### 1. Explain Why the Inverse Method Works

The determinant is $\det A=2\cdot3-1\cdot1=5\ne0$, so $A$ is invertible. Left-multiplying both sides of $Ax=b$ by $A^{-1}$ gives

```math
A^{-1}(Ax)=A^{-1}b,
\qquad
A^{-1}(Ax)=(A^{-1}A)x=Ix=x.
```

Therefore, $x=A^{-1}b$.

### 2. Compute the Solution

The $2\times2$ inverse formula gives

```math
A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix}.
```

Multiplying by $b$ gives

```math
x=\frac15
\begin{pmatrix}
3\cdot5-1\cdot7\\
-1\cdot5+2\cdot7
\end{pmatrix}
=\begin{pmatrix}\frac85\\[2pt]\frac95\end{pmatrix}.
```

### 3. Check Both Original Equations

```math
\begin{aligned}
2\left(\frac85\right)+\frac95
&=\frac{16+9}{5}=5,\\
\frac85+3\left(\frac95\right)
&=\frac{8+27}{5}=7.
\end{aligned}
```

Both equations give their original right-hand sides, so the computed vector satisfies the original system.
