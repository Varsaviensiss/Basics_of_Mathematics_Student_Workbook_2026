
# Problem 8. Number of Requests Handled by a Server

The arrival rate during the first 5 minutes is

\[
r(t)=100+20t,\qquad 0\le t\le5
\]

where \(r(t)\) is measured in requests per minute.

## 1. Compute the Total Number of Requests

The total number of requests is the integral of the arrival rate:

\[
N=\int_0^5 r(t)\,dt
\]

Substitute the given function:

\[
N=\int_0^5(100+20t)\,dt
\]

Integrate:

\[
N=\left[100t+10t^2\right]_0^5
\]

Evaluate the limits:

\[
N=(100\cdot5+10\cdot25)-0
\]

\[
N=500+250=750
\]

Therefore, the total number of requests is

\[
\boxed{N=750\text{ requests}}
\]

## 2. Compute the Average Rate

The average rate over an interval is the total number of requests divided by the interval length:

\[
r_{\text{avg}}=\frac{1}{5-0}\int_0^5r(t)\,dt
\]

Using the result from Part 1:

\[
r_{\text{avg}}=\frac{750}{5}
\]

\[
\boxed{r_{\text{avg}}=150\text{ requests/min}}
\]

## 3. Compare the Average Rate with the Endpoint Values

At the beginning:

\[
r(0)=100+20(0)=100
\]

At the end:

\[
r(5)=100+20(5)=200
\]

Therefore,

\[
r(0)=100,\qquad r_{\text{avg}}=150,\qquad r(5)=200
\]

The average rate is exactly halfway between the endpoint values because the rate increases linearly.

## Final Answers

1. Total requests: \(\boxed{750}\).
2. Average rate: \(\boxed{150\text{ requests/min}}\).
3. Initial rate: \(100\text{ requests/min}\).
4. Final rate: \(200\text{ requests/min}\).
