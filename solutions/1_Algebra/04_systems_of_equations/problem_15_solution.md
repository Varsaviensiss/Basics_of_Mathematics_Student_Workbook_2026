# Exercise 15. Two Methods for Solving the Same System

Given:

$$
A=\begin{pmatrix}2&1\\1&3\end{pmatrix},
\qquad
b=\begin{pmatrix}7\\8\end{pmatrix}
$$

We solve:

$$
Ax=b
$$

using two methods.

## Method 1. Using \(x=A^{-1}b\)

### Step 1. Find the inverse

Calculate the determinant:

$$
\det(A)=2\cdot3-1\cdot1=5
$$

Since the determinant is nonzero, \(A^{-1}\) exists.

$$
A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix}
$$

### Step 2. Calculate \(x=A^{-1}b\)

$$
x=\frac15
\begin{pmatrix}3&-1\\-1&2\end{pmatrix}
\begin{pmatrix}7\\8\end{pmatrix}
$$

$$
x=\frac15
\begin{pmatrix}
3(7)-8\\
-7+2(8)
\end{pmatrix}
$$

$$
x=\frac15\begin{pmatrix}13\\9\end{pmatrix}
$$

Therefore:

$$
\boxed{x=\begin{pmatrix}\frac{13}{5}\\[2pt]\frac95\end{pmatrix}}
$$

### Step 3. Verify

$$
A x=
\begin{pmatrix}2&1\\1&3\end{pmatrix}
\begin{pmatrix}\frac{13}{5}\\[2pt]\frac95\end{pmatrix}
$$

$$
=
\begin{pmatrix}
\frac{26}{5}+\frac95\\[4pt]
\frac{13}{5}+\frac{27}{5}
\end{pmatrix}
=
\begin{pmatrix}7\\8\end{pmatrix}
$$

Thus, \(Ax=b\).

## Method 2. Using Gaussian elimination

The system is:

$$
\begin{cases}
2x+y=7,\\
x+3y=8.
\end{cases}
$$

Write the augmented matrix:

$$
\left[
\begin{array}{cc|c}
2&1&7\\
1&3&8
\end{array}
\right]
$$

Swap the two rows:

$$
R_1\leftrightarrow R_2
$$

$$
\left[
\begin{array}{cc|c}
1&3&8\\
2&1&7
\end{array}
\right]
$$

Eliminate the entry below the first pivot:

$$
R_2\leftarrow R_2-2R_1
$$

$$
\left[
\begin{array}{cc|c}
1&3&8\\
0&-5&-9
\end{array}
\right]
$$

The second row gives:

$$
-5y=-9
$$

$$
\boxed{y=\frac95}
$$

Substitute into the first equation:

$$
x+3\left(\frac95\right)=8
$$

$$
x=\frac{40}{5}-\frac{27}{5}
$$

$$
\boxed{x=\frac{13}{5}}
$$

Therefore:

$$
\boxed{x=\begin{pmatrix}\frac{13}{5}\\[2pt]\frac95\end{pmatrix}}
$$

## Comparison

Both methods give the same solution:

$$
\boxed{x=\frac{13}{5},\qquad y=\frac95}
$$

For this particular system, Gaussian elimination is simpler because it solves the equations directly without requiring a separate inverse calculation. The inverse method is useful when the inverse is already known or when solving several systems with the same matrix \(A\).
