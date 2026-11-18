```markdown
# Exercise 11. Decomposition into Parallel and Perpendicular Components

Given $\mathbf{u}=(3,4)$ and $\mathbf{v}=(1,2)$, find the components of $\mathbf{u}$ parallel and perpendicular to $\mathbf{v}$. Verify that they add up to $\mathbf{u}$ and that the perpendicular component is orthogonal to $\mathbf{v}$. Explain why these two checks are independent.

## 1. Find the Components

Since $\mathbf{u}\cdot\mathbf{v}=3(1)+4(2)=11$ and $\mathbf{v}\cdot\mathbf{v}=1^2+2^2=5$,

$$
\mathbf{u}_{\parallel}
=\frac{\mathbf{u}\cdot\mathbf{v}}{\mathbf{v}\cdot\mathbf{v}}\mathbf{v}
=\frac{11}{5}(1,2)
=\left(\frac{11}{5},\frac{22}{5}\right).
$$

$$
\mathbf{u}_{\perp}
=\mathbf{u}-\mathbf{u}_{\parallel}
=\left(\frac{4}{5},-\frac{2}{5}\right).
$$

## 2. Verify Both Conditions

$$
\mathbf{u}_{\parallel}+\mathbf{u}_{\perp}
=\left(\frac{11+4}{5},\frac{22-2}{5}\right)
=(3,4)=\mathbf{u}.
$$

$$
\mathbf{u}_{\perp}\cdot\mathbf{v}
=\frac{4}{5}(1)-\frac{2}{5}(2)=0.
$$

## 3. Explain Why the Checks Are Independent

- **Reconstruction can pass while perpendicularity fails.** Choose the proposed components $\mathbf{p}=(0,0)$ and $\mathbf{q}=(3,4)$. Then $\mathbf{p}+\mathbf{q}=\mathbf{u}$, but $\mathbf{q}\cdot\mathbf{v}=3(1)+4(2)=11\ne0$.
- **Perpendicularity can pass while reconstruction fails.** Choose $\mathbf{p}=(1,2)$ and $\mathbf{q}=(2,-1)$. Here $\mathbf{p}$ is parallel to $\mathbf{v}$ and $\mathbf{q}\cdot\mathbf{v}=2(1)-1(2)=0$, but $\mathbf{p}+\mathbf{q}=(3,1)\ne\mathbf{u}$.

Each check can pass while the other fails, so both checks are necessary.
```
