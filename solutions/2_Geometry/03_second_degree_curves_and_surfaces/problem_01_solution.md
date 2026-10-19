# Exercise 1. Recognizing Curves from Canonical Form

We are given four equations:

1. \(x^2+y^2=9\)
2. \(\dfrac{x^2}{16}+\dfrac{y^2}{9}=1\)
3. \(y^2=8x\)
4. \(\dfrac{x^2}{9}-\dfrac{y^2}{4}=1\)

We will identify each curve, determine its most important features, and explain how its equation reveals its type.

## 1. The Circle: \(x^2+y^2=9\)

### Step 1: Recognize the curve

The standard equation of a circle centered at the origin is

$$
x^2+y^2=r^2
$$

Compare this with the given equation:

$$
x^2+y^2=9
$$

Therefore,

$$
r^2=9
$$

$$
r=\sqrt{9}=3
$$

The curve is a **circle**.

### Step 2: Identify the important features

- **Center:** \((0,0)\)
- **Radius:** \(r=3\)
- **Horizontal intercepts:** \((-3,0)\) and \((3,0)\)
- **Vertical intercepts:** \((0,-3)\) and \((0,3)\)
- **Symmetry:** About both coordinate axes and the origin.

To find the horizontal intercepts, set \(y=0\):

$$
x^2+0^2=9
$$

$$
x^2=9
$$

$$
x=\pm3
$$

To find the vertical intercepts, set \(x=0\):

$$
0^2+y^2=9
$$

$$
y^2=9
$$

$$
y=\pm3
$$

### Step 3: Sketch the curve

To sketch the circle, plot the four points

$$
(-3,0),\quad (3,0),\quad (0,-3),\quad (0,3)
$$

Then draw a smooth circle passing through all four points, centered at the origin.

### Why is it a circle?

Both variables are squared, their coefficients are equal and positive, and their sum equals a positive constant. These are the defining features of a circle in this canonical form.

---

## 2. The Ellipse: \(\dfrac{x^2}{16}+\dfrac{y^2}{9}=1\)

### Step 1: Recognize the curve

The standard equation of an ellipse centered at the origin is

$$
\frac{x^2}{a^2}+\frac{y^2}{b^2}=1
$$

Compare it with the given equation:

$$
\frac{x^2}{16}+\frac{y^2}{9}=1
$$

Therefore,

$$
a^2=16,\qquad b^2=9
$$

Taking square roots gives

$$
a=4,\qquad b=3
$$

Since both squared terms are added and have positive coefficients, the curve is an **ellipse**.

### Step 2: Identify the important features

- **Center:** \((0,0)\)
- **Horizontal semi-axis:** \(a=4\)
- **Vertical semi-axis:** \(b=3\)
- **Major axis:** Horizontal, length \(2a=8\)
- **Minor axis:** Vertical, length \(2b=6\)
- **Vertices:** \((-4,0)\) and \((4,0)\)
- **Co-vertices:** \((0,-3)\) and \((0,3)\)

The horizontal semi-axis is longer because

$$
4>3
$$

Therefore, the ellipse stretches farther horizontally than vertically.

### Step 3: Find the foci

For an ellipse with a horizontal major axis,

$$
c^2=a^2-b^2
$$

Substitute the values:

$$
c^2=16-9
$$

$$
c^2=7
$$

$$
c=\sqrt7
$$

Thus, the foci are

$$
\boxed{(-\sqrt7,0)\text{ and }(\sqrt7,0)}
$$

### Step 4: Sketch the curve

Plot the center and the four axis endpoints:

$$
(0,0),\quad (-4,0),\quad (4,0),\quad (0,-3),\quad (0,3)
$$

Draw a smooth, closed oval through the four endpoints, wider horizontally than vertically.

### Why is it an ellipse?

Both variables are squared, their terms are added, and both denominators are positive. The unequal denominators indicate different horizontal and vertical semi-axis lengths.

---

## 3. The Parabola: \(y^2=8x\)

### Step 1: Recognize the curve

The standard equation of a parabola opening to the right or left is

$$
y^2=4px
$$

Compare this with

$$
y^2=8x
$$

Therefore,

$$
4p=8
$$

$$
p=2
$$

Since the coefficient on the right-hand side is positive, the parabola opens to the **right**.

### Step 2: Identify the important features

- **Vertex:** \((0,0)\)
- **Axis of symmetry:** The \(x\)-axis
- **Opening direction:** Right
- **Focal parameter:** \(p=2\)
- **Focus:** \((p,0)=(2,0)\)
- **Directrix:** \(x=-p=-2\)

The focus and directrix are located the same distance from the vertex on opposite sides.

### Step 3: Find additional points for the sketch

Starting with

$$
y^2=8x
$$

Solve for \(x\):

$$
x=\frac{y^2}{8}
$$

Choose convenient values of \(y\).

When \(y=0\):

$$
x=\frac{0^2}{8}=0
$$

So one point is

$$
(0,0)
$$

When \(y=4\):

$$
x=\frac{4^2}{8}=\frac{16}{8}=2
$$

So another point is

$$
(2,4)
$$

When \(y=-4\):

$$
x=\frac{(-4)^2}{8}=\frac{16}{8}=2
$$

So another point is

$$
(2,-4)
$$

### Step 4: Sketch the curve

Plot the points

$$
(0,0),\quad (2,4),\quad (2,-4)
$$

Mark the focus \((2,0)\) and the directrix \(x=-2\). Draw a smooth, U-shaped curve opening to the right and symmetric about the \(x\)-axis.

### Why is it a parabola?

Only one variable is squared, while the other variable appears to the first power. The form \(y^2=4px\) identifies a horizontal parabola.

---

## 4. The Hyperbola: \(\dfrac{x^2}{9}-\dfrac{y^2}{4}=1\)

### Step 1: Recognize the curve

The standard equation of a horizontal hyperbola centered at the origin is

$$
\frac{x^2}{a^2}-\frac{y^2}{b^2}=1
$$

Compare this with

$$
\frac{x^2}{9}-\frac{y^2}{4}=1
$$

Therefore,

$$
a^2=9,\qquad b^2=4
$$

Taking square roots gives

$$
a=3,\qquad b=2
$$

Because the squared terms are **subtracted**, the curve is a hyperbola. Since the positive term contains \(x^2\), the branches open to the left and right.

### Step 2: Identify the important features

- **Center:** \((0,0)\)
- **Horizontal semi-axis:** \(a=3\)
- **Vertical parameter:** \(b=2\)
- **Vertices:** \((-3,0)\) and \((3,0)\)
- **Transverse axis:** Horizontal, length \(2a=6\)
- **Conjugate axis:** Vertical, length \(2b=4\)

### Step 3: Find the foci

For a hyperbola,

$$
c^2=a^2+b^2
$$

Substitute the values:

$$
c^2=9+4
$$

$$
c^2=13
$$

$$
c=\sqrt{13}
$$

Therefore, the foci are

$$
\boxed{(-\sqrt{13},0)\text{ and }(\sqrt{13},0)}
$$

### Step 4: Find the asymptotes

For this horizontal hyperbola, the asymptotes are

$$
y=\pm\frac{b}{a}x
$$

Substitute \(a=3\) and \(b=2\):

$$
\boxed{y=\frac23x\qquad\text{and}\qquad y=-\frac23x}
$$

The branches approach these lines as they extend away from the center.

### Step 5: Sketch the curve

Plot the center and vertices:

$$
(0,0),\quad (-3,0),\quad (3,0)
$$

Draw the two asymptotes through the origin:

$$
y=\frac23x,\qquad y=-\frac23x
$$

Then draw two separate branches, one opening to the right from \((3,0)\) and the other opening to the left from \((-3,0)\). The branches approach the asymptotes but never intersect them.

### Why is it a hyperbola?

Both variables are squared, but the terms are subtracted rather than added. The positive \(x^2\) term identifies the horizontal direction in which the branches open.

---

## Final Comparison

| Equation | Curve | Center or vertex | Important features |
|---|---|---|---|
| \(x^2+y^2=9\) | Circle | Center: \((0,0)\) | Radius \(3\) |
| \(\dfrac{x^2}{16}+\dfrac{y^2}{9}=1\) | Ellipse | Center: \((0,0)\) | Semi-axes \(4,3\); foci \((\pm\sqrt7,0)\) |
| \(y^2=8x\) | Parabola | Vertex: \((0,0)\) | Opens right; focus \((2,0)\); directrix \(x=-2\) |
| \(\dfrac{x^2}{9}-\dfrac{y^2}{4}=1\) | Hyperbola | Center: \((0,0)\) | Opens left and right; asymptotes \(y=\pm\frac23x\); foci \((\pm\sqrt{13},0)\) |

## How to Recognize Each Curve

The key is to examine whether the variables are squared and how their squared terms are combined.

- **Circle:** \(x^2\) and \(y^2\) have equal positive coefficients and are added.
- **Ellipse:** \(x^2\) and \(y^2\) are added with positive but generally unequal coefficients.
- **Parabola:** Only one variable is squared.
- **Hyperbola:** \(x^2\) and \(y^2\) are subtracted.

These patterns allow us to identify the curve directly from its canonical equation before calculating its features or sketching it.
