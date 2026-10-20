
# Problem 9. Analyze the Ellipsoid

Given the surface:

\[
\frac{x^2}{9}+\frac{y^2}{4}+\frac{z^2}{16}=1
\]

## 1. Identify the Surface

The equation is in the standard form of an ellipsoid:

\[
\frac{x^2}{a^2}+\frac{y^2}{b^2}+\frac{z^2}{c^2}=1
\]

Comparing the equations:

\[
a^2=9,\qquad b^2=4,\qquad c^2=16
\]

Therefore, the semi-axis lengths are:

\[
a=3,\qquad b=2,\qquad c=4
\]

- Surface type: Ellipsoid
- Center: \((0,0,0)\)
- Semi-axis lengths: \(3,2,4\)

## 2. Find the Intercepts

Set two variables equal to zero at a time.

**x-intercepts:** Set \(y=0\) and \(z=0\).

\[
\frac{x^2}{9}=1
\]

\[
x=\pm3
\]

Points:

\[
(\pm3,0,0)
\]

**y-intercepts:** Set \(x=0\) and \(z=0\).

\[
\frac{y^2}{4}=1
\]

\[
y=\pm2
\]

Points:

\[
(0,\pm2,0)
\]

**z-intercepts:** Set \(x=0\) and \(y=0\).

\[
\frac{z^2}{16}=1
\]

\[
z=\pm4
\]

Points:

\[
(0,0,\pm4)
\]

## 3. Find the Horizontal Traces

Set \(z=c\):

\[
\frac{x^2}{9}+\frac{y^2}{4}+\frac{c^2}{16}=1
\]

Rearranging:

\[
\frac{x^2}{9}+\frac{y^2}{4}
=1-\frac{c^2}{16}
\]

For \(|c|<4\), divide by the right-hand side:

\[
\frac{x^2}{9\left(1-\frac{c^2}{16}\right)}
+
\frac{y^2}{4\left(1-\frac{c^2}{16}\right)}
=1
\]

These traces are ellipses.

- If \(|c|<4\), the trace is an ellipse.
- If \(c=\pm4\), the trace is a single point.
- If \(|c|>4\), there are no real points.

The semi-axis lengths of each horizontal ellipse are:

\[
a_x=3\sqrt{1-\frac{c^2}{16}}
\]

\[
a_y=2\sqrt{1-\frac{c^2}{16}}
\]

## Final Answers

1. Surface: Ellipsoid.
2. Center: \((0,0,0)\).
3. Semi-axis lengths: \(3\) along the \(x\)-axis, \(2\) along the \(y\)-axis, and \(4\) along the \(z\)-axis.
4. x-intercepts: \((\pm3,0,0)\).
5. y-intercepts: \((0,\pm2,0)\).
6. z-intercepts: \((0,0,\pm4)\).
7. Horizontal traces: Ellipses for \(|c|<4\), points for \(c=\pm4\), and no real points for \(|c|>4\).
