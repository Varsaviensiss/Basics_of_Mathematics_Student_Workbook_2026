# Exercise 2. Different Growth Rates

## Given

Compute the following limits and compare the results.

[\
L_1=\lim\_{n\to\infty}\frac{3n+1}{n^2+4}\
]

[\
L_2=\lim\_{n\to\infty}\frac{2n^3-n}{5n^2+1}\
]

## 1. Compute the First Limit

[\
L_1=\lim\_{n\to\infty}\frac{3n+1}{n^2+4}\
]

The numerator is a polynomial of degree (1), while the denominator is a polynomial of degree (2).

Divide every term in the numerator and denominator by (n^2):

[\
L_1=\lim\_{n\to\infty}\
\frac{\frac{3}{n}+\frac{1}{n^2}}\
{1+\frac{4}{n^2}}\
]

As (n\to\infty),

[\
\frac1n\to0,\qquad \frac1{n^2}\to0\
]

Therefore,

[\
L_1=\frac{0+0}{1+0}=0\
]

Hence,

[\
\boxed{L_1=0}\
]

The denominator grows faster than the numerator, so the fraction approaches zero.

## 2. Compute the Second Limit

[\
L_2=\lim\_{n\to\infty}\frac{2n^3-n}{5n^2+1}\
]

The numerator has degree (3), while the denominator has degree (2).

Divide every term in the numerator and denominator by (n^2):

[\
L_2=\lim\_{n\to\infty}\
\frac{2n-\frac1n}{5+\frac1{n^2}}\
]

As (n\to\infty),

[\
2n-\frac1n\to+\infty\
]

and

[\
5+\frac1{n^2}\to5\
]

Since the numerator approaches positive infinity and the denominator approaches the positive number (5),

[\
\boxed{L_2=+\infty}\
]

Thus, the second sequence grows without bound.

## 3. Compare the Two Limits

The results are different because the degrees of the numerator and denominator are different.

- **First limit:** The numerator has a lower degree than the denominator. Therefore, the limit is (0).
- **Second limit:** The numerator has a higher degree than the denominator. Since the leading coefficients are positive, the limit is (+\infty).

In general, for a ratio of polynomials:

1. If the numerator has a lower degree than the denominator, the limit is (0).
2. If both polynomials have the same degree, the limit is the ratio of their leading coefficients.
3. If the numerator has a higher degree than the denominator, the magnitude of the ratio grows without bound. The signs of the leading terms determine whether the limit is (+\infty) or (-\infty).

## Final Answer

[\
\boxed{\displaystyle\lim\_{n\to\infty}\frac{3n+1}{n^2+4}=0}\
]

[\
\boxed{\displaystyle\lim\_{n\to\infty}\frac{2n^3-n}{5n^2+1}=+\infty}\
]

The degree of the numerator relative to the degree of the denominator determines the limiting behaviour of these polynomial ratios.

Add a quick numerical checkMake the comparison more concise
