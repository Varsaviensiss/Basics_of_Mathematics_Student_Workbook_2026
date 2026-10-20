```

# Problem 1. Antiderivative and Verification

Given the function

\[
f(x)=3x^2-4x+5,
\]

find one antiderivative, write the entire family of antiderivatives, verify the result by differentiation, and explain the meaning of the constant \(C\).

## Step 1: Find One Antiderivative

To find an antiderivative, integrate the function with respect to \(x\):

\[
F(x)=\int(3x^2-4x+5)\,dx.
\]

Using the power rule,

\[
\int x^n\,dx=\frac{x^{n+1}}{n+1}+C,
\qquad n\ne-1,
\]

integrate each term separately:

\[
\int 3x^2\,dx=x^3,
\]

\[
\int -4x\,dx=-2x^2,
\]

\[
\int 5\,dx=5x.
\]

Combining the results gives one antiderivative:

\[
\boxed{F(x)=x^3-2x^2+5x}.
\]

## Step 2: Write the Entire Family of Antiderivatives

When a function is differentiated, any constant disappears because the derivative of a constant is zero.

Therefore, we include an arbitrary constant \(C\):

\[
\boxed{F(x)=x^3-2x^2+5x+C}.
\]

This represents the entire family of antiderivatives of \(f(x)\).

## Step 3: Verify the Result by Differentiation

Differentiate the result:

\[
F'(x)=\frac{d}{dx}(x^3-2x^2+5x+C).
\]

Applying the power rule gives

\[
F'(x)=3x^2-4x+5+0.
\]

Thus,

\[
F'(x)=3x^2-4x+5.
\]

Since

\[
F'(x)=f(x),
\]

the antiderivative is verified.

## Step 4: Explain the Meaning of the Constant \(C\)

The constant \(C\) can be any real number. All functions of the form

\[
F(x)=x^3-2x^2+5x+C
\]

have the same derivative because the derivative of \(C\) is zero.

Geometrically, changing \(C\) shifts the graph vertically without changing its shape or slope at any point.

For example, the functions

\[
F_1(x)=x^3-2x^2+5x
\]

and

\[
F_2(x)=x^3-2x^2+5x+7
\]

have the same derivative:

\[
F_1'(x)=F_2'(x)=3x^2-4x+5.
\]

Therefore, the constant \(C\) accounts for all possible vertical shifts of the antiderivative.

## Final Answer

The entire family of antiderivatives is

\[
\boxed{F(x)=x^3-2x^2+5x+C,\qquad C\in\mathbb R}.
\]

Verification:

\[
\boxed{F'(x)=3x^2-4x+5=f(x)}.
\]

```
