```

# Problem 8: Find the Indefinite Integral

Evaluate:

\[
\int x\cos x\,dx
\]

## Step 1: Choose a Method

The integrand is a product of two functions, \(x\) and \(\cos x\).

Therefore, use **integration by parts**.

The formula is:

\[
\int u\,dv=uv-\int v\,du
\]

## Step 2: Choose \(u\) and \(dv\)

Let

\[
u=x
\]

\[
dv=\cos x\,dx
\]

Differentiate \(u\):

\[
du=dx
\]

Integrate \(dv\):

\[
v=\int\cos x\,dx=\sin x
\]

We choose \(u=x\) because differentiating it simplifies it to \(1\).

## Step 3: Apply Integration by Parts

Using the formula,

\[
\int u\,dv=uv-\int v\,du
\]

we get

\[
\int x\cos x\,dx
=x\sin x-\int\sin x\,dx
\]

## Step 4: Evaluate the Remaining Integral

Recall that

\[
\int\sin x\,dx=-\cos x
\]

Substitute this into the expression:

\[
\int x\cos x\,dx
=x\sin x-(-\cos x)+C
\]

Simplify:

\[
\int x\cos x\,dx=x\sin x+\cos x+C
\]

## Final Answer

\[
\boxed{x\sin x+\cos x+C}
\]

## Step 5: Verify by Differentiation

Differentiate the answer:

\[
\frac{d}{dx}(x\sin x+\cos x+C)
\]

Using the product rule:

\[
=\sin x+x\cos x-\sin x
\]

The \(\sin x\) terms cancel:

\[
=x\cos x
\]

This matches the original integrand, so the answer is correct.

## Key Idea

For integration by parts, choose the function that becomes simpler when differentiated as \(u\).

Here, \(u=x\) becomes \(1\), while \(\cos x\) is easy to integrate into \(\sin x\).

```
