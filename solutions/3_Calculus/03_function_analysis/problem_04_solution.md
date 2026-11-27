# Problem 4. A Function with Two Vertical Asymptotes

## Question

Given the function

$$
f(x)=\frac{1}{x^2-1}.
$$

Determine the domain, asymptotes, sign, and monotonicity on the intervals of the domain. Explain why each interval must be analyzed separately.

## Solution

### 1. Find the Domain

The denominator must be nonzero. Since $x^2-1=(x-1)(x+1)$, we must exclude $x=-1$ and $x=1$. The domain is

$$
D_f=\mathbb{R}\setminus\{-1,1\}.
$$

This gives three separate intervals: $(-\infty,-1)$, $(-1,1)$, and $(1,\infty)$.

### 2. Find the Asymptotes

The denominator tends to zero as $x$ approaches $-1$ or $1$, while the numerator stays equal to $1$. Therefore, $x=-1$ and $x=1$ are vertical asymptotes.

As $x\to\pm\infty$, the denominator grows without bound and $f(x)\to0$. Thus $y=0$ is the horizontal asymptote.

### 3. Determine the Sign

The numerator is always positive, so the sign of $f(x)$ depends on the product $(x-1)(x+1)$.

- For $x<-1$, both factors are negative, so $f(x)>0$.
- For $-1<x<1$, the factors have opposite signs, so $f(x)<0$.
- For $x>1$, both factors are positive, so $f(x)>0$.

The function has no zeros because its numerator is always $1$.

### 4. Find the Derivative and Determine Monotonicity

Differentiating gives

$$
f'(x)=-\frac{2x}{(x^2-1)^2}.
$$

The denominator is positive everywhere in the domain, so the sign of $f'(x)$ depends on $-2x$.

- The function increases on $(-\infty,-1)$ and $(-1,0)$.
- The function decreases on $(0,1)$ and $(1,\infty)$.

At $x=0$, the derivative changes from positive to negative. Since $f(0)=-1$, the function has a local maximum at $(0,-1)$.

### 5. Explain Why Each Interval Must Be Analyzed Separately

The function is undefined at $x=-1$ and $x=1$. These points divide the domain into three disconnected intervals. The derivative test applies on intervals where the function is defined throughout, so monotonicity must be analyzed separately on each interval.
