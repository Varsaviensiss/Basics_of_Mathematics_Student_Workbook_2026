# Exercise 4. Analyze the Sequences

**1.** (\displaystyle \lim\_{n\to\infty}\left(\frac{2}{3}\right)^n)

Since (0<\frac{2}{3}<1), each term becomes smaller as (n) increases. Therefore, the sequence approaches zero.

[\
\boxed{\lim\_{n\to\infty}\left(\frac{2}{3}\right)^n=0}\
]

**2.** (\displaystyle \lim\_{n\to\infty}\left(\frac{3}{2}\right)^n)

Since (\frac{3}{2}>1), the terms become larger as (n) increases. Therefore, the sequence grows without bound.

[\
\boxed{\lim\_{n\to\infty}\left(\frac{3}{2}\right)^n=+\infty}\
]

**3.** (\displaystyle \lim\_{n\to\infty}(-1)^n)

The sequence alternates between (1) and (-1).

For even values of (n), ((-1)^n=1).

For odd values of (n), ((-1)^n=-1).

Since the sequence does not approach a single value, the limit does not exist.

[\
\boxed{\lim\_{n\to\infty}(-1)^n\text{ does not exist}}\
]

**4.** (\displaystyle \lim\_{n\to\infty}\frac{(-1)^n}{n})

Since ((-1)^n) alternates between (1) and (-1), the numerator remains bounded. Meanwhile, the denominator (n) increases without bound.

We can also use the inequality

[\
-\frac{1}{n}\leq\frac{(-1)^n}{n}\leq\frac{1}{n}.\
]

As (n\to\infty),

[\
\lim\_{n\to\infty}-\frac{1}{n}=0\
\quad\text{and}\quad\
\lim\_{n\to\infty}\frac{1}{n}=0.\
]

By the Squeeze Theorem, the limit is zero.

[\
\boxed{\lim\_{n\to\infty}\frac{(-1)^n}{n}=0}\
]
