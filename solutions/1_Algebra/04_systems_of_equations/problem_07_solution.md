# Exercise 7. Choosing a Method Deliberately

## Question

For each situation, choose the method that best uses the structure of the problem and justify your choice:

1. One system with a triangular coefficient matrix:

   ```math
   \begin{cases}
   2x-y=3,\\
   4y=8.
   \end{cases}
   ```

2. Three systems $Ax=b_i$ with the same invertible matrix $A$, when $A^{-1}$ is already known.
3. One $3\times3$ system for which the inverse is not given and the goal is only to find one solution vector.

Solve case 1 completely. For cases 2 and 3, describe the plan and identify which computation can be reused or is unnecessary. Base your choices on the structure of the coefficient matrix and the number of right-hand sides.

## Solution

### 1. Triangular System: Back-Substitution

The second equation contains only $y$, so $4y=8$ gives $y=2$. Substitute this into the first equation:

```math
2x-2=3 \quad\Longrightarrow\quad x=\frac52.
```

Thus, $(x,y)=(5/2,2)$. Checking both equations gives $2(5/2)-2=3$ and $4(2)=8$.

### 2. Three Right-Hand Sides: Reuse the Known Inverse

Use $x_i=A^{-1}b_i$ for $i=1,2,3$. The coefficient matrix is the same in all three systems, so the already computed inverse can be reused. Only the right-hand-side vector changes in each matrix-vector multiplication.

### 3. One $3\times3$ System: Gaussian Elimination

Row-reduce the augmented matrix $[A\mid b]$ to echelon form. Check for a row of the form $[0\;0\;0\mid c]$ with $c\ne0$, which would make the system inconsistent. If the system is consistent and all three variable columns have pivots, back-substitution gives the unique solution. If a variable column has no pivot, choose a value for each free variable and back-substitute to obtain one solution.

Elimination works directly with the one right-hand side we need. Forming the inverse would require solving for three identity columns, which is unnecessary here.
