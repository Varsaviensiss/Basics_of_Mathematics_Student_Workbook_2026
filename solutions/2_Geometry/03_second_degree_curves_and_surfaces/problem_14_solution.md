# Exercise 14. Cone and Cylinder

## Question

Compare the surfaces $x^2+y^2=z^2$ and $x^2+y^2=4$. For each surface, find and describe the cross-sections in the planes $z=c$, $x=0$, and $y=0$. Draw a labeled sketch of each surface and explain why the horizontal radius varies for the cone but stays constant for the cylinder.

## Solution

### 1. Double Cone

- At $z=c$, the equation becomes $x^2+y^2=c^2$. If $c\ne 0$, the section is a circle of radius $|c|$ centered at $(0,0,c)$. If $c=0$, the section is the single point $(0,0,0)$.
- At $x=0$, the equation becomes $y^2=z^2$. The section consists of the two intersecting lines $y=z$ and $y=-z$ in the $yz$-plane.
- At $y=0$, the equation becomes $x^2=z^2$. The section consists of the two intersecting lines $x=z$ and $x=-z$ in the $xz$-plane.

The two halves meet at the vertex $O=(0,0,0)$. The horizontal radius is $\sqrt{z^2}=|z|$, so the cone widens as the distance from the plane $z=0$ increases.

### 2. Circular Cylinder

- At $z=c$, the section is a circle of radius $2$ centered at $(0,0,c)$ for every real $c$.
- At $x=0$, the equation becomes $y^2=4$. The section consists of the two lines $y=-2$ and $y=2$ in the $yz$-plane, both parallel to the $z$-axis.
- At $y=0$, the equation becomes $x^2=4$. The section consists of the two lines $x=-2$ and $x=2$ in the $xz$-plane, both parallel to the $z$-axis.

The equation is independent of $z$, so the cylinder has radius $2$ at every height and extends indefinitely in both directions along the $z$-axis.

### 3. Labeled Sketches

The side views show the sections in the plane $y=0$. Rotating each side view about the $z$-axis gives the corresponding surface. The sections in the plane $x=0$ have the same shapes, with $y$ in place of $x$.

```text
DOUBLE CONE — side view in the plane y = 0

                     ^ z
        \            |            /
         \           |           /
          A----------+----------B     z = 2
             \       |       /
                \    |    /
 <-------------------O-------------------> x
                /    |    \
             /       |       \
          C----------+----------D     z = -2
         /           |           \
        /            |            \

O = (0, 0, 0) is the vertex.
The diagonal lines are x = z and x = -z.
AB and CD are diameters of the horizontal circles at z = 2
and z = -2, each with radius 2. At z = 0 only O remains.
```

```text
CIRCULAR CYLINDER — side view in the plane y = 0

                     ^ z
              |      |      |
              A------+------+B        z = 2
              |      |      |
 <------------+------O------+------------> x
              |      |      |
              C------+------+D        z = -2
              |      |      |
            x = -2        x = 2

The two outer vertical lines are x = -2 and x = 2.
AB and CD are diameters of the horizontal circles at z = 2
and z = -2, each with radius 2.
Every horizontal section has the same radius.
```
