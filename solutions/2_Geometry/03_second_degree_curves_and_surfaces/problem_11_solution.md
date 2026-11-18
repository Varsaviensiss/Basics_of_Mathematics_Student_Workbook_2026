# Exercise 11. Two Similar Surfaces

## Question

Compare the surfaces

$$
x^2+y^2-z^2=1
\qquad\text{and}\qquad
x^2+y^2-z^2=-1.
$$

For each surface, describe the horizontal cross-sections at $z=c$. State when they exist, give their radii, and explain how they change with $c$. Compare the connectivity of the surfaces and draw labeled sketches showing the $z$-axis.

## Solution

### 1. One-Sheet Hyperboloid

For $x^2+y^2-z^2=1$, setting $z=c$ gives

$$
x^2+y^2=1+c^2.
$$

For every real $c$, the cross-section is a circle centered at $(0,0,c)$ with radius $\sqrt{1+c^2}$. The radius is smallest at $c=0$, where it equals $1$, and increases as $|c|$ increases. These circles form one connected surface with a narrow waist at $z=0$.

### 2. Two-Sheet Hyperboloid

For $x^2+y^2-z^2=-1$, setting $z=c$ gives

$$
x^2+y^2=c^2-1.
$$

- If $|c|>1$, the cross-section is a circle of radius $\sqrt{c^2-1}$ centered at $(0,0,c)$.
- If $|c|=1$, the cross-section is a single point, $(0,0,c)$.
- If $|c|<1$, the cross-section is empty.

The upper sheet begins at $(0,0,1)$ and widens as $z$ increases. The lower sheet begins at $(0,0,-1)$ and widens as $z$ decreases. The gap $-1<z<1$ separates the two sheets.

### 3. Labeled Sketches

![One-sheet hyperboloid with its waist at z=0 and two-sheet hyperboloid with vertices at z=±1. Both sketches show the z-axis.](./hyperboloids-exercise-11.png)

For the first sketch, draw the radius-$1$ waist at $z=0$ and widen the surface above and below it. For the second, mark the two vertices on the $z$-axis and draw the sheets widening away from the gap.
