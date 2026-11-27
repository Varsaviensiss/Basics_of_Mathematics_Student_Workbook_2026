# Problem 15. Recovering a Function from Its Derivative and a Condition

## Question

The function $F$ satisfies

$$
F'(x)=2xe^{x^2}
\qquad\text{and}\qquad
F(0)=3.
$$

1. Recognize the method needed to find the function $F$.
2. Determine the entire family of functions with the given derivative.
3. Use the condition $F(0)=3$ to determine the correct constant.
4. Verify the final result by differentiation and substitution of $x=0$.

## Solution

### 1. Choose the method

Use substitution because the exponent is $x^2$ and its derivative, $2x$, appears as a factor. Let $u=x^2$. Then $du=2x\,dx$.

### 2. Find the family of functions

Integrate the given derivative and substitute back:

$$
F(x)=\int 2xe^{x^2}\,dx
=\int e^u\,du
=e^u+C
=e^{x^2}+C,
\qquad C\in\mathbb{R}.
$$

### 3. Determine the constant

The condition $F(0)=3$ gives

$$
e^{0^2}+C=1+C=3.
$$

Thus $C=2$, so the function is

$$
F(x)=e^{x^2}+2.
$$

### 4. Verify both conditions

The chain rule gives

$$
\frac{d}{dx}\left(e^{x^2}+2\right)=2xe^{x^2},
$$

which is the given derivative. Substituting $x=0$ gives

$$
F(0)=e^0+2=3,
$$

which confirms the initial condition.
