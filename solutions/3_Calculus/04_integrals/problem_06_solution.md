# Problem 6. When Does a Logarithm Appear from an Integral?

## Question

Compute

$$
\int\frac{2x}{x^2+5}\,dx.
$$

Identify the denominator as a candidate for substitution, compare the numerator with its derivative, and explain the source of the logarithm in the result.

## Solution

### 1. Choose the substitution

The denominator is $x^2+5$, and its derivative is $2x$, exactly the numerator. Let $u=x^2+5$. Then $du=2x\,dx$, so

$$
\int\frac{2x}{x^2+5}\,dx=\int\frac{1}{u}\,du.
$$

### 2. Explain the logarithm and integrate

The substitution leaves the reciprocal $1/u$. Its antiderivative is $\ln|u|$ because $\frac{d}{du}\ln|u|=1/u$ for $u\ne0$. Therefore,

$$
\int\frac{2x}{x^2+5}\,dx
=\ln|x^2+5|+C
=\ln(x^2+5)+C.
$$

The absolute value can be removed because $x^2+5>0$ for every real $x$.

### 3. Verify by differentiation

By the chain rule,

$$
\frac{d}{dx}\left[\ln(x^2+5)+C\right]
=\frac{1}{x^2+5}\cdot2x
=\frac{2x}{x^2+5}.
$$

The derivative matches the original integrand.
