# Exercise 15. Classifying Three Systems

## Question

For each system, perform only as much elimination as needed to determine whether it has one solution, infinitely many solutions, or no solution. Justify each classification.

```math
\text{System 1}\quad
\begin{cases}
x+y=2,\\
x-y=0
\end{cases}
\qquad
\text{System 2}\quad
\begin{cases}
x+y=2,\\
2x+2y=4
\end{cases}
\qquad
\text{System 3}\quad
\begin{cases}
x+y=2,\\
2x+2y=5.
\end{cases}
```

## Solution

### System 1: One Solution

Subtract the first equation from the second:

```math
(x-y)-(x+y)=0-2
\quad\Longrightarrow\quad -2y=-2.
```

This row fixes $y=1$. Substituting into $x+y=2$ fixes $x=1$. Both variables are determined, so the unique solution is $(1,1)$.

### System 2: Infinitely Many Solutions

Apply $R_2\leftarrow R_2-2R_1$:

```math
(2x+2y)-2(x+y)=4-2(2)
\quad\Longrightarrow\quad 0=0.
```

This row is true for every $x$ and $y$, so it adds no constraint. The remaining equation $x+y=2$ describes a line. Its solutions are $(2-t,t)$ for every real $t$, so there are infinitely many solutions.

### System 3: No Solution

Apply the same operation, $R_2\leftarrow R_2-2R_1$:

```math
(2x+2y)-2(x+y)=5-2(2)
\quad\Longrightarrow\quad 0=1.
```

This row is a contradiction. No pair $(x,y)$ can satisfy both equations, so the system has no solution.
