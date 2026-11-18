# Exercise 11. A Parameter in a System of Three Equations

## Question

Analyze the number of solutions depending on $t$:

```math
\begin{cases}
x+y+z=1,\\
x+ty+z=2,\\
x+y+tz=3.
\end{cases}
```

Use elimination and separately analyze any parameter value for which a standard calculation step ceases to be valid.

## Solution

Subtract the first equation from the second and from the third:

```math
\begin{aligned}
(x+ty+z)-(x+y+z)&=2-1
&\quad\Longrightarrow\quad (t-1)y&=1,\\
(x+y+tz)-(x+y+z)&=3-1
&\quad\Longrightarrow\quad (t-1)z&=2.
\end{aligned}
```

### Case 1: $t=1$

The first reduced equation becomes $0=1$, a contradiction. Therefore, the system has **no solution** at $t=1$.

### Case 2: $t\ne1$

Since $t-1$ is nonzero, we can divide both reduced equations by it:

```math
y=\frac{1}{t-1},
\qquad
z=\frac{2}{t-1}.
```

The first equation then gives

```math
x=1-y-z=1-\frac{3}{t-1}.
```

Each variable is determined, so this solution is unique.

### Check All Three Equations

```math
\begin{aligned}
x+y+z &=1-\frac{3}{t-1}+\frac{1}{t-1}+\frac{2}{t-1}=1,\\
x+ty+z &=(x+y+z)+(t-1)y=1+1=2,\\
x+y+tz &=(x+y+z)+(t-1)z=1+2=3.
\end{aligned}
```

Thus, the system has **no solution when $t=1$** and **exactly one solution when $t\ne1$**.
