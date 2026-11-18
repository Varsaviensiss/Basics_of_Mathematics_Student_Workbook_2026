# Exercise 14. A Small Change in the Right-Hand Side

## Question

Compare the systems

```math
\begin{cases}
x+y=2,\\
2x-y=1,\\
3x=3
\end{cases}
\qquad\text{and}\qquad
\begin{cases}
x+y=2,\\
2x-y=1,\\
3x=3.1.
\end{cases}
```

Check the consistency of each system and explain why a small change in one number can change the type of the system.

## Solution

Both systems have the same first two equations. Adding them eliminates $y$:

```math
(x+y)+(2x-y)=2+1
\quad\Longrightarrow\quad 3x=3
\quad\Longrightarrow\quad x=1.
```

Substituting $x=1$ into $x+y=2$ gives $y=1$. Any solution of either full system must satisfy the first two equations, so $(1,1)$ is the only possible solution.

### First System

At $(1,1)$, the third equation is satisfied because $3(1)=3$. The first system is consistent and has the unique solution $(1,1)$.

### Second System

At $(1,1)$, the third equation fails because $3(1)=3\ne3.1$. The second system is inconsistent and has no solution.

### Geometric Explanation

The first two lines intersect at $(1,1)$ in both systems. In the first system, the third line is $x=1$, which passes through that point. In the second system, the third line moves to $x=31/30$ and misses the intersection. Even this small shift removes the common point of all three lines.
