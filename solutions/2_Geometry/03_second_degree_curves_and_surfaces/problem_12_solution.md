# Exercise 12. Recognizing a Surface from Cross-Sections

## Question

Find an equation for a surface whose cross-section at $z=0$ is a single point and whose horizontal cross-sections at $z=c>0$ are circles with radii that increase as $c$ increases. Every vertical plane containing the $z$-axis should cut the surface in an upward-opening parabola. Verify all these properties for your equation.

## Solution

A suitable equation is

$$
\boxed{z=x^2+y^2}.
$$

### 1. Horizontal Cross-Sections

At $z=0$, the equation becomes $x^2+y^2=0$. Both squares are nonnegative, so $x=y=0$. The section is the single point $(0,0,0)$.

At $z=c>0$, the equation becomes $x^2+y^2=c$. This is a circle in the plane $z=c$, centered at $(0,0,c)$, with radius $\sqrt{c}$. Its radius increases with $c$.

### 2. Vertical Cross-Sections

In the plane $x=0$, the section is $z=y^2$. In the plane $y=0$, it is $z=x^2$.

More generally, fix an angle $\theta$. In the vertical plane through the $z$-axis at that angle, write

$$
x=s\cos\theta,\qquad y=s\sin\theta,\qquad s\in\mathbb R.
$$

Substituting gives

$$
z=s^2\cos^2\theta+s^2\sin^2\theta=s^2.
$$

Thus every such plane cuts the surface in an upward-opening parabola with vertex at the origin. The surface is an upward-opening circular paraboloid with the $z$-axis as its axis of symmetry.
