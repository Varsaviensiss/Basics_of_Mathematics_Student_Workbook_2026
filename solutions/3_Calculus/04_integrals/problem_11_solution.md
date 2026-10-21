```

# Problem 11: Choose the Best Integration Method

For each integral, identify the best method and evaluate it.

## 1. Evaluate \(\int \sin(3x)\,dx\)

### Step 1: Choose a Method

The expression inside the sine function is \(3x\). Since its derivative is a constant, use **substitution**.

Let

\[
u=3x
\]

Differentiate:

\[
du=3\,dx
\]

Therefore,

\[
dx=\frac13\,du
\]

### Step 2: Rewrite the Integral

Substitute \(u=3x\) and \(dx=\frac13du\):

\[
\int\sin(3x)\,dx
=\frac13\int\sin u\,du
\]

### Step 3: Integrate

Since

\[
\int\sin u\,du=-\cos u+C
\]

we get

\[
-\frac13\cos u+C
\]

Substitute \(u=3x\) back:

\[
\boxed{-\frac13\cos(3x)+C}
\]

### Verification

Differentiate:

\[
\frac{d}{dx}\left[-\frac13\cos(3x)\right]
=-\frac13[-3\sin(3x)]
=\sin(3x)
\]

The result is correct.

---

## 2. Evaluate \(\int x\ln x\,dx\)

### Step 1: Choose a Method

The integrand is a product of \(x\) and \(\ln x\). Use **integration by parts**.

Recall the formula:

\[
\int u\,dv=uv-\int v\,du
\]

Choose

\[
u=\ln x
\qquad
dv=x\,dx
\]

This choice is useful because differentiating \(\ln x\) simplifies it to \(\frac1x\).

### Step 2: Find \(du\) and \(v\)

Differentiate \(u\):

\[
du=\frac1x\,dx
\]

Integrate \(dv\):

\[
v=\int x\,dx=\frac{x^2}{2}
\]

### Step 3: Apply Integration by Parts

\[
\int x\ln x\,dx
=uv-\int v\,du
\]

Substitute:

\[
=\frac{x^2}{2}\ln x
-\int\frac{x^2}{2}\cdot\frac1x\,dx
\]

Simplify the remaining integrand:

\[
=\frac{x^2}{2}\ln x-\frac12\int x\,dx
\]

### Step 4: Finish Integrating

Since

\[
\int x\,dx=\frac{x^2}{2}
\]

we obtain

\[
\frac{x^2}{2}\ln x-\frac12\left(\frac{x^2}{2}\right)+C
\]

Therefore,

\[
\boxed{\frac{x^2}{2}\ln x-\frac{x^2}{4}+C}
\]

Here, \(x>0\) because \(\ln x\) is defined for positive real \(x\).

### Verification

Differentiate:

\[
\frac{d}{dx}\left(
\frac{x^2}{2}\ln x-\frac{x^2}{4}
\right)
\]

Using the product rule:

\[
=x\ln x+\frac{x^2}{2}\cdot\frac1x-\frac{x}{2}
\]

Simplify:

\[
=x\ln x+\frac{x}{2}-\frac{x}{2}
=x\ln x
\]

The result is correct.

---

## 3. Evaluate \(\int\frac{x}{x^2+1}\,dx\)

### Step 1: Choose a Method

The denominator is \(x^2+1\), whose derivative is \(2x\). The numerator \(x\) is half of that derivative.

Therefore, use **substitution**.

Let

\[
u=x^2+1
\]

Differentiate:

\[
du=2x\,dx
\]

So,

\[
x\,dx=\frac12\,du
\]

### Step 2: Rewrite the Integral

\[
\int\frac{x}{x^2+1}\,dx
=\frac12\int\frac1u\,du
\]

### Step 3: Integrate

Recall the logarithmic integral rule:

\[
\int\frac1u\,du=\ln|u|+C
\]

Therefore,

\[
\frac12\ln|u|+C
\]

Substitute \(u=x^2+1\):

\[
\frac12\ln|x^2+1|+C
\]

Since \(x^2+1>0\) for every real \(x\), the absolute value is unnecessary.

### Final Answer

\[
\boxed{\frac12\ln(x^2+1)+C}
\]

### Verification

Differentiate:

\[
\frac{d}{dx}\left[\frac12\ln(x^2+1)\right]
=\frac12\cdot\frac{2x}{x^2+1}
=\frac{x}{x^2+1}
\]

The result is correct.

---

## Summary: Which Method Should You Use?

| Integral | Best method | Reason |
|---|---|---|
| \(\int\sin(3x)\,dx\) | Substitution | The inside function is \(3x\). |
| \(\int x\ln x\,dx\) | Integration by parts | The integrand is a product of two functions. |
| \(\int\frac{x}{x^2+1}\,dx\) | Substitution | The numerator is proportional to the derivative of the denominator. |

## Key Idea

Before integrating, look at the structure of the expression:

- **Substitution:** Use it when an inside function and its derivative appear together.
- **Integration by parts:** Use it when a product becomes simpler after differentiating one factor.

Choosing the right method often makes the calculation much easier.

```
