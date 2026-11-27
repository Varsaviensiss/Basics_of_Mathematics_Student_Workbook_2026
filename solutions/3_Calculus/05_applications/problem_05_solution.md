# Problem 5. Distance from Velocity

## Question

The velocity of a car during the first five seconds is

$$
v(t)=4t+2\ \mathrm{m/s},\qquad 0\le t\le5.
$$

Find the distance traveled during this time. Explain why the integral of velocity gives the change in position. What changes if the velocity also takes negative values?

## Solution

### 1. Calculate the distance traveled

The velocity is positive throughout $[0,5]$, so the car always moves in the positive direction and its speed equals its velocity. Its total distance is

$$
D=\int_0^5(4t+2)\,dt
=\left[2t^2+2t\right]_0^5
=50+10
=60\ \mathrm{m}.
$$

### 2. Explain the change in position

If $s(t)$ is the position, then $s'(t)=v(t)$. By the Fundamental Theorem of Calculus,

$$
s(5)-s(0)=\int_0^5v(t)\,dt.
$$

This signed integral gives the displacement. Because the car moves in the positive direction throughout the interval, the displacement and the total distance are both $60\ \mathrm{m}$.

### 3. Explain what changes when velocity can be negative

The signed integral $\int_0^5v(t)\,dt$ still gives the displacement. Negative velocity contributes negatively to displacement. For total distance, motion in either direction contributes positively, so we integrate the speed:

$$
D=\int_0^5|v(t)|\,dt.
$$

If a continuous velocity changes sign, split the interval at the zeros where the sign changes. Integrate $v(t)$ where it is positive and $-v(t)$ where it is negative, then add the resulting distances.
