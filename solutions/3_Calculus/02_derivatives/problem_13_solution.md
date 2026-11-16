```markdown
# Problem 13. A Multi-Layer Composition

For the function

$$
f(x)=e^{\sin(x^2)},
$$

compute the derivative. First write the layers

$$
x\longrightarrow x^2\longrightarrow\sin(x^2)
\longrightarrow e^{\sin(x^2)}
$$

and explain why differentiation moves through them in the reverse order.

## Step 1: Identify the Layers

The function is evaluated from the inside outward:

$$
u=x^2,\qquad v=\sin u,\qquad y=e^v.
$$

First we square $x$, then take the sine, and finally apply the exponential function.

## Step 2: Explain the Outside-In Procedure

To differentiate, we start with the outermost function $y=e^v$. Its derivative describes how $y$ changes with its input $v$. We then multiply by how $v$ changes with $u$, and finally by how $u$ changes with $x$.

The chain rule expresses this as

$$
\frac{dy}{dx}
=\frac{dy}{dv}\frac{dv}{du}\frac{du}{dx}.
$$

Thus, differentiation works through the layers in reverse order: exponential, sine, then square. Each outer response is multiplied by the rate of change of its input, accounting for all three factors.

## Step 3: Differentiate Each Layer

$$
\frac{dy}{dv}=e^v,
\qquad
\frac{dv}{du}=\cos u,
\qquad
\frac{du}{dx}=2x.
$$

## Step 4: Combine the Factors

Applying the chain rule gives

$$
f'(x)=e^v\cos u\cdot2x.
$$

Substituting $u=x^2$ and $v=\sin(x^2)$,

$$
f'(x)=e^{\sin(x^2)}\cos(x^2)\cdot2x.
$$

Therefore,

$$
\boxed{f'(x)=2x\cos(x^2)e^{\sin(x^2)}}.
$$
```
