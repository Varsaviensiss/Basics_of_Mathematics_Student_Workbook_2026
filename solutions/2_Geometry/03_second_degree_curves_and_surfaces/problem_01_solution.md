# Exercise 1. Recognizing Curves from Canonical Form

## Given

Recognize the following curves, identify their most important features, and describe their shapes.

\[
\text{(1)}\quad x^2+y^2=9
\]

\[
\text{(2)}\quad \frac{x^2}{16}+\frac{y^2}{9}=1
\]

\[
\text{(3)}\quad y^2=8x
\]

\[
\text{(4)}\quad \frac{x^2}{9}-\frac{y^2}{4}=1
\]

## 1. Identify the Circle

The first equation is

\[
x^2+y^2=9
\]

The canonical equation of a circle is

\[
(x-h)^2+(y-k)^2=r^2
\]

Comparing the two equations, we obtain

\[
h=0,\qquad k=0,\qquad r^2=9
\]

Therefore,

\[
r=3
\]

**Important features:**

- Type: Circle
- Center: \(C=(0,0)\)
- Radius: \(r=3\)
- Intercepts: \((3,0),(-3,0),(0,3),(0,-3)\)

**Sketch:** Draw a circle centered at the origin, passing through the four intercepts listed above.

## 2. Identify the Ellipse

The second equation is

\[
\frac{x^2}{16}+\frac{y^2}{9}=1
\]

The canonical equation of an ellipse centered at the origin is

\[
\frac{x^2}{a^2}+\frac{y^2}{b^2}=1
\]

Comparing the equations gives

\[
a^2=16,\qquad b^2=9
\]

Therefore,

\[
a=4,\qquad b=3
\]

Since \(a>b\), the ellipse is stretched farther along the \(x\)-axis.

**Important features:**

- Type: Ellipse
- Center: \(C=(0,0)\)
- Horizontal semiaxis: \(a=4\)
- Vertical semiaxis: \(b=3\)
- Vertices: \((4,0),(-4,0)\)
- Co-vertices: \((0,3),(0,-3)\)

**Sketch:** Draw a horizontal ellipse centered at the origin, extending from \(x=-4\) to \(x=4\) and from \(y=-3\) to \(y=3\).

## 3. Identify the Parabola

The third equation is

\[
y^2=8x
\]

The canonical equation of a parabola opening to the right is

\[
y^2=4px
\]

Comparing the equations,

\[
4p=8
\]

Thus,

\[
p=2
\]

**Important features:**

- Type: Parabola
- Vertex: \(V=(0,0)\)
- Axis of symmetry: \(y=0\), or the \(x\)-axis
- Opening direction: To the right
- Focus: \(F=(2,0)\)
- Directrix: \(x=-2\)

To find some points, let \(x=2\):

\[
y^2=8(2)=16
\]

\[
y=\pm4
\]

Therefore, two points on the parabola are

\[
(2,4),\qquad (2,-4)
\]

**Sketch:** Draw a right-opening parabola with vertex at the origin, passing through \((2,4)\) and \((2,-4)\).

## 4. Identify the Hyperbola

The fourth equation is

\[
\frac{x^2}{9}-\frac{y^2}{4}=1
\]

The canonical equation of a horizontal hyperbola centered at the origin is

\[
\frac{x^2}{a^2}-\frac{y^2}{b^2}=1
\]

Comparing the equations gives

\[
a^2=9,\qquad b^2=4
\]

Therefore,

\[
a=3,\qquad b=2
\]

**Important features:**

- Type: Hyperbola
- Center: \(C=(0,0)\)
- Transverse semiaxis: \(a=3\)
- Conjugate semiaxis: \(b=2\)
- Vertices: \((3,0),(-3,0)\)
- Opening direction: Left and right

The asymptotes are given by

\[
y=\pm\frac ba x
\]

Substituting \(a=3\) and \(b=2\),

\[
\boxed{y=\pm\frac23x}
\]

**Sketch:** Draw two separate branches opening to the left and right, with vertices at \((-3,0)\) and \((3,0)\). The branches approach the two asymptotes as they extend outward.

## 5. Comparison of the Four Curves

| Equation | Curve | Main feature |
|---|---|---|
| \(x^2+y^2=9\) | Circle | Constant distance \(3\) from the origin |
| \(\frac{x^2}{16}+\frac{y^2}{9}=1\) | Ellipse | Closed curve, stretched horizontally |
| \(y^2=8x\) | Parabola | Opens to the right |
| \(\frac{x^2}{9}-\frac{y^2}{4}=1\) | Hyperbola | Two branches opening left and right |

## Final Answer

The four equations represent a **circle, an ellipse, a parabola, and a hyperbola**, respectively.

Their types can be recognized from their canonical forms:

- A circle has equal positive coefficients for \(x^2\) and \(y^2\).
- An ellipse has two positive squared terms with different denominators.
- A parabola has only one variable squared.
- A hyperbola has squared terms with opposite signs.
