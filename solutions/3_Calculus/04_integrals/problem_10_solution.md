```

# Problem 10: Estimate and Evaluate a Definite Integral

Evaluate:

\[
\int_0^2 (x^2+1)\,dx
\]

First, estimate the integral using bounds. Then calculate its exact value and explain how the estimate helps us check our answer.

## Step 1: Find Bounds for the Function

On the interval \(0\le x\le 2\), we have

\[
0\le x^2\le 4
\]

Adding \(1\) to every part gives

\[
1\le x^2+1\le 5
\]

Therefore, the function \(f(x)=x^2+1\) stays between \(1\) and \(5\) throughout the interval \([0,2]\).

## Step 2: Use the Bounds to Estimate the Integral

Since the interval has length

\[
2-0=2
\]

and the function is always at least \(1\) and at most \(5\), its integral must satisfy

\[
1(2)\le \int_0^2(x^2+1)\,dx\le 5(2)
\]

Simplifying:

\[
\boxed{2\le \int_0^2(x^2+1)\,dx\le 10}
\]

So the integral must lie between \(2\) and \(10\).

## Step 3: Calculate the Exact Value

Integrate each term:

\[
\int(x^2+1)\,dx
=\frac{x^3}{3}+x+C
\]

Apply the limits:

\[
\int_0^2(x^2+1)\,dx
=\left[\frac{x^3}{3}+x\right]_0^2
\]

Evaluate at \(x=2\):

\[
\frac{2^3}{3}+2=\frac83+2=\frac{14}{3}
\]

Evaluate at \(x=0\):

\[
\frac{0^3}{3}+0=0
\]

Subtract:

\[
\int_0^2(x^2+1)\,dx
=\frac{14}{3}-0
\]

## Final Answer

\[
\boxed{\frac{14}{3}}
\]

Approximately,

\[
\frac{14}{3}\approx 4.67
\]

## Step 4: Check the Estimate

Our bounds were

\[
2\le \int_0^2(x^2+1)\,dx\le 10
\]

The exact answer satisfies them because

\[
2\le \frac{14}{3}\le 10
\]

Therefore, our result is consistent with the estimate.

## Key Idea: Why Are Bounds Useful?

Bounds give us a quick way to check whether an answer is reasonable.

If we had calculated an answer of \(12\) or \(-3\), we would know that something was wrong because the integral must lie between \(2\) and \(10\).

**Remember:** Estimating the bounds does not replace finding the exact integral. It provides a useful check on the final result.

```
