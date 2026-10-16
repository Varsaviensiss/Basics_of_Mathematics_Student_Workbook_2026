# Exercise 15. Associativity of Multiplication and Different Calculation Paths

Given the matrices

$$
A=\begin{pmatrix}
1&2&0\\
0&1&1
\end{pmatrix},
\quad
B=\begin{pmatrix}
1&0\\
2&1\\
-1&3
\end{pmatrix},
\quad
C=\begin{pmatrix}
2&1\\
0&-1
\end{pmatrix}
$$

## Step 1: Calculate \((AB)C\)

First, multiply \(A\) and \(B\):

$$
AB=
\begin{pmatrix}
1&2&0\\
0&1&1
\end{pmatrix}
\begin{pmatrix}
1&0\\
2&1\\
-1&3
\end{pmatrix}
$$

$$
AB=
\begin{pmatrix}
5&2\\
1&4
\end{pmatrix}
$$

Next, multiply the result by \(C\):

$$
(AB)C=
\begin{pmatrix}
5&2\\
1&4
\end{pmatrix}
\begin{pmatrix}
2&1\\
0&-1
\end{pmatrix}
$$

$$
\boxed{(AB)C=
\begin{pmatrix}
10&3\\
2&-3
\end{pmatrix}}
$$

## Step 2: Calculate \(A(BC)\)

First, multiply \(B\) and \(C\):

$$
BC=
\begin{pmatrix}
1&0\\
2&1\\
-1&3
\end{pmatrix}
\begin{pmatrix}
2&1\\
0&-1
\end{pmatrix}
$$

$$
BC=
\begin{pmatrix}
2&1\\
4&1\\
-2&-4
\end{pmatrix}
$$

Next, multiply \(A\) by the result:

$$
A(BC)=
\begin{pmatrix}
1&2&0\\
0&1&1
\end{pmatrix}
\begin{pmatrix}
2&1\\
4&1\\
-2&-4
\end{pmatrix}
$$

$$
\boxed{A(BC)=
\begin{pmatrix}
10&3\\
2&-3
\end{pmatrix}}
$$

## Step 3: Compare the Results

Both calculation paths give the same result:

$$
\boxed{(AB)C=A(BC)=
\begin{pmatrix}
10&3\\
2&-3
\end{pmatrix}}
$$

Each path requires two matrix multiplications:
- First path: calculate \(AB\), then multiply by \(C\).
- Second path: calculate \(BC\), then multiply by \(A\).

Both paths use the same number of matrix multiplications, although the intermediate matrices are different.

## Conclusion

Associativity of matrix multiplication means that changing the grouping of the matrices does not change the final result:

$$
(AB)C=A(BC)
$$

In this example, we can multiply \(A\) and \(B\) first or \(B\) and \(C\) first. Both methods produce the same final matrix. However, associativity does not mean that matrix multiplication can be performed in any order; the order of the matrices must remain unchanged.
