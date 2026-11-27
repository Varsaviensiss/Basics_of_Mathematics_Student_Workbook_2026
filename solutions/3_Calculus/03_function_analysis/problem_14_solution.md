# Problem 14. Reconstructing Information from the Derivative

## Question

It is known that

$$
f'(x)=(x-1)(x+2).
$$

Determine the monotonicity and the locations of the extrema, and sketch a possible qualitative shape of the function. Then, for

$$
g(x)=\frac{x^3}{3}+\frac{x^2}{2}-2x,
$$

verify that $g'(x)=(x-1)(x+2)$, and compare the specific graph with the earlier qualitative sketch.

## Solution

### 1. Monotonicity and extrema of $f$

The derivative vanishes when $(x-1)(x+2)=0$, so the critical numbers are $x=-2$ and $x=1$. The signs of the two factors determine the sign of the derivative.

| Interval | Sign of $x-1$ | Sign of $x+2$ | Sign of $f'(x)$ | Behavior |
|---|---|---|---|---|
| $(-\infty,-2)$ | $-$ | $-$ | $+$ | Increasing |
| $(-2,1)$ | $-$ | $+$ | $-$ | Decreasing |
| $(1,\infty)$ | $+$ | $+$ | $+$ | Increasing |

At $x=-2$, the derivative changes from positive to negative, giving a local maximum. At $x=1$, it changes from negative to positive, giving a local minimum. The derivative determines the locations of the extrema, while their heights depend on the vertical position of the graph.

### 2. Qualitative sketch of $f$

```text
                local maximum
                     ●
                 ╭───┴───╮                             ↗
              ╭──╯       ╰──╮                        ╭─╯
           ╭──╯             ╰──╮                  ╭──╯
         ↙                      ╰───╮        ╭────╯
                                    ╰───●────╯
                                    local minimum

                    −2                  1           x values
```

The labels give the horizontal positions of the turning points. Their heights are unspecified.

### 3. Verify the derivative and find the extrema of $g$

Differentiating term by term gives

$$
g'(x)=x^2+x-2=(x-1)(x+2).
$$

Thus $g$ has the same increasing and decreasing intervals as $f$. Evaluating $g$ at the critical numbers gives

$$
g(-2)=-\frac83+2+4=\frac{10}{3},
\qquad
g(1)=\frac13+\frac12-2=-\frac76.
$$

The local maximum is $M=(-2,10/3)$ and the local minimum is $m=(1,-7/6)$. Also, $g(0)=0$, so the graph passes through the origin.

### 4. Sketch of $g$

```text
                                ↑ y
                                │                         ↗
             ╭──M──╮            │                       ╭─╯
          ╭──╯     ╰──╮         │                     ╭─╯
        ╭─╯           ╰──╮      │                   ╭─╯
───────╱─────────────────╰──────O──────────────────╱──────→ x
      ╱                         │╰──╮           ╭─╯
    ↙                           │   ╰────m──────╯

M = (-2, 10/3), local maximum
O = (0, 0), origin
m = (1, -7/6), local minimum
```

### 5. Compare the sketches

Because $f'(x)=g'(x)$ for every real $x$, the derivative of $f-g$ is zero everywhere. Therefore, $f(x)=g(x)+C$ for some constant $C$. The two graphs have the same shape and turn at the same $x$-values. The constant $C$ shifts the graph vertically, moving the extremum heights to $10/3+C$ and $-7/6+C$.
