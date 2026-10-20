
# Problem 2. Powers, Roots, and the Domain

Compute the integral

\[
\int\left(2x+3x^2-x^{1/3}\right)\,dx.
\]

First, rewrite the terms as powers, determine the domain of the original expression, and verify the result by differentiation.

## Step 1: Rewrite the Terms as Powers

The expression is

\[
2x+3x^2-\sqrt[3]{x}.
\]

Rewrite the first and third terms using exponent notation:

\[
2x=2x^1,\qquad \sqrt[3]{x}=x^{1/3}.
\]

Therefore, the integrand is

\[
2x^1+3x^2-x^{1/3}.
\]

## Step 2: Determine the Domain

The original expression contains a cube root:

\[
\sqrt[3]{x}.
\]

Unlike a square root, a cube root is defined for both positive and negative real numbers, as well as zero.

There are no denominators or logarithms that impose additional restrictions.

Therefore, the domain is

\[
\boxed{x\in\mathbb{R}}.
\]

## Step 3: Integrate Term by Term

Use the power rule:

\[
\int x^n\,dx=\frac{x^{n+1}}{n+1}+C,
\qquad n\ne-1.
\]

Integrate the first term:

\[
\int 2x\,dx
=2\frac{x^2}{2}
=x^2.
\]

Integrate the second term:

\[
\int 3x^2\,dx
=3\frac{x^3}{3}
=x^3.
\]

Integrate the third term:

\[
\int -x^{1/3}\,dx
=-\frac{x^{4/3}}{4/3}
=-\frac34x^{4/3}.
\]

Combining the terms gives

\[
\boxed{F(x)=x^2+x^3-\frac34x^{4/3}+C}.
\]

## Step 4: Verify by Differentiation

Differentiate the antiderivative:

\[
F'(x)=\frac{d}{dx}
\left(x^2+x^3-\frac34x^{4/3}+C\right).
\]

Apply the power rule:

\[
F'(x)=2x+3x^2-\frac34\cdot\frac43x^{1/3}.
\]

Since

\[
\frac34\cdot\frac43=1,
\]

we obtain

\[
F'(x)=2x+3x^2-x^{1/3}.
\]

This matches the original integrand.

Therefore,

\[
F'(x)=f(x).
\]

The result is correct.

## Final Answer

\[
\boxed{
\int\left(2x+3x^2-x^{1/3}\right)\,dx
=x^2+x^3-\frac34x^{4/3}+C
}
\]

The original expression and its antiderivative are defined for all real numbers \(x\).
