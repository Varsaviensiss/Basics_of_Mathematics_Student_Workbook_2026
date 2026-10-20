```

# Problem 4. Substitution as Reversing the Chain Rule

Compute the integral

\[
\int 2x(x^2+1)^4\,dx.
\]

Before calculating, identify a suitable substitution and show that its derivative appears in the integral. Then verify the result by differentiation.

## Step 1: Identify the Substitution

The expression \(x^2+1\) is raised to the fourth power.

Let

\[
u=x^2+1.
\]

Differentiate both sides with respect to \(x\):

\[
\frac{du}{dx}=2x.
\]

Therefore,

\[
du=2x\,dx.
\]

The factor \(2x\,dx\) already appears in the original integral, so this substitution simplifies the expression.

## Step 2: Rewrite the Integral

The original integral is

\[
\int 2x(x^2+1)^4\,dx.
\]

Using

\[
u=x^2+1
\]

and

\[
du=2x\,dx,
\]

we obtain

\[
\int u^4\,du.
\]

## Step 3: Integrate Using the Power Rule

Apply the power rule:

\[
\int u^4\,du=\frac{u^5}{5}+C.
\]

Thus,

\[
F(u)=\frac{u^5}{5}+C.
\]

Substitute \(u=x^2+1\) back into the result:

\[
\boxed{F(x)=\frac{(x^2+1)^5}{5}+C}.
\]

## Step 4: Verify by Differentiation

Differentiate the result using the chain rule:

\[
F'(x)=\frac{d}{dx}
\left(\frac{(x^2+1)^5}{5}+C\right).
\]

Applying the chain rule gives

\[
F'(x)=\frac15\cdot5(x^2+1)^4\cdot2x.
\]

Simplify:

\[
F'(x)=2x(x^2+1)^4.
\]

This matches the original integrand exactly.

Therefore, the result is correct.

## Final Answer

\[
\boxed{
\int 2x(x^2+1)^4\,dx
=\frac{(x^2+1)^5}{5}+C
}
\]

**Key idea:** Substitution reverses the chain rule. When the derivative of an inner function appears as a factor in the integrand, replacing the inner function with \(u\) can simplify the integral.

```
