# Problem 8. Choosing the Factors in Integration by Parts

## Question

Compute

$$
\int x\cos x\,dx.
$$

Before calculating, justify why it is convenient to differentiate $x$ and integrate $\cos x$, rather than the other way around.

## Solution

### 1. Justify the choice of factors

Differentiating $x$ gives $1$, and integrating $\cos x$ gives $\sin x$. This leaves a simple integral involving only $\sin x$. The reverse choice would introduce the factor $x^2/2$ from integrating $x$, leaving a product of a quadratic and $\sin x$ to integrate.

### 2. Apply integration by parts

Choose $u=x$ and $dv=\cos x\,dx$. Then $du=dx$ and we can take $v=\sin x$. Using integration by parts gives

$$
\begin{aligned}
\int x\cos x\,dx
&=x\sin x-\int\sin x\,dx\\
&=x\sin x+\cos x+C.
\end{aligned}
$$

### 3. Verify by differentiation

The product rule gives

$$
\frac{d}{dx}\bigl(x\sin x+\cos x+C\bigr)
=\sin x+x\cos x-\sin x
=x\cos x.
$$

The derivative matches the original integrand.
