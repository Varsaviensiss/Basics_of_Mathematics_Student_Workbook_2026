# Exercise 10. Continuity of a Piecewise Function

## Question

Given the function

$$
f(x)=
\begin{cases}
ax+1, & x<2,\\[0pt]
x^2-1, & x\geq 2,
\end{cases}
$$

find the value of $a$ that makes $f$ continuous at $x=2$. Calculate and compare the left-hand limit, the right-hand limit, and the function value at $x=2$.

## Solution

### 1. Left-Hand Limit

For $x<2$, we have $f(x)=ax+1$. Therefore,

$$
\lim_{x\to2^-}f(x)=\lim_{x\to2^-}(ax+1)=2a+1.
$$

### 2. Right-Hand Limit

For $x>2$, we have $f(x)=x^2-1$. Therefore,

$$
\lim_{x\to2^+}f(x)=\lim_{x\to2^+}(x^2-1)=2^2-1=3.
$$

### 3. Function Value

The second branch includes $x=2$, so

$$
f(2)=2^2-1=3.
$$

### 4. Compare the Three Values

Continuity at $x=2$ requires both one-sided limits to equal $f(2)$. The right-hand limit already equals $f(2)=3$, so the remaining condition is

$$
2a+1=3 \quad\Longrightarrow\quad \boxed{a=1}.
$$

For $a=1$, the left-hand limit, the right-hand limit, and $f(2)$ are all equal to $3$. Thus, $f$ is continuous at $x=2$ exactly when $a=1$.
