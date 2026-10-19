# Exercise 15. Comparing Directions Using the Cosine of the Angle

## Given

$$
\mathbf{a}=(1,2,1)
$$

$$
\mathbf{b}=(2,4,2)
$$

$$
\mathbf{c}=(2,0,3)
$$

For each pair, calculate the cosine of the angle:

$$
\cos\theta=\frac{\mathbf{u}\cdot\mathbf{v}}{|\mathbf{u}||\mathbf{v}|}
$$

## 1. Calculate the Vector Lengths

For \(\mathbf{a}\):

$$
|\mathbf{a}|=\sqrt{1^2+2^2+1^2}
$$

$$
=\sqrt{1+4+1}
$$

$$
\boxed{|\mathbf{a}|=\sqrt6}
$$

For \(\mathbf{b}\):

$$
|\mathbf{b}|=\sqrt{2^2+4^2+2^2}
$$

$$
=\sqrt{4+16+4}
$$

$$
=\sqrt{24}
$$

$$
\boxed{|\mathbf{b}|=2\sqrt6}
$$

For \(\mathbf{c}\):

$$
|\mathbf{c}|=\sqrt{2^2+0^2+3^2}
$$

$$
=\sqrt{4+0+9}
$$

$$
\boxed{|\mathbf{c}|=\sqrt{13}}
$$

## 2. Compare \(\mathbf{a}\) and \(\mathbf{b}\)

Calculate the dot product:

$$
\mathbf{a}\cdot\mathbf{b}=1(2)+2(4)+1(2)
$$

$$
=2+8+2
$$

$$
\boxed{\mathbf{a}\cdot\mathbf{b}=12}
$$

Calculate the cosine:

$$
\cos\theta_{ab}
=\frac{12}{\sqrt6(2\sqrt6)}
$$

$$
=\frac{12}{12}
$$

$$
\boxed{\cos\theta_{ab}=1}
$$

Therefore,

$$
\boxed{\theta_{ab}=0^\circ}
$$

The vectors point in exactly the same direction.

## 3. Compare \(\mathbf{a}\) and \(\mathbf{c}\)

Calculate the dot product:

$$
\mathbf{a}\cdot\mathbf{c}=1(2)+2(0)+1(3)
$$

$$
=2+0+3
$$

$$
\boxed{\mathbf{a}\cdot\mathbf{c}=5}
$$

Calculate the cosine:

$$
\cos\theta_{ac}
=\frac{5}{\sqrt6\sqrt{13}}
$$

$$
\boxed{\cos\theta_{ac}=\frac5{\sqrt{78}}}
$$

Therefore,

$$
\theta_{ac}=\cos^{-1}\left(\frac5{\sqrt{78}}\right)
$$

$$
\boxed{\theta_{ac}\approx55.6^\circ}
$$

## 4. Compare \(\mathbf{b}\) and \(\mathbf{c}\)

Calculate the dot product:

$$
\mathbf{b}\cdot\mathbf{c}=2(2)+4(0)+2(3)
$$

$$
=4+0+6
$$

$$
\boxed{\mathbf{b}\cdot\mathbf{c}=10}
$$

Calculate the cosine:

$$
\cos\theta_{bc}
=\frac{10}{(2\sqrt6)(\sqrt{13})}
$$

$$
=\frac{10}{2\sqrt{78}}
$$

$$
\boxed{\cos\theta_{bc}=\frac5{\sqrt{78}}}
$$

Therefore,

$$
\boxed{\theta_{bc}\approx55.6^\circ}
$$

## 5. Order the Pairs by Increasing Angle

The calculated angles are

$$
\theta_{ab}=0^\circ
$$

$$
\theta_{ac}\approx55.6^\circ
$$

$$
\theta_{bc}\approx55.6^\circ
$$

Thus, the order is

$$
\boxed{(\mathbf{a},\mathbf{b})<(\mathbf{a},\mathbf{c})=(\mathbf{b},\mathbf{c})}
$$

The pair \((\mathbf{a},\mathbf{b})\) has the smallest angle, while the other two pairs have equal angles.

## 6. Why Is the Cosine Equal to \(1\) for \(\mathbf{a}\) and \(\mathbf{b}\) Despite Their Different Lengths?

Observe that

$$
\mathbf{b}=(2,4,2)=2(1,2,1)
$$

$$
\boxed{\mathbf{b}=2\mathbf{a}}
$$

Therefore, \(\mathbf{b}\) is a positive scalar multiple of \(\mathbf{a}\). The vectors have different lengths, but they point in the same direction.

The angle between them is zero, so

$$
\boxed{\cos 0^\circ=1}
$$

The cosine formula divides the dot product by both vector lengths, removing the effect of their magnitudes and measuring their directional alignment.

## Final Answers

| Pair | Dot product | Cosine of angle | Angle |
|---|---:|---:|---:|
| \(\mathbf{a},\mathbf{b}\) | \(12\) | \(1\) | \(0^\circ\) |
| \(\mathbf{a},\mathbf{c}\) | \(5\) | \(\frac5{\sqrt{78}}\) | \(\approx55.6^\circ\) |
| \(\mathbf{b},\mathbf{c}\) | \(10\) | \(\frac5{\sqrt{78}}\) | \(\approx55.6^\circ\) |
