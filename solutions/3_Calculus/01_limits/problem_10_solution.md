# Exercise 10. Continuity of a Piecewise Function

We are given the piecewise function

[\
f(x)=\
\begin{cases}\
ax+1, & x<2,\\\
x^2-1, & x\geq2.\
\end{cases}\
]

We need to find the value of (a) that makes the function continuous at (x=2).

**Step 1: Calculate the left-hand limit**

For (x<2), the function is (f(x)=ax+1).

Therefore,

[\
\lim\_{x\to2^-}f(x)\
\=\lim\_{x\to2^-}(ax+1).\
]

Substituting (x=2), we get

[\
\boxed{\lim\_{x\to2^-}f(x)=2a+1}.\
]

**Step 2: Calculate the right-hand limit**

For (x\geq2), the function is (f(x)=x^2-1).

Therefore,

[\
\lim\_{x\to2^+}f(x)\
\=\lim\_{x\to2^+}(x^2-1).\
]

Substituting (x=2), we get

[\
\lim\_{x\to2^+}f(x)=2^2-1=4-1.\
]

Thus,

[\
\boxed{\lim\_{x\to2^+}f(x)=3}.\
]

**Step 3: Calculate the function value at (x=2)**

Since the second part applies when (x\geq2), we use (f(x)=x^2-1).

[\
f(2)=2^2-1=4-1.\
]

Therefore,

[\
\boxed{f(2)=3}.\
]

**Step 4: Apply the continuity condition**

A function is continuous at (x=2) if

[\
\lim\_{x\to2^-}f(x)\
\=\lim\_{x\to2^+}f(x)\
\=f(2).\
]

Substituting our results gives

[\
2a+1=3.\
]

Solving for (a),

[\
2a=3-1,\
]

[\
2a=2,\
]

[\
\boxed{a=1}.\
]

**Final Answer:**

The function is continuous at (x=2) when (a=1).

For this value,

[\
\lim\_{x\to2^-}f(x)=3,\
]

[\
\lim\_{x\to2^+}f(x)=3,\
]

and

[\
f(2)=3.\
]

Since the left-hand limit, right-hand limit, and function value are all equal, the function is continuous at (x=2).
