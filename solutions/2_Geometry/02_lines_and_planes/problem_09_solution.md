# Exercise 9. Distances

## Part 1. Distance from a Point to a Line

Find the distance from $P=(2,3)$ to the line $3x+4y-10=0$.

The normal vector is $\mathbf n=(3,4)$, so its length is $\sqrt{3^2+4^2}=5$. The distance is

$$
d=\frac{|3(2)+4(3)-10|}{\sqrt{3^2+4^2}}
=\boxed{\frac{8}{5}}.
$$

## Part 2. Distance from a Point to a Plane

Find the distance from $Q=(2,-1,3)$ to the plane $2x-2y+z-4=0$.

The normal vector is $\mathbf n=(2,-2,1)$, so its length is $\sqrt{2^2+(-2)^2+1^2}=3$. The distance is

$$
d=\frac{|2(2)-2(-1)+3-4|}{\sqrt{2^2+(-2)^2+1^2}}
=\boxed{\frac{5}{3}}.
$$

## Part 3. Why Both Formulas Work

In either case, write the equation as $\mathbf n\cdot Y+k=0$ and choose a point $X_0$ on the line or plane. For a point $X$, the perpendicular distance is the magnitude of the scalar projection of $X-X_0$ onto the unit normal $\mathbf n/\|\mathbf n\|$:

$$
d=\left|(X-X_0)\cdot\frac{\mathbf n}{\|\mathbf n\|}\right|
=\frac{|(X-X_0)\cdot\mathbf n|}{\|\mathbf n\|}.
$$

Since $X_0$ lies on the line or plane, $\mathbf n\cdot X_0=-k$. Substituting gives

$$
(X-X_0)\cdot\mathbf n=\mathbf n\cdot X+k,
\qquad
d=\frac{|\mathbf n\cdot X+k|}{\|\mathbf n\|}.
$$

The expression $\mathbf n\cdot X+k$ is the **unnormalized signed residual**. Dividing it by $\|\mathbf n\|$ gives the signed distance in the chosen normal direction. Taking the absolute value gives the perpendicular distance.
