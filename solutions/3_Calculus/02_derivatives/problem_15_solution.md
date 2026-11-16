```markdown
# Problem 15. The Difference Quotient as a Check of the Derivative

Choose one function from the problem set and a point $x_0$ at which the derivative exists. Compute $f'(x_0)$ exactly, and then calculate

$$
\frac{f(x_0+h)-f(x_0)}{h}
$$

for $h=1$, $0.1$, and $0.01$. Compare the values with $f'(x_0)$ and explain why the difference quotient approaching a single number is consistent with the definition of the derivative, while a few computations do not replace a limit argument.

## Step 1: Choose the Function and Point

Choose $f(x)=x^2$ from Problem 11 and $x_0=1$.

By the power rule,

$$
f'(x)=2x.
$$

Therefore, the exact derivative at the chosen point is

$$
\boxed{f'(1)=2}.
$$

## Step 2: Compute the Difference Quotient

For $h\neq0$, let

$$
Q(h)=\frac{f(1+h)-f(1)}{h}.
$$

Substituting the function values and simplifying,

$$
Q(h)=\frac{(1+h)^2-1}{h}
=\frac{2h+h^2}{h}
=\boxed{2+h}.
$$

## Step 3: Calculate and Compare Values

| $h$ | Difference quotient $Q(h)=2+h$ | Exact derivative $f'(1)$ |
|---:|---:|---:|
| $1$ | $3$ | $2$ |
| $0.1$ | $2.1$ | $2$ |
| $0.01$ | $2.01$ | $2$ |

The calculated values get closer to $2$ as these positive values of $h$ get closer to zero. This illustrates the behavior expected from the definition of the derivative.

## Step 4: Prove the Limit

The algebraic identity $Q(h)=2+h$ holds for every nonzero real $h$. Hence,

$$
\lim_{h\to0}Q(h)
=\lim_{h\to0}(2+h)
=2.
$$

This holds as $h$ approaches zero from either side. More explicitly,

$$
|Q(h)-2|=|h|.
$$

For any $\varepsilon>0$, choosing $\delta=\varepsilon$ ensures that $0<|h|<\delta$ implies $|Q(h)-2|<\varepsilon$.

Therefore, by the definition of the derivative,

$$
\boxed{f'(1)=2}.
$$

## Step 5: Explain Why the Table Is Not a Proof

Finitely many values of $h$ leave untested values arbitrarily close to zero. A table therefore cannot establish what happens for every sufficiently small nonzero $h$, including values approaching zero from the negative side.

The formula $Q(h)=2+h$ proves convergence for every approach $h\to0$. Thus, the table illustrates the derivative limit, while the algebraic limit argument proves it.
```
