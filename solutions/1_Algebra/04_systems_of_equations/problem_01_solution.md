# Exercise 1 — From a System to a Matrix

## Problem

Write the following system of linear equations in the matrix form

\[
Ax=b.
\]

Given the system:

\[
\begin{cases}
2x-y+z=4,\\
x+3y-2z=1,\\
3x+y+z=7.
\end{cases}
\]

Identify the coefficient matrix \(A\), the vector of unknowns \(x\), and the right-hand side vector \(b\). Explain how each row of the matrix corresponds to one equation.

---

## Step 1 — Identify the Coefficients

First, write the coefficients of \(x\), \(y\), and \(z\) in each equation.

| Equation | \(x\) | \(y\) | \(z\) | Right-hand side |
|:--|--:|--:|--:|--:|
| \(2x-y+z=4\) | 2 | -1 | 1 | 4 |
| \(x+3y-2z=1\) | 1 | 3 | -2 | 1 |
| \(3x+y+z=7\) | 3 | 1 | 1 | 7 |

The coefficients are arranged row by row, following the order of the variables \(x\), \(y\), and \(z\).

## Step 2 — Construct the Coefficient Matrix

The coefficient matrix \(A\) contains the coefficients of the unknowns:

\[
\boxed{
A=
\begin{pmatrix}
2 & -1 & 1\\
1 & 3 & -2\\
3 & 1 & 1
\end{pmatrix}
}
\]

Each row represents one equation, and each column represents one variable.

## Step 3 — Define the Unknown Vector

The vector of unknowns contains the variables in the same order as the columns of \(A\):

\[
\boxed{
\mathbf{x}=
\begin{pmatrix}
x\\
y\\
z
\end{pmatrix}
}
\]

## Step 4 — Define the Right-Hand Side Vector

The right-hand side vector contains the constant terms from the original equations:

\[
\boxed{
\mathbf{b}=
\begin{pmatrix}
4\\
1\\
7
\end{pmatrix}
}
\]

## Step 5 — Write the Matrix Equation

Combining the three components gives the required matrix form:

\[
\boxed{
\underbrace{
\begin{pmatrix}
2 & -1 & 1\\
1 & 3 & -2\\
3 & 1 & 1
\end{pmatrix}
}_{A}
\underbrace{
\begin{pmatrix}
x\\
y\\
z
\end{pmatrix}
}_{\mathbf{x}}
=
\underbrace{
\begin{pmatrix}
4\\
1\\
7
\end{pmatrix}
}_{\mathbf{b}}
}
\]

Equivalently,

\[
\boxed{A\mathbf{x}=\mathbf{b}}
\]

## Explanation: How the Rows Correspond to the Equations

Matrix multiplication produces the following system:

\[
A\mathbf{x}
=
\begin{pmatrix}
2x-y+z\\
x+3y-2z\\
3x+y+z
\end{pmatrix}.
\]

Equating this vector to \(\mathbf{b}\) gives

\[
\begin{pmatrix}
2x-y+z\\
x+3y-2z\\
3x+y+z
\end{pmatrix}
=
\begin{pmatrix}
4\\
1\\
7
\end{pmatrix}.
\]

Therefore:

- **First row:** \(2x-y+z=4\)
- **Second row:** \(x+3y-2z=1\)
- **Third row:** \(3x+y+z=7\)

Each row of the coefficient matrix reproduces the coefficients of the corresponding equation, while the matching entry of \(\mathbf{b}\) supplies its constant term.

---

## Final Answer

The system in matrix form is

\[
\boxed{
\begin{pmatrix}
2 & -1 & 1\\
1 & 3 & -2\\
3 & 1 & 1
\end{pmatrix}
\begin{pmatrix}
x\\
y\\
z
\end{pmatrix}
=
\begin{pmatrix}
4\\
1\\
7
\end{pmatrix}
}
\]

where:

- \(A\) is the \(3\times3\) coefficient matrix.
- \(\mathbf{x}\) is the \(3\times1\) vector of unknowns.
- \(\mathbf{b}\) is the \(3\times1\) right-hand side vector.

**Conclusion:** Writing a system as \(A\mathbf{x}=\mathbf{b}\) organizes its coefficients, variables, and constants into a compact matrix representation without changing the original equations.
