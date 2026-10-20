```

# Problem 13. A Logarithm and an Asymptote

Given:

\[
f(x)=\frac{\ln x}{x},\qquad x>0.
\]

Perform a complete analysis of the function. Find the maximum and examine its behavior at the ends of the domain. Explain what information is necessary for a correct sketch.

## 1. Find the Domain

The natural logarithm \(\ln x\) is defined only for \(x>0\). Therefore,

\[
\boxed{D_f=(0,\infty)}
\]

## 2. Find the Zero

Set \(f(x)=0\):

\[
\frac{\ln x}{x}=0
\]

Since \(x>0\), this means

\[
\ln x=0
\]

\[
x=1.
\]

The function has one zero:

\[
\boxed{(1,0)}
\]

## 3. Find the Derivative

Using the quotient rule:

\[
f'(x)=\frac{x\cdot\frac1x-\ln x\cdot1}{x^2}
\]

Simplify:

\[
f'(x)=\frac{1-\ln x}{x^2}
\]

Set the derivative equal to zero:

\[
1-\ln x=0
\]

\[
\ln x=1
\]

\[
x=e.
\]

The critical point is \(x=e\).

## 4. Determine Monotonicity

Since \(x^2>0\) for every \(x>0\), the sign of \(f'(x)\) depends on \(1-\ln x\).

- For \(0<x<e\), \(1-\ln x>0\), so \(f'(x)>0\).
- For \(x>e\), \(1-\ln x<0\), so \(f'(x)<0\).

Therefore, the function is:

- Increasing on \((0,e)\).
- Decreasing on \((e,\infty)\).

## 5. Find the Maximum

The derivative changes from positive to negative at \(x=e\). Thus, the function has a maximum there.

Calculate the function value:

\[
f(e)=\frac{\ln e}{e}=\frac1e.
\]

The maximum point is

\[
\boxed{\left(e,\frac1e\right)}.
\]

This is the global maximum on the domain.

## 6. Examine the Limits

As \(x\to0^+\):

\[
\lim_{x\to0^+}\frac{\ln x}{x}=-\infty.
\]

Therefore, \(x=0\) is a vertical asymptote.

As \(x\to\infty\):

\[
\lim_{x\to\infty}\frac{\ln x}{x}=0.
\]

Therefore, \(y=0\) is a horizontal asymptote as \(x\to\infty\).

## 7. Determine the Sign of the Function

- For \(0<x<1\), \(\ln x<0\), so \(f(x)<0\).
- At \(x=1\), \(f(x)=0\).
- For \(x>1\), \(\ln x>0\), so \(f(x)>0\).

## 8. Qualitative Sketch

The graph:

- Starts at negative infinity as \(x\to0^+\).
- Crosses the \(x\)-axis at \((1,0)\).
- Continues increasing until the maximum \(\left(e,\frac1e\right)\).
- Decreases after \(x=e\).
- Approaches the horizontal asymptote \(y=0\) from above as \(x\to\infty\).

For a correct sketch, mark the domain, intercept, maximum point, vertical asymptote, horizontal asymptote, and increasing/decreasing intervals.

## Final Answers

1. Domain: \((0,\infty)\).
2. Zero: \(x=1\).
3. Derivative: \(f'(x)=\frac{1-\ln x}{x^2}\).
4. Increasing interval: \((0,e)\).
5. Decreasing interval: \((e,\infty)\).
6. Global maximum: \(\left(e,\frac1e\right)\).
7. Vertical asymptote: \(x=0\).
8. Horizontal asymptote: \(y=0\), as \(x\to\infty\).

```
