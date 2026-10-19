# Exercise 14. Rotation Matrices

Given the rotation matrix

$$
R(\theta)=
\begin{pmatrix}
\cos\theta & -\sin\theta\\
\sin\theta & \cos\theta
\end{pmatrix}
$$

We need to compute \(R(\alpha)R(\beta)\), prove that

$$
R(\alpha)R(\beta)=R(\alpha+\beta),
$$

and explain the result geometrically.

## 1. Compute \(R(\alpha)R(\beta)\)

Write both rotation matrices:

$$
R(\alpha)=
\begin{pmatrix}
\cos\alpha & -\sin\alpha\\
\sin\alpha & \cos\alpha
\end{pmatrix}
$$

$$
R(\beta)=
\begin{pmatrix}
\cos\beta & -\sin\beta\\
\sin\beta & \cos\beta
\end{pmatrix}
$$

Multiply the matrices:

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos\alpha & -\sin\alpha\\
\sin\alpha & \cos\alpha
\end{pmatrix}
\begin{pmatrix}
\cos\beta & -\sin\beta\\
\sin\beta & \cos\beta
\end{pmatrix}
$$

Calculate the entry in the first row and first column:

$$
(\cos\alpha)(\cos\beta)+(-\sin\alpha)(\sin\beta)
$$

$$
=\cos\alpha\cos\beta-\sin\alpha\sin\beta
$$

Calculate the entry in the first row and second column:

$$
(\cos\alpha)(-\sin\beta)+(-\sin\alpha)(\cos\beta)
$$

$$
=-\cos\alpha\sin\beta-\sin\alpha\cos\beta
$$

Calculate the entry in the second row and first column:

$$
(\sin\alpha)(\cos\beta)+(\cos\alpha)(\sin\beta)
$$

$$
=\sin\alpha\cos\beta+\cos\alpha\sin\beta
$$

Calculate the entry in the second row and second column:

$$
(\sin\alpha)(-\sin\beta)+(\cos\alpha)(\cos\beta)
$$

$$
=-\sin\alpha\sin\beta+\cos\alpha\cos\beta
$$

Therefore, the product is

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta
&
-\cos\alpha\sin\beta-\sin\alpha\cos\beta
\\
\sin\alpha\cos\beta+\cos\alpha\sin\beta
&
\cos\alpha\cos\beta-\sin\alpha\sin\beta
\end{pmatrix}
$$

## 2. Use the Angle-Sum Formulas

The angle-sum formulas for cosine and sine are:

$$
\cos(\alpha+\beta)
=
\cos\alpha\cos\beta-\sin\alpha\sin\beta
$$

$$
\sin(\alpha+\beta)
=
\sin\alpha\cos\beta+\cos\alpha\sin\beta
$$

Using the cosine formula, the diagonal entries become:

$$
\cos\alpha\cos\beta-\sin\alpha\sin\beta
=\cos(\alpha+\beta)
$$

Using the sine formula, the entry in the second row and first column becomes:

$$
\sin\alpha\cos\beta+\cos\alpha\sin\beta
=\sin(\alpha+\beta)
$$

For the entry in the first row and second column:

$$
-\cos\alpha\sin\beta-\sin\alpha\cos\beta
$$

Factor out the negative sign:

$$
=-(\cos\alpha\sin\beta+\sin\alpha\cos\beta)
$$

Apply the sine angle-sum formula:

$$
=-\sin(\alpha+\beta)
$$

Substitute these expressions into the product matrix:

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos(\alpha+\beta) & -\sin(\alpha+\beta)\\
\sin(\alpha+\beta) & \cos(\alpha+\beta)
\end{pmatrix}
$$

By the definition of the rotation matrix,

$$
R(\alpha+\beta)=
\begin{pmatrix}
\cos(\alpha+\beta) & -\sin(\alpha+\beta)\\
\sin(\alpha+\beta) & \cos(\alpha+\beta)
\end{pmatrix}
$$

Therefore,

$$
\boxed{R(\alpha)R(\beta)=R(\alpha+\beta)}
$$

## 3. Geometric Explanation

A rotation matrix \(R(\theta)\) rotates a vector in the plane counterclockwise through an angle \(\theta\) about the origin.

Applying \(R(\beta)\) first rotates a vector through angle \(\beta\). Applying \(R(\alpha)\) afterward rotates the resulting vector through another angle \(\alpha\).

The total rotation angle is

$$
\theta_{\text{total}}=\beta+\alpha
$$

Since angle addition is commutative,

$$
\beta+\alpha=\alpha+\beta
$$

the composition is equivalent to a single rotation through angle \(\alpha+\beta\).

Thus, the matrix identity expresses the geometric fact that two successive rotations about the same origin are equivalent to one rotation whose angle is the sum of the two angles.

## Final Answer

The product of the two rotation matrices is

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta
&
-\cos\alpha\sin\beta-\sin\alpha\cos\beta
\\
\sin\alpha\cos\beta+\cos\alpha\sin\beta
&
\cos\alpha\cos\beta-\sin\alpha\sin\beta
\end{pmatrix}
$$

Using the angle-sum formulas gives

$$
\boxed{R(\alpha)R(\beta)=R(\alpha+\beta)}
$$

Geometrically, two successive rotations about the origin combine into a single rotation through the sum of their angles.

