# Exercise 10. A Polynomial Through Three Points

## Question

Find a polynomial $p(x)=ax^2+bx+c$ whose graph passes through $(0,1)$, $(1,3)$, and $(2,9)$. Reduce the problem to a system of equations and verify the result by substituting all three points.

## Solution

Substitute each point into $p(x)=ax^2+bx+c$:

```math
\begin{aligned}
p(0)=1 &\quad\Longrightarrow\quad c=1,\\
p(1)=3 &\quad\Longrightarrow\quad a+b+c=3,\\
p(2)=9 &\quad\Longrightarrow\quad 4a+2b+c=9.
\end{aligned}
```

Substituting $c=1$ gives $a+b=2$ and $4a+2b=8$. Subtract twice the first equation from the second:

```math
(4a+2b)-2(a+b)=8-2(2)
\quad\Longrightarrow\quad 2a=4
\quad\Longrightarrow\quad a=2.
```

Then $b=2-a=0$. Therefore,

```math
\boxed{p(x)=2x^2+1}.
```

## Check All Three Points

```math
p(0)=2(0)^2+1=1,\qquad
p(1)=2(1)^2+1=3,\qquad
p(2)=2(2)^2+1=9.
```

The polynomial passes through all three required points.
