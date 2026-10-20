```

# Problem 15. Find the Error in the Monotonicity Analysis

Given:

\[
f(x)=x^3-3x
\]

The derivative is correctly computed as:

\[
f'(x)=3(x-1)(x+1)
\]

A student claims that the function is decreasing on \((-\infty,-1)\cup(1,\infty)\) and increasing on \((-1,1)\).

## 1. Find the Error

The critical points are found by setting the derivative equal to zero:

\[
3(x-1)(x+1)=0
\]

\[
x=-1,\qquad x=1
\]

The student's error is reversing the signs of the derivative. Since the derivative has a positive leading coefficient, it is positive outside the roots and negative between them.

## 2. Construct the Correct Sign Chart

The critical points divide the real line into three intervals:

\[
(-\infty,-1),\qquad (-1,1),\qquad (1,\infty)
\]

The derivative signs are:

| Interval | Sign of \(f'(x)\) |
|---|---|
| \((-\infty,-1)\) | Positive \((+)\) |
| \((-1,1)\) | Negative \((-)\) |
| \((1,\infty)\) | Positive \((+)\) |

## 3. Determine Monotonicity and Extrema

- The function is increasing on \((-\infty,-1)\).
- The function is decreasing on \((-1,1)\).
- The function is increasing on \((1,\infty)\).

At \(x=-1\), the function changes from increasing to decreasing. Therefore, there is a local maximum:

\[
f(-1)=(-1)^3-3(-1)=-1+3=2
\]

Local maximum point:

\[
\boxed{(-1,2)}
\]

At \(x=1\), the function changes from decreasing to increasing. Therefore, there is a local minimum:

\[
f(1)=1^3-3(1)=1-3=-2
\]

Local minimum point:

\[
\boxed{(1,-2)}
\]

## 4. Verify Using Test Points

Choose one test point from each interval.

**Interval 1: \((-\infty,-1)\)**

Choose \(x=-2\):

\[
f'(-2)=3(-2-1)(-2+1)
\]

\[
=3(-3)(-1)=9>0
\]

Therefore, the function is increasing.

**Interval 2: \((-1,1)\)**

Choose \(x=0\):

\[
f'(0)=3(0-1)(0+1)
\]

\[
=3(-1)(1)=-3<0
\]

Therefore, the function is decreasing.

**Interval 3: \((1,\infty)\)**

Choose \(x=2\):

\[
f'(2)=3(2-1)(2+1)
\]

\[
=3(1)(3)=9>0
\]

Therefore, the function is increasing.

## Final Answers

1. The student's error is reversing the signs of the derivative.
2. The correct derivative signs are \(+,-,+\).
3. Increasing intervals: \((-\infty,-1)\) and \((1,\infty)\).
4. Decreasing interval: \((-1,1)\).
5. Local maximum: \((-1,2)\).
6. Local minimum: \((1,-2)\).
7. Test points \(-2\), \(0\), and \(2\) confirm the correct sign chart.

```
