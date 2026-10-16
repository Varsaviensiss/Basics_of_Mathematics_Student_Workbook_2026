# Exercise 2 — Gaussian Elimination: One Solution

## Problem

Solve the following system of linear equations using Gaussian elimination:

\[
\begin{cases}
x+y+z=6,\\
2x-y+z=3,\\
x+2y-z=2.
\end{cases}
\]

After finding the solution, substitute it into all three original equations to verify consistency.

---

## Step 1 — Write the Augmented Matrix

The system can be represented by the following augmented matrix:

\[
\left[
\begin{array}{ccc|c}
1&1&1&6\\
2&-1&1&3\\
1&2&-1&2
\end{array}
\right]
\]

The first three columns contain the coefficients of \(x\), \(y\), and \(z\). The last column contains the right-hand side constants.

## Step 2 — Eliminate the First Column

Use the first row as the pivot row.

Apply the row operations:

\[
R_2\leftarrow R_2-2R_1
\]

\[
R_3\leftarrow R_3-R_1
\]

The augmented matrix becomes

\[
\left[
\begin{array}{ccc|c}
1&1&1&6\\
0&-3&-1&-9\\
0&1&-2&-4
\end{array}
\right]
\]

The first column now contains zeros below the pivot.

## Step 3 — Eliminate the Second Column

To avoid fractions, use the operation

\[
R_3\leftarrow 3R_3+R_2.
\]

This gives

\[
\left[
\begin{array}{ccc|c}
1&1&1&6\\
0&-3&-1&-9\\
0&0&-7&-21
\end{array}
\right]
\]

The matrix is now in **row-echelon form**, so we can solve the system using back-substitution.

## Step 4 — Back-Substitution

From the third row:

\[
-7z=-21
\]

\[
\boxed{z=3}
\]

From the second row:

\[
-3y-z=-9
\]

Substitute \(z=3\):

\[
-3y-3=-9
\]

\[
-3y=-6
\]

\[
\boxed{y=2}
\]

From the first row:

\[
x+y+z=6
\]

Substitute \(y=2\) and \(z=3\):

\[
x+2+3=6
\]

\[
\boxed{x=1}
\]

Therefore, the solution is

\[
\boxed{(x,y,z)=(1,2,3)}
\]

## Step 5 — Verify the Solution

Substitute \(x=1\), \(y=2\), and \(z=3\) into each original equation.

**Equation 1**

\[
x+y+z=6
\]

\[
1+2+3=6\quad\checkmark
\]

**Equation 2**

\[
2x-y+z=3
\]

\[
2(1)-2+3=3\quad\checkmark
\]

**Equation 3**

\[
x+2y-z=2
\]

\[
1+2(2)-3=2\quad\checkmark
\]

All three equations are satisfied.

---

## Final Answer

\[
\boxed{x=1,\qquad y=2,\qquad z=3}
\]

The solution satisfies every original equation, confirming that the system is consistent.

**Conclusion:** Gaussian elimination transforms the augmented matrix into row-echelon form, allowing the unknowns to be found by back-substitution. Substitution into the original equations provides an independent check of the result.
