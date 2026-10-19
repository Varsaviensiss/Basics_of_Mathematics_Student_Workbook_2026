# 📘 Calculus — Exercise 1
## Dominant Terms in a Sequence

---

### 🎯 Objective

Compute the limit

\[
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}
\]

and explain why the highest-degree terms determine the result as \(n\to\infty\).

---

## 🔹 Step 1 — Identify the Dominant Terms

Consider the numerator and denominator:

\[
\frac{4n^2-3n+1}{2n^2+5n-7}
\]

The highest-degree term in the numerator is \(4n^2\), while the highest-degree term in the denominator is \(2n^2\).

As \(n\) becomes very large, the quadratic terms grow much faster than the linear and constant terms.

| Expression | Highest-degree term | Lower-order terms |
|:---|:---:|:---|
| Numerator | \(4n^2\) | \(-3n+1\) |
| Denominator | \(2n^2\) | \(5n-7\) |

Therefore, the dominant terms are \(4n^2\) and \(2n^2\).

---

## 🔹 Step 2 — Divide by the Highest Power

The highest power of \(n\) in the expression is \(n^2\).

Divide both the numerator and denominator by \(n^2\):

\[
\lim_{n\to\infty}
\frac{4n^2-3n+1}{2n^2+5n-7}
\]

\[
=
\lim_{n\to\infty}
\frac{4-\frac{3}{n}+\frac{1}{n^2}}
{2+\frac{5}{n}-\frac{7}{n^2}}
\]

This form makes the behavior of each term as \(n\to\infty\) clear.

---

## 🔹 Step 3 — Evaluate the Limit

As \(n\to\infty\),

\[
\frac{1}{n}\to0
\qquad\text{and}\qquad
\frac{1}{n^2}\to0
\]

Substituting these limits gives

\[
\lim_{n\to\infty}
\frac{4-\frac{3}{n}+\frac{1}{n^2}}
{2+\frac{5}{n}-\frac{7}{n^2}}
=
\frac{4-0+0}{2+0-0}
\]

Therefore,

\[
\boxed{\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}=2}
\]

---

## 📊 Step 4 — Why Do the Highest-Degree Terms Dominate?

When \(n\) becomes large, the lower-order terms become insignificant compared with \(n^2\).

For example,

\[
\frac{-3n}{n^2}=-\frac{3}{n}\to0
\]

and

\[
\frac{5n}{n^2}=\frac{5}{n}\to0
\]

The constant terms also vanish after division by \(n^2\):

\[
\frac{1}{n^2}\to0,
\qquad
\frac{-7}{n^2}\to0
\]

Consequently, only the leading coefficients remain relevant to the limit.

In general, if the numerator and denominator are polynomials of the same degree, the limit at infinity equals the ratio of their leading coefficients, provided the denominator's leading coefficient is nonzero.

For this exercise,

\[
\frac{\text{leading coefficient of numerator}}
{\text{leading coefficient of denominator}}
=
\frac42=2
\]

---

## 🏆 Final Conclusion

The limit is

\[
\boxed{2}
\]

**Key takeaway:** For rational expressions with numerator and denominator of the same degree, the highest-degree terms determine the limit at infinity. Lower-order terms become negligible as \(n\) grows without bound.

---

*📚 Topic: Calculus · Limits of Sequences · Dominant Terms · Limits at Infinity*
