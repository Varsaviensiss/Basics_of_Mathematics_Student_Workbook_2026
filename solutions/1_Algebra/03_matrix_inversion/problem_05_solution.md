# Exercise 5. Inverse of a \(3\times3\) Matrix

Given:

$$
A=\begin{pmatrix}
1&1&0\\
0&1&1\\
1&0&1
\end{pmatrix}
$$

Start with the augmented matrix \([A\mid I]\).

$$
\left[
\begin{array}{ccc|ccc}
1&1&0&1&0&0\\
0&1&1&0&1&0\\
1&0&1&0&0&1
\end{array}
\right]
$$

## Step 1. Eliminate the first entry in row 3

Apply:

$$
R_3\leftarrow R_3-R_1
$$

$$
\left[
\begin{array}{ccc|ccc}
1&1&0&1&0&0\\
0&1&1&0&1&0\\
0&-1&1&-1&0&1
\end{array}
\right]
$$

## Step 2. Eliminate the second entry in row 3

Apply:

$$
R_3\leftarrow R_3+R_2
$$

$$
\left[
\begin{array}{ccc|ccc}
1&1&0&1&0&0\\
0&1&1&0&1&0\\
0&0&2&-1&1&1
\end{array}
\right]
$$

## Step 3. Make the third pivot equal to 1

Apply:

$$
R_3\leftarrow \frac12R_3
$$

$$
\left[
\begin{array}{ccc|ccc}
1&1&0&1&0&0\\
0&1&1&0&1&0\\
0&0&1&-\frac12&\frac12&\frac12
\end{array}
\right]
$$

## Step 4. Eliminate the third-column entries above the pivot

Apply:

$$
R_2\leftarrow R_2-R_3
$$

$$
\left[
\begin{array}{ccc|ccc}
1&1&0&1&0&0\\
0&1&0&\frac12&\frac12&-\frac12\\
0&0&1&-\frac12&\frac12&\frac12
\end{array}
\right]
$$

## Step 5. Eliminate the second-column entry in row 1

Apply:

$$
R_1\leftarrow R_1-R_2
$$

$$
\left[
\begin{array}{ccc|ccc}
1&0&0&\frac12&-\frac12&\frac12\\
0&1&0&\frac12&\frac12&-\frac12\\
0&0&1&-\frac12&\frac12&\frac12
\end{array}
\right]
$$

Thus:

$$
\boxed{
A^{-1}=\frac12
\begin{pmatrix}
1&-1&1\\
1&1&-1\\
-1&1&1
\end{pmatrix}
}
$$

## Step 6. Verify by multiplication

$$
AA^{-1}
=
\frac12
\begin{pmatrix}
1&1&0\\
0&1&1\\
1&0&1
\end{pmatrix}
\begin{pmatrix}
1&-1&1\\
1&1&-1\\
-1&1&1
\end{pmatrix}
$$

$$
=\frac12
\begin{pmatrix}
2&0&0\\
0&2&0\\
0&0&2
\end{pmatrix}
$$

$$
\boxed{AA^{-1}=I}
$$

The inverse is correct.
