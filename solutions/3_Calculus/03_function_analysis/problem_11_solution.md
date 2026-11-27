# Problem 11. A Parameter and the Number of Extrema

## Question

Consider the family of functions

$$
f_a(x)=x^3-3ax,\qquad a\in\mathbb{R}.
$$

Determine how the number and type of local extrema depend on $a$. Analyze the cases $a>0$, $a=0$, and $a<0$ separately.

## Solution

Differentiating gives

$$
f_a'(x)=3x^2-3a=3(x^2-a).
$$

The derivative exists for every real $x$. The critical numbers therefore satisfy $x^2=a$.

### 1. Case $a>0$

There are two critical numbers, $x=-\sqrt a$ and $x=\sqrt a$. The derivative is positive when $|x|>\sqrt a$ and negative when $|x|<\sqrt a$.

| Interval | Sign of $f_a'(x)$ | Behavior of $f_a$ |
|---|---|---|
| $(-\infty,-\sqrt a)$ | $+$ | Increasing |
| $(-\sqrt a,\sqrt a)$ | $-$ | Decreasing |
| $(\sqrt a,\infty)$ | $+$ | Increasing |

At $x=-\sqrt a$, the derivative changes from positive to negative. At $x=\sqrt a$, it changes from negative to positive. At either critical number, $x^2=a$, so $f_a(x)=x(x^2-3a)=-2ax$. Therefore:

- The local maximum is $\left(-\sqrt a,\,2a\sqrt a\right)$.
- The local minimum is $\left(\sqrt a,\,-2a\sqrt a\right)$.

### 2. Case $a=0$

Here $f_0(x)=x^3$ and $f_0'(x)=3x^2$. The derivative is zero at $x=0$ and positive on both sides, so the function increases through $x=0$ and has no local extremum there.

The second derivative is $f_0''(x)=6x$. It changes from negative to positive at $x=0$, so the graph changes concavity there. Since $f_0'(0)=0$ and $f_0(0)=0$, the origin is a **stationary inflection point**.

### 3. Case $a<0$

Since $x^2-a=x^2+|a|>0$ for all real $x$, the derivative is strictly positive everywhere. Thus $f_a$ is strictly increasing on $\mathbb{R}$ and has no critical points or local extrema.
