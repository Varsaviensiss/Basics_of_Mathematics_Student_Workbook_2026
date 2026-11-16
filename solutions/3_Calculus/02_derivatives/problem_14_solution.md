```markdown
# Problem 14. Continuity and Differentiability of a Piecewise Function

Investigate the behavior at $x=0$ of

$$
f(x)=
\begin{cases}
x^2, & x\geq0,\\
ax, & x<0.
\end{cases}
$$

For which values of $a$ is the function continuous? For which values do the one-sided derivatives exist and agree? For which value of $a$ is the function differentiable? Explain why continuity alone is not sufficient.

## Step 1: Check Continuity at Zero

The function value is

$$
f(0)=0^2=0.
$$

For every real $a$, the one-sided limits are

$$
\lim_{x\to0^-}f(x)=\lim_{x\to0^-}ax=0
$$

and

$$
\lim_{x\to0^+}f(x)=\lim_{x\to0^+}x^2=0.
$$

Both limits equal $f(0)$. Therefore, the function is continuous at zero for

$$
\boxed{a\in\mathbb{R}}.
$$

## Step 2: Compute the One-Sided Derivatives

Using the difference quotient and $f(0)=0$, the left-hand derivative is

$$
f'_-(0)
=\lim_{h\to0^-}\frac{f(h)-f(0)}{h}
=\lim_{h\to0^-}\frac{ah}{h}
=a.
$$

The right-hand derivative is

$$
f'_+(0)
=\lim_{h\to0^+}\frac{f(h)-f(0)}{h}
=\lim_{h\to0^+}\frac{h^2}{h}
=\lim_{h\to0^+}h
=0.
$$

Thus, both one-sided derivatives exist for every real $a$:

$$
\boxed{f'_-(0)=a,\qquad f'_+(0)=0}.
$$

They agree exactly when

$$
\boxed{a=0}.
$$

## Step 3: Determine Differentiability

The derivative at zero exists precisely when the two one-sided derivatives agree. Therefore, the function is differentiable at zero only for

$$
\boxed{a=0}.
$$

In that case, $f'(0)=0$.

## Step 4: Explain Why Continuity Is Not Sufficient

Continuity requires the function values from both sides to approach $f(0)$. Differentiability additionally requires the one-sided slopes to agree.

For example, when $a=1$, the function is continuous at zero, but

$$
f'_-(0)=1\neq0=f'_+(0).
$$

Hence, it is not differentiable there. Matching values alone does not guarantee matching slopes.
```
