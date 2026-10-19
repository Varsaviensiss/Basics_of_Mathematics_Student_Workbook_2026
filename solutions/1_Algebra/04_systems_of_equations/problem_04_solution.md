# Exercise 4. Infinitely Many Solutions

Given:

$$
\begin{cases}
x+y+z=2,\\
2x+2y+2z=4,\\
x-y+z=0.
\end{cases}
$$

## Step 1. Write the augmented matrix

$$
\left[
\begin{array}{ccc|c}
1&1&1&2\\
2&2&2&4\\
1&-1&1&0
\end{array}
\right]
$$

## Step 2. Eliminate entries below the first pivot

Apply:

$$
R_2\leftarrow R_2-2R_1
$$

$$
R_3\leftarrow R_3-R_1
$$

Then:

$$
\left[
\begin{array}{ccc|c}
1&1&1&2\\
0&0&0&0\\
0&-2&0&-2
\end{array}
\right]
$$

Swap rows 2 and 3:

$$
\left[
\begin{array}{ccc|c}
1&1&1&2\\
0&-2&0&-2\\
0&0&0&0
\end{array}
\right]
$$

Divide row 2 by \(-2\):

$$
R_2\leftarrow-\frac12R_2
$$

$$
\left[
\begin{array}{ccc|c}
1&1&1&2\\
0&1&0&1\\
0&0&0&0
\end{array}
\right]
$$

## Step 3. Express the variables

The second row gives:

$$
y=1
$$

The first row gives:

$$
x+y+z=2
$$

Substitute \(y=1\):

$$
x+1+z=2
$$

$$
x+z=1
$$

Choose the free variable:

$$
z=t,\qquad t\in\mathbb{R}
$$

Then:

$$
x=1-t
$$

Therefore, the parametric solution is:

$$
\boxed{
(x,y,z)=(1-t,1,t),\qquad t\in\mathbb{R}
}
$$

## Step 4. Check one parameter value

Choose \(t=0\). Then:

$$
(x,y,z)=(1,1,0)
$$

Check the first equation:

$$
1+1+0=2
$$

Check the second equation:

$$
2(1)+2(1)+2(0)=4
$$

Check the third equation:

$$
1-1+0=0
$$

All three equations are satisfied.

## Conclusion

The system has infinitely many solutions because one variable is free and the system contains no contradictory row.
