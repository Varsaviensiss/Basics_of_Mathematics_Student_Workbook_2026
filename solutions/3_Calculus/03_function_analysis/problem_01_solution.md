Tabii abi. İlk soruyu önceki yaptıklarımız gibi, İngilizce, formüllü, işaret tablosu içeren ve sonucu kutu içine alınmış, GitHub Markdown dosyasına doğrudan kopyalanabilir şekilde hazırladım.

# Problem 1. A Cubic Polynomial

Analyze the monotonicity and extrema of the function

[\
f(x)=x^3-3x^2+2.\
]

## Step 1. Domain

Since (f(x)) is a polynomial, it is defined for all real numbers.

[\
\boxed{D_f=\mathbb{R}}\
]

## Step 2. Calculate the First Derivative

Differentiate the function:

[\
f(x)=x^3-3x^2+2\
]

[\
f'(x)=3x^2-6x\
]

Factor the derivative:

[\
f'(x)=3x(x-2)\
]

Find the critical points by setting the derivative equal to zero:

[\
f'(x)=0\
]

[\
3x(x-2)=0\
]

Therefore,

[\
x=0 \quad \text{or} \quad x=2\
]

The critical numbers are

[\
\boxed{x_1=0,\qquad x_2=2}\
]

## Step 3. Determine the Sign of the First Derivative

The critical numbers divide the real line into three intervals:

[\
(-\infty,0),\qquad (0,2),\qquad (2,\infty)\
]

Recall that

[\
f'(x)=3x(x-2).\
]

Since (3) is positive, the sign of the derivative depends on the signs of (x) and (x-2).

### Sign analysis

- For (x\in(-\infty,0)), both (x) and (x-2) are negative. Therefore, (f'(x)>0).
- For (x\in(0,2)), (x) is positive and (x-2) is negative. Therefore, (f'(x)<0).
- For (x\in(2,\infty)), both factors are positive. Therefore, (f'(x)>0).

### First derivative sign table

| Interval      | Sign of (x) | Sign of (x-2) | Sign of (f'(x)) | Behavior   |
| ------------- | ----------- | ------------- | --------------- | ---------- |
| ((-\infty,0)) | (-)         | (-)           | (+)             | Increasing |
| ((0,2))       | (+)         | (-)           | (-)             | Decreasing |
| ((2,\infty))  | (+)         | (+)           | (+)             | Increasing |

## Step 4. Determine the Local Maximum and Minimum

### At (x=0)

The derivative changes from positive to negative:

[\
+\ \longrightarrow\ -\
]

Therefore, (x=0) is a local maximum.

Calculate the function value:

[\
f(0)=0^3-3(0)^2+2\
]

[\
f(0)=2\
]

Hence, the local maximum point is

[\
\boxed{M=(0,2)}\
]

### At (x=2)

The derivative changes from negative to positive:

[\
-\ \longrightarrow\ +\
]

Therefore, (x=2) is a local minimum.

Calculate the function value:

[\
f(2)=2^3-3(2)^2+2\
]

[\
f(2)=8-12+2\
]

[\
f(2)=-2\
]

Hence, the local minimum point is

[\
\boxed{m=(2,-2)}\
]

## Step 5. Complete Monotonicity Table

The variation table summarizes the derivative signs and the behavior of the function.

| (x)     | ((-\infty,0)) | (0)           | ((0,2))    | (2)           | ((2,\infty)) |
| ------- | ------------- | ------------- | ---------- | ------------- | ------------ |
| (f'(x)) | (+)           | (0)           | (-)        | (0)           | (+)          |
| (f(x))  | Increasing    | Local maximum | Decreasing | Local minimum | Increasing   |

The function values at the critical points are

[\
f(0)=2,\qquad f(2)=-2.\
]

## Step 6. Analyze the End Behavior

The highest-degree term is (x^3), which determines the end behavior.

As (x\to-\infty),

[\
\lim\_{x\to-\infty}(x^3-3x^2+2)=-\infty.\
]

As (x\to+\infty),

[\
\lim\_{x\to+\infty}(x^3-3x^2+2)=+\infty.\
]

Therefore,

[\
\boxed{\lim\_{x\to-\infty}f(x)=-\infty}\
]

[\
\boxed{\lim\_{x\to+\infty}f(x)=+\infty}\
]

The function has no absolute maximum or absolute minimum on (\mathbb{R}), because it is unbounded above and below.

## Step 7. Sketch the Graph

The graph:

1. Rises from the lower left.
2. Reaches a local maximum at (M=(0,2)).
3. Decreases until it reaches a local minimum at (m=(2,-2)).
4. Rises toward (+\infty).

The (x)-intercepts can also help with the sketch. Solve

[\
x^3-3x^2+2=0.\
]

Since (x=1) is a root, factor the polynomial:

[\
x^3-3x^2+2=(x-1)(x^2-2x-2).\
]

Solve the quadratic equation:

[\
x^2-2x-2=0\
]

[\
x=\frac{2\pm\sqrt{4+8}}{2}\
]

[\
x=1\pm\sqrt{3}.\
]

Thus, the three (x)-intercepts are

[\
\boxed{x=1-\sqrt3,\quad x=1,\quad x=1+\sqrt3}.\
]

A qualitative sketch is shown below.

```
 y
 ↑
 3 |
 2 |                ● M(0,2)
   |              /     \
 1 |             /       \
 0 |----●-------/---------●----------------●----→ x
   |  1-√3               1              1+√3
-1 |                       \             /
-2 |                         ● m(2,-2)
   |                       /             \
   |
```

*The sketch is schematic and not to scale.*

## Final Answer

**Domain**

[\
\boxed{D_f=\mathbb{R}}\
]

**Critical numbers**

[\
\boxed{x=0,\qquad x=2}\
]

**Intervals of increase**

[\
\boxed{(-\infty,0)\cup(2,\infty)}\
]

**Interval of decrease**

[\
\boxed{(0,2)}\
]

**Local maximum**

[\
\boxed{M=(0,2)}\
]

**Local minimum**

[\
\boxed{m=(2,-2)}\
]

**End behavior**

[\
\boxed{\lim\_{x\to-\infty}f(x)=-\infty,\qquad\
\lim\_{x\to+\infty}f(x)=+\infty}\
]

Add the full variation tableFix the graph sketch coordinates
