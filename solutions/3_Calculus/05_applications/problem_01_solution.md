# Basic Problems

## Problem 1: Motion — From Position to Velocity

### Given

The position of a point is described by

$$
s(t)=t^3-6t^2+9t+2,\qquad t\geq 0
$$

### 1. Determine the velocity and acceleration

Velocity is the first derivative of the position function with respect to time.

$$
v(t)=s'(t)
$$

Differentiating the position function gives

$$
\begin{aligned}
v(t)&=\frac{d}{dt}(t^3-6t^2+9t+2)\\
&=3t^2-12t+9
\end{aligned}
$$

Therefore, the velocity function is

$$
\boxed{v(t)=3t^2-12t+9}
$$

Acceleration is the derivative of velocity, or the second derivative of position.

$$
a(t)=v'(t)=s''(t)
$$

Differentiating the velocity function gives

$$
\begin{aligned}
a(t)&=\frac{d}{dt}(3t^2-12t+9)\\
&=6t-12
\end{aligned}
$$

Therefore, the acceleration function is

$$
\boxed{a(t)=6t-12}
$$

### 2. Find the times at which the point stops

The point stops momentarily when its velocity is zero. Therefore, we solve

$$
v(t)=0
$$

Substituting the velocity function,

$$
3t^2-12t+9=0
$$

Dividing both sides by 3,

$$
t^2-4t+3=0
$$

Factoring the quadratic equation,

$$
(t-1)(t-3)=0
$$

Hence,

$$
t=1\qquad\text{or}\qquad t=3
$$

Both values satisfy the condition \(t\geq 0\).

**Conclusion:** The point stops momentarily at

$$
\boxed{t=1,\quad t=3}
$$

### 3. Determine the direction of motion

The direction of motion is determined by the sign of the velocity:

- If \(v(t)>0\), the point moves in the positive direction.
- If \(v(t)<0\), the point moves in the negative direction.
- If \(v(t)=0\), the point is momentarily at rest.

Factor the velocity function:

$$
v(t)=3(t-1)(t-3)
$$

The critical times \(t=1\) and \(t=3\) divide the domain into three intervals.

| Time interval | Sign of velocity | Direction of motion |
|---|---|---|
| \(0\leq t<1\) | Positive | Positive direction |
| \(1<t<3\) | Negative | Negative direction |
| \(t>3\) | Positive | Positive direction |

At \(t=1\) and \(t=3\), the velocity is zero.

Therefore, the point moves in the positive direction on

$$
\boxed{[0,1)\cup(3,\infty)}
$$

The point moves in the negative direction on

$$
\boxed{(1,3)}
$$

### Final Conclusion

The velocity and acceleration functions are

$$
\boxed{v(t)=3t^2-12t+9}
$$

$$
\boxed{a(t)=6t-12}
$$

The point stops at \(t=1\) and \(t=3\). It moves in the positive direction for \(0\leq t<1\) and \(t>3\), and in the negative direction for \(1<t<3\).

The sign of the velocity determines the direction of motion, while the derivative of velocity describes the acceleration.
