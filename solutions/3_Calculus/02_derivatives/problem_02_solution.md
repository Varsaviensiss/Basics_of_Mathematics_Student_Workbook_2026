# Problem 2. Powers, Roots, and the Domain

Given the function

$$
f(x)=2\sqrt{x}-\frac{3}{x^2}+x^{3/2},
$$

1. Rewrite the function using powers.
2. Determine its domain.
3. Compute the derivative.
4. Compare the domain of the function with the domain of its derivative.

## Solution

### 1. Rewrite Using Powers

Using $\sqrt{x}=x^{1/2}$ and $1/x^2=x^{-2}$, we obtain

$$
\boxed{f(x)=2x^{1/2}-3x^{-2}+x^{3/2}}.
$$

This form allows us to apply the power rule term by term.

### 2. Domain of the Function

The terms $\sqrt{x}$ and $x^{3/2}$ require $x\geq0$ over the real numbers. The denominator $x^2$ requires $x\neq0$.

Combining these restrictions gives

$$
\boxed{D_f=(0,\infty)}.
$$

### 3. Compute the Derivative

Using the power rule,

$$
\frac{d}{dx}x^n=nx^{n-1},
$$

we differentiate each term:

$$
f'(x)
=2\cdot\frac12x^{-1/2}
-3(-2)x^{-3}
+\frac32x^{1/2}.
$$

Therefore,

$$
\boxed{f'(x)=\frac{1}{\sqrt{x}}+\frac{6}{x^3}+\frac32\sqrt{x}}.
$$

### 4. Compare the Domains

The term $1/\sqrt{x}$ requires $x>0$, the term $6/x^3$ requires $x\neq0$, and $\sqrt{x}$ requires $x\geq0$.

Thus,

$$
\boxed{D_{f'}=(0,\infty)}.
$$

The two domains agree:

$$
\boxed{D_f=D_{f'}=(0,\infty)}.
$$

The original function already excludes $x=0$, so differentiation introduces no additional domain restriction.
