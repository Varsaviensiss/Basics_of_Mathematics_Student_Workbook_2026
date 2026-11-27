# Problem 10. A Cable Through Water and Land

## Question

Point $A$ lies on one bank of a river of width $100$ m, and point $B$ lies on the other bank, $500$ m along the bank from the point directly opposite $A$.

The cost per meter of cable underwater is twice the cost per meter of cable on land.

Build a cost function depending on the point where the cable comes out of the water, determine the domain, and find the solution that minimizes the cost.

## Solution

### 1. Define the variable and its domain

Let $P$ be the point directly opposite $A$. Let $x$ be the distance from $P$ to the cable's emergence point, measured along the opposite bank toward $B$.

If the cable emerges beyond either end of the segment from $P$ to $B$, moving the emergence point to the nearest endpoint shortens both the underwater and land portions. Thus it is enough to consider emergence points on that segment. The physical domain is

$$
0\le x\le500.
$$

### 2. Build the cost function

By the Pythagorean theorem, the underwater cable length is $\sqrt{100^2+x^2}$. The remaining land cable length is $500-x$.

Let $c>0$ be the cost per meter of land cable. Since underwater cable costs $2c$ per meter, the total cost is

$$
C(x)=2c\sqrt{10000+x^2}+c(500-x).
$$

Dividing by the positive constant $c$ preserves the minimizer, so we minimize

$$
f(x)=2\sqrt{10000+x^2}+500-x.
$$

### 3. Find and verify the minimum

Differentiating gives

$$
f'(x)=\frac{2x}{\sqrt{10000+x^2}}-1.
$$

Setting $f'(x)=0$ gives $2x=\sqrt{10000+x^2}$. Both sides are nonnegative on the domain. Squaring and simplifying gives $3x^2=10000$, so

$$
x_*=\frac{100}{\sqrt3}\approx57.74\ \mathrm{m}.
$$

Since $0<100/\sqrt3<100<500$, this point lies inside the physical domain. Also,

$$
f''(x)=\frac{20000}{(10000+x^2)^{3/2}}>0
$$

throughout the domain. The cost is strictly convex, so this interior stationary point gives the unique global minimum.

The cable should emerge **$57.74$ m from $P$ toward $B$**, leaving approximately **$442.26$ m** of land cable.
