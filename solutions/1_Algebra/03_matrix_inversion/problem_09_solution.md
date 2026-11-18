# Exercise 9. Matrix Equation

## Question

Solve $AX=B$ for $X$ and verify the result by computing $AX$.

```math
A=\begin{pmatrix}1&2\\0&1\end{pmatrix},
\qquad
B=\begin{pmatrix}3&1\\2&4\end{pmatrix}.
```

## Solution

### 1. Find the Inverse of A

The determinant is $\det A=1\cdot1-2\cdot0=1\ne0$, so $A$ is invertible. Using the $2\times2$ inverse formula, we get

```math
A^{-1}
=\frac{1}{1\cdot1-2\cdot0}
\begin{pmatrix}1&-2\\-0&1\end{pmatrix}
=\begin{pmatrix}1&-2\\0&1\end{pmatrix}.
```

### 2. Isolate X

Since $A$ multiplies $X$ on the left, left-multiply both sides of $AX=B$ by $A^{-1}$:

```math
A^{-1}(AX)=(A^{-1}A)X=IX=X.
```

Therefore, $X=A^{-1}B$.

### 3. Compute X

```math
X=
\begin{pmatrix}1&-2\\0&1\end{pmatrix}
\begin{pmatrix}3&1\\2&4\end{pmatrix}
=
\begin{pmatrix}3-4&1-8\\2&4\end{pmatrix}
=
\begin{pmatrix}-1&-7\\2&4\end{pmatrix}.
```

### 4. Verify the Result

```math
AX=
\begin{pmatrix}1&2\\0&1\end{pmatrix}
\begin{pmatrix}-1&-7\\2&4\end{pmatrix}
=
\begin{pmatrix}-1+4&-7+8\\2&4\end{pmatrix}
=
\begin{pmatrix}3&1\\2&4\end{pmatrix}
=B.
```

The computed matrix satisfies the original equation.
