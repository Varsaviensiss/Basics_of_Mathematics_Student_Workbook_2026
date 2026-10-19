# Problem 3: A Box Made from Cardboard

## Given

A rectangular sheet of cardboard measures \(30\text{ cm}\times40\text{ cm}\). Squares of side length \(x\) are cut from each corner, and the remaining cardboard is folded upward to form an open box.

We need to determine the volume function, its physically meaningful domain, and the value of \(x\) that maximizes the volume.

## 1. Write the volume as a function of \(x\)

After cutting out squares of side length \(x\) from each corner and folding the edges upward, the box has the following dimensions:

- **Height:** \(x\) cm
- **Length:** \(40-2x\) cm
- **Width:** \(30-2x\) cm

The volume of a rectangular box is

$$
V=\text{length}\times\text{width}\times\text{height}
$$

Substituting the dimensions gives

$$
V(x)=x(30-2x)(40-2x)
$$

Expanding,

$$
(30-2x)(40-2x)=1200-140x+4x^2
$$

Therefore,

$$
V(x)=x(1200-140x+4x^2)
$$

The volume function is

$$
\boxed{V(x)=4x^3-140x^2+1200x}
$$

where \(V(x)\) is measured in cubic centimeters.

## 2. Determine the physically meaningful domain

For the box to be physically possible, all three dimensions must be positive.

First, the height must satisfy

$$
x>0
$$

The width must also be positive:

$$
30-2x>0
$$

Solving this inequality gives

$$
x<15
$$

Similarly, the length must be positive:

$$
40-2x>0
$$

Therefore,

$$
x<20
$$

Combining all the conditions, we obtain

$$
x>0,\qquad x<15,\qquad x<20
$$

The most restrictive upper bound is \(x<15\). Thus, the physically meaningful domain is

$$
\boxed{0<x<15}
$$

## 3. Find the value of \(x\) that maximizes the volume

The volume function is

$$
V(x)=4x^3-140x^2+1200x
$$

Differentiate with respect to \(x\):

$$
V'(x)=12x^2-280x+1200
$$

To find the critical points, set the first derivative equal to zero:

$$
12x^2-280x+1200=0
$$

Dividing both sides by \(4\),

$$
3x^2-70x+300=0
$$

Using the quadratic formula,

$$
x=\frac{70\pm\sqrt{70^2-4(3)(300)}}{2(3)}
$$

Simplifying,

$$
x=\frac{70\pm\sqrt{4900-3600}}{6}
$$

$$
x=\frac{70\pm\sqrt{1300}}{6}
$$

Since \(\sqrt{1300}=10\sqrt{13}\),

$$
x=\frac{70\pm10\sqrt{13}}{6}
$$

Therefore,

$$
x=\frac{35\pm5\sqrt{13}}{3}
$$

The two critical points are

$$
x_1=\frac{35-5\sqrt{13}}{3}
\approx5.66
$$

and

$$
x_2=\frac{35+5\sqrt{13}}{3}
\approx17.67
$$

The second critical point is outside the physically meaningful domain \(0<x<15\), so it must be rejected.

Hence, the only critical point in the domain is

$$
\boxed{x=\frac{35-5\sqrt{13}}{3}\approx5.66\text{ cm}}
$$

## 4. Verify that the volume is maximized

The first derivative is

$$
V'(x)=12x^2-280x+1200
$$

Taking the second derivative gives

$$
V''(x)=24x-280
$$

At the critical point \(x=\frac{35-5\sqrt{13}}{3}\),

$$
V''(x)=24\left(\frac{35-5\sqrt{13}}{3}\right)-280
$$

Simplifying,

$$
V''(x)=280-40\sqrt{13}-280
$$

$$
V''(x)=-40\sqrt{13}<0
$$

Since the second derivative is negative at this critical point, the volume function has a local maximum there.

Furthermore, the volume approaches zero at both ends of the physical domain:

$$
\lim_{x\to0^+}V(x)=0
$$

$$
\lim_{x\to15^-}V(x)=0
$$

Therefore, the critical point gives the greatest possible volume on the physically meaningful domain.

## Final Answer

The volume function is

$$
\boxed{V(x)=x(30-2x)(40-2x)}
$$

or, in expanded form,

$$
\boxed{V(x)=4x^3-140x^2+1200x}
$$

The physically meaningful domain is

$$
\boxed{0<x<15}
$$

The value of \(x\) that maximizes the volume is

$$
\boxed{x=\frac{35-5\sqrt{13}}{3}\approx5.66\text{ cm}}
$$

At this value, the box has approximate dimensions

$$
\begin{aligned}
\text{Height}&\approx5.66\text{ cm}\\
\text{Width}&\approx18.68\text{ cm}\\
\text{Length}&\approx28.68\text{ cm}
\end{aligned}
$$

The maximum volume is approximately

$$
\boxed{V_{\max}\approx3033.13\text{ cm}^3}
$$

Thus, cutting squares of side length approximately \(5.66\) cm from each corner produces the open box with the greatest volume.
