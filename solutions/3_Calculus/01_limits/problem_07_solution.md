# Exercise 7. Limit at a Point and Canceling a Factor

## Question

Compute the limit by factoring the numerator and canceling the common factor:

$$
\lim_{x\to3}\frac{x^2-4x+3}{x-3}.
$$

Explain why the value of the function at $x=3$ is not needed to evaluate this limit.

## Solution

Direct substitution gives the indeterminate form $0/0$. Factor the numerator:

$$
x^2-4x+3=(x-1)(x-3).
$$

For $x\ne3$, we can cancel the common factor:

$$
\frac{x^2-4x+3}{x-3}
=\frac{(x-1)(x-3)}{x-3}
=x-1.
$$

Since $x-1$ is continuous at $x=3$,

$$
\lim_{x\to3}\frac{x^2-4x+3}{x-3}
=\lim_{x\to3}(x-1)
=3-1
=\boxed{2}.
$$

### Why the Function Value at $x=3$ Is Not Needed

The limit depends on the function values for $x$ arbitrarily close to $3$ with $x\ne3$. The original fraction is undefined at $x=3$, but it equals $x-1$ on both sides of $3$. Those nearby values approach $2$, so the limit exists.
