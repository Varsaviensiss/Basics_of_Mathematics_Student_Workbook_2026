# Exercise 13. Does Every Equation Add New Information?

## Question

Consider the system

```math
\begin{cases}
x_1+x_2=10,\\
x_2+x_3=8,\\
x_1-x_3=2.
\end{cases}
```

Solve the system and check whether all three equations are independently necessary to describe the solution set. If one follows from the others, show this by calculation.

## Solution

Subtract the second equation from the first:

```math
(x_1+x_2)-(x_2+x_3)=10-8
\quad\Longrightarrow\quad x_1-x_3=2.
```

This is exactly the third equation. It follows from the first two, so it adds no new constraint.

The first two equations are independent: one determines $x_1$ and the other determines $x_3$ once $x_2$ is chosen. Thus, two independent constraints on three variables leave one free variable. Let $x_2=t$, where $t$ is any real number. Then $x_1=10-t$ and $x_3=8-t$, so the full solution set is

```math
\boxed{(x_1,x_2,x_3)=(10-t,t,8-t),\qquad t\in\mathbb R}.
```

## Check All Three Equations

```math
\begin{aligned}
x_1+x_2 &=(10-t)+t=10,\\
x_2+x_3 &=t+(8-t)=8,\\
x_1-x_3 &=(10-t)-(8-t)=2.
\end{aligned}
```

All three equations hold for every real $t$, so there are infinitely many solutions.
