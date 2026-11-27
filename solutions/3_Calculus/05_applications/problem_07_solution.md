# Problem 7. Exponential Growth

## Question

A population is described by the exponential growth model

$$
N(t)=N_0e^{kt},\qquad N_0>0,\quad k>0.
$$

1. Verify that $N'(t)=kN(t)$.
2. Find the population doubling time.
3. Explain why the doubling time does not depend on the initial population $N_0$.

## Solution

### 1. Verify the growth equation

By the chain rule,

$$
N'(t)=N_0ke^{kt}=k(N_0e^{kt})=kN(t).
$$

### 2. Find the doubling time

Let $T$ be the time required for the population to grow from $N_0$ to $2N_0$. Then

$$
N(T)=N_0e^{kT}=2N_0.
$$

Since $N_0>0$, we can divide both sides by $N_0$ to obtain $e^{kT}=2$. Taking the natural logarithm gives $kT=\ln 2$. Therefore,

$$
T=\frac{\ln 2}{k}.
$$

### 3. Explain why the doubling time is independent of $N_0$

The initial population cancels because doubling is defined by the ratio $N(T)/N_0=2$. That ratio equals $e^{kT}$, so the doubling time depends only on the growth rate $k$. Any two positive populations with the same growth rate have the same doubling time.
