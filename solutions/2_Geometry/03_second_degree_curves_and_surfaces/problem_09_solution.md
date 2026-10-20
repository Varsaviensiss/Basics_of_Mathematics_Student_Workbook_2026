
## Exercise 9. Ellipsoid and Its Cross-Sections

Given the equation

\[
\frac{x^2}{9}+\frac{y^2}{4}+\frac{z^2}{16}=1.
\]

### 1. Semiaxis lengths

Compare the equation with the standard ellipsoid equation:

\[
\frac{x^2}{a^2}+\frac{y^2}{b^2}+\frac{z^2}{c^2}=1.
\]

Therefore, the semiaxis lengths are

\[
a=3,\qquad b=2,\qquad c=4.
\]

The ellipsoid is centered at \((0,0,0)\), with semiaxes of lengths \(3\), \(2\), and \(4\) along the \(x\)-, \(y\)-, and \(z\)-axes, respectively.

### 2. Cross-section \(z=0\)

Substitute \(z=0\) into the equation:

\[
\frac{x^2}{9}+\frac{y^2}{4}=1.
\]

This is an ellipse in the \(xy\)-plane with semiaxes \(3\) and \(2\).

### 3. Cross-sections \(z=c\), where \(|c|<4\)

Substitute \(z=c\):

\[
\frac{x^2}{9}+\frac{y^2}{4}+\frac{c^2}{16}=1.
\]

Rearrange:

\[
\frac{x^2}{9}+\frac{y^2}{4}
=1-\frac{c^2}{16}.
\]

Since \(|c|<4\), the right-hand side is positive. Dividing by it gives

\[
\frac{x^2}{9\left(1-\frac{c^2}{16}\right)}
+
\frac{y^2}{4\left(1-\frac{c^2}{16}\right)}
=1.
\]

Thus, each cross-section is an ellipse with semiaxis lengths

\[
a_c=3\sqrt{1-\frac{c^2}{16}},
\]

\[
b_c=2\sqrt{1-\frac{c^2}{16}}.
\]

### 4. How the cross-sections change

- At \(c=0\), the ellipse is largest, with semiaxes \(3\) and \(2\).
- As \(|c|\) increases toward \(4\), both semiaxes decrease.
- As \(c\to 4\) or \(c\to -4\), the ellipses shrink to a point.
- At \(c=\pm4\), the cross-section is the single point \((0,0,\pm4)\).

**Conclusion:** The horizontal cross-sections are ellipses that become smaller as we move away from the \(xy\)-plane in either direction along the \(z\)-axis. Together, they form an ellipsoid.
