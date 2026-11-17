# Section 1.1 --- Functions and Their Graphs

*Based on Thomas' Calculus: Early Transcendentals, 13th Edition*

## 1. What is a function?

A **function** assigns exactly one output to each input.

We commonly write:

$$
y=f(x)
$$

-   $x$ is the input (independent variable).
-   $f(x)$ or $y$ is the output (dependent variable).
-   A function must give only one output for each valid input.

**Example:**

$$
f(x)=x^2
$$

If $x=2$, then $f(2)=4$. If $x=-2$, then $f(-2)=4$.

Different inputs may have the same output, but one input cannot have two
different outputs.

## 2. Domain and range

-   **Domain:** The set of all permitted input values ($x$).
-   **Range:** The set of all output values ($y=f(x)$) produced by those
    inputs.

For example:

$$
f(x)=x^2
$$

Its domain is all real numbers, and its range is nonnegative real
numbers:

$$
D=(-\infty,\infty),\qquad R=[0,\infty)
$$

### Common restrictions when finding a domain

1.  **Denominators cannot be zero.**

    For $f(x)=\frac{1}{x-4}$, exclude $x=4$.

2.  **A real square root requires a nonnegative radicand.**

    For $f(x)=\sqrt{x-3}$, require $x-3\geq0$, so $x\geq3$.

3.  If a formula has no such restriction (for example, a polynomial),
    its domain is all real numbers.

Always check the expression and identify which input values make it
undefined.

## 3. Graphs of functions

The graph of $y=f(x)$ is the collection of points:

$$
(x,f(x))
$$

A graph shows how the output changes as the input changes. A function
can be represented by: - A formula (algebraically). - A graph
(visually). - A table of values (numerically).

### Vertical Line Test

A curve represents a function of $x$ if **no vertical line intersects
the curve more than once**.

-   If a vertical line crosses a curve twice or more, it is not a
    function of $x$.
-   A circle fails the test.
-   An upper or lower semicircle can pass the test.

## 4. Piecewise-defined functions

A piecewise-defined function uses different formulas on different parts
of its domain.

The absolute value function is an example:

$$
|x| =
\begin{cases}
x, & x\geq0\\
-x, & x<0
\end{cases}
$$

Examples:

$$
|5|=5,\qquad |-5|=5
$$

A piecewise function is still one function, provided each input has
exactly one assigned output.

## 5. Greatest and least integer functions

### Greatest integer (floor) function

The greatest integer function, written $\lfloor x\rfloor$, gives the
**greatest integer less than or equal to $x$**.

Examples:

$$
\lfloor 2.4\rfloor=2
$$

$$
\lfloor -1.2\rfloor=-2
$$

### Least integer (ceiling) function

The least integer function, written $\lceil x\rceil$, gives the
**smallest integer greater than or equal to $x$**.

Examples:

$$
\lceil 2.4\rceil=3
$$

$$
\lceil -1.2\rceil=-1
$$

For an integer $n$:

$$
\lfloor n\rfloor=\lceil n\rceil=n
$$

And:

$$
\lfloor x\rfloor=\lceil x\rceil
\quad\Longleftrightarrow\quad
x\in\mathbb Z
$$

## 6. Increasing and decreasing functions

A function is **increasing** on an interval if larger inputs always give
larger outputs.

For $x_1<x_2$:

$$
f(x_1)<f(x_2)
$$

A function is **decreasing** on an interval if larger inputs always give
smaller outputs.

For $x_1<x_2$:

$$
f(x_1)>f(x_2)
$$

The comparison must hold for every pair of points in the interval.

## 7. Even and odd functions (symmetry)

### Even function

A function is even if:

$$
f(-x)=f(x)
$$

Its graph is symmetric about the **$y$-axis**.

Example:

$$
f(x)=x^2
$$

### Odd function

A function is odd if:

$$
f(-x)=-f(x)
$$

Its graph is symmetric about the **origin** (a 180-degree rotation
leaves it unchanged).

Example:

$$
f(x)=x^3
$$

The domain must contain both $x$ and $-x$ for the relevant symmetry
test.

## 8. Common types of functions

### Linear functions

$$
f(x)=mx+b
$$

The graph is a straight line. $m$ is the slope and $b$ is the vertical
intercept.

A proportionality relationship has the form:

$$
y=kx
$$

where $k$ is a nonzero constant.

### Power functions

$$
f(x)=x^a
$$

where $a$ is a constant.

Examples include $x^2$, $x^3$, $x^{-1}$ and $\sqrt{x}$.

Important domain facts: - Positive integer powers are defined for all
real $x$. - $x^{-1}=1/x$ excludes $x=0$. - $\sqrt{x}$ requires
$x\geq0$. - $\sqrt[3]{x}$ is defined for all real $x$.

### Polynomials

A polynomial has the form:

$$
p(x)=a_nx^n+a_{n-1}x^{n-1}+\cdots+a_1x+a_0
$$

where $n$ is a nonnegative integer and the coefficients are real
numbers.

All polynomials have domain:

$$
(-\infty,\infty)
$$

A degree-1 polynomial is linear; a degree-2 polynomial is quadratic; a
degree-3 polynomial is cubic.

### Rational functions

A rational function is a ratio of polynomials:

$$
f(x)=\frac{p(x)}{q(x)}
$$

Its domain contains all real values for which:

$$
q(x)\neq0
$$

### Algebraic functions

These are functions constructed from polynomials using algebraic
operations: addition, subtraction, multiplication, division and taking
roots. Rational functions are included.

### Trigonometric functions

The six basic trigonometric functions are sine, cosine, tangent,
cotangent, secant and cosecant. Their graphs are periodic.

### Exponential functions

$$
f(x)=a^x,\qquad a>0,\quad a\neq1
$$

Their domain and range are:

$$
D=(-\infty,\infty),\qquad R=(0,\infty)
$$

An exponential function never equals zero.

### Logarithmic functions

$$
f(x)=\log_a x,\qquad a>0,\quad a\neq1
$$

Logarithmic functions are the inverse functions of exponential
functions. Their domain and range are:

$$
D=(0,\infty),\qquad R=(-\infty,\infty)
$$

### Transcendental functions

These are functions that are not algebraic. They include trigonometric,
inverse trigonometric, exponential and logarithmic functions.

## 9. Quick revision checklist

Before moving to Section 1.2, make sure you can:

-   Explain what makes a relation a function.
-   Find the domain and range of basic functions.
-   Apply the vertical line test.
-   Read and interpret a function graph.
-   Understand piecewise, floor and ceiling functions.
-   Identify increasing and decreasing intervals.
-   Test whether a function is even or odd.
-   Recognize common function families and their basic domain
    restrictions.

## 10. Important formulas at a glance

  ------------------------------------------------------------------------
  Concept                             Rule
  ----------------------------------- ------------------------------------
  Function                            One output for each valid input

  Vertical line test                  No vertical line crosses the graph
                                      more than once

  Floor                               $\lfloor x\rfloor$: greatest integer
                                      $\leq x$

  Ceiling                             $\lceil x\rceil$: smallest integer
                                      $\geq x$

  Even                                $f(-x)=f(x)$

  Odd                                 $f(-x)=-f(x)$

  Increasing                          $x_1<x_2\Rightarrow f(x_1)<f(x_2)$

  Decreasing                          $x_1<x_2\Rightarrow f(x_1)>f(x_2)$

  Rational function                   $p(x)/q(x)$, with $q(x)\neq0$
  ------------------------------------------------------------------------

------------------------------------------------------------------------

*End of Section 1.1 summary.*
