# Problem 15. Find the Error in the Monotonicity Analysis

## Question

For the function

$$
f(x)=x^3-3x,
$$

the derivative was correctly computed as

$$
f'(x)=3(x-1)(x+1).
$$

However, a student wrote the following conclusion:

> The derivative is positive between its zeros and negative outside them. Therefore, the function is decreasing on $(-\infty,-1)\cup(1,\infty)$, increasing on $(-1,1)$, has a local minimum at $x=-1$, and a local maximum at $x=1$.

1. Without differentiating again, explain why merely identifying the zeros of the derivative does not justify the stated sign chart, and find the error in the student's reasoning.
2. Construct the correct sign chart for $f'(x)$.
3. Give the correct intervals of monotonicity and the character of the extrema.
4. In each of the three intervals, choose one simple test point and show that the sign of the derivative confirms your classification.

## Solution

### 1. Find the error

The zeros $x=-1$ and $x=1$ tell us where to split the real line. To determine the sign on each interval, we must check the signs of the factors $x-1$ and $x+1$. The student reversed the signs of their product.

### 2. Construct the correct sign chart

The factor $3$ is positive, so $f'(x)$ has the sign of $(x-1)(x+1)$.

| Interval | Sign of $x-1$ | Sign of $x+1$ | Sign of $f'(x)$ |
|---|---|---|---|
| $(-\infty,-1)$ | $-$ | $-$ | $+$ |
| $(-1,1)$ | $-$ | $+$ | $-$ |
| $(1,\infty)$ | $+$ | $+$ | $+$ |

### 3. Determine monotonicity and extrema

The function is increasing on $(-\infty,-1)$ and $(1,\infty)$ and decreasing on $(-1,1)$.

At $x=-1$, the derivative changes from positive to negative. Since $f(-1)=(-1)^3-3(-1)=2$, the graph has a **local maximum at $(-1,2)$**.

At $x=1$, the derivative changes from negative to positive. Since $f(1)=1^3-3(1)=-2$, the graph has a **local minimum at $(1,-2)$**.

### 4. Verify with test points

| Interval | Test point | Derivative value | Confirms |
|---|---|---|---|
| $(-\infty,-1)$ | $x=-2$ | $f'(-2)=3(-3)(-1)=9>0$ | Increasing |
| $(-1,1)$ | $x=0$ | $f'(0)=3(-1)(1)=-3<0$ | Decreasing |
| $(1,\infty)$ | $x=2$ | $f'(2)=3(1)(3)=9>0$ | Increasing |
