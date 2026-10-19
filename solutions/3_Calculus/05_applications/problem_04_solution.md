# Problem 4: Area Between Curves

## Given

Find the area of the region bounded by the graphs

$$
y=x \qquad \text{and} \qquad y=x^2
$$

## 1. Find the intersection points

To find the intersection points, set the two functions equal to each other:

$$
x=x^2
$$

Rearranging the equation gives

$$
x^2-x=0
$$

Factoring,

$$
x(x-1)=0
$$

Therefore,

$$
x=0 \qquad \text{or} \qquad x=1
$$

Substituting these values into \(y=x\), we obtain the intersection points

$$
\boxed{(0,0)\text{ and }(1,1)}
$$

Thus, the interval of integration is

$$
\boxed{0\leq x\leq1}
$$

## 2. Determine which function is greater

On the interval \([0,1]\), we compare \(x\) and \(x^2\).

Since \(0\leq x\leq1\), multiplying \(x\) by itself gives a value that is less than or equal to \(x\). Therefore,

$$
x\geq x^2
$$

For \(0<x<1\), the inequality is strict:

$$
x>x^2
$$

Hence, \(y=x\) is the upper function and \(y=x^2\) is the lower function on the interval \([0,1]\).

## 3. Set up the area integral

The area between two curves is calculated by integrating the upper function minus the lower function:

$$
A=\int_a^b
\bigl(\text{upper function}-\text{lower function}\bigr)\,dx
$$

Using the intersection points as the limits of integration,

$$
A=\int_0^1(x-x^2)\,dx
$$

## 4. Calculate the area

Integrating term by term gives

$$
A=\left[\frac{x^2}{2}-\frac{x^3}{3}\right]_0^1
$$

Evaluating at the upper limit \(x=1\) and subtracting the value at the lower limit \(x=0\),

$$
A=\left(\frac{1}{2}-\frac{1}{3}\right)
-\left(0-0\right)
$$

Therefore,

$$
A=\frac{1}{2}-\frac{1}{3}
$$

Using a common denominator,

$$
A=\frac{3}{6}-\frac{2}{6}
$$

Hence, the area is

$$
\boxed{A=\frac{1}{6}}
$$

## Final Answer

The intersection points are

$$
\boxed{(0,0)\text{ and }(1,1)}
$$

On the interval \([0,1]\), the upper function is \(y=x\) and the lower function is \(y=x^2\).

The required area is

$$
A=\int_0^1(x-x^2)\,dx
$$

Therefore, the area of the bounded region is

$$
\boxed{A=\frac{1}{6}\text{ square units}}
$$
