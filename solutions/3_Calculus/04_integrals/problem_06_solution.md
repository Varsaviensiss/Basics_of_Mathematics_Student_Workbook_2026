```

# Problem 6: Find the Indefinite Integral

Evaluate:

\[
\int \frac{2x}{x^2+5}\,dx
\]

## Step 1: Choose a Method

The denominator is \(x^2+5\), and its derivative is \(2x\), which matches the numerator.

Therefore, **use substitution**.

## Step 2: Define the Substitution

Let

\[
u=x^2+5
\]

Differentiate both sides:

\[
du=2x\,dx
\]

So we can replace \(x^2+5\) with \(u\) and \(2x\,dx\) with \(du\).

## Step 3: Rewrite the Integral

\[
\int \frac{2x}{x^2+5}\,dx
=
\int \frac{1}{u}\,du
\]

## Step 4: Integrate

Recall the logarithmic integral rule:

\[
\int \frac{1}{u}\,du=\ln|u|+C
\]

Therefore,

\[
\int \frac{1}{u}\,du=\ln|u|+C
\]

Substitute \(u=x^2+5\) back into the result:

\[
\ln|x^2+5|+C
\]

Since \(x^2+5>0\) for every real number \(x\), we can remove the absolute value.

## Final Answer

\[
\boxed{\ln(x^2+5)+C}
\]

## Step 5: Verify by Differentiation

Differentiate the answer:

\[
\frac{d}{dx}\left[\ln(x^2+5)+C\right]
=
\frac{1}{x^2+5}\cdot 2x
\]

Thus,

\[
F'(x)=\frac{2x}{x^2+5}
\]

This matches the original integrand, so the answer is correct.

## Key Idea

When the numerator is the derivative of the denominator, look for the pattern

\[
\int \frac{g'(x)}{g(x)}\,dx
=
\ln|g(x)|+C
\]

Here, \(g(x)=x^2+5\) and \(g'(x)=2x\).

```
