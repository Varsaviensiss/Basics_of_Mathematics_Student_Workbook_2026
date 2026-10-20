
# Problem 7. Chain Rule

Given:

\[
f(x)=\sin(x^2+1)
\]

## Step 1: Identify the Inner and Outer Functions

This function contains one function inside another, so we use the **chain rule**.

The chain rule is:

\[
\frac{d}{dx}f(g(x))=f'(g(x))\cdot g'(x)
\]

Identify the outer and inner functions:

- Outer function: \(\sin(u)\)
- Inner function: \(u=x^2+1\)

## Step 2: Differentiate the Outer Function

The derivative of \(\sin(u)\) is:

\[
\frac{d}{du}\sin(u)=\cos(u)
\]

Therefore, the derivative of the outer function is:

\[
\cos(x^2+1)
\]

## Step 3: Differentiate the Inner Function

The inner function is:

\[
u=x^2+1
\]

Its derivative is:

\[
\frac{du}{dx}=2x
\]

## Step 4: Apply the Chain Rule

Multiply the derivative of the outer function by the derivative of the inner function:

\[
f'(x)=\cos(x^2+1)\cdot 2x
\]

Thus,

\[
\boxed{f'(x)=2x\cos(x^2+1)}
\]

## Step 5: Determine the Sign of \(f'(0)\)

Substitute \(x=0\):

\[
f'(0)=2(0)\cos(0^2+1)
\]

\[
f'(0)=0\cdot\cos(1)
\]

Therefore,

\[
\boxed{f'(0)=0}
\]

The tangent line at \(x=0\) is horizontal.

## Final Answer

\[
\boxed{f'(x)=2x\cos(x^2+1)}
\]

\[
\boxed{f'(0)=0}
\]

**Key idea:** When differentiating a composite function, differentiate the outer function first, keep the inner function unchanged, and then multiply by the derivative of the inner function.
