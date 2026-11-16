```markdown
# Problem 11. Derivative from the Definition

Using only

$$
f'(x)=\lim_{h\to0}\frac{f(x+h)-f(x)}{h},
$$

find the derivative of $f(x)=x^2$. Compare the result with the power rule and indicate where the limit is used in the calculation.

## Step 1: Substitute into the Definition

Since $f(x+h)=(x+h)^2$,

$$
f'(x)=\lim_{h\to0}\frac{(x+h)^2-x^2}{h}.
$$

## Step 2: Expand and Simplify

Expanding the numerator gives

$$
f'(x)=\lim_{h\to0}\frac{x^2+2xh+h^2-x^2}{h}
=\lim_{h\to0}\frac{2xh+h^2}{h}.
$$

Factor out $h$:

$$
f'(x)=\lim_{h\to0}\frac{h(2x+h)}{h}.
$$

For $h\neq0$, cancellation gives

$$
f'(x)=\lim_{h\to0}(2x+h).
$$

Cancellation is valid because a limit as $h\to0$ considers nonzero values of $h$ approaching zero.

## Step 3: Evaluate the Limit

For each fixed $x$, as $h\to0$, the expression $2x+h$ approaches $2x$. Therefore,

$$
f'(x)=\lim_{h\to0}(2x+h)=2x.
$$

Thus,

$$
\boxed{f'(x)=2x}.
$$

The limit is evaluated in this final step. The preceding expansion and cancellation are algebraic operations valid for $h\neq0$. We do not substitute $h=0$ into the original quotient, which is undefined there.

## Step 4: Compare with the Power Rule

The power rule gives

$$
\frac{d}{dx}x^2=2x^{2-1}=2x.
$$

This agrees with the result obtained directly from the definition. The power rule was used only for comparison, not in the definition-based derivation.
```
