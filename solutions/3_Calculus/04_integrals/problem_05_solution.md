```

# Problem 5. The Same Substitution in a Different Context

Given:

\[
\int xe^{x^2}\,dx
\]

We need to recognize the appropriate substitution, calculate the integral, and verify the result by differentiation.

## Step 1: Compare with Problem 4

In Problem 4, we had:

\[
\int 2x(x^2+1)^4\,dx
\]

Here, we have:

\[
\int xe^{x^2}\,dx
\]

Although the functions look different, they share the same structure:

- Both contain an inner function involving \(x^2\).
- Both contain a factor related to the derivative of that inner function.
- Both can be solved using substitution.

The key is recognizing the derivative of the exponent \(x^2\).

## Step 2: Choose a Substitution

Let:

\[
u=x^2
\]

Differentiate both sides:

\[
\frac{du}{dx}=2x
\]

Therefore:

\[
du=2x\,dx
\]

However, our integral contains \(x\,dx\), not \(2x\,dx\).

Divide both sides by \(2\):

\[
x\,dx=\frac{1}{2}du
\]

## Step 3: Rewrite the Integral

Start with:

\[
\int xe^{x^2}\,dx
\]

Substitute:

\[
u=x^2,\qquad e^{x^2}=e^u,\qquad x\,dx=\frac12du
\]

The integral becomes:

\[
\int e^u\frac12\,du
\]

Take the constant outside:

\[
=\frac12\int e^u\,du
\]

## Step 4: Integrate

Since:

\[
\int e^u\,du=e^u+C
\]

we obtain:

\[
F(x)=\frac12e^u+C
\]

Substitute \(u=x^2\) back into the result:

\[
\boxed{F(x)=\frac12e^{x^2}+C}
\]

## Step 5: Verify by Differentiation

Differentiate the result using the chain rule:

\[
F'(x)=\frac12e^{x^2}\cdot 2x
\]

The constants simplify:

\[
F'(x)=xe^{x^2}
\]

Therefore:

\[
\boxed{F'(x)=xe^{x^2}}
\]

This matches the original integrand.

## Final Answer

\[
\boxed{\int xe^{x^2}\,dx=\frac12e^{x^2}+C}
\]

**Key idea:** Substitution depends on the structure of the integrand, not on whether the outer function is a power or an exponential. The derivative of the inner function \(x^2\) is \(2x\), so the missing factor of \(2\) produces the coefficient \(\frac12\).

```
