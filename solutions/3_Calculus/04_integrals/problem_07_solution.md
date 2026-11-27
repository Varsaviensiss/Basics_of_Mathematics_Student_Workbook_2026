# Problem 7. Integration by Parts as Reversing the Product Rule

## Question

Compute

$$
\int xe^x\,dx.
$$

First write the product differentiation rule and, on that basis, explain the meaning of the integration-by-parts formula. Verify the result by differentiation.

## Solution

### 1. Derive the integration-by-parts formula

The product rule states that

$$
(uv)'=u'v+uv'.
$$

Integrating both sides gives

$$
uv=\int u'v\,dx+\int uv'\,dx,
$$

with the constant of integration absorbed into the antiderivatives. Rearranging gives

$$
\int uv'\,dx=uv-\int u'v\,dx.
$$

Integration by parts reverses the product rule by rewriting the integral of $uv'$ as the product $uv$ minus the integral of $u'v$. This helps when differentiating $u$ makes the remaining integral simpler.

### 2. Apply the formula

Choose $u=x$ and $v'=e^x$. Then $u'=1$ and we can take $v=e^x$. This choice reduces the remaining integral to $\int e^x\,dx$.

$$
\int xe^x\,dx
=xe^x-\int e^x\,dx
=xe^x-e^x+C
=e^x(x-1)+C.
$$

### 3. Verify by differentiation

Using the product rule gives

$$
\frac{d}{dx}\left[e^x(x-1)+C\right]
=e^x(x-1)+e^x
=xe^x.
$$

The derivative matches the original integrand.
