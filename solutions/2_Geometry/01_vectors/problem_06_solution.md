# Exercise 6. Projection and Perpendicular Component

## Given

$$
\mathbf{u}=(4,2),\qquad \mathbf{v}=(1,1)
$$

## 1. Find the Projection of \(\mathbf{u}\) onto \(\mathbf{v}\)

The projection formula is

$$
\operatorname{proj}_{\mathbf{v}}\mathbf{u}
=\frac{\mathbf{u}\cdot\mathbf{v}}{\mathbf{v}\cdot\mathbf{v}}\mathbf{v}
$$

Calculate the dot products:

$$
\mathbf{u}\cdot\mathbf{v}=4(1)+2(1)=6
$$

$$
\mathbf{v}\cdot\mathbf{v}=1^2+1^2=2
$$

Substitute:

$$
\operatorname{proj}_{\mathbf{v}}\mathbf{u}
=\frac62(1,1)
$$

$$
=3(1,1)
$$

Therefore,

$$
\boxed{\operatorname{proj}_{\mathbf{v}}\mathbf{u}=(3,3)}
$$

## 2. Compute the Perpendicular Component

The perpendicular component is

$$
\mathbf{r}=\mathbf{u}-\operatorname{proj}_{\mathbf{v}}\mathbf{u}
$$

Substitute the vectors:

$$
\mathbf{r}=(4,2)-(3,3)
$$

$$
\boxed{\mathbf{r}=(1,-1)}
$$

## 3. Verify That \(\mathbf{r}\cdot\mathbf{v}=0\)

$$
\mathbf{r}\cdot\mathbf{v}=(1,-1)\cdot(1,1)
$$

$$
=1(1)+(-1)(1)
$$

$$
=1-1=0
$$

Therefore,

$$
\boxed{\mathbf{r}\cdot\mathbf{v}=0}
$$

## 4. Geometric Meaning

The original vector is decomposed into two components:

- The projection \((3,3)\) is parallel to \(\mathbf{v}\).
- The vector \((1,-1)\) is perpendicular to \(\mathbf{v}\).

Their sum reconstructs the original vector:

$$
(3,3)+(1,-1)=(4,2)
$$

$$
\boxed{\mathbf{u}=\operatorname{proj}_{\mathbf{v}}\mathbf{u}+\mathbf{r}}
$$

This decomposition separates the part of \(\mathbf{u}\) along the direction of \(\mathbf{v}\) from the part perpendicular to it.
