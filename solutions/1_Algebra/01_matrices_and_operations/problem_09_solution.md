# Exercise 9. Composing Transformations

Given:

$$
S=\begin{pmatrix}2&0\\0&1\end{pmatrix},
\qquad
R=\begin{pmatrix}0&-1\\1&0\end{pmatrix},
\qquad
x=\begin{pmatrix}1\\2\end{pmatrix}
$$

## 1. Compute \(RSx\)

First, calculate \(Sx\):

$$
Sx=
\begin{pmatrix}2&0\\0&1\end{pmatrix}
\begin{pmatrix}1\\2\end{pmatrix}
=\begin{pmatrix}2\\2\end{pmatrix}
$$

Next, multiply by \(R\):

$$
RSx=
\begin{pmatrix}0&-1\\1&0\end{pmatrix}
\begin{pmatrix}2\\2\end{pmatrix}
=\begin{pmatrix}-2\\2\end{pmatrix}
$$

Therefore,

$$
\boxed{RSx=\begin{pmatrix}-2\\2\end{pmatrix}}
$$

## 2. Compute \(SRx\)

First, calculate \(Rx\):

$$
Rx=
\begin{pmatrix}0&-1\\1&0\end{pmatrix}
\begin{pmatrix}1\\2\end{pmatrix}
=\begin{pmatrix}-2\\1\end{pmatrix}
$$

Next, multiply by \(S\):

$$
SRx=
\begin{pmatrix}2&0\\0&1\end{pmatrix}
\begin{pmatrix}-2\\1\end{pmatrix}
=\begin{pmatrix}-4\\1\end{pmatrix}
$$

Therefore,

$$
\boxed{SRx=\begin{pmatrix}-4\\1\end{pmatrix}}
$$

## 3. Compare the Results

The results are different:

$$
RSx=\begin{pmatrix}-2\\2\end{pmatrix},
\qquad
SRx=\begin{pmatrix}-4\\1\end{pmatrix}
$$

Thus, \(RSx\ne SRx\).

## 4. Geometric Explanation

The matrix \(S\) doubles the horizontal coordinate and leaves the vertical coordinate unchanged. The matrix \(R\) rotates a vector by \(90^\circ\) counterclockwise.

When we scale first and then rotate, we obtain \((-2,2)\). When we rotate first and then scale, we obtain \((-4,1)\).

The order matters because the scaling is nonuniform. Rotating the vector first changes its coordinates before the scaling is applied, producing a different final result.

## Conclusion

This example shows that matrix multiplication represents the composition of transformations. Changing the order of transformations can change the final result.
