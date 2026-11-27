# Problem 9. An Oblique Asymptote

## Question

For the function

$$
f(x)=\frac{x^2+1}{x-1},
$$

find the vertical and oblique asymptotes. Use polynomial division and explain why the difference between the function and its oblique asymptote tends to zero as $x\to+\infty$ and as $x\to-\infty$.

## Solution

### 1. Divide the polynomials

Since $(x-1)(x+1)=x^2-1$, the division gives quotient $x+1$ and remainder $2$:

$$
x^2+1=(x-1)(x+1)+2.
$$

Dividing by $x-1$ gives

$$
f(x)=x+1+\frac{2}{x-1},\qquad x\ne 1.
$$

### 2. Find the vertical asymptote

As $x$ approaches $1$, the term $x+1$ tends to $2$, while the remainder term $\frac{2}{x-1}$ grows without bound in magnitude. The denominator is negative to the left of $1$ and positive to the right, so

$$
\lim_{x\to1^-}f(x)=-\infty,
\qquad
\lim_{x\to1^+}f(x)=+\infty.
$$

Therefore, the vertical asymptote is **$x=1$**.

### 3. Find the oblique asymptote

The difference between the function and the line $y=x+1$ is

$$
f(x)-(x+1)=\frac{2}{x-1}.
$$

As $x\to+\infty$ or $x\to-\infty$, the magnitude $|x-1|$ grows without bound while the numerator stays equal to $2$. Therefore,

$$
\lim_{x\to+\infty}\bigl(f(x)-(x+1)\bigr)=0,
\qquad
\lim_{x\to-\infty}\bigl(f(x)-(x+1)\bigr)=0.
$$

Thus **$y=x+1$** is the oblique asymptote at both ends of the graph.
