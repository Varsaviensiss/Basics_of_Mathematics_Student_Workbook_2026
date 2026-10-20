```

# Problem 5. The Chain Rule as Working Through Layers

Given the function

\[
f(x)=(3x^2-2x+1)^5,
\]

identify the inner and outer functions, compute their derivatives, and apply the chain rule.

## Step 1: Identify the Inner and Outer Functions

The function contains an expression raised to the fifth power.

The inner function is

\[
u(x)=3x^2-2x+1.
\]

The outer function is

\[
g(u)=u^5.
\]

Therefore, the original function can be written as

\[
f(x)=g(u(x)).
\]

## Step 2: Differentiate the Inner Function

Differentiate

\[
u(x)=3x^2-2x+1.
\]

Using the power rule,

\[
u'(x)=6x-2.
\]

Thus,

\[
\boxed{u'(x)=6x-2}.
\]

## Step 3: Differentiate the Outer Function

The outer function is

\[
g(u)=u^5.
\]

Differentiating with respect to \(u\),

\[
g'(u)=5u^4.
\]

Therefore,

\[
\boxed{g'(u)=5u^4}.
\]

## Step 4: Apply the Chain Rule

The chain rule states that

\[
\boxed{f'(x)=g'(u(x))\cdot u'(x)}.
\]

In words, differentiate the outer function first, keep the inner expression unchanged, and then multiply by the derivative of the inner function.

Substitute the expressions we found:

\[
f'(x)=5(3x^2-2x+1)^4(6x-2).
\]

Therefore,

\[
\boxed{f'(x)=5(3x^2-2x+1)^4(6x-2)}.
\]

We can also factor out \(2\) from \(6x-2\):

\[
\boxed{f'(x)=10(3x-1)(3x^2-2x+1)^4}.
\]

## Step 5: Explain the Additional Factor

The factor

\[
6x-2
\]

appears because the inner function \(3x^2-2x+1\) also depends on \(x\).

If we differentiated only the outer power, we would obtain

\[
5(3x^2-2x+1)^4,
\]

which is incomplete. The chain rule requires multiplying this expression by the derivative of the inner function.

## Final Answer

\[
\boxed{
f'(x)=5(3x^2-2x+1)^4(6x-2)
}
\]

**Key idea:** When a function is composed of multiple layers, differentiate the outer layer and multiply by the derivative of the inner layer.

```
