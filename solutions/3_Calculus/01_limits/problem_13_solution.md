# Exercise 13. Fundamental Trigonometric Limit

## Question

Use the fundamental trigonometric limit, with angles measured in radians,

$$
\lim_{u\to0}\frac{\sin u}{u}=1,
$$

to evaluate both of the following limits. Show how each expression reduces to the fundamental limit.

1. $\displaystyle\lim_{x\to0}\frac{\sin(5x)}{x}$
2. $\displaystyle\lim_{x\to0}\frac{\sin(2x)}{\sin(3x)}$

## Solution

### 1. First Limit

For $x\ne0$, rewrite the expression as

$$
\frac{\sin(5x)}{x}
=5\frac{\sin(5x)}{5x}.
$$

Since $5x\to0$ as $x\to0$, the fundamental limit gives

$$
\lim_{x\to0}\frac{\sin(5x)}{x}
=5\cdot1
=\boxed{5}.
$$

### 2. Second Limit

For nonzero $x$ sufficiently close to zero, rewrite the ratio as

$$
\frac{\sin(2x)}{\sin(3x)}
=\frac{2}{3}\frac{\sin(2x)/(2x)}{\sin(3x)/(3x)}.
$$

Both $2x$ and $3x$ tend to zero, so both sine quotients tend to $1$. Since the denominator tends to a nonzero value,

$$
\lim_{x\to0}\frac{\sin(2x)}{\sin(3x)}
=\frac{2}{3}\cdot\frac{1}{1}
=\boxed{\frac{2}{3}}.
$$
