# Exercise 14. Closest Point on a Line

## Given

$$
P=(4,1),\qquad \mathbf{v}=(1,2)
$$

The line passes through the origin and has direction vector \(\mathbf{v}\).

## 1. Find the Closest Point on the Line

Every point on the line can be written as

$$
Q=t\mathbf{v}
$$

The closest point is the projection of \(\overrightarrow{OP}=(4,1)\) onto \(\mathbf{v}\):

$$
\overrightarrow{OQ}
=\frac{\overrightarrow{OP}\cdot\mathbf{v}}{\mathbf{v}\cdot\mathbf{v}}\mathbf{v}
$$

Calculate the dot products:

$$
\overrightarrow{OP}\cdot\mathbf{v}=4(1)+1(2)=6
$$

$$
\mathbf{v}\cdot\mathbf{v}=1^2+2^2=5
$$

Substitute:

$$
\overrightarrow{OQ}=\frac65(1,2)
$$

$$
=\left(\frac65,\frac{12}{5}\right)
$$

Therefore, the closest point is

$$
\boxed{Q=\left(\frac65,\frac{12}{5}\right)}
$$

## 2. Find the Distance from \(P\) to the Line

The vector from \(Q\) to \(P\) is

$$
\overrightarrow{QP}=P-Q
$$

$$
=(4,1)-\left(\frac65,\frac{12}{5}\right)
$$

$$
=\left(\frac{20}{5}-\frac65,\frac55-\frac{12}{5}\right)
$$

$$
\boxed{\overrightarrow{QP}=\left(\frac{14}{5},-\frac75\right)}
$$

The distance is the length of this vector:

$$
d(P,Q)=|\overrightarrow{QP}|
$$

$$
=\sqrt{\left(\frac{14}{5}\right)^2+\left(-\frac75\right)^2}
$$

$$
=\sqrt{\frac{196}{25}+\frac{49}{25}}
$$

$$
=\sqrt{\frac{245}{25}}
$$

$$
=\frac{\sqrt{245}}5
$$

Since \(245=49\cdot5\),

$$
\boxed{d(P,\text{line})=\frac{7\sqrt5}{5}}
$$

## 3. Verify Perpendicularity

The shortest segment from a point to a line is perpendicular to the line.

Check the dot product:

$$
\overrightarrow{QP}\cdot\mathbf{v}
=\left(\frac{14}{5},-\frac75\right)\cdot(1,2)
$$

$$
=\frac{14}{5}-\frac{14}{5}
$$

$$
=0
$$

Therefore,

$$
\boxed{\overrightarrow{QP}\cdot\mathbf{v}=0}
$$

## Final Answers

- **Closest point:** \(\displaystyle Q=\left(\frac65,\frac{12}{5}\right)\)
- **Distance to the line:** \(\displaystyle \frac{7\sqrt5}{5}\)
- **Verification:** The vector from \(Q\) to \(P\) is perpendicular to the line's direction vector.
