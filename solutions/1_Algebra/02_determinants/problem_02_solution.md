### Exercise 2. Determinant of a 3×3 Matrix

Given:

A = | 1   2  -1 |
    | 0   3   4 |
    | 2   1   5 |

**Step 1: Apply Sarrus' Rule**

Repeat the first two columns:

1   2  -1 | 1   2
0   3   4 | 0   3
2   1   5 | 2   1

Sum of the downward diagonal products:

1×3×5 + 2×4×2 + (-1)×0×1
= 15 + 16 + 0
= 31

Sum of the upward diagonal products:

(-1)×3×2 + 2×0×5 + 1×4×1
= -6 + 0 + 4
= -2

Therefore,

det(A) = 31 - (-2) = 33

**Step 2: Check Using a Determinant Property**

Adding a multiple of one row to another row does not change the determinant.

Apply R3 → R3 - 2R1:

A = | 1   2  -1 |
    | 0   3   4 |
    | 0  -3   7 |

Expanding along the first column:

det(A) = 1 × (3×7 - 4×(-3))
       = 21 + 12
       = 33

The check confirms the result.

**Final Answer: det(A) = 33**
