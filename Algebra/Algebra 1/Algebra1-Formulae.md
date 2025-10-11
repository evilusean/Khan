## I. Linear Equations and Graphs

**Slope Formula:**
$$m = \frac{y_2 - y_1}{x_2 - x_1}$$

**Slope-Intercept Form:**
$$y = mx + b$$
**Standard Form:**
$$Ax + By = C$$

**Point-Slope Form:**
$$y - y_1 = m(x - x_1)$$

**Distance Formula:**
$$d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$

**Midpoint Formula:**
$$\left(\frac{x_1 + x_2}{2},\ \frac{y_1 + y_2}{2}\right)$$

**Parallel Lines:**
$$m_1 = m_2$$

**Perpendicular Lines:**
$$m_1 = -\frac{1}{m_2}$$
### 💡 Three Methods to Solve Systems of Linear Equations

A system of linear equations involves finding the point $(\mathbf{x, y})$ where two or more lines intersect. There are three primary methods for finding this solution:

---

#### 1. Graphing 📉

* **Goal:** Plot both lines and physically identify the point of intersection.
* **Best When:** The question asks for a visual solution, or you expect the intersection point to be simple, exact integers (e.g., $(2, -3)$).
* **Process:** Convert equations to **Slope-Intercept Form ($\mathbf{y = mx + b}$)**, then graph the lines and look for the common point.

---

#### 2. Substitution 🔄

* **Goal:** Replace a variable in one equation with an equivalent expression from the other equation to reduce the system to a single variable.
* **Best When:** One of the variables in either equation already has a coefficient of **1** or **-1** (making it easy to isolate).
* **Process:**
    1.  Isolate one variable (e.g., $y = 3x - 5$).
    2.  Substitute that expression into the other equation.
    3.  Solve for the remaining variable.

---

#### 3. Elimination (or Addition) ➕➖

* **Goal:** Add or subtract the equations to cancel out one of the variables.
* **Best When:** Equations are in **Standard Form ($\mathbf{Ax + By = C}$)**, and coefficients are easily made opposites (e.g., $4y$ and $-4y$).
* **Process:**
    1.  Multiply one or both equations so that one set of coefficients are **opposites** (like $2x$ and $-2x$).
    2.  Add the equations to **eliminate** that variable.
    3.  Solve for the remaining variable.
---

## II. Laws of Exponents

**Product Rule:**
$$a^m \cdot a^n = a^{m+n}$$

**Quotient Rule:**
$$\frac{a^n}{a^m} = a^{n-m}$$

**Power of a Power Rule:**
$$(a^m)^n = a^{m \cdot n}$$

**Zero Exponent Rule:**
$$a^0 = 1$$

**Negative Exponent Rule:**
$$a^{-m} = \frac{1}{a^m}$$

---

## III. Polynomials and Factoring

**Difference of Squares:**
$$a^2 - b^2 = (a-b)(a+b)$$

**Perfect Square Trinomial 1:**
$$a^2 + 2ab + b^2 = (a+b)^2$$

**Perfect Square Trinomial 2:**
$$a^2 - 2ab + b^2 = (a-b)^2$$

**FOIL Method:**
First, Outer, Inner, Last (for $$ (a+b)(c+d) $$

---

## IV. Quadratic Equations

**Standard Form:**
$$ax^2 + bx + c = 0$$

**Quadratic Formula:**
$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

**Discriminant:**
$$\Delta = b^2 - 4ac$$

**Vertex (x-coordinate):**
$$x = -\frac{b}{2a}$$

---

## V. Sequences

**Arithmetic Sequence (Explicit):**
$$a_n = a_1 + (n-1)d$$

**Geometric Sequence (Explicit):**
$$a_n = a_1 \cdot r^{n-1}$$


---

## VI. Inverse Functions

**Definition:**

If $f(x)$ is a function, its inverse $f^{-1}(x)$ satisfies $f(f^{-1}(x)) = x$ and $f^{-1}(f(x)) = x$.

  
**Finding the Inverse:**

1. Replace $f(x)$ with $y$.

2. Solve for $x$ in terms of $y$.

3. Swap $x$ and $y$.

4. Write as $f^{-1}(x)$.


**Example:**

If $f(x) = 2x + 3$, then $f^{-1}(x) = \frac{x - 3}{2}$

  

---
## VII. Rational Functions & Variations

**Rational Function :** A function of the form: $$f(x) = \frac{P(x)}{Q(x)}$$ where $P$ and $Q$ are polynomials and $Q(x) \neq 0$. 
**Direct Variation:** $$y = kx \quad \text{or} \quad y \propto x$$ **Inverse Variation:**  $$ yx = k $$
$$y = \frac{k}{x} \quad \text{or} \quad y \propto \frac{1}{x}$$ **Joint Variation:** $$y = kxz$$ (Varies directly with $x$ and $z$) **Combined Variation:** $$y = \frac{kx}{z}$$ (Varies directly with $x$, inversely with $z$)

---
## VIII. Radicals and Square Roots

**Square Root:**

$$\sqrt{x}$$

**Cube Root:**

$$\sqrt[3]{x}$$

**nth Root:**

$$\sqrt[n]{x}$$
**Properties:**

$$\sqrt{a^2} = |a|$$

$$\sqrt{ab} = \sqrt{a} \cdot \sqrt{b}$$

$$\sqrt{\frac{a}{b}} = \frac{\sqrt{a}}{\sqrt{b}}$$

$$\sqrt{a^2 + b^2}$$
---

## IX. Polynomial Division and Roots

### 💡 Synthetic Division and The Remainder Theorem

These tools are used to quickly divide polynomials by linear factors and evaluate polynomials at specific values.

---

#### 1. Synthetic Division

Synthetic division is the rapid method for dividing a polynomial, $P(x)$, by a linear binomial of the form $\mathbf{(x - k)}$.


$$\mathbf{\frac{P(x)}{x - k} = Q(x) + \frac{R}{x - k}}$$

* The degree of $Q(x)$ is always **one less** than the degree of $P(x)$.

---

#### 2. The Remainder Theorem

The Remainder Theorem provides a shortcut to finding the remainder of polynomial division and is equivalent to evaluating the function.

**Formula:**
If a polynomial $\mathbf{P(x)}$ is divided by $\mathbf{(x - k)}$, then the remainder $\mathbf{R}$ is equal to $\mathbf{P(k)}$.

$$\mathbf{R = P(k)}$$

**Application:**
To find the value of $P(3)$, you can either substitute $x=3$ into the polynomial **or** use synthetic division with $\mathbf{k=3}$. The last number obtained in the synthetic division process will be the remainder, $\mathbf{R}$, which is equal to $\mathbf{P(3)}$.

---

#### 3. The Factor Theorem

The Factor Theorem is a direct consequence of the Remainder Theorem, establishing a condition for when a linear binomial is a factor.

**Formula:**

$$\mathbf{(x - k) \text{ is a factor of } P(x) \iff P(k) = 0}$$

* If the remainder $\mathbf{R}$ (or $\mathbf{P(k)}$) equals **zero**, then $\mathbf{(x - k)}$ is a factor of $P(x)$, and $k$ is a root (or zero) of the polynomial.