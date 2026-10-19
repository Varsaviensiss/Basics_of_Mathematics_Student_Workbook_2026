# Exercise 12. A Normal Vector to a Plane

## Given

$$
A=(1,0,2),\quad B=(2,1,0),\quad C=(0,3,1)
$$

## 1. Construct Two Vectors in the Plane

Use point \(A\) as the starting point for both vectors.

$$
\overrightarrow{AB}=B-A
$$

$$
=(2-1,1-0,0-2)
$$

$$
\boxed{\overrightarrow{AB}=(1,1,-2)}
$$

Similarly,

$$
\overrightarrow{AC}=C-A
$$

$$
=(0-1,3-0,1-2)
$$

$$
\boxed{\overrightarrow{AC}=(-1,3,-1)}
$$

## 2. Find a Vector Perpendicular to Both

Take the cross product:

$$
\mathbf{n}=\overrightarrow{AB}\times\overrightarrow{AC}
$$

$$
\mathbf{n}=
\begin{vmatrix}
\mathbf{i}&\mathbf{j}&\mathbf{k}\\
1&1&-2\\
-1&3&-1
\end{vmatrix}
$$

$$
=\mathbf{i}(1(-1)-(-2)(3))
-\mathbf{j}(1(-1)-(-2)(-1))
+\mathbf{k}(1(3)-1(-1))
$$

$$
=\mathbf{i}(-1+6)-\mathbf{j}(-1-2)+\mathbf{k}(3+1)
$$

$$
=(5,3,4)
$$

Therefore,

$$
\boxed{\mathbf{n}=(5,3,4)}
$$

## 3. Verify Perpendicularity to \(\overrightarrow{AB}\)

$$
\mathbf{n}\cdot\overrightarrow{AB}
=(5,3,4)\cdot(1,1,-2)
$$

$$
=5+3-8
$$

$$
=0
$$

Thus,

$$
\boxed{\mathbf{n}\cdot\overrightarrow{AB}=0}
$$

## 4. Verify Perpendicularity to \(\overrightarrow{AC}\)

$$
\mathbf{n}\cdot\overrightarrow{AC}
=(5,3,4)\cdot(-1,3,-1)
$$

$$
=-5+9-4
$$

$$
=0
$$

Thus,

$$
\boxed{\mathbf{n}\cdot\overrightarrow{AC}=0}
$$

## Final Answer

A normal vector to the plane is

$$
\boxed{\mathbf{n}=(5,3,4)}
$$

It is perpendicular to both vectors lying in the plane, as verified by the two zero dot products.
