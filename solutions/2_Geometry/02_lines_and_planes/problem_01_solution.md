# Exercise 1: Line Through Two Points

Given:

\[
A=(1,2),\qquad B=(4,-1)
\]

## 1. Finding the Direction Vector

The direction vector is obtained by subtracting the coordinates of \(A\) from those of \(B\).

\[
\overrightarrow{AB}=B-A
\]

\[
\overrightarrow{AB}=(4,-1)-(1,2)
\]

\[
\overrightarrow{AB}=(4-1,-1-2)
\]

\[
\boxed{\overrightarrow{AB}=(3,-3)}
\]

The vector can be simplified by dividing both components by \(3\):

\[
\boxed{\vec d=(1,-1)}
\]

Both vectors describe the same direction.

## 2. Finding the Parametric Form

The parametric form of a line is

\[
(x,y)=(x_0,y_0)+t(a,b),
\qquad t\in\mathbb R.
\]

Using \(A=(1,2)\) and \(\vec d=(1,-1)\):

\[
(x,y)=(1,2)+t(1,-1)
\]

Expanding the coordinates:

\[
x=1+t(1)
\]

\[
y=2+t(-1)
\]

Therefore,

\[
\boxed{
\begin{aligned}
x&=1+t,\\
y&=2-t,
\end{aligned}
\quad t\in\mathbb R
}
\]

### Verification Using the Parametric Form

| Point | Value of \(t\) | Calculation | Result |
|---|---:|---|---|
| \(A=(1,2)\) | \(0\) | \(x=1,\ y=2\) | \(A\) |
| \(B=(4,-1)\) | \(3\) | \(x=1+3=4,\ y=2-3=-1\) | \(B\) |

Both points satisfy the parametric equations.

## 3. Finding the General Form

First, calculate the slope:

\[
m=\frac{y_2-y_1}{x_2-x_1}
\]

Substitute the coordinates:

\[
m=\frac{-1-2}{4-1}
\]

\[
m=\frac{-3}{3}
\]

\[
\boxed{m=-1}
\]

Use the point-slope equation:

\[
y-y_1=m(x-x_1)
\]

Substitute \(A=(1,2)\) and \(m=-1\):

\[
y-2=-(x-1)
\]

Expand:

\[
y-2=-x+1
\]

Move all terms to the left-hand side:

\[
x+y-2-1=0
\]

Thus, the general form is

\[
\boxed{x+y-3=0}
\]

## 4. Finding a Normal Vector

For a line in the form

\[
ax+by+c=0,
\]

a normal vector is

\[
\vec n=(a,b).
\]

Comparing this with

\[
x+y-3=0,
\]

we identify

\[
a=1,\qquad b=1.
\]

Therefore,

\[
\boxed{\vec n=(1,1)}
\]

### Verification of Perpendicularity

The direction vector and normal vector must have a dot product equal to zero.

\[
\vec d\cdot\vec n=(1,-1)\cdot(1,1)
\]

\[
=(1)(1)+(-1)(1)
\]

\[
=1-1
\]

\[
\boxed{\vec d\cdot\vec n=0}
\]

Therefore, the normal vector is perpendicular to the line's direction vector.

## 5. Checking Both Points in the General Equation

The equation is

\[
x+y-3=0.
\]

**For \(A=(1,2)\):**

\[
1+2-3=0
\]

\[
3-3=0
\]

\[
\boxed{0=0\quad\checkmark}
\]

**For \(B=(4,-1)\):**

\[
4+(-1)-3=0
\]

\[
4-1-3=0
\]

\[
3-3=0
\]

\[
\boxed{0=0\quad\checkmark}
\]

Both points satisfy the general equation.

## Final Results

| Required Quantity | Answer |
|---|---|
| Direction vector | \(\vec d=(1,-1)\) |
| Parametric form | \(x=1+t,\ y=2-t,\ t\in\mathbb R\) |
| General form | \(x+y-3=0\) |
| Normal vector | \(\vec n=(1,1)\) |
| Direction-normal check | \(\vec d\cdot\vec n=0\) |
| Point \(A\) verification | \(1+2-3=0\) |
| Point \(B\) verification | \(4-1-3=0\) |

The parametric and general equations represent the same line through the two given points. All required checks are satisfied.
