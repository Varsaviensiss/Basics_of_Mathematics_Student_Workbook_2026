# Exercise 15: Comparing Directions Using the Cosine of the Angle

Given the vectors

\[
a=(1,2,1),\qquad b=(2,4,2),\qquad c=(2,0,3).
\]

To compare the directions of the vectors, we use the cosine formula

\[
\boxed{\cos\theta=\frac{u\cdot v}{\|u\|\|v\|}},
\]

where \(u\cdot v\) is the dot product and \(\|u\|\), \(\|v\|\) are the magnitudes of the vectors.

We calculate this value for each pair: \((a,b)\), \((a,c)\), and \((b,c)\).

## 1. Pair \((a,b)\)

### Step 1: Compute the dot product

\[
a\cdot b=(1)(2)+(2)(4)+(1)(2).
\]

\[
a\cdot b=2+8+2.
\]

\[
\boxed{a\cdot b=12}
\]

### Step 2: Compute the magnitudes

For vector \(a=(1,2,1)\),

\[
\|a\|=\sqrt{1^2+2^2+1^2}.
\]

\[
\|a\|=\sqrt{1+4+1}=\sqrt{6}.
\]

For vector \(b=(2,4,2)\),

\[
\|b\|=\sqrt{2^2+4^2+2^2}.
\]

\[
\|b\|=\sqrt{4+16+4}=\sqrt{24}=2\sqrt{6}.
\]

### Step 3: Compute the cosine of the angle

\[
\cos\theta_{ab}
=\frac{a\cdot b}{\|a\|\|b\|}.
\]

Substitute the values:

\[
\cos\theta_{ab}
=\frac{12}{(\sqrt{6})(2\sqrt{6})}.
\]

\[
=\frac{12}{2\cdot6}
=\frac{12}{12}.
\]

Therefore,

\[
\boxed{\cos\theta_{ab}=1}.
\]

Since \(\cos 0^\circ=1\),

\[
\boxed{\theta_{ab}=0^\circ}.
\]

The vectors point in the same direction.

## 2. Pair \((a,c)\)

### Step 1: Compute the dot product

\[
a\cdot c=(1)(2)+(2)(0)+(1)(3).
\]

\[
a\cdot c=2+0+3.
\]

\[
\boxed{a\cdot c=5}
\]

### Step 2: Compute the magnitudes

We already know that

\[
\|a\|=\sqrt{6}.
\]

For vector \(c=(2,0,3)\),

\[
\|c\|=\sqrt{2^2+0^2+3^2}.
\]

\[
\|c\|=\sqrt{4+0+9}.
\]

\[
\boxed{\|c\|=\sqrt{13}}
\]

### Step 3: Compute the cosine of the angle

\[
\cos\theta_{ac}
=\frac{a\cdot c}{\|a\|\|c\|}.
\]

Substitute the values:

\[
\cos\theta_{ac}
=\frac{5}{(\sqrt{6})(\sqrt{13})}.
\]

Therefore,

\[
\boxed{\cos\theta_{ac}=\frac{5}{\sqrt{78}}\approx0.5661}.
\]

To find the angle, take the inverse cosine:

\[
\theta_{ac}=\cos^{-1}\left(\frac{5}{\sqrt{78}}\right).
\]

\[
\boxed{\theta_{ac}\approx55.52^\circ}
\]

## 3. Pair \((b,c)\)

### Step 1: Compute the dot product

\[
b\cdot c=(2)(2)+(4)(0)+(2)(3).
\]

\[
b\cdot c=4+0+6.
\]

\[
\boxed{b\cdot c=10}
\]

### Step 2: Compute the magnitudes

We already know that

\[
\|b\|=2\sqrt{6},\qquad \|c\|=\sqrt{13}.
\]

### Step 3: Compute the cosine of the angle

\[
\cos\theta_{bc}
=\frac{b\cdot c}{\|b\|\|c\|}.
\]

Substitute the values:

\[
\cos\theta_{bc}
=\frac{10}{(2\sqrt{6})(\sqrt{13})}.
\]

\[
=\frac{10}{2\sqrt{78}}.
\]

Therefore,

\[
\boxed{\cos\theta_{bc}=\frac{5}{\sqrt{78}}\approx0.5661}.
\]

The angle is

\[
\theta_{bc}=\cos^{-1}\left(\frac{5}{\sqrt{78}}\right).
\]

Thus,

\[
\boxed{\theta_{bc}\approx55.52^\circ}.
\]

## 4. Order the Pairs by Increasing Angle

The calculated values are summarized in the following table.

| Pair | Dot Product | Magnitudes | Cosine | Angle |
|---|---:|---|---:|---:|
| \((a,b)\) | \(12\) | \(\sqrt6,\ 2\sqrt6\) | \(1\) | \(0^\circ\) |
| \((a,c)\) | \(5\) | \(\sqrt6,\ \sqrt{13}\) | \(\frac{5}{\sqrt{78}}\approx0.5661\) | \(55.52^\circ\) |
| \((b,c)\) | \(10\) | \(2\sqrt6,\ \sqrt{13}\) | \(\frac{5}{\sqrt{78}}\approx0.5661\) | \(55.52^\circ\) |

Therefore, the pairs ordered by increasing angle are

\[
\boxed{(a,b)<(a,c)=(b,c)}.
\]

The pair \((a,b)\) has the smallest angle, \(0^\circ\). The other two pairs have equal angles of approximately \(55.52^\circ\).

## 5. Explain Why the Cosine for \(a\) and \(b\) Is \(1\) Even Though Their Lengths Are Different

The vectors are

\[
a=(1,2,1),\qquad b=(2,4,2).
\]

Notice that

\[
b=2a.
\]

Therefore, \(b\) is a positive scalar multiple of \(a\). Multiplying a vector by a positive scalar changes its magnitude but does not change its direction.

The magnitudes are

\[
\|a\|=\sqrt6,
\]

\[
\|b\|=2\sqrt6.
\]

Thus, the vectors have different lengths. However, they point in exactly the same direction.

Using the cosine formula,

\[
\cos\theta_{ab}
=\frac{a\cdot b}{\|a\|\|b\|}
=\frac{12}{12}=1.
\]

A cosine value of \(1\) corresponds to an angle of \(0^\circ\). Therefore, the vectors are parallel and point in the same direction.

**Geometric interpretation:** The dot-product cosine formula measures the angle between vectors independently of their lengths. The magnitudes in the denominator normalize the dot product, allowing us to compare directions rather than sizes.

## Final Results

\[
\boxed{\cos\theta_{ab}=1,\qquad \theta_{ab}=0^\circ}
\]

\[
\boxed{\cos\theta_{ac}=\frac{5}{\sqrt{78}},\qquad \theta_{ac}\approx55.52^\circ}
\]

\[
\boxed{\cos\theta_{bc}=\frac{5}{\sqrt{78}},\qquad \theta_{bc}\approx55.52^\circ}
\]

The increasing order of the angles is

\[
\boxed{\theta_{ab}<\theta_{ac}=\theta_{bc}}.
\]
