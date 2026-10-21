```

# Problem 2. Powers, Roots, and the Domain

Given:

\[
\int (2x+3x^2-x^{1/3})\,dx
\]

We need to rewrite the terms as powers, determine the domain of the original expression, calculate the antiderivative, and verify the result by differentiation.

## Step 1: Rewrite the Terms as Powers

The integrand is:

\[
f(x)=2x+3x^2-x^{1/3}
\]

The fractional exponent represents a cube root:

\[
x^{1/3}=\sqrt[3]{x}
\]

Therefore, we can write:

\[
f(x)=2x^1+3x^2-x^{1/3}
\]

All terms are now expressed as powers of \(x\).

## Step 2: Determine the Domain

The original function contains the cube root:

\[
\sqrt[3]{x}
\]

Unlike a square root, a cube root is defined for negative numbers, zero, and positive numbers.

Therefore, the domain is:

\[
\boxed{D_f=\mathbb{R}}
\]

The integrand is defined for every real number.

## Step 3: Apply the Power Rule for Integration

The power rule is:

\[
\int x^n\,dx=\frac{x^{n+1}}{n+1}+C,
\qquad n\neq -1
\]

Integrate each term separately.

First term:

\[
\int 2x\,dx
=2\cdot\frac{x^2}{2}
=x^2
\]

Second term:

\[
\int 3x^2\,dx
=3\cdot\frac{x^3}{3}
=x^3
\]

Third term:

\[
\int -x^{1/3}\,dx
=-\frac{x^{4/3}}{4/3}
=-\frac{3}{4}x^{4/3}
\]

## Step 4: Combine the Results

Adding the three antiderivatives gives:

\[
F(x)=x^2+x^3-\frac{3}{4}x^{4/3}+C
\]

Thus, the entire family of antiderivatives is:

\[
\boxed{F(x)=x^2+x^3-\frac{3}{4}x^{4/3}+C}
\]

## Step 5: Verify by Differentiation

Differentiate the result:

\[
F(x)=x^2+x^3-\frac{3}{4}x^{4/3}+C
\]

Using the power rule:

\[
F'(x)=2x+3x^2-\frac{3}{4}\cdot\frac{4}{3}x^{1/3}
\]

The coefficients simplify:

\[
\frac{3}{4}\cdot\frac{4}{3}=1
\]

Therefore:

\[
\boxed{F'(x)=2x+3x^2-x^{1/3}}
\]

This matches the original integrand.

## Final Answer

The domain of the original function is:

\[
\boxed{D_f=\mathbb{R}}
\]

The entire family of antiderivatives is:

\[
\boxed{F(x)=x^2+x^3-\frac{3}{4}x^{4/3}+C}
\]

**Key idea:** Rewrite roots as fractional powers, integrate each term using the power rule, and differentiate the result to verify it. The cube root allows the original expression to be defined for every real number.

```
