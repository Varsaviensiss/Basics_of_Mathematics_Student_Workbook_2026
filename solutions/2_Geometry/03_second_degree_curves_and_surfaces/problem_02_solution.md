# Exercise 2. Circle by Completing the Square

Given the equation

$$
x^2+y^2-6x+4y-3=0
$$

We will reduce it to canonical form, find the center and radius, and verify two points using both forms of the equation.

## Step 1: Group the \(x\)-terms and \(y\)-terms

Move the constant term to the right-hand side:

$$
x^2+y^2-6x+4y=3
$$

Group the terms involving the same variable:

$$
(x^2-6x)+(y^2+4y)=3
$$

## Step 2: Complete the square for \(x\)

Take half the coefficient of \(x\) and square it:

$$
\frac{-6}{2}=-3
$$

$$
(-3)^2=9
$$

Add \(9\) to the \(x\)-expression:

$$
x^2-6x+9=(x-3)^2
$$

## Step 3: Complete the square for \(y\)

Take half the coefficient of \(y\) and square it:

$$
\frac{4}{2}=2
$$

$$
2^2=4
$$

Add \(4\) to the \(y\)-expression:

$$
y^2+4y+4=(y+2)^2
$$

Since we added \(9\) and \(4\) to the left-hand side, we must also add them to the right-hand side:

$$
(x^2-6x+9)+(y^2+4y+4)=3+9+4
$$

Simplify:

$$
(x-3)^2+(y+2)^2=16
$$

## Step 4: Identify the canonical form

The standard equation of a circle is

$$
(x-h)^2+(y-k)^2=r^2
$$

Comparing this with

$$
(x-3)^2+(y+2)^2=16
$$

we obtain

$$
h=3,\qquad k=-2,\qquad r^2=16
$$

Therefore, the center is

$$
\boxed{C=(3,-2)}
$$

The radius is

$$
r=\sqrt{16}
$$

$$
\boxed{r=4}
$$

## Step 5: Choose two simple points on the circle

Choose points at the top and bottom of the circle. Since the center is \((3,-2)\) and the radius is \(4\), these points are

$$
P=(3,2)
$$

and

$$
Q=(3,-6)
$$

Both points are four units vertically from the center.

### Verify point \(P=(3,2)\)

**Using the canonical form:**

$$
(x-3)^2+(y+2)^2=16
$$

Substitute \(x=3\) and \(y=2\):

$$
(3-3)^2+(2+2)^2
$$

$$
=0^2+4^2
$$

$$
=0+16=16
$$

The equation is satisfied.

**Using the original equation:**

$$
x^2+y^2-6x+4y-3=0
$$

Substitute \(x=3\) and \(y=2\):

$$
3^2+2^2-6(3)+4(2)-3
$$

$$
=9+4-18+8-3
$$

$$
=13-18+8-3
$$

$$
=-5+8-3
$$

$$
=3-3=0
$$

Therefore, \(P=(3,2)\) satisfies both forms.

### Verify point \(Q=(3,-6)\)

**Using the canonical form:**

$$
(x-3)^2+(y+2)^2=16
$$

Substitute \(x=3\) and \(y=-6\):

$$
(3-3)^2+(-6+2)^2
$$

$$
=0^2+(-4)^2
$$

$$
=0+16=16
$$

The equation is satisfied.

**Using the original equation:**

$$
x^2+y^2-6x+4y-3=0
$$

Substitute \(x=3\) and \(y=-6\):

$$
3^2+(-6)^2-6(3)+4(-6)-3
$$

$$
=9+36-18-24-3
$$

$$
=45-18-24-3
$$

$$
=27-24-3
$$

$$
=3-3=0
$$

Therefore, \(Q=(3,-6)\) also satisfies both forms.

## Final Answer

The canonical form is

$$
\boxed{(x-3)^2+(y+2)^2=16}
$$

The center and radius are

$$
\boxed{C=(3,-2)}
$$

$$
\boxed{r=4}
$$

The two verified points are

$$
\boxed{P=(3,2),\qquad Q=(3,-6)}
$$

Both points satisfy the original equation and the canonical form, confirming the result.

