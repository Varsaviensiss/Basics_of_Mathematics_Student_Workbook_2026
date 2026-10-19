# Exercise 9. Area and the Determinant

Given the vectors

$$
u=\begin{pmatrix}3\\1\end{pmatrix},
\qquad
v=\begin{pmatrix}1\\4\end{pmatrix}
$$

These vectors span a parallelogram. We will compute its area using a determinant and then reverse the order of the vectors.

## 1. Compute the area using a determinant

Place the vectors as the columns of a matrix:

$$
A=\begin{pmatrix}
3 & 1\\
1 & 4
\end{pmatrix}
$$

For a \(2\times2\) matrix,

$$
\det(A)=ad-bc
$$

Therefore,

$$
\det(A)=(3)(4)-(1)(1)
$$

$$
\det(A)=12-1
$$

$$
\det(A)=11
$$

The area of the parallelogram is the absolute value of the determinant:

$$
\text{Area}=|\det(A)|
$$

$$
\text{Area}=|11|
$$

$$
\boxed{\text{Area}=11\text{ square units}}
$$

## 2. Reverse the order of the vectors

Now place \(v\) first and \(u\) second:

$$
B=\begin{pmatrix}
1 & 3\\
4 & 1
\end{pmatrix}
$$

Calculate its determinant:

$$
\det(B)=(1)(1)-(3)(4)
$$

$$
\det(B)=1-12
$$

$$
\det(B)=-11
$$

Therefore,

$$
\boxed{\det(B)=-11}
$$

## 3. Compare the determinant and the area

Reversing the order of two columns changes the sign of the determinant:

$$
\det(B)=-\det(A)
$$

$$
-11=-11
$$

The area is the absolute value of the determinant. Thus,

$$
\text{Area}=|\det(B)|
$$

$$
\text{Area}=|-11|
$$

$$
\boxed{\text{Area}=11\text{ square units}}
$$

## Final Comparison

| Quantity | Original order \((u,v)\) | Reversed order \((v,u)\) |
|---|---:|---:|
| Determinant | \(11\) | \(-11\) |
| Absolute value | \(11\) | \(11\) |
| Parallelogram area | \(11\) square units | \(11\) square units |

**Explanation:** Reversing the order of the vectors changes the sign of the determinant because it reverses the orientation of the vectors. However, the geometric area does not change, since area is always the absolute value of the determinant.
