# Problem 3. A Box Made from Cardboard

## Question

A rectangular sheet of cardboard measures $30\ \mathrm{cm}\times40\ \mathrm{cm}$. Squares of side length $x$ are cut from each corner, and the remaining cardboard is folded upward to form an open box.

1. Write the volume as a function of $x$.
2. Determine the physically meaningful domain.
3. Find the value of $x$ that maximizes the volume and justify the maximum.

## Solution

### 1. Find the volume function

The height is $x$, the width is $30-2x$, and the length is $40-2x$. Multiplying the three dimensions gives

$$
V(x)=x(30-2x)(40-2x)=4x^3-140x^2+1200x.
$$

### 2. Determine the physical domain

All three dimensions must be positive. The conditions $x>0$, $30-2x>0$, and $40-2x>0$ give the physical domain $0<x<15$.

### 3. Find the maximizing cut size

Differentiating gives

$$
V'(x)=12x^2-280x+1200=4(3x^2-70x+300).
$$

Solving $V'(x)=0$ with the quadratic formula gives

$$
x=\frac{70\pm\sqrt{4900-3600}}6
=\frac{35\pm5\sqrt{13}}3.
$$

The larger root is approximately $17.68$, outside the physical domain. The only critical point in the domain is

$$
x_*=\frac{35-5\sqrt{13}}3\approx5.66\ \mathrm{cm}.
$$

### 4. Justify the maximum and evaluate the volume

Since $V''(x)=24x-280$, we have $V''(x_*)=-40\sqrt{13}<0$, so $x_*$ gives a local maximum. The volume function extends continuously to $[0,15]$, where $V(0)=V(15)=0$. Because the volume is positive on $(0,15)$ and $x_*$ is the only interior critical point, it gives the global maximum.

Substituting the exact cut size before rounding gives

$$
V_{\max}=x_*(30-2x_*)(40-2x_*)
\approx3032.30\ \mathrm{cm}^3.
$$

The box is approximately $5.66\ \mathrm{cm}$ high, $18.69\ \mathrm{cm}$ wide, and $28.69\ \mathrm{cm}$ long.
