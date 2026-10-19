# Exercise 8. Linear Combination and Checking the Result

## Given

$$
\mathbf{w}=(5,1),\quad \mathbf{u}=(1,1),\quad \mathbf{v}=(2,-1)
$$

We want to determine whether

$$
\mathbf{w}=a\mathbf{u}+b\mathbf{v}
$$

## 1. Find \(a\) and \(b\)

Substitute the vectors:

$$
(5,1)=a(1,1)+b(2,-1)
$$

Multiply each vector by its scalar:

$$
(5,1)=(a,a)+(2b,-b)
$$

Add the components:

$$
(5,1)=(a+2b,a-b)
$$

Equate corresponding components:

$$
a+2b=5
$$

$$
a-b=1
$$

From the second equation:

$$
a=1+b
$$

Substitute into the first equation:

$$
1+b+2b=5
$$

$$
3b=4
$$

$$
\boxed{b=\frac43}
$$

Find \(a\):

$$
a=1+\frac43
$$

$$
\boxed{a=\frac73}
$$

Therefore,

$$
\boxed{\mathbf{w}=\frac73\mathbf{u}+\frac43\mathbf{v}}
$$

## 2. Reconstruct \(\mathbf{w}\)

Substitute the coefficients:

$$
\frac73(1,1)+\frac43(2,-1)
$$

$$
=\left(\frac73,\frac73\right)+\left(\frac83,-\frac43\right)
$$

$$
=\left(\frac73+\frac83,\frac73-\frac43\right)
$$

$$
=(5,1)
$$

This matches the given vector:

$$
\boxed{\mathbf{w}=(5,1)}
$$

## 3. Geometric Meaning

The vector \(\mathbf{w}\) can be formed by scaling \(\mathbf{u}\) by \(\frac73\), scaling \(\mathbf{v}\) by \(\frac43\), and adding the results.

Since the coefficients exist, \(\mathbf{w}\) lies in the span of \(\mathbf{u}\) and \(\mathbf{v}\).

$$
\boxed{\mathbf{w}\in\operatorname{span}\{\mathbf{u},\mathbf{v}\}}
$$
