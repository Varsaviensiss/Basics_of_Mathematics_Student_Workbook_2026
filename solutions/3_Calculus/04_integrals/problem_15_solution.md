```

# Problem 15: Find a Function Using Its Derivative and an Initial Condition

Given:

\[
F'(x)=2xe^{x^2}
\]

and

\[
F(0)=3
\]

Find \(F(x)\).

## Step 1: Understand the Problem

We know the derivative \(F'(x)\), and we are given the value of the original function at \(x=0\).

To find \(F(x)\), we need to:

1. Integrate \(F'(x)\) to find the general antiderivative.
2. Use the initial condition \(F(0)=3\) to determine the constant \(C\).

## Step 2: Integrate the Derivative

Since

\[
F'(x)=2xe^{x^2}
\]

we have

\[
F(x)=\int 2xe^{x^2}\,dx
\]

The exponent contains \(x^2\), whose derivative is \(2x\). This suggests using **substitution**.

Let

\[
u=x^2
\]

Differentiate:

\[
du=2x\,dx
\]

## Step 3: Rewrite the Integral

Substitute \(u=x^2\) and \(du=2x\,dx\):

\[
F(x)=\int e^u\,du
\]

Since

\[
\int e^u\,du=e^u+C
\]

we obtain

\[
F(x)=e^u+C
\]

Substitute \(u=x^2\) back:

\[
\boxed{F(x)=e^{x^2}+C}
\]

This is the general antiderivative. We still need to find \(C\).

## Step 4: Use the Initial Condition

We are given

\[
F(0)=3
\]

Substitute \(x=0\) into the general solution:

\[
F(0)=e^{0^2}+C
\]

Since \(e^0=1\),

\[
1+C=3
\]

Solve for \(C\):

\[
C=3-1
\]

Therefore,

\[
\boxed{C=2}
\]

## Step 5: Write the Particular Solution

Substitute \(C=2\) into the general solution:

\[
F(x)=e^{x^2}+2
\]

## Final Answer

\[
\boxed{F(x)=e^{x^2}+2}
\]

## Step 6: Verify the Answer

We must check both the derivative and the initial condition.

### Check the derivative

Differentiate:

\[
\frac{d}{dx}\left(e^{x^2}+2\right)
\]

Using the chain rule:

\[
=e^{x^2}\cdot 2x
\]

Therefore,

\[
F'(x)=2xe^{x^2}
\]

This matches the given derivative.

### Check the initial condition

Substitute \(x=0\):

\[
F(0)=e^{0^2}+2
\]

\[
=1+2=3
\]

This matches the given condition \(F(0)=3\).

Both conditions are satisfied, so the solution is correct.

## Key Idea

When a problem gives both a derivative and an initial condition:

- **Integrate** to find the general antiderivative, including \(C\).
- **Substitute the initial value** to determine \(C\).
- **Verify** both the derivative and the initial condition.

The initial condition selects one specific function from the family of antiderivatives.

```
