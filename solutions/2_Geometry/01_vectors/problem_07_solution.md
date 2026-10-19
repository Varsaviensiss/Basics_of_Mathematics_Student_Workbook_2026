# Exercise 7. Linear Dependence Without Heavy Computation

## Given

$$
\mathbf{u}=(1,2,3)
$$

$$
\mathbf{v}=(2,4,6)
$$

$$
\mathbf{w}=(0,1,1)
$$

## 1. Identify the Relation Between \(\mathbf{u}\) and \(\mathbf{v}\)

Compare their components:

$$
2\mathbf{u}=2(1,2,3)
$$

$$
2\mathbf{u}=(2,4,6)
$$

Since \(\mathbf{v}=(2,4,6)\),

$$
\boxed{\mathbf{v}=2\mathbf{u}}
$$

Thus, \(\mathbf{u}\) and \(\mathbf{v}\) are scalar multiples of each other.

## 2. Determine Whether the Three Vectors Can Be Linearly Independent

A set of vectors is linearly dependent if at least one vector can be expressed as a linear combination of the others.

From the relation above,

$$
2\mathbf{u}-\mathbf{v}=\mathbf{0}
$$

This is a nontrivial linear relation because the coefficients are not all zero.

Therefore,

$$
\boxed{\mathbf{u},\mathbf{v},\mathbf{w}\text{ are linearly dependent}}
$$

## 3. Why Is No Long Calculation Needed?

The relation \(\mathbf{v}=2\mathbf{u}\) immediately shows that two vectors point in the same direction and are not independent.

Adding \(\mathbf{w}\) cannot make the entire set linearly independent.

$$
\boxed{\text{One scalar-multiple relation is sufficient to prove dependence.}}
$$
