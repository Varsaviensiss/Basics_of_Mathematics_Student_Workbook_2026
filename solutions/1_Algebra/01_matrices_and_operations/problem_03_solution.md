# Exercise 3: When Can Matrices Be Multiplied?

Given matrix sizes:

- \(A: 2\times3\)
- \(B: 3\times4\)
- \(C: 4\times2\)
- \(D: 2\times2\)

**Condition for matrix multiplication:**

The number of columns of the first matrix must equal the number of rows of the second matrix. The resulting matrix has the number of rows of the first matrix and the number of columns of the second matrix.

## 1. Product \(AB\)

\[
(2\times3)(3\times4)
\]

The inner dimensions are equal (3 = 3), so the product is defined.

\[
\boxed{AB: 2\times4}
\]

## 2. Product \(BA\)

\[
(3\times4)(2\times3)
\]

The inner dimensions are not equal (4 ≠ 2), so the product is not defined.

## 3. Product \(BC\)

\[
(3\times4)(4\times2)
\]

The inner dimensions are equal (4 = 4), so the product is defined.

\[
\boxed{BC: 3\times2}
\]

## 4. Product \(CB\)

\[
(4\times2)(3\times4)
\]

The inner dimensions are not equal (2 ≠ 3), so the product is not defined.

## 5. Product \(AC\)

\[
(2\times3)(4\times2)
\]

The inner dimensions are not equal (3 ≠ 4), so the product is not defined.

## 6. Product \(CA\)

\[
(4\times2)(2\times3)
\]

The inner dimensions are equal (2 = 2), so the product is defined.

\[
\boxed{CA: 4\times3}
\]

## 7. Product \(AD\)

\[
(2\times3)(2\times2)
\]

The inner dimensions are not equal (3 ≠ 2), so the product is not defined.

## 8. Product \(DA\)

\[
(2\times2)(2\times3)
\]

The inner dimensions are equal (2 = 2), so the product is defined.

\[
\boxed{DA: 2\times3}
\]

## Conclusion

The defined products are \(AB\), \(BC\), \(CA\), and \(DA\).

Their sizes are:

- \(AB: 2\times4\)
- \(BC: 3\times2\)
- \(CA: 4\times3\)
- \(DA: 2\times3\)

The products \(BA\), \(CB\), \(AC\), and \(AD\) are not defined because their inner dimensions do not match.
