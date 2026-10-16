# Exercise 8. Row Operations and Their Reversibility

Given the matrix

$$
A=\begin{pmatrix}
1&2&-1\\
2&4&1\\
-1&1&3
\end{pmatrix}
$$

## 1. First Operation: \(R_2\leftarrow R_2-2R_1\)

The second row becomes the second row minus twice the first row.

$$
R_2=(2,4,1)-2(1,2,-1)
$$

$$
R_2=(2,4,1)-(2,4,-2)=(0,0,3)
$$

The resulting matrix is

$$
\boxed{
\begin{pmatrix}
1&2&-1\\
0&0&3\\
-1&1&3
\end{pmatrix}
}
$$

**Reverse operation:** \(R_2\leftarrow R_2+2R_1\).

## 2. Second Operation: \(R_3\leftarrow R_3+R_1\)

The third row becomes the third row plus the first row.

$$
R_3=(-1,1,3)+(1,2,-1)=(0,3,2)
$$

The resulting matrix is

$$
\boxed{
\begin{pmatrix}
1&2&-1\\
0&0&3\\
0&3&2
\end{pmatrix}
}
$$

**Reverse operation:** \(R_3\leftarrow R_3-R_1\).

## 3. Third Operation: Interchange \(R_2\) and \(R_3\)

We swap the second and third rows.

The resulting matrix is

$$
\boxed{
\begin{pmatrix}
1&2&-1\\
0&3&2\\
0&0&3
\end{pmatrix}
}
$$

**Reverse operation:** Interchange \(R_2\) and \(R_3\) again.

## 4. Conclusion

Each row operation is reversible. Adding or subtracting a multiple of another row can be undone by performing the opposite operation. Swapping two rows can be undone by swapping them again.

These operations are useful in Gaussian elimination because they simplify matrices while allowing us to reverse each step.
