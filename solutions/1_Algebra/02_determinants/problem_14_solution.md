# Exercise 14. A System of Equations and the Determinant

Consider the system

$$
Ax=b
$$

where

$$
A=
\begin{pmatrix}
1 & 2\\
k & 4
\end{pmatrix}
$$

We need to determine the values of \(k\) for which the system has exactly one solution for every \(b\). For the remaining value, we will give examples of right-hand sides that produce infinitely many solutions and no solution, respectively.

## 1. Find the determinant of \(A\)

For a \(2\times2\) matrix,

$$
\det(A)=ad-bc
$$

Therefore,

$$
\det(A)=(1)(4)-(2)(k)
$$

$$
\det(A)=4-2k
$$

## 2. Determine when the system has exactly one solution

A square linear system \(Ax=b\) has exactly one solution for every \(b\) if and only if \(A\) is invertible.

A matrix is invertible if and only if its determinant is nonzero:

$$
\det(A)\neq0
$$

Substitute the determinant:

$$
4-2k\neq0
$$

$$
-2k\neq-4
$$

$$
k\neq2
$$

Therefore, the system has exactly one solution for every \(b\) when

$$
\boxed{k\neq2}
$$

## 3. Analyze the remaining value \(k=2\)

When \(k=2\), the matrix becomes

$$
A=
\begin{pmatrix}
1 & 2\\
2 & 4
\end{pmatrix}
$$

The system \(Ax=b\), with \(x=(x_1,x_2)^T\) and \(b=(b_1,b_2)^T\), is

$$
\begin{cases}
x_1+2x_2=b_1\\
2x_1+4x_2=b_2
\end{cases}
$$

The second equation has a left-hand side that is twice the first equation's left-hand side.

For the system to be consistent, its right-hand sides must satisfy

$$
b_2=2b_1
$$

There are two possibilities.

### Case A: Infinitely many solutions

Choose

$$
b=
\begin{pmatrix}
1\\
2
\end{pmatrix}
$$

The system becomes

$$
\begin{cases}
x_1+2x_2=1\\
2x_1+4x_2=2
\end{cases}
$$

The second equation is twice the first, so the two equations represent the same line.

From the first equation,

$$
x_1+2x_2=1
$$

$$
x_1=1-2x_2
$$

Let \(x_2=t\), where \(t\in\mathbb{R}\). Then

$$
x_1=1-2t
$$

Hence, the solutions are

$$
\begin{pmatrix}
x_1\\
x_2
\end{pmatrix}
=
\begin{pmatrix}
1-2t\\
t
\end{pmatrix},
\qquad t\in\mathbb{R}
$$

Therefore,

$$
\boxed{\text{Infinitely many solutions}}
$$

### Case B: No solution

Choose

$$
b=
\begin{pmatrix}
1\\
3
\end{pmatrix}
$$

The system becomes

$$
\begin{cases}
x_1+2x_2=1\\
2x_1+4x_2=3
\end{cases}
$$

Multiplying the first equation by \(2\) gives

$$
2x_1+4x_2=2
$$

But the second equation requires

$$
2x_1+4x_2=3
$$

This is a contradiction because

$$
2\neq3
$$

Therefore,

$$
\boxed{\text{No solution}}
$$

## Final Answers

- **Exactly one solution for every \(b\):**

$$
\boxed{k\neq2}
$$

- **When \(k=2\), an example with infinitely many solutions:**

$$
\boxed{b=\begin{pmatrix}1\\2\end{pmatrix}}
$$

- **When \(k=2\), an example with no solution:**

$$
\boxed{b=\begin{pmatrix}1\\3\end{pmatrix}}
$$

The determinant explains the distinction:

$$
\det(A)=4-2k
$$

When \(k\neq2\), the determinant is nonzero and the system has a unique solution for every \(b\). When \(k=2\), the determinant is zero, and the system may have infinitely many solutions or no solution, depending on \(b\).
