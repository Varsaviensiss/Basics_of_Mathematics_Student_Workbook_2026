# Exercise 12. Formula for a Matrix Power

Given:

$$
A=\begin{pmatrix}1&1\\0&1\end{pmatrix}
$$

## 1. Compute \(A^2\)

$$
A^2=A\cdot A
=\begin{pmatrix}1&1\\0&1\end{pmatrix}
\begin{pmatrix}1&1\\0&1\end{pmatrix}
$$

Therefore,

$$
\boxed{A^2=\begin{pmatrix}1&2\\0&1\end{pmatrix}}
$$

## 2. Compute \(A^3\)

$$
A^3=A^2A
=\begin{pmatrix}1&2\\0&1\end{pmatrix}
\begin{pmatrix}1&1\\0&1\end{pmatrix}
$$

Therefore,

$$
\boxed{A^3=\begin{pmatrix}1&3\\0&1\end{pmatrix}}
$$

## 3. Compute \(A^4\)

$$
A^4=A^3A
=\begin{pmatrix}1&3\\0&1\end{pmatrix}
\begin{pmatrix}1&1\\0&1\end{pmatrix}
$$

Therefore,

$$
\boxed{A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix}}
$$

## 4. Formulate a Conjecture for \(A^n\)

The first powers are

$$
A^2=\begin{pmatrix}1&2\\0&1\end{pmatrix},
\quad
A^3=\begin{pmatrix}1&3\\0&1\end{pmatrix},
\quad
A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix}
$$

The diagonal entries remain \(1\), the bottom-left entry remains \(0\), and the top-right entry equals the exponent.

Therefore, we conjecture that

$$
\boxed{A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}}
$$

for every positive integer \(n\).

## 5. Prove the Formula by Mathematical Induction

**Base case:** For \(n=1\),

$$
A^1=\begin{pmatrix}1&1\\0&1\end{pmatrix}
=\begin{pmatrix}1&1\\0&1\end{pmatrix}
$$

Thus, the formula is true for \(n=1\).

**Inductive hypothesis:** Assume the formula is true for some positive integer \(n\):

$$
A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}
$$

**Inductive step:** Multiply both sides by \(A\):

$$
A^{n+1}=A^nA
$$

Substituting the assumed formula gives

$$
A^{n+1}=
\begin{pmatrix}1&n\\0&1\end{pmatrix}
\begin{pmatrix}1&1\\0&1\end{pmatrix}
$$

Multiplying the matrices:

$$
A^{n+1}=
\begin{pmatrix}
1&1+n\\
0&1
\end{pmatrix}
$$

Therefore,

$$
A^{n+1}=\begin{pmatrix}1&n+1\\0&1\end{pmatrix}
$$

This is exactly the same formula with \(n+1\) replacing \(n\).

By mathematical induction, the formula holds for every positive integer \(n\).

## Conclusion

The general formula for the powers of \(A\) is

$$
\boxed{A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}}
$$

The formula follows from the observed pattern and is proved using mathematical induction.
