# Problem 3. A Rational Function

## Question

Analyze the domain, zeros, asymptotes, and monotonicity of

$$
f(x)=\frac{x+1}{x-2}.
$$

Finally, sketch a graph consistent with all the information obtained.

## Solution

### Domain and zero

The denominator is zero at $x=2$, so the domain is $\mathbb{R}\setminus\{2\}$.

The numerator vanishes at $x=-1$. Since the denominator is nonzero there, the only zero is $x=-1$, and the graph crosses the $x$-axis at $(-1,0)$.

### Asymptotes

Rewrite the function as

$$
f(x)=1+\frac{3}{x-2}.
$$

As $x$ approaches $2$ from the left, the fraction tends to $-\infty$. As $x$ approaches $2$ from the right, it tends to $+\infty$. Thus $x=2$ is the **vertical asymptote**.

As $x\to\pm\infty$, the fraction tends to zero, so $y=1$ is the **horizontal asymptote**. The left branch lies below $y=1$ because $x-2<0$. The right branch lies above $y=1$ because $x-2>0$.

### Monotonicity

Differentiating the rewritten form gives

$$
f'(x)=-\frac{3}{(x-2)^2}<0 \qquad (x\ne 2).
$$

Therefore, the function is strictly decreasing on each interval of its domain, $(-\infty,2)$ and $(2,\infty)$.

### Labeled sketch

```text
                    y              x = 2
                    ↑                :  ↖
                    │                :   ╲
                    │                :    ╲
                    │                :     ╰──╮
                    │                :        ╰──────→
····················│················:················  y = 1
←──────╮            │                :
       ╰─────╮      │                :
─────────────A──────┼────────────────:───────────────→ x
              ╲     │                :
               ╰────●──╮             :
                    │  ╰──╮          :
                    │     ╰──╮       :
                    │        ╰──╮    :
                    │           ╲    :
                    │            ↘   :

A = (-1, 0)
● = (0, -1/2), the y-intercept
Dotted lines mark the asymptotes x = 2 and y = 1.
```
