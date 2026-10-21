# Exercise 14. A (0/0) Limit with Trigonometry

We need to compute

[\
L=\lim\_{x\to0}\frac{1-\cos x}{x^2}.\
]

We will use a trigonometric identity and the fundamental trigonometric limit, without using l'Hôpital's rule.

**Step 1: Use a trigonometric identity**

Recall the identity

[\
1-\cos x=2\sin^2\frac{x}{2}.\
]

Substituting this into the limit gives

[\
L=\lim\_{x\to0}\frac{2\sin^2(x/2)}{x^2}.\
]

**Step 2: Rewrite the expression**

Since (x^2=4\left(\frac{x}{2}\right)^2), we obtain

[\
L=\lim\_{x\to0}\
\frac{2\sin^2(x/2)}\
{4(x/2)^2}.\
]

Simplifying,

[\
L=\frac12\lim\_{x\to0}\
\left(\frac{\sin(x/2)}{x/2}\right)^2.\
]

**Step 3: Apply the fundamental trigonometric limit**

We know that

[\
\lim\_{u\to0}\frac{\sin u}{u}=1.\
]

Let (u=\frac{x}{2}). As (x\to0), (u\to0). Therefore,

[\
L=\frac12(1)^2.\
]

**Final Answer:**

[\
\boxed{\lim\_{x\to0}\frac{1-\cos x}{x^2}=\frac12}\
]

**Explanation:**

We used the identity (1-\cos x=2\sin^2(x/2)) to transform the original expression into the standard trigonometric limit. Since (\frac{\sin u}{u}\to1) as (u\to0), the result is (\frac12). No use of l'Hôpital's rule is necessary.
