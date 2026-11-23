# Thomas' Calculus — Section 1.2 Summary
## Combining Functions; Shifting and Scaling Graphs

*Based on Thomas' Calculus: Early Transcendentals, 13th Edition.*

This section teaches two main skills:

1. **Combining functions** to create new functions.
2. **Transforming graphs** by shifting, stretching, compressing, and reflecting them.

The central idea is that you can build new functions from existing ones without starting from scratch.

## 1. Combining functions

Suppose we have two functions, $f(x)$ and $g(x)$. We can combine them using the four basic arithmetic operations.

| Operation | Formula |
|---|---|
| Addition | $(f+g)(x)=f(x)+g(x)$ |
| Subtraction | $(f-g)(x)=f(x)-g(x)$ |
| Multiplication | $(fg)(x)=f(x)g(x)$ |
| Division | $\left(\frac fg\right)(x)=\frac{f(x)}{g(x)}$ |

We can also multiply a function by a constant:

$(cf)(x)=cf(x)$

### Domain rules

- For addition, subtraction, and multiplication, the input must belong to both functions' domains.
- For division, the input must belong to both domains, and the denominator must not equal zero.

So the domain is generally the intersection of the original domains, with any additional restrictions required by division.

### Example

Suppose $f(x)=2x$ and $g(x)=x+1$.

Addition:

$(f+g)(x)=2x+(x+1)=3x+1$

Multiplication:

$(fg)(x)=2x(x+1)=2x^2+2x$

Division:

$\left(\frac fg\right)(x)=\frac{2x}{x+1},\qquad x\ne-1$

## 2. Composite functions

A composite function means using the output of one function as the input of another function.

It is written as:

$(f\circ g)(x)=f(g(x))$

Read this as “f composed with g.”

The order matters:

1. First calculate $g(x)$.
2. Then use that result as the input to $f$.

### Example

Suppose $f(x)=2x$ and $g(x)=x+1$. Find $(f\circ g)(x)$.

First, take the inner function:

$g(x)=x+1$

Substitute it into $f$:

$f(g(x))=2(x+1)$

Simplify:

$\boxed{(f\circ g)(x)=2x+2}$

Reverse the order:

$(g\circ f)(x)=g(f(x))=2x+1$

Notice that, in general:

$f\circ g\ne g\circ f$

**Domain of a composite function:** The input must belong to the domain of the inner function, and the inner function's output must belong to the domain of the outer function.

## 3. Shifting a graph

A shift moves a graph without changing its basic shape.

### A. Vertical shifts

$y=f(x)+k$

- If $k>0$, the graph moves upward by $k$ units.
- If $k<0$, the graph moves downward by $|k|$ units.

For $y=x^2$:

- $y=x^2+3$: moves up 3 units.
- $y=x^2-2$: moves down 2 units.

### B. Horizontal shifts

$y=f(x+h)$

- If $h>0$, the graph moves left by $h$ units.
- If $h<0$, the graph moves right by $|h|$ units.

For $y=x^2$:

- $y=(x+3)^2$: moves left 3 units.
- $y=(x-2)^2$: moves right 2 units.

**Remember:** Horizontal shifts work in the opposite direction to the sign inside the function.

## 4. Scaling and reflecting a graph

Scaling changes the size of a graph. Reflection flips it across an axis.

### A. Vertical scaling

$y=cf(x)$

- If $c>1$, the graph is stretched vertically by a factor of $c$.
- If $0<c<1$, the graph is compressed vertically by a factor of $1/c$.

Example: $y=3x^2$ is a vertical stretch of $y=x^2$ by a factor of 3.

### B. Horizontal scaling

$y=f(cx)$

- If $c>1$, the graph is compressed horizontally by a factor of $c$.
- If $0<c<1$, the graph is stretched horizontally by a factor of $1/c$.

A horizontal stretch by a factor of $c$ can also be written:

$y=f\left(\frac{x}{c}\right)$

### C. Reflection

| Formula | Transformation |
|---|---|
| $y=-f(x)$ | Reflection across the x-axis |
| $y=f(-x)$ | Reflection across the y-axis |

For example, if $f(x)=x^2$, then $y=-x^2$ is the reflection of the original parabola across the x-axis.

## 5. Combining multiple transformations

You can apply more than one transformation to the same function.

Example:

$y=|x-2|-1$

Start with the basic graph $y=|x|$:

1. $x-2$ shifts the graph 2 units right.
2. $-1$ shifts the graph 1 unit down.

The same idea applies to more complicated functions.

## 6. Quick reference sheet

| Transformation | Formula | Effect |
|---|---|---|
| Vertical shift up | $f(x)+k$, $k>0$ | Up $k$ units |
| Vertical shift down | $f(x)-k$, $k>0$ | Down $k$ units |
| Horizontal shift left | $f(x+h)$, $h>0$ | Left $h$ units |
| Horizontal shift right | $f(x-h)$, $h>0$ | Right $h$ units |
| Vertical stretch | $cf(x)$, $c>1$ | Stretch vertically |
| Vertical compression | $cf(x)$, $0<c<1$ | Compress vertically |
| Horizontal compression | $f(cx)$, $c>1$ | Compress horizontally |
| Horizontal stretch | $f(x/c)$, $c>1$ | Stretch horizontally |
| Reflection across x-axis | $-f(x)$ | Flip vertically |
| Reflection across y-axis | $f(-x)$ | Flip horizontally |

## 7. What you should understand before moving on

- [ ] Add, subtract, multiply, and divide two functions.
- [ ] Determine the domain of a combined function.
- [ ] Understand and evaluate composite functions.
- [ ] Understand why $f(g(x))$ and $g(f(x))$ can be different.
- [ ] Shift graphs horizontally and vertically.
- [ ] Stretch and compress graphs.
- [ ] Reflect graphs across the x-axis and y-axis.
- [ ] Combine multiple graph transformations.

## 8. Why this matters for robotics

These concepts are useful because robotics involves mathematical functions that describe physical quantities and transformations.

- **Function composition:** A robot's position can depend on joint angles through several connected mathematical functions.
- **Shifting and scaling:** Coordinate systems, sensor measurements, and physical quantities often require changes of scale and reference.
- **Reflection:** Changing coordinate directions can involve sign changes and reflections.

You will encounter more advanced versions of these ideas when studying robotics kinematics and coordinate transformations.

## Main takeaway

Section 1.1 taught you what functions are. Section 1.2 teaches you how to combine functions and transform their graphs.
