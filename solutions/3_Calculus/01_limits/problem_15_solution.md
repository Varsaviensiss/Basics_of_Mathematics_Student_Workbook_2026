# Exercise 15. Observation Versus Proof

## Question

Choose a sequence and a function from this problem set. Calculate several terms of the sequence and several values of the function on both sides of the point it approaches. Sketch both graphs, find both limits analytically, and compare the results with your observations. Explain why tables and sketches alone do not prove a limit.

## Solution

### 1. Sequence from Exercise 5

Consider $a_n=(1+1/n)^n$.

| $n$ | $a_n$ (rounded) |
|---:|---:|
| 1 | 2.00000 |
| 2 | 2.25000 |
| 5 | 2.48832 |
| 10 | 2.59374 |
| 100 | 2.70481 |
| 1000 | 2.71692 |

The values suggest that $a_n$ approaches $e\approx2.71828$. To establish the limit analytically, take logarithms:

$$
\ln a_n=n\ln(1+1/n)=\frac{\ln(1+1/n)}{1/n}.
$$

As $n\to\infty$, this quotient tends to $1$ because it is the difference quotient of $\ln$ at $1$, where its derivative is $1$. By continuity of the exponential function,

$$
\boxed{\lim_{n\to\infty}a_n=e}.
$$

### 2. Function from Exercise 7

Consider $f(x)=\frac{x^2-4x+3}{x-3}$ as $x\to3$.

| $x$ approaching from the left | $f(x)$ | $x$ approaching from the right | $f(x)$ |
|---:|---:|---:|---:|
| 2.9 | 1.9 | 3.1 | 2.1 |
| 2.99 | 1.99 | 3.01 | 2.01 |
| 2.999 | 1.999 | 3.001 | 2.001 |

The values approach $2$ from both sides. Factoring gives, for every $x\ne3$,

$$
f(x)=\frac{(x-1)(x-3)}{x-3}=x-1.
$$

Since $x-1$ is continuous at $3$,

$$
\boxed{\lim_{x\to3}f(x)=2}.
$$

### 3. Sketches

**Sequence from Exercise 5**

```text
a_n
  e  | - - - - - - - - - - - - - -  y = e
     |                       *  *
     |                  *
     |             *
     |        *
2.0  |   *
     +-----------------------------> n
```

The dots represent individual terms of $a_n=(1+1/n)^n$. As $n$ increases, the terms approach $e$ from below. The sketch is not to scale.

**Function from Exercise 7**

```text
f(x)
  ^
3 |                 *  (4, 3)
  |               /
2 |             o  (3, 2)
  |           /
1 |         *  (2, 1)
  |       /
  +--------------------------> x
```

The graph follows $y=x-1$ for $x\ne3$. The open circle at $(3,2)$ marks the hole because $f(3)$ is undefined. Both sides approach the same height, $2$.
### 4. Observation Versus Proof

The tables and sketches agree with the analytical limits. A finite table leaves infinitely many sequence terms and function values untested. The logarithmic argument establishes convergence for all sufficiently large $n$. For the function, $|f(x)-2|=|x-3|$ for every $x\ne3$, so the values approach $2$ from either side.
