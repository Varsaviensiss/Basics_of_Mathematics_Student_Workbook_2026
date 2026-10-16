# Exercise 4 — Infinitely Many Solutions

> **Topic:** Linear Algebra  
> **Method:** Gaussian Elimination  
> **Objective:** Find the parametric solution of a system with infinitely many solutions, identify a free variable, and verify one solution.

---

## 1. Problem Statement

Consider the following system of linear equations:

\[
\begin{cases}
x+y+z=2,\\
2x+2y+2z=4,\\
x-y+z=0.
\end{cases}
\]

Solve the system in parametric form, identify a free variable, and verify one chosen solution by substitution.

### Given Information

| Property | Description |
|:--|:--|
| Number of equations | 3 |
| Number of unknowns | 3 |
| Unknown variables | \(x,y,z\) |
| Required method | Gaussian elimination |
| Expected result | Parametric solution |

---

## 2. Step 1 — Construct the Augmented Matrix

Write the coefficients and constants in an augmented matrix:

\[
\left[
\begin{array}{ccc|c}
1&1&1&2\\
2&2&2&4\\
1&-1&1&0
\end{array}
\right]
\]

---

## 3. Step 2 — Apply Gaussian Elimination

First, eliminate the first entry of the second row:

\[
R_2\leftarrow R_2-2R_1
\]

Next, eliminate the first entry of the third row:

\[
R_3\leftarrow R_3-R_1
\]

The resulting matrix is

\[
\left[
\begin{array}{ccc|c}
1&1&1&2\\
0&0&0&0\\
0&-2&0&-2
\end{array}
\right]
\]

Swap the second and third rows:

\[
R_2\leftrightarrow R_3
\]

The matrix becomes

\[
\boxed{
\left[
\begin{array}{ccc|c}
1&1&1&2\\
0&-2&0&-2\\
0&0&0&0
\end{array}
\right]
}
\]

The second row gives \(y=1\), while the third row represents \(0=0\), which adds no new restriction.

---

## 4. Step 3 — Find the Free Variable

From the second row,

\[
-2y=-2
\]

Therefore,

\[
\boxed{y=1}
\]

The first row gives

\[
x+y+z=2.
\]

Substitute \(y=1\):

\[
x+1+z=2
\]

Hence,

\[
x+z=1
\]

There are three variables but only two independent equations. Therefore, one variable can be chosen freely.

Let

\[
\boxed{z=t,\qquad t\in\mathbb{R}}
\]

Then

\[
x=1-t.
\]

---

## 5. Step 4 — Write the Parametric Solution

The variables are

\[
x=1-t,\qquad y=1,\qquad z=t,
\]

where \(t\) can be any real number.

Thus, the solution in parametric form is

\[
\boxed{
(x,y,z)=(1-t,\ 1,\ t),\qquad t\in\mathbb{R}
}
\]

### Solution Summary

| Variable | Expression | Type |
|:--|:--|:--|
| \(x\) | \(1-t\) | Dependent variable |
| \(y\) | \(1\) | Fixed variable |
| \(z\) | \(t\) | Free variable |
| \(t\) | Any real number | Parameter |

Because \(t\) can take infinitely many real values, the system has infinitely many solutions.

---

## 6. Step 5 — Verify One Solution

Choose the parameter value

\[
t=0.
\]

The resulting point is

\[
(x,y,z)=(1,1,0).
\]

Substitute this point into each original equation.

| Equation | Substitution | Result | Status |
|:--|:--|:--:|:--:|
| \(x+y+z=2\) | \(1+1+0=2\) | \(2=2\) | ✓ |
| \(2x+2y+2z=4\) | \(2(1)+2(1)+2(0)=4\) | \(4=4\) | ✓ |
| \(x-y+z=0\) | \(1-1+0=0\) | \(0=0\) | ✓ |

All three equations are satisfied. Therefore, the chosen point is a valid solution.

---

## 7. Final Answer

\[
\boxed{
\begin{aligned}
x&=1-t,\\
y&=1,\\
z&=t,
\end{aligned}
\qquad t\in\mathbb{R}
}
\]

| Property | Result |
|:--|:--|
| Free variable | \(z\) |
| Parameter | \(t\in\mathbb{R}\) |
| Number of solutions | Infinitely many |
| Verified point | \((1,1,0)\) |

**Conclusion:** Gaussian elimination reveals two independent equations and one free variable. The parameter \(t\) generates infinitely many solutions, and substituting \(t=0\) confirms that \((1,1,0)\) satisfies the original system.

---

*End of Exercise 4.*
