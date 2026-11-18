# Exercise 5. The Classical Limit Leading to the Number e

## Question

Evaluate the limit

$$
L=\lim_{n\to\infty}\left(1+\frac{1}{n}\right)^n.
$$

Calculate the expression for several increasing values of $n$ and compare the results with $e$. Explain what the numerical values suggest and why a finite table does not prove the limit.

## Solution

### 1. Numerical Comparison

Let $a_n=\left(1+\frac{1}{n}\right)^n$.

| $n$ | $a_n$ (rounded to five decimal places) |
|---:|---:|
| 1 | 2.00000 |
| 2 | 2.25000 |
| 5 | 2.48832 |
| 10 | 2.59374 |
| 100 | 2.70481 |
| 1,000 | 2.71692 |
| 10,000 | 2.71815 |

The displayed values are below $e\approx2.71828$ and get closer to it as $n$ increases.

### 2. Evaluate the Limit

By the classical limit definition of $e$,

$$
\boxed{L=\lim_{n\to\infty}\left(1+\frac{1}{n}\right)^n=e}.
$$

The base approaches $1$ while the exponent grows without bound. This is the indeterminate form $1^\infty$, so the behavior of the base alone does not determine the limit.

### 3. Why the Table Does Not Prove the Limit

The table illustrates convergence by showing selected terms close to $e$. A proof must establish that for every $\varepsilon>0$, all terms with sufficiently large $n$ are within $\varepsilon$ of $e$. A finite table leaves infinitely many later terms untested.
