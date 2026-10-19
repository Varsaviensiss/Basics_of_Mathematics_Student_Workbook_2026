# Exercise 3. Vector Normalization

## Given

$$
\mathbf{v}=(3,4)
$$

## 1. Find the Length of \(\mathbf{v}\)

The length of a vector \(\mathbf{v}=(v_1,v_2)\) is

$$
|\mathbf{v}|=\sqrt{v_1^2+v_2^2}
$$

Substitute the components:

$$
|\mathbf{v}|=\sqrt{3^2+4^2}
$$

$$
=\sqrt{9+16}
$$

$$
=\sqrt{25}
$$

Therefore,

$$
\boxed{|\mathbf{v}|=5}
$$

## 2. Find a Unit Vector with the Same Direction and Orientation

A unit vector is obtained by dividing the original vector by its length:

$$
\mathbf{e}=\frac{\mathbf{v}}{|\mathbf{v}|}
$$

Substitute \(\mathbf{v}=(3,4)\) and \(|\mathbf{v}|=5\):

$$
\mathbf{e}=\frac{(3,4)}{5}
$$

$$
\mathbf{e}=\left(\frac35,\frac45\right)
$$

Therefore, the required unit vector is

$$
\boxed{\mathbf{e}=\left(\frac35,\frac45\right)}
$$

## 3. Verify That \(|\mathbf{e}|=1\)

Calculate the length of \(\mathbf{e}\):

$$
|\mathbf{e}|=\sqrt{\left(\frac35\right)^2+\left(\frac45\right)^2}
$$

$$
=\sqrt{\frac9{25}+\frac{16}{25}}
$$

$$
=\sqrt{\frac{25}{25}}
$$

$$
=\sqrt{1}
$$

Therefore,

$$
\boxed{|\mathbf{e}|=1}
$$

The vector \(\mathbf{e}\) is a unit vector.

## 4. Reconstruct \(\mathbf{v}\) in the Form \(\mathbf{v}=|\mathbf{v}|\mathbf{e}\)

We know that

$$
|\mathbf{v}|=5
$$

and

$$
\mathbf{e}=\left(\frac35,\frac45\right)
$$

Multiply the unit vector by the original length:

$$
|\mathbf{v}|\mathbf{e}
=5\left(\frac35,\frac45\right)
$$

$$
=\left(5\cdot\frac35,5\cdot\frac45\right)
$$

$$
=(3,4)
$$

Since \(\mathbf{v}=(3,4)\),

$$
\boxed{\mathbf{v}=|\mathbf{v}|\mathbf{e}}
$$

The original vector has been reconstructed correctly.

## 5. What Changes During Normalization?

- **What changes:** The length changes from \(5\) to \(1\).
- **What remains unchanged:** The direction and orientation remain the same.

Normalization scales a nonzero vector to have length \(1\) without changing the direction in which it points.

## Final Answers

$$
\boxed{|\mathbf{v}|=5}
$$

$$
\boxed{\mathbf{e}=\left(\frac35,\frac45\right)}
$$

$$
\boxed{|\mathbf{e}|=1}
$$

$$
\boxed{\mathbf{v}=5\mathbf{e}=(3,4)}
$$
