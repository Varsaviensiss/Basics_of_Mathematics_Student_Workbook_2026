# Problem 7: Exponential Growth

Given the exponential growth model

\[
N(t)=N_0e^{kt}, \qquad k>0.
\]

### 1. Verify that \(N'(t)=kN(t)\)

Differentiate the function:

\[
N'(t)=N_0ke^{kt}.
\]

Since \(N(t)=N_0e^{kt}\), we obtain

\[
\boxed{N'(t)=kN(t)}.
\]

Therefore, the model satisfies the given relation.

### 2. Find the population doubling time

Let \(T\) be the doubling time. Then

\[
N(T)=2N_0.
\]

Substitute the model:

\[
N_0e^{kT}=2N_0.
\]

Divide both sides by \(N_0\):

\[
e^{kT}=2.
\]

Taking the natural logarithm of both sides gives

\[
kT=\ln 2.
\]

Solving for \(T\):

\[
\boxed{T=\frac{\ln 2}{k}}.
\]

Thus, the population doubling time is \(\frac{\ln 2}{k}\).

### 3. Explain why the doubling time does not depend on \(N_0\)

The doubling time is

\[
T=\frac{\ln 2}{k}.
\]

This formula depends only on the growth rate \(k\), not on the initial population \(N_0\). The initial population cancels when solving \(N(T)=2N_0\).

Therefore, populations with different initial sizes have the same doubling time if they have the same growth rate.

### Final Answer

\[
\boxed{N'(t)=kN(t)}, \qquad
\boxed{T=\frac{\ln 2}{k}}.
\]

The doubling time depends only on \(k\) and is independent of \(N_0\).
