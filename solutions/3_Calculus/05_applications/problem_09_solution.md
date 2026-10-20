
# Problem 9. Minimizing the Material Used for a Can

A closed cylinder has a fixed volume \(V\). Find the dimensions that minimize its surface area.

## 1. Write the Volume Constraint

Let:

- \(r\) be the radius of the cylinder.
- \(h\) be its height.
- \(V>0\) be its fixed volume.

The volume of a cylinder is

\[
V=\pi r^2h
\]

Therefore, the constraint is

\[
\boxed{\pi r^2h=V}
\]

## 2. Eliminate One Variable

Solve the volume constraint for \(h\):

\[
h=\frac{V}{\pi r^2}
\]

Since \(V>0\) and the radius must be positive,

\[
r>0
\]

## 3. Express the Surface Area as a Function of \(r\)

A closed cylinder has two circular ends and one curved lateral surface.

Its surface area is

\[
S=2\pi r^2+2\pi rh
\]

Substitute \(h=\frac{V}{\pi r^2}\):

\[
S(r)=2\pi r^2+
2\pi r\left(\frac{V}{\pi r^2}\right)
\]

Simplify:

\[
\boxed{S(r)=2\pi r^2+\frac{2V}{r}}
\]

The objective is to minimize \(S(r)\) for \(r>0\).

## 4. Find the Critical Point

Differentiate:

\[
S'(r)=4\pi r-\frac{2V}{r^2}
\]

Set the derivative equal to zero:

\[
4\pi r-\frac{2V}{r^2}=0
\]

Multiply by \(r^2\):

\[
4\pi r^3=2V
\]

Therefore,

\[
r^3=\frac{V}{2\pi}
\]

The optimal radius is

\[
\boxed{r=\sqrt[3]{\frac{V}{2\pi}}}
\]

## 5. Determine the Corresponding Height

Use the volume constraint:

\[
h=\frac{V}{\pi r^2}
\]

Since \(V=2\pi r^3\) at the critical point,

\[
h=\frac{2\pi r^3}{\pi r^2}
\]

Thus,

\[
\boxed{h=2r}
\]

## 6. Verify That It Is a Minimum

The second derivative is

\[
S''(r)=4\pi+\frac{4V}{r^3}
\]

For every \(r>0\),

\[
S''(r)>0
\]

Therefore, the critical point is a minimum.

Also, \(S(r)\to\infty\) as \(r\to0^+\) and as \(r\to\infty\), so this is the global minimum.

## Final Answers

1. Volume constraint: \(\boxed{\pi r^2h=V}\).
2. Height as a function of radius: \(\boxed{h=\frac{V}{\pi r^2}}\).
3. Surface area: \(\boxed{S(r)=2\pi r^2+\frac{2V}{r}}\).
4. Optimal radius: \(\boxed{r=\sqrt[3]{\frac{V}{2\pi}}}\).
5. Optimal height: \(\boxed{h=2r}\).

**Geometric interpretation:** The minimum amount of material is used when the cylinder's height equals its diameter.
