# Exercise 1. From a System to a Matrix

Given the system:

$$
\begin{cases}
2x-y+z=4,\\
x+3y-2z=1,\\
3x+y+z=7.
\end{cases}
$$

## Step 1. Identify the coefficient matrix

The coefficient matrix contains the coefficients of \(x\), \(y\), and \(z\) in each equation, in the same order.

$$
\boxed{
A=\begin{pmatrix}
2&-1&1\\
1&3&-2\\
3&1&1
\end{pmatrix}
}
$$

Each row corresponds to one equation:

- Row 1: \(2x-y+z=4\)
- Row 2: \(x+3y-2z=1\)
- Row 3: \(3x+y+z=7\)

## Step 2. Identify the vector of unknowns

$$
\boxed{
\mathbf{x}=\begin{pmatrix}x\\y\\z\end{pmatrix}
}
$$

## Step 3. Identify the right-hand side vector

The right-hand side vector contains the constants from the equations.

$$
\boxed{
\mathbf{b}=\begin{pmatrix}4\\1\\7\end{pmatrix}
}
$$

## Step 4. Write the system in matrix form

The system can now be written as:

$$
\boxed{A\mathbf{x}=\mathbf{b}}
$$

Explicitly:

$$
\begin{pmatrix}
2&-1&1\\
1&3&-2\\
3&1&1
\end{pmatrix}
\begin{pmatrix}x\\y\\z\end{pmatrix}
=
\begin{pmatrix}4\\1\\7\end{pmatrix}
$$

## Conclusion

The matrix equation \(A\mathbf{x}=\mathbf{b}\) represents the original system because matrix multiplication produces the left-hand side of each equation, while \(\mathbf{b}\) contains the corresponding constants.
