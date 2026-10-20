
# Problem 4. A Quotient and Domain Control

Given the function

\[
f(x)=\frac{x^2+1}{x-1},
\]

determine the domain, compute the derivative, simplify the result, and explain why the restriction \(x\ne1\) remains important.

## Step 1: Determine the Domain

The function is a quotient:

\[
f(x)=\frac{x^2+1}{x-1}.
\]

A fraction is undefined when its denominator equals zero.

Set the denominator equal to zero:

\[
x-1=0.
\]

Therefore,

\[
x=1.
\]

This value must be excluded from the domain.

Hence, the domain is

\[
\boxed{D_f=\mathbb{R}\setminus\{1\}}.
\]

## Step 2: Identify the Quotient Rule

The quotient rule states that

\[
\boxed{
\left(\frac{u}{v}\right)'
=\frac{u'v-uv'}{v^2}
}
\]

where \(v\ne0\).

For our function, let

\[
u=x^2+1,\qquad v=x-1.
\]

Differentiate both expressions:

\[
u'=2x,\qquad v'=1.
\]

## Step 3: Apply the Quotient Rule

Substitute into the formula:

\[
f'(x)=
\frac{2x(x-1)-(x^2+1)(1)}{(x-1)^2}.
\]

Expand the numerator:

\[
f'(x)=
\frac{2x^2-2x-x^2-1}{(x-1)^2}.
\]

Combine like terms:

\[
\boxed{
f'(x)=\frac{x^2-2x-1}{(x-1)^2}
}.
\]

## Step 4: Explain the Domain Restriction

The derivative contains the denominator

\[
(x-1)^2.
\]

At \(x=1\), this denominator is zero, so the derivative is undefined.

More importantly, the original function itself is undefined at \(x=1\). Differentiation cannot restore a point that was excluded from the original function's domain.

Therefore, the derivative has the same domain restriction:

\[
\boxed{D_{f'}=\mathbb{R}\setminus\{1\}}.
\]

## Final Answers

**Domain of the function:**

\[
\boxed{D_f=\mathbb{R}\setminus\{1\}}
\]

**Derivative:**

\[
\boxed{
f'(x)=\frac{x^2-2x-1}{(x-1)^2}
}
\]

**Domain of the derivative:**

\[
\boxed{D_{f'}=\mathbb{R}\setminus\{1\}}
\]

**Key idea:** The restriction \(x\ne1\) must be preserved because the original function and its derivative are both undefined at that point.
