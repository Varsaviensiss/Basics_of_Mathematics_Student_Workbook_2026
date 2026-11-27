# Exercise 1. Recognizing Curves from Canonical Form

## Question

Identify the type of curve represented by each equation. Explain how the canonical form determines the type, list the key features, and draw a labeled sketch of each curve.

1. $x^2+y^2=9$
2. $\frac{x^2}{16}+\frac{y^2}{9}=1$
3. $y^2=8x$
4. $\frac{x^2}{9}-\frac{y^2}{4}=1$

## Solution

### 1. Circle

The squared terms have equal positive coefficients, so the equation has the form $x^2+y^2=r^2$. The center is $(0,0)$ and the radius is $r=\sqrt{9}=3$. The axis intercepts are $(\pm3,0)$ and $(0,\pm3)$.

```text
                    ^ y
                    |
                ****T****
             ***    |    ***
            *       |       *
           *        |        *
<----------L--------O--------R----------> x
           *        |        *
            *       |       *
             ***    |    ***
                ****B****
                    |

O = (0, 0), radius = 3
L = (-3, 0), R = (3, 0)
T = (0, 3),  B = (0, -3)
```

### 2. Ellipse

Both squared terms are positive and have different denominators, so the equation represents an ellipse centered at $(0,0)$. The horizontal semiaxis is $\sqrt{16}=4$ and the vertical semiaxis is $\sqrt{9}=3$, so the ellipse is wider along the $x$-axis. The intercepts are $(\pm4,0)$ and $(0,\pm3)$.

```text
                    ^ y
                    |
               *****T*****
           ****     |     ****
         **         |         **
        *           |           *
<-------L-----------O-----------R-------> x
        *           |           *
         **         |         **
           ****     |     ****
               *****B*****
                    |

O = (0, 0)
L = (-4, 0), R = (4, 0)
T = (0, 3),  B = (0, -3)
Horizontal semiaxis = 4, vertical semiaxis = 3
```

### 3. Parabola

Only $y$ is squared, and the equation has the form $y^2=4px$. Since $4p=8$, we get $p=2$. The vertex is $(0,0)$, the axis of symmetry is $y=0$, and the focus is $(2,0)$. The parabola opens to the right because $p>0$.

```text
        ^ y
        |                        *
        |                 *
        |           *
        |      *
        |   *
        | *
<-------V-------F---------------------> x
        | *
        |   *
        |      *
        |           *
        |                 *
        |                        *

V = (0, 0) is the vertex.
F = (2, 0) is the focus.
The x-axis (y = 0) is the axis of symmetry.
```

### 4. Hyperbola

The squared terms have opposite signs, so the equation represents a hyperbola. The positive $x^2$ term means that the branches open left and right. The center is $(0,0)$ and the vertices are $(\pm3,0)$. With $a=3$ and $b=2$, the asymptotes are $y=\pm\frac{b}{a}x=\pm\frac{2}{3}x$.

```text
                            ^ y
                            |
  *  .                      |                      .  *
      *  .                  |                  .  *
          *  .              |              .  *
             *   .          |          .   *
                *    .      |      .    *
                 *       .  |  .       *
<-----------------L---------O---------R-----------------> x
                 *       .  |  .       *
                *    .      |      .    *
             *   .          |          .   *
          *  .              |              .  *
      *  .                  |                  .  *
  *  .                      |                      .  *

O = (0, 0) is the center.
L = (-3, 0) and R = (3, 0) are the vertices.
Dots mark the asymptotes y = (2/3)x and y = -(2/3)x.
```
