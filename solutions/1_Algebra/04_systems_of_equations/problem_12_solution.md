# Exercise 12. Homogeneous System

## Question

Solve the system

```math
\begin{cases}
x+2y-z=0,\\
2x+4y-2z=0,\\
x-y+2z=0.
\end{cases}
```

Give all solutions in parametric form and explain why $(0,0,0)$ always satisfies a homogeneous system.

## Solution

Subtract twice the first equation from the second. This gives $0=0$, so the second equation adds no constraint. Subtract the first equation from the third:

```math
(x-y+2z)-(x+2y-z)=0
\quad\Longrightarrow\quad -3y+3z=0
\quad\Longrightarrow\quad z=y.
```

Let $y=t$, where $t$ is any real number. Then $z=t$, and the first equation gives $x+2t-t=0$, so $x=-t$. The full solution set is

```math
\boxed{(x,y,z)=(-t,t,t),\qquad t\in\mathbb{R}}.
```

## Check All Three Equations

```math
\begin{aligned}
(-t)+2t-t&=0,\\
2(-t)+4t-2t&=0,\\
(-t)-t+2t&=0.
\end{aligned}
```

These equalities hold for every real $t$.

## Why Every Homogeneous System Has a Zero Solution

In a homogeneous linear system, the right-hand side of every equation is zero. Setting every unknown to zero makes each term on the left a coefficient multiplied by zero. Their sum is zero, so every equation is satisfied. Here, setting $t=0$ gives the zero solution $(0,0,0)$.
