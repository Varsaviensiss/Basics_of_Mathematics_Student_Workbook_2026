# Problem 10. Complete Function Analysis

## Question

Perform a complete analysis of

$$
f(x)=\frac{x}{x^2+1}.
$$

Include the domain, symmetry, zeros, limits, monotonicity, extrema, and convexity. Finally, produce a sketch based only on this information.

## Solution

### 1. Domain, symmetry, and zeros

Since $x^2+1>0$ for every real $x$, the domain is $\mathbb{R}$. Also,

$$
f(-x)=\frac{-x}{x^2+1}=-f(x),
$$

so $f$ is odd and its graph is symmetric about the origin. The numerator is zero only at $x=0$, so $(0,0)$ is the only intercept.

### 2. Limits and asymptotes

For $x\ne0$, dividing the numerator and denominator by $x^2$ gives

$$
f(x)=\frac{1/x}{1+1/x^2}.
$$

Thus $f(x)\to0$ as $x\to-\infty$ and as $x\to+\infty$. The graph approaches the horizontal asymptote $y=0$ from below on the left and from above on the right because $f(x)$ has the same sign as $x$. There are no vertical asymptotes because the denominator never vanishes.

### 3. Monotonicity and extrema

The quotient rule gives

$$
f'(x)=\frac{(x^2+1)-2x^2}{(x^2+1)^2}
=\frac{1-x^2}{(x^2+1)^2}.
$$

The denominator is positive, so the sign of the derivative is determined by $1-x^2$. The only critical numbers are $x=-1$ and $x=1$.

| Interval | Sign of $f'(x)$ | Behavior |
|---|---|---|
| $(-\infty,-1)$ | $-$ | Decreasing |
| $(-1,1)$ | $+$ | Increasing |
| $(1,\infty)$ | $-$ | Decreasing |

At $x=-1$, the derivative changes from negative to positive, giving a minimum at $m=(-1,-1/2)$. At $x=1$, it changes from positive to negative, giving a maximum at $M=(1,1/2)$. Both extrema are absolute because the middle interval joins these two values monotonically, while the outer intervals approach $0$.

### 4. Concavity and inflection points

Differentiating again and simplifying gives

$$
f''(x)
=\frac{-2x(x^2+1)-4x(1-x^2)}{(x^2+1)^3}
=\frac{2x(x^2-3)}{(x^2+1)^3}.
$$

The denominator is positive. The numerator changes sign at $x=-\sqrt{3}$, $x=0$, and $x=\sqrt{3}$.

| Interval | Sign of $f''(x)$ | Concavity |
|---|---|---|
| $(-\infty,-\sqrt{3})$ | $-$ | Concave down |
| $(-\sqrt{3},0)$ | $+$ | Concave up |
| $(0,\sqrt{3})$ | $-$ | Concave down |
| $(\sqrt{3},\infty)$ | $+$ | Concave up |

Concavity changes at all three values, so the inflection points are

$$
I_-=\left(-\sqrt{3},-\frac{\sqrt{3}}4\right),
\qquad
O=(0,0),
\qquad
I_+=\left(\sqrt{3},\frac{\sqrt{3}}4\right).
$$

### 5. Labeled sketch

```text
                               y
                               ↑
                               │       ╭──M──╮
                               │     ╭─╯     ╰──I+──╮
                               │   ╭─╯              ╰──────→
                               │ ╭─╯
───────────────────────────────O────────────────────────────→ x
                             ╭─╯
←──────╮                   ╭─╯ │
       ╰──I-──╮          ╭─╯   │
              ╰────m─────╯     │

m = (-1, -1/2)   absolute minimum
M = (1, 1/2)     absolute maximum
I- = (-sqrt(3), -sqrt(3)/4) and I+ = (sqrt(3), sqrt(3)/4)
O = (0, 0)      intercept and inflection point
The x-axis, y = 0, is the horizontal asymptote.
```
