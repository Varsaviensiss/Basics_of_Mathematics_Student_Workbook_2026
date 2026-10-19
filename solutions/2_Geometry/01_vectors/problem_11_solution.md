# Exercise 11. Decomposition into Parallel and Perpendicular Components

## Given

$$
\mathbf{u}=(3,4),\qquad \mathbf{v}=(1,2)
$$

## 1. Find the Parallel Component

The projection of \(\mathbf{u}\) onto \(\mathbf{v}\) is

$$
\mathbf{u}_{\parallel}
=\frac{\mathbf{u}\cdot\mathbf{v}}{\mathbf{v}\cdot\mathbf{v}}\mathbf{v}
$$

Calculate the dot products:

$$
\mathbf{u}\cdot\mathbf{v}=3(1)+4(2)=11
$$

$$
\mathbf{v}\cdot\mathbf{v}=1^2+2^2=5
$$

Substitute:

$$
\mathbf{u}_{\parallel}=\frac{11}{5}(1,2)
$$

$$
\boxed{\mathbf{u}_{\parallel}=\left(\frac{11}{5},\frac{22}{5}\right)}
$$

## 2. Find the Perpendicular Component

The perpendicular component is

$$
\mathbf{u}_{\perp}=\mathbf{u}-\mathbf{u}_{\parallel}
$$

$$
=(3,4)-\left(\frac{11}{5},\frac{22}{5}\right)
$$

$$
=\left(\frac{15}{5}-\frac{11}{5},\frac{20}{5}-\frac{22}{5}\right)
$$

$$
\boxed{\mathbf{u}_{\perp}=\left(\frac45,-\frac25\right)}
$$

## 3. Check That the Components Reconstruct \(\mathbf{u}\)

$$
\mathbf{u}_{\parallel}+\mathbf{u}_{\perp}
=\left(\frac{11}{5},\frac{22}{5}\right)
+\left(\frac45,-\frac25\right)
$$

$$
=\left(\frac{15}{5},\frac{20}{5}\right)
$$

$$
=(3,4)
$$

Therefore,

$$
\boxed{\mathbf{u}=\mathbf{u}_{\parallel}+\mathbf{u}_{\perp}}
$$

## 4. Check Perpendicularity

$$
\mathbf{u}_{\perp}\cdot\mathbf{v}
=\left(\frac45,-\frac25\right)\cdot(1,2)
$$

$$
=\frac45-\frac45
$$

$$
=0
$$

Therefore,

$$
\boxed{\mathbf{u}_{\perp}\cdot\mathbf{v}=0}
$$

## 5. Why Are These Two Independent Checks?

- The reconstruction check confirms that the two components add up to the original vector.
- The perpendicularity check confirms that the perpendicular component is orthogonal to \(\mathbf{v}\).

Both are necessary to verify the intended decomposition.

## Final Answer

$$
\boxed{\mathbf{u}_{\parallel}=\left(\frac{11}{5},\frac{22}{5}\right)}
$$

$$
\boxed{\mathbf{u}_{\perp}=\left(\frac45,-\frac25\right)}
$$
