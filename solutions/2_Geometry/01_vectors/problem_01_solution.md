# Solution to Exercise 15: Recognition and Sketch Without a Given Name

## 1. Problem Statement

Analyze the following two second-degree equations:

1. **Equation 1 (in $\mathbb{R}^2$):**
   $$
   4x^2 + 9y^2 - 8x + 36y + 4 = 0
   $$
   - Reduce the equation to canonical form by completing the square.
   - Identify the geometric type of the curve and state its primary features (center, semiaxes, vertices, foci).

2. **Equation 2 (in $\mathbb{R}^3$):**
   $$
   4x^2 + y^2 = z^2
   $$
   - Without assuming a predefined name, systematically describe the horizontal cross-sections by planes $z = c$, and the vertical cross-sections by the planes $x = 0$ and $y = 0$, paying careful attention to the different coordinate scales.
   - Based on this cross-sectional evidence, identify the surface.

---

## 2. Theoretical Background and Concepts

1. **Second-Degree Curve Reduction in $\mathbb{R}^2$:**
   An equation $A x^2 + C y^2 + D x + E y + F = 0$ with $A \cdot C > 0$ and $A \ne C$ indicates **elliptic type**. After normalizing so $A, C > 0$ and completing the squares, the equation becomes $A(x - x_0)^2 + C(y - y_0)^2 = M$.
   - A **real non-degenerate ellipse** is obtained if and only if the normalized right-hand side is strictly positive ($M > 0$):
     $$
     \frac{(x - x_0)^2}{a^2} + \frac{(y - y_0)^2}{b^2} = 1, \qquad a = \sqrt{\frac{M}{A}}, \; b = \sqrt{\frac{M}{C}}.
     $$
   - If $M = 0$, it degenerates to a single point $(x_0, y_0)$.
   - If $M < 0$, the solution set is the empty set $\emptyset$ (no real locus).

2. **Homogeneous Quadratic Surfaces in $\mathbb{R}^3$:**
   An equation of the form $\frac{x^2}{a^2} + \frac{y^2}{b^2} = z^2$ is homogeneous of degree 2.
   - If horizontal slices $z = c \ne 0$ yield ellipses with constant aspect ratio $\frac{b}{a}$, and vertical coordinate slices yield intersecting lines passing through the origin, the surface is an **elliptic cone**.

---

## 3. Detailed Step-by-Step Solution

### Part 1: Analysis of Equation 1 ($4x^2 + 9y^2 - 8x + 36y + 4 = 0$)

#### Step 1: Group Terms and Factor Leading Coefficients
$$
(4x^2 - 8x) + (9y^2 + 36y) + 4 = 0
$$
$$
4(x^2 - 2x) + 9(y^2 + 4y) + 4 = 0
$$

#### Step 2: Complete the Squares
- For $x$: $x^2 - 2x = (x - 1)^2 - 1^2 = (x - 1)^2 - 1$
- For $y$: $y^2 + 4y = (y + 2)^2 - 2^2 = (y + 2)^2 - 4$

#### Step 3: Substitute and Simplify
$$
4\left[(x - 1)^2 - 1\right] + 9\left[(y + 2)^2 - 4\right] + 4 = 0
$$
$$
4(x - 1)^2 - 4 + 9(y + 2)^2 - 36 + 4 = 0
$$
Combine the constant terms:
$$
-4 - 36 + 4 = -36
$$
$$
4(x - 1)^2 + 9(y + 2)^2 - 36 = 0 \implies 4(x - 1)^2 + 9(y + 2)^2 = 36
$$

Divide both sides by $36$:
$$
\frac{4(x - 1)^2}{36} + \frac{9(y + 2)^2}{36} = 1 \implies \frac{(x - 1)^2}{9} + \frac{(y + 2)^2}{4} = 1
$$
Writing denominators as squares:
$$
\frac{(x - 1)^2}{3^2} + \frac{(y + 2)^2}{2^2} = 1
$$

#### Step 4: Geometric Features of the Curve
- **Classification:** An **ellipse** with horizontal major axis.
- **Center:** $S = (x_0, y_0) = (1, -2)$
- **Major Semiaxis (horizontal):** $a = 3$ (major axis length $2a = 6$)
- **Minor Semiaxis (vertical):** $b = 2$ (minor axis length $2b = 4$)
- **Vertices:**
  - On the major axis: $(x_0 \pm a, y_0) = (1 \pm 3, -2) \implies A_1(-2, -2)$ and $A_2(4, -2)$
  - On the minor axis: $(x_0, y_0 \pm b) = (1, -2 \pm 2) \implies B_1(1, -4)$ and $B_2(1, 0)$
- **Linear Eccentricity and Foci:**
  $$
  c = \sqrt{a^2 - b^2} = \sqrt{9 - 4} = \sqrt{5} \approx 2.236
  $$
  $$
  F_1 = (1 - \sqrt{5}, -2), \qquad F_2 = (1 + \sqrt{5}, -2)
  $$

---

### Part 2: Analysis of Equation 2 ($4x^2 + y^2 = z^2$)

#### Step 1: Horizontal Cross-Sections $z = c$
Substitute $z = c$ (with $c \in \mathbb{R}$):
$$
4x^2 + y^2 = c^2
$$

- **For $c = 0$:**
  $$
  4x^2 + y^2 = 0 \implies x = 0, \quad y = 0
  $$
  The cross-section is the **single point** $(0, 0, 0)$ (the apex of the surface).
- **For $c \ne 0$:**
  Divide by $c^2 > 0$:
  $$
  \frac{4x^2}{c^2} + \frac{y^2}{c^2} = 1 \iff \frac{x^2}{(c/2)^2} + \frac{y^2}{c^2} = 1
  $$
  Writing in standard form $\frac{x^2}{a(c)^2} + \frac{y^2}{b(c)^2} = 1$:
  - Semiaxis along $x$: $a(c) = \frac{|c|}{2}$
  - Semiaxis along $y$: $b(c) = |c|$
  
  **Geometric Nature of the Horizontal Slice:**
  Every horizontal slice $z = c \ne 0$ is an **ellipse** centered at $(0, 0, c)$.
  Crucially, the ratio of the semiaxes is:
  $$
  \frac{b(c)}{a(c)} = \frac{|c|}{|c|/2} = 2
  $$
  The ellipse is **twice as elongated along the $y$-axis as along the $x$-axis** for every single value of $c$.

#### Step 2: Vertical Cross-Section by $x = 0$ (the $yz$-plane)
Substitute $x = 0$ into $4x^2 + y^2 = z^2$:
$$
4(0)^2 + y^2 = z^2 \iff y^2 = z^2 \iff z^2 - y^2 = 0 \iff (z - y)(z + y) = 0
$$
This represents a **pair of straight lines** intersecting at the origin in the $yz$-plane:
$$
z = y \quad \text{and} \quad z = -y \quad (\text{slope } m = \pm 1)
$$

#### Step 3: Vertical Cross-Section by $y = 0$ (the $xz$-plane)
Substitute $y = 0$ into $4x^2 + y^2 = z^2$:
$$
4x^2 + 0^2 = z^2 \iff z^2 - 4x^2 = 0 \iff (z - 2x)(z + 2x) = 0
$$
This represents a **pair of straight lines** intersecting at the origin in the $xz$-plane:
$$
z = 2x \quad \text{and} \quad z = -2x \quad (\text{slope } m = \pm 2)
$$
Notice the lines in the $xz$-plane are steeper (slope magnitude $2$) than those in the $yz$-plane (slope magnitude $1$), which corresponds directly to the compression along the $x$-axis.

#### Step 4: Deduction of Surface Identity
Combining the evidence:
1. Horizontal slices are ellipses whose dimensions scale strictly linearly with height $|z|$,
2. All vertical slices passing through the origin are pairs of straight lines meeting at the apex $(0, 0, 0)$,
3. The surface consists of two symmetrical nappes meeting at the origin.

Therefore, the surface is an **elliptic cone** (Polish: *stożek eliptyczny*), with apex at the origin $(0, 0, 0)$, vertical axis of symmetry $Oz$, and an aspect ratio of $2 : 1$ between the $y$- and $x$-axes.

### Step 5: Required Qualitative Sketches of Both Objects

#### 1. Translated Ellipse: $\frac{(x - 1)^2}{9} + \frac{(y + 2)^2}{4} = 1$
```
                       y
                       ^
                       |
                       |  (1, 0) [Co-vertex B_2]
                  .----+----.
              .        |        .
           .           |           .
  --------+------------+------------+--------> x
        -2|          (1,-2)         | 4
  [Vertex A_1]     [Center]     [Vertex A_2]
           .           |           .
              .        |        .
                  '----+----'
                       |  (1, -4) [Co-vertex B_1]
                       |
```
*Labels:* Center $S(1, -2)$; horizontal major axis ($2a = 6$) with vertices $A_1(-2, -2)$ and $A_2(4, -2)$; vertical minor axis ($2b = 4$) with co-vertices $B_1(1, -4)$ and $B_2(1, 0)$.

#### 2. Elliptic Cone: $4x^2 + y^2 = z^2$ (Aspect Ratio $y : x = 2 : 1$)
```
                    z
                    ^
            \       |       /   Upper nappe (z > 0)
             \    .---.    /    Horizontal slice: Ellipse
              \  (  .  )  /     Major semiaxis along y: b(c) = |c|
               \  '---'  /      Minor semiaxis along x: a(c) = |c|/2
                \   |   /
                 \  |  /        Steeper trace in xz-plane (z = +-2x)
                  \ | /         Gentler trace in yz-plane (z = +-y)
  ------------------+------------------> y
                  / | \         Apex at Origin (0, 0, 0)
                 /  |  \
                /   |   \
               /  .---.  \
              /  (     )  \
             /    '---'    \    Lower nappe (z < 0)
            /       |       \
                   /
                  v x
```
*Labels:* Vertical axis of symmetry $z$; apex at $(0, 0, 0)$ connecting both nappes; elliptical cross-sections $z = c \ne 0$ with narrower $x$-dimension ($|c|/2$) and wider $y$-dimension ($|c|$); vertical traces $z = \pm 2x$ in $xz$-plane and $z = \pm y$ in $yz$-plane.

---

## 4. Verification and Consistency Checks

1. **Equation 1 Point Check:**
   Substitute co-vertex $B_2(1, 0)$ into $4x^2 + 9y^2 - 8x + 36y + 4 = 0$:
   $$
   4(1)^2 + 9(0)^2 - 8(1) + 36(0) + 4 = 4 + 0 - 8 + 0 + 4 = 0 \quad (\checkmark)
   $$
   Substitute vertex $A_2(4, -2)$ into the equation:
   $$
   4(16) + 9(4) - 8(4) + 36(-2) + 4 = 64 + 36 - 32 - 72 + 4 = 104 - 104 = 0 \quad (\checkmark)
   $$

2. **Equation 2 Straight Line Generator Check:**
   Consider the spatial line $L(t) = t\left(\frac{1}{2}, 1, \sqrt{2}\right)$:
   - $x(t) = \frac{1}{2}t$, $y(t) = t$, $z(t) = \sqrt{2}t$.
   - Evaluate $4x^2 + y^2$:
     $$
     4\left(\frac{1}{2}t\right)^2 + t^2 = 4\left(\frac{1}{4}t^2\right) + t^2 = t^2 + t^2 = 2t^2
     $$
   - Evaluate $z^2$:
     $$
     z^2 = (\sqrt{2}t)^2 = 2t^2
     $$
   Since $4x^2 + y^2 = z^2$ holds for all $t \in \mathbb{R}$, this straight line lies entirely on the surface, confirming the ruled nature of the elliptic cone.
