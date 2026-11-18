# Exercise 9. Ellipsoid and Its Cross-Sections

## Question

Consider the ellipsoid

$$
\frac{x^2}{9}+\frac{y^2}{4}+\frac{z^2}{16}=1.
$$

Find the lengths of its three semiaxes. Describe the cross-section at $z=0$ and the cross-sections at $z=c$ for $|c|<4$. Explain how the cross-sections change as $c$ varies.

## Solution

### 1. Semiaxis Lengths

The ellipsoid is centered at $(0,0,0)$. Its semiaxis lengths are $\sqrt{9}=3$ along the $x$-axis, $\sqrt{4}=2$ along the $y$-axis, and $\sqrt{16}=4$ along the $z$-axis.

### 2. Cross-Section at $z=0$

Substituting $z=0$ gives

$$
\frac{x^2}{9}+\frac{y^2}{4}=1.
$$

This is an ellipse in the $xy$-plane with semiaxis lengths $3$ and $2$.

### 3. Cross-Sections at $z=c$ for $|c|<4$

Substituting $z=c$ gives

$$
\frac{x^2}{9}+\frac{y^2}{4}=1-\frac{c^2}{16}.
$$

Since $|c|<4$, the right-hand side is positive. Dividing by it gives

$$
\frac{x^2}{9(1-c^2/16)}+\frac{y^2}{4(1-c^2/16)}=1.
$$

The cross-section is an ellipse centered at $(0,0,c)$, with semiaxis lengths

$$
3\sqrt{1-\frac{c^2}{16}}
\qquad\text{and}\qquad
2\sqrt{1-\frac{c^2}{16}}.
$$

### 4. How the Cross-Sections Change

The largest horizontal section occurs at $c=0$. Both semiaxes shrink by the same factor as $|c|$ increases, so the ellipses keep the same proportions. At $c=4$ and $c=-4$, the sections reduce to the single points $(0,0,4)$ and $(0,0,-4)$, respectively.
