# Exercise 8. A Square Root in a Function Limit

## Question

Evaluate the following limit by rationalizing the numerator:

$$
\lim_{x\to4}\frac{\sqrt{x}-2}{x-4}.
$$

Compare the rationalization method with the one used in Exercise 3.

## Solution

Direct substitution gives the indeterminate form $0/0$. Multiply the numerator and denominator by the conjugate $\sqrt{x}+2$:

$$
\frac{\sqrt{x}-2}{x-4}
=
\frac{(\sqrt{x}-2)(\sqrt{x}+2)}{(x-4)(\sqrt{x}+2)}
=
\frac{x-4}{(x-4)(\sqrt{x}+2)}.
$$

The difference of squares produces the factor $x-4$ in the numerator. For $x\ne4$, we can cancel it:

$$
\frac{\sqrt{x}-2}{x-4}=\frac{1}{\sqrt{x}+2}.
$$

The simplified expression is continuous at $x=4$, so

$$
\lim_{x\to4}\frac{\sqrt{x}-2}{x-4}
=\frac{1}{\sqrt{4}+2}
=\boxed{\frac14}.
$$

## Comparison with Exercise 3

Both exercises use a conjugate and the difference-of-squares identity. In Exercise 3, rationalization turns an $\infty-\infty$ expression into a quotient, which we simplify by dividing by $n$ as $n\to\infty$. Here, rationalization exposes the common factor $x-4$, which we cancel to resolve the $0/0$ form as $x\to4$.
