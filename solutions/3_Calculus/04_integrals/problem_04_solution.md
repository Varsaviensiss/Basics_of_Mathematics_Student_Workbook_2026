```

# Problem 4. Substitution as Reversing the Chain Rule

Given:

\[
\int 2x(x^2+1)^4\,dx
\]

We need to identify a suitable substitution, calculate the integral, and verify the result by differentiation.

## Step 1: Identify the Inner Function

Notice that the expression contains:

\[
(x^2+1)^4
\]

The inner function is:

\[
u=x^2+1
\]

Differentiate it:

\[
\frac{du}{dx}=2x
\]

Therefore:

\[
du=2x\,dx
\]

The factor \(2x\,dx\) already appears in the original integral. This makes substitution convenient.

## Step 2: Substitute into the Integral

Start with:

\[
\int 2x(x^2+1)^4\,dx
\]

Using:

\[
u=x^2+1,\qquad du=2x\,dx
\]

we obtain:

\[
\int u^4\,du
\]

## Step 3: Apply the Power Rule

The power rule for integration is:

\[
\int u^n\,du=\frac{u^{n+1}}{n+1}+C
\]

For \(n=4\):

\[
\int u^4\,du=\frac{u^5}{5}+C
\]

Therefore:

\[
F(x)=\frac{u^5}{5}+C
\]

## Step 4: Substitute Back

Replace \(u\) with \(x^2+1\):

\[
F(x)=\frac{(x^2+1)^5}{5}+C
\]

Thus, the antiderivative is:

\[
\boxed{F(x)=\frac{(x^2+1)^5}{5}+C}
\]

## Step 5: Verify by Differentiation

Differentiate the result using the chain rule:

\[
F'(x)=\frac{1}{5}\cdot 5(x^2+1)^4\cdot 2x
\]

Simplify:

\[
F'(x)=(x^2+1)^4\cdot 2x
\]

Therefore:

\[
\boxed{F'(x)=2x(x^2+1)^4}
\]

This matches the original integrand.

## Final Answer

\[
\boxed{\int 2x(x^2+1)^4\,dx
=\frac{(x^2+1)^5}{5}+C}
\]

**Key idea:** Substitution reverses the chain rule. When the derivative of an inner function appears as a factor in the integrand, replacing the inner function with \(u\) can turn a complicated integral into a simple power-rule integral.

```
