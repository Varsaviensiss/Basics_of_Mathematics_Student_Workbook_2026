# Problem 1. A Cubic Polynomial

Analyze the monotonicity and extrema of

\[
f(x)=x^3-3x^2+2.
\]

## 1. Domain

Since \(f\) is a polynomial,

\[
D_f=\mathbb{R}.
\]

## 2. First Derivative

Differentiate:

\[
f'(x)=3x^2-6x.
\]

Factor:

\[
f'(x)=3x(x-2).
\]

Critical points satisfy \(f'(x)=0\):

\[
3x(x-2)=0.
\]

Therefore,

\[
x=0 \quad \text{or} \quad x=2.
\]

## 3. Sign of the Derivative

The critical points divide the real line into three intervals.

- If \(x<0\), both \(x\) and \(x-2\) are negative, so \(f'(x)>0\).
- If \(0<x<2\), \(x>0\) and \(x-2<0\), so \(f'(x)<0\).
- If \(x>2\), both factors are positive, so \(f'(x)>0\).

Thus,

| Interval | Sign of \(f'(x)\) | Behavior |
|---|---|---|
| \((-\infty,0)\) | \(+\) | Increasing |
| \((0,2)\) | \(-\) | Decreasing |
| \((2,\infty)\) | \(+\) | Increasing |

## 4. Local Extrema

At \(x=0\), the derivative changes from positive to negative. Therefore, \(x=0\) is a local maximum.

\[
f(0)=0-0+2=2.
\]

The local maximum is

\[
\boxed{(0,2)}.
\]

At \(x=2\), the derivative changes from negative to positive. Therefore, \(x=2\) is a local minimum.

\[
f(2)=8-12+2=-2.
\]

The local minimum is

\[
\boxed{(2,-2)}.
\]

## 5. End Behavior

The leading term is \(x^3\), so

\[
\lim_{x\to-\infty}f(x)=-\infty,
\qquad
\lim_{x\to\infty}f(x)=\infty.
\]

## 6. Sketch

The graph rises from the lower left, reaches a local maximum at \((0,2)\), falls to a local minimum at \((2,-2)\), and then rises toward the upper right.

```text
 y
 ↑
 2             ● (0,2)
              / \
             /   \
 0 ---------/-----\--------------→ x
           /       \
          /         ● (2,-2)
                    / \
                   /   \
```

The sketch is qualitative and not to scale. The critical points are \((0,2)\) and \((2,-2)\).

## Final Answer

\[
\boxed{\text{Increasing on }(-\infty,0)\text{ and }(2,\infty)}
\]

\[
\boxed{\text{Decreasing on }(0,2)}
\]

\[
\boxed{\text{Local maximum: }(0,2)}
\]

\[
\boxed{\text{Local minimum: }(2,-2)}
\]
