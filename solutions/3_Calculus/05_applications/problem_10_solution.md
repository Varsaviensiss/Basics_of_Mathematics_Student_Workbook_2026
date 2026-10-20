```

# Problem 10. Optimal Cable Installation

## Step 1: Define the Variables

The river is 100 meters wide, and point B is 500 meters along the opposite bank from the point directly across from A.

Let:
- \(x\) = the distance along the opposite bank from the point directly across from A to where the cable reaches the bank.
- \(500-x\) = the remaining land distance to point B.

The underwater cable costs twice as much per meter as the land cable.

## Step 2: Express the Cable Lengths

Using the Pythagorean theorem, the underwater cable length is

\[
L_{\text{water}}=\sqrt{100^2+x^2}
=\sqrt{10000+x^2}.
\]

The land cable length is

\[
L_{\text{land}}=500-x.
\]

## Step 3: Construct the Cost Function

Let \(c\) be the cost per meter of land cable. The underwater cable costs \(2c\) per meter.

Therefore, the total cost is

\[
C(x)=2c\sqrt{10000+x^2}+c(500-x).
\]

Factor out \(c\):

\[
C(x)=c\left[2\sqrt{10000+x^2}+500-x\right].
\]

Since \(c\) is a positive constant, minimize

\[
f(x)=2\sqrt{10000+x^2}+500-x.
\]

## Step 4: Find the Critical Point

Differentiate:

\[
f'(x)=\frac{2x}{\sqrt{10000+x^2}}-1.
\]

Set the derivative equal to zero:

\[
\frac{2x}{\sqrt{10000+x^2}}-1=0.
\]

Thus,

\[
\frac{2x}{\sqrt{10000+x^2}}=1.
\]

Multiply both sides by the denominator:

\[
2x=\sqrt{10000+x^2}.
\]

Square both sides:

\[
4x^2=10000+x^2.
\]

Simplify:

\[
3x^2=10000.
\]

\[
x^2=\frac{10000}{3}.
\]

Since \(x\) is a distance, take the positive root:

\[
\boxed{x=\frac{100}{\sqrt{3}}\approx57.74\text{ m}}.
\]

## Step 5: Verify the Minimum

Differentiate again:

\[
f''(x)=\frac{20000}{(10000+x^2)^{3/2}}.
\]

Because

\[
f''(x)>0,
\]

the cost function is concave up, so the critical point gives a minimum.

## Step 6: Calculate the Land Cable Length

The remaining distance along the bank is

\[
500-x=500-\frac{100}{\sqrt{3}}.
\]

Therefore,

\[
\boxed{L_{\text{land}}\approx442.26\text{ m}}.
\]

## Final Answer

The cable should reach the opposite bank approximately **57.74 meters** from the point directly across from A.

The remaining land cable from that point to B should be approximately **442.26 meters**.

```
