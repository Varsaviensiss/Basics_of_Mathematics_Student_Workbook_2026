# Exercise 6. A System with a Parameter

Given:

$$
\begin{cases}
x+y=2,\\
ax+ay=4.
\end{cases}
$$

## Step 1. Write the augmented matrix

$$
\left[
\begin{array}{cc|c}
1&1&2\\
a&a&4
\end{array}
\right]
$$

Apply the row operation:

$$
R_2\leftarrow R_2-aR_1
$$

Then:

$$
\left[
\begin{array}{cc|c}
1&1&2\\
0&0&4-2a
\end{array}
\right]
$$

The second row represents:

$$
0=4-2a
$$

## Case 1. \(a=2\)

Then:

$$
4-2a=4-4=0
$$

The second row becomes \(0=0\), so the two equations are equivalent.

The remaining equation is:

$$
x+y=2
$$

Let \(y=t\). Then:

$$
x=2-t
$$

Thus:

$$
\boxed{(x,y)=(2-t,t),\qquad t\in\mathbb{R}}
$$

There are infinitely many solutions.

## Case 2. \(a\neq2\)

Then:

$$
4-2a\neq0
$$

The second row represents a contradiction:

$$
0=4-2a
$$

Therefore, the system has no solution.

This includes \(a=0\), when the second equation becomes \(0=4\).

## Conclusion

- If \(a=2\), there are infinitely many solutions.
- If \(a\neq2\), there is no solution.
- There is no value of \(a\) for which the system has exactly one solution, because the two equations always have proportional coefficient rows.
