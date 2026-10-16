Exercise 3: When Can Matrices Be Multiplied?
1. Problem Statement

The matrix sizes are A (2 × 3), B (3 × 4), C (4 × 2), and D (2 × 2).

Determine whether the products AB, BA, BC, CB, AC, CA, AD, and DA are defined. If defined, state the size of each result.

2. Theoretical Background and Concepts

Matrix multiplication is possible when the number of columns in the first matrix equals the number of rows in the second matrix. If the sizes are m × n and n × p, the product has size m × p.

3. Detailed Step-by-Step Solution
AB: (2 × 3)(3 × 4). The inner dimensions match. Defined; result size: 2 × 4.
BA: (3 × 4)(2 × 3). The inner dimensions 4 and 2 do not match. Not defined.
BC: (3 × 4)(4 × 2). The inner dimensions match. Defined; result size: 3 × 2.
CB: (4 × 2)(3 × 4). The inner dimensions 2 and 3 do not match. Not defined.
AC: (2 × 3)(4 × 2). The inner dimensions 3 and 4 do not match. Not defined.
CA: (4 × 2)(2 × 3). The inner dimensions match. Defined; result size: 4 × 3.
AD: (2 × 3)(2 × 2). The inner dimensions 3 and 2 do not match. Not defined.
DA: (2 × 2)(2 × 3). The inner dimensions match. Defined; result size: 2 × 3.
4. Verification and Consistency Checks

Every defined product has matching inner dimensions. Its result size is determined by the outer dimensions. All products with mismatched inner dimensions are correctly identified as undefined.

Final Answer

AB: 2 × 4
BA: Not defined
BC: 3 × 2
CB: Not defined
AC: Not defined
CA: 4 × 3
AD: Not defined
DA: 2 × 3
