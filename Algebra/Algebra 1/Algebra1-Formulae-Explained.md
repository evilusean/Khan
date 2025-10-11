## 📝 Algebra 1 Essential Formulas: Detailed Explanations & Breakdowns

---

## I. Linear Equations and Graphs

**Slope Formula:**
$$m = \frac{y_2 - y_1}{x_2 - x_1}$$
> **Description:** This formula calculates the **slope ($m$)** (or rate of change) of a line. The slope quantifies the **steepness and direction** of the line.
> **Breakdown:**
> * $m$: Represents the slope, defined as the ratio of **Vertical Change (Rise)** to **Horizontal Change (Run)**.
> * $(y_2 - y_1)$: The change in the $y$-coordinates (Rise).
> * $(x_2 - x_1)$: The change in the $x$-coordinates (Run).
> **Usage:** Use this when given **two points** on a line, $(x_1, y_1)$ and $(x_2, y_2)$. The order of subtraction must be consistent in both the numerator and the denominator.

**Slope-Intercept Form:**
$$y = mx + b$$
> **Description:** This is the most intuitive form for graphing a line. It defines $y$ as a function of $x$ based on the line's key properties.
> **Breakdown:**
> * $m$: The **slope** (rate of change). A positive $m$ means the line rises from left to right; a negative $m$ means it falls.
> * $b$: The **$y$-intercept**. This is the specific point **$(0, b)$** where the line crosses the vertical $y$-axis.
> **Usage:** To graph the line, start at $b$ (the initial value), and then use $m = \frac{\text{rise}}{\text{run}}$ to find subsequent points. Also used to easily identify the properties of any linear function.

**Standard Form:**
$$Ax + By = C$$
> **Description:** A general form where the $x$ and $y$ variables are on the same side. $A$, $B$, and $C$ are typically required to be integers (whole numbers).
> **Breakdown:**
> * $A, B, C$: Integer coefficients and constant. This form is often used to model real-world problems involving limited resources (e.g., $Ax + By$ is the total cost).
> **Usage:** Most useful for solving **systems of linear equations** using the **Elimination Method** and for quickly finding the $x$ and $y$ intercepts by setting the opposite variable to zero.

**Point-Slope Form:**
$$y - y_1 = m(x - x_1)$$
> **Description:** This form allows you to write the equation of a line if you know the slope and only one point. It is derived directly from the Slope Formula.
> **Breakdown:**
> * $m$: The slope.
> * $(x_1, y_1)$: A single, specific point on the line.
> * $(x, y)$: Represents any other point on the line.
> **Usage:** This is the best starting point when given a slope and a point. It can be algebraically rearranged (by distributing $m$ and adding $y_1$) to the Slope-Intercept Form.

**Distance Formula:**
$$d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$
> **Description:** Calculates the straight-line distance ($d$) between two points, $(x_1, y_1)$ and $(x_2, y_2)$. It is a direct application of the **Pythagorean Theorem** ($a^2 + b^2 = c^2$) on the coordinate plane.
> **Breakdown:**
> * $(x_2 - x_1)^2$: Represents the square of the horizontal change ($\Delta x^2$).
> * $(y_2 - y_1)^2$: Represents the square of the vertical change ($\Delta y^2$).
> * The final square root gives you the hypotenuse length ($d$).
> **Usage:** Substitute the coordinates, perform the subtraction and squaring *first*, then add the results, and finally take the square root.

**Midpoint Formula:**
$$\left(\frac{x_1 + x_2}{2},\ \frac{y_1 + y_2}{2}\right)$$
> **Description:** Finds the coordinates of the **exact center point** (midpoint) of the line segment connecting two endpoints.
> **Breakdown:**
> * The formula is essentially calculating the **average** (mean) of the $x$-coordinates and the average of the $y$-coordinates.
> **Usage:** Used to bisect a line segment or find the center of a figure (like the center of a circle from two points on its diameter).

**Parallel Lines:**
$$m_1 = m_2$$
> **Description:** Lines that lie in the same plane and never intersect.
> **Usage:** To be parallel, the lines **must have the exact same slope**.

**Perpendicular Lines:**
$$m_1 = -\frac{1}{m_2}$$
> **Description:** Lines that intersect at a **$90^\circ$ (right) angle**.
> **Usage:** Their slopes must be **negative reciprocals**. (Take the original slope, flip the fraction, and change the sign). If $m_1 \cdot m_2 = -1$, they are perpendicular.

---

## II. Laws of Exponents

**Product Rule:**
$$a^m \cdot a^n = a^{m+n}$$
> **Description:** When multiplying exponential expressions with the **same base ($a$)**, you **add** the exponents.
> **Breakdown:** The rule works because you are simply counting the total factors being multiplied. Example: $x^2 \cdot x^3 = (x \cdot x) \cdot (x \cdot x \cdot x) = x^5$.

**Quotient Rule:**
$$\frac{a^n}{a^m} = a^{n-m}$$
> **Description:** When dividing exponential expressions with the **same base ($a$)**, you **subtract** the exponent of the denominator ($m$) from the exponent of the numerator ($n$).
> **Breakdown:** The subtraction represents the cancellation of common factors in the numerator and denominator.

**Power of a Power Rule:**
$$(a^m)^n = a^{m \cdot n}$$
> **Description:** When an exponential term is raised to an external power, you **multiply** the exponents.
> **Breakdown:** Example: $(x^3)^2 = x^3 \cdot x^3$. Applying the Product Rule gives $x^{3+3} = x^6$, which is the same as $x^{3 \cdot 2}$.

**Zero Exponent Rule:**
$$a^0 = 1$$
> **Description:** Any non-zero base ($a$) raised to the power of zero is **always equal to 1**.
> **Breakdown:** This is derived from the Quotient Rule: $\frac{a^n}{a^n} = a^{n-n} = a^0$. Since any number divided by itself is 1, $a^0$ must be 1.

**Negative Exponent Rule:**
$$a^{-m} = \frac{1}{a^m}$$
> **Description:** A term with a negative exponent is equal to the reciprocal of the term with a positive exponent.
> **Breakdown:** The negative sign dictates a move to the opposite side of the fraction bar (numerator $\leftrightarrow$ denominator) to change the sign of the exponent. Example: $\frac{1}{x^{-2}} = x^2$.

---

## III. Polynomials and Factoring

**Difference of Squares:**
$$a^2 - b^2 = (a-b)(a+b)$$
> **Description:** This formula works in two ways: it's used to **factor** a binomial (left side to right side), or to quickly multiply two **conjugate binomials** (right side to left side).
> **Breakdown:** The middle terms ($+ab$ and $-ab$) cancel out when multiplying the conjugates, leaving only the difference of the squared terms.

**Perfect Square Trinomial 1:**
$$a^2 + 2ab + b^2 = (a+b)^2$$
> **Description:** The result of squaring a binomial with a plus sign.
> **Usage:** Used for factoring: if the first and last terms are perfect squares and the middle term is **twice the product** of their square roots, it's a perfect square trinomial.

**Perfect Square Trinomial 2:**
$$a^2 - 2ab + b^2 = (a-b)^2$$
> **Description:** The result of squaring a binomial with a minus sign.
> **Usage:** Used for factoring when the first and last terms are perfect squares and the middle term is **negative twice the product** of their square roots.

**FOIL Method:**
First, Outer, Inner, Last (for $$(a+b)(c+d)$$)
> **Description:** A systematic way to remember the four products necessary when **multiplying two binomials** (expressions with two terms).
> **Breakdown:** $\mathbf{F} = a \cdot c$; $\mathbf{O} = a \cdot d$; $\mathbf{I} = b \cdot c$; $\mathbf{L} = b \cdot d$. After multiplying, always combine the resulting $\mathbf{O}$ and $\mathbf{I}$ terms if they are like terms.

---

## IV. Quadratic Equations

**Standard Form:**
$$ax^2 + bx + c = 0$$
> **Description:** The required form for a quadratic equation (a polynomial of degree 2, whose graph is a parabola). All terms are collected on one side, set equal to zero.
> **Breakdown:** $a$ is the leading coefficient (determines parabola's direction and width), $b$ is the linear coefficient, and $c$ is the constant term (the $y$-intercept).

**Quadratic Formula:**
$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$
> **Description:** A universal tool for finding the **roots** (solutions, zeros, or $x$-intercepts) of **any** quadratic equation in standard form.
> **Breakdown:**
> * The **$\pm$** sign is key: it indicates there are usually two solutions (or one repeated solution).
> * $(-b / 2a)$ is the axis of symmetry (and the $x$-coordinate of the vertex).
> * The entire $\pm \sqrt{\dots}$ part determines the distance from the axis of symmetry to the roots.

**Discriminant:**
$$\Delta = b^2 - 4ac$$
> **Description:** The expression **inside the square root** of the Quadratic Formula. It determines the nature and number of the roots without fully solving the equation.
> **Breakdown:**
> * If $\Delta > 0$ (positive): **Two distinct real solutions** (The parabola crosses the $x$-axis twice).
> * If $\Delta = 0$: **One real solution** (The parabola touches the $x$-axis at one point, the vertex).
> * If $\Delta < 0$ (negative): **No real solutions** (The parabola does not cross the $x$-axis).

**Vertex (x-coordinate):**
$$x = -\frac{b}{2a}$$
> **Description:** This formula finds the **$x$-coordinate** of the **vertex** of the parabola, which is the point of maximum or minimum value. This line is called the **axis of symmetry**.
> **Usage:** Substitute $a$ and $b$ from the standard form. Then, plug this resulting $x$-value back into the original quadratic equation to find the corresponding $y$-coordinate of the vertex.

---

## V. Sequences

**Arithmetic Sequence (Explicit):**
$$a_n = a_1 + (n-1)d$$
> **Description:** This **Explicit Formula** allows you to calculate the value of **any term** ($a_n$) in a sequence where the terms increase or decrease by a **constant difference**.
> **Breakdown:**
> * $a_n$: The $n$-th term you want to find.
> * $a_1$: The value of the first term.
> * $n$: The term number (position in the sequence, e.g., 5th term is $n=5$).
> * $d$: The **common difference** (the amount added or subtracted each time).
> * $(n-1)d$: Represents the total distance traveled from the first term to the $n$-th term.

**Geometric Sequence (Explicit):**
$$a_n = a_1 \cdot r^{n-1}$$
> **Description:** This **Explicit Formula** calculates the value of **any term** ($a_n$) in a sequence where the terms change by a **constant ratio** (multiplication).
> **Breakdown:**
> * $r$: The **common ratio** (the amount multiplied each time).
> * $r^{n-1}$: Represents the total times the ratio has been multiplied, starting after the first term.

---

## VI. Inverse Functions

**Definition:**
If $f(x)$ is a function, its inverse $f^{-1}(x)$ satisfies $f(f^{-1}(x)) = x$ and $f^{-1}(f(x)) = x$.
> **Description:** An inverse function, denoted $f^{-1}(x)$, is one that **undoes** the work of the original function $f(x)$.
> **Breakdown:** The process of applying the function and then its inverse (or vice-versa) results in the original input, $x$. Graphically, the inverse is the reflection of the original function across the line $y=x$.

**Finding the Inverse:**

1. Replace $f(x)$ with $y$.
2. Solve for $x$ in terms of $y$.
3. Swap $x$ and $y$.
4. Write as $f^{-1}(x)$.

**Example:**
If $f(x) = 2x + 3$, then $f^{-1}(x) = \frac{x - 3}{2}$
> **Explanation:** This is the universal algebraic procedure for finding an inverse. **Step 3 (swapping $x$ and $y$)** is the fundamental mathematical action that defines the inverse relationship.

---
## VII. Rational Functions & Variations

**Rational Function :** A function of the form:
$$f(x) = \frac{P(x)}{Q(x)}$$
where $P$ and $Q$ are polynomials and $Q(x) \neq 0$.
> **Description:** A function that is the ratio of two polynomials.
> **Breakdown:** The crucial mathematical restriction is that the **denominator $Q(x)$ can never equal zero** because division by zero is undefined. Setting $Q(x) = 0$ identifies values excluded from the domain, which are often the locations of **vertical asymptotes**.

**Direct Variation:**
$$y = kx \quad \text{or} \quad y \propto x$$
> **Description:** $y$ varies directly with $x$. This means $y$ is directly proportional to $x$.
> **Breakdown:** The ratio $\frac{y}{x}$ is always a **constant ($k$)**, the **constant of variation**. As one variable increases, the other increases at the same rate. The graph is a straight line through the origin $(0,0)$.

**Inverse Variation:**
$$yx = k$$
$$y = \frac{k}{x} \quad \text{or} \quad y \propto \frac{1}{x}$$
> **Description:** $y$ varies inversely with $x$.
> **Breakdown:** The **product** $y \cdot x$ is always a **constant ($k$)**. As $x$ increases, $y$ decreases proportionally (and vice-versa). The graph is a hyperbola.

**Joint Variation:**
$$y = kxz$$
> **Description:** $y$ varies directly with **two or more** variables ($x$ and $z$).
> **Usage:** Use a given set of values for $y, x,$ and $z$ to solve for the constant $k$, and then write the complete variation equation.

**Combined Variation:**
$$y = \frac{kx}{z}$$
> **Description:** A relationship combining direct and inverse variation. $y$ varies **directly** with $x$ and **inversely** with $z$.

---
## VIII. Radicals and Square Roots

**Square Root:**
$$\sqrt{x}$$
> **Description:** Refers to the **principal (positive) square root**. Asks: "What non-negative number multiplied by itself equals $x$?"
> **Restriction:** For real numbers, the radicand ($x$) must be **non-negative** ($x \geq 0$).

**Cube Root:**
$$\sqrt[3]{x}$$
> **Description:** The inverse operation of cubing a number. Asks: "What number multiplied by itself three times equals $x$?"
> **Note:** The radicand ($x$) **can be negative** for cube roots.

**nth Root:**
$$\sqrt[n]{x}$$
> **Description:** The generalized radical form where $n$ is the **index** (or degree).
> **Note:** If $n$ is **even**, $x$ must be $\geq 0$. If $n$ is **odd**, $x$ can be any real number.

**Properties:**

$$\sqrt{a^2} = |a|$$
> **Description:** The square root of a perfect square is the **absolute value** of the term.
> **Reason:** This ensures the result is always positive, as the $\sqrt{}$ symbol means the principal (positive) root.

$$\sqrt{ab} = \sqrt{a} \cdot \sqrt{b}$$
> **Description:** The square root of a product can be split into the product of the square roots.
> **Usage:** This is the primary rule for **simplifying radicals** by factoring out the largest perfect square (e.g., $\sqrt{72} = \sqrt{36 \cdot 2} = 6\sqrt{2}$).

$$\sqrt{\frac{a}{b}} = \frac{\sqrt{a}}{\sqrt{b}}$$
> **Description:** The square root of a quotient can be split into the quotient of the square roots.
> **Usage:** Used in the process of **rationalizing the denominator** (ensuring no radical remains in the denominator).

$$\sqrt{a^2 + b^2}$$
> **Crucial Note:** This expression **cannot be simplified** to $a + b$. It is a common algebraic error to assume you can split the root across the addition sign.
> **Context:** This exact form appears inside the **Distance Formula**.
## IX. Polynomial Division and Roots

### 💡 Synthetic Division and The Remainder Theorem

These tools are used to quickly divide polynomials by linear factors and evaluate polynomials at specific values.

---

#### 1. Synthetic Division

Synthetic division is the rapid method for dividing a **Dividend Polynomial, $\mathbf{P(x)}$**, by a **linear Divisor** of the form $\mathbf{(x - k)}$.

* **Divisor Form:** $\mathbf{(x - k)}$
* **Term Used for Division:** $\mathbf{k}$ (the root/zero of the divisor).

**Setup Notation:**
The divisor $\mathbf{(x - k)}$ is represented by the root $\mathbf{k}$. The $\mathbf{c_n}$ terms are the coefficients of $\mathbf{P(x)}$ (use $\mathbf{0}$ for missing powers).

$$\mathbf{k} \text{ | } \mathbf{c_n} \quad \mathbf{c_{n-1}} \quad \mathbf{\dots} \quad \mathbf{c_1} \quad \mathbf{c_0}$$

**Result (The Quotient $\mathbf{Q(x)}$ and Remainder $\mathbf{R}$):**
The result consists of the **Quotient Polynomial, $\mathbf{Q(x)}$**, and a **constant Remainder, $\mathbf{R}$**. The degree of $\mathbf{Q(x)}$ is always one less than the degree of $\mathbf{P(x)}$.

$$\mathbf{\frac{P(x)}{x - k} = Q(x) + \frac{R}{x - k}}$$

---

#### 2. The Remainder Theorem

This theorem provides a shortcut to finding the remainder of polynomial division, which is equivalent to evaluating the function.

**Formula:**
If $\mathbf{P(x)}$ is divided by $\mathbf{(x - k)}$, the remainder $\mathbf{R}$ is equal to the value of $\mathbf{P(x)}$ evaluated at $x=k$.

$$\mathbf{R = P(k)}$$

**Application:**
To find the value of $P(3)$, the remainder $\mathbf{R}$ obtained from synthetic division with $\mathbf{k=3}$ will be equal to $\mathbf{P(3)}$.

---

#### 3. The Factor Theorem

A consequence of the Remainder Theorem that establishes when a linear binomial is a factor of a polynomial.

**Formula:**
The binomial $\mathbf{(x - k)}$ is a factor of $\mathbf{P(x)}$ if and only if the remainder $\mathbf{P(k)}$ is zero.

$$\mathbf{(x - k) \text{ is a factor of } P(x) \iff P(k) = 0}$$

* **Condition:** If the remainder $\mathbf{R}$ (or $\mathbf{P(k)}$) equals **zero**, then $\mathbf{k}$ is a root (or zero) of the polynomial.