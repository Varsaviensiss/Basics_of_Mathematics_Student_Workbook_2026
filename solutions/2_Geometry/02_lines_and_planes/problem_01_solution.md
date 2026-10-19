# Exercise 1. Line Through Two Points

## Given

$$
A=(1,2),\qquad B=(4,-1)
$$

## 1. Find a Direction Vector

Subtract the coordinates of \(A\) from those of \(B\):

$$
\mathbf{v}=B-A
$$

$$
=(4-1,-1-2)
$$

$$
\boxed{\mathbf{v}=(3,-3)}
$$

## 2. Find the Parametric Equation

A line through \(A\) with direction vector \(\mathbf{v}\) is

$$
(x,y)=(1,2)+t(3,-3)
$$

Therefore,

$$
\boxed{x=1+3t,\qquad y=2-3t}
$$

where \(t\in\mathbb{R}\).

## 3. Find the General Form

The slope is

$$
m=\frac{-1-2}{4-1}=-1
$$

Using the point-slope form:

$$
y-2=-(x-1)
$$

$$
y-2=-x+1
$$

$$
\boxed{x+y-3=0}
$$

## 4. Find a Normal Vector

The coefficients of \(x\) and \(y\) in the general equation give a normal vector:

$$
\boxed{\mathbf{n}=(1,1)}
$$

Check perpendicularity:

$$
\mathbf{n}\cdot\mathbf{v}=(1,1)\cdot(3,-3)
$$

$$
=3-3=0
$$

Thus, the normal vector is perpendicular to the direction vector.

## 5. Check Both Points

For \(A=(1,2)\):

$$
1+2-3=0
$$

For \(B=(4,-1)\):

$$
4+(-1)-3=0
$$

Both points satisfy the general equation.

## Final Answer

$$
\boxed{x=1+3t,\quad y=2-3t}
$$

$$
\boxed{x+y-3=0}
$$

$$
\boxed{\mathbf{v}=(3,-3),\quad \mathbf{n}=(1,1)}
$$
