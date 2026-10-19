# Exercise 2. Gaussian Elimination — One Solution

Given:

$$
\begin{cases}
x+y+z=6,\\
2x-y+z=3,\\
x+2y-z=2.
\end{cases}
$$

## Step 1. Write the augmented matrix

$$
\left[
\begin{array}{ccc|c}
1&1&1&6\\
2&-1&1&3\\
1&2&-1&2
\end{array}
\right]
$$

## Step 2. Eliminate the entries below the first pivot

Apply:

$$
R_2\leftarrow R_2-2R_1
$$

$$
R_3\leftarrow R_3-R_1
$$

The augmented matrix becomes:

$$
\left[
\begin{array}{ccc|c}
1&1&1&6\\
0&-3&-1&-9\\
0&1&-2&-4
\end{array}
\right]
$$

Swap rows 2 and 3:

$$
R_2\leftrightarrow R_3
$$

$$
\left[
\begin{array}{ccc|c}
1&1&1&6\\
0&1&-2&-4\\
0&-3&-1&-9
\end{array}
\right]
$$

## Step 3. Eliminate the entry below the second pivot

Apply:

$$
R_3\leftarrow R_3+3R_2
$$

$$
\left[
\begin{array}{ccc|c}
1&1&1&6\\
0&1&-2&-4\\
0&0&-7&-21
\end{array}
\right]
$$

## Step 4. Use back-substitution

From the third row:

$$
-7z=-21
$$

$$
\boxed{z=3}
$$

From the second row:

$$
y-2z=-4
$$

Substitute \(z=3\):

$$
y-6=-4
$$

$$
\boxed{y=2}
$$

From the first row:

$$
x+y+z=6
$$

$$
x+2+3=6
$$

$$
\boxed{x=1}
$$

Therefore:

$$
\boxed{(x,y,z)=(1,2,3)}
$$

## Step 5. Verify the solution

First equation:

$$
1+2+3=6
$$

Second equation:

$$
2(1)-2+3=3
$$

Third equation:

$$
1+2(2)-3=2
$$

All three equations are satisfied. Therefore, the solution is correct and consistent.
