# Exercise 2 — Gaussian Elimination: One Solution

> **Topic:** Linear Algebra  
> **Method:** Gaussian Elimination and Back-Substitution  
> **Objective:** Solve a system of linear equations and verify the result.

---

## 1. Problem Statement

Solve the following system using Gaussian elimination.

\[
\begin{cases}
x+y+z=6\\
2x-y+z=3\\
x+2y-z=2
\end{cases}
\]

### Given Information

| Property | Description |
|:--|:--|
| Number of equations | 3 |
| Number of unknowns | 3 |
| Unknown variables | \(x,y,z\) |
| Required method | Gaussian elimination |
| Verification | Substitution into all original equations |

---

## 2. Step 1 — Construct the Augmented Matrix

Write the coefficients and constants in an augmented matrix.

\[
\left[
\begin{array}{ccc|c}
1&1&1&6\\
2&-1&1&3\\
1&2&-1&2
\end{array}
\right]
\]

The first three columns represent the coefficients of \(x\), \(y\), and \(z\). The last column contains the constants on the right-hand side.

---

## 3. Step 2 — Eliminate the First Column

Use the first row as the pivot row.

Apply the following row operations:

\[
R_2\leftarrow R_2-2R_1
\]

\[
R_3\leftarrow R_3-R_1
\]

The resulting matrix is

\[
\left[
\begin{array}{ccc|c}
1&1&1&6\\
0&-3&-1&-9\\
0&1&-2&-4
\end{array}
\right]
\]

### Row Operation Summary

| Operation | Purpose |
|:--|:--|
| \(R_2-2R_1\) | Eliminate the first entry of row 2 |
| \(R_3-R_1\) | Eliminate the first entry of row 3 |

---

## 4. Step 3 — Eliminate the Second Column

To eliminate the second entry in row 3, apply

\[
R_3\leftarrow 3R_3+R_2.
\]

This gives

\[
\boxed{
\left[
\begin{array}{ccc|c}
1&1&1&6\\
0&-3&-1&-9\\
0&0&-7&-21
\end{array}
\right]
}
\]

The matrix is now in **row-echelon form**. We can find the unknowns using back-substitution.

---

## 5. Step 4 — Back-Substitution

Starting from the last row, solve for each variable.

| Step | Equation | Result |
|:--|:--|:--|
| 1 | \(-7z=-21\) | \(z=3\) |
| 2 | \(-3y-z=-9\) | \(y=2\) |
| 3 | \(x+y+z=6\) | \(x=1\) |

### Detailed Calculations

**Find \(z\):**

\[
-7z=-21
\]

\[
z=\frac{-21}{-7}=\boxed{3}
\]

**Find \(y\):**

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
y=\boxed{2}
\]

**Find \(x\):**

\[
x+y+z=6
\]

Substitute \(y=2\) and \(z=3\):

\[
x+2+3=6
\]

\[
x=\boxed{1}
\]

---

## 6. Step 5 — Verification of the Solution

The calculated solution is

\[
(x,y,z)=(1,2,3).
\]

Substitute these values into every original equation.

| Equation | Substitution | Result | Status |
|:--|:--|:--:|:--:|
| \(x+y+z=6\) | \(1+2+3=6\) | \(6=6\) | ✓ |
| \(2x-y+z=3\) | \(2(1)-2+3=3\) | \(3=3\) | ✓ |
| \(x+2y-z=2\) | \(1+2(2)-3=2\) | \(2=2\) | ✓ |

All three equations are satisfied. Therefore, the solution is consistent with the original system.

---

## 7. Final Answer

\[
\boxed{x=1,\qquad y=2,\qquad z=3}
\]

| Variable | Solution |
|:--:|:--:|
| \(x\) | \(1\) |
| \(y\) | \(2\) |
| \(z\) | \(3\) |

**Conclusion:** Gaussian elimination transforms the augmented matrix into row-echelon form. Back-substitution gives the values of the unknowns, and substitution into the original equations confirms the result.

---

*End of Exercise 2.*
