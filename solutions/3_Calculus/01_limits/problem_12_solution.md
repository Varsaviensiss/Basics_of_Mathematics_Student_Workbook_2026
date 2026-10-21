# Exercise 12. Exponential Function Limit

We need to compute

[\
L=\lim\_{x\to0}(1+3x)^{1/x}.\
]

**Step 1: Transform the exponent**

We rewrite the expression as

[\
(1+3x)^{1/x}\
\=\left[(1+3x)^{1/(3x)}\right]^3.\
]

Therefore,

[\
L=\left[\lim\_{x\to0}(1+3x)^{1/(3x)}\right]^3.\
]

**Step 2: Use a substitution**

Let

[\
t=3x.\
]

When (x\to0), we also have (t\to0). Thus,

[\
L=\left[\lim\_{t\to0}(1+t)^{1/t}\right]^3.\
]

**Step 3: Apply the classical limit**

From Exercise 5, we know that

[\
\lim\_{t\to0}(1+t)^{1/t}=e.\
]

Therefore,

[\
L=e^3.\
]

**Final Answer:**

[\
\boxed{\lim\_{x\to0}(1+3x)^{1/x}=e^3}\
]

Numerically,

[\
e^3\approx20.0855.\
]

**Explanation:**

This problem uses the same classical limit as Exercise 5. By rewriting the expression and making the substitution (t=3x), we obtain the standard form that approaches (e). Since the original expression is the cube of this standard form, the final answer is (e^3).
