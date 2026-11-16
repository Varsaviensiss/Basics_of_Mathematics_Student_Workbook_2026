# Problem 8. Two Exponential Functions

For the function

$$
f(x)=e^{2x-3}+5^x,
$$

compute the derivative. Explain why the factor $2$ appears in the first term and why $\ln 5$ appears in the second.

## Step 1: Differentiate the First Term

The inner function is $u(x)=2x-3$, whose derivative is $u'(x)=2$.

By the chain rule,

$$
\frac{d}{dx}e^{2x-3}
=e^{2x-3}\frac{d}{dx}(2x-3)
=2e^{2x-3}.
$$

The factor $2$ comes from differentiating the exponent $2x-3$.

## Step 2: Differentiate the Second Term

Rewrite the exponential using base $e$:

$$
5^x=e^{x\ln 5}.
$$

Since $\ln 5$ is constant, the derivative of the exponent $x\ln 5$ is $\ln 5$. Applying the chain rule gives

$$
\frac{d}{dx}5^x
=\frac{d}{dx}e^{x\ln 5}
=e^{x\ln 5}\ln 5
=5^x\ln 5.
$$

Thus, the factor $\ln 5$ comes from differentiating the exponent $x\ln 5$.

## Step 3: Combine the Derivatives

Using the sum rule,

$$
\boxed{f'(x)=2e^{2x-3}+5^x\ln 5}.
$$
