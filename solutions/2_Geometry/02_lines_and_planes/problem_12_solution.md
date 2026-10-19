# Exercise 12. Intersection Line of Two Planes

## Given

$$
\Pi_1:x+y+z=3
$$

$$
\Pi_2:x-y+z=1
$$

## 1. Find the Intersection Line Algebraically

Subtract the second equation from the first:

$$
(x+y+z)-(x-y+z)=3-1
$$

$$
2y=2
$$

$$
\boxed{y=1}
$$

Substitute \(y=1\) into the first plane equation:

$$
x+1+z=3
$$

$$
x+z=2
$$

$$
z=2-x
$$

Let \(x=t\). Then

$$
x=t,\qquad y=1,\qquad z=2-t
$$

Therefore, the intersection line is

$$
\boxed{(x,y,z)=(0,1,2)+t(1,0,-1)}
$$

## 2. Find the Direction Vector Using the Normal Vectors

The plane normal vectors are

$$
\mathbf{n}_1=(1,1,1)
$$

$$
\mathbf{n}_2=(1,-1,1)
$$

The intersection direction is perpendicular to both normals. Therefore, calculate their cross product:

$$
\mathbf{v}=\mathbf{n}_1\times\mathbf{n}_2
$$

$$
\mathbf{v}=
\begin{vmatrix}
\mathbf{i}&\mathbf{j}&\mathbf{k}\\
1&1&1\\
1&-1&1
\end{vmatrix}
$$

$$
=\mathbf{i}(1-(-1))
-\mathbf{j}(1-1)
+\mathbf{k}(-1-1)
$$

$$
=(2,0,-2)
$$

Simplify by dividing by \(2\):

$$
\boxed{\mathbf{v}=(1,0,-1)}
$$

This matches the direction vector found algebraically.

## 3. Compare the Two Methods

- **Algebraic method:** Solving the two plane equations gives \(y=1\) and \(x+z=2\).
- **Geometric method:** The cross product of the normals gives the intersection direction.

Both methods produce the same line:

$$
\boxed{(x,y,z)=(0,1,2)+t(1,0,-1)}
$$

