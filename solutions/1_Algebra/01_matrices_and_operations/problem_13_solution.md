# Exercise 13. A Recurrence Written in Matrix Form

Given:

$$
F=\begin{pmatrix}1&1\\1&0\end{pmatrix}
$$

## 1. Compute \(F^2\)

$$
F^2=F\cdot F
=\begin{pmatrix}1&1\\1&0\end{pmatrix}
\begin{pmatrix}1&1\\1&0\end{pmatrix}
$$

Therefore,

$$
\boxed{F^2=\begin{pmatrix}2&1\\1&1\end{pmatrix}}
$$

## 2. Compute \(F^3\)

$$
F^3=F^2F
=\begin{pmatrix}2&1\\1&1\end{pmatrix}
\begin{pmatrix}1&1\\1&0\end{pmatrix}
$$

Therefore,

$$
\boxed{F^3=\begin{pmatrix}3&2\\2&1\end{pmatrix}}
$$

## 3. Compute \(F^4\)

$$
F^4=F^3F
=\begin{pmatrix}3&2\\2&1\end{pmatrix}
\begin{pmatrix}1&1\\1&0\end{pmatrix}
$$

Therefore,

$$
\boxed{F^4=\begin{pmatrix}5&3\\3&2\end{pmatrix}}
$$

## 4. Compute \(F^5\)

$$
F^5=F^4F
=\begin{pmatrix}5&3\\3&2\end{pmatrix}
\begin{pmatrix}1&1\\1&0\end{pmatrix}
$$

Therefore,

$$
\boxed{F^5=\begin{pmatrix}8&5\\5&3\end{pmatrix}}
$$

## 5. Relationship with the Fibonacci Sequence

The Fibonacci sequence is

$$
0,1,1,2,3,5,8,13,\ldots
$$

Each term is the sum of the two previous terms. The matrix powers contain consecutive Fibonacci numbers:

$$
F^2=\begin{pmatrix}2&1\\1&1\end{pmatrix}
$$

$$
F^3=\begin{pmatrix}3&2\\2&1\end{pmatrix},
\quad
F^4=\begin{pmatrix}5&3\\3&2\end{pmatrix}
$$

$$
F^5=\begin{pmatrix}8&5\\5&3\end{pmatrix}
$$

Thus, the entries of the powers of \(F\) follow the Fibonacci sequence.

In general,

$$
F^n=\begin{pmatrix}
F_{n+1}&F_n\\
F_n&F_{n-1}
\end{pmatrix}
$$

where \(F_0=0\), \(F_1=1\), and \(F_n=F_{n-1}+F_{n-2}\).

## 6. Compute \(F\begin{pmatrix}a\\b\end{pmatrix}\)

Multiplying the matrix by the vector gives

$$
F\begin{pmatrix}a\\b\end{pmatrix}
=
\begin{pmatrix}1&1\\1&0\end{pmatrix}
\begin{pmatrix}a\\b\end{pmatrix}
$$

Therefore,

$$
\boxed{
F\begin{pmatrix}a\\b\end{pmatrix}
=\begin{pmatrix}a+b\\a\end{pmatrix}
}
$$

The new vector contains the sum \(a+b\) as its first entry and keeps \(a\) as its second entry.

## Conclusion

Multiplication by \(F\) performs one step of the Fibonacci recurrence. It adds two consecutive terms to produce the next term and shifts the previous term into the second position. Repeated multiplication by \(F\) generates successive Fibonacci numbers.
