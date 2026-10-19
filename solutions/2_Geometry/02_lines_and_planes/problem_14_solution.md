# Exercise 14. Contrast: Intersection and Parallelism

## Given

$$
P=(0,0,1)
$$

$$
\mathbf{v}_1=(2,1,-1),\qquad \mathbf{v}_2=(2,1,0)
$$

The plane is

$$
\Pi:z=0
$$

Its normal vector is

$$
\boxed{\mathbf{n}=(0,0,1)}
$$

## 1. First Line: Direction \(\mathbf{v}_1=(2,1,-1)\)

The line is

$$
L_1:(x,y,z)=(0,0,1)+t(2,1,-1)
$$

Therefore,

$$
x=2t,\qquad y=t,\qquad z=1-t
$$

To find the intersection with \(z=0\), set

$$
1-t=0
$$

$$
t=1
$$

Substitute \(t=1\):

$$
x=2(1)=2
$$

$$
y=1
$$

$$
z=0
$$

Therefore, the intersection point is

$$
\boxed{Q=(2,1,0)}
$$

Check the plane equation:

$$
z=0
$$

The point lies on the plane.

## 2. Second Line: Direction \(\mathbf{v}_2=(2,1,0)\)

The line is

$$
L_2:(x,y,z)=(0,0,1)+t(2,1,0)
$$

Therefore,

$$
x=2t,\qquad y=t,\qquad z=1
$$

The \(z\)-coordinate is always \(1\), regardless of \(t\).

Since the plane requires \(z=0\), the line never intersects it.

$$
\boxed{L_2\cap\Pi=\varnothing}
$$

## 3. Explain Why the Second Line Is Parallel to the Plane

Calculate the dot product of the direction vector and the normal vector:

$$
\mathbf{v}_2\cdot\mathbf{n}
=(2,1,0)\cdot(0,0,1)
$$

$$
=0+0+0=0
$$

The direction vector is perpendicular to the plane's normal, so the line's direction is parallel to the plane. Since the line's point has \(z=1\), it does not lie in the plane.

## Final Answers

- **First line:** Intersects the plane at \(\boxed{(2,1,0)}\).
- **Second line:** Parallel to the plane with no intersection.
