# Exercise 5. Hyperbola and Asymptotes

## Question

Consider the hyperbola

$$
\frac{x^2}{16}-\frac{y^2}{9}=1.
$$

Find its $x$-intercepts and asymptotes. Describe its shape and explain why the asymptotes describe the behavior of the curve far from the center. Make a labeled sketch showing the coordinate axes, vertices, both branches, and dashed asymptotes.

## Solution

### 1. Shape and Intercepts

The equation has the form $\frac{x^2}{a^2}-\frac{y^2}{b^2}=1$, with $a=4$ and $b=3$. The center is $(0,0)$. The positive $x^2$ term gives two branches that open left and right.

Setting $y=0$ gives $x^2=16$, so the $x$-intercepts are $(-4,0)$ and $(4,0)$. These are also the vertices. Setting $x=0$ gives $y^2=-9$, so there are no real $y$-intercepts.

### 2. Asymptotes

The asymptotes pass through the center and have slopes $\pm b/a=\pm 3/4$. Their equations are

$$
y=\frac{3}{4}x
\qquad\text{and}\qquad
y=-\frac{3}{4}x.
$$

### 3. Behavior Far from the Center

For $|x|\ge 4$, rearranging the hyperbola equation gives $|y|=\frac34\sqrt{x^2-16}$. At the same $x$-coordinate, the asymptote in the corresponding quadrant has absolute height $\frac34|x|$. The vertical gap is

$$
\frac34\left(|x|-\sqrt{x^2-16}\right)
=\frac34\cdot
\frac{x^2-(x^2-16)}{|x|+\sqrt{x^2-16}}
=\frac{12}{|x|+\sqrt{x^2-16}}.
$$

The denominator grows without bound as $|x|\to\infty$, so the gap tends to zero. Therefore, each end of the hyperbola approaches the asymptote in its quadrant.

### 4. Labeled Sketch

```text
                             ^ y
                             |
  *   .                      |                      .   *
      *   .                  |                  .   *
         *    .              |              .    *
           *      .          |          .      *
             *        .      |      .        *
              *           .  |  .           *
<-------------L--------------O--------------R-------------> x
              *           .  |  .           *
             *        .      |      .        *
           *      .          |          .      *
         *    .              |              .    *
      *   .                  |                  .   *
  *   .                      |                      .   *

O = (0, 0) is the center.
L = (-4, 0) and R = (4, 0) are the vertices and x-intercepts.
* marks the left and right branches.
. marks the asymptotes y = (3/4)x and y = -(3/4)x.
```

The graph is symmetric about both coordinate axes.
