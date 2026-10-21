```

# Problem 9: Evaluate the Definite Integral

Evaluate:

\[
\int_{-1}^{2} 2x\,dx
\]

## Step 1: Find the Antiderivative

We know that

\[
\int 2x\,dx=x^2+C
\]

Therefore, an antiderivative is

\[
F(x)=x^2
\]

## Step 2: Apply the Fundamental Theorem of Calculus

For a definite integral,

\[
\int_a^b f(x)\,dx=F(b)-F(a)
\]

Using the limits \(a=-1\) and \(b=2\):

\[
\int_{-1}^{2}2x\,dx
=\left[x^2\right]_{-1}^{2}
\]

Evaluate at the upper limit and subtract the value at the lower limit:

\[
=2^2-(-1)^2
\]

\[
=4-1
\]

## Final Answer

\[
\boxed{3}
\]

## Step 3: Understand the Geometric Meaning

The graph of \(y=2x\) is a straight line passing through the origin.

- From \(x=-1\) to \(x=0\), the graph is below the \(x\)-axis.
- From \(x=0\) to \(x=2\), the graph is above the \(x\)-axis.

A definite integral measures **signed area**: areas above the \(x\)-axis count as positive, while areas below it count as negative.

### Area from \(x=-1\) to \(x=0\)

This region is a triangle with base \(1\) and height \(2\).

\[
A_1=\frac12(1)(2)=1
\]

Because it lies below the \(x\)-axis, its signed contribution is \(-1\).

### Area from \(x=0\) to \(x=2\)

This region is a triangle with base \(2\) and height \(4\).

\[
A_2=\frac12(2)(4)=4
\]

Because it lies above the \(x\)-axis, its contribution is \(+4\).

The net signed area is

\[
-1+4=3
\]

This agrees with our calculation.

## Key Idea

A definite integral gives the **net signed area**, not necessarily the total geometric area.

For this problem:

\[
\text{Net signed area}=4-1=\boxed{3}
\]

The total geometric area, counting both regions as positive, would instead be \(4+1=5\).

```
