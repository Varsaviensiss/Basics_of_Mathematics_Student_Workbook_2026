# Problem 8. A Quartic Polynomial

## Question

Analyze the monotonicity, extrema, and concavity of

$$
f(x)=x^4-4x^2.
$$

Find the inflection points and sketch the graph, marking the extrema and inflection points.

## Solution

The function is defined for every real $x$. Since $f(-x)=f(x)$, the graph is symmetric about the $y$-axis.

### 1. Monotonicity and extrema

Differentiate and factor:

$$
f'(x)=4x^3-8x=4x(x^2-2).
$$

The derivative is zero at $x=-\sqrt{2}$, $x=0$, and $x=\sqrt{2}$. The signs of $x$ and $x^2-2$ give the following intervals.

| Interval | Sign of $f'(x)$ | Behavior of $f$ |
|---|---|---|
| $(-\infty,-\sqrt{2})$ | $-$ | Decreasing |
| $(-\sqrt{2},0)$ | $+$ | Increasing |
| $(0,\sqrt{2})$ | $-$ | Decreasing |
| $(\sqrt{2},\infty)$ | $+$ | Increasing |

At $x=\pm\sqrt{2}$, the derivative changes from negative to positive. Since

$$
f(x)=(x^2-2)^2-4\ge -4,
$$

both points $(-\sqrt{2},-4)$ and $(\sqrt{2},-4)$ are absolute minima. At $x=0$, the derivative changes from positive to negative, so $(0,0)$ is a local maximum. There is no absolute maximum because $f(x)\to+\infty$ as $x\to\pm\infty$.

### 2. Concavity and inflection points

The second derivative is

$$
f''(x)=12x^2-8=4(3x^2-2).
$$

Let $a=\sqrt{2/3}$. The second derivative is zero at $x=-a$ and $x=a$.

| Interval | Sign of $f''(x)$ | Concavity |
|---|---|---|
| $(-\infty,-a)$ | $+$ | Concave up |
| $(-a,a)$ | $-$ | Concave down |
| $(a,\infty)$ | $+$ | Concave up |

The concavity changes at both values. Since

$$
f(\pm a)=\left(\frac23\right)^2-4\left(\frac23\right)=-\frac{20}{9},
$$

the inflection points are

$$
\left(-\sqrt{\frac23},-\frac{20}{9}\right)
\quad\text{and}\quad
\left(\sqrt{\frac23},-\frac{20}{9}\right).
$$

### 3. Labeled sketch

Factoring $f(x)=x^2(x-2)(x+2)$ gives the zeros $-2$, $0$, and $2$. The graph crosses the $x$-axis at $-2$ and $2$, and touches it at the local maximum $(0,0)$. Both tails rise.

```text
                          ↑ y
    ↖                     │                     ↗
     ╲                    │                    ╱
──────A───────────────────M───────────────────B──────→ x
       ╲               ╭──╯──╮               ╱
        ╲             ╱   │   ╲             ╱
         ╲          I₁    │    I₂          ╱
          ╲        ╱      │      ╲        ╱
           ╰──L───╯       │       ╰──R───╯

A = (-2, 0) and B = (2, 0): x-axis crossings
M = (0, 0): local maximum
L = (-sqrt(2), -4) and R = (sqrt(2), -4): absolute minima
I₁ = (-sqrt(2/3), -20/9) and I₂ = (sqrt(2/3), -20/9): inflection points
```
