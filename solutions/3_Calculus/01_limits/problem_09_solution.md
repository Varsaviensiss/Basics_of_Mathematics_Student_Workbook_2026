# Exercise 9. One-Sided Limits and an Asymptote

## Question

For $f(x)=\frac{1}{x-2}$, find the left-hand and right-hand limits as $x$ approaches $2$. Determine whether the two-sided limit exists, identify the vertical asymptote, and sketch both branches of the graph, marking the line $x=2$.

## Solution

### Left-Hand Limit

As $x\to2^-$, the denominator $x-2$ approaches zero through negative values. Its reciprocal decreases without bound:

$$
\lim_{x\to2^-}\frac{1}{x-2}=-\infty.
$$

### Right-Hand Limit

As $x\to2^+$, the denominator $x-2$ approaches zero through positive values. Its reciprocal increases without bound:

$$
\lim_{x\to2^+}\frac{1}{x-2}=+\infty.
$$

### Two-Sided Limit and Vertical Asymptote

The one-sided limits go to opposite infinities, so the two-sided limit does not exist. Since the function is unbounded as $x$ approaches $2$ from either side, the line $x=2$ is a vertical asymptote.

### Graph

```text
                     x = 2
                       : ↑  +inf
                       : *
                       :  *
                       :     * (3, 1)
                       :          * * * ...
-----------------------:--------------------> x (y = 0)
 ... * * *             :
           * (1, -1)   :
                *      :
                   *   :
                     * :
               -inf  ↓ :
```

The left branch lies below the horizontal axis and falls without bound near $x=2$. The right branch lies above the horizontal axis and rises without bound near $x=2$. Far from the asymptote, both branches approach $y=0$.
