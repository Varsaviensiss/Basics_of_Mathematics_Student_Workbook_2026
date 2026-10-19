# Exercise 9. Distances

## Part 1. Distance from a Point to a Line

### Given

$$
P=(2,3)
$$

$$
3x+4y-10=0
$$

The distance from a point \((x_0,y_0)\) to a line \(ax+by+c=0\) is

$$
d=\frac{|ax_0+by_0+c|}{\sqrt{a^2+b^2}}
$$

Substitute \(a=3\), \(b=4\), \(c=-10\), and \(P=(2,3)\):

$$
d=\frac{|3(2)+4(3)-10|}{\sqrt{3^2+4^2}}
$$

$$
=\frac{|6+12-10|}{\sqrt{9+16}}
$$

$$
=\frac8{\sqrt{25}}
$$

$$
\boxed{d= \frac85}
$$

## Part 2. Distance from a Point to a Plane

### Given

$$
Q=(2,-1,3)
$$

$$
2x-2y+z-4=0
$$

The distance from a point \((x_0,y_0,z_0)\) to a plane \(ax+by+cz+d=0\) is

$$
d=\frac{|ax_0+by_0+cz_0+d|}{\sqrt{a^2+b^2+c^2}}
$$

Substitute the values:

$$
d=\frac{|2(2)-2(-1)+3-4|}{\sqrt{2^2+(-2)^2+1^2}}
$$

$$
=\frac{|4+2+3-4|}{\sqrt{4+4+1}}
$$

$$
=\frac5{\sqrt9}
$$

$$
\boxed{d=\frac53}
$$

## Part 3. Compare the Formulas

For a line in two dimensions:

$$
d=\frac{|ax_0+by_0+c|}{\sqrt{a^2+b^2}}
$$

For a plane in three dimensions:

$$
d=\frac{|ax_0+by_0+cz_0+d|}{\sqrt{a^2+b^2+c^2}}
$$

Both formulas use the same geometric idea:

- The numerator measures the point's signed displacement relative to the line or plane equation.
- The denominator is the length of the normal vector.
- The absolute value ensures that distance is nonnegative.

## Final Answers

$$
\boxed{d(P,\text{line})=\frac85}
$$

$$
\boxed{d(Q,\text{plane})=\frac53}
$$
