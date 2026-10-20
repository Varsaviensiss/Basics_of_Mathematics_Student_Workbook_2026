
# Problem 3. A Rational Function

Given the function:

\[
f(x)=\frac{x+1}{x-2}
\]

Analyze the domain, zeros, asymptotes, and monotonicity. Sketch a graph consistent with the results.

## 1. Find the Domain

The denominator cannot equal zero:

\[
x-2\ne0
\]

\[
x\ne2
\]

Therefore, the domain is

\[
\boxed{D_f=\mathbb{R}\setminus\{2\}}
\]

## 2. Find the Zero

Set \(f(x)=0\). A fraction equals zero when its numerator is zero and its denominator is nonzero.

\[
x+1=0
\]

\[
x=-1
\]

Since \(-1-2\ne0\), this is valid.

Therefore, the zero is

\[
\boxed{x=-1}
\]

The graph crosses the \(x\)-axis at \((-1,0)\).

## 3. Find the Asymptotes

Rewrite the function:

\[
f(x)=\frac{x-2+3}{x-2}
\]

\[
f(x)=1+\frac{3}{x-2}
\]

**Vertical asymptote:**

The denominator approaches zero at \(x=2\), while the numerator approaches \(3\).

\[
\boxed{x=2}
\]

**Horizontal asymptote:**

As \(x\to\pm\infty\),

\[
\frac{3}{x-2}\to0
\]

Therefore,

\[
\boxed{y=1}
\]

## 4. Determine the Monotonicity

Differentiate using the quotient rule:

\[
f'(x)=\frac{(x-2)-(x+1)}{(x-2)^2}
\]

Simplify:

\[
f'(x)=\frac{-3}{(x-2)^2}
\]

Since \((x-2)^2>0\) for every \(x\ne2\),

\[
f'(x)<0
\]

Thus, the function is strictly decreasing on each interval of its domain:

\[
\boxed{(-\infty,2)}
\]

\[
\boxed{(2,\infty)}
\]

The intervals must be considered separately because the function is undefined at \(x=2\).

## 5. Determine the Behavior Near the Asymptotes

As \(x\to2^-\),

\[
\lim_{x\to2^-}f(x)=-\infty
\]

As \(x\to2^+\),

\[
\lim_{x\to2^+}f(x)=+\infty
\]

At both ends of the real line,

\[
\lim_{x\to-\infty}f(x)=1
\]

\[
\lim_{x\to+\infty}f(x)=1
\]

The graph approaches \(y=1\) from below on the left and from above on the right.

## Final Answers

1. Domain: \(\boxed{\mathbb{R}\setminus\{2\}}\).
2. Zero: \(\boxed{x=-1}\).
3. Vertical asymptote: \(\boxed{x=2}\).
4. Horizontal asymptote: \(\boxed{y=1}\).
5. Derivative: \(\boxed{f'(x)=-\frac{3}{(x-2)^2}}\).
6. Monotonicity: strictly decreasing on \((-\infty,2)\) and \((2,\infty)\).
