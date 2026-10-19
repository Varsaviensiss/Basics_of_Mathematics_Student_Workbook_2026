# Exercise 11. Plane Containing a Line and a Point

## Given

$$
L:(x,y,z)=(1,0,2)+t(1,1,-1)
$$

$$
P=(0,2,1)
$$

## 1. Construct Two Independent Direction Vectors

The line's direction vector is

$$
\boxed{\mathbf{v}=(1,1,-1)}
$$

A point on the line is \(A=(1,0,2)\). Construct a vector from \(A\) to \(P\):

$$
\overrightarrow{AP}=P-A
$$

$$
=(0-1,2-0,1-2)
$$

$$
\boxed{\overrightarrow{AP}=(-1,2,-1)}
$$

These vectors are not scalar multiples, so they determine a plane.

## 2. Find a Normal Vector

Take the cross product:

$$
\mathbf{n}=\mathbf{v}\times\overrightarrow{AP}
$$

$$
\mathbf{n}=
\begin{vmatrix}
\mathbf{i}&\mathbf{j}&\mathbf{k}\\
1&1&-1\\
-1&2&-1
\end{vmatrix}
$$

$$
=\mathbf{i}(-1+2)-\mathbf{j}(-1-1)+\mathbf{k}(2+1)
$$

$$
\boxed{\mathbf{n}=(1,2,3)}
$$

## 3. Find the Plane Equation

Using the normal vector:

$$
x+2y+3z=d
$$

Substitute \(A=(1,0,2)\):

$$
1+2(0)+3(2)=d
$$

$$
d=7
$$

Therefore,

$$
\boxed{x+2y+3z=7}
$$

## 4. Check the Entire Line

Substitute the parametric coordinates

$$
x=1+t,\quad y=t,\quad z=2-t
$$

into the plane equation:

$$
(1+t)+2t+3(2-t)=7
$$

$$
1+t+2t+6-3t=7
$$

$$
7=7
$$

The equation holds for every real \(t\), so the entire line lies in the plane.

## 5. Check the Given Point

Substitute \(P=(0,2,1)\):

$$
0+2(2)+3(1)=7
$$

$$
4+3=7
$$

The point also lies in the plane.

## Final Answer

$$
\boxed{x+2y+3z-7=0}
$$
