```

# Problem 14: Evaluate an Integral of a Piecewise Function

Given the piecewise function

\[
f(x)=
\begin{cases}
x+1, & -1\leq x<1\\
2, & 1\leq x\leq 3
\end{cases}
\]

Evaluate:

\[
\int_{-1}^{3}f(x)\,dx
\]

## Step 1: Understand the Piecewise Function

The function has two different rules on two intervals:

- For \(-1\leq x<1\), use \(f(x)=x+1\).
- For \(1\leq x\leq3\), use \(f(x)=2\).

Because the formula changes at \(x=1\), we must split the integral at that point.

## Step 2: Split the Integral

Write the integral as

\[
\int_{-1}^{3}f(x)\,dx
=
\int_{-1}^{1}(x+1)\,dx
+
\int_{1}^{3}2\,dx
\]

Now evaluate each part separately.

## Step 3: Evaluate the First Integral

Calculate

\[
\int_{-1}^{1}(x+1)\,dx
\]

Find the antiderivative:

\[
\int(x+1)\,dx=\frac{x^2}{2}+x+C
\]

Apply the limits:

\[
\left[\frac{x^2}{2}+x\right]_{-1}^{1}
\]

Substitute \(x=1\):

\[
\frac{1^2}{2}+1=\frac32
\]

Substitute \(x=-1\):

\[
\frac{(-1)^2}{2}+(-1)
=\frac12-1=-\frac12
\]

Subtract:

\[
\frac32-\left(-\frac12\right)=2
\]

Therefore,

\[
\boxed{\int_{-1}^{1}(x+1)\,dx=2}
\]

## Step 4: Evaluate the Second Integral

Calculate

\[
\int_{1}^{3}2\,dx
\]

The antiderivative of \(2\) is \(2x\), so

\[
\left[2x\right]_{1}^{3}
=2(3)-2(1)
\]

\[
=6-2=4
\]

Therefore,

\[
\boxed{\int_{1}^{3}2\,dx=4}
\]

## Step 5: Add the Results

Combine both parts:

\[
\int_{-1}^{3}f(x)\,dx=2+4
\]

## Final Answer

\[
\boxed{\int_{-1}^{3}f(x)\,dx=6}
\]

## Step 6: Check Using Geometry

We can verify the answer by looking at the areas under the graph.

- From \(x=-1\) to \(x=1\), the graph \(y=x+1\) forms a triangle with base \(2\) and height \(2\). Its area is

\[
A_1=\frac12(2)(2)=2
\]

- From \(x=1\) to \(x=3\), the graph \(y=2\) forms a rectangle with width \(2\) and height \(2\). Its area is

\[
A_2=(2)(2)=4
\]

Add the areas:

\[
A_1+A_2=2+4=6
\]

This confirms the result.

## Key Idea

When integrating a piecewise function, **split the integral wherever the formula changes**.

Then integrate each piece over its own interval and add the results:

\[
\boxed{\int_a^b f(x)\,dx
=\int_a^c f_1(x)\,dx+\int_c^b f_2(x)\,dx}
\]

Here, the splitting point is \(c=1\), giving the final answer \(6\).

```
