# Exercise 10. Projection of a Point onto a Plane

## Given

$$
P=(2,1,3)
$$

$$
\Pi:x+y+z=3
$$

## 1. Find the Normal Vector

The plane's normal vector is

$$
\boxed{\mathbf{n}=(1,1,1)}
$$

The orthogonal projection lies along the normal direction.

## 2. Find the Projection Point

The plane equation is

$$
\mathbf{n}\cdot\mathbf{x}=3
$$

Evaluate the plane expression at \(P\):

$$
2+1+3=6
$$

The signed difference from the plane constant is

$$
6-3=3
$$

The squared length of the normal vector is

$$
\mathbf{n}\cdot\mathbf{n}=1^2+1^2+1^2=3
$$

The projection is given by

$$
H=P-\frac{\mathbf{n}\cdot P-3}{\mathbf{n}\cdot\mathbf{n}}\mathbf{n}
$$

Substitute:

$$
H=(2,1,3)-\frac{6-3}{3}(1,1,1)
$$

$$
=(2,1,3)-(1,1,1)
$$

Therefore,

$$
\boxed{H=(1,0,2)}
$$

## 3. Find the Reflection of \(P\) Across the Plane

The projection point \(H\) is the midpoint between \(P\) and its reflection \(P'\).

Thus,

$$
H=\frac{P+P'}2
$$

Rearrange:

$$
P'=2H-P
$$

Substitute:

$$
P'=2(1,0,2)-(2,1,3)
$$

$$
=(2,0,4)-(2,1,3)
$$

$$
\boxed{P'=(0,-1,1)}
$$

## 4. Check That the Projection Lies on the Plane

$$
1+0+2=3
$$

Therefore, \(H\) lies on the plane.

## 5. Check the Midpoint of \(P\) and \(P'\)

$$
\frac{P+P'}2
=\frac{(2,1,3)+(0,-1,1)}2
$$

$$
=\frac{(2,0,4)}2
$$

$$
=(1,0,2)=H
$$

The midpoint lies on the plane because

$$
1+0+2=3
$$

## Final Answers

- **Orthogonal projection:** \(\boxed{H=(1,0,2)}\)
- **Reflection:** \(\boxed{P'=(0,-1,1)}\)
