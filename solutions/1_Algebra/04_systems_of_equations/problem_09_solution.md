# Exercise 9. A System from a Sum Condition

## Question

Find $x$ and $y$ satisfying

```math
\begin{cases}
x+y=10,\\
2x+5y=32.
\end{cases}
```

Solve the system and explain geometrically why the solution is unique.

## Solution

Subtract twice the first equation from the second:

```math
(2x+5y)-2(x+y)=32-2(10)
\quad\Longrightarrow\quad
3y=12
\quad\Longrightarrow\quad
y=4.
```

Substitute $y=4$ into $x+y=10$ to get $x=6$.

## Check Both Equations

```math
6+4=10,\qquad 2(6)+5(4)=12+20=32.
```

## Why the Solution Is Unique

The equations describe the lines $y=10-x$ and $y=\frac{32}{5}-\frac25 x$. Their slopes are $-1$ and $-\frac25$, respectively. Since the slopes are different, the lines intersect exactly once, at $(6,4)$.
