# Problem 12. Compare Two Definite Integrals

## Question

Compare

$$
\int_{-2}^{2}x\,dx
\qquad\text{and}\qquad
\int_{-2}^{2}|x|\,dx.
$$

Before calculating, sketch $y=x$ and $y=|x|$ on $[-2,2]$. Use symmetry and the signed areas to predict the two values. Then evaluate both integrals and explain why the results differ.

## Solution

### 1. Sketch and predict the results

```text
y = x

                  ^ y
                  |               B (2, 2)
                  |           /// |
                  |       ///     |   Right triangle: +2
                  |   ///         |
  (-2, 0) +-------O---------------+----> x
          |   /// |
          |///    |   Left triangle: -2
 A (-2,-2)        |

O = (0, 0)
```

Each triangle has base $2$ and height $2$, so its geometric area is $\frac12\cdot2\cdot2=2$. The function $y=x$ is odd. On the symmetric interval $[-2,2]$, the left triangle contributes $-2$ and the right triangle contributes $+2$. The predicted integral is **$0$**.

```text
y = |x|

                  ^ y
  A' (-2, 2)      |               B (2, 2)
          | \     |             / |
          |   \   |         /     |
          |     \ |     /         |
  (-2, 0) +-------O---------------+----> x

      Left triangle: +2     Right triangle: +2
O = (0, 0)
```

Taking the absolute value reflects the left triangle above the $x$-axis. The function $y=|x|$ is even, so both triangles contribute $+2$. The predicted integral is **$4$**.

### 2. Evaluate the integral of $x$

$$
\int_{-2}^{2}x\,dx
=\left[\frac{x^2}{2}\right]_{-2}^{2}
=\frac{2^2}{2}-\frac{(-2)^2}{2}
=2-2=0.
$$

### 3. Evaluate the integral of $|x|$

For $x<0$, we have $|x|=-x$. For $x\ge0$, we have $|x|=x$. Splitting at $x=0$ gives

$$
\begin{aligned}
\int_{-2}^{2}|x|\,dx
&=\int_{-2}^{0}(-x)\,dx+\int_{0}^{2}x\,dx\\
&=\left[-\frac{x^2}{2}\right]_{-2}^{0}
+\left[\frac{x^2}{2}\right]_{0}^{2}\\
&=2+2=4.
\end{aligned}
$$

Both calculations confirm the predictions. For $y=x$, the two signed areas cancel. For $y=|x|$, both areas are above the axis and add together.
