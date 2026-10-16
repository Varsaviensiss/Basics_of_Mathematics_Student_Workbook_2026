# Exercise 3 — Swapping Two Rows

## Problem Statement

Given the matrix

\[
A=
\begin{pmatrix}
1&2&0\\
0&3&1\\
2&1&1
\end{pmatrix},
\]

we are asked to:

1. Calculate the determinant of \(A\).
2. Construct a new matrix \(B\) by swapping the first and second rows of \(A\).
3. Predict \(\det(B)\) using a determinant property.
4. Calculate \(\det(B)\) directly to verify the prediction.

---

## Step 1 — Calculate the Determinant of \(A\)

For a \(3\times3\) matrix

\[
A=
\begin{pmatrix}
a&b&c\\
d&e&f\\
g&h&i
\end{pmatrix},
\]

the determinant is given by

\[
\det(A)=a(ei-fh)-b(di-fg)+c(dh-eg).
\]

For the given matrix,

\[
A=
\begin{pmatrix}
1&2&0\\
0&3&1\\
2&1&1
\end{pmatrix},
\]

the entries are

\[
a=1,\quad b=2,\quad c=0,
\]

\[
d=0,\quad e=3,\quad f=1,
\]

\[
g=2,\quad h=1,\quad i=1.
\]

Substituting these values into the determinant formula gives

\[
\begin{aligned}
\det(A)
&=1(3\cdot1-1\cdot1)\\
&\quad-2(0\cdot1-1\cdot2)\\
&\quad+0(0\cdot1-3\cdot2).
\end{aligned}
\]

Simplifying each term,

\[
\begin{aligned}
\det(A)
&=1(3-1)-2(0-2)+0\\
&=2-2(-2)\\
&=2+4\\
&=6.
\end{aligned}
\]

Therefore,

\[
\boxed{\det(A)=6}
\]

---

## Step 2 — Construct Matrix \(B\)

We obtain \(B\) by swapping the first and second rows of \(A\).

The original rows are

\[
R_1=(1,2,0),
\]

\[
R_2=(0,3,1),
\]

\[
R_3=(2,1,1).
\]

After exchanging \(R_1\) and \(R_2\), the new matrix is

\[
\boxed{
B=
\begin{pmatrix}
0&3&1\\
1&2&0\\
2&1&1
\end{pmatrix}
}
\]

The row operation can be written as

\[
R_1\leftrightarrow R_2.
\]

---

## Step 3 — Predict the Determinant of \(B\)

A fundamental property of determinants states:

**When two rows of a matrix are exchanged, the determinant changes its sign.**

Mathematically,

\[
\det(B)=-\det(A).
\]

Since Step 1 gave

\[
\det(A)=6,
\]

we can predict that

\[
\det(B)=-6.
\]

Thus, before calculating the determinant of \(B\) directly, our prediction is

\[
\boxed{\det(B)=-6}
\]

This prediction follows directly from the row-swapping property.

---

## Step 4 — Verify the Prediction by Calculation

Now calculate the determinant of \(B\) independently.

The matrix is

\[
B=
\begin{pmatrix}
0&3&1\\
1&2&0\\
2&1&1
\end{pmatrix}.
\]

Using the determinant formula for a \(3\times3\) matrix,

\[
\det(B)=a(ei-fh)-b(di-fg)+c(dh-eg),
\]

we obtain

\[
\begin{aligned}
\det(B)
&=0(2\cdot1-0\cdot1)\\
&\quad-3(1\cdot1-0\cdot2)\\
&\quad+1(1\cdot1-2\cdot2).
\end{aligned}
\]

Simplifying,

\[
\begin{aligned}
\det(B)
&=0-3(1)+1(1-4)\\
&=-3-3\\
&=-6.
\end{aligned}
\]

Therefore,

\[
\boxed{\det(B)=-6}
\]

The direct calculation agrees with our prediction.

---

## Step 5 — Compare the Results

| Property | Matrix \(A\) | Matrix \(B\) |
|:--|:--:|:--:|
| Row operation | Original matrix | First and second rows exchanged |
| Determinant | \(6\) | \(-6\) |
| Absolute value | \(6\) | \(6\) |
| Sign | Positive | Negative |

The comparison shows that exchanging two rows preserves the absolute value of the determinant but reverses its sign.

---

## Final Answer

The determinant of the original matrix is

\[
\boxed{\det(A)=6}.
\]

After swapping the first and second rows, the new matrix is

\[
B=
\begin{pmatrix}
0&3&1\\
1&2&0\\
2&1&1
\end{pmatrix}.
\]

Using the row-swapping property, we predict

\[
\det(B)=-\det(A)=-6.
\]

Direct calculation confirms the result:

\[
\boxed{\det(B)=-6}.
\]

**Conclusion:** Swapping two rows of a matrix multiplies its determinant by \(-1\). Both calculations confirm this property for the given matrices.

---

*End of Exercise 3.*
