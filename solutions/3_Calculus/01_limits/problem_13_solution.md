# Exercise 13. Fundamental Trigonometric Limit

We use the fundamental trigonometric limit

[\
\lim\_{x\to0}\frac{\sin x}{x}=1.\
]

## 1. Compute (\displaystyle\lim\_{x\to0}\frac{\sin 5x}{x})

**Step 1: Rewrite the expression**

Multiply and divide by (5):

[\
\lim\_{x\to0}\frac{\sin 5x}{x}\
\=5\lim\_{x\to0}\frac{\sin 5x}{5x}.\
]

**Step 2: Apply the fundamental limit**

As (x\to0), we have (5x\to0). Therefore,

[\
\lim\_{x\to0}\frac{\sin 5x}{5x}=1.\
]

Thus,

[\
L=5\cdot1.\
]

**Answer:**

[\
\boxed{\lim\_{x\to0}\frac{\sin 5x}{x}=5}\
]

## 2. Compute (\displaystyle\lim\_{x\to0}\frac{\sin 2x}{\sin 3x})

**Step 1: Rewrite the expression**

Multiply and divide by (2x) in the numerator and by (3x) in the denominator:

[\
L=\lim\_{x\to0}\
\frac{\sin 2x}{2x}\
\cdot\
\frac{3x}{\sin 3x}\
\cdot\frac23.\
]

Rearranging gives

[\
L=\frac23\
\lim\_{x\to0}\frac{\sin 2x}{2x}\
\cdot\
\lim\_{x\to0}\frac{3x}{\sin 3x}.\
]

**Step 2: Apply the fundamental limit**

Since (2x\to0) and (3x\to0),

[\
\lim\_{x\to0}\frac{\sin 2x}{2x}=1\
]

and

[\
\lim\_{x\to0}\frac{3x}{\sin 3x}=1.\
]

Therefore,

[\
L=\frac23\cdot1\cdot1.\
]

**Answer:**

[\
\boxed{\lim\_{x\to0}\frac{\sin 2x}{\sin 3x}=\frac23}\
]

## Conclusion

Both limits are calculated using the fundamental trigonometric limit. The key is to rewrite each expression so that it contains the standard form (\frac{\sin u}{u}), whose limit is (1) as (u\to0).
