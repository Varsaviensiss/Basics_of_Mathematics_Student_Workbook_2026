# Exercise 3. A Square Root and Removing an Indeterminate Form

## Question

Evaluate

$$
\lim_{n\to\infty}\left(\sqrt{n^2+5n}-n\right).
$$

Use the conjugate and explain why it removes the difficulty in evaluating the limit.

## Solution

Both $\sqrt{n^2+5n}$ and $n$ tend to infinity, so their difference has the indeterminate form $\infty-\infty$.

Multiply and divide by the conjugate $\sqrt{n^2+5n}+n$. Using the identity $(a-b)(a+b)=a^2-b^2$, we get

$$
\sqrt{n^2+5n}-n
=
\frac{(n^2+5n)-n^2}{\sqrt{n^2+5n}+n}
=
\frac{5n}{\sqrt{n^2+5n}+n}.
$$

The conjugate turns the difference of two growing terms into a quotient. The $n^2$ terms cancel in the numerator, and for $n>0$ we can divide both numerator and denominator by $n$:

$$
\frac{5n}{\sqrt{n^2+5n}+n}
=
\frac{5}{\sqrt{1+5/n}+1}.
$$

Since $5/n\to0$, the denominator tends to $2$. Therefore,

$$
\boxed{\lim_{n\to\infty}\left(\sqrt{n^2+5n}-n\right)=\frac52}.
$$
