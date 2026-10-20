
## Problem 15. Find the Error in the Monotonicity Analysis

Given:

\[
f(x)=x^3-3x
\]

The derivative is

\[
f'(x)=3(x-1)(x+1).
\]

### 1. Find the error

The critical points are

\[
x=-1,\qquad x=1.
\]

The student's error is claiming that the derivative is positive between its zeros and negative outside them. Since the derivative has a positive leading coefficient, its sign is positive outside the roots and negative between them.

### 2. Correct sign chart

- For \(x<-1\), \(f'(x)>0\).
- For \(-1<x<1\), \(f'(x)<0\).
- For \(x>1\), \(f'(x)>0\).

### 3. Intervals of monotonicity and extrema

- Increasing on \((-\infty,-1)\).
- Decreasing on \((-1,1)\).
- Increasing on \((1,\infty)\).

At \(x=-1\), the function changes from increasing to decreasing, so there is a local maximum:

\[
f(-1)=(-1)^3-3(-1)=2.
\]

Local maximum: \((-1,2)\).

At \(x=1\), the function changes from decreasing to increasing, so there is a local minimum:

\[
f(1)=1^3-3(1)=-2.
\]

Local minimum: \((1,-2)\).

### 4. Test points

Choose one point from each interval.

**Interval \((-\infty,-1)\):** choose \(x=-2\).

\[
f'(-2)=3(-3)(-1)=9>0.
\]

Therefore, the function is increasing.

**Interval \((-1,1)\):** choose \(x=0\).

\[
f'(0)=3(-1)(1)=-3<0.
\]

Therefore, the function is decreasing.

**Interval \((1,\infty)\):** choose \(x=2\).

\[
f'(2)=3(1)(3)=9>0.
\]

Therefore, the function is increasing.

### Conclusion

The student reversed the signs of the derivative. The correct function increases, then decreases, then increases, with a local maximum at \((-1,2)\) and a local minimum at \((1,-2)\).
