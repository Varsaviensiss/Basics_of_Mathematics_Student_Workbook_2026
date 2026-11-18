# Exercise 15. Two Methods for Solving the Same System

## Question

Solve $A\mathbf{x}=\mathbf{b}$ using both the inverse matrix and Gaussian elimination:

```math
A=\begin{pmatrix}2&1\\1&3\end{pmatrix},
\qquad
\mathbf{b}=\begin{pmatrix}7\\8\end{pmatrix}.
```

Explain why the inverse method works, verify the solution, and compare the essential stages of the two methods.

## Solution

### Method 1. Use the Inverse Matrix

If $A$ is invertible, left-multiplying both sides of $A\mathbf{x}=\mathbf{b}$ by $A^{-1}$ gives

```math
A^{-1}(A\mathbf{x})=(A^{-1}A)\mathbf{x}
=I\mathbf{x}=\mathbf{x}=A^{-1}\mathbf{b}.
```

Here $\det A=2\cdot3-1\cdot1=5\ne0$, so the inverse exists. The inverse formula and vector multiplication give

```math
A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix},
\qquad
\mathbf{x}=A^{-1}\mathbf{b}
=\frac15\begin{pmatrix}3\cdot7-8\\-7+2\cdot8\end{pmatrix}
=\begin{pmatrix}13/5\\9/5\end{pmatrix}.
```

### Method 2. Use Gaussian Elimination

Swap the rows to put a $1$ in the first pivot position. Then subtract twice the first row from the second:

```math
\left[\begin{array}{cc|c}2&1&7\\1&3&8\end{array}\right]
\xrightarrow{R_1\leftrightarrow R_2}
\left[\begin{array}{cc|c}1&3&8\\2&1&7\end{array}\right]
\xrightarrow{R_2\leftarrow R_2-2R_1}
\left[\begin{array}{cc|c}1&3&8\\0&-5&-9\end{array}\right].
```

The second row gives $-5y=-9$, so $y=9/5$. Back-substitute into $x+3y=8$ to get $x=8-27/5=13/5$.

### Verify the Solution

Substitute into both original equations:

```math
2(13/5)+9/5=35/5=7,
\qquad
13/5+3(9/5)=40/5=8.
```

Both methods give the same solution, and it satisfies the original system.

### Compare the Essential Stages

Counting stages by purpose and treating verification as a shared final check, the inverse method has three stages: compute the determinant, construct the inverse, and multiply it by the right-hand-side vector. Elimination also has three stages in the calculation shown: swap the rows, perform a row replacement, and back-substitute. The back-substitution stage includes finding $y$ from the last row and then finding $x$.

For this single right-hand side, elimination is more direct because it solves the equations without constructing an inverse. If the inverse is already known, it can be reused for multiple right-hand sides.
