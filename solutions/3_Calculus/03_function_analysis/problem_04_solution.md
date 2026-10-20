
# Problem 4. A Function with Two Vertical Asymptotes

Given the function:

\[
f(x)=\frac{1}{x^2-1}
\]

Determine the domain, asymptotes, sign, and monotonicity on the intervals of the domain.

## 1. Find the Domain

The denominator must not equal zero:

\[
x^2-1\ne0
\]

Factor:

\[
(x-1)(x+1)\ne0
\]

Therefore,

\[
x\ne-1,\qquad x\ne1
\]

The domain is

\[
\boxed{D_f=\mathbb{R}\setminus\{-1,1\}}
\]

This creates three separate intervals:

\[
(-\infty,-1),\quad(-1,1),\quad(1,\infty)
\]

## 2. Find the Asymptotes

**Vertical asymptotes:**

The denominator is zero at \(x=-1\) and \(x=1\), while the numerator is nonzero.

Therefore,

\[
\boxed{x=-1,\qquad x=1}
\]

**Horizontal asymptote:**

As \(x\to\pm\infty\),

\[
\lim_{x\to\pm\infty}\frac{1}{x^2-1}=0
\]

Thus,

\[
\boxed{y=0}
\]

## 3. Determine the Sign

Factor the denominator:

\[
f(x)=\frac{1}{(x-1)(x+1)}
\]

Analyze the sign on each interval.

- For \(x<-1\), both factors are negative, so their product is positive. Hence \(f(x)>0\).
- For \(-1<x<1\), the factors have opposite signs. Hence \(f(x)<0\).
- For \(x>1\), both factors are positive. Hence \(f(x)>0\).

Therefore,

\[
\boxed{f(x)>0\text{ on }(-\infty,-1)\cup(1,\infty)}
\]

\[
\boxed{f(x)<0\text{ on }(-1,1)}
\]

The function has no zeros because its numerator is always \(1\).

## 4. Find the Derivative

Differentiate:

\[
f'(x)=-\frac{2x}{(x^2-1)^2}
\]

Since the denominator is positive everywhere in the domain, the sign of \(f'(x)\) depends on \(-2x\).

- If \(x<0\), then \(f'(x)>0\).
- If \(x>0\), then \(f'(x)<0\).

Therefore:

- Increasing on \((-\infty,-1)\).
- Increasing on \((-1,0)\).
- Decreasing on \((0,1)\).
- Decreasing on \((1,\infty)\).

At \(x=0\),

\[
f(0)=\frac{1}{-1}=-1
\]

The function has a local maximum at

\[
\boxed{(0,-1)}
\]

## 5. Explain Why Each Interval Must Be Analyzed Separately

The function is undefined at \(x=-1\) and \(x=1\). These points divide the domain into three disconnected intervals.

The function cannot be continuous across either vertical asymptote, so its behavior on one interval cannot automatically be extended across the excluded points. Monotonicity must therefore be described separately on each interval.

## Final Answers

1. Domain: \(\boxed{\mathbb{R}\setminus\{-1,1\}}\).
2. Vertical asymptotes: \(\boxed{x=-1,\ x=1}\).
3. Horizontal asymptote: \(\boxed{y=0}\).
4. Sign: positive for \(|x|>1\), negative for \(|x|<1\).
5. Increasing on \((-\infty,-1)\) and \((-1,0)\).
6. Decreasing on \((0,1)\) and \((1,\infty)\).
7. Local maximum: \(\boxed{(0,-1)}\).
8. There are no zeros.
