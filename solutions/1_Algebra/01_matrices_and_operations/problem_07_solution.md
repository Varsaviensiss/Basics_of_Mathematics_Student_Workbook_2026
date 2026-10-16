# Exercise 7. Identity Matrix, Zero Matrix, and Powers

Given:

$$
A=\begin{pmatrix}2&1\\0&2\end{pmatrix}
$$

## 1. Compute \(AI\) and \(IA\)

The identity matrix is

$$
I=\begin{pmatrix}1&0\\0&1\end{pmatrix}
$$

Multiplying a matrix by the identity matrix does not change the matrix.

$$
AI=\begin{pmatrix}2&1\\0&2\end{pmatrix}
\begin{pmatrix}1&0\\0&1\end{pmatrix}
=\boxed{\begin{pmatrix}2&1\\0&2\end{pmatrix}}
$$

Similarly,

$$
IA=\begin{pmatrix}1&0\\0&1\end{pmatrix}
\begin{pmatrix}2&1\\0&2\end{pmatrix}
=\boxed{\begin{pmatrix}2&1\\0&2\end{pmatrix}}
$$

Therefore, \(AI=IA=A\).

## 2. Compute \(A+0\)

The zero matrix is

$$
0=\begin{pmatrix}0&0\\0&0\end{pmatrix}
$$

Adding the zero matrix does not change the original matrix.

$$
A+0=
\begin{pmatrix}2&1\\0&2\end{pmatrix}
+\begin{pmatrix}0&0\\0&0\end{pmatrix}
$$

Therefore,

$$
\boxed{A+0=\begin{pmatrix}2&1\\0&2\end{pmatrix}}
$$

## 3. Compute \(A^2\)

By definition, \(A^2=A\cdot A\).

$$
A^2=
\begin{pmatrix}2&1\\0&2\end{pmatrix}
\begin{pmatrix}2&1\\0&2\end{pmatrix}
$$

Multiplying the matrices:

$$
A^2=
\begin{pmatrix}
2(2)+1(0)&2(1)+1(2)\\
0(2)+2(0)&0(1)+2(2)
\end{pmatrix}
$$

Therefore,

$$
\boxed{A^2=\begin{pmatrix}4&4\\0&4\end{pmatrix}}
$$

## 4. Compute \(A^3\)

By definition, \(A^3=A^2A\).

$$
A^3=
\begin{pmatrix}4&4\\0&4\end{pmatrix}
\begin{pmatrix}2&1\\0&2\end{pmatrix}
$$

Multiplying the matrices:

$$
A^3=
\begin{pmatrix}
4(2)+4(0)&4(1)+4(2)\\
0(2)+4(0)&0(1)+4(2)
\end{pmatrix}
$$

Therefore,

$$
\boxed{A^3=\begin{pmatrix}8&12\\0&8\end{pmatrix}}
$$

## 5. Explain the Roles of \(I\) and \(0\)

The identity matrix \(I\) is the multiplicative identity because multiplying a matrix by \(I\) leaves it unchanged: \(AI=IA=A\).

The zero matrix \(0\) is the additive identity because adding it to a matrix leaves the matrix unchanged: \(A+0=A\).

## 6. Pattern in Successive Powers of \(A\)

The first three powers are

$$
A=\begin{pmatrix}2&1\\0&2\end{pmatrix}
$$

$$
A^2=\begin{pmatrix}4&4\\0&4\end{pmatrix}
$$

$$
A^3=\begin{pmatrix}8&12\\0&8\end{pmatrix}
$$

The diagonal entries double with each successive power: \(2,4,8\). The bottom-left entry remains zero, while the top-right entry follows the pattern \(1,4,12\).

In general, the pattern is

$$
\boxed{A^n=\begin{pmatrix}2^n&n2^{n-1}\\0&2^n\end{pmatrix}}
$$

This formula shows the regular pattern in the successive powers of \(A\).

## Conclusion

The identity matrix leaves a matrix unchanged under multiplication, while the zero matrix leaves a matrix unchanged under addition. The powers of \(A\) follow a regular pattern: the diagonal entries are \(2^n\), and the top-right entry is \(n2^{n-1}\).
