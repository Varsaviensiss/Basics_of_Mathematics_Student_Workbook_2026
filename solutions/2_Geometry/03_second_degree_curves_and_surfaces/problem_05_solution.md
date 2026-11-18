# Exercise 5. Hyperbola and Asymptotes

## Given

Consider the hyperbola

$$
\frac{x^2}{16}-\frac{y^2}{9}=1.
$$

Find its $x$-intercepts and asymptotes. Describe its shape and explain why the asymptotes describe the behavior of the curve far from the center. Make a labeled sketch showing the coordinate axes, vertices, both branches, and dashed asymptotes.

## Solution

### 1. Identify the Shape and Intercepts

The equation has the form $x^2/a^2-y^2/b^2=1$ with $a=4$ and $b=3$. The center is $(0,0)$. The positive $x^2$ term gives two branches opening to the left and right.

Setting $y=0$ gives $x^2=16$, so the $x$-intercepts are $(-4,0)$ and $(4,0)$. These are also the vertices. Setting $x=0$ gives $y^2=-9$, so there are no real $y$-intercepts.

### 2. Find the Asymptotes

The slopes of the asymptotes are $\pm b/a=\pm3/4$. Both lines pass through the center, so their equations are

$$
y=\frac34x
\qquad\text{and}\qquad
y=-\frac34x.
$$

### 3. Explain the Behavior Far from the Center

Rearranging the equation gives $|y|=\frac34\sqrt{x^2-16}$. At the same $x$-coordinate, the asymptotes have absolute height $\frac34|x|$. The vertical gap to the asymptote in the corresponding quadrant is

$$
\frac34|x|-\frac34\sqrt{x^2-16}
=
\frac{12}{|x|+\sqrt{x^2-16}}
\longrightarrow 0
\qquad\text{as } |x|\to\infty.
$$

Thus, each end of the hyperbola gets arbitrarily close to its corresponding asymptote.

### 4. Sketch

Draw the coordinate axes and mark the center $(0,0)$ and the vertices $(-4,0)$ and $(4,0)$. Draw the two asymptotes as dashed lines, then draw the left and right branches through their vertices, approaching the dashed lines outward. The graph is symmetric about both coordinate axes.

![Horizontal hyperbola with vertices at (-4,0) and (4,0), both branches, and dashed asymptotes y = ±3x/4](./hyperbola-exercise-05.png)
