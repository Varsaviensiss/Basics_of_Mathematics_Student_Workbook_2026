# Exercise 11. Two Similar Surfaces

## Question

Compare the surfaces

$$
x^2+y^2-z^2=1
\qquad\text{and}\qquad
x^2+y^2-z^2=-1.
$$

For each surface, describe the horizontal cross-sections at $z=c$. State when they exist, give their radii, and explain how they change with $c$. Check several specific heights. Compare the connectivity of the surfaces and draw labeled sketches showing the $z$-axis.

## Solution

### 1. One-Sheet Hyperboloid

Setting $z=c$ in $x^2+y^2-z^2=1$ gives

$$
x^2+y^2=1+c^2.
$$

Since $1+c^2>0$ for every real $c$, each horizontal section is a circle centered at $(0,0,c)$ with radius $\sqrt{1+c^2}$. The minimum radius is $1$ at $z=0$. The radius increases as $|c|$ increases. The circles vary continuously with height and form one connected surface with a narrow waist at $z=0$.

### 2. Two-Sheet Hyperboloid

Setting $z=c$ in $x^2+y^2-z^2=-1$ gives

$$
x^2+y^2=c^2-1.
$$

- If $|c|>1$, the section is a circle centered at $(0,0,c)$ with radius $\sqrt{c^2-1}$.
- If $|c|=1$, the section is the single point $(0,0,c)$.
- If $|c|<1$, the section is empty because $x^2+y^2$ cannot be negative.

The upper sheet starts at $(0,0,1)$ and widens as $z$ increases. The lower sheet starts at $(0,0,-1)$ and widens as $z$ decreases. There are no points with $-1<z<1$, so the sheets are disconnected.

### 3. Checks at Specific Heights

| Height | One-sheet hyperboloid | Two-sheet hyperboloid |
|---|---|---|
| $z=0$ | $x^2+y^2=1$, circle of radius $1$ | $x^2+y^2=-1$, empty |
| $z=1$ | $x^2+y^2=2$, circle of radius $\sqrt{2}$ | $x^2+y^2=0$, single point $(0,0,1)$ |
| $z=2$ | $x^2+y^2=5$, circle of radius $\sqrt{5}$ | $x^2+y^2=3$, circle of radius $\sqrt{3}$ |

The same radii occur at negative heights with the same absolute value because both equations depend on $c^2$.

### 4. Labeled Sketches

The sketches show the profiles in the plane $y=0$. Rotating each profile about the $z$-axis gives the corresponding surface.

```text
One-sheet hyperboloid

                       ^ z
       *               |               *
          *            |            *
             *         |         *
                *      |      *
                  *    |    *
<------------------L---O---R------------------> x  (z = 0)
                  *    |    *
                *      |      *
             *         |         *
          *            |            *
       *               |               *

L = (-1, 0, 0), R = (1, 0, 0)
Rotating the profile gives a circular waist of radius 1 at z = 0.
The surface widens above and below the waist.
```

```text
Two-sheet hyperboloid

                       ^ z
       *               |               *
            *          |          *
                 *     |     *
                     * U *           z = 1
                       |
<----------------------O----------------------> x  (z = 0)
                       |
                     * D *           z = -1
                 *     |     *
            *          |          *
       *               |               *

U = (0, 0, 1), D = (0, 0, -1)
The vertical line through U, O, and D is the z-axis.
The surface has no points between z = -1 and z = 1.
```
