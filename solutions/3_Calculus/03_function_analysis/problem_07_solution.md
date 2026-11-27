# Problem 7. A Trigonometric Function on a Closed Interval

## Question

Analyze the monotonicity and extrema of

$$
f(x)=\sin x+\cos x,\qquad x\in[0,2\pi].
$$

Compare the values at the critical points and endpoints to find the absolute maximum and minimum.

## Solution

### 1. Find the critical points

Differentiating and rewriting the result gives

$$
f'(x)=\cos x-\sin x
=\sqrt{2}\cos\left(x+\frac{\pi}{4}\right).
$$

The derivative is zero when $x+\frac{\pi}{4}=\frac{\pi}{2}+k\pi$, so the critical points in the interval occur at $x=\frac{\pi}{4}$ and $x=\frac{5\pi}{4}$.

### 2. Determine monotonicity

The sign of $f'(x)$ follows from the sign of $\cos(x+\frac{\pi}{4})$.

| Interval | Sign of $f'(x)$ | Behavior of $f$ |
|---|---|---|
| $(0,\frac{\pi}{4})$ | $+$ | Increasing |
| $(\frac{\pi}{4},\frac{5\pi}{4})$ | $-$ | Decreasing |
| $(\frac{5\pi}{4},2\pi)$ | $+$ | Increasing |

Thus $x=\frac{\pi}{4}$ is a local maximum and $x=\frac{5\pi}{4}$ is a local minimum.

### 3. Compare the critical points and endpoints

The function is continuous on the closed interval $[0,2\pi]$. To find the absolute extrema, evaluate it at both critical points and both endpoints.

$$
\begin{aligned}
f(0)&=1,\\
f\left(\frac{\pi}{4}\right)&=\frac{\sqrt{2}}{2}+\frac{\sqrt{2}}{2}=\sqrt{2},\\
f\left(\frac{5\pi}{4}\right)&=-\frac{\sqrt{2}}{2}-\frac{\sqrt{2}}{2}=-\sqrt{2},\\
f(2\pi)&=1.
\end{aligned}
$$

Since $-\sqrt{2}<1<\sqrt{2}$, the **absolute maximum** is $\sqrt{2}$ at $x=\frac{\pi}{4}$, and the **absolute minimum** is $-\sqrt{2}$ at $x=\frac{5\pi}{4}$.
