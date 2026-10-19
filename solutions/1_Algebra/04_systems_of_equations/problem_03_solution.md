# Exercise 3. Inconsistent System

Given:

$$
\begin{cases}
x+2y=3,\\
2x+4y=7.
\end{cases}
$$

## Step 1. Write the augmented matrix

$$
\left[
\begin{array}{cc|c}
1&2&3\\
2&4&7
\end{array}
\right]
$$

## Step 2. Eliminate the first entry in row 2

Apply:

$$
R_2\leftarrow R_2-2R_1
$$

Then:

$$
\left[
\begin{array}{cc|c}
1&2&3\\
0&0&1
\end{array}
\right]
$$

The second row represents:

$$
0x+0y=1
$$

Therefore:

$$
\boxed{0=1}
$$

This is a contradiction.

## Step 3. Interpret the contradiction

The first equation is:

$$
x+2y=3
$$

Multiplying it by \(2\) gives:

$$
2x+4y=6
$$

However, the second equation requires:

$$
2x+4y=7
$$

The same expression cannot equal both \(6\) and \(7\).

## Conclusion

The system is inconsistent and has no solution.

$$
\boxed{\text{No solution}}
$$

In Gaussian elimination, a row of the form \([0\quad0\mid c]\), where \(c\neq0\), indicates inconsistency.
