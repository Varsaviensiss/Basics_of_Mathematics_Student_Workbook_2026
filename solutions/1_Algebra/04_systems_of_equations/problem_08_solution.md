# Exercise 8. Two Systems with the Same Coefficient Matrix

## Question

Solve both systems by elimination:

```math
\begin{cases}
2x+y=5,\\
x-y=1,
\end{cases}
\qquad
\begin{cases}
2x+y=1,\\
x-y=4.
\end{cases}
```

Compare the successive elimination steps. Which part of the calculation is the same in both cases, and why?

## Solution

### 1. First System

Subtract twice the second equation from the first to eliminate $x$:

```math
(2x+y)-2(x-y)=5-2(1)
\quad\Longrightarrow\quad 3y=3.
```

Thus $y=1$. Substituting into $x-y=1$ gives $x=2$. The solution is $(x,y)=(2,1)$.

### 2. Second System

Apply the same elimination step:

```math
(2x+y)-2(x-y)=1-2(4)
\quad\Longrightarrow\quad 3y=-7.
```

Thus $y=-7/3$. Substituting into $x-y=4$ gives $x=4-7/3=5/3$. The solution is $(x,y)=(5/3,-7/3)$.

### 3. Compare the Steps

Both systems have the same coefficient matrix, so the row operation $R_1\leftarrow R_1-2R_2$ changes the coefficient entries of the first row from $(2,1)$ to $(0,3)$ in both cases. The right-hand sides differ, so the same operation gives $5-2(1)=3$ in the first system and $1-2(4)=-7$ in the second.
