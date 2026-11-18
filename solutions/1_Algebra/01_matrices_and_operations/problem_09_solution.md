# Exercise 9. Composing Transformations

Given

$$
S=\begin{pmatrix}2&0\\0&1\end{pmatrix},
\qquad
R=\begin{pmatrix}0&-1\\1&0\end{pmatrix},
\qquad
x=\begin{pmatrix}1\\2\end{pmatrix},
$$

compute $RSx$ and $SRx$, compare the results, and explain geometrically why the order matters.

## 1. Compute $RSx$

First apply $S$ to $x$. Each component is the dot product of a row of $S$ with $x$:

$$
Sx
=\begin{pmatrix}2\cdot1+0\cdot2\\0\cdot1+1\cdot2\end{pmatrix}
=\begin{pmatrix}2\\2\end{pmatrix}.
$$

Then apply $R$ to the resulting vector:

$$
RSx=R(Sx)
=\begin{pmatrix}0\cdot2-1\cdot2\\1\cdot2+0\cdot2\end{pmatrix}
=\begin{pmatrix}-2\\2\end{pmatrix}.
$$

## 2. Compute $SRx$

First apply $R$ to $x$:

$$
Rx
=\begin{pmatrix}0\cdot1-1\cdot2\\1\cdot1+0\cdot2\end{pmatrix}
=\begin{pmatrix}-2\\1\end{pmatrix}.
$$

Then apply $S$ to the resulting vector:

$$
SRx=S(Rx)
=\begin{pmatrix}2\cdot(-2)+0\cdot1\\0\cdot(-2)+1\cdot1\end{pmatrix}
=\begin{pmatrix}-4\\1\end{pmatrix}.
$$

## 3. Compare the Results

The results are different, so $RSx\ne SRx$.

## 4. Geometric Explanation

The matrix $S$ doubles the horizontal coordinate and leaves the vertical coordinate unchanged. The matrix $R$ rotates a vector $90^\circ$ counterclockwise.

If we scale first, the doubled horizontal coordinate becomes the vertical coordinate after rotation. If we rotate first, the original vertical coordinate becomes the new horizontal coordinate with its sign reversed, and $S$ then doubles it. This is why the two orders give different results.
