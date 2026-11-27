# Problem 1. A Cubic Polynomial

## Question

Analyze the monotonicity and extrema of

$$
f(x)=x^3-3x^2+2.
$$

Sketch the graph based on the results and mark the critical points.

## Solution

### Derivative and monotonicity

Differentiate and factor:

$$
f'(x)=3x^2-6x=3x(x-2).
$$

The derivative exists for all real $x$. It is zero at $x=0$ and $x=2$, so these values divide the real line into three intervals. The signs of the two factors determine whether the function increases or decreases.

| Interval | Sign of $x$ | Sign of $x-2$ | Sign of $f'(x)$ | Behavior of $f$ |
|---|---|---|---|---|
| $(-\infty,0)$ | $-$ | $-$ | $+$ | Increasing |
| $(0,2)$ | $+$ | $-$ | $-$ | Decreasing |
| $(2,\infty)$ | $+$ | $+$ | $+$ | Increasing |

### Local extrema

At $x=0$, the derivative changes from positive to negative. Since $f(0)=2$, the graph has a **local maximum at $M=(0,2)$**.

At $x=2$, the derivative changes from negative to positive. Since $f(2)=8-12+2=-2$, the graph has a **local minimum at $m=(2,-2)$**.

### Labeled sketch

To locate the $x$-intercepts, factor the original polynomial:

$$
f(x)=(x-1)(x^2-2x-2)=(x-1)\bigl((x-1)^2-3\bigr).
$$

The graph crosses the $x$-axis at $x=1-\sqrt{3}$, $x=1$, and $x=1+\sqrt{3}$. The positive leading term $x^3$ sends the left tail downward and the right tail upward.

```text
                ↑ y
                │                              ↗
                │                             ╱
           ╭────M────╮                       ╱
         ╭─╯    │    ╰─╮                    ╱
        ╱       │      ╰─╮                 ╱
───────A────────┼─────────B───────────────C────→ x
      ╱         │          ╰─╮          ╭─╯
     ╱          │            ╰─╮      ╭─╯
    ╱           │              ╰────m─╯
   ↙            │

A = (1 - sqrt(3), 0)
B = (1, 0)
C = (1 + sqrt(3), 0)
M = (0, 2), local maximum and y-intercept
m = (2, -2), local minimum
```
