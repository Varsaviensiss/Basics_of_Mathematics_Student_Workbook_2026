# Problem 2. Maximum Area of a Rectangle

## Question

A rectangle has a perimeter of 40 units.

1. Express its area as a function of the length of one side.
2. Determine the geometric domain of the area function.
3. Find the dimensions that maximize the area.
4. Justify that these dimensions give the maximum area.

## Solution

### 1. Express the area as a function of one side

Let $x$ and $y$ be the side lengths. The perimeter condition gives

$$
2x+2y=40,
\qquad
y=20-x.
$$

Substituting into $A=xy$ gives

$$
A(x)=x(20-x)=20x-x^2.
$$

### 2. Determine the geometric domain

Both side lengths must be positive. Since $y=20-x$, we need $x>0$ and $20-x>0$. Therefore, the geometric domain is

$$
0<x<20.
$$

### 3. Find the maximizing dimensions

Differentiating gives $A'(x)=20-2x$. Setting $A'(x)=0$ gives $x=10$, which lies in the domain. The other side is $y=20-10=10$.

### 4. Justify the maximum

Since $A''(x)=-2<0$ throughout the domain, the area function is strictly concave. Its critical point at $x=10$ gives the global maximum.

Completing the square confirms this:

$$
A(x)=100-(x-10)^2\le 100,
$$

with equality only at $x=10$. Thus the maximizing rectangle has dimensions **$10\times10$ units**, and its maximum area is **$100$ square units**.
