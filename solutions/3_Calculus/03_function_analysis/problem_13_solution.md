# Problem 13. A Logarithm and an Asymptote

## Question

For the function

$$
f(x)=\frac{\ln x}{x},\qquad x>0,
$$

perform a complete analysis. Find the maximum, examine the behavior at both ends of the domain, and explain what information is needed to sketch the graph correctly.

## Solution

### 1. Domain, zero, and sign

The natural logarithm is defined for $x>0$, so the domain is $(0,\infty)$. The denominator is positive throughout the domain, so $f$ has the same sign as $\ln x$. Hence $f(x)<0$ on $(0,1)$, $f(1)=0$, and $f(x)>0$ on $(1,\infty)$. The only intercept is $(1,0)$.

### 2. Monotonicity and maximum

The quotient rule gives

$$
f'(x)=\frac{x(1/x)-\ln x}{x^2}
=\frac{1-\ln x}{x^2}.
$$

Since $x^2>0$, the sign of $f'(x)$ is determined by $1-\ln x$. It is positive on $(0,e)$, zero at $x=e$, and negative on $(e,\infty)$. Therefore, $f$ increases on $(0,e)$ and decreases on $(e,\infty)$. Its absolute maximum is at

$$
\left(e,f(e)\right)=\left(e,\frac1e\right).
$$

### 3. Limits and asymptotes

For $0<x<e^{-1}$, we have $\ln x<-1$. Dividing by the positive number $x$ gives $f(x)<-1/x$. Since $-1/x\to-\infty$ as $x\to0^+$, it follows that

$$
\lim_{x\to0^+}\frac{\ln x}{x}=-\infty.
$$

Thus $x=0$ is a vertical asymptote.

As $x\to+\infty$, both $\ln x$ and $x$ tend to $+\infty$. L'Hôpital's rule gives

$$
\lim_{x\to+\infty}\frac{\ln x}{x}
=\lim_{x\to+\infty}\frac{1/x}{1}
=0.
$$

Thus $y=0$ is a horizontal asymptote on the right. Since $f(x)>0$ for $x>1$, the graph approaches it from above.

### 4. Concavity and inflection point

Differentiating $f'(x)=(1-\ln x)x^{-2}$ gives

$$
f''(x)=-x^{-3}-2(1-\ln x)x^{-3}
=\frac{2\ln x-3}{x^3}.
$$

The denominator is positive. The numerator vanishes when $\ln x=3/2$, so the concavity changes at $x=e^{3/2}$.

| Interval | Sign of $f''(x)$ | Concavity |
|---|---|---|
| $(0,e^{3/2})$ | $-$ | Concave down |
| $(e^{3/2},\infty)$ | $+$ | Concave up |

Since $f(e^{3/2})=3/(2e^{3/2})$, the inflection point is

$$
\left(e^{3/2},\frac{3}{2e^{3/2}}\right).
$$

### 5. Sketch guidance

Draw the graph to the right of the vertical asymptote $x=0$. It rises from $-\infty$, crosses the $x$-axis at $(1,0)$, and reaches its maximum at $(e,1/e)$. It then decreases, remaining concave down up to the inflection point. Beyond that point, it is concave up and continues decreasing toward the horizontal asymptote $y=0$ from above.
