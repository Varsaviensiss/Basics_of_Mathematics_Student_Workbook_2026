# Exercise 12. Exponential Function Limit

## Question

Evaluate the limit

$$
\lim_{x\to0}(1+3x)^{1/x}.
$$

Transform the expression into the standard form that tends to $e$ and explain its connection with the classical sequence limit in Exercise 5.

## Solution

For nonzero $x$ sufficiently close to zero, $1+3x>0$. Since $1/x=3/(3x)$, we can write

$$
(1+3x)^{1/x}
=
\left[(1+3x)^{1/(3x)}\right]^3.
$$

Let $t=3x$. As $x\to0$, we have $t\to0$, so

$$
\lim_{x\to0}(1+3x)^{1/x}
=
\left[\lim_{t\to0}(1+t)^{1/t}\right]^3
=
\boxed{e^3}.
$$

## Connection with Exercise 5

In Exercise 5, taking $t=1/n$ gives $(1+t)^{1/t}=(1+1/n)^n$. This is the same expression evaluated along a sequence of positive values approaching zero.

Here $t$ can approach zero from either side. The two-sided standard limit follows from $\ln(1+t)/t\to1$, since this quotient is the difference quotient of $\ln$ at $1$. Thus $(1+t)^{1/t}\to e$, and cubing gives $e^3$.
