```markdown
# Problem 12. Several Rules at Once

For the function

$$
f(x)=(x^2+1)^3e^x,
$$

compute the derivative. Before calculating, write down a plan: which rule applies to the whole expression and which rule applies to one of its factors. Finally, organize the result by factoring out common factors.

## Step 1: Plan Before Calculating

The whole expression is a product of $(x^2+1)^3$ and $e^x$, so we will use the product rule:

$$
(uv)'=u'v+uv'.
$$

The first factor is a composition, so we will use the chain rule to differentiate it. Its outer function is the cube function, and its inner function is $x^2+1$.

The second factor, $e^x$, is its own derivative. After applying the product rule, we will factor out the common factors.

## Step 2: Differentiate the Factors

Let

$$
u(x)=(x^2+1)^3,\qquad v(x)=e^x.
$$

Using the chain rule,

$$
u'(x)=3(x^2+1)^2(2x)=6x(x^2+1)^2.
$$

Also,

$$
v'(x)=e^x.
$$

## Step 3: Apply the Product Rule

$$
f'(x)=u'(x)v(x)+u(x)v'(x).
$$

Substituting gives

$$
f'(x)=6x(x^2+1)^2e^x+(x^2+1)^3e^x.
$$

## Step 4: Factor the Result

Both terms contain $e^x(x^2+1)^2$. Factoring gives

$$
f'(x)=e^x(x^2+1)^2[6x+(x^2+1)].
$$

Therefore,

$$
\boxed{f'(x)=e^x(x^2+1)^2(x^2+6x+1)}.
$$
```
