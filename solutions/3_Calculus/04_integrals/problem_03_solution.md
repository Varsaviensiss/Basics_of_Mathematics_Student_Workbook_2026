
# Problem 3. Recognizing Basic Antiderivatives

Given:

\[
\int (2e^x+3\cos x-4\sin x)\,dx
\]

We need to integrate each term using known antiderivative rules and verify the result by differentiation.

## Step 1: Identify the Basic Antiderivatives

We use the following rules:

\[
\int e^x\,dx=e^x+C
\]

\[
\int \cos x\,dx=\sin x+C
\]

\[
\int \sin x\,dx=-\cos x+C
\]

The last rule follows because the derivative of \(-\cos x\) is \(\sin x\).

## Step 2: Integrate Each Term

First term:

\[
\int 2e^x\,dx=2e^x
\]

Second term:

\[
\int 3\cos x\,dx=3\sin x
\]

Third term:

\[
\int -4\sin x\,dx=4\cos x
\]

Notice that the third term becomes positive because:

\[
\int \sin x\,dx=-\cos x
\]

## Step 3: Combine the Results

Adding the antiderivatives gives:

\[
F(x)=2e^x+3\sin x+4\cos x+C
\]

Therefore, the entire family of antiderivatives is:

\[
\boxed{F(x)=2e^x+3\sin x+4\cos x+C}
\]

## Step 4: Verify by Differentiation

Differentiate each term:

\[
\frac{d}{dx}(2e^x)=2e^x
\]

\[
\frac{d}{dx}(3\sin x)=3\cos x
\]

\[
\frac{d}{dx}(4\cos x)=-4\sin x
\]

Also:

\[
\frac{d}{dx}C=0
\]

Combining the derivatives:

\[
F'(x)=2e^x+3\cos x-4\sin x
\]

This matches the original integrand.

## Final Answer

\[
\boxed{\int (2e^x+3\cos x-4\sin x)\,dx
=2e^x+3\sin x+4\cos x+C}
\]

**Key idea:** Recognize the basic antiderivatives of exponential and trigonometric functions. Pay particular attention to signs: the antiderivative of \(\sin x\) is \(-\cos x\).
