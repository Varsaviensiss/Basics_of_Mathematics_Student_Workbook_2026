
## Exercise 15. Recognition and Sketch Without a Given Name

### Part 1. Reduce the Equation to Canonical Form

**Given equation:**

\[
4x^2+9y^2-8x+36y+4=0
\]

Group the terms:

\[
4(x^2-2x)+9(y^2+4y)+4=0
\]

Complete the square:

\[
4[(x-1)^2-1]+9[(y+2)^2-4]+4=0
\]

Expand and simplify:

\[
4(x-1)^2-4+9(y+2)^2-36+4=0
\]

\[
4(x-1)^2+9(y+2)^2=36
\]

Divide both sides by \(36\):

\[
\boxed{\frac{(x-1)^2}{9}+\frac{(y+2)^2}{4}=1}
\]

### Center and Semiaxis Lengths

Compare with the standard equation:

\[
\frac{(x-h)^2}{a^2}+\frac{(y-k)^2}{b^2}=1
\]

Therefore:

- **Center:** \(C=(1,-2)\)
- **Horizontal semiaxis:** \(a=\sqrt{9}=3\)
- **Vertical semiaxis:** \(b=\sqrt{4}=2\)
- **Vertices:** \((-2,-2)\) and \((4,-2)\)
- **Co-vertices:** \((1,-4)\) and \((1,0)\)

Since \(a>b\), the major axis is horizontal.

**Sketch:** Draw an ellipse centered at \((1,-2)\), extending \(3\) units left and right and \(2\) units up and down.

---

### Part 2. Analyze the Surface Using Cross-Sections

**Given equation:**

\[
4x^2+y^2=z^2
\]

#### 1. Horizontal Cross-Sections: \(z=c\)

Substitute \(z=c\):

\[
4x^2+y^2=c^2
\]

For \(c\neq0\), divide by \(c^2\):

\[
\boxed{\frac{x^2}{c^2/4}+\frac{y^2}{c^2}=1}
\]

These cross-sections are ellipses with semiaxis lengths

\[
a_x=\frac{|c|}{2},\qquad a_y=|c|.
\]

The ellipse is twice as wide along the \(y\)-direction as along the \(x\)-direction.

When \(c=0\):

\[
4x^2+y^2=0
\]

This gives only the point \((0,0,0)\).

#### 2. Cross-Section by the Plane \(x=0\)

Substitute \(x=0\):

\[
y^2=z^2
\]

Therefore:

\[
\boxed{z=\pm y}
\]

The cross-section consists of two intersecting straight lines in the \(yz\)-plane.

#### 3. Cross-Section by the Plane \(y=0\)

Substitute \(y=0\):

\[
4x^2=z^2
\]

Therefore:

\[
\boxed{z=\pm2x}
\]

The cross-section consists of two intersecting straight lines in the \(xz\)-plane.

#### 4. Identify the Surface

The horizontal cross-sections are ellipses whose sizes increase with \(|z|\). The vertical cross-sections through the \(z\)-axis consist of intersecting straight lines.

Therefore, the surface is an **elliptic double cone** with its vertex at the origin.

The equation shows that the cone is narrower along the \(x\)-direction than along the \(y\)-direction.

**Sketch:** Draw two cone-shaped parts meeting at the origin, extending upward and downward along the \(z\)-axis. Their horizontal cross-sections are ellipses, wider along \(y\) than \(x\).
