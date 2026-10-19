# Problem 1. Antiderivative and Verification

Given:

\[
f(x)=3x^2-4x+5
\]

## 1. Find One Antiderivative \(F(x)\)

An antiderivative \(F(x)\) of \(f(x)\) satisfies:

\[
F'(x)=f(x)
\]

Integrate both sides:

\[
F(x)=\int (3x^2-4x+5)\,dx
\]

Using the sum rule for integration:

\[
F(x)=\int 3x^2\,dx-\int 4x\,dx+\int 5\,dx
\]

Apply the power rule:

\[
\int x^n\,dx=\frac{x^{n+1}}{n+1}+C,
\qquad n\neq -1
\]

Integrate each term separately:

\[
\int 3x^2\,dx
=3\cdot\frac{x^{2+1}}{2+1}
\]

\[
\int 3x^2\,dx=x^3
\]

\[
\int (-4x)\,dx
=-4\cdot\frac{x^{1+1}}{1+1}
\]

\[
\int (-4x)\,dx=-2x^2
\]

\[
\int 5\,dx=5x
\]

Combine the results:

\[
F(x)=x^3-2x^2+5x+C
\]

One antiderivative is obtained by choosing \(C=0\):

\[
\boxed{F(x)=x^3-2x^2+5x}
\]

## 2. Write the Entire Family of Antiderivatives

The indefinite integral includes an arbitrary constant because the derivative of any constant is zero.

Therefore, the entire family of antiderivatives is:

\[
\boxed{F(x)=x^3-2x^2+5x+C,\qquad C\in\mathbb{R}}
\]

Different values of \(C\) give different antiderivatives, but all have the same derivative.

For example:

| Constant \(C\) | Antiderivative |
|---:|---|
| \(0\) | \(x^3-2x^2+5x\) |
| \(1\) | \(x^3-2x^2+5x+1\) |
| \(-3\) | \(x^3-2x^2+5x-3\) |

## 3. Verify the Result by Differentiation

Start with the general antiderivative:

\[
F(x)=x^3-2x^2+5x+C
\]

Differentiate both sides term by term:

\[
F'(x)=\frac{d}{dx}(x^3-2x^2+5x+C)
\]

Apply the power rule:

\[
F'(x)=3x^{3-1}-2(2x^{2-1})+5\frac{d}{dx}(x)+\frac{d}{dx}(C)
\]

Simplify each term:

\[
F'(x)=3x^2-4x+5+0
\]

Therefore:

\[
F'(x)=3x^2-4x+5
\]

Since the original function is

\[
f(x)=3x^2-4x+5,
\]

we obtain:

\[
F'(x)=f(x)
\]

Hence, the antiderivative is verified:

\[
\boxed{F'(x)=f(x)}
\]

## 4. Explain the Meaning of the Constant \(C\)

The constant \(C\) represents any real number that can be added to an antiderivative without changing its derivative.

For any constant \(C\),

\[
\frac{d}{dx}(C)=0
\]

Consequently,

\[
\frac{d}{dx}\left(x^3-2x^2+5x+C\right)
=3x^2-4x+5
\]

Thus, all functions of the form

\[
F(x)=x^3-2x^2+5x+C
\]

have the same derivative.

Geometrically, changing \(C\) shifts the graph vertically without changing its shape or slope at any \(x\)-value.

## Final Answer

One antiderivative is:

\[
\boxed{F(x)=x^3-2x^2+5x}
\]

The complete family of antiderivatives is:

\[
\boxed{F(x)=x^3-2x^2+5x+C,\qquad C\in\mathbb{R}}
\]

Differentiation confirms the result:

\[
\boxed{F'(x)=3x^2-4x+5=f(x)}
\]

The constant \(C\) accounts for all possible vertical shifts of the antiderivative and does not affect its derivative.

