Start : 06March2026
End :

https://www.youtube.com/playlist?list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP

## 2026-March-06 - Intro to Precalculus :
https://www.youtube.com/watch?v=9OOrhA2iKak&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=1
- College Algebra +  Trigonometry = PreCalculus
## 2026-March-06 - Introduction to Functions (Precalculus - College Algebra 2) : 
https://www.youtube.com/watch?v=FkUEsP9efFg&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=2
- **Function** = A relationship that maps one input to one output - An input never gives more than 1 output (one x to ANY y)
- **One to One Function** : A relationship that maps one input to one *unique* output (can't be shared) (one x to ONE y)
- **Function Notation** : **f(x)** = **y** : function of *x* equals *y*
- **Independant Variable** : *x* (your input is always independant) you can choose
- **Dependant Variable** : *y* (your out put is always dependant on the input) you can not chosen
- Functions create an *ordered pair* : (x, y) or (x, f(x))
- **Domain** : set of values you input into a function (*x*'s)
- **Range** : Set of values you get as output (*y*'s)
- To find out if an equation is a function, solve for '*y*' (the dependant variable)
- $\sqrt{y^2} =\pm \sqrt{x}$ : when you square something to get rid of the exponent, be careful, because the squared can be plus or minus (2 different outputs) and not a function - when solving for *y* **ANY** time you have to take a square root to solve it, it will have a plus or minus and *NOT* be a function
## 2026-March-07 - How to Evaluate Functions (Precalculus - College Algebra 3) :
https://www.youtube.com/watch?v=p1sGAHulT8w&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=5
- A **composition function**, denoted as $(f \circ g)(x)$ or $f(g(x))$, is an operation where the output of one function becomes the input of another, creating a "chain" where the final result depends on the sequential evaluation of both rules.
- $y = -7x + 5$ : $f(x) = -7x+5$ : they are the same
- Why do you use *Function Notation*? Because if every function was named '*y*' it would be very hard to distinguish between them, so it's better to use $f(x)$
- $f(2)$ : means plug in *2* everywhere you see *x*
- Only numbers in the *domain* are real (no imaginary numbers like $\sqrt{-2}$ or '0') positive numbers (>0) - *Square Roots* and *Denominators* can give you problems, so make sure to check your domain inputs for those
- **Difference Quotient** : $\frac{f(x+h)-f(x)}{h}$ :  
### h(x) = -2x² + x - 1

To evaluate $h(x) = -2x^2 + x - 1$, substitute the given value or expression into every instance of $x$ in the original function.

---

#### 1. Evaluate h(-1)
Substitute $-1$ for $x$:
$$h(-1) = -2(-1)^2 + (-1) - 1$$
$$h(-1) = -2(1) - 1 - 1$$
$$h(-1) = -2 - 1 - 1$$
**$h(-1) = -4$**

---

#### 2. Evaluate h(-x)
Substitute $-x$ for $x$:
$$h(-x) = -2(-x)^2 + (-x) - 1$$
Since $(-x)^2 = x^2$ and $+(-x) = -x$:
**$h(-x) = -2x^2 - x - 1$**

---

#### 3. Evaluate h(x + 1)
Substitute the expression $(x + 1)$ for $x$:
$$h(x + 1) = -2(x + 1)^2 + (x + 1) - 1$$

**Step A: Expand the binomial**
$$(x + 1)^2 = (x + 1)(x + 1) = x^2 + 2x + 1$$

**Step B: Distribute the -2**
$$h(x + 1) = -2(x^2 + 2x + 1) + x + 1 - 1$$
$$h(x + 1) = -2x^2 - 4x - 2 + x + 0$$

**Step C: Combine like terms**
**$h(x + 1) = -2x^2 - 3x - 2$**

---

> [!abstract] Algebra Takeaway
> When evaluating $h(x+1)$, the most common error is forgetting to expand the binomial $(x+1)^2$ fully before multiplying by $-2$. Always follow the Order of Operations (**PEMDAS**): handle the exponent (squaring the binomial) before performing the multiplication.
### $f(x) = \sqrt{x^2 - 3x}$

To evaluate these, substitute the given value or expression into every $x$ under the radical.

---

#### 1. Evaluate $f(5)$
$$f(5) = \sqrt{(5)^2 - 3(5)}$$
$$f(5) = \sqrt{25 - 15}$$
**$f(5) = \sqrt{10}$**

---

#### 2. Evaluate $f(0)$
$$f(0) = \sqrt{(0)^2 - 3(0)}$$
$$f(0) = \sqrt{0 - 0}$$
**$f(0) = 0$**

---

#### 3. Evaluate $f(2x)$
$$f(2x) = \sqrt{(2x)^2 - 3(2x)}$$
Square both the $2$ and the $x$ inside the first term:
**$f(2x) = \sqrt{4x^2 - 6x}$**

---

#### 4. Evaluate $f(x + h)$
$$f(x + h) = \sqrt{(x + h)^2 - 3(x + h)}$$
Expand the squared binomial and distribute the $-3$:
**$f(x + h) = \sqrt{x^2 + 2xh + h^2 - 3x - 3h}$**

---

#### 5. Evaluate $f(1)$
$$f(1) = \sqrt{(1)^2 - 3(1)}$$
$$f(1) = \sqrt{1 - 3}$$
**$f(1) = \sqrt{-2}$**
*(Note: Undefined in the real number system; results in $i\sqrt{2}$.)*

---

> [!abstract] Algebra Takeaway
> When working with square root functions, the **domain** is restricted. If the value inside the radical is negative, the function has no real-number output. As seen with $f(1)$, $x=1$ is not in the domain.
### $g(x) = \frac{2x+1}{x-5}$

To evaluate this rational function, substitute the given value or expression into every instance of $x$ in both the numerator and the denominator.

---

#### 1. Evaluate $g(0)$
Substitute $0$ for $x$:
$$g(0) = \frac{2(0) + 1}{0 - 5}$$
$$g(0) = \frac{1}{-5}$$
**$g(0) = -\frac{1}{5}$**

---

#### 2. Evaluate $g(x^2)$
Substitute $x^2$ for $x$:
**$g(x^2) = \frac{2x^2 + 1}{x^2 - 5}$**

---

#### 3. Evaluate $g(5)$
Substitute $5$ for $x$:
$$g(5) = \frac{2(5) + 1}{5 - 5}$$
$$g(5) = \frac{11}{0}$$
**$g(5) = \text{Undefined}$**
*(Note: Division by zero is impossible, meaning $x = 5$ is an exclusion from the domain.)*


---

#### 4. Evaluate $-g(x)$
This is the negative of the entire function. You can distribute the negative to either the numerator OR the denominator, but not both:
$$-g(x) = -\left(\frac{2x + 1}{x - 5}\right)$$
**$-g(x) = \frac{-2x - 1}{x - 5}$** *(Commonly represented this way)*

---

> [!abstract] Algebra Takeaway
> When evaluating rational functions like $g(5)$, a zero in the denominator indicates a **vertical asymptote** or a "hole" in the graph. In your Obsidian vault, you can link this to **Domain Restrictions**, as $x$ can be any real number except $5$. When calculating $-g(x)$, be careful not to multiply both top and bottom by $-1$, as that would actually result in the original function (a double negative).
### Identifying Even, Odd, and Neither Functions

To determine the symmetry of a function, you use the **"$-x$ Plugin"** test. This involves substituting every $x$ in the function with $(-x)$ and comparing the result to the original function.

---
#### 1. Even Functions (Symmetric about the y-axis)
A function is **Even** if plugging in $-x$ results in the exact same original function.
* **Condition:** $f(-x) = f(x)$
* **Visual:** If you fold the graph along the y-axis, the two sides match perfectly.
---
#### 2. Odd Functions (Symmetric about the origin)
A function is **Odd** if plugging in $-x$ results in the original function with every sign flipped (the negative of the original).
* **Condition:** $f(-x) = -f(x)$
* **Visual:** If you rotate the graph $180^\circ$ around the $(0,0)$ point, it looks identical.
---
#### 3. Neither
A function is **Neither** if the result of the $-x$ substitution does not match the original function and is not the exact negative of the original.
* **Condition:** $f(-x) \neq f(x)$ AND $f(-x) \neq -f(x)$
---
#### Step-by-Step Plugin Examples

**Example A: $f(x) = x^2 + 5$**
1. Substitute $-x$: $f(-x) = (-x)^2 + 5$
2. Simplify: $f(-x) = x^2 + 5$
3. **Result:** Matches original. **Even.**

**Example B: $f(x) = x^3 - x$**
1. Substitute $-x$: $f(-x) = (-x)^3 - (-x)$
2. Simplify: $f(-x) = -x^3 + x$
3. Factor out $-1$: $f(-x) = -(x^3 - x)$
4. **Result:** Matches negative of original. **Odd.**

**Example C: $f(x) = 2x + 1$**
1. Substitute $-x$: $f(-x) = 2(-x) + 1$
2. Simplify: $f(-x) = -2x + 1$
3. **Result:** Neither original nor exact negative (the $+1$ didn't flip). **Neither.**

---

> [!abstract] Algebra Takeaway
> When using the $-x$ plugin, remember that **even exponents** (2, 4, 6...) will always "absorb" the negative sign, while **odd exponents** (1, 3, 5...) will "keep" the negative sign. Constants (like $+5$) are unaffected by the $-x$ substitution.### Difference Quotient

* The **Difference Quotient**, $\frac{f(x+h)-f(x)}{h}$, is a formula used to find the **average rate of change** between two points on a curve, which represents the slope of a **secant line**. As $h$ approaches zero, this formula becomes the foundation for the derivative, allowing you to find the slope at a single specific point.
---
#### Step-by-Step Execution Guide

To solve the difference quotient for any function $f(x)$, follow these three steps to keep the algebra clean:

1.  **Find $f(x+h)$:** Substitute $(x+h)$ into the original function and expand/simplify it completely.
2.  **Subtract $f(x)$:** Subtract the original function from your result in Step 1. This should cause all terms without an $h$ to cancel out.
3.  **Divide by $h$:** Factor out an $h$ from the numerator and cancel it with the $h$ in the denominator.

---

#### Example: $f(x) = x^2 + 3$

**Step 1: Evaluate $f(x+h)$**
$$f(x+h) = (x+h)^2 + 3$$
$$f(x+h) = x^2 + 2xh + h^2 + 3$$

**Step 2: Subtract $f(x)$**
$$(x^2 + 2xh + h^2 + 3) - (x^2 + 3)$$
$$x^2 + 2xh + h^2 + 3 - x^2 - 3$$
Remaining: **$2xh + h^2$**

**Step 3: Divide by $h$**
$$\frac{2xh + h^2}{h} = \frac{h(2x + h)}{h}$$
**Result: $2x + h$**

---

> [!abstract] Algebra Takeaway
> The primary goal of simplifying a difference quotient is to **cancel the $h$ in the denominator**. If you reach the final step and you cannot factor an $h$ out of every term in the numerator, you likely made a distribution or sign error in Step 2.

### Difference Quotient

* The **Difference Quotient**, $\frac{f(x+h)-f(x)}{h}$, is a formula used to find the **average rate of change** between two points on a curve, which represents the slope of a **secant line**. As $h$ approaches zero, this formula becomes the foundation for the derivative, allowing you to find the slope at a single specific point.

---
#### Step-by-Step Execution Guide

To solve the difference quotient for any function $f(x)$, follow these three steps to keep the algebra clean:

1.  **Find $f(x+h)$:** Substitute $(x+h)$ into the original function and expand/simplify it completely.
2.  **Subtract $f(x)$:** Subtract the original function from your result in Step 1. This should cause all terms without an $h$ to cancel out.
3.  **Divide by $h$:** Factor out an $h$ from the numerator and cancel it with the $h$ in the denominator.
---
#### Example: $f(x) = x^2 + 3$

**Step 1: Evaluate $f(x+h)$**
$$f(x+h) = (x+h)^2 + 3$$
$$f(x+h) = x^2 + 2xh + h^2 + 3$$

**Step 2: Subtract $f(x)$**
$$(x^2 + 2xh + h^2 + 3) - (x^2 + 3)$$
$$x^2 + 2xh + h^2 + 3 - x^2 - 3$$
Remaining: **$2xh + h^2$**

**Step 3: Divide by $h$**
$$\frac{2xh + h^2}{h} = \frac{h(2x + h)}{h}$$
**Result: $2x + h$**

---

> [!abstract] Algebra Takeaway
> The primary goal of simplifying a difference quotient is to **cancel the $h$ in the denominator**. If you reach the final step and you cannot factor an $h$ out of every term in the numerator, you likely made a distribution or sign error in Step 2.

## 2026-March-09 - Finding the Domain of Functions (Precalculus - College Algebra 4)
https://www.youtube.com/watch?v=LvUCDcp6Z3k&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=6
- **Domain** = Is the set of inputs of a function that can give a *DEFINED* *REAL* number output (not imaginary, and defined aka not zero, and some functions can't handle negative numbers)
- Two Problem Areas : 
  - $\sqrt{1}$  you *CAN NOT have a negative square root radicand* (imaginary number) - A square root will tell you what numbers it wants to have, find numbers that when you plug in will be $\ge 0$ - You can plug in negative numbers to a square root as long as the resulting number is POSITIVE or at least ZERO
  - $\frac{1}{0}$ *Denominators can not equal to zero* - it will tell you what numbers it can't have
- 
### Finding the Domain of $f(x) = \sqrt{5-4x}$

To find the domain of a square root function, the expression inside the radical (the radicand) must be greater than or equal to zero, as you cannot take the square root of a negative number in the real number system.

---

#### Step 1: Set up the Inequality
Set the radicand to be $\ge 0$:
$$5 - 4x \ge 0$$

#### Step 2: Solve for x
Subtract 5 from both sides:
$$-4x \ge -5$$

#### Step 3: Divide by -4
**Crucial Rule:** When dividing or multiplying an inequality by a negative number, you must **flip the inequality sign**.
$$x \le \frac{-5}{-4}$$
$$x \le 1.25$$

---

#### Final Domain Notation
* **Inequality Notation:** $x \le \frac{5}{4}$
* **Interval Notation:** $(-\infty, \frac{5}{4}]$
* **Set Builder Notation:** $\{x | x \in \mathbb{R}, x \le \frac{5}{4}\}$

---

> [!abstract] Algebra Takeaway
> The "Plugin" test is a quick way to verify your domain. If you pick a number larger than $1.25$ (like $x=2$), the result is $\sqrt{5-8}$, which is $\sqrt{-3}$ (undefined). If you pick a number smaller than $1.25$ (like $x=0$), the result is $\sqrt{5}$ (defined). This confirms the domain must include all values **less than or equal to** $1.25$.
### Finding the Domain of $g(t) = \frac{5t}{t^3 - 16t}$

To find the domain of a rational function (a fraction), you must identify all values that would cause the **denominator to equal zero**, as division by zero is undefined.

---

#### Step 1: Set the Denominator to Zero
We need to solve for $t$ when the bottom part of the fraction is zero:
$$t^3 - 16t = 0$$

#### Step 2: Factor the Expression
First, factor out the greatest common factor, which is $t$:
$$t(t^2 - 16) = 0$$

Next, recognize that $(t^2 - 16)$ is a **difference of squares** ($a^2 - b^2$):
$$t(t - 4)(t + 4) = 0$$

#### Step 3: Solve for Excluded Values
Set each factor to zero:
* $t = 0$
* $t - 4 = 0 \Rightarrow t = 4$
* $t + 4 = 0 \Rightarrow t = -4$

---

#### Final Domain Notation
The domain includes all real numbers **except** $-4, 0,$ and $4$.

* **Inequality Notation:** $t \neq -4, t \neq 0, t \neq 4$
* **Interval Notation:** $(-\infty, -4) \cup (-4, 0) \cup (0, 4) \cup (4, \infty)$
* **Set Builder Notation:** $\{t \mid t \in \mathbb{R}, t \neq \pm 4, t \neq 0\}$

---

> [!abstract] Algebra Takeaway
> In this specific function, you might notice a $t$ in both the numerator and denominator. While they could algebraically "cancel out," the **original** function still has a hole at $t=0$. When finding the domain, always analyze the denominator in its **original, unsimplified form** to ensure you don't miss any points where the function is undefined.
### Finding the Domain of f(x) = 3x² - 2x + 4

To find the domain of a function, you look for restricted operations, such as division by zero or taking the square root of a negative number.

---

#### Step 1: Analyze the Function Type
The function $f(x) = 3x^2 - 2x + 4$ is a **polynomial function** (specifically a quadratic). 

#### Step 2: Check for Restrictions
* **Denominators:** There are no variables in a denominator (no division by zero).
* **Radicals:** There are no square roots or even-indexed roots (no negative radicands).
* **Logarithms:** There are no logarithmic expressions.

Since there are no operations that would lead to an undefined result, you can plug any real number into $x$ and get a valid output.

---

#### Final Domain Notation
The domain is all real numbers.

* **Inequality Notation:** $-\infty < x < \infty$
* **Interval Notation:** $(-\infty, \infty)$
* **Set Builder Notation:** $\{x \mid x \in \mathbb{R}\}$

---

> [!abstract] Algebra Takeaway
> All polynomial functions—whether they are linear, quadratic, cubic, or higher—have a domain of **all real numbers**. In Obsidian, you can categorize this as a "unrestricted domain." The graph of this function is a parabola that continues infinitely to the left and right, meaning every $x$-value is accounted for.
### Finding the Domain of $h(x) = \frac{\sqrt{3x - 15}}{x - 4}$

To find the domain of this function, you must satisfy the restrictions of both the **square root in the numerator** and the **variable in the denominator**. 

---
#### Step 1: Solve for the Radical (Numerator)
The expression inside the square root must be greater than or equal to zero:
$$3x - 15 \ge 0$$
$$3x \ge 15$$
$$x \ge 5$$
*This tells us the function only exists from 5 to positive infinity.*

#### Step 2: Solve for the Denominator
The denominator cannot equal zero:
$$x - 4 \neq 0$$
$$x \neq 4$$
*This tells us the function is undefined at exactly 4.*

#### Step 3: Combine the Restrictions
Now, we look for the overlap:
1. The radical restricts us to values **5 or greater**.
2. The denominator forbids the value **4**.

Since the radical already restricts the domain to $x \ge 5$, the "forbidden" value of $4$ is already excluded by default (it's outside the valid range of the radical). Therefore, the restriction at $x=4$ does not further limit our domain.

---
#### Final Domain Notation
* **Inequality Notation:** $x \ge 5$
* **Interval Notation:** $[5, \infty)$
* **Set Builder Notation:** $\{x \mid x \in \mathbb{R}, x \ge 5\}$
---

> [!abstract] Algebra Takeaway
> When dealing with multiple restrictions, always check if one "overrides" the other. In this case, the square root's requirement ($x \ge 5$) is more restrictive than the denominator's requirement ($x \neq 4$). Even though $x=4$ would cause division by zero, the function is already "dead" there because you'd be trying to take the square root of a negative number.
### Finding the Domain of $g(x) = \frac{5}{\sqrt{x-8}}$

This function combines two restrictions: a **variable in a denominator** and a **variable inside a square root**.

---
#### Step 1: Analyze the Restrictions
1.  **Square Root Rule:** The radicand ($x - 8$) must normally be $\ge 0$.
2.  **Denominator Rule:** The denominator cannot be $0$.

Because the square root is *in* the denominator, the value inside cannot be zero ($\sqrt{0} = 0$, which would cause division by zero). Therefore, we must strictly use "greater than" rather than "greater than or equal to."

#### Step 2: Solve the Inequality
Set the radicand to be strictly greater than zero:
$$x - 8 > 0$$
Add 8 to both sides:
**$x > 8$**

---

#### Final Domain Notation
* **Inequality Notation:** $x > 8$
* **Interval Notation:** $(8, \infty)$
* **Set Builder Notation:** $\{x \mid x \in \mathbb{R}, x > 8\}$

---

> [!abstract] Algebra Takeaway
> Usually, square roots allow for a "closed bracket" (meaning the number is included). However, when the radical is in the denominator, you must switch to an **open parenthesis**. This indicates that while the function exists for $8.00001$, it is undefined at exactly $8$.

## 2026-March-10 - Operations of Functions (Precalculus - College Algebra 5) : 
https://www.youtube.com/watch?v=7N_-G4usp6Q&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=6
- if you run something through two functions, you have to make sure that it clears BOTH the domains - domain issues persist through addition, subtraction, multiplication, and division - You can even develop new domain problems after doing operations
- When multiplying, you should always keep the denominators factored and not combined/distributed, it's easier to have the denominator factored when graphing, or when working with fractions it's easier to find the LCD(lowest common denominator)
- 
### Operations of Functions

When performing operations like addition, subtraction, multiplication, or division on two functions, the most critical factor is the **domain**. A common mistake is to only look at the final simplified result; however, a function always carries the "baggage" of its original domain restrictions.

---
#### 1. The "Pessimistic" Rule of Domain
The domain of a resulting function is the **intersection** (the overlap) of the domains of the original functions.
* **The Principle:** If a number was "bad" for one of the starting functions, it remains "bad" for the result, even if it looks like the problem was "canceled out" algebraically [00:01:15].
* **Workflow:** Always find the individual domains of $f(x)$ and $g(x)$ **first** before performing any operations [00:01:40].

---
#### 2. Basic Operations
Given two functions $f(x)$ and $g(x)$:
* **Addition:** $(f + g)(x) = f(x) + g(x)$
* **Subtraction:** $(f - g)(x) = f(x) - g(x)$
* **Multiplication:** $(fg)(x) = f(x) \cdot g(x)$
* **Division:** $(f / g)(x) = \frac{f(x)}{g(x)}$

---
#### 3. Dividing Functions: Hidden Restrictions
Division is the only operation that can create **new** domain problems. 
* **The New Constraint:** In $(f/g)(x)$, not only must you follow the original restrictions for $f$ and $g$, but you must also ensure $g(x) \neq 0$ [00:10:45].
* **The "Vanishing" Denominator:** If you multiply by a reciprocal and a denominator cancels out, the restriction at that point **must still be recorded** in your final domain [00:12:38].

---
#### Step-by-Step Example: $f(x) = \sqrt{x+3}$ and $g(x) = \frac{5}{x}$

**Step 1: Find Initial Domains**
* Domain of $f(x)$: $x+3 \ge 0 \Rightarrow x \ge -3$ [00:16:06].
* Domain of $g(x)$: $x \neq 0$ [00:16:48].
* **Combined Domain:** $x \ge -3$ AND $x \neq 0$.

**Step 2: Division $(f/g)(x)$**
$$\frac{\sqrt{x+3}}{\frac{5}{x}} = \sqrt{x+3} \cdot \frac{x}{5} = \frac{x\sqrt{x+3}}{5}$$

**Step 3: State the Final Domain**
Even though the final result $\frac{x\sqrt{x+3}}{5}$ has no $x$ in the denominator, you must retain the original restriction from $g(x)$.
* **Result:** $\frac{x\sqrt{x+3}}{5}$ with a domain of **$[-3, 0) \cup (0, \infty)$** [00:20:46].

---

> [!abstract] Algebra Takeaway
> Think of a function's domain like "skeletons in the closet" [00:00:36]. You cannot simplify away a domain restriction. When adding, subtracting, or multiplying, the domain is simply the overlap of the two originals. When dividing, you must also check if the *entire* denominator function equals zero at any point and exclude those values as well.

### Operations of Functions: Addition Example

When performing operations on rational functions, you must handle the algebraic combining of terms while strictly maintaining the domain restrictions from the original functions.

---

#### 1. The Functions
$f(x) = \frac{2x+3}{3x-2}$
$g(x) = \frac{4x}{3x-2}$

#### 2. Identify Initial Restrictions (Domain)
Before performing the operation, identify where the individual functions are undefined. Both $f(x)$ and $g(x)$ have the same denominator:
$$3x - 2 \neq 0$$
$$3x \neq 2$$
$$x \neq \frac{2}{3}$$
**Initial Domain:** $\{x \mid x \in \mathbb{R}, x \neq \frac{2}{3}\}$

#### 3. Perform the Operation $(f + g)(x)$
Since the denominators are common, you can add the numerators directly:
$$(f + g)(x) = \frac{(2x + 3) + (4x)}{3x - 2}$$
$$(f + g)(x) = \frac{6x + 3}{3x - 2}$$

---

### ⚠️ What to Look Out For

> [!important] The "Persistence of Restrictions"
> Even if the numerator and denominator had a common factor that could be canceled (e.g., if the numerator simplified to $3x-2$), the restriction $x \neq \frac{2}{3}$ would **still exist** as a "hole" in the graph. In your Obsidian notes, always record the domain based on the unsimplified parts.

#### 1. Common Denominator Necessity
If the denominators were different, you would need to find a Least Common Denominator (LCD) before adding. This often introduces **new** variables into the numerator, increasing the complexity of the final expression.

#### 2. The Intersection Rule
The domain of $(f + g)$ is the **intersection** of the domains of $f$ and $g$. 
* If $f$ is "broken" at $x=A$.
* If $g$ is "broken" at $x=B$.
* Then $(f+g)$ is "broken" at **both** $x=A$ and $x=B$.

#### 3. Factoring for Simplification
Always check if the final numerator can be factored. In this result, $6x + 3$ can be factored into $3(2x + 1)$.
$$(f + g)(x) = \frac{3(2x + 1)}{3x - 2}$$
While this doesn't cancel with the denominator here, it is a standard step in verification to ensure no further simplification is possible.

---

> [!abstract] Algebra Takeaway
> Addition of functions is straightforward when denominators match, but the "hidden" part of the problem is always the domain. In your final result, the vertical asymptote remains at $x = \frac{2}{3}$, just as it was in the original two functions.

### Operations of Functions: Subtraction Example

When subtracting rational functions, the focus is on maintaining a common denominator and correctly distributing the negative sign across the second numerator.

---

#### 1. The Functions
$f(x) = \frac{2x+3}{3x-2}$
$g(x) = \frac{4x}{3x-2}$

#### 2. Identify Initial Restrictions (Domain)
Before performing the operation, identify where the individual functions are undefined. Both $f(x)$ and $g(x)$ share the same denominator:
$$3x - 2 \neq 0$$
$$3x \neq 2$$
$$x \neq \frac{2}{3}$$
**Initial Domain:** $\{x \mid x \in \mathbb{R}, x \neq \frac{2}{3}\}$

#### 3. Perform the Operation $(f - g)(x)$
Since the functions already share a common denominator, subtract the numerators directly:
$$(f - g)(x) = \frac{(2x + 3) - (4x)}{3x - 2}$$
Combine like terms:
$$(f - g)(x) = \frac{-2x + 3}{3x - 2}$$

---

### ⚠️ What to Look Out For

> [!important] The "Subtraction Sign" Trap
> One of the most common errors in precalculus is failing to distribute the negative sign to the *entire* numerator of $g(x)$. While $g(x)$ only has one term here ($4x$), if it were a binomial (e.g., $4x + 1$), you would need to subtract both terms: $-(4x + 1) = -4x - 1$.

#### 1. Maintaining the Restriction
Even if the numerator simplified in a way that allowed you to cancel out the $(3x-2)$ in the denominator, the restriction $x \neq \frac{2}{3}$ **must remain** in the domain of the resulting function. In a graph, this would appear as a "hole" (removable discontinuity).

#### 2. Domain Intersection
The domain of $(f - g)(x)$ is strictly the **intersection** of the domains of $f$ and $g$. 
* If $f$ is undefined at $x=2/3$ and $g$ is undefined at $x=2/3$, the result is also undefined at $x=2/3$.
* If $g$ had an additional restriction (e.g., if it also had a square root), that restriction would carry over into the final result as well.

#### 3. Simplified Form vs. Original Form
Always check if the final numerator can be factored. Here, $-2x + 3$ cannot be factored to cancel the denominator, so the expression is in its simplest form.

---

> [!abstract] Algebra Takeaway
> Subtraction is essentially "addition of the opposite." In your Obsidian vault, categorize this under **Rational Operations**. Always find the domain of the individual functions *before* you start crossing things out or combining them, to ensure you don't lose track of excluded values.

### Operations of Functions: Multiplication Example

When multiplying rational functions, you multiply the numerators together and the denominators together. While the algebra is often straightforward, tracking the domain and potential simplifications is key.

---

#### 1. The Functions
$f(x) = \frac{2x+3}{3x-2}$
$g(x) = \frac{4x}{3x-2}$

#### 2. Identify Initial Restrictions (Domain)
Before performing the operation, identify where the individual functions are undefined. Both $f(x)$ and $g(x)$ share a denominator that cannot be zero:
$$3x - 2 \neq 0$$
$$3x \neq 2$$
$$x \neq \frac{2}{3}$$
**Initial Domain:** $\{x \mid x \in \mathbb{R}, x \neq \frac{2}{3}\}$

#### 3. Perform the Operation $(f \cdot g)(x)$
Multiply the numerators and the denominators:
$$(f \cdot g)(x) = \frac{(2x + 3)(4x)}{(3x - 2)(3x - 2)}$$

Distribute the $4x$ in the numerator and express the denominator as a square:
$$(f \cdot g)(x) = \frac{8x^2 + 12x}{(3x - 2)^2}$$

---

### ⚠️ What to Look Out For

> [!important] The "Squared Restriction"
> Even though the denominator is now $(3x - 2)^2$, the restriction remains $x \neq \frac{2}{3}$. Squaring the denominator doesn't change the "bad" value, but it does change the behavior of the graph (it typically creates a "volcano" shape at the asymptote where both sides approach the same infinity).

#### 1. Numerator Distribution
Ensure you distribute the $4x$ to **both** terms in the numerator of $f(x)$. A common mistake is only multiplying $2x$ by $4x$ and forgetting the constant $3$.
* *Correct:* $4x(2x) + 4x(3) = 8x^2 + 12x$

#### 2. Domain Overlap
The domain of $(f \cdot g)(x)$ is the **intersection** of the domains of $f$ and $g$. If $f$ or $g$ had different restricted values, the final result would be restricted by **all** of them combined.

#### 3. Simplification Opportunities
Always check if the resulting numerator can be factored to cancel out part of the denominator. 
* Here, the numerator factors to $4x(2x + 3)$. 
* Since $(2x + 3)$ does not match $(3x - 2)$, no further simplification is possible.

---

> [!abstract] Algebra Takeaway
> Unlike addition and subtraction, multiplication does not require a common denominator. However, it often results in higher-degree polynomials (like $x^2$) in both the top and bottom. In your Obsidian vault, note that for multiplication, the domain restrictions of the original functions are strictly inherited.

### Operations of Functions: Division Example

Division is the most complex operation because it introduces an additional layer of domain restrictions. You must account for the original restrictions of $f$ and $g$, as well as any new restrictions created by $g$ moving into the denominator.

---

#### 1. The Functions
$f(x) = \frac{2x+3}{3x-2}$
$g(x) = \frac{4x}{3x-2}$

#### 2. Identify Initial Restrictions (The "Pessimistic" Domain)
Before calculating, look at the individual functions:
* Both $f(x)$ and $g(x)$ are undefined when $3x - 2 = 0$.
* **Constraint 1:** $x \neq \frac{2}{3}$

#### 3. Perform the Operation $(f / g)(x)$
To divide fractions, multiply the first fraction by the **reciprocal** of the second:
$$(f / g)(x) = \frac{2x+3}{3x-2} \div \frac{4x}{3x-2}$$
$$(f / g)(x) = \frac{2x+3}{3x-2} \cdot \frac{3x-2}{4x}$$

#### 4. Simplify and Identify New Restrictions
Notice that $(3x-2)$ appears in both the numerator and denominator, allowing them to cancel. However, a **new** term, $4x$, is now in the denominator.
* **Constraint 2:** $4x \neq 0 \Rightarrow x \neq 0$

**Final Simplified Result:**
$$(f / g)(x) = \frac{2x+3}{4x}$$

---

### ⚠️ What to Look Out For

> [!important] The "Vanishing Denominator" Trap
> This is the most common mistake in precalculus. Even though $(3x-2)$ canceled out algebraically, the restriction $x \neq \frac{2}{3}$ **does not disappear**. In a graph, this would be a "hole," while the $x=0$ would be a vertical asymptote.

#### 1. The Three-Point Domain Check
When dividing functions $f/g$, you must exclude:
1.  Any values that make the denominator of $f$ zero.
2.  Any values that make the denominator of $g$ zero.
3.  Any values that make the **entire function** $g$ equal to zero (because $g$ is now the divisor).

#### 2. Reciprocal Multiplication
Always write out the step where you flip the second fraction. This helps you visually identify which terms were originally in a denominator and which terms moved there during the operation.

#### 3. Domain Intersection vs. Final Result
The domain of $(f/g)(x)$ is strictly the overlap of the original domains **plus** the new restriction. 
* **Final Domain:** $\{x \mid x \in \mathbb{R}, x \neq \frac{2}{3}, x \neq 0\}$
* **Interval Notation:** $(-\infty, 0) \cup (0, \frac{2}{3}) \cup (\frac{2}{3}, \infty)$

---

> [!abstract] Algebra Takeaway
> Division is "picky." You have to respect the "bad" numbers from the start of the problem and the "bad" numbers created during the flip. In your Obsidian vault, mark division as the only operation that can change the domain beyond just a simple intersection of the two starting sets.

### Operations of Functions: Addition Example (Radical + Rational)

When adding a radical function and a rational function, the algebra is usually left in "uncombined" form unless a common denominator is required. The primary challenge is correctly identifying the overlapping domain.

---

#### 1. The Functions
$f(x) = \sqrt{x+3}$
$g(x) = \frac{5}{x}$

#### 2. Identify Individual Domains
* **Domain of $f(x)$:** The radicand must be $\ge 0$.
    $$x + 3 \ge 0 \Rightarrow x \ge -3$$
* **Domain of $g(x)$:** The denominator cannot be $0$.
    $$x \neq 0$$

#### 3. Perform the Operation $(f + g)(x)$
To add them, simply write the sum of the two expressions:
**$(f + g)(x) = \sqrt{x+3} + \frac{5}{x}$**

*(Note: You could find a common denominator to get $\frac{x\sqrt{x+3} + 5}{x}$, but in most Precalculus contexts, the uncombined form is preferred for clarity.)*

---

### ⚠️ What to Look Out For

> [!important] The "Intersection" Requirement
> The resulting function $(f + g)(x)$ only exists where **both** original functions exist simultaneously. If you pick a number that works for $g$ but not $f$, the entire operation is undefined.

#### 1. Visualizing the Overlap
Imagine a number line:
* $f(x)$ starts at $-3$ and goes to infinity.
* $g(x)$ is the entire line with a "hole" at $0$.
* **The Overlap:** You start at $-3$, but you must "jump over" the $0$.

#### 2. Zero as a Special Case
In this specific problem, $0$ is within the valid range of the square root ($x \ge -3$), but it is forbidden by the fraction. Therefore, $0$ must be excluded from the final domain. If the square root had been $\sqrt{x-5}$, the domain would have started at $5$, and the $x \neq 0$ restriction would have been redundant.

#### 3. Domain Notation
* **Inequality Notation:** $x \ge -3, x \neq 0$
* **Interval Notation:** $[-3, 0) \cup (0, \infty)$
* **Set Builder Notation:** $\{x \mid x \in \mathbb{R}, x \ge -3, x \neq 0\}$

---

> [!abstract] Algebra Takeaway
> When adding different "types" of functions (like a root and a fraction), the domain is the most restrictive combination of both. In your Obsidian vault, note that you should always check if the "excluded" values of your rational part ($x \neq 0$) fall inside the "allowed" values of your radical part ($x \ge -3$). If they do, you must explicitly cut them out of the interval.

### Operations of Functions: Division Example (Radical / Rational)

Dividing a radical function by a rational function requires careful algebraic manipulation and a multi-step domain check. Because $g(x)$ is the divisor, it creates two separate potential restrictions.

---
#### 1. The Functions
$f(x) = \sqrt{x+3}$
$g(x) = \frac{5}{x}$

#### 2. Identify Initial Restrictions
Before dividing, find the domains of the starting functions:
* **For $f(x)$:** $x + 3 \ge 0 \Rightarrow x \ge -3$
* **For $g(x)$:** $x \neq 0$

#### 3. Perform the Operation $(f / g)(x)$
To divide by a fraction, multiply by its reciprocal:
$$(f / g)(x) = \frac{\sqrt{x+3}}{1} \div \frac{5}{x}$$
$$(f / g)(x) = \sqrt{x+3} \cdot \frac{x}{5}$$

**Final Simplified Result:**
$$(f / g)(x) = \frac{x\sqrt{x+3}}{5}$$
---
### ⚠️ What to Look Out For

> [!important] The "Three-Layer" Domain Check
> When you divide $f/g$, the domain must satisfy three conditions simultaneously:
> 1. The domain of $f$ ($x \ge -3$).
> 2. The domain of $g$ ($x \neq 0$).
> 3. Anywhere that $g(x) = 0$.

#### 1. Checking if $g(x) = 0$
In this specific case, $g(x) = \frac{5}{x}$. A fraction only equals zero if its **numerator** is zero. Since the numerator is a constant ($5$), $g(x)$ can never equal zero. Therefore, this third condition adds no new restrictions.

#### 2. The "Disappearing" Denominator
Looking at the final result $\frac{x\sqrt{x+3}}{5}$, it appears that $x=0$ would be perfectly fine to plug in. However, because $x=0$ was restricted in the **original** function $g(x)$, it remains restricted in the final result.
* **Result at $x=0$:** $f(0)/g(0) = \sqrt{3} / (5/0)$, which is undefined.

#### 3. Final Domain Construction
We combine $x \ge -3$ and $x \neq 0$:
* **Inequality Notation:** $x \ge -3, x \neq 0$
* **Interval Notation:** $[-3, 0) \cup (0, \infty)$
* **Set Builder Notation:** $\{x \mid x \in \mathbb{R}, x \ge -3, x \neq 0\}$
---

> [!abstract] Algebra Takeaway
> In division, the "bad" values from the original denominator stay "bad" even if the denominator is flipped into the numerator. In your Obsidian vault, note that for $f/g$, the final domain is the intersection of the domains of $f$ and $g$, minus any values where the output of $g$ is zero.

## 2026-March-10 - Using the Vertical Line Test (Precalculus - College Algebra 6) : 
https://www.youtube.com/watch?v=7j6kh8Z2H90&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=6
### Using the Vertical Line Test

The Vertical Line Test (VLT) is a graphical method used to determine if a relationship between an input and an output is a **function**. 

---
#### 1. Why It Works (The Core Logic)
* **The Definition of a Function:** For every single input, there can only be exactly **one** output [00:00:48].
* **Axis Orientation:**
    * **Horizontal Axis:** Represents inputs ($x$-values) [00:01:05].
    * **Vertical Axis:** Represents outputs ($y$-values) [00:01:43].
* **The Interplay:** When you pick an input on the horizontal axis, its corresponding output must be located directly above or below it. Therefore, checking vertically allows you to see how many outputs exist for that one specific input [00:02:18].

---
#### 2. How to Perform the Test
1.  Imagine a vertical line moving across the graph from left to right.
2.  At any given point, observe how many times that vertical line crosses the graph.
3.  **The Rule:** * If the line touches the graph at **most** one time for every input, the graph is a **function** [00:05:15].
    * If the line touches the graph **more than once** at any point, it is **not a function** [00:07:08].

---
#### 3. Key Examples
* **Straight & Wavy Lines:** Linear functions and polynomials typically pass the test because any vertical slice only hits the line once [00:05:15].
* **Circles & Sideways Parabolas:** These **fail** the VLT because a vertical line will hit both the top and the bottom of the shape, meaning one $x$ has two different $y$ outputs [00:07:08].
* **Vertical Lines:** A vertical line fails its own test because for that one specific $x$-input, there are an infinite number of $y$-outputs [00:10:35].

---
#### 4. Important Clarifications
* **Multiple Inputs, Same Output:** It is perfectly fine for two different inputs to have the same output (like a horizontal line or a parabola). The VLT only cares if one input has **more than one** output [00:04:47].
* **No Outputs:** If a vertical line doesn't touch the graph at all (like looking at negative $x$ values for $\sqrt{x}$), it is **still a function**. A function doesn't have to have an output for every possible number, but for every input it *does* use, it can only have one output [00:08:25].

---

> [!abstract] Algebra Takeaway
> Use the Vertical Line Test as a quick visual "sanity check" whenever you are graphing, especially with **Piecewise Functions**. If your graph overlaps vertically at any point, you have accidentally created a non-function relationship [00:11:31].

## 2026-March-11 - Features of Graphs, Domain, Range (Precalculus - College Algebra 7) :
https://www.youtube.com/watch?v=d3b-4Zz65ZE&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=8
### Features of Graphs, Domain, Range

Analyzing a graph involves understanding the relationship between inputs ($x$) and outputs ($f(x)$ or $y$). Every point on a graph is simply a completed pair $(x, f(x))$ that satisfies the function's equation [00:01:01].

---

#### 1. Evaluating Points Graphically
* **Given an Input:** To find $f(0)$, go to $x=0$ on the horizontal axis and find the corresponding $y$-value on the graph [00:01:44].
* **Given an Output:** To find $x$ when $f(x) = 2$, look at the height of $y=2$ and find which $x$-values hit the graph at that level [00:24:00].
* **Positive vs. Negative:** $f(x) > 0$ means the graph is **above** the $x$-axis. $f(x) < 0$ means it is **below** the $x$-axis [00:03:46].

---

#### 2. Domain (The $x$-axis Interval)
The **Domain** is the section of the $x$-axis that the graph "covers" from left to right [00:17:06].
* **Visualizing:** Imagine squashing the graph onto the $x$-axis. The resulting line is your domain [00:36:03].
* **Arrows:** If the graph has arrows pointing left and right, the domain is often $(-\infty, \infty)$ [00:29:22].
* **Open Circles:** An open circle at an endpoint means that specific $x$-value is **excluded** (use parentheses) [00:32:00].

---

#### 3. Range (The $y$-axis Interval)
The **Range** is the section of the $y$-axis that the graph "covers" from bottom to top [00:19:34].
* **Visualizing:** Squash the graph onto the $y$-axis. Look for the lowest point (minimum) and the highest point (maximum) [00:20:36].
* **Asymptotes:** If a graph approaches a horizontal line but never touches it, that value is excluded from the range [00:31:06].

---

#### 4. Intercepts
* **$x$-intercepts:** Points where the graph crosses the $x$-axis (where $f(x) = 0$). A function can have many $x$-intercepts [00:06:51].
* **$y$-intercept:** Point where the graph crosses the $y$-axis (where $x = 0$). A function can have at most **one** $y$-intercept to pass the Vertical Line Test [00:22:47].

---

#### 5. Solving Algebraically (Without a Graph)
If you are given an equation like $f(x) = \frac{x+2}{x-6}$:
* **Find the Domain:** Set the denominator $\neq 0$. Here, $x \neq 6$ [00:44:06].
* **Find $x$-intercepts:** Set the **numerator** equal to zero ($x+2 = 0 \Rightarrow x = -2$) [00:46:27].
* **Find $y$-intercepts:** Plug in $0$ for $x$ and solve for $y$ ($f(0) = \frac{0+2}{0-6} = -\frac{1}{3}$) [00:47:11].
* **Find $x$ for a specific output:** If $f(x) = 2$, set the entire equation equal to $2$ and solve for $x$ ($2 = \frac{x+2}{x-6}$) [00:40:18].

---

### ⚠️ What to Look Out For

> [!warning] Brackets vs. Parentheses
> * Use **Brackets $[ ]$** when a point is "closed" (filled in) or the graph explicitly reaches that value [00:18:57].
> * Use **Parentheses $( )$** for open circles, asymptotes, or infinities [00:12:23].

> [!warning] Intercept Confusion
> Do not confuse $f(0)$ with $f(x)=0$. 
> * $f(0)$ is the **$y$-intercept** (plug in 0). 
> * $f(x)=0$ are the **$x$-intercepts** (solve for 0) [00:05:34].

---

> [!abstract] Algebra Takeaway
> Domain and Range are one-dimensional descriptions of a two-dimensional shape. Domain only looks at "left-to-right," while Range only looks at "down-to-up" [00:20:39]. Always check for open circles or asymptotes that might "break" your intervals.

