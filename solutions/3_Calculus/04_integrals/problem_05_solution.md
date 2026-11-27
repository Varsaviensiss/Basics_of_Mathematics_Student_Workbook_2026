# Problem 5. The Same Substitution in a Different Context

## Question

Compute

$$
\int xe^{x^2}\,dx.
$$

First compare the structure with Problem 4 and explain what is common despite the different appearance of the function.

## Solution

### 1. Compare with Problem 4 before calculating

In Problem 4, the integrand is $2x(x^2+1)^4$. The inner function is $x^2+1$, and its derivative $2x$ appears as a factor.

Here the integrand is $xe^{x^2}$. The inner function is $x^2$, and the factor $x$ is half its derivative. In both problems, the integrand is an outer function evaluated at an inner function, multiplied by a constant multiple of the inner derivative. This structure makes substitution work in both cases.

### 2. Substitute and integrate

Let $u=x^2$. Then $du=2x\,dx$, so $x\,dx=\frac12\,du$. Substituting gives

$$
\int xe^{x^2}\,dx
=\frac12\int e^u\,du
=\frac12e^u+C
=\frac12e^{x^2}+C.
$$

### 3. Verify by differentiation

The chain rule gives

$$
\frac{d}{dx}\left(\frac12e^{x^2}+C\right)
=\frac12e^{x^2}\cdot 2x
=xe^{x^2}.
$$

The derivative matches the original integrand.
