# 📘 Solution to Exercise 1: Dominant Terms in a Sequence

---

## 1. Problem Statement

Compute the limit of the rational sequence:

\[
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}
\]

The objectives are:

1. Evaluate the limit algebraically.
2. Explain why the highest-degree terms determine the result as \(n\to\infty\).

---

## 2. Theoretical Background

### 2.1. Limit of a Sequence

A sequence \((a_n)\) converges to a real number \(L\), written

\[
\lim_{n\to\infty}a_n=L,
\]

if for every \(\varepsilon>0\), there exists an integer \(N\) such that

\[
n>N\implies |a_n-L|<\varepsilon.
\]

In other words, the terms of the sequence become arbitrarily close to \(L\) as \(n\) increases.

### 2.2. The Principle of Dominant Terms

For a polynomial

\[
P(n)=a_kn^k+a_{k-1}n^{k-1}+\cdots+a_0,
\]

where \(a_k\neq0\), the leading term \(a_kn^k\) dominates the polynomial for large \(n\).

For any lower-degree term \(a_jn^j\), where \(j<k\),

\[
\lim_{n\to\infty}\frac{a_jn^j}{a_kn^k}
=
\frac{a_j}{a_k}
\lim_{n\to\infty}\frac{1}{n^{k-j}}
=0.
\]

Thus, every lower-degree term becomes negligible relative to the leading term.

### 2.3. Limit of a Rational Sequence

If the numerator and denominator are polynomials of the same degree, then

\[
\lim_{n\to\infty}
\frac{a_kn^k+\cdots+a_0}
{b_kn^k+\cdots+b_0}
=
\frac{a_k}{b_k},
\]

provided \(b_k\neq0\).

---

## 3. Detailed Step-by-Step Solution

### Step 1: Identify the Dominant Terms

Consider the sequence

\[
a_n=\frac{4n^2-3n+1}{2n^2+5n-7}.
\]

| Component | Leading term | Degree | Leading coefficient |
|:---|:---:|:---:|:---:|
| Numerator | \(4n^2\) | \(2\) | \(4\) |
| Denominator | \(2n^2\) | \(2\) | \(2\) |

Both polynomials have degree \(2\). Therefore, their leading terms determine the limit.

### Step 2: Divide by the Highest Power of \(n\)

Divide the numerator and denominator by \(n^2\):

\[
a_n=
\frac{4n^2-3n+1}{2n^2+5n-7}
\]

\[
=
\frac{4-\frac{3}{n}+\frac{1}{n^2}}
{2+\frac{5}{n}-\frac{7}{n^2}}.
\]

This transformation makes the behavior of the lower-degree terms explicit.

### Step 3: Evaluate the Individual Limits

As \(n\to\infty\),

\[
\lim_{n\to\infty}\frac{1}{n}=0,
\qquad
\lim_{n\to\infty}\frac{1}{n^2}=0.
\]

Consequently, the numerator approaches

\[
\lim_{n\to\infty}
\left(4-\frac{3}{n}+\frac{1}{n^2}\right)=4,
\]

while the denominator approaches

\[
\lim_{n\to\infty}
\left(2+\frac{5}{n}-\frac{7}{n^2}\right)=2.
\]

### Step 4: Apply the Quotient Rule

Since the denominator approaches \(2\neq0\), the quotient rule for limits gives

\[
\lim_{n\to\infty}a_n=\frac{4}{2}.
\]

Therefore,

\[
\boxed{\displaystyle
\lim_{n\to\infty}
\frac{4n^2-3n+1}{2n^2+5n-7}=2
}
\]

---

## 4. Why Do the Highest-Degree Terms Dominate?

### 4.1. Relative Growth Rate

The quadratic term \(n^2\) grows faster than the linear term \(n\) and any constant.

For example, when \(n=1000\),

\[
n^2=1{,}000{,}000,
\qquad n=1000.
\]

The numerator becomes

\[
4n^2-3n+1=3{,}997{,}001.
\]

The leading term \(4n^2\) is much larger in magnitude than the lower-degree contribution \(-3n+1\).

### 4.2. Vanishing Relative Contributions

Dividing by \(n^2\) gives

\[
\frac{-3n}{n^2}=-\frac{3}{n}\to0,
\]

\[
\frac{1}{n^2}\to0,
\qquad
\frac{5n}{n^2}=\frac{5}{n}\to0,
\qquad
\frac{-7}{n^2}\to0.
\]

All lower-degree contributions vanish in the limit. Only the leading coefficients, \(4\) and \(2\), remain.

### 4.3. Asymptotic Equivalence

We can express the dominant behavior as

\[
4n^2-3n+1\sim4n^2
\]

and

\[
2n^2+5n-7\sim2n^2
\]

as \(n\to\infty\).

Therefore,

\[
\lim_{n\to\infty}
\frac{4n^2-3n+1}{2n^2+5n-7}
=
\lim_{n\to\infty}\frac{4n^2}{2n^2}
=\frac42=2.
\]

Here, \(\sim\) means that the ratio of the two expressions approaches \(1\).

---

## 5. Numerical Verification

The following values illustrate how the sequence approaches its limit.

| \(n\) | \(a_n\) | Approximate value |
|---:|---|---:|
| \(10\) | \(\frac{371}{243}\) | \(1.52675\) |
| \(100\) | \(\frac{39701}{20493}\) | \(1.93730\) |
| \(1000\) | \(\frac{3997001}{2004993}\) | \(1.99352\) |
| \(10000\) | \(\frac{399970001}{200049993}\) | \(1.99935\) |

The numerical values approach \(2\), which agrees with the algebraic result.

---

## 6. Additional Verification: Difference from the Limit

We can verify convergence by calculating \(a_n-2\):

\[
a_n-2=
\frac{4n^2-3n+1}{2n^2+5n-7}-2.
\]

Combining the fractions gives

\[
a_n-2=
\frac{4n^2-3n+1-2(2n^2+5n-7)}
{2n^2+5n-7}.
\]

Simplifying,

\[
a_n-2=\frac{-13n+15}{2n^2+5n-7}.
\]

Divide the numerator and denominator by \(n^2\):

\[
a_n-2=
\frac{-\frac{13}{n}+\frac{15}{n^2}}
{2+\frac{5}{n}-\frac{7}{n^2}}.
\]

As \(n\to\infty\), the numerator approaches \(0\) and the denominator approaches \(2\). Hence,

\[
\boxed{\lim_{n\to\infty}(a_n-2)=0}.
\]

This independently confirms that \(a_n\to2\).

Moreover, the difference is of order \(O(1/n)\), meaning that its magnitude is bounded by a constant multiple of \(1/n\) for sufficiently large \(n\).

---

## 7. Final Conclusion

The limit is

\[
\boxed{\displaystyle
\lim_{n\to\infty}
\frac{4n^2-3n+1}{2n^2+5n-7}=2
}
\]

The numerator and denominator have the same degree, so the limit equals the ratio of their leading coefficients:

\[
\boxed{\frac{4}{2}=2}.
\]

**Key takeaway:** When evaluating the limit of a rational sequence whose numerator and denominator have the same degree, divide by the highest power of \(n\). The lower-degree terms tend to zero, leaving the ratio of the leading coefficients.

---

*📚 Topic: Calculus · Limits of Sequences · Dominant Terms · Asymptotic Behavior*
