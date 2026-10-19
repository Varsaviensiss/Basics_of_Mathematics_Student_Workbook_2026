# Exercise 15. Complete Classification of a Line Relative to a Plane

## General Form

Let the line be

$$
L:\mathbf{x}=\mathbf{p}+t\mathbf{v}
$$

and the plane be

$$
\Pi:\mathbf{n}\cdot\mathbf{x}=d
$$

where \(\mathbf{p}\) is a point on the line, \(\mathbf{v}\) is its direction vector, and \(\mathbf{n}\) is the plane's normal vector.

Substitute the line into the plane equation:

$$
\mathbf{n}\cdot(\mathbf{p}+t\mathbf{v})=d
$$

Expand:

$$
\mathbf{n}\cdot\mathbf{p}+t(\mathbf{n}\cdot\mathbf{v})=d
$$

Rearrange:

$$
t(\mathbf{n}\cdot\mathbf{v})=d-\mathbf{n}\cdot\mathbf{p}
$$

This equation gives three possible cases.

## Case 1. One Intersection Point

Condition:

$$
\boxed{\mathbf{n}\cdot\mathbf{v}\neq0}
$$

Solve for the parameter:

$$
t=\frac{d-\mathbf{n}\cdot\mathbf{p}}{\mathbf{n}\cdot\mathbf{v}}
$$

There is exactly one intersection point.

### Example

Let

$$
L:(x,y,z)=(0,0,1)+t(0,0,-1)
$$

and

$$
\Pi:z=0
$$

Substitute the line's \(z\)-coordinate:

$$
1-t=0
$$

$$
t=1
$$

The intersection point is

$$
\boxed{Q=(0,0,0)}
$$

## Case 2. Parallel with No Common Points

Condition:

$$
\boxed{\mathbf{n}\cdot\mathbf{v}=0}
$$

and

$$
\boxed{\mathbf{n}\cdot\mathbf{p}\neq d}
$$

The line's direction is parallel to the plane, but its point does not lie in the plane.

### Example

Let

$$
L:(x,y,z)=(0,0,1)+t(1,0,0)
$$

and

$$
\Pi:z=0
$$

The direction vector and normal vector are

$$
\mathbf{v}=(1,0,0),\qquad \mathbf{n}=(0,0,1)
$$

Their dot product is

$$
\mathbf{n}\cdot\mathbf{v}=0
$$

However, the point \((0,0,1)\) does not satisfy \(z=0\).

Therefore,

$$
\boxed{L\parallel\Pi,\qquad L\cap\Pi=\varnothing}
$$

## Case 3. The Line Lies in the Plane

Condition:

$$
\boxed{\mathbf{n}\cdot\mathbf{v}=0}
$$

and

$$
\boxed{\mathbf{n}\cdot\mathbf{p}=d}
$$

The direction is parallel to the plane, and a point on the line lies in the plane. Therefore, every point on the line lies in the plane.

### Example

Let

$$
L:(x,y,z)=(0,0,0)+t(1,2,0)
$$

and

$$
\Pi:z=0
$$

The direction vector is

$$
\mathbf{v}=(1,2,0)
$$

The normal vector is

$$
\mathbf{n}=(0,0,1)
$$

Their dot product is

$$
\mathbf{n}\cdot\mathbf{v}=0
$$

The initial point \((0,0,0)\) satisfies the plane equation. Every point on the line has \(z=0\).

Therefore,

$$
\boxed{L\subset\Pi}
$$

## Summary Table

| Condition | Relative position |
|---|---|
| \(\mathbf{n}\cdot\mathbf{v}\neq0\) | One intersection point |
| \(\mathbf{n}\cdot\mathbf{v}=0\) and \(\mathbf{n}\cdot\mathbf{p}\neq d\) | Parallel, no common points |
| \(\mathbf{n}\cdot\mathbf{v}=0\) and \(\mathbf{n}\cdot\mathbf{p}=d\) | Line lies in the plane |

## Final Conclusion

The dot product \(\mathbf{n}\cdot\mathbf{v}\) determines whether the line's direction is parallel to the plane. If it is zero, checking one point on the line distinguishes between a line outside the plane and a line contained in it.
