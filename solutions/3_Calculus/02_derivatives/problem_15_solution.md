```

# Problem 15. Understanding the Difference Quotient

Given:

\[
f(x)=x^2
\]

Use the difference quotient to estimate the derivative at \(x=1\), and explain how it approaches the exact derivative.

## Step 1: Write the Difference Quotient

The difference quotient is:

\[
\frac{f(x+h)-f(x)}{h}
\]

To estimate the derivative at \(x=1\), substitute \(x=1\):

\[
\frac{f(1+h)-f(1)}{h}
\]

## Step 2: Calculate the Function Values

Since \(f(x)=x^2\):

\[
f(1+h)=(1+h)^2
\]

Expanding:

\[
f(1+h)=1+2h+h^2
\]

Also:

\[
f(1)=1^2=1
\]

## Step 3: Simplify the Difference Quotient

Substitute the function values:

\[
\frac{f(1+h)-f(1)}{h}
=
\frac{(1+h)^2-1}{h}
\]

Expand and simplify:

\[
=\frac{1+2h+h^2-1}{h}
\]

\[
=\frac{2h+h^2}{h}
\]

Factor and cancel \(h\), where \(h\neq 0\):

\[
=\frac{h(2+h)}{h}
\]

Therefore:

\[
\boxed{\frac{f(1+h)-f(1)}{h}=2+h}
\]

## Step 4: Estimate the Derivative

Choose values of \(h\) that get closer to zero.

| \(h\) | Difference quotient \(2+h\) |
|---:|---:|
| \(1\) | \(3\) |
| \(0.1\) | \(2.1\) |
| \(0.01\) | \(2.01\) |
| \(0.001\) | \(2.001\) |
| \(-0.01\) | \(1.99\) |
| \(-0.001\) | \(1.999\) |

As \(h\) approaches zero from either direction, the difference quotient approaches \(2\).

## Step 5: Find the Exact Derivative

The derivative is the limit of the difference quotient:

\[
f'(1)=\lim_{h\to 0}\frac{f(1+h)-f(1)}{h}
\]

Using the simplified expression:

\[
f'(1)=\lim_{h\to 0}(2+h)
\]

As \(h\to 0\):

\[
\boxed{f'(1)=2}
\]

This agrees with the power rule:

\[
f'(x)=2x
\]

Therefore:

\[
f'(1)=2(1)=2
\]

## Final Answer

The difference quotient is:

\[
\boxed{2+h}
\]

The exact derivative at \(x=1\) is:

\[
\boxed{f'(1)=2}
\]

**Key idea:** The difference quotient gives the slope of a secant line. As \(h\) approaches zero, the secant slope approaches the slope of the tangent line, which is the derivative. Numerical examples illustrate this behavior, while the limit establishes the exact result.

```
