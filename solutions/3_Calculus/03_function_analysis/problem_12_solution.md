# Problem 12. The Graph of an Absolute Value

## Question

Sketch the graph of $y=x^2-4$ and use it to sketch

$$
f(x)=|x^2-4|.
$$

Explain how the absolute value changes the graph and why corners occur at $x=-2$ and $x=2$.

## Solution

### 1. Sketch the original parabola and reflect its negative arc

The graph of $g(x)=x^2-4$ is an upward-opening parabola with vertex $(0,-4)$ and zeros at $x=-2$ and $x=2$. It lies below the $x$-axis for $-2<x<2$ and on or above the axis for $|x|\ge 2$.

The absolute value reflects the negative arc across the $x$-axis. The outer branches and the two zeros stay in place. Therefore,

$$
f(x)=
\begin{cases}
x^2-4, & |x|\ge2,\\
4-x^2, & |x|<2.
\end{cases}
$$

The reflected middle arc opens downward and has its highest point at $(0,4)$.

```text
                             ↑ y
       ↖                     │                     ↗
        ╲                ╭───T───╮                ╱
         ╲             ╭─╯   │   ╰─╮             ╱
          ╲          ╭─╯     │     ╰─╮          ╱
           ╲       ╭─╯       │       ╰─╮       ╱
────────────L──────╯─────────┼─────────╰──────R────────────→ x
             ··              │              ··
               ···           │           ···
                  ···        │        ···
                     ········V········

L = (-2, 0) and R = (2, 0): corners
T = (0, 4): top of the reflected arc
V = (0, -4): vertex of the original parabola
Solid curve: y = |x^2 - 4|
Dotted arc plus the shared outer branches: y = x^2 - 4
```

### 2. Explain the corners

On the outer branches, $f'(x)=2x$. On the middle arc, $f'(x)=-2x$. These formulas give the one-sided slopes:

| Point | Left-hand slope | Right-hand slope |
|---|---|---|
| $x=-2$ | $2(-2)=-4$ | $-2(-2)=4$ |
| $x=2$ | $-2(2)=-4$ | $2(2)=4$ |

The two pieces meet continuously at each zero, but the one-sided slopes differ at both points. Therefore, $f$ is not differentiable at $x=-2$ or $x=2$, and the graph has a corner at each point.
