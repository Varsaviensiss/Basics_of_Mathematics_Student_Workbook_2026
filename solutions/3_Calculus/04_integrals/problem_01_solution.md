```

# Problem 1. Antiderivative and Verification

Given:

\[
f(x)=3x^2-4x+5
\]

Find one antiderivative \(F(x)\), write the entire family of antiderivatives, verify the result by differentiation, and explain the meaning of the constant \(C\).

## Step 1: Understand the Goal

We need to find a function \(F(x)\) whose derivative is \(f(x)\).

In other words:

\[
F'(x)=3x^2-4x+5
\]

To do this, we integrate each term separately:

\[
F(x)=\int(3x^2-4x+5)\,dx
\]

## Step 2: Integrate Each Term

Use the power rule for integration:

\[
\int x^n\,dx=\frac{x^{n+1}}{n+1}+C,
\qquad n\neq -1
\]

First term:

\[
\int 3x^2\,dx
=3\cdot\frac{x^3}{3}
=x^3
\]

Second term:

\[
\int -4x\,dx
=-4\cdot\frac{x^2}{2}
=-2x^2
\]

Third term:

\[
\int 5\,dx=5x
\]

Combine the results:

\[
F(x)=x^3-2x^2+5x+C
\]

## Step 3: Write One Antiderivative

One antiderivative is obtained by choosing \(C=0\):

\[
\boxed{F(x)=x^3-2x^2+5x}
\]

## Step 4: Write the Entire Family of Antiderivatives

The complete family includes every possible constant \(C\):

\[
\boxed{F(x)=x^3-2x^2+5x+C}
\]

Here, \(C\) is any real constant.

Different values of \(C\) shift the graph vertically, but they do not change its derivative because the derivative of a constant is zero.

## Step 5: Verify the Result by Differentiation

Differentiate the general antiderivative:

\[
F(x)=x^3-2x^2+5x+C
\]

Using the power rule:

\[
F'(x)=3x^2-4x+5+0
\]

Therefore:

\[
\boxed{F'(x)=3x^2-4x+5}
\]

This matches the original function \(f(x)\), so the result is correct.

## Final Answer

One antiderivative:

\[
\boxed{F(x)=x^3-2x^2+5x}
\]

The entire family of antiderivatives:

\[
\boxed{F(x)=x^3-2x^2+5x+C}
\]

**Key idea:** Integration reverses differentiation. The constant \(C\) appears because every constant has a derivative of zero, so infinitely many functions can have the same derivative.

```
