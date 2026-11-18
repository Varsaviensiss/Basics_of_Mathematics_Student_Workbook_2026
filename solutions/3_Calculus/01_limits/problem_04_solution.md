# Exercise 4. Analyze the Sequences

## Question

Determine whether each sequence converges or diverges. If it converges, find its limit. If it diverges, explain whether it grows without bound or oscillates. Justify each answer.

1. $\left(\frac{2}{3}\right)^n$
2. $\left(\frac{3}{2}\right)^n$
3. $(-1)^n$
4. $\frac{(-1)^n}{n}$

## Solution

### 1. $\left(\frac{2}{3}\right)^n$

Since $0<\frac{2}{3}<1$, the terms of this geometric sequence approach zero:

$$
\boxed{\lim_{n\to\infty}\left(\frac{2}{3}\right)^n=0}.
$$

### 2. $\left(\frac{3}{2}\right)^n$

Since $\frac{3}{2}>1$, the terms of this geometric sequence grow without bound:

$$
\boxed{\lim_{n\to\infty}\left(\frac{3}{2}\right)^n=+\infty}.
$$

### 3. $(-1)^n$

The even-indexed terms are all $1$, and the odd-indexed terms are all $-1$. These two subsequences have different limits, so $(-1)^n$ oscillates and its limit does not exist.

### 4. $\frac{(-1)^n}{n}$

Since $-1\leq(-1)^n\leq1$, for every $n\geq1$ we have

$$
-\frac{1}{n}\leq\frac{(-1)^n}{n}\leq\frac{1}{n}.
$$

Both bounds approach zero as $n\to\infty$. By the Squeeze Theorem,

$$
\boxed{\lim_{n\to\infty}\frac{(-1)^n}{n}=0}.
$$
