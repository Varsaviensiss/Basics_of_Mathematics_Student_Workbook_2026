# Problem 1. Motion — from Position to Velocity

## Question

The position of a point is described by

$$
s(t)=t^3-6t^2+9t+2,\qquad t\ge 0.
$$

1. Determine the velocity and acceleration.
2. Find the times at which the point stops.
3. Determine on which intervals the point moves in the positive direction of the axis and on which intervals it moves in the negative direction.

## Solution

### 1. Determine the velocity and acceleration

Velocity is the first derivative of the position function with respect to time:

$$
v(t)=s'(t)=3t^2-12t+9.
$$

Acceleration is the derivative of velocity, or the second derivative of position:

$$
a(t)=v'(t)=s''(t)=6t-12.
$$

### 2. Find the times at which the point stops

The point stops momentarily when its velocity is zero. Setting $v(t)=0$, dividing by $3$, and factoring gives

$$
3t^2-12t+9=0
\quad\Longleftrightarrow\quad
t^2-4t+3=0
\quad\Longleftrightarrow\quad
(t-1)(t-3)=0.
$$

Both solutions satisfy $t\ge0$, so the point stops momentarily at $t=1$ and $t=3$.

### 3. Determine the direction of motion

The direction of motion is determined by the sign of $v(t)=3(t-1)(t-3)$. The stopping times divide the domain into three intervals.

| Time interval | Sign of velocity | Direction of motion |
|---|---|---|
| $[0,1)$ | Positive | Positive direction |
| $(1,3)$ | Negative | Negative direction |
| $(3,\infty)$ | Positive | Positive direction |

Thus the point moves in the positive direction on $[0,1)\cup(3,\infty)$ and in the negative direction on $(1,3)$. It is momentarily at rest at $t=1$ and $t=3$.
