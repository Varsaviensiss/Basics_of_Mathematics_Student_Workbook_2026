```

# Problem 12. Product Rule and Chain Rule

Given:

\[
f(x)=(x^2+1)^3e^x
\]

## Step 1: Identify the Rules

The function is the product of two expressions:

\[
u=(x^2+1)^3,\qquad v=e^x
\]

Therefore, we use the **product rule**:

\[
(uv)'=u'v+uv'
\]

To differentiate \((x^2+1)^3\), we also need the **chain rule**.

## Step 2: Differentiate the First Factor

Let:

\[
u=(x^2+1)^3
\]

Using the chain rule:

\[
\frac{d}{dx}(g(x))^3=3(g(x))^2g'(x)
\]

Here, the inner function is:

\[
g(x)=x^2+1
\]

Its derivative is:

\[
g'(x)=2x
\]

Therefore:

\[
u'=3(x^2+1)^2(2x)
\]

Simplify:

\[
\boxed{u'=6x(x^2+1)^2}
\]

## Step 3: Differentiate the Second Factor

Let:

\[
v=e^x
\]

The derivative of \(e^x\) is \(e^x\), so:

\[
\boxed{v'=e^x}
\]

## Step 4: Apply the Product Rule

Using:

\[
f'(x)=u'v+uv'
\]

Substitute the derivatives:

\[
f'(x)=6x(x^2+1)^2e^x+(x^2+1)^3e^x
\]

## Step 5: Simplify the Result

Both terms contain \(e^x(x^2+1)^2\). Factor it out:

\[
f'(x)=e^x(x^2+1)^2[6x+(x^2+1)]
\]

Simplify the expression inside the brackets:

\[
6x+(x^2+1)=x^2+6x+1
\]

Therefore, the simplified derivative is:

\[
\boxed{f'(x)=e^x(x^2+1)^2(x^2+6x+1)}
\]

## Final Answer

\[
\boxed{f'(x)=e^x(x^2+1)^2(x^2+6x+1)}
\]

**Key idea:** When a function is a product, use the product rule. If one factor contains a function raised to a power, use the chain rule to differentiate that factor.

```
