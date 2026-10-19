# Exercise 2: Distance as the Length of a Vector

Given the points

\[
A=(1,2,3), \qquad B=(4,-2,6).
\]

## 1. Construct the Vector \(\overrightarrow{AB}\)

The vector from point \(A\) to point \(B\) is found by subtracting the coordinates of \(A\) from the coordinates of \(B\).

The formula is

\[
\overrightarrow{AB}=B-A.
\]

Substitute the coordinates:

\[
\overrightarrow{AB}=(4,-2,6)-(1,2,3).
\]

Subtract the corresponding components:

\[
\overrightarrow{AB}=(4-1,-2-2,6-3).
\]

Simplifying,

\[
\boxed{\overrightarrow{AB}=(3,-4,3)}.
\]

The components of the vector are summarized below.

| Component | Calculation | Result |
|---|---|---:|
| \(x\) | \(4-1\) | \(3\) |
| \(y\) | \(-2-2\) | \(-4\) |
| \(z\) | \(6-3\) | \(3\) |

## 2. Compute the Length of \(\overrightarrow{AB}\)

The length of a vector in three-dimensional space is calculated using the formula

\[
\|\mathbf{v}\|=\sqrt{v_x^2+v_y^2+v_z^2}.
\]

Since

\[
\overrightarrow{AB}=(3,-4,3),
\]

its length is

\[
\|\overrightarrow{AB}\|
=\sqrt{3^2+(-4)^2+3^2}.
\]

Square each component:

\[
=\sqrt{9+16+9}.
\]

Add the values:

\[
=\sqrt{34}.
\]

Therefore, the length of the vector is

\[
\boxed{\|\overrightarrow{AB}\|=\sqrt{34}\approx5.83}.
\]

## 3. Compute the Distance Using the Coordinate Formula

The distance between two points in three-dimensional space is given by

\[
d(A,B)=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}.
\]

For the given points,

\[
A=(1,2,3), \qquad B=(4,-2,6),
\]

we have

\[
x_1=1,\quad y_1=2,\quad z_1=3,
\]

\[
x_2=4,\quad y_2=-2,\quad z_2=6.
\]

Substitute these coordinates into the formula:

\[
d(A,B)=\sqrt{(4-1)^2+(-2-2)^2+(6-3)^2}.
\]

Simplify the differences:

\[
=\sqrt{3^2+(-4)^2+3^2}.
\]

Calculate the squares:

\[
=\sqrt{9+16+9}.
\]

Therefore,

\[
\boxed{d(A,B)=\sqrt{34}\approx5.83}.
\]

## 4. Explain Why Both Calculations Give the Same Result

The vector \(\overrightarrow{AB}\) represents the displacement from point \(A\) to point \(B\). Its components describe the changes in the \(x\)-, \(y\)-, and \(z\)-coordinates.

The distance between two points is the magnitude, or length, of the displacement vector connecting them.

Mathematically,

\[
\overrightarrow{AB}
=(x_2-x_1,y_2-y_1,z_2-z_1).
\]

Taking its magnitude gives

\[
\|\overrightarrow{AB}\|
=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}.
\]

This is exactly the coordinate distance formula. Therefore,

\[
\boxed{d(A,B)=\|\overrightarrow{AB}\|}.
\]

Both methods give the same result because the coordinate distance formula is derived directly from the length of the difference vector.

## Final Results

| Quantity | Result |
|---|---|
| Vector \(\overrightarrow{AB}\) | \((3,-4,3)\) |
| Length of \(\overrightarrow{AB}\) | \(\sqrt{34}\approx5.83\) |
| Distance \(d(A,B)\) | \(\sqrt{34}\approx5.83\) |
| Relationship | \(d(A,B)=\|\overrightarrow{AB}\|\) |
