# Problem 5: Distance from Velocity

## Given

The velocity of a car during the first five seconds is described by

$$
v(t)=4t+2 \quad [\mathrm{m/s}]
$$

The time interval is

$$
0\leq t\leq5
$$

We need to calculate the distance traveled and explain the relationship between the integral of velocity and the change in position.

## 1. Compute the distance traveled

Distance traveled can be calculated by integrating the speed over the time interval.

Since the velocity function is

$$
v(t)=4t+2
$$

and \(v(t)>0\) for every \(t\in[0,5]\), the car always moves in the positive direction. Therefore, its speed equals its velocity, and the distance traveled is

$$
D=\int_0^5 v(t)\,dt
$$

Substituting the velocity function gives

$$
D=\int_0^5(4t+2)\,dt
$$

Integrating term by term,

$$
D=\left[2t^2+2t\right]_0^5
$$

Evaluating at the limits,

$$
D=(2(5)^2+2(5))-(2(0)^2+2(0))
$$

$$
D=50+10
$$

Therefore, the total distance traveled is

$$
\boxed{D=60\text{ m}}
$$

## 2. Explain why the integral of velocity gives the change in position

Velocity is the rate of change of position with respect to time:

$$
v(t)=\frac{ds}{dt}
$$

Rearranging this relationship gives

$$
ds=v(t)\,dt
$$

Integrating both sides from \(t=0\) to \(t=5\),

$$
\int_{s(0)}^{s(5)}ds=\int_0^5v(t)\,dt
$$

Therefore,

$$
s(5)-s(0)=\int_0^5v(t)\,dt
$$

This means that the definite integral of velocity gives the **change in position, also called displacement**.

In this problem, the velocity is always positive, so the displacement equals the total distance traveled:

$$
\boxed{\Delta s=60\text{ m}}
$$

## 3. What changes if the velocity takes negative values?

If the velocity takes negative values, the car can move in the negative direction. In this case, the integral of velocity still gives the displacement, but it does not necessarily give the total distance traveled.

Displacement is calculated using the signed integral:

$$
\Delta s=\int_0^5v(t)\,dt
$$

However, total distance must account for motion in both directions. Therefore, we integrate the absolute value of velocity:

$$
\boxed{D=\int_0^5|v(t)|\,dt}
$$

If the velocity changes sign, we must identify the times when \(v(t)=0\), split the interval at those points, and add the positive distances traveled on each interval.

Negative velocity contributes negatively to displacement but positively to total distance.

## Final Answer

The total distance traveled during the first five seconds is

$$
\boxed{D=60\text{ m}}
$$

The integral of velocity gives the change in position because velocity is the derivative of position with respect to time.

If velocity can be negative, the integral of velocity gives displacement, while total distance is calculated by integrating the absolute value of velocity:

$$
\boxed{\Delta s=\int_0^5v(t)\,dt}
$$

$$
\boxed{D=\int_0^5|v(t)|\,dt}
$$
