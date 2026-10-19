# Exercise 5. Row Echelon Form and Number of Solutions

Given the augmented matrix:

$$
\left[
\begin{array}{ccc|c}
1&2&-1&3\\
0&1&2&1\\
0&0&0&0
\end{array}
\right]
$$

## Step 1. Write the corresponding equations

The first row gives:

$$
x+2y-z=3
$$

The second row gives:

$$
y+2z=1
$$

The third row gives:

$$
0=0
$$

The third row adds no new restriction.

## Step 2. Identify the free variable

There are three variables, \(x,y,z\), but only two pivot columns.

Therefore, one variable can be chosen freely. Let:

$$
z=t,\qquad t\in\mathbb{R}
$$

## Step 3. Solve for \(y\)

From:

$$
y+2z=1
$$

Substitute \(z=t\):

$$
y+2t=1
$$

$$
y=1-2t
$$

## Step 4. Solve for \(x\)

From:

$$
x+2y-z=3
$$

Substitute \(y=1-2t\) and \(z=t\):

$$
x+2(1-2t)-t=3
$$

$$
x+2-4t-t=3
$$

$$
x=1+5t
$$

## Final answer

$$
\boxed{
(x,y,z)=(1+5t,1-2t,t),\qquad t\in\mathbb{R}
}
$$

The system has infinitely many solutions because there is one free variable and no contradictory equation.
