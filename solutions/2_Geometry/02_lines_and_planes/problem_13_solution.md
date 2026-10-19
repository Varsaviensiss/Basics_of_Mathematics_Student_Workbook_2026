# Exercise 13. Closest Point on a Plane

## Given

$$
\Pi:x+2y+2z=4
$$

$$
P=(3,0,0)
$$

## 1. Find the Normal Vector

The plane's normal vector is

$$
\boxed{\mathbf{n}=(1,2,2)}
$$

Its squared length is

$$
|\mathbf{n}|^2=1^2+2^2+2^2
$$

$$
=1+4+4=9
$$

## 2. Find the Closest Point

The orthogonal projection of \(P\) onto the plane is

$$
H=P-\frac{\mathbf{n}\cdot P-4}{|\mathbf{n}|^2}\mathbf{n}
$$

Calculate the dot product:

$$
\mathbf{n}\cdot P=1(3)+2(0)+2(0)=3
$$

Substitute:

$$
H=(3,0,0)-\frac{3-4}{9}(1,2,2)
$$

$$
=(3,0,0)+\frac19(1,2,2)
$$

Therefore,

$$
\boxed{H=\left(\frac{28}{9},\frac29,\frac29\right)}
$$

## 3. Check That \(H\) Lies on the Plane

$$
\frac{28}{9}+2\left(\frac29\right)+2\left(\frac29\right)
$$

$$
=\frac{28}{9}+\frac49+\frac49
$$

$$
=\frac{36}{9}=4
$$

Thus, \(H\) lies on the plane.

## 4. Find the Distance

The vector from \(P\) to \(H\) is

$$
\overrightarrow{PH}=H-P
$$

$$
=\left(\frac{28}{9}-3,\frac29,\frac29\right)
$$

$$
=\left(\frac19,\frac29,\frac29\right)
$$

Its length is

$$
d(P,\Pi)=|\overrightarrow{PH}|
$$

$$
=\sqrt{\left(\frac19\right)^2+\left(\frac29\right)^2+\left(\frac29\right)^2}
$$

$$
=\sqrt{\frac{1+4+4}{81}}
$$

$$
=\sqrt{\frac9{81}}
$$

$$
\boxed{d(P,\Pi)=\frac13}
$$

## 5. Verify Perpendicularity

The displacement vector is

$$
\overrightarrow{PH}=\frac19(1,2,2)
$$

Since it is a scalar multiple of the normal vector, it is perpendicular to the plane.

Equivalently,

$$
\overrightarrow{PH}\times\mathbf{n}=\mathbf{0}
$$

## Final Answers

- **Closest point:** \(\displaystyle H=\left(\frac{28}{9},\frac29,\frac29\right)\)
- **Distance:** \(\displaystyle \frac13\)
- **Perpendicularity:** \(\overrightarrow{PH}\) is parallel to the plane's normal vector.
