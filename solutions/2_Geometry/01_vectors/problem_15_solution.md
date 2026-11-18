# Exercise 15. Comparing Directions Using the Cosine of the Angle

Given $\mathbf{a}=(1,2,1)$, $\mathbf{b}=(2,4,2)$, and $\mathbf{c}=(2,0,3)$, calculate the cosine and angle for each pair. Order the pairs by increasing angle and explain why the cosine for $\mathbf{a}$ and $\mathbf{b}$ equals $1$ despite their different lengths.

## 1. Calculate the Vector Lengths

$$
\|\mathbf{a}\|=\sqrt{1^2+2^2+1^2}=\sqrt{6},
\qquad
\|\mathbf{b}\|=\sqrt{2^2+4^2+2^2}=2\sqrt{6},
\qquad
\|\mathbf{c}\|=\sqrt{2^2+0^2+3^2}=\sqrt{13}.
$$

For each pair, use

$$
\cos\theta=\frac{\mathbf{u}\cdot\mathbf{v}}{\|\mathbf{u}\|\|\mathbf{v}\|}.
$$

## 2. Compare a and b

$$
\mathbf{a}\cdot\mathbf{b}=1(2)+2(4)+1(2)=12.
$$

$$
\cos\theta_{ab}=\frac{12}{\sqrt{6}(2\sqrt{6})}=1,
\qquad
\theta_{ab}=0^\circ.
$$

## 3. Compare a and c

$$
\mathbf{a}\cdot\mathbf{c}=1(2)+2(0)+1(3)=5.
$$

$$
\cos\theta_{ac}=\frac{5}{\sqrt{6}\sqrt{13}}=\frac{5}{\sqrt{78}},
\qquad
\theta_{ac}=\arccos\left(\frac{5}{\sqrt{78}}\right)\approx55.52^\circ.
$$

## 4. Compare b and c

$$
\mathbf{b}\cdot\mathbf{c}=2(2)+4(0)+2(3)=10.
$$

$$
\cos\theta_{bc}=\frac{10}{(2\sqrt{6})\sqrt{13}}=\frac{5}{\sqrt{78}},
\qquad
\theta_{bc}=\arccos\left(\frac{5}{\sqrt{78}}\right)\approx55.52^\circ.
$$

## 5. Order the Angles

$$
\theta_{ab}<\theta_{ac}=\theta_{bc}.
$$

The pair $(\mathbf{a},\mathbf{b})$ has the smallest angle. The other two angles are exactly equal because their exact cosines are equal.

## 6. Explain Why the First Cosine Is 1

Since $\mathbf{b}=2\mathbf{a}$, both vectors point in the same direction even though $\mathbf{b}$ is twice as long. Multiplying by $2$ doubles both the dot product and the length of $\mathbf{b}$, so the factor cancels in the cosine formula. Their angle is $0^\circ$, and its cosine is $1$.

## Final Answers

| Pair | Dot product | Exact cosine | Angle |
|---|---:|---:|---:|
| $(\mathbf{a},\mathbf{b})$ | $12$ | $1$ | $0^\circ$ |
| $(\mathbf{a},\mathbf{c})$ | $5$ | $\frac{5}{\sqrt{78}}$ | $\approx 55.52^\circ$ |
| $(\mathbf{b},\mathbf{c})$ | $10$ | $\frac{5}{\sqrt{78}}$ | $\approx 55.52^\circ$ |
