# Exercise 3 — Inconsistent System of Linear Equations

> **Topic:** Linear Algebra  
> **Method:** Gaussian Elimination  
> **Objective:** Determine whether a system has a solution and identify a contradiction using an augmented matrix.

---

## 1. Problem Statement

Consider the following system of linear equations:

\[
\begin{cases}
x+2y=3,\\
2x+4y=7.
\end{cases}
\]

Determine whether the system has a solution. If it is inconsistent, show how the contradiction appears during Gaussian elimination and explain its meaning.

### Given Information

| Property | Description |
|:--|:--|
| Number of equations | 2 |
| Number of unknowns | 2 |
| Unknown variables | \(x,y\) |
| Required method | Gaussian elimination |
| Expected outcome | Consistent or inconsistent system |

---

## 2. Step 1 — Construct the Augmented Matrix

The coefficients of \(x\) and \(y\) form the first two columns. The constants form the last column.

\[
\left[
\begin{array}{cc|c}
1&2&3\\
2&4&7
\end{array}
\right]
\]

---

## 3. Step 2 — Apply Gaussian Elimination

Eliminate the first entry of the second row using the operation

\[
R_2\leftarrow R_2-2R_1.
\]

The calculation for the second row is

\[
(2,\ 4\mid 7)-2(1,\ 2\mid 3)
=(0,\ 0\mid 1).
\]

Therefore, the augmented matrix becomes

\[
\boxed{
\left[
\begin{array}{cc|c}
1&2&3\\
0&0&1
\end{array}
\right]
}
\]

The second row represents the equation

\[
\boxed{0x+0y=1}
\]

or, equivalently,

\[
\boxed{0=1}.
\]

This is a contradiction because zero can never equal one.

---

## 4. Step 3 — Interpret the Contradiction

The original equations are

\[
x+2y=3
\]

and

\[
2x+4y=7.
\]

The left-hand side of the second equation is exactly twice the left-hand side of the first equation:

\[
2(x+2y)=2x+4y.
\]

Therefore, if both equations were consistent, the right-hand side would also have to double:

\[
2(3)=6.
\]

However, the second equation requires the same expression to equal \(7\), not \(6\).

| First equation multiplied by 2 | Second equation |
|:--|:--|
| \(2x+4y=6\) | \(2x+4y=7\) |
| Required constant: \(6\) | Given constant: \(7\) |
| The equations disagree | Contradiction |

The two equations describe parallel lines with different intercepts. Consequently, they cannot intersect.

---

## 5. Final Result

\[
\boxed{\text{The system is inconsistent.}}
\]

| Question | Answer |
|:--|:--|
| Does a solution exist? | No |
| What contradiction appears? | \(0=1\) |
| Why is the system inconsistent? | The equations require the same expression to equal two different constants. |
| Number of solutions | \(0\) |

**Conclusion:** Gaussian elimination produces a row of the form \([0\quad 0\mid 1]\), which represents the impossible equation \(0=1\). Therefore, the system has no solution.

---

*End of Exercise 3.*
