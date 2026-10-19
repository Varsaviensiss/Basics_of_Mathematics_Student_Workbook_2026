# Exercise 4. Plane Through Three Points

## Given

$$
A=(1,0,0),\quad B=(0,1,0),\quad C=(0,0,1)
$$

## 1. Construct Two Vectors in the Plane

$$
\overrightarrow{AB}=B-A
$$

$$
=(0-1,1-0,0-0)
$$

$$
\boxed{\overrightarrow{AB}=(-1,1,0)}
$$

Similarly,

$$
\overrightarrow{AC}=C-A
$$

$$
=(0-1,0-0,1-0)
$$

$$
\boxed{\overrightarrow{AC}=(-1,0,1)}
$$

## 2. Find a Normal Vector Using the Cross Product

$$
\mathbf{n}=\overrightarrow{AB}\times\overrightarrow{AC}
$$

$$
\mathbf{n}=
\begin{vmatrix}
\mathbf{i}&\mathbf{j}&\mathbf{k}\\
-1&1&0\\
-1&0&1
\end{vmatrix}
$$

$$
=\mathbf{i}(1\cdot1-0\cdot0)
-\mathbf{j}((-1)\cdot1-0\cdot(-1))
+\mathbf{k}((-1)\cdot0-1\cdot(-1))
$$

$$
=(1,1,1)
$$

Therefore,

$$
\boxed{\mathbf{n}=(1,1,1)}
$$

## 3. Find the Plane Equation

Using the normal vector, write

$$
x+y+z=d
$$

Substitute point \(A=(1,0,0)\):

$$
1+0+0=d
$$

$$
d=1
$$

Thus, the plane equation is

$$
\boxed{x+y+z=1}
$$

## 4. Check All Three Points

For \(A=(1,0,0)\):

$$
1+0+0=1
$$

For \(B=(0,1,0)\):

$$
0+1+0=1
$$

For \(C=(0,0,1)\):

$$
0+0+1=1
$$

All three points satisfy the equation.

## Final Answer

$$
\boxed{x+y+z-1=0}
$$
