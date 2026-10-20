
# Problem 9. Derivative of a Logarithmic Function

Given:

\[
f(x)=\ln(x^2+1)
\]

## Step 1: Identify the Chain Rule

The function contains a logarithm with an inner function, so we use the chain rule.

The derivative rule for the natural logarithm is:

\[
\frac{d}{dx}\ln(u)=\frac{u'}{u}
\]

The inner function is:

\[
u=x^2+1
\]

## Step 2: Differentiate the Inner Function

Differentiate:

\[
u=x^2+1
\]

We get:

\[
u'=2x
\]

## Step 3: Apply the Chain Rule

Substitute \(u=x^2+1\) and \(u'=2x\) into the logarithm rule:

\[
f'(x)=\frac{2x}{x^2+1}
\]

Therefore,

\[
\boxed{f'(x)=\frac{2x}{x^2+1}}
\]

## Step 4: Determine Where the Derivative Is Positive or Negative

The denominator is always positive because:

\[
x^2+1>0
\]

Therefore, the sign of \(f'(x)\) depends only on the numerator, \(2x\).

- If \(x<0\), then \(f'(x)<0\). The function is decreasing.
- If \(x=0\), then \(f'(x)=0\).
- If \(x>0\), then \(f'(x)>0\). The function is increasing.

## Step 5: Find the Minimum

At \(x=0\):

\[
f(0)=\ln(0^2+1)=\ln(1)=0
\]

The function decreases before \(x=0\) and increases after \(x=0\). Therefore, it has a global minimum at:

\[
\boxed{(0,0)}
\]

## Final Answer

\[
\boxed{f'(x)=\frac{2x}{x^2+1}}
\]

- Decreasing on \((-\infty,0)\).
- Increasing on \((0,\infty)\).
- Global minimum at \(\boxed{(0,0)}\).

**Key idea:** The derivative tells us whether a function is increasing or decreasing. A change from negative to positive indicates a minimum.
