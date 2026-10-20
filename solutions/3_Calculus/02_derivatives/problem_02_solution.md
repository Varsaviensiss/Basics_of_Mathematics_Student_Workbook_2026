```

# Problem 2. Powers, Roots, and the Domain

Given the function

\[
f(x)=2x-3x^2+\sqrt{x},
\]

1. Rewrite the function using powers.
2. Determine its domain.
3. Compute the derivative.
4. Compare the domain of the function with the domain of its derivative.

## Step 1: Rewrite the Function Using Powers

We know that

\[
\sqrt{x}=x^{1/2}.
\]

Therefore, the function can be written as

\[
\boxed{f(x)=2x-3x^2+x^{1/2}}.
\]

This form allows us to apply the power rule to each term.

## Step 2: Determine the Domain

The terms \(2x\) and \(-3x^2\) are defined for all real numbers.

However, the square root \(\sqrt{x}\) is defined over the real numbers only when

\[
x\geq 0.
\]

Therefore, the domain of the original function is

\[
\boxed{D_f=[0,\infty)}.
\]

## Step 3: Compute the Derivative

Using the power rule,

\[
\frac{d}{dx}x^n=nx^{n-1},
\]

differentiate each term separately:

\[
\frac{d}{dx}(2x)=2,
\]

\[
\frac{d}{dx}(-3x^2)=-6x,
\]

\[
\frac{d}{dx}(x^{1/2})
=\frac12x^{-1/2}.
\]

Combining the results,

\[
f'(x)=2-6x+\frac12x^{-1/2}.
\]

Rewrite the negative exponent using a square root:

\[
\boxed{f'(x)=2-6x+\frac{1}{2\sqrt{x}}}.
\]

## Step 4: Determine the Domain of the Derivative

The derivative contains the term

\[
\frac{1}{2\sqrt{x}}.
\]

For this expression to be defined, the square root must be real and the denominator must not equal zero.

Thus,

\[
x>0.
\]

At \(x=0\), the original function is defined, but the derivative formula is undefined. In fact, the right-hand difference quotient for the square-root term grows without bound as \(x\) approaches zero from the right, so there is no finite derivative at \(x=0\).

Therefore, the domain of the derivative is

\[
\boxed{D_{f'}=(0,\infty)}.
\]

## Step 5: Compare the Domains

The original function is defined at \(x=0\), but its derivative is not defined there.

Hence,

\[
\boxed{D_f=[0,\infty)}
\]

and

\[
\boxed{D_{f'}=(0,\infty)}.
\]

The derivative's domain is smaller because differentiability requires a finite derivative, which fails at \(x=0\).

## Final Answers

**Function in power form:**

\[
\boxed{f(x)=2x-3x^2+x^{1/2}}
\]

**Domain of the function:**

\[
\boxed{D_f=[0,\infty)}
\]

**Derivative:**

\[
\boxed{f'(x)=2-6x+\frac{1}{2\sqrt{x}},\quad x>0}
\]

**Domain of the derivative:**

\[
\boxed{D_{f'}=(0,\infty)}
\]

**Key idea:** A function can be defined at a point without being differentiable there. In this example, \(f(0)\) exists, but \(f'(0)\) does not.

```
