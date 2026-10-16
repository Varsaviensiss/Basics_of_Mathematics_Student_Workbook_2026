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

Next, apply the rotation matrix \(R\):

$$
RSx=
\begin{pmatrix}0&-1\\1&0\end{pmatrix}
\begin{pmatrix}2\\2\end{pmatrix}
$$

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

Next, apply the scaling matrix \(S\):

$$
SRx=
\begin{pmatrix}2&0\\0&1\end{pmatrix}
\begin{pmatrix}-2\\1\end{pmatrix}
$$

$$
\boxed{SRx=\begin{pmatrix}-4\\1\end{pmatrix}}
$$

## 3. Geometric Explanation

The results are different:

$$
RSx=\begin{pmatrix}-2\\2\end{pmatrix},
\qquad
SRx=\begin{pmatrix}-4\\1\end{pmatrix}
$$

When we apply scaling first and then rotation, the vector becomes \((-2,2)\). When we rotate first and then apply scaling, the vector becomes \((-4,1)\).

The order matters because the scaling is nonuniform: the horizontal coordinate is doubled, while the vertical coordinate remains unchanged. Rotating before scaling changes which coordinates are affected by the scaling.

Therefore, \(RSx\ne SRx\), showing that the order of transformations matters.

## Conclusion

Matrix multiplication represents composition of transformations. In general, changing the order of two transformations changes the final result.
