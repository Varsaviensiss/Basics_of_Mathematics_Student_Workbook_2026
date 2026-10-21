# Exercise 6. From a Sequence to a Function — Limit at Infinity

We need to compute

[\
L=\lim\_{x\to\infty}\frac{3x^2-x+15}{5x^2+4x-2}.\
]

**Step 1: Identify the highest power**

The highest power of (x) in both the numerator and denominator is (x^2).

**Step 2: Divide every term by (x^2)**

[\
L=\lim\_{x\to\infty}\
\frac{\frac{3x^2}{x^2}-\frac{x}{x^2}+\frac{15}{x^2}}\
{\frac{5x^2}{x^2}+\frac{4x}{x^2}-\frac{2}{x^2}}.\
]

Simplifying gives

[\
L=\lim\_{x\to\infty}\
\frac{3-\frac1x+\frac{15}{x^2}}\
{5+\frac4x-\frac{2}{x^2}}.\
]

**Step 3: Apply the limit**

As (x\to\infty),

[\
\frac1x\to0,\qquad \frac1{x^2}\to0.\
]

Therefore,

[\
L=\frac{3-0+0}{5+0-0}.\
]

Hence,

[\
\boxed{L=\frac35}\
]

**Comparison with Exercise 1**

The method is the same as in Exercise 1. In both problems, we divide the numerator and denominator by the highest power of the variable. The terms with lower powers approach zero, so only the leading coefficients determine the limit.

The difference is that Exercise 1 deals with a sequence, where (n) takes positive integer values. Here, (x) is a real variable and can take any real value while approaching infinity.

**Conclusion:** The technique stays the same, but the variable changes from integer values (n) to real values (x).
