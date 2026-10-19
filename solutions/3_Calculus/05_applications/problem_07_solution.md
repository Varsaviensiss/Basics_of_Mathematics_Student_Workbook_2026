# Problem 7: Exponential Growth

Given the exponential growth model

\[
N(t)=N_0e^{kt}, \qquad k>0.
\]

## 1. Verify that \(N'(t)=kN(t)\)

Starting with

\[
N(t)=N_0e^{kt},
\]

differentiate with respect to \(t\):

\[
N'(t)=N_0\frac{d}{dt}(e^{kt}).
\]

Using the chain rule,

\[
\frac{d}{dt}(e^{kt})=ke^{kt}.
\]

Therefore,

\[
N'(t)=N_0ke^{kt}.
\]

Rearranging,

\[
N'(t)=k(N_0e^{kt}).
\]

Since \(N(t)=N_0e^{kt}\),

\[
\boxed{N'(t)=kN(t)}.
\]

Thus, the model satisfies the given relation.

## 2. Find the population doubling time

Let \(T\) be the time required for the population to double.

At the doubling time,

\[
N(T)=2N_0.
\]

Using the given model,

\[
N_0e^{kT}=2N_0.
\]

Divide both sides by \(N_0\):

\[
\frac{N_0e^{kT}}{N_0}=\frac{2N_0}{N_0}.
\]

Simplifying,

\[
e^{kT}=2.
\]

Take the natural logarithm of both sides:

\[
\ln(e^{kT})=\ln 2.
\]

Using \(\ln(e^x)=x\),

\[
kT=\ln 2.
\]

Divide both sides by \(k\):

\[
T=\frac{\ln 2}{k}.
\]

Therefore, the population doubling time is

\[
\boxed{T=\frac{\ln 2}{k}}.
\]

## 3. Explain why the doubling time does not depend on \(N_0\)

From Part 2, the doubling time is

\[
T=\frac{\ln 2}{k}.
\]

The formula contains only the growth rate \(k\) and the constant \(\ln 2\). The initial population \(N_0\) does not appear in the formula because it cancels when we solve

\[
N_0e^{kT}=2N_0.
\]

Therefore, the doubling time is independent of the initial population. Any two populations with the same growth rate \(k\) will have the same doubling time, even if their initial sizes are different.
