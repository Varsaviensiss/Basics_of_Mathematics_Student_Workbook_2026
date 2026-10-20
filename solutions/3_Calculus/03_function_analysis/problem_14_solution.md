
# Problem 14. Reconstructing Information from the Derivative

Given:

\[
f'(x)=(x-1)(x+2)
\]

Determine the monotonicity and extrema, sketch a possible qualitative shape of the function, and verify the derivative for

\[
g(x)=\frac{x^3}{3}+\frac{x^2}{2}-2x.
\]

## 1. Find the Critical Points

Set the derivative equal to zero:

\[
(x-1)(x+2)=0
\]

Therefore,

\[
x=1,\qquad x=-2.
\]

These critical points divide the real line into three intervals:

\[
(-\infty,-2),\quad (-2,1),\quad (1,\infty).
\]

## 2. Determine the Sign of the Derivative

- For \(x<-2\), both factors are negative, so \(f'(x)>0\).
- For \(-2<x<1\), one factor is negative and the other is positive, so \(f'(x)<0\).
- For \(x>1\), both factors are positive, so \(f'(x)>0\).

The sign chart is:

| Interval | Sign of \(f'(x)\) | Behavior |
|---|---|---|
| \((-\infty,-2)\) | \(+\) | Increasing |
| \((-2,1)\) | \(-\) | Decreasing |
| \((1,\infty)\) | \(+\) | Increasing |

## 3. Determine the Extrema

At \(x=-2\), the function changes from increasing to decreasing. Therefore, it has a local maximum at \(x=-2\).

At \(x=1\), the function changes from decreasing to increasing. Therefore, it has a local minimum at \(x=1\).

For the general function \(f\), the exact extremum values cannot be determined from \(f'(x)\) alone because the original function is not fully specified.

## 4. Verify the Derivative for \(g(x)\)

Given:

\[
g(x)=\frac{x^3}{3}+\frac{x^2}{2}-2x
\]

Differentiate each term:

\[
g'(x)=x^2+x-2
\]

Factor:

\[
g'(x)=(x-1)(x+2).
\]

This confirms the given derivative.

## 5. Find the Extrema of \(g(x)\)

At \(x=-2\):

\[
g(-2)=\frac{(-2)^3}{3}+\frac{(-2)^2}{2}-2(-2)
\]

\[
=-\frac{8}{3}+2+4=\frac{10}{3}.
\]

Therefore, the local maximum is

\[
\boxed{\left(-2,\frac{10}{3}\right)}.
\]

At \(x=1\):

\[
g(1)=\frac{1}{3}+\frac{1}{2}-2
\]

\[
=\frac{2}{6}+\frac{3}{6}-\frac{12}{6}
=-\frac{7}{6}.
\]

Therefore, the local minimum is

\[
\boxed{\left(1,-\frac{7}{6}\right)}.
\]

## 6. Qualitative Sketch

The graph of \(g(x)\):

- Increases until \(x=-2\).
- Reaches a local maximum at \(\left(-2,\frac{10}{3}\right)\).
- Decreases from \(x=-2\) to \(x=1\).
- Reaches a local minimum at \(\left(1,-\frac{7}{6}\right)\).
- Increases again for \(x>1\).

Since \(g(x)\) is a cubic polynomial with a positive leading coefficient, its graph goes down to the left and up to the right.

## Final Answers

1. Critical points: \(x=-2\) and \(x=1\).
2. Increasing intervals: \((-\infty,-2)\) and \((1,\infty)\).
3. Decreasing interval: \((-2,1)\).
4. For the general function \(f\), there is a local maximum at \(x=-2\) and a local minimum at \(x=1\).
5. The derivative of \(g(x)\) is \(g'(x)=(x-1)(x+2)\).
6. Local maximum of \(g\): \(\left(-2,\frac{10}{3}\right)\).
7. Local minimum of \(g\): \(\left(1,-\frac{7}{6}\right)\).
