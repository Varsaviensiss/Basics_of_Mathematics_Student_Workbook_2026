# Exercise 9. Cross Product as a Perpendicular Direction

## Given

$$
\mathbf{u}=(1,2,0),\qquad \mathbf{v}=(0,1,3)
$$

## 1. Compute \(\mathbf{u}\times\mathbf{v}\)

The cross product is

$$
\mathbf{u}\times\mathbf{v}
=
\begin{vmatrix}
\mathbf{i}&\mathbf{j}&\mathbf{k}\\
1&2&0\\
0&1&3
\end{vmatrix}
$$

Expand along the first row:

$$
\mathbf{u}\times\mathbf{v}
=\mathbf{i}(2\cdot3-0\cdot1)
-\mathbf{j}(1\cdot3-0\cdot0)
+\mathbf{k}(1\cdot1-2\cdot0)
$$

$$
=(6,-3,1)
$$

Therefore,

$$
\boxed{\mathbf{u}\times\mathbf{v}=(6,-3,1)}
$$

## 2. Check Perpendicularity to \(\mathbf{u}\)

$$
(\mathbf{u}\times\mathbf{v})\cdot\mathbf{u}
=(6,-3,1)\cdot(1,2,0)
$$

$$
=6(1)+(-3)(2)+1(0)
$$

$$
=6-6+0=0
$$

Thus,

$$
\boxed{(\mathbf{u}\times\mathbf{v})\cdot\mathbf{u}=0}
$$

## 3. Check Perpendicularity to \(\mathbf{v}\)

$$
(\mathbf{u}\times\mathbf{v})\cdot\mathbf{v}
=(6,-3,1)\cdot(0,1,3)
$$

$$
=6(0)+(-3)(1)+1(3)
$$

$$
=0-3+3=0
$$

Thus,

$$
\boxed{(\mathbf{u}\times\mathbf{v})\cdot\mathbf{v}=0}
$$

The cross product is perpendicular to both original vectors.

## 4. Compute \(\mathbf{v}\times\mathbf{u}\)

$$
\mathbf{v}\times\mathbf{u}
=
\begin{vmatrix}
\mathbf{i}&\mathbf{j}&\mathbf{k}\\
0&1&3\\
1&2&0
\end{vmatrix}
$$

$$
=\mathbf{i}(1\cdot0-3\cdot2)
-\mathbf{j}(0\cdot0-3\cdot1)
+\mathbf{k}(0\cdot2-1\cdot1)
$$

$$
=(-6,3,-1)
$$

Therefore,

$$
\boxed{\mathbf{v}\times\mathbf{u}=(-6,3,-1)}
$$

Compare the results:

$$
\boxed{\mathbf{v}\times\mathbf{u}=-(\mathbf{u}\times\mathbf{v})}
$$

## Final Conclusion

The cross product gives a vector perpendicular to both input vectors. Reversing their order reverses the direction of the resulting vector.
