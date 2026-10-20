```

# Problem 3. Recognizing Basic Antiderivatives

Compute the integral

\[
\int(2e^x+3\cos x-4\sin x)\,dx.
\]

Match each term with a known derivative and verify the result by differentiation.

## Step 1: Recall the Basic Antiderivatives

We use the following derivative rules:

\[
\frac{d}{dx}e^x=e^x
\]

\[
\frac{d}{dx}\sin x=\cos x
\]

\[
\frac{d}{dx}\cos x=-\sin x
\]

Reversing these rules gives the basic antiderivatives:

\[
\int e^x\,dx=e^x+C
\]

\[
\int\cos x\,dx=\sin x+C
\]

\[
\int\sin x\,dx=-\cos x+C
\]

## Step 2: Integrate Each Term Separately

Using the sum rule for integration,

\[
\int(2e^x+3\cos x-4\sin x)\,dx
\]

\[
=\int2e^x\,dx+\int3\cos x\,dx-\int4\sin x\,dx.
\]

Integrate the first term:

\[
\int2e^x\,dx=2e^x.
\]

Integrate the second term:

\[
\int3\cos x\,dx=3\sin x.
\]

Integrate the third term:

\[
\int-4\sin x\,dx=4\cos x.
\]

Therefore, the antiderivative is

\[
\boxed{F(x)=2e^x+3\sin x+4\cos x+C}.
\]

## Step 3: Verify by Differentiation

Differentiate the entire result:

\[
F'(x)=\frac{d}{dx}
\left(2e^x+3\sin x+4\cos x+C\right).
\]

Applying the derivative rules gives

\[
F'(x)=2e^x+3\cos x-4\sin x.
\]

This is exactly the original integrand:

\[
F'(x)=2e^x+3\cos x-4\sin x.
\]

Therefore, the result is correct.

## Final Answer

\[
\boxed{
\int(2e^x+3\cos x-4\sin x)\,dx
=2e^x+3\sin x+4\cos x+C
}
\]

```
