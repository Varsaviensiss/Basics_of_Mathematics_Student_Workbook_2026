
# Problem 12. Maximizing the Area of a Rectangular Museum Room

A rectangular museum room is built next to an existing wall. The wall forms one side of the rectangle, so no construction is needed on that side.

The two sides perpendicular to the wall cost 300 PLN per meter, and the side parallel to the wall costs 500 PLN per meter. The total budget is 30,000 PLN.

Find the dimensions that maximize the room's area.

## Step 1: Define the Variables

Let:

- \(x\) = the length of each side perpendicular to the wall, in meters.
- \(y\) = the length of the side parallel to the wall, in meters.

The area of the rectangular room is

\[
A=xy.
\]

## Step 2: Write the Budget Equation

There are two sides of length \(x\), each costing 300 PLN per meter. The third constructed side has length \(y\) and costs 500 PLN per meter.

Therefore, the total construction cost is

\[
300x+300x+500y=30000.
\]

Simplify:

\[
600x+500y=30000.
\]

Solve for \(y\):

\[
500y=30000-600x.
\]

\[
y=60-1.2x.
\]

## Step 3: Express the Area as a Function of One Variable

The area is

\[
A=xy.
\]

Substitute \(y=60-1.2x\):

\[
A(x)=x(60-1.2x).
\]

Expand:

\[
\boxed{A(x)=60x-1.2x^2}.
\]

## Step 4: Find the Critical Point

Differentiate the area function:

\[
A'(x)=60-2.4x.
\]

Set the derivative equal to zero:

\[
60-2.4x=0.
\]

\[
2.4x=60.
\]

\[
\boxed{x=25\text{ m}}.
\]

## Step 5: Verify the Maximum

Differentiate again:

\[
A''(x)=-2.4.
\]

Since

\[
A''(x)<0,
\]

the area function is concave down. Therefore, the critical point gives the maximum area.

## Step 6: Find the Other Dimension

Use the budget equation:

\[
y=60-1.2x.
\]

Substitute \(x=25\):

\[
y=60-1.2(25).
\]

\[
y=60-30.
\]

\[
\boxed{y=30\text{ m}}.
\]

## Step 7: Calculate the Maximum Area

\[
A=xy.
\]

\[
A=25(30).
\]

\[
\boxed{A_{\max}=750\text{ m}^2}.
\]

## Step 8: Check the Budget

The two perpendicular sides cost

\[
2(300)(25)=15000\text{ PLN}.
\]

The parallel side costs

\[
500(30)=15000\text{ PLN}.
\]

The total cost is

\[
15000+15000=30000\text{ PLN}.
\]

The budget is satisfied exactly.

## Final Answers

- **Each perpendicular side:** \(25\text{ m}\)
- **The parallel side:** \(30\text{ m}\)
- **Maximum area:** \(\boxed{750\text{ m}^2}\)
- **Total construction cost:** \(30,000\text{ PLN}\)
