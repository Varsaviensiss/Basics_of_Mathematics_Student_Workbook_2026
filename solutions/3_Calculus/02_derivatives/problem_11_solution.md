```

# Problem 11. Finding a Derivative Using the Definition

Given:

\[
f(x)=x^2
\]

Find the derivative using the **definition of the derivative**, rather than the power rule.

## Step 1: Write the Definition

The derivative is defined as:

\[
f'(x)=\lim_{h\to 0}\frac{f(x+h)-f(x)}{h}
\]

This formula measures the change in the function divided by the change in \(x\), as the change approaches zero.

## Step 2: Calculate \(f(x+h)\)

Since:

\[
f(x)=x^2
\]

replace \(x\) with \(x+h\):

\[
f(x+h)=(x+h)^2
\]

Expand the square:

\[
f(x+h)=x^2+2xh+h^2
\]

## Step 3: Substitute into the Definition

Substitute \(f(x+h)\) and \(f(x)\) into the formula:

\[
f'(x)=\lim_{h\to 0}\frac{(x+h)^2-x^2}{h}
\]

Expand and simplify the numerator:

\[
f'(x)=\lim_{h\to 0}\frac{x^2+2xh+h^2-x^2}{h}
\]

The \(x^2\) terms cancel:

\[
f'(x)=\lim_{h\to 0}\frac{2xh+h^2}{h}
\]

## Step 4: Simplify the Expression

Factor \(h\) from the numerator:

\[
f'(x)=\lim_{h\to 0}\frac{h(2x+h)}{h}
\]

For \(h\neq 0\), cancel \(h\):

\[
f'(x)=\lim_{h\to 0}(2x+h)
\]

## Step 5: Evaluate the Limit

As \(h\to 0\), the expression becomes:

\[
f'(x)=2x+0
\]

Therefore,

\[
\boxed{f'(x)=2x}
\]

## Step 6: Compare with the Power Rule

The power rule states:

\[
\frac{d}{dx}x^n=nx^{n-1}
\]

For \(f(x)=x^2\):

\[
f'(x)=2x^{2-1}=2x
\]

Both methods give the same result.

## Final Answer

\[
\boxed{f'(x)=2x}
\]

**Key idea:** The derivative definition uses a limit to calculate the instantaneous rate of change. The power rule gives the same derivative more quickly, but the definition explains where the derivative comes from.

```
