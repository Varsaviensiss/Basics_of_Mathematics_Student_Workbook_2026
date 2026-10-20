
# Problem 5. An Exponential Function with a Maximum

Given the function:

\[
f(x)=xe^{-x}
\]

Analyze its monotonicity, extrema, and behavior as \(x\to\infty\).

## 1. Find the Domain

The exponential function \(e^{-x}\) is defined for every real number. Therefore,

\[
\boxed{D_f=\mathbb{R}}
\]

## 2. Find the Derivative

Use the product rule:

\[
f'(x)=1\cdot e^{-x}+x(-e^{-x})
\]

Simplify:

\[
f'(x)=e^{-x}(1-x)
\]

Since \(e^{-x}>0\) for all real \(x\), the sign of \(f'(x)\) depends only on \(1-x\).

Set the derivative equal to zero:

\[
e^{-x}(1-x)=0
\]

Because \(e^{-x}\ne0\),

\[
1-x=0
\]

\[
x=1
\]

## 3. Determine the Monotonicity

For \(x<1\),

\[
1-x>0\implies f'(x)>0
\]

Therefore, \(f\) is increasing on

\[
\boxed{(-\infty,1)}
\]

For \(x>1\),

\[
1-x<0\implies f'(x)<0
\]

Therefore, \(f\) is decreasing on

\[
\boxed{(1,\infty)}
\]

## 4. Find the Maximum

The function changes from increasing to decreasing at \(x=1\), so it has a maximum there.

Evaluate the function:

\[
f(1)=1\cdot e^{-1}
\]

\[
f(1)=\frac{1}{e}
\]

Thus, the maximum point is

\[
\boxed{\left(1,\frac{1}{e}\right)}
\]

This is the global maximum because the function increases before \(x=1\) and decreases afterward.

## 5. Examine the Limit as \(x\to\infty\)

Rewrite the function:

\[
f(x)=\frac{x}{e^x}
\]

As \(x\to\infty\), both numerator and denominator approach infinity. Applying L'Hôpital's rule gives

\[
\lim_{x\to\infty}\frac{x}{e^x}
=
\lim_{x\to\infty}\frac{1}{e^x}
=0
\]

Therefore,

\[
\boxed{\lim_{x\to\infty}xe^{-x}=0}
\]

The graph approaches the horizontal asymptote \(y=0\) from above on the right-hand side. After reaching its maximum, the function decreases toward zero but remains positive for \(x>0\).

## 6. Examine the Behavior as \(x\to-\infty\)

As \(x\to-\infty\),

\[
e^{-x}\to\infty
\]

while \(x\to-\infty\). Consequently,

\[
\boxed{\lim_{x\to-\infty}xe^{-x}=-\infty}
\]

Thus, the left-hand side of the graph descends without bound.

## Final Answers

1. Domain: \(\boxed{\mathbb{R}}\).
2. Derivative: \(\boxed{f'(x)=e^{-x}(1-x)}\).
3. Increasing on: \(\boxed{(-\infty,1)}\).
4. Decreasing on: \(\boxed{(1,\infty)}\).
5. Global maximum point: \(\boxed{\left(1,\frac{1}{e}\right)}\).
6. Limit as \(x\to\infty\): \(\boxed{0}\).
7. Horizontal asymptote on the right: \(\boxed{y=0}\).
8. Limit as \(x\to-\infty\): \(\boxed{-\infty}\).
