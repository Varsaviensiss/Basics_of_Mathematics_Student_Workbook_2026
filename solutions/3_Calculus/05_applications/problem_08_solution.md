# Problem 8. Number of Requests Handled by a Server

## Question

During the first five minutes, requests arrive at a server at the rate

$$
r(t)=100+20t,\qquad 0\le t\le5,
$$

where $t$ is measured in minutes and $r(t)$ in requests per minute.

1. Compute the total number of requests during the first five minutes.
2. Compute the average arrival rate over this interval.
3. Compare the average rate with the rates at the beginning and end of the interval.

## Solution

### 1. Compute the total number of requests

Integrating the arrival rate over the first five minutes gives

$$
N=\int_0^5r(t)\,dt
=\int_0^5(100+20t)\,dt
=\left[100t+10t^2\right]_0^5
=500+250
=750\ \text{requests}.
$$

### 2. Compute the average rate

Divide the total number of requests by the length of the interval:

$$
r_{\mathrm{avg}}=\frac{1}{5-0}\int_0^5r(t)\,dt
=\frac{750}{5}
=150\ \text{requests/min}.
$$

### 3. Compare with the endpoint rates

The rate starts at $r(0)=100$ requests per minute and ends at $r(5)=200$ requests per minute. Since the rate increases linearly, its time average is exactly halfway between the endpoint rates:

$$
r_{\mathrm{avg}}=\frac{r(0)+r(5)}{2}
=\frac{100+200}{2}
=150\ \text{requests/min}.
$$
