# Exercise 10. Triangle Area from Vectors

## Given

$$
A=(0,0,0),\quad B=(2,1,0),\quad C=(1,3,2)
$$

## 1. Construct \(\overrightarrow{AB}\) and \(\overrightarrow{AC}\)

Subtract the coordinates of \(A\):

$$
\overrightarrow{AB}=B-A
$$

$$
=(2-0,1-0,0-0)
$$

$$
\boxed{\overrightarrow{AB}=(2,1,0)}
$$

Similarly,

$$
\overrightarrow{AC}=C-A
$$

$$
=(1-0,3-0,2-0)
$$

$$
\boxed{\overrightarrow{AC}=(1,3,2)}
$$

## 2. Compute the Cross Product

$$
\overrightarrow{AB}\times\overrightarrow{AC}
=
\begin{vmatrix}
\mathbf{i}&\mathbf{j}&\mathbf{k}\\
2&1&0\\
1&3&2
\end{vmatrix}
$$

$$
=\mathbf{i}(1\cdot2-0\cdot3)
-\mathbf{j}(2\cdot2-0\cdot1)
+\mathbf{k}(2\cdot3-1\cdot1)
$$

$$
=(2,-4,5)
$$

Therefore,

$$
\boxed{\overrightarrow{AB}\times\overrightarrow{AC}=(2,-4,5)}
$$

## 3. Find the Area of the Parallelogram

The area of the parallelogram is the magnitude of the cross product:

$$
A_{\text{parallelogram}}
=\left|\overrightarrow{AB}\times\overrightarrow{AC}\right|
$$

$$
=\sqrt{2^2+(-4)^2+5^2}
$$

$$
=\sqrt{4+16+25}
$$

$$
=\sqrt{45}
$$

$$
\boxed{A_{\text{parallelogram}}=3\sqrt5}
$$

## 4. Find the Area of the Triangle

The diagonal of a parallelogram divides it into two triangles of equal area.

Therefore, the triangle has half the area of the parallelogram:

$$
A_{\text{triangle}}=\frac12A_{\text{parallelogram}}
$$

$$
=\frac12(3\sqrt5)
$$

$$
\boxed{A_{\text{triangle}}=\frac{3\sqrt5}{2}}
$$

## 5. Explain the Factor \(\frac12\)

The parallelogram formed by \(\overrightarrow{AB}\) and \(\overrightarrow{AC}\) consists of two congruent triangles.

Thus,

$$
A_{\text{triangle}}=\frac12A_{\text{parallelogram}}
$$

The factor is \(\frac12\), not \(12\): the triangle's area is half the parallelogram's area.

## Final Answers

$$
\boxed{\overrightarrow{AB}=(2,1,0)}
$$

$$
\boxed{\overrightarrow{AC}=(1,3,2)}
$$

$$
\boxed{A_{\text{parallelogram}}=3\sqrt5}
$$

$$
\boxed{A_{\text{triangle}}=\frac{3\sqrt5}{2}}
$$
