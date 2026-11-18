# Exercise 15. Recognition and Sketch Without a Given Name

## Question

1. Reduce $4x^2+9y^2-8x+36y+4=0$ to canonical form. Identify the curve, find its center and semiaxis lengths, and draw a labeled sketch showing its four axis endpoints.
2. Identify the surface $4x^2+y^2=z^2$ using its cross-sections in the planes $z=c$, $x=0$, and $y=0$. Draw a labeled sketch of the surface and show how the horizontal semiaxis lengths compare.

## Solution

### Part 1. Identify the Curve

Group the terms and complete the square:

$$
4(x^2-2x)+9(y^2+4y)+4=0.
$$

$$
4[(x-1)^2-1]+9[(y+2)^2-4]+4=0.
$$

Rearranging gives $4(x-1)^2+9(y+2)^2=36$. Dividing by $36$ gives

$$
\boxed{\frac{(x-1)^2}{9}+\frac{(y+2)^2}{4}=1}.
$$

This is an ellipse centered at $(1,-2)$. Its horizontal semiaxis is $3$ and its vertical semiaxis is $2$, so the major axis is horizontal. The vertices are $(-2,-2)$ and $(4,-2)$, and the co-vertices are $(1,-4)$ and $(1,0)$.

To sketch it, mark the center and move $3$ units left and right and $2$ units up and down. Draw the ellipse through these four points.

### Part 2. Identify the Surface

**Horizontal sections at $z=c$.** Substitution gives $4x^2+y^2=c^2$. For $c\ne0$, this becomes

$$
\frac{x^2}{c^2/4}+\frac{y^2}{c^2}=1.
$$

The section is an ellipse centered at $(0,0,c)$ with semiaxes $\lvert c\rvert/2$ along $x$ and $\lvert c\rvert$ along $y$. Thus the $y$ semiaxis is twice the $x$ semiaxis. At $c=0$, the section is the single point $(0,0,0)$.

**Vertical section at $x=0$.** The equation becomes $y^2=z^2$, giving the intersecting lines $z=\pm y$ in the $yz$-plane.

**Vertical section at $y=0$.** The equation becomes $4x^2=z^2$, giving the intersecting lines $z=\pm2x$ in the $xz$-plane.

The surface is an **elliptic double cone** with its vertex at the origin. To sketch it, draw two halves extending along the positive and negative $z$-axis. Draw horizontal ellipses that widen as $\lvert z\rvert$ increases, keeping the $y$ semiaxis twice the $x$ semiaxis. For example, at $z=2$ the semiaxes are $1$ along $x$ and $2$ along $y$.

## Labeled Sketches

![Translated ellipse with its four axis endpoints, elliptic double cone, and the horizontal section at z=2 showing semiaxes 1 and 2](./ellipse-cone-exercise-15.png)
