# 📘 Linear Algebra — Exercise 2
## Formula for a \(2\times2\) Matrix

---

### 🎯 Objective

Find the inverse of a \(2\times2\) matrix using the standard inverse formula, then verify the result by multiplying it by the original matrix.

### 🧮 Given Matrix

\[
A=\begin{pmatrix}
3 & 2\\
5 & 4
\end{pmatrix}
\]

Our goal is to find \(A^{-1}\).

---

## 🔹 Step 1 — Recall the Inverse Formula

For a general \(2\times2\) matrix

\[
A=\begin{pmatrix}
a & b\\
c & d
\end{pmatrix}
\]

the inverse is given by

\[
\boxed{
A^{-1}=\frac{1}{ad-bc}
\begin{pmatrix}
d & -b\\
-c & a
\end{pmatrix}
}
\]

provided that

\[
ad-bc\neq0
\]

The expression \(ad-bc\) is called the **determinant** of the matrix.

---

## 🔹 Step 2 — Calculate the Determinant

For our matrix,

\[
A=\begin{pmatrix}
3 & 2\\
5 & 4
\end{pmatrix}
\]

we have

\[
a=3,\quad b=2,\quad c=5,\quad d=4
\]

Calculate the determinant:

\[
\det(A)=ad-bc
\]

\[
\det(A)=(3)(4)-(2)(5)
\]

\[
\det(A)=12-10=2
\]

Therefore,

\[
\boxed{\det(A)=2\neq0}
\]

✅ Since the determinant is nonzero, the inverse exists.

---

## 🔹 Step 3 — Apply the Formula

Substitute the matrix entries into the inverse formula:

\[
A^{-1}=\frac{1}{3(4)-2(5)}
\begin{pmatrix}
4 & -2\\
-5 & 3
\end{pmatrix}
\]

Using the determinant calculated above:

\[
A^{-1}=\frac12
\begin{pmatrix}
4 & -2\\
-5 & 3
\end{pmatrix}
\]

Multiply every entry by \(\frac12\):

\[
A^{-1}=
\begin{pmatrix}
\frac{4}{2} & \frac{-2}{2}\\
\frac{-5}{2} & \frac{3}{2}
\end{pmatrix}
\]

Hence, the inverse matrix is

\[
\boxed{
A^{-1}=
\begin{pmatrix}
2 & -1\\
-\frac52 & \frac32
\end{pmatrix}
}
\]

---

## 🔹 Step 4 — Verify the Result

To check our answer, we compute \(AA^{-1}\).

By the definition of the inverse, the product must equal the identity matrix \(I_2\).

\[
AA^{-1}=
\begin{pmatrix}
3 & 2\\
5 & 4
\end{pmatrix}
\begin{pmatrix}
2 & -1\\
-\frac52 & \frac32
\end{pmatrix}
\]

Using row-by-column multiplication:

\[
AA^{-1}=
\begin{pmatrix}
3(2)+2\left(-\frac52\right)
&
3(-1)+2\left(\frac32\right)
\\[6pt]
5(2)+4\left(-\frac52\right)
&
5(-1)+4\left(\frac32\right)
\end{pmatrix}
\]

Simplifying each entry:

\[
AA^{-1}=
\begin{pmatrix}
6-5 & -3+3\\
10-10 & -5+6
\end{pmatrix}
\]

Therefore,

\[
\boxed{
AA^{-1}=
\begin{pmatrix}
1&0\\
0&1
\end{pmatrix}
=I_2
}
\]

✅ The result is verified.

---

## 📊 Summary

| Step | Calculation | Result |
|:---|:---|:---|
| 1 | Determinant | \(\det(A)=2\) |
| 2 | Check existence | Inverse exists |
| 3 | Apply the formula | \(A^{-1}=\begin{pmatrix}2&-1\\-\frac52&\frac32\end{pmatrix}\) |
| 4 | Verify the product | \(AA^{-1}=I_2\) |

---

## 🏆 Final Answer

The inverse of

\[
A=\begin{pmatrix}
3&2\\
5&4
\end{pmatrix}
\]

is

\[
\boxed{
A^{-1}=
\begin{pmatrix}
2&-1\\
-\frac52&\frac32
\end{pmatrix}
}
\]

The calculation is confirmed because multiplying the original matrix by its inverse produces the identity matrix.

> **Key takeaway:** For a \(2\times2\) matrix, calculate the determinant, swap the diagonal entries, change the signs of the off-diagonal entries, and divide by the determinant. Finally, verify the answer by multiplication.

---

*📚 Topic: Linear Algebra · Inverse Matrices · The \(2\times2\) Inverse Formula*
