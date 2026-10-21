# Exercise 5. The Classical Limit Leading to the Number (e)

We need to compute the limit

[\
L=\lim\_{n\to\infty}\left(1+\frac1n\right)^n.\
]

**Step 1: Calculate several values**

Let us calculate the expression for increasing values of (n).

| (n)   | (\left(1+\frac1n\right)^n) |
| ----- | -------------------------- |
| 1     | 2                          |
| 2     | 2.25                       |
| 5     | 2.48832                    |
| 10    | 2.59374                    |
| 100   | 2.70481                    |
| 1000  | 2.71692                    |
| 10000 | 2.71815                    |

We observe that the values approach approximately (2.71828).

**Step 2: Calculate the limit**

The classical definition of the number (e) is

[\
e=\lim\_{n\to\infty}\left(1+\frac1n\right)^n.\
]

Therefore,

[\
\boxed{\lim\_{n\to\infty}\left(1+\frac1n\right)^n=e}\
]

where

[\
e\approx 2.71828.\
]

**Step 3: Explain the observed behavior**

As (n) increases, the fraction (\frac1n) approaches zero. However, the entire expression is raised to the power (n). These two effects combine so that the expression approaches the finite number (e), rather than (1) or infinity.

**Step 4: Why are a few values not a proof?**

Calculating several terms helps us understand the behavior of the sequence, but it does not prove the limit. Even if the first several values approach a particular number, later terms could behave differently. A mathematical proof must show that the sequence approaches (e) as (n) tends to infinity, not merely that some calculated values are close to (e).

**Final Answer:**

[\
\boxed{L=e\approx 2.71828}\
]
