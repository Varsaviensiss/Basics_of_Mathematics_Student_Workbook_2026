# Exercise 3. When Can Matrices Be Multiplied?

Given the matrix sizes:

$$
A:2\times3,\qquad B:3\times4
$$

$$
C:4\times2,\qquad D:2\times2
$$

## Dimension Compatibility Condition

Two matrices can be multiplied if the number of columns of the first matrix equals the number of rows of the second matrix.

If

$$
A_{m\times n}B_{p\times q}
$$

then the product is defined only if

$$
n=p
$$

When the product is defined, its size is

$$
\boxed{m\times q}
$$

## 1. Product \(AB\)

The dimensions are:

$$
A:2\times3,\qquad B:3\times4
$$

Compare the inner dimensions:

$$
3=3
$$

The inner dimensions match, so the product is defined.

The result has the outer dimensions:

$$
2\times4
$$

Therefore:

$$
\boxed{AB\text{ is defined and has size }2\times4}
$$

## 2. Product \(BA\)

The dimensions are:

$$
B:3\times4,\qquad A:2\times3
$$

Compare the inner dimensions:

$$
4\neq2
$$

The inner dimensions do not match, so the product is not defined.

Therefore:

$$
\boxed{BA\text{ is not defined}}
$$

## 3. Product \(BC\)

The dimensions are:

$$
B:3\times4,\qquad C:4\times2
$$

Compare the inner dimensions:

$$
4=4
$$

The inner dimensions match, so the product is defined.

The result has the outer dimensions:

$$
3\times2
$$

Therefore:

$$
\boxed{BC\text{ is defined and has size }3\times2}
$$

## 4. Product \(CB\)

The dimensions are:

$$
C:4\times2,\qquad B:3\times4
$$

Compare the inner dimensions:

$$
2\neq3
$$

The inner dimensions do not match, so the product is not defined.

Therefore:

$$
\boxed{CB\text{ is not defined}}
$$

## 5. Product \(AC\)

The dimensions are:

$$
A:2\times3,\qquad C:4\times2
$$

Compare the inner dimensions:

$$
3\neq4
$$

The inner dimensions do not match, so the product is not defined.

Therefore:

$$
\boxed{AC\text{ is not defined}}
$$

## 6. Product \(CA\)

The dimensions are:

$$
C:4\times2,\qquad A:2\times3
$$

Compare the inner dimensions:

$$
2=2
$$

The inner dimensions match, so the product is defined.

The result has the outer dimensions:

$$
4\times3
$$

Therefore:

$$
\boxed{CA\text{ is defined and has size }4\times3}
$$

## 7. Product \(AD\)

The dimensions are:

$$
A:2\times3,\qquad D:2\times2
$$

Compare the inner dimensions:

$$
3\neq2
$$

The inner dimensions do not match, so the product is not defined.

Therefore:

$$
\boxed{AD\text{ is not defined}}
$$

## 8. Product \(DA\)

The dimensions are:

$$
D:2\times2,\qquad A:2\times3
$$

Compare the inner dimensions:

$$
2=2
$$

The inner dimensions match, so the product is defined.

The result has the outer dimensions:

$$
2\times3
$$

Therefore:

$$
\boxed{DA\text{ is defined and has size }2\times3}
$$

## Summary Table

| Product | Inner dimensions | Defined? | Result size |
|---|---|---|---|
| \(AB\) | \(3=3\) | Yes | \(2\times4\) |
| \(BA\) | \(4\neq2\) | No | — |
| \(BC\) | \(4=4\) | Yes | \(3\times2\) |
| \(CB\) | \(2\neq3\) | No | — |
| \(AC\) | \(3\neq4\) | No | — |
| \(CA\) | \(2=2\) | Yes | \(4\times3\) |
| \(AD\) | \(3\neq2\) | No | — |
| \(DA\) | \(2=2\) | Yes | \(2\times3\) |

## Final Answer

The defined products are:

$$
\boxed{AB:2\times4}
$$

$$
\boxed{BC:3\times2}
$$

$$
\boxed{CA:4\times3}
$$

$$
\boxed{DA:2\times3}
$$

The products \(BA\), \(CB\), \(AC\), and \(AD\) are not defined because their inner dimensions do not match.

**Conclusion:** Matrix multiplication is possible only when the number of columns of the first matrix equals the number of rows of the second matrix. The result has the number of rows of the first matrix and the number of columns of the second matrix.

