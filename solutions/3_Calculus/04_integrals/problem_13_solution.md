```

# Problem 13: Use the Fundamental Theorem of Calculus

Given:

\[
F(x)=\int_0^x(t^2+1)\,dt
\]

Find \(F(x)\) and \(F'(x)\). Explain the relationship between the derivative and the integrand.

## Step 1: Understand the Integral

We are given

\[
F(x)=\int_0^x(t^2+1)\,dt
\]

The lower limit is \(0\), and the upper limit is \(x\).

The variable \(t\) is a dummy variable of integration. It is used inside the integral, while \(x\) determines the upper limit.

To find \(F(x)\), we first evaluate the integral.

## Step 2: Find the Antiderivative

Integrate each term:

\[
\int(t^2+1)\,dt
=\frac{t^3}{3}+t+C
\]

Therefore,

\[
F(x)=\left[\frac{t^3}{3}+t\right]_0^x
\]

## Step 3: Apply the Limits

Evaluate at the upper limit \(t=x\):

\[
\frac{x^3}{3}+x
\]

Evaluate at the lower limit \(t=0\):

\[
\frac{0^3}{3}+0=0
\]

Subtract the lower-limit value from the upper-limit value:

\[
F(x)=\left(\frac{x^3}{3}+x\right)-0
\]

Thus,

\[
\boxed{F(x)=\frac{x^3}{3}+x}
\]

## Step 4: Find \(F'(x)\)

Differentiate \(F(x)\):

\[
F'(x)=\frac{d}{dx}\left(\frac{x^3}{3}+x\right)
\]

Differentiate each term:

\[
F'(x)=x^2+1
\]

Therefore,

\[
\boxed{F'(x)=x^2+1}
\]

## Step 5: Explain the Relationship

Recall the **Fundamental Theorem of Calculus**:

\[
\frac{d}{dx}\left(\int_a^x f(t)\,dt\right)=f(x)
\]

This theorem tells us that differentiating an accumulation function recovers the original integrand evaluated at the upper limit.

In this problem,

\[
F(x)=\int_0^x(t^2+1)\,dt
\]

so

\[
F'(x)=x^2+1
\]

The derivative is exactly the original integrand, with \(t\) replaced by \(x\).

## Final Answers

\[
\boxed{F(x)=\frac{x^3}{3}+x}
\]

\[
\boxed{F'(x)=x^2+1}
\]

## Key Idea: Accumulation and Rate of Change

The function \(F(x)\) measures the accumulated signed area under \(y=t^2+1\) from \(0\) to \(x\).

Its derivative \(F'(x)\) describes how quickly that accumulated area changes as the upper limit moves.

Because the integrand is \(t^2+1\), the rate of change at \(x\) is

\[
\boxed{F'(x)=x^2+1}
\]

```
