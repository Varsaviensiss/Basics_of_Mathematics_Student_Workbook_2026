# Exercise 6. Shifted Ellipse

## Question

Given the equation

$$
4x^2+9y^2-16x+18y-11=0,
$$

reduce it to canonical form. Find the center and the lengths of both semiaxes. Check the result by evaluating the original left-hand side at the center.

## Solution

### 1. Reduce to Canonical Form

Group the terms and complete the square:

$$
4(x^2-4x)+9(y^2+2y)=11.
$$

Using $x^2-4x=(x-2)^2-4$ and $y^2+2y=(y+1)^2-1$, we obtain

$$
4(x-2)^2+9(y+1)^2=11+16+9=36.
$$

Dividing by $36$ gives the canonical form:

$$
\boxed{\frac{(x-2)^2}{9}+\frac{(y+1)^2}{4}=1}.
$$

### 2. Find the Center and Semiaxes

The center is $(2,-1)$. The horizontal semiaxis has length $\sqrt{9}=3$, and the vertical semiaxis has length $\sqrt{4}=2$. The major axis is horizontal.

### 3. Check the Original Expression at the Center

Substitute $x=2$ and $y=-1$ into the original left-hand side:

$$
4(2)^2+9(-1)^2-16(2)+18(-1)-11
=16+9-32-18-11
=\boxed{-36}.
$$

This agrees with the completed-square expression $4(x-2)^2+9(y+1)^2-36$, which also equals $-36$ at the center.
