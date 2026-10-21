# Exercise 15. Observation Versus Proof

In this exercise, we study one sequence and one function. We calculate several values, observe their behavior, and compare the results with the analytical limits.

## Part 1: Sequence

Consider the sequence

[\
a_n=\left(1+\frac1n\right)^n.\
]

We calculate several values for increasing (n).

| (n)  | (a_n)   |
| ---- | ------- |
| 1    | 2       |
| 2    | 2.25    |
| 5    | 2.48832 |
| 10   | 2.59374 |
| 100  | 2.70481 |
| 1000 | 2.71692 |

The values approach approximately (2.71828).

The analytical result is

[\
\boxed{\lim\_{n\to\infty}\left(1+\frac1n\right)^n=e}\
]

where (e\approx2.71828).

Therefore, the numerical calculations agree with the analytical result.

## Part 2: Function

Consider the function

[\
f(x)=\frac{x^2-1}{x-1}.\
]

We want to calculate

[\
\lim\_{x\to1}\frac{x^2-1}{x-1}.\
]

First, factor the numerator:

[\
x^2-1=(x-1)(x+1).\
]

For (x\ne1), we can cancel the common factor:

[\
f(x)=x+1.\
]

Therefore,

[\
\boxed{\lim\_{x\to1}\frac{x^2-1}{x-1}=2}\
]

### Table of values

We calculate values approaching (1) from the left and right.

| (x)   | (f(x)) |
| ----- | ------ |
| 0.9   | 1.9    |
| 0.99  | 1.99   |
| 0.999 | 1.999  |
| 1.001 | 2.001  |
| 1.01  | 2.01   |
| 1.1   | 2.1    |

From the table, the function values approach (2) from both sides.

\<Graph expressions={[{"latex":"y=\frac{x^2-1}{x-1}","restrictions":["x<1"]},{"latex":"y=\frac{x^2-1}{x-1}","restrictions":["x>1"]},{"latex":"y=2"}]} />

The graph follows the line (y=x+1), except the original function is undefined at (x=1). There is a hole at ((1,2)), but the limit still exists.

## Part 3: Observation Versus Proof

The tables and graph help us understand the behavior of the sequence and function. The numerical values suggest that the sequence approaches (e) and the function approaches (2).

However, a finite number of calculations cannot prove that a limit exists. We can only calculate a limited number of values, and later terms might behave differently. Similarly, a graph may not show every detail of a function.

A mathematical proof establishes that the values approach a particular number as the variable approaches the required point or infinity.

## Conclusion

The numerical observations agree with the analytical results:

[\
\lim\_{n\to\infty}\left(1+\frac1n\right)^n=e\
]

and

[\
\lim\_{x\to1}\frac{x^2-1}{x-1}=2.\
]

Tables and graphs provide useful intuition, but a mathematical proof is needed to establish the existence and value of a limit rigorously.

Add a true two-sided function tableGive a brief analytical proof for the sequence
