# Problem 14. A Piecewise-Defined Function

## Question

Let

$$
f(x)=
\begin{cases}
x+1, & -1\le x<1,\\
2, & 1\le x\le 3.
\end{cases}
$$

Sketch the graph, decide where to split the integral, compute

$$
\int_{-1}^{3}f(x)\,dx,
$$

and verify the result geometrically.

## Solution

### 1. Sketch the graph and choose where to split

The graph rises along a straight line from $(-1,0)$ to $(1,2)$, then stays at height $2$ until $(3,2)$. The two pieces meet at $(1,2)$, where the formula changes. Split the integral at $x=1$.

```text
                ^ y
                |       B-------------------C   y = 2
                |     / :                   :
                |   /   :                   :
                | /     :                   :
                *       :                   :
              / |       :                   :
            /   |   T   :         R         :
          /     |       :                   :
--------A-------O-------D-------------------E----> x
       -1       0       1                   3

A = (-1, 0), B = (1, 2), C = (3, 2)
T = triangle ABD, R = rectangle DBCE
The dotted vertical lines mark the region boundaries.
```

### 2. Compute the definite integral

By additivity of the definite integral,

$$
\begin{aligned}
\int_{-1}^{3}f(x)\,dx
&=\int_{-1}^{1}(x+1)\,dx+\int_{1}^{3}2\,dx\\
&=\left[\frac{x^2}{2}+x\right]_{-1}^{1}+[2x]_{1}^{3}\\
&=\left(\frac32-\left(-\frac12\right)\right)+(6-2)\\
&=2+4=6.
\end{aligned}
$$

### 3. Verify geometrically

Both regions lie above the $x$-axis. From $x=-1$ to $x=1$, the triangle has base $2$ and height $2$, so its area is $\frac12\cdot2\cdot2=2$. From $x=1$ to $x=3$, the rectangle has width $2$ and height $2$, so its area is $2\cdot2=4$.

The total area is $2+4=6$, which agrees with the integral.
