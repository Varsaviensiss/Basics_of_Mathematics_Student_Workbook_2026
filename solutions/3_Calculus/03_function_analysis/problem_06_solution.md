```

# Problem 6. A Logarithmic Function

Analyze the domain, zero, and monotonicity of

\[
f(x)=\ln x-x+1
\]

Explain why the analysis must begin with the domain.

## 1. Find the Domain

The natural logarithm \(\ln x\) is defined only for \(x>0\).

Therefore, the domain is

\[
\boxed{D_f=(0,\infty)}
\]

We must begin with the domain because the function and its derivative are only considered where the function is defined. In particular, \(x=0\) and negative values of \(x\) are not allowed.

## 2. Find the Zero

Set \(f(x)=0\):

\[
\ln x-x+1=0
\]

Rearrange:

\[
\ln x=x-1
\]

We can see that \(x=1\) is a solution because

\[
\ln 1-1+1=0
\]

To prove that it is the only zero, we analyze the derivative.

## 3. Find the Derivative

Differentiate the function:

\[
f'(x)=\frac{1}{x}-1
\]

Simplify:

\[
f'(x)=\frac{1-x}{x}
\]

Since \(x>0\) throughout the domain, the denominator is always positive. Therefore, the sign of \(f'(x)\) depends only on \(1-x\).

Set the derivative equal to zero:

\[
\frac{1-x}{x}=0
\]

\[
1-x=0
\]

\[
x=1
\]

The only critical point in the domain is \(x=1\).

## 4. Determine the Monotonicity

Study the sign of \(f'(x)\) on the intervals determined by \(x=1\).

**For \(0<x<1\):**

\[
1-x>0 \implies f'(x)>0
\]

Therefore, \(f\) is increasing on \((0,1)\).

**For \(x>1\):**

\[
1-x<0 \implies f'(x)<0
\]

Therefore, \(f\) is decreasing on \((1,\infty)\).

At \(x=1\):

\[
f(1)=\ln 1-1+1=0
\]

The function changes from increasing to decreasing, so it has a global maximum at \((1,0)\).

## 5. Prove That the Zero Is Unique

We found that

\[
f(1)=0
\]

Since \(f\) is strictly increasing on \((0,1)\) and strictly decreasing on \((1,\infty)\), and its maximum value is \(0\), we have

\[
f(x)<0 \qquad \text{for all }x\ne1,\ x>0
\]

Thus, \(x=1\) is the unique zero of the function.

## Final Answers

1. **Domain:**

\[
\boxed{(0,\infty)}
\]

2. **Unique zero:**

\[
\boxed{x=1}
\]

3. **Increasing interval:**

\[
\boxed{(0,1)}
\]

4. **Decreasing interval:**

\[
\boxed{(1,\infty)}
\]

5. **Global maximum:**

\[
\boxed{f(1)=0}
\]

6. **Why begin with the domain?**

The domain identifies where the function is defined and where its derivative can be analyzed. Because \(\ln x\) requires \(x>0\), all calculations and monotonicity intervals must be restricted to \((0,\infty)\).

```
