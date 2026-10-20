```

# Problem 8. Derivatives of Exponential Functions

Given:

\[
f(x)=e^{2x-3}+5^x
\]

## Step 1: Identify the Derivative Rules

We use two exponential derivative rules.

For the natural exponential function:

\[
\frac{d}{dx}e^{u}=e^u\cdot u'
\]

For an exponential function with base \(a\):

\[
\frac{d}{dx}a^x=a^x\ln(a)
\]

## Step 2: Differentiate the First Term

The first term is:

\[
e^{2x-3}
\]

The inner function is:

\[
u=2x-3
\]

Its derivative is:

\[
u'=2
\]

Using the chain rule:

\[
\frac{d}{dx}e^{2x-3}=e^{2x-3}\cdot 2
\]

Therefore,

\[
\frac{d}{dx}e^{2x-3}=2e^{2x-3}
\]

## Step 3: Differentiate the Second Term

The second term is:

\[
5^x
\]

Using the exponential derivative rule:

\[
\frac{d}{dx}5^x=5^x\ln(5)
\]

Therefore,

\[
\frac{d}{dx}5^x=5^x\ln(5)
\]

## Step 4: Combine the Derivatives

Since the original function is a sum, differentiate each term separately:

\[
f'(x)=2e^{2x-3}+5^x\ln(5)
\]

## Final Answer

\[
\boxed{f'(x)=2e^{2x-3}+5^x\ln(5)}
\]

**Key idea:**
- For \(e^{u}\), multiply by the derivative of the exponent \(u'\).
- For \(a^x\), multiply by \(\ln(a)\).

```
