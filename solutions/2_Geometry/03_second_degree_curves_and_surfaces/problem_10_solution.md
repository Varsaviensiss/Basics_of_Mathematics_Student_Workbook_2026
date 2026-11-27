# Exercise 10. Paraboloids

## Question

For the surfaces $z=x^2+y^2$ and $z=x^2-y^2$, find and describe the cross-sections in the planes $x=0$, $y=0$, and $z=c$. For the horizontal sections, consider $c>0$, $c=0$, and $c<0$. Draw a labeled sketch of each surface and explain the difference between the bowl and saddle shapes.

## Solution

### 1. Elliptic Paraboloid — $z=x^2+y^2$

- In the plane $x=0$, the section is $z=y^2$, an upward-opening parabola in the $yz$-plane.
- In the plane $y=0$, the section is $z=x^2$, an upward-opening parabola in the $xz$-plane.
- In the plane $z=c$, the section satisfies $x^2+y^2=c$. If $c>0$, it is a circle of radius $\sqrt{c}$ centered at $(0,0,c)$. If $c=0$, it is the single point $(0,0,0)$. If $c<0$, the section is empty because $x^2+y^2\ge 0$.

Both vertical sections open upward from $O=(0,0,0)$, and the horizontal circles widen as $c$ increases. Together these sections describe an upward-opening bowl.

```text
Bowl — vertical profiles through the vertex

 y = 0: z = x^2                  x = 0: z = y^2

          ^ z                             ^ z
   *      |      *                 *      |      *
    *     |     *                   *     |     *
     *    |    *                     *    |    *
       *  |  *                         *  |  *
 <--------O--------> x           <--------O--------> y

Bowl — perspective sketch

                   ^ z
          .--------|--------.
       .-'         |         '-.
      (            |            )   z = c > 0
       '-._________|_________.-'    circle of radius sqrt(c)
        \          |          /
         \         |         /
          '.       |       .'
            '-.____O____.-'         vertex O = (0, 0, 0)
```

### 2. Hyperbolic Paraboloid — $z=x^2-y^2$

- In the plane $x=0$, the section is $z=-y^2$, a downward-opening parabola in the $yz$-plane.
- In the plane $y=0$, the section is $z=x^2$, an upward-opening parabola in the $xz$-plane.
- In the plane $z=c$, the section satisfies $x^2-y^2=c$. If $c>0$, the hyperbola opens in the $x$-direction. If $c<0$, rewriting the equation as $y^2-x^2=-c$ shows that the hyperbola opens in the $y$-direction. If $c=0$, factoring gives $(x-y)(x+y)=0$, so the section consists of the two lines $y=x$ and $y=-x$ in the plane $z=0$.

From $O=(0,0,0)$, the surface rises along the $x$-direction and falls along the $y$-direction. These opposite vertical curvatures give the surface its saddle shape.

```text
Saddle — two perpendicular vertical profiles through O

 y = 0: z = x^2                  x = 0: z = -y^2

          ^ z                             ^ z
   *      |      *                        |
    *     |     *                         |
     *    |    *                          |
       *  |  *                            |
 <--------O--------> x           <--------O--------> y
          |                            *  |  *
          |                          *    |    *
          |                         *     |     *
          |                        *      |      *

Saddle — horizontal section at z = 0 (view from above)

                ^ y
     y = -x  \  |  /  y = x
              \ | /
               \|/
 <--------------O--------------> x
               /|\
              / | \
             /  |  \

The surface rises in the sectors around the x-axis
and falls in the sectors around the y-axis.
```
