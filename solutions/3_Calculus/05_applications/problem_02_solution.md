# Problem 2: Maximum Area of a Rectangle

## Given

A rectangle has a perimeter of 40 units.

Let \(x\) be the length of one side and \(y\) be the length of the other side.

The perimeter formula is

$$
2x+2y=40
$$

Dividing both sides by 2 gives

$$
x+y=20
$$

Solving for \(y\),

$$
y=20-x
$$

## 1. Write the area as a function of one side

The area of a rectangle is

$$
A=xy
$$

Substituting \(y=20-x\), we obtain

$$
A(x)=x(20-x)
$$

Expanding gives

$$
\boxed{A(x)=20x-x^2}
$$

## 2. Determine the domain of the function

Both side lengths must be positive:

$$
x>0,\qquad y>0
$$

Since \(y=20-x\),

$$
20-x>0
$$

Therefore,

$$
x<20
$$

Combining these conditions, the domain is

$$
\boxed{0<x<20}
$$

## 3. Find the dimensions that give the maximum area

The area function is

$$
A(x)=20x-x^2
$$

Taking the first derivative,

$$
A'(x)=20-2x
$$

To find the critical point, set the derivative equal to zero:

$$
20-2x=0
$$

Solving for \(x\),

$$
2x=20
$$

$$
x=10
$$

Using \(y=20-x\),

$$
y=20-10=10
$$

Therefore, the dimensions that maximize the area are

$$
\boxed{x=10,\qquad y=10}
$$

The maximum area is

$$
A(10)=10\cdot10=100
$$

Thus,

$$
\boxed{A_{\max}=100\text{ square units}}
$$

## 4. Verify that the critical point gives a maximum

The first derivative is

$$
A'(x)=20-2x
$$

Taking the second derivative,

$$
A''(x)=-2
$$

Since

$$
A''(x)=-2<0
$$

the area function is strictly concave downward. Therefore, the critical point \(x=10\) gives a maximum.

Alternatively, completing the square gives

$$
A(x)=20x-x^2
$$

$$
A(x)=100-(x-10)^2
$$

Since \((x-10)^2\geq0\),

$$
A(x)\leq100
$$

Equality holds when \(x=10\). Hence, the maximum area is 100 square units.

## Final Answer

The area function and its domain are

$$
\boxed{A(x)=20x-x^2,\qquad 0<x<20}
$$

The rectangle with the maximum area has dimensions

$$
\boxed{10\times10}
$$

The maximum area is

$$
\boxed{100\text{ square units}}
$$

The second derivative test confirms that this is a maximum.
