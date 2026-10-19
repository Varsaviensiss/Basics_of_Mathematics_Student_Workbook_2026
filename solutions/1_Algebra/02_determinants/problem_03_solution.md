# Exercise 3. Swapping Two Rows

Given:

$$
A=
\begin{pmatrix}
1 & 2 & 0\\
0 & 3 & 1\\
2 & 1 & 1
\end{pmatrix}
$$

We need to compute \(\det(A)\), swap the first and second rows to form \(B\), predict \(\det(B)\), and verify the result by calculation.

## 1. Compute \(\det(A)\)

Using Sarrus' rule:

$$
\det(A)=aei+bfg+cdh-ceg-bdi-afh
$$

For the matrix

$$
A=
\begin{pmatrix}
1 & 2 & 0\\
0 & 3 & 1\\
2 & 1 & 1
\end{pmatrix},
$$

the entries are

$$
a=1,\quad b=2,\quad c=0
$$

$$
d=0,\quad e=3,\quad f=1
$$

$$
g=2,\quad h=1,\quad i=1
$$

Calculate the positive diagonal products:

$$
aei=(1)(3)(1)=3
$$

$$
bfg=(2)(1)(2)=4
$$

$$
cdh=(0)(0)(1)=0
$$

Add them:

$$
3+4+0=7
$$

Calculate the negative diagonal products:

$$
ceg=(0)(3)(2)=0
$$

$$
bdi=(2)(0)(1)=0
$$

$$
afh=(1)(1)(1)=1
$$

Add them:

$$
0+0+1=1
$$

Subtract:

$$
\det(A)=7-1
$$

Therefore,

$$
\boxed{\det(A)=6}
$$

## 2. Form Matrix \(B\) by Swapping the First and Second Rows

The original matrix is

$$
A=
\begin{pmatrix}
1 & 2 & 0\\
0 & 3 & 1\\
2 & 1 & 1
\end{pmatrix}
$$

Swap the first and second rows:

$$
R_1\leftrightarrow R_2
$$

The resulting matrix is

$$
B=
\begin{pmatrix}
0 & 3 & 1\\
1 & 2 & 0\\
2 & 1 & 1
\end{pmatrix}
$$

## 3. Predict \(\det(B)\) Using a Determinant Property

A fundamental property of determinants states that **swapping two rows changes the sign of the determinant**.

Therefore,

$$
\det(B)=-\det(A)
$$

Since

$$
\det(A)=6,
$$

we predict

$$
\det(B)=-6
$$

Thus,

$$
\boxed{\det(B)=-6}
$$

## 4. Verify the Prediction by Calculating \(\det(B)\)

Using Sarrus' rule for

$$
B=
\begin{pmatrix}
0 & 3 & 1\\
1 & 2 & 0\\
2 & 1 & 1
\end{pmatrix},
$$

the determinant is

$$
\det(B)=aei+bfg+cdh-ceg-bdi-afh
$$

The entries are

$$
a=0,\quad b=3,\quad c=1
$$

$$
d=1,\quad e=2,\quad f=0
$$

$$
g=2,\quad h=1,\quad i=1
$$

Calculate the positive diagonal products:

$$
aei=(0)(2)(1)=0
$$

$$
bfg=(3)(0)(2)=0
$$

$$
cdh=(1)(1)(1)=1
$$

Add them:

$$
0+0+1=1
$$

Calculate the negative diagonal products:

$$
ceg=(1)(2)(2)=4
$$

$$
bdi=(3)(1)(1)=3
$$

$$
afh=(0)(0)(1)=0
$$

Add them:

$$
4+3+0=7
$$

Subtract:

$$
\det(B)=1-7
$$

$$
\boxed{\det(B)=-6}
$$

## 5. Compare the Results

The original determinant is

$$
\det(A)=6
$$

The determinant after swapping the first and second rows is

$$
\det(B)=-6
$$

Therefore,

$$
\det(B)=-\det(A)
$$

The direct calculation agrees with the prediction.

## Final Answer

$$
\boxed{\det(A)=6}
$$

After swapping the first and second rows:

$$
\boxed{
B=
\begin{pmatrix}
0 & 3 & 1\\
1 & 2 & 0\\
2 & 1 & 1
\end{pmatrix}
}
$$

The determinant changes sign:

$$
\boxed{\det(B)=-\det(A)=-6}
$$

The calculation verifies the determinant property: swapping two rows multiplies the determinant by \(-1\).


