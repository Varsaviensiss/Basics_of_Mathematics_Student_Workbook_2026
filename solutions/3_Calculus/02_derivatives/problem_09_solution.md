```markdown
# Problem 9. A Logarithm and the Chain Rule

For the function

$$
f(x)=\ln(x^2+1),
$$

compute the derivative. Then determine the sign of $f'(x)$ for $x<0$, $x=0$, and $x>0$, and describe qualitatively how the function behaves around zero.

## Step 1: Identify the Rule and Domain

Since $x^2+1>0$ for every real $x$, the function is defined on $\mathbb{R}$.

The logarithm contains the inner function $u(x)=x^2+1$, so we use the chain rule:

$$
\frac{d}{dx}\ln u(x)=\frac{u'(x)}{u(x)}.
$$

## Step 2: Compute the Derivative

The derivative of the inner function is

$$
u'(x)=2x.
$$

Therefore,

$$
\boxed{f'(x)=\frac{2x}{x^2+1}}.
$$

## Step 3: Analyze the Sign

The denominator $x^2+1$ is always positive, so the sign of $f'(x)$ is determined by $2x$.

- For $x<0$, we have $f'(x)<0$.
- For $x=0$, we have $f'(0)=0$.
- For $x>0$, we have $f'(x)>0$.

## Step 4: Describe the Behavior Around Zero

The function decreases on $(-\infty,0)$ and increases on $(0,\infty)$. Thus, it decreases toward $x=0$ from the left and increases away from it on the right.

At zero,

$$
f(0)=\ln 1=0.
$$

The derivative changes from negative to positive, so the function has a global minimum at

$$
\boxed{(0,0)}.
$$

Since $f'(0)=0$, the tangent line there is horizontal.
```
