# Exercise 4. Gauss–Jordan Elimination

Given:

$$
A=\begin{pmatrix}1&2\\3&5\end{pmatrix}
$$

To find \(A^{-1}\), start with the augmented matrix \([A\mid I]\) and use elementary row operations to transform the left side into the identity matrix.

## Step 1. Form the augmented matrix

$$
\left[
\begin{array}{cc|cc}
1&2&1&0\\
3&5&0&1
\end{array}
\right]
$$

## Step 2. Eliminate the entry below the first pivot

Apply:

$$
R_2\leftarrow R_2-3R_1
$$

Then:

$$
\left[
\begin{array}{cc|cc}
1&2&1&0\\
0&-1&-3&1
\end{array}
\right]
$$

## Step 3. Make the second pivot equal to 1

Apply:

$$
R_2\leftarrow -R_2
$$

Then:

$$
\left[
\begin{array}{cc|cc}
1&2&1&0\\
0&1&3&-1
\end{array}
\right]
$$

## Step 4. Eliminate the entry above the second pivot

Apply:

$$
R_1\leftarrow R_1-2R_2
$$

Then:

$$
\left[
\begin{array}{cc|cc}
1&0&-5&2\\
0&1&3&-1
\end{array}
\right]
$$

The left side is now the identity matrix. Therefore, the right side is the inverse:

$$
\boxed{
A^{-1}=\begin{pmatrix}-5&2\\3&-1\end{pmatrix}
}
$$

## Step 5. Verify the result

$$
AA^{-1}=
\begin{pmatrix}1&2\\3&5\end{pmatrix}
\begin{pmatrix}-5&2\\3&-1\end{pmatrix}
$$

$$
=
\begin{pmatrix}
-5+6&2-2\\
-15+15&6-5
\end{pmatrix}
$$

$$
=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I
$$

## Conclusion

Gauss–Jordan elimination transforms \([A\mid I]\) into \([I\mid A^{-1}]\). The same row operations applied to both sides preserve the corresponding matrix equation, so the right side becomes the inverse when the left side becomes \(I\).
