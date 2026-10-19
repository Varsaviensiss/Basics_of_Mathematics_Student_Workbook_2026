# Problem 6: Average Value of a Function

## Given

The function is

$$
f(x)=x^2
$$

on the interval

$$
[0,3]
$$

We need to calculate the average value of the function, find a point \(c\in[0,3]\) where the function equals its average value, and interpret the result geometrically.

## 1. Compute the average value of the function

The average value of a continuous function \(f(x)\) on the interval \([a,b]\) is given by

$$
f_{\mathrm{avg}}=\frac{1}{b-a}\int_a^b f(x)\,dx
$$

For \(f(x)=x^2\) on \([0,3]\), we have \(a=0\) and \(b=3\). Therefore,

$$
f_{\mathrm{avg}}=\frac{1}{3-0}\int_0^3x^2\,dx
$$

Integrating,

$$
f_{\mathrm{avg}}=\frac{1}{3}\left[\frac{x^3}{3}\right]_0^3
$$

Evaluating the limits gives

$$
f_{\mathrm{avg}}=\frac{1}{3}\left(\frac{3^3}{3}-\frac{0^3}{3}\right)
$$

$$
f_{\mathrm{avg}}=\frac{1}{3}(9)
$$

Thus, the average value is

$$
\boxed{f_{\mathrm{avg}}=3}
$$

## 2. Find a point \(c\in[0,3]\) such that \(f(c)\) equals the average value

We need to find \(c\) such that

$$
f(c)=f_{\mathrm{avg}}
$$

Since \(f(x)=x^2\) and \(f_{\mathrm{avg}}=3\),

$$
c^2=3
$$

Taking the square root of both sides gives

$$
c=\pm\sqrt{3}
$$

However, the point must belong to the interval \([0,3]\). Since \(-\sqrt{3}\notin[0,3]\), we choose the positive solution.

Therefore,

$$
\boxed{c=\sqrt{3}\approx1.732}
$$

Indeed,

$$
f(\sqrt{3})=(\sqrt{3})^2=3
$$

which equals the average value of the function.

## 3. Geometric interpretation

The average value of a function represents the constant height that produces the same area over the interval as the area under the original function.

The area under \(f(x)=x^2\) from \(x=0\) to \(x=3\) is

$$
\int_0^3x^2\,dx=9
$$

A rectangle with width \(3\) and height equal to the average value \(3\) has area

$$
A=3\cdot3=9
$$

Thus, the rectangle and the region under the curve have the same area.

Furthermore, the point \(c=\sqrt{3}\) is where the graph \(y=x^2\) reaches the average height \(y=3\).

This illustrates the integral mean value theorem: because \(f(x)=x^2\) is continuous on \([0,3]\), there exists a point \(c\in[0,3]\) such that

$$
f(c)=\frac{1}{3-0}\int_0^3f(x)\,dx
$$

## Final Answer

The average value of the function is

$$
\boxed{f_{\mathrm{avg}}=3}
$$

The point where the function equals its average value is

$$
\boxed{c=\sqrt{3}\approx1.732}
$$

Geometrically, the rectangle with width \(3\) and height \(3\) has the same area as the region under the curve \(y=x^2\) on \([0,3]\). Both areas equal \(9\) square units.
