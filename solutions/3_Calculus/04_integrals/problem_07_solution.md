
# Problem 7: Find the Indefinite Integral

Evaluate:

\[
\int xe^x\,dx
\]

## Step 1: Choose a Method

The integrand is a product of two functions: \(x\) and \(e^x\).

We should use **integration by parts**.

The formula is:

\[
\int u\,dv=uv-\int v\,du
\]

## Step 2: Choose \(u\) and \(dv\)

Let

\[
u=x \qquad dv=e^x\,dx
\]

Differentiate \(u\):

\[
du=dx
\]

Integrate \(dv\):

\[
v=\int e^x\,dx=e^x
\]

We choose \(u=x\) because differentiating it simplifies it to \(1\), while \(e^x\) is easy to integrate.

## Step 3: Apply the Formula

Using

\[
\int u\,dv=uv-\int v\,du
\]

we get

\[
\int xe^x\,dx
=xe^x-\int e^x\,dx
\]

## Step 4: Evaluate the Remaining Integral

Since

\[
\int e^x\,dx=e^x
\]

we obtain

\[
\int xe^x\,dx=xe^x-e^x+C
\]

Factor out \(e^x\):

\[
\int xe^x\,dx=e^x(x-1)+C
\]

## Final Answer

\[
\boxed{e^x(x-1)+C}
\]

## Step 5: Verify by Differentiation

Differentiate using the product rule:

\[
\frac{d}{dx}\left[e^x(x-1)+C\right]
\]

\[
=e^x(x-1)+e^x(1)
\]

Simplify:

\[
=e^x(x-1+1)
\]

\[
=xe^x
\]

This matches the original integrand, so the answer is correct.

## Key Idea

Use integration by parts when an integral contains a product of functions and differentiating one of them makes it simpler.

For this problem:

- \(u=x\), because its derivative is \(1\).
- \(dv=e^x\,dx\), because its integral is \(e^x\).
