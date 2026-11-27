# Exercise 15. Recognition and Sketch Without a Given Name

## Question

1. Reduce $4x^2+9y^2-8x+36y+4=0$ to canonical form. Identify the curve, give its most important features, and draw a labeled sketch showing its four axis endpoints.
2. For $4x^2+y^2=z^2$, first describe the sections in the planes $z=c$, $x=0$, and $y=0$. Compare the scales along the axes. Then identify the surface and draw a labeled sketch.

## Solution

### Part 1. Identify the Curve

Group the terms and complete the square.

$$
\begin{aligned}
4(x^2-2x)+9(y^2+4y)+4 &= 0,\\
4[(x-1)^2-1]+9[(y+2)^2-4]+4 &= 0,\\
4(x-1)^2+9(y+2)^2 &= 36.
\end{aligned}
$$

Dividing by $36$ gives the canonical equation

$$
\frac{(x-1)^2}{9}+\frac{(y+2)^2}{4}=1.
$$

This is an ellipse centered at $C=(1,-2)$. Its horizontal semiaxis is $3$ and its vertical semiaxis is $2$, so its major axis is horizontal. The vertices are $L=(-2,-2)$ and $R=(4,-2)$. The co-vertices are $T=(1,0)$ and $B=(1,-4)$.

```text
              ^ y
              |
<-------------O---T--------------------> x  (y = 0)
          ****|       ****
        **    |           **
      L-------|---C-----------R             (y = -2)
        **    |           **
          ****|       ****
              |   B                         (y = -4)
              |

O = (0, 0)      C = (1, -2)
L = (-2, -2)    R = (4, -2)
T = (1, 0)      B = (1, -4)
```

### Part 2. Identify the Surface from Its Cross-Sections

**Horizontal sections at $z=c$.** Substitution gives $4x^2+y^2=c^2$. At $c=0$, the section is the single point $(0,0,0)$. For $c\ne 0$, dividing by $c^2$ gives

$$
\frac{x^2}{c^2/4}+\frac{y^2}{c^2}=1.
$$

This section is an ellipse centered at $(0,0,c)$. Its $x$ semiaxis is $|c|/2$ and its $y$ semiaxis is $|c|$. Thus every nondegenerate horizontal section has a $y$ semiaxis twice as long as its $x$ semiaxis.

**Vertical section at $x=0$.** The equation becomes $y^2=z^2$, giving the lines $z=y$ and $z=-y$ in the $yz$-plane.

**Vertical section at $y=0$.** The equation becomes $4x^2=z^2$, giving the lines $z=2x$ and $z=-2x$ in the $xz$-plane.

The horizontal ellipses widen in proportion to $|z|$ on both sides of the origin. The vertical sections are pairs of straight lines through the origin. Together these sections identify an **elliptic double cone** with vertex $O=(0,0,0)$ and axis along $z$.

```text
ELLIPTIC DOUBLE CONE — two vertical profiles

y = 0: z = ±2x                    x = 0: z = ±y

          ^ z                              ^ z
      *   |   *                    *       |       *   z = 2
        * | *                          *   |   *
<---------O---------> x       <------------O------------> y
        * | *                          *   |   *
      *   |   *                    *       |       *   z = -2
```

At $z=2$, the horizontal section has equation $4x^2+y^2=4$. Its endpoints are $(\pm1,0,2)$ and $(0,\pm2,2)$.

```text
HORIZONTAL SECTION AT z = 2 — viewed from above

                  ^ y
                  T (0, 2, 2)
                **|**
               *  |  *
              *   |   *
<-------------L---C---R-------------> x
              *   |   *
               *  |  *
                **|**
                  B (0, -2, 2)

C = (0, 0, 2)
L = (-1, 0, 2), R = (1, 0, 2)
x semiaxis = 1, y semiaxis = 2
```
