# Exercise 6. Angle Between Planes

## Given

$$
\Pi_1:x+y+z=1
$$

$$
\Pi_2:x-y=2
$$

## 1. Find the Normal Vectors

From the coefficients of the plane equations:

$$
\boxed{\mathbf{n}_1=(1,1,1)}
$$

$$
\boxed{\mathbf{n}_2=(1,-1,0)}
$$

## 2. Determine Whether the Planes Are Parallel

Two planes are parallel if their normal vectors are scalar multiples of each other.

The vectors \((1,1,1)\) and \((1,-1,0)\) are not scalar multiples.

Therefore,

$$
\boxed{\text{The planes are not parallel.}}
$$

## 3. Compute the Angle Between the Planes

The acute angle between two planes is the angle between their normal vectors, taken as the smaller angle.

$$
\cos\theta=
\frac{|\mathbf{n}_1\cdot\mathbf{n}_2|}
{|\mathbf{n}_1||\mathbf{n}_2|}
$$

Calculate the dot product:

$$
\mathbf{n}_1\cdot\mathbf{n}_2
=1(1)+1(-1)+1(0)
$$

$$
=1-1+0=0
$$

Calculate the lengths:

$$
|\mathbf{n}_1|=\sqrt{1^2+1^2+1^2}=\sqrt3
$$

$$
|\mathbf{n}_2|=\sqrt{1^2+(-1)^2+0^2}=\sqrt2
$$

Substitute:

$$
\cos\theta=\frac{|0|}{\sqrt3\sqrt2}=0
$$

$$
\theta=\cos^{-1}(0)
$$

Therefore,

$$
\boxed{\theta=90^\circ}
$$

## 4. Why Are the Normal Vectors Sufficient?

A plane's normal vector determines its orientation. The angle between two planes is therefore determined by the angle between their normal vectors.

Because the normal vectors are perpendicular, the planes meet at a right angle.

## Final Answer

$$
\boxed{\Pi_1\perp\Pi_2,\qquad \theta=90^\circ}
$$
