# Exercise 13. Do Four Points Lie in One Plane?

## Given

$$
A=(0,0,0),\quad B=(1,2,0)
$$

$$
C=(0,1,1),\quad D=(2,5,1)
$$

## 1. Construct \(\overrightarrow{AB}\) and \(\overrightarrow{AC}\)

$$
\overrightarrow{AB}=B-A
$$

$$
=(1-0,2-0,0-0)
$$

$$
\boxed{\overrightarrow{AB}=(1,2,0)}
$$

Similarly,

$$
\overrightarrow{AC}=C-A
$$

$$
=(0-0,1-0,1-0)
$$

$$
\boxed{\overrightarrow{AC}=(0,1,1)}
$$

## 2. Find \(\mathbf{n}=\overrightarrow{AB}\times\overrightarrow{AC}\)

$$
\mathbf{n}=
\begin{vmatrix}
\mathbf{i}&\mathbf{j}&\mathbf{k}\\
1&2&0\\
0&1&1
\end{vmatrix}
$$

$$
=\mathbf{i}(2\cdot1-0\cdot1)
-\mathbf{j}(1\cdot1-0\cdot0)
+\mathbf{k}(1\cdot1-2\cdot0)
$$

$$
=(2,-1,1)
$$

Therefore,

$$
\boxed{\mathbf{n}=(2,-1,1)}
$$

## 3. Construct \(\overrightarrow{AD}\)

$$
\overrightarrow{AD}=D-A
$$

$$
=(2-0,5-0,1-0)
$$

$$
\boxed{\overrightarrow{AD}=(2,5,1)}
$$

Calculate its dot product with the normal vector:

$$
\overrightarrow{AD}\cdot\mathbf{n}
=(2,5,1)\cdot(2,-1,1)
$$

$$
=2(2)+5(-1)+1(1)
$$

$$
=4-5+1
$$

$$
=0
$$

Therefore,

$$
\boxed{\overrightarrow{AD}\cdot\mathbf{n}=0}
$$

## 4. Does \(D\) Lie in the Plane Through \(A,B,C\)?

The normal vector \(\mathbf{n}\) is perpendicular to the plane determined by \(A,B,C\).

A point \(D\) lies in this plane if its vector from \(A\) is perpendicular to the normal vector:

$$
\overrightarrow{AD}\cdot\mathbf{n}=0
$$

Since this condition is satisfied,

$$
\boxed{D\text{ lies in the plane determined by }A,B,C}
$$

## Final Conclusion

All four points are coplanar. The zero dot product verifies that \(\overrightarrow{AD}\) lies in the plane through \(A,B,C\).
