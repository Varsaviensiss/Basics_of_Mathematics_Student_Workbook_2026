# Problem 11. Volume of a Solid of Revolution

## Question

The region under the graph

$$
y=\sqrt{x},\qquad x\in[0,4],
$$

is rotated about the $x$-axis.

1. Construct the integral describing the volume using the disk method.
2. Compute the volume.
3. Explain where the factor $\pi y^2$ in the integral comes from.

## Solution

### 1. Construct the volume integral

At a fixed $x$, the vertical segment from the $x$-axis to the curve has length $y=\sqrt{x}$. Rotating that segment about the $x$-axis fills a disk of radius $y$. Its cross-sectional area is $\pi y^2$.

A thin slice of thickness $\Delta x$ has approximate volume $\pi y^2\Delta x$. Adding the slices and taking the limit gives

$$
V=\int_0^4\pi y^2\,dx
=\pi\int_0^4(\sqrt{x})^2\,dx
=\pi\int_0^4x\,dx.
$$

### 2. Compute the volume

An antiderivative of $x$ is $x^2/2$, so

$$
V=\pi\left[\frac{x^2}{2}\right]_0^4
=\pi\left(\frac{16}{2}-0\right)
=8\pi.
$$

The volume is **$8\pi$ cubic units**, approximately **$25.13$ cubic units**.
