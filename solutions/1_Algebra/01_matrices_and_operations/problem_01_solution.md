Exercise 1: Matrix Size and Entries
1. Original Problem
Given the matrices: $$A = \begin{pmatrix} 2 & -1 & 3 \ 0 & 4 & 5 \end{pmatrix}, \qquad B = \begin{pmatrix} 1 & 0 \ -2 & 3 \ 4 & 1 \end{pmatrix}$$

State the sizes of matrices 
A
 and 
B
.
Read off the entries 
a
12
, 
a
23
, 
b
21
, and 
b
32
.
Write the second row of 
A
 and the first column of 
B
 as vectors.
2. What We Are Trying to Find
In this exercise, we want to:

Determine the outer dimensions (number of horizontal rows and vertical columns) of matrices 
A
 and 
B
.
Locate four specific numbers inside the matrices using double-index coordinates 
(
i
,
j
)
.
Extract a specific horizontal row from matrix 
A
 and a specific vertical column from matrix 
B
 and write them down as standalone vectors.
3. Key Concepts and Theorems
Matrix Size (
m
×
n
): A matrix with 
m
 horizontal rows and 
n
 vertical columns has size 
m
×
n
 (read "$m$ by 
n
"). The standard convention is always rows first, then columns (memory aid: Row then Column, like "RC car").
Double-Index Notation (
a
i
j
): In any entry symbol 
a
i
j
, the first subscript 
i
 denotes the row number (counting top to bottom), and the second subscript 
j
 denotes the column number (counting left to right).
Row and Column Vectors:
A row vector has size 
1
×
n
 and is written horizontally: $\begin{pmatrix} r_1 & r_2 & \dots & r_n \end{pmatrix}$.
A column vector has size 
m
×
1
 and is written vertically: $\begin{pmatrix} c_1 \ c_2 \ \vdots \ c_m \end{pmatrix}$.
4. Detailed Step-by-Step Solution
Step 1: Determine the Sizes of 
A
 and 
B
Look at matrix 
A
: $$A = \begin{pmatrix} 2 & -1 & 3 \ 0 & 4 & 5 \end{pmatrix}$$

Count rows (horizontal lines):
Row 1: 
(
2
,
−
1
,
3
)
Row 2: 
(
0
,
4
,
5
)
Total rows 
m
=
2
.
Count columns (vertical lines):
Column 1: $\begin{pmatrix} 2 \ 0 \end{pmatrix}$, Column 2: $\begin{pmatrix} -1 \ 4 \end{pmatrix}$, Column 3: $\begin{pmatrix} 3 \ 5 \end{pmatrix}$
Total columns 
n
=
3
.
Therefore, the size of matrix 
A
 is 
2
×
3
.
Look at matrix 
B
: $$B = \begin{pmatrix} 1 & 0 \ -2 & 3 \ 4 & 1 \end{pmatrix}$$

Count rows (horizontal lines):
Row 1: 
(
1
,
0
)
Row 2: 
(
−
2
,
3
)
Row 3: 
(
4
,
1
)
Total rows 
m
=
3
.
Count columns (vertical lines):
Column 1: $\begin{pmatrix} 1 \ -2 \ 4 \end{pmatrix}$, Column 2: $\begin{pmatrix} 0 \ 3 \ 1 \end{pmatrix}$
Total columns 
n
=
2
.
Therefore, the size of matrix 
B
 is 
3
×
2
.
Step 2: Read Off the Requested Entries
Entry 
a
12
: Go to matrix 
A
, locate row 1, and take the element in column 2. 
a
12
=
−
1
Entry 
a
23
: Go to matrix 
A
, locate row 2, and take the element in column 3. 
a
23
=
5
Entry 
b
21
: Go to matrix 
B
, locate row 2, and take the element in column 1. 
b
21
=
−
2
Entry 
b
32
: Go to matrix 
B
, locate row 3, and take the element in column 2. 
b
32
=
1
Step 3: Write Row 2 of 
A
 and Column 1 of 
B
 as Vectors
The second row of 
A
 contains the entries 
0
,
4
,
5
. Written horizontally as a row vector: $$\mathbf{r}_2 = \begin{pmatrix} 0 & 4 & 5 \end{pmatrix}$$
The first column of 
B
 contains the entries 
1
,
−
2
,
4
. Written vertically as a column vector: $$\mathbf{c}_1 = \begin{pmatrix} 1 \ -2 \ 4 \end{pmatrix}$$
5. Why Each Step Is Valid
Counting Dimensions: Matrix size is defined solely by counting complete horizontal lines and complete vertical lines; the definition does not depend on the numerical values of the elements.
Reading Indices: The standard index rule universally maps 
(
i
,
j
)
 to 
(
row 
i
,
column 
j
)
. This guarantees that every entry has a unique address.
Forming Vectors: An isolated row of an 
m
×
n
 matrix is an element of 
R
1
×
n
 (a row vector), while an isolated column is an element of 
R
m
×
1
 (a column vector).
6. Final Answer in Words
Matrix 
A
 has 
2
 rows and 
3
 columns, so its size is 
2
×
3
. Matrix 
B
 has 
3
 rows and 
2
 columns, so its size is 
3
×
2
. The specific entries are 
a
12
=
−
1
, 
a
23
=
5
, 
b
21
=
−
2
, and 
b
32
=
1
. The second row of matrix 
A
 expressed as a vector is $\begin{pmatrix} 0 & 4 & 5 \end{pmatrix}$, and the first column of matrix 
B
 expressed as a vector is $\begin{pmatrix} 1 \ -2 \ 4 \end{pmatrix}$.

7. Quick Verification
Total Element Count: A 
2
×
3
 matrix must have 
2
⋅
3
=
6
 elements. Listing the entries of 
A
 gives 
2
,
−
1
,
3
,
0
,
4
,
5
, which is exactly 
6
 numbers. Similarly, 
B
 has 
3
⋅
2
=
6
 elements: 
1
,
0
,
−
2
,
3
,
4
,
1
.
Index Bounds: In matrix 
A
 (
2
×
3
), valid row indices are 
1
,
2
 and valid column indices are 
1
,
2
,
3
. For 
a
12
 and 
a
23
, both index pairs lie within these bounds. In matrix 
B
 (
3
×
2
), valid row indices are 
1
,
2
,
3
 and column indices are 
1
,
2
. Both 
b
21
 and 
b
32
 fall strictly within bounds.
Vector Lengths: The row vector 
r
2
 has 
3
 components, matching the number of columns in 
A
. The column vector 
c
1
 has 
3
 components, matching the number of rows in 
B
.
8. Common Mistakes to Avoid
Swapping Rows and Columns in Size: Writing 
3
×
2
 for 
A
 instead of 
2
×
3
. Remember: horizontal count always precedes vertical count.
Inverting Subscripts: Reading 
a
12
 as row 2, column 1 (which would be 
0
) instead of row 1, column 2 (which is 
−
1
).
Confusing Row Vectors with Column Vectors: Writing the column of 
B
 horizontally without a transpose sign, losing the distinction between rows and columns.
9. Classroom Presentation (3-Sentence Summary)
"To determine the size of a matrix, we always count the rows first and then the columns, making matrix 
A
 a 
2
×
3
 matrix and matrix 
B
 a 
3
×
2
 matrix. When reading matrix entries like 
a
12
 or 
b
21
, the first subscript tells us the row while the second tells us the column. Finally, isolating a horizontal line gives us a row vector, while isolating a vertical line gives us a column vector."
