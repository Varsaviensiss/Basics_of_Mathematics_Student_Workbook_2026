```

# Problem 13. Multiple Applications of the Chain Rule

Given:

\[
f(x)=e^{\sin(x^2)}
\]

Find the derivative using the chain rule.

## Step 1: Identify the Nested Functions

This function contains three layers:

1. The innermost function: \(u=x^2\)
2. The middle function: \(\sin(u)\)
3. The outermost function: \(e^{\sin(u)}\)

We must differentiate each layer, starting from the outside and working inward.

## Step 2: Differentiate the Outer Function

The outer function is an exponential function:

\[
\frac{d}{dx}e^u=e^u\cdot u'
\]

Keeping the exponent unchanged for now:

\[
f'(x)=e^{\sin(x^2)}\cdot\frac{d}{dx}\sin(x^2)
\]

## Step 3: Differentiate the Middle Function

The derivative of \(\sin(u)\) is:

\[
\frac{d}{dx}\sin(u)=\cos(u)\cdot u'
\]

Substituting \(u=x^2\):

\[
\frac{d}{dx}\sin(x^2)=\cos(x^2)\cdot\frac{d}{dx}(x^2)
\]

## Step 4: Differentiate the Inner Function

The innermost function is:

\[
u=x^2
\]

Using the power rule:

\[
\frac{d}{dx}(x^2)=2x
\]

Therefore:

\[
\frac{d}{dx}\sin(x^2)=2x\cos(x^2)
\]

## Step 5: Combine All the Derivatives

Substitute the result from Step 4 into the expression from Step 2:

\[
f'(x)=e^{\sin(x^2)}\cdot\cos(x^2)\cdot 2x
\]

Rearranging the factors gives:

\[
\boxed{f'(x)=2x\cos(x^2)e^{\sin(x^2)}}
\]

## Final Answer

\[
\boxed{f'(x)=2x\cos(x^2)e^{\sin(x^2)}}
\]

**Key idea:** For nested functions, apply the chain rule at every layer. Differentiate the outer function, keep the inner expression unchanged, and multiply by the derivative of the inner expression.

```
