# Problem 7: Exponential Growth

Given the exponential growth model

\[
N(t)=N_0e^{kt}, \qquad k>0,
\]

where \(N_0\) is the initial population and \(k\) is the constant growth rate.

## 1. Verify that \(N'(t)=kN(t)\)

Differentiate the model with respect to \(t\):

\[
N(t)=N_0e^{kt}.
\]

Since \(N_0\) is a constant and the derivative of \(e^{kt}\) is \(ke^{kt}\), we obtain

\[
N'(t)=N_0ke^{kt}.
\]

Rearranging gives

\[
N'(t)=kN_0e^{kt}.
\]

Because \(N(t)=N_0e^{kt}\), it follows that

\[
\boxed{N'(t)=kN(t)}.
\]

Therefore, the model satisfies the given differential relation. This means that the population's growth rate is proportional to its current size.

## 2. Find the population doubling time

Let \(T\) represent the doubling time. By definition, the population doubles when

\[
N(T)=2N_0.
\]

Substitute the exponential growth model:

\[
N_0e^{kT}=2N_0.
\]

Assuming \(N_0>0\), divide both sides by \(N_0\):

\[
e^{kT}=2.
\]

Take the natural logarithm of both sides:

\[
\ln(e^{kT})=\ln 2.
\]

Using \(\ln(e^x)=x\), we obtain

\[
kT=\ln 2.
\]

Solving for \(T\) gives

\[
\boxed{T=\frac{\ln 2}{k}}.
\]

Thus, the population doubling time is \(\frac{\ln 2}{k}\) time units.

## 3. Explain why the doubling time does not depend on \(N_0\)

The doubling time is

\[
T=\frac{\ln 2}{k}.
\]

This formula depends only on the growth rate \(k\), not on the initial population \(N_0\).

The initial population cancels when we solve the equation \(N(T)=2N_0\). Therefore, for a fixed positive growth rate, populations with different initial sizes have the same doubling time.

For example, if one population starts at 100 and another starts at 1,000, both populations will double in the same amount of time, provided they have the same growth rate \(k\).

## Final Answer

1. Differentiating \(N(t)=N_0e^{kt}\) gives \(N'(t)=kN(t)\).
2. The population doubling time is

   \[
   \boxed{T=\frac{\ln 2}{k}}.
   \]

3. The doubling time does not depend on \(N_0\) because the initial population cancels when solving \(N(T)=2N_0\). It depends only on the growth rate \(k\).
