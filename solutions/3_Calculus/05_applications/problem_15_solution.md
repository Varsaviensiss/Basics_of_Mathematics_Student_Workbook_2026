# Problem 15. Work Required to Empty a Conical Reservoir (Enrichment)

## Question

An inverted right circular cone has a top rim radius of $4\ \mathrm{m}$ and a height of $6\ \mathrm{m}$. Its vertex is at ground level, and it contains water to a depth of $4\ \mathrm{m}$ measured upward from the vertex. Take the water density to be $\rho=1000\ \mathrm{kg/m^3}$ and gravitational acceleration to be $g=9.8\ \mathrm{m/s^2}$.

Find the gravitational work required to pump all the water to the top rim.

1. Choose a vertical coordinate and find the radius of a horizontal slice.
2. Express the slice's volume, mass, and weight.
3. Find the distance each slice must be lifted.
4. Set up and evaluate the work integral, giving the result in joules and kilojoules.
5. Verify the result using the volume and center of mass of the water.

## Solution

### 1. Find the cross-sectional radius and area

Measure height $y$ upward from the vertex. The rim is at $y=6$, and the water occupies $0\le y\le4$.

```text
       \-----------------------/   y = 6 m, top rim
        \                     /
         \-------------------/     y = 4 m, water surface
          \                 /
           \---------------/       slice at height y
            \             /
              \         /
                \     /
                  \ /
                   V               y = 0, vertex
```

By similar triangles, the radius and area at height $y$ are

$$
r(y)=\frac{4}{6}y=\frac23y,
\qquad
A(y)=\pi r(y)^2=\frac{4\pi}{9}y^2.
$$

### 2. Find the weight of a slice and its lifting distance

A horizontal slice of thickness $dy$ has volume $dV=A(y)\,dy$, mass $dm=\rho\,dV$, and weight $dF=g\,dm$. Thus

$$
dF=\rho g\frac{4\pi}{9}y^2\,dy.
$$

The slice must be raised from height $y$ to the rim at height $6$, so its lifting distance is $D(y)=6-y$.

### 3. Set up and evaluate the work integral

For a thin slice of thickness $\Delta y$, the work is approximately its weight times its lifting distance. Summing these contributions and taking the Riemann-sum limit gives

$$
\begin{aligned}
W
&=\int_0^4 \rho g A(y)(6-y)\,dy\\
&=\frac{4\pi\rho g}{9}\int_0^4(6y^2-y^3)\,dy\\
&=\frac{4\pi\rho g}{9}\left[2y^3-\frac{y^4}{4}\right]_0^4\\
&=\frac{4\pi\rho g}{9}(128-64)
=\frac{256\pi\rho g}{9}.
\end{aligned}
$$

Substituting $\rho g=9800\ \mathrm{N/m^3}$ gives

$$
W=\frac{2{,}508{,}800\pi}{9}\ \mathrm{J}
=\frac{12{,}544\pi}{45}\ \mathrm{kJ}
\approx875{,}736.41\ \mathrm{J}
\approx875.74\ \mathrm{kJ}.
$$

### 4. Verify using the center of mass

The water forms a cone of height $4\ \mathrm{m}$ and surface radius $r(4)=8/3\ \mathrm{m}$. Its volume and mass are

$$
V=\frac13\pi\left(\frac83\right)^2(4)
=\frac{256\pi}{27}\ \mathrm{m^3},
\qquad
M=\rho V=\frac{256{,}000\pi}{27}\ \mathrm{kg}.
$$

The centroid of a uniform solid cone lies three-quarters of the way from its vertex to its base. The water's center of mass is therefore at $\bar y=\frac34(4)=3\ \mathrm{m}$. Raising all the water to the rim increases its gravitational potential energy by

$$
W=Mg(6-\bar y)
=\frac{256{,}000\pi}{27}\cdot9.8\cdot3
=\frac{2{,}508{,}800\pi}{9}\ \mathrm{J},
$$

which agrees with the slice calculation. The units are $\mathrm{N\cdot m}=\mathrm{J}$.
