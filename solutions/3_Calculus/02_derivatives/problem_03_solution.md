```

# Problem 3. The Product Rule — Why Is It Needed?

Given the function

\[
f(x)=(x^2+1)e^x,
\]

compute the derivative. Then compare the correct result with the incorrect idea of differentiating only the first factor.

## Step 1: Identify the Two Factors

The function is a product of two functions:

\[
u(x)=x^2+1
\]

and

\[
v(x)=e^x.
\]

Because both factors depend on \(x\), we must use the **product rule**.

The product rule states that

\[
\boxed{(uv)'=u'v+uv'}.
\]

In words, differentiate the first factor and keep the second unchanged, then add the first factor multiplied by the derivative of the second.

## Step 2: Differentiate Each Factor

Differentiate the first factor:

\[
u'(x)=\frac{d}{dx}(x^2+1)=2x.
\]

Differentiate the second factor:

\[
v'(x)=\frac{d}{dx}(e^x)=e^x.
\]

## Step 3: Apply the Product Rule

Using

\[
f'(x)=u'(x)v(x)+u(x)v'(x),
\]

substitute the expressions:

\[
f'(x)=2x\cdot e^x+(x^2+1)e^x.
\]

Therefore,

\[
f'(x)=2xe^x+(x^2+1)e^x.
\]

Factor out the common factor \(e^x\):

\[
\boxed{f'(x)=e^x(x^2+2x+1)}.
\]

Since \(x^2+2x+1=(x+1)^2\), we can also write

\[
\boxed{f'(x)=e^x(x+1)^2}.
\]

## Step 4: Explain the Common Mistake

An incorrect approach would be to write

\[
f'(x)=2xe^x.
\]

This differentiates only the first factor \(x^2+1\) while leaving \(e^x\) unchanged.

The missing term is

\[
(x^2+1)e^x,
\]

which comes from differentiating the second factor \(e^x\).

The correct product rule includes both contributions:

\[
f'(x)=
\underbrace{2xe^x}_{\text{differentiate the first factor}}
+
\underbrace{(x^2+1)e^x}_{\text{differentiate the second factor}}.
\]

## Step 5: Verify by Differentiation Structure

The product rule gives the derivative of the original product directly:

\[
\frac{d}{dx}\left[(x^2+1)e^x\right]
=2xe^x+(x^2+1)e^x.
\]

Both factors have been accounted for, so the result is correct.

## Final Answer

\[
\boxed{f'(x)=2xe^x+(x^2+1)e^x}
\]

Equivalently,

\[
\boxed{f'(x)=e^x(x+1)^2}.
\]

**Key idea:** The derivative of a product is not generally the product of one factor's derivative and the other factor. The product rule requires two terms, one for each factor's derivative.

```
