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

## 2026-March-13 - Properties of Functions - Even vs Odd (Precalculus - College Algebra 8) :
https://www.youtube.com/watch?v=6897XAx3O9Q&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=9
- **Even Function** = Symmetric about *Y-Axis*
- **Odd Function** = Summetric about *Origin* - Need to rotate 180 degrees 
- **Neither** = No Symmetry - Featureless
- Why is this important? Graphing Polynomials/Rational Functions - Graphing Even Vs Odd tells you alot about how they look and behave
- Sometimes you don't have a graph to look at, methods to distinguish each type below :
- $f(x) = f(-x)$  : **Even** functions the outputs are the same when you plug in opposite inputs (IE : 4, -4 would give the same result) 
- $-f(x) = f(-x)$ : **Odd** Functions the outputs are opposite when you plug in opposite inputs - Opposite inputs = Opposite Outputs
- **Odd powers** like $x^1 x^3 x^5...$ etc will always change the power sign when you $f(-x)$ while **Even Powers** like $x^2 x^4 x^6 ...$ etc will always stay the same even when you input $f(-x)$ = A quick way to check if something is an even or odd function through polynomials - constants won't change though and won't give you the opposite answer and become **Neither** 
### Properties of Functions: Even vs. Odd

A common misconception is that "even" or "odd" refers solely to the exponents in a polynomial. While related, the mathematical definition is actually based on how a function handles **opposite inputs** ($x$ and $-x$) [00:00:52].

---
#### 1. Even Functions (Y-Axis Symmetry)
A function is **even** if plugging in an opposite input results in the exact same output [00:10:02].
* **Algebraic Definition:** $f(-x) = f(x)$ [00:11:00].
* **Graphical Feature:** Symmetric about the **y-axis**. If you fold the graph along the y-axis, the two sides match perfectly [00:01:22].
* **Example:** $f(x) = x^4 + x^2 + 5$. Plugging in $-x$ gives $(-x)^4 + (-x)^2 + 5$, which simplifies back to $x^4 + x^2 + 5$ [00:18:05].

---
#### 2. Odd Functions (Origin Symmetry)
A function is **odd** if plugging in an opposite input results in an opposite output [00:12:06].
* **Algebraic Definition:** $f(-x) = -f(x)$ [00:15:02].
* **Graphical Feature:** Symmetric about the **origin**. If you rotate the graph $180^\circ$ around $(0,0)$, it looks identical. Another way to visualize this is a "double flip"—reflect it over the y-axis, then the x-axis [00:01:58].
* **Example:** $g(x) = \frac{x}{x^2 - 1}$. Plugging in $-x$ results in $\frac{-x}{(-x)^2 - 1} = -\left(\frac{x}{x^2 - 1}\right)$ [00:19:32].

---
#### 3. Neither Even nor Odd
Many functions have no symmetry at all. 
* **The "Neither" Case:** If $f(-x)$ does not equal $f(x)$ AND it does not equal $-f(x)$, it is neither [00:22:20].
* **The Domain Check:** A function cannot be even or odd if its domain is not symmetric. For example, $h(x) = \sqrt{x}$ is neither because negative inputs are not even defined, so you cannot compare $f(x)$ to $f(-x)$ [00:27:17].

---
#### 4. The Algebraic Test Strategy
To determine if a function is even, odd, or neither without a graph:
1.  Replace every $x$ with $(-x)$ [00:16:13].
2.  Simplify the expression:
    * **Even powers** ($2, 4, 6...$) and absolute values "eat" the negative sign [00:18:20].
    * **Odd powers** ($1, 3, 5...$) and the sine function preserve the negative sign [00:19:44].
    * **Constants** never change [00:21:12].
3.  Compare the result to the original:
    * Matches original? **Even**.
    * Every sign is flipped (original with a negative out front)? **Odd**.
    * Some signs flipped but not all? **Neither**.
---
> [!abstract] Algebra Takeaway
> Symmetry is a powerful tool for graphing. If you know a function is **even**, you only need to plot half of it and mirror it. If it is **odd**, you know it *must* pass through the origin (if $0$ is in the domain) because $f(0)$ would have to equal $-f(0)$, which only happens at $0$ [00:13:48].
### Determining Symmetry for f(x) = 2x⁴ - x²

To determine if a function is even, odd, or neither, we apply the **Algebraic Test for Symmetry** by replacing every $x$ with $(-x)$ and simplifying.

---
#### The Algebraic Test
**1. Substitute $(-x)$ into the function:**
$$f(-x) = 2(-x)^4 - (-x)^2$$

**2. Simplify the terms:**
* $(-x)^4 = x^4$ (Any negative number raised to an **even** power becomes positive).
* $(-x)^2 = x^2$ (Similarly, this even power results in a positive).

So, the equation becomes:
$$f(-x) = 2(x^4) - (x^2)$$
$$f(-x) = 2x^4 - x^2$$

**3. Compare to the original function:**
* The simplified result $2x^4 - x^2$ is **exactly the same** as the original $f(x)$.

---
#### Final Classification
Since **$f(-x) = f(x)$**, this is an **Even Function**.

---

#### ⚠️ What to Look Out For

> [!important] The Exponent Shortcut
> In polynomial functions, if **all** exponents are even (including the "hidden" $x^0$ for constant terms), the function is Even. If **all** exponents are odd, the function is Odd. 
> * Here, $4$ and $2$ are both even, which confirms our algebraic result.
> * If the function was $f(x) = 2x^4 - x^2 + 5x$, the $x^1$ term would break the symmetry, making it **Neither**.

#### Graphical Meaning: Y-Axis Symmetry
Because this function is even, its graph is perfectly symmetric across the **y-axis**. If you were to calculate the point $(2, 28)$, you automatically know that the point $(-2, 28)$ also exists on the graph.

---

> [!abstract] Algebra Takeaway
> Always perform the $(-x)$ substitution to be certain. While the exponent shortcut works for polynomials, it does not work for functions involving radicals, absolute values, or trigonometry. For an even function, the negative sign is effectively "eaten" by the even powers.
### Determining Symmetry for $g(x) = \frac{x}{x^2-1}$

To determine if a function is even, odd, or neither, we evaluate $g(-x)$ and compare the resulting expression to the original $g(x)$.

---
#### The Algebraic Test
**1. Substitute $(-x)$ into the function:**
$$g(-x) = \frac{(-x)}{(-x)^2 - 1}$$

**2. Simplify the terms:**
* The numerator is simply $-x$.
* The denominator has $(-x)^2$, which simplifies to $x^2$ because the even exponent "eats" the negative sign.

So, the expression becomes:
$$g(-x) = \frac{-x}{x^2 - 1}$$

**3. Compare to the original function:**
* **Is it Even?** No. $g(-x)$ is not the same as $\frac{x}{x^2 - 1}$.
* **Is it Odd?** Let's check if $g(-x) = -g(x)$. 
  If we factor the negative out of the numerator, we get:
  $$g(-x) = -\left( \frac{x}{x^2 - 1} \right)$$
  This is exactly the negative of the original function.

---
#### Final Classification
Since **$g(-x) = -g(x)$**, this is an **Odd Function**.

---
#### ⚠️ What to Look Out For

> [!important] Symmetry of Components
> This function is a fraction. In rational functions, you can often predict symmetry by looking at the "parity" of the top and bottom:
> * **Numerator ($x$):** Odd power ($x^1$).
> * **Denominator ($x^2 - 1$):** Even powers ($x^2$ and the constant $x^0$).
> * **The Rule:** An **Odd** divided by an **Even** (or vice versa) results in an **Odd** function. If both were the same (Even/Even or Odd/Odd), the result would be **Even**.

#### Graphical Meaning: Origin Symmetry
Because this function is odd, it has **rotational symmetry** around the origin $(0,0)$. If you rotate the graph $180^\circ$, it will land perfectly on itself. This means that if the point $(2, \frac{2}{3})$ is on the graph, the point $(-2, -\frac{2}{3})$ must also be on the graph.

---

> [!abstract] Algebra Takeaway
> For rational functions, the negative sign from the $(-x)$ substitution in the numerator can be pulled out to the front of the entire fraction. If the denominator remains unchanged (which happens if it only contains even powers and constants), the whole function effectively flips its sign, confirming it is odd.

### Determining Symmetry for h(x) = 3x³ + 5

To determine if a function is even, odd, or neither, we evaluate $h(-x)$ and compare the result to both the original $h(x)$ and its negative version $-h(x)$.

---

#### The Algebraic Test
**1. Substitute $(-x)$ into the function:**
$$h(-x) = 3(-x)^3 + 5$$

**2. Simplify the terms:**
* $(-x)^3 = -x^3$ (A negative number raised to an **odd** power remains negative).
* The constant $+5$ remains unchanged.

So, the expression becomes:
$$h(-x) = -3x^3 + 5$$

**3. Compare to the original $h(x)$:**
* **Is it Even?** No. $-3x^3 + 5$ is not the same as $3x^3 + 5$.
* **Is it Odd?** To be odd, every single sign must flip ($h(-x)$ would need to equal $-3x^3 - 5$).
* **Check:** Our result has a flipped sign for the $x^3$ term, but the constant $+5$ stayed the same.

---
#### Final Classification
Since $h(-x)$ is neither the same as the original function nor the exact negative of the original function, this is a **Neither Function**.

---
#### ⚠️ What to Look Out For

> [!important] The "Constant" Spoiler
> In polynomials, a constant term (like $+5$) is technically $5x^0$. Since $0$ is an even number, a constant acts as an **even** component. 
> * If you add a constant to an **odd** function (like $3x^3$), the symmetry is broken.
> * The $3x^3$ term wants origin symmetry, but the $+5$ shifts the graph up, moving the "center" of the symmetry away from the origin $(0,0)$.

#### Graphical Meaning
Because this function is neither, it lacks the specific symmetries needed for a classification:
* It is not mirrored across the y-axis (Not Even).
* It cannot be rotated $180^\circ$ around the origin to land on itself (Not Odd).

---

> [!abstract] Algebra Takeaway
> For a polynomial to be **Odd**, every single term (including constants) must have an odd exponent. Since a constant is an even-powered term ($x^0$), its presence in an otherwise odd polynomial immediately results in a classification of **Neither**.

### Determining Symmetry for $f(x) = \frac{x^2 + 3}{x^2 - 1}$

To determine if the function is even, odd, or neither, we apply the algebraic test by substituting $(-x)$ for every $x$ and simplifying the result.

---

#### The Algebraic Test
**1. Substitute $(-x)$ into the function:**
$$f(-x) = \frac{(-x)^2 + 3}{(-x)^2 - 1}$$

**2. Simplify the terms:**
* In the numerator, $(-x)^2 = x^2$ because an even power eliminates the negative sign.
* In the denominator, $(-x)^2 = x^2$ for the same reason.

So, the expression becomes:
$$f(-x) = \frac{x^2 + 3}{x^2 - 1}$$

**3. Compare to the original function:**
* The simplified result $\frac{x^2 + 3}{x^2 - 1}$ is **exactly the same** as the original $f(x)$.

---

#### Final Classification
Since **$f(-x) = f(x)$**, this is an **Even Function**.

---

#### ⚠️ What to Look Out For

> [!important] The Rational Symmetry Rule
> For a rational function (a fraction of polynomials), you can check the symmetry of the numerator and denominator separately:
> * **Numerator ($x^2 + 3$):** All even powers ($x^2$ and constant $x^0$). This is an **Even** expression.
> * **Denominator ($x^2 - 1$):** All even powers ($x^2$ and constant $x^0$). This is an **Even** expression.
> * **The Rule:** An **Even** divided by an **Even** always results in an **Even** function.

#### Graphical Meaning: Y-Axis Symmetry
Because this function is even, the graph is a mirror image across the **y-axis**. This function has vertical asymptotes at $x = 1$ and $x = -1$. Because of the even symmetry, the behavior of the graph near $x = 1$ will be perfectly mirrored near $x = -1$.

---

> [!abstract] Algebra Takeaway
> In your Obsidian vault, note that "Even / Even = Even" and "Odd / Odd = Even". Only when you have a "mismatch" (one even and one odd) do you end up with an **Odd** function. If either the top or the bottom is "Neither," the entire function will be **Neither**.

### Determining Symmetry for $h(x) = \frac{-x^3}{3x^2 - 9}$

To determine the symmetry of this rational function, we test how it reacts to a negative input by evaluating $h(-x)$.

---
#### The Algebraic Test
**1. Substitute $(-x)$ into the function:**
$$h(-x) = \frac{-(-x)^3}{3(-x)^2 - 9}$$

**2. Simplify the terms:**
* **Numerator:** $(-x)^3 = -x^3$. Substituting this back gives $-(-x^3)$, which simplifies to **$x^3$**.
* **Denominator:** $(-x)^2 = x^2$ because the even power "eats" the negative sign. The constant $-9$ remains unchanged.

The expression now looks like this:
$$h(-x) = \frac{x^3}{3x^2 - 9}$$

**3. Compare to the original $h(x)$:**
* **Is it Even?** No. $\frac{x^3}{3x^2 - 9}$ is not the same as $\frac{-x^3}{3x^2 - 9}$.
* **Is it Odd?** Let's check if $h(-x) = -h(x)$. 
  If we take the original function $h(x) = \frac{-x^3}{3x^2 - 9}$ and multiply it by $-1$, we get:
  $$-h(x) = -\left( \frac{-x^3}{3x^2 - 9} \right) = \frac{x^3}{3x^2 - 9}$$
  This matches our result for $h(-x)$ exactly.

---
#### Final Classification
Since **$h(-x) = -h(x)$**, this is an **Odd Function**.

---
#### ⚠️ What to Look Out For

> [!important] The Parity Shortcut
> You can quickly verify this by looking at the "parity" of the numerator and denominator:
> * **Numerator ($-x^3$):** Only an odd power ($x^3$). This is an **Odd** expression.
> * **Denominator ($3x^2 - 9$):** All even powers ($x^2$ and the constant $x^0$). This is an **Even** expression.
> * **The Rule:** An **Odd** divided by an **Even** results in an **Odd** function.

#### Graphical Meaning: Origin Symmetry
Because this is an odd function, the graph has **rotational symmetry** around the origin $(0,0)$. This function has vertical asymptotes at $x = \sqrt{3}$ and $x = -\sqrt{3}$. If the graph goes "up" toward positive infinity at one asymptote, it will go "down" toward negative infinity at the other in a mirrored, rotated fashion.

---

> [!abstract] Algebra Takeaway
> In rational functions, a single negative sign in the numerator can be thought of as a "toggle." When you plug in $(-x)$, the numerator's sign flips while the denominator stays the same. This results in the entire function's sign flipping, which is the definition of an odd function.

### Determining Symmetry for g(x) = \sqrt{x}

To determine if a function is even, odd, or neither, we evaluate $g(-x)$ and compare it to $g(x)$. However, for radical functions, the first step should always be checking the **domain**.

---
#### 1. The Domain Check
The square root function $g(x) = \sqrt{x}$ is only defined for $x \ge 0$.
* **The Restriction:** Negative numbers are not in the domain of this function.
* **The Requirement for Symmetry:** To be even or odd, a function must have a **symmetric domain**. This means if you can plug in $x$, you must also be able to plug in $-x$ [00:27:17].

Since we cannot plug in $-5$ if we plug in $5$, the function cannot possibly be even or odd.

---
#### 2. The Algebraic Test
Even if we ignore the domain and try to plug in $(-x)$:
$$g(-x) = \sqrt{-x}$$
* **Is it Even?** No. $\sqrt{-x}$ is not the same as $\sqrt{x}$.
* **Is it Odd?** No. $\sqrt{-x}$ is not the same as $-\sqrt{x}$.

---
#### Final Classification
Because the function is not defined for negative $x$-values, it lacks the necessary inputs to be compared. Therefore, $g(x) = \sqrt{x}$ is a **Neither Function**.

---
### ⚠️ What to Look Out For

> [!important] The "Symmetric Domain" Rule
> Always check the domain first. If a function only exists on one side of the y-axis (like $\sqrt{x}$ or $\ln(x)$), it is automatically **Neither**. Symmetry requires a "mirror image" partner for every point, and if the $x$-values don't exist on both sides, the mirror image can't exist.

#### Graphical Meaning
The graph of $\sqrt{x}$ starts at the origin $(0,0)$ and shoots off into the first quadrant. There is absolutely nothing in the second or third quadrants to "match" it, so there is no y-axis symmetry (Even) or origin symmetry (Odd).

---

> [!abstract] Algebra Takeaway
> In your Obsidian vault, note that **Radical Functions** with an even index (square root, fourth root) are almost always **Neither** unless there is an absolute value or an even power inside the radical (e.g., $\sqrt{x^2}$), which would change the domain to $(-\infty, \infty)$.

## 2026-March-13 - Properties of Functions - Increasing vs Decreasing (Precalculus - College Algebra 9) :
https://www.youtube.com/watch?v=cIRDvscVPr0&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=9
### Properties of Functions: Increasing vs. Decreasing

Understanding where a function increases or decreases is essential for identifying "peaks" (maximums) and "troughs" (minimums) in a graph. These properties describe the behavior of the output ($y$) as the input ($x$) moves from left to right [00:00:13].

---
#### 1. Core Definitions
* **Increasing:** As you move from **left to right** along the x-axis, the graph climbs upward. Algebraically, as $x$ gets larger, the output $f(x)$ also gets larger [00:01:24].
* **Decreasing:** As you move from **left to right**, the graph falls downward. Algebraically, as $x$ gets larger, the output $f(x)$ gets smaller [00:01:45].
* **Constant:** The graph is a horizontal line; the output remains the same as $x$ increases [00:07:54].
---
#### 2. The "Two-Hand" Method for Intervals
To correctly identify these intervals, use this technique:
* **Right Hand:** Trace the actual curve of the graph.
* **Left Hand:** Mark the corresponding section on the **x-axis** [00:04:43].
* **The Goal:** You are describing **where on the x-axis** the behavior is happening, not how high or low the graph goes [00:03:30].

---
#### 3. Strict Rules for Notation
> [!important] Always Use Open Intervals
> When writing intervals for increasing or decreasing behavior, **never use brackets $[ ]$**. Always use **parentheses $( )$** [00:01:51].
> * **Reasoning:** At the exact "turning point" (the peak or trough), the graph is neither increasing nor decreasing—it is momentarily flat. Since you can't be "climbing" at a single stagnant point, endpoints are excluded [00:05:33].

---
#### 4. Examples & Scenarios
* **Polynomials/Wavy Graphs:** These often switch between behaviors. For example, a graph might be increasing on $(-2, 0)$ and $(2, 4)$, and decreasing on $(-4, -2)$ and $(0, 2)$ [00:05:15].
* **Infinite Behavior (Arrows):** If a graph is falling and has an arrow pointing to the left, it is decreasing from $(-\infty, \text{point})$. If it climbs and has an arrow pointing right, it is increasing to $(\text{point}, \infty)$ [00:10:03].
* **Logarithmic/Square Root Styles:** A graph like $\sqrt{x}$ only exists for $x \ge 0$. It increases over its entire domain: $(0, \infty)$ [00:14:01].

---
### ⚠️ What to Look Out For

> [!warning] The "Y-Axis" Trap
> A common mistake is to list the $y$-values (the height) in the interval. **Increasing/Decreasing intervals are always x-axis values.** If a graph climbs from a height of $-5$ to $10$ between $x=1$ and $x=3$, the interval is $(1, 3)$, NOT $(-5, 10)$ [00:14:24].

> [!warning] Reading the "Wrong" Way
> Always read the graph from **left to right**. An arrow pointing down and to the left might *look* like it's increasing if you follow it toward the origin, but as you move left-to-right, that section is actually falling (decreasing) [00:09:33].

---

> [!abstract] Algebra Takeaway
> Increasing and decreasing intervals tell you the "story" of the graph's movement. In your Obsidian vault, note that these intervals are the foundation for finding **Relative Extrema** (the next topic), as a maximum only occurs where a function switches from increasing to decreasing [00:14:50].
## 2026-March-14 - Properties of Functions - Extrema (Precalculus - College Algebra 10) :
https://www.youtube.com/watch?v=2hItEGb3KJo&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=12
### Properties of Functions: Extrema (Max/Min)

Analyzing extrema involves identifying the highest and lowest points of a graph. These are categorized into **Local (Relative)** and **Absolute** values.

---
#### 1. Local (Relative) Extrema
A local maximum or minimum is a high or low point within a "neighborhood" (a small open interval) of the graph [00:00:46].
* **Local Maximum:** Occurs where a function changes from **increasing to decreasing**. It creates a "peak" [00:02:18].
* **Local Minimum:** Occurs where a function changes from **decreasing to increasing**. It creates a "trough" [00:03:13].
* **The Neighborhood Rule:** Local extrema can only exist on an **open interval**. This means **endpoints can never be local extrema** because you cannot check both sides of the point [00:06:53].

---
#### 2. Absolute Extrema
The absolute maximum or minimum is the single highest or lowest value attained by the function over its entire domain [00:04:34].
* **Absolute Maximum:** The highest $y$-value on the entire graph [00:04:34].
* **Absolute Minimum:** The lowest $y$-value on the entire graph [00:04:40].
* **Endpoints:** Unlike local extrema, absolute extrema **can occur at endpoints** [00:06:08].

---
#### 3. The Extreme Value Theorem
Every **closed, continuous interval** (no gaps, no asymptotes, and including endpoints) is guaranteed to have both an absolute maximum and an absolute minimum [00:05:05].
* If the interval is open or the function is discontinuous (e.g., has a hole), there may be no absolute maximum or minimum [00:15:14].

---
#### 4. Critical Distinctions
* **Output vs. Location:** The "maximum" or "minimum" is the **$y$-value** (the output). The $x$-value is merely **where** it occurs [00:01:24].
    * *Example:* If a peak is at $(2, 4)$, the local maximum is **4** at $x=2$ [00:08:21].
* **Multiple Occurrences:** A function can have many local maxima/minima (like a roller coaster), and an absolute maximum can occur at multiple $x$-values if they all reach the same highest height [00:25:05].

---
### ⚠️ What to Look Out For

> [!important] The "Hole" Trap
> If a peak or trough is represented by an open circle (a hole), there is **no local or absolute extremum** at that point. You can get infinitely close to the value, but you never actually reach it, so no maximum exists [00:16:27].

> [!warning] Infinity is Not an Extremum
> If a graph goes up forever (arrows pointing to $\infty$) or has a vertical asymptote, there is **no absolute maximum**. Infinity is a direction, not a specific value attained by the function [00:19:46].

---

> [!abstract] Algebra Takeaway
> To find extrema on a graph:
> 1. Mark every peak and trough as a **Local** max/min (excluding endpoints).
> 2. Compare all peaks and endpoints to find the single highest point (**Absolute Max**).
> 3. Compare all troughs and endpoints to find the single lowest point (**Absolute Min**).

## 2026-March-14 - Average Rate of Change of a Function (Precalculus - College Algebra 11) : 
https://www.youtube.com/watch?v=H5Y-ONkezDM&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=11
### Average Rate of Change of a Function

The **Average Rate of Change** calculates how much a function's output changes relative to its input over a specific interval $[a, b]$. Geometrically, this is the slope of the **secant line** connecting two points on a curve.

---
#### 1. The Secant Line
Since you cannot find a single "slope" for a curved line, we use a straight line (secant line) to connect two points $(a, f(a))$ and $(b, f(b))$. The slope of this line represents the average change over that distance.



#### 2. The Formula
The formula is identical to the slope formula ($m = \frac{y_2 - y_1}{x_2 - x_1}$), but expressed in function notation:

$$\text{Average Rate of Change} = \frac{f(b) - f(a)}{b - a}$$

#### 3. Calculation Steps
To find the average rate of change for a function $f(x)$ on interval $[a, b]$:
1.  **Find the outputs:** Calculate $f(a)$ and $f(b)$ by plugging the x-values into the equation.
2.  **Plug into the formula:** Subtract the outputs for the numerator and the inputs for the denominator.
3.  **Simplify:** The resulting value is the slope of the secant line.

---
### ⚠️ What to Look Out For

> [!important] Direction Matters
> If the result is **positive**, the function is increasing on average over that interval. If **negative**, it is decreasing. If **zero**, the starting and ending heights are the same.

#### 1. Order Consistency
Ensure that if you start with $f(b)$ in the numerator, you start with $b$ in the denominator. Mixing the order ($f(b)-f(a) / a-b$) will result in the wrong sign.

#### 2. Average vs. Instantaneous
The average rate of change covers a "gap." In Calculus, this formula is used as the basis for the **Difference Quotient**, which leads to finding the "Instantaneous Rate of Change" (the slope at exactly one point).

---

> [!abstract] Algebra Takeaway
> "Average Rate of Change" is simply code for "find the slope." Treat it as a two-point slope problem every time.

### Finding the Average Rate of Change for f(x) = x² - 2x

The Average Rate of Change (ROC) over the interval $[3, 5]$ is the slope of the secant line connecting the points on the graph where $x=3$ and $x=5$.

---
#### 1. The Function and Interval
* **Function:** $f(x) = x^2 - 2x$
* **Interval:** $[3, 5]$

#### 2. Find the Coordinate Pairs
To use the slope formula, we first need the $y$-values (outputs) for our given $x$-values.

**For x = 3:**
$$f(3) = (3)^2 - 2(3)$$
$$f(3) = 9 - 6 = 3$$
*Point 1:* $(3, 3)$

**For x = 5:**
$$f(5) = (5)^2 - 2(5)$$
$$f(5) = 25 - 10 = 15$$
*Point 2:* $(5, 15)$

#### 3. Apply the Average ROC Formula
$$\text{Average ROC} = \frac{f(5) - f(3)}{5 - 3}$$
$$\text{Average ROC} = \frac{15 - 3}{5 - 3}$$
$$\text{Average ROC} = \frac{12}{2} = 6$$

**Final Result:** The average rate of change is **6**.

---
### ⚠️ What to Look Out For

> [!important] Geometric Interpretation
> On the graph of $x^2 - 2x$, the curve is actually getting steeper as $x$ increases. The value **6** tells us that, on average, for every 1 unit we move to the right between $x=3$ and $x=5$, the graph rises by 6 units.

#### 1. Negative Signs in Subtraction
If your $y$-values were negative, be extremely careful with the "double negative" in the numerator.
* *Example:* If $f(a) = -4$, the numerator would be $f(b) - (-4)$, which becomes $f(b) + 4$.

#### 2. The "Units" of ROC
If this function represented physical movement:
* **$x$** = time in seconds
* **$f(x)$** = position in meters
* **ROC (6)** = average velocity in **meters per second**.

---

> [!abstract] Algebra Takeaway
> Finding the average rate of change is a three-step process: find the two points, find the difference in $y$, and divide by the difference in $x$. It is essentially the Algebra 1 slope formula dressed up in Precalculus notation.

## 2026-March-15 - How to Graph Piecewise Functions (Precalculus - College Algebra 12) :
https://www.youtube.com/watch?v=KHZKgl_9o7M&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=14
### Graphing Piecewise Functions

Piecewise functions are functions defined by different rules (pieces) for different intervals of the domain. Each piece behaves like a standard function but is only "active" on a specific part of the x-axis.

---
#### 1. Understanding the Notation
A piecewise function is defined by two parts:
- **The "What":** The expressions (like $x^2$ or $3x-2$) tell you *what* shape to graph.
- **The "When":** The inequalities (the constraints) tell you *where* on the x-axis to graph that shape.
#### 2. Evaluating Piecewise Functions
To find an output $f(a)$, you must look at the constraints first.
* **The "One-Piece" Rule:** Never plug the same value into both pieces. A function must only produce one output.
* **Boundary Values:** If a value falls exactly on the boundary, use the equation that includes the "or equal to" ($\le$ or $\ge$) sign.
#### 3. Step-by-Step Graphing
1.  **Mark Boundaries:** Draw light vertical dashed lines at the $x$-values where the function changes rules. These are your "fences."
2.  **Plot the Endpoints:**
    * Plug the boundary value into the equation for that piece.
    * **$\le$ or $\ge$ (Included):** Use a **closed circle** (solid dot).
    * **$<$ or $>$ (Excluded):** Use an **open circle** (hole).
3.  **Fill in the Shape:** Use your knowledge of parent functions (slopes for lines, curves for cubics) to draw the piece only within its allowed section.

---
### ⚠️ What to Look Out For

> [!important] The "Eraser" Method
> If it’s easier, you can graph the entire function for each piece lightly in pencil, then erase everything that falls outside its specified domain constraint.

#### 1. Continuity vs. Discontinuity
* **Continuous:** The pieces meet perfectly at the boundary. You can draw the whole graph without lifting your pencil.
* **Discontinuous:** There is a "jump" or a "gap" where one piece ends and another begins at a different height.
#### 2. The Vertical Line Test
Even though a piecewise function has multiple parts, it must still pass the Vertical Line Test. If you have two solid dots stacked vertically at a boundary, it is **not** a function.

---

> [!abstract] Algebra Takeaway
> Treat each piece as its own mini-problem. The most critical part is correctly identifying whether the endpoint is a solid dot (included) or an open hole (excluded).

### Evaluating the Piecewise Function: f(x) = { x³, x < 1 | 3x - 2, x ≥ 1 }

Evaluating a piecewise function is a process of "logic first, math second." You must decide which rule applies to your input before performing any calculations.

---
#### 1. Evaluation Breakdown

| Input ($x$) | Constraint Check | Rule to Use | Calculation | Result |
| :--- | :--- | :--- | :--- | :--- |
| **$f(-1)$** | $-1 < 1$ (True) | $x^3$ | $(-1)^3$ | **$-1$** |
| **$f(0)$** | $0 < 1$ (True) | $x^3$ | $(0)^3$ | **$0$** |
| **$f(1)$** | $1 \ge 1$ (True) | $3x - 2$ | $3(1) - 2$ | **$1$** |
| **$f(3)$** | $3 \ge 1$ (True) | $3x - 2$ | $3(3) - 2$ | **$7$** |

---
#### 2. What to Watch Out For

> [!important] The "Boundary" Hand-off
> At $x = 1$, the function switches from a cubic curve to a linear slope. 
> * Since the rule for $x \ge 1$ is $3x - 2$, the point $(1, 1)$ is a **closed circle** (solid dot).
> * If we were to check the "limit" of the first piece ($x^3$) as it approaches 1, it would also equal 1. Because both pieces "meet" at the same $y$-value, this function is **continuous** at the boundary.

#### 3. Common Errors to Avoid
1.  **Double-Dipping:** Never plug $x=1$ into both equations. Even if they give the same answer (as they do here), mathematically, the input only belongs to the piece with the "or equal to" ($\ge$) sign.
2.  **Misreading the Inequality:** It is easy to see "1" and grab the first equation by default. Always look at the symbol:
    * $x < 1$: Everything *up to* but not including 1.
    * $x \ge 1$: Everything *including* 1 and above.
3.  **The Negative Cube:** When evaluating $f(-1)$, remember that $(-1)^3 = -1$. Odd powers preserve the negative sign, whereas even powers (like $x^2$) would "eat" it.

---

> [!abstract] Algebra Takeaway
> When $x=1$, you are standing exactly on the "fence." The $\ge$ symbol tells you that the right-side piece (the line) "owns" that specific point. In your Obsidian vault, note that if the pieces didn't meet at the same $y$-value, you would have a **jump discontinuity**.

### Evaluating the Three-Piece Function: f(x) : $f(x) = \begin{cases} x^2, & x < 0 \\ 2, & x = 0 \\ 2x + 1, & x > 0 \end{cases}$

This function has three distinct rules: a parabola for negative values, a single point at the origin, and a line for positive values.

$$f(x) = \begin{cases} x^2, & x < 0 \\ 2, & x = 0 \\ 2x + 1, & x > 0 \end{cases}$$

---
#### 1. Evaluation Breakdown

| Input ($x$) | Constraint Check | Rule to Use | Calculation | Result |
| :--- | :--- | :--- | :--- | :--- |
| **$f(-2)$** | $-2 < 0$ | $x^2$ | $(-2)^2$ | **$4$** |
| **$f(0)$** | $0 = 0$  | $2$ (Constant) | (None) | **$2$** |
| **$f(2)$** | $2 > 0$  | $2x + 1$ | $2(2) + 1$ | **$5$** |

---
#### 2. What to Watch Out For

> [!important] The "Removable" Discontinuity (The Hole)
> As $x$ approaches $0$ from the left ($x^2$), the graph heads toward $y=0$. As it approaches from the right ($2x+1$), it heads toward $y=1$. However, the actual value at $x=0$ is defined as $2$. 
> * This creates a **double jump**: the graph "breaks" at the boundary and exists as a floating point at $(0, 2)$.

#### 3. Key Observations for Your Vault
1.  **The Constant Piece:** When a piece is just a number (like $x=0, y=2$), it appears on the graph as a single **isolated solid dot**.
2.  **Open Circles:** If you were graphing this, both the $x^2$ piece (at $x=0$) and the $2x+1$ piece (at $x=0$) would require **open circles** because their constraints ($<$ and $>$) do not include zero.
3.  **The Square of a Negative:** When calculating $f(-2)$, remember that $(-2)^2 = 4$. The negative sign is eliminated. If you were graphing this, the left side of your y-axis would show the left "arm" of a parabola.
---

> [!abstract] Algebra Takeaway
> This is a classic example of a **discontinuous function**. Because the three pieces do not "link up" at the same y-value at the boundary $x=0$, you would have to lift your pencil twice to draw this. In your Obsidian notes, label this as a "Jump" or "Point" discontinuity.

### Evaluating the Piecewise Function: f(x) $f(x) = \begin{cases} x + 3, & -4 \leq x < -2 \\ -2x - 3, & x \geq -2 \end{cases}$

This function consists of two linear pieces with a boundary "hand-off" occurring at $x = -2$.

$$f(x) = \begin{cases} x + 3, & -4 \leq x < -2 \\ -2x - 3, & x \geq -2 \end{cases}$$

---
#### 1. Evaluation Scenarios

| Input ($x$) | Constraint Check | Rule to Use | Calculation | Result |
| :--- | :--- | :--- | :--- | :--- |
| **$f(-4)$** | $-4 \leq -4$ (True) | $x + 3$ | $-4 + 3$ | **$-1$** |
| **$f(-3)$** | $-4 \leq -3 < -2$ | $x + 3$ | $-3 + 3$ | **$0$** |
| **$f(-2)$** | $-2 \geq -2$ (True) | $-2x - 3$ | $-2(-2) - 3$ | **$1$** |
| **$f(0)$** | $0 \geq -2$ (True) | $-2x - 3$ | $-2(0) - 3$ | **$-3$** |

---
#### 2. What to Watch Out For

> [!important] The "Endpoint" Behavior
> This function has a strict starting point at $x = -4$.
> * **The Start:** At $x = -4$, the graph has a **solid dot** because of the $\leq$ sign.
> * **The Gap:** At $x = -2$, the first piece ($x+3$) would end at $y=1$ if it could reach it, but it has a $<$ sign, creating an **open circle**. However, the second piece ($-2x-3$) actually starts at $y=1$ ($x=-2$ gives $1$).
> * **The Result:** Because the second piece "fills in" the hole left by the first piece, the graph is actually **continuous** at the boundary.

#### 3. Common Errors to Avoid
1.  **The "Out of Bounds" Error:** If you try to plug in $f(-5)$, the answer is **undefined**. The function does not exist to the left of $x = -4$.
2.  **Sign Errors with Negatives:** In the second piece, you are multiplying a negative by a negative ($-2 \cdot -2$). Watch out for the common mistake of getting $-4$ instead of $+4$.
3.  **Boundary Confusion:** It is tempting to use $x+3$ for $x=-2$ because it looks "simpler," but the mathematical instruction is clear: $x=-2$ belongs strictly to the second rule.

---

> [!abstract] Algebra Takeaway
> When two pieces meet at the same $y$-value (like they do here at $y=1$), the "open circle" from the first piece is covered by the "solid dot" of the second. This creates a **continuous** graph with a sharp turn (a "corner") at $x = -2$.

## 2026-March-16 - Graphs You Must Know (Precalculus - College Algebra 13) :
https://www.youtube.com/watch?v=NrmmR3-VxA8&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=15
### Library of Functions (Graphs You Must Know)

This "Library of Functions" is a set of basic graph shapes (Parent Functions) that you must memorize. Understanding these is the foundation for performing **Transformations** (shifts, stretches, and reflections) in the next topic.

---
#### 1. The Power of "Key Points"
Professor Leonard emphasizes that instead of plugging in dozens of numbers, you should memorize these **3 Key Points** for almost every basic function:
* **(1, 1):** Present in every function except the constant function.
* **(0, 0):** Present in every function except the Reciprocal function.
* **(-1, y):** If **Odd**, the point is **(-1, -1)**. If **Even**, the point is **(-1, 1)**.

---
#### 2. The Odd Functions (Origin Symmetry)
These functions can be rotated $180^\circ$ around the origin to land on themselves. They share the points **(0,0), (1,1), and (-1,-1)**.

* **Identity Function $f(x) = x$:** A straight diagonal line. It increases everywhere.
* **Cubing Function $f(x) = x^3$:** A "dynamic" curve that passes through the origin.
* **Cube Root Function $f(x) = \sqrt[3]{x}$:** The "S-shape" curve that is essentially a cubing function reflected on its side.
* **Reciprocal Function $f(x) = \frac{1}{x}$:**
    * **Asymptotes:** Has a Vertical Asymptote at $x=0$ and a Horizontal Asymptote at $y=0$.
    * **Key Points:** $(1, 1)$ and $(-1, -1)$. It **does not** have the point $(0,0)$.
    * **Behavior:** Always decreasing on its domain.

---
#### 3. The Even Functions (Y-Axis Symmetry)
These functions are mirror images across the y-axis. They share the points **(0,0), (1,1), and (-1, 1)**.

* **Constant Function $f(x) = b$:** A horizontal line. No matter what $x$ is, $y$ stays the same.
* **Squaring Function (Parabola) $f(x) = x^2$:** A U-shaped curve. Decreasing on $(-\infty, 0)$ and increasing on $(0, \infty)$.
* **Absolute Value Function $f(x) = |x|$:** A V-shaped graph. It takes the negative side of the identity function and reflects it up to be positive.

---
#### 4. The "Neither" Function
* **Square Root Function $f(x) = \sqrt{x}$:** * **Domain Restriction:** Only exists for $x \ge 0$. You cannot plug in negatives.
    * **Shape:** Half of a parabola on its side.
    * **Key Points:** $(0, 0)$ and $(1, 1)$. Because there is no graph on the left side, it cannot be even or odd.

---
### ⚠️ What to Look Out For

> [!important] Asymptote: The "MC Hammer" Line
> A vertical asymptote (found in $1/x$) is a line you **cannot touch**. The graph will get infinitely close to it but never cross it [00:09:12]. 

#### 1. Range vs. Domain
* **Odd Functions ($x, x^3, \sqrt[3]{x}$):** Generally have a domain and range of **all real numbers** $(-\infty, \infty)$.
* **Even Functions ($x^2, |x|$):** Often have a restricted range (e.g., $[0, \infty)$) because the outputs can never be negative.
#### 2. Why Memorize These?
In the next video, you will be asked to graph something like $f(x) = (x-3)^2 + 4$. If you know the "Key Points" of the parent function $x^2$, you can simply move those three points right 3 and up 4 to get the new graph instantly [00:18:52].

---

> [!abstract] Algebra Takeaway
> To master these:
> 1. Sketch the shape.
> 2. Plot the 3 key points.
> 3. Verify the symmetry (Even vs. Odd).
> 4. Check the "fences" (Domain/Asymptotes).

### The Library of Functions: Parent Graph Cheat Sheet

This "Library" contains the essential parent functions used throughout Precalculus and Calculus. Memorizing these shapes and their **Key Points** is the foundation for understanding transformations.

---

#### 1. Linear & Constant Functions
| Function | Formula | Symmetry | Key Points | Shape |
| :--- | :--- | :--- | :--- | :--- |
| **Identity** | $f(x) = x$ | **Odd** | $(-1,-1), (0,0), (1,1)$ | Straight $45^\circ$ diagonal line. |
| **Constant** | $f(x) = c$ | **Even** | $(0,c), (1,c), (2,c)$ | Horizontal line through $y=c$. |


---

#### 2. Power Functions ($x^2, x^3$)
| Function | Formula | Symmetry | Key Points | Shape |
| :--- | :--- | :--- | :--- | :--- |
| **Squaring** | $f(x) = x^2$ | **Even** | $(-1,1), (0,0), (1,1)$ | U-shaped **Parabola**. |
| **Cubing** | $f(x) = x^3$ | **Odd** | $(-1,-1), (0,0), (1,1)$ | S-shaped curve (origin-centered). |


---

#### 3. Root Functions ($\sqrt{x}, \sqrt[3]{x}$)
| Function | Formula | Symmetry | Key Points | Shape |
| :--- | :--- | :--- | :--- | :--- |
| **Square Root**| $f(x) = \sqrt{x}$ | **Neither**| $(0,0), (1,1), (4,2)$ | Starts at $(0,0)$, arcs to the right. |
| **Cube Root** | $f(x) = \sqrt[3]{x}$ | **Odd** | $(-1,-1), (0,0), (1,1)$ | S-shape on its side (reaches all quadrants).|


---

#### 4. Absolute Value & Reciprocal
| Function           | Formula              | Symmetry | Key Points       | Shape                                 |                        |                                            |
| :----------------- | :------------------- | :------- | :--------------- | :------------------------------------ | ---------------------- | ------------------------------------------ |
| **Absolute Value** | $f(x) =              | x        | $                | **Even**                              | $(-1,1), (0,0), (1,1)$ | V-shaped with a sharp "corner" at $(0,0)$. |
| **Reciprocal**     | $f(x) = \frac{1}{x}$ | **Odd**  | $(-1,-1), (1,1)$ | Two curves; Asymptotes at $x=0, y=0$. |                        |                                            |


---

### ⚠️ Critical Analysis Tips

> [!important] The Even/Odd Relationship
> * **Even Functions:** Mirror across the $y$-axis. If $(x, y)$ is a point, $(-x, y)$ is also a point.
> * **Odd Functions:** Rotate $180^\circ$ around the origin. If $(x, y)$ is a point, $(-x, -y)$ is also a point.

#### Domain Restrictions
Watch out for functions that "break" or "stop":
* **$f(x) = \frac{1}{x}$:** Domain is $(-\infty, 0) \cup (0, \infty)$. It is **undefined** at $x=0$.
* **$f(x) = \sqrt{x}$:** Domain is $[0, \infty)$. It does not exist for negative $x$-values.

---

> [!abstract] Algebra Takeaway
> When graphing transformations, always start with these **Key Points**. For example, if you see $f(x) = (x-2)^2 + 3$, you take the Squaring ($x^2$) key points and shift them 2 units right and 3 units up.

![[Pasted image 20260316143228.png]]

## 2026-March-17 - Introduction to Graph Transformations (Precalculus - College Algebra 14) :
https://www.youtube.com/watch?v=sTCRB6hMsC4&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=14
### Introduction to Graph Transformations

Graph transformations allow you to determine how a function's graph is affected based on operations applied to its "parent" function from the Library of Functions. Instead of plotting dozens of points, you transform the **3 Key Points** of the basic shape.

---
#### 1. Vertical Shifts (Affects the Output)
Vertical shifts happen **outside** the function's main operation (after the square, absolute value, or square root is finished).
* **Rule:** $f(x) + k$ (up $k$ units) or $f(x) - k$ (down $k$ units).
* **Mechanism:** You are taking the final $y$-value and adding/subtracting a constant. 
* **Visual Aid:** Imagine your $x$-axis physically sliding up or down while the $y$-axis stays put. [00:03:34]
#### 2. Horizontal Shifts (Affects the Input)
Horizontal shifts happen **inside** the function's operation (inside parentheses, absolute value bars, or square roots).
* **Rule:** $f(x + h)$ is a shift **LEFT**; $f(x - h)$ is a shift **RIGHT**.
* **Mechanism:** This is counter-intuitive! To get the same output height, you must provide a smaller or larger input to "undo" the constant.
* **Visual Aid:** Imagine the $y$-axis sliding left or right. [00:12:15]
#### 3. Vertical Stretches and Compressions
This occurs when you multiply the entire function by a constant $a$ ($y = a \cdot f(x)$). This affects the **output** values.
* **Vertical Stretch ($a > 1$):** The graph becomes taller and narrower. Points move farther from the $x$-axis. [00:31:02]
* **Vertical Compression ($0 < a < 1$):** The graph becomes shorter and wider. Points move closer to the $x$-axis. [00:32:41]
* **Method:** Multiply the $y$-coordinates of your Key Points by $a$. [00:33:44]
#### 4. Reflections
Reflections occur when you multiply by a negative sign.
* **Reflection about the X-axis (Vertical):** $y = -f(x)$. The negative is **outside**. All positive $y$-values become negative (flips upside down). [00:41:39]
* **Reflection about the Y-axis (Horizontal):** $y = f(-x)$. The negative is **inside**. All positive $x$-values become negative (flips left-to-right). [00:42:30]

---
### 🛠️ The "Leonard Method" for Graphing
Instead of a table of values, use this sequence for your Obsidian notes:

1.  **Identify Parent Function:** (e.g., $x^2, |x|, \sqrt{x}$).
2.  **List Key Points:** (e.g., $(-1, 1), (0,0), (1,1)$ for $x^2$).
3.  **Apply Stretches/Reflections:** Multiply the $y$-values of your Key Points by the constant/negative sign.
4.  **Create "New" Axes:** * Shift your vertical axis for horizontal shifts.
    * Shift your horizontal axis for vertical shifts.
5.  **Plot Points:** Plot your transformed Key Points relative to your new "fake" origin. [00:20:14]

---

> [!abstract] Algebra Takeaway
> **Inside = Horizontal & Opposite:** Anything inside the function ($x \pm h$) moves horizontally and behaves the opposite of what you'd expect ($+$ is Left, $-$ is Right).
> **Outside = Vertical & Normal:** Anything outside the function ($f(x) \pm k$) moves vertically and behaves exactly as you'd expect ($+$ is Up, $-$ is Down). [00:11:55]

### Graph Transformation: f(x) = x² + 3

To understand the transformation of $f(x) = x^2 + 3$, we compare it to its parent function in the Library of Functions.

---
#### 1. Identify the Parent Function
The base shape is the **Squaring Function**:
$$y = x^2$$
* **Shape:** A U-shaped parabola symmetric about the y-axis.
* **Key Points:** $(-1, 1)$, $(0, 0)$, and $(1, 1)$.
#### 2. Analyze the Change
The function has a constant ($+3$) added **outside** the main operation (the square).
* **Operation:** $f(x) = x^2 + 3$
* **Transformation Type:** **Vertical Shift**.
* **Direction:** **Up 3 units**.

#### 3. Transforming the Key Points
Because the change is "outside," we apply the transformation directly to the $y$-coordinates (outputs). We add 3 to every $y$-value of the parent points.

| Parent Point ($x^2$) | Calculation ($y + 3$) | Transformed Point |
| :--- | :--- | :--- |
| $(-1, 1)$ | $1 + 3 = 4$ | **$(-1, 4)$** |
| $(0, 0)$ | $0 + 3 = 3$ | **$(0, 3)$** |
| $(1, 1)$ | $1 + 3 = 4$ | **$(1, 4)$** |

---
### ⚠️ What to Look Out For

> [!important] The "Fake" Origin
> When graphing this manually, you can simply move your horizontal axis (the x-axis) down 3 units or move your starting point (the vertex) from $(0,0)$ up to $(0,3)$. All other points follow that same upward shift.

#### Vertical vs. Horizontal Confusion
If the $+3$ were **inside** the square—$f(x) = (x + 3)^2$—the transformation would be a **horizontal shift** to the left. Since it is outside, it is strictly a vertical movement.

---

> [!abstract] Algebra Takeaway
> Any addition or subtraction outside the parentheses/operation is a "vertical slide." 
> * $+k$ = Slide Up
> * $-k$ = Slide Down
### Graph Transformation: f(x) = |x + 2|

To understand the transformation of $f(x) = |x + 2|$, we compare it to its parent function in the Library of Functions.

---
#### 1. Identify the Parent Function
The base shape is the **Absolute Value Function**:
$$y = |x|$$
* **Shape:** A sharp V-shape with the vertex at the origin.
* **Key Points:** $(-1, 1)$, $(0, 0)$, and $(1, 1)$.
#### 2. Analyze the Change
The function has a constant ($+2$) added **inside** the absolute value bars (the main operation).
* **Operation:** $f(x) = |x + 2|$
* **Transformation Type:** **Horizontal Shift**.
* **Direction:** **Left 2 units**.

> [!warning] The "Inside-Opposite" Rule
> Remember that changes **inside** the operation (affecting the $x$ directly) behave the opposite of what you might expect. Even though it is $+2$, we shift in the **negative** direction (Left).

#### 3. Transforming the Key Points
Because the change is "inside," we apply the transformation to the $x$-coordinates. To "counteract" the $+2$, we subtract 2 from every $x$-value of the parent points. The $y$-values remain unchanged.

| Parent Point ($|x|$) | Calculation ($x - 2$) | Transformed Point |
| :--- | :--- | :--- |
| $(-1, 1)$ | $-1 - 2 = -3$ | **$(-3, 1)$** |
| $(0, 0)$ | $0 - 2 = -2$ | **$(-2, 0)$** |
| $(1, 1)$ | $1 - 2 = -1$ | **$(-1, 1)$** |

---
### ⚠️ What to Look Out For

#### 1. The Vertex Location
The vertex of the parent function is always at $(0,0)$. For this transformed function, the vertex has moved to **$(-2, 0)$**. You can verify this by checking what value of $x$ makes the inside of the bars equal zero: $x + 2 = 0 \implies x = -2$.

#### 2. Inside vs. Outside
* **$f(x) = |x + 2|$**: The $+2$ is inside. This is a **horizontal** shift (Left 2).
* **$f(x) = |x| + 2$**: The $+2$ is outside. This would be a **vertical** shift (Up 2).

---

> [!abstract] Algebra Takeaway
> When you see a modification inside the function's "core" (parentheses, bars, or roots), think **horizontal and opposite**. To graph it, simply slide your parent V-shape 2 units to the left on the x-axis.
### Graph Transformation: f(x) = (x + 1)³ - 1

This function involves two separate shifts (horizontal and vertical) applied to a power function.

---
#### 1. Identify the Parent Function
The base shape is the **Cubing Function**:
$$y = x^3$$
* **Shape:** An "S-curve" that passes through the origin.
* **Key Points:** $(-1, -1)$, $(0, 0)$, and $(1, 1)$.
#### 2. Analyze the Changes
We look at the "Inside" of the operation (inside the parentheses) and the "Outside" (after the cube).

* **Inside ($x + 1$):** This is a **Horizontal Shift**. Because it is $+1$, we follow the "Inside-Opposite" rule and move **Left 1 unit**.
* **Outside ($- 1$):** This is a **Vertical Shift**. Because it is $-1$, we follow the "Outside-Normal" rule and move **Down 1 unit**.

#### 3. Transforming the Key Points
To get the new points, we subtract 1 from every $x$-coordinate and subtract 1 from every $y$-coordinate.

| Parent Point ($x^3$) | x-calc ($x - 1$) | y-calc ($y - 1$) | Transformed Point |
| :--- | :--- | :--- | :--- |
| $(-1, -1)$ | $-1 - 1 = -2$ | $-1 - 1 = -2$ | **$(-2, -2)$** |
| $(0, 0)$ | $0 - 1 = -1$ | $0 - 1 = -1$ | **$(-1, -1)$** |
| $(1, 1)$ | $1 - 1 = 0$ | $1 - 1 = 0$ | **$(0, 0)$** |

---
### ⚠️ What to Look Out For

#### 1. The "New Origin" (Inflection Point)
In the parent function, the graph "flattens" at $(0,0)$. After the transformations, this central point (the point of inflection) is now located at **$(-1, -1)$**.

#### 2. Order of Operations
When only dealing with shifts (additions/subtractions), the order doesn't technically change the final result. however, it is best practice to:
1.  Perform Horizontal shifts.
2.  Perform Vertical shifts.

#### 3. Checking Your Intercepts
A quick way to verify your graph is to find the $y$-intercept. Plug in $x=0$:
$f(0) = (0 + 1)^3 - 1$
$f(0) = 1^3 - 1 = 0$
The graph should pass through the origin $(0,0)$, which matches our third transformed point.

---

> [!abstract] Algebra Takeaway
> When multiple shifts are present, move the "anchor point" (the origin for $x^3$) first. For $(x+1)^3 - 1$, move the origin **Left 1** and **Down 1**, then draw the standard S-curve shape starting from that new center.
### Graph Transformation: g(x) = √(x - 2) + 3

This function applies a horizontal and vertical shift to the square root "parent" shape.

---
#### 1. Identify the Parent Function
The base shape is the **Square Root Function**:
$$f(x) = \sqrt{x}$$
* **Shape:** A "starting arc" that begins at the origin and curves slowly into the first quadrant.
* **Key Points:** $(0, 0)$, $(1, 1)$, and $(4, 2)$.
#### 2. Analyze the Changes
We examine the operations "Inside" the radical and "Outside" the radical.

* **Inside ($x - 2$):** This is a **Horizontal Shift**. Because it is $-2$, we follow the "Inside-Opposite" rule and move **Right 2 units**.
* **Outside ($+ 3$):** This is a **Vertical Shift**. Because it is $+3$, we follow the "Outside-Normal" rule and move **Up 3 units**.
#### 3. Transforming the Key Points
To find the new coordinates, we add 2 to every $x$-value and add 3 to every $y$-value of the parent points.

| Parent Point ($\sqrt{x}$) | x-calc ($x + 2$) | y-calc ($y + 3$) | Transformed Point |
| :--- | :--- | :--- | :--- |
| $(0, 0)$ | $0 + 2 = 2$ | $0 + 3 = 3$ | **$(2, 3)$** |
| $(1, 1)$ | $1 + 2 = 3$ | $1 + 3 = 4$ | **$(3, 4)$** |
| $(4, 2)$ | $4 + 2 = 6$ | $2 + 3 = 5$ | **$(6, 5)$** |

---
### ⚠️ What to Look Out For

#### 1. The Starting Point (The "Vertex")
The most important point for a square root function is its starting point. In the parent function, this is $(0, 0)$. In $g(x)$, the graph **begins at (2, 3)**. There is no graph to the left of $x = 2$.

#### 2. Domain and Range
Transformations directly affect the domain and range:
* **Domain:** Originally $x \ge 0$. After the horizontal shift right 2, the new domain is **$[2, \infty)$**.
* **Range:** Originally $y \ge 0$. After the vertical shift up 3, the new range is **$[3, \infty)$**.

#### 3. Inside vs. Outside
Always distinguish between what is under the square root bar and what is outside of it. If the function were $g(x) = \sqrt{x - 2 + 3}$, that would simplify to $\sqrt{x + 1}$, which is a completely different transformation (Left 1 unit).

---

> [!abstract] Algebra Takeaway
> To graph $g(x) = \sqrt{x-2} + 3$, locate your new starting point at **$(2, 3)$** and then draw the standard "arc" shape of a square root function from that position.
### Graph Transformation: f(x) = 2x²

This function involves a vertical change to the squaring parent function, affecting how "steeply" the graph climbs.

---
#### 1. Identify the Parent Function
The base shape is the **Squaring Function**:
$$y = x^2$$
* **Shape:** A standard U-shaped parabola.
* **Key Points:** $(-1, 1)$, $(0, 0)$, and $(1, 1)$.
#### 2. Analyze the Change
The function is being multiplied by a constant ($2$) **outside** the squaring operation.
* **Operation:** $f(x) = 2x^2$
* **Transformation Type:** **Vertical Stretch**.
* **Factor:** **2**.
#### 3. Transforming the Key Points
Because the multiplier is on the "outside," it only affects the $y$-coordinates (outputs). You multiply every parent $y$-value by 2. The $x$-values remain exactly the same.

| Parent Point ($x^2$) | Calculation ($y \cdot 2$) | Transformed Point |
| :--- | :--- | :--- |
| $(-1, 1)$ | $1 \cdot 2 = 2$ | **$(-1, 2)$** |
| $(0, 0)$ | $0 \cdot 2 = 0$ | **$(0, 0)$** |
| $(1, 1)$ | $1 \cdot 2 = 2$ | **$(1, 2)$** |

---
### ⚠️ What to Look Out For

#### 1. Vertical Stretch vs. Compression
* **Stretch ($a > 1$):** Like $2x^2$, the graph looks "skinnier" or "narrower" because the $y$-values are growing twice as fast.
* **Compression ($0 < a < 1$):** Like $\frac{1}{2}x^2$, the graph would look "wider" or "flatter" because the $y$-values are only half as tall as the original.
#### 2. The "Fixed" Point
Notice that the vertex $(0, 0)$ did not move. In a pure vertical stretch or compression, any point on the x-axis (where $y=0$) stays exactly where it is because $0 \cdot a = 0$.
#### 3. Horizontal vs. Vertical Confusion
If the 2 were **inside** the square—$f(x) = (2x)^2$—that would be a **Horizontal Compression**. While the resulting graph looks similar to a vertical stretch, the mathematical logic (and the points you plot) would be different.

---

> [!abstract] Algebra Takeaway
> A vertical stretch pulls the graph away from the x-axis. To graph it quickly, keep your vertex at $(0,0)$ and move your other key points twice as high as they used to be.
### Graph Transformation: f(x) = 1/2x³

This transformation involves a vertical modification to the cubing parent function, which "flattens" the curve as it moves away from the origin.

---
#### 1. Identify the Parent Function
The base shape is the **Cubing Function**:
$$y = x^3$$
* **Shape:** The standard S-curve (origin-symmetric).
* **Key Points:** $(-1, -1)$, $(0, 0)$, and $(1, 1)$.
#### 2. Analyze the Change
The function is being multiplied by a constant ($\frac{1}{2}$) **outside** the cubing operation.
* **Operation:** $f(x) = \frac{1}{2}x^3$
* **Transformation Type:** **Vertical Compression** (also called a Vertical Shrink).
* **Factor:** **1/2**.
#### 3. Transforming the Key Points
Because the multiplier is on the "outside," it only affects the $y$-coordinates. You multiply every parent $y$-value by $\frac{1}{2}$. The $x$-values remain exactly the same.

| Parent Point ($x^3$) | Calculation ($y \cdot \frac{1}{2}$) | Transformed Point |
| :--- | :--- | :--- |
| $(-1, -1)$ | $-1 \cdot \frac{1}{2} = -0.5$ | **$(-1, -0.5)$** |
| $(0, 0)$ | $0 \cdot \frac{1}{2} = 0$ | **$(0, 0)$** |
| $(1, 1)$ | $1 \cdot \frac{1}{2} = 0.5$ | **$(1, 0.5)$** |

---

### ⚠️ What to Look Out For

#### 1. "Wider" vs. "Shorter" Appearance
In your Obsidian notes, remember that a vertical compression makes the graph look "wider" or "fatter" because the $y$-values are not rising as quickly as the original. Mathematically, the points are being "pushed" toward the x-axis.
#### 2. The Invariant Point
Notice that $(0,0)$ stays at $(0,0)$. Any point where $y=0$ is an **invariant point** under vertical stretching or compression because multiplying zero by any factor still results in zero.
#### 3. Vertical vs. Horizontal Compression
* **Vertical Compression ($y = \frac{1}{2}x^3$):** The output is halved.
* **Horizontal Stretch ($y = (\frac{1}{2}x)^3$):** The input is halved *inside* the cube. While the visual result is a wider graph, the key points would be calculated differently (multiplying $x$ by 2).

---

> [!abstract] Algebra Takeaway
> A vertical compression (where $0 < a < 1$) makes the graph "lazy." It takes longer for the S-curve to climb or descend. To graph it, keep your center at $(0,0)$ and plot your next points only half as high/low as the parent points.
### Graph Transformation: f(x) = (3x)²

This function applies a modification **inside** the squaring operation, which affects the horizontal "speed" of the graph.

---
#### 1. Identify the Parent Function
The base shape is the **Squaring Function**:
$$y = x^2$$
* **Shape:** A standard U-shaped parabola.
* **Key Points:** $(-1, 1)$, $(0, 0)$, and $(1, 1)$.
#### 2. Analyze the Change
The constant ($3$) is multiplying the $x$ **inside** the parentheses before the squaring happens.
* **Operation:** $f(x) = (3x)^2$
* **Transformation Type:** **Horizontal Compression** (also called a Horizontal Shrink).
* **Factor:** **1/3**.

> [!warning] The "Inside-Opposite" Rule
> Just like horizontal shifts, horizontal stretches and compressions are counter-intuitive. Multiplying by 3 **inside** doesn't make the graph 3 times wider; it makes it **3 times narrower** ($1/3$ the original width).
#### 3. Transforming the Key Points
Because the change is "inside," it only affects the $x$-coordinates. To "counteract" the 3, you must divide every parent $x$-value by 3 (or multiply by $1/3$). The $y$-values remain exactly the same.

| Parent Point ($x^2$) | Calculation ($x \cdot \frac{1}{3}$) | Transformed Point |
| :------------------- | :---------------------------------- | :---------------- |
| $(-1, 1)$            | $-1 \cdot \frac{1}{3} = -1/3$       | **$(-1/3, 1)$**   |
| $(0, 0)$             | $0 \cdot \frac{1}{3} = 0$           | **$(0, 0)$**      |
| $(1, 1)$             | $1 \cdot \frac{1}{3} = 1/3$         | **$(1/3, 1)$**    |

---
### ⚠️ What to Look Out For

#### 1. Visual Similarity to Vertical Stretch
In your Obsidian notes, observe that $f(x) = (3x)^2$ is mathematically identical to $f(x) = 9x^2$. 
* A **Horizontal Compression** by $1/3$ looks exactly like a **Vertical Stretch** by $9$. 
* While the visual result is the same "skinny" parabola, the *description* of the transformation depends entirely on whether the number is inside or outside the operation.
#### 2. The Invariant Point
The vertex $(0,0)$ remains unchanged because $0 \div 3 = 0$. Horizontal transformations "pull" or "push" the graph toward or away from the **y-axis**.
#### 3. Horizontal Stretch vs. Compression
* **Compression ($a > 1$):** Like $(3x)^2$, the graph is squeezed toward the y-axis.
* **Stretch ($0 < a < 1$):** Like $(\frac{1}{3}x)^2$, the graph would be pulled away from the y-axis, making it look much wider.
---
> [!abstract] Algebra Takeaway
> To graph a horizontal compression, keep your $y$-values the same but move your points closer to the center (the y-axis). For $(3x)^2$, your points are now only $1/3$ as far from the center as the parent points were.
### Graph Transformation: f(x) = -∛x

This transformation involves a vertical modification that flips the "S-curve" of the cube root function across the horizontal axis.

---
#### 1. Identify the Parent Function
The base shape is the **Cube Root Function**:
$$y = \sqrt[3]{x}$$
* **Shape:** An "S-shaped" curve that exists in all quadrants and passes through the origin.
* **Key Points:** $(-1, -1)$, $(0, 0)$, and $(1, 1)$.
#### 2. Analyze the Change
The function is being multiplied by a negative sign ($-1$) **outside** the radical.
* **Operation:** $f(x) = -\sqrt[3]{x}$
* **Transformation Type:** **Reflection about the x-axis** (Vertical Reflection).
* **Mechanism:** Every positive $y$-value becomes negative, and every negative $y$-value becomes positive.

#### 3. Transforming the Key Points
Because the negative sign is on the "outside," it only affects the $y$-coordinates. You multiply every parent $y$-value by $-1$. The $x$-values remain exactly the same.

| Parent Point ($\sqrt[3]{x}$) | Calculation ($y \cdot -1$) | Transformed Point |
| :--- | :--- | :--- |
| $(-1, -1)$ | $-1 \cdot -1 = 1$ | **$(-1, 1)$** |
| $(0, 0)$ | $0 \cdot -1 = 0$ | **$(0, 0)$** |
| $(1, 1)$ | $1 \cdot -1 = -1$ | **$(1, -1)$** |

---
### ⚠️ What to Look Out For

#### 1. Reflection vs. Rotation
In your Obsidian notes, observe that for the cube root function, a **reflection about the x-axis** looks identical to a **reflection about the y-axis** ($f(x) = \sqrt[3]{-x}$). This is because the cube root is an **Odd Function**. Rotating it $180^\circ$ or flipping it either way results in the same visual path.

#### 2. The Invariant Point
The origin $(0, 0)$ is on the axis of reflection, so it does not move. The graph still passes through $(0,0)$, but its "direction" is reversed. Instead of going from bottom-left to top-right, it now goes from **top-left to bottom-right**.

#### 3. Inside vs. Outside Negatives
* **$f(x) = -\sqrt[3]{x}$**: Reflection across the **x-axis** (Up/Down flip).
* **$f(x) = \sqrt[3]{-x}$**: Reflection across the **y-axis** (Left/Right flip).

---

> [!abstract] Algebra Takeaway
> A negative sign outside the function is a "vertical flip." To graph $f(x) = -\sqrt[3]{x}$, take your standard S-curve and swap the "up" part with the "down" part. The points $(1,1)$ and $(-1,-1)$ simply trade their vertical positions.
### Graph Transformation: f(x) = √(-x)

This transformation involves a horizontal modification that flips the square root "parent" shape across the vertical axis.

---
#### 1. Identify the Parent Function
The base shape is the **Square Root Function**:
$$y = \sqrt{x}$$
* **Shape:** A "starting arc" that begins at the origin and curves into the first quadrant.
* **Key Points:** $(0, 0)$, $(1, 1)$, and $(4, 2)$.
#### 2. Analyze the Change
The negative sign is located **inside** the radical, directly affecting the $x$ input.
* **Operation:** $f(x) = \sqrt{-x}$
* **Transformation Type:** **Reflection about the y-axis** (Horizontal Reflection).
* **Mechanism:** Every positive $x$-value becomes negative. To keep the value under the radical non-negative, you must now plug in negative numbers.

#### 3. Transforming the Key Points
Because the negative sign is on the "inside," it only affects the $x$-coordinates. You multiply every parent $x$-value by $-1$. The $y$-values remain exactly the same.

| Parent Point ($\sqrt{x}$) | Calculation ($x \cdot -1$) | Transformed Point |
| :--- | :--- | :--- |
| $(0, 0)$ | $0 \cdot -1 = 0$ | **$(0, 0)$** |
| $(1, 1)$ | $1 \cdot -1 = -1$ | **$(-1, 1)$** |
| $(4, 2)$ | $4 \cdot -1 = -4$ | **$(-4, 2)$** |

---
### ⚠️ What to Look Out For

#### 1. Domain Flip
The domain of the parent function is $[0, \infty)$. After the reflection, the new domain is **$(-\infty, 0]$**. 
* **Logic:** If you plug in $x = -4$, the function becomes $\sqrt{-(-4)}$, which is $\sqrt{4} = 2$. This is why the graph now exists only on the left side of the y-axis.
#### 2. The "Anchor" Point
The starting point $(0, 0)$ sits exactly on the y-axis (the axis of reflection), so it does not move. The graph still "launches" from the origin, but it now heads toward the **top-left** instead of the top-right.
#### 3. Inside vs. Outside Negatives
* **$f(x) = \sqrt{-x}$**: Reflection across the **y-axis** (Left/Right flip).
* **$f(x) = -\sqrt{x}$**: Reflection across the **x-axis** (Up/Down flip).

---

> [!abstract] Algebra Takeaway
> A negative sign inside the function is a "horizontal flip." To graph $f(x) = \sqrt{-x}$, take your standard square root "arc" and draw it as a mirror image on the left side of the coordinate plane.
## 2026-March-18 - How to Graph with Transformations (Precalculus - College Algebra 15) :
https://www.youtube.com/watch?v=HkrMJLSpJFI&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=17
### Advanced Graphing with Transformations

This lesson focuses on a "Unified Method" for graphing complex functions. Instead of plotting random points, you transform the **"Key Points"** of a parent function and use a **"New Origin"** to anchor the sketch.

---
#### 1. The 4-Step Leonard Method
To graph any complex function like $f(x) = a \cdot \text{parent}(x - h) + k$:

1.  **Identify the Parent:** Determine the shape (V for absolute value, S for cubic, arc for square root).
2.  **List Key Points:** Start with the standard points (usually $(0,0), (1,1), (-1, y)$).
3.  **Identify Transformations:** * **Outside (+/-):** Vertical Shift (Up/Down).
    * **Inside (+/-):** Horizontal Shift (Left/Right - *Opposite of sign*).
    * **Outside Multiplier ($a$):** Vertical Stretch/Compression + X-axis reflection if negative.
    * **Inside Multiplier:** Horizontal Stretch/Compression + Y-axis reflection if negative.
4.  **The "New Origin" Sketch:** Move your axes to the new $(h, k)$ position and plot your transformed key points relative to that intersection [00:05:34].
---
#### 2. Handling the "Inside" (Horizontal Refinements)
Professor Leonard emphasizes that for horizontal transformations to be clear, the **$x$ must be positive and listed first** inside the function [00:18:20].

* **Factoring for Clarity:** If you have $\sqrt{1-x}$, rewrite it by factoring out the negative: $\sqrt{-(x-1)}$.
    * This reveals the graph is shifted **Right 1**, then reflected across the **Y-axis** [00:26:20].
* **Reciprocal Functions:** For $f(x) = \frac{3}{x-2} + 1$, rewrite it as $3 \cdot (\frac{1}{x-2}) + 1$ to clearly see the parent is $1/x$, stretched vertically by 3 [00:19:08].
---
#### 3. Summary of Transformation Effects

| Transformation | Location | Effect on Points | Visual Result |
| :--- | :--- | :--- | :--- |
| **Vertical Shift** | Outside ($+k$) | Add $k$ to $y$ | Slides graph Up/Down [00:01:46] |
| **Horizontal Shift**| Inside ($-h$) | Add $h$ to $x$ | Slides graph Left/Right (*Opposite*) [00:02:13] |
| **Vertical Stretch** | Outside ($a > 1$) | Multiply $y$ by $a$ | Graph gets "tall/skinny" [00:22:20] |
| **Vertical Compression**| Outside ($a < 1$) | Multiply $y$ by $a$ | Graph gets "short/wide" [00:03:18] |
| **X-axis Reflection**| Outside ($-$) | Multiply $y$ by $-1$ | Flips graph upside down [00:03:48] |
| **Y-axis Reflection**| Inside ($-$) | Multiply $x$ by $-1$ | Flips graph left-to-right [00:28:25] |

---
#### 4. Improving Accuracy
After sketching the transformed key points, use these two "Quality Control" steps:
* **Find the Y-Intercept:** Plug in $x=0$ to the original equation. This provides a concrete anchor point to check your sketch [00:08:16].
* **Use Symmetry:** If the parent is even (like $x^2$ or $|x|$), the transformed graph will still have an **Axis of Symmetry** running through the new vertex [00:09:17].
---

> [!abstract] Algebra Takeaway
> Never graph by "random plugging." Identify the parent shape, find the new "origin" $(h, k)$, and adjust the height of your key points based on the multiplier $a$. This method works for everything from basic parabolas to complex trigonometric waves [00:30:21].

### Graph Transformation: f(x) = -1/2 |x - 3| + 2

This function applies four distinct transformations to the absolute value parent function. To graph this accurately, follow the "Leonard Method" of transforming key points.

---
#### 1. Identify the Parent Function
The base shape is the **Absolute Value Function**:
$$y = |x|$$
* **Shape:** A V-shape symmetric about the y-axis.
* **Key Points:** $(-1, 1)$, $(0, 0)$, and $(1, 1)$.
#### 2. Analyze the Transformations
Break the function down from the "inside" out:

1.  **Horizontal Shift (Inside: $x - 3$):** Moves the graph **Right 3 units** (Opposite of the sign).
2.  **Vertical Compression (Outside: $1/2$):** Multiplies $y$-values by $1/2$, making the V-shape **wider/flatter**.
3.  **Reflection (Outside: negative sign):** Reflects the graph across the **x-axis**, flipping the V-shape **upside down**.
4.  **Vertical Shift (Outside: $+ 2$):** Moves the entire flipped graph **Up 2 units**.
#### 3. Transforming the Key Points
Apply the horizontal change ($x + 3$) and then the vertical changes (multiply $y$ by $-1/2$, then add $2$).

| Parent Point ($|x|$) | x-calc ($x + 3$) | y-calc ($-\frac{1}{2}y + 2$) | Transformed Point |
| :--- | :--- | :--- | :--- |
| $(-1, 1)$ | $-1 + 3 = 2$ | $-\frac{1}{2}(1) + 2 = 1.5$ | **$(2, 1.5)$** |
| $(0, 0)$ | $0 + 3 = 3$ | $-\frac{1}{2}(0) + 2 = 2$ | **$(3, 2)$** |
| $(1, 1)$ | $1 + 3 = 4$ | $-\frac{1}{2}(1) + 2 = 1.5$ | **$(4, 1.5)$** |

---
### ⚠️ What to Look Out For

#### 1. The New Vertex
The "tip" of the V-shape (the vertex) has moved from $(0,0)$ to **$(3, 2)$**. This point $(h, k)$ is your "new origin" for sketching.
#### 2. Direction of Opening
Because of the negative sign outside the absolute value bars, the graph opens **downward**. 
#### 3. Slope and "Width"
The $1/2$ acts like a slope for the two lines forming the V. Starting from the vertex $(3, 2)$, the lines go "down 1 unit for every 2 units across" ($m = \pm 1/2$). This makes the graph appear much wider than the parent function.
#### 4. The Y-Intercept (Check)
Plug in $x=0$ to verify your sketch:
$f(0) = -1/2 |0 - 3| + 2$
$f(0) = -1/2 (3) + 2 = -1.5 + 2 = 0.5$
Your graph should cross the y-axis at **$(0, 0.5)$**.

---

> [!abstract] Algebra Takeaway
> To graph $f(x) = -1/2 |x-3| + 2$, start at the vertex **$(3, 2)$**. Because of the $-1/2$, move right 1 and down 0.5 to plot your next point, then use symmetry to plot the left side. The resulting shape is a wide, upside-down "V".

### Graph Transformation: f(x) = 3 / (x - 2) + 1

This function applies three transformations to the reciprocal parent function, which is the most complex shape in the basic library due to its "split" nature and asymptotes.

---
#### 1. Identify the Parent Function
The base shape is the **Reciprocal Function**:
$$y = \frac{1}{x}$$
* **Shape:** A hyperbola with two separate branches in Quadrants I and III.
* **Key Points:** $(1, 1)$ and $(-1, -1)$.
* **Asymptotes:** Vertical at $x = 0$; Horizontal at $y = 0$.
#### 2. Analyze the Transformations
To see the transformations clearly, rewrite the function as:  
$$f(x) = 3 \cdot \left( \frac{1}{x - 2} \right) + 1$$

1.  **Horizontal Shift (Inside: $x - 2$):** Moves the graph **Right 2 units**. This moves the Vertical Asymptote.
2.  **Vertical Stretch (Outside: $3$):** Multiplies $y$-values by 3, pulling the curves farther from the center.
3.  **Vertical Shift (Outside: $+ 1$):** Moves the entire graph **Up 1 unit**. This moves the Horizontal Asymptote.
#### 3. Transforming the Asymptotes (The "Frame")
Before plotting points, move the "invisible fences" that guide the graph:
* **New Vertical Asymptote (VA):** $x = 2$ (Shifted right 2).
* **New Horizontal Asymptote (HA):** $y = 1$ (Shifted up 1).

The intersection of these two lines **$(2, 1)$** acts as your "new origin."
#### 4. Transforming the Key Points
Apply the horizontal change ($x + 2$) and then the vertical changes (multiply $y$ by $3$, then add $1$).

| Parent Point ($1/x$) | x-calc ($x + 2$) | y-calc ($3y + 1$) | Transformed Point |
| :--- | :--- | :--- | :--- |
| $(1, 1)$ | $1 + 2 = 3$ | $3(1) + 1 = 4$ | **$(3, 4)$** |
| $(-1, -1)$ | $-1 + 2 = 1$ | $3(-1) + 1 = -2$ | **$(1, -2)$** |

---
### ⚠️ What to Look Out For

#### 1. The "Steepness"
Because of the vertical stretch of 3, the curves will look much "sharper" or farther away from the intersection of the asymptotes compared to the parent function.
#### 2. The Y-Intercept (Check)
Plug in $x = 0$ to verify where the left branch crosses the axis:
$f(0) = \frac{3}{0 - 2} + 1 = -1.5 + 1 = -0.5$
Your graph should cross the y-axis at **$(0, -0.5)$**.
#### 3. Domain and Range
* **Domain:** All real numbers except $x = 2$.
* **Range:** All real numbers except $y = 1$.
---

> [!abstract] Algebra Takeaway
> When graphing $f(x) = \frac{3}{x-2} + 1$, draw your dashed asymptote lines at $x=2$ and $y=1$ first. Then, treat their intersection as $(0,0)$ and plot your stretched points $(1,3)$ and $(-1,-3)$ relative to that spot.

### Graph Transformation: g(x) = 2√(1 - x) + 3

This function is a "trick" question common in Precalculus. Before identifying transformations, you **must** factor the inside so the $x$ is positive and has a coefficient of $1$.

**Standard Form Rewrite:**
$$g(x) = 2\sqrt{-(x - 1)} + 3$$

---
#### 1. Identify the Parent Function
The base shape is the **Square Root Function**:
$$f(x) = \sqrt{x}$$
* **Shape:** A "starting arc" beginning at the origin.
* **Key Points:** $(0, 0), (1, 1), (4, 2)$.
#### 2. Analyze the Transformations (In Order)
Using the rewritten form $g(x) = 2\sqrt{-(x - 1)} + 3$:

1.  **Horizontal Shift (Inside: $x - 1$):** Moves the graph **Right 1 unit**.
2.  **Horizontal Reflection (Inside: negative sign):** Reflects the graph across the **y-axis**. Because the shift happened first, it now "faces" left.
3.  **Vertical Stretch (Outside: $2$):** Multiplies $y$-values by 2, making the arc **taller**.
4.  **Vertical Shift (Outside: $+ 3$):** Moves the entire graph **Up 3 units**.
#### 3. Transforming the Key Points
Apply horizontal changes (multiply $x$ by $-1$, then add $1$) and vertical changes (multiply $y$ by $2$, then add $3$).

| Parent Point ($\sqrt{x}$) | x-calc ($-x + 1$) | y-calc ($2y + 3$) | Transformed Point |
| :--- | :--- | :--- | :--- |
| **$(0, 0)$** | $0 + 1 = 1$ | $2(0) + 3 = 3$ | **$(1, 3)$** |
| **$(1, 1)$** | $-1 + 1 = 0$ | $2(1) + 3 = 5$ | **$(0, 5)$** |
| **$(4, 2)$** | $-4 + 1 = -3$ | $2(2) + 3 = 7$ | **$(-3, 7)$** |

---

### ⚠️ What to Look Out For

#### 1. The "Starting Point"
The origin $(0,0)$ has moved to **$(1, 3)$**. Because of the horizontal reflection, the graph starts at $x=1$ and grows toward the **left** (negative x-direction).

#### 2. The Factoring Trap
If you don't factor $\sqrt{1-x}$ into $\sqrt{-(x-1)}$, you might mistakenly think the graph shifts *left* 1 unit. Always ensure the $x$ inside the parentheses has a coefficient of $+1$ before naming the shift.

#### 3. Domain and Range
* **Domain:** $(-\infty, 1]$. The $x$-values must be less than or equal to 1 to keep the inside of the radical positive.
* **Range:** $[3, \infty)$. The $y$-values start at 3 and go up.

#### 4. The Y-Intercept (Check)
$g(0) = 2\sqrt{1-0} + 3 = 2(1) + 3 = 5$.
This matches our transformed key point **$(0, 5)$**.

---

> [!abstract] Algebra Takeaway
> When you see a negative $x$ inside a radical or parentheses, **factor it out** first. For $g(x) = 2\sqrt{-(x - 1)} + 3$, locate your starting point at **$(1, 3)$** and draw your "tall" square root arc heading toward the **top-left**.

##  2026-March-18 - Introduction to Solving Quadratics (Precalculus - College Algebra 16) :
https://www.youtube.com/watch?v=OIEkJaPgjKs&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=16
### Introduction to Solving Quadratics

Solving a quadratic equation is fundamentally about finding **where the function hits the ground**. In mathematical terms, you are finding the **x-intercepts**, **roots**, or **zeros** of a parabola [00:02:05].

---
#### 1. What are we actually finding?
A quadratic function is a polynomial of degree 2 (highest power is $x^2$):
$$f(x) = ax^2 + bx + c$$
When we "solve" this, we replace $f(x)$ with **0**.
* **The Logic:** $f(x)$ represents the height. By setting it to 0, we are asking: "At what x-values is the height exactly zero?" [00:01:41].
* **The Goal:** Those x-values are the points where the parabola crosses or touches the x-axis [00:02:19].
---
#### 2. The Three Possible Outcomes
Because quadratics create parabolas, there are only three ways the graph can interact with the x-axis [00:05:12]:

| Outcome | Visual Behavior | Solution Type |
| :--- | :--- | :--- |
| **Two X-Intercepts** | The parabola crosses the axis twice. | **2 Real Solutions** (No $i$ or imaginary parts) [00:06:04]. |
| **One X-Intercept** | The vertex "bounces" or touches the axis. | **1 Real Solution** (Often called a "Double Root") [00:07:02]. |
| **No X-Intercepts** | The parabola is entirely above or below the axis. | **2 Complex Solutions** (Contains $i$ / imaginary units) [00:09:14]. |

---
#### 3. The Four Solving Methods
Professor Leonard introduces four main techniques for finding these zeros. Some are faster for specific problems, while others work for every single quadratic [00:03:09]:

1.  **Square Root Method:** Best when you can isolate the $x^2$ term (e.g., $x^2 = 9$) or a perfect square block [00:03:16].
2.  **Factoring:** Uses the Zero Product Property. If $(x-r_1)(x-r_2) = 0$, then $x$ must be $r_1$ or $r_2$ [00:03:29].
3.  **Completing the Square:** A reliable but more involved method that forces the equation into a perfect square format [00:03:41].
4.  **Quadratic Formula:** The "Universal Tool" that works on any quadratic, even those with complex or messy roots [00:03:52].
    * Formula: $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$

---
### ⚠️ Common Pitfalls

> [!important] Complex Solutions $\neq$ "No Solution"
> If you solve an equation and get an imaginary number (like $2 \pm 3i$), the equation **has** solutions, but the graph has **no x-intercepts**. It means the parabola is "missing" the axis entirely [00:10:03].

#### Terminology Confusion
In your Obsidian notes, remember that these four terms are often used interchangeably in textbooks [00:02:05]:
* **Zeros**
* **Roots**
* **X-intercepts**
* **Solutions**
---

> [!abstract] Algebra Takeaway
> To solve a quadratic, you are simply finding the horizontal locations where the height of the parabola is zero. Whether you factor or use the formula, you are identifying the "footprints" of the graph on the x-axis [00:11:05].

## 2026-March-19 - The Square Root Method in Solving Quadratics (Precalculus - College Algebra 17) :
https://www.youtube.com/watch?v=mXAd6rkNSK0&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=18
### The Square Root Method (Solving Quadratics)

The Square Root Method is the first and often easiest technique to check for when solving a quadratic equation. It is used to find the **x-intercepts**, **roots**, or **zeros** of a parabola [00:00:55].

---
#### 1. When to Use This Method
You can use the Square Root Method **if and only if** you can isolate a perfect square (either $x^2$ or a squared binomial) on one side of the equation with a constant on the other [00:03:11].
* **Look for:** $ax^2 = c$ or $(x + h)^2 = k$.
* **Avoid if:** There is a "middle" $x$ term (like $3x^2 + 5x - 2 = 0$) that cannot be easily wrapped into a parenthesis [00:03:18].
---
#### 2. The Golden Rule: $\pm$ (Plus or Minus)
The most critical step—and the most common mistake—is forgetting the plus-or-minus sign [00:01:39].
* When you "undo" a square by taking a square root, you must acknowledge that both a positive and a negative value, when squared, result in a positive number [00:05:04].
* **Example:** If $x^2 = 18$, then $x = \pm\sqrt{18}$.
---
#### 3. Step-by-Step Procedure
1.  **Set to Zero:** Start with $f(x) = 0$ to find the x-intercepts [00:02:43].
2.  **Isolate the Square:** Move constants and divide by coefficients until the squared term is alone [00:12:03].
3.  **Square Root Both Sides:** Apply the radical to both sides. **Add $\pm$ to the constant side immediately** [00:17:22].
4.  **Simplify the Radical:** Pull out perfect squares (e.g., $\sqrt{32} = \sqrt{16 \cdot 2} = 4\sqrt{2}$) [00:24:24].
5.  **Solve for x:** If you have a binomial like $(x+2)$, subtract or add to isolate $x$. Place the moved number **in front** of the $\pm$ [00:18:55].
    * *Example:* $x = -2 \pm 1$ results in $x = -1$ and $x = -3$ [00:19:44].

---
#### 4. Interpreting the Results
The type of answer you get tells you exactly what the parabola is doing on the graph [00:08:33]:

| Result Type | Example | Graphical Meaning |
| :--- | :--- | :--- |
| **Two Distinct Reals** | $x = 3 \pm \sqrt{11}$ | Crosses the x-axis at two different points [00:13:47]. |
| **One Real (Double Root)** | $x = 7 \pm 0$ | The vertex sits exactly on the x-axis (bounces) [00:35:16]. |
| **Two Complex/Imaginary** | $x = 2 \pm 5i$ | The parabola never touches the x-axis (floats above/below) [00:39:00]. |

---
### 💡 Formatting Tips for Calculations
* **Exact Solutions:** Keep the radical (e.g., $\sqrt{11}$). Do not use decimals unless specifically asked for an "approximation" [00:14:23].
* **Complex Conjugates:** Imaginary solutions always come in pairs (conjugates) because of the $\pm$ sign ($a + bi$ and $a - bi$) [00:42:07].
* **Simplifying Fractions:** If you have $\frac{-3 \pm 4\sqrt{2}}{2}$, you can only simplify if the denominator divides **both** terms in the numerator [00:27:02].
### Solving f(x) = x² - 18 (Square Root Method)

To find the **x-intercepts** (zeros) of the function $f(x) = x^2 - 18$, we set the function to zero and isolate the squared term.

---
#### 1. Set the Function to Zero
$$0 = x^2 - 18$$

#### 2. Isolate the Squared Term
Add 18 to both sides of the equation:
$$18 = x^2$$
#### 3. Apply the Square Root Method
Take the square root of both sides. **Crucial:** Remember to include the $\pm$ sign to account for both the positive and negative roots.
$$\pm\sqrt{18} = x$$

#### 4. Simplify the Radical
Break down 18 into its prime factors to find the largest perfect square ($\sqrt{9}$):
$$x = \pm\sqrt{9 \cdot 2}$$
$$x = \pm3\sqrt{2}$$

---
### ⚠️ Graphical Interpretation

* **X-Intercepts:** The graph crosses the x-axis at approximately **$(4.24, 0)$** and **$(-4.24, 0)$**.
* **Vertex:** Since there is no "middle" $bx$ term, the vertex remains on the y-axis at **$(0, -18)$**.
* **Solutions:** Because we have two real, distinct numbers, the parabola has two clear x-intercepts.
---
> [!abstract] Algebra Takeaway
> When using the square root method, always simplify your radical into **exact form** (using the radical symbol) rather than decimals unless otherwise specified. For $x^2 = 18$, the "clean" answer is $\pm3\sqrt{2}$.

### Solving f(x) = 3x² - 33 (Square Root Method)

To find the **x-intercepts** (zeros) of the function $f(x) = 3x^2 - 33$, we set the function to zero and isolate the $x^2$ term before applying the Square Root Method.

---
#### 1. Set the Function to Zero
Replace $f(x)$ with $0$ to find where the parabola touches the x-axis:
$$0 = 3x^2 - 33$$

#### 2. Isolate the Squared Term
First, add 33 to both sides:
$$33 = 3x^2$$
Next, divide both sides by 3 to get $x^2$ completely alone:
$$11 = x^2$$

#### 3. Apply the Square Root Method
Take the square root of both sides. **Crucial:** You must include the $\pm$ sign to account for both the positive and negative directions on the x-axis.
$$x = \pm\sqrt{11}$$
---
### ⚠️ Graphical Interpretation

* **X-Intercepts:** The graph crosses the x-axis at approximately **$(3.32, 0)$** and **$(-3.32, 0)$**.
* **Vertex:** Since there is no "middle" $bx$ term, the vertex is located at **$(0, -33)$**.
* **Type of Solutions:** Because 11 is not a perfect square, we leave the answer in its **Exact Form**: $\pm\sqrt{11}$.
---

> [!abstract] Algebra Takeaway
> Always isolate the squared part **completely** (including dividing by any coefficients) before you take the square root. For $3x^2 = 33$, dividing by 3 first is the only way to avoid messy calculations under the radical.
### Solving g(x) = (x + 2)² - 1 (Square Root Method)

To find the **x-intercepts** (zeros) of the function $g(x) = (x + 2)^2 - 1$, we set the function to zero and isolate the squared binomial.

---
#### 1. Set the Function to Zero
Replace $g(x)$ with $0$ to find the roots:
$$0 = (x + 2)^2 - 1$$

#### 2. Isolate the Squared Binomial
Add 1 to both sides to move the constant away from the square:
$$1 = (x + 2)^2$$

#### 3. Apply the Square Root Method
Take the square root of both sides. **Crucial:** You must add the $\pm$ sign to the constant side immediately.
$$\pm\sqrt{1} = x + 2$$
$$\pm 1 = x + 2$$

#### 4. Solve for x
Isolate $x$ by subtracting 2 from both sides. Place the $-2$ in front of the $\pm$ sign for clarity:
$$x = -2 \pm 1$$

Now, calculate both separate solutions:
* **Solution 1:** $x = -2 + 1 = \mathbf{-1}$
* **Solution 2:** $x = -2 - 1 = \mathbf{-3}$

---
### ⚠️ Graphical Interpretation

* **X-Intercepts:** The graph crosses the x-axis at exactly **$(-1, 0)$** and **$(-3, 0)$**.
* **Vertex:** Using your knowledge of transformations, the vertex is at **$(-2, -1)$**.
* **Type of Solutions:** Because we obtained two distinct integers, we know the original quadratic could also have been solved by factoring if expanded.

---

> [!abstract] Algebra Takeaway
> When solving a squared binomial, do not expand it (FOIL). Instead, isolate the entire group, take the square root, and then finish by moving the number inside the parentheses. This is significantly faster and less prone to calculation errors.

### Solving h(x) = (2x + 3)² - 32 (Square Root Method)

To find the **x-intercepts** (zeros) of the function $h(x) = (2x + 3)^2 - 32$, we isolate the squared binomial and apply the Square Root Method.

---
#### 1. Set the Function to Zero
Replace $h(x)$ with $0$ to find where the parabola crosses the x-axis:
$$0 = (2x + 3)^2 - 32$$

#### 2. Isolate the Squared Binomial
Add 32 to both sides to move the constant away from the square:
$$32 = (2x + 3)^2$$

#### 3. Apply the Square Root Method
Take the square root of both sides. **Crucial:** You must include the $\pm$ sign to account for both directions on the x-axis.
$$\pm\sqrt{32} = 2x + 3$$
#### 4. Simplify the Radical
Break down 32 into its factors to pull out the largest perfect square ($16$):
$$\pm\sqrt{16 \cdot 2} = 2x + 3$$
$$\pm 4\sqrt{2} = 2x + 3$$
#### 5. Solve for x
First, subtract 3 from both sides. Place it **in front** of the $\pm$ sign:
$$-3 \pm 4\sqrt{2} = 2x$$

Finally, divide the entire expression by 2:
$$x = \frac{-3 \pm 4\sqrt{2}}{2}$$
---
### ⚠️ Graphical Interpretation

* **X-Intercepts:** The graph crosses the x-axis at approximately **$(1.33, 0)$** and **$(-4.33, 0)$**.
* **Vertex:** Using your knowledge of transformations, the vertex is located at **$(-1.5, -32)$**.
* **Exact vs. Approximate:** In Precalculus, we leave the answer as **$\frac{-3 \pm 4\sqrt{2}}{2}$**. This represents two irrational real numbers.
---

> [!abstract] Algebra Takeaway
> When the coefficient of $x$ inside the square is not 1 (like the $2$ in $2x+3$), your very last step will always be a division. Make sure you divide **both** the lead number and the radical coefficient by the denominator if they are divisible; otherwise, leave it as one large fraction.
### Solving f(x) = (x - 7)² (Square Root Method)

To find the **x-intercepts** (zeros) of the function $f(x) = (x - 7)^2$, we set the function to zero and solve for $x$ using the Square Root Method.

---

#### 1. Set the Function to Zero
Replace $f(x)$ with $0$ to identify the points where the graph touches the x-axis:
$$0 = (x - 7)^2$$

#### 2. Apply the Square Root Method
Take the square root of both sides. 
* **Note:** Unlike previous problems, $\sqrt{0}$ is simply $0$. There is no "plus or minus" zero because zero is neutral.
$$\pm\sqrt{0} = x - 7$$
$$0 = x - 7$$
#### 3. Solve for x
Isolate $x$ by adding 7 to both sides:
$$x = 7$$

---
### ⚠️ Graphical Interpretation

* **X-Intercept:** The graph touches the x-axis at exactly **$(7, 0)$**.
* **Vertex:** Using transformations, we know the parent function $x^2$ was shifted **Right 7 units**. The vertex is at **$(7, 0)$**.
* **Type of Solution:** This is a **Single Real Solution**, also known as a **Double Root**. 
    * Because the squared binomial is equal to zero, the parabola does not "cross" the axis; it "bounces" off the axis at its vertex.

---

> [!abstract] Algebra Takeaway
> When a squared term equals zero, you will only have one solution. This indicates that the vertex of your parabola is sitting directly on the x-axis. In your Obsidian notes, remember that $(x-7)^2 = 0$ is the algebraic way of saying the graph just "kisses" the x-axis at $x=7$.

### Solving f(x) = (3x - 2)² + 75 (Square Root Method)

To find the **x-intercepts** (zeros) of the function $f(x) = (3x - 2)^2 + 75$, we isolate the squared binomial and apply the Square Root Method. Because the squared term will equal a negative number, the solutions will be **complex**.

---
#### 1. Set the Function to Zero
Replace $f(x)$ with $0$ to identify the points where the graph would interact with the x-axis:
$$0 = (3x - 2)^2 + 75$$
#### 2. Isolate the Squared Binomial
Subtract 75 from both sides of the equation:
$$-75 = (3x - 2)^2$$
#### 3. Apply the Square Root Method
Take the square root of both sides. **Crucial:** You must include the $\pm$ sign and account for the negative inside the radical using $i$ ($\sqrt{-1} = i$).
$$\pm\sqrt{-75} = 3x - 2$$
$$\pm i\sqrt{75} = 3x - 2$$
#### 4. Simplify the Radical
Break down 75 into its prime factors to pull out the largest perfect square ($25$):
$$\pm i\sqrt{25 \cdot 3} = 3x - 2$$
$$\pm 5i\sqrt{3} = 3x - 2$$
#### 5. Solve for x
First, add 2 to both sides. Place it **in front** of the $\pm$ sign:
$$2 \pm 5i\sqrt{3} = 3x$$

Finally, divide the entire expression by 3:
$$x = \frac{2 \pm 5i\sqrt{3}}{3}$$

---
### ⚠️ Graphical Interpretation
* **X-Intercepts:** There are **no real x-intercepts**. Because the solutions contain the imaginary unit $i$, the parabola never touches or crosses the x-axis.
* **Vertex:** Using transformations, the vertex is located at approximately **$(2/3, 75)$**.
* **Type of Solutions:** These are **Complex Conjugates**. In your Obsidian notes, remember that complex solutions always come in pairs ($a + bi$ and $a - bi$).
---

> [!abstract] Algebra Takeaway
> When you take the square root of a negative number, the graph "floats" away from the x-axis. Algebraically, you simply factor out the $i$ and continue simplifying the radical as usual. The resulting fraction represents the two complex roots of the quadratic.

## 2026-March-20 - Using Factoring to Solve Quadratics (Precalculus - College Algebra 18) :
https://www.youtube.com/watch?v=u2CFHYJWS60&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=21
### Solving Quadratics by Factoring (Professor Leonard)

Factoring is the second primary technique for finding **x-intercepts** (also called zeros, roots, or solutions). While the Square Root Method is faster for isolated squares, factoring is the go-to when you have an $ax^2 + bx + c$ trinomial where $b \neq 0$.

---
#### 1. Core Prerequisites for Factoring
Before applying any factoring technique, your equation must meet these three conditions:
1.  **Set to Zero:** The equation must be $f(x) = 0$.
2.  **Descending Order:** Terms must be arranged as $ax^2 + bx + c$.
3.  **Positive Leading Coefficient:** If $a$ is negative, multiply the entire equation by $-1$ to make $a$ positive. This simplifies the process without changing the x-intercepts [00:36:58].
4.  **Factor GCF First:** Always check for a Greatest Common Factor (GCF) before starting. This keeps your numbers small and manageable [00:18:50].
---
#### 2. The "Diamond Method" (Graphic Organizer)
To factor a trinomial $ax^2 + bx + c$, use an "X" or diamond to find two numbers that satisfy two specific conditions:
* **Top of X:** The $b$ term (the sum).
* **Bottom of X:** The product of $a \cdot c$.
* **Goal:** Find two numbers that **multiply** to $a \cdot c$ and **add** to $b$ [00:06:55].
---
#### 3. The "Complete Shortcut" for $a > 1$
Professor Leonard teaches a specific shortcut that works even when the leading coefficient is not 1. This prevents the need for long "Factoring by Grouping" [00:31:52]:

1.  Find your two magic numbers from the Diamond Method.
2.  **Divide** both numbers by the leading coefficient ($a$).
3.  **Simplify** the resulting fractions, but keep them as fractions (e.g., write $4$ as $4/1$).
4.  **Read the Factors:**
    * **Denominator:** Tells you the coefficient of $x$.
    * **Numerator:** Tells you the constant.
    * *Example:* A fraction of $2/3$ becomes a factor of $(3x + 2)$ [00:33:14].
5.  **Find Solutions:** Simply change the signs of your simplified fractions to get the x-intercepts immediately [00:33:40].
---
#### 4. Special Cases in Factoring
* **Double Roots:** If your two magic numbers are the same (e.g., -6 and -6), you have a "perfect square trinomial." The graph just "bounces" off the x-axis at a single point [00:47:35].
* **Non-Perfect Square Differences:** You can factor things like $x^2 - 5$ by using the square root: $(x - \sqrt{5})(x + \sqrt{5})$ [00:54:15].
* **No Imaginary Solutions:** Unlike the Square Root Method or Quadratic Formula, if a quadratic is factorable over real numbers, you will not encounter $i$ [00:02:07].
---
### ⚠️ Critical Comparison

| Method | When to Use | Result Type |
| :--- | :--- | :--- |
| **Square Root Method** | When there is no $bx$ term (e.g., $x^2 - 18$). | Real or Imaginary. |
| **Factoring** | When $ax^2 + bx + c$ is present and factorable. | Real only. |

---
> [!abstract] Algebra Takeaway
> The "Complete Shortcut" (dividing by $a$) is the most reliable way to handle complex factoring. It bridges the gap between simple factoring and the heavy lifting of the Quadratic Formula. Always simplify your fractions before reading your factors!

### Solving f(x) = x² + 7x + 6

This quadratic can be solved using two different approaches. **Factoring** (using Professor Leonard's "Diamond Method" shortcut) is the fastest when the numbers are clean, while **Completing the Square** is a universal method that works even for messy decimals or imaginary roots.

---
### Method 1: Professor Leonard's Factoring Shortcut
Since the leading coefficient is $1$, we look for two numbers that satisfy the "Diamond" requirements.

1.  **Identify the Target:**
    * **Sum ($b$):** $7$
    * **Product ($a \cdot c$):** $1 \cdot 6 = 6$
2.  **Find the "Magic Numbers":** Which two numbers multiply to $6$ and add to $7$?
    * The numbers are **$6$** and **$1$**.
3.  **Apply the Shortcut:**
    * Since $a=1$, we simply place these into binomials:
    * $f(x) = (x + 6)(x + 1)$
4.  **Solve for Zeros:** Set each factor to zero.
    * $x + 6 = 0 \rightarrow \mathbf{x = -6}$
    * $x + 1 = 0 \rightarrow \mathbf{x = -1}$

---
### Method 2: Completing the Square
This method forces the equation into a "Squared Binomial" format so we can use the Square Root Method.

1.  **Isolate the x-terms:** Move the constant to the other side.
    $$x^2 + 7x = -6$$
2.  **Find the "Magic Number":** Use the formula $(\frac{b}{2})^2$.
    * $b = 7$
    * $\frac{7}{2} = 3.5$
    * $(3.5)^2 = \mathbf{12.25}$ (or $49/4$)
3.  **Balance the Equation:** Add $12.25$ to **both** sides.
    $$x^2 + 7x + 12.25 = -6 + 12.25$$
4.  **The Factoring Shortcut:** The left side *always* factors into $(x + \frac{b}{2})^2$.
    $$(x + 3.5)^2 = 6.25$$
5.  **Square Root Method:**
    $$x + 3.5 = \pm\sqrt{6.25}$$
    $$x + 3.5 = \pm 2.5$$
6.  **Final Solutions:**
    * $x = -3.5 + 2.5 = \mathbf{-1}$
    * $x = -3.5 - 2.5 = \mathbf{-6}$

---
### ⚠️ Comparison for your Notes

| Feature | Factoring Method | Completing the Square |
| :--- | :--- | :--- |
| **Speed** | Very Fast (if factorable) | Slower, more steps |
| **Reliability** | Only works for "clean" roots | Works for **all** quadratics |
| **Visual Hint** | Finds intercepts directly | Reveals the **Vertex** ($h, k$) |

---

> [!abstract] Algebra Takeaway
> While factoring $(x+6)(x+1)$ is the path of least resistance here, Completing the Square is the superior tool for graphing because it gives you the vertex **$(-3.5, -6.25)$** as a byproduct of the calculation.
### ### Solving g(x) = 3x(x - 4) - 36

To find the **x-intercepts** (zeros) of this function, we first need to get it into standard trinomial form ($ax^2 + bx + c$) by distributing the $3x$:
$$g(x) = 3x^2 - 12x - 36$$

Setting the function to zero:
$$0 = 3x^2 - 12x - 36$$

---
### Method 1: Professor Leonard's Factoring Shortcut
This is the fastest method when the quadratic is factorable. 

1.  **Factor the GCF first:** Notice all terms are divisible by 3.
    $$0 = 3(x^2 - 4x - 12)$$
2.  **Identify the Target (Diamond Method):**
    * **Sum ($b$):** $-4$
    * **Product ($a \cdot c$):** $1 \cdot (-12) = -12$
3.  **Find the Magic Numbers:** Which two numbers multiply to $-12$ and add to $-4$?
    * The numbers are **$-6$** and **$+2$**.
4.  **Apply the Shortcut:**
    * $0 = 3(x - 6)(x + 2)$
5.  **Solve for Zeros:**
    * $x - 6 = 0 \rightarrow \mathbf{x = 6}$
    * $x + 2 = 0 \rightarrow \mathbf{x = -2}$

---
### Method 2: Completing the Square
This method is used to force the equation into a "Squared Binomial" so we can use the **Square Root Method**.

1.  **Isolate and Simplify:** Move the constant and divide by the leading coefficient ($a=3$).
    $$3x^2 - 12x = 36$$
    $$x^2 - 4x = 12$$
2.  **Find the Magic Number:** Use $(\frac{b}{2})^2$.
    * $b = -4$
    * $\frac{-4}{2} = -2$
    * $(-2)^2 = \mathbf{4}$
3.  **Balance the Equation:** Add $4$ to **both** sides.
    $$x^2 - 4x + 4 = 12 + 4$$
4.  **The Factoring Shortcut:** The left side *always* factors into $(x + \frac{b}{2})^2$.
    $$(x - 2)^2 = 16$$
5.  **Square Root Method (The Finisher):**
    $$x - 2 = \pm\sqrt{16}$$
    $$x - 2 = \pm 4$$
6.  **Final Solutions:**
    * $x = 2 + 4 = \mathbf{6}$
    * $x = 2 - 4 = \mathbf{-2}$
---
### ⚠️ Comparison for your Notes

| Feature | Factoring Method | Completing the Square |
| :--- | :--- | :--- |
| **Setup** | Set to $0$, pull out GCF | Move constant, divide by $a$ |
| **Core Logic** | $(x - 6)(x + 2) = 0$ | $(x - 2)^2 = 16$ |
| **Best Used For** | Quick mental math | Finding the **Vertex** $(2, -48)$ |

---
> [!abstract] Algebra Takeaway
> Whether you factor it into $(x-6)(x+2)$ or complete the square to get $(x-2)^2$, you are describing the same parabola. Factoring is your "sprint" to the answers, while Completing the Square is your "map" of the graph's structure.

### Solving g(x) = 3x² + 2 + 5x

To solve this quadratic, we first rewrite it in **Standard Form** ($ax^2 + bx + c = 0$):
$$0 = 3x^2 + 5x + 2$$
---
### Method 1: Professor Leonard's "Diamond Method" Shortcut
This is the fastest factoring technique for when the leading coefficient ($a$) is greater than 1.

1.  **The Diamond Setup:**
    * **Top (Sum $b$):** $5$
    * **Bottom (Product $a \cdot c$):** $3 \cdot 2 = 6$
2.  **Find the Magic Numbers:** Which two numbers multiply to $6$ and add to $5$?
    * The numbers are **$3$** and **$2$**.
3.  **The "Complete Shortcut" (Division by $a$):**
    * Divide both magic numbers by the leading coefficient ($a = 3$):
    * **Number 1:** $3/3 = \mathbf{1/1}$
    * **Number 2:** $\mathbf{2/3}$
4.  **Read the Factors:** (Denominator is the $x$ coefficient, Numerator is the constant)
    * $1/1 \rightarrow (1x + 1)$
    * $2/3 \rightarrow (3x + 2)$
    * **Factored Form:** $0 = (x + 1)(3x + 2)$
5.  **Solve for Zeros:**
    * $x + 1 = 0 \rightarrow \mathbf{x = -1}$
    * $3x + 2 = 0 \rightarrow 3x = -2 \rightarrow \mathbf{x = -2/3}$
---
### Method 2: Completing the Square
This method is used to find the vertex and works even if the numbers don't factor cleanly.

1.  **Isolate and Normalize:** Move the constant and divide by $a = 3$.
    $$3x^2 + 5x = -2$$
    $$x^2 + \frac{5}{3}x = -\frac{2}{3}$$
2.  **Find the Magic Number:** Use $(\frac{b}{2})^2$.
    * $b = 5/3$
    * $\frac{1}{2} \cdot \frac{5}{3} = \frac{5}{6}$
    * $(\frac{5}{6})^2 = \mathbf{\frac{25}{36}}$
3.  **Balance the Equation:** Add $25/36$ to both sides.
    $$x^2 + \frac{5}{3}x + \frac{25}{36} = -\frac{2}{3} + \frac{25}{36}$$
    *Convert $-2/3$ to $-24/36$ to add:*
    $$x^2 + \frac{5}{3}x + \frac{25}{36} = \frac{1}{36}$$
4.  **The Factoring Shortcut:**
    $$(x + \frac{5}{6})^2 = \frac{1}{36}$$
5.  **Square Root Method (The Finisher):**
    $$x + \frac{5}{6} = \pm\sqrt{\frac{1}{36}}$$
    $$x + \frac{5}{6} = \pm \frac{1}{6}$$
6.  **Final Solutions:**
    * $x = -\frac{5}{6} + \frac{1}{6} = -\frac{4}{6} = \mathbf{-2/3}$
    * $x = -\frac{5}{6} - \frac{1}{6} = -\frac{6}{6} = \mathbf{-1}$

---
### ⚠️ Comparison for your Notes

| Feature | Diamond Method | Completing the Square |
| :--- | :--- | :--- |
| **Logic** | $(x+1)(3x+2) = 0$ | $(x + 5/6)^2 = 1/36$ |
| **Key Advantage** | Fastest for x-intercepts | Reveals Vertex: **$(-5/6, -1/36)$** |
| **Common Error** | Forgetting to divide by $a$ | Mistakes in fraction addition |

---
> [!abstract] Algebra Takeaway
> Professor Leonard's Diamond Shortcut ($a \cdot c$) is a lifesaver for $3x^2$ problems. However, Completing the Square proves that even when you have messy fractions like $5/3$, the structure of the parabola remains predictable and solvable.

### Solving h(x) = -2x² - 5x + 12 (Professor Leonard's Diamond Method)

To solve this quadratic for the **x-intercepts** (zeros), we must first ensure the leading coefficient ($a$) is positive. Professor Leonard recommends multiplying the entire equation by $-1$ to make factoring significantly easier.

---
#### 1. Setup and Normalize
Set the function to zero and multiply both sides by $-1$ to flip the signs:
$$0 = -2x^2 - 5x + 12$$
$$0 = 2x^2 + 5x - 12$$

#### 2. The Diamond Setup
Now, we look for two "magic numbers" that satisfy the $a \cdot c$ conditions:
* **Top (Sum $b$):** $5$
* **Bottom (Product $a \cdot c$):** $2 \cdot (-12) = \mathbf{-24}$
#### 3. Find the Magic Numbers
We need two numbers that multiply to $-24$ and add to $5$:
* **Pair:** $8$ and $-3$
* Check: $8 \times -3 = -24$ and $8 + (-3) = 5$.
#### 4. The "Complete Shortcut" (Division by $a$)
Divide both magic numbers by the leading coefficient ($a = 2$) and simplify the fractions:
* **Number 1:** $8/2 = \mathbf{4/1}$
* **Number 2:** $\mathbf{-3/2}$ (Already simplified)
#### 5. Read the Factors
Using the denominator as the $x$ coefficient and the numerator as the constant:
* $4/1 \rightarrow (1x + 4)$
* $-3/2 \rightarrow (2x - 3)$

**Factored Form:** $0 = (x + 4)(2x - 3)$
#### 6. Solve for Zeros
Set each binomial factor to zero:
* $x + 4 = 0 \rightarrow \mathbf{x = -4}$
* $2x - 3 = 0 \rightarrow 2x = 3 \rightarrow \mathbf{x = 3/2}$ (or $1.5$)
---
### ⚠️ Graphical Interpretation

* **X-Intercepts:** The graph crosses the x-axis at **$(-4, 0)$** and **$(1.5, 0)$**.
* **Direction:** Because the *original* leading coefficient was negative ($-2$), the parabola opens **downward**.
* **Y-Intercept:** Looking at the original equation, the constant term is $+12$, so the graph crosses the y-axis at **$(0, 12)$**.
---

> [!abstract] Algebra Takeaway
> Never try to factor with a negative $x^2$ term. Flipping the signs at the start (Step 1) allows you to use the Diamond Method shortcut accurately without confusing the signs of your factors.
### Solving h(x) = -2x² - 5x + 12 (Factoring by Grouping)

To find the **x-intercepts** using grouping, we first set the function to zero and multiply by $-1$ to ensure the leading coefficient is positive, exactly like we did for the Diamond Method.

---
#### 1. Setup and Standardize
$$0 = 2x^2 + 5x - 12$$
#### 2. Find the "Split" Numbers
We need two numbers that multiply to $a \cdot c$ ($2 \times -12 = -24$) and add to $b$ ($5$).
* As determined previously, those numbers are **$8$** and **$-3$**.
#### 3. Rewrite the Middle Term
Instead of $5x$, we rewrite the equation using our two magic numbers. This turns the trinomial into a four-term polynomial:
$$0 = 2x^2 + 8x - 3x - 12$$
#### 4. Group and Factor GCF
Divide the four terms into two separate groups:
* **Group 1:** $(2x^2 + 8x)$ $\rightarrow$ Factor out the GCF: **$2x(x + 4)$**
* **Group 2:** $(-3x - 12)$ $\rightarrow$ Factor out the GCF: **$-3(x + 4)$**
#### 5. Factor the Common Binomial
Notice that **$(x + 4)$** is now common to both terms. Pull it out to the front:
$$0 = (x + 4)(2x - 3)$$
#### 6. Solve for Zeros
* $x + 4 = 0 \rightarrow \mathbf{x = -4}$
* $2x - 3 = 0 \rightarrow 2x = 3 \rightarrow \mathbf{x = 3/2}$

---
### ⚠️ Method Comparison: Shortcut vs. Grouping

| Feature | Diamond Shortcut | Factoring by Grouping |
| :--- | :--- | :--- |
| **Effort** | Low (uses fractions) | Medium (requires 4 terms) |
| **Logic** | Mechanical pattern | Structural algebra |
| **Best For** | Fast test-taking | Showing full work on exams |

---

> [!abstract] Algebra Takeaway
> Factoring by grouping is the "why" behind Professor Leonard's shortcut. While the shortcut skips the middle steps by using $a$ as a denominator, grouping shows exactly how the $5x$ term is split and redistributed to form the final binomials.
### Solving f(x) = 4x² - 12x + 9

First, we rewrite the function in **Standard Form** ($ax^2 + bx + c$):
$$f(x) = 4x^2 - 12x + 9$$

To find the x-intercepts, we set the function to zero:
$$0 = 4x^2 - 12x + 9$$
---
### Method 1: Professor Leonard's Diamond Method
This is the "Complete Shortcut" for when $a > 1$.

1.  **The Diamond Setup:**
    * **Top (Sum $b$):** $-12$
    * **Bottom (Product $a \cdot c$):** $4 \cdot 9 = 36$
2.  **Find the Magic Numbers:** Which two numbers multiply to $36$ and add to $-12$?
    * The numbers are **$-6$** and **$-6$**.
3.  **The Shortcut (Division by $a$):**
    * Divide both magic numbers by the leading coefficient ($a = 4$):
    * **Number 1:** $-6/4 = \mathbf{-3/2}$
    * **Number 2:** $-6/4 = \mathbf{-3/2}$
4.  **Read the Factors:**
    * $0 = (2x - 3)(2x - 3) \rightarrow \mathbf{(2x - 3)^2 = 0}$
5.  **Solve for Zeros:**
    * $2x - 3 = 0 \rightarrow 2x = 3 \rightarrow \mathbf{x = 1.5}$
---
### Method 2: Factoring by Grouping
This shows the algebraic structure by splitting the middle term.

1.  **Split the Middle Term:** Use the magic numbers ($-6, -6$) to rewrite $-12x$:
    $$0 = 4x^2 - 6x - 6x + 9$$
2.  **Group and Factor GCF:**
    * **Group 1:** $(4x^2 - 6x) \rightarrow \mathbf{2x(2x - 3)}$
    * **Group 2:** $(-6x + 9) \rightarrow \mathbf{-3(2x - 3)}$
3.  **Factor the Common Binomial:**
    * $0 = (2x - 3)(2x - 3)$
    * $0 = (2x - 3)^2$
---
### Method 3: Factoring by Squaring (Perfect Square Trinomial)
Professor Leonard highlights this as a "special case" where the first and last terms are perfect squares.

1.  **Identify the Pattern:**
    * Is $4x^2$ a square? Yes, $(2x)^2$.
    * Is $9$ a square? Yes, $(3)^2$.
    * Is the middle term $2 \cdot (2x) \cdot (3)$? Yes, $12x$.
2.  **Write the Square:**
    * Since the middle sign is negative, it follows $(A - B)^2$:
    * $0 = (2x - 3)^2$
3.  **Solve using Square Root Method:**
    * $\sqrt{(2x - 3)^2} = \sqrt{0}$
    * $2x - 3 = 0 \rightarrow \mathbf{x = 1.5}$
---
### ⚠️ Graphical Interpretation
* **Type of Solution:** This is a **Double Root**. 
* **Behavior:** Because the two factors are identical, the parabola does not cross through the x-axis; it simply **touches/bounces** at the vertex $(1.5, 0)$.

---

> [!abstract] Algebra Takeaway
> When your magic numbers in the Diamond Method are identical, you have found a Perfect Square Trinomial. You can move directly to the "Squaring" logic, which is the most efficient way to solve and graph the vertex.

### Summary: Solving g(x) = x² - 5

To find the **x-intercepts** (roots) of the function $g(x) = x^2 - 5$, we set the function to zero and solve for $x$ using two mathematically identical approaches.

---
#### Method 1: Difference of Squares (x - √5)(x + √5)
Professor Leonard demonstrates that any binomial in the form $A^2 - B^2$ can be factored into $(A - B)(A + B)$, even if $B$ is not a perfect square integer.

1.  **Identify the Terms:** * $A^2 = x^2 \rightarrow A = x$
    * $B^2 = 5 \rightarrow B = \sqrt{5}$
2.  **Set up the Factors:**
    $$0 = (x - \sqrt{5})(x + \sqrt{5})$$
3.  **Solve for Zeros:**
    * $x - \sqrt{5} = 0 \Rightarrow \mathbf{x = \sqrt{5}}$
    * $x + \sqrt{5} = 0 \Rightarrow \mathbf{x = -\sqrt{5}}$
#### Method 2: Factoring by Squaring (Square Root Method)
Since there is no "middle" $bx$ term, we can isolate the squared variable directly. This is often the most efficient path for this specific structure.

1.  **Isolate the Square:**
    $$x^2 = 5$$
2.  **Take the Square Root of Both Sides:**
    Apply the radical to both sides. **Crucial:** You must include the $\pm$ sign to account for both the positive and negative roots.
    $$\sqrt{x^2} = \pm\sqrt{5}$$
3.  **Final Solutions:**
    $$\mathbf{x = \pm\sqrt{5}}$$
---
#### Graphical Interpretation
* **X-Intercepts:** The graph crosses the x-axis at approximately **(2.24, 0)** and **(-2.24, 0)**.
* **Vertex:** Because there is no horizontal shift ($h=0$), the vertex remains on the y-axis at **(0, -5)**.
* **Exact Form:** In Precalculus, always leave the answer as $\pm\sqrt{5}$ unless an approximation is requested.

> [!abstract] Algebra Takeaway
> Factoring $x^2 - 5$ as a difference of squares $(x - \sqrt{5})(x + \sqrt{5})$ is the structural equivalent of taking the square root of both sides. Both methods rely on the fact that 5 is the square of $\sqrt{5}$.

## 2026-March-21 - Completing the Square Made Easy (Precalculus - College Algebra 19) : 
https://www.youtube.com/watch?v=pYSYL_vy6YQ&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=21
### Completing the Square Made Easy
Completing the square is a method used to force a quadratic into a **Perfect Square Trinomial** so that the **Square Root Method** can be used to solve for $x$. While the Quadratic Formula is often faster for finding zeros, completing the square is a foundational tool for higher-level math (like Calculus II and analyzing Conic Sections).

---
#### 1. Core Principles
* **The Goal:** Transform $ax^2 + bx + c = 0$ into the form $(x + h)^2 = k$.
* **Balance Rule:** If you add a number to one side of the equation to make it factorable, you must immediately subtract it (or add it to the other side) to keep the equation balanced.
* **The "Leonard Way":** Work on one side of the equation. Add the "magic number" inside the parentheses and subtract it outside.
---
#### 2. The Step-by-Step Process ($a = 1$)
For a standard quadratic like $x^2 + 4x - 3 = 0$:

1.  **Isolate the Variable Terms:** Move the constant or "hold it off" to the side: $x^2 + 4x + (\_\_\_) - 3 = 0$.
2.  **Find the Magic Number:** * Take the $b$ term ($4$) and divide it by $2$ $\rightarrow$ **$2$**.
    * Square that result ($2^2$) $\rightarrow$ **$4$**.
3.  **Complete the Square:** Add $4$ inside and subtract $4$ outside:
    $$(x^2 + 4x + 4) - 4 - 3 = 0$$
4.  **Factor and Simplify:**
    $$(x + 2)^2 - 7 = 0$$
5.  **Solve:** $(x + 2)^2 = 7 \rightarrow x + 2 = \pm\sqrt{7} \rightarrow \mathbf{x = -2 \pm \sqrt{7}}$.

---
#### 3. Handling $a > 1$ (The Factoring Step)
If the leading coefficient is not 1 (e.g., $5x^2 - 10x + 2 = 0$), you **must** factor $a$ out of the $x$ terms first:
1.  **Factor out $a$:** $5(x^2 - 2x) + 2 = 0$.
2.  **Find the Magic Number for the interior:** Half of $-2$ is $-1$; $(-1)^2 = \mathbf{1}$.
3.  **Adjust for the Distribution:**
    * You add $1$ inside the parentheses: $5(x^2 - 2x + 1)$.
    * **Crucial:** You didn't actually add $1$; you added $5 \times 1 = 5$.
    * To balance, you must **subtract 5** outside: $5(x^2 - 2x + 1) - 5 + 2 = 0$.
4.  **Result:** $5(x - 1)^2 - 3 = 0$.
---
#### 4. Handling Fractions
When $b$ is an odd number or a fraction (e.g., $x^2 - 3x + 1 = 0$):
* **Half of $b$:** Half of $-3$ is **$-3/2$**.
* **Square it:** $(-3/2)^2 = \mathbf{9/4}$.
* **Balance:** $(x^2 - 3x + 9/4) - 9/4 + 1 = 0$.
* **Factor:** $(x - 3/2)^2 - 5/4 = 0$.
---
### ⚠️ Common Pitfalls to Avoid
* **Forgetting to Square:** Students often add $b/2$ instead of $(b/2)^2$.
* **Sign Errors:** When $a$ is negative (e.g., $-2x^2$), factoring it out changes the sign of the $b$ term inside the parentheses.
* **Distribution Oversight:** Always multiply the "magic number" by the factored-out $a$ before subtracting it from the constant.
---

> [!abstract] Algebra Takeaway
> Completing the square is essentially "manufacturing" a perfect square. By dividing $b$ by 2 and squaring it, you are finding the exact constant needed to make the $x$ terms collapse into a single squared binomial.

### Solving x² - 6x + 9 = 0 (Completing the Square)

To find the **x-intercepts** (zeros), we use the Completing the Square method to transform the trinomial into a squared binomial.

---
#### 1. Isolate the Variable Terms
Move the constant ($+9$) to the right side of the equation to create a "gap" for our calculation:
$$x^2 - 6x = -9$$
#### 2. Find the "Magic Number"
Use Professor Leonard's shortcut formula $(\frac{b}{2})^2$:
1.  **Identify $b$:** $-6$
2.  **Divide by 2:** $-3$
3.  **Square it:** $(-3)^2 = \mathbf{9}$

Add **9** to **both** sides of the equation to maintain algebraic balance:
$$x^2 - 6x + 9 = -9 + 9$$
#### 3. The Factoring Shortcut
The left side is now a **Perfect Square Trinomial**. It always factors into $(x + \frac{b}{2})^2$. Since half of our $b$ was $-3$:
$$(x - 3)^2 = 0$$
#### 4. The Square Root Method (The Finisher)
Take the square root of both sides. Because $\sqrt{0}$ is simply $0$, the $\pm$ sign is unnecessary here.
$$x - 3 = 0$$
#### 5. Final Solution
Isolate $x$ by adding 3 to both sides:
$$\mathbf{x = 3}$$
---
### ⚠️ Graphical Interpretation

* **X-Intercept:** The graph touches the x-axis at exactly **$(3, 0)$**.
* **Type of Solution:** This is a **Single Real Solution** (also known as a **Double Root**). 
* **Vertex:** Because the equation simplifies perfectly to $(x-3)^2 = 0$, the vertex is located exactly at the x-intercept: **$(3, 0)$**.
---

> [!abstract] Algebra Takeaway
> If the "magic number" you calculate $(\frac{b}{2})^2$ is identical to the constant already in the equation, you are dealing with a Perfect Square Trinomial. This means the parabola "bounces" off the x-axis at a single point rather than crossing through it.
### Solving f(x) = x² + 4x - 3 (Completing the Square)

To find the **x-intercepts** (zeros), we use the Completing the Square method to transform the trinomial into a squared binomial, which then allows us to use the Square Root Method.

---
#### 1. Set the Function to Zero and Isolate Variable Terms
Replace $f(x)$ with $0$ and move the constant ($-3$) to the right side of the equation to create a "gap" for our calculation:
$$x^2 + 4x = 3$$
#### 2. Find the "Magic Number"
Use Professor Leonard's shortcut formula $(\frac{b}{2})^2$:
1.  **Identify $b$:** $4$
2.  **Divide by 2:** $2$
3.  **Square it:** $(2)^2 = \mathbf{4}$

Add **4** to **both** sides of the equation to maintain algebraic balance:
$$x^2 + 4x + 4 = 3 + 4$$
#### 3. The Factoring Shortcut
The left side is now a **Perfect Square Trinomial**. It always factors into $(x + \frac{b}{2})^2$. Since half of our $b$ was $+2$:
$$(x + 2)^2 = 7$$
#### 4. The Square Root Method (The Finisher)
Take the square root of both sides. Because $7$ is not a perfect square, we leave it in radical form and include the $\pm$ sign:
$$x + 2 = \pm\sqrt{7}$$
#### 5. Final Solutions
Isolate $x$ by subtracting 2 from both sides:
$$\mathbf{x = -2 \pm \sqrt{7}}$$

* **Exact Solutions:** $x = -2 + \sqrt{7}$ and $x = -2 - \sqrt{7}$
* **Approximate Solutions:** $x \approx 0.65$ and $x \approx -4.65$
---
### ⚠️ Graphical Interpretation

* **X-Intercepts:** The graph crosses the x-axis at two irrational points: **$(-2 + \sqrt{7}, 0)$** and **$(-2 - \sqrt{7}, 0)$**.
* **Vertex:** Completing the square reveals the vertex form. From $(x + 2)^2 - 7 = 0$, the vertex is at **$(-2, -7)$**.
* **Type of Solutions:** These are **Real, Irrational Solutions**. Because the number under the radical (7) is positive but not a perfect square, the roots are real but cannot be written as simple fractions.
---
> [!abstract] Algebra Takeaway
> Completing the square is the most reliable way to find the "Vertex Form" of a quadratic. While factoring $(x+h)(x+k)$ only works if the roots are rational, completing the square works for any quadratic, including those with square roots or imaginary numbers.
### Solving g(x) = x² - 3x + 1 (Completing the Square)

To find the **x-intercepts** (zeros), we use Completing the Square. This specific problem involves an **odd** $b$ value, which means we will be working with fractions.

---
#### 1. Set the Function to Zero and Isolate Variable Terms
Replace $g(x)$ with $0$ and move the constant ($+1$) to the right side of the equation:
$$x^2 - 3x = -1$$#### 2. Find the "Magic Number"
Use Professor Leonard's shortcut formula $(\frac{b}{2})^2$:
1.  **Identify $b$:** $-3$
2.  **Divide by 2:** $-\frac{3}{2}$
3.  **Square it:** $(-\frac{3}{2})^2 = \mathbf{\frac{9}{4}}$

Add **9/4** to **both** sides of the equation to maintain balance:
$$x^2 - 3x + \frac{9}{4} = -1 + \frac{9}{4}$$#### 3. The Factoring Shortcut
The left side is now a **Perfect Square Trinomial**. It always factors into $(x + \frac{b}{2})^2$. Since half of our $b$ was $-\frac{3}{2}$:
$$(x - \frac{3}{2})^2 = -\frac{4}{4} + \frac{9}{4}$$
$$(x - \frac{3}{2})^2 = \frac{5}{4}$$#### 4. The Square Root Method (The Finisher)
Take the square root of both sides. Remember to apply the root to both the numerator and denominator:
$$x - \frac{3}{2} = \pm\sqrt{\frac{5}{4}}$$
$$x - \frac{3}{2} = \pm\frac{\sqrt{5}}{2}$$#### 5. Final Solutions
Isolate $x$ by adding $3/2$ to both sides. Since the denominators are the same, we can combine them into one fraction:
$$\mathbf{x = \frac{3 \pm \sqrt{5}}{2}}$$
* **Exact Solutions:** $x = \frac{3 + \sqrt{5}}{2}$ and $x = \frac{3 - \sqrt{5}}{2}$
* **Approximate Solutions:** $x \approx 2.62$ and $x \approx 0.38$
---
### ⚠️ Graphical Interpretation

* **X-Intercepts:** The graph crosses the x-axis at two irrational points: **$(\frac{3 + \sqrt{5}}{2}, 0)$** and **$(\frac{3 - \sqrt{5}}{2}, 0)$**.
* **Vertex:** From the completed square form $(x - 1.5)^2 - 1.25 = 0$, the vertex is at **$(1.5, -1.25)$**.
* **Type of Solutions:** These are **Real, Irrational Solutions**. Because 5 is not a perfect square, we must keep the radical to maintain an exact value.
---
> [!abstract] Algebra Takeaway
> When $b$ is an odd number, don't be afraid of the fractions. Keeping the "magic number" as a fraction ($9/4$) instead of a decimal ($2.25$) usually makes the square root step much easier, as the denominator will almost always be a perfect square ($4, 16, 64$, etc.).
### Solving h(x) = 5x² - 10x + 2 (Completing the Square)

This problem is a "Level 3" quadratic because the leading coefficient ($a$) is not 1. To complete the square, we must factor $a$ out of the $x$-terms first.

---
#### 1. Set the Function to Zero and Isolate Variable Terms
Replace $h(x)$ with $0$ and move the constant ($+2$) to the right side:
$$5x^2 - 10x = -2$$
#### 2. Factor out the Leading Coefficient ($a=5$)
Professor Leonard emphasizes that you cannot find the "magic number" until the $x^2$ term is isolated with a coefficient of 1. Factor 5 out of the left side:
$$5(x^2 - 2x) = -2$$
#### 3. Find the "Magic Number"
Focus only on the terms inside the parentheses ($x^2 - 2x$):
1.  **Identify $b$:** $-2$
2.  **Divide by 2:** $-1$
3.  **Square it:** $(-1)^2 = \mathbf{1}$
#### 4. Balance the Equation
**Crucial Step:** When you add $1$ inside the parentheses, you are actually adding $5 \times 1 = \mathbf{5}$ to the left side of the equation. To keep it balanced, you must add **5** to the right side as well:
$$5(x^2 - 2x + 1) = -2 + 5$$
$$5(x^2 - 2x + 1) = 3$$
#### 5. The Factoring Shortcut
The interior of the parentheses is now a Perfect Square Trinomial. Factor it using $(x + \frac{b}{2})^2$:
$$5(x - 1)^2 = 3$$
#### 6. Solve using the Square Root Method
First, divide by 5 to isolate the squared binomial, then take the square root of both sides:
$$(x - 1)^2 = \frac{3}{5}$$
$$x - 1 = \pm\sqrt{\frac{3}{5}}$$
#### 7. Final Solutions
Isolate $x$ and rationalize the denominator if required (multiply by $\sqrt{5}/\sqrt{5}$):
$$x = 1 \pm \frac{\sqrt{3}}{\sqrt{5}}$$
$$\mathbf{x = 1 \pm \frac{\sqrt{15}}{5}}$$
---
### ⚠️ Graphical Interpretation

* **Vertex:** The vertex is easily visible from the completed square form: **$(1, -3)$**. 
    * *Note:* In the form $5(x-1)^2 = 3$, moving the 3 back gives $5(x-1)^2 - 3 = 0$.
* **X-Intercepts:** The graph crosses at approximately **$1.77$** and **$0.23$**.
* **Direction:** Since $a=5$ (positive), the parabola opens upward and is narrower than a standard $x^2$ graph.
---
> [!abstract] Algebra Takeaway
> The most common mistake with $a \neq 1$ is forgetting to multiply the "magic number" by the factored-out coefficient. Always remember: **What you add to the inside must be multiplied by the outside before you add it to the other side.**
### Solving g(x) = x² + 2/3x - 1/3 (Completing the Square)

This problem involves fractions from the start. To find the **x-intercepts** (zeros), we use the Completing the Square method. 

---
#### 1. Set the Function to Zero and Isolate Variable Terms
Replace $g(x)$ with $0$ and move the constant ($-\frac{1}{3}$) to the right side of the equation:
$$x^2 + \frac{2}{3}x = \frac{1}{3}$$
#### 2. Find the "Magic Number"
Use Professor Leonard's formula $(\frac{b}{2})^2$:
1.  **Identify $b$:** $\frac{2}{3}$
2.  **Divide by 2:** $\frac{2}{3} \cdot \frac{1}{2} = \mathbf{\frac{1}{3}}$
3.  **Square it:** $(\frac{1}{3})^2 = \mathbf{\frac{1}{9}}$

Add **1/9** to **both** sides of the equation to maintain balance:
$$x^2 + \frac{2}{3}x + \frac{1}{9} = \frac{1}{3} + \frac{1}{9}$$
#### 3. The Factoring Shortcut
The left side is now a **Perfect Square Trinomial**. It always factors into $(x + \frac{b}{2})^2$. Using our result from Step 2:
$$(x + \frac{1}{3})^2 = \frac{3}{9} + \frac{1}{9}$$
$$(x + \frac{1}{3})^2 = \frac{4}{9}$$
#### 4. The Square Root Method (The Finisher)
Take the square root of both sides. Since both 4 and 9 are perfect squares, the radical disappears:
$$x + \frac{1}{3} = \pm\sqrt{\frac{4}{9}}$$
$$x + \frac{1}{3} = \pm\frac{2}{3}$$
#### 5. Final Solutions
Isolate $x$ by subtracting $1/3$ from both sides:
$$x = -\frac{1}{3} \pm \frac{2}{3}$$

* **Solution 1:** $x = -\frac{1}{3} + \frac{2}{3} = \frac{1}{3} \approx \mathbf{0.33}$
* **Solution 2:** $x = -\frac{1}{3} - \frac{2}{3} = -\frac{3}{3} = \mathbf{-1}$
---
### ⚠️ Graphical Interpretation

* **X-Intercepts:** The graph crosses the x-axis at **$(1/3, 0)$** and **$(-1, 0)$**.
* **Vertex:** From the completed square form $(x + 1/3)^2 - 4/9 = 0$, the vertex is at **$(-1/3, -4/9)$**.
* **Type of Solutions:** These are **Real, Rational Solutions**. Because the magic number combined with the constant resulted in a perfect square ($4/9$), the roots are clean fractions/integers.
---
> [!abstract] Algebra Takeaway
> Even when the problem starts with fractions, the process remains identical. Keeping everything in fraction form (using $1/9$ instead of $0.111...$) ensures that your "finishing" step with the square root remains precise and often results in perfect squares that are easy to simplify.

### Solving f(x) = 3x² + x - 1/2 (Completing the Square)

This is a "Level 4" problem because it combines a leading coefficient ($a=3$), an odd middle term, and a fractional constant. We must follow Professor Leonard’s steps for factoring $a$ out before finding the magic number.

---
#### 1. Set the Function to Zero and Isolate Variable Terms
Replace $f(x)$ with $0$ and move the constant ($-\frac{1}{2}$) to the right side:
$$3x^2 + x = \frac{1}{2}$$
#### 2. Factor out the Leading Coefficient ($a=3$)
To complete the square, the $x^2$ term must have a coefficient of 1. Factor 3 out of the left side:
$$3(x^2 + \frac{1}{3}x) = \frac{1}{2}$$
#### 3. Find the "Magic Number"
Focus on the interior of the parentheses ($x^2 + \frac{1}{3}x$):
1.  **Identify $b$:** $\frac{1}{3}$
2.  **Divide by 2:** $\frac{1}{3} \cdot \frac{1}{2} = \mathbf{\frac{1}{6}}$
3.  **Square it:** $(\frac{1}{6})^2 = \mathbf{\frac{1}{36}}$
#### 4. Balance the Equation
**Crucial Step:** When you add $1/36$ inside the parentheses, you are actually adding $3 \times \frac{1}{36} = \mathbf{\frac{1}{12}}$ to the left side. You must add **1/12** to the right side to keep it balanced:
$$3(x^2 + \frac{1}{3}x + \frac{1}{36}) = \frac{1}{2} + \frac{1}{12}$$
*Convert 1/2 to 6/12 to add:*
$$3(x^2 + \frac{1}{3}x + \frac{1}{36}) = \frac{7}{12}$$
#### 5. The Factoring Shortcut
The interior factors into $(x + \frac{b}{2})^2$. Using our result from Step 3:
$$3(x + \frac{1}{6})^2 = \frac{7}{12}$$
#### 6. Solve using the Square Root Method
First, divide by 3 (which is the same as multiplying by $1/3$), then take the square root:
$$(x + \frac{1}{6})^2 = \frac{7}{36}$$
$$x + \frac{1}{6} = \pm\sqrt{\frac{7}{36}}$$
$$x + \frac{1}{6} = \pm\frac{\sqrt{7}}{6}$$
#### 7. Final Solutions
Isolate $x$ by subtracting $1/6$ from both sides:
$$\mathbf{x = \frac{-1 \pm \sqrt{7}}{6}}$$

* **Exact Solutions:** $x = \frac{-1 + \sqrt{7}}{6}$ and $x = \frac{-1 - \sqrt{7}}{6}$
* **Approximate Solutions:** $x \approx 0.27$ and $x \approx -0.61$
---
### ⚠️ Graphical Interpretation

* **Vertex:** The vertex is found at **$(-1/6, -7/12)$**. (In the form $3(x+1/6)^2 - 7/12 = 0$).
* **Type of Solutions:** These are **Real, Irrational Solutions**. Because 7 is not a perfect square, we must keep the radical.
* **Y-Intercept:** Looking at the original equation, the constant is $-1/2$, so it crosses the y-axis at **$(0, -0.5)$**.
---

> [!abstract] Algebra Takeaway
> This problem highlights why maintaining fractions is superior to decimals in Precalculus. By using $1/36$, the denominator naturally becomes a perfect square ($36$), which makes the square root step clean and allows for an exact radical answer.

### Solving h(x) = -2x² + 5x - 7 (Completing the Square)

This problem is a "Level 5" quadratic because it combines a negative leading coefficient ($a = -2$), an odd middle term ($b = 5$), and a result that leads into **Complex/Imaginary numbers**.

---
#### 1. Set the Function to Zero and Isolate Variable Terms
Replace $h(x)$ with $0$ and move the constant ($-7$) to the right side:
$$-2x^2 + 5x = 7$$
#### 2. Factor out the Leading Coefficient ($a = -2$)
To complete the square, the $x^2$ term must have a coefficient of $1$. Factor $-2$ out of the left side. 
**Note:** This changes the sign of the $x$ term inside the parentheses.
$$-2(x^2 - \frac{5}{2}x) = 7$$
#### 3. Find the "Magic Number"
Focus on the interior of the parentheses ($x^2 - \frac{5}{2}x$):
1.  **Identify $b$:** $-5/2$
2.  **Divide by 2:** $-\frac{5}{2} \cdot \frac{1}{2} = -\frac{5}{4}$
3.  **Square it:** $(-\frac{5}{4})^2 = \mathbf{\frac{25}{16}}$
#### 4. Balance the Equation
**Crucial Step:** When you add $25/16$ inside the parentheses, you are actually adding $-2 \times \frac{25}{16} = \mathbf{-\frac{25}{8}}$ to the left side. You must add **-25/8** to the right side to keep it balanced:
$$-2(x^2 - \frac{5}{2}x + \frac{25}{16}) = 7 - \frac{25}{8}$$
*Convert 7 to 56/8 to subtract:*
$$-2(x^2 - \frac{5}{2}x + \frac{25}{16}) = \frac{31}{8}$$

#### 5. The Factoring Shortcut
The interior factors into $(x + \frac{b}{2})^2$. Using our result from Step 3 ($b/2 = -5/4$):
$$-2(x - \frac{5}{4})^2 = \frac{31}{8}$$
#### 6. Solve using the Square Root Method
First, divide by $-2$ (which is the same as multiplying by $-1/2$), then take the square root:
$$(x - \frac{5}{4})^2 = -\frac{31}{16}$$
$$x - \frac{5}{4} = \pm\sqrt{-\frac{31}{16}}$$
#### 7. Final Solutions (Complex/Imaginary)
Since we are taking the square root of a negative number, we factor out $i$ ($\sqrt{-1}$).
$$x - \frac{5}{4} = \pm \frac{i\sqrt{31}}{4}$$
$$\mathbf{x = \frac{5 \pm i\sqrt{31}}{4}}$$

---
### ⚠️ Graphical Interpretation

* **X-Intercepts:** None. Because the solutions are **Complex**, the parabola never touches or crosses the x-axis.
* **Vertex:** The vertex is found at **$(1.25, -3.875)$**. In vertex form: $h(x) = -2(x - 1.25)^2 - 3.875$.
* **Direction:** Since $a = -2$, the parabola opens **downward**. Because the vertex is below the x-axis and it opens down, it is impossible for it to have real roots.
---
> [!abstract] Algebra Takeaway
> Completing the square is the most visual way to prove why a quadratic has no real roots. When you reach $(x-h)^2 = \text{negative number}$, you can immediately see that no real number squared can result in a negative, confirming that the graph exists entirely above or below the x-axis.

## 2026-March-22 - Proving the Quadratic Formula - Twice (Precalculus - College Algebra 20) :
https://www.youtube.com/watch?v=2BUg_w1Cu9E&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=21
### Proving the Quadratic Formula

In this video, Professor Leonard demonstrates that the **Quadratic Formula** isn't just a random set of symbols to memorize—it is the direct result of performing **Completing the Square** on the general standard form of a quadratic equation.

---
#### 1. Why Prove It?
* **The Connection:** Completing the square is the "engine" inside the quadratic formula. By doing the work once on a general equation ($ax^2 + bx + c = 0$), we create a shortcut that works for every quadratic thereafter. [00:01:45]
* **Efficiency:** While completing the square is essential for understanding the structure of functions (like circles or vertex form), the Quadratic Formula is the faster "best friend" for finding x-intercepts, especially when factoring is too slow or impossible. [00:02:45]

---
#### 2. The Proof: Method 1 (The "Leonard" Way)
This method follows the grouping and balancing technique used in previous lessons.

1.  **Group and Isolate:** Group the $x$ terms and hold off the constant $c$:
    $$a(x^2 + \frac{b}{a}x) + c = 0$$
2.  **Find the Magic Number:** Take half of the middle term ($\frac{b}{2a}$) and square it: $\frac{b^2}{4a^2}$. [00:05:54]
3.  **Balance the Equation:** Add the magic number inside the parentheses. To balance the outside, subtract it—but remember to multiply by the leading coefficient $a$ first: [00:08:31]
    $$a(x^2 + \frac{b}{a}x + \frac{b^2}{4a^2}) - \frac{b^2}{4a} + c = 0$$
4.  **Factor into a Perfect Square:**
    $$a(x + \frac{b}{2a})^2 = \frac{b^2 - 4ac}{4a}$$
5.  **Isolate and Solve:** Divide by $a$, take the square root of both sides (adding $\pm$), and isolate $x$ to reach the final formula: [00:14:10]
    $$\mathbf{x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}}$$
---
#### 3. The Proof: Method 2 (The Traditional Way)
A slightly cleaner algebraic approach that divides by $a$ at the very beginning. [00:15:26]

1.  **Divide Everything by $a$:** This clears the leading coefficient immediately:
    $$x^2 + \frac{b}{a}x + \frac{c}{a} = 0$$
2.  **Move the Constant:** $x^2 + \frac{b}{a}x = -\frac{c}{a}$
3.  **Complete the Square:** Add $\frac{b^2}{4a^2}$ to both sides.
4.  **Common Denominator:** Combine the right side into a single fraction: $\frac{b^2 - 4ac}{4a^2}$. [00:17:38]
5.  **Finish:** Square root both sides and solve for $x$.
---
#### 4. Key Takeaways
* **The Discriminant ($b^2 - 4ac$):** This part of the formula (found under the radical) determines the nature of the roots. If it's negative, you have imaginary solutions. [00:15:01]
* **A Universal Tool:** Because the formula was derived from general variables ($a, b, c$), it will find x-intercepts (zeros/roots) for **any** quadratic, whether the solutions are rational, irrational, or complex. [00:02:18]

> [!abstract] Algebra Takeaway
> The Quadratic Formula is simply the "pre-packaged" result of completing the square. It allows you to skip the tedious balancing steps and jump straight to the solution by simply identifying the coefficients $a, b,$ and $c$.
## 2026-March-23 - Using the Quadratic Formula (Precalculus - College Algebra 21) :
https://www.youtube.com/watch?v=KIWXZVsdpbE&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=22
### Using the Quadratic Formula

This video focuses on the practical application of the **Quadratic Formula**. Professor Leonard explains that while it is derived from "Completing the Square," it serves as a universal fail-safe for finding x-intercepts when other methods (like factoring) are too difficult. [00:00:34]

---
#### 1. Preparation: The "Leonard Setup"
To avoid the most common sign errors, always prepare your quadratic equation ($ax^2 + bx + c = 0$) following these rules:
* **Set to Zero:** Ensure everything is on one side of the equation. [00:02:04]
* **Standard Order:** Exponents must decrease ($x^2$, then $x$, then constant).
* **First Term Positive:** If $a$ is negative, multiply the entire equation by $-1$. This prevents dividing by a negative number later, which is where 90% of student errors occur. [00:02:40]
* **Kill the Fractions:** If the equation has fractions, multiply everything by the **LCD** before starting. "Never plug fractions into the quadratic formula." [00:19:42]
---
#### 2. The "Blank Space" Method
Professor Leonard recommends writing the formula with empty parentheses for every variable before plugging in numbers. This maintains signs and operations: [00:05:11]

$$x = \frac{-(\quad) \pm \sqrt{(\quad)^2 - 4(\quad)(\quad)}}{2(\quad)}$$
---
#### 3. Analyzing the Discriminant ($b^2 - 4ac$)
The value inside the square root tells you exactly what the graph of the parabola looks like before you even finish the math: [00:08:12]

| Discriminant Value | Resulting Solutions | Graphical Meaning |
| :--- | :--- | :--- |
| **Positive** ($>0$) | 2 Real Solutions | The parabola crosses the x-axis twice. |
| **Zero** ($=0$) | 1 Real Solution | The vertex "bounces" or sits exactly on the x-axis. |
| **Negative** ($<0$) | 2 Complex Solutions | The parabola never touches the x-axis (floats above/below). |

---
#### 4. Simplification & Exact vs. Approximate
* **Exact Form:** Keeping the solution with the radical (e.g., $\sqrt{17}$). This contains "all the information" of the number. [00:33:19]
* **Approximate Form:** Using a calculator to get a decimal. Leonard warns that rounding "cuts off a portion of the number" since irrational roots go on forever. [00:33:40]
* **Reducing Fractions:** You can only simplify the final fraction if the denominator divides **all** terms in the numerator. [00:17:18]
---

> [!abstract] Algebra Takeaway
> The Quadratic Formula is your "best friend" because it works 100% of the time. While the Square Root method and Factoring only work for specific cases, the formula handles rational, irrational, and complex numbers equally well.
### Solving f(x) = 3x² - 5x + 1 (Quadratic Formula)

To find the **x-intercepts** (zeros), we use the Quadratic Formula. This method is the "universal key" for solving any quadratic equation that cannot be easily factored.

---
#### 1. Identify the Coefficients
From the standard form $ax^2 + bx + c = 0$:
* **a = 3**
* **b = -5**
* **c = 1**
#### 2. The Quadratic Formula Setup
Professor Leonard recommends writing the formula with empty parentheses first to avoid sign errors:
$$x = \frac{-(\quad) \pm \sqrt{(\quad)^2 - 4(\quad)(\quad)}}{2(\quad)}$$

Plug in the values:
$$x = \frac{-(-5) \pm \sqrt{(-5)^2 - 4(3)(1)}}{2(3)}$$
#### 3. Simplify the Discriminant ($b^2 - 4ac$)
The value under the radical determines the nature of the roots:
* $(-5)^2 = 25$
* $4(3)(1) = 12$
* $25 - 12 = \mathbf{13}$

Since $13$ is positive but not a perfect square, we will have **two real, irrational solutions**.
#### 4. Solve for x
$$x = \frac{5 \pm \sqrt{13}}{6}$$

---
#### 5. Exact vs. Approximate Solutions
In Precalculus, the **Exact Form** is typically required for your notes.

* **Exact Solutions:** $$x = \frac{5 + \sqrt{13}}{6} \quad \text{and} \quad x = \frac{5 - \sqrt{13}}{6}$$
* **Approximate Solutions (Decimal):**
  Using $\sqrt{13} \approx 3.606$:
  $$x \approx \frac{5 + 3.606}{6} \approx \mathbf{1.43}$$
  $$x \approx \frac{5 - 3.606}{6} \approx \mathbf{0.23}$$
---
### ⚠️ Graphical Interpretation

* **X-Intercepts:** The graph crosses the x-axis at approximately **(1.43, 0)** and **(0.23, 0)**.
* **Y-Intercept:** Looking at the original equation, the constant is $+1$, so it crosses the y-axis at **(0, 1)**.
* **Direction:** Since $a=3$ (positive), the parabola opens **upward**.
---
> [!abstract] Algebra Takeaway
> Because 13 is not a perfect square, this quadratic could not have been solved using the Diamond Method or Factoring by Grouping. The Quadratic Formula (or Completing the Square) is required whenever the "magic numbers" are irrational.

### Solving g(x) = 3x(x + 2) - 1 (Quadratic Formula)

To solve this for the **x-intercepts** (zeros), we must first convert the function into **Standard Form** ($ax^2 + bx + c = 0$).

---
#### 1. Expand to Standard Form
Distribute the $3x$ and set the function to zero:
$$0 = 3x(x) + 3x(2) - 1$$
$$0 = 3x^2 + 6x - 1$$
#### 2. Identify the Coefficients
* **a = 3**
* **b = 6**
* **c = -1**
#### 3. The Quadratic Formula Setup
Using Professor Leonard's "Parentheses Method" to ensure signs are handled correctly:
$$x = \frac{-(6) \pm \sqrt{(6)^2 - 4(3)(-1)}}{2(3)}$$
#### 4. Simplify the Discriminant ($b^2 - 4ac$)
Calculate the value under the radical:
* $(6)^2 = 36$
* $-4(3)(-1) = +12$
* $36 + 12 = \mathbf{48}$

Since $48$ is positive, we will have **two real, irrational solutions**.
#### 5. Solve and Simplify the Radical
$$x = \frac{-6 \pm \sqrt{48}}{6}$$

Simplify $\sqrt{48}$ by finding the largest perfect square factor ($16 \times 3$):
$$\sqrt{48} = \sqrt{16 \cdot 3} = 4\sqrt{3}$$
$$x = \frac{-6 \pm 4\sqrt{3}}{6}$$
#### 6. Final Reductions
Factor out a $2$ from the numerator to simplify the fraction:
$$x = \frac{2(-3 \pm 2\sqrt{3})}{6}$$
$$\mathbf{x = \frac{-3 \pm 2\sqrt{3}}{3}}$$
---
### ⚠️ Graphical Interpretation

* **Exact Solutions:** $x = \frac{-3 + 2\sqrt{3}}{3}$ and $x = \frac{-3 - 2\sqrt{3}}{3}$
* **Approximate Solutions:** $x \approx 0.15$ and $x \approx -2.15$
* **Vertex:** Using $h = -b/2a$, the vertex is at $x = -6/6 = \mathbf{-1}$. Plugging $-1$ into the original function gives $g(-1) = 3(-1)(-1+2) - 1 = \mathbf{-4}$.
* **Vertex Point:** **$(-1, -4)$**
---
> [!abstract] Algebra Takeaway
> Always simplify your radical ($4\sqrt{3}$) before trying to reduce the final fraction. Remember that a denominator can only divide into the numerator if it divides into **every** term. In this case, $6$ divides into both $-6$ and $4$ (by a factor of $2$), resulting in our final simplified denominator of $3$.

### Solving h(x) = 3x² + x - 1/2 (Quadratic Formula)

To find the **x-intercepts** (zeros), we use the Quadratic Formula. This problem is unique because it contains a fractional constant ($c = -1/2$). Following Professor Leonard's advice, we will "kill the fraction" first to make the substitution cleaner.

---
#### 1. Prepare the Equation (Eliminate Fractions)
Set the function to zero and multiply the entire equation by the LCD (**2**) to remove the fraction:
$$2 \cdot (3x^2 + x - \frac{1}{2} = 0)$$
$$6x^2 + 2x - 1 = 0$$
#### 2. Identify the New Coefficients
* **a = 6**
* **b = 2**
* **c = -1**
#### 3. The Quadratic Formula Setup
Using the "Parentheses Method" to ensure signs are handled correctly:
$$x = \frac{-(2) \pm \sqrt{(2)^2 - 4(6)(-1)}}{2(6)}$$
#### 4. Simplify the Discriminant ($b^2 - 4ac$)
Calculate the value under the radical:
* $(2)^2 = 4$
* $-4(6)(-1) = +24$
* $4 + 24 = \mathbf{28}$

Since **28** is positive, we will have **two real, irrational solutions**.
#### 5. Solve and Simplify the Radical
$$x = \frac{-2 \pm \sqrt{28}}{12}$$

Simplify $\sqrt{28}$ by finding the largest perfect square factor ($4 \times 7$):
$$\sqrt{28} = \sqrt{4 \cdot 7} = 2\sqrt{7}$$
$$x = \frac{-2 \pm 2\sqrt{7}}{12}$$
#### 6. Final Reductions
Factor out a **2** from the numerator to simplify the fraction:
$$x = \frac{2(-1 \pm \sqrt{7})}{12}$$
$$\mathbf{x = \frac{-1 \pm \sqrt{7}}{6}}$$
---
### ⚠️ Graphical Interpretation

* **Exact Solutions:** $x = \frac{-1 + \sqrt{7}}{6}$ and $x = \frac{-1 - \sqrt{7}}{6}$
* **Approximate Solutions:** $x \approx 0.27$ and $x \approx -0.61$
* **Vertex:** Using $h = -b/2a$ from our original coefficients ($a=3, b=1$), the vertex x-coordinate is $x = -1/6$. 
* **Y-Intercept:** The original constant is $-1/2$, so the graph crosses the y-axis at **$(0, -0.5)$**.
---

> [!abstract] Algebra Takeaway
> Notice that by multiplying the equation by 2 in Step 1, we made the arithmetic much easier. If we had plugged $c = -1/2$ directly into the formula, we would have dealt with "fractions inside of a square root," which increases the chance of a calculation error. Both paths lead to the same final answer: $\frac{-1 \pm \sqrt{7}}{6}$.

### Solving f(x) = 1/8x² - 1/4x - 2 (Quadratic Formula)

To solve this for the **x-intercepts** (zeros), we use the Quadratic Formula. This problem contains several fractions. To avoid "fractions inside of a square root," we will follow Professor Leonard's advice and "kill the fractions" first.

---
#### 1. Prepare the Equation (Eliminate Fractions)
Set the function to zero and multiply the entire equation by the **Least Common Denominator (LCD)**, which is **8**:
$$8 \cdot \left( \frac{1}{8}x^2 - \frac{1}{4}x - 2 = 0 \right)$$
$$x^2 - 2x - 16 = 0$$
#### 2. Identify the New Coefficients
* **a = 1**
* **b = -2**
* **c = -16**
#### 3. The Quadratic Formula Setup
Using the "Parentheses Method" to ensure signs (especially for $-b$ and $c$) are handled correctly:
$$x = \frac{-(-2) \pm \sqrt{(-2)^2 - 4(1)(-16)}}{2(1)}$$
#### 4. Simplify the Discriminant ($b^2 - 4ac$)
Calculate the value under the radical:
* $(-2)^2 = 4$
* $-4(1)(-16) = +64$
* $4 + 64 = \mathbf{68}$

Since **68** is positive but not a perfect square, we will have **two real, irrational solutions**.
#### 5. Solve and Simplify the Radical
$$x = \frac{2 \pm \sqrt{68}}{2}$$
Simplify $\sqrt{68}$ by finding the largest perfect square factor ($4 \times 17$):
$$\sqrt{68} = \sqrt{4 \cdot 17} = 2\sqrt{17}$$
$$x = \frac{2 \pm 2\sqrt{17}}{2}$$#### 6. Final Reductions
Factor out a **2** from the numerator to simplify the fraction:
$$x = \frac{2(1 \pm \sqrt{17})}{2}$$
$$\mathbf{x = 1 \pm \sqrt{17}}$$
---
### ⚠️ Graphical Interpretation

* **Exact Solutions:** $x = 1 + \sqrt{17}$ and $x = 1 - \sqrt{17}$
* **Approximate Solutions:** $x \approx 5.12$ and $x \approx -3.12$
* **Vertex:** Using $h = -b/2a$ from our simplified coefficients ($x^2 - 2x - 16$), the vertex x-coordinate is $x = 1$. 
* **Y-Intercept:** The original constant is $-2$, so the graph crosses the y-axis at **$(0, -2)$**.
---

> [!abstract] Algebra Takeaway
> Always look for the LCD before starting the Quadratic Formula. By transforming the coefficients into integers ($1, -2, -16$), you reduce the problem to a simple arithmetic exercise and avoid complex fraction manipulation inside the radical.

### Solving f(x) = 9x² - 6x + 1 (Quadratic Formula)

To find the **x-intercepts** (zeros), we use the Quadratic Formula. This specific problem is an example of a **Perfect Square Trinomial**, which results in a unique discriminant value.

---
#### 1. Identify the Coefficients
From the standard form $ax^2 + bx + c = 0$:
* **a = 9**
* **b = -6**
* **c = 1**
* #### 2. The Quadratic Formula Setup
Using the "Parentheses Method" to ensure signs are handled correctly:
$$x = \frac{-(-6) \pm \sqrt{(-6)^2 - 4(9)(1)}}{2(9)}$$
#### 3. Simplify the Discriminant ($b^2 - 4ac$)
Calculate the value under the radical:
* $(-6)^2 = 36$
* $4(9)(1) = 36$
* $36 - 36 = \mathbf{0}$
Since the discriminant is **zero**, we will have exactly **one real solution** (a double root).
#### 4. Solve for x
Since the $\pm \sqrt{0}$ term disappears:
$$x = \frac{6 \pm 0}{18}$$
$$x = \frac{6}{18}$$
#### 5. Final Solution
Simplify the fraction by dividing both numerator and denominator by 6:
$$\mathbf{x = \frac{1}{3}}$$
---
### ⚠️ Graphical Interpretation

* **X-Intercept:** The graph touches the x-axis at exactly **$(1/3, 0)$**.
* **Vertex:** Because there is only one solution, the vertex is located at the x-intercept: **$(1/3, 0)$**.
* **Y-Intercept:** The original constant is $+1$, so the graph crosses the y-axis at **$(0, 1)$**.
* **Type of Solution:** This is a **Rational Solution**. It is a "double root," meaning the factor $(x - 1/3)$ appears twice in the factored form: $9(x - 1/3)^2 = 0$.
---
> [!abstract] Algebra Takeaway
> When the discriminant ($b^2 - 4ac$) equals zero, it is a mathematical "red flag" that the quadratic is a Perfect Square Trinomial. In these cases, you don't actually need the full formula—you could have factored it as $(3x - 1)^2 = 0$ to reach the same result faster.

### Solving g(x) = -4x² - x - 4 (Quadratic Formula)

This problem is a "Level 5" quadratic because it features a negative leading coefficient ($a = -4$) and will result in **Complex/Imaginary** solutions. We will follow Professor Leonard's advice to "clean" the equation before plugging in the values.

---
#### 1. Prepare the Equation (The "Leonard Setup")
To avoid dividing by a negative number later, we set the function to zero and multiply the entire equation by **$-1$**:
$$-1 \cdot (-4x^2 - x - 4 = 0)$$
$$4x^2 + x + 4 = 0$$
#### 2. Identify the New Coefficients
* **a = 4**
* **b = 1**
* **c = 4**
#### 3. The Quadratic Formula Setup
Using the "Parentheses Method" to protect the signs:
$$x = \frac{-(1) \pm \sqrt{(1)^2 - 4(4)(4)}}{2(4)}$$
#### 4. Simplify the Discriminant ($b^2 - 4ac$)
Calculate the value under the radical:
* $(1)^2 = 1$
* $4(4)(4) = 64$
* $1 - 64 = \mathbf{-63}$

Since the discriminant is **negative**, we will have **two complex (imaginary) solutions**.
#### 5. Solve and Simplify the Radical
When the value under the radical is negative, we factor out $i$ ($\sqrt{-1}$):
$$x = \frac{-1 \pm \sqrt{-63}}{8}$$

Simplify $\sqrt{63}$ by finding the largest perfect square factor ($9 \times 7$):
$$\sqrt{63} = \sqrt{9 \cdot 7} = 3\sqrt{7}$$
$$x = \frac{-1 \pm 3i\sqrt{7}}{8}$$
#### 6. Final Solution
Since $8$ does not divide evenly into both $1$ and $3$, the fraction is already in its simplest form.
$$\mathbf{x = \frac{-1 \pm 3i\sqrt{7}}{8}}$$
---
### ⚠️ Graphical Interpretation

* **X-Intercepts:** None. The solutions are **Complex**, meaning the parabola does not touch the x-axis.
* **Vertex:** Using $h = -b/2a$ from our original coefficients ($a=-4, b=-1$), the vertex x-coordinate is $x = -1/8$.
* **Direction:** Since the original $a = -4$ (negative), the parabola opens **downward**. Because the vertex is below the x-axis and it opens down, the graph exists entirely in quadrants III and IV.
---
> [!abstract] Algebra Takeaway
> When you encounter a negative discriminant, do not stop. Simply "pull out" the $i$ to show that the solutions exist in the complex number plane. In physics and engineering, these imaginary roots often represent things like dampened oscillations or rotations.

## 2026-March-24 - Finding Intersections of Functions (Precaluclus - College Algebra 22) :
https://www.youtube.com/watch?v=2cXEuUazjCc&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=26
### Finding Intersections of Functions

Finding where two functions intersect means finding the specific points $(x, y)$ that they both share. Professor Leonard emphasizes that "intersection" is just another way of saying two functions have the same input and same output at the same time.

---
#### 1. The Core Procedure
To find the intersection of any two functions, $f(x)$ and $g(x)$:
1.  **Set them equal:** $f(x) = g(x)$.
2.  **Solve for $x$:** This gives you the x-coordinates of the intersection points.
3.  **Find the $y$-coordinates:** Plug your $x$ values back into *either* original function to find the corresponding $y$. 
    * *Pro-tip:* Plug the $x$ into **both** functions to check your work. If the $y$ values aren't identical, you made an algebra error. [00:05:17]
---
#### 2. Geometric Interpretation: Shifting the Parabola
Professor Leonard provides a unique way to visualize the algebra:
* When you set $x^2 + 6x + 3 = 3$ and subtract $3$ to get $x^2 + 6x = 0$, you are essentially shifting the original parabola down 3 units. [00:02:46]
* Finding the **x-intercepts** of this new, shifted function is mathematically identical to finding the **points of intersection** of the original two functions. [00:03:26]
---
#### 3. Common Intersection Scenarios

| Scenario | Geometric Visualization | Algebraic Strategy |
| :--- | :--- | :--- |
| **Parabola & Horizontal Line** | A "U" shape crossed by a flat line. | Set quadratic equal to the constant; use factoring or square root method. |
| **Parabola & Linear Line** | A "U" shape crossed by a slanted line. | Set equal; move all terms to one side to form a new quadratic. [00:08:41] |
| **Two Parabolas** | Two "U" shapes (e.g., one narrow, one wide). | Set equal; subtract terms to reduce it to a single quadratic equation. [00:14:20] |

---
#### 4. Solving the Resulting Equation
Once the functions are set equal and moved to one side ($... = 0$), use the hierarchy of solving quadratics:
1.  **GCF Factoring:** Always check for a Greatest Common Factor first. [00:04:01]
2.  **Standard Factoring:** Look for numbers that multiply to $c$ and add to $b$.
3.  **Quadratic Formula:** Use this if the equation is not factorable. [00:15:26]
    * *Note:* If you use the Quadratic Formula, keep your answers in **exact form** (radicals) unless decimals are specifically requested. [00:16:56]
---
### ⚠️ Common Pitfalls
* **Stopping at $x$:** An intersection is a **point**. You must always find the $y$-value to complete the ordered pair $(x, y)$. [00:01:18]
* **Sign Errors during Move:** When moving terms from $g(x)$ over to $f(x)$, remember to flip the signs of every term you move.
* **First Term Positive:** Professor Leonard strongly recommends moving terms so that the $x^2$ coefficient stays positive. This makes factoring much easier. [00:09:00]
---
> [!abstract] Algebra Takeaway
> Setting $f(x) = g(x)$ is a universal tool. While this lesson focuses on quadratics, this same logic applies later in math to intersections of logarithms, exponentials, and trigonometric functions.

### Finding the Intersection of f(x) = x² + 6x + 3 and g(x) = 3

To find the intersection points, we must determine the $(x, y)$ coordinates where both functions share the same input and output. Following Professor Leonard's method, we set the functions equal to each other.

---
#### 1. Set the Functions Equal
Since we want to find where $f(x) = g(x)$:
$$x^2 + 6x + 3 = 3$$
#### 2. Move All Terms to One Side
Subtract $3$ from both sides to set the equation to zero. Notice that the constant terms cancel out:
$$x^2 + 6x = 0$$
#### 3. Solve for x (Factoring)
Since there is no constant term, we solve by factoring out the **Greatest Common Factor (GCF)**, which is $x$:
$$x(x + 6) = 0$$

Set each factor to zero:
* $x = 0$
* $x + 6 = 0 \Rightarrow \mathbf{x = -6}$
#### 4. Find the Corresponding y-Coordinates
To find the full intersection points, plug the $x$ values back into either original function. Since $g(x) = 3$ is a horizontal line, the $y$-value will be $3$ for any $x$ on that line.

* **For $x = 0$:** $g(0) = 3 \Rightarrow \mathbf{(0, 3)}$
* **For $x = -6$:** $g(-6) = 3 \Rightarrow \mathbf{(-6, 3)}$

*(Self-Check: $f(0) = 0^2 + 6(0) + 3 = 3$. Correct!)*

---
### ⚠️ Graphical Interpretation

* **The Intersection Points:** The parabola $f(x)$ crosses the horizontal line $g(x)$ at **$(0, 3)$** and **$(-6, 3)$**.
* **The "Shift" Visual:** Algebraically, solving $x^2 + 6x = 0$ is the same as looking at a new parabola that has been shifted down 3 units, where the intersections have become the new x-intercepts.
* **Symmetry:** Because the $y$-values are the same ($3$), these two points are symmetric across the axis of symmetry ($x = -3$).
---

> [!abstract] Algebra Takeaway
> When intersecting a quadratic with a horizontal line, the algebra often simplifies significantly. If the constants cancel out (as they did here), factoring out the $x$ is much faster than using the Quadratic Formula or Completing the Square.

### Finding the Intersection of f(x) = -2x² + 1 and g(x) = 3x + 2

To find the intersection points, we must determine the $(x, y)$ coordinates where the parabola $f(x)$ and the line $g(x)$ meet. This occurs when $f(x) = g(x)$.

---
#### 1. Set the Functions Equal
Set the quadratic expression equal to the linear expression:
$$-2x^2 + 1 = 3x + 2$$

#### 2. Move All Terms to One Side (The "Leonard Setup")
Professor Leonard recommends moving terms so that the $x^2$ coefficient becomes **positive**. Move all terms from the left side to the right side:
$$0 = 2x^2 + 3x + 2 - 1$$
$$2x^2 + 3x + 1 = 0$$
#### 3. Solve for x (Factoring)
Since this is a "Level 2" quadratic ($a \neq 1$), we check if it is factorable using the **Diamond Method** (AC Method):
1.  **Multiply $a \cdot c$:** $2 \cdot 1 = \mathbf{2}$
2.  **Find factors of 2 that add to 3 ($b$):** $\mathbf{2}$ and $\mathbf{1}$
3.  **Rewrite and Group:**
    $$2x^2 + 2x + 1x + 1 = 0$$
    $$2x(x + 1) + 1(x + 1) = 0$$
    $$(2x + 1)(x + 1) = 0$$

Set each factor to zero:
* $x + 1 = 0 \Rightarrow \mathbf{x = -1}$
* $2x + 1 = 0 \Rightarrow \mathbf{x = -1/2}$
#### 4. Find the Corresponding y-Coordinates
Plug the $x$ values back into the **simpler** function (the linear line $g(x) = 3x + 2$) to find the $y$-values.

* **For $x = -1$:**
    $g(-1) = 3(-1) + 2 = -3 + 2 = \mathbf{-1}$
    **Point 1: $(-1, -1)$**
* **For $x = -1/2$:**
    $g(-1/2) = 3(-1/2) + 2 = -1.5 + 2 = \mathbf{0.5}$
    **Point 2: $(-0.5, 0.5)$**

*(Self-Check: $f(-1) = -2(-1)^2 + 1 = -2 + 1 = -1$. Both match!)*

---
### ⚠️ Graphical Interpretation

* **The Intersection Points:** The parabola and the line cross at **$(-1, -1)$** and **$(-0.5, 0.5)$**.
* **The Quadratic Nature:** Because the resulting equation $2x^2 + 3x + 1 = 0$ had a positive discriminant ($b^2 - 4ac = 1$), we knew there would be exactly two points of intersection.
* **Relative Position:** Since $f(x)$ has a negative $a$, it opens downward. The line $g(x)$ has a positive slope, cutting through the parabola from the bottom-left toward the top-right.
---

> [!abstract] Algebra Takeaway
> When intersecting a parabola and a line, always move the terms to the side that makes the $x^2$ term positive. This makes the factoring step (or the Quadratic Formula) much less prone to sign errors.

### Finding the Intersection of f(x) = x² - x + 1 and g(x) = 2x² - 3x - 14

To find the intersection points of two parabolas, we determine the $(x, y)$ coordinates where they share the same input and output. This occurs when $f(x) = g(x)$.

---
#### 1. Set the Functions Equal
Set the two quadratic expressions equal to each other:
$$x^2 - x + 1 = 2x^2 - 3x - 14$$
#### 2. Move All Terms to One Side
To keep the $x^2$ coefficient positive (following Professor Leonard's "Leonard Setup"), move all terms from the left side to the right side:
$$0 = (2x^2 - x^2) + (-3x + x) + (-14 - 1)$$
$$x^2 - 2x - 15 = 0$$
#### 3. Solve for x (Factoring)
This is a standard trinomial where $a=1$. We need two numbers that:
* **Multiply to:** $-15$
* **Add to:** $-2$

The numbers are **$-5$** and **$3$**.
$$(x - 5)(x + 3) = 0$$

Set each factor to zero:
* $x - 5 = 0 \Rightarrow \mathbf{x = 5}$
* $x + 3 = 0 \Rightarrow \mathbf{x = -3}$
#### 4. Find the Corresponding y-Coordinates
Plug the $x$ values back into the simpler function ($f(x) = x^2 - x + 1$) to find the $y$-values.

* **For $x = 5$:**
    $$f(5) = (5)^2 - (5) + 1$$
    $$f(5) = 25 - 5 + 1 = \mathbf{21}$$
    **Point 1: $(5, 21)$**

* **For $x = -3$:**
    $$f(-3) = (-3)^2 - (-3) + 1$$
    $$f(-3) = 9 + 3 + 1 = \mathbf{13}$$
    **Point 2: $(-3, 13)$**

*(Self-Check: $g(5) = 2(25) - 3(5) - 14 = 50 - 15 - 14 = 21$. Both match!)*

---
### ⚠️ Graphical Interpretation

* **The Intersection Points:** The two parabolas cross at **$(5, 21)$** and **$(-3, 13)$**.
* **Shape Difference:** $g(x)$ has a leading coefficient of $2$, meaning it is narrower than $f(x)$, which has a leading coefficient of $1$. Because they are both positive, they both open upward.
* **The "New" Quadratic:** Algebraically, solving $x^2 - 2x - 15 = 0$ is like looking at a third parabola. Its x-intercepts ($5$ and $-3$) tell us exactly where the original two functions were at the same "height."
---

> [!abstract] Algebra Takeaway
> When intersecting two quadratics, you are essentially creating a third quadratic equation that represents the "difference" between them. Solving for the zeros of that difference equation provides the x-coordinates for the intersection of the original two graphs.

## 2026-March-25 - Using Substitutions to Solve Equations (Precalculus - College Algebra 23) :
https://www.youtube.com/watch?v=P8uoP-JFj54&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=24
### Using Substitutions to Solve Equations (Professor Leonard)

Substitution (often called **u-substitution**) is a "re-skinning" technique. It allows you to take a complex equation that is "quadratic in form" and transform it into a simple quadratic equation that you already know how to factor or solve.

---
#### 1. When Can You Use Substitution?
A substitution will work if the equation follows a specific pattern:
* **Three Terms:** Usually set equal to zero.
* **The "2x" Exponent Rule:** The exponent of the leading term must be exactly **double** the exponent of the middle term. [00:10:35]
    * *Example:* $x^4$ and $x^2$ (since $4 = 2 \times 2$).
    * *Example:* $x^{2/3}$ and $x^{1/3}$ (since $2/3 = 2 \times 1/3$). [00:23:59]
    * *Example:* $x^{-2}$ and $x^{-1}$ (since $-2 = 2 \times -1$). [00:40:15]

---
#### 2. The "Breadcrumb" Method (Step-by-Step)
Professor Leonard compares this to the story of Hansel and Gretel: you leave a trail of "u" breadcrumbs to get through the forest, but you must follow them back to find your way home to "x." [00:03:01]

1.  **Identify $u$:** Let $u$ equal the middle variable part (e.g., $u = x^2$ or $u = (3x+4)$).
2.  **Rewrite:** Substitute $u$ into the equation to create a standard quadratic: $au^2 + bu + c = 0$. [00:03:32]
3.  **Solve for $u$:** Factor the equation or use the Quadratic Formula to find the numerical values of $u$.
4.  **Substitute Back:** Replace $u$ with the original $x$-expression. **This is the most critical step.** [00:15:04]
5.  **Final Solve:** Solve the resulting mini-equations for the original variable.
---
#### 3. Handling Different "Back-Substitutions"
The final step depends entirely on what $u$ was originally representing:

| If $u$ equals... | Then to solve for the original variable... | Note |
| :--- | :--- | :--- |
| **$x^2$** | Take the Square Root ($\pm$) | Use $i$ for negative results. [00:15:44] |
| **$x^{1/3}$** | Cube both sides | Cube roots can equal negative numbers. [00:27:37] |
| **$x^{1/2}$ ($\sqrt{x}$)** | Square both sides | **Caution:** A square root cannot equal a negative. Discard these. [00:32:06] |
| **$x^{-1}$ ($1/x$)** | Take the reciprocal | Simply "flip" the fraction of your $u$ value. [00:44:05] |

---
#### 4. Critical Warnings & Tips

* **The "Dummy" Variable:** Always use a different letter (typically $u$) to stay organized and avoid confusing $u$-solutions with $x$-solutions. [00:02:32]
* **Don't Stop Too Soon:** Finding $u = 5$ is not the end. You haven't finished until you solve for the variable given in the original problem. [00:06:57]
* **Check for Extraneous Solutions:** When squaring both sides (like with $x^{1/2}$), you might create a "false friend" solution. Always verify if the original root could actually equal that number. [00:33:10]
* **Negative Leading Terms:** If the $x^{2n}$ term is negative, multiply the whole equation by $-1$ first to make factoring easier. [00:39:14]
---

> [!abstract] Algebra Takeaway
> Substitution is a universal tool. It doesn't just work for polynomials; it works for any expression where one part is the square of another. By calling that part "$u$," you hide the complexity and reveal the simple quadratic structure underneath.

### Solving g(x) = (3x + 4)² - 6(3x + 4) + 9 (u-Substitution)

This equation is "quadratic in form" because the first term is the square of the middle binomial. By using **u-substitution**, we can simplify the expression into a basic quadratic and solve for $x$.

---
#### 1. Identify and Substitute "u"
Let $u$ represent the repeating binomial part of the equation:
**Let $u = (3x + 4)$**

Now, rewrite the equation in terms of $u$:
$$u^2 - 6u + 9 = 0$$
#### 2. Solve the Quadratic for "u"
This is a **Perfect Square Trinomial**. We need two numbers that:
* **Multiply to:** $9$
* **Add to:** $-6$

The numbers are $-3$ and $-3$.
$$(u - 3)(u - 3) = 0 \quad \text{or} \quad (u - 3)^2 = 0$$

Set the factor to zero:
$$u - 3 = 0 \Rightarrow \mathbf{u = 3}$$
#### 3. Back-Substitute to Solve for "x"
Now, follow the "breadcrumbs" back to the original variable by replacing $u$ with $(3x + 4)$:
$$3x + 4 = 3$$

Solve for $x$:
1. Subtract 4 from both sides: $3x = -1$
2. Divide by 3: $\mathbf{x = -\frac{1}{3}}$
---
### ⚠️ Graphical Interpretation

* **The Solution:** There is only **one real solution** ($x = -1/3$).
* **The Root Type:** Because the discriminant of the $u$-quadratic was zero ($(-6)^2 - 4(1)(9) = 0$), the original function $g(x)$ has its vertex sitting exactly on the x-axis.
* **Vertex Point:** **$(-1/3, 0)$**
---
> [!abstract] Algebra Takeaway
> Without substitution, you would have to expand $(3x+4)^2$, distribute the $-6$, and combine like terms before solving. Substitution allowed us to see the "Perfect Square" structure immediately, saving time and reducing the risk of distribution errors.

### Solving f(x) = 3x⁴ - 2x² - 1 (u-Substitution)

This equation is "quadratic in form" because the exponent of the first term ($4$) is exactly double the exponent of the middle term ($2$). We can use **u-substitution** to temporarily turn this quartic equation into a standard quadratic.

---
#### 1. Identify and Substitute "u"
We let $u$ represent the middle variable part:
**Let $u = x^2$** (which means $u^2 = x^4$)

Now, rewrite the equation in terms of $u$:
$$3u^2 - 2u - 1 = 0$$
#### 2. Solve the Quadratic for "u"
We check for factors of $a \cdot c$ ($3 \times -1 = -3$) that add to $b$ ($-2$):
* The numbers are **$-3$** and **$1$**.

Using grouping:
1. $3u^2 - 3u + 1u - 1 = 0$
2. $3u(u - 1) + 1(u - 1) = 0$
3. $(3u + 1)(u - 1) = 0$

Set each factor to zero:
* $3u + 1 = 0 \Rightarrow \mathbf{u = -1/3}$
* $u - 1 = 0 \Rightarrow \mathbf{u = 1}$
#### 3. Back-Substitute to Solve for "x"
Now, follow the "breadcrumbs" back to the original variable by replacing $u$ with $x^2$.

**Case 1: $x^2 = 1$**
Take the square root of both sides:
$$x = \pm \sqrt{1}$$
$$\mathbf{x = 1, \quad x = -1}$$

**Case 2: $x^2 = -1/3$**
Take the square root of both sides. Since the value is negative, we use $i$:
$$x = \pm \sqrt{-1/3}$$
$$x = \pm \frac{i}{\sqrt{3}}$$
Rationalize the denominator:
$$\mathbf{x = \pm \frac{i\sqrt{3}}{3}}$$
---
### ⚠️ Graphical Interpretation

* **Real Zeros:** The graph of $f(x)$ crosses the x-axis at **$(1, 0)$** and **$(-1, 0)$**.
* **Complex Zeros:** The other two solutions are imaginary, meaning they do not appear on a standard 2D coordinate plane.
* **Function Type:** This is a **Quartic** function (degree 4). It has 4 total roots (2 real, 2 imaginary) as predicted by the Fundamental Theorem of Algebra.
---

> [!abstract] Algebra Takeaway
> When solving higher-order equations like $x^4$, the substitution method is only half the battle. The real work happens during the back-substitution step where you must apply the Square Root Property. Remember to always include the $\pm$ and watch for negative radicands that produce $i$.

### Solving $f(x) = x^(2/3) - 7x^(1/3) + 10 = 0$ (u-Substitution)

This equation is "quadratic in form" because the leading exponent ($2/3$) is exactly double the middle exponent ($1/3$). By using **u-substitution**, we can simplify the fractional exponents into a standard quadratic.

---
#### 1. Identify and Substitute "u"
We let $u$ represent the middle variable part:
**Let $u = x^{1/3}$** (which is the same as $\sqrt[3]{x}$)

Now, rewrite the equation in terms of $u$:
$$u^2 - 7u + 10 = 0$$
#### 2. Solve the Quadratic for "u"
We need two numbers that:
* **Multiply to:** $10$
* **Add to:** $-7$

The numbers are **$-5$** and **$-2$**.
$$(u - 5)(u - 2) = 0$$
Set each factor to zero:
* $u - 5 = 0 \Rightarrow \mathbf{u = 5}$
* $u - 2 = 0 \Rightarrow \mathbf{u = 2}$
#### 3. Back-Substitute to Solve for "x"
Follow the "breadcrumbs" back to the original variable by replacing $u$ with $x^{1/3}$.

**Case 1: $x^{1/3} = 5$**
To isolate $x$, perform the inverse operation: **cube both sides**.
$$(x^{1/3})^3 = (5)^3$$
$$\mathbf{x = 125}$$

**Case 2: $x^{1/3} = 2$**
Cube both sides:
$$(x^{1/3})^3 = (2)^3$$
$$\mathbf{x = 8}$$

---
### ⚠️ Graphical Interpretation

* **Real Zeros:** The graph of $f(x)$ crosses the x-axis at **$(8, 0)$** and **$(125, 0)$**.
* **Domain:** Unlike square roots ($x^{1/2}$), cube roots ($x^{1/3}$) are defined for all real numbers, so we don't need to worry about negative $x$ values being excluded from the domain in this specific step.
* **Verification:**
    * $f(8) = (8)^{2/3} - 7(8)^{1/3} + 10 = 4 - 7(2) + 10 = 0$. (Check!)
    * $f(125) = (125)^{2/3} - 7(125)^{1/3} + 10 = 25 - 7(5) + 10 = 0$. (Check!)

---

> [!abstract] Algebra Takeaway
> Fractional exponents can look intimidating, but the "2-to-1" ratio rule still applies. Once you solve for $u$, simply use the denominator of the fractional exponent as the power for both sides (e.g., if you have a $1/3$ power, cube both sides; if you have a $1/4$ power, raise both sides to the 4th).

### Solving g(x) = x + √x - 20 = 0 (u-Substitution)

This equation is "quadratic in form" because the exponent of the first term ($x^1$) is exactly double the exponent of the middle term ($\sqrt{x} = x^{1/2}$). By using **u-substitution**, we can transform this radical equation into a simple quadratic.

---
#### 1. Identify and Substitute "u"
We let $u$ represent the middle variable part:
**Let $u = \sqrt{x}$** (which means $u^2 = x$)

Now, rewrite the equation in terms of $u$:
$$u^2 + u - 20 = 0$$
#### 2. Solve the Quadratic for "u"
We need two numbers that:
* **Multiply to:** $-20$
* **Add to:** $1$

The numbers are **$5$** and **$-4$**.
$$(u + 5)(u - 4) = 0$$
Set each factor to zero:
* $u + 5 = 0 \Rightarrow \mathbf{u = -5}$
* $u - 4 = 0 \Rightarrow \mathbf{u = 4}$
#### 3. Back-Substitute to Solve for "x"
Follow the "breadcrumbs" back to the original variable by replacing $u$ with $\sqrt{x}$. **Note: This step requires checking for extraneous solutions.**

**Case 1: $\sqrt{x} = 4$**
To isolate $x$, square both sides:
$$(\sqrt{x})^2 = (4)^2$$
$$\mathbf{x = 16}$$
**Case 2: $\sqrt{x} = -5$**
In the real number system, the principal square root of a number cannot be negative.
$$\sqrt{x} = -5 \quad \Rightarrow \text{No Real Solution}$$
---
### ⚠️ Graphical Interpretation & Verification

* **Real Zeros:** The graph of $g(x)$ crosses the x-axis at exactly **$(16, 0)$**.
* **Extraneous Solution:** While $u = -5$ is a valid solution for the quadratic part of the math, it fails the "back-substitution" test because squaring it would give $x = 25$, but $\sqrt{25}$ is $5$, not $-5$.
* **Verification:**
    * $g(16) = 16 + \sqrt{16} - 20 = 16 + 4 - 20 = 0$. (Check!)
    * $g(25) = 25 + \sqrt{25} - 20 = 25 + 5 - 20 = 10$. (Fails!)

---

> [!abstract] Algebra Takeaway
> Whenever your substitution involves a square root ($u = \sqrt{x}$), you must be on high alert for extraneous solutions. A square root is defined as the positive root; if your $u$-solve gives you a negative number, that specific branch of the solution must be discarded.

### Solving h(y) = -2y⁻² - 11y⁻¹ + 40 = 0 (u-Substitution)

This equation is "quadratic in form" because the leading exponent ($-2$) is exactly double the middle exponent ($-1$). We will use **u-substitution** and follow the "Leonard Setup" to handle the negative leading coefficient.

---
#### 1. Prepare the Equation (The "Leonard Setup")
To make factoring easier, set the function to zero and multiply the entire equation by **$-1$** to make the leading term positive:
$$-1 \cdot (-2y^{-2} - 11y^{-1} + 40 = 0)$$
$$2y^{-2} + 11y^{-1} - 40 = 0$$
#### 2. Identify and Substitute "u"
We let $u$ represent the middle variable part:
**Let $u = y^{-1}$** (which is the same as $1/y$)

Now, rewrite the equation in terms of $u$:
$$2u^2 + 11u - 40 = 0$$
#### 3. Solve the Quadratic for "u"
We use the **AC Method** (Diamond Method) to find factors of $2 \times -40 = -80$ that add to $11$:
* The numbers are **$16$** and **$-5$**.
* 
Rewrite and group:
1. $2u^2 + 16u - 5u - 40 = 0$
2. $2u(u + 8) - 5(u + 8) = 0$
3. $(2u - 5)(u + 8) = 0$

Set each factor to zero:
* $2u - 5 = 0 \Rightarrow \mathbf{u = 5/2}$
* $u + 8 = 0 \Rightarrow \mathbf{u = -8}$
#### 4. Back-Substitute to Solve for "y"
Follow the "breadcrumbs" back to the original variable by replacing $u$ with $y^{-1}$. Since $y^{-1} = 1/y$, we simply **take the reciprocal** of our $u$ values.

**Case 1: $y^{-1} = 5/2$**
Flip the fraction:
$$\mathbf{y = 2/5 \quad (or \ 0.4)}$$

**Case 2: $y^{-1} = -8$**
Flip the number (remember $-8$ is $-8/1$):
$$\mathbf{y = -1/8 \quad (or \ -0.125)}$$
---
### ⚠️ Graphical Interpretation & Verification

* **Real Zeros:** the graph of $h(y)$ crosses the y-axis (as the independent variable) at **$2/5$** and **$-1/8$**.
* **Domain Restriction:** Because the original equation has negative exponents ($1/y^2$ and $1/y$), the function is undefined at **$y = 0$**.
* **Verification:**
    * $h(0.4) = -2(0.4)^{-2} - 11(0.4)^{-1} + 40 = -2(6.25) - 11(2.5) + 40 = -12.5 - 27.5 + 40 = 0$. (Check!)

---

> [!abstract] Algebra Takeaway
> When dealing with negative exponents, the process is the same as any other substitution. The "magic" happens in the final step: because $y^{-1}$ means "one over y," you just need to find the reciprocal of your $u$ answer to get back to $y$.

## 2026-March-26 - Graphing Quadratic Functions (Precalculus - College Algebra 24) :
https://www.youtube.com/watch?v=VH4tzzBVbgA&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=24
### Graphing Quadratic Functions 
This lecture covers the properties and procedures for graphing quadratic functions, moving from the basic "vertex form" to handling standard form equations that may require the Quadratic Formula for x-intercepts.

---
#### 1. The Anatomy of a Parabola
Every quadratic function $f(x) = ax^2 + bx + c$ creates a **parabola**.
* **Opening Direction:** [00:00:54]
    * If $a > 0$, it opens **upward** (has a minimum).
    * If $a < 0$, it opens **downward** (has a maximum).
* **Vertical Stretch/Compression:** [00:01:06]
    * $|a| > 1$: Narrow (stretched).
    * $|a| < 1$: Wide (compressed).
* **Axis of Symmetry:** A vertical line ($x = h$) that passes through the vertex. Every point on one side has a mirrored "free point" on the other. [00:11:13]
---
#### 2. The Step-by-Step Graphing Process
Professor Leonard recommends this specific order to save time and avoid searching for x-intercepts that don't exist: [00:03:52]

1.  **Find the Vertex $(h, k)$:** Use the **Vertex Formula**. [00:05:15]
    * $x = \frac{-b}{2a}$
    * Plug that $x$ back into the function to find $y$.
2.  **Find the y-intercept:** Set $x = 0$. It is always the value of $c$ in standard form: $(0, c)$. [00:09:13]
3.  **Get a "Free Point":** Use the Axis of Symmetry to mirror the y-intercept across the vertex. [00:11:58]
4.  **Determine if x-intercepts exist:** [00:10:07]
    * If the vertex is *below* the x-axis and opens *up*, you have two x-intercepts.
    * If the vertex is *above* the x-axis and opens *up*, you have **zero** x-intercepts.
5.  **Solve for x-intercepts (if needed):** Set $f(x) = 0$. Use factoring or the **Quadratic Formula**. [00:13:30]

---
#### 3. Vertex Form vs. Standard Form
Professor Leonard explains that while the Vertex Formula is faster, **Completing the Square** transforms the equation into **Vertex Form**: $f(x) = a(x - h)^2 + k$. [00:18:01]

* **Standard Form:** $f(x) = 2x^2 + 8x + 5$
* **Vertex Form:** $f(x) = 2(x + 2)^2 - 3$ [00:20:42]
    * This shows a shift **left 2** and **down 3**.
    * The vertex is $(-2, -3)$.
---
#### 4. Finding the Equation from a Graph
If you are given a vertex $(h, k)$ and a point (like a y-intercept), you can build the function: [00:49:53]
1.  Plug the vertex into the form $f(x) = a(x - h)^2 + k$.
2.  Plug the coordinates of the other point into $x$ and $f(x)$.
3.  Solve for the missing value of **$a$**. [00:52:36]

---

> [!abstract] Algebra Takeaway
> Always find the vertex first. It tells you the maximum or minimum of the function and, when combined with the y-intercept, tells you immediately whether you need to bother solving for x-intercepts.
### Finding the Vertex Using x = -b/2a 

When a quadratic function is in **Standard Form** ($f(x) = ax^2 + bx + c$), the vertex represents the absolute highest or lowest point of the parabola. The formula $x = -b/2a$ is a derivation of the Quadratic Formula that identifies the vertical center of the graph.

---
#### 1. The Vertex Formula Components
The vertex is a point $(h, k)$. We find it in two distinct stages:

* **To find $h$ (the x-coordinate):** Use the formula derived from the axis of symmetry.
    $$x = \frac{-b}{2a}$$
* **To find $k$ (the y-coordinate):** Evaluate the function at the $x$ value you just found.
    $$y = f\left(\frac{-b}{2a}\right)$$

---
#### 2. Why this Formula Works
Professor Leonard explains that the Quadratic Formula is $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$. 
* The $\pm$ part gives you the distance to the left and right to find the x-intercepts.
* The **$\frac{-b}{2a}$** part is the "middle" or the "anchor" that sits exactly halfway between those two intercepts.
* Therefore, the x-coordinate of the vertex **must** be $-b/2a$. [00:05:45]

---
#### 3. Step-by-Step Execution
To find the vertex of $f(x) = 2x^2 + 8x + 5$:

1.  **Identify $a$ and $b$:** $a = 2$, $b = 8$.
2.  **Calculate $x$ ($h$):**
    $$x = \frac{-(8)}{2(2)} = \frac{-8}{4} = \mathbf{-2}$$
3.  **Calculate $y$ ($k$):** Plug $-2$ back into the original equation.
    $$f(-2) = 2(-2)^2 + 8(-2) + 5$$
    $$f(-2) = 8 - 16 + 5 = \mathbf{-3}$$
4.  **Result:** The Vertex is **$(-2, -3)$**.

---
#### 4. Strategic Advantages
* **Faster than Completing the Square:** You don't have to worry about factoring or "adding the magic number" to both sides.
* **Instant Axis of Symmetry:** Once you have the $x$ value of the vertex, you immediately have the equation for the axis of symmetry (e.g., $x = -2$).
* **Max/Min Identification:** * If $a > 0$, the $y$-value ($k$) is the **minimum**.
    * If $a < 0$, the $y$-value ($k$) is the **maximum**. [00:00:54]

---

> [!abstract] Algebra Takeaway
> Think of $-b/2a$ as the "DNA" of the parabola. It tells you where the graph turns around. If you are asked to graph a quadratic, always calculate this first; it acts as the starting point for your table of values.

### Finding X-Intercepts via Graphical Properties

If you have already identified the **Vertex $(h, k)$**, the **y-intercept $(0, c)$**, and the **Axis of Symmetry ($x = h$)**, you can often determine the x-intercepts through a combination of symmetry and algebra.

---
#### 1. The Symmetry Shortcut (The "Free Point")
The Axis of Symmetry acts as a mirror. If you know the y-intercept, you can immediately find a "mirror point" at the same height on the opposite side of the vertex.

* **Step:** Measure the horizontal distance from the y-intercept ($x=0$) to the Axis of Symmetry ($x=h$).
* **Step:** Move that same distance to the other side of the axis. 
* **Result:** This gives you a third point $(2h, c)$. While this isn't an x-intercept, it helps you "aim" the parabola to see where it will cross the x-axis.
---
#### 2. The Existence Test (Do they even exist?)
Before calculating, use the vertex and the leading coefficient ($a$) to see if the graph even touches the x-axis:

| Vertex Position ($k$) | Opening Direction ($a$) | X-Intercepts |
| :--- | :--- | :--- |
| **Below** x-axis ($k < 0$) | **Upward** ($a > 0$) | **Two** Real Intercepts |
| **Above** x-axis ($k > 0$) | **Downward** ($a < 0$) | **Two** Real Intercepts |
| **Above** x-axis ($k > 0$) | **Upward** ($a > 0$) | **Zero** (Complex Only) |
| **On** x-axis ($k = 0$) | Any | **One** (The Vertex itself) |

---
#### 3. Solving via Vertex Form
If you have the vertex $(h, k)$ and the y-intercept $(0, c)$, you can solve for the x-intercepts without using the standard Quadratic Formula.

**Step A: Find the "a" value**
Plug the vertex and the y-intercept into the Vertex Form equation:
$$y = a(x - h)^2 + k$$
$$c = a(0 - h)^2 + k$$
Solve this for **$a$**.

**Step B: Solve for Zeros**
Set $y = 0$ and use the **Square Root Property**:
$$0 = a(x - h)^2 + k$$
$$-k = a(x - h)^2$$
$$\frac{-k}{a} = (x - h)^2$$
$$\pm\sqrt{\frac{-k}{a}} = x - h$$
$$\mathbf{x = h \pm \sqrt{\frac{-k}{a}}}$$

---
### ⚠️ Practical Example
If your vertex is **$(3, -4)$** and your y-intercept is **$(0, 5)$**:
1.  **Symmetry:** You have a mirror point at **$(6, 5)$**.
2.  **Logic:** The vertex is below the axis and the y-intercept is above it, so it **must** cross the x-axis twice.
3.  **Calculation:** * $5 = a(0-3)^2 - 4 \Rightarrow 9 = 9a \Rightarrow \mathbf{a = 1}$.
    * $0 = 1(x-3)^2 - 4 \Rightarrow 4 = (x-3)^2$.
    * $\pm 2 = x - 3$.
    * **$x = 5$** and **$x = 1$**.
---

> [!abstract] Algebra Takeaway
> The x-intercepts are always equidistant from the Axis of Symmetry. If you find one x-intercept is 2 units to the right of the axis ($h+2$), the other must be 2 units to the left ($h-2$). This is why the Quadratic Formula always looks like $\text{Vertex} \pm \text{Distance}$.
### Graphing Analysis of f(x) = 2x² + 8x + 5

To fully map this parabola for your notes, we will identify the key "anchor points": the y-intercept, the vertex, and the x-intercepts.

---
#### 1. Find the y-intercept
The y-intercept occurs when $x = 0$. In standard form $ax^2 + bx + c$, this is always the constant $c$.
$$f(0) = 2(0)^2 + 8(0) + 5 = 5$$
**y-intercept: (0, 5)**

---
#### 2. Find the Vertex (h, k)
We use the Vertex Formula to find the x-coordinate ($h$), then plug it back in for the y-coordinate ($k$).

**Identify Coefficients:** $a = 2, b = 8, c = 5$

**Step A: Find h**
$$h = \frac{-b}{2a} = \frac{-(8)}{2(2)} = \frac{-8}{4} = -2$$

**Step B: Find k**
$$k = f(-2) = 2(-2)^2 + 8(-2) + 5$$
$$k = 2(4) - 16 + 5$$
$$k = 8 - 16 + 5 = -3$$

**Vertex: (-2, -3)**

---
#### 3. Solve for x-intercepts (Quadratic Formula)
Since the vertex is at $y = -3$ and the parabola opens upward ($a=2$), we know there are **two real x-intercepts**. We set $f(x) = 0$:

$$x = \frac{-(8) \pm \sqrt{(8)^2 - 4(2)(5)}}{2(2)}$$

**Simplify the Discriminant:**
* $8^2 = 64$
* $4(2)(5) = 40$
* $64 - 40 = \mathbf{24}$

**Solve and Simplify:**
$$x = \frac{-8 \pm \sqrt{24}}{4}$$

Simplify $\sqrt{24}$ (which is $\sqrt{4 \cdot 6} = 2\sqrt{6}$):
$$x = \frac{-8 \pm 2\sqrt{6}}{4}$$

Factor out a 2 from the numerator to reduce the fraction:
$$x = \frac{2(-4 \pm \sqrt{6})}{4}$$
$$\mathbf{x = \frac{-4 \pm \sqrt{6}}{2}}$$

**Approximate Values:** $x \approx -0.78$ and $x \approx -3.22$

---
#### 4. Summary Table for Graphing

| Feature | Coordinate(s) |
| :--- | :--- |
| **Opening** | Upward ($a=2$) |
| **Vertex** | $(-2, -3)$ |
| **y-intercept** | $(0, 5)$ |
| **x-intercepts** | $(\frac{-4 \pm \sqrt{6}}{2}, 0)$ |
| **Axis of Symmetry** | $x = -2$ |

---
> [!abstract] Algebra Takeaway
> Using the $-b/2a$ method is often the fastest way to find the "turning point" of the graph. Once you have the vertex and the y-intercept, you have enough information to sketch the general shape of the parabola even before solving the Quadratic Formula.

### Graphing Analysis of g(x) = -2x² - 4x + 2

To map this downward-opening parabola for your notes, we will calculate the y-intercept, identify the vertex using the $h = -b/2a$ method, and solve for the x-intercepts using the Quadratic Formula.

---
#### 1. Find the y-intercept
The y-intercept occurs when $x = 0$. In standard form $ax^2 + bx + c$, this is the constant $c$.
$$g(0) = -2(0)^2 - 4(0) + 2 = 2$$
**y-intercept: (0, 2)**

---
#### 2. Find the Vertex (h, k)
We use the Vertex Formula to find the x-coordinate ($h$), then evaluate the function for the y-coordinate ($k$).

**Identify Coefficients:** $a = -2, b = -4, c = 2$

**Step A: Find h**
$$h = \frac{-b}{2a} = \frac{-(-4)}{2(-2)} = \frac{4}{-4} = -1$$

**Step B: Find k**
$$k = g(-1) = -2(-1)^2 - 4(-1) + 2$$
$$k = -2(1) + 4 + 2$$
$$k = -2 + 4 + 2 = 4$$

**Vertex: (-1, 4)**

---
#### 3. Solve for x-intercepts (Quadratic Formula)
Since the vertex is above the x-axis ($k = 4$) and the parabola opens downward ($a = -2$), there are **two real x-intercepts**. Set $g(x) = 0$:

$$x = \frac{-(-4) \pm \sqrt{(-4)^2 - 4(-2)(2)}}{2(-2)}$$

**Simplify the Discriminant:**
* $(-4)^2 = 16$
* $-4(-2)(2) = 16$
* $16 + 16 = \mathbf{32}$

**Solve and Simplify:**
$$x = \frac{4 \pm \sqrt{32}}{-4}$$

Simplify $\sqrt{32}$ (which is $\sqrt{16 \cdot 2} = 4\sqrt{2}$):
$$x = \frac{4 \pm 4\sqrt{2}}{-4}$$

Divide each term in the numerator by $-4$:
$$\mathbf{x = -1 \mp \sqrt{2}}$$

**Approximate Values:** $x \approx 0.41$ and $x \approx -2.41$

---
#### 4. Summary Table for Graphing

| Feature | Coordinate(s) |
| :--- | :--- |
| **Opening** | Downward ($a = -2$) |
| **Vertex** | $(-1, 4)$ |
| **y-intercept** | $(0, 2)$ |
| **x-intercepts** | $(-1 \pm \sqrt{2}, 0)$ |
| **Axis of Symmetry** | $x = -1$ |

---
> [!abstract] Algebra Takeaway
> When $a$ is negative, the vertex represents the **maximum** value of the function. Notice how the x-intercepts are exactly $\sqrt{2}$ units to the left and right of the axis of symmetry ($x = -1$). This symmetry is a built-in "check" for your work.

### Graphing Analysis of f(x) = -4x² - 4x - 1

To map this downward-opening parabola for your notes, we will calculate the y-intercept, identify the vertex using the $h = -b/2a$ method, and solve for the x-intercepts using the Quadratic Formula.

---
#### 1. Find the y-intercept
The y-intercept occurs when $x = 0$. In standard form $ax^2 + bx + c$, this is always the constant $c$.
$$f(0) = -4(0)^2 - 4(0) - 1 = -1$$
**y-intercept: (0, -1)**

---
#### 2. Find the Vertex (h, k)
We use the Vertex Formula to find the x-coordinate ($h$), then evaluate the function for the y-coordinate ($k$).

**Identify Coefficients:** $a = -4, b = -4, c = -1$

**Step A: Find h**
$$h = \frac{-b}{2a} = \frac{-(-4)}{2(-4)} = \frac{4}{-8} = \mathbf{-1/2}$$

**Step B: Find k**
$$k = f(-1/2) = -4(-1/2)^2 - 4(-1/2) - 1$$
$$k = -4(1/4) + 2 - 1$$
$$k = -1 + 2 - 1 = \mathbf{0}$$

**Vertex: (-1/2, 0)**

---
#### 3. Solve for x-intercepts (Quadratic Formula)
Since the vertex is exactly on the x-axis ($k = 0$), we expect only **one real x-intercept** (a "double root"). Let's verify with the formula:

$$x = \frac{-(-4) \pm \sqrt{(-4)^2 - 4(-4)(-1)}}{2(-4)}$$

**Simplify the Discriminant:**
* $(-4)^2 = 16$
* $-4(-4)(-1) = -16$
* $16 - 16 = \mathbf{0}$

**Solve:**
$$x = \frac{4 \pm \sqrt{0}}{-8}$$
$$x = \frac{4}{-8} = \mathbf{-1/2}$$

---
#### 4. Summary Table for Graphing

| Feature | Coordinate(s) |
| :--- | :--- |
| **Opening** | Downward ($a = -4$) |
| **Vertex** | $(-1/2, 0)$ |
| **y-intercept** | $(0, -1)$ |
| **x-intercepts** | $(-1/2, 0)$ |
| **Axis of Symmetry** | $x = -1/2$ |

---

> [!abstract] Algebra Takeaway
> Whenever the discriminant ($b^2 - 4ac$) equals zero, the vertex of the parabola is your only x-intercept. This means the parabola just "kisses" the x-axis at a single point before turning back around.

### Graphing Analysis of g(x) = 3x² + 2x + 5

To map this upward-opening parabola for your notes, we will calculate the y-intercept, identify the vertex using the $h = -b/2a$ method, and solve for the x-intercepts using the Quadratic Formula.

---
#### 1. Find the y-intercept
The y-intercept occurs when $x = 0$. In standard form $ax^2 + bx + c$, this is always the constant $c$.
$$g(0) = 3(0)^2 + 2(0) + 5 = 5$$
**y-intercept: (0, 5)**

---
#### 2. Find the Vertex (h, k)
We use the Vertex Formula to find the x-coordinate ($h$), then evaluate the function for the y-coordinate ($k$).

**Identify Coefficients:** $a = 3, b = 2, c = 5$

**Step A: Find h**
$$h = \frac{-b}{2a} = \frac{-(2)}{2(3)} = \frac{-2}{6} = \mathbf{-1/3}$$

**Step B: Find k**
$$k = g(-1/3) = 3(-1/3)^2 + 2(-1/3) + 5$$
$$k = 3(1/9) - 2/3 + 5$$
$$k = 1/3 - 2/3 + 15/3 = \mathbf{14/3 \ ( \approx 4.67 )}$$

**Vertex: (-1/3, 14/3)**

---
#### 3. Solve for x-intercepts (Quadratic Formula)
Since the vertex is above the x-axis ($k \approx 4.67$) and the parabola opens upward ($a = 3$), the graph will never cross the x-axis. We expect **complex/imaginary solutions**.

$$x = \frac{-(2) \pm \sqrt{(2)^2 - 4(3)(5)}}{2(3)}$$

**Simplify the Discriminant:**
* $(2)^2 = 4$
* $4(3)(5) = 60$
* $4 - 60 = \mathbf{-56}$

**Solve and Simplify:**
$$x = \frac{-2 \pm \sqrt{-56}}{6}$$

Simplify $\sqrt{-56}$ (which is $\sqrt{-1 \cdot 4 \cdot 14} = 2i\sqrt{14}$):
$$x = \frac{-2 \pm 2i\sqrt{14}}{6}$$

Divide each term by the common factor of 2:
$$\mathbf{x = \frac{-1 \pm i\sqrt{14}}{3}}$$

---
#### 4. Summary Table for Graphing

| Feature | Coordinate(s) |
| :--- | :--- |
| **Opening** | Upward ($a = 3$) |
| **Vertex** | $(-1/3, 14/3)$ |
| **y-intercept** | $(0, 5)$ |
| **x-intercepts** | None (Complex: $\frac{-1 \pm i\sqrt{14}}{3}$) |
| **Axis of Symmetry** | $x = -1/3$ |



---

> [!abstract] Algebra Takeaway
> When the discriminant is negative ($b^2 - 4ac < 0$), the parabola does not have any real x-intercepts. Graphically, this means the entire parabola sits completely above or completely below the x-axis. In your notes, always label these as "No Real Solutions" or provide the complex coordinates if required.

### Finding the Quadratic Function from a Vertex and Y-Intercept

When given the vertex $(h, k)$ and an additional point (like the y-intercept), we use **Vertex Form** to solve for the leading coefficient $a$ and build the function.

---
#### 1. Identify the Given Information
* **Vertex $(h, k)$:** $(1, -5)$
    * $h = 1$
    * $k = -5$
* **Y-intercept:** $(0, -3)$
    * This gives us a point where $x = 0$ and $f(x) = -3$.

#### 2. Plug the Vertex into Vertex Form
The standard Vertex Form is $f(x) = a(x - h)^2 + k$.
Substitute $h = 1$ and $k = -5$:
$$f(x) = a(x - 1)^2 - 5$$
#### 3. Solve for "a" Using the Y-intercept
Substitute the coordinates of the y-intercept $(0, -3)$ into the equation for $x$ and $f(x)$:
$$-3 = a(0 - 1)^2 - 5$$

Now, simplify and solve for $a$:
1.  **Simplify inside the parentheses:** $-3 = a(-1)^2 - 5$
2.  **Square the value:** $-3 = a(1) - 5$
3.  **Isolate $a$:** Add 5 to both sides.
    $$2 = a$$

#### 4. Write the Final Function
Now that we have $a = 2$, we plug it back into the Vertex Form equation from Step 2:
$$\mathbf{f(x) = 2(x - 1)^2 - 5}$$

---
### ⚠️ Graphical Properties of this Function
* **Opening:** Since $a = 2$ (positive), the parabola opens **upward**.
* **Stretch:** Since $|a| > 1$, the parabola is **narrower** than the parent function $x^2$.
* **Symmetry:** Using the Axis of Symmetry ($x = 1$), we know there is a "mirror point" for the y-intercept at **$(2, -3)$**.

---
> [!abstract] Algebra Takeaway
> Always remember that the formula uses $(x - h)$. If your vertex is positive ($h = 1$), the formula will look like $(x - 1)$. If your vertex was negative ($h = -1$), the formula would become $(x + 1)$.

## 2026-March-28 - Solving Quadratic Inequalities (Precalculus - College Algebra 25) :
https://www.youtube.com/watch?v=qd41nGPHbMU&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=27
### Solving Quadratic Inequalities

Quadratic inequalities (e.g., $ax^2 + bx + c > 0$) determine the intervals of $x$ where a parabola sits above or below the x-axis.

---
#### 1. The Standard Workflow
1. **Set to Zero:** Move all terms to one side so the inequality compares the quadratic to zero.
2. **Find Critical Values:** Solve the related equation $ax^2 + bx + c = 0$ using factoring or the Quadratic Formula. these x-intercepts are your "Boundary Points."
3. **Test Intervals:** Plot the boundary points on a number line to create three regions.
4. **Check Truth:** - **Algebraically:** Plug a test $x$ from each region into the inequality.
   - **Graphically:** Note if the parabola opens up ($a>0$) or down ($a<0$).

---
#### 2. Interpreting the Graph
* **If $f(x) > 0$:** You are looking for where the graph is **above** the x-axis.
   - If opening up: The "wings" $(-\infty, x_1) \cup (x_2, \infty)$.
   - If opening down: The "valley" between intercepts $(x_1, x_2)$.
* **If $f(x) < 0$:** You are looking for where the graph is **below** the x-axis.
   - If opening up: The "valley" between intercepts $(x_1, x_2)$.
   - If opening down: The "wings" $(-\infty, x_1) \cup (x_2, \infty)$.

---
#### 3. Notation Rules
* Use **Parentheses** `( )` for strict inequalities ($<$ or $>$). These represent "open holes" on a number line.
* Use **Brackets** `[ ]` for non-strict inequalities ($\le$ or $\ge$). These represent "closed holes" because the intercept itself is a solution.
* Use the **Union Symbol** $\cup$ to join disconnected intervals.

---
> [!abstract] Algebra Takeaway
> A quadratic inequality doesn't have a single "x =" answer; it has a range. The x-intercepts are the only places where the function can change from "True" to "False," so they are the only points you need to find to define your boundaries.

### Solving the Quadratic Inequality: x² - 3x - 10 ≤ 0

To solve this inequality for your Obsidian notes, we will find the boundary points (x-intercepts) and determine which interval of the parabola sits below or on the x-axis.

---
#### 1. Find the Boundary Points (Roots)
First, treat the inequality as an equation to find where the parabola crosses the x-axis:
$$x^2 - 3x - 10 = 0$$

**Factor the Quadratic:**
We need two numbers that multiply to $-10$ and add to $-3$.
The numbers are **$-5$** and **$2$**.
$$(x - 5)(x + 2) = 0$$

**Solve for x:**
* $x - 5 = 0 \Rightarrow \mathbf{x = 5}$
* $x + 2 = 0 \Rightarrow \mathbf{x = -2}$

These are our **Critical Values**.

---
#### 2. Test the Intervals
Since the inequality is $\le 0$, we are looking for the region where the graph is **below or touching** the x-axis.
* **Interval A $(-\infty, -2)$:** Test $x = -3 \Rightarrow (-3)^2 - 3(-3) - 10 = 9 + 9 - 10 = 8$ (Positive/False)
* **Interval B $[-2, 5]$:** Test $x = 0 \Rightarrow (0)^2 - 3(0) - 10 = -10$ (Negative/True)
* **Interval C $(5, \infty)$:** Test $x = 6 \Rightarrow (6)^2 - 3(6) - 10 = 36 - 18 - 10 = 8$ (Positive/False)
---
#### 3. Graphical Description
The function $f(x) = x^2 - 3x - 10$ is an **upward-opening** parabola ($a = 1$). 

* **Vertex:** The vertex is located at $x = -b/2a = 1.5$. Since the y-value at the vertex is negative ($1.5^2 - 3(1.5) - 10 = -12.25$), the "valley" of the parabola dips below the x-axis.
* **The "Valley":** The solution to $\le 0$ corresponds to this bottom portion of the "U" shape.
* **Visual:** Imagine a shaded region on the x-axis starting at $-2$ and ending at $5$. Every point on the curve between these two values is "underwater" (below $y=0$).
---
#### 4. Final Solution
Since the inequality includes "or equal to" ($\le$), we use **brackets** to include the boundary points.

**Interval Notation:** $$\mathbf{[-2, 5]}$$

**Set-Builder Notation:**
$$\mathbf{\{x \mid -2 \le x \le 5\}}$$

---
> [!abstract] Algebra Takeaway
> For an upward-opening parabola, "less than or equal to" will almost always result in a single, closed interval between the two roots. Think of it as the segment of the graph that is "submerged" below the x-axis line.

### Solving the Quadratic Inequality: 2x² < 5x + 3

To solve this inequality for your Obsidian notes, we must first move all terms to one side to compare the quadratic to zero.

---
#### 1. Standard Form and Boundary Points
Subtract $5x$ and $3$ from both sides to set the inequality to zero:
$$2x^2 - 5x - 3 < 0$$

Now, find the **Critical Values** by solving the related equation:
$$2x^2 - 5x - 3 = 0$$

**Factor by Grouping (AC Method):**
* $a \cdot c = 2 \cdot -3 = -6$
* Find factors of $-6$ that add to $-5$: **$-6$** and **$1$**.

$$2x^2 - 6x + 1x - 3 = 0$$
$$2x(x - 3) + 1(x - 3) = 0$$
$$(2x + 1)(x - 3) = 0$$

**Solve for x:**
* $2x + 1 = 0 \Rightarrow \mathbf{x = -1/2}$
* $x - 3 = 0 \Rightarrow \mathbf{x = 3}$
---
#### 2. Test the Intervals
Since the inequality is **$< 0$**, we are looking for the region where the parabola is **strictly below** the x-axis.
* **Interval A $(-\infty, -1/2)$:** Test $x = -1 \Rightarrow 2(-1)^2 - 5(-1) - 3 = 4$ (Positive/False)
* **Interval B $(-1/2, 3)$:** Test $x = 0 \Rightarrow 2(0)^2 - 5(0) - 3 = -3$ (Negative/True)
* **Interval C $(3, \infty)$:** Test $x = 4 \Rightarrow 2(4)^2 - 5(4) - 3 = 9$ (Positive/False)
---
#### 3. Graphical Description
The function $f(x) = 2x^2 - 5x - 3$ is an **upward-opening** parabola ($a = 2$).

* **Opening:** Because $a > 0$, the "bowl" of the parabola points up.
* **The "Below" Region:** Since we want $f(x) < 0$, we are looking for the "valley" or the bottom part of the "U" that dips below the x-axis.
* **Visual:** The graph crosses the x-axis at $-0.5$ and $3$. Between these two points, the y-values are negative. Because it is a strict inequality ($<$), we visualize **open circles** at the intercepts, meaning the graph exactly at $y=0$ is not included.
---
#### 4. Final Solution
We use **parentheses** because the inequality does not include the "equal to" sign.

**Interval Notation:** $$\mathbf{(-1/2, 3)}$$
**Set-Builder Notation:**
$$\mathbf{\{x \mid -1/2 < x < 3\}}$$
---
> [!abstract] Algebra Takeaway
> When a quadratic is "Less Than" zero and opens upward, the solution is always the single interval between the roots. If the inequality had been "Greater Than" zero ($> 0$), the solution would have been the two separate "wings" pointing toward infinity.

### Solving the Quadratic Inequality: x(x + 1) > 20

To solve this inequality for your Obsidian notes, we must first distribute and move all terms to one side to compare the quadratic to zero.

---
#### 1. Standard Form and Boundary Points
First, distribute the $x$ and subtract $20$ from both sides:
$$x^2 + x > 20$$
$$x^2 + x - 20 > 0$$

Now, find the **Critical Values** by solving the related equation:
$$x^2 + x - 20 = 0$$

**Factor the Quadratic:**
We need two numbers that multiply to $-20$ and add to $1$.
The numbers are **$5$** and **$-4$**.
$$(x + 5)(x - 4) = 0$$

**Solve for x:**
* $x + 5 = 0 \Rightarrow \mathbf{x = -5}$
* $x - 4 = 0 \Rightarrow \mathbf{x = 4}$

These intercepts are where the parabola crosses the x-axis.

---
#### 2. Test the Intervals
Since the inequality is **$> 0$**, we are looking for the regions where the parabola is **above** the x-axis.
* **Interval A $(-\infty, -5)$:** Test $x = -6 \Rightarrow (-6)^2 + (-6) - 20 = 36 - 6 - 20 = 10$ (Positive/True)
* **Interval B $(-5, 4)$:** Test $x = 0 \Rightarrow (0)^2 + (0) - 20 = -20$ (Negative/False)
* **Interval C $(4, \infty)$:** Test $x = 5 \Rightarrow (5)^2 + (5) - 20 = 25 + 5 - 20 = 10$ (Positive/True)
---
#### 3. Graphical Description
The function $f(x) = x^2 + x - 20$ is an **upward-opening** parabola ($a = 1$).

* **Opening:** Because $a > 0$, the "arms" of the parabola point toward positive infinity.
* **The "Above" Region:** Since we want $f(x) > 0$, we are looking for the two "wings" of the parabola that rise above the x-axis.
* **Visual:** The graph dips below the x-axis between $-5$ and $4$ (the "valley"). Because we want the parts *greater than* zero, we select everything to the left of $-5$ and everything to the right of $4$. We use **open circles** at the intercepts because it is a strict inequality.
---
#### 4. Final Solution
Since the solution consists of two separate pieces, we use the **Union Symbol ($\cup$)** and **parentheses**.

**Interval Notation:** $$\mathbf{(-\infty, -5) \cup (4, \infty)}$$
**Set-Builder Notation:**
$$\mathbf{\{x \mid x < -5 \text{ or } x > 4\}}$$
---
> [!abstract] Algebra Takeaway
> For an upward-opening parabola, "Greater Than" zero ($> 0$) always results in a split solution (the "wings"). If the inequality had been "Less Than" zero ($< 0$), the solution would have been the single "valley" between $-5$ and $4$.

### Solving the Quadratic Inequality: 4x² + 9 < 6x

To solve this inequality for your Obsidian notes, we must first move all terms to one side to compare the quadratic to zero and identify the boundary points.

---
#### 1. Standard Form and Discriminant Check
Subtract $6x$ from both sides to set the inequality to zero:
$$4x^2 - 6x + 9 < 0$$

Before attempting to factor, let's check the **Discriminant** ($b^2 - 4ac$) to see if there are any real x-intercepts:
* $a = 4$
* $b = -6$
* $c = 9$

$$\text{Discriminant} = (-6)^2 - 4(4)(9)$$
$$\text{Discriminant} = 36 - 144$$
$$\text{Discriminant} = \mathbf{-108}$$

Since the discriminant is **negative**, there are **no real x-intercepts**. The parabola never crosses or touches the x-axis.

---
#### 2. Graphical Description
The function $f(x) = 4x^2 - 6x + 9$ is an **upward-opening** parabola ($a = 4$).

* **Vertex Location:** The x-coordinate of the vertex is $h = -b/2a = 6/8 = \mathbf{0.75}$.
* **Vertex Height:** Plugging $0.75$ back into the function:
  $f(0.75) = 4(0.75)^2 - 6(0.75) + 9 = 2.25 - 4.5 + 9 = \mathbf{6.75}$.
* **Visual:** The vertex is at $(0.75, 6.75)$, which is well above the x-axis. Since the parabola opens upward, the entire graph "floats" in the upper half-plane and never enters the region below the x-axis.
---
#### 3. Determining the Solution
The inequality asks: "Where is the parabola **less than** zero ($< 0$)?"

* **Observation:** Based on our graph, the y-values of this function are always $6.75$ or higher.
* **Conclusion:** There are **no values of $x$** that will make the expression less than zero.

---
#### 4. Final Solution

**Solution:** $$\mathbf{\text{No Solution (or } \emptyset)}$$

---

> [!abstract] Algebra Takeaway
> If a quadratic has a negative discriminant, it is either "Always True" or "Never True" across all real numbers. 
> * If $a > 0$ and you want $f(x) < 0$, the answer is **No Solution**.
> * If $a > 0$ and you want $f(x) > 0$, the answer is **All Real Numbers** $(-\infty, \infty)$.

## 2026-March-29 - Applications of Quadratic Functions (Precalculus - College Algebra 26) : 
https://www.youtube.com/watch?v=Ow_u0qLAOJI&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=28
### Applications of Quadratic Functions (Professor Leonard)

This lecture transitions from abstract algebra to real-world modeling. The central theme is that the **Vertex** of a parabola represents the "optimum" point—either a **Maximum** (for downward-opening parabolas) or a **Minimum** (for upward-opening ones).

---
#### 1. The Power of the Vertex
In application problems, you are almost always searching for a "best-case scenario."
* **Maximum Value:** Use the vertex formula $x = -b/2a$ when you see words like *maximum height, maximum revenue,* or *largest area*. [00:01:16]
* **Minimum Value:** Use the vertex formula for *minimum cost* or *least distance*. [00:01:22]
---
#### 2. Business Application: Maximum Revenue
Revenue ($R$) is defined as the number of items sold ($x$) multiplied by the price per item ($p$). [00:01:54]

* **The Setup:** If price decreases as production increases (e.g., $p = -1/3x + 100$), the revenue function becomes quadratic:
  $$R(x) = x \cdot (-1/3x + 100) = -1/3x^2 + 100x$$
* **Finding Max Revenue:** [00:11:19]
    1. Find $x = -b/2a$ to determine the **number of items** needed for peak revenue.
    2. Plug that $x$ back into $R(x)$ to find the **actual maximum dollar amount**.
    3. Plug that $x$ into the price function to find the **ideal price** to charge customers. [00:14:40]

---
#### 3. Geometric Application: Maximum Area (Constraints)
When you have a limited resource (like 3,000 ft of fencing) and want to enclose the largest possible space, you use a **Constraint Equation**. [00:16:34]

* **Step 1 (Constraint):** Write the perimeter formula: $2x + 2y = 3000$. [00:17:16]
* **Step 2 (Goal):** Write the area formula: $A = x \cdot y$. [00:18:07]
* **Step 3 (Substitution):** Solve the constraint for one variable ($y = 1500 - x$) and plug it into the area formula:
  $$A(x) = x(1500 - x) = -x^2 + 1500x$$ [00:19:50]
* **Step 4 (Solve):** Find the vertex. For a standard rectangle, the maximum area is always achieved when the shape is a **square** ($x = y$). [00:22:45]

---
#### 4. Physics Application: Projectile Motion
Projectiles (balls, rockets, etc.) follow a parabolic path defined by height ($h$) over distance or time ($t$). [00:24:00]

* **Range:** To find how far the object travels, set $h = 0$ (the ground) and solve for $x$ using the Quadratic Formula. [00:24:36]
* **Peak Height:** Use the vertex formula ($x = -b/2a$) to find when or where the object reaches its highest point. [00:25:04]

---

> [!abstract] Algebra Takeaway
> Application problems are essentially "Vertex Searches." The hardest part is building the equation from the word problem; once the quadratic equation is set up, the $-b/2a$ formula consistently provides the answer for any "maximum" or "minimum" request.

### Maximum Revenue Application: R(x) = x · p

This problem from Professor Leonard's lecture demonstrates how a business finds the "sweet spot" for pricing to achieve the highest possible income using quadratic properties.

---
#### 1. The Setup: Building the Revenue Function
Revenue ($R$) is the total money coming in, calculated as the **number of items sold ($x$)** times the **price per item ($p$)**.

* **Given Price Function (Demand):** $p = -\frac{1}{3}x + 100$
  * This linear equation shows that as you produce more items ($x$), the price ($p$) must drop to sell them all.
* **The Revenue Equation:**
  $$R(x) = x \cdot p$$
  $$R(x) = x\left(-\frac{1}{3}x + 100\right)$$
  $$R(x) = -\frac{1}{3}x^2 + 100x$$
---
#### 2. Finding the Optimal Production (x)
Since the leading coefficient ($a = -1/3$) is negative, the graph is a downward-opening parabola. The maximum revenue occurs at the **Vertex**.

**Identify Coefficients:** $a = -1/3$, $b = 100$.

**Calculate the Vertex x-coordinate ($h$):**
$$x = \frac{-b}{2a} = \frac{-100}{2(-1/3)} = \frac{-100}{-2/3}$$
To divide by a fraction, multiply by the reciprocal:
$$x = -100 \cdot \left(-\frac{3}{2}\right) = \mathbf{150 \text{ units}}$$

---
#### 3. Finding the Optimal Price (p)
To find the price the business should charge to sell exactly 150 units, plug $x = 150$ back into the **Price Function**:
$$p = -\frac{1}{3}(150) + 100$$
$$p = -50 + 100 = \mathbf{\$50}$$

---
#### 4. Calculating Maximum Revenue
To find the actual maximum dollar amount, plug $x = 150$ into the **Revenue Function**:
$$R(150) = 150 \cdot 50 = \mathbf{\$7,500}$$

---
#### 5. Summary Table

| Question | Variable to Find | Result |
| :--- | :--- | :--- |
| **How many units to sell?** | $x = -b/2a$ | **150 units** |
| **What price to charge?** | $p = f(x)$ | **$50** |
| **What is the max revenue?** | $R(x)$ | **$7,500** |

---
> [!abstract] Algebra Takeaway
> In business applications, the "x" of the vertex tells you **how much to make**, while the "y" of the vertex tells you **the maximum money** you can make. If you need the price, you must jump back to the original price (demand) linear equation.

### Maximum Area with a Fixed Perimeter (Constraint Problem)

This problem from Professor Leonard's lecture demonstrates how to use a **Constraint Equation** (the available fencing) to find the dimensions that produce the **Maximum Area**.

---
#### 1. The Two-Equation Setup
To solve "Optimization" problems, we need two separate equations:

* **Constraint Equation (Perimeter):** The physical limit of your materials.
    $$P = 2x + 2y = 3000$$
* **Objective Equation (Area):** The thing you want to maximize.
    $$A = x \cdot y$$
---
#### 2. Substitution: Reducing to One Variable
We cannot find the vertex of an equation with two different variables ($x$ and $y$). We must substitute one into the other.

1.  **Solve the Constraint for $y$:**
    $$2x + 2y = 3000$$
    $$2y = 3000 - 2x$$
    $$y = 1500 - x$$
2.  **Plug $y$ into the Area Equation:**
    $$A(x) = x(1500 - x)$$
    $$A(x) = -x^2 + 1500x$$

---
#### 3. Finding the Maximum (The Vertex)
Since $a = -1$, this is a downward-opening parabola. The maximum area occurs at the vertex.

**Identify Coefficients:** $a = -1$, $b = 1500$.

**Calculate the Optimal Width ($x$):**
$$x = \frac{-b}{2a} = \frac{-1500}{2(-1)} = \frac{-1500}{-2} = \mathbf{750 \text{ feet}}$$

**Calculate the Optimal Length ($y$):**
Using our substituted equation $y = 1500 - x$:
$$y = 1500 - 750 = \mathbf{750 \text{ feet}}$$
---
#### 4. The Final Result
* **Dimensions:** $750' \times 750'$ (A Square)
* **Maximum Area:**
    $$A = 750 \cdot 750 = \mathbf{562,500 \text{ sq ft}}$$

---
#### 5. Summary Table

| Step | Component | Result |
| :--- | :--- | :--- |
| **1** | Constraint | $2x + 2y = 3000$ |
| **2** | Objective | $A = -x^2 + 1500x$ |
| **3** | Best Width ($x$) | $750'$ |
| **4** | Max Area ($A$) | $562,500 \text{ ft}^2$ |

---

> [!abstract] Algebra Takeaway
> In a standard four-sided rectangular fencing problem, the maximum area is **always a square**. If the problem changes (e.g., fencing only 3 sides because of a river), the dimensions will shift, but the method remains the same: **Constraint $\rightarrow$ Substitution $\rightarrow$ Vertex.**

### Projectile Motion Application: h(x) = -32x² / (2000)² + x

In this problem from Professor Leonard's lecture, we analyze the path of a projectile (like a ball or shell) where $x$ represents the horizontal distance traveled and $h(x)$ represents the vertical height.

---
#### 1. Identifying the Components
The equation is a quadratic in the form $ax^2 + bx + c$:
* **$a = \frac{-32}{2000^2}$**: The leading coefficient is negative, meaning the parabola opens **downward**. This coefficient represents the effect of gravity.
* **$b = 1$**: The linear term (from the $+x$).
* **$c = 0$**: There is no constant, meaning the projectile starts at a height of **0** (the ground).
---
#### 2. Finding the Maximum Height (The Vertex)
To find the peak of the projectile's flight, we find the vertex $(h, k)$.

**Step A: Find the horizontal distance to the peak ($x$):**
Using the vertex formula $x = \frac{-b}{2a}$:
$$x = \frac{-(1)}{2 \left( \frac{-32}{2000^2} \right)}$$
$$x = \frac{-1}{\frac{-64}{4,000,000}}$$
$$x = \frac{4,000,000}{64} = \mathbf{62,500 \text{ feet}}$$

**Step B: Find the maximum vertical height ($y$):**
Plug $x = 62,500$ back into the original function:
$$h(62,500) = \frac{-32(62,500)^2}{4,000,000} + 62,500$$
After simplifying the arithmetic:
$$\mathbf{\text{Max Height} = 31,250 \text{ feet}}$$
---
#### 3. Finding the Total Range (X-Intercepts)
To find how far the projectile travels before hitting the ground, set $h(x) = 0$.

$$0 = \frac{-32x^2}{2000^2} + x$$
**Factor out x:**
$$0 = x \left( \frac{-32x}{4,000,000} + 1 \right)$$

**Solve for x:**
1.  **$x = 0$**: This is the launch point.
2.  **$0 = \frac{-32x}{4,000,000} + 1$**
    $$\frac{32x}{4,000,000} = 1$$
    $$32x = 4,000,000$$
    $$x = \frac{4,000,000}{32} = \mathbf{125,000 \text{ feet}}$$
---
#### 4. Summary Table

| Question | Calculation | Result |
| :--- | :--- | :--- |
| **Launch Point** | $c$ value | $0 \text{ ft}$ |
| **Distance to Peak** | $x = -b/2a$ | $62,500 \text{ ft}$ |
| **Maximum Height** | $f(x)$ at vertex | $31,250 \text{ ft}$ |
| **Total Range** | $x$-intercept | $125,000 \text{ ft}$ |

---
> [!abstract] Algebra Takeaway
> In projectile motion, the parabola is perfectly symmetrical. The horizontal distance to the peak ($62,500$) is exactly **half** of the total range ($125,000$). If you find the vertex $x$-coordinate, you can simply double it to find where the object hits the ground (provided it starts at height 0).

## 2026-March-30 - Introduction to Polynomial Functions (Precalculus - College Algebra 27) : 
https://www.youtube.com/watch?v=6Uh3Z6DJ_pI&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=29
### Introduction to Polynomial Functions

This lecture defines what makes a function a "polynomial" and introduces the vocabulary used to describe their structure, which is essential for predicting their behavior in Calculus.

---
#### 1. What Defines a Polynomial?
A polynomial is a mathematical expression consisting of one or more terms connected by addition or subtraction. 

**The Golden Rules:** [00:10:15]
* **Exponents:** Must be **non-negative integers** (0, 1, 2, 3...). 
    * *No fractions:* $x^{1/2}$ (radicals like $\sqrt{x}$) are **not** allowed. [00:20:40]
    * *No negatives:* $x^{-1}$ (variables in the denominator like $1/x$) are **not** allowed. [00:21:13]
* **Domain:** Because there are no radicals or denominators with variables, the domain of every polynomial is **all real numbers** ($-\infty, \infty$). [00:11:30]
* **Continuity:** The graphs are always smooth, continuous curves with no holes, gaps, or sharp corners (cusps). [00:34:04]

---
#### 2. Key Vocabulary & Standard Form
Standard form requires writing terms in **descending order** of their exponents (highest to lowest). [00:02:20]
* **Leading Term:** The entire first term (e.g., $4x^4$). It dictates the "end behavior" of the graph. [00:05:30]
* **Leading Coefficient:** The number in front of the leading term (e.g., $4$). [00:06:40]
* **Degree ($n$):** The value of the **largest exponent** in the polynomial. [00:07:49]
    * Degree tells you the maximum number of x-intercepts ($n$) and the maximum number of turning points ($n-1$).
* **Constant Term:** The number at the end without a variable. If there isn't one, the constant is 0. [00:06:51]

---
#### 3. Identifying Polynomials (Examples)

| Function | Polynomial? | Reason |
| :--- | :--- | :--- |
| $f(x) = 5x^2 + x^4$ | **Yes** | Just needs reordering to $x^4 + 5x^2$. Degree 4. [00:13:42] |
| $h(x) = 9$ | **Yes** | A "Constant Function." Degree 0. [00:17:44] |
| $f(x) = x^{3/2}$ | **No** | Fractional exponents (radicals) are forbidden. [00:20:40] |
| $g(x) = \frac{x^2-1}{x}$ | **No** | Variable in the denominator (Rational Function). [00:21:13] |
| $f(x) = \frac{3x^2-1}{7}$ | **Yes** | The denominator is a constant, not a variable. [00:25:38] |

---
#### 4. The "Fake Distribution" Shortcut [00:30:15]
When a polynomial is factored (e.g., $f(x) = 2(x-1)^2(x+3)$), you don't need to multiply everything out to find the leading term. 

1.  **Identify the highest power in each factor.**
2.  **Apply any exponents outside the parentheses to those powers.**
3.  **Multiply them all together** along with the front coefficient.

**Example:** $f(x) = 2(x-1)^2(x+5)^3(x)$ [00:31:52]
* $(x-1)^2 \rightarrow x^2$
* $(x+5)^3 \rightarrow x^3$
* $(x) \rightarrow x^1$
* **Leading Term:** $2 \cdot x^2 \cdot x^3 \cdot x^1 = \mathbf{2x^6}$ (Degree 6).

---
> [!abstract] Algebra Takeaway
> The **Leading Term** ($a_nx^n$) is the "boss" of the function. It tells you where the graph starts and ends (End Behavior) and the maximum complexity the graph can have (Turning Points). Always put your polynomials in order first to identify the boss!

### Understanding Subscripts in Polynomial Notation

In precalculus and higher-level algebra, you will often see polynomials written in **General Form** using subscripts rather than unique letters for each coefficient.

---
#### 1. The General Formula
Instead of writing $f(x) = ax^2 + bx + c$, mathematicians use a "template" that can work for a polynomial of **any** degree ($n$):

$$f(x) = a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x^1 + a_0$$



---
#### 2. Why Use Subscripts?
Subscripts are used for **indexing** and **organization** for three main reasons:

* **Infinite Capacity:** The alphabet only has 26 letters. If you have a polynomial of degree 30 ($x^{30}$), you would run out of letters ($a, b, c...$) to represent the coefficients. Subscripts allow for an infinite number of coefficients ($a_1, a_2, a_3 \dots a_{100}$).
* **Matching Exponents:** The subscript usually matches the exponent of the variable it belongs to. 
    * $a_2$ is the coefficient for $x^2$.
    * $a_5$ is the coefficient for $x^5$.
    * $a_0$ is the **constant term** (because $x^0 = 1$).
* **Leading Coefficient Identification:** In the term $a_n x^n$, the $n$ tells you exactly which term is the "Boss" (the Leading Term) based on the degree of the polynomial.

---
#### 3. Breakdown of $a_n$ vs. $n$
It is important to distinguish between the **exponent** and the **subscript**:

| Symbol | Name | Role |
| :--- | :--- | :--- |
| $n$ | **Degree/Exponent** | Tells you the "power" and the shape of the graph. |
| $a_n$ | **Coefficient** | The actual number (constant) multiplying that power. |

**Example:** $f(x) = 7x^4 - 3x^2 + 5$
* $a_4 = 7$ (The coefficient of the $x^4$ term)
* $a_3 = 0$ (Because there is no $x^3$ term)
* $a_2 = -3$
* $a_1 = 0$
* $a_0 = 5$ (The constant)

---

> [!abstract] Algebra Takeaway
> Think of a subscript as a **name tag** or a **house address**. It doesn't change the value of the number; it simply tells you which "street" (exponent) that coefficient lives on. If you see $a_n$, it just means "the coefficient belonging to the highest power $n$."

## 2026-March-31 - Power Functions (Precalculus - College Algebra 28) : 
https://www.youtube.com/watch?v=FXTlAPOBA_U&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=30
### Power Functions: End Behavior of Polynomials

This lecture by Professor Leonard focuses on **Power Functions** ($f(x) = ax^n$), which consist of a single term. The primary goal of studying these is to understand the **End Behavior** of more complex polynomials. Since the leading term of any polynomial is a power function, it dictates where the "tails" of the graph go as $x$ approaches infinity. [00:00:17]

---
#### 1. Even vs. Odd Power Functions
Power functions are incredibly predictable because they follow one of two patterns based on their exponent ($n$). [00:02:01]

**Even Power Functions ($n = 2, 4, 6 \dots$)**
* **Symmetry:** Symmetrical about the **y-axis** (mirror image). [00:05:56]
* **Key Points:** Always pass through $(-1, 1)$, $(0, 0)$, and $(1, 1)$. [00:05:04]
* **Shape:** Look like a parabola. As the exponent increases ($x^4, x^6$), the graph becomes "boxier"—flatter near the origin and steeper outside the interval $[-1, 1]$. [00:09:23]
* **Range:** $[0, \infty)$ if $a > 0$; $(-\infty, 0]$ if $a < 0$. [00:17:14]

**Odd Power Functions ($n = 1, 3, 5 \dots$)**
* **Symmetry:** Symmetrical about the **origin** (180-degree rotation). [00:05:49]
* **Key Points:** Always pass through $(-1, -1)$, $(0, 0)$, and $(1, 1)$. [00:04:19]
* **Shape:** $x^1$ is a straight line; $x^3, x^5$ etc., have an "S-curve." Higher exponents make the curve more dramatic and "boxy." [00:07:30]
* **Range:** Always all real numbers $(-\infty, \infty)$. [00:16:43]
---
#### 2. The Four End Behavior Cases
The leading term of any polynomial tells you which of these four "tails" the graph will have: [00:01:06]

| Degree ($n$) | Coefficient ($a$) | End Behavior Description | Visual Path |
| :--- | :--- | :--- | :--- |
| **Even** | **Positive** | Both ends point UP. | Up on Left, Up on Right |
| **Even** | **Negative** | Both ends point DOWN. | Down on Left, Down on Right |
| **Odd** | **Positive** | Starts low, ends high. | Down on Left, Up on Right |
| **Odd** | **Negative** | Starts high, ends low. | Up on Left, Down on Right |

---
#### 3. Graphing with Transformations [00:19:50]
You can graph shifted power functions (like $g(x) = 3(x+2)^5 - 3$) by combining power function properties with transformation rules.

* **Shift:** Use the $h$ and $k$ values to find a "new origin" (in this case, left 2, down 3). [00:21:06]
* **Key Points:** Start from your new origin and apply the key points ($1, 1$) and $(-1, \pm 1)$ based on whether the power is even or odd. [00:22:50]
* **Stretch/Reflection:** Multiply the $y$-values of your key points by the leading coefficient ($a$) before plotting them relative to the new origin. [00:22:31]

---
> [!abstract] Algebra Takeaway
> A power function is the "skeleton" of a polynomial. No matter how many terms a polynomial has in the middle, the **Leading Term** is the only thing that matters for the ends of the graph. If you know if the degree is even/odd and if the coefficient is positive/negative, you know exactly where the graph is headed at infinity. [00:10:50]

## 2026-April-01 - Multiplicity and End Behavior of Polynomials (Precalculus - College Algebra 29) : 
https://www.youtube.com/watch?v=Gxh-mEt1K-o&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=34
### Multiplicity and End Behavior of Polynomials

This lecture by Professor Leonard focuses on the features of polynomials that allow for accurate sketching with minimal work. The core concepts are how a graph interacts with the x-axis at its roots (Multiplicity) and where the "tails" of the graph go (End Behavior).

---
#### 1. Multiplicity of Zeros
**Multiplicity** refers to how many times a specific zero (root/x-intercept) is repeated in a polynomial. This is determined by the exponent on the factor from which the zero is derived. [00:01:07]

* **Even Multiplicity (2, 4, 6...):** The graph **bounces** or **touches** the x-axis at that point but does not cross it. [00:14:46]
    * *Reason:* In the "neighborhood" (zoom-in) of the root, the sign of the function stays the same on both sides because an even exponent results in the same sign for both positive and negative inputs. [00:15:55]
* **Odd Multiplicity (1, 3, 5...):** The graph **crosses** the x-axis at that point. [00:18:13]
    * *Reason:* Odd exponents preserve the sign change that occurs when moving from one side of the zero to the other. [00:20:29]

---
#### 2. End Behavior & The Leading Term
The **Leading Term** ($a_n x^n$) dictates what the graph does as $x$ approaches positive or negative infinity. This is because, at extreme values, the highest power dominates all other terms. [00:23:00]

| Degree ($n$) | Coefficient ($a_n$) | Left Tail ($x \to -\infty$) | Right Tail ($x \to \infty$) | Pattern                        |
| :----------- | :------------------ | :-------------------------- | :-------------------------- | :----------------------------- |
| **Even**     | **Positive**        | Up ($\uparrow$)             | Up ($\uparrow$)             | Both Up                        |
| **Even**     | **Negative**        | Down ($\downarrow$)         | Down ($\downarrow$)         | Both Down                      |
| **Odd**      | **Positive**        | Down ($\downarrow$)         | Up ($\uparrow$)             | Opposite (Start Low, End High) |
| **Odd**      | **Negative**        | Up ($\uparrow$)             | Down ($\downarrow$)         | Opposite (Start High, End Low) |

---
#### 3. "Fake Distribution" for Factored Forms [00:34:37]
When a polynomial is already factored, you don't need to fully distribute it to find the leading term. Instead, multiply the leading coefficient and the variables from each factor, accounting for their exponents.

**Example:** $f(x) = 7x^2(x-2)(x+0.5)^4(x+3)^5$
* Combine: $7 \cdot (x^2) \cdot (x^1) \cdot (x^4) \cdot (x^5)$
* Add exponents: $2 + 1 + 4 + 5 = 12$
* **Leading Term:** $7x^{12}$ (Degree 12, Positive coefficient). Both tails go **UP**. [00:35:44]
---
#### 4. Turning Points and Smoothness
* **Turning Points:** These are local maximums or minimums where the graph changes direction. A polynomial of degree $n$ can have **at most $n-1$** turning points. [00:31:03]
* **Continuity:** Polynomials are always smooth and continuous. There are **no gaps, holes, asymptotes, or sharp corners (cusps)**. [00:33:01]
---
> [!abstract] Algebra Takeaway
> To sketch a polynomial quickly: 
> 1. Identify the **Leading Term** to draw the "tails" (End Behavior). 
> 2. Plot the **Zeros** on the x-axis. 
> 3. Use **Multiplicity** to decide if you "bounce" or "cross" at each zero. 
> 4. Connect everything with a **smooth, continuous curve**. [00:33:41]

## 2026-April-02 - Creating Polynomials from Real Zeros (Precalculus - College Algebra 30) : 
https://www.youtube.com/watch?v=v-pnhWbHmQ8&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=32
### Creating Polynomials from Real Zeros (Professor Leonard)

This lecture explains how to reverse-engineer a polynomial function if you are given its x-intercepts (zeros/roots) or its graph.

---
#### 1. The Core Concept: Zero Product Property in Reverse
When we solve a polynomial, we set factors to zero to find the intercepts. To create a polynomial, we take the intercepts and turn them back into factors. [00:05:46]

**The Process:**
1.  **Identify Zeros:** e.g., $x = -3, x = 4, x = 0$.
2.  **Create Factors:** Set each equal to zero.
    * $x + 3 = 0 \rightarrow (x+3)$
    * $x - 4 = 0 \rightarrow (x-4)$
    * $x = 0 \rightarrow (x)$
3.  **Build the Function:** $f(x) = a(x)(x+3)(x-4)$

---
#### 2. The Role of "a" (The Family of Curves)
Without a specific point off the x-axis, you cannot determine a unique polynomial. You must include a leading coefficient $a$. [00:11:02]
* Any constant $a$ (like 7 or -7) will result in the **same x-intercepts**.
* The value of $a$ only changes the "dramaticness" (vertical stretch/compression) or orientation (reflection) of the graph. [00:10:23]

---
#### 3. Matching the Degree and Multiplicity [00:22:50]
If a problem specifies a degree (e.g., "Degree 4"), your factors must account for that. This is handled via **Multiplicity** (exponents on the factors).
* **Crossing:** Use an **odd** multiplicity (usually 1). [00:36:05]
* **Bouncing/Touching:** Use an **even** multiplicity (usually 2). [00:36:45]
**Example Check:** Zeros at $-2$ (mult 2), $5$ (mult 1), $0$ (mult 3). [00:28:30]
* $f(x) = a(x)^3(x+2)^2(x-5)^1$
* **Fake Distribution:** $x^3 \cdot x^2 \cdot x^1 = x^6$. This is a Degree 6 polynomial. [00:31:06]

---
#### 4. Solving for a Specific Polynomial [00:43:10]
If you are given a graph with a point **off the x-axis** (like a y-intercept), you can solve for the exact value of $a$.
**The "Specific Curve" Steps:** [00:44:42]
1.  Write the general form: $f(x) = a(factor_1)(factor_2)...$
2.  Plug in the coordinates $(x, y)$ of the extra point.
3.  Solve the resulting linear equation for $a$.
4.  Rewrite the final function with the calculated $a$ value. [00:46:27]

---
#### 5. Fractional Zeros Shortcut [00:31:35]
If a zero is a fraction, such as $x = 1/2$:
* **Factor Method A:** $(x - 1/2)$
* **Factor Method B:** Multiply by 2 and subtract 1 $\rightarrow (2x - 1)$
* *Note:* Both produce the same zero, but Method A is preferred for synthetic division, while Method B is cleaner for standard form. [00:31:54]
---

> [!abstract] Algebra Takeaway
> To build a polynomial: **Zeros $\rightarrow$ Factors $\rightarrow$ Multiplicity $\rightarrow$ Solve for $a$.**
> Always verify your final "fake distribution" against the required degree and end behavior to ensure the graph matches the equation. [00:57:42]

### Finding Zeros (x-intercepts) for f(x) = x² + 2x - 8

To find the zeros of a quadratic function, we set $f(x) = 0$ and solve for $x$. These values represent where the graph crosses the x-axis.

---
#### 1. Set the Function to Zero
$$x^2 + 2x - 8 = 0$$

---
#### 2. Factor the Quadratic
We need two numbers that:
* **Multiply** to give $ac$ ($1 \cdot -8 = -8$)
* **Add** to give $b$ ($2$)

The factors of $-8$ are:
* $-1, 8$ (Sum: $7$)
* $1, -8$ (Sum: $-7$)
* $-2, 4$ (Sum: **$2$**) $\leftarrow$ **This is our pair.**

**Write in Factored Form:**
$$(x - 2)(x + 4) = 0$$

---
#### 3. Solve for x (Zero Product Property)
Set each factor equal to zero:
* $x - 2 = 0 \Rightarrow \mathbf{x = 2}$
* $x + 4 = 0 \Rightarrow \mathbf{x = -4}$

**The x-intercepts are at $(2, 0)$ and $(-4, 0)$.**

---
#### 4. Graphical Description
* **Orientation:** Since the leading coefficient ($a=1$) is positive, the parabola opens **upward**.
* **Intercepts:** The graph crosses the x-axis at $x = -4$ and $x = 2$.
* **Multiplicity:** Both zeros have a multiplicity of **1** (the factors are $(x-2)^1$ and $(x+4)^1$), so the graph **crosses** straight through the x-axis at both points rather than bouncing.
* **Y-intercept:** Plugging in $x=0$ gives $f(0) = -8$, so the graph crosses the y-axis at $(0, -8)$.

---

> [!abstract] Algebra Takeaway
> The zeros of a polynomial are the "DNA" of its graph. By finding $x = 2$ and $x = -4$, you've identified the two most critical points on the horizontal axis. Because the degree is 2, you know there can be at most two real zeros, which we have found here.

### Creating a Polynomial from Zeros: x = -3, 4, 1, 0

To build the polynomial for your Obsidian notes, we transform each x-intercept (zero) into a linear factor and then combine them into a single function.

---
#### 1. Define the Factors
Using the Zero Product Property in reverse, an intercept at $x = c$ corresponds to a factor $(x - c)$.

* **For $x = -3$:** The factor is $(x - (-3)) \Rightarrow \mathbf{(x + 3)}$
* **For $x = 4$:** The factor is $\mathbf{(x - 4)}$
* **For $x = 1$:** The factor is $\mathbf{(x - 1)}$
* **For $x = 0$:** The factor is $(x - 0) \Rightarrow \mathbf{x}$

---
#### 2. Build the General Function
A polynomial with these specific zeros belongs to a "family" of curves defined by a leading coefficient $a$.

$$f(x) = a \cdot x(x + 3)(x - 4)(x - 1)$$

*Note: Unless a specific point off the x-axis is provided, we typically assume $a = 1$ for the simplest version of the polynomial.*

---
#### 3. Standard Form (Optional Distribution)
To write the polynomial in standard form, we multiply the factors together:

1.  **Multiply $(x+3)(x-4)$:** $x^2 - 4x + 3x - 12 = x^2 - x - 12$
2.  **Multiply $(x)(x-1)$:** $x^2 - x$
3.  **Multiply the results:** $(x^2 - x - 12)(x^2 - x)$
    * $x^2(x^2 - x) = x^4 - x^3$
    * $-x(x^2 - x) = -x^3 + x^2$
    * $-12(x^2 - x) = -12x^2 + 12x$

**Combine Like Terms:**
$$\mathbf{f(x) = x^4 - 2x^3 - 11x^2 + 12x}$$
---
#### 4. Graphical Description
* **Degree:** This is a **Degree 4 (Quartic)** polynomial.
* **End Behavior:** Since the degree is even and the leading coefficient ($a=1$) is positive, both "tails" of the graph point **UP** $( \uparrow, \uparrow )$.
* **Intercept Behavior:** Each zero has a multiplicity of **1**, so the graph **crosses** through the x-axis at all four locations $(-3, 0, 1, 4)$.
* **Turning Points:** Since $n=4$, the graph has a maximum of **3 turning points** (peaks or valleys).

---

> [!abstract] Algebra Takeaway
> To go from intercepts to an equation, simply "flip the signs" into parentheses and multiply them by $x$ for any zero at the origin. The final degree of your polynomial should always match the total number of real zeros (counting multiplicities).

### Creating a Polynomial from Zeros: x = -1, 0, 4, -9 (Degree 4)

To build this polynomial for your Obsidian notes, we transform each given x-intercept into its corresponding linear factor. Since we have four distinct zeros and are asked for a **Degree 4** polynomial, each factor will have a multiplicity of 1.

---
#### 1. Define the Factors
For any zero $c$, the factor is $(x - c)$.

* **For $x = -1$:** $(x - (-1)) \Rightarrow \mathbf{(x + 1)}$
* **For $x = 0$:** $(x - 0) \Rightarrow \mathbf{x}$
* **For $x = 4$:** $\mathbf{(x - 4)}$
* **For $x = -9$:** $(x - (-9)) \Rightarrow \mathbf{(x + 9)}$

---
#### 2. Build the Function (Factored Form)
Combining these factors gives the simplest version of the polynomial (assuming a leading coefficient $a = 1$):

$$f(x) = x(x + 1)(x - 4)(x + 9)$$

---
#### 3. Standard Form (Distribution)
To expand this into a standard polynomial expression:

1.  **Multiply $(x+1)(x-4)$:**
    $x^2 - 4x + x - 4 = \mathbf{x^2 - 3x - 4}$
2.  **Multiply the result by $(x+9)$:**
    $(x^2 - 3x - 4)(x + 9)$
    $= x^2(x + 9) - 3x(x + 9) - 4(x + 9)$
    $= (x^3 + 9x^2) - (3x^2 + 27x) - (4x + 36)$
    $= x^3 + 6x^2 - 31x - 36$
3.  **Multiply the entire result by $x$:**
    $$\mathbf{f(x) = x^4 + 6x^3 - 31x^2 - 36x}$$
---
#### 4. Graphical Description
* **Degree:** This is a **Degree 4 (Quartic)** polynomial, consistent with the requirement.
* **End Behavior:** Since the degree is even ($n=4$) and the leading coefficient ($a=1$) is positive, both "tails" point **UP** $(\uparrow, \uparrow)$.
* **Intercept Behavior:** Because each zero has an **odd multiplicity (1)**, the graph **crosses** the x-axis at all four points: $x = -9, -1, 0, \text{ and } 4$.
* **Turning Points:** The graph will have **3 turning points** (two relative minimums and one relative maximum).
---
> [!abstract] Algebra Takeaway
> When given exactly $n$ zeros for a polynomial of degree $n$, each zero is a simple root that crosses the axis. The constant zero ($x=0$) is always represented by a standalone $x$ factor outside of parentheses.

### Creating a Polynomial from Zeros: x = 1 (Mult 1) and x = 2 (Mult 2)

To build this degree 3 polynomial for your Obsidian notes, we translate each zero and its given multiplicity into a specific factor with a matching exponent.

---
#### 1. Define the Factors and Multiplicities
The multiplicity of a zero becomes the exponent of its corresponding linear factor.

* **For $x = 1$ (Multiplicity 1):** The factor is $(x - 1)^1$, or simply $\mathbf{(x - 1)}$.
* **For $x = 2$ (Multiplicity 2):** The factor is $(x - 2)^2$, which is $\mathbf{(x - 2)(x - 2)}$.

---
#### 2. Build the Function (Factored Form)
Combining these factors creates a polynomial of **Degree 3** ($1 + 2 = 3$), satisfying the requirement.

$$f(x) = a(x - 1)(x - 2)^2$$

*Assuming the simplest leading coefficient $a = 1$:*
$$f(x) = (x - 1)(x - 2)^2$$

---
#### 3. Standard Form (Distribution)
To expand this into a standard polynomial expression:

1.  **Expand the Squared Factor $(x-2)^2$:**
    $$(x - 2)(x - 2) = x^2 - 4x + 4$$
2.  **Multiply by the Remaining Factor $(x-1)$:**
    $$(x - 1)(x^2 - 4x + 4)$$
    $= x(x^2 - 4x + 4) - 1(x^2 - 4x + 4)$
    $= (x^3 - 4x^2 + 4x) - (x^2 - 4x + 4)$
    $= x^3 - 5x^2 + 8x - 4$

**Final Polynomial:**
$$\mathbf{f(x) = x^3 - 5x^2 + 8x - 4}$$

---
#### 4. Graphical Description
* **Degree:** This is a **Degree 3 (Cubic)** polynomial.
* **End Behavior:** Since the degree is odd ($n=3$) and the leading coefficient ($a=1$) is positive, the graph starts low and ends high (Down on Left, Up on Right).
* **Intercept Behavior:**
    * **At $x = 1$:** The multiplicity is **odd (1)**, so the graph **crosses** the x-axis.
    * **At $x = 2$:** The multiplicity is **even (2)**, so the graph **bounces** off the x-axis (it touches $y=0$ and turns back up).
* **Turning Points:** The graph has **2 turning points** (one local maximum and one local minimum at $x=2$).
---

> [!abstract] Algebra Takeaway
> Multiplicity dictates the "touch" of the graph. A multiplicity of 2 creates a parabolic "U" shape at that specific x-intercept. When checking your work, ensure the sum of all multiplicities equals the required degree of the polynomial.

### Creating a Polynomial from Zeros: Degree 9

To build this Degree 9 polynomial, we translate each zero and its specific multiplicity into a factor with a matching exponent. The sum of the multiplicities ($2 + 1 + 3 + 3$) equals **9**, confirming the degree.

---
#### 1. Define the Factors and Multiplicities
Using the zero-to-factor rule: a zero at $c$ with multiplicity $k$ becomes $(x - c)^k$.

* **For $x = -2$ (Mult 2):** $(x - (-2))^2 \Rightarrow \mathbf{(x + 2)^2}$
* **For $x = 5$ (Mult 1):** $\mathbf{(x - 5)}$
* **For $x = 0$ (Mult 3):** $(x - 0)^3 \Rightarrow \mathbf{x^3}$
* **For $x = 1/2$ (Mult 3):** $(x - 1/2)^3$ 
    * *Note:* To avoid fractions in the factors, we can use the form $\mathbf{(2x - 1)^3}$.

---
#### 2. Build the Function (Factored Form)
Combining these gives the polynomial in its most useful form for identifying behavior:

$$f(x) = a \cdot x^3(x + 2)^2(x - 5)(2x - 1)^3$$

*Assuming the simplest leading coefficient $a = 1$:*
$$f(x) = x^3(x + 2)^2(x - 5)(2x - 1)^3$$
---
#### 3. Analyzing the Polynomial (Degree & End Behavior)
* **Verify Degree:** $$x^3 \cdot x^2 \cdot x^1 \cdot x^3 = x^{(3+2+1+3)} = \mathbf{x^9}$$
* **Leading Coefficient:** Since we used $(2x-1)^3$, the leading term is $1 \cdot 1 \cdot 1 \cdot 2^3 = \mathbf{8x^9}$.
* **End Behavior:** Since the degree is **Odd (9)** and the leading coefficient is **Positive (8)**, the graph starts low and ends high (Down on Left, Up on Right).
---
#### 4. Intercept Behavior (Multiplicity Table)

| Zero ($x$) | Multiplicity | Graph Behavior | Visual Description |
| :--- | :--- | :--- | :--- |
| **$-2$** | **2 (Even)** | **Bounce** | Touches the axis and turns back up like a parabola. |
| **$5$** | **1 (Odd)** | **Cross** | Passes straight through the axis like a line. |
| **$0$** | **3 (Odd)** | **Cross/Flatten** | Passes through but "flattens out" like an $x^3$ curve. |
| **$1/2$** | **3 (Odd)** | **Cross/Flatten** | Passes through while flattening against the axis. |

---

> [!abstract] Algebra Takeaway
> When building high-degree polynomials, the **sum of multiplicities** must always match the **degree**. Even multiplicities create "U" shapes (bounces) at the axis, while odd multiplicities greater than 1 create "S" shapes (flattened crosses) at the axis.

## 2026-April-03 - How to Sketch Polynomial Functions (Precalculus - College Algebra 31) :
https://www.youtube.com/watch?v=6MAtqY6Fqjs&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=34
### Sketching Polynomial Functions (Professor Leonard Summary)

This summary covers the systematic approach to sketching polynomials from their factored forms as detailed by Professor Leonard.

---
#### 1. The Leading Term & End Behavior
Instead of fully distributing a complex factored polynomial, use "fake distribution" to find the **Leading Term** ($ax^n$).
* **How to find it:** Multiply the leading coefficient of the entire function by the highest power of $x$ from each individual factor. [00:03:29]
* **Information gained:**
    * **Degree ($n$):** The sum of all exponents in the factors. [00:06:20]
    * **Max Turning Points:** A polynomial can have at most $n-1$ turning points. [00:06:43]
    * **End Behavior:** Determined by the degree (Even vs. Odd) and the sign of the leading coefficient. [00:07:36]
---
#### 2. Finding Intercepts
* **Y-intercept:** Evaluate the function at $f(0)$. You do not need the standard form; just plug zero into the factored version. [00:09:32]
* **X-intercepts (Zeros):** Set each factor containing a variable equal to zero. [00:10:45]
    * **Note on Irreducible Quadratics:** Factors like $(x^2 + 9)$ yield no real x-intercepts and often represent "hidden" turning points that don't touch the axis. [00:13:35]
---
#### 3. Multiplicity & Axis Behavior
The exponent of each factor (the multiplicity) dictates how the graph interacts with the x-axis at that specific zero. [00:14:46]

| Multiplicity          | Type   | Graph Action                                | Visual Hint                                                  |
| :-------------------- | :----- | :------------------------------------------ | :----------------------------------------------------------- |
| **Odd** (1, 3, 5...)  | Cross  | The graph passes through the axis.          | Higher odd powers (3+) "flatten" at the crossing. [00:16:31] |
| **Even** (2, 4, 6...) | Bounce | The graph touches and turns back (tangent). | Also known as a "Touch." [00:16:25]                          |

---
#### 4. The "Dotted Line" Technique
To avoid common sketching errors, Professor Leonard suggests placing a **vertical dotted line** at any x-intercept with an **even multiplicity** (a bounce). This serves as a visual cue that you are not allowed to cross the axis at that point. [00:26:31]

---
#### 5. Step-by-Step Sketching Workflow
1.  **Leading Term:** Identify degree and end behavior $(\uparrow, \uparrow; \downarrow, \downarrow; \dots)$.
2.  **Intercepts:** Mark the y-intercept and all x-intercepts on the coordinate plane.
3.  **Multiplicity:** Label each x-intercept as a "Cross" or "Bounce."
4.  **Additional Points:** If the y-intercept is $(0,0)$, or to show the "dynamics" (depth) of the curves, plug in x-values between the intercepts. [00:27:45]
5.  **Connect:** Start from the left end behavior, move through each intercept according to its multiplicity, and finish at the right end behavior. [00:29:06]
---
> [!tip] Final Check
> Everything must "mesh." If your end behavior says the graph should end pointing up, but your last intercept is a bounce that keeps you pointing down, you have likely made a sign error or miscalculated a multiplicity. [00:19:52]

### Analysis and Sketching of h(x) = -2(x - 7)(x + 1/2)²(x + 4)³(x² + 9)²

To analyze this complex polynomial for your Obsidian notes, we break it down into its core properties using the "Fake Distribution" method and intercept analysis.

---
#### 1. Finding the Leading Term & Degree
Instead of multiplying everything out, take the leading term from each factor and account for the exponents.

* **Constant Multiplier:** $-2$
* **From $(x - 7)$:** $x^1$
* **From $(x + 1/2)^2$:** $x^2$
* **From $(x + 4)^3$:** $x^3$
* **From $(x^2 + 9)^2$:** $(x^2)^2 = x^4$

**Leading Term Calculation:**
$$(-2) \cdot (x^1) \cdot (x^2) \cdot (x^3) \cdot (x^4) = \mathbf{-2x^{10}}$$

* **Degree ($n$):** **10** (The sum of exponents: $1+2+3+4$).
* **Leading Coefficient ($a_n$):** **$-2$**.

---
#### 2. Max Turning Points (TP) & End Behavior
* **Max Turning Points:** $n - 1 = 10 - 1 = \mathbf{9}$.
* **End Behavior:**
    * Since the degree is **Even (10)**, the tails point in the **Same** direction.
    * Since the leading coefficient is **Negative (-2)**, both tails point **Down**.
    * **Notation:** As $x \to \pm\infty, f(x) \to -\infty$.
---
#### 3. Intercepts and Multiplicity
To find the x-intercepts, set each factor to zero.

| Factor | Zero ($x$) | Multiplicity | Behavior on Graph |
| :--- | :--- | :--- | :--- |
| $(x - 7)$ | **$7$** | $1$ (Odd) | **Cross** (Straight) |
| $(x + 1/2)^2$ | **$-1/2$** | $2$ (Even) | **Bounce** (Parabolic) |
| $(x + 4)^3$ | **$-4$** | $3$ (Odd) | **Cross** (Flattened/S-curve) |
| $(x^2 + 9)^2$ | **None** | N/A | **Irreducible** (No real zeros) |

*Note: The factor $(x^2+9)^2$ never equals zero for real numbers. It adds to the degree but does not create an x-intercept.*

**Y-Intercept:**
Plug in $x = 0$:
$$h(0) = -2(0 - 7)(0 + 1/2)^2(0 + 4)^3(0^2 + 9)^2$$
$$h(0) = -2(-7)(1/4)(64)(81)$$
$$h(0) = 14 \cdot 16 \cdot 81 = \mathbf{18,144}$$
The y-intercept is at **$(0, 18144)$**.

---
#### 4. Step-by-Step Graphing Instructions

1.  **Plot the Intercepts:** Mark points at $x = -4$, $x = -1/2$, and $x = 7$ on the x-axis. Mark the y-intercept way up at $18,144$ (or just label it if the scale is tight).
2.  **Draw the Tails:** From the leftmost intercept ($-4$) and rightmost intercept ($7$), draw arrows pointing **Down** into Quadrant III and Quadrant IV.
3.  **Navigate from Left to Right:**
    * **At $x = -4$:** Approach from below and **Cross** with an "S-curve" (flattening out).
    * **Heading to $-1/2$:** The graph must turn back down toward the axis.
    * **At $x = -1/2$:** Reach the axis and **Bounce** (touch and turn back down).
    * **Heading to $y$-intercept:** Turn up to hit the y-axis at $18,144$.
    * **Heading to $x = 7$:** Turn back toward the x-axis.
    * **At $x = 7$:** **Cross** straight through the axis to meet the right-side tail pointing down.

---

> [!abstract] Algebra Takeaway
> Even though this is a Degree 10 polynomial, it only touches the x-axis 3 times. The "missing" zeros from $(x^2+9)^2$ mean the graph has complex turns or "wiggles" in the coordinate plane that don't result in intercepts. Always trust your **End Behavior** and **Multiplicity** to guide the flow of the sketch.

### Analysis and Sketching of f(x) = x²(x - 3)

To analyze this cubic polynomial for your Obsidian notes, we break it down into its core properties using the "Fake Distribution" method and intercept analysis.

---
#### 1. Finding the Leading Term & Degree
For factored polynomials, we multiply the leading term of each factor together, accounting for their exponents.

* **From $x^2$:** $x^2$
* **From $(x - 3)$:** $x^1$

**Leading Term Calculation:**
$$(x^2) \cdot (x^1) = \mathbf{x^3}$$

* **Degree ($n$):** **3** (Cubic).
* **Leading Coefficient ($a_n$):** **1** (Positive).

---
#### 2. Max Turning Points (TP) & End Behavior
* **Max Turning Points:** $n - 1 = 3 - 1 = \mathbf{2}$.
* **End Behavior:**
    * Since the degree is **Odd (3)**, the tails point in **Opposite** directions.
    * Since the leading coefficient is **Positive (1)**, the graph starts **Low** and ends **High**.
    * **Notation:** As $x \to -\infty, f(x) \to -\infty$ and as $x \to \infty, f(x) \to \infty$.
---
#### 3. Intercepts and Multiplicity
To find the x-intercepts, set each factor to zero and identify its exponent.

| Factor | Zero ($x$) | Multiplicity | Behavior on Graph |
| :--- | :--- | :--- | :--- |
| $x^2$ | **0** | $2$ (Even) | **Bounce** (Parabolic touch) |
| $(x - 3)$ | **3** | $1$ (Odd) | **Cross** (Straight through) |

**Y-Intercept:**
Evaluate the function at $x = 0$:
$$f(0) = (0)^2(0 - 3) = \mathbf{0}$$
The y-intercept is at **$(0, 0)$**. (Note: If $0$ is an x-intercept, it is automatically the y-intercept).

---
#### 4. Step-by-Step Graphing Instructions

1.  **Plot the Intercepts:** Mark points at $x = 0$ and $x = 3$ on the x-axis.
2.  **Draw the Tails:** Based on the end behavior, draw an arrow pointing **Down** from the far left (Quadrant III) and an arrow pointing **Up** from the far right (Quadrant I).
3.  **Navigate from Left to Right:**
    * **Approach $x = 0$:** Start from the bottom-left tail and move toward the origin.
    * **At $x = 0$:** Because the multiplicity is **Even (2)**, the graph reaches the origin and **Bounces** back down into Quadrant IV.
    * **Turn toward $x = 3$:** The graph must eventually turn back up to reach the next intercept. (This creates a "local minimum" between 0 and 3).
    * **At $x = 3$:** Because the multiplicity is **Odd (1)**, the graph **Crosses** straight through the axis and continues upward to meet the right-side tail.
---

> [!abstract] Algebra Takeaway
> In this function, the $x^2$ factor acts like a mini-parabola at the origin. Even though the overall function is a cubic ($x^3$), the "square" on the $x$ factor forces the graph to kiss the axis and turn around at that specific point.

### Analysis and Sketching of f(x) = -2(x + 2)(x - 2)³

To analyze this quartic polynomial for your Obsidian notes, we break it down into its core properties using the "Fake Distribution" method and intercept analysis.

---
#### 1. Finding the Leading Term & Degree
Multiply the leading coefficient by the highest power of $x$ from each individual factor.

* **Constant Multiplier:** $-2$
* **From $(x + 2)$:** $x^1$
* **From $(x - 2)^3$:** $x^3$

**Leading Term Calculation:**
$$(-2) \cdot (x^1) \cdot (x^3) = \mathbf{-2x^4}$$

* **Degree ($n$):** **4** (Quartic).
* **Leading Coefficient ($a_n$):** **$-2$** (Negative).

---
#### 2. Max Turning Points (TP) & End Behavior
* **Max Turning Points:** $n - 1 = 4 - 1 = \mathbf{3}$.
* **End Behavior:**
    * Since the degree is **Even (4)**, the tails point in the **Same** direction.
    * Since the leading coefficient is **Negative (-2)**, both tails point **Down**.
    * **Notation:** As $x \to \pm\infty, f(x) \to -\infty$.
---
#### 3. Intercepts and Multiplicity
To find the x-intercepts, set each factor to zero and identify its exponent.

| Factor | Zero ($x$) | Multiplicity | Behavior on Graph |
| :--- | :--- | :--- | :--- |
| $(x + 2)$ | **$-2$** | $1$ (Odd) | **Cross** (Straight through) |
| $(x - 2)^3$ | **$2$** | $3$ (Odd) | **Cross** (Flattened/S-curve) |

**Y-Intercept:**
Evaluate the function at $x = 0$:
$$f(0) = -2(0 + 2)(0 - 2)^3$$
$$f(0) = -2(2)(-8) = \mathbf{32}$$
The y-intercept is at **$(0, 32)$**.

---
#### 4. Step-by-Step Graphing Instructions

1.  **Plot the Intercepts:** Mark points at $x = -2$ and $x = 2$ on the x-axis, and $y = 32$ on the y-axis.
2.  **Draw the Tails:** Draw arrows pointing **Down** from the far left (Quadrant III) and the far right (Quadrant IV).
3.  **Navigate from Left to Right:**
    * **At $x = -2$:** Approach from below and **Cross** the axis relatively straight (multiplicity 1).
    * **Connect to Y-intercept:** Continue upward to pass through $(0, 32)$. This will likely be the peak (local maximum) of the graph.
    * **At $x = 2$:** Head back down toward the x-axis. Because the multiplicity is **Odd (3)**, the graph will **Cross** the axis, but it must "flatten out" (horizontal tangent) as it passes through $x = 2$, resembling an $x^3$ shape.
    * **Final Path:** Once through $x = 2$, continue downward to meet the right-side tail pointing to negative infinity.
---

> [!abstract] Algebra Takeaway
> This is a "U-shaped" graph (even degree) that has been flipped upside down (negative coefficient). The cubic factor $(x-2)^3$ is what gives the graph its characteristic "shelf" or "flat spot" on the right side of the peak.

### Analysis and Sketching of h(x) = (x + 4)²(1 - x)

To analyze this cubic polynomial for your Obsidian notes, we break it down into its core properties using the "Fake Distribution" method and intercept analysis.

---
#### 1. Finding the Leading Term & Degree
Multiply the leading term of each factor together, being careful with the signs.

* **From $(x + 4)^2$:** $x^2$
* **From $(1 - x)$:** $-x$ (Note the negative sign on the variable)

**Leading Term Calculation:**
$$(x^2) \cdot (-x) = \mathbf{-x^3}$$

* **Degree ($n$):** **3** (Cubic).
* **Leading Coefficient ($a_n$):** **$-1$** (Negative).

---
#### 2. Max Turning Points (TP) & End Behavior
* **Max Turning Points:** $n - 1 = 3 - 1 = \mathbf{2}$.
* **End Behavior:**
    * Since the degree is **Odd (3)**, the tails point in **Opposite** directions.
    * Since the leading coefficient is **Negative (-1)**, the graph starts **High** and ends **Low**.
    * **Notation:** As $x \to -\infty, f(x) \to \infty$ and as $x \to \infty, f(x) \to -\infty$.
---
#### 3. Intercepts and Multiplicity
To find the x-intercepts, set each factor to zero and identify its exponent.

| Factor | Zero ($x$) | Multiplicity | Behavior on Graph |
| :--- | :--- | :--- | :--- |
| $(x + 4)^2$ | **$-4$** | $2$ (Even) | **Bounce** (Parabolic touch) |
| $(1 - x)$ | **$1$** | $1$ (Odd) | **Cross** (Straight through) |

**Y-Intercept:**
Evaluate the function at $x = 0$:
$$h(0) = (0 + 4)^2(1 - 0)$$
$$h(0) = (16)(1) = \mathbf{16}$$
The y-intercept is at **$(0, 16)$**.

---
#### 4. Step-by-Step Graphing Instructions

1.  **Plot the Intercepts:** Mark points at $x = -4$ and $x = 1$ on the x-axis, and $y = 16$ on the y-axis.
2.  **Draw the Tails:** Based on the end behavior, draw an arrow pointing **Up** from the far left (Quadrant II) and an arrow pointing **Down** from the far right (Quadrant IV).
3.  **Navigate from Left to Right:**
    * **Approach $x = -4$:** Start from the top-left tail and move toward $x = -4$.
    * **At $x = -4$:** Because the multiplicity is **Even (2)**, the graph reaches the axis and **Bounces** back up into Quadrant II.
    * **Pass through Y-intercept:** Continue upward to pass through $(0, 16)$. This will likely be the peak (local maximum).
    * **At $x = 1$:** Head back down toward the x-axis. Because the multiplicity is **Odd (1)**, the graph **Crosses** straight through the axis.
    * **Final Path:** Once through $x = 1$, continue downward to meet the right-side tail pointing to negative infinity.
---

> [!abstract] Algebra Takeaway
> The term $(1-x)$ is a common "trick" in polynomial problems. Because the $x$ is negative, it flips the entire cubic graph upside down. Always check the sign of the variable inside each set of parentheses when calculating your leading term.

### Analysis and Sketching of f(x) = -5x(x² - 4)(x + 3)

To analyze this polynomial for your Obsidian notes, we first identify that the term $(x^2 - 4)$ is a **Difference of Squares**. For the most accurate intercept and multiplicity analysis, it is best to fully factor the function first.

**Factored Form:**
$$f(x) = -5x(x - 2)(x + 2)(x + 3)$$

---
#### 1. Finding the Leading Term & Degree
Multiply the leading coefficient by the highest power of $x$ from each individual factor.

* **Constant Multiplier:** $-5$
* **From $x$:** $x^1$
* **From $(x^2 - 4)$:** $x^2$
* **From $(x + 3)$:** $x^1$

**Leading Term Calculation:**
$$(-5) \cdot (x^1) \cdot (x^2) \cdot (x^1) = \mathbf{-5x^4}$$

* **Degree ($n$):** **4** (Quartic).
* **Leading Coefficient ($a_n$):** **$-5$** (Negative).

---
#### 2. Max Turning Points (TP) & End Behavior
* **Max Turning Points:** $n - 1 = 4 - 1 = \mathbf{3}$.
* **End Behavior:**
    * Since the degree is **Even (4)**, the tails point in the **Same** direction.
    * Since the leading coefficient is **Negative (-5)**, both tails point **Down**.
    * 
    * **Notation:** As $x \to \pm\infty, f(x) \to -\infty$.

---
#### 3. Intercepts and Multiplicity
Using the fully factored form $f(x) = -5x(x - 2)(x + 2)(x + 3)$:

| Factor | Zero ($x$) | Multiplicity | Behavior on Graph |
| :--- | :--- | :--- | :--- |
| $-5x$ | **$0$** | $1$ (Odd) | **Cross** (Straight through) |
| $(x - 2)$ | **$2$** | $1$ (Odd) | **Cross** (Straight through) |
| $(x + 2)$ | **$-2$** | $1$ (Odd) | **Cross** (Straight through) |
| $(x + 3)$ | **$-3$** | $1$ (Odd) | **Cross** (Straight through) |

**Y-Intercept:**
Evaluate at $f(0)$:
$$f(0) = -5(0)(0^2 - 4)(0 + 3) = \mathbf{0}$$
The y-intercept is at **$(0, 0)$**.

---
#### 4. Step-by-Step Graphing Instructions

1.  **Plot the Intercepts:** Mark points at $x = -3, -2, 0, \text{ and } 2$ on the x-axis.
2.  **Draw the Tails:** Draw arrows pointing **Down** from the far left (past $-3$) and the far right (past $2$).
3.  **Navigate from Left to Right:**
    * **At $x = -3$:** Approach from the bottom-left and **Cross** the axis moving upward.
    * **At $x = -2$:** Turn back down and **Cross** the axis moving downward.
    * **At $x = 0$:** Turn back up and **Cross** the axis moving upward through the origin.
    * **At $x = 2$:** Turn back down one last time and **Cross** the axis moving downward.
    * **Final Path:** Continue downward to meet the right-side tail pointing to negative infinity.
---

> [!abstract] Algebra Takeaway
> Because every single zero in this function has a multiplicity of 1, the graph is a classic "W" shape (flipped upside down into an "M" shape). There are no bounces or flat spots; the graph simply weaves in and out of the x-axis four times.

### Analysis and Sketching of g(x) = 2(x - 1)²(x² - 16)

To analyze this polynomial for your Obsidian notes, we first identify that the term $(x^2 - 16)$ is a **Difference of Squares**. Fully factoring the function is the most reliable way to determine intercepts and multiplicity.

**Factored Form:**
$$g(x) = 2(x - 1)^2(x - 4)(x + 4)$$

---
#### 1. Finding the Leading Term & Degree
Multiply the leading coefficient by the highest power of $x$ from each individual factor.

* **Constant Multiplier:** $2$
* **From $(x - 1)^2$:** $x^2$
* **From $(x^2 - 16)$:** $x^2$

**Leading Term Calculation:**
$$(2) \cdot (x^2) \cdot (x^2) = \mathbf{2x^4}$$

* **Degree ($n$):** **4** (Quartic).
* **Leading Coefficient ($a_n$):** **$2$** (Positive).

---
#### 2. Max Turning Points (TP) & End Behavior
* **Max Turning Points:** $n - 1 = 4 - 1 = \mathbf{3}$.
* **End Behavior:**
    * Since the degree is **Even (4)**, the tails point in the **Same** direction.
    * Since the leading coefficient is **Positive (2)**, both tails point **Up**.
    * 
    * **Notation:** As $x \to \pm\infty, g(x) \to \infty$.

---
#### 3. Intercepts and Multiplicity
Using the fully factored form $g(x) = 2(x - 1)^2(x - 4)(x + 4)$:

| Factor | Zero ($x$) | Multiplicity | Behavior on Graph |
| :--- | :--- | :--- | :--- |
| $(x - 1)^2$ | **$1$** | $2$ (Even) | **Bounce** (Parabolic touch) |
| $(x - 4)$ | **$4$** | $1$ (Odd) | **Cross** (Straight through) |
| $(x + 4)$ | **$-4$** | $1$ (Odd) | **Cross** (Straight through) |

**Y-Intercept:**
Evaluate at $g(0)$:
$$g(0) = 2(0 - 1)^2(0^2 - 16)$$
$$g(0) = 2(1)(-16) = \mathbf{-32}$$
The y-intercept is at **$(0, -32)$**.

---
#### 4. Step-by-Step Graphing Instructions

1.  **Plot the Intercepts:** Mark points at $x = -4, 1, \text{ and } 4$ on the x-axis, and $y = -32$ on the y-axis.
2.  **Draw the Tails:** Draw arrows pointing **Up** from the far left (past $-4$) and the far right (past $4$).
3.  **Navigate from Left to Right:**
    * **At $x = -4$:** Approach from the top-left and **Cross** the axis moving downward into Quadrant III.
    * **Pass through Y-intercept:** Continue downward to hit $(0, -32)$.
    * **At $x = 1$:** Turn back up toward the axis. Because the multiplicity is **Even (2)**, the graph reaches the axis and **Bounces** back down into Quadrant IV.
    * **At $x = 4$:** Turn back up one last time and **Cross** the axis moving upward.
    * **Final Path:** Continue upward to meet the right-side tail pointing to positive infinity.
---
> [!abstract] Algebra Takeaway
> This graph creates a "W" shape where one of the middle peaks just barely touches the x-axis. Always remember that the $x^2$ term in $(x^2-16)$ produces *two* separate roots with multiplicity 1, while the $(x-1)^2$ term produces *one* root with multiplicity 2.

## 2026-April-05 - Synthetic Division and Long Division of Polynomials (Precalculus - College Algebra 32) :
https://www.youtube.com/watch?v=AKJgo-WR_K4&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=34
### Summary: Synthetic Division and Long Division of Polynomials

The core purpose of polynomial division is to factor higher-degree polynomials and find their x-intercepts (zeros). This becomes essential when using the **Rational Zeros Theorem** to break down complex functions.
#### 1. Core Theorems
* **Factor Theorem:** If a polynomial $f(x)$ is divided by $(x - c)$ and the remainder is $0$, then $(x - c)$ is a factor of the polynomial. [00:01:20]
* **Remainder Theorem:** If you evaluate a function at a specific value, $f(c)$, the result is exactly the same as the remainder you would get by dividing the polynomial by $(x - c)$. [00:06:36]
#### 2. Long Division of Polynomials
Long division is the "robust" method. It works regardless of the divisor's degree (linear, quadratic, etc.) or its leading coefficient. [00:11:36]

* **Setup:** Ensure the dividend is in descending order. Use "0" as a placeholder for any missing powers of $x$ (e.g., if there is no $x^2$ term, write $0x^2$). [00:08:10]
* **Process:**
    1. Divide the first term of the dividend by the first term of the divisor. [00:12:04]
    2. Multiply the result by the entire divisor. [00:12:34]
    3. **Subtract** the result from the dividend. (Crucial: Subtracting a polynomial flips the signs of all terms in that row). [00:13:37]
    4. Bring down the next term and repeat until the remainder's degree is less than the divisor's.
#### 3. Synthetic Division
Synthetic division is a shorthand "algorithm" using only coefficients. It is much faster but **only works** if the divisor is in the form $(x - c)$ (linear with a leading coefficient of 1). [00:10:59]

* **Process:**
    1. List the coefficients of the polynomial (including 0s for missing terms). [00:22:03]
    2. Use the x-intercept value ($c$) outside the division box, not the factor $(x - c)$. [00:22:31]
    3. Bring down the first coefficient. [00:23:35]
    4. Multiply the value outside by the value at the bottom, place it under the next coefficient, and **add**. [00:24:34]
    5. The final number in the row is the **Remainder**. [00:25:07]
    6. The remaining numbers represent the coefficients of the quotient, which will be one degree lower than the original polynomial. [00:25:55]
#### 4. Handling Non-Zero Remainders
If division results in a remainder $R \neq 0$:
* The divisor is **not** a factor.
* The final answer is written as: $\text{Quotient} + \frac{\text{Remainder}}{\text{Divisor}}$. [00:46:39]

### Polynomial Long Division: The "Divide, Multiply, Subtract, Bring Down" Cycle

Polynomial long division is identical to the long division you learned in grade school (e.g., $742 \div 3$). The only difference is that you are tracking powers of $x$ instead of place values like tens or hundreds.

Think of it as a four-step loop that you repeat until you run out of terms.

---
#### 1. The Setup
* **Dividend:** The polynomial inside the "house" (e.g., $2x^3 - x^2 + 2x - 3$).
* **Divisor:** The factor outside the house (e.g., $x - 1$).
* **Crucial Rule:** If a power of $x$ is missing (like if there is no $x^2$), you **must** write it as $0x^2$. This keeps your columns aligned.

---
#### 2. The Four-Step Loop (DMSB)

**Step A: Divide (First terms only)**
Look **only** at the first term of the divisor ($x$) and the first term of the dividend ($2x^3$). Ask: *"How many times does $x$ go into $2x^3$?"* or *"What is $2x^3 \div x$?"*
* **Result:** $2x^2$. Place this on top of the house.

**Step B: Multiply (The whole divisor)**
Multiply your new result ($2x^2$) by the **entire** divisor $(x - 1)$. 
* **Result:** $2x^2(x) - 2x^2(1) = 2x^3 - 2x^2$. Write this underneath the dividend.

**Step C: Subtract (The "Danger Zone")**
Subtract the line you just wrote from the line above it. 
* **Pro Tip:** Draw a line, change the signs of the bottom row, and then add. This prevents the common mistake of forgetting to distribute the negative.
* **Goal:** The first terms ($2x^3 - 2x^3$) **must** cancel out to zero.

**Step D: Bring Down**
Bring down the next term from the original dividend and start the loop over at Step A.

---
#### 3. When are you finished?
You stop when the term you "bring down" has a lower degree than your divisor. 
* If you have a number left over (like $5$), that is your **Remainder**. 
* You write the remainder as a fraction: $\frac{5}{\text{divisor}}$.

---
#### 4. Mental Model: "The Lead Term is King"
Don't let the $(x - 1)$ or $(x + 5)$ intimidate you. When you are **dividing**, you only care about the $x$. The rest of the divisor (the $-1$ or $+5$) only matters during the **multiplication** and **subtraction** steps. 

> [!abstract] Algebra Takeaway
> If your first terms aren't canceling out to zero during the **Subtract** step, you either divided incorrectly in Step A or forgot to flip your signs in Step C. 
### Polynomial Long Division: f(x) = 2x³ - x² + 2x - 3 divided by (x - 1)

To solve this for your Obsidian notes, we will divide the cubic polynomial $2x^3 - x^2 + 2x - 3$ by the linear factor $(x - 1)$.

---
#### 1. Setup
Write the dividend ($2x^3 - x^2 + 2x - 3$) under the division symbol and the divisor ($x - 1$) to the left.

---
#### 2. Long Division Steps

**Step 1: Divide the first terms**
* Divide $2x^3$ by $x$ to get **$2x^2$**. Place this above the $x^2$ term.
* Multiply $2x^2$ by $(x - 1)$ to get $2x^3 - 2x^2$.
* Subtract $(2x^3 - 2x^2)$ from $(2x^3 - x^2)$.
* *Note:* $-x^2 - (-2x^2) = \mathbf{x^2}$.
* Bring down the next term ($+2x$).

**Step 2: Divide the new first term**
* Divide $x^2$ by $x$ to get **$+x$**. Place this above the $x$ term.
* Multiply $x$ by $(x - 1)$ to get $x^2 - x$.
* Subtract $(x^2 - x)$ from $(x^2 + 2x)$.
* *Note:* $2x - (-x) = \mathbf{3x}$.
* Bring down the final term ($-3$).

**Step 3: Divide the final first term**
* Divide $3x$ by $x$ to get **$+3$**. Place this above the constant term.
* Multiply $3$ by $(x - 1)$ to get $3x - 3$.
* Subtract $(3x - 3)$ from $(3x - 3)$.
* *Note:* $3x - 3 - (3x - 3) = \mathbf{0}$.

---
#### 3. Final Result
Since the remainder is **0**, we know that $(x - 1)$ is a factor of $f(x)$.

**Quotient:** $2x^2 + x + 3$
**Remainder:** $0$

**Factored Form:**
$$f(x) = (x - 1)(2x^2 + x + 3)$$

---

> [!abstract] Algebra Takeaway
> Because the remainder is zero, the **Factor Theorem** confirms that $x = 1$ is a root (x-intercept) of the polynomial. To find the remaining zeros, you would now apply the Quadratic Formula to the quotient $2x^2 + x + 3$.

### Synthetic Division: f(x) = 2x³ - x² + 2x - 3 divided by (x - 1)

Since we are dividing by a linear factor where the zero is $x = 1$, we can use synthetic division. This method is a shortcut that uses only the coefficients of the polynomial.

---
#### 1. Setup
* **The Zero ($c$):** Put $1$ in the small box on the left.
* **The Coefficients:** List the coefficients of $2x^3 - x^2 + 2x - 3$ in a row: $2, -1, 2, -3$.
* **The Line:** Leave a blank row and draw a horizontal line underneath.
---
#### 2. The Synthetic Division Process

1.  **Bring Down:** Drop the first coefficient ($2$) straight below the line.
2.  **Multiply:** Multiply the $1$ (in the box) by the $2$ (at the bottom). Place the result ($2$) under the next coefficient ($-1$).
3.  **Add:** Add $-1 + 2$ to get **$1$**. Write this at the bottom.
4.  **Multiply:** Multiply the $1$ (in the box) by the new $1$ (at the bottom). Place the result ($1$) under the next coefficient ($2$).
5.  **Add:** Add $2 + 1$ to get **$3$**. Write this at the bottom.
6.  **Multiply:** Multiply the $1$ (in the box) by the $3$ (at the bottom). Place the result ($3$) under the final coefficient ($-3$).
7.  **Add:** Add $-3 + 3$ to get **$0$**. Write this at the bottom.
---
#### 3. Interpreting the Result
The numbers at the bottom row represent the coefficients of the quotient and the remainder.

* **Bottom Row:** $2, 1, 3 \mid 0$
* **The Quotient:** Start one degree lower than the original ($x^3 \rightarrow x^2$).
  * **$2x^2 + 1x + 3$**
* **The Remainder:** The final number is **$0$**.

**Final Answer:**
$$2x^2 + x + 3$$

---

> [!abstract] Algebra Takeaway
> Synthetic division is significantly faster than long division because it replaces subtraction with addition and ignores the variables ($x$) until the very end. Since the remainder is $0$, we have confirmed that $f(1) = 0$ and $(x - 1)$ is a perfect factor of the polynomial.

### Polynomial Long Division: g(x) = 3x⁶ + 82x³ + 27 divided by (x + 3)

To solve this for your Obsidian notes, we must account for every power of $x$ from $6$ down to $0$. Missing terms must be represented as $0$ to maintain column alignment.

---
#### 1. Setup with Placeholders
The dividend is $3x^6 + 0x^5 + 0x^4 + 82x^3 + 0x^2 + 0x + 27$.
The divisor is $x + 3$.

---
#### 2. Long Division Steps

**Cycle 1:**
* Divide $3x^6$ by $x = \mathbf{3x^5}$.
* Multiply $3x^5(x+3) = 3x^6 + 9x^5$.
* Subtract: $(0x^5) - (9x^5) = \mathbf{-9x^5}$. Bring down $0x^4$.

**Cycle 2:**
* Divide $-9x^5$ by $x = \mathbf{-9x^4}$.
* Multiply $-9x^4(x+3) = -9x^5 - 27x^4$.
* Subtract: $(0x^4) - (-27x^4) = \mathbf{27x^4}$. Bring down $82x^3$.

**Cycle 3:**
* Divide $27x^4$ by $x = \mathbf{27x^3}$.
* Multiply $27x^3(x+3) = 27x^4 + 81x^3$.
* Subtract: $(82x^3) - (81x^3) = \mathbf{x^3}$. Bring down $0x^2$.

**Cycle 4:**
* Divide $x^3$ by $x = \mathbf{x^2}$.
* Multiply $x^2(x+3) = x^3 + 3x^2$.
* Subtract: $(0x^2) - (3x^2) = \mathbf{-3x^2}$. Bring down $0x$.

**Cycle 5:**
* Divide $-3x^2$ by $x = \mathbf{-3x}$.
* Multiply $-3x(x+3) = -3x^2 - 9x$.
* Subtract: $(0x) - (-9x) = \mathbf{9x}$. Bring down $27$.

**Cycle 6:**
* Divide $9x$ by $x = \mathbf{9}$.
* Multiply $9(x+3) = 9x + 27$.
* Subtract: $(27) - (27) = \mathbf{0}$.

---
#### 3. Final Result
Since the remainder is **0**, $(x+3)$ is a perfect factor.

**Quotient:**
$$3x^5 - 9x^4 + 27x^3 + x^2 - 3x + 9$$

**Factored Form:**
$$g(x) = (x + 3)(3x^5 - 9x^4 + 27x^3 + x^2 - 3x + 9)$$

---

> [!abstract] Algebra Takeaway
> When dealing with large gaps in exponents (like $x^6$ jumping to $x^3$), placeholders are non-negotiable. Without them, your subtraction steps will align unlike terms (e.g., trying to subtract $x^5$ from $x^6$), which is the most common cause of failure in polynomial division.

### Synthetic Division: g(x) = 3x⁶ + 82x³ + 27 divided by (x + 3)

Since we are dividing by $(x + 3)$, the zero we use for synthetic division is **$x = -3$**. Because the polynomial jumps from $x^6$ to $x^3$, we **must** use zero placeholders for the missing $x^5, x^4, x^2,$ and $x^1$ terms.

---
#### 1. Setup
* **The Zero:** Place **$-3$** in the box.
* **The Coefficients:** $3$ ($x^6$), $0$ ($x^5$), $0$ ($x^4$), $82$ ($x^3$), $0$ ($x^2$), $0$ ($x$), $27$ (constant).
---
#### 2. The Synthetic Division Process

1.  **Bring Down:** Drop the **$3$** to the bottom row.
2.  **Multiply & Add:** $(-3 \times 3) = -9$. Add $0 + (-9) = \mathbf{-9}$.
3.  **Multiply & Add:** $(-3 \times -9) = 27$. Add $0 + 27 = \mathbf{27}$.
4.  **Multiply & Add:** $(-3 \times 27) = -81$. Add $82 + (-81) = \mathbf{1}$.
5.  **Multiply & Add:** $(-3 \times 1) = -3$. Add $0 + (-3) = \mathbf{-3}$.
6.  **Multiply & Add:** $(-3 \times -3) = 9$. Add $0 + 9 = \mathbf{9}$.
7.  **Multiply & Add:** $(-3 \times 9) = -27$. Add $27 + (-27) = \mathbf{0}$.

---
#### 3. Interpreting the Result
The degree of the quotient is always one less than the dividend ($x^6 \to x^5$).

* **Bottom Row:** $3, -9, 27, 1, -3, 9 \mid 0$
* **The Quotient:** $3x^5 - 9x^4 + 27x^3 + x^2 - 3x + 9$
* **The Remainder:** $0$

**Final Answer:**
$$3x^5 - 9x^4 + 27x^3 + x^2 - 3x + 9$$

---

> [!abstract] Algebra Takeaway
> Synthetic division is much more efficient than long division for high-degree polynomials, but its success depends entirely on the **zero placeholders**. If you missed even one $0$ in the coefficient row, the entire multiplication chain would have collapsed.

### Problem: Evaluate and Divide $f(x) = 4x^3 - 3x^2 - 8x + 4$ at $x = 2$

This note demonstrates three different methods to find the value of a polynomial at a given $x$ and the resulting quotient when divided by a linear factor.

---
#### 1. Method 1: Evaluating (Plugging In)
The **Remainder Theorem** states that $f(c)$ is equal to the remainder of the division.

$$f(2) = 4(2)^3 - 3(2)^2 - 8(2) + 4$$
$$f(2) = 4(8) - 3(4) - 16 + 4$$
$$f(2) = 32 - 12 - 16 + 4$$
$$f(2) = 20 - 16 + 4$$
$$f(2) = \mathbf{8}$$

---
#### 2. Method 2: Polynomial Long Division
We divide $4x^3 - 3x^2 - 8x + 4$ by $(x - 2)$.


1.  **Divide $4x^3$ by $x$:** Result is **$4x^2$**.
    * Multiply $4x^2(x - 2) = 4x^3 - 8x^2$.
    * Subtract: $(-3x^2) - (-8x^2) = \mathbf{5x^2}$. Bring down $-8x$.
2.  **Divide $5x^2$ by $x$:** Result is **$+5x$**.
    * Multiply $5x(x - 2) = 5x^2 - 10x$.
    * Subtract: $(-8x) - (-10x) = \mathbf{2x}$. Bring down $+4$.
3.  **Divide $2x$ by $x$:** Result is **$+2$**.
    * Multiply $2(x - 2) = 2x - 4$.
    * Subtract: $(4) - (-4) = \mathbf{8}$.

**Quotient:** $4x^2 + 5x + 2$
**Remainder:** $8$

---
#### 3. Method 3: Synthetic Division
Using the zero $x = 2$ and the coefficients $[4, -3, -8, 4]$.


1.  **Bring down the 4.**
2.  **Multiply & Add:** $2 \times 4 = 8$. Add $-3 + 8 = \mathbf{5}$.
3.  **Multiply & Add:** $2 \times 5 = 10$. Add $-8 + 10 = \mathbf{2}$.
4.  **Multiply & Add:** $2 \times 2 = 4$. Add $4 + 4 = \mathbf{8}$.

**Result Row:** $4, 5, 2 \mid 8$
**Quotient:** $4x^2 + 5x + 2$
**Remainder:** $8$

---

> [!abstract] Algebra Takeaway
> All three methods confirm the same result: the remainder is **8**. This means $(x - 2)$ is **not** a factor of the polynomial, and the coordinate $(2, 8)$ exists on the graph of $f(x)$.

## 2026-April-06 - Descartes Rule of Signs (Precalculus - College Algebra 33) :
https://www.youtube.com/watch?v=-AW6Y1bL4KU&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=34
### Summary: Descartes' Rule of Signs 
Descartes' Rule of Signs is a technique used to determine the possible number of positive and negative real zeros (x-intercepts) a polynomial has. While it doesn't tell you exactly what the zeros are, it significantly narrows down your search when using the Rational Zeros Theorem. [00:00:19]

---
#### 1. The Core Rule: Positive Real Zeros
To find the number of potential positive real zeros, look at the polynomial $f(x)$ in standard form (descending order). [00:02:18]

* **Step:** Count the number of **sign changes** between consecutive non-zero coefficients. [00:02:53]
* **Result:** The number of positive real zeros is either:
    1.  Equal to the number of sign changes.
    2.  Less than that number by an **even integer** (keep subtracting 2 until you reach 1 or 0). [00:04:08]

**Example:** If there are 3 sign changes, there are either **3 or 1** positive real zeros. [00:05:19]

---
#### 2. The Core Rule: Negative Real Zeros
To find the number of potential negative real zeros, you must first evaluate $f(-x)$. [00:10:11]

* **The Shortcut:** Instead of fully plugging in $-x$, simply **change the signs of all terms with odd exponents**. Keep the even exponents and the constant term the same. [00:10:38]
* **Step:** Count the sign changes in this new version, $f(-x)$. [00:11:56]
* **Result:** The number of negative real zeros is equal to this count or less by an even integer. [00:13:02]
---
#### 3. Why Subtract by Two?
The rule subtracts by 2 because non-real (complex) zeros always occur in **conjugate pairs**. If a potential x-intercept "disappears" from the graph, it is because it has become a pair of complex numbers that do not touch the x-axis (often caused by irreducible quadratics). [00:08:35, 00:15:12]

---
#### 4. The Power of "Zero Sign Changes"
Descartes' Rule is most powerful when it results in **zero sign changes**. [00:22:36]
* If $f(x)$ has 0 sign changes $\rightarrow$ **Zero positive real zeros.**
* If $f(-x)$ has 0 sign changes $\rightarrow$ **Zero negative real zeros.** [00:22:53]
* **Strategic Advantage:** If you know there are no negative zeros, you can ignore half of your list when testing numbers with synthetic division, saving a massive amount of time. [00:23:35]

---
#### 5. Logic Summary Table

| Sign Changes in $f(x)$ | Possible Positive Zeros |
| :--- | :--- |
| 0 | 0 |
| 1 | 1 |
| 2 | 2 or 0 |
| 3 | 3 or 1 |
| 4 | 4, 2, or 0 |

> [!abstract] Algebra Takeaway
> Always ensure your polynomial is in **descending order** before counting. A degree $n$ polynomial has exactly $n$ total zeros (including complex ones); Descartes' Rule helps you categorize how many of those $n$ zeros are actually visible on the left or right side of the graph. [00:18:20]

### Descartes' Rule of Signs: f(x) = -4x⁷ + x³ - x² + 2

This method allows us to determine the possible number of positive and negative real zeros by analyzing sign changes in the coefficients.

---
#### 1. Finding Possible Positive Real Zeros
We look at the sign changes in the original function $f(x)$.

**Function:** $f(x) = \mathbf{-}4x^7 \mathbf{+}x^3 \mathbf{-}x^2 \mathbf{+}2$

* **Change 1:** From $-4x^7$ to $+x^3$ (Negative to Positive)
* **Change 2:** From $+x^3$ to $-x^2$ (Positive to Negative)
* **Change 3:** From $-x^2$ to $+2$ (Negative to Positive)

**Total Sign Changes:** 3

**Possible Positive Real Zeros:** **3 or 1**
*(We take the number of changes and subtract by an even integer: $3, 3-2=1$.)*

---
#### 2. Finding Possible Negative Real Zeros
We evaluate $f(-x)$. A shortcut is to **flip the signs of terms with odd exponents** and keep the signs of even exponents and constants the same.

* $-4x^7$ (Odd exponent) $\rightarrow$ becomes **$+4x^7$**
* $+x^3$ (Odd exponent) $\rightarrow$ becomes **$-x^3$**
* $-x^2$ (Even exponent) $\rightarrow$ stays **$-x^2$**
* $+2$ (Constant) $\rightarrow$ stays **$+2$**

**Function $f(-x)$:** $f(-x) = \mathbf{+}4x^7 \mathbf{-}x^3 \mathbf{-}x^2 \mathbf{+}2$

* **Change 1:** From $+4x^7$ to $-x^3$ (Positive to Negative)
* **Change 2:** From $-x^2$ to $+2$ (Negative to Positive)
* *Note: There is no change between $-x^3$ and $-x^2$.*

**Total Sign Changes:** 2

**Possible Negative Real Zeros:** **2 or 0**
*(We take the number of changes and subtract by an even integer: $2, 2-2=0$.)*

---
#### 3. Summary Table of Zeros
Since the degree of the polynomial is **7**, there must be a total of 7 zeros (including real and complex).

| Positive Real | Negative Real | Complex (Imaginary) | Total |
| :--- | :--- | :--- | :--- |
| 3 | 2 | 2 | 7 |
| 3 | 0 | 4 | 7 |
| 1 | 2 | 4 | 7 |
| 1 | 0 | 6 | 7 |

---

> [!abstract] Algebra Takeaway
> Descartes' Rule tells us there is **at least one** positive real zero for this function. Because there is a possibility of **0** negative real zeros, if you were using synthetic division to test roots, it would be statistically smarter to test positive numbers first.

### Descartes' Rule of Signs: g(x) = -x² + 2x³ + 2x - 3

**Important:** Before applying the rule, you must rewrite the polynomial in **Standard Form** (descending order of exponents).

**Standard Form:** $g(x) = 2x^3 - x^2 + 2x - 3$

---
#### 1. Finding Possible Positive Real Zeros
Examine the sign changes in $g(x)$.

**Function:** $g(x) = \mathbf{+}2x^3 \mathbf{-}x^2 \mathbf{+}2x \mathbf{-}3$

* **Change 1:** From $+2x^3$ to $-x^2$ (Positive to Negative)
* **Change 2:** From $-x^2$ to $+2x$ (Negative to Positive)
* **Change 3:** From $+2x$ to $-3$ (Positive to Negative)

**Total Sign Changes:** 3

**Possible Positive Real Zeros:** **3 or 1**
*(Subtract by 2 until you reach 1 or 0: $3, 1$.)*

---
#### 2. Finding Possible Negative Real Zeros
Evaluate $g(-x)$ by flipping the signs of the terms with **odd exponents** ($x^3$ and $x^1$).

* $+2x^3$ (Odd exponent) $\rightarrow$ becomes **$-2x^3$**
* $-x^2$ (Even exponent) $\rightarrow$ stays **$-x^2$**
* $+2x$ (Odd exponent) $\rightarrow$ becomes **$-2x$**
* $-3$ (Constant) $\rightarrow$ stays **$-3$**

**Function $g(-x)$:** $g(-x) = \mathbf{-}2x^3 \mathbf{-}x^2 \mathbf{-}2x \mathbf{-}3$

* **Changes:** There are **0** sign changes. Every term is negative.

**Possible Negative Real Zeros:** **0**

---
#### 3. Summary Table of Zeros
The degree of the polynomial is **3**, so there are exactly 3 total zeros.

| Positive Real | Negative Real | Complex (Imaginary) | Total |
| :--- | :--- | :--- | :--- |
| 3 | 0 | 0 | 3 |
| 1 | 0 | 2 | 3 |

---

> [!abstract] Algebra Takeaway
> This is a very powerful result. Descartes' Rule tells us there are **no negative real zeros** for this function. When you move on to synthetic division or the Rational Zeros Theorem, you should **only test positive numbers**. Testing any negative number would be a waste of time.

### Descartes' Rule of Signs: h(x) = 3x⁶ + 82x³ + 27

This polynomial is already in standard form (descending order). We will now analyze the sign changes to determine the possible number of positive and negative real zeros.

---
#### 1. Finding Possible Positive Real Zeros
Examine the sign changes in the original function $h(x)$.

**Function:** $h(x) = \mathbf{+}3x^6 \mathbf{+}82x^3 \mathbf{+}27$

* **Signs:** Positive, Positive, Positive.
* **Changes:** There are **0** sign changes.

**Possible Positive Real Zeros:** **0**

---
#### 2. Finding Possible Negative Real Zeros
Evaluate $h(-x)$ by flipping the signs of terms with **odd exponents** (only $x^3$ in this case).

* $+3x^6$ (Even exponent) $\rightarrow$ stays **$+3x^6$**
* $+82x^3$ (Odd exponent) $\rightarrow$ becomes **$-82x^3$**
* $+27$ (Constant) $\rightarrow$ stays **$+27$**

**Function $h(-x)$:** $h(-x) = \mathbf{+}3x^6 \mathbf{-}82x^3 \mathbf{+}27$

* **Change 1:** From $+3x^6$ to $-82x^3$ (Positive to Negative)
* **Change 2:** From $-82x^3$ to $+27$ (Negative to Positive)

**Total Sign Changes:** 2

**Possible Negative Real Zeros:** **2 or 0**
*(Subtract by 2 until you reach 0: $2, 0$.)*

---
#### 3. Summary Table of Zeros
The degree of the polynomial is **6**, so there must be a total of 6 zeros.

| Positive Real | Negative Real | Complex (Imaginary) | Total |
| :--- | :--- | :--- | :--- |
| 0 | 2 | 4 | 6 |
| 0 | 0 | 6 | 6 |

---

> [!abstract] Algebra Takeaway
> Descartes' Rule shows that this function has **no positive real zeros**. This is extremely helpful because when you look for roots, you can immediately discard every positive number from your list. Any real x-intercepts that exist **must** be on the negative side of the x-axis.

## 2026-April-07 - How to Use the Rational Zeros Theorem (Precalculus - College Algebra 34) :
https://www.youtube.com/watch?v=g7wEpxwgB3w&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=35
### Rational Zeros Theorem (Rational Roots Theorem)

The Rational Zeros Theorem provides a method for finding all possible rational x-intercepts (zeros) of a polynomial function with integer coefficients. This acts as a starting point for factoring higher-degree polynomials when standard factoring techniques (like grouping) aren't immediately obvious.
#### The Theorem Formula
For a polynomial in the form $f(x) = a_n x^n + \dots + a_0$:
- **p**: Factors of the constant term ($a_0$).
- **q**: Factors of the leading coefficient ($a_n$).
- **Possible Rational Zeros**: All permutations of $\pm \frac{p}{q}$.
#### The General Workflow
1.  **Check for Order & Degree**: Ensure the polynomial is in descending order. Identify the degree to know the maximum number of possible x-intercepts.
2.  **Descartes' Rule of Signs**: Use this to determine the possible number of positive and negative real zeros. This helps narrow down which numbers from your $\frac{p}{q}$ list to test first.
3.  **Generate the List**: Find all factors of the constant ($p$) and the leading coefficient ($q$), then list all possible $\frac{p}{q}$ fractions.
4.  **Test Values (Remainder Theorem)**: Evaluate the function using values from the list. If $f(c) = 0$, then $x = c$ is an x-intercept and $(x - c)$ is a factor.
    * *Tip*: Start with simple integers like $1$ or $-1$.
5.  **Synthetic Division**: Once a zero is found, use synthetic division to "depress" the polynomial (reduce its degree).
6.  **Repeat or Factor**:
    * If the remaining quotient is a quadratic, use the Quadratic Formula or standard factoring.
    * If the degree is still 3 or higher, repeat the process using the new quotient.
#### Key Strategies & Constraints
- **Factoring First**: Always check for a Greatest Common Factor (GCF) or factoring by grouping before starting the theorem; it saves significant time.
- **Repeated Roots**: If a value works once, check it again in the depressed polynomial. It may have a multiplicity greater than 1 (a "bouncy" zero on a graph).
- **Irrational & Complex Zeros**: The theorem **only** finds rational zeros (integers or fractions). If the remaining factor is an irreducible quadratic like $(x^2 + 25)$ or $(x^2 - 7)$, the zeros will be imaginary or radical ($\pm 5i$ or $\pm \sqrt{7}$), which will not appear on the $\frac{p}{q}$ list.
- **Fractional Zeros**: Synthetic division works with fractions (e.g., $1/2$), but be careful with the resulting coefficients and how they relate to the linear factor (e.g., $x - 1/2$ vs $2x - 1$).

### Detailed Breakdown: Rational Zeros Theorem (The "p over q" Rule)

#### 1. The Core Formula: $\frac{p}{q}$
The theorem states that every rational zero (a zero that can be written as a fraction) **must** be a combination of:
* **$p$**: All factors of the **Constant Term** (the number at the end).
* **$q$**: All factors of the **Leading Coefficient** (the number in front of the highest power).

**Possible Rational Zeros = $\pm \frac{\text{Factors of } p}{\text{Factors of } q}$**

---
#### 2. The Full Strategic Workflow
This is the order Professor Leonard uses to solve these without wasting hours on "guess and check":

1.  **List all possible $\frac{p}{q}$:** Write out every possible fraction. 
    * *Example:* If $p=6$ and $q=2$, your list is $\pm \frac{1, 2, 3, 6}{1, 2}$, which simplifies to $\pm \{1, 2, 3, 6, \frac{1}{2}, \frac{3}{2}\}$.
2.  **Apply Descartes' Rule of Signs:** (See previous notes). This tells you how many positive vs. negative zeros to expect.
    * If the rule says "0 negative zeros," you instantly delete all negative numbers from your $\frac{p}{q}$ list.
3.  **The "Low-Hanging Fruit" Test:** Before doing synthetic division, quickly plug $1$ and $-1$ into the function.
    * If $f(1) = 0$, you found your first zero in 5 seconds.
4.  **Synthetic Division (The Extraction):** Once you find a zero ($c$), perform synthetic division.
    * The result is a **Depressed Polynomial** (one degree lower).
    * **Crucial:** Always work off the *new* depressed polynomial for the next step, not the original.
5.  **The Quadratic Finish Line:** Continue the process until you reach a **Degree 2** (Quadratic) polynomial.
    * Once you hit $x^2$, stop using the theorem. Use the **Quadratic Formula** or **Factoring** to find the final two zeros (which might be irrational or imaginary).

---
#### 3. Advanced "Clutch" Tactics from the Video

* **The Upper and Lower Bound Tests:** * If you do synthetic division with a positive number and the bottom row is all **positive**, that number is an "Upper Bound"—no zeros exist higher than that. Stop testing bigger numbers. [00:48:12]
    * If you use a negative number and the bottom row **alternates signs** (+, -, +, -), that is a "Lower Bound." Stop testing smaller (more negative) numbers.
* **Handling Fractions in Synthetic Division:**
    * If your zero is $\frac{1}{2}$, your factor is $(x - \frac{1}{2})$. In your notes, you might want to write this as $(2x - 1)$ to keep the coefficients as integers. [01:05:22]
* **Multiplicity (The Bounce):**
    * If a zero works once, it might work again! If you have a depressed polynomial, test the same zero a second time before moving to a new number.

---
#### 4. Why the Theorem "Fails" Sometimes
* **Irrational Zeros:** If a zero is $\sqrt{2}$, it will **never** appear on your $\frac{p}{q}$ list.
* **Imaginary Zeros:** If a zero is $3i$, it will **never** appear on your list.
* **Conclusion:** The theorem is only a "key" to unlock the first few doors. Once the polynomial is small enough ($x^2$), the Quadratic Formula handles the "invisible" zeros the theorem can't see.

> [!abstract] Algebra Takeaway
> The Rational Zeros Theorem is an "Elimination Game." You start with a huge list of possibilities and use Descartes' Rule and Synthetic Division to kill off the "fake" zeros until only the real ones remain.

### Solving f(x) = 2x³ + 11x² - 7x - 6 using Rational Zeros Theorem

To find the zeros of this cubic polynomial for your Obsidian notes, we will follow the full strategic workflow: listing possibilities, narrowing them down, and using synthetic division.

---
#### 1. List Possible Rational Zeros ($\pm p/q$)
* **p (Factors of constant -6):** $\pm 1, 2, 3, 6$
* **q (Factors of leading coefficient 2):** $\pm 1, 2$

**Possible Rational Zeros ($p/q$):**
$$\pm \left\{ \frac{1}{1}, \frac{2}{1}, \frac{3}{1}, \frac{6}{1}, \frac{1}{2}, \frac{3}{2} \right\}$$
**Simplified List:** $\pm \{1, 2, 3, 6, 0.5, 1.5\}$

---

#### 2. Narrowing Down (Descartes' Rule of Signs)
* **f(x):** $+2x^3 + 11x^2 - 7x - 6$ → **1 sign change**.
    * *Result:* Exactly **1 positive real zero**.
* **f(-x):** $-2x^3 + 11x^2 + 7x - 6$ → **2 sign changes**.
    * *Result:* Either **2 or 0 negative real zeros**.



---
#### 3. Testing Zeros (The "Low-Hanging Fruit")
Let's test $x = 1$ first since it's the easiest positive number.
$$f(1) = 2(1)^3 + 11(1)^2 - 7(1) - 6$$
$$f(1) = 2 + 11 - 7 - 6 = 0$$
**Success!** $x = 1$ is a zero, which means $(x - 1)$ is a factor.

---
#### 4. Synthetic Division (Depressing the Polynomial)
Now we divide the original polynomial by the zero we found ($x = 1$).



1.  **Bring down 2.**
2.  Multiply $1 \times 2 = 2$; Add $11 + 2 = \mathbf{13}$.
3.  Multiply $1 \times 13 = 13$; Add $-7 + 13 = \mathbf{6}$.
4.  Multiply $1 \times 6 = 6$; Add $-6 + 6 = \mathbf{0}$.

**New Depressed Polynomial (Quadratic):** $2x^2 + 13x + 6$

---
#### 5. Factoring the Resulting Quadratic
Now we solve $2x^2 + 13x + 6 = 0$ using the "ac" method or factoring by grouping.
* **ac product:** $2 \times 6 = 12$.
* **Factors of 12 that add to 13:** $12$ and $1$.

$$2x^2 + 12x + 1x + 6$$
$$2x(x + 6) + 1(x + 6)$$
$$(2x + 1)(x + 6)$$

Setting these to zero:
* $2x + 1 = 0 \implies x = -1/2$
* $x + 6 = 0 \implies x = -6$

---
#### 6. Final Summary
* **Rational Zeros:** $1, -1/2, -6$
* **Factored Form:** $f(x) = (x - 1)(2x + 1)(x + 6)$

> [!abstract] Algebra Takeaway
> Notice how Descartes' Rule was perfectly accurate: we found exactly **one** positive zero ($1$) and **two** negative zeros ($-0.5$ and $-6$). By finding the easiest positive root first, we were able to skip the "guess and check" for the more difficult negative fractions.

### Solving h(x) = 3x³ + 6x² - 15x - 30 using Rational Zeros Theorem

Before starting the Rational Zeros Theorem, we should always check for a **Greatest Common Factor (GCF)** to make the numbers smaller and easier to manage.

---
#### 1. Pre-Step: Factor out the GCF
Each coefficient is divisible by 3.
$$h(x) = 3(x^3 + 2x^2 - 5x - 10)$$
We will now use the Rational Zeros Theorem on the "depressed" polynomial: **$g(x) = x^3 + 2x^2 - 5x - 10$**.

---
#### 2. List Possible Rational Zeros ($\pm p/q$)
* **p (Factors of constant -10):** $\pm 1, 2, 5, 10$
* **q (Factors of leading coefficient 1):** $\pm 1$

**Possible Rational Zeros:** $\pm \{1, 2, 5, 10\}$



---
#### 3. Narrowing Down (Descartes' Rule of Signs)
* **g(x):** $+x^3 + 2x^2 - 5x - 10$ → **1 sign change**.
    * *Result:* Exactly **1 positive real zero**.
* **g(-x):** $-x^3 + 2x^2 + 5x - 10$ → **2 sign changes**.
    * *Result:* Either **2 or 0 negative real zeros**.

---
#### 4. Testing Zeros
Let's test the positive list first since there is guaranteed to be one.
* **Test $x = 1$:** $1^3 + 2(1)^2 - 5(1) - 10 = 1 + 2 - 5 - 10 = -12$ (No)
* **Test $x = 2$:** $2^3 + 2(2)^2 - 5(2) - 10 = 8 + 8 - 10 - 10 = -4$ (No)
* **Test $x = 5$:** $5^3 + 2(5)^2 - 5(5) - 10 = 125 + 50 - 25 - 10 = 140$ (No)

*Wait—* If $x=2$ gave a negative result ($-4$) and $x=5$ gave a massive positive result ($140$), the zero must be an **irrational number** between 2 and 5. Let's pivot to the negative list.

* **Test $x = -2$:** $(-2)^3 + 2(-2)^2 - 5(-2) - 10 = -8 + 8 + 10 - 10 = \mathbf{0}$
**Success!** $x = -2$ is a zero.

---
#### 5. Synthetic Division
Divide $x^3 + 2x^2 - 5x - 10$ by the zero $x = -2$.
1.  **Bring down 1.**
2.  Multiply $-2 \times 1 = -2$; Add $2 + (-2) = \mathbf{0}$.
3.  Multiply $-2 \times 0 = 0$; Add $-5 + 0 = \mathbf{-5}$.
4.  Multiply $-2 \times -5 = 10$; Add $-10 + 10 = \mathbf{0}$.

**New Quadratic:** $x^2 + 0x - 5$ or simply **$x^2 - 5$**.

---
#### 6. Solving the Quadratic
$$x^2 - 5 = 0$$
$$x^2 = 5$$
$$x = \pm \sqrt{5}$$

---
#### 7. Final Summary
* **Rational Zeros:** $-2$
* **Irrational Zeros:** $\sqrt{5}, -\sqrt{5}$
* **Factored Form:** $h(x) = 3(x + 2)(x - \sqrt{5})(x + \sqrt{5})$

> [!abstract] Algebra Takeaway
> This problem highlights why the Rational Zeros Theorem is only a starting point. We found the rational zero ($-2$), but the other two zeros ($\pm \sqrt{5}$) were **irrational**. If we hadn't used synthetic division to get to the quadratic $x^2 - 5$, we never would have found them because $\sqrt{5}$ is not on the $p/q$ list.

### Solving g(x) = x⁵ - 7x⁴ + 19x³ - 37x² + 60x - 36 using Rational Zeros Theorem

This is a degree 5 polynomial, meaning there are 5 total zeros to find. We will use the Rational Zeros Theorem to find the "easy" ones and synthetic division to break the polynomial down.

---
#### 1. List Possible Rational Zeros ($\pm p/q$)
* **p (Factors of constant -36):** $\pm 1, 2, 3, 4, 6, 9, 12, 18, 36$
* **q (Factors of leading coefficient 1):** $\pm 1$

**Possible Rational Zeros:** $\pm \{1, 2, 3, 4, 6, 9, 12, 18, 36\}$

---
#### 2. Narrowing Down (Descartes' Rule of Signs)
* **g(x):** $+x^5 - 7x^4 + 19x^3 - 37x^2 + 60x - 36$
    * Sign changes: $+ \to -$, $- \to +$, $+ \to -$, $- \to +$, $+ \to -$
    * **5 sign changes.**
    * *Result:* **5, 3, or 1 positive real zeros.**
* **g(-x):** $-x^5 - 7x^4 - 19x^3 - 37x^2 - 60x - 36$
    * Sign changes: **0**.
    * *Result:* **0 negative real zeros.** (We can ignore the entire negative list!)

---
#### 3. Finding the First Zero
Since all real zeros must be positive, let's test $x = 1$:
$$g(1) = 1 - 7 + 19 - 37 + 60 - 36 = 0$$
**Success!** $x = 1$ is a zero.

---
#### 4. First Synthetic Division
Divide the coefficients $[1, -7, 19, -37, 60, -36]$ by $1$.

1.  Bring down $1$.
2.  Multiply/Add: $(1\times1)-7 = -6$; $(1\times-6)+19 = 13$; $(1\times13)-37 = -24$; $(1\times-24)+60 = 36$; $(1\times36)-36 = 0$.

**Depressed Polynomial (Degree 4):** $x^4 - 6x^3 + 13x^2 - 24x + 36$

---
#### 5. Finding the Second Zero
We test the new polynomial. Let's try $x = 2$:
$$2^4 - 6(2^3) + 13(2^2) - 24(2) + 36 = 16 - 48 + 52 - 48 + 36 = 8 \neq 0$$
Let's try $x = 3$:
$$3^4 - 6(3^3) + 13(3^2) - 24(3) + 36 = 81 - 162 + 117 - 72 + 36 = 0$$
**Success!** $x = 3$ is a zero.

---
#### 6. Second Synthetic Division
Divide the degree 4 coefficients $[1, -6, 13, -24, 36]$ by $3$.

1.  Bring down $1$.
2.  Multiply/Add: $(3\times1)-6 = -3$; $(3\times-3)+13 = 4$; $(3\times4)-24 = -12$; $(3\times-12)+36 = 0$.

**Depressed Polynomial (Degree 3):** $x^3 - 3x^2 + 4x - 12$

---
#### 7. Finding the Third Zero
Notice that $x^3 - 3x^2 + 4x - 12$ can be factored by **grouping**:
$$x^2(x - 3) + 4(x - 3)$$
$$(x^2 + 4)(x - 3)$$

This gives us another zero at **$x = 3$** (this zero has a **multiplicity of 2**).

---
#### 8. Final Zeros and Factoring
Solve the remaining quadratic: $x^2 + 4 = 0$
$$x^2 = -4 \implies x = \pm 2i$$

**Final Zeros:** $1, 3$ (multiplicity 2), $2i, -2i$

**Factored Form:**
$$g(x) = (x - 1)(x - 3)^2(x^2 + 4)$$

> [!abstract] Algebra Takeaway
> Descartes' Rule predicted 5, 3, or 1 positive real zeros. We found **3** real zeros ($1, 3, 3$). The "missing" 2 zeros were a complex conjugate pair ($\pm 2i$), which do not show up as x-intercepts on a graph.

### Solving f(x) = 2x⁵ - x⁴ + 48x³ - 24x² - 50x + 25

Professor Leonard often demonstrates two paths: one using the **Rational Zeros Theorem (RZT)** and another using **Factoring by Grouping** (when the polynomial structure allows it). We will solve this using both to see how they converge.

---
#### 1. Method 1: The Rational Zeros Theorem (The "Standard" Way)

**Step A: List Possible Rational Zeros ($\pm p/q$)**
* **p (Factors of 25):** $\pm 1, 5, 25$
* **q (Factors of 2):** $\pm 1, 2$
* **Possible Zeros:** $\pm \{1, 5, 25, \frac{1}{2}, \frac{5}{2}, \frac{25}{2}\}$

**Step B: Descartes' Rule of Signs**
* **f(x):** $+2x^5 - x^4 + 48x^3 - 24x^2 - 50x + 25$ (4 sign changes)
    * **4, 2, or 0 Positive Real Zeros.**
* **f(-x):** $-2x^5 - x^4 - 48x^3 - 24x^2 + 50x + 25$ (1 sign change)
    * **Exactly 1 Negative Real Zero.**

**Step C: Testing Zeros & Synthetic Division**
Let's test $x = \frac{1}{2}$ (0.5), as it looks promising based on the coefficients.
1.  Bring down **2**.
2.  Multiply/Add: $(0.5 \times 2) - 1 = \mathbf{0}$
3.  Multiply/Add: $(0.5 \times 0) + 48 = \mathbf{48}$
4.  Multiply/Add: $(0.5 \times 48) - 24 = \mathbf{0}$
5.  Multiply/Add: $(0.5 \times 0) - 50 = \mathbf{-50}$
6.  Multiply/Add: $(0.5 \times -50) + 25 = \mathbf{0}$

**Depressed Polynomial (Degree 4):** $2x^4 + 48x^2 - 50$

**Step D: Solving the Resulting Quadratic-Style Equation**
Divide by 2: $x^4 + 24x^2 - 25 = 0$.
This is a quadratic in form. Let $u = x^2$:
$$u^2 + 24u - 25 = 0$$
$$(u + 25)(u - 1) = 0$$
Substituting $x^2$ back in:
1. $x^2 + 25 = 0 \implies x = \pm 5i$
2. $x^2 - 1 = 0 \implies x = \pm 1$

---
#### 2. Method 2: Factoring by Grouping (The "Clutch" Way)

Professor Leonard emphasizes looking for patterns first. Notice the ratios between coefficients:
$$(2x^5 - x^4) + (48x^3 - 24x^2) + (-50x + 25)$$

**Step A: Factor out the GCF of each pair**
* $x^4(2x - 1)$
* $24x^2(2x - 1)$
* $-25(2x - 1)$

**Step B: Factor out the common binomial $(2x - 1)$**
$$(2x - 1)(x^4 + 24x^2 - 25)$$

**Step C: Factor the trinomial**
$$(2x - 1)(x^2 + 25)(x^2 - 1)$$
$$(2x - 1)(x^2 + 25)(x - 1)(x + 1)$$

---
#### 3. Final Summary of Zeros
By setting each factor to zero:
* $2x - 1 = 0 \implies \mathbf{x = 1/2}$
* $x - 1 = 0 \implies \mathbf{x = 1}$
* $x + 1 = 0 \implies \mathbf{x = -1}$
* $x^2 + 25 = 0 \implies \mathbf{x = \pm 5i}$

> [!abstract] Algebra Takeaway
> Both methods yield the same results. **Method 2** is much faster if you spot the grouping pattern, but **Method 1 (RZT)** is the fail-safe "tank" method that works even when the polynomial doesn't have a clean grouping structure.

## 2026-April-08 - Introduction to Complex Solutions of Polynomials (Precalculus - College Algebra 35) : 
https://www.youtube.com/watch?v=g-69B5jkcO4&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=36
### Complex Solutions of Polynomials

This summary covers the transition from factoring over the Real Number System to the **Complex Number System**.

---
#### 1. The Linear Factorization Theorem
Every polynomial of degree $n > 0$ has exactly $n$ zeros in the complex number system. 
* In the real number system, some polynomials were "irreducible" (like $x^2 + 1$).
* In the complex system, these are now factorable: $x^2 + 1 = (x + i)(x - i)$.
* **Result:** A degree $n$ polynomial will always have exactly $n$ linear factors.

---
#### 2. The Complex Conjugate Root Theorem
Complex zeros never exist in isolation; they always appear in **conjugate pairs**.
* If **$a + bi$** is a zero, then **$a - bi$** must also be a zero.
* **Important:** This only applies to polynomials with **real coefficients**.
* **Visualizing Pairs:**
    * If $3 + 2i$ is a root, $3 - 2i$ is a root.
    * If $-i$ is a root, $+i$ is a root.

---
#### 3. Why the "Pairs" Rule Matters
Because complex zeros come in pairs, they always take up an **even number** of slots in a polynomial's degree count.
* **Odd-Degree Polynomials:** Must have at least one **real** zero. (Example: A degree 3 polynomial could have 3 real zeros OR 1 real and 2 complex zeros).
* **Even-Degree Polynomials:** Could potentially have **zero** real zeros. (Example: A degree 4 polynomial could have 4 complex zeros).

---
#### 4. Logic Summary Table (Degree 5 Example)

| Real Zeros | Complex Zeros | Total Zeros |
| :--- | :--- | :--- |
| 5 | 0 | 5 |
| 3 | 2 (1 pair) | 5 |
| 1 | 4 (2 pairs) | 5 |

---
#### 5. Relationship to Descartes' Rule
This explains why Descartes' Rule of Signs requires you to subtract by **2**. Each time you subtract 2 from the count of sign changes, you are essentially acknowledging that a pair of potential real zeros may actually be a pair of complex zeros.

> [!abstract] Algebra Takeaway
> In the Complex Number System, the **Degree = Number of Zeros**. There are no "missing" answers; if a zero doesn't show up on the x-axis (real), it exists in the complex plane as a conjugate pair.

## 2026-April-09 - Creating Polynomials from Complex Solutions (Precalculus - College Algebra 36) : 
https://www.youtube.com/watch?v=lIFeZLHVWmc&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=39
### Creating Polynomials from Complex Solutions (Professor Leonard)

This process involves building a polynomial function $f(x)$ when given its zeros.

---
#### 1. The Setup
If $c$ is a zero, then $(x - c)$ is a factor.
1. **Identify all zeros.** (If a complex zero like $2 + i$ is given, you must manually include its conjugate $2 - i$).
2. **Write out the factors.** $f(x) = a(x - c_1)(x - c_2)...$
3. **Multiply the factors.** It is usually best to multiply the complex conjugate factors first.

---
#### 2. The Grouping Trick for Complex Factors
Multiplying $(x - (2 + i))(x - (2 - i))$ is difficult if you distribute everything. Instead, group the real parts:

1. **Distribute the negative:** $(x - 2 - i)(x - 2 + i)$
2. **Group the real part:** $[(x - 2) - i] \cdot [(x - 2) + i]$
3. **Difference of Squares:** Notice this is $(A - B)(A + B) = A^2 - B^2$.
4. **Expand:** $(x - 2)^2 - i^2$
5. **Simplify:** $(x^2 - 4x + 4) - (-1) = \mathbf{x^2 - 4x + 5}$

---
#### 3. Solving for 'a' (The Leading Coefficient)
If the problem provides a specific point $(x, y)$ that the graph passes through:
1. Plug the $x$ and $y$ values into your function.
2. Solve for $a$.
3. Distribute $a$ through the final polynomial.

---
#### 4. Step-by-Step Logic Example
**Problem:** Find a degree 3 polynomial with zeros $x = 4$ and $x = 2i$, passing through $(1, -15)$.

1. **Find all zeros:** $4, 2i, -2i$ (Complex roots must have pairs).
2. **Set up factors:** $f(x) = a(x - 4)(x - 2i)(x + 2i)$
3. **Multiply complex factors:** $(x - 2i)(x + 2i) = x^2 - 4i^2 = \mathbf{x^2 + 4}$
4. **Current function:** $f(x) = a(x - 4)(x^2 + 4)$
5. **Solve for $a$ using $(1, -15)$:**
   $$-15 = a(1 - 4)(1^2 + 4)$$
   $$-15 = a(-3)(5)$$
   $$-15 = -15a \implies \mathbf{a = 1}$$
6. **Final Standard Form:** $f(x) = (x - 4)(x^2 + 4) = \mathbf{x^3 - 4x^2 + 4x - 16}$

> [!abstract] Algebra Takeaway
> When multiplying complex conjugates, the $i$ terms will always cancel out, leaving you with a quadratic that has real coefficients. If your final polynomial still has an $i$ in it, you made a distribution error or forgot a conjugate pair.

### Linear Factors vs. Irreducible Quadratics

In the context of factoring polynomials over the **Real Number System**, every polynomial can be broken down into a product of these two types of building blocks.

---
#### 1. Linear Factors
A linear factor is a first-degree polynomial in the form **$(ax + b)$** or simply **$(x - c)$**.
* **X-Intercepts:** Every linear factor corresponds to exactly one **real x-intercept** on a graph.
* **Solvability:** Setting a linear factor to zero is straightforward (e.g., $x - 3 = 0 \implies x = 3$).
* **Graphical Behavior:** The graph will either cross through or "bounce" off the x-axis at this value, depending on the multiplicity.

---
#### 2. Irreducible Quadratics
An irreducible quadratic is a second-degree polynomial **$(ax^2 + bx + c)$** that **cannot** be factored further into linear factors using real numbers.
* **The Discriminant Test:** A quadratic is irreducible over the reals if its discriminant is negative: **$b^2 - 4ac < 0$**.
* **X-Intercepts:** These factors do **not** produce real x-intercepts. On a graph, these represent the parts of the polynomial that "turn around" before reaching the x-axis.
* **Complex Solutions:** If you use the Quadratic Formula on an irreducible quadratic, you will always get two **complex (imaginary) solutions** in conjugate pairs (e.g., $x = 2 \pm 3i$).

---
#### 3. Summary Comparison

| Feature | Linear Factor | Irreducible Quadratic |
| :--- | :--- | :--- |
| **Form** | $x - c$ | $ax^2 + bx + c$ |
| **Degree** | 1 | 2 |
| **Real Zeros** | Exactly 1 | 0 |
| **Complex Zeros** | 0 | 2 (Conjugate pair) |
| **X-Axis Interaction** | Crosses or Bounces | Never touches |

---
#### 4. The "Complete Factorization" Context
* **Over the Reals:** You stop factoring once you have a mix of linear factors and irreducible quadratics.
  * *Example:* $f(x) = (x - 2)(x^2 + 9)$
* **Over the Complex Numbers:** You "break" the irreducible quadratics into two linear complex factors.
  * *Example:* $f(x) = (x - 2)(x + 3i)(x - 3i)$

> [!abstract] Algebra Takeaway
> Think of **Linear Factors** as "visible" roots (you can see them on the graph) and **Irreducible Quadratics** as "hidden" roots (they exist mathematically but stay off the x-axis in the complex plane).

### Distributing Complex Conjugates: `f(x) = a(x - 4)²[(x - 3) - 2i ] [ (x - 3) + 2i]` 

When dealing with complex conjugates in Obsidian notes, the most efficient method is to avoid "brute force" distribution and instead use the **Difference of Squares** shortcut.

---
#### 1. Grouping the Real Parts
Instead of treating $(x - 3 - 2i)$ as three separate terms, group the real part $(x - 3)$ together. This turns the expression into a binomial pattern:

$$[(x - 3) - 2i] \cdot [(x - 3) + 2i]$$

Notice this now fits the pattern: **$(A - B)(A + B)$**
* **$A = (x - 3)$**
* **$B = 2i$**

---
#### 2. Applying the Difference of Squares
Using the formula $A^2 - B^2$:

$$(x - 3)^2 - (2i)^2$$

---
#### 3. Expanding and Simplifying
Now, expand both terms separately:

**A. Expand the Real Square:**
$$(x - 3)^2 = x^2 - 6x + 9$$

**B. Expand the Imaginary Square:**
$$(2i)^2 = 4i^2$$
*Since $i^2 = -1$:*
$$4(-1) = -4$$

---
#### 4. Final Combination
Combine the two results back into the equation:

$$(x^2 - 6x + 9) - (-4)$$
$$(x^2 - 6x + 9) + 4$$
$$\mathbf{x^2 - 6x + 13}$$



---
#### 5. The Simplified Polynomial (Factored Form)
Now that the complex conjugates are merged into an **irreducible quadratic**, your function looks like this:

$$f(x) = a(x - 4)^2(x^2 - 6x + 13)$$

> [!abstract] Algebra Takeaway
> **The Conjugate Shortcut:** When you multiply $(x - a - bi)$ and $(x - a + bi)$, the result will always be **$(x - a)^2 + b^2$**. Notice that the negative sign from the Difference of Squares ($A^2 - B^2$) and the $i^2$ always cancel out to become a **plus** sign.

### Building a Polynomial from Complex Zeros: i, -i, 1 + 2i, 1 - 2i

This degree 4 polynomial consists entirely of complex conjugate pairs. We will build the function by converting these zeros into factors and using the grouping method to eliminate the imaginary units.

---
#### 1. Identify the Zeros and Factors
Since the degree is 4 and we have 4 zeros, we have a complete set:
* **Pair 1:** $x = i$ and $x = -i \implies$ Factors: $(x - i)(x + i)$
* **Pair 2:** $x = 1 + 2i$ and $x = 1 - 2i \implies$ Factors: $[(x - 1) - 2i][(x - 1) + 2i]$



---
#### 2. Multiply the First Pair (Pure Imaginary)
The pair $(x - i)(x + i)$ follows the difference of squares pattern:
$$(x)^2 - (i)^2$$
$$x^2 - (-1)$$
$$\mathbf{x^2 + 1}$$

---
#### 3. Multiply the Second Pair (Complex Binomials)
Use the **grouping trick** for $[(x - 1) - 2i][(x - 1) + 2i]$:
1.  **Group the real part:** $[(x - 1) - 2i][(x - 1) + 2i]$
2.  **Difference of Squares:** $(x - 1)^2 - (2i)^2$
3.  **Expand $(x - 1)^2$:** $x^2 - 2x + 1$
4.  **Expand $(2i)^2$:** $4i^2 = -4$
5.  **Combine:** $(x^2 - 2x + 1) - (-4)$
6.  **Simplify:** $\mathbf{x^2 - 2x + 5}$

---
#### 4. Combine into Final Polynomial
Now multiply the two resulting quadratics:
$$f(x) = (x^2 + 1)(x^2 - 2x + 5)$$

**Distribution (FOIL-style):**
* $x^2(x^2 - 2x + 5) = x^4 - 2x^3 + 5x^2$
* $1(x^2 - 2x + 5) = x^2 - 2x + 5$

**Final Standard Form:**
$$f(x) = x^4 - 2x^3 + 6x^2 - 2x + 5$$

---
#### Summary of the Process
1.  **Linear Factors:** Convert each zero $c$ into a factor $(x - c)$.
2.  **Grouping:** For zeros with real parts (like $1 \pm 2i$), group the real part $(x - 1)$ to use the $(A-B)(A+B)$ shortcut.
3.  **Quadratic Form:** Multiplying conjugate pairs always results in an **irreducible quadratic** with real coefficients.
4.  **Final Product:** Multiply the quadratics together to reach the final degree of the polynomial.

> [!abstract] Algebra Takeaway
> In this problem, because all zeros are complex, the graph of this polynomial will **never touch or cross the x-axis**. The "Degree 4" tells us there are 4 solutions, but they all exist in the complex plane.

### Building a Polynomial: Degree 5, Zeros: 1 (mult 3), 1 + i

For your Obsidian notes, we will combine the **Multiplicity** rule with the **Complex Conjugate Root Theorem** to build the function.

---
#### 1. Identify All Zeros
A degree 5 polynomial must have 5 zeros.
* **Real Zero:** $x = 1$ with multiplicity 3.
* **Complex Zero:** $x = 1 + i$.
* **Hidden Conjugate:** Because complex roots come in pairs, we must include **$x = 1 - i$**.

**Total List:** $1, 1, 1, 1+i, 1-i$ (5 zeros total).

---
#### 2. Set Up the Factors
Convert each zero into a linear factor $(x - c)$:
$$f(x) = a(x - 1)^3 [(x - 1) - i][(x - 1) + i]$$

---
#### 3. Multiply the Complex Conjugates (The Grouping Trick)
We multiply the complex factors first to eliminate the $i$ terms using the Difference of Squares.

1.  **Group the real part:** $[(x - 1) - i] \cdot [(x - 1) + i]$
2.  **Difference of Squares:** $(x - 1)^2 - i^2$
3.  **Expand and Simplify:**
    * $(x - 1)^2 = x^2 - 2x + 1$
    * $- i^2 = -(-1) = +1$
4.  **Result:** $(x^2 - 2x + 1) + 1 = \mathbf{x^2 - 2x + 2}$



---
#### 4. Expand the Real Factor (Multiplicity 3)
Next, we expand $(x - 1)^3$. You can use Pascal's Triangle or manual distribution:
$$(x - 1)^3 = \mathbf{x^3 - 3x^2 + 3x - 1}$$

---
#### 5. Combine into Final Standard Form
Now, multiply the two results:
$$f(x) = (x^3 - 3x^2 + 3x - 1)(x^2 - 2x + 2)$$

**Distribution Step-by-Step:**
* $x^3(x^2 - 2x + 2) = x^5 - 2x^4 + 2x^3$
* $-3x^2(x^2 - 2x + 2) = -3x^4 + 6x^3 - 6x^2$
* $3x(x^2 - 2x + 2) = 3x^3 - 6x^2 + 6x$
* $-1(x^2 - 2x + 2) = -x^2 + 2x - 2$

**Combine Like Terms:**
$$f(x) = x^5 + (-2-3)x^4 + (2+6+3)x^3 + (-6-6-1)x^2 + (6+2)x - 2$$

**Final Polynomial:**
$$\mathbf{f(x) = x^5 - 5x^4 + 11x^3 - 13x^2 + 8x - 2}$$

> [!abstract] Algebra Takeaway
> Multiplicity 3 means the graph doesn't just cross the x-axis at $x=1$; it "flattens out" as it passes through, like a cubic function. The complex pair ($1 \pm i$) ensures the rest of the "turns" in the graph stay off the x-axis.

## 2026-April-10 - Finding ALL Solutions of Polynomials (Precalculus - College Algebra 37) :
https://www.youtube.com/watch?v=xuhk2kSVwe0&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=38
### Finding ALL Solutions of Polynomials (Professor Leonard)

This process combines every tool learned so far to break a high-degree polynomial down into all its individual zeros (Real and Complex).

---
#### 1. The Master Workflow
To find all $n$ zeros of a degree $n$ polynomial:
1.  **Factoring:** Always check for a GCF or Grouping first.
2.  **Rational Zeros Theorem (RZT):** List potential rational zeros ($\pm p/q$).
3.  **Descartes' Rule of Signs:** Narrow down how many positive/negative roots to look for.
4.  **Synthetic Division:** Test roots from your RZT list. When you find one that works (remainder 0), use the resulting "depressed" polynomial for the next step.
5.  **Quadratic Formula:** Once you reach a degree 2 (quadratic) polynomial, use the quadratic formula to find the final two zeros.

---
#### 2. Handling Complex Zeros in Division
If the problem **gives** you a complex zero (e.g., $x = 1 + 3i$), you can use it to find the other zeros:
1.  **Find the Pair:** Immediately identify the conjugate ($x = 1 - 3i$).
2.  **Build the Quadratic:** Multiply the two complex factors together:
    $[(x - 1) - 3i][(x - 1) + 3i] \implies (x - 1)^2 - (3i)^2 \implies \mathbf{x^2 - 2x + 10}$
3.  **Long Division:** Use **Polynomial Long Division** to divide the original polynomial by this irreducible quadratic. This will reveal the remaining factors/zeros.

---
#### 3. Real vs. Complex Factorization
* **Factored over the Reals:** The polynomial is written as a product of linear factors and **irreducible quadratics** (no $i$ allowed).
    * *Example:* $f(x) = (x - 5)(x^2 + 4)$
* **Factored over the Complex Numbers:** Every single factor is linear ($i$ is allowed).
    * *Example:* $f(x) = (x - 5)(x + 2i)(x - 2i)$

---
#### 4. The Strategy Table

| If the zero is... | Then use... | To get... |
| :--- | :--- | :--- |
| **Rational** ($1, -2, 1/2$) | Synthetic Division | A lower-degree polynomial. |
| **Complex** ($a \pm bi$) | Long Division | A lower-degree polynomial (after multiplying the pair). |
| **Irrational** ($\pm \sqrt{3}$) | Long Division | A lower-degree polynomial (after multiplying $(x^2 - 3)$). |

> [!abstract] Algebra Takeaway
> "Solving" a polynomial is a game of reduction. Every time you find a zero and divide it out, the "boss" (the polynomial) gets smaller and weaker until it's just a simple quadratic you can solve with the quadratic formula.

### Solving f(x) = x³ - 4x² + 4x - 16 given a zero of 2i

Since the degree of the polynomial is 3, we are looking for a total of three zeros. We are given one complex zero, which allows us to find the second one immediately.

---
#### 1. Identify the Complex Pair
According to the **Complex Conjugate Root Theorem**, complex zeros must appear in pairs.
* **Given Zero:** $x = 2i$
* **Conjugate Zero:** $x = -2i$

#### 2. Create the Quadratic Factor
To find the remaining zero, we multiply the factors associated with our complex pair to create a quadratic divisor.
$$(x - 2i)(x + 2i)$$
Using the difference of squares:
$$x^2 - (2i)^2$$
$$x^2 - 4i^2$$
Since $i^2 = -1$:
$$x^2 + 4$$
#### 3. Polynomial Long Division
We now divide the original polynomial $f(x)$ by our quadratic factor $x^2 + 4$ to find the final linear factor.


1. **Divide:** $x^3 / x^2 = x$
2. **Multiply:** $x(x^2 + 4) = x^3 + 4x$
3. **Subtract:** $(x^3 - 4x^2 + 4x - 16) - (x^3 + 4x) = -4x^2 - 16$
4. **Divide:** $-4x^2 / x^2 = -4$
5. **Multiply:** $-4(x^2 + 4) = -4x^2 - 16$
6. **Subtract:** $(-4x^2 - 16) - (-4x^2 - 16) = 0$

The quotient is **$x - 4$**.

#### 4. Find the Final Zero
Set the remaining linear factor to zero:
$$x - 4 = 0$$
$$x = 4$$

---
#### Final Summary
* **Zeros:** $2i, -2i, 4$
* **Factored Form (Complex):** $f(x) = (x - 2i)(x + 2i)(x - 4)$
* **Factored Form (Real):** $f(x) = (x^2 + 4)(x - 4)$


> [!abstract] Algebra Takeaway
> Even though this is a degree 3 polynomial, it only crosses the x-axis **once** (at $x=4$). The other two zeros are imaginary, meaning they do not produce x-intercepts on a standard coordinate plane.

### Solving g(x) = x⁴ - 9x³ + 21x² - 130 given a zero of 3 - 2i

Since the degree of $g(x)$ is 4, there are exactly four zeros. We are given one complex zero, which allows us to find its pair and reduce the polynomial to a quadratic.

---
#### 1. Identify the Complex Conjugate
Complex zeros of polynomials with real coefficients always occur in conjugate pairs.
* **Given Zero:** $x = 3 - 2i$
* **Conjugate Zero:** $x = 3 + 2i$
#### 2. Create the Irreducible Quadratic Factor
We build a quadratic factor by multiplying the factors associated with these two zeros. We use the grouping method for efficiency:
$$[(x - 3) + 2i][(x - 3) - 2i]$$

Apply the Difference of Squares:
$$(x - 3)^2 - (2i)^2$$
$$x^2 - 6x + 9 - (4i^2)$$
$$x^2 - 6x + 9 - (-4)$$
$$\mathbf{x^2 - 6x + 13}$$
#### 3. Polynomial Long Division
We divide the original polynomial by our quadratic factor to find the remaining quadratic factor.


**The Division:**
$$\frac{x^4 - 9x^3 + 21x^2 - 130}{x^2 - 6x + 13} = x^2 - 3x - 10$$

1.  $(x^4 - 6x^3 + 13x^2)$ subtracted from $(x^4 - 9x^3 + 21x^2)$ leaves $-3x^3 + 8x^2$.
2.  Bring down the next term (effectively $0x$) and continue.
3.  The final quotient is $x^2 - 3x - 10$ with a remainder of 0.
#### 4. Factor the Resulting Quadratic
Now we find the final two zeros by factoring the quotient:
$$x^2 - 3x - 10 = 0$$
$$(x - 5)(x + 2) = 0$$

* $x - 5 = 0 \implies \mathbf{x = 5}$
* $x + 2 = 0 \implies \mathbf{x = -2}$

---
#### Final Summary
* **All Zeros:** $3 - 2i, 3 + 2i, 5, -2$
* **Factored Form (Complex):** $g(x) = (x - (3-2i))(x - (3+2i))(x - 5)(x + 2)$
* **Factored Form (Real):** $g(x) = (x^2 - 6x + 13)(x - 5)(x + 2)$

> [!abstract] Algebra Takeaway
> By using the given complex zero to form a quadratic divisor, we reduced a difficult degree 4 polynomial into a factorable degree 2 polynomial. The two real zeros ($5$ and $-2$) are where the graph crosses the x-axis, while the complex pair accounts for the remaining "turns" in the function.

### Finding the Zeros of f(x) = x⁴ - 1

To find the zeros, we set the polynomial equal to zero and solve for $x$. This specific polynomial is a **Difference of Squares**, which allows us to solve it through repeated factoring.

---
#### 1. Factoring as a Difference of Squares
The expression $x^4 - 1$ can be seen as $(x^2)^2 - (1)^2$.
$$f(x) = (x^2 - 1)(x^2 + 1)$$

#### 2. Identifying the Real Zeros
The first factor, $(x^2 - 1)$, is another difference of squares:
$$(x - 1)(x + 1) = 0$$
* $x - 1 = 0 \implies \mathbf{x = 1}$
* $x + 1 = 0 \implies \mathbf{x = -1}$
#### 3. Identifying the Complex Zeros
The second factor, $(x^2 + 1)$, is an irreducible quadratic over the real numbers. To find the zeros, we set it to zero:
$$x^2 + 1 = 0$$
$$x^2 = -1$$
$$x = \pm \sqrt{-1}$$
* $\mathbf{x = i}$
* $\mathbf{x = -i}$

---
#### Final Summary
* **Total Zeros:** $1, -1, i, -i$
* **Factored Form (Real):** $f(x) = (x - 1)(x + 1)(x^2 + 1)$
* **Factored Form (Complex):** $f(x) = (x - 1)(x + 1)(x - i)(x + i)$

> [!abstract] Algebra Takeaway
> This is a degree 4 polynomial, so it must have 4 zeros. While only two are visible as x-intercepts ($1$ and $-1$), the other two exist in the complex plane as a conjugate pair ($i$ and $-i$).

### Finding the Zeros of g(x) = x⁴ + 13x² + 36

This polynomial is in **quadratic form**, meaning we can treat it like a standard trinomial by using a substitution or by factoring it directly into two quadratic factors.

---
#### 1. Factoring the Trinomial
We look for two numbers that multiply to $36$ and add to $13$.
* The factors are **9** and **4**.
$$g(x) = (x^2 + 9)(x^2 + 4)$$
#### 2. Identifying the First Pair of Zeros
Set the first factor to zero:
$$x^2 + 9 = 0$$
$$x^2 = -9$$
$$x = \pm \sqrt{-9}$$
* $\mathbf{x = 3i}$
* $\mathbf{x = -3i}$
#### 3. Identifying the Second Pair of Zeros
Set the second factor to zero:
$$x^2 + 4 = 0$$
$$x^2 = -4$$
$$x = \pm \sqrt{-4}$$
* $\mathbf{x = 2i}$
* $\mathbf{x = -2i}$

---
#### Final Summary
* **Total Zeros:** $3i, -3i, 2i, -2i$
* **Factored Form (Real/Irreducible):** $g(x) = (x^2 + 9)(x^2 + 4)$
* **Factored Form (Complex):** $g(x) = (x - 3i)(x + 3i)(x - 2i)(x + 2i)$

> [!abstract] Algebra Takeaway
> Since all four zeros are complex, the graph of $g(x)$ exists entirely above the x-axis and has no x-intercepts. This is a degree 4 polynomial with two distinct pairs of complex conjugates.

### Finding the Zeros of f(x) = x⁴ + 2x³ + 22x² + 50x - 75

To find all four zeros of this degree 4 polynomial, we will use the Rational Zeros Theorem to find real roots and then reduce the polynomial to a quadratic.

---
#### 1. Rational Zeros Theorem (RZT)
We list potential rational zeros by taking the factors of the constant term ($-75$) over the factors of the leading coefficient ($1$).
* **Factors of 75:** $\pm 1, \pm 3, \pm 5, \pm 15, \pm 25, \pm 75$
#### 2. Testing Potential Zeros (Synthetic Division)
**Test $x = 1$:**
$$1 \mid \begin{smallmatrix} 1 & 2 & 22 & 50 & -75 \\ & 1 & 3 & 25 & 75 \\ \hline 1 & 3 & 25 & 75 & \mathbf{0} \end{smallmatrix}$$
* **Success!** $x = 1$ is a zero. The depressed polynomial is $x^3 + 3x^2 + 25x + 75$.

**Test $x = -3$ (on the depressed polynomial):**
$$-3 \mid \begin{smallmatrix} 1 & 3 & 25 & 75 \\ & -3 & 0 & -75 \\ \hline 1 & 0 & 25 & \mathbf{0} \end{smallmatrix}$$
* **Success!** $x = -3$ is a zero. The remaining depressed polynomial is $x^2 + 25$.
#### 3. Solving the Remaining Quadratic
Set the final depressed polynomial to zero:
$$x^2 + 25 = 0$$
$$x^2 = -25$$
$$x = \pm \sqrt{-25}$$
* $\mathbf{x = 5i}$
* $\mathbf{x = -5i}$
#### 4. Final Zeros and Factorization
* **All Zeros:** $1, -3, 5i, -5i$
* **Factored Form (Real/Irreducible):** $f(x) = (x - 1)(x + 3)(x^2 + 25)$
* **Factored Form (Complex):** $f(x) = (x - 1)(x + 3)(x - 5i)(x + 5i)$

> [!abstract] Algebra Takeaway
> We successfully "chipped away" at the degree 4 polynomial by finding two real rational zeros. This left us with a simple quadratic ($x^2 + 25$) that yielded a pair of pure imaginary conjugate zeros.

### Finding the Zeros of g(x) = 3x⁴ + 5x³ + 25x² + 45x - 18

To find all four zeros of this degree 4 polynomial, we will apply the Rational Zeros Theorem to identify real roots and use synthetic division to reduce the function to a quadratic.

---
#### 1. Rational Zeros Theorem (RZT)
We list potential rational zeros by taking the factors of the constant term ($-18$) over the factors of the leading coefficient ($3$).
* **Factors of $p$ (-18):** $\pm 1, \pm 2, \pm 3, \pm 6, \pm 9, \pm 18$
* **Factors of $q$ (3):** $\pm 1, \pm 3$
* **Potential Rational Zeros ($p/q$):** $\pm 1, \pm 2, \pm 3, \pm 6, \pm 9, \pm 18, \pm 1/3, \pm 2/3$
#### 2. Testing Zeros (Synthetic Division)
**Test $x = -2$:**
$$-2 \mid \begin{smallmatrix} 3 & 5 & 25 & 45 & -18 \\ & -6 & 2 & -54 & 18 \\ \hline 3 & -1 & 27 & -9 & \mathbf{0} \end{smallmatrix}$$
* **Success!** $x = -2$ is a zero. The depressed polynomial is $3x^3 - x^2 + 27x - 9$.

**Test $x = 1/3$ (on the depressed polynomial):**
$$1/3 \mid \begin{smallmatrix} 3 & -1 & 27 & -9 \\ & 1 & 0 & 9 \\ \hline 3 & 0 & 27 & \mathbf{0} \end{smallmatrix}$$
* **Success!** $x = 1/3$ is a zero. The remaining depressed polynomial is $3x^2 + 27$.
#### 3. Solving the Remaining Quadratic
Set the final depressed polynomial to zero:
$$3x^2 + 27 = 0$$
$$3x^2 = -27$$
$$x^2 = -9$$
$$x = \pm \sqrt{-9}$$
* $\mathbf{x = 3i}$
* $\mathbf{x = -3i}$
#### 4. Final Zeros and Factorization
* **All Zeros:** $-2, 1/3, 3i, -3i$
* **Factored Form (Real/Irreducible):** $g(x) = (x + 2)(3x - 1)(x^2 + 9)$
* **Factored Form (Complex):** $g(x) = 3(x + 2)(x - 1/3)(x - 3i)(x + 3i)$

> [!abstract] Algebra Takeaway
> This polynomial crosses the x-axis at one integer ($-2$) and one fraction ($1/3$). The remaining degree is accounted for by a pair of pure imaginary zeros ($ \pm 3i$), which do not appear as x-intercepts.
## 2026-April-13 - Finding Vertical Asymptotes of Rational Functions (Precalculus - College Algebra 38) :
https://www.youtube.com/watch?v=y-bSJaEonho&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=40
### Finding Vertical Asymptotes and Holes (Professor Leonard)

Rational functions $f(x) = \frac{N(x)}{D(x)}$ have discontinuities wherever the denominator $D(x)$ equals zero. These take two forms: **Holes** and **Vertical Asymptotes (V.A.)**.

---
#### 1. The Relationship: Vertical Asymptotes vs. Holes
A discontinuity occurs whenever a value of $x$ is excluded from the domain.

* **Hole (Removable):** Occurs if a factor in the denominator **cancels** with an identical factor in the numerator. It represents a single missing point.
* **Vertical Asymptote (Non-removable):** Occurs if a factor in the denominator **remains** after simplification. It represents a line the graph cannot cross.
---
#### 2. Analysis Procedure
Always follow these steps in order to avoid missing hidden holes:

1.  **Factor:** Factor both the numerator and the denominator completely.
2.  **State the Domain:** List all values that make the denominator zero *before* canceling anything.
3.  **Simplify:** Cancel common factors.
4.  **Classify:** * Factors that were canceled = **Holes**.
    * Factors that remain in the denominator = **Vertical Asymptotes**.

---
#### 3. Multiplicity and Behavior at V.A.
The power (multiplicity) of the denominator's remaining factor determines the "look" of the asymptote:

* **Odd Multiplicity (e.g., $(x-c)^1$):** The graph approaches the asymptote from **opposite directions** (one side goes to $+\infty$, the other to $-\infty$).
* **Even Multiplicity (e.g., $(x-c)^2$):** The graph approaches the asymptote from the **same direction** (both sides go to $+\infty$ or both to $-\infty$), creating a "volcano" effect.
---
#### 4. Finding the Y-Coordinate of a Hole
Since a hole is a specific point, you must find its $y$-value:
1.  Take the $x$-value that caused the hole.
2.  Plug it into the **simplified** version of the function.
3.  The result is the height of the "missing" point.

> [!warning] Critical Error to Avoid
> Never cancel factors before defining your domain. If you cancel first, you will lose the information that tells you where the holes are located, leading to an incorrect domain and an incomplete graph.

> [!abstract] Algebra Takeaway
> Vertical Asymptotes are the "walls" of the graph, while Holes are just "potholes" in the road. Both are caused by zero in the denominator, but canceling makes the difference between a point and an asymptote.

### Vertical Asymptotes Appearance with Multiplicity :
![[Pasted image 20260413193911.png]]
### Multiplicity and Vertical Asymptote Behavior

The power of a non-removable factor in the denominator dictates the direction the function takes as it approaches the vertical asymptote.

---
#### 1. Odd Multiplicity (Opposite Directions)
When the multiplicity is odd (e.g., $(x-c)^1, (x-c)^3$), the graph approaches the asymptote from **opposite** directions.
* **Positive Lead:** Approaches $-\infty$ from the left and $+\infty$ from the right.
* **Example:** $f(x) = \frac{1}{x-2}$
    * Factor $(x-2)$ has multiplicity **1**.
    * At $x=2$, the left side falls and the right side rises.

---
#### 2. Even Multiplicity (Same Direction)
When the multiplicity is even (e.g., $(x-c)^2, (x-c)^4$), the graph approaches the asymptote from the **same** direction.
* **Positive Lead:** Both sides approach $+\infty$ (the "volcano").
* **Example:** $g(x) = \frac{1}{(x+3)^2}$
    * Factor $(x+3)$ has multiplicity **2**.
    * At $x=-3$, both the left and right sides rise toward $+\infty$.

---
#### 3. Summary of Signs

| Multiplicity | Leading Sign | Left Side Behavior | Right Side Behavior | Visual Effect |
| :--- | :--- | :--- | :--- | :--- |
| **Odd** | Positive (+) | $\to -\infty$ | $\to +\infty$ | Split |
| **Odd** | Negative (-) | $\to +\infty$ | $\to -\infty$ | Split (Reflected) |
| **Even** | Positive (+) | $\to +\infty$ | $\to +\infty$ | Volcano |
| **Even** | Negative (-) | $\to -\infty$ | $\to -\infty$ | Well/Pit |

> [!tip] Quick Check
> If you aren't sure of the direction, pick a test point extremely close to the asymptote (e.g., if the V.A. is at $x=2$, test $1.9$ and $2.1$) to see if the resulting $y$-value is a large positive or large negative number.

### Analysis of $f(x) = \frac{x+3}{x-4}$

To determine the behavior of a rational function, we must first identify the values that make the denominator zero.

---
#### 1. Set the Denominator to Zero
We find the restricted values of $x$ by setting $D(x) = 0$:
$$x - 4 = 0$$
$$x = 4$$
#### 2. Domain
The domain consists of all real numbers except those that cause division by zero.
**Domain:** $\{x \mid x \neq 4\}$ or $(-\infty, 4) \cup (4, \infty)$

#### 3. Classifying the Discontinuity
To decide if $x = 4$ is a hole or a vertical asymptote, we check if the factor $(x-4)$ cancels with anything in the numerator.
* **Numerator:** $(x + 3)$
* **Denominator:** $(x - 4)$
Since the factor $(x-4)$ does **not** cancel, it is a **Vertical Asymptote**.

---
#### 4. Graphical Behavior
The graph's appearance around $x = 4$ is determined by the multiplicity of the factor and the leading signs.

* **Asymptote Location:** A vertical dashed line at $x = 4$.
* **Multiplicity:** The factor $(x-4)$ has an exponent of **1** (odd).
* **Behavior:** The graph will approach opposite infinities.
    * As $x \to 4^-$, $f(x) \to -\infty$ (The left side goes down).
    * As $x \to 4^+$, $f(x) \to +\infty$ (The right side goes up).
* **Horizontal Asymptote:** Since the degrees of the numerator and denominator are the same ($1/1$), there is a horizontal asymptote at $y = 1$.

---
#### Summary Table
| Feature | Value |
| :--- | :--- |
| **Discontinuity** | $x = 4$ |
| **Type** | Vertical Asymptote |
| **Multiplicity** | Odd (1) |
| **Direction** | Opposite ($\swarrow \nearrow$) |

> [!abstract] Algebra Takeaway
> Because the factor $(x-4)$ remained in the denominator after we attempted to simplify, it creates a non-removable discontinuity. This acts as a physical barrier that the graph follows toward infinity rather than a simple "hole" in the line.

### Analysis of $g(x) = \frac{2}{(x-1)^2}$

We analyze this function by identifying the restricted values and determining the graphical behavior at the discontinuity.

---

#### 1. Set the Denominator to Zero
We find the restricted values of $x$ by setting the denominator equal to zero:
$$(x - 1)^2 = 0$$
$$x - 1 = 0$$
$$\mathbf{x = 1}$$

#### 2. Domain
The domain includes every real number except the value that causes division by zero.
**Domain:** $\{x \mid x \neq 1\}$ or $(-\infty, 1) \cup (1, \infty)$

#### 3. Classifying the Discontinuity
We check if the factor $(x - 1)$ cancels with the numerator:
* **Numerator:** $2$ (constant)
* **Denominator:** $(x - 1)^2$
Since the factor $(x - 1)$ cannot be canceled out, the discontinuity at **$x = 1$** is a **Vertical Asymptote**.

---
#### 4. Graphical Behavior
The appearance of the graph around the asymptote is dictated by the multiplicity and the sign of the constant.

* **Asymptote Location:** A vertical dashed line at $x = 1$.
* **Multiplicity:** The factor $(x - 1)$ has an exponent of **2** (**Even**).
* **Behavior:** Because the multiplicity is even, the graph approaches the same infinity from both sides.
    * Since the numerator is positive ($+2$), both sides approach $+\infty$.
    * This creates a **"volcano"** or **"chimney"** shape at $x = 1$.

---
#### Summary Table
| Feature | Value |
| :--- | :--- |
| **Discontinuity** | $x = 1$ |
| **Type** | Vertical Asymptote |
| **Multiplicity** | Even (2) |
| **Direction** | Same Direction ($\uparrow \uparrow$) |

> [!abstract] Algebra Takeaway
> The even power on the $(x - 1)$ term ensures that regardless of whether you plug in a number slightly smaller than 1 or slightly larger than 1, the denominator becomes a very small *positive* number, forcing the entire function toward $+\infty$.

### Analysis of h(x) = \frac{2x}{x^2 - 4}

To understand the behavior of this rational function, we must factor the denominator to find all restricted values and classify the resulting discontinuities.

---
#### 1. Set the Denominator to Zero
First, we factor the denominator using the difference of squares:
$$x^2 - 4 = (x - 2)(x + 2)$$
Setting the denominator to zero gives us:
$$(x - 2)(x + 2) = 0$$
$$\mathbf{x = 2, \quad x = -2}$$
#### 2. Domain
The domain consists of all real numbers except the two values that cause the denominator to be zero.
**Domain:** $\{x \mid x \neq 2, x \neq -2\}$ or $(-\infty, -2) \cup (-2, 2) \cup (2, \infty)$
#### 3. Classifying the Discontinuities
We check if either factor in the denominator cancels with the numerator:
* **Numerator:** $2x$
* **Denominator:** $(x - 2)(x + 2)$
Neither $(x - 2)$ nor $(x + 2)$ can be canceled by the $2x$ in the numerator. Therefore:
* **x = 2** is a **Vertical Asymptote**.
* **x = -2** is a **Vertical Asymptote**.

---
#### 4. Graphical Behavior
Since both discontinuities are asymptotes, we look at their multiplicities to determine the graph's appearance.

* **Multiplicity:** Both $(x - 2)$ and $(x + 2)$ have an exponent of **1** (**Odd**).
* **Behavior:** The graph will approach opposite infinities at both $x = 2$ and $x = -2$.
**Step-by-Step Visualizing:**
1.  **At x = -2:** As you approach from the left, the function goes down ($-\infty$); from the right, it comes from above ($+\infty$).
2.  **The Middle Section:** Between $x = -2$ and $x = 2$, the graph passes through the origin $(0,0)$ because the numerator $2(0) = 0$.
3.  **At x = 2:** As you approach from the left, the function goes down ($-\infty$); from the right, it comes from above ($+\infty$).

---
#### Summary Table
| Feature | Value | Type | Multiplicity |
| :--- | :--- | :--- | :--- |
| **Discontinuity 1** | $x = -2$ | Vertical Asymptote | Odd (1) |
| **Discontinuity 2** | $x = 2$ | Vertical Asymptote | Odd (1) |
| **X-Intercept** | $(0, 0)$ | Crossing Point | N/A |

> [!abstract] Algebra Takeaway
> Since there are two non-removable factors in the denominator, the graph is split into three distinct sections by two vertical "walls." Because the multiplicities are odd, the graph "jumps" from one infinity to the other as it passes each asymptote.

### Analysis of F(x) = \frac{x^2 - 9}{x^2 + 4x - 21}

To identify the behavior of this rational function, we must factor both the numerator and the denominator to find restricted values and classify them.

---
#### 1. Factoring and Setting Denominator to Zero
First, we factor the entire expression:
* **Numerator:** $x^2 - 9 = (x - 3)(x + 3)$
* **Denominator:** $x^2 + 4x - 21 = (x + 7)(x - 3)$

Setting the denominator to zero:
$$(x + 7)(x - 3) = 0$$
$$\mathbf{x = -7, \quad x = 3}$$

#### 2. Domain
The domain consists of all real numbers except those that cause division by zero.
**Domain:** $\{x \mid x \neq -7, x \neq 3\}$ or $(-\infty, -7) \cup (-7, 3) \cup (3, \infty)$

#### 3. Classifying the Discontinuities
We compare the factors in the numerator and denominator to see what simplifies:
$$F(x) = \frac{(x - 3)(x + 3)}{(x + 7)(x - 3)}$$

* **Discontinuity at x = 3:** The factor $(x - 3)$ appears in both the numerator and denominator. Since it cancels out, this is a **Hole (Removable Discontinuity)**.
* **Discontinuity at x = -7:** The factor $(x + 7)$ remains in the denominator after simplification. Therefore, this is a **Vertical Asymptote**.

---
#### 4. Graphical Behavior
The appearance of the graph is dictated by the simplified function: $f_{simp}(x) = \frac{x + 3}{x + 7}$.

* **At x = -7 (Vertical Asymptote):** * The multiplicity is **1** (odd).
    * The graph will approach opposite infinities ($\swarrow \nearrow$).
* **At x = 3 (Hole):** * There is a tiny "pothole" or open circle at this $x$-value. 
    * To find the $y$-coordinate: $\frac{3 + 3}{3 + 7} = \frac{6}{10} = 0.6$.
    * **Hole Location:** $(3, 0.6)$.

---
#### Summary Table
| Feature | Value | Type | Behavior |
| :--- | :--- | :--- | :--- |
| **Discontinuity 1** | $x = -7$ | Vertical Asymptote | Opposite Directions |
| **Discontinuity 2** | $x = 3$ | Hole | Open circle at $(3, 0.6)$ |
| **Multiplicity (at -7)** | 1 | Odd | $\swarrow \nearrow$ |

> [!abstract] Algebra Takeaway
> Even though both $3$ and $-7$ make the denominator zero, they behave differently on a graph. The factor that "disappears" through cancellation only creates a hole, while the factor that "stays" creates a vertical wall (asymptote).

## 2026-April-14 - Graphing Rational Functions with Transformations (Precalculus - College Algebra 39) :
https://www.youtube.com/watch?v=-k4uXF4hsAs&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=40
### Graphing Rational Functions with Transformations

Rational functions can be graphed by applying transformations to two primary "parent" functions: the **Reciprocal Function** ($1/x$) and the **Reciprocal Squared Function** ($1/x^2$). Understanding how $h, k,$ and $a$ modify these parents is the key to sketching them accurately.

---
#### 1. The Parent Functions
The shape of the graph is determined by the multiplicity of the factor in the denominator.

| Feature | $f(x) = \frac{1}{x}$ (Odd) | $f(x) = \frac{1}{x^2}$ (Even) |
| :--- | :--- | :--- |
| **V.A. Behavior** | Opposite Infinities ($\swarrow \nearrow$) | Same Infinity ($\uparrow \uparrow$) |
| **Symmetry** | Odd (Origin) | Even (y-axis) |
| **Key Points** | $(1, 1), (-1, -1)$ | $(1, 1), (-1, 1)$ |

---
#### 2. The Transformation Model: $f(x) = \frac{a}{(x - h)^n} + k$
Transformations are applied to the asymptotes first, then the points.

* **$h$ (Horizontal Shift):** Moves the **Vertical Asymptote**.
    * $x = h$ is the new V.A.
* **$k$ (Vertical Shift):** Moves the **Horizontal Asymptote**.
    * $y = k$ is the new H.A.
* **$a$ (Stretch & Reflection):**
    * If $a < 0$, the graph reflects across the **Horizontal Asymptote**.
    * $a$ acts as a vertical stretch/compression from the H.A.

---
#### 3. Graphing Steps (The "New Origin" Method)
Instead of plotting random points, use the intersection of the asymptotes $(h, k)$ as your reference point:

1.  **Sketch Asymptotes:** Draw $x = h$ and $y = k$ as dashed lines.
2.  **Determine Multiplicity:** * If $n$ is **odd**, use the "hyperbola" shape (opposite corners).
    * If $n$ is **even**, use the "volcano" shape (same side of H.A.).
3.  **Plot Transformative Key Points:**
    * From $(h, k)$, go right 1 and up $a$.
    * From $(h, k)$, go left 1 and up/down $a$ (depending on parent parity).
4.  **Find Intercepts:** * **y-int:** $f(0)$
    * **x-int:** Set numerator to 0 and solve.

---
#### Summary Table
| Transformation | Algebra | Graphical Change |
| :--- | :--- | :--- |
| **Horizontal Shift** | $f(x - h)$ | Moves the "Wall" (V.A.) |
| **Vertical Shift** | $f(x) + k$ | Moves the "Floor/Ceiling" (H.A.) |
| **Vertical Reflection** | $-f(x)$ | Flips graph over the H.A. |
| **Vertical Stretch** | $a \cdot f(x)$ | Pulls points away from the H.A. |

> [!tip] Limit Logic
> Think of the Horizontal Asymptote ($y=k$) as the "end behavior." As $x$ gets extremely large or small, the fraction part of the equation disappears (approaches zero), leaving only the $k$ value behind.

### Analysis of $f(x) = \frac{1}{x^2} + 3$

This function is a transformation of the **Reciprocal Squared** parent function. We determine its behavior by analyzing the shifts applied to the parent's asymptotes and symmetry.

---
#### 1. Parent Function & Symmetry
* **Parent:** $y = \frac{1}{x^2}$
* **Symmetry:** This is an **Even** function. 
    * Algebraically: $f(-x) = \frac{1}{(-x)^2} + 3 = \frac{1}{x^2} + 3$. Since $f(-x) = f(x)$, it is even.
    * Graphically: It is symmetric with respect to the $y$-axis.
#### 2. Transformations & Offsets
The function follows the model $f(x) = \frac{a}{(x-h)^n} + k$.
* **Horizontal Shift ($h$):** There is no value subtracted from $x$ in the denominator ($h=0$). The **Vertical Asymptote** remains at **$x = 0$**.
* **Vertical Shift ($k$):** The $+3$ outside the fraction moves the entire graph **Up 3 units**. The **Horizontal Asymptote** shifts from $y=0$ to **$y = 3$**.
* **Stretch/Reflection ($a$):** $a=1$, so there is no reflection or vertical stretch.
#### 3. Graphical Appearance
* **The "Volcano" Shape:** Because the exponent is **even** (2), both sides of the graph approach the same infinity.
* **Vertical Asymptote:** The graph approaches $+\infty$ as $x$ gets closer to $0$ from both the left and right.
* **Horizontal Asymptote:** As $x \to \pm\infty$, the $\frac{1}{x^2}$ term approaches zero, and the graph flattens out along the line **$y = 3$**.
* **Key Points:** Relative to the new "center" $(0, 3)$, the points are $(1, 4)$ and $(-1, 4)$.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Parity** | Even |
| **Vertical Asymptote** | $x = 0$ |
| **Horizontal Asymptote** | $y = 3$ |
| **Transformations** | Vertical shift up 3 |
| **Behavior at V.A.** | Same direction ($\uparrow \uparrow$) |

> [!abstract] Algebra Takeaway
> Adding a constant to the end of a rational function acts as a vertical offset. While the "walls" (vertical asymptotes) stay put if the denominator doesn't change, the "floor" (horizontal asymptote) is lifted or lowered by that constant.

### Analysis of g(x) = \frac{1}{(x-1)^2} - 2

This function is a transformation of the **Reciprocal Squared** parent function. We determine its behavior by analyzing the shifts applied to the asymptotes and the parity of the function.

---
#### 1. Parent Function & Symmetry
* **Parent:** $y = \frac{1}{x^2}$
* **Parity (Even/Odd/Neither):** This function is **Neither**.
    * Algebraically: $g(-x) = \frac{1}{(-x-1)^2} - 2$. This does not equal $g(x)$ nor $-g(x)$.
    * While the *parent* function is even, the horizontal shift moves the axis of symmetry away from the $y$-axis ($x=0$), so the resulting function is no longer even.
#### 2. Transformations & Offsets
The function follows the model $g(x) = \frac{a}{(x-h)^n} + k$.

* **Horizontal Shift ($h$):** The $(x - 1)$ in the denominator shifts the graph **Right 1 unit**. The **Vertical Asymptote** moves to **$x = 1$**.
* **Vertical Shift ($k$):** The $-2$ at the end shifts the entire graph **Down 2 units**. The **Horizontal Asymptote** moves to **$y = -2$**.
* **Stretch/Reflection ($a$):** $a = 1$, so there is no vertical stretch or reflection.
#### 3. Graphical Appearance
* **The "Volcano" Shape:** Because the exponent is **even** (2), both sides of the graph approach the same infinity.
* **Vertical Asymptote:** The graph approaches $+\infty$ as $x$ approaches $1$ from both the left and right.
* **Horizontal Asymptote:** As $x \to \pm\infty$, the fraction approaches zero, and the graph flattens out along the line **$y = -2$**.
* **Key Points:** Relative to the intersection of the asymptotes $(1, -2)$, the key points are:
    * $(1+1, -2+1) \to (2, -1)$
    * $(1-1, -2+1) \to (0, -1)$ (This is also the y-intercept).

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Parity** | Neither |
| **Vertical Asymptote** | $x = 1$ |
| **Horizontal Asymptote** | $y = -2$ |
| **Transformations** | Right 1, Down 2 |
| **Behavior at V.A.** | Same direction ($\uparrow \uparrow$) |

> [!abstract] Algebra Takeaway
> Shifting a "volcano" graph $(1/x^2)$ horizontally removes its even parity relative to the y-axis, though it remains symmetric with respect to its own vertical asymptote ($x=1$). The vertical shift determines the new "ground level" the graph settles on as $x$ moves toward infinity.

### Analysis of $h(x) = \frac{-2}{(x+3)^2} - 4$

This function is a transformation of the **Reciprocal Squared** parent function. It features a reflection, a vertical stretch, and both horizontal and vertical shifts.

---
#### 1. Parent Function & Symmetry
* **Parent:** $y = \frac{1}{x^2}$
* **Parity (Even/Odd/Neither):** This function is **Neither**.
    * Algebraically: $h(-x) = \frac{-2}{(-x+3)^2} - 4$. This is not equal to $h(x)$ or $-h(x)$.
    * While the parent function is even, the horizontal shift to $x = -3$ moves the axis of symmetry away from the $y$-axis.
#### 2. Transformations & Offsets
The function follows the model $h(x) = \frac{a}{(x-h)^n} + k$.
* **Horizontal Shift ($h$):** The $(x + 3)$ in the denominator shifts the graph **Left 3 units**. The **Vertical Asymptote** is at **$x = -3$**.
* **Vertical Shift ($k$):** The $-4$ at the end shifts the graph **Down 4 units**. The **Horizontal Asymptote** is at **$y = -4$**.
* **Reflection & Stretch ($a$):**
    * The negative sign ($a = -2$) **reflects** the graph across the horizontal asymptote.
    * The value $2$ represents a **Vertical Stretch** by a factor of 2.
#### 3. Graphical Appearance
* **The "Well" Shape:** Because the exponent is **even** (2) but the leading coefficient is **negative**, both sides of the graph approach $-\infty$ instead of $+\infty$. This creates an upside-down volcano or a "pit" shape.
* **Vertical Asymptote:** The graph drops toward $-\infty$ as $x$ approaches $-3$ from both sides.
* **Horizontal Asymptote:** As $x \to \pm\infty$, the graph levels off at **$y = -4$**.
* **Key Points:** Relative to the asymptote intersection $(-3, -4)$:
    * Right 1, Down 2: $(-2, -6)$
    * Left 1, Down 2: $(-4, -6)$

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Parity** | Neither |
| **Vertical Asymptote** | $x = -3$ |
| **Horizontal Asymptote** | $y = -4$ |
| **Transformations** | Left 3, Down 4, Reflected, Vertically Stretched |
| **Behavior at V.A.** | Same direction ($\downarrow \downarrow$) |

> [!abstract] Algebra Takeaway
> The negative numerator is a "game changer" for the reciprocal squared parent—it flips the behavior from approaching positive infinity to negative infinity. Combined with the shifts, the entire "pit" is centered at $x = -3$ and sits below the line $y = -4$.

### Analysis of G(x) = -\frac{1}{x+1} + 2

This function is a transformation of the **Reciprocal** parent function ($1/x$). We analyze it by identifying the shifts and reflections applied to the parent's asymptotes and shape.

---
#### 1. Parent Function & Symmetry
* **Parent:** $y = \frac{1}{x}$
* **Parity (Even/Odd/Neither):** This function is **Neither**.
    * Algebraically: $G(-x) = -\frac{1}{-x+1} + 2$. This does not equal $G(x)$ or $-G(x)$.
    * While the parent function $1/x$ has odd symmetry (origin), the horizontal and vertical shifts move the center of symmetry away from $(0,0)$, breaking the parity.
#### 2. Transformations & Offsets
The function follows the model $G(x) = \frac{a}{(x-h)^n} + k$.
* **Horizontal Shift ($h$):** The $(x + 1)$ in the denominator shifts the graph **Left 1 unit**. The **Vertical Asymptote** is at **$x = -1$**.
* **Vertical Shift ($k$):** The $+2$ at the end shifts the graph **Up 2 units**. The **Horizontal Asymptote** is at **$y = 2$**.
* **Reflection ($a$):** The negative sign in front of the fraction ($a = -1$) **reflects** the graph across the horizontal asymptote.
#### 3. Graphical Appearance
* **Opposite Directions:** Because the exponent is **odd** (1), the graph approaches opposite infinities on either side of the asymptote.
* **Reflected Shape:** Usually, $1/x$ is in the upper-right and lower-left quadrants. Because of the negative sign, this graph is in the **upper-left** and **lower-right** relative to the asymptotes.
* **Vertical Asymptote ($x = -1$):**
    * As $x \to -1^-$, $G(x) \to +\infty$ (Left side goes up).
    * As $x \to -1^+$, $G(x) \to -\infty$ (Right side goes down).
* **Key Points:** Relative to the intersection $(-1, 2)$:
    * Right 1, Down 1: $(0, 1)$ (This is the y-intercept).
    * Left 1, Up 1: $(-2, 3)$.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Parity** | Neither |
| **Vertical Asymptote** | $x = -1$ |
| **Horizontal Asymptote** | $y = 2$ |
| **Transformations** | Left 1, Up 2, Reflected |
| **Behavior at V.A.** | Opposite directions ($\nwarrow \searrow$) |

> [!abstract] Algebra Takeaway
> The negative sign "flips" the quadrants of the hyperbola. Instead of the standard "positive" behavior, the left side of the wall now shoots upward while the right side plunges downward.

## 2026-April-15 - Finding a Horizontal Asymptote of a Rational Function (Precalculus - College Algebra 40) :
https://www.youtube.com/watch?v=D-H9N-_Y77Y&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=42
### Finding Horizontal Asymptotes of Rational Functions

A horizontal asymptote (H.A.) describes the **end behavior** of a function. It is the $y$-value that the graph approaches as $x$ moves toward positive or negative infinity ($x \to \pm\infty$).

---
#### 1. The Three Cases (Degree Comparison)
To find the H.A., compare the degree of the numerator ($n$) to the degree of the denominator ($m$).

| Relationship | Rule | Asymptote |
| :--- | :--- | :--- |
| **$n < m$** | Denominator grows faster | $y = 0$ (x-axis) |
| **$n = m$** | Grow at the same rate | $y = \frac{\text{Leading Coefficient of } N(x)}{\text{Leading Coefficient of } D(x)}$ |
| **$n > m$** | Numerator grows faster | **None** (Potential Slant Asymptote) |

---
#### 2. Logic & Examples

**Case 1: Denominator is "Stronger" ($n < m$)**
If the degree of the bottom is higher, the denominator eventually becomes so large that the fraction shrinks to zero.
* **Example:** $f(x) = \frac{x^2 - 4}{x^3 + 5}$
* **Result:** H.A. is **$y = 0$**.

**Case 2: Degrees are "Equal" ($n = m$)**
If the degrees match, the $x$ variables essentially cancel each other out at infinity, leaving the ratio of the leading coefficients.
* **Example:** $f(x) = \frac{6x^2 + 1}{2x^2 - 5}$
* **Calculation:** $y = \frac{6}{2} = 3$
* **Result:** H.A. is **$y = 3$**.

**Case 3: Numerator is "Stronger" ($n > m$)**
If the top grows faster, the function will head toward $\pm\infty$ rather than leveling off.
* **Example:** $f(x) = \frac{x^2}{x - 1}$
* **Result:** **No Horizontal Asymptote**.

---
#### 3. Important Rules
* **Crossing the Asymptote:** Unlike vertical asymptotes (which are domain restrictions), a graph **can** cross a horizontal asymptote in its middle section. The H.A. only dictates the behavior at the "tails" of the graph.
* **Exclusivity:** A rational function can have at most **one** horizontal asymptote.
* **Limit Definition:** In calculus, the H.A. is found by taking the limit: $\lim_{x \to \infty} f(x)$.

> [!abstract] Algebra Takeaway
> Think of a horizontal asymptote as the "ultimate destination" of the graph. It doesn't matter what happens near the origin; as you zoom out further and further, the graph will eventually settle onto this horizontal line.

### Analysis of $f(x) = \frac{4x^3 - 7x + 1}{7x^5 + 2x^3 - 3}$

To find the horizontal asymptote and understand the end behavior, we compare the degrees of the numerator and the denominator.

---
#### 1. Identifying the Degrees
* **Numerator Degree ($n$):** The highest exponent is **3**.
* **Denominator Degree ($m$):** The highest exponent is **5**.
#### 2. Determining the Horizontal Asymptote
Since the degree of the denominator ($m = 5$) is **greater** than the degree of the numerator ($n = 3$), we follow the rule for "Bottom-Heavy" functions:
* **Horizontal Asymptote:** **$y = 0$** (the x-axis).
#### 3. Why? (The Logic of Growth)
As $x$ becomes extremely large ($x \to \infty$ or $x \to -\infty$), the leading terms dominate the function. The function behaves like:
$$f(x) \approx \frac{4x^3}{7x^5} = \frac{4}{7x^2}$$
As $x$ grows, the denominator $7x^2$ grows significantly faster than the constant numerator. Dividing a small number by an increasingly massive number results in a value that approaches **zero**.

---
#### 4. End Behavior
The end behavior describes what happens to the $y$-value as $x$ moves to the far left and far right of the coordinate plane.
* **As $x \to \infty$, $f(x) \to 0$**
* **As $x \to -\infty$, $f(x) \to 0$**

#### 5. What the Graph Looks Like
* **At the "Tails":** Both the left and right ends of the graph will flatten out and hug the x-axis ($y=0$).
* **In the Center:** There may be turns, x-intercepts, or vertical asymptotes, but as you zoom out, the graph eventually gets pulled toward the height of zero.
* **Position:** Since the highest power in the simplified end-behavior model ($4/7x^2$) is even and the coefficient is positive, the "tails" of this specific function will both approach zero from **above** the x-axis as $x$ gets very large.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Numerator Degree** | 3 |
| **Denominator Degree** | 5 |
| **Comparison** | $n < m$ |
| **Horizontal Asymptote** | $y = 0$ |
| **End Behavior** | Approaches the x-axis from both sides |

> [!abstract] Algebra Takeaway
> When the denominator has a higher degree, it "wins" the tug-of-war at infinity. It pulls the entire function down to zero, regardless of what the numerator is doing.

### Analysis of $g(x) = \frac{8x^3 - 2x + 3}{2x^3 + x^2 - 7x + 5}$

To find the horizontal asymptote and determine the end behavior of this rational function, we compare the degrees of the numerator and the denominator.

---
#### 1. Identifying the Degrees
* **Numerator Degree ($n$):** The highest exponent is **3**.
* **Denominator Degree ($m$):** The highest exponent is **3**.

#### 2. Determining the Horizontal Asymptote
Since the degrees are **equal** ($n = m$), the horizontal asymptote is determined by the ratio of the leading coefficients.

* **Leading Coefficient of Numerator:** 8
* **Leading Coefficient of Denominator:** 2
* **Calculation:** \(y = \frac{8}{2} = 4\)

**Horizontal Asymptote:** **\(y = 4\)**

---
#### 3. Why? (The Logic of Growth)
At the "ends" of the graph (where \(x\) is a very large positive or negative number), the terms with the highest exponents dominate. All other terms (\(-2x, 3, x^2, -7x, 5\)) become insignificant by comparison.

The function effectively simplifies to its leading terms:
\[g(x) \approx \frac{8x^3}{2x^3}\]
As \(x \to \pm\infty\), the \(x^3\) terms cancel out, leaving the constant ratio of **4**. This is the height the graph settles on as it extends forever to the left and right.

---
#### 4. End Behavior
The end behavior describes the value the function approaches as \(x\) moves toward infinity:
* **As \(x \to \infty\), \(g(x) \to 4\)**
* **As \(x \to -\infty\), \(g(x) \to 4\)**

#### 5. What the Graph Looks Like
* **The "Tails":** On the far left and far right of the coordinate plane, the graph will flatten out and approach the dashed horizontal line at **\(y = 4\)**.
* **The Center:** While there may be vertical asymptotes or intercepts in the middle (where \(x\) is small), the function is "tethered" to the height of 4 at its extremities.
* **Approaching the Asymptote:** Depending on the values of the lower-degree terms, the graph might approach the line \(y = 4\) from above or below, and it is even possible for the graph to cross this horizontal line before eventually settling onto it.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Numerator Degree** | 3 |
| **Denominator Degree** | 3 |
| **Comparison** | \(n = m\) |
| **Horizontal Asymptote** | \(y = 4\) |
| **End Behavior** | Settles at height 4 on both ends |

> [!abstract] Algebra Takeaway
> When the "power" of the numerator and denominator is a tie, they cancel each other's growth out. The "winner" is the ratio of their coefficients, which dictates the altitude of the graph's end behavior.

## 2026-April-16 - Finding an Oblique Asymptote of a Rational Function (Precalculus - College Algebra 41) : 
https://www.youtube.com/watch?v=NVhaVk4wNu8&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=42
### Finding Oblique (Slant) Asymptotes of Rational Functions

An **Oblique Asymptote** (also called a **Slant Asymptote**) is a diagonal line that a rational function approaches as $x$ moves toward positive or negative infinity. It represents the "end behavior" of functions where the numerator is "stronger" than the denominator by a specific margin.

---
#### 1. The Condition for an Oblique Asymptote
An oblique asymptote occurs **only** when the degree of the numerator ($n$) is **exactly one greater** than the degree of the denominator ($m$). [00:02:14]

* **Condition:** $n = m + 1$
* **Exclusivity:** A function can have a Horizontal Asymptote **OR** an Oblique Asymptote, but **never both**. [00:04:01]

---
#### 2. Why It Happens (Leading Term Logic)
If you divide the leading terms of a function where the top is one degree higher (e.g., $x^2 / x$), the result is a first-degree polynomial (e.g., $x$). This linear result acts as the "guide" for the graph's ends. [00:03:05]

---
#### 3. How to Find the Equation: Long Division
To find the exact equation of the line ($y = mx + b$), you must use **Long Division** of polynomials. 

> [!important] The "Two-Step" Shortcut
> You only need to perform two iterations of long division to get the $mx$ and the $b$. You do **not** need the remainder. [00:09:57]

**Process Example:** $f(x) = \frac{3x^4 - x^2}{x^3 - x^2 + 1}$
1.  **First Division:** Divide the first term of the numerator by the first term of the denominator ($3x^4 \div x^3 = 3x$). This is your **slope ($mx$)**. [00:10:13]
2.  **Distribute & Subtract:** Multiply $3x$ by the entire divisor and subtract it from the numerator to find the new leading term. [00:11:33]
3.  **Second Division:** Divide the new leading term by the divisor's first term (e.g., $3x^3 \div x^3 = 3$). This is your **y-intercept ($b$)**. [00:13:02]
4.  **Result:** The Oblique Asymptote is **$y = 3x + 3$**.

---
#### 4. Graphical Characteristics
* **End Behavior:** Instead of flattening out like a horizontal asymptote, the graph will follow the diagonal path of the line $y = mx + b$ toward infinity. [00:02:27]
* **Crossing the Asymptote:** Just like horizontal asymptotes, the graph **can** cross an oblique asymptote in the middle sections. The asymptote only governs what happens at the far edges of the graph. [00:14:33]

---
#### Summary Table: End Behavior Cases
| Degree Comparison | Type of Asymptote | Calculation Method |
| :--- | :--- | :--- |
| **$n < m$** | Horizontal ($y = 0$) | None (Automatic) |
| **$n = m$** | Horizontal ($y = \text{ratio}$) | Ratio of leading coefficients |
| **$n = m + 1$** | **Oblique / Slant** | **Long Division** (ignore remainder) |
| **$n > m + 1$** | General End Behavior | Leading term simplification |

> [!tip] Remainder Irrelevance
> When doing the long division, once you have your constant term ($b$), stop. The remainder represents a fraction that approaches zero as $x \to \infty$, which is why it doesn't affect the line the graph follows at the ends. [00:15:14]

### Analysis of f(x) = \frac{3x^4 - x^2}{x^3 - x^2 + 1}

To determine if an oblique (slant) asymptote exists and how the graph behaves at infinity, we compare the degrees of the numerator and denominator.

---
#### 1. Identifying the Degrees
* **Numerator Degree ($n$):** 4
* **Denominator Degree ($m$):** 3
* **Comparison:** Since $n = m + 1$ (the numerator is exactly one degree higher than the denominator), the function has an **Oblique Asymptote**.

#### 2. Finding the Equation (Long Division)
We divide the numerator by the denominator. We only need the linear part ($mx + b$) and can ignore the remainder.

**Step 1: Divide the first terms**
$$3x^4 \div x^3 = 3x$$
This gives us our $mx$.

**Step 2: Multiply and Subtract**
$3x(x^3 - x^2 + 1) = 3x^4 - 3x^3 + 3x$
Subtracting this from the original numerator ($3x^4 + 0x^3 - x^2 + 0x$):
$$(3x^4 - x^2) - (3x^4 - 3x^3 + 3x) = 3x^3 - x^2 - 3x$$

**Step 3: Divide again**
$$3x^3 \div x^3 = 3$$
This gives us our $b$.

**Oblique Asymptote:** **$y = 3x + 3$**

---
#### 3. Why? (End Behavior Logic)
As $x$ approaches infinity, the rational function behaves like the result of the division:
$$f(x) = (3x + 3) + \frac{\text{remainder}}{x^3 - x^2 + 1}$$
As $x \to \pm\infty$, the remainder fraction approaches **zero**. This leaves the function to follow the linear path of $y = 3x + 3$.

**End Behavior:**
* As $x \to \infty$, $f(x) \to \infty$ (following the line $3x+3$ upward).
* As $x \to -\infty$, $f(x) \to -\infty$ (following the line $3x+3$ downward).

---
#### 4. What the Graph Looks Like
* **Diagonal "Guide":** The graph will not level off horizontally. Instead, it will be "trapped" between its vertical asymptotes in the middle and follow the slanted line $y = 3x + 3$ as it moves off the screen.
* **The "Hugging" Effect:** Far away from the origin, the curve of the function will look almost identical to the straight line $y = 3x + 3$.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Numerator Degree** | 4 |
| **Denominator Degree** | 3 |
| **Asymptote Type** | Oblique (Slant) |
| **Equation** | $y = 3x + 3$ |
| **End Behavior** | Follows the line $y = 3x + 3$ |

> [!abstract] Algebra Takeaway
> An oblique asymptote is simply the quotient of the numerator and denominator when the degrees differ by one. The "slant" tells you that the function's growth is linear at its extremities rather than constant (horizontal) or explosive (higher-degree curves).

## 2026-April-16 - Finding End Behavior of Rational Functions (Precalculus - College Algebra 42) :
https://www.youtube.com/watch?v=_cnmQXAo5XM&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=42
### Finding End Behavior of Rational Functions

End behavior describes the direction a graph takes as $x$ approaches positive or negative infinity ($x \to \pm\infty$). While horizontal and oblique asymptotes are types of end behavior, this lesson focuses on the "explosive" case where the numerator's degree is significantly larger than the denominator's.

---
#### 1. The Condition for General End Behavior
This case occurs when the degree of the numerator ($n$) is larger than the degree of the denominator ($m$) by **more than one**. [00:00:50]

* **Relationship:** $n > m + 1$
* **Result:** There is **no** horizontal asymptote and **no** oblique asymptote. Instead, the function mimics the behavior of a power function ($ax^p$). [00:01:40]
---
#### 2. The Power Function Model
To find the end behavior, you simplify the ratio of the **leading terms** of the numerator and denominator. [00:02:03]

**Example:** $f(x) = \frac{4x^5 + \dots}{x^3 + \dots}$
1.  **Isolate leading terms:** $\frac{4x^5}{x^3}$
2.  **Simplify:** $4x^{5-3} = 4x^2$
3.  **Result:** As $x \to \pm\infty$, the graph will look like the parabola $y = 4x^2$. [00:02:51]

---
#### 3. Analyzing the Model
Once you have your simplified power function, use your knowledge of polynomial end behavior to determine the "arrows" of the graph. [00:04:16]

| Simplified Result | Example Shape | Left End ($x \to -\infty$) | Right End ($x \to \infty$) |
| :--- | :--- | :--- | :--- |
| **Even Power, Pos. Coeff.** ($x^2, x^4$) | Volcano / Upward Parabola | $\to \infty$ | $\to \infty$ |
| **Even Power, Neg. Coeff.** ($-x^2$) | Pit / Downward Parabola | $\to -\infty$ | $\to -\infty$ |
| **Odd Power, Pos. Coeff.** ($x^3, x^5$) | Standard Cubic | $\to -\infty$ | $\to \infty$ |
| **Odd Power, Neg. Coeff.** ($-x^3$) | Reflected Cubic | $\to \infty$ | $\to -\infty$ |

---
#### 4. Middle vs. Ends
It is important to remember that while the "ends" follow these power function shapes, the **middle** of the graph can still contain: [00:03:14]
* Vertical Asymptotes (from non-removable factors in the denominator).
* X-intercepts (from the numerator).
* Holes (from removable factors).

The end behavior model only tells you where the graph is heading once it gets past all the "drama" in the center. [00:06:51]

---
#### Summary of Asymptote/End Behavior Hierarchy
| Degree Comparison | Resulting Behavior |
| :--- | :--- |
| **$n < m$** | Horizontal Asymptote at $y = 0$ |
| **$n = m$** | Horizontal Asymptote at $y = \text{ratio of coefficients}$ |
| **$n = m + 1$** | Oblique (Slant) Asymptote (Line: $y = mx + b$) |
| **$n > m + 1$** | **General End Behavior** (Power Function: $y = ax^p$) |

> [!abstract] Algebra Takeaway
> To find how any rational function ends, simply ignore everything except the highest powers on top and bottom and reduce the fraction. The resulting term tells you exactly which "parent function" the graph will resemble at the far edges of the coordinate plane.

### Analysis of $g(x) = \frac{4x^5 - 7x + 1}{x^3 + 1}$

To determine the asymptotes and end behavior of this rational function, we compare the degrees of the numerator and the denominator.

---
#### 1. Identifying the Degrees
* **Numerator Degree ($n$):** The highest exponent is **5**.
* **Denominator Degree ($m$):** The highest exponent is **3**.
#### 2. Determining Asymptotes
* **Horizontal Asymptote:** None. Since the numerator's degree is greater than the denominator's ($5 > 3$), the function does not level off at a constant $y$-value.
* **Oblique (Slant) Asymptote:** None. An oblique asymptote only occurs when the numerator is exactly one degree higher than the denominator ($n = m + 1$). Here, the difference is **2**.
* **Vertical Asymptote:** * Set the denominator to zero: $x^3 + 1 = 0 \implies x^3 = -1 \implies \mathbf{x = -1}$.
    * Since $x = -1$ does not make the numerator zero, there is a **Vertical Asymptote at $x = -1$**.

---
#### 3. End Behavior (The Power Function Model)
When the degree of the numerator is more than one greater than the denominator, the graph mimics the behavior of a power function ($y = ax^p$) as $x \to \pm\infty$. We find this by simplifying the ratio of the leading terms:

$$\text{End Behavior Model} = \frac{4x^5}{x^3} = 4x^2$$



* **As $x \to \infty$, $g(x) \to \infty$**
* **As $x \to -\infty$, $g(x) \to \infty$**
The ends of the graph will both point upward, just like a parabola.

---
#### 4. What the Graph Looks Like
* **The Ends:** Far away from the center, the graph looks like the parabola $y = 4x^2$, rising steeply on both the left and right sides.
* **The Middle:** * There is a vertical "wall" (asymptote) at $x = -1$.
    * Because the denominator factor $(x+1)$ is part of $(x^3+1)$ and has an odd multiplicity, the graph will approach opposite infinities at the asymptote.
    * As $x$ approaches $-1$ from the left, the function will likely shoot toward $+\infty$ (to match the parabolic end behavior).
    * As $x$ approaches $-1$ from the right, the function will likely shoot toward $-\infty$ before turning back up toward $+\infty$ to satisfy the right-side end behavior.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Numerator Degree** | 5 |
| **Denominator Degree** | 3 |
| **Horizontal/Oblique Asymptote** | None |
| **Vertical Asymptote** | $x = -1$ |
| **End Behavior Model** | $y = 4x^2$ |
| **Left End Behavior** | $\to \infty$ |
| **Right End Behavior** | $\to \infty$ |

> [!abstract] Algebra Takeaway
> Because the numerator is "stronger" than the denominator by a power of 2, the graph eventually ignores the fractional nature of the function and behaves like a quadratic. The vertical asymptote at $x = -1$ creates a local "break," but it doesn't stop the overall parabolic trend of the ends.

## 2026-April-18 - Finding Asymptotes and Holes of Rational Functions (Precalculus - College Algebra 43) :
https://www.youtube.com/watch?v=tyXWPcvSQvk&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=44
### Finding Asymptotes and Holes of Rational Functions

This lesson provides a structured, efficient workflow for identifying all graphical features of a rational function. Following this specific order limits redundant work and prepares you for full graphing. [00:00:12]

---
#### 1. Step-by-Step Workflow
1.  **End Behavior (First):** Use the leading terms to find the Horizontal Asymptote (HA), Oblique Asymptote (OA), or general end behavior. It is easier to do this in standard form before factoring. [00:01:02]
2.  **Factor Everything:** Factor both the numerator and denominator completely. [00:01:21]
3.  **Define Domain:** Identify values that make the denominator zero *before* canceling anything. [00:01:41]
4.  **Identify Holes vs. Vertical Asymptotes:**
    * **Holes:** If a factor cancels out.
    * **Vertical Asymptotes (VA):** If a factor does not cancel. [00:01:48]
5.  **Simplify and Evaluate:** If a hole exists, plug the $x$-value into the *simplified* function to find the exact $(x, y)$ coordinate of the hole. [00:01:53]

---
#### 2. Categorizing Discontinuities (The Domain)
A value excluded from the domain must manifest in one of two ways on the graph: [00:05:09]
##### Vertical Asymptotes (Non-Removable)
* Occur at $x$-values where the denominator is zero and the factor **cannot** be canceled.
* **Odd Multiplicity:** Graph approaches opposite infinities (one side up, one side down). [00:06:27]
* **Even Multiplicity:** Graph approaches the same infinity (both sides up or both sides down).
##### Holes (Removable)
* Occur at $x$-values where a factor in the denominator **can** be canceled with a factor in the numerator. [00:22:18]
* **Crucial Step:** You must find the $y$-coordinate. The graph will look identical to the simplified version, just with a single point missing. [00:24:55]
---
#### 3. End Behavior Recall
| Degree Comparison | Result | Method |
| :--- | :--- | :--- |
| **$n < m$** | HA at $y = 0$ | Denominator outpaces numerator. [00:08:25] |
| **$n = m$** | HA at $y = \frac{\text{leading coeff.}}{\text{leading coeff.}}$ | Degrees are tied. [00:03:50] |
| **$n = m + 1$** | Oblique Asymptote | Use long division (first two steps). [00:34:31] |
| **$n > m + 1$** | Power Function | Simplify leading terms ratio. [00:16:53] |

---
#### 4. Unique Cases: The Oblique-Function Match
Sometimes, if a function simplifies into a linear equation (e.g., $g(x) = 2x - 1$ after canceling a hole), the "oblique asymptote" is actually the function itself. The graph is simply that line with a hole poked in it. [00:46:19]

---
#### Summary Checklist for Graphing
* [ ] Find HA/OA using leading terms.
* [ ] Factor and list domain restrictions.
* [ ] Label each restriction as a VA or a Hole.
* [ ] For Holes: Find the $y$-coordinate by plugging $x$ into the simplified version.
* [ ] For VAs: Determine if they are Odd or Even.

> [!abstract] Algebra Takeaway
> Always define your domain **before** you simplify. If you simplify first, you "lose" the information about the holes, which results in an incomplete and incorrect graph.

### Analysis of $f(x) = \frac{3x+5}{x-6}$

Following the lesson's structured workflow, we analyze the function from the outside in (end behavior first, then local features).

---
#### 1. End Behavior (Leading Term Analysis)
Before factoring or simplifying, we compare the degrees of the numerator and denominator.
* **Numerator Degree ($n$):** 1 (from $3x^1$)
* **Denominator Degree ($m$):** 1 (from $x^1$)
* **Comparison ($n = m$):** Since the degrees are equal, the **Horizontal Asymptote (H.A.)** is the ratio of the leading coefficients.
    * $y = \frac{3}{1} = 3$

**End Behavior:**
* As $x \to \infty, f(x) \to 3$
* As $x \to -\infty, f(x) \to 3$

---
#### 2. Domain & Discontinuities (Factoring)
The function is already in its simplest factored form: $f(x) = \frac{3x+5}{x-6}$.

* **Domain Restriction:** Set denominator to zero: $x - 6 = 0 \implies x = 6$.
* **Vertical Asymptote (V.A.) vs. Hole:** Since the factor $(x-6)$ does not cancel out with anything in the numerator, it is a **Vertical Asymptote**.
    * **V.A. at $x = 6$**
* **Multiplicity:** The factor $(x-6)$ has a power of 1 (odd). The graph will approach **opposite infinities** at the asymptote.

---
#### 3. Local Intercepts
* **y-intercept:** Set $x=0$.
    * $f(0) = \frac{3(0)+5}{0-6} = -\frac{5}{6} \approx -0.83$
* **x-intercept:** Set numerator to zero.
    * $3x+5 = 0 \implies 3x = -5 \implies x = -\frac{5}{3} \approx -1.67$

---
#### 4. How and Why it Looks Like This
* **The Skeleton:** Imagine a crosshair formed by the dashed lines $y = 3$ (H.A.) and $x = 6$ (V.A.).
* **Quadrant Placement:**
    * To the left of $x=6$, the graph passes through $(-1.67, 0)$ and $(0, -0.83)$. Since these points are below the H.A. ($y=3$), the left branch lives in the "lower-left" region of the asymptote crosshair and dives toward $-\infty$ as it hits the wall.
    * To the right of $x=6$, because the V.A. has odd multiplicity, the graph must come from the opposite direction. It will start at $+\infty$ and curve down to "hug" the H.A. at $y=3$.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Horizontal Asymptote** | $y = 3$ |
| **Vertical Asymptote** | $x = 6$ |
| **Holes** | None |
| **x-intercept** | $(-1.67, 0)$ |
| **y-intercept** | $(0, -0.83)$ |
| **V.A. Behavior** | Opposite Directions ($\swarrow \nearrow$) |

> [!abstract] Algebra Takeaway
> Because the degrees are tied, the graph is "pulled" toward $y=3$ at the edges. The single restriction at $x=6$ creates a "break" in the graph where the function cannot exist, forcing the two branches to shoot off to infinity in opposite directions.

### Analysis of $g(x) = \frac{x^3}{x^4 - 1}$

Following the structured workflow from the lesson, we analyze the function's global behavior (asymptotes) and local behavior (holes/intercepts).

---
#### 1. End Behavior (Leading Term Analysis)
Before factoring, we compare the degrees of the numerator ($n$) and denominator ($m$).
* **Numerator Degree ($n$):** 3
* **Denominator Degree ($m$):** 4
* **Comparison ($n < m$):** This is a "bottom-heavy" function. The denominator grows significantly faster than the numerator as $x \to \pm\infty$.

**Horizontal Asymptote (H.A.):** **$y = 0$** (the x-axis).

**End Behavior:**
* As $x \to \infty, g(x) \to 0$
* As $x \to -\infty, g(x) \to 0$
---
#### 2. Domain & Discontinuities (Factoring)
Now, we factor the denominator to find where the function is undefined.
$$g(x) = \frac{x^3}{(x^2 - 1)(x^2 + 1)} = \frac{x^3}{(x - 1)(x + 1)(x^2 + 1)}$$

* **Identify Domain Restrictions:**
    * $x - 1 = 0 \implies x = 1$
    * $x + 1 = 0 \implies x = -1$
    * $x^2 + 1 = 0 \implies$ No real solutions (imaginary).
* **Vertical Asymptotes (V.A.) vs. Holes:** Since none of these factors cancel with the $x^3$ in the numerator, both real roots are asymptotes.
    * **V.A. 1:** $x = 1$
    * **V.A. 2:** $x = -1$
* **Multiplicity:** Both factors $(x-1)$ and $(x+1)$ have an odd multiplicity (power of 1). The graph will approach **opposite infinities** at both walls.

---
#### 3. Local Intercepts & Symmetry
* **x-intercept:** Set numerator to zero. $x^3 = 0 \implies (0, 0)$.
* **y-intercept:** Set $x=0$. $g(0) = \frac{0}{-1} = 0 \implies (0, 0)$.
* **Parity:** $g(-x) = \frac{(-x)^3}{(-x)^4 - 1} = \frac{-x^3}{x^4 - 1}$. Since $g(-x) = -g(x)$, the function is **Odd**. It has origin symmetry.

---
#### 4. How and Why it Looks Like This
* **The Frame:** The graph is divided into three sections by the vertical walls at $x = -1$ and $x = 1$. It must level off to $y = 0$ at the far left and far right.
* **The "Tails":** * To the right of $x=1$: Plugging in $x=2$ gives a positive value ($\approx 0.53$), so the graph stays above the x-axis, coming from $+\infty$ and hugging $y=0$.
    * To the left of $x=-1$: Due to odd symmetry, this must be the opposite—the graph stays below the x-axis, coming from $-\infty$ and hugging $y=0$.
* **The Middle:** * Between $x = -1$ and $x = 1$: The graph must pass through the origin $(0,0)$. Since it goes toward $-\infty$ as it hits $x=1$ from the left (to be opposite the right-side tail), it must come from $+\infty$ at $x=-1$. It creates a "snake-like" curve through the origin.
---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Horizontal Asymptote** | $y = 0$ |
| **Vertical Asymptotes** | $x = 1$ and $x = -1$ |
| **Holes** | None |
| **x/y-intercept** | $(0, 0)$ |
| **Symmetry** | Odd (Origin) |
| **V.A. Behavior** | Opposite Directions at both $1$ and $-1$ |

> [!abstract] Algebra Takeaway
> Because the denominator is higher degree, the graph is "anchored" to the x-axis at its ends. The two vertical asymptotes break the graph into three distinct pieces, and the odd symmetry ensures that whatever happens in the upper-right quadrant is mirrored upside-down in the lower-left.

### Analysis of $G(x) = \frac{x^4 - 16}{x^2 - 2x}$

Following the lesson's workflow, we determine the function's end behavior, identify domain restrictions, and distinguish between vertical asymptotes and holes.

---
#### 1. End Behavior (Leading Term Analysis)
Before factoring, we compare the degrees of the numerator ($n$) and denominator ($m$).
* **Numerator Degree ($n$):** 4
* **Denominator Degree ($m$):** 2
* **Comparison ($n > m + 1$):** Since the numerator is more than one degree higher than the denominator ($4 > 2+1$), there is no horizontal or oblique asymptote. Instead, the function follows a **Power Function Model**.

**End Behavior Model:**
$$\frac{x^4}{x^2} = x^2$$

**End Behavior:**
* As $x \to \infty, G(x) \to \infty$
* As $x \to -\infty, G(x) \to \infty$
The graph will ultimately behave like an upward-opening parabola at its far ends.
---
#### 2. Factor and Define Domain
We must factor both the numerator and denominator completely to find the restrictions.

* **Numerator:** $x^4 - 16 = (x^2 - 4)(x^2 + 4) = (x - 2)(x + 2)(x^2 + 4)$
* **Denominator:** $x^2 - 2x = x(x - 2)$

**The Full Function:**
$$G(x) = \frac{(x - 2)(x + 2)(x^2 + 4)}{x(x - 2)}$$

**Domain Restrictions:** $x \neq 0$ and $x \neq 2$.

---
#### 3. Holes vs. Vertical Asymptotes
* **Hole:** The factor $(x - 2)$ exists in both the top and bottom. It cancels out.
    * There is a **Hole at $x = 2$**.
    * To find the $y$-coordinate, plug $x=2$ into the simplified version:
      $$\frac{(2 + 2)(2^2 + 4)}{2} = \frac{(4)(8)}{2} = \frac{32}{2} = 16$$
    * **Hole Location:** $(2, 16)$.
* **Vertical Asymptote (V.A.):** The factor $x$ remains in the denominator after cancellation.
    * There is a **Vertical Asymptote at $x = 0$**.
    * **Multiplicity:** The factor $x$ is power 1 (odd), so the graph will approach **opposite infinities**.

---
#### 4. Simplified Function for Graphing
After canceling the $(x-2)$, the "guide" function is:
$$y = \frac{(x + 2)(x^2 + 4)}{x} = \frac{x^3 + 2x^2 + 4x + 8}{x}$$

**x-intercepts:** Set the remaining numerator to zero.
* $x + 2 = 0 \implies x = -2$.
* $x^2 + 4 = 0 \implies$ No real roots.
* **Intercept:** $(-2, 0)$.

---
#### 5. How and Why it Looks Like This
* **The "Parabolic" Ends:** Because the end behavior is $x^2$, the graph shoots upward to the left and right.
* **The Wall at $x=0$:** As the graph approaches the y-axis ($x=0$):
    * From the left (near $x=-2$), it passes through the intercept and dives toward $-\infty$ (since $y \approx 8/-0.1$ is negative).
    * From the right, due to odd multiplicity, it comes down from $+\infty$.
* **The Missing Point:** As the graph curves upward toward the right-side end behavior, it passes through the location $(2, 16)$, but there is an open circle (hole) there.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **End Behavior Model** | $y = x^2$ (Up/Up) |
| **Vertical Asymptote** | $x = 0$ (Opposite Directions) |
| **Hole Location** | $(2, 16)$ |
| **x-intercept** | $(-2, 0)$ |
| **y-intercept** | None (V.A. at $x=0$) |

> [!abstract] Algebra Takeaway
> While the function looks like a simple curve at the ends, the local features tell a different story: a vertical "chasm" at the y-axis and a specific "missing pixel" at $(2, 16)$. Always simplify to find holes, but remember the hole still represents an undefined value in the original domain.

### Analysis of $F(x) = \frac{2x^2 - 5x - 12}{3x^2 - 11x - 4}$

Following the lesson's structured workflow, we examine the function's global behavior first, then drill down into the local details (holes and asymptotes).

---
#### 1. End Behavior (Leading Term Analysis)
Compare the degrees of the numerator ($n$) and denominator ($m$) before factoring.
* **Numerator Degree ($n$):** 2
* **Denominator Degree ($m$):** 2
* **Comparison ($n = m$):** Since the degrees are equal, the **Horizontal Asymptote (H.A.)** is the ratio of the leading coefficients.
    * $y = \frac{2}{3}$

**End Behavior:**
* As $x \to \infty, F(x) \to \frac{2}{3}$
* As $x \to -\infty, F(x) \to \frac{2}{3}$

---
#### 2. Factor and Define Domain
To find local features, we factor both polynomials.

* **Numerator:** $2x^2 - 5x - 12 = (2x + 3)(x - 4)$
* **Denominator:** $3x^2 - 11x - 4 = (3x + 1)(x - 4)$

**The Full Function:**
$$F(x) = \frac{(2x + 3)(x - 4)}{(3x + 1)(x - 4)}$$

**Domain Restrictions:** $x \neq 4$ and $x \neq -\frac{1}{3}$.

---
#### 3. Holes vs. Vertical Asymptotes
* **Hole:** The factor $(x - 4)$ is common to both the numerator and denominator and cancels out.
    * There is a **Hole at $x = 4$**.
    * Plug $x = 4$ into the simplified function $\frac{2x + 3}{3x + 1}$ to find the $y$-coordinate:
      $$\frac{2(4) + 3}{3(4) + 1} = \frac{8 + 3}{12 + 1} = \frac{11}{13}$$
    * **Hole Location:** $(4, \frac{11}{13})$ or approximately $(4, 0.85)$.
* **Vertical Asymptote (V.A.):** The factor $(3x + 1)$ remains in the denominator.
    * There is a **Vertical Asymptote at $x = -\frac{1}{3}$**.
    * **Multiplicity:** Odd (power of 1), so the graph approaches **opposite infinities**.

---
#### 4. Local Intercepts
Using the simplified function $y = \frac{2x + 3}{3x + 1}$:
* **x-intercept:** Set numerator to zero. $2x + 3 = 0 \implies x = -1.5$. Intercept: $(-1.5, 0)$.
* **y-intercept:** Set $x = 0$. $F(0) = \frac{3}{1} = 3$. Intercept: $(0, 3)$.

---
#### 5. How and Why it Looks Like This
* **The Frame:** The graph is built around the "skeleton" of the H.A. at $y \approx 0.67$ and the V.A. at $x \approx -0.33$.
* **The Left Branch:** To the left of the V.A., the graph passes through $(-1.5, 0)$. As it moves toward the V.A. from the left, it dives toward $-\infty$. As it moves to the left, it levels off toward $y = 2/3$.
* **The Right Branch:** To the right of the V.A., the graph passes through $(0, 3)$. Since this is above the H.A., the graph comes down from $+\infty$ at the V.A. and slowly approaches $y = 2/3$ as $x$ increases.
* **The "Missing Pixel":** As the right branch levels off, it must have an open circle at the exact coordinate $(4, 11/13)$ to account for the hole.

---
#### Summary Table
| Feature                  | Value / Description              |
| :----------------------- | :------------------------------- |
| **Horizontal Asymptote** | $y = 2/3$                        |
| **Vertical Asymptote**   | $x = -1/3$ (Opposite Directions) |
| **Hole Location**        | $(4, 11/13)$                     |
| **x-intercept**          | $(-1.5, 0)$                      |
| **y-intercept**          | $(0, 3)$                         |

> [!abstract] Algebra Takeaway
> This function looks almost exactly like a simple hyperbola, but the factoring reveals that the point at $x = 4$ is actually undefined. The "tie" in degrees ensures the graph never wanders too far from the $y = 2/3$ line at the far ends.

### Analysis of $g(x) = \frac{x^3 - 8}{x^2 - 5x + 6}$

Following the lesson's workflow, we analyze the global behavior first, then decompose the function to find local features like holes and intercepts.

---
#### 1. End Behavior (Leading Term Analysis)
We compare the degrees of the numerator ($n$) and denominator ($m$) to identify the asymptote type.
* **Numerator Degree ($n$):** 3
* **Denominator Degree ($m$):** 2
* **Comparison ($n = m + 1$):** Since the numerator is exactly one degree higher, the function has an **Oblique (Slant) Asymptote**.

**Finding the Slant Asymptote (Long Division):**
We divide $x^3 + 0x^2 + 0x - 8$ by $x^2 - 5x + 6$.
1.  $x^3 \div x^2 = \mathbf{x}$
2.  $x(x^2 - 5x + 6) = x^3 - 5x^2 + 6x$. Subtracting this from the numerator leaves $5x^2 - 6x - 8$.
3.  $5x^2 \div x^2 = \mathbf{5}$
* **Oblique Asymptote:** **$y = x + 5$**

**End Behavior:**
* As $x \to \infty, g(x) \to \infty$ (following the line $y = x + 5$).
* As $x \to -\infty, g(x) \to -\infty$ (following the line $y = x + 5$).

---
#### 2. Factor and Define Domain
Now we factor completely to find discontinuities.
* **Numerator (Difference of Cubes):** $x^3 - 8 = (x - 2)(x^2 + 2x + 4)$
* **Denominator (Trinomial):** $x^2 - 5x + 6 = (x - 2)(x - 3)$

**The Full Function:**
$$g(x) = \frac{(x - 2)(x^2 + 2x + 4)}{(x - 2)(x - 3)}$$

**Domain Restrictions:** $x \neq 2$ and $x \neq 3$.

---
#### 3. Holes vs. Vertical Asymptotes
* **Hole:** The factor $(x - 2)$ cancels out.
    * There is a **Hole at $x = 2$**.
    * Plug $x = 2$ into the simplified version $\frac{x^2 + 2x + 4}{x - 3}$:
        $$\frac{(2)^2 + 2(2) + 4}{2 - 3} = \frac{4 + 4 + 4}{-1} = -12$$
    * **Hole Location:** $(2, -12)$.
* **Vertical Asymptote (V.A.):** The factor $(x - 3)$ remains.
    * There is a **Vertical Asymptote at $x = 3$**.
    * **Multiplicity:** Odd, so the graph approaches **opposite infinities**.

---
#### 4. Local Intercepts
Using the simplified function $y = \frac{x^2 + 2x + 4}{x - 3}$:
* **x-intercept:** Set numerator to zero ($x^2 + 2x + 4 = 0$). The discriminant ($b^2 - 4ac$) is $4 - 16 = -12$. No real roots. **No x-intercepts**.
* **y-intercept:** Set $x = 0$. $g(0) = \frac{-8}{6} = -\frac{4}{3} \approx -1.33$.

---
#### 5. How and Why it Looks Like This
* **The Slant:** Far from the origin, the graph "hugs" the diagonal line $y = x + 5$.
* **The Wall:** At $x = 3$, the graph splits. 
    * To the right of $x = 3$, the values are positive and large, shooting to $+\infty$ and then curving down to follow the slant asymptote.
    * To the left of $x = 3$, the graph shoots down to $-\infty$. 
* **The Gap:** As the graph heads down from the y-intercept toward the vertical asymptote, there is an open circle at $(2, -12)$.
---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Oblique Asymptote** | $y = x + 5$ |
| **Vertical Asymptote** | $x = 3$ (Opposite Directions) |
| **Hole Location** | $(2, -12)$ |
| **x-intercept** | None |
| **y-intercept** | $(0, -1.33)$ |

> [!abstract] Algebra Takeaway
> This function's growth is linear at the edges because the numerator is exactly one degree higher than the denominator. The "cancelation" at $x=2$ keeps the graph from having a second vertical asymptote, turning that potential wall into a single missing point.

### Analysis of $H(x) = \frac{6x^2 + 7x - 5}{3x + 5}$

Following the lesson's structured workflow, we examine the global behavior first, then decompose the function to find local features like holes and intercepts.

---
#### 1. End Behavior (Leading Term Analysis)
Compare the degrees of the numerator ($n$) and denominator ($m$) to identify the asymptote type.
* **Numerator Degree ($n$):** 2
* **Denominator Degree ($m$):** 1
* **Comparison ($n = m + 1$):** Since the numerator is exactly one degree higher, the function has an **Oblique (Slant) Asymptote**.

**Finding the Slant Asymptote (Long Division):**
We divide $6x^2 + 7x - 5$ by $3x + 5$.
1.  $6x^2 \div 3x = \mathbf{2x}$
2.  $2x(3x + 5) = 6x^2 + 10x$. Subtracting this from the numerator ($6x^2 + 7x$) leaves $-3x - 5$.
3.  $-3x \div 3x = \mathbf{-1}$
* **Oblique Asymptote:** **$y = 2x - 1$**

**End Behavior:**
* As $x \to \infty, H(x) \to \infty$ (following the line $y = 2x - 1$).
* As $x \to -\infty, H(x) \to -\infty$ (following the line $y = 2x - 1$).

---
#### 2. Factor and Define Domain
Now we factor completely to find discontinuities.
* **Numerator (Trinomial):** $6x^2 + 7x - 5 = (3x + 5)(2x - 1)$
* **Denominator:** $(3x + 5)$

**The Full Function:**
$$H(x) = \frac{(3x + 5)(2x - 1)}{(3x + 5)}$$

**Domain Restriction:** Set $3x + 5 = 0 \implies \mathbf{x \neq -5/3}$.

---
#### 3. Holes vs. Vertical Asymptotes
* **Hole:** The factor $(3x + 5)$ exists in both the top and bottom and cancels out completely.
    * There is a **Hole at $x = -5/3$**.
    * Plug $x = -5/3$ into the simplified version $(2x - 1)$ to find the $y$-coordinate:
        $$2(-5/3) - 1 = -10/3 - 3/3 = -13/3$$
    * **Hole Location:** $(-5/3, -13/3)$ or approximately $(-1.67, -4.33)$.
* **Vertical Asymptote (V.A.):** Since no factors remain in the denominator after cancellation, there is **no vertical asymptote**.

---
#### 4. Local Intercepts
Using the simplified function $y = 2x - 1$:
* **x-intercept:** Set $y = 0$. $2x - 1 = 0 \implies x = 0.5$. Intercept: $(0.5, 0)$.
* **y-intercept:** Set $x = 0$. $y = 2(0) - 1 = -1$. Intercept: $(0, -1)$.

---
#### 5. How and Why it Looks Like This
* **The "Line" Effect:** Because the denominator divides perfectly into the numerator, the graph is not a curve—it is a **straight line**.
* **The Visual:** The graph looks exactly like the linear function **$y = 2x - 1$**.
* **The Removable Discontinuity:** There is one single "missing pixel" or open circle at the coordinate $(-5/3, -13/3)$.
* **Why:** The end behavior (oblique asymptote) and the function itself are identical in this case because there is no remainder left over after division.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **End Behavior / OA** | $y = 2x - 1$ |
| **Vertical Asymptote** | None |
| **Hole Location** | $(-1.67, -4.33)$ |
| **x-intercept** | $(0.5, 0)$ |
| **y-intercept** | $(0, -1)$ |

> [!abstract] Algebra Takeaway
> When the denominator is a factor of the numerator, the "asymptote" is the function. The graph isn't "approaching" the line $y = 2x - 1$ at infinity; it is *on* the line for every value except the hole at $x = -5/3$.

## 2026-April-19 - Graphing Rational Functions (Precalculus - College Algebra 44) :
https://www.youtube.com/watch?v=wHATRiYbPPA&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=45
### Graphing Rational Functions: The Master Workflow

Graphing rational functions is the culmination of finding asymptotes, holes, and intercepts. The key is to build a "skeleton" first and then use test points to determine where the branches of the graph live. [00:01:10]

---
#### 1. The Seven-Step Graphing Strategy
To ensure accuracy, follow this specific order of operations: [00:02:45]

1.  **Find the Y-Intercept:** Evaluate $f(0)$.
2.  **Factor & Simplify:** Factor the numerator and denominator.
    * **Identify Holes:** Any factors that cancel create a hole. Find the $y$-coordinate by plugging the $x$-value into the simplified function. [00:04:12]
3.  **Find the X-Intercepts:** Set the simplified numerator to zero.
4.  **Find Vertical Asymptotes (V.A.):** Set the simplified denominator to zero. Note the **multiplicity** of each VA (Odd = opposite directions, Even = same direction). [00:06:30]
5.  **Find the Horizontal or Oblique Asymptote:** Compare the degrees of the original numerator ($n$) and denominator ($m$). [00:08:15]
6.  **Check for Asymptote Intersection:** Determine if the graph crosses the horizontal/oblique asymptote by setting the simplified function equal to the asymptote's value/equation. [00:10:05]
7.  **Plot & Connect:** Use all identified features and add "test points" if a region is still ambiguous.
---
#### 2. Understanding Multiplicity at the Vertical Asymptote
The behavior of the graph as it approaches a vertical asymptote is determined by the exponent of the factor in the denominator: [00:15:20]

* **Odd Multiplicity (e.g., $(x-c)^1$):** The graph shoots to $+\infty$ on one side and $-\infty$ on the other. [00:16:45]
* **Even Multiplicity (e.g., $(x-c)^2$):** The graph shoots toward the **same** infinity on both sides (forming a "volcano" or "pit" shape). [00:18:10]
---
#### 3. Testing Regions
If you are unsure where a branch is located, choose an $x$-value in that interval and determine if the resulting $y$-value is positive or negative. [00:25:30]

* **Tip:** You don't always need the exact value; you just need to know if the point is **above or below** the horizontal asymptote or x-axis. [00:27:10]
---
#### 4. Summary of End Behavior
The Horizontal/Oblique asymptote acts as a "magnet" for the far ends of the graph ($x \to \pm\infty$). [00:35:12]

| Case | Degree Comparison | End Behavior Result |
| :--- | :--- | :--- |
| **I** | $n < m$ | $y = 0$ (x-axis) |
| **II** | $n = m$ | $y = \text{ratio of leading coefficients}$ |
| **III** | $n = m + 1$ | $y = mx + b$ (Slant Asymptote) |
| **IV** | $n > m + 1$ | $y = ax^{(n-m)}$ (Power Function) |

---
#### 5. Common "Gotchas"
* **Crossing the H.A.:** Students often think graphs cannot cross asymptotes. While they **never** cross vertical asymptotes, they frequently cross horizontal or oblique asymptotes in the "middle" of the graph. [00:45:10]
* **Holes:** Always represent a hole with an open circle. If you don't find the $y$-coordinate, your graph's path may look disconnected or incorrect. [00:48:22]

> [!abstract] Algebra Takeaway
> Think of a rational function graph as a puzzle. The asymptotes and intercepts provide the border and the corners; the test points and multiplicity rules fill in the middle pieces. Always define your domain and find holes *before* you start drawing lines.

### Analysis of $f(x) = \frac{x-1}{x^2 - 4}$

Following the seven-step strategy, we build the graph from the ground up by identifying its "skeleton" features first.

---
#### 1. Y-Intercept
Set $x = 0$:
$$f(0) = \frac{0 - 1}{0^2 - 4} = \frac{-1}{-4} = 0.25$$
**Intercept:** $(0, 0.25)$

#### 2. Factor & Simplify
$$f(x) = \frac{x - 1}{(x - 2)(x + 2)}$$
* **Holes:** No factors cancel between the numerator and denominator. **There are no holes.**
#### 3. X-Intercepts
Set the numerator to zero:
$$x - 1 = 0 \implies x = 1$$
**Intercept:** $(1, 0)$
#### 4. Vertical Asymptotes (V.A.)
Set the denominator factors to zero:
* $x - 2 = 0 \implies \mathbf{x = 2}$
* $x + 2 = 0 \implies \mathbf{x = -2}$
* **Multiplicity:** Both have a power of 1 (odd). The graph will approach **opposite infinities** at both $x = -2$ and $x = 2$.
#### 5. Horizontal Asymptote (H.A.)
Compare degrees:
* Degree of numerator ($n$) = 1
* Degree of denominator ($m$) = 2
* **Condition:** Since $n < m$ (bottom-heavy), the H.A. is **$y = 0$** (the x-axis).

#### 6. Asymptote Intersection
Does the graph cross the H.A. ($y = 0$)?
Set the function equal to 0:
$$0 = \frac{x-1}{x^2-4} \implies 0 = x - 1 \implies x = 1$$
Yes, the graph crosses its horizontal asymptote at the point **$(1, 0)$**.

---
#### 7. How and Why the Graph Looks Like This
The graph is divided into three distinct regions by the two vertical asymptotes.

* **Left Region ($x < -2$):**
    Pick a test point ($x = -3$): $f(-3) = \frac{-4}{5} = -0.8$.
    The graph stays below the x-axis, "hugging" $y=0$ on the far left and diving toward $-\infty$ as it approaches $x = -2$.
* **Middle Region ($-2 < x < 2$):**
    The graph must pass through the y-intercept $(0, 0.25)$ and the x-intercept $(1, 0)$.
    As it approaches $x = -2$ from the right, it must go toward $+\infty$ (to be opposite the left-side branch). It then travels down through $(0, 0.25)$ and $(1, 0)$, continuing toward $-\infty$ as it hits $x = 2$.
* **Right Region ($x > 2$):**
    As it approaches $x = 2$ from the right, it must come from $+\infty$ (opposite the middle branch). It then curves down to "hug" the H.A. ($y = 0$) from above.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **Horizontal Asymptote** | $y = 0$ |
| **Vertical Asymptotes** | $x = -2, x = 2$ |
| **X-Intercept** | $(1, 0)$ |
| **Y-Intercept** | $(0, 0.25)$ |
| **Holes** | None |
| **Crosses H.A.?** | Yes, at $x = 1$ |

> [!abstract] Algebra Takeaway
> This is a classic "three-piece" rational function. The key observation is the intersection at $(1, 0)$; even though $y=0$ is an asymptote, the graph passes right through it before leveling off again at the far ends.

### Analysis of $f(x) = \frac{x^4 - 1}{x^2 - 4}$

Following the seven-step graphing strategy, we break down this higher-degree rational function to understand its global and local behaviors.

---
#### 1. Y-Intercept
Set $x = 0$:
$$f(0) = \frac{0^4 - 1}{0^2 - 4} = \frac{-1}{-4} = 0.25$$
**Intercept:** $(0, 0.25)$
#### 2. Factor & Simplify
* **Numerator (Difference of Squares twice):** $x^4 - 1 = (x^2 - 1)(x^2 + 1) = (x - 1)(x + 1)(x^2 + 1)$
* **Denominator:** $x^2 - 4 = (x - 2)(x + 2)$

**Full Factored Form:**
$$f(x) = \frac{(x - 1)(x + 1)(x^2 + 1)}{(x - 2)(x + 2)}$$
* **Holes:** No factors cancel. **There are no holes.**
#### 3. X-Intercepts
Set the numerator factors to zero:
* $x - 1 = 0 \implies x = 1$
* $x + 1 = 0 \implies x = -1$
* $x^2 + 1 = 0 \implies$ No real solutions.
**Intercepts:** $(1, 0)$ and $(-1, 0)$
#### 4. Vertical Asymptotes (V.A.)
Set the denominator factors to zero:
* $x - 2 = 0 \implies \mathbf{x = 2}$
* $x + 2 = 0 \implies \mathbf{x = -2}$
* **Multiplicity:** Both are power 1 (odd). The graph will approach **opposite infinities** at both walls.
#### 5. End Behavior (Asymptotes)
Compare degrees:
* Degree of numerator ($n$) = 4
* Degree of denominator ($m$) = 2
* **Condition:** Since $n > m + 1$ (numerator is more than one degree higher), there is no horizontal or oblique asymptote.
* **Power Function Model:** $\frac{x^4}{x^2} = x^2$.

**End Behavior:** The far ends of the graph will mimic an upward-opening parabola ($y \to \infty$ as $x \to \pm\infty$).
#### 6. Asymptote Intersection
Since there is no horizontal or oblique asymptote, we do not need to check for intersections with one. The graph will simply grow toward infinity at the ends.

---
#### 7. How and Why the Graph Looks Like This
The graph is divided into three sections by the V.A.s at $x = -2$ and $x = 2$.

* **Left Region ($x < -2$):**
    As $x \to -\infty$, the graph goes to $+\infty$ (matching our $x^2$ end behavior). As it approaches $x = -2$ from the left, it will shoot to $+\infty$. (You can verify with a test point like $x = -3$, which yields a positive value).
* **Middle Region ($-2 < x < 2$):**
    The graph must pass through $(-1, 0)$, $(0, 0.25)$, and $(1, 0)$. 
    Since the V.A. at $x = -2$ is odd, if the left side went to $+\infty$, the right side must come from $-\infty$. It curves up through the x-intercepts and y-intercept (forming a small "hump") and then dives back to $-\infty$ as it hits $x = 2$.
* **Right Region ($x > 2$):**
    Following the odd multiplicity at $x = 2$, the graph comes down from $+\infty$ and then curves back up toward $+\infty$ to satisfy the parabolic end behavior.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **End Behavior Model** | $y = x^2$ (Up / Up) |
| **Vertical Asymptotes** | $x = -2, x = 2$ |
| **X-Intercepts** | $(-1, 0), (1, 0)$ |
| **Y-Intercept** | $(0, 0.25)$ |
| **Symmetry** | Even ($f(-x) = f(x)$) |

> [!abstract] Algebra Takeaway
> Because the numerator is two degrees higher, the function "wants" to be a parabola. The denominator acts as a local disruptor, "tearing" the parabola apart at $x = \pm 2$ and forcing the middle section to flip upside down.

### Analysis of $f(x) = \frac{3x^2 - 3x}{x^2 + x - 12}$

Following the specific order of operations from the lesson to ensure the "skeleton" of the graph is built correctly for your notes.

---
#### 1. Analyze End Behavior (Asymptotes)
Compare the degrees of the numerator ($n$) and denominator ($m$):
* **Numerator Degree ($n$):** 2
* **Denominator Degree ($m$):** 2
* **Comparison ($n = m$):** Since the degrees are equal, we have a **Horizontal Asymptote (H.A.)**.
    * $y = \frac{3}{1} = 3$
* **Behavior:** As $x \to \pm\infty, f(x) \to 3$.

---
#### 2. Factor the Function
Factor both the numerator and denominator completely:
* **Numerator:** $3x(x - 1)$
* **Denominator:** $(x + 4)(x - 3)$
* **Full Factored Form:** $f(x) = \frac{3x(x - 1)}{(x + 4)(x - 3)}$

---
#### 3. Define Domain & Identify Holes
* **Domain Restrictions:** Set the denominator factors to zero: $x \neq -4$ and $x \neq 3$.
* **Holes:** No factors are common to both the numerator and denominator. **There are no holes.**
* **Vertical Asymptotes (V.A.):** Since no factors canceled, both restrictions are asymptotes.
    * **V.A. 1:** $x = -4$ (Multiplicity 1: Opposite directions)
    * **V.A. 2:** $x = 3$ (Multiplicity 1: Opposite directions)

---
#### 4. Determine Zeroes and Multiplicity (Numerator)
Set the simplified numerator factors to zero to find the x-intercepts:
* $3x = 0 \implies x = 0$
* $x - 1 = 0 \implies x = 1$
* **Multiplicity:** Both intercepts have a multiplicity of 1, meaning the graph **crosses** the x-axis at both $(0, 0)$ and $(1, 0)$.

---
#### 5. Find the Y-Intercept
Evaluate $f(0)$:
* $f(0) = \frac{3(0)^2 - 3(0)}{0^2 + 0 - 12} = \frac{0}{-12} = 0$
* **Intercept:** $(0, 0)$ (This matches our x-intercept).

---
#### 6. Check for Asymptote Intersections
Does the graph cross the H.A. ($y = 3$)? Set the function equal to the asymptote value:
$$3 = \frac{3x^2 - 3x}{x^2 + x - 12}$$
$$3(x^2 + x - 12) = 3x^2 - 3x$$
$$3x^2 + 3x - 36 = 3x^2 - 3x$$
$$3x - 36 = -3x$$
$$6x = 36 \implies x = 6$$
**Intersection:** The graph crosses the horizontal asymptote at the point **$(6, 3)$**.

---
#### 7. Final Sketch: How and Why it Looks Like This
* **Left Section ($x < -4$):** Test $x = -5$. The value is positive and above the H.A. ($y \approx 11.25$). The graph comes from the H.A. and shoots up to $+\infty$.
* **Middle Section ($-4 < x < 3$):** Following opposite multiplicity, it comes from $-\infty$ at $x = -4$, crosses the x-axis at $(0,0)$, peaks slightly, crosses back through $(1,0)$, and dives to $-\infty$ at $x = 3$.
* **Right Section ($x > 3$):** It comes from $+\infty$ at $x = 3$. It curves down, **crosses through** the H.A. at $(6, 3)$, dips slightly below it, and then levels off back toward $y = 3$ from below.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **End Behavior (H.A.)** | $y = 3$ |
| **Vertical Asymptotes** | $x = -4, x = 3$ |
| **Holes** | None |
| **X-Intercepts** | $(0, 0)$ and $(1, 0)$ |
| **Y-Intercept** | $(0, 0)$ |
| **H.A. Intersection** | Yes, at $x = 6$ |

> [!abstract] Algebra Takeaway
> The intersection at $(6, 3)$ is the most critical detail. It proves that a horizontal asymptote is only a guide for the "ends" of the graph, not a forbidden zone in the middle.

### Analysis of $f(x) = \frac{2x^2 - 5x + 2}{x^2 - 4}$

Following the definitive graphing workflow:

---
#### 1. Analyze End Behavior (Asymptotes)
Compare the degrees of the numerator ($n$) and denominator ($m$):
* **Numerator Degree ($n$):** 2
* **Denominator Degree ($m$):** 2
* **Comparison ($n = m$):** Since the degrees are equal, there is a **Horizontal Asymptote (H.A.)**.
    * $y = \frac{2}{1} = 2$
* **Behavior:** As $x \to \pm\infty, f(x) \to 2$.

---
#### 2. Factor the Function
Factor both the numerator and denominator completely:
* **Numerator:** $2x^2 - 5x + 2 = (2x - 1)(x - 2)$
* **Denominator:** $x^2 - 4 = (x - 2)(x + 2)$
* **Full Factored Form:** $f(x) = \frac{(2x - 1)(x - 2)}{(x - 2)(x + 2)}$

---
#### 3. Define Domain & Identify Holes
* **Domain Restrictions:** Set original denominator to zero: $x \neq 2$ and $x \neq -2$.
* **Holes:** The factor $(x - 2)$ is common to both the top and bottom and cancels out.
    * There is a **Hole at $x = 2$**.
    * Plug $x = 2$ into the simplified function $\frac{2x - 1}{x + 2}$ to find the $y$-coordinate:
      $$\frac{2(2) - 1}{2 + 2} = \frac{3}{4} = 0.75$$
    * **Hole Location:** $(2, 0.75)$
* **Vertical Asymptotes (V.A.):** The factor $(x + 2)$ remains in the denominator.
    * **V.A.:** $x = -2$ (Multiplicity 1: Opposite directions)



---
#### 4. Determine Zeroes and Multiplicity (Numerator)
Set the **simplified** numerator factor to zero to find the x-intercept:
* $2x - 1 = 0 \implies x = 0.5$
* **Multiplicity:** Multiplicity of 1, so the graph **crosses** the x-axis at $(0.5, 0)$.

---
#### 5. Find the Y-Intercept
Evaluate $f(0)$ using the simplified function:
* $f(0) = \frac{2(0) - 1}{0 + 2} = -\frac{1}{2} = -0.5$
* **Intercept:** $(0, -0.5)$

---
#### 6. Check for Asymptote Intersections
Does the graph cross the H.A. ($y = 2$)? Set the simplified function equal to 2:
$$2 = \frac{2x - 1}{x + 2}$$
$$2(x + 2) = 2x - 1$$
$$2x + 4 = 2x - 1$$
$$4 = -1 \quad (\text{False})$$
**Result:** The graph **never crosses** the horizontal asymptote.

---
#### 7. Final Sketch: How and Why it Looks Like This
* **Left Section ($x < -2$):** As $x \to -\infty$, the graph hugs $y = 2$. As it approaches the wall at $x = -2$ from the left, the values shoot to $+\infty$ (e.g., test $x = -3$, $y = 7$).
* **Right Section ($x > -2$):** Due to odd multiplicity at the V.A., the graph must come from $-\infty$ on the right side of $x = -2$. It climbs through the y-intercept $(0, -0.5)$, crosses the x-axis at $(0.5, 0)$, passes through the **Hole at $(2, 0.75)$**, and levels off to hug $y = 2$ from below.
---
#### Summary Table
| Feature                 | Value / Description |
| :---------------------- | :------------------ |
| **End Behavior (H.A.)** | $y = 2$             |
| **Vertical Asymptote**  | $x = -2$            |
| **Hole Location**       | $(2, 0.75)$         |
| **X-Intercept**         | $(0.5, 0)$          |
| **Y-Intercept**         | $(0, -0.5)$         |
| **H.A. Intersection**   | None                |

### Analysis of $f(x) = \frac{x^3 - 1}{x^2 - 9}$

Following the definitive graphing workflow:

---
#### 1. Analyze End Behavior (Asymptotes)
Compare the degrees of the numerator ($n$) and denominator ($m$):
* **Numerator Degree ($n$):** 3
* **Denominator Degree ($m$):** 2
* **Comparison ($n = m + 1$):** Since the numerator is exactly one degree higher, there is an **Oblique (Slant) Asymptote**.

**Finding the Slant Asymptote (Long Division):**
Divide $x^3 + 0x^2 + 0x - 1$ by $x^2 - 9$.
1.  $x^3 \div x^2 = \mathbf{x}$
2.  $x(x^2 - 9) = x^3 - 9x$. Subtracting this from the numerator leaves $9x - 1$.
* **Oblique Asymptote:** **$y = x$**
* **End Behavior:** As $x \to \pm\infty$, the graph follows the line $y = x$.

---
#### 2. Factor the Function
Factor both the numerator and denominator completely:
* **Numerator (Difference of Cubes):** $(x - 1)(x^2 + x + 1)$
* **Denominator (Difference of Squares):** $(x - 3)(x + 3)$
* **Full Factored Form:** $f(x) = \frac{(x - 1)(x^2 + x + 1)}{(x - 3)(x + 3)}$

---
#### 3. Define Domain & Identify Holes
* **Domain Restrictions:** Set the denominator to zero: $x \neq 3$ and $x \neq -3$.
* **Holes:** No factors are common to both the top and bottom. **There are no holes.**
* **Vertical Asymptotes (V.A.):** Both restrictions are vertical walls.
    * **V.A. 1:** $x = 3$ (Multiplicity 1: Opposite directions)
    * **V.A. 2:** $x = -3$ (Multiplicity 1: Opposite directions)

---
#### 4. Determine Zeroes and Multiplicity (Numerator)
Set the numerator factors to zero to find the x-intercepts:
* $x - 1 = 0 \implies x = 1$
* $x^2 + x + 1 = 0 \implies$ No real solutions (Discriminant $1 - 4 = -3$).
* **Multiplicity:** Multiplicity of 1, so the graph **crosses** the x-axis at **$(1, 0)$**.

---
#### 5. Find the Y-Intercept
Evaluate $f(0)$:
* $f(0) = \frac{0^3 - 1}{0^2 - 9} = \frac{-1}{-9} = \frac{1}{9}$
* **Intercept:** $(0, 0.11)$

---
#### 6. Check for Asymptote Intersections
Does the graph cross the Slant Asymptote ($y = x$)? Set the function equal to $x$:
$$x = \frac{x^3 - 1}{x^2 - 9}$$
$$x(x^2 - 9) = x^3 - 1$$
$$x^3 - 9x = x^3 - 1$$
$$-9x = -1 \implies x = \frac{1}{9}$$
**Intersection:** The graph crosses the slant asymptote at the point **$(1/9, 1/9)$**.

---
#### 7. Final Sketch: How and Why it Looks Like This
* **Left Section ($x < -3$):** As $x \to -\infty$, the graph follows $y = x$ downward. As it approaches $x = -3$ from the left, it shoots to $-\infty$ (Test $x = -4$, $y \approx -9.3$).
* **Middle Section ($-3 < x < 3$):** Following opposite multiplicity, it comes from $+\infty$ at $x = -3$. It travels down through the y-intercept $(0, 1/9)$, the intersection $(1/9, 1/9)$, and the x-intercept $(1, 0)$, then dives to $-\infty$ as it hits $x = 3$.
* **Right Section ($x > 3$):** It comes from $+\infty$ at $x = 3$. It curves down and then heads back up toward $+\infty$ as it levels out to follow the line $y = x$.

---
#### Summary Table
| Feature                 | Value / Description |
| :---------------------- | :------------------ |
| **End Behavior (O.A.)** | $y = x$             |
| **Vertical Asymptotes** | $x = -3, x = 3$     |
| **Holes**               | None                |
| **X-Intercept**         | $(1, 0)$            |
| **Y-Intercept**         | $(0, 1/9)$          |
| **O.A. Intersection**   | Yes, at $x = 1/9$   |
### Analysis of $f(x) = \frac{x^2(x-1)^2}{(x+3)^4}$

Following the definitive graphing workflow:

---
#### 1. Analyze End Behavior (Asymptotes)
Compare the degrees of the numerator ($n$) and denominator ($m$):
* **Numerator Degree ($n$):** $x^2 \cdot x^2 = 4$
* **Denominator Degree ($m$):** 4
* **Comparison ($n = m$):** Since the degrees are equal, there is a **Horizontal Asymptote (H.A.)**.
    * $y = \frac{1}{1} = 1$
* **Behavior:** As $x \to \pm\infty, f(x) \to 1$.

---
#### 2. Factor the Function
The function is already provided in factored form:
$$f(x) = \frac{x^2(x - 1)^2}{(x + 3)^4}$$

---
#### 3. Define Domain & Identify Holes
* **Domain Restrictions:** Set the denominator to zero: $(x + 3)^4 = 0 \implies x \neq -3$.
* **Holes:** No factors cancel between the numerator and denominator. **There are no holes.**
* **Vertical Asymptote (V.A.):** * **V.A.:** $x = -3$
    * **Multiplicity:** 4 (**Even**). Because the multiplicity is even, the graph will shoot toward the **same infinity** on both sides of the asymptote.

---
#### 4. Determine Zeroes and Multiplicity (Numerator)
Set the numerator factors to zero to find the x-intercepts:
* $x^2 = 0 \implies x = 0$
* $(x - 1)^2 = 0 \implies x = 1$
* **Multiplicity:** Both zeros have a multiplicity of 2 (**Even**). The graph will **touch and turn around (bounce)** at both $(0, 0)$ and $(1, 0)$.

---
#### 5. Find the Y-Intercept
Evaluate $f(0)$:
* $f(0) = \frac{0^2(0 - 1)^2}{(0 + 3)^4} = \frac{0}{81} = 0$
* **Intercept:** $(0, 0)$

---
#### 6. Check for Asymptote Intersections
Does the graph cross the H.A. ($y = 1$)? Set the function equal to 1:
$$1 = \frac{x^2(x - 1)^2}{(x + 3)^4}$$
$$(x + 3)^4 = x^2(x - 1)^2$$
Take the square root of both sides:
$$(x + 3)^2 = \pm x(x - 1)$$

* **Case 1:** $x^2 + 6x + 9 = x^2 - x \implies 7x = -9 \implies x = -9/7$
* **Case 2:** $x^2 + 6x + 9 = -x^2 + x \implies 2x^2 + 5x + 9 = 0$ (No real solutions, $D = 25 - 72 = -47$).

**Intersection:** The graph crosses the horizontal asymptote at $x \approx -1.29$.

---
#### 7. Final Sketch: How and Why it Looks Like This
* **Left Section ($x < -3$):** As $x \to -\infty$, the graph hugs $y = 1$ from below. As it approaches the wall at $x = -3$, the values become large and positive. It shoots to $+\infty$.
* **Right Section ($x > -3$):** Because the V.A. has **even multiplicity**, the graph must also come from $+\infty$ on the right side of $x = -3$.
    * It dives down, crosses the H.A. at $x \approx -1.29$, and hits $(0, 0)$.
    * At $(0, 0)$, it **bounces** back up slightly, then comes back down to $(1, 0)$.
    * At $(1, 0)$, it **bounces** again and then levels off to approach the H.A. $y = 1$ from below.

---
#### Summary Table
| Feature | Value / Description |
| :--- | :--- |
| **End Behavior (H.A.)** | $y = 1$ |
| **Vertical Asymptote** | $x = -3$ (Same direction: Up/Up) |
| **Holes** | None |
| **X-Intercepts** | $(0, 0)$ and $(1, 0)$ (Both Bounce) |
| **Y-Intercept** | $(0, 0)$ |
| **H.A. Intersection** | Yes, at $x = -9/7$ |
### Analysis of $f(x) = 2x + \frac{9}{x}$

To follow the definitive graphing workflow, we first rewrite the function as a single rational expression by finding a common denominator.
$$f(x) = \frac{2x^2 + 9}{x}$$

---
#### 1. Analyze End Behavior (Asymptotes)
Compare the degrees of the numerator ($n$) and denominator ($m$):
* **Numerator Degree ($n$):** 2
* **Denominator Degree ($m$):** 1
* **Comparison ($n = m + 1$):** Since the numerator is exactly one degree higher, there is an **Oblique (Slant) Asymptote**.
* **Finding the Slant Asymptote:** Because the function was given as $2x + \frac{9}{x}$, the division is already done. As $x \to \pm\infty$, the remainder term $\frac{9}{x}$ goes to zero.
* **Oblique Asymptote:** **$y = 2x$**

---
#### 2. Factor the Function
* **Numerator:** $2x^2 + 9$ (This is a sum of squares and cannot be factored over real numbers).
* **Denominator:** $x$
* **Factored Form:** $f(x) = \frac{2x^2 + 9}{x}$

---
#### 3. Define Domain & Identify Holes
* **Domain Restriction:** Set the denominator to zero: $x \neq 0$.
* **Holes:** No factors cancel. **There are no holes.**
* **Vertical Asymptote (V.A.):** * **V.A.:** $x = 0$ (the y-axis).
    * **Multiplicity:** 1 (Odd). The graph will approach **opposite infinities** at $x = 0$.

---
#### 4. Determine Zeroes and Multiplicity (Numerator)
Set the numerator to zero:
* $2x^2 + 9 = 0 \implies x^2 = -4.5$
* **Result:** No real solutions. **There are no x-intercepts.**

---
#### 5. Find the Y-Intercept
Evaluate $f(0)$:
* Since $x = 0$ is a vertical asymptote, the function is undefined at the y-axis.
* **Result:** **No y-intercept.**

---
#### 6. Check for Asymptote Intersections
Does the graph cross the Slant Asymptote ($y = 2x$)? Set the function equal to $2x$:
$$2x = 2x + \frac{9}{x}$$
$$0 = \frac{9}{x}$$
* **Result:** There is no value for $x$ that satisfies this. The graph **never crosses** the slant asymptote.

---
#### 7. Final Sketch: How and Why it Looks Like This
The graph is confined to two regions split by the V.A. at $x=0$.

* **Right Section ($x > 0$):** * As $x$ gets very small (approaching 0), the term $\frac{9}{x}$ dominates and the graph shoots to $+\infty$.
    * As $x$ gets very large, the graph approaches the line $y = 2x$ from above.
    * (Test point $x=3$: $y = 2(3) + 9/3 = 9$).
* **Left Section ($x < 0$):**
    * Following the odd multiplicity at $x=0$, if the right side went to $+\infty$, the left side must come from $-\infty$.
    * The graph comes up from $-\infty$, reaches a local maximum, and then heads back down to follow the slant asymptote $y = 2x$ from below.
    * (Test point $x=-3$: $y = 2(-3) + 9/-3 = -9$).

---
#### Summary Table
| Feature                 | Value / Description |
| :---------------------- | :------------------ |
| **End Behavior (O.A.)** | $y = 2x$            |
| **Vertical Asymptote**  | $x = 0$             |
| **Holes**               | None                |
| **X-Intercepts**        | None                |
| **Y-Intercept**         | None                |
| **O.A. Intersection**   | None                |
## 2026-April-20 - Inequalities with Functions - Graphically (Precalculus - College Algebra 45) :
https://www.youtube.com/watch?v=bngBtS7RBZ4&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=47
### Inequalities with Functions: Graphical Analysis

The core objective of this lesson is to move away from purely algebraic solutions and learn how to "read" the relationship between two functions on a coordinate plane. This provides a visual confirmation of where one function is "greater" or "less" than another. [00:01:45]

---
#### 1. Defining the Relationship
When we look at an inequality such as $f(x) > g(x)$, we are asking a specific question about the **y-values (outputs)** for a given **x-value (input)**: [00:03:20]

* **$f(x) > g(x)$:** On which intervals is the graph of $f(x)$ **above** the graph of $g(x)$?
* **$f(x) < g(x)$:** On which intervals is the graph of $f(x)$ **below** the graph of $g(x)$?
* **$f(x) = g(x)$:** Where do the two graphs **intersect**?

---
#### 2. The Critical Point Strategy
To solve these graphically, you must follow a structured process to identify the boundaries where the relationship changes: [00:08:15]

1.  **Find the Intersection Points:** Solve $f(x) = g(x)$. These $x$-values are the "fences" or boundaries of your intervals.
2.  **Mark the Boundaries:** Drop vertical lines (mentally or physically) from the intersection points to the x-axis. [00:10:40]
3.  **Analyze the Regions:** Between each set of boundaries, look at which curve is higher.
4.  **Write the Solution:** Express the $x$-values as an interval.
    * Use **parentheses** $( \dots )$ for strict inequalities ($>$ or $<$).
    * Use **brackets** $[ \dots ]$ for non-strict inequalities ($\geq$ or $\leq$), *unless* a point is undefined (like at a vertical asymptote). [00:15:30]

---
#### 3. Working with Zero: $f(x) \geq 0$
A common version of this problem is comparing a function to the x-axis ($g(x) = 0$): [00:22:10]

* **$f(x) \geq 0$:** Look for where the graph is on or above the x-axis.
* **$f(x) < 0$:** Look for where the graph is strictly below the x-axis.
* **Critical Points:** The x-intercepts (zeros) of the function are your boundaries.

---
#### 4. Handling Rational Inequalities Graphically
Rational functions add a layer of complexity because the relationship can change at **Vertical Asymptotes** even if the functions don't intersect there. [00:35:45]

* **Rule:** Your "boundaries" must include both the **Intersection Points** AND the **Vertical Asymptotes**. [00:37:20]
* **Asymptote Caution:** You can **never** use a bracket $[ \dots ]$ on an $x$-value that represents a vertical asymptote, because the function does not exist there. [00:40:15]

---
#### 5. Common Pitfalls
* **Confusing X and Y:** Always remember that the *inequality* refers to the height (y), but the *solution* is written in terms of the horizontal interval (x). [00:48:50]
* **Holes and Discontinuities:** If there is a hole in the graph at a boundary point, you must use a parenthesis, even for $\geq$ or $\leq$. [00:52:10]

> [!abstract] Algebra Takeaway
> Solving inequalities graphically is often faster and less prone to sign errors than the algebraic "test point" method. If you can identify the intersection points and the vertical asymptotes, you simply have to look at which "wire" is on top to find your interval.

## 2026-April-21 - Inequalities with Polynomial Functions (Precalculus - College Algebra 46) :
https://www.youtube.com/watch?v=qFJ-Mq0XcTI&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=47
### Inequalities with Polynomial Functions

This lesson transitions from graphical observation to the algebraic mechanics of solving polynomial inequalities. The goal is to determine the intervals of $x$ for which a polynomial expression is positive ($>0$) or negative ($<0$). [00:01:10]

---
#### 1. The Core Concept: The Sign Chart
A polynomial can only change its sign (from positive to negative or vice versa) at its **zeros** (x-intercepts). Between any two consecutive zeros, the polynomial must remain entirely above or entirely below the x-axis. [00:03:45]

---
#### 2. Step-by-Step Algebraic Strategy
To solve an inequality like $P(x) > 0$ or $P(x) \leq 0$: [00:08:20]

1.  **Move everything to one side:** Ensure the inequality is compared to zero (e.g., $P(x) \geq 0$).
2.  **Find the Zeros:** Factor the polynomial completely and set it equal to zero. These are your **Critical Values**. [00:12:15]
3.  **Create a Number Line (Sign Chart):** Mark your critical values on a number line. This divides the x-axis into several test intervals. [00:15:50]
4.  **Select Test Points:** Pick a number within each interval and plug it back into the *factored* form of the polynomial.
    * You only care if the result is **positive (+)** or **negative (-)**. [00:18:30]
5.  **Identify the Solution:** * If the problem asks for $> 0$, choose the $(+)$ intervals.
    * If the problem asks for $< 0$, choose the $(-)$ intervals.
6.  **Write in Interval Notation:** Use brackets $[\dots]$ for $\leq$ or $\geq$, and parentheses $(\dots)$ for $<$ or $>$. [00:22:10]
---
#### 3. The Multiplicity Shortcut
Instead of testing a number in every single interval, you can use the **Multiplicity** of the zeros to determine sign changes: [00:30:45]

* **Odd Multiplicity (e.g., exponent 1, 3, 5):** The polynomial **changes sign** at that zero. The graph crosses the x-axis.
* **Even Multiplicity (e.g., exponent 2, 4):** The polynomial **retains its sign** on both sides of that zero. The graph touches the x-axis and bounces. [00:33:15]

**The Workflow:** Test a single point in the far-right interval (using the Leading Coefficient) and then "work backward" through the zeros, switching the sign only at odd multiplicities. [00:36:50]

---
#### 4. Handling Irreducible Quadratics
Sometimes factoring leads to a quadratic that cannot be factored further (e.g., $x^2 + 1$). [00:42:10]
* **Rule:** An irreducible quadratic with a positive leading coefficient is **always positive** for all real numbers.
* **Impact:** It does not contribute any zeros (boundaries) to your sign chart, but it must be considered when calculating the final sign of a test point. [00:44:30]

---
#### 5. Common Errors
* **Dividing by Variables:** Never divide both sides of an inequality by an expression containing $x$ (like $x-2$). This can flip the inequality sign unpredictably or delete valid solutions. Always move terms to one side and factor. [00:50:15]
* **Strict vs. Non-Strict:** Forgetting to check if the endpoints (the zeros) should be included. If the problem is strictly $>$ or $<$, the zeros are **never** included. [00:55:00]

> [!abstract] Algebra Takeaway
> Polynomial inequalities are all about "The Boundary." Once you find the zeros, the polynomial is trapped in a specific sign within each interval. The factored form is your best friend—it makes testing points as simple as counting negative signs.

### Analysis of $f(x) = (x - 5)^2 (x + 2)$

Following the step-by-step algebraic strategy for polynomial inequalities, we determine the intervals where the function is positive, negative, or zero.

---
#### 1. Move everything to one side
The expression is already compared to zero implicitly by the prompt's request for $f(x) < 0$ and $f(x) \geq 0$.
#### 2. Find the Zeros (Critical Values)
Set each factor to zero:
* $(x - 5)^2 = 0 \implies \mathbf{x = 5}$
* $(x + 2) = 0 \implies \mathbf{x = -2}$
#### 3. Create a Number Line (Sign Chart)
We mark $-2$ and $5$ on the number line, creating three test intervals:
1.  $(-\infty, -2)$
2.  $(-2, 5)$
3.  $(5, \infty)$
#### 4. Select Test Points / Multiplicity Shortcut
Using the **Multiplicity Shortcut** and the **Leading Coefficient**:
* **Leading Coefficient:** Positive ($+1 \cdot +1$). For very large $x$, the graph goes to $+\infty$.
* **Interval $(5, \infty)$:** The sign is **(+)**.
* **At $x = 5$ (Multiplicity 2/Even):** The graph **bounces**. The sign stays **(+)**.
* **Interval $(-2, 5)$:** The sign is **(+)**.
* **At $x = -2$ (Multiplicity 1/Odd):** The graph **crosses**. The sign changes to **(-)**.
* **Interval $(-\infty, -2)$:** The sign is **(-)**.

---
#### 5. Identify the Solutions

**For f(x) < 0 (Strictly Negative):**
We look for the $(-)$ intervals. We do not include the zeros because the inequality is strict.
* **Solution:** $(-\infty, -2)$
**For f(x) >= 0 (Positive or Zero):**
We look for the $(+)$ intervals and **include** the zeros. 
* *Note:* Since the graph stays positive on both sides of $x = 5$, the two intervals $(-2, 5]$ and $[5, \infty)$ merge into one continuous set.
* **Solution:** $[-2, \infty)$

---
#### Summary Table
| Interval | Test Point ($x$) | Calculation | Sign |
| :--- | :--- | :--- | :--- |
| $(-\infty, -2)$ | $-3$ | $(-8)^2(-1) = 64(-1)$ | **(-)** |
| $(-2, 5)$ | $0$ | $(-5)^2(2) = 25(2)$ | **(+)** |
| $(5, \infty)$ | $6$ | $(1)^2(8) = 1(8)$ | **(+)** |


> [!abstract] Algebra Takeaway
> Because of the even multiplicity at $x = 5$, the function "kisses" the x-axis and goes back up. This is why the solution for $f(x) \geq 0$ is a single joined interval $[-2, \infty)$, while $f(x) > 0$ would have required a break at 5, like $(-2, 5) \cup (5, \infty)$.

### Analysis of $f(x) = x^3 - 4x^2$

Following the algebraic strategy for polynomial inequalities:

---
#### 1. Move everything to one side
The expression is already compared to zero:
$$x^3 - 4x^2 \geq 0$$

#### 2. Factor First (Find Critical Values)
Factor out the Greatest Common Factor (GCF):
$$x^2(x - 4) \geq 0$$
Set each factor to zero to find the **Critical Values**:
* $x^2 = 0 \implies \mathbf{x = 0}$
* $x - 4 = 0 \implies \mathbf{x = 4}$
#### 3. Create a Number Line (Sign Chart)
The critical values $0$ and $4$ divide the x-axis into three test intervals:
1.  $(-\infty, 0)$
2.  $(0, 4)$
3.  $(4, \infty)$
#### 4. Select Test Points / Multiplicity Shortcut
Using the **Multiplicity Shortcut** and the **Leading Coefficient**:
* **Leading Coefficient:** Positive ($+1$). For very large $x$, the graph goes to $+\infty$.
* **Interval $(4, \infty)$:** The sign is **(+)**.
* **At $x = 4$ (Multiplicity 1/Odd):** The exponent on $(x-4)$ is 1. The graph **crosses** the x-axis. The sign changes.
* **Interval $(0, 4)$:** The sign is **(-)**.
* **At $x = 0$ (Multiplicity 2/Even):** The exponent on $x^2$ is 2. The graph **bounces** off the x-axis. The sign stays the same.
* **Interval $(-\infty, 0)$:** The sign stays **(-)**.
#### 5. Identify the Solutions

**For f(x) < 0 (Strictly Negative):**
We look for the $(-)$ intervals. We do not include the zeros. Because the graph hits zero at $x=0$, we must break the interval.
* **Solution:** $(-\infty, 0) \cup (0, 4)$

**For f(x) >= 0 (Positive or Zero):**
We look for the $(+)$ intervals and include the zeros. 
* *Crucial Detail:* Even though the graph is negative on both sides of $x=0$, the value **at** $x=0$ is exactly zero, which satisfies the "$\geq 0$" condition.
* **Solution:** $\{0\} \cup [4, \infty)$
---
#### Summary Table
| Interval | Test Point ($x$) | Calculation | Sign |
| :--- | :--- | :--- | :--- |
| $(-\infty, 0)$ | $-1$ | $(-1)^2(-1-4) = 1(-5)$ | **(-)** |
| $(0, 4)$ | $1$ | $(1)^2(1-4) = 1(-3)$ | **(-)** |
| $(4, \infty)$ | $5$ | $(5)^2(5-4) = 25(1)$ | **(+)** |


> [!abstract] Algebra Takeaway
> Always check your "isolated" zeros. Because $x=0$ makes the function exactly zero, it must be included in the $\geq 0$ solution as a single point, even if the intervals immediately surrounding it are negative.

### Analysis of $f(x) = x^3 + 2x^2 \geq 3$

To solve this polynomial inequality, we must first set the expression to zero so we can analyze the signs of the intervals.

---
#### 1. Move everything to one side
Subtract 3 from both sides to compare the function to zero:
$$x^3 + 2x^2 - 3 \geq 0$$

#### 2. Factor First (Find Critical Values)
Since this is a cubic polynomial without a common factor, we use the **Rational Root Theorem** and **Synthetic Division**.
* Potential roots: $\pm 1, \pm 3$.
* Testing $x = 1$: $1^3 + 2(1)^2 - 3 = 0$. So, $(x - 1)$ is a factor.

**Synthetic Division:**
Divide $(x^3 + 2x^2 + 0x - 3)$ by $(x - 1)$:
1 | 1  2  0 -3
  |    1  3  3
  ------------
    1  3  3  0

The remaining quadratic is $x^2 + 3x + 3$.
* **Check the Discriminant ($D$) for $x^2 + 3x + 3$:**
  $$D = b^2 - 4ac = 3^2 - 4(1)(3) = 9 - 12 = -3$$
* Since the discriminant is negative, the quadratic has no real zeros and is **always positive**.

**Full Factored Form:**
$$(x - 1)(x^2 + 3x + 3) \geq 0$$
**Critical Value:** $\mathbf{x = 1}$

---
#### 3. Create a Number Line (Sign Chart)
With only one real critical value at $1$, the x-axis is divided into two test intervals:
1.  $(-\infty, 1)$
2.  $(1, \infty)$
#### 4. Select Test Points / Multiplicity Shortcut
* **Leading Coefficient:** Positive ($+1$). For large $x$, the graph heads toward $+\infty$.
* **Interval $(1, \infty)$:** The sign is **(+)**.
* **At $x = 1$ (Multiplicity 1/Odd):** The exponent on $(x-1)$ is 1. The graph **crosses** the x-axis.
* **Interval $(-\infty, 1)$:** The sign changes to **(-)**.

*Note: The irreducible quadratic $(x^2 + 3x + 3)$ is always positive, so it never changes the sign of the overall function.*
#### 5. Identify the Solution
The problem asks for where the expression is **greater than or equal to zero** ($\geq 0$).
* We look for the $(+)$ interval and **include** the zero.
* **Solution:** $[1, \infty)$

---
#### Summary Table
| Interval | Test Point ($x$) | Calculation | Sign |
| :--- | :--- | :--- | :--- |
| $(-\infty, 1)$ | $0$ | $(0-1)(0+0+3) = (-1)(3)$ | **(-)** |
| $(1, \infty)$ | $2$ | $(2-1)(4+6+3) = (1)(13)$ | **(+)** |

> [!abstract] Algebra Takeaway
> When you encounter an irreducible quadratic with no real zeros, it acts as a "constant" positive multiplier. It won't create boundaries on your sign chart, but it’s the reason the graph doesn't come back down to cross the x-axis again.

### Analysis of $f(x) = x^4 > 1$

Following the specific step-by-step algebraic strategy for polynomial inequalities:

---
#### 1. Move everything to one side
Subtract 1 from both sides to compare the function to zero:
$$x^4 - 1 > 0$$

#### 2. Factor First (Find Critical Values)
Use the **Difference of Squares** pattern twice:
1.  $(x^2 - 1)(x^2 + 1) > 0$
2.  $(x - 1)(x + 1)(x^2 + 1) > 0$

**Identify Critical Values:**
* $x - 1 = 0 \implies \mathbf{x = 1}$
* $x + 1 = 0 \implies \mathbf{x = -1}$
* $x^2 + 1 = 0 \implies$ No real solutions (irreducible quadratic, always positive).

**Critical Values:** $-1$ and $1$.

---
#### 3. Create a Number Line (Sign Chart)
The values $-1$ and $1$ divide the x-axis into three test intervals:
1.  $(-\infty, -1)$
2.  $(-1, 1)$
3.  $(1, \infty)$
#### 4. Select Test Points / Multiplicity Shortcut
Using the **Multiplicity Shortcut** and the **Leading Coefficient**:
* **Leading Coefficient:** Positive ($+1$). For very large $x$, the graph heads toward $+\infty$.
* **Interval $(1, \infty)$:** The sign is **(+)**.
* **At $x = 1$ (Multiplicity 1/Odd):** The graph **crosses** the x-axis.
* **Interval $(-1, 1)$:** The sign changes to **(-)**.
* **At $x = -1$ (Multiplicity 1/Odd):** The graph **crosses** the x-axis.
* **Interval $(-\infty, -1)$:** The sign changes back to **(+)**.
#### 5. Identify the Solution
The problem asks for where $x^4 - 1$ is **strictly greater than zero** ($> 0$).
* We look for the $(+)$ intervals. Since it is a strict inequality, we use **parentheses** and do not include the zeros.
* **Solution:** $(-\infty, -1) \cup (1, \infty)$

---
#### Summary Table
| Interval | Test Point ($x$) | Calculation | Sign |
| :--- | :--- | :--- | :--- |
| $(-\infty, -1)$ | $-2$ | $(-2)^4 - 1 = 16 - 1 = 15$ | **(+)** |
| $(-1, 1)$ | $0$ | $(0)^4 - 1 = -1$ | **(-)** |
| $(1, \infty)$ | $2$ | $(2)^4 - 1 = 16 - 1 = 15$ | **(+)** |

> [!abstract] Algebra Takeaway
> The irreducible quadratic factor $(x^2 + 1)$ acts as a positive constant. It never changes the sign of the expression, so the "switching" of signs only happens at the real roots $x=1$ and $x=-1$.

## 2026-May-04 - Inequalities with Rational Functions (Precalculus - College Algebra 47) :
https://www.youtube.com/watch?v=QSh1xcbYKZk&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=66
### Analysis of Inequalities with Rational Functions

This lesson covers the algebraic process for solving inequalities involving rational expressions. Unlike polynomials, rational functions have "fences" created by both zeros and vertical asymptotes.

---
#### 1. The Golden Rule: Never Multiply by a Variable
The most critical error to avoid is multiplying both sides of an inequality by an expression containing $x$ (e.g., $x-2$). Because you do not know if that expression is positive or negative, you cannot determine whether to flip the inequality sign. Instead, you must move all terms to one side and set the inequality to zero.

---
#### 2. Step-by-Step Algebraic Strategy
To solve a rational inequality such as $\frac{P(x)}{Q(x)} \geq 0$:

1.  **Set to Zero:** Move all terms to the left side so the right side is zero.
2.  **Find a Common Denominator:** Combine the terms into a single rational expression.
3.  **Identify Critical Values:** Find the "fences" where the function can change signs:
    *   **Zeros:** Set the numerator to zero.
    *   **Vertical Asymptotes:** Set the denominator to zero.
4.  **Create a Sign Chart:** Mark all critical values on a number line.
5.  **Test Intervals:** Pick a test point in each region to determine if the function is positive (+) or negative (-).
6.  **Write the Solution:** Express the correct regions in interval notation.

---
#### 3. Handling Boundaries (Parentheses vs. Brackets)
When writing your final answer, the choice between $( \dots )$ and $[ \dots ]$ depends on two factors:

*   **The Inequality Sign:** If the problem uses $>$ or $<$, all boundaries use parentheses.
*   **The "Undefined" Rule:** You **must always** use parentheses for critical values that come from the **denominator** (Vertical Asymptotes), even if the problem is $\geq$ or $\leq$. A function is never "equal to zero" where it is undefined.

---
#### 4. The Multiplicity Shortcut for Rational Functions
Just like polynomials, you can use multiplicity to speed up the sign chart:
*   **Numerator Factor Multiplicity:** Determines if the graph crosses or bounces at an x-intercept.
*   **Denominator Factor Multiplicity:** Determines if the graph goes in opposite directions (odd multiplicity) or the same direction (even multiplicity) at a vertical asymptote.

**Workflow:** Find the sign of the far-right interval using the leading coefficients of the top and bottom, then flip the sign as you pass through each critical value with an odd multiplicity.

---
#### 5. Common Pitfalls
*   **Missing Asymptotes:** Forgetting that the denominator's zeros are critical values. The sign of the function can change across a vertical asymptote just as easily as it can across an x-intercept.
*   **Incorrect Interval Merging:** Be careful when a function "bounces" or stays on the same side of an asymptote. Always double-check if the critical value itself is included in the solution.

> [!abstract] Algebra Takeaway
> Rational inequalities are solved exactly like polynomial inequalities, with one extra restriction: the denominator's zeros are "fences" that can never be included in the final solution set.


### Determining Multiplicity of Vertical Asymptotes

In a rational expression, the "behavior" at a vertical asymptote (V.A.) is determined by the **multiplicity** of the factor in the denominator that creates that asymptote. This multiplicity tells you whether the graph shoots off in the same direction or opposite directions as it approaches the asymptote.

---
#### 1. Identify the Multiplicity (The Exponent)
To find the multiplicity, you must first factor the denominator completely. Look at the exponent attached to the specific factor that equals zero at the asymptote location:

*   **Odd Multiplicity:** The factor is raised to an odd power (e.g., $(x - c)^1$, $(x - c)^3$).
*   **Even Multiplicity:** The factor is raised to an even power (e.g., $(x - c)^2$, $(x - c)^4$).

---
#### 2. Graphical Behavior
The exponent dictates how the $y$-values behave on either side of the V.A.:

| Multiplicity | Behavior Description | Visual Result |
| :--- | :--- | :--- |
| **Odd** | The $y$-values go to **opposite infinities**. | One side goes to $+\infty$, the other to $-\infty$. |
| **Even** | The $y$-values go to the **same infinity**. | Both sides shoot up to $+\infty$ or both down to $-\infty$. |

---
#### 3. Examples
*   **Example 1 (Odd):** $f(x) = \frac{1}{x-1}$
    *   The factor $(x-1)$ has an implied exponent of **1**.
    *   This is **odd multiplicity**, so the graph will head to $+\infty$ on one side of $x=1$ and $-\infty$ on the other.

*   **Example 2 (Even):** $f(x) = \frac{1}{(x+3)^2}$
    *   The factor $(x+3)$ has an exponent of **2**.
    *   This is **even multiplicity**, so the graph will head toward $+\infty$ on both sides of $x=-3$.

---

> [!tip] Note-Taking Tip
> When solving rational inequalities, knowing if a V.A. is odd or even allows you to use the **Multiplicity Shortcut** on your sign chart. If the V.A. is odd, the sign of the function **switches** as you pass over it; if it is even, the sign **stays the same**.
### Analysis of $\frac{(x-3)(x+2)}{x-1} \leq 0$

Following the algebraic strategy for rational inequalities, we identify the critical "fences" where the function can change signs.

---
#### 1. Identify Critical Values
To build our sign chart, we must find the values from both the numerator and the denominator.

*   **Zeros (Numerator):** Set the numerator factors to zero.
    *   $x - 3 = 0 \implies \mathbf{x = 3}$
    *   $x + 2 = 0 \implies \mathbf{x = -2}$
*   **Vertical Asymptotes (Denominator):** Set the denominator factor to zero.
    *   $x - 1 = 0 \implies \mathbf{x = 1}$

**Critical Values:** $-2, 1, 3$.

---
#### 2. Create a Sign Chart
These three values divide the x-axis into four test intervals:
1.  $(-\infty, -2)$
2.  $(-2, 1)$
3.  $(1, 3)$
4.  $(3, \infty)$
#### 3. Select Test Points / Multiplicity Shortcut
Using the **Multiplicity Shortcut**:
*   **Leading Coefficient:** All $x$ terms are positive, so the far-right interval is **(+)**.
*   **At $x = 3$ (Multiplicity 1):** Odd multiplicity; the sign **changes** to **(-)**.
*   **At $x = 1$ (Multiplicity 1):** Odd multiplicity; the sign **changes** to **(+)**.
*   **At $x = -2$ (Multiplicity 1):** Odd multiplicity; the sign **changes** to **(-)**.

| Interval | Test Point ($x$) | Sign |
| :--- | :--- | :--- |
| $(-\infty, -2)$ | $-3$ | **(-)** |
| $(-2, 1)$ | $0$ | **(+)** |
| $(1, 3)$ | $2$ | **(-)** |
| $(3, \infty)$ | $4$ | **(+)** |

---
#### 4. Identify the Solution
The problem asks for where the expression is **less than or equal to zero** ($\leq 0$).

*   **Select Negative Intervals:** $(-\infty, -2)$ and $(1, 3)$.
*   **Handling Boundaries:**
    *   The Zeros ($-2$ and $3$) get **brackets** because of the $\leq$ sign.
    *   The Vertical Asymptote ($1$) **must** have a **parenthesis** because the function is undefined there.

**Solution:** $(-\infty, -2] \cup (1, 3]$
#### 5. Graphical Appearance
The graph of $f(x) = \frac{(x-3)(x+2)}{x-1}$ is split into distinct sections by the vertical asymptote at $x=1$ and the behavior at the x-intercepts:

*   **Left Section ($x < 1$):**
    *   The graph comes up from $-\infty$ at the far left and crosses the x-axis at **$(-2, 0)$** (multiplicity 1).
    *   It reaches a local maximum in the interval $(-2, 1)$, passing through the y-intercept at **$(0, 6)$**.
    *   As it approaches the "wall" at $x=1$ from the left, it shoots toward **$+\infty$**.
*   **Right Section ($x > 1$):**
    *   Due to the **odd multiplicity** of the vertical asymptote, the graph enters from **$-\infty$** on the right side of $x=1$.
    *   It climbs and crosses the x-axis at **$(3, 0)$** (multiplicity 1).
    *   As $x$ increases, the graph follows its **Oblique Asymptote ($y = x - 2$)** toward $+\infty$.

**Visual Summary of Solutions:**
*   The solution for $f(x) \leq 0$ represents the parts of the graph **on or below** the x-axis.
*   This occurs during the "dive" on the far left before reaching $-2$, and the "climb" from the asymptote up to the intercept at $3$.
---

> [!abstract] Algebra Takeaway
> Even though the inequality includes "or equal to," the value $x=1$ is a "hard wall" that can never be included in your solution because it makes the denominator zero.

### Analysis of $f(x) = \frac{(x+5)^2}{x^2 - 4} \geq 0$

Following the algebraic strategy for rational inequalities, we identify the critical "fences" created by the zeros and vertical asymptotes.

---
#### 1. Identify Critical Values
To build our sign chart, we find the values where the function can change signs.

*   **Zeros (Numerator):** Set the numerator factors to zero.
    *   $(x + 5)^2 = 0 \implies \mathbf{x = -5}$ (Multiplicity 2).
*   **Vertical Asymptotes (Denominator):** Factor the denominator and set to zero.
    *   $x^2 - 4 = (x - 2)(x + 2) = 0$.
    *   **V.A. 1:** $\mathbf{x = 2}$ (Multiplicity 1).
    *   **V.A. 2:** $\mathbf{x = -2}$ (Multiplicity 1).

**Critical Values:** $-5, -2, 2$.

---
#### 2. Create a Sign Chart
These values divide the x-axis into four test intervals:
1.  $(-\infty, -5)$
2.  $(-5, -2)$
3.  $(-2, 2)$
4.  $(2, \infty)$
#### 3. Select Test Points / Multiplicity Shortcut
Using the **Multiplicity Shortcut**:
*   **Leading Coefficient:** The ratio of leading terms ($x^2/x^2$) is positive, so the far-right interval is **(+)**.
*   **At $x = 2$ (Multiplicity 1):** Odd multiplicity; the sign **changes** to **(-)**.
*   **At $x = -2$ (Multiplicity 1):** Odd multiplicity; the sign **changes** to **(+)**.
*   **At $x = -5$ (Multiplicity 2):** Even multiplicity; the sign **stays the same** **(+)**.

| Interval | Test Point ($x$) | Sign |
| :--- | :--- | :--- |
| $(-\infty, -5)$ | $-6$ | **(+)** |
| $(-5, -2)$ | $-3$ | **(+)** |
| $(-2, 2)$ | $0$ | **(-)** |
| $(2, \infty)$ | $3$ | **(+)** |

---
#### 4. Identify the Solution
The problem asks for where the expression is **greater than or equal to zero** ($\geq 0$).

*   **Select Positive Intervals:** $(-\infty, -5)$, $(-5, -2)$, and $(2, \infty)$.
*   **Handling Boundaries:**
    *   The Zero at $-5$ is included because it makes the function exactly zero. Since the intervals on both sides are positive, these merge into one interval.
    *   The Vertical Asymptotes at $-2$ and $2$ **must** use **parentheses** because the function is undefined there.

**Solution:** $(-\infty, -2) \cup (2, \infty)$

---
#### 5. Graphical Appearance
The graph is shaped by its even-multiplicity intercept and odd-multiplicity asymptotes:

*   **Left Section ($x < -2$):**
    *   The graph stays above the x-axis ($y=1$ is the Horizontal Asymptote).
    *   It comes down from the H.A., **touches and bounces** at **$(-5, 0)$** (even multiplicity), then climbs toward **$+\infty$** as it approaches $x = -2$.
*   **Middle Section ($-2 < x < 2$):**
    *   Due to the **odd multiplicity** at $x = -2$, the graph enters from **$-\infty$**.
    *   It reaches a local maximum at the y-intercept **$(0, -6.25)$** and then dives back to **$-\infty$** at $x = 2$.
*   **Right Section ($x > 2$):**
    *   The graph enters from **$+\infty$** on the right of $x = 2$.
    *   It curves down and levels off, approaching the Horizontal Asymptote **$y = 1$** from above.

> [!abstract] Algebra Takeaway
> The "bounce" at $x = -5$ is critical. Even though the function hits zero there, it never crosses into negative territory in that section, allowing the two left-hand intervals to merge in your solution.

### Analysis of $f(x) = \frac{x(x^2+1)(x-2)}{(x-1)(x+1)} \geq 0$

Following the algebraic strategy for rational inequalities, we identify the critical "fences" where the function can change signs.

---
#### 1. Identify Critical Values
To build our sign chart, we must find the values from both the numerator and the denominator.

*   **Zeros (Numerator):** Set the numerator factors to zero.
    *   $x = \mathbf{0}$ (Multiplicity 1).
    *   $x^2 + 1 = 0 \implies$ No real solutions (Irreducible quadratic; always positive).
    *   $x - 2 = 0 \implies \mathbf{x = 2}$ (Multiplicity 1).
*   **Vertical Asymptotes (Denominator):** Set the denominator factors to zero.
    *   $x - 1 = 0 \implies \mathbf{x = 1}$ (Multiplicity 1).
    *   $x + 1 = 0 \implies \mathbf{x = -1}$ (Multiplicity 1).

**Critical Values:** $-1, 0, 1, 2$.

---
#### 2. Create a Sign Chart
These four values divide the x-axis into five test intervals:
1.  $(-\infty, -1)$
2.  $(-1, 0)$
3.  $(0, 1)$
4.  $(1, 2)$
5.  $(2, \infty)$
#### 3. Select Test Points / Multiplicity Shortcut
Using the **Multiplicity Shortcut**:
*   **Leading Coefficient:** The ratio of leading terms ($x^4/x^2$) is positive, so the far-right interval is **(+)**.
*   **At $x = 2$ (Multiplicity 1):** Odd; sign **changes** to **(-)**.
*   **At $x = 1$ (Multiplicity 1):** Odd; sign **changes** to **(+)**.
*   **At $x = 0$ (Multiplicity 1):** Odd; sign **changes** to **(-)**.
*   **At $x = -1$ (Multiplicity 1):** Odd; sign **changes** to **(+)**.

| Interval | Test Point ($x$) | Sign |
| :--- | :--- | :--- |
| $(-\infty, -1)$ | $-2$ | **(+)** |
| $(-1, 0)$ | $-0.5$ | **(-)** |
| $(0, 1)$ | $0.5$ | **(+)** |
| $(1, 2)$ | $1.5$ | **(-)** |
| $(2, \infty)$ | $3$ | **(+)** |

---
#### 4. Identify the Solution
The problem asks for where the expression is **greater than or equal to zero** ($\geq 0$).

*   **Select Positive Intervals:** $(-\infty, -1)$, $(0, 1)$, and $(2, \infty)$.
*   **Handling Boundaries:**
    *   The Zeros ($0$ and $2$) get **brackets** because of the $\geq$ sign.
    *   The Vertical Asymptotes ($-1$ and $1$) **must** use **parentheses** because the function is undefined there.

**Solution:** $(-\infty, -1) \cup [0, 1) \cup [2, \infty)$

---
#### 5. Graphical Appearance
The graph is shaped by its odd multiplicity at every critical point and its end behavior:

*   **End Behavior:** Since the numerator degree (4) is two higher than the denominator degree (2), the graph follows a **parabolic ($x^2$) end behavior**, shooting toward $+\infty$ on both the far left and far right.
*   **Left Section ($x < -1$):** The graph comes down from $+\infty$ and shoots toward $+\infty$ again as it approaches the V.A. at $x = -1$.
*   **Middle Section 1 ($-1 < x < 1$):**
    *   Due to the **odd multiplicity** at $x = -1$, the graph enters from **$-\infty$**.
    *   It crosses the x-axis at **$(0, 0)$** and continues upward toward **$+\infty$** as it approaches $x = 1$.
*   **Middle Section 2 ($1 < x < 2$):**
    *   Due to the **odd multiplicity** at $x = 1$, the graph enters from **$-\infty$**.
    *   It climbs to cross the x-axis at **$(2, 0)$**.
*   **Right Section ($x > 2$):**
    *   After crossing at $x = 2$, the graph continues to rise toward $+\infty$, following its parabolic end behavior.

> [!abstract] Algebra Takeaway
> Because every critical value (zeros and asymptotes) had an odd multiplicity, the sign of the function flipped at every single "fence". This created the alternating pattern of the solution set.

### Analysis of $f(x) = \frac{3x-5}{x+2} \leq 2$

To solve this rational inequality correctly, we must avoid the common mistake of multiplying by the variable expression and instead set the inequality to zero.

---
#### 1. Move everything to one side
Subtract 2 from both sides to compare the function to zero:
$$\frac{3x-5}{x+2} - 2 \leq 0$$

#### 2. Find a Common Denominator
Combine the terms into a single rational expression:
$$\frac{3x-5}{x+2} - \frac{2(x+2)}{x+2} \leq 0$$
$$\frac{3x - 5 - 2x - 4}{x+2} \leq 0$$
$$\frac{x - 9}{x + 2} \leq 0$$
#### 3. Identify Critical Values
Find the "fences" where the function can change signs:
*   **Zeros (Numerator):** $x - 9 = 0 \implies \mathbf{x = 9}$ (Multiplicity 1).
*   **Vertical Asymptotes (Denominator):** $x + 2 = 0 \implies \mathbf{x = -2}$ (Multiplicity 1).

**Critical Values:** $-2, 9$.

---
#### 4. Create a Sign Chart
These values divide the x-axis into three test intervals:
1.  $(-\infty, -2)$
2.  $(-2, 9)$
3.  $(9, \infty)$
#### 5. Select Test Points / Multiplicity Shortcut
Using the **Multiplicity Shortcut**:
*   **Leading Coefficient:** The ratio of leading terms ($x/x$) is positive, so the far-right interval is **(+)**.
*   **At $x = 9$ (Multiplicity 1):** Odd; the sign **changes** to **(-)**.
*   **At $x = -2$ (Multiplicity 1):** Odd; the sign **changes** to **(+)**.

| Interval | Test Point ($x$) | Calculation (Simplified Form) | Sign |
| :--- | :--- | :--- | :--- |
| $(-\infty, -2)$ | $-3$ | $(-3-9)/(-3+2) = -12/-1$ | **(+)** |
| $(-2, 9)$ | $0$ | $(0-9)/(0+2) = -9/2$ | **(-)** |
| $(9, \infty)$ | $10$ | $(10-9)/(10+2) = 1/12$ | **(+)** |

---
#### 6. Identify the Solution
The problem asks for where the expression is **less than or equal to zero** ($\leq 0$).

*   **Select Negative Intervals:** $(-2, 9)$.
*   **Handling Boundaries:**
    *   The Zero at $9$ gets a **bracket** because of the $\leq$ sign.
    *   The Vertical Asymptote at $-2$ **must** use a **parenthesis** because the function is undefined there.

**Solution:** $(-2, 9]$

---
#### 7. Graphical Appearance
The graph of the simplified comparison function $g(x) = \frac{x-9}{x+2}$ provides the visual solution:

*   **Vertical Asymptote ($x = -2$):** Because it has an **odd multiplicity**, the graph shoots to $+\infty$ on the left and enters from $-\infty$ on the right.
*   **X-Intercept ($9, 0$):** The graph crosses the x-axis at $x=9$.
*   **End Behavior:** The horizontal asymptote is $y = 1$.
*   **The Region:** The solution $(-2, 9]$ represents the part of the graph that is **below or on the x-axis**. This is the section where the graph climbs from $-\infty$ (on the right of the asymptote) up to the intercept at $9$.

> [!abstract] Algebra Takeaway
> Never multiply across an inequality by a variable. By moving the $2$ over and finding a common denominator, you transform the problem into a standard rational inequality that clearly shows the critical "fences" at $-2$ and $9$.

### Analysis of f(x) = \frac{5}{x-3} \geq \frac{3}{x+1}

Following the exact algebraic strategy for rational inequalities:

---
#### 1. Move everything to one side
Set the inequality to zero by subtracting the right-hand side. **Do not multiply by (x-3) or (x+1).**
$$\frac{5}{x-3} - \frac{3}{x+1} \geq 0$$

#### 2. Find a Common Denominator
The Least Common Denominator (LCD) is $(x-3)(x+1)$.
$$\frac{5(x+1)}{(x-3)(x+1)} - \frac{3(x-3)}{(x-3)(x+1)} \geq 0$$
Combine the numerators:
$$\frac{5x + 5 - 3x + 9}{(x-3)(x+1)} \geq 0$$
$$\frac{2x + 14}{(x-3)(x+1)} \geq 0$$
Factor the numerator:
$$\frac{2(x + 7)}{(x-3)(x+1)} \geq 0$$

#### 3. Identify Critical Values (The Fences)
*   **Zeros (Numerator):** $x + 7 = 0 \implies \mathbf{x = -7}$ (Multiplicity 1).
*   **Vertical Asymptotes (Denominator):**
    *   $x - 3 = 0 \implies \mathbf{x = 3}$ (Multiplicity 1).
    *   $x + 1 = 0 \implies \mathbf{x = -1}$ (Multiplicity 1).

**Critical Values:** $-7, -1, 3$.

---
#### 4. Create a Sign Chart
Divide the number line into four test intervals:
1.  $(-\infty, -7)$
2.  $(-7, -1)$
3.  $(-1, 3)$
4.  $(3, \infty)$
#### 5. Select Test Points / Multiplicity Shortcut
Using the **Multiplicity Shortcut**:
*   **Leading Coefficient:** All factors are positive ($2, 1, 1$), so the far-right interval is **(+)**.
*   **At x = 3 (Odd):** Sign **changes** to **(-)**.
*   **At x = -1 (Odd):** Sign **changes** to **(+)**.
*   **At x = -7 (Odd):** Sign **changes** to **(-)**.

| Interval | Test Point ($x$) | Calculation | Sign |
| :--- | :--- | :--- | :--- |
| $(-\infty, -7)$ | $-8$ | $2(-1) / (-11)(-7) = -2 / 77$ | **(-)** |
| $(-7, -1)$ | $-4$ | $2(3) / (-7)(-3) = 6 / 21$ | **(+)** |
| $(-1, 3)$ | $0$ | $2(7) / (-3)(1) = 14 / -3$ | **(-)** |
| $(3, \infty)$ | $4$ | $2(11) / (1)(5) = 22 / 5$ | **(+)** |

---
#### 6. Identify the Solution
The problem asks for where the expression is **greater than or equal to zero** ($\geq 0$).
*   **Select Positive Intervals:** $(-7, -1)$ and $(3, \infty)$.
*   **Handling Boundaries:**
    *   The zero at $-7$ is included (**bracket**) because of the $\geq$ sign.
    *   The Vertical Asymptotes at $-1$ and $3$ **must** use **parentheses** because the function is undefined there.

**Solution:** $[-7, -1) \cup (3, \infty)$

---
#### 7. Graphical Appearance
The graph of the comparison function $g(x) = \frac{2(x+7)}{(x-3)(x+1)}$ looks like:
*   **Vertical Asymptotes:** "Fences" at $x = -1$ and $x = 3$. Because they are odd multiplicity, the graph shoots to opposite infinities on either side.
*   **X-Intercept:** The graph crosses the x-axis at **$(-7, 0)$**.
*   **End Behavior:** The horizontal asymptote is $y = 0$ (the x-axis).
*   **The Region:** The solution represents where the graph is **above or on the x-axis**. This occurs in a "hill" between $-7$ and $-1$, and the entire curve to the right of the $x=3$ asymptote.

## 2026-May-05 - Composition of Functions (Precalculus - College Algebra 48) : 
https://www.youtube.com/watch?v=EsgHKmLSPVc&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=50
### Composition of Functions

**Core Concept**
Composition of functions occurs when one entire function is substituted into the variable of another function. Essentially, the output of the "inner" function becomes the input for the "outer" function.

**Notation and Meaning**
*   **Notation:** $(f \circ g)(x)$ or $f(g(x))$.
*   **Pronunciation:** "f of g of x".
*   **Mechanism:** In the expression $f(g(x))$, $g(x)$ is the inner function and $f(x)$ is the outer function. You "open up" the variable in $f$ and place the entire $g$ function inside that space.

**The "Blank Space" Technique**
1.  **Identify the Outer Function:** Look at the first function listed (e.g., $f$ in $f \circ g$).
2.  **Create Blank Spaces:** Rewrite the outer function, replacing every instance of the variable $x$ with a set of parentheses $()$.
3.  **Insert the Inner Function:** Place the entire expression for the second function (the inner function) into every set of parentheses.
4.  **Simplify:** Follow the order of operations (PEMDAS), specifically handling exponents and distribution, to reach standard form.

**Evaluation Methods**
There are two primary ways to evaluate a composite function at a specific value, such as $(f \circ g)(1)$:
*   **Method A (Algebraic First):** Find the composite expression $f(g(x))$ first, simplify it, and then plug in the value $1$.
*   **Method B (Step-by-Step):** 
    1. Evaluate the inner function first: find $g(1)$.
    2. Use the result (the output of $g$) as the new input for the outer function $f$.
    *This method is often easier if the simplified algebraic expression contains large exponents.*

**Domain of Composite Functions**
The domain of a composite function is not just the domain of the final resulting expression. It is a combination of two constraints:
1.  The domain of the **inner function** (the function being plugged in).
2.  The domain of the **resulting function** after simplification.
*If both the inner and outer functions are polynomials, the domain is typically all real numbers ($-\infty, \infty$).*

**Key Properties**
*   **Non-Commutative:** In general, $f(g(x)) \neq g(f(x))$. The order of composition matters significantly.
*   **Inverse Relationship:** If $(f \circ g)(x) = x$ and $(g \circ f)(x) = x$, then $f$ and $g$ are inverse functions. This is a primary test for mathematical inverses.
### $(f \circ g)(x)$

$f(x) = 2x^2 -5$ 
and
$g(x) = 1-3x^2$

To find the composition $(f \circ g)(x)$ using the "Blank Space" technique, we treat the outer function as a template and substitute the inner function into it.

---

#### Step 1: Identify and Open the Outer Function
The notation $(f \circ g)(x)$ means $f(g(x))$, which tells us that **$f(x)$ is the outer function**. 
Given $f(x) = 2x^2 - 5$, we create a "Blank Space" by replacing every instance of the variable $x$ with parentheses. This creates a landing spot for our input:
$$2(\quad)^2 - 5$$

#### Step 2: Insert the Inner Function
The notation $f(g(x))$ tells us that **$g(x)$ is the inner function** acting as the input. 
Given $g(x) = 1 - 3x^2$, we take this entire expression and "shove" it into the blank space we created in $f(x)$:
$$2(1 - 3x^2)^2 - 5$$

#### Step 3: Expand the Squared Term
According to the order of operations (PEMDAS), we must handle the exponent before distributing. We expand $(1 - 3x^2)^2$ by multiplying the binomial by itself:
$$(1 - 3x^2)(1 - 3x^2) = 1 - 3x^2 - 3x^2 + 9x^4$$
$$= 1 - 6x^2 + 9x^4$$

#### Step 4: Distribute and Combine Like Terms
Now, substitute the expanded expression back into the structure of $f(x)$ and distribute the coefficient $2$:
$$2(1 - 6x^2 + 9x^4) - 5$$
$$= 2 - 12x^2 + 18x^4 - 5$$

Finally, combine the constant terms ($2 - 5 = -3$) and arrange the polynomial in standard form (highest degree to lowest):
$$18x^4 - 12x^2 - 3$$

---

**Final Result:**
$$(f \circ g)(x) = 18x^4 - 12x^2 - 3$$
### $(g \circ f)(x)$

$f(x) = 2x^2 -5$ 
and
$g(x) = 1-3x^2$

To find the composition $(g \circ f)(x)$ using the "Blank Space" technique, we treat the outer function as a template and substitute the inner function into it.

---

#### Step 1: Identify and Open the Outer Function
The notation $(g \circ f)(x)$ means $g(f(x))$, which tells us that **$g(x)$ is the outer function**. 
Given $g(x) = 1 - 3x^2$, we create a "Blank Space" by replacing every instance of the variable $x$ with parentheses. This allows us to see exactly where the new input will go:
$$1 - 3(\quad)^2$$

#### Step 2: Insert the Inner Function
The notation $g(f(x))$ tells us that **$f(x)$ is the inner function** acting as the input. 
Given $f(x) = 2x^2 - 5$, we take this entire expression and "shove" it into the blank space we created in $g(x)$:
$$1 - 3(2x^2 - 5)^2$$

#### Step 3: Expand the Squared Term
Following the order of operations (PEMDAS), we must handle the exponent on the parentheses before multiplying by $-3$. We expand $(2x^2 - 5)^2$ by multiplying the binomial by itself:
$$(2x^2 - 5)(2x^2 - 5) = 4x^4 - 10x^2 - 10x^2 + 25$$
$$= 4x^4 - 20x^2 + 25$$

#### Step 4: Distribute and Combine Like Terms
Now, substitute that expanded result back into the expression for $g$ and distribute the $-3$. Be careful to apply the negative sign to every term:
$$1 - 3(4x^4 - 20x^2 + 25)$$
$$= 1 - 12x^4 + 60x^2 - 75$$

Finally, combine the constant terms ($1 - 75 = -74$) and arrange the polynomial in standard form:
$$-12x^4 + 60x^2 - 74$$

---

**Final Result:**
$$(g \circ f)(x) = -12x^4 + 60x^2 - 74$$

### $(f \circ f)(x)$

$f(x) = 2x^2 -5$ 
and
$g(x) = 1-3x^2$

To find the composition $(f \circ f)(x)$ using the "Blank Space" technique, we treat the function as both the template and the input, substituting the function into itself.

---
#### Step 1: Identify and Open the Outer Function
The notation $(f \circ f)(x)$ means $f(f(x))$, which tells us that **$f(x)$ is the outer function**. 
Given $f(x) = 2x^2 - 5$, we create a "Blank Space" by replacing the variable $x$ with parentheses:
$$2(\quad)^2 - 5$$

#### Step 2: Insert the Inner Function
The notation $f(f(x))$ tells us that **$f(x)$ is also the inner function** acting as the input. 
Given $f(x) = 2x^2 - 5$, we take this entire expression and "shove" it into the blank space we created in the outer version of $f(x)$:
$$2(2x^2 - 5)^2 - 5$$

#### Step 3: Expand the Squared Term
Following the order of operations (PEMDAS), we must evaluate the exponent before distributing the $2$. We expand $(2x^2 - 5)^2$ by multiplying the binomial by itself:
$$(2x^2 - 5)(2x^2 - 5) = 4x^4 - 10x^2 - 10x^2 + 25$$
$$= 4x^4 - 20x^2 + 25$$

#### Step 4: Distribute and Combine Like Terms
Now, substitute the expanded expression back into the outer structure and distribute the coefficient $2$:
$$2(4x^4 - 20x^2 + 25) - 5$$
$$= 8x^4 - 40x^2 + 50 - 5$$

Finally, combine the constant terms ($50 - 5 = 45$) and arrange the polynomial in standard form:
$$8x^4 - 40x^2 + 45$$

---

**Final Result:**
$$(f \circ f)(x) = 8x^4 - 40x^2 + 45$$

### $(g \circ g)(x)$

$f(x) = 2x^2 -5$ 
and
$g(x) = 1-3x^2$

To find the composition $(g \circ g)(x)$ using the "Blank Space" technique, we treat the function as both the template and the input, substituting the function into its own variable.

---
#### Step 1: Identify and Open the Outer Function
The notation $(g \circ g)(x)$ means $g(g(x))$, which tells us that **$g(x)$ is the outer function**. 
Given $g(x) = 1 - 3x^2$, we create a "Blank Space" by replacing the variable $x$ with parentheses. This creates the landing spot for our input:
$$1 - 3(\quad)^2$$

#### Step 2: Insert the Inner Function
The notation $g(g(x))$ tells us that **$g(x)$ is also the inner function** acting as the input. 
Given $g(x) = 1 - 3x^2$, we take this entire expression and "shove" it into the blank space we created in Step 1:
$$1 - 3(1 - 3x^2)^2$$

#### Step 3: Expand the Squared Term
Following the order of operations (PEMDAS), we must handle the exponent before multiplying by $-3$. We expand $(1 - 3x^2)^2$ by multiplying the binomial by itself:
$$(1 - 3x^2)(1 - 3x^2) = 1 - 3x^2 - 3x^2 + 9x^4$$
$$= 1 - 6x^2 + 9x^4$$

#### Step 4: Distribute and Combine Like Terms
Now, substitute the expanded result back into the expression and distribute the $-3$. Ensure the negative sign is applied to every term within the parentheses:
$$1 - 3(1 - 6x^2 + 9x^4)$$
$$= 1 - 3 + 18x^2 - 27x^4$$

Finally, combine the constant terms ($1 - 3 = -2$) and arrange the polynomial in standard form (highest degree to lowest):
$$-27x^4 + 18x^2 - 2$$

---

**Final Result:**
$$(g \circ g)(x) = -27x^4 + 18x^2 - 2$$

### $(f \circ g)(1)$

$f(x) = 2x^2 -5$ 
and
$g(x) = 1-3x^2$

Evaluating a composite function at a specific number can be done in two ways. Using the "Step-by-Step" method from the video, we run the input through the inner function first, then use that result as the input for the outer function.

---
#### Step 1: Identify the Order of Evaluation
The notation $(f \circ g)(1)$ is equivalent to $f(g(1))$.
*   **Inner Function:** $g(x) = 1 - 3x^2$ (Evaluate this first with the input $1$)
*   **Outer Function:** $f(x) = 2x^2 - 5$ (Evaluate this second using the output from $g$)

#### Step 2: Evaluate the Inner Function $g(1)$
Take the input $1$ and plug it into $g(x)$. Using the "Blank Space" technique:
$$g(1) = 1 - 3(1)^2$$
$$g(1) = 1 - 3(1)$$
$$g(1) = -2$$

The output of our inner function is **$-2$**.

#### Step 3: Evaluate the Outer Function $f(-2)$
Now, take the result from Step 2 and use it as the input for the outer function $f(x)$. We are "shoving" the output of $g$ into the variable for $f$:
$$f(g(1)) = f(-2)$$

Using the "Blank Space" technique on $f(x) = 2x^2 - 5$:
$$f(-2) = 2(-2)^2 - 5$$
$$f(-2) = 2(4) - 5$$
$$f(-2) = 8 - 5$$
$$f(-2) = 3$$

---

**Final Result:**
$$(f \circ g)(1) = 3$$
### $(g \circ f)(2)$

$f(x) = 2x^2 -5$ 
and
$g(x) = 1-3x^2$

Evaluating a composite function at a specific number involves running the input through the "inner" function first, then using that result as the input for the "outer" function.

---
#### Step 1: Identify the Order of Evaluation
The notation $(g \circ f)(2)$ is equivalent to $g(f(2))$. 
*   **Inner Function:** $f(x) = 2x^2 - 5$ (Evaluate this first with the input $2$)
*   **Outer Function:** $g(x) = 1 - 3x^2$ (Evaluate this second using the output from $f$)

#### Step 2: Evaluate the Inner Function $f(2)$
Take the initial input $2$ and plug it into $f(x)$. Using the "Blank Space" technique:
$$f(2) = 2(2)^2 - 5$$
$$f(2) = 2(4) - 5$$
$$f(2) = 8 - 5$$
$$f(2) = 3$$

The output of our inner function is **$3$**.

#### Step 3: Evaluate the Outer Function $g(3)$
Now, take the result from Step 2 ($3$) and use it as the new input for the outer function $g(x)$. This represents $g(f(2))$ which is now $g(3)$.
Using the "Blank Space" technique on $g(x) = 1 - 3x^2$:
$$g(3) = 1 - 3(3)^2$$
$$g(3) = 1 - 3(9)$$
$$g(3) = 1 - 27$$
$$g(3) = -26$$

---

**Final Result:**
$$(g \circ f)(2) = -26$$

### $(f \circ f)(-1)$

$f(x) = 2x^2 -5$ 
and
$g(x) = 1-3x^2$

To evaluate the composition of a function onto itself at a specific value, we run the input through the function once, then take that result and run it through the same function a second time.

---

#### Step 1: Identify the Order of Evaluation
The notation $(f \circ f)(-1)$ is equivalent to $f(f(-1))$. 
*   **Inner Function:** $f(x) = 2x^2 - 5$ (Evaluate this first with the input $-1$)
*   **Outer Function:** $f(x) = 2x^2 - 5$ (Evaluate this second using the output from the first step)

#### Step 2: Evaluate the Inner Function $f(-1)$
Take the initial input $-1$ and plug it into $f(x)$. Using the "Blank Space" technique:
$$f(-1) = 2(-1)^2 - 5$$
$$f(-1) = 2(1) - 5$$
$$f(-1) = 2 - 5$$
$$f(-1) = -3$$

The output of our inner function is **$-3$**.

#### Step 3: Evaluate the Outer Function $f(-3)$
Now, take the result from Step 2 and use it as the new input for the outer function $f(x)$. This represents $f(f(-1))$, which we now know is $f(-3)$.
Using the "Blank Space" technique on $f(x) = 2x^2 - 5$ again:
$$f(-3) = 2(-3)^2 - 5$$
$$f(-3) = 2(9) - 5$$
$$f(-3) = 18 - 5$$
$$f(-3) = 13$$

---

**Final Result:**
$$(f \circ f)(-1) = 13$$

### $(g \circ g)(0)$

$f(x) = 2x^2 -5$ 
and
$g(x) = 1-3x^2$

To evaluate the composition of a function onto itself at a specific value, we run the input through the function once, then take that output and use it as the input for the function a second time.

---

#### Step 1: Identify the Order of Evaluation
The notation $(g \circ g)(0)$ is equivalent to $g(g(0))$. 
*   **Inner Function:** $g(x) = 1 - 3x^2$ (Evaluate this first with the input $0$)
*   **Outer Function:** $g(x) = 1 - 3x^2$ (Evaluate this second using the output from the first step)

#### Step 2: Evaluate the Inner Function $g(0)$
Take the initial input $0$ and plug it into $g(x)$. Using the "Blank Space" technique:
$$g(0) = 1 - 3(0)^2$$
$$g(0) = 1 - 3(0)$$
$$g(0) = 1 - 0$$
$$g(0) = 1$$

The output of our inner function is **$1$**.

#### Step 3: Evaluate the Outer Function $g(1)$
Now, take the result from Step 2 ($1$) and use it as the new input for the outer function $g(x)$. This represents $g(g(0))$, which we now know is $g(1)$.
Using the "Blank Space" technique on $g(x) = 1 - 3x^2$ again:
$$g(1) = 1 - 3(1)^2$$
$$g(1) = 1 - 3(1)$$
$$g(1) = 1 - 3$$
$$g(1) = -2$$

---

**Final Result:**
$$(g \circ g)(0) = -2$$

## 2026-April-06 - Finding Domain of Composite Functions (Precalculus - College Algebra 49) :
https://www.youtube.com/watch?v=G8r9oL-ke9s&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=50
### Finding Domain of Composite Functions

This summary covers the process of determining the domain for a composition of functions $(f \circ g)(x)$, as explained by Professor Leonard.
#### Core Concept: The "Two-Part" Domain Rule
The domain of a composite function is not just the domain of the final simplified expression. It is a combination of two distinct constraints:
1.  **The Inside Function:** The domain of the function being "plugged in" (e.g., $g(x)$ in $f(g(x))$).
2.  **The Resulting Function:** The domain of the final, simplified composite expression.
#### The Step-by-Step Process
1.  **Identify the "Inside" Function:** In $f(g(x))$, $g(x)$ is the inside function.
2.  **Find the Domain of the Inside Function:** Check for restrictions (denominators $\neq 0$, even roots $\geq 0$). Write this down immediately—it must be part of the final answer even if it "simplifies away" later.
3.  **Perform the Composition:** Replace every $x$ in the outside function with a set of parentheses and insert the inside function.
4.  **Simplify the Expression:** Use algebra (like multiplying by the LCD for complex fractions) to simplify.
5.  **Find the Domain of the Simplified Result:** Check the new expression for any additional restrictions.
6.  **Combine Constraints:** The final domain is the intersection of the constraints from Step 2 and Step 5.
#### Example Cases
*   **Rational Functions:** If $g(x) = \frac{2}{x}$, then $x \neq 0$ is a permanent restriction. If the final simplified $f(g(x))$ results in $\frac{2}{3x+2}$, you must also exclude $x = -\frac{2}{3}$. The combined domain excludes both values.
*   **Radical Functions:** If $g(x) = \sqrt{x-1}$, the domain is $x \geq 1$. If $f(g(x))$ simplifies to just $x$ (indicating the functions are inverses), the domain remains $x \geq 1$ because the inside function cannot process values smaller than 1.
#### Key Takeaways
*   **"Baggage" Rule:** A function never loses the restrictions of its components. If a value was undefined at the start, it remains undefined in the composition.
*   **Inverse Functions:** When $(f \circ g)(x) = x$ and $(g \circ f)(x) = x$, the functions are inverses. However, they are often only inverses over a specific restricted domain.
*   **The "Blank Space" Method:** To avoid errors, write the outer function with empty parentheses for every $x$ before substituting the inner function.

### Finding the Domain of $(f \circ g)(x)$

To find the domain of the composite function $(f \circ g)(x)$ using the Leonard technique, we must consider the "baggage" of the inside function as well as the restrictions of the final simplified expression.

---
#### Step 1: Analyze the Individual Functions
Before composing, we identify the restrictions for both functions:
*   **Outer Function:** $f(x) = \frac{x}{x+3}$  
    *Constraint: $x + 3 \neq 0 \implies x \neq -3$*
*   **Inner Function:** $g(x) = \frac{2}{x}$  
    *Constraint: $x \neq 0$*

#### Step 2: Identify the Inside Domain
In the composition $(f \circ g)(x)$, the function **$g(x)$ is the inside function**. Because every input must first pass through $g(x)$, the domain of our composition must immediately exclude any values that make $g(x)$ undefined.
*   **Inside Restriction:** $x \neq 0$

#### Step 3: Perform the Composition (The "Blank Space" Technique)
We open up the outer function $f(x)$ and insert the inner function $g(x)$:
$$f(g(x)) = \frac{(\quad)}{(\quad) + 3}$$
Substitute $g(x) = \frac{2}{x}$ into the blanks:
$$\frac{\frac{2}{x}}{\frac{2}{x} + 3}$$

#### Step 4: Simplify the Expression
To simplify this complex fraction, we multiply the entire numerator and denominator by the LCD, which is $x$:
$$\frac{\frac{2}{x} \cdot (x)}{\left(\frac{2}{x} + 3\right) \cdot (x)} = \frac{2}{2 + 3x}$$

#### Step 5: Identify the Resulting Domain
Now we look at our simplified result, $\frac{2}{3x + 2}$, and check for new restrictions. The denominator cannot be zero:
$$3x + 2 = 0$$
$$3x = -2$$
$$x = -\frac{2}{3}$$
*   **Resulting Restriction:** $x \neq -\frac{2}{3}$

#### Step 6: Combine for the Final Domain
The final domain is the combination of the **inside function's restriction** and the **simplified function's restriction**. Even though $0$ looks like it could be plugged into the final version, it would have failed the very first step inside $g(x)$.

**Final Domain:**
*   **Set Notation:** $\{x \mid x \neq 0, x \neq -\frac{2}{3}\}$
*   **Interval Notation:** $(-\infty, -\frac{2}{3}) \cup (-\frac{2}{3}, 0) \cup (0, \infty)$
### Finding the Domain of $(g \circ f)(x)$

To find the domain of the composite function $(g \circ f)(x)$ using the Leonard technique, we evaluate the domain of the "inner" function first and then the domain of the resulting simplified expression.

---
#### Step 1: Analyze the Individual Functions
We start by identifying the domain restrictions for both given functions:
*   **Function 1:** $f(x) = \frac{x}{x+3}$
    *Constraint: The denominator $x+3 \neq 0$, so $x \neq -3$.*
*   **Function 2:** $g(x) = \frac{2}{x}$
    *Constraint: The denominator $x \neq 0$.*
#### Step 2: Identify the "Inside" Domain
In the composition $(g \circ f)(x)$, **$f(x)$ is the inner function**. Any value that makes $f(x)$ undefined must be excluded from the domain of the composition immediately, as the input cannot even pass through the first "machine."
*   **Inside Restriction:** $x \neq -3$
#### Step 3: Perform the Composition
We evaluate $g(f(x))$ by substituting the entire expression of $f(x)$ into the $x$ position of $g(x)$:
$$g(f(x)) = \frac{2}{(\quad)}$$
Insert $f(x) = \frac{x}{x+3}$:
$$\frac{2}{\frac{x}{x+3}}$$
#### Step 4: Simplify the Expression
To simplify this complex fraction, we multiply the numerator by the reciprocal of the denominator:
$$2 \cdot \frac{x+3}{x} = \frac{2(x+3)}{x} = \frac{2x+6}{x}$$
#### Step 5: Identify the "Outside" Domain Restriction
Now we look at the simplified result, $\frac{2x+6}{x}$. For this expression to be defined, the new denominator must not be zero.
*   **Resulting Restriction:** $x \neq 0$
#### Step 6: Combine Restrictions for the Final Domain
The domain of the composition is the intersection of the restrictions found in Step 2 and Step 5. We must exclude $-3$ because it breaks the inner function, and we must exclude $0$ because it breaks the simplified outer function.

**Final Domain:**
*   **Set Notation:** $\{x \mid x \neq -3, x \neq 0\}$
*   **Interval Notation:** $(-\infty, -3) \cup (-3, 0) \cup (0, \infty)$
### Finding the Domain of $(f \circ g)(x)$

To find the domain of the composite function $(f \circ g)(x)$ using the Leonard technique, we must consider the restrictions of the "inside" function as well as any restrictions that emerge in the final simplified expression.

---
#### Step 1: Analyze the Individual Functions
First, we identify the domain of each function independently to spot potential "baggage":
*   **Outer Function:** $f(x) = x^2 + 1$
    *   This is a polynomial. Polynomials have no square roots or denominators with variables.
    *   **Domain:** All real numbers ($-\infty, \infty$).
*   **Inner Function:** $g(x) = \sqrt{x-1}$
    *   This is a square root function. The value inside (the radicand) must be non-negative.
    *   $x - 1 \geq 0 \implies x \geq 1$.
    *   **Domain:** $[1, \infty)$.
#### Step 2: Identify the "Inside" Domain
In the composition $(f \circ g)(x)$, the function **$g(x)$ is the inside function**. Because every input $x$ must first be processed by $g(x)$ before it can reach $f(x)$, the composition is restricted by $g$'s domain.
*   **Inside Restriction:** $x \geq 1$

#### Step 3: Perform the Composition
Using the "Blank Space" technique, we open up $f(x)$ and insert $g(x)$:
$$f(g(x)) = (\quad)^2 + 1$$
Substitute $g(x) = \sqrt{x-1}$ into the blank:
$$(\sqrt{x-1})^2 + 1$$
#### Step 4: Simplify the Expression
When we square a square root, the operations "undo" each other:
$$(\sqrt{x-1})^2 + 1 = (x - 1) + 1 = x$$
The simplified result is simply **$x$**.

#### Step 5: Identify the Resulting Domain
Now we look at the simplified result, $h(x) = x$. By itself, this expression has no restrictions (all real numbers). However, we cannot ignore Step 2.

#### Step 6: Combine for the Final Domain
Even though the simplified version ($x$) looks like it could accept any number, it only exists if the input was first able to pass through the inner function $\sqrt{x-1}$. Since we cannot take the square root of a negative number in the real number system, we must keep the restriction from Step 2.

**Final Domain:**
*   **Set Notation:** $\{x \mid x \geq 1\}$
*   **Interval Notation:** $[1, \infty)$

---

**Note on Inverses:** Because $(f \circ g)(x) = x$, these two functions behave as inverses on this specific restricted domain ($x \geq 1$).

### Finding the Domain of $(g \circ f)(x)$

To find the domain of the composite function $(g \circ f)(x)$ using the Leonard technique, we look at the restrictions of the "inside" function and then the restrictions of the final composed expression.

---
#### Step 1: Analyze the Individual Functions
We first establish the domain for each function independently to understand their natural limits:
*   **Function 1:** $f(x) = x^2 + 1$
    *   This is a polynomial. There are no denominators or even-indexed roots.
    *   **Domain:** $(-\infty, \infty)$ (All real numbers).
*   **Function 2:** $g(x) = \sqrt{x-1}$
    *   This is a square root function. The radicand must be greater than or equal to zero.
    *   $x - 1 \geq 0 \implies x \geq 1$.
    *   **Domain:** $[1, \infty)$.
#### Step 2: Identify the "Inside" Domain
In the composition $(g \circ f)(x)$, **$f(x)$ is the inside function**. We must first ensure the input $x$ is valid for $f(x)$.
*   Since $f(x)$ accepts all real numbers, there are **no initial restrictions** from the inside function.
#### Step 3: Perform the Composition
We evaluate $g(f(x))$ by substituting the expression for $f(x)$ into every $x$ in $g(x)$:
$$g(f(x)) = \sqrt{(\quad) - 1}$$
Substitute $f(x) = x^2 + 1$ into the blank:
$$\sqrt{(x^2 + 1) - 1}$$
#### Step 4: Simplify the Expression
We simplify the expression inside the radical:
$$\sqrt{x^2 + 1 - 1} = \sqrt{x^2}$$
While $\sqrt{x^2}$ is equivalent to $|x|$, we look at the domain requirements of the expression **before** taking the absolute value to ensure it remains defined.
#### Step 5: Identify the "Outside" Domain Restriction
Now we look at our composed expression $\sqrt{x^2}$. For this to be defined in the real number system, the radicand ($x^2$) must be greater than or equal to zero:
$$x^2 \geq 0$$
Since any real number squared is always zero or positive, this inequality is true for **all real numbers**.
#### Step 6: Combine for the Final Domain
We combine the restrictions from the inside function (Step 2) and the resulting composition (Step 5). 
1.  The inside function $f(x)$ allows all real numbers.
2.  The resulting expression $\sqrt{x^2}$ allows all real numbers.

**Final Domain:**
*   **Set Notation:** $\{x \mid x \in \mathbb{R}\}$
*   **Interval Notation:** $(-\infty, \infty)$

## 2026-April-07 - One to One Functions (Precalculus - College Algebra 50) :
https://www.youtube.com/watch?v=C0Q_m2UDerc&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=52
### One-to-One Functions & The Horizontal Line Test

This summary covers the core concepts of "One-to-One" (1-1) functions, which are the prerequisite for a function to have an inverse.

---
#### 1. Defining a One-to-One Function
A function is **one-to-one** if every unique input ($x$) results in a unique output ($y$). 
*   **Standard Function:** Every $x$ has exactly one $y$ (but multiple $x$'s can share the same $y$).
*   **One-to-One Function:** Every $x$ has exactly one $y$, **AND** every $y$ comes from exactly one $x$.
    *   *Mathematical Definition:* If $f(x_1) = f(x_2)$, then $x_1 = x_2$.
#### 2. The Horizontal Line Test (HLT)
While the Vertical Line Test determines if a graph is a *function*, the **Horizontal Line Test** determines if a function is *one-to-one*.
*   **The Rule:** If any horizontal line intersects the graph of a function more than once, the function is **not** one-to-one.
*   **Logic:** If a horizontal line hits two points, it means two different $x$-values share the same height ($y$-value).

| Function Type | Example | 1-1 Status | Reason |
| :--- | :--- | :--- | :--- |
| **Linear** | $f(x) = mx + b$ | Yes | Slanted lines only cross a horizontal line once. |
| **Quadratic** | $f(x) = x^2$ | No | A horizontal line hits both sides of the parabola ($y=4$ at $x=2$ and $x=-2$). |
| **Cubic** | $f(x) = x^3$ | Yes | Always increasing; never "doubles back" on a $y$-value. |
| **Absolute Value** | $f(x) = |x|$ | No | Forms a "V" shape; fails the HLT. |
#### 3. Why One-to-One Matters: Inverses
The primary reason we identify one-to-one functions is to determine if an **Inverse Function** ($f^{-1}$) exists.
*   An inverse function "undoes" the original function. 
*   If a function is NOT one-to-one (like $x^2$), the inverse would not be a function (it would provide two answers for one input, failing the Vertical Line Test).
*   **Condition:** A function has an inverse if and only if it is one-to-one.
#### 4. Increasing and Decreasing Functions
A helpful shortcut mentioned by Professor Leonard:
*   If a function is **strictly increasing** or **strictly decreasing** over its entire domain, it is guaranteed to be one-to-one.
*   It never changes direction, so it can never repeat a $y$-value.
#### 5. Restricting the Domain
If a function is not one-to-one (like $f(x) = x^2$), we can **restrict the domain** to make it one-to-one.
*   *Example:* By saying $f(x) = x^2$ for $x \geq 0$, we only look at the right side of the parabola. This "half" passes the Horizontal Line Test and therefore has an inverse (the principal square root).
## 2026-April-08 - Finding Inverse Functions (Precalculus - College Algebra 51) :
https://www.youtube.com/watch?v=fK7IPeeZoFE&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=52
### Finding Inverse Functions

This summary details the algebraic process and conceptual requirements for finding the inverse of a function, denoted as $f^{-1}(x)$.

---
#### 1. Prerequisite: The One-to-One Check
Before attempting to find an inverse, you must ensure the function is **one-to-one**.
*   If a function fails the Horizontal Line Test (like $f(x) = x^2$), it does not have an inverse function unless the domain is restricted.
*   The inverse must also be a function, meaning each input must map to exactly one output.
#### 2. The Relationship Between $f(x)$ and $f^{-1}(x)$
The core concept of an inverse is that the **inputs and outputs swap roles**.
*   **Domain of $f$** becomes the **Range of $f^{-1}$**.
*   **Range of $f$** becomes the **Domain of $f^{-1}$**.
*   On a graph, $f^{-1}(x)$ is a reflection of $f(x)$ across the line $y = x$.
#### 3. The Algebraic Steps (The 4-Step Method)
To find the inverse of a function algebraically, follow these consistent steps:

1.  **Replace $f(x)$ with $y$:** This makes the algebra easier to manipulate.
2.  **Swap $x$ and $y$:** This step represents the conceptual "inversion" where inputs and outputs switch.
3.  **Solve for the new $y$:** Use algebraic operations to isolate $y$ on one side of the equation.
4.  **Replace $y$ with $f^{-1}(x)$:** Use formal inverse notation for the final answer.
#### 4. Example Walkthrough
**Problem:** Find the inverse of $f(x) = \frac{2x - 3}{x + 4}$

*   **Step 1:** $y = \frac{2x - 3}{x + 4}$
*   **Step 2 (Swap):** $x = \frac{2y - 3}{y + 4}$
*   **Step 3 (Solve for $y$):**
    *   Multiply by denominator: $x(y + 4) = 2y - 3$
    *   Distribute: $xy + 4x = 2y - 3$
    *   Get all $y$ terms on one side: $xy - 2y = -4x - 3$
    *   Factor out $y$: $y(x - 2) = -4x - 3$
    *   Isolate $y$: $y = \frac{-4x - 3}{x - 2}$
*   **Step 4:** $f^{-1}(x) = \frac{-4x - 3}{x - 2}$
#### 5. Verifying the Inverse
To mathematically prove that two functions are inverses, you must perform a **composition**. If they are truly inverses, they will "cancel" each other out, leaving only the original input $x$.
*   **Test 1:** $(f \circ f^{-1})(x) = x$
*   **Test 2:** $(f^{-1} \circ f)(x) = x$

> [!IMPORTANT]
> Both compositions must equal $x$ to confirm the inverse relationship. If you get any other result, they are not inverses or an algebraic error occurred.

### Finding the Inverse of $f(x) = 1 - 3x$

To find the inverse function $f^{-1}(x)$, we use the 4-step algebraic method, which involves swapping the input and output variables.

---
#### Step 1: Replace $f(x)$ with $y$
Rewrite the function in terms of $y$ to make it easier to manipulate.
$$y = 1 - 3x$$

#### Step 2: Swap $x$ and $y$
This step represents the conceptual switch between the domain and the range.
$$x = 1 - 3y$$

#### Step 3: Solve for the new $y$
Isolate $y$ using algebraic operations:
1.  **Subtract 1** from both sides:
    $$x - 1 = -3y$$
2.  **Divide by -3** to isolate $y$:
    $$y = \frac{x - 1}{-3}$$
3.  **Simplify the signs** (optional but standard):
    Multiply the numerator and denominator by $-1$:
    $$y = \frac{-(x - 1)}{3} = \frac{-x + 1}{3} \quad \text{or} \quad y = \frac{1 - x}{3}$$

#### Step 4: Replace $y$ with $f^{-1}(x)$
Write the final result using proper inverse notation.
$$f^{-1}(x) = \frac{1 - x}{3}$$

---
#### Verification (The Check)
To confirm this is the correct inverse, we can compose $f(x)$ with $f^{-1}(x)$. If they are inverses, the result must be $x$:
$$(f \circ f^{-1})(x) = 1 - 3\left( \frac{1 - x}{3} \right)$$
$$= 1 - (1 - x)$$
$$= 1 - 1 + x$$
$$= x$$
The functions are verified as inverses.
### Finding the Inverse of $g(x) = x^3 + 4$

To find the inverse function $g^{-1}(x)$, we use the standard 4-step algebraic method. Since $g(x)$ is a cubic function, it is one-to-one and has a natural inverse.

---
#### Step 1: Replace $g(x)$ with $y$
Rewrite the function using $y$ for easier calculation.
$$y = x^3 + 4$$

#### Step 2: Swap $x$ and $y$
Switch the input and output variables to represent the inverse relationship.
$$x = y^3 + 4$$

#### Step 3: Solve for the new $y$
Isolate $y$ using inverse operations:
1.  **Subtract 4** from both sides:
    $$x - 4 = y^3$$
2.  **Take the cube root** of both sides to undo the power of 3:
    $$\sqrt[3]{x - 4} = y$$

#### Step 4: Replace $y$ with $g^{-1}(x)$
Write the final result using formal inverse notation.
$$g^{-1}(x) = \sqrt[3]{x - 4}$$

---
#### Verification (The Check)
We can verify the result by composing the two functions. If they are truly inverses, $(g \circ g^{-1})(x)$ must equal $x$:

$$(g \circ g^{-1})(x) = (\sqrt[3]{x - 4})^3 + 4$$
$$= (x - 4) + 4$$
$$= x$$

The functions are successfully verified as inverses.
### Finding the Inverse of $h(x) = x^2 + 9$

To determine the inverse of $h(x)$, we must first consider whether the function is **one-to-one** (passes the Horizontal Line Test).

---
#### Step 1: The One-to-One Check
The function $h(x) = x^2 + 9$ is a parabola shifted up 9 units. Because it is a quadratic function with an unrestricted domain, it is **not one-to-one**.
*   For example: $h(2) = (2)^2 + 9 = 13$ and $h(-2) = (-2)^2 + 9 = 13$.
*   Since two different inputs ($2$ and $-2$) lead to the same output ($13$), the function fails the Horizontal Line Test.

> [!CAUTION]
> Technically, $h(x) = x^2 + 9$ does not have an inverse **function** unless we restrict the domain (e.g., $x \geq 0$). However, we can still perform the algebraic steps to find the inverse relation.

#### Step 2: Replace $h(x)$ with $y$
$$y = x^2 + 9$$

#### Step 3: Swap $x$ and $y$
$$x = y^2 + 9$$

#### Step 4: Solve for $y$
1.  **Subtract 9** from both sides:
    $$x - 9 = y^2$$
2.  **Take the square root** of both sides:
    $$y = \pm \sqrt{x - 9}$$

#### Step 5: Replace $y$ with Inverse Notation
Because of the $\pm$, the result is a relation, not a single function. If we restrict the original domain to $x \geq 0$, we choose the principal (positive) root:
$$h^{-1}(x) = \sqrt{x - 9}$$

---
#### Key Properties
*   **Domain of $h(x)$:** $(-\infty, \infty)$
*   **Range of $h(x)$:** $[9, \infty)$
*   **Domain of $h^{-1}(x)$:** $[9, \infty)$ (The input $x$ must be 9 or greater to avoid a negative under the radical).
*   **Range of $h^{-1}(x)$:** $[0, \infty)$ (If using the restricted domain).
### Finding the Inverse of $f(x) = \frac{4}{2-x}$

To find the inverse function $f^{-1}(x)$, we utilize the algebraic swapping method and then analyze the graphical behavior of both functions.

---
#### Step 1: Replace $f(x)$ with $y$
$$y = \frac{4}{2-x}$$

#### Step 2: Swap $x$ and $y$
$$x = \frac{4}{2-y}$$

#### Step 3: Solve for the new $y$
1.  **Multiply by the denominator** to clear the fraction:
    $$x(2 - y) = 4$$
2.  **Divide by $x$**:
    $$2 - y = \frac{4}{x}$$
3.  **Isolate $y$**:
    $$-y = \frac{4}{x} - 2$$
4.  **Multiply by $-1$** to solve for positive $y$:
    $$y = 2 - \frac{4}{x}$$
    *Note: This can also be written as a single fraction: $y = \frac{2x - 4}{x}$.*

#### Step 4: Replace $y$ with $f^{-1}(x)$
$$f^{-1}(x) = 2 - \frac{4}{x}$$

---
#### Graphical Analysis

The graphs of $f(x)$ and $f^{-1}(x)$ are **rational functions** (hyperbolas). Because they are inverses, they are symmetric reflections of each other across the diagonal line $y = x$.
#### The Original Function: $f(x) = \frac{4}{2-x}$
*   **Vertical Asymptote:** $x = 2$ (where the denominator is zero).
*   **Horizontal Asymptote:** $y = 0$ (the x-axis, as $x$ gets very large).
*   **Intercepts:** $y$-intercept at $(0, 2)$. No $x$-intercepts.
*   **Shape:** The graph is a hyperbola split into two branches by the vertical asymptote at $x=2$.
#### The Inverse Function: $f^{-1}(x) = 2 - \frac{4}{x}$
*   **Vertical Asymptote:** $x = 0$ (the y-axis).
*   **Horizontal Asymptote:** $y = 2$.
*   **Intercepts:** $x$-intercept at $(2, 0)$. No $y$-intercepts.
*   **Shape:** This graph is also a hyperbola. Notice how the asymptotes and intercepts have swapped values compared to the original function:
    *   $f(x)$ VA $x=2 \implies f^{-1}(x)$ HA $y=2$.
    *   $f(x)$ HA $y=0 \implies f^{-1}(x)$ VA $x=0$.
    *   $f(x)$ point $(0, 2) \implies f^{-1}(x)$ point $(2, 0)$.

---
#### Verification
$$(f \circ f^{-1})(x) = \frac{4}{2 - (2 - \frac{4}{x})}$$
$$= \frac{4}{2 - 2 + \frac{4}{x}}$$
$$= \frac{4}{\frac{4}{x}} = 4 \cdot \frac{x}{4} = x$$
### Finding the Inverse of $g(x) = \frac{-2x}{x-1}$

To find the inverse function $g^{-1}(x)$, we use the standard algebraic process of swapping the roles of $x$ and $y$.

---

#### Step 1: Replace $g(x)$ with $y$
$$y = \frac{-2x}{x-1}$$

#### Step 2: Swap $x$ and $y$
$$x = \frac{-2y}{y-1}$$

#### Step 3: Solve for the new $y$
1.  **Clear the fraction** by multiplying both sides by $(y - 1)$:
    $$x(y - 1) = -2y$$
2.  **Distribute** the $x$:
    $$xy - x = -2y$$
3.  **Group all $y$ terms** on one side:
    $$xy + 2y = x$$
4.  **Factor out** $y$:
    $$y(x + 2) = x$$
5.  **Isolate $y$**:
    $$y = \frac{x}{x + 2}$$

#### Step 4: Replace $y$ with $g^{-1}(x)$
$$g^{-1}(x) = \frac{x}{x + 2}$$

---
#### Graphical Analysis

Both functions are **rational functions** (hyperbolas). As inverses, their graphs are reflections of each other across the identity line $y = x$.

#### The Original Function: $g(x) = \frac{-2x}{x-1}$
*   **Vertical Asymptote:** $x = 1$
*   **Horizontal Asymptote:** $y = -2$ (determined by the ratio of the leading coefficients $\frac{-2}{1}$)
*   **Intercepts:** Passes through the origin $(0, 0)$.

#### The Inverse Function: $g^{-1}(x) = \frac{x}{x + 2}$
*   **Vertical Asymptote:** $x = -2$
*   **Horizontal Asymptote:** $y = 1$ (the ratio $\frac{1}{1}$)
*   **Intercepts:** Passes through the origin $(0, 0)$.

> [!NOTE]
> Notice the **Symmetry of Asymptotes**:
> *   The Vertical Asymptote of $g(x)$ ($x=1$) became the Horizontal Asymptote of $g^{-1}(x)$ ($y=1$).
> *   The Horizontal Asymptote of $g(x)$ ($y=-2$) became the Vertical Asymptote of $g^{-1}(x)$ ($x=-2$).

---
#### Verification
$$(g \circ g^{-1})(x) = \frac{-2\left(\frac{x}{x+2}\right)}{\left(\frac{x}{x+2}\right) - 1}$$
Multiply the numerator and denominator by the LCD, $(x + 2)$:
$$\frac{-2x}{x - (x + 2)} = \frac{-2x}{-2} = x$$
The functions are verified as inverses.
### Finding the Inverse of $h(x) = \frac{3x+4}{x-2}$

To find the inverse function $h^{-1}(x)$, we follow the algebraic process of swapping the independent and dependent variables.

---
#### Step 1: Replace $h(x)$ with $y$
$$y = \frac{3x+4}{x-2}$$

#### Step 2: Swap $x$ and $y$
$$x = \frac{3y+4}{y-2}$$

#### Step 3: Solve for the new $y$
1.  **Clear the fraction** by multiplying both sides by $(y - 2)$:
    $$x(y - 2) = 3y + 4$$
2.  **Distribute** $x$:
    $$xy - 2x = 3y + 4$$
3.  **Group all $y$ terms** on one side and constants on the other:
    $$xy - 3y = 2x + 4$$
4.  **Factor out** $y$:
    $$y(x - 3) = 2x + 4$$
5.  **Isolate $y$**:
    $$y = \frac{2x + 4}{x - 3}$$

#### Step 4: Replace $y$ with $h^{-1}(x)$
$$h^{-1}(x) = \frac{2x + 4}{x - 3}$$

---
#### Graphical Analysis

Both functions are hyperbolas. The inverse relationship is characterized by the swapping of domain and range, which manifests visually as a swap of the asymptotes.
##### The Original Function: $h(x) = \frac{3x+4}{x-2}$
*   **Vertical Asymptote:** $x = 2$
*   **Horizontal Asymptote:** $y = 3$ (Ratio of leading coefficients $\frac{3}{1}$)
*   **$x$-intercept:** Set $3x+4 = 0 \implies (-\frac{4}{3}, 0)$
*   **$y$-intercept:** Set $x = 0 \implies (0, -2)$
##### The Inverse Function: $h^{-1}(x) = \frac{2x+4}{x-3}$
*   **Vertical Asymptote:** $x = 3$
*   **Horizontal Asymptote:** $y = 2$ (Ratio of leading coefficients $\frac{2}{1}$)
*   **$x$-intercept:** Set $2x+4 = 0 \implies (-2, 0)$
*   **$y$-intercept:** Set $x = 0 \implies (0, -\frac{4}{3})$

> [!NOTE]
> **Symmetry Check:** 
> The Vertical Asymptote of $h$ ($x=2$) is the Horizontal Asymptote of $h^{-1}$ ($y=2$).
> The Horizontal Asymptote of $h$ ($y=3$) is the Vertical Asymptote of $h^{-1}$ ($x=3$).
> The intercepts also swap coordinates: $(0, -2)$ becomes $(-2, 0)$ and $(-\frac{4}{3}, 0)$ becomes $(0, -\frac{4}{3})$.

---
#### Verification
$$(h \circ h^{-1})(x) = \frac{3\left(\frac{2x+4}{x-3}\right)+4}{\left(\frac{2x+4}{x-3}\right)-2}$$
Multiply numerator and denominator by $(x-3)$:
$$\frac{3(2x+4) + 4(x-3)}{(2x+4) - 2(x-3)} = \frac{6x + 12 + 4x - 12}{2x + 4 - 2x + 6} = \frac{10x}{10} = x$$
### Finding the Inverse of $f(x) = \frac{x^{2}+3}{3x^{2}}$

To determine the inverse of this function, we must first note that $f(x)$ is an **even function** (the graph is symmetric across the y-axis because $x$ is squared). Consequently, it is not one-to-one over its entire domain. To find a functional inverse, we must restrict the domain, typically to $x > 0$.

---
#### Step 1: Replace $f(x)$ with $y$
$$y = \frac{x^{2}+3}{3x^{2}}$$

#### Step 2: Swap $x$ and $y$
$$x = \frac{y^{2}+3}{3y^{2}}$$

#### Step 3: Solve for the new $y$
1.  **Clear the fraction** by multiplying by $3y^{2}$:
    $$3xy^{2} = y^{2} + 3$$
2.  **Move all $y^{2}$ terms** to one side:
    $$3xy^{2} - y^{2} = 3$$
3.  **Factor out** $y^{2}$:
    $$y^{2}(3x - 1) = 3$$
4.  **Isolate $y^{2}$**:
    $$y^{2} = \frac{3}{3x - 1}$$
5.  **Take the square root**:
    $$y = \pm \sqrt{\frac{3}{3x - 1}}$$

#### Step 4: Replace $y$ with $f^{-1}(x)$
Assuming a restricted domain of $x > 0$ for the original function to make it one-to-one:
$$f^{-1}(x) = \sqrt{\frac{3}{3x - 1}}$$

---
#### Graphical Analysis

The graphs of these functions are more complex than simple linear or standard rational functions.
##### The Original Function: $f(x) = \frac{x^{2}+3}{3x^{2}}$
*   **Vertical Asymptote:** $x = 0$ (the y-axis).
*   **Horizontal Asymptote:** $y = \frac{1}{3}$ (ratio of $x^{2}$ coefficients).
*   **Symmetry:** Even function (symmetric across the y-axis).
*   **Shape:** The graph resembles two "horns" reaching up toward infinity at $x=0$ and flattening out toward $y=1/3$ as $x \to \pm\infty$.
##### The Inverse Function: $f^{-1}(x) = \sqrt{\frac{3}{3x - 1}}$
*   **Vertical Asymptote:** $x = \frac{1}{3}$ (where $3x-1=0$).
*   **Horizontal Asymptote:** $y = 0$ (as $x \to \infty$).
*   **Domain:** $x > \frac{1}{3}$ (the value inside the root must be positive).
*   **Shape:** The graph exists only to the right of $x = 1/3$. It starts high near the vertical asymptote and curves down toward the x-axis.

> [!NOTE]
> **Symmetry Check:**
> The original function's Horizontal Asymptote ($y=1/3$) has become the inverse function's Vertical Asymptote ($x=1/3$).
> The original function's Vertical Asymptote ($x=0$) has become the inverse function's Horizontal Asymptote ($y=0$).

---
#### Verification
$$(f \circ f^{-1})(x) = \frac{\left(\sqrt{\frac{3}{3x - 1}}\right)^{2} + 3}{3\left(\sqrt{\frac{3}{3x - 1}}\right)^{2}}$$
$$= \frac{\frac{3}{3x - 1} + 3}{3\left(\frac{3}{3x - 1}\right)} = \frac{\frac{3 + 3(3x - 1)}{3x - 1}}{\frac{9}{3x - 1}}$$
$$= \frac{3 + 9x - 3}{9} = \frac{9x}{9} = x$$
## 2026-May-09 - Graphs of Exponential Functions (Precalculus - College Algebra 52) : 
https://www.youtube.com/watch?v=2w14jBb0e9Q&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=54
### Graphs of Exponential Functions

This summary explores the behavior, characteristics, and transformations of exponential functions, which take the general form $f(x) = b^x$.

---
#### 1. Defining the Exponential Function
An exponential function is defined as $f(x) = b^x$, where the variable is in the exponent.
*   **Base ($b$):** Must be a positive constant ($b > 0$) and cannot be 1 ($b \neq 1$).
*   **Case 1: Exponential Growth ($b > 1$):** As $x$ increases, $y$ increases rapidly (e.g., $2^x, 5^x, e^x$).
*   **Case 2: Exponential Decay ($0 < b < 1$):** As $x$ increases, $y$ decreases toward zero (e.g., $(\frac{1}{2})^x, 0.5^x$).
#### 2. Key Characteristics of the Parent Graph ($b^x$)
Regardless of the base (as long as it is growth), the basic graph share several features:
*   **Horizontal Asymptote:** The x-axis ($y = 0$). The graph approaches but never touches this line.
*   **y-intercept:** Always $(0, 1)$ because any non-zero base to the power of zero is 1 ($b^0 = 1$).
*   **Domain:** $(-\infty, \infty)$ (All real numbers).
*   **Range:** $(0, \infty)$ (Always positive).
*   **Key Points:** $(0, 1)$, $(1, b)$, and $(-1, \frac{1}{b})$.
#### 3. Transformations of Exponential Functions
The general transformed equation is $f(x) = a \cdot b^{x-h} + k$.

| Transformation | Effect on Graph |
| :--- | :--- |
| **Vertical Shift ($k$)** | Moves the graph up or down. **This changes the Horizontal Asymptote to $y = k$.** |
| **Horizontal Shift ($h$)** | Moves the graph left ($+h$) or right ($-h$). |
| **Vertical Stretch ($a$)** | Multiplies the $y$-values. If $a$ is negative, the graph reflects over the x-axis. |
| **Negative Exponent ($-x$)** | Reflects the graph over the y-axis (turning Growth into Decay). |

#### 4. The Natural Base ($e$)
The number $e$ (Euler's number) is an irrational constant approximately equal to $2.71828$.
*   It is used frequently in calculus and finance (continuous compounding).
*   The graph of $f(x) = e^x$ is a standard growth curve situated between $2^x$ and $3^x$.
#### 5. Comparison: Exponential vs. Polynomial
*   **Polynomial ($x^2$):** The base varies, the exponent is constant.
*   **Exponential ($2^x$):** The base is constant, the exponent varies.
*   Exponential functions eventually grow much faster than any polynomial function.
> [!TIP]
> When graphing transformations, always plot the **Horizontal Asymptote** first. It serves as the new "floor" (or "ceiling") for your function.

## 2026-May-10 - Graphing Exponential Functions with Transformations (Precalculus -College Algebra 53) :
https://www.youtube.com/watch?v=uycM-AzUDQ4&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=55
### Graphing Exponential Functions with Transformations

This summary focuses on the practical application of transformations to exponential parent functions. The key to graphing these efficiently is tracking the "anchor" points and the horizontal asymptote.

---
#### 1. The General Transformation Formula
The transformed exponential function is typically written as:
$$f(x) = a \cdot b^{x-h} + k$$

*   **$b$**: The base (determines the basic shape: growth if $b > 1$, decay if $0 < b < 1$).
*   **$a$**: Vertical stretch/compression and reflection over the x-axis.
*   **$h$**: Horizontal shift (Right if $x-h$, Left if $x+h$).
*   **$k$**: Vertical shift. **This is the most critical value for the asymptote.**
#### 2. Tracking the Horizontal Asymptote (HA)
In the parent function $y = b^x$, the HA is always $y = 0$. 
*   **The Rule:** The Horizontal Asymptote is always determined by the vertical shift ($k$).
*   **Equation:** $y = k$
*   *Action:* Always draw the dashed line for the HA first to provide a boundary for your curve.
#### 3. The 3 Step-Graphing Method
Professor Leonard emphasizes tracking how the transformations affect the "standard" coordinates of the parent function.
##### Step A: Identify Parent Points
For any base $b$, the three easiest points to track are:
*   $(-1, 1/b)$
*   $(0, 1)$
*   $(1, b)$
##### Step B: Apply Reflections and Stretches ($a$)
If there is a coefficient $a$ in front of the base, multiply the $y$-coordinates of your parent points by $a$. If $a$ is negative, the graph flips upside down.
##### Step C: Apply Shifts ($h, k$)
*   **Horizontal ($h$):** Add or subtract from the $x$-values.
*   **Vertical ($k$):** Add or subtract from the $y$-values. This shift also moves your HA.
#### 4. Common Transformation Scenarios

| Feature | $f(x) = 2^{x+3} - 4$ | $f(x) = -3^x + 2$ |
| :--- | :--- | :--- |
| **Base** | 2 (Growth) | 3 (Growth) |
| **Reflections** | None | Over x-axis (Negative $a$) |
| **Horizontal Shift** | Left 3 | None |
| **Vertical Shift** | Down 4 | Up 2 |
| **Asymptote** | $y = -4$ | $y = 2$ |

#### 5. Finding the Intercepts Algebraically
To ensure accuracy in your Obsidian notes, always solve for intercepts:
*   **y-intercept:** Evaluate $f(0)$. This is often $(0, a \cdot b^{-h} + k)$.
*   **x-intercept:** Set $f(x) = 0$ and solve for $x$ (this will eventually require logarithms if the bases cannot be made equal).

> [!IMPORTANT]
> **Domain and Range:** 
> The **Domain** of an exponential function remains $(-\infty, \infty)$ regardless of transformations. 
> The **Range** is restricted by the HA. If $a > 0$, the range is $(k, \infty)$. If $a < 0$, the range is $(-\infty, k)$.

### Graphing $f(x) = 3^x - 2$ with Transformations

This analysis breaks down the behavior of the function by comparing it to its parent graph and identifying the specific shifts applied.

---
#### 1. Identify the Parent Function
The parent function is $y = 3^x$.
*   **Type:** Exponential Growth (since the base $b=3$ is greater than 1).
*   **Parent Asymptote:** $y = 0$ (the x-axis).
*   **Parent Key Points:** 
    *   $(-1, 1/3)$
    *   $(0, 1)$
    *   $(1, 3)$
#### 2. Identify the Transformations
The equation is in the form $f(x) = b^x + k$.
*   **Vertical Shift:** The $-2$ at the end indicates a **shift down 2 units**.
*   **Horizontal Shift:** None (the exponent is just $x$).
*   **Reflections:** None (the base and the coefficient are positive).
#### 3. Determine the New Horizontal Asymptote
Since the entire graph shifted down 2 units, the "floor" of the function moves with it.
*   **New Asymptote:** $y = -2$
#### 4. Track the Transformed Key Points
Subtract 2 from the $y$-values of the parent points:
*   $(-1, 1/3)$ becomes **$(-1, -5/3)$** or approximately $(-1, -1.67)$
*   $(0, 1)$ becomes **$(0, -1)$** (The new y-intercept)
*   $(1, 3)$ becomes **$(1, 1)$**
#### 5. Visual Description of the Graph
*   **Direction:** The graph starts very close to the dashed horizontal line at $y = -2$ on the far left side.
*   **Curvature:** It moves toward the right, passing through the y-axis at $(0, -1)$.
*   **Growth:** As $x$ increases, the graph curves sharply upward, crossing the point $(1, 1)$ and continuing toward positive infinity.
*   **Quadrant Placement:** The graph occupies parts of Quadrants I, III, and IV, but never goes below $y = -2$.
#### 6. Domain and Range
*   **Domain:** $(-\infty, \infty)$
*   **Range:** $(-2, \infty)$
### Graphing $f(x) = 1 - 2^{x+3}$ with Transformations

To properly analyze this function using the Leonard technique, we should look at it in the standard form: $f(x) = -2^{x+3} + 1$.

---
#### 1. Parent Function Identification
The parent function is $y = 2^x$.
*   **Type:** Exponential Growth ($b=2$).
*   **Parent Asymptote:** $y = 0$.
*   **Parent Key Points:** 
    *   $(-1, 0.5)$
    *   $(0, 1)$
    *   $(1, 2)$
#### 2. Sequence of Transformations
Following the algebraic order of operations ($x$-transformations first, then $y$):
1.  **Horizontal Shift:** The $(x+3)$ shifts the graph **Left 3 units**.
2.  **Vertical Reflection:** The negative sign in front of the base reflects the graph **over the x-axis**.
3.  **Vertical Shift:** The constant $+1$ shifts the graph **Up 1 unit**.
#### 3. New Horizontal Asymptote (HA)
The HA is determined solely by the vertical shift ($k$).
*   **New Asymptote:** $y = 1$
#### 4. Tracking Point Transformations
We apply $(x - 3)$ to the x-coordinates and $(-y + 1)$ to the y-coordinates:

| Parent $(x, y)$ | Applied Transformation | Transformed Point |
| :--- | :--- | :--- |
| $(-1, 0.5)$ | $(-1-3, -0.5+1)$ | **$(-4, 0.5)$** |
| $(0, 1)$ | $(0-3, -1+1)$ | **$(-3, 0)$** |
| $(1, 2)$ | $(1-3, -2+1)$ | **$(-2, -1)$** |

*   **y-intercept:** Calculated by $f(0) = 1 - 2^{0+3} = 1 - 8 = -7$. The point is **$(0, -7)$**.
#### 5. Visual Description of the Graph
*   **Orientation:** Because of the x-axis reflection, the graph is "upside down" compared to a standard growth curve.
*   **Left Side ($x \to -\infty$):** The graph stays very flat, hugging the bottom of the horizontal asymptote line at $y = 1$.
*   **Right Side ($x \to \infty$):** After crossing the x-axis at $(-3, 0)$, the graph dives steeply downward, accelerating toward negative infinity.
*   **Quadrant Path:** It begins in Quadrant II (below the asymptote), passes through Quadrant III, and crosses into Quadrant IV at its y-intercept.
#### 6. Domain and Range
*   **Domain:** $(-\infty, \infty)$
*   **Range:** $(-\infty, 1)$
### Graphing $f(x) = 2^{x+2}$ with Transformations

This analysis follows the method of identifying the parent function and tracking how specific changes to the exponent affect the graph's position.

---
#### 1. Parent Function Identification
The parent function is $y = 2^x$.
*   **Type:** Exponential Growth ($b=2$).
*   **Parent Asymptote:** $y = 0$ (the x-axis).
*   **Parent Key Points:** 
    *   $(-1, 0.5)$
    *   $(0, 1)$
    *   $(1, 2)$
#### 2. Sequence of Transformations
The function is in the form $f(x) = b^{x-h} + k$.
*   **Horizontal Shift:** The $+2$ inside the exponent indicates a shift **Left 2 units**.
*   **Vertical Shift:** None ($k=0$).
*   **Reflections:** None.
#### 3. New Horizontal Asymptote (HA)
Because there is no vertical shift ($k=0$), the horizontal asymptote remains unchanged.
*   **New Asymptote:** $y = 0$
#### 4. Tracking Point Transformations
We apply the horizontal shift by subtracting 2 from each $x$-coordinate while keeping the $y$-coordinates the same:

| Parent $(x, y)$ | Applied Transformation $(x-2, y)$ | Transformed Point |
| :--- | :--- | :--- |
| $(-1, 0.5)$ | $(-1-2, 0.5)$ | **$(-3, 0.5)$** |
| $(0, 1)$ | $(0-2, 1)$ | **$(-2, 1)$** |
| $(1, 2)$ | $(1-2, 2)$ | **$(-1, 2)$** |

*   **y-intercept:** Calculated by $f(0) = 2^{0+2} = 2^2 = 4$. The point is **$(0, 4)$**.
#### 5. Visual Description of the Graph
*   **Shape:** The graph maintains the standard "J-curve" shape of exponential growth.
*   **Position:** The entire curve has been slid 2 units to the left. This makes the graph appear "steeper" as it crosses the y-axis compared to the parent function.
*   **Left Side ($x \to -\infty$):** The graph approaches the x-axis ($y=0$) but never touches it.
*   **Right Side ($x \to \infty$):** The graph rises rapidly toward positive infinity, passing through the y-intercept at $(0, 4)$.
#### 6. Domain and Range
*   **Domain:** $(-\infty, \infty)$
*   **Range:** $(0, \infty)$
### Graphing $f(x) = -3^x + 1$ with Transformations

This breakdown follows the Leonard method by identifying the parent growth curve and applying reflections and vertical shifts to determine the final position of the hyperbola.

---
#### 1. Parent Function Identification
The parent function is $y = 3^x$.
*   **Type:** Exponential Growth ($b=3$).
*   **Parent Asymptote:** $y = 0$ (the x-axis).
*   **Parent Key Points:** 
    *   $(-1, 1/3)$
    *   $(0, 1)$
    *   $(1, 3)$
#### 2. Sequence of Transformations
The function is in the form $f(x) = -b^x + k$.
*   **Vertical Reflection:** The negative sign in front of the base ($a = -1$) reflects the graph **over the x-axis**.
*   **Vertical Shift:** The $+1$ indicates a shift **Up 1 unit**.
*   **Horizontal Shift:** None.
#### 3. New Horizontal Asymptote (HA)
The horizontal asymptote is strictly defined by the vertical shift constant.
*   **New Asymptote:** $y = 1$
#### 4. Tracking Point Transformations
We apply the reflection (multiply $y$ by $-1$) and then the vertical shift (add 1 to $y$) to the parent coordinates:

| Parent $(x, y)$ | Applied Transformation $(-y + 1)$ | Transformed Point |
| :--- | :--- | :--- |
| $(-1, 1/3)$ | $(-1, -1/3 + 1)$ | **$(-1, 2/3)$** |
| $(0, 1)$ | $(0, -1 + 1)$ | **$(0, 0)$** (Origin) |
| $(1, 3)$ | $(1, -3 + 1)$ | **$(1, -2)$** |
#### 5. Visual Description of the Graph
*   **Orientation:** Due to the reflection, the graph is "inverted." Instead of curving upward to infinity, it curves downward.
*   **Left Side ($x \to -\infty$):** The graph is very flat, hugging the underside of the horizontal asymptote at $y = 1$.
*   **Right Side ($x \to \infty$):** After passing through the origin $(0, 0)$, the graph dives steeply into Quadrant IV, moving toward negative infinity.
*   **Intercepts:** The graph passes exactly through the origin $(0, 0)$, serving as both the x and y-intercept.
#### 6. Domain and Range
*   **Domain:** $(-\infty, \infty)$
*   **Range:** $(-\infty, 1)$ (All $y$-values must be below the asymptote).
### Graphing $f(x) = 3(\frac{1}{2})^x$ with Transformations

This analysis applies the tracking method to an exponential decay function, identifying how a vertical stretch affects the parent points.

---
#### 1. Parent Function Identification
The parent function is $y = (\frac{1}{2})^x$.
*   **Type:** Exponential Decay (since the base $0 < b < 1$).
*   **Parent Asymptote:** $y = 0$ (the x-axis).
*   **Parent Key Points:** 
    *   $(-1, 2)$
    *   $(0, 1)$
    *   $(1, 0.5)$
#### 2. Sequence of Transformations
The function is in the form $f(x) = a \cdot b^x$.
*   **Vertical Stretch:** The coefficient $a=3$ indicates a **vertical stretch by a factor of 3**. This means every $y$-value is tripled.
*   **Horizontal Shift:** None.
*   **Vertical Shift:** None.
*   **Reflections:** None.
#### 3. New Horizontal Asymptote (HA)
Because there is no vertical shift ($k=0$), the horizontal asymptote does not move.
*   **New Asymptote:** $y = 0$
#### 4. Tracking Point Transformations
We apply the vertical stretch by multiplying each $y$-coordinate by 3:

| Parent $(x, y)$ | Applied Transformation $(x, 3y)$ | Transformed Point |
| :--- | :--- | :--- |
| $(-1, 2)$ | $(-1, 2 \cdot 3)$ | **$(-1, 6)$** |
| $(0, 1)$ | $(0, 1 \cdot 3)$ | **$(0, 3)$** (y-intercept) |
| $(1, 0.5)$ | $(1, 0.5 \cdot 3)$ | **$(1, 1.5)$** |

#### 5. Visual Description of the Graph
*   **Shape:** The graph maintains the "L-curve" of exponential decay, sloping downward from left to right.
*   **Steepness:** Due to the vertical stretch, the graph is "taller" and appears to drop more dramatically from the left than the parent function.
*   **Left Side ($x \to -\infty$):** The graph rises rapidly toward positive infinity.
*   **Right Side ($x \to \infty$):** The graph flattens out, approaching the x-axis ($y=0$) but never reaching it.
*   **Intercept:** The y-intercept has moved from $(0, 1)$ up to $(0, 3)$.
#### 6. Domain and Range
*   **Domain:** $(-\infty, \infty)$
*   **Range:** $(0, \infty)$
### Graphing $f(x) = e^{x+2}-1$ with Transformations

This analysis tracks the natural exponential function $e^x$ through horizontal and vertical shifts to determine its final position on the coordinate plane.

---
#### 1. Parent Function Identification
The parent function is $y = e^x$.
*   **Type:** Exponential Growth ($e \approx 2.718$).
*   **Parent Asymptote:** $y = 0$.
*   **Parent Key Points:** 
    *   $(-1, 1/e) \approx (-1, 0.37)$
    *   $(0, 1)$
    *   $(1, e) \approx (1, 2.72)$
#### 2. Sequence of Transformations
The function follows the form $f(x) = e^{x-h} + k$.
*   **Horizontal Shift:** The $+2$ in the exponent indicates a shift **Left 2 units**.
*   **Vertical Shift:** The $-1$ at the end indicates a shift **Down 1 unit**.
*   **Reflections:** None.
#### 3. New Horizontal Asymptote (HA)
The HA follows the vertical shift ($k$).
*   **New Asymptote:** $y = -1$
#### 4. Tracking Point Transformations
We subtract 2 from the $x$-coordinates and subtract 1 from the $y$-coordinates:

| Parent $(x, y)$ | Applied Transformation $(x-2, y-1)$ | Transformed Point |
| :--- | :--- | :--- |
| $(-1, 0.37)$ | $(-1-2, 0.37-1)$ | **$(-3, -0.63)$** |
| $(0, 1)$ | $(0-2, 1-1)$ | **$(-2, 0)$** (x-intercept) |
| $(1, 2.72)$ | $(1-2, 2.72-1)$ | **$(-1, 1.72)$** |

*   **y-intercept:** $f(0) = e^{0+2} - 1 = e^2 - 1 \approx 7.39 - 1 = 6.39$. The point is **$(0, 6.39)$**.
#### 5. Visual Description of the Graph
*   **Shape:** A standard exponential growth curve that has been shifted into the left quadrants and pulled down.
*   **Left Side ($x \to -\infty$):** The graph flattens out horizontally, approaching the dashed line at $y = -1$ from above.
*   **Right Side ($x \to \infty$):** The graph passes through the x-axis at $(-2, 0)$ and climbs rapidly through the y-intercept at $(0, 6.39)$, heading toward positive infinity.
*   **Placement:** The graph exists in all four quadrants but remains strictly above the "floor" at $y = -1$.
#### 6. Domain and Range
*   **Domain:** $(-\infty, \infty)$
*   **Range:** $(-1, \infty)$
### Graphing $g(x) = 5 - 2e^{-x+1}$ with Transformations

To apply the tracking technique effectively, we first rewrite the function in a more standard transformation form:  
$g(x) = -2e^{-(x-1)} + 5$

---
#### 1. Parent Function Identification
The parent function is $y = e^x$.
*   **Type:** Exponential Growth ($e \approx 2.72$).
*   **Parent Asymptote:** $y = 0$.
*   **Parent Key Points:** 
    *   $(-1, 1/e) \approx (-1, 0.37)$
    *   $(0, 1)$
    *   $(1, e) \approx (1, 2.72)$
#### 2. Sequence of Transformations
We track the changes from the "inside" out:
1.  **Horizontal Shift:** The $(x-1)$ indicates a shift **Right 1 unit**.
2.  **Horizontal Reflection:** The negative sign on the $x$ reflects the graph **over the y-axis** (turning growth into decay).
3.  **Vertical Stretch & Reflection:** The $-2$ coefficient **stretches the graph by 2** and reflects it **over the x-axis**.
4.  **Vertical Shift:** The $+5$ shifts the entire graph **Up 5 units**.
#### 3. New Horizontal Asymptote (HA)
The HA is determined by the vertical shift ($k$).
*   **New Asymptote:** $y = 5$
#### 4. Tracking Point Transformations
We apply the transformations to the parent points. Note: For the $x$-reflection and shift, we use the logic $-(x-1) = -x + 1$.

| Parent $(x, y)$ | $x \to -x+1$ | $y \to -2y+5$ | Final Transformed Point        |
| :-------------- | :----------- | :------------ | :----------------------------- |
| $(-1, 0.37)$    | $1+1 = 2$    | $-2(0.37)+5$  | **$(2, 4.26)$**                |
| $(0, 1)$        | $0+1 = 1$    | $-2(1)+5$     | **$(1, 3)$**                   |
| $(1, 2.72)$     | $-1+1 = 0$   | $-2(2.72)+5$  | **$(0, -0.44)$** (y-intercept) |

#### 5. Visual Description of the Graph
*   **Orientation:** Because of the double reflection (over both $x$ and $y$ axes), the graph looks like a growth curve that has been flipped upside down and mirrored.
*   **Left Side ($x \to -\infty$):** The graph dives steeply downward toward negative infinity.
*   **Right Side ($x \to \infty$):** The graph curves upward, passing through $(1, 3)$ and $(2, 4.26)$, eventually flattening out and approaching the horizontal asymptote at $y = 5$ from below.
*   **Intercepts:** It crosses the y-axis at approximately $(0, -0.44)$.
#### 6. Domain and Range
*   **Domain:** $(-\infty, \infty)$
*   **Range:** $(-\infty, 5)$
## 2026-May-12 - Solving Exponential Equations with Common Bases (Precalculus - College Algebra 54) :
https://www.youtube.com/watch?v=gkUWLFontZU&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=60
### Solving Exponential Equations with Common Bases

This summary covers the technique for solving exponential equations by utilizing the "One-to-One Property" of exponents. This method is used when both sides of an equation can be expressed using the same base.

---
#### 1. The One-to-One Property
The core logic used in these problems is the One-to-One Property of exponential functions:
> If $b^x = b^y$, then $x = y$ (where $b > 0$ and $b \neq 1$).

This allows us to "drop" the bases once they are identical and solve the resulting algebraic equation formed by the exponents.
#### 2. The General Procedure
To solve these equations, follow these four steps:
1.  **Identify a Common Base:** Look at the bases on both sides and determine if they are powers of the same number (e.g., 4 and 8 are both powers of 2).
2.  **Rewrite Both Sides:** Express each side of the equation using that common base.
3.  **Simplify Exponents:** Use the power-to-a-power rule: $(b^M)^N = b^{M \cdot N}$.
4.  **Set Exponents Equal:** Once you have $b^{expression1} = b^{expression2}$, set $expression1 = expression2$ and solve for the variable.
#### 3. Common Base Reference Table
Recognizing powers quickly is essential for this technique:

| Base | Powers to Recognize |
| :--- | :--- |
| **2** | $4, 8, 16, 32, 64, 128$ |
| **3** | $9, 27, 81, 243$ |
| **5** | $25, 125, 625$ |
| **10**| $10, 100, 1000$ |
#### 4. Handling Fractions and Roots
If the equation involves fractions or radicals, use the following exponent rules to find the common base:
*   **Fractions:** $\frac{1}{b^n} = b^{-n}$ (e.g., $\frac{1}{9} = 3^{-2}$)
*   **Radicals:** $\sqrt[n]{b^m} = b^{m/n}$ (e.g., $\sqrt{5} = 5^{1/2}$)
#### 5. Example Walkthrough
Solve: $9^{x+1} = 27^{x-1}$
1.  **Common Base:** Both 9 and 27 are powers of **3**.
2.  **Rewrite:** $(3^2)^{x+1} = (3^3)^{x-1}$
3.  **Simplify:** $3^{2(x+1)} = 3^{3(x-1)}$
4.  **Solve Exponents:** 
    $$2(x+1) = 3(x-1)$$
    $$2x + 2 = 3x - 3$$
    $$5 = x$$
#### 6. When This Method Fails
If the bases cannot be rewritten as powers of the same number (e.g., $2^x = 7$), this method cannot be used. In those cases, you must use **Logarithms** to pull the variable out of the exponent.

> [!CAUTION]
> **Distributive Property Warning:** When simplifying $(b^M)^N$, remember to distribute the $M$ to *every* term in $N$. A common error is writing $2(x+1)$ as $2x+1$ instead of $2x+2$.

### Solving $2^{-x} = 16$ Using Common Bases

Following the method demonstrated by Professor Leonard, we utilize the One-to-One Property of exponential functions to solve for the variable without the need for logarithms.

---
#### 1. Identify the Common Base
We look at both sides of the equation ($2$ and $16$) and determine if they can be written as powers of the same prime number.
*   The left side already has a base of **2**.
*   The right side, $16$, is a power of 2 ($2 \cdot 2 \cdot 2 \cdot 2 = 16$).
#### 2. Rewrite the Equation
Express both sides with the base of **2**:
$$2^{-x} = 2^4$$
#### 3. Apply the One-to-One Property
Since the bases are now identical ($b^M = b^N$), we can set the exponents equal to one another:
$$-x = 4$$
#### 4. Solve for $x$
Multiply or divide both sides by $-1$ to isolate the variable:
$$x = -4$$

---
#### 5. Verification
Plug the result back into the original equation to ensure the statement is true:
$$2^{-(-4)} = 16$$
$$2^4 = 16$$
$$16 = 16 \quad \checkmark$$

> [!NOTE]
> **Key Takeaway:** Always check if the larger number is a clean power of the smaller base. If the right side had been a fraction like $1/16$, we would have rewritten it as $2^{-4}$ before setting the exponents equal.

### Solving $2^{2x-1} = 4^{3x+1}$ Using Common Bases

This solution follows the step-by-step process of identifying a common base and applying the One-to-One Property of exponents.

---
#### 1. Identify the Common Base
We examine the bases on both sides of the equation, which are **2** and **4**. 
*   The number 4 can be rewritten as a power of 2 ($4 = 2^2$).
*   Therefore, the common base is **2**.
#### 2. Rewrite the Equation
Substitute $2^2$ in place of the 4. Use parentheses to ensure the exponent is handled correctly.
$$2^{2x-1} = (2^2)^{3x+1}$$
#### 3. Simplify the Exponents
Use the power-to-a-power rule, which states $(b^M)^N = b^{M \cdot N}$. We must distribute the 2 to both terms in the exponent $(3x + 1)$.
$$2^{2x-1} = 2^{2(3x+1)}$$
$$2^{2x-1} = 2^{6x+2}$$
#### 4. Apply the One-to-One Property
Now that the bases are identical, we set the exponents equal to each other:
$$2x - 1 = 6x + 2$$
#### 5. Solve for $x$
1.  **Group the $x$ terms:** Subtract $2x$ from both sides.
    $$-1 = 4x + 2$$
2.  **Isolate the $x$ term:** Subtract 2 from both sides.
    $$-3 = 4x$$
3.  **Final Division:**
    $$x = -\frac{3}{4}$$
---
#### 6. Verification
Checking the exponents by substituting $x = -0.75$:
*   **Left Exponent:** $2(-0.75) - 1 = -1.5 - 1 = -2.5$
*   **Right Exponent (after conversion):** $6(-0.75) + 2 = -4.5 + 2 = -2.5$
Since the exponents match when the bases are the same, the solution is correct.

> [!CAUTION]
> **Common Error:** Forgetting to distribute the new base's exponent. When rewriting $4^{3x+1}$ as $2^{2(3x+1)}$, ensure the 2 multiplies both the $3x$ and the $1$.
### Solving $25^{x+3} = \frac{1}{125}$ Using Common Bases

This solution follows the Leonard method of utilizing negative exponents to handle fractions and the One-to-One Property to solve for the variable.

---
#### 1. Identify the Common Base
We look at the bases 25 and 125.
*   25 is a power of 5 ($5^2$).
*   125 is a power of 5 ($5^3$).
*   Therefore, the common base for both sides is **5**.
#### 2. Rewrite the Equation
We must express both sides using the base of 5. For the fraction, we use the negative exponent rule: $\frac{1}{b^n} = b^{-n}$.
*   Left side: $(5^2)^{x+3}$
*   Right side: $\frac{1}{5^3} = 5^{-3}$

$$ (5^2)^{x+3} = 5^{-3} $$
#### 3. Simplify the Exponents
Apply the power-to-a-power rule on the left side by distributing the 2 to both terms in the exponent $(x + 3)$.
$$ 5^{2(x+3)} = 5^{-3} $$
$$ 5^{2x+6} = 5^{-3} $$
#### 4. Apply the One-to-One Property
Since the bases are now identical, we set the exponents equal to each other:
$$ 2x + 6 = -3 $$
#### 5. Solve for $x$
1.  **Isolate the $x$ term:** Subtract 6 from both sides.
    $$ 2x = -9 $$
2.  **Final Division:**
    $$ x = -\frac{9}{2} \text{ or } -4.5 $$
---
#### 6. Verification
Plug the result back into the simplified exponent form:
*   Left side: $2(-4.5) + 6 = -9 + 6 = -3$
*   Right side: $-3$
The exponents match, confirming the solution is correct.

> [!TIP]
> **Fraction Rule:** Whenever you see a fraction where the denominator is a clean power of your base, immediately think of **negative exponents**. It is the only way to get the base out of the denominator and onto the same level as the other side.

### Solving $9^{2x} \cdot 27^{x^2} = \frac{1}{3}$ Using Common Bases

This problem involves multiple terms on the left side. Following the Leonard method, we must first find a common base for all terms, simplify using exponent rules, and then apply the One-to-One Property.

---
#### 1. Identify the Common Base
Looking at 9, 27, and 3:
*   $9 = 3^2$
*   $27 = 3^3$
*   $3 = 3^1$
The common base is **3**.
#### 2. Rewrite the Equation
Substitute the base of 3 into every term. Use the negative exponent rule for the fraction: $\frac{1}{3} = 3^{-1}$.
$$(3^2)^{2x} \cdot (3^3)^{x^2} = 3^{-1}$$
#### 3. Simplify the Exponents
Apply the power-to-a-power rule $(b^M)^N = b^{M \cdot N}$:
$$3^{4x} \cdot 3^{3x^2} = 3^{-1}$$

Next, use the **Product Rule** for exponents ($b^M \cdot b^N = b^{M+N}$) to combine the terms on the left side into a single base:
$$3^{3x^2 + 4x} = 3^{-1}$$
#### 4. Apply the One-to-One Property
Now that the bases are identical, set the exponents equal to each other:
$$3x^2 + 4x = -1$$
#### 5. Solve the Resulting Quadratic Equation
To solve for $x$, set the quadratic equation to zero:
$$3x^2 + 4x + 1 = 0$$

Using the factoring method (or the quadratic formula):
1.  Find factors of $3 \cdot 1 = 3$ that add up to $4$. Those are $3$ and $1$.
2.  Rewrite and factor by grouping:
    $$3x^2 + 3x + 1x + 1 = 0$$
    $$3x(x + 1) + 1(x + 1) = 0$$
    $$(3x + 1)(x + 1) = 0$$
**Solve for each factor:**
*   $3x + 1 = 0 \implies \mathbf{x = -1/3}$
*   $x + 1 = 0 \implies \mathbf{x = -1}$

---
#### 6. Summary of Solutions
The equation $9^{2x} \cdot 27^{x^2} = \frac{1}{3}$ has two solutions:
$$x = -\frac{1}{3}, -1$$

> [!IMPORTANT]
> **Order of Operations:** You must combine the bases on the left side into a **single** term using the Product Rule *before* you can drop the bases. You cannot set exponents equal while there are still multiple bases being multiplied.

### Solving $3^{x^2} \cdot \frac{1}{3^7} = 27^{2x}$ Using Common Bases

This problem requires consolidating the left side into a single base using division and product rules before setting the exponents equal to the right side.

---
#### 1. Identify the Common Base
Scanning the terms 3 and 27:
*   The left side already utilizes the base **3**.
*   $27 = 3^3$.
The common base for the entire equation is **3**.
#### 2. Rewrite the Equation
Express all terms with the base of 3. Use the negative exponent rule for the fraction: $\frac{1}{3^7} = 3^{-7}$.
$$3^{x^2} \cdot 3^{-7} = (3^3)^{2x}$$
#### 3. Simplify the Exponents
Apply the **Product Rule** ($b^M \cdot b^N = b^{M+N}$) to the left side and the **Power Rule** ($(b^M)^N = b^{M \cdot N}$) to the right side:
$$3^{x^2 - 7} = 3^{6x}$$
#### 4. Apply the One-to-One Property
Since the bases are now identical and isolated on each side, we set the exponents equal to each other:
$$x^2 - 7 = 6x$$
#### 5. Solve the Resulting Quadratic Equation
Move all terms to one side to set the equation to zero:
$$x^2 - 6x - 7 = 0$$

Factor the quadratic by finding two numbers that multiply to $-7$ and add to $-6$:
*   The factors are $-7$ and $+1$.
$$(x - 7)(x + 1) = 0$$
**Solve for each factor:**
*   $x - 7 = 0 \implies \mathbf{x = 7}$
*   $x + 1 = 0 \implies \mathbf{x = -1}$
---
#### 6. Summary of Solutions
The equation $3^{x^2} \cdot \frac{1}{3^7} = 27^{2x}$ has two valid solutions:
$$x = 7, -1$$

> [!NOTE]
> **Refining the Left Side:** It is often easier to treat the fraction $\frac{1}{3^7}$ as a negative exponent ($3^{-7}$) and then add it to the other exponent on the left. This keeps everything on one line and prevents the need for a quotient step later.

### Solving $e^{x^2} = e^{3x} \cdot \frac{1}{e^2}$ Using Common Bases

This problem features the natural base $e$. Following the Leonard method, we simplify the right side of the equation into a single base before applying the One-to-One Property.

---
#### 1. Identify the Common Base
All terms in the equation are already expressed in terms of the natural base **$e$**.
*   Base: $e \approx 2.718$
#### 2. Rewrite the Equation
Express the fraction on the right side using a negative exponent so that all terms are on the same level:
$$e^{x^2} = e^{3x} \cdot e^{-2}$$
#### 3. Simplify the Exponents
Use the **Product Rule** for exponents ($b^M \cdot b^N = b^{M+N}$) to combine the terms on the right side:
$$e^{x^2} = e^{3x - 2}$$
#### 4. Apply the One-to-One Property
Since the bases are identical and isolated on each side, we drop the bases and set the exponents equal:
$$x^2 = 3x - 2$$
#### 5. Solve the Resulting Quadratic Equation
Move all terms to the left side to set the equation to zero:
$$x^2 - 3x + 2 = 0$$

Factor the quadratic by finding two numbers that multiply to $+2$ and add to $-3$:
*   The factors are $-2$ and $-1$.
$$(x - 2)(x - 1) = 0$$

**Solve for each factor:**
*   $x - 2 = 0 \implies \mathbf{x = 2}$
*   $x - 1 = 0 \implies \mathbf{x = 1}$

---
#### 6. Summary of Solutions
The equation $e^{x^2} = e^{3x} \cdot \frac{1}{e^2}$ has two solutions:
$$x = 2, 1$$

> [!TIP]
> **Working with $e$:** Treat $e$ exactly like any other numerical base (like 2 or 3). The same rules for multiplication, division, and powers apply. Don't let the irrational nature of $e$ distract you from the algebraic steps.

## 2026-May-14 - Introduction to Logarithms and Their Graphs (Precalculus - College Algebra 55) :
https://www.youtube.com/watch?v=jfnTwz79PWU&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=58
### Introduction to Logarithms and Their Graphs

This summary covers the definition of logarithms as inverse functions of exponentials and how to interpret, evaluate, and graph them using the Leonard technique.

---
#### 1. Definition of a Logarithm
A logarithm is the **inverse** of an exponential function. It answers the question: "To what power must we raise the base to get this number?"

> **The Logarithmic Equivalence:**
> $$y = \log_b(x) \iff b^y = x$$
> *(Where $b > 0$, $b \neq 1$, and $x > 0$)*

*   **$b$** is the **Base**.
*   **$y$** is the **Exponent**.
*   **$x$** is the **Argument** (or result).
#### 2. Logarithmic Forms and Bases
*   **Common Logarithm:** If no base is written, it is assumed to be base 10.
    *   $\log(x) = \log_{10}(x)$
*   **Natural Logarithm:** Logarithms using the natural base $e$ are written as $ln$.
    *   $\ln(x) = \log_e(x)$
#### 3. Evaluating Logarithms (The "Think" Method)
To evaluate $\log_2(8)$, convert it to its exponential heart:
1.  **Question:** $2$ to what power gives me $8$?
2.  **Equation:** $2^? = 8$
3.  **Result:** $2^3 = 8$, so $\log_2(8) = 3$.

#### 4. Parent Graph of $f(x) = \log_b(x)$
Because logarithms are inverses of exponentials, their graphs are reflections across the line $y = x$.

*   **Vertical Asymptote (VA):** $x = 0$ (the y-axis).
*   **Domain:** $(0, \infty)$ — You cannot take the log of a negative number or zero.
*   **Range:** $(-\infty, \infty)$
*   **Key Points (for $b > 1$):**
    *   $(1, 0)$ — The x-intercept (always 1 unless shifted).
    *   $(b, 1)$
    *   $(1/b, -1)$
#### 5. Graphing with Transformations
To graph a transformed log function like $f(x) = a \log_b(x-h) + k$:

1.  **Find the Vertical Asymptote:** Set the argument equal to zero: $x - h = 0 \implies x = h$.
2.  **Identify the Domain:** The argument must be positive: $x - h > 0$.
3.  **Track Key Points:** 
    *   Start with the parent points $(1, 0)$ and $(b, 1)$.
    *   Apply horizontal shifts to $x$ and vertical changes/shifts to $y$.
4.  **Determine Behavior:**
    *   As $x \to VA^+$, $y \to -\infty$ (or $\infty$ if reflected).
    *   As $x \to \infty$, $y \to \infty$ (grows very slowly).
#### 6. Important Properties to Remember
*   **$\log_b(1) = 0$** (Because $b^0 = 1$)
*   **$\log_b(b) = 1$** (Because $b^1 = b$)
*   **$\log_b(b^x) = x$** (Inverse property)
*   **$b^{\log_b(x)} = x$** (Inverse property)

> [!IMPORTANT]
> **The Domain Constraint:** Unlike exponential functions which have a domain of all real numbers, logarithms are restricted. The "inside" (argument) of a log must ALWAYS be greater than zero. This dictates where your graph can and cannot exist.

### Converting Exponential Equations to Logarithmic Form

Following the logarithmic equivalence rule: $b^y = x \iff \log_b(x) = y$.

---
#### Exponential to Logarithmic Conversion

| Exponential Form | Logarithmic Form | Notes |
| :--- | :--- | :--- |
| $9 = 3^2$ | **$\log_3(9) = 2$** | Base is 3, exponent is 2. |
| $a^3 = 2.1$ | **$\log_a(2.1) = 3$** | Base is $a$, exponent is 3. |
| $2^x = 7.2$ | **$\log_2(7.2) = x$** | Base is 2, exponent is $x$. |
| $10^x = 2.3$ | **$\log(2.3) = x$** | Base 10 is the **Common Log**. |
| $e^x = 8$ | **$\ln(8) = x$** | Base $e$ is the **Natural Log**. |

---
#### Key Reminders for Your Notes
*   **Common Log ($\log$):** When the base is 10, we omit the subscript.
*   **Natural Log ($\ln$):** When the base is $e$, we use "ln" instead of "$\log_e$".
*   **The "Heart" Method:** The base of the exponent always remains the base of the log. The exponent and the result "switch" sides.
### Converting Logarithmic Equations to Exponential Form

Following the logarithmic equivalence rule: $\log_b(x) = y \iff b^y = x$.

---
#### Logarithmic to Exponential Conversion

| Logarithmic Form | Exponential Form | Notes |
| :--- | :--- | :--- |
| $\log_3(\frac{1}{9}) = -2$ | **$3^{-2} = \frac{1}{9}$** | Base is 3, exponent is -2. |
| $\log_b(4) = 2$ | **$b^2 = 4$** | Base is $b$, exponent is 2. |
| $\log_2(6) = x$ | **$2^x = 6$** | Base is 2, exponent is $x$. |
| $\ln(4) = x$ | **$e^x = 4$** | "ln" implies the natural base **$e$**. |
| $\log(x) = 3$ | **$10^3 = x$** | "log" with no base implies base **10**. |

---
#### Key Reminders for Your Notes
*   **The Circular Motion:** To convert, take the **base**, move across the equal sign to find your **exponent**, and set it equal to the **argument**.
*   **Invisible Bases:** 
    *   $\ln \implies e$
    *   $\log \implies 10$
*   **Identity Check:** For $10^3 = x$, you can quickly solve that $x = 1000$.

### Evaluating Logarithmic Expressions

To solve these, we set each expression equal to $x$ and convert them into their exponential form: $b^x = \text{argument}$.

---
#### 1. $\log_5 25 = x$
*   **Exponential Form:** $5^x = 25$
*   **Solve:** Since $5^2 = 25$
*   **Result:** **$x = 2$**
#### 2. $\log_{1/3} 9 = x$
*   **Exponential Form:** $(\frac{1}{3})^x = 9$
*   **Common Base (3):** $(3^{-1})^x = 3^2 \implies 3^{-x} = 3^2$
*   **Result:** **$x = -2$**
#### 3. $\log \sqrt{10} = x$
*   **Note:** No base written implies common log (base 10).
*   **Exponential Form:** $10^x = \sqrt{10}$
*   **Rewrite Radical:** $10^x = 10^{1/2}$
*   **Result:** **$x = 1/2$**
#### 4. $\log_5 \sqrt[3]{25} = x$
*   **Exponential Form:** $5^x = \sqrt[3]{25}$
*   **Rewrite Right Side:** $5^x = (25)^{1/3} \implies 5^x = (5^2)^{1/3}$
*   **Simplify:** $5^x = 5^{2/3}$
*   **Result:** **$x = 2/3$**
#### 5. $\log_{\sqrt{3}} 9 = x$
*   **Exponential Form:** $(\sqrt{3})^x = 9$
*   **Common Base (3):** $(3^{1/2})^x = 3^2$
*   **Simplify:** $3^{x/2} = 3^2$
*   **Solve:** $\frac{x}{2} = 2 \implies x = 4$
*   **Result:** **$x = 4$**
#### 6. $\ln e^3 = x$
*   **Note:** $\ln$ is base $e$.
*   **Exponential Form:** $e^x = e^3$
*   **Result:** **$x = 3$** (Inverse Property: $\ln e^a = a$)
#### 7. $\log_2 1 = x$
*   **Exponential Form:** $2^x = 1$
*   **Solve:** Any non-zero base raised to the power of 0 equals 1.
*   **Result:** **$x = 0$**
---
> [!TIP]
> **The Radical Shortcut:** When dealing with roots in logs, remember the fractional exponent rule: $\sqrt[root]{base^{power}} = base^{power/root}$. This often allows you to see the answer immediately once the bases match.

### Finding the Domain of $f(x) = \ln(x-3)$

This analysis identifies the set of all possible input values for a natural logarithmic function by applying the logarithmic constraint.

---
#### 1. The Logarithmic Constraint
For any logarithmic function $y = \log_b(u)$, the **argument** ($u$) must be strictly greater than zero. Logarithms are not defined for zero or negative numbers.
*   **Rule:** $\text{Argument} > 0$
#### 2. Set Up the Inequality
Identify the argument of the function $f(x) = \ln(x-3)$, which is $(x-3)$.
$$x - 3 > 0$$
#### 3. Solve for $x$
Add 3 to both sides of the inequality:
$$x > 3$$
#### 4. Final Domain Notation
The domain consists of all real numbers greater than 3.

*   **Inequality Notation:** $\{x \mid x > 3\}$
*   **Interval Notation:** $(3, \infty)$
*   **Set Notation:** $x \in (3, \infty)$

---
#### 5. Visual Context for the Graph
*   **Vertical Asymptote (VA):** The boundary of the domain occurs where the argument equals zero.
    *   $x - 3 = 0 \implies \mathbf{x = 3}$
*   **Graph Placement:** Because $x$ must be greater than 3, the graph will only exist to the **right** of the vertical line $x = 3$.

> [!CAUTION]
> **Common Error:** Do not include the boundary point. Because $\ln(0)$ is undefined (the graph approaches the asymptote but never touches it), the interval must use a parenthesis `(` rather than a bracket `[`.
> 
### Finding the Domain of $g(x) = 3-2\log_4[5-\frac{x}{2}]$

To find the domain of any logarithmic function, we focus exclusively on the **argument**. Transformations outside the log (the $3$, the $-2$, and the base $4$) affect the range and the shape of the graph, but they do not change the domain constraints.

---
#### 1. The Logarithmic Constraint
The argument of a logarithm must always be strictly greater than zero.
*   **Rule:** $\text{Argument} > 0$
#### 2. Set Up the Inequality
Identify the argument inside the brackets for the function $g(x)$:
$$5 - \frac{x}{2} > 0$$
#### 3. Solve for $x$
We isolate $x$ using standard algebraic steps. **Note:** Remember that multiplying or dividing an inequality by a negative number flips the inequality sign.

1.  **Subtract 5 from both sides:**
    $$-\frac{x}{2} > -5$$

2.  **Multiply both sides by -2:**
    *   Since we are multiplying by a negative number, the sign flips from $>$ to $<$.
    $$x < 10$$
#### 4. Final Domain Notation
The domain consists of all real numbers less than 10.

*   **Inequality Notation:** $\{x \mid x < 10\}$
*   **Interval Notation:** $(-\infty, 10)$

---
#### 5. Visual Context for the Graph
*   **Vertical Asymptote (VA):** The boundary occurs where the argument is exactly zero.
    *   $5 - \frac{x}{2} = 0 \implies x = 10$.
*   **Graph Direction:** Because the domain is $x < 10$, the graph exists only to the **left** of the vertical asymptote.
*   **Reflections:** The negative sign inside the argument ($-\frac{x}{2}$) is what caused the horizontal reflection, forcing the graph to point toward negative infinity instead of positive infinity.

> [!IMPORTANT]
> **Inequality Flip:** A common mistake in this specific problem is forgetting to flip the inequality sign when multiplying by $-2$. If the sign isn't flipped, the domain would incorrectly suggest the graph exists to the right of 10.

### Finding the Domain of $h(x) = \log_5 \left[\frac{x+1}{x}\right]$

Finding the domain for this function requires solving a rational inequality. We must ensure the entire argument inside the logarithm is strictly positive.

---
#### 1. The Logarithmic Constraint
The argument of any logarithm must be greater than zero.
*   **Condition:** $\frac{x+1}{x} > 0$
#### 2. Identify Critical Values
To solve the rational inequality, we find the values where the expression is either zero or undefined (the "boundary points").
*   **Numerator = 0:** $x + 1 = 0 \implies \mathbf{x = -1}$
*   **Denominator = 0:** $\mathbf{x = 0}$
#### 3. Sign Analysis (Test Intervals)
We test the sign of the fraction $\frac{x+1}{x}$ in the three intervals created by our critical values: $(-\infty, -1)$, $(-1, 0)$, and $(0, \infty)$.

| Interval | Test Value | Calculation | Sign | Result |
| :--- | :--- | :--- | :--- | :--- |
| $(-\infty, -1)$ | $x = -2$ | $\frac{-2+1}{-2} = \frac{-1}{-2}$ | **Positive (+)** | **Keep** |
| $(-1, 0)$ | $x = -0.5$ | $\frac{-0.5+1}{-0.5} = \frac{0.5}{-0.5}$ | **Negative (-)** | **Discard** |
| $(0, \infty)$ | $x = 1$ | $\frac{1+1}{1} = \frac{2}{1}$ | **Positive (+)** | **Keep** |
#### 4. Final Domain Notation
The domain consists of the intervals where the expression resulted in a positive value. We use parentheses because the argument cannot equal zero, and the function is undefined at $x=0$.

*   **Inequality Notation:** $x < -1$ or $x > 0$
*   **Interval Notation:** $(-\infty, -1) \cup (0, \infty)$

---
#### 5. Visual Context for the Graph
*   **Vertical Asymptotes:** This graph has **two** vertical asymptotes at $x = -1$ and $x = 0$.
*   **Gap in Graph:** There is a "hole" or gap in the middle of the graph between $-1$ and $0$ where the function does not exist.
*   **Behavior:** As $x$ approaches $-1$ from the left, the argument approaches zero, meaning the log will dive toward $-\infty$. As $x$ approaches $0$ from the right, the argument approaches $+\infty$.

> [!CAUTION]
> **Denominator Constraint:** Even if the logarithm wasn't there, $x$ could never be $0$ because division by zero is undefined. Always check for values that make the denominator zero in rational arguments.

## 2026-May-15 - Graphing Logarithms with Transformations (Precalculus - College Algebra 56) :
https://www.youtube.com/watch?v=swC7KrDO0Uo&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=57
### Graphing Logarithms with Transformations

This summary outlines the systematically structured approach used by Professor Leonard to graph logarithmic functions by evaluating the vertical asymptote, finding the domain, and tracking key tracking points through transformations.

---
#### 1. The Transformed Log Equation Template
$$f(x) = a \log_b(c(x - h)) + k$$

*   **Vertical Asymptote (VA):** Shifted by $h$. Found by setting the argument inside the log equal to zero.
*   **Horizontal Reflection:** Occurs if $c$ is negative (graph faces left).
*   **Vertical Reflection:** Occurs if $a$ is negative (graph flips upside down).
*   **Vertical Shift:** Shifted up or down by $k$.
#### 2. The Step-by-Step Graphing Method
Instead of plotting random points, look for structural anchor points and boundaries:

1.  **Find and Sketch the Vertical Asymptote:** Set the inner argument equal to zero and solve for $x$. Draw this as a dashed vertical line.
2.  **Determine the Domain:** Set the inner argument $> 0$ and solve. This tells you which side of the asymptote to draw your graph.
3.  **Identify the Parent Points:** Start with the standard un-transformed points for $\log_b(x)$:
    *   Anchor Point 1: $(1, 0)$  *(Because $\log_b(1) = 0$)*
    *   Anchor Point 2: $(b, 1)$  *(Because $\log_b(b) = 1$)*
4.  **Transform the Points:** Apply the horizontal transformations to the x-coordinates and vertical transformations to the y-coordinates.
5.  **Sketch the Curve:** Draw the curve passing through the transformed anchor points, ensuring it runs parallel to the vertical asymptote on the correct side.
#### 3. Anchor Points Tracking Table
When evaluating transformations manually or via point-tracking:

| Parent Coordinate | Horizontal Effect ($x$) | Vertical Effect ($y$) |
| :--- | :--- | :--- |
| **$(1, 0)$** | Divide by $c$, add $h$ | Multiply by $a$, add $k$ |
| **$(b, 1)$** | Divide by $c$, add $h$ | Multiply by $a$, add $k$ |
#### 4. Behavior Near the Asymptote
*   Log graphs grow extremely slowly as $x \to \infty$.
*   Log graphs plummet toward $-\infty$ (or climb to $+\infty$ if vertically reflected) as they get closer and closer to the vertical asymptote.

---
#### 5. Example Blueprint Analysis
Graphing $f(x) = -\log_2(x + 3) + 1$:

1.  **Asymptote:** $x + 3 = 0 \implies \mathbf{x = -3}$
2.  **Domain:** $x + 3 > 0 \implies \mathbf{x > -3}$ (Graph is to the right of $-3$)
3.  **Parent Points (Base 2):** $(1, 0)$ and $(2, 1)$
4.  **Apply Shifts:**
    *   Horizontal: Shift left by 3 ($x - 3$)
    *   Vertical: Multiply by $-1$, then add 1 ($-y + 1$)
5.  **Transformed Points:**
    *   $(1, 0) \to (1-3, -0+1) \to \mathbf{(-2, 1)}$
    *   $(2, 1) \to (2-3, -1+1) \to \mathbf{(-1, 0)}$

---

> [!TIP]
> **The X-Intercept Clue:** The parent point $(1,0)$ is highly valuable because whatever makes the argument of the log equal to $1$ will yield an easy integer value for $y$, making it the cleanest point to plot after transformations.

### Graphing $f(x) = 2 + \ln(x-1)$ with Transformations

This entry details the step-by-step structural breakdown and visual behavior of the transformed natural log function.

---
#### 1. Parent Function & Core Identity
*   **Parent Function:** $y = \ln(x)$ (Logarithm with the natural base $e \approx 2.718$)
*   **Standard Un-transformed Shape:** A curve starting near a vertical asymptote at $x=0$, passing through $(1,0)$ and $(e,1)$, and flattening out as it moves right.

#### 2. Identification of Transformations
Rewriting the equation to align with standard transformation templates makes the modifications clear:  
$$f(x) = \ln(x-1) + 2$$

*   **Horizontal Shift (Inside the Argument):** The $-1$ inside the argument shifts the entire graph **right by 1 unit**.
*   **Vertical Shift (Outside the Log):** The $+2$ added to the function shifts the entire graph **up by 2 units**.
*   **Reflections/Stretches:** There are no negative signs or coefficients, meaning there are no reflections or scaling adjustments.
#### 3. Domain and Asymptote Analysis
*   **Vertical Asymptote (VA):** Set the argument to zero.
    $$x - 1 = 0 \implies \mathbf{x = 1}$$
*   **Domain:** Set the argument greater than zero.
    $$x - 1 > 0 \implies \mathbf{x > 1 \quad \text{or} \quad (1, \infty)}$$
#### 4. Tracking Key Anchor Points
We apply the identified shifts (**Add 1 to $x$**, **Add 2 to $y$**) to the parent points of base $e$:

1.  **The Intercept Pivot Point:**
    *   Parent: $(1, 0)$
    *   Transformed: $(1 + 1, \, 0 + 2) \to \mathbf{(2, 2)}$
2.  **The Base Point:**
    *   Parent: $(e, 1) \approx (2.718, 1)$
    *   Transformed: $(e + 1, \, 1 + 2) \to \mathbf{(e+1, 3)} \approx \mathbf{(3.718, 3)}$

---
#### 5. What the Graph Looks Like
*   **Boundary Line:** There is a vertical dashed line (asymptote) passing through $x = 1$. The graph only exists to the right side of this boundary line.
*   **Behavior near the asymptote:** As you follow the graph left toward $x = 1$, the curve plunges downward vertically toward negative infinity ($-\infty$).
*   **Curve Behavior:** Moving right from the asymptote, the curve climbs through the anchor point $(2,2)$. Because the domain is restricted to $x > 1$, this graph never crosses the y-axis, meaning it has no y-intercept.
*   **Long-Term Growth:** As $x$ increases toward positive infinity ($+\infty$), the graph continues to rise. Consistent with all logarithmic curves, the rate of upward growth slows down dramatically, creating a long, flattened trajectory as it extends to the right.
### Graphing $g(x) = 3 - 2\log_3(x+1)$ with Transformations

This entry details the step-by-step structural breakdown, point adjustments, and visual trajectory of a base-3 logarithmic function with multiple transformations.

---
#### 1. Parent Function & Core Identity
*   **Parent Function:** $y = \log_3(x)$
*   **Standard Un-transformed Shape:** Steady upward curve starting near a vertical asymptote at $x=0$, passing through $(1,0)$ and $(3,1)$.
#### 2. Identification of Transformations
Rewriting the equation to match standard graphing formats highlights the exact order of operations:  
$$g(x) = -2\log_3(x+1) + 3$$

*   **Horizontal Shift:** The $+1$ inside the argument shifts the graph **left by 1 unit**.
*   **Vertical Reflection:** The negative sign on the $-2$ reflects the graph **vertically across the x-axis** (it flips upside down).
*   **Vertical Stretch:** The scalar value of $2$ stretches the graph vertically by a **factor of 2**.
*   **Vertical Shift:** The $+3$ shifts the entire graph **up by 3 units**.
#### 3. Domain and Asymptote Analysis
*   **Vertical Asymptote (VA):** Set the argument to zero.
    $$x + 1 = 0 \implies \mathbf{x = -1}$$
*   **Domain:** Set the argument greater than zero.
    $$x + 1 > 0 \implies \mathbf{x > -1 \quad \text{or} \quad (-1, \infty)}$$
#### 4. Tracking Key Anchor Points
We apply the horizontal changes (**Subtract 1 from $x$**) and vertical changes (**Multiply $y$ by $-2$, then add 3**) to the parent points of base 3:

1.  **The Intercept Pivot Point:**
    *   Parent: $(1, 0)$
    *   Transformed: $(1 - 1, \, [0 \cdot -2] + 3) \to \mathbf{(0, 3)}$ *(This forms your y-intercept)*
2.  **The Base Point:**
    *   Parent: $(3, 1)$
    *   Transformed: $(3 - 1, \, [1 \cdot -2] + 3) \to (2, \, -2 + 3) \to \mathbf{(2, 1)}$

---
#### 5. What the Graph Looks Like
*   **Boundary Line:** A vertical dashed line (asymptote) stands at $x = -1$. The curve only exists to the right of this line.
*   **Behavior near the asymptote:** Unlike a normal log curve that dives downward, the vertical reflection causes this graph to climb upward toward **positive infinity ($+\infty$)** as it approaches $x = -1$ from the right.
*   **Curve Behavior:** Moving to the right from the asymptote, the curve drops down, passing cleanly through the y-axis at $(0,3)$, and continues downward through $(2,1)$.
*   **Long-Term Growth:** As $x$ heads toward positive infinity ($+\infty$), the graph continuously sinks lower and lower into negative territory. Due to the vertical stretch, it drops more sharply than a typical log graph, but it still eventually flattens out into a slow, gradual downward slope toward negative infinity ($-\infty$).
## 2026-May-16 - Introduction to Solving Logarithms and Exponentials (Precalculus - College Algebra 57) :
https://www.youtube.com/watch?v=KezbqAAlOZk&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=60
### Introduction to Solving Logarithms and Exponentials

This summary outlines the foundational strategies taught by Professor Leonard for solving algebraic equations involving exponents and logarithms. The core philosophy centers around using inverse operations to isolate variables.

---
#### 1. Core Principles of Solving
The fundamental concept depends on the inverse relationship between exponential functions and logarithmic functions:
*   To undo an **exponential**, use a **logarithm**.
*   To undo a **logarithm**, use an **exponential**.
#### 2. The Two Primary Toolsets
Professor Leonard breaks down solving into two algebraic pathways:
##### Pathway A: The One-to-One Property
If you can make both sides of the equation share the exact same base, you can drop the bases entirely.
*   **Exponential Property:** $b^M = b^N \implies M = N$
*   **Logarithmic Property:** $\log_b(M) = \log_b(N) \implies M = N$
##### Pathway B: Definition Conversion (The Rewrite)
If you cannot easily obtain identical bases on both sides, change the operational form using the equivalence relation: 
$$\log_b(x) = y \iff b^y = x$$

---
#### 3. Solving Exponential Equations
When the variable is trapped in the exponent position, apply these steps:

1.  **Isolate the Exponential Term:** Clean up the equation so only the base and its exponent remain on one side (e.g., $b^x = \text{value}$).
2.  **Determine if Bases Match:**
    *   *If they match:* Use common bases to set the exponents equal.
    *   *If they do not match:* Convert the equation into a logarithm.
3.  **Solve for $x$:** Complete the remaining linear or quadratic algebra.
> **Example (Conversion Method):** Solve $5^x = 12$
> *   Isolate check: Complete.
> *   Bases match check: No easy common base between 5 and 12.
> *   Convert to Log: $\log_5(12) = x$
#### 4. Solving Logarithmic Equations
When the variable is trapped inside the argument of a logarithm, apply these steps:

1.  **Isolate the Logarithmic Term:** Clean up multipliers or added numbers surrounding the log until you have $\log_b(\text{argument}) = \text{value}$.
2.  **Convert to Exponential Form:** Use the "circular motion" method to raise the base to the power of the opposite side.
3.  **Solve for $x$:** Finish the algebra.
4.  **Check for Extraneous Solutions:** You **must** plug your answers back into the original equation to ensure the arguments remain strictly positive ($> 0$).
---
#### 5. Crucial Mechanics & Pitfalls

> [!WARNING]
> **Isolation Is Required First:** You cannot drop bases or convert forms if there are loose coefficients standing in front of your terms. For example, in $2 \cdot 3^x = 18$, you *must* divide by 2 to get $3^x = 9$ before processing the exponent.

> [!IMPORTANT]
> **Extraneous Solution Checks:** Exponential functions have a domain of all real numbers, meaning their solutions are naturally safe. Logarithmic functions have restricted domains. If your algebraic solution results in evaluating something like $\log(-5)$ or $\log(0)$, that solution is invalid and must be discarded.

### Solving $\log_2(2x+1) = 3$ via Exponential Conversion

This problem is solved by using the definition of a logarithm to rewrite the expression in its inverse exponential form, breaking the variable out of the argument.

---

#### Step-by-Step Solution

##### Step 1: Check for Isolation
Before converting forms, the logarithmic term must be completely isolated on one side of the equation. 
*   **Analysis:** The left side contains only $\log_2(2x+1)$. There are no numbers multiplied in front of the log or added outside of it. Isolation is complete.
##### Step 2: Convert to Exponential Form
Apply the logarithmic equivalence rule: $\log_b(x) = y \iff b^y = x$. 
*   **Action:** Take the base (**2**), raise it to the power of the right side (**3**), and set it equal to the inside argument (**$2x+1$**).
$$2^3 = 2x + 1$$
*   *Why we do this:* This removes the logarithm operation entirely, shifting the variable from a locked argument down into a standard linear equation.
##### Step 3: Evaluate the Numerical Power
Simplify the exponential side.
*   **Action:** Calculate $2^3$, which is $2 \cdot 2 \cdot 2 = 8$.
$$8 = 2x + 1$$
##### Step 4: Isolate and Solve for $x$
Perform standard linear algebra to isolate the variable.
1.  Subtract 1 from both sides:
    $$7 = 2x$$
2.  Divide both sides by 2:
    $$x = \frac{7}{2}$$

---
#### Step 5: Check for Extraneous Solutions
Logarithmic arguments must always be strictly greater than zero ($>0$). We must test $x = \frac{7}{2}$ in the original argument.

*   **Argument Check:**
    $$2x + 1 \to 2\left(\frac{7}{2}\right) + 1 = 7 + 1 = 8$$
*   **Conclusion:** Since $8$ is greater than zero, the argument is valid. 

---
#### Final Solution
$$x = \frac{7}{2}$$

> [!NOTE]
> **The Conversion Goal:** Converting to an exponential is the most direct tool when you have a single logarithm equal to a constant number. It immediately changes a calculus/pre-calculus problem into basic algebra.

### Solving $\log_3(x^2+1) = 2$ via Exponential Conversion

This problem utilizes exponential conversion to extract a quadratic expression from inside a base-3 logarithm.

---

#### Step-by-Step Solution

##### Step 1: Check for Isolation
The logarithmic expression must be isolated before changing forms.
*   **Analysis:** The term $\log_3(x^2+1)$ stands alone on the left-hand side. There are no external coefficients or constant terms to move. Isolation is complete.
##### Step 2: Convert to Exponential Form
Apply the definition of a logarithm to rewrite the equation: $\log_b(x) = y \iff b^y = x$.
*   **Action:** Take the base (**3**), raise it to the power of the right side (**2**), and set it equal to the inner quadratic argument (**$x^2+1$**).
$$3^2 = x^2 + 1$$
*   *Why we do this:* This inverse operation eliminates the log function, leaving behind a standard quadratic equation that can be evaluated using standard algebraic methods.
##### Step 3: Evaluate the Constant Power
Simplify the numerical exponent.
*   **Action:** Calculate $3^2$, which is $9$.
$$9 = x^2 + 1$$

##### Step 4: Solve the Quadratic Equation
Since this quadratic equation contains an $x^2$ term but no linear $x$ term, the most efficient method is using the **Square Root Property**.

1.  Isolate the $x^2$ term by subtracting 1 from both sides:
    $$8 = x^2$$
2.  Take the square root of both sides. Remember to include both the positive and negative roots ($\pm$):
    $$x = \pm\sqrt{8}$$
3.  Simplify the radical by factoring out the perfect square ($4 \cdot 2$):
    $$x = \pm2\sqrt{2}$$

---
#### Step 5: Check for Extraneous Solutions
We must verify that substituting our values back into the original argument ($x^2 + 1$) yields a result strictly greater than zero.

*   **Argument Check:**
    $$\left(\pm2\sqrt{2}\right)^2 + 1 = 8 + 1 = 9$$
*   **Conclusion:** Since $9 > 0$, both the positive and negative values are valid solutions.

---
#### Final Solutions
$$x = 2\sqrt{2}, \quad x = -2\sqrt{2}$$

> [!TIP]
> **The Even Power Advantage:** Because the variable inside the log argument is squared ($x^2$), any negative solution we plug back in automatically becomes positive during the checking step. This makes it highly unlikely for solutions to be extraneous in this specific setup, though checking remains mandatory.

### Solving $\ln(-2x+1) = 8$ via Exponential Conversion

This entry shows how to clear a natural log ($\ln$) using its inverse base $e$ exponential to solve for a variable embedded in a linear expression.

---
#### Step-by-Step Solution

##### Step 1: Check for Isolation
The natural log term must stand alone before rewriting the equation.
*   **Analysis:** The expression $\ln(-2x+1)$ is isolated on the left side. No extra numbers are added or multiplied outside the parenthesis. Isolation is complete.
##### Step 2: Convert to Exponential Form
Apply the log equivalence identity, keeping in mind that the natural log ($\ln$) has an invisible base of $e \approx 2.718$.
*   **Action:** Rewrite the expression by raising base **$e$** to the power of the right side (**8**), and set it equal to the inner argument (**$-2x+1$**).
$$e^8 = -2x + 1$$
*   *Why we do this:* Raising base $e$ to a log of base $e$ completely cancels the log operation, unlocking the inner expression so the variable can be isolated.
##### Step 3: Handle the Exact Value Constant
Unlike integer bases, $e^8$ is an irrational, transcendental number.
*   **Action:** Leave $e^8$ written exactly as it is. Treat it as a single constant number throughout the rest of your algebraic steps to maintain an exact answer.
##### Step 4: Isolate and Solve for $x$
Perform standard linear steps to isolate $x$:

1.  Subtract 1 from both sides:
    $$e^8 - 1 = -2x$$
2.  Divide both sides by -2 to isolate $x$:
    $$x = \frac{e^8 - 1}{-2}$$
3.  Clean up the fraction by distributing the negative sign to the numerator (optional but mathematically clean):
    $$x = \frac{1 - e^8}{2}$$

---
#### Step 5: Check for Extraneous Solutions
We must verify that our solution keeps the original argument ($-2x + 1$) strictly positive.

*   **Argument Check:** Substitute $x = \frac{1 - e^8}{2}$ back into the argument:
    $$-2\left(\frac{1 - e^8}{2}\right) + 1$$
*   The $2$ and $-2$ simplify, leaving a negative multiplier for the numerator:
    $$-(1 - e^8) + 1 \implies -1 + e^8 + 1 \implies e^8$$
*   **Conclusion:** Since $e^8 \approx 2980.96$, which is clearly greater than zero, the solution is valid.

---
#### Final Exact Solution
$$x = \frac{1 - e^8}{2}$$

> [!IMPORTANT]
> **Exact vs. Approximate:** In college algebra and pre-calculus, always leave your answer in terms of $e$ unless explicitly asked for a decimal approximation. $\frac{1 - e^8}{2}$ is the exact value; evaluating it as $\approx -1489.98$ is an approximation.
### Solving $\ln e^{2x} = 8$ via Inverse Properties

While this problem can be completed by converting to exponential form, it also highlights an essential inverse identity where a base $e$ logarithm meets a base $e$ exponent. Both approaches yield the same step-by-step logic.

---
#### Step-by-Step Solution

##### Step 1: Check for Isolation
The natural log term must be completely isolated on its side of the equation.
*   **Analysis:** The left side contains only $\ln e^{2x}$. There are no outside numbers added or multiplied. Isolation is complete.
##### Step 2: Convert to Exponential Form
Recall that the natural log ($\ln$) represents a logarithm with an unwritten base of $e$. Apply the equivalence rule: $\log_b(x) = y \iff b^y = x$.
*   **Action:** Take the invisible base **$e$**, raise it to the power of the right side (**8**), and set it equal to the inner argument (**$e^{2x}$**).
$$e^8 = e^{2x}$$
*   *Why we do this:* Rewriting the statement transforms the logarithmic equation into an exponential equation where both sides share an identical base.
##### Step 3: Apply the One-to-One Property
When both sides of an equation share the exact same base, their exponents must be equal.
*   **Identity Rule:** $b^M = b^N \implies M = N$
*   **Action:** Drop the matching bases ($e$) and set the exponents equal to each other.
$$8 = 2x$$

---
#### Alternative Method: Direct Inverse Property
Professor Leonard frequently emphasizes recognizing inverse pairings immediately to save steps. 
*   Because $\ln(x)$ and $e^x$ are exact inverses, they undo each other when nested: $\ln(e^{\square}) = \square$.
*   Applying this directly to the original equation:
    $$\ln e^{2x} = 8 \implies 2x = 8$$
*   Both methods lead directly to the same simplified linear equation.

---
##### Step 4: Solve for $x$
Divide both sides of the linear equation by 2 to isolate the variable.
$$x = \frac{8}{2}$$
$$x = 4$$
##### Step 5: Check for Extraneous Solutions
We test $x = 4$ back inside the original argument ($e^{2x}$).
*   **Argument Check:** $e^{2(4)} = e^8$
*   **Conclusion:** Base $e$ raised to any real power is always strictly positive ($e^8 > 0$). The solution is valid.

---
#### Final Solution
$$x = 4$$
### Solving $\log_6 36 = 5x + 4$ via Exponential Conversion

This problem is unique because the variable $x$ is located completely outside of the logarithm. While you could simplify the left side directly, converting the equation to exponential form handles the log systematically.

---
#### Step-by-Step Solution

##### Step 1: Check for Isolation
The logarithm term must be isolated on one side of the equation.
*   **Analysis:** The left side consists entirely of $\log_6 36$. No outside multipliers or constant terms are attached to it. Isolation is complete.
##### Step 2: Convert to Exponential Form
Apply the standard logarithmic definition: $\log_b(x) = y \iff b^y = x$.
*   **Action:** Take the base (**6**), raise it to the power of the entire expression on the right side (**$5x+4$**), and set it equal to the inner argument (**36**).
$$6^{5x+4} = 36$$
*   *Why we do this:* This process eliminates the logarithm function, transforming the expression into an exponential equation where the terms can be rewritten to share a common base.
##### Step 3: Utilize the One-to-One Property (Match Bases)
To solve an exponential equation, attempt to write both sides using the exact same base so the exponents can be set equal.
1.  **Analyze the bases:** The left-hand base is 6. The right-hand number is 36.
2.  **Rewrite 36:** Recognize that $36 = 6^2$. Substitute this value back into the equation:
    $$6^{5x+4} = 6^2$$

##### Step 4: Drop the Bases and Solve for $x$
Since both sides have a matching base of 6, apply the property $b^M = b^N \implies M = N$.
1.  Set the exponents equal to each other:
    $$5x + 4 = 2$$
2.  Subtract 4 from both sides to isolate the variable term:
    $$5x = -2$$
3.  Divide both sides by 5:
    $$x = -\frac{2}{5}$$

---
#### Alternative Method: Direct Evaluation First
Professor Leonard often notes that if the logarithm contains purely numbers, you can evaluate it immediately before doing any algebra:
1.  $\log_6 36$ asks the question: *"6 raised to what power equals 36?"*
2.  Since $6^2 = 36$, then $\log_6 36 = 2$.
3.  Substitute 2 back into the equation: $2 = 5x + 4$.
4.  Solving this yields the exact same linear steps: $5x = -2 \implies x = -\frac{2}{5}$.

---
##### Step 5: Check for Extraneous Solutions
Because the variable $x$ was outside the logarithm's argument from the start, there is no risk of creating a zero or negative argument within the original expression. The argument remains a constant $36$, which is always valid.

---
#### Final Solution
$$x = -\frac{2}{5}$$
### Solving $\log_x\left(\frac{1}{8}\right) = 3$ via Exponential Conversion

In this problem, the variable is located in the **base** position of the logarithm. Converting it to exponential form is the standard way to isolate a base variable.

---
#### Step-by-Step Solution

##### Step 1: Check for Isolation
The logarithmic term must be fully isolated on one side of the equation.
*   **Analysis:** The left side contains only $\log_x\left(\frac{1}{8}\right)$. There are no external coefficients or constant terms to move. Isolation is complete.
##### Step 2: Convert to Exponential Form
Apply the standard logarithmic equivalence rule: $\log_b(M) = y \iff b^y = M$.
*   **Action:** Take the variable base (**$x$**), raise it to the power of the right side (**3**), and set it equal to the inner fraction argument (**$\frac{1}{8}$**).
$$x^3 = \frac{1}{8}$$
*   *Why we do this:* This removes the logarithm entirely and transforms the equation into a power equation, positioning the variable as a standard base.
##### Step 3: Isolate the Base Variable
To undo a cubing operation ($x^3$), take the cube root ($\sqrt[3]{\quad}$) of both sides of the equation.
*   **Action:** Apply the cube root to both sides.
$$\sqrt[3]{x^3} = \sqrt[3]{\frac{1}{8}}$$
$$x = \sqrt[3]{\frac{1}{8}}$$
##### Step 4: Simplify the Radical Fraction
Evaluate the cube root of the fraction by taking the cube root of the numerator and the denominator separately.
1.  **Break apart the root:**
    $$x = \frac{\sqrt[3]{1}}{\sqrt[3]{8}}$$
2.  **Evaluate:** Since $1^3 = 1$ and $2^3 = 8$:
    $$x = \frac{1}{2}$$

---
#### Step 5: Check Logarithmic Base Constraints
Logarithmic bases have strict structural requirements that must be verified:
1.  The base must be strictly greater than zero ($b > 0$).
2.  The base cannot equal one ($b \neq 1$).

*   **Base Check:** Our calculated base is $x = \frac{1}{2}$. 
    *   $\frac{1}{2} > 0$ (True)
    *   $\frac{1}{2} \neq 1$ (True)
*   **Conclusion:** The solution satisfies all base criteria and is valid.

---
#### Final Solution
$$x = \frac{1}{2}$$

> [!IMPORTANT]
> **Odd vs. Even Roots:** Because we took an *odd* root (a cube root), we do not include a $\pm$ sign. If the equation had been $x^2 = \frac{1}{4}$, taking the square root would yield $x = \pm\frac{1}{2}$, and we would have to discard the negative option because log bases cannot be negative.

### Solving $7^{2x+5} = 8$ via Logarithmic Conversion

This problem features a variable trapped inside an exponential expression. Because the two bases ($7$ and $8$) cannot be rewritten into a common integer base, we use a logarithmic conversion to unlock the exponent.

---
#### Step-by-Step Solution

##### Step 1: Check for Isolation
The exponential term containing the variable must be completely isolated before changing forms.
*   **Analysis:** The left-hand side consists entirely of the base $7$ raised to its exponent. There are no trailing constants or coefficients multiplying the front. Isolation is complete.
##### Step 2: Convert to Logarithmic Form
Apply the conversion identity that links exponentials to logarithms: $b^y = x \iff \log_b(x) = y$.
*   **Action:** Convert the expression by writing a logarithm with a base of **7**, placing the opposite side (**8**) into the argument, and setting it equal to the exponent (**$2x+5$**).
$$\log_7(8) = 2x + 5$$
*   *Why we do this:* A logarithm calculates exponents. By rewriting the expression this way, the linear polynomial $2x+5$ is pulled out of the exponent position down onto the main algebra line.
##### Step 3: Isolate and Solve for $x$
Treat $\log_7(8)$ as a single exact constant value and perform standard linear algebra to isolate $x$:

1.  **Subtract 5 from both sides:**
    $$\log_7(8) - 5 = 2x$$
    *(Be careful to keep the $-5$ outside of the log argument; it does not combine with the 8).*
2.  **Divide the entire equation by 2:**
    $$x = \frac{\log_7(8) - 5}{2}$$

---
#### Alternative Representation: Change of Base Formula
Professor Leonard often demonstrates how to rewrite exact logarithmic expressions using standard calculator bases ($\log_{10}$ or $\ln$) so they can be easily evaluated.

*   **Change of Base Identity:** $\log_b(a) = \frac{\ln(a)}{\ln(b)}$
*   Applying this to our exact solution:
    $$x = \frac{\frac{\ln(8)}{\ln(7)} - 5}{2}$$

---
##### Step 4: Check for Extraneous Solutions
Exponential functions accept any real number in their domain. Because the variable began inside an exponent rather than a log argument, there is no structural risk of an extraneous solution. The answer is completely safe.

---
#### Final Exact Solution
$$x = \frac{\log_7(8) - 5}{2}$$

> [!CAUTION]
> **Parenthesis Awareness:** When tracking your notes, ensure you write $\log_7(8) - 5$ rather than $\log_7(8-5)$. The subtraction occurs *after* the logarithm is evaluated, not inside the argument.

### Solving $5e^{0.2x} = 7$ via Logarithmic Conversion

This problem demonstrates how to solve a base-$e$ exponential equation with an external multiplier. We must isolate the exponential term completely before converting it into a natural logarithm.

---
#### Step-by-Step Solution

##### Step 1: Isolate the Exponential Term
Before any logarithmic conversion can take place, the base and its exponent must stand alone on one side of the equation.
*   **Analysis:** The left side contains a multiplier of $5$ in front of the base $e$.
*   **Action:** Divide both sides of the equation by $5$.
$$e^{0.2x} = \frac{7}{5}$$
*   *Why we do this:* If you try to convert to a log while the $5$ is still attached, you would violate the basic conversion template ($b^y = x$). Complete isolation is a mandatory prerequisite.
##### Step 2: Convert to Logarithmic Form
Apply the conversion identity: $b^y = x \iff \log_b(x) = y$. Since our base is $e$, we use the natural logarithm ($\ln$).
*   **Action:** Take the natural log ($\ln$) of the fraction on the right side, and set it equal to the isolated exponent (**$0.2x$**).
$$\ln\left(\frac{7}{5}\right) = 0.2x$$
*   *Why we do this:* The natural log is the exact inverse of base $e$. Applying it brings the variable out of the exponent position down onto the main algebraic line.
##### Step 3: Isolate and Solve for $x$
The term $\ln(7/5)$ is an exact transcendental constant. We isolate $x$ by removing the decimal coefficient.
1.  **Divide both sides by 0.2:**
    $$x = \frac{\ln\left(\frac{7}{5}\right)}{0.2}$$
2.  **Simplify the fraction (Optional but cleaner):** 
    Recognize that $0.2 = \frac{1}{5}$. Dividing by $\frac{1}{5}$ is identical to multiplying the entire numerator by $5$.
    $$x = 5\ln\left(\frac{7}{5}\right)$$
---
#### Alternative Method: Apply $\ln$ to Both Sides
Professor Leonard often notes that instead of shifting terms conceptually, you can visually apply $\ln$ to both sides of the isolated equation:
1.  $\ln\left(e^{0.2x}\right) = \ln\left(\frac{7}{5}\right)$
2.  Using the inverse property ($\ln(e^{\square}) = \square$), the left side simplifies directly:
    $0.2x = \ln\left(\frac{7}{5}\right)$
3.  This results in the exact same final linear calculation.

---
##### Step 4: Check for Extraneous Solutions
Because the variable originated inside an exponential function rather than a logarithmic argument, the domain includes all real numbers. No extraneous solution check is required.

---

#### Final Exact Solution
$$x = 5\ln\left(\frac{7}{5}\right)$$
### Solving $8 \cdot 10^{2x-7} = 3$ via Logarithmic Conversion

This problem demonstrates how to handle a base-10 exponential equation featuring an front coefficient and a linear algebraic expression inside the exponent.

---
#### Step-by-Step Solution

##### Step 1: Isolate the Exponential Term
The base and its corresponding exponent must be completely isolated on one side of the equation before applying logarithmic conversions.
*   **Analysis:** The term $10^{2x-7}$ is currently being multiplied by an front coefficient of $8$.
*   **Action:** Divide both sides of the equation by $8$.
$$10^{2x-7} = \frac{3}{8}$$
*   *Why we do this:* Logarithmic conversion identities only apply to a clean $b^y = x$ structure. Isolating the base eliminates any conflicting coefficients.
##### Step 2: Convert to Logarithmic Form
Apply the conversion identity: $b^y = x \iff \log_b(x) = y$. Because the base is **10**, the conversion results in a common logarithm ($\log$), where the base 10 is implied and left unwritten.
*   **Action:** Take the common log of the right side fraction, and set it equal to the exponent expression (**$2x-7$**).
$$\log\left(\frac{3}{8}\right) = 2x - 7$$
*   *Why we do this:* The common logarithm acts as the inverse operation to base 10, bringing the linear expression $2x-7$ out of the exponent down to the standard line of algebra.
##### Step 3: Isolate and Solve for $x$
Treat the term $\log(3/8)$ as a single exact numeric constant and use standard linear operations to isolate the variable:

1.  **Add 7 to both sides of the equation:**
    $$\log\left(\frac{3}{8}\right) + 7 = 2x$$
    *(Make sure the $+7$ remains strictly outside of the log argument fraction).*
2.  **Divide the entire equation by 2:**
    $$x = \frac{\log\left(\frac{3}{8}\right) + 7}{2}$$

---
#### Step 4: Check for Extraneous Solutions
The initial equation frames the variable within an exponential function. Since exponential functions have an unrestricted domain consisting of all real numbers, this solution contains no risk of structural invalidity. No check is required.

---
#### Final Exact Solution
$$x = \frac{\log\left(\frac{3}{8}\right) + 7}{2}$$

> [!TIP]
> **Typographical Separation:** When adding constants next to logarithms, always write the log term first with parentheses around its argument, or place the constant in front (e.g., $\frac{7 + \log(3/8)}{2}$). This prevents accidentally grouping the constant inside the argument during fast calculations.

### Solving $4e^{x+1} = 5$ via Logarithmic Conversion

This problem outlines the steps to resolve a base-$e$ exponential term that features a multi-term linear exponent and a leading coefficient.

---
#### Step-by-Step Solution

##### Step 1: Isolate the Exponential Term
The exponential base and its exponent must stand alone before you can apply a logarithmic conversion.
*   **Analysis:** The base $e^{x+1}$ has an outside multiplier of $4$ attached to its front.
*   **Action:** Divide both sides of the equation by $4$.
$$e^{x+1} = \frac{5}{4}$$
*   *Why we do this:* You cannot convert to a logarithm while there are loose coefficients on the same side as the exponential base. Isolation cleans the equation into a standard $b^y = x$ structure.
##### Step 2: Convert to Logarithmic Form
Apply the exponential-to-logarithm conversion rule: $b^y = x \iff \log_b(x) = y$. Because the base is **$e$**, we convert it into a natural logarithm ($\ln$).
*   **Action:** Take the natural log ($\ln$) of the fraction on the right side, and set it equal to the exponent expression (**$x+1$**).
$$\ln\left(\frac{5}{4}\right) = x + 1$$
*   *Why we do this:* The natural log is the exact inverse operation of base $e$. Applying it cancels out the base $e$, freeing the expression $x+1$ from the exponent position.
##### Step 3: Isolate and Solve for $x$
Treat the expression $\ln(5/4)$ as a single exact numerical value and isolate $x$ using standard subtraction.
*   **Action:** Subtract 1 from both sides of the equation.
$$x = \ln\left(\frac{5}{4}\right) - 1$$

---
#### Alternative Visualization: $\ln$ Both Sides
Professor Leonard often demonstrates that you can achieve this exact same result by taking the natural log of both sides of the isolated equation:
1.  $\ln\left(e^{x+1}\right) = \ln\left(\frac{5}{4}\right)$
2.  Using the inverse rule $\ln(e^{\square}) = \square$, the left side cancels completely:
    $$x + 1 = \ln\left(\frac{5}{4}\right)$$
3.  Subtracting 1 yields the same final step.

---
##### Step 4: Check for Extraneous Solutions
Because the variable began inside an exponential expression rather than a logarithm, the domain covers all real numbers. There is no structural restriction, meaning the exact solution is automatically valid.

---
#### Final Exact Solution
$$x = \ln\left(\frac{5}{4}\right) - 1$$

> [!CAUTION]
> **Keep Constants Separate:** Make sure to write the $-1$ clearly outside the natural log's parenthesis. Writing $\ln(5/4 - 1)$ changes the argument to $1/4$, which is algebraically incorrect.

## 2026-May-17 - Properties of Logarithms (Precalculus - College Algebra 58) : 
https://www.youtube.com/watch?v=u0uScdsBPfk&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=59
### Properties of Logarithms

This summary outlines the fundamental algebraic properties of logarithms as taught by Professor Leonard. These rules serve as the primary toolkit for expanding, condensing, and simplifying logarithmic expressions across college algebra and calculus.

---
#### 1. The Core Logarithmic Properties
Logarithms possess three primary operational properties that correspond directly to standard exponent rules. 

##### The Product Property
When two terms are multiplied inside a logarithmic argument, they can be split into the sum of two separate logarithms.
$$\log_b(M \cdot N) = \log_b(M) + \log_b(N)$$

##### The Quotient Property
When two terms are divided inside a logarithmic argument, they can be split into the difference of two separate logarithms (numerator log minus denominator log).
$$\log_b\left(\frac{M}{N}\right) = \log_b(M) - \log_b(N)$$

##### The Power Property
An exponent on the argument of a logarithm can be moved down to the front of the logarithm to act as a multiplier.
$$\log_b(M^k) = k \cdot \log_b(M)$$

---
#### 2. Expanding Logarithmic Expressions
Expanding is the process of breaking a single complex logarithm down into multiple, simpler logarithms. 
##### Step-by-Step Strategy for Expansion:
1.  **Convert Roots to Rational Exponents:** Rewrite any radicals as fractional exponents (e.g., $\sqrt{x} \to x^{1/2}$, $\sqrt[3]{y} \to y^{1/3}$).
2.  **Apply Product and Quotient Properties First:** Separate terms in the numerator with addition, and terms in the denominator with subtraction.
3.  **Apply the Power Property Last:** Bring all exponents down to the front of their respective individual logs as coefficients.

> **Expansion Example:** 
> $$\log_b\left(\frac{x^3\sqrt{y}}{z^2}\right) \to \log_b\left(\frac{x^3 y^{1/2}}{z^2}\right)$$
> $$\to \log_b(x^3) + \log_b(y^{1/2}) - \log_b(z^2)$$
> $$\to 3\log_b(x) + \frac{1}{2}\log_b(y) - 2\log_b(z)$$

---
#### 3. Condensing Logarithmic Expressions
Condensing is the reverse process of expansion, shrinking multiple logarithmic terms into one singular logarithmic term. This is a critical skill for solving complex logarithmic equations.
##### Step-by-Step Strategy for Condensing:
1.  **Check the Bases:** Logarithms can **only** be condensed if they share the exact same base.
2.  **Apply the Power Property First:** Move any leading coefficients back up to become exponents on the arguments.
3.  **Apply Product and Quotient Properties:** 
    *   Terms with *positive* front signs merge into the **numerator** of the single log argument.
    *   Terms with *negative* front signs merge into the **denominator** of the single log argument.

> **Condensing Example:**
> $$4\ln(x) + \frac{1}{3}\ln(y) - 2\ln(z)$$
> $$\to \ln(x^4) + \ln(y^{1/3}) - \ln(z^2)$$
> $$\to \ln\left(\frac{x^4\sqrt[3]{y}}{z^2}\right)$$

---
#### 4. The Change of Base Formula
Professor Leonard explains that standard scientific or graphing calculators generally only have buttons for the common log ($\log_{10}$) and the natural log ($\ln$). To evaluate a log with an unconventional base, use the Change of Base formula:

$$\log_b(x) = \frac{\log_c(x)}{\log_c(b)}$$

In practice, you will change the base to either $e$ or $10$:
$$\log_b(x) = \frac{\ln(x)}{\ln(b)} \quad \text{or} \quad \log_b(x) = \frac{\log(x)}{\log(b)}$$

---
#### 5. Common Pitfalls & Illegal Moves

> [!CAUTION]
> **Distributing inside the argument is illegal:** 
> $\log_b(M + N) \neq \log_b(M) + \log_b(N)$
> There is no property to split a sum or difference inside an argument.

> [!WARNING]
> **Dividing entire log operations is not the quotient rule:**
> $\frac{\log_b(M)}{\log_b(N)} \neq \log_b(M) - \log_b(N)$
> Dividing one log by another log is a Change of Base setup, not a subtraction expansion.

### Inverse and Identity Properties of Logarithms

This entry details the fundamental identity and inverse properties of logarithms as presented by Professor Leonard. These properties represent structural shortcuts that occur when the base of a logarithm matches the base of its argument or exponential companion.

---
#### 1. Foundational Properties Defined

##### The Zero Property: $\log_a(1) = 0$
*   **Explanation:** This property answers the question: *"Base $a$ raised to what power equals 1?"* Since any non-zero base raised to the power of 0 equals 1 ($a^0 = 1$), the log of 1 regardless of the base is always 0.
##### The Identity Property: $\log_a(a) = 1$
*   **Explanation:** This answers: *"Base $a$ raised to what power equals itself ($a$)?"* Because any base raised to the first power remains unchanged ($a^1 = a$), a logarithm evaluates to 1 whenever its base matches its argument exactly.
##### The Log-of-a-Base Inverse Property: $\log_a(a^r) = r$
*   **Explanation:** When a logarithm of base $a$ encounters a matching exponential base $a$ inside its argument, the log operation and the exponential base cancel out completely. The logarithm un-clutches the exponent, leaving behind just the power $r$.
##### The Base-of-a-Log Inverse Property: $a^{\log_a(M)} = M$
*   **Explanation:** This represents the inverse relationship occurring in reverse. When an exponential base $a$ is raised to a logarithmic power that shares that exact same base $a$, the operations cancel each other out entirely, dropping down the argument $M$.
---
#### 2. Evaluating Examples: $\log_a(a^r) = r$

The following examples demonstrate the cancellation shortcut when the logarithmic base matches the internal argument base.
##### Example A: $\log_2(2^{-13})$
*   **Analysis:** The logarithm has a base of $2$, and the argument is an exponential term with a base of $2$. 
*   **Cancellation:** The base-2 log and base-2 exponential cancel out.
*   **Result:** $-13$
##### Example B: $\log\left(10^{1/3}\right)$
*   **Analysis:** This is a common logarithm ($\log$), meaning its implied base is $10$. The internal exponential base is also $10$.
*   **Cancellation:** The implied base-10 log cancels out the base-10 exponential.
*   **Result:** $\frac{1}{3}$
##### Example C: $\ln\left(e^{-4}\right)$
*   **Analysis:** This is a natural logarithm ($\ln$), meaning its implied base is the transcendental number $e$. The internal exponential base matches it exactly as $e$.
*   **Cancellation:** The natural log cancels the base-$e$ exponential.
*   **Result:** $-4$
---
#### 3. Evaluating Examples: $a^{\log_a(M)} = M$

The following examples demonstrate the cancellation shortcut when an exponential base is raised to a matching logarithmic power.
##### Example D: $2^{\log_2(7)}$
*   **Analysis:** An exponential base of $2$ is being raised to a logarithmic power that also has a base of $2$.
*   **Cancellation:** The outer base $2$ and the log base $2$ undo each other, freeing the argument.
*   **Result:** $7$
##### Example E: $10^{\log\left(1/4\right)}$
*   **Analysis:** An exponential base of $10$ is raised to a common logarithm ($\log$) power, which carries an implicit base of $10$.
*   **Cancellation:** The matching base-10 structures cancel.
*   **Result:** $\frac{1}{4}$
##### Example F: $e^{\ln(8)} = 8$
*   **Analysis:** An exponential base of $e$ is raised to a natural logarithm ($\ln$) power, which carries an implicit base of $e$. 
*   **Cancellation:** The exponential base $e$ and natural log cancel each other out completely.
*   **Result:** $8$
> [!NOTE]
> **Notation Cleanup:** In standard algebra, ensure the exponent is explicitly tracked as the log argument. For instance, writing $e^{\ln(8)}$ avoids confusion with formatting errors like $e^{\ln^8}$, keeping it mathematically clear that $8$ is the structural value being isolated.
### The Product Property of Logarithms

This entry outlines the mechanics, logic, and directional applications of the Product Property of Logarithms as taught by Professor Leonard.

---
#### 1. Core Definition
The Product Property states that a single logarithm containing a product (multiplication) inside its argument can be broken apart into the sum of two separate logarithms sharing the same base.

$$\log_a(M \cdot N) = \log_a(M) + \log_a(N)$$

*   **The Conceptual Rule:** Multiplication inside a logarithmic argument translates directly to addition outside between independent logarithmic operations.

---
#### 2. The Algebraic Logic: Why It Works
Professor Leonard explains that logarithms are, fundamentally, exponents. Therefore, logarithmic properties behave exactly like exponent rules.

Consider the standard product rule for exponents: 
$$x^A \cdot x^B = x^{A+B}$$
*   When you **multiply** matching exponential bases, you **add** their exponents.
*   Because a logarithm outputs an exponent value, taking the log of a multiplied product ($\log_a(M \cdot N)$) naturally requires adding the individual exponents ($\log_a(M) + \log_a(N)$) together.

---

#### 3. Two-Way Directional Application
Like all algebraic properties, this rule is a "two-way street." You must know how to use it in both directions depending on the goal of your problem.

##### Direction 1: Expanding Expressions (Left-to-Right)
Expanding breaks a single, complex logarithm into smaller components. This is highly useful in calculus for taking derivatives of complicated functions.
*   **Action:** Look for multiplication inside the parenthesis and split them into separate added terms.
*   **Example:** 
    $$\log_5(5x) \implies \log_5(5) + \log_5(x)$$
    Using identity rules ($\log_5(5) = 1$), this simplifies cleanly to:
    $$1 + \log_5(x)$$
##### Direction 2: Condensing Expressions (Right-to-Left)
Condensing combines multiple logarithmic terms into one singular logarithm. This is a non-negotiable prerequisite step when solving advanced logarithmic equations.
*   **Action:** Look for separate logs of the same base joined by addition, and multiply their arguments together inside a single log.
*   **Example:** 
    $$\log_2(x) + \log_2(x+3) \implies \log_2\big(x \cdot (x+3)\big) \implies \log_2(x^2 + 3x)$$

---
#### 4. Critical Warnings & Mistakes to Avoid

> [!CAUTION]
> **The Distribution Fallacy (Illegal Move):**
> $$\log_a(M + N) \neq \log_a(M) + \log_a(N)$$
> You **cannot** split a logarithm if there is addition *inside* the argument. The property only works if there is *multiplication* inside the argument. 

> [!WARNING]
> **Multiplying Independent Logarithms:**
> $$\log_a(M) \cdot \log_a(N) \neq \log_a(M \cdot N)$$
> Multiplying two entirely separate log operations together does *not* trigger the product property. The addition of separate logs is what yields a multiplied inner argument.

### The Quotient Property of Logarithms

This entry outlines the mechanics, underlying logic, and structural applications of the Quotient Property of Logarithms as taught by Professor Leonard.

---
#### 1. Core Definition
The Quotient Property states that a single logarithm containing a quotient (division) inside its argument can be broken apart into the difference (subtraction) of two separate logarithms sharing the same base.

$$\log_a\left(\frac{M}{N}\right) = \log_a(M) - \log_a(N)$$

*   **The Conceptual Rule:** Division inside a logarithmic argument translates directly to subtraction outside, where the denominator's log is subtracted from the numerator's log.

---
#### 2. The Algebraic Logic: Why It Works
Because logarithms track exponents, their rules reflect the operational behavior of exponents. 

Consider the standard quotient rule for exponents: 
$$\frac{x^A}{x^B} = x^{A-B}$$
*   When you **divide** matching exponential bases, you **subtract** the bottom exponent from the top exponent.
*   Since a logarithm calculates an exponent, taking the log of a divided argument ($\log_a(M/N)$) requires subtracting the corresponding log expressions ($\log_a(M) - \log_a(N)$).

---
#### 3. Two-Way Directional Application

##### Direction 1: Expanding Expressions (Left-to-Right)
Expanding breaks a complex, fractional log expression down into simpler linear pieces.
*   **Action:** Take whatever is in the numerator and give it a positive log term; take whatever is in the denominator and subtract its log term.
*   **Example:** 
    $$\ln\left(\frac{e}{x}\right) \implies \ln(e) - \ln(x)$$
    Using identity rules ($\ln(e) = 1$), this simplifies cleanly to:
    $$1 - \ln(x)$$

##### Direction 2: Condensing Expressions (Right-to-Left)
Condensing combines scattered log terms into one singular logarithm, which is a mandatory step for isolating variables when solving logarithmic equations.
*   **Action:** Look for two logs of the same base separated by subtraction. Combine them by placing the argument of the positive log in the numerator and the argument of the negative log in the denominator.
*   **Example:** 
    $$\log_3(x+5) - \log_3(x) \implies \log_3\left(\frac{x+5}{x}\right)$$

---
#### 4. Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Total Division Fallacy (Illegal Move):**
> $$\frac{\log_a(M)}{\log_a(N)} \neq \log_a(M) - \log_a(N)$$
> Dividing an entire logarithm by another entirely separate logarithm does **not** trigger the quotient rule. The division must happen completely *inside the argument* of a single log to allow subtraction expansion. (Dividing two separate logs is actually a Change of Base setup).

> [!WARNING]
> **Internal Subtraction Splitting:**
> $$\log_a(M - N) \neq \frac{\log_a(M)}{\log_a(N)} \quad \text{and} \quad \log_a(M - N) \neq \log_a(M) - \log_a(N)$$
> There is no algebraic property that allows you to break apart a subtraction or addition operation that is stuck *inside* a log argument.

### The Power Property of Logarithms

This entry outlines the mechanics, underlying logic, and structural applications of the Power Property of Logarithms as taught by Professor Leonard.

---
#### 1. Core Definition
The Power Property states that an exponent on the argument of a logarithm can be moved down to the front of the logarithm to act as a coefficient multiplier.

$$\log_a(M^r) = r \cdot \log_a(M)$$

*   **The Conceptual Rule:** A power *inside* a logarithmic argument translates directly to a multiplier *outside* the entire logarithmic term.

---
#### 2. The Algebraic Logic: Why It Works
Because logarithms are exponents, this property is the direct reflection of the "power to a power" rule for exponents.

Consider the standard power rule for exponents:
$$(x^A)^B = x^{A \cdot B}$$
*   When raising an exponential term to another power, you **multiply** the exponents together.
*   Since a logarithm outputs an exponent, taking the log of a base raised to a power ($\log_a(M^r)$) means multiplying the exponent of the argument ($r$) by the overall exponent of the log expression ($\log_a(M)$).
##### Alternative Proof via the Product Property:
You can also see this property work by expanding an argument out through simple multiplication. For example, if we have a cubed argument:
$$\log_a(M^3) = \log_a(M \cdot M \cdot M)$$
Applying the Product Property to split the multiplication into addition yields:
$$\log_a(M) + \log_a(M) + \log_a(M) = 3\log_a(M)$$

---
#### 3. Two-Way Directional Application

##### Direction 1: Expanding Expressions (Left-to-Right)
Expanding pulls exponents out of arguments to simplify the internal expression. This is heavily utilized in calculus to avoid using the chain rule during differentiation.
*   **Action:** Locate any power on the argument and swing it down to the front as a scalar multiplier.
*   **Important Step (Radicals):** Always convert radicals into fractional exponents before expanding (e.g., $\sqrt{x} \to x^{1/2}$).
*   **Example:** 
    $$\ln(\sqrt[3]{x}) \implies \ln(x^{1/3}) \implies \frac{1}{3}\ln(x)$$
##### Direction 2: Condensing Expressions (Right-to-Left)
Condensing clears out any coefficients in front of logarithms, which is an absolute requirement before you can merge multiple logs using the Product or Quotient properties.
*   **Action:** Take any scalar coefficient in front of a log term and move it up to become an exponent on the inner argument.
*   **Example:** 
    $$2\log_5(x) + \log_5(y) \implies \log_5(x^2) + \log_5(y) \implies \log_5(x^2y)$$

---
#### 4. Critical Warnings & Common Pitfalls

> [!CAUTION]
> **Whole-Function Powers vs. Argument Powers:**
> $$\big(\log_a(M)\big)^r \neq r \cdot \log_a(M)$$
> The power property **only** applies if the exponent is exclusively attached to the internal argument $M$. If the entire logarithmic operation is raised to a power, the power property cannot be used.

> [!WARNING]
> **Grouped Arguments Require Parentheses:**
> When expanding an expression like $\log_a(3x)^2$, the exponent applies to the whole argument, allowing $2\log_a(3x)$. However, if it is written as $\log_a 3x^2$, the exponent belongs *only* to the $x$, meaning you cannot bring the 2 to the front until you separate the 3 using the Product Property first: $\log_a 3 + 2\log_a x$.

### Step-by-Step Breakdown: Expanding $\log_5(25x)$

This entry demonstrates how to apply the **Product Property of Logarithms** to expand a combined term into separate components, and then evaluate the remaining numerical constant as taught by Professor Leonard.

---
#### 1. Applying the Property

##### The Given Equation
$$\log_5(25x) = \log_5(25) + \log_5(x)$$

##### Why This Step Works
The expression inside the argument on the left side is a product ($25 \cdot x$). 
*   **The Product Property Identity:** $\log_a(M \cdot N) = \log_a(M) + \log_a(N)$
*   By matching the template, our base $a$ is **5**, our term $M$ is **25**, and our term $N$ is **$x$**. We split the internal multiplication into an external addition between two separate base-5 logarithms.

---
#### 2. Evaluating the Numerical Logarithm

Professor Leonard emphasizes that when expanding logarithmic expressions, you are never done until you check if any of the newly created logs consist purely of numbers that can be evaluated.

Look closely at the first term on the right side: **$\log_5(25)$**
1.  **Ask the Core Logarithmic Question:** This expression asks: *"5 raised to what power equals 25?"*
2.  **Relate to Exponents:** Since we know that $5^2 = 25$, the logarithm evaluates exactly to the exponent, which is **2**.
3.  **Substitute back into the expression:** Replace $\log_5(25)$ with the integer $2$.

---
#### 3. Final Fully Simplified Form

$$2 + \log_5(x)$$

> [!TIP]
> **When to Stop:** In your notes, always look to see if the argument is a perfect power of the base. If the argument can be written as $b^r$, evaluate it completely using the identity $\log_b(b^r) = r$. If the argument is a variable (like $x$), it cannot be simplified further and must be left alone.

### Expanding $\ln\left(\frac{e}{x}\right)$ via Logarithmic Properties

This entry demonstrates how to expand a fractional natural log expression into a fully simplified linear expression by combining the **Quotient Property** and the **Identity Property**.

---
#### Step-by-Step Expansion
##### Step 1: Apply the Quotient Property
The argument inside the natural log contains a fraction ($\frac{e}{x}$).
*   **The Identity Rule:** $\ln\left(\frac{M}{N}\right) = \ln(M) - \ln(N)$
*   **Action:** Separate the numerator ($e$) and the denominator ($x$) into independent log terms, subtracting the denominator's log from the numerator's log.
$$\ln(e) - \ln(x)$$
*   *Why we do this:* This step dismantles the rational fraction structure, turning an internal division operation into an external subtraction line.
##### Step 2: Apply the Identity Property
Look closely at the first term: **$\ln(e)$**.
*   **The Identity Rule:** $\ln(e) = 1$
*   **Action:** The natural log has an unwritten implicit base of $e$. This term asks the fundamental question: *"Base $e$ raised to what power equals $e$?"* Since $e^1 = e$, the log of its own base simplifies cleanly to the integer **1**.
$$\ln(e) \implies 1$$
##### Step 3: Combine and Finalize
Substitute the simplified integer back into the expression to find the final form.
$$1 - \ln(x)$$

---
#### Final Fully Expanded Form
$$1 - \ln(x)$$

### Expanding $\ln\left(\frac{x}{e^x}\right)$ via Logarithmic Properties

This entry demonstrates how to break down a fractional natural log expression by combining the **Quotient Property** and the **Inverse Identity Property** into a fully simplified form.

---
#### Step-by-Step Expansion

##### Step 1: Apply the Quotient Property
The argument of the natural log is a fraction involving division ($\frac{x}{e^x}$).
*   **The Identity Rule:** $\ln\left(\frac{M}{N}\right) = \ln(M) - \ln(N)$
*   **Action:** Separate the numerator ($x$) and the denominator ($e^x$) into their own independent logs, subtracting the bottom from the top.
$$\ln(x) - \ln(e^x)$$
*   *Why we do this:* This removes the fraction entirely, changing an internal division operation into an external subtraction line.
##### Step 2: Apply the Log-of-a-Base Inverse Property
Look closely at the second term: **$\ln(e^x)$**. 
*   **The Identity Rule:** $\ln(e^{\square}) = \square$
*   **Action:** Because the natural log ($\ln$) has an implicit base of $e$, it perfectly matches the exponential base $e$ inside its argument. The operations cancel each other out completely, leaving behind just the exponent **$x$**.
$$\ln(e^x) \implies x$$

##### Step 3: Combine and Finalize
Substitute the simplified value back into our expanded expression.
$$\ln(x) - x$$

---
#### Final Fully Expanded Form
$$\ln(x) - x$$

> [!TIP]
> **Order of Operations Notice:** No parentheses are needed around the final $x$. The subtraction occurs completely outside of the natural log operation, meaning only the initial variable $x$ remains bound inside the function: $(\ln(x)) - x$.

## 2026-May-18 - How to Expand Logarithms (Precalculus - College Algebra 59) : 
https://www.youtube.com/watch?v=qCeN653SdX4&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=62
### How to Expand Logarithms

Expansion is the process of taking a single logarithm with a complex argument (containing multiplication, division, roots, and exponents) and breaking it apart into a linear chain of separate, simple logarithms.

---
#### The Global Goal of Expansion
Every individual factor in the original argument must end up inside its own separate logarithm with an exponent of exactly 1.

---
#### The Order of Operations for Expansion
To avoid making algebraic errors, apply the properties of logarithms in a definitive, structured order.
##### Step 1: Convert Radicals to Rational Exponents
Logarithms do not have specific operational properties for roots ($\sqrt{\quad}$), but they have rules for exponents. Before doing any splitting, convert all radical signs into fractional exponents.
*   $\sqrt{x} \implies x^{1/2}$
*   $\sqrt[3]{y^2} \implies y^{2/3}$
##### Step 2: Apply the Quotient Property (Split the Fraction)
If the expression contains a fraction, address the numerator and denominator first. 
*   Everything in the **numerator** gets a **positive** logarithm.
*   Everything in the **denominator** gets a **negative** (subtracted) logarithm.
##### Step 3: Apply the Product Property (Split Multiplied Terms)
Look inside your newly separated logarithms. If an individual argument still contains factors multiplied together, split them into addition.
*   $\log_b(xy) \implies \log_b(x) + \log_b(y)$
##### Step 4: Apply the Power Property (Pull Down Exponents)
Once every factor is isolated inside its own individual logarithm, take the exponents of those arguments and swing them down to the front to act as coefficients. This must be the final structural step.
*   $\log_b(x^r) \implies r\log_b(x)$
##### Step 5: Evaluate Numerical Constants
Always scan your final expanded chain. If any logarithm contains purely numbers (e.g., $\log_2(8)$ or $\ln(e)$), evaluate them down to integers to complete the simplification.

---
#### Comprehensive Expansion Example

$$\log_4\left( \frac{16x^3}{\sqrt{y}} \right)$$

##### Step 1: Rewrite Radicals
$$\log_4\left( \frac{16x^3}{y^{1/2}} \right)$$
##### Step 2 & 3: Split Numerator and Denominator
*(Note: If a term comes from the top, its log is positive; if it comes from the bottom, its log is negative).*
$$\log_4(16) + \log_4(x^3) - \log_4(y^{1/2})$$
##### Step 4: Apply Power Property
Bring all exponents to the front as scalar multipliers:
$$\log_4(16) + 3\log_4(x) - \frac{1}{2}\log_4(y)$$

##### Step 5: Evaluate Constants
Look at the first term: $\log_4(16)$. Since $4^2 = 16$, the term simplifies cleanly to $2$.
$$2 + 3\log_4(x) - \frac{1}{2}\log_4(y)$$

---
#### Critical Pitfalls to Avoid

> [!CAUTION]
> **Premature Exponent Pull-Down:**
> Given $\log_b(5x^3)$, you **cannot** immediately bring the 3 to the front because the exponent 3 only belongs to the $x$, not the 5. You must use the product rule first: $\log_b(5) + \log_b(x^3) \to \log_b(5) + 3\log_b(x)$.

> [!WARNING]
> **Multi-Term Denominator Traps:**
> Given $\log_b\left(\frac{a}{cd}\right)$, notice that both $c$ and $d$ reside in the denominator. When expanded, *both* terms must be subtracted: $\log_b(a) - \log_b(c) - \log_b(d)$. Alternatively, use parentheses if keeping the product property grouped: $\log_b(a) - \big(\log_b(c) + \log_b(d)\big)$.

### Expanding $\ln(x^2 \sqrt{1-x})$ via Logarithmic Properties

This entry outlines the step-by-step expansion of a natural logarithm containing a product, a power, and a radical expression.

---
#### Step-by-Step Expansion

##### Step 1: Convert Radicals to Rational Exponents
Before applying any logarithmic splitting properties, rewrite all roots using fractional exponents.
*   **Action:** Convert the square root into an exponent of $\frac{1}{2}$.
$$\ln\big(x^2 (1-x)^{1/2}\big)$$
*   *Why we do this:* Logarithms do not have specific operational properties for radical symbols, but they possess clear rules for handling exponential powers.
##### Step 2: Apply the Product Property
The argument contains two distinct algebraic factors multiplied together: $x^2$ and $(1-x)^{1/2}$.
*   **The Identity Rule:** $\ln(M \cdot N) = \ln(M) + \ln(N)$
*   **Action:** Separate the two factors into their own individual natural log terms joined by addition.
$$\ln(x^2) + \ln\big((1-x)^{1/2}\big)$$
*   *Why we do this:* This isolates each distinct algebraic component into its own functional environment.
##### Step 3: Apply the Power Property
Each individual logarithm now contains an argument raised to a specific power.
*   **The Identity Rule:** $\ln(M^r) = r \cdot \ln(M)$
*   **Action:** Swing the exponents ($2$ and $\frac{1}{2}$) down to the absolute front of their respective log terms to serve as coefficients.
$$2\ln(x) + \frac{1}{2}\ln(1-x)$$
*   *Why we do this:* This completes the expansion by ensuring every internal argument has a clean, unweighted exponent of 1.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **Internal Subtraction Splitting Trap:**
> Do **not** attempt to break apart the final term $\ln(1-x)$ into $\ln(1) - \ln(x)$. There is absolutely no logarithmic property that allows you to split a subtraction or addition operation stuck inside an argument. It must be left exactly as $\ln(1-x)$.

---
#### Final Fully Expanded Form
$$2\ln(x) + \frac{1}{2}\ln(1-x)$$
### Expanding $\log_5 \left( \frac{\sqrt[3]{x^2+1}}{x^2 - 1} \right)$ via Logarithmic Properties

This entry outlines the step-by-step expansion of a base-5 logarithm featuring a rational fraction, a cube root, and quadratic arguments.

---
#### Step-by-Step Expansion

##### Step 1: Convert Radicals to Rational Exponents
Before separating any terms into independent logarithms, eliminate all radical symbols by converting them into fractional exponents.
*   **Action:** Rewrite the cube root ($\sqrt[3]{\quad}$) in the numerator as an exponent of $\frac{1}{3}$.
$$\log_5 \left( \frac{(x^2+1)^{1/3}}{x^2 - 1} \right)$$
*   *Why we do this:* Logarithms lack structural rules to manage raw radical signs, but converting them into exponential powers unlocks the use of the Power Property later on.
##### Step 2: Apply the Quotient Property
The primary structure inside the argument is a fraction involving algebraic division.
*   **The Identity Rule:** $\log_a\left(\frac{M}{N}\right) = \log_a(M) - \log_a(N)$
*   **Action:** Split the expression into two distinct base-5 logarithms. Give the numerator factor a positive sign and subtract the denominator factor.
$$\log_5\big((x^2+1)^{1/3}\big) - \log_5(x^2 - 1)$$
*   *Why we do this:* This removes the rational fraction layout entirely, converting internal division into an external subtraction line.
##### Step 3: Apply the Power Property
Examine the newly separated terms to check for powers attached directly to the individual arguments.
*   **The Identity Rule:** $\log_a(M^r) = r \cdot \log_a(M)$
*   **Action:** Swing the exponent $\frac{1}{3}$ from the numerator's argument down to the absolute front of its specific log term to serve as a scalar coefficient.
$$\frac{1}{3}\log_5(x^2+1) - \log_5(x^2 - 1)$$
*   *Why we do this:* Bringing powers out front ensures that the grouped factor $(x^2+1)$ functions with an unweighted exponent of 1.

---
#### Alternative/Advanced Consideration: Factoring
Professor Leonard frequently reminds students to inspect arguments to ensure they cannot be broken down further algebraically using basic factoring.
*   **Analysis:** The term $(x^2 + 1)$ is a sum of squares and cannot be factored over real numbers. However, the term $(x^2 - 1)$ is a **difference of squares** and can be factored into $(x - 1)(x + 1)$.
*   **Action:** Factor the second argument and apply the Product Property:
    $$\log_5(x^2 - 1) = \log_5\big((x - 1)(x + 1)\big) = \log_5(x - 1) + \log_5(x + 1)$$
*   **Distribute the Negative Sign:** Because the original log term was subtracted, the negative sign applies to both factored parts:
    $$\frac{1}{3}\log_5(x^2+1) - \big(\log_5(x - 1) + \log_5(x + 1)\big)$$
    $$\frac{1}{3}\log_5(x^2+1) - \log_5(x - 1) - \log_5(x + 1)$$

---

#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **Internal Operator Traps (Illegal Moves):**
> Do **not** attempt to split the expression $\log_5(x^2+1)$ into $\log_5(x^2) + \log_5(1)$. There is absolutely no identity that allows you to expand addition or subtraction stuck inside a logarithmic argument. 

> [!WARNING]
> **Premature Exponent Pull-Down:**
> In the term $\log_5(x^2-1)$, you **cannot** bring the power of 2 to the front. The exponent 2 belongs strictly to the variable $x$, not to the entire grouped argument $(x^2-1)$.

---
#### Final Fully Expanded Form
$$\frac{1}{3}\log_5(x^2+1) - \log_5(x - 1) - \log_5(x + 1)$$
*(Note: Leaving the last terms unfactored as $- \log_5(x^2 - 1)$ is also technically correct, but completely expanding down to linear binomial arguments matches the thorough standard required in calculus).*
### Expanding $\log \left[ \frac{x^3 \sqrt{x+1}}{(x-2)^2(x-1)} \right]$ via Logarithmic Properties

This entry details the multi-step expansion of a highly complex common logarithm (base 10) featuring multiple factors in both the numerator and denominator, a power, and a square root.

---
#### Step-by-Step Expansion

##### Step 1: Convert Radicals to Rational Exponents
Eliminate any radical symbols within the expression by re-writing them as fractional powers.
*   **Action:** Convert the square root ($\sqrt{\quad}$) in the numerator to an exponent of $\frac{1}{2}$.
$$\log \left[ \frac{x^3 (x+1)^{1/2}}{(x-2)^2(x-1)} \right]$$
*   *Why we do this:* Logarithms do not possess distinct properties to handle roots, but changing them to rational exponents allows them to be simplified using the Power Property.
##### Step 2: Split the Rational Structure (Quotient & Product Properties)
Professor Leonard emphasizes a fast, foolproof trick for expanding large fractions: **Any factor originating from the numerator gets a positive log term, and any factor originating from the denominator gets a negative (subtracted) log term.**
*   **Action:** Split all four independent factors ($x^3$, $(x+1)^{1/2}$, $(x-2)^2$, and $(x-1)$) into their own individual common log operations.
$$\log(x^3) + \log\big((x+1)^{1/2}\big) - \log\big((x-2)^2\big) - \log(x-1)$$
*   *Why we do this:* This completely dismantles the fractional layout. Because both $(x-2)^2$ and $(x-1)$ are grouped together inside the denominator, they must both be subtracted to show they are dividing the overall expression.
##### Step 3: Apply the Power Property
Examine each newly separated logarithm and move any exponents down to clear out the inner arguments.
*   **The Identity Rule:** $\log(M^r) = r \cdot \log(M)$
*   **Action:** Swing the exponents ($3$, $\frac{1}{2}$, and $2$) down to the front of their respective individual terms to act as scalar multiplier coefficients.
$$3\log(x) + \frac{1}{2}\log(x+1) - 2\log(x-2) - \log(x-1)$$
*   *Why we do this:* This represents the final structural step of expansion, leaving every algebraic argument with an unweighted exponent of exactly 1.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Multi-Term Denominator Sign Error:**
> A very frequent mistake is writing the final term as $+ \log(x-1)$ because it was multiplied by $(x-2)^2$ at the bottom. Remember, because it resides in the denominator, its net effect is division, meaning its expanded logarithm **must** be subtracted: $- \log(x-1)$.

> [!WARNING]
> **Internal Operator Restrictions (No Splitting Polynomials):**
> Do **not** attempt to split terms like $\log(x+1)$ or $\log(x-2)$ into independent pieces like $\log(x) + \log(1)$. Logarithms can never expand addition or subtraction that is bound inside an argument. They must remain grouped as binomials.

---
#### Final Fully Expanded Form
$$3\log(x) + \frac{1}{2}\log(x+1) - 2\log(x-2) - \log(x-1)$$
### Expanding $\ln \left[ \frac{5x^2 \sqrt[3]{7-2x}}{4(x+1)^2} \right]$ via Logarithmic Properties

This entry outlines the systematic expansion of a complex natural logarithm (base $e$) containing multiple constants, variables, powers, a cube root, and a grouped binomial denominator.

---
#### Step-by-Step Expansion

##### Step 1: Convert Radicals to Rational Exponents
Before separating any terms into independent logarithms, eliminate all radical symbols by converting them into fractional exponents.
*   **Action:** Rewrite the cube root ($\sqrt[3]{\quad}$) in the numerator as an exponent of $\frac{1}{3}$.
$$\ln \left[ \frac{5x^2 (7-2x)^{1/3}}{4(x+1)^2} \right]$$
*   *Why we do this:* Logarithms lack rules for managing raw radical signs, but converting them into exponential exponents allows us to apply the Power Property later on.
##### Step 2: Split the Rational Structure (Quotient & Product Properties)
Apply Professor Leonard's foundational rule for multi-factor fractions: **Every distinct factor originating from the numerator gets a positive log term, and every distinct factor originating from the denominator gets a negative (subtracted) log term.**
*   **Action:** Identify all five distinct factors ($5$, $x^2$, $(7-2x)^{1/3}$, $4$, and $(x+1)^2$) and split them into separate natural log operations.
$$\ln(5) + \ln(x^2) + \ln\big((7-2x)^{1/3}\big) - \ln(4) - \ln\big((x+1)^2\big)$$
*   *Why we do this:* This entirely dismantles the fractional product layout. Because both the constant $4$ and the binomial term $(x+1)^2$ live in the denominator, their respective log operations must be subtracted.
##### Step 3: Apply the Power Property
Scan the individual log terms and move any exponents down to the front to act as coefficients.
*   **The Identity Rule:** $\ln(M^r) = r \cdot \ln(M)$
*   **Action:** Swing the exponents ($2$, $\frac{1}{3}$, and $2$) down to the absolute front of their respective individual terms.
$$\ln(5) + 2\ln(x) + \frac{1}{3}\ln(7-2x) - \ln(4) - 2\ln(x+1)$$
*   *Why we do this:* This completes the structural process of expansion, leaving every algebraic argument with an unweighted exponent of exactly 1.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Constant Coefficient Trap:**
> Do **not** bring the power of 2 down to the front of the numerator before splitting the 5 away. In the original expression $5x^2$, the exponent 2 belongs *exclusively* to the $x$, not to the 5. You must isolate the factors using the product rule first: $\ln(5) + \ln(x^2) \to \ln(5) + 2\ln(x)$.

> [!WARNING]
> **Internal Operator Restrictions:**
> Do **not** attempt to expand or split terms containing internal operations like $\ln(7-2x)$ or $\ln(x+1)$. Logarithmic properties only exist for multiplication and division *inside* arguments, not addition or subtraction. These terms must remain intact as binomial arguments.

---
#### Final Fully Expanded Form
$$\ln(5) + 2\ln(x) + \frac{1}{3}\ln(7-2x) - \ln(4) - 2\ln(x+1)$$
### Expanding $\log \left[ \frac{(x-4)^2}{x^2 - 9} \right]^{2/3}$ via Logarithmic Properties

This entry details the multi-step expansion of a common logarithm (base 10) where the entire fractional argument is raised to a global exponent, and the denominator contains a factorable quadratic binomial.

---
#### Step-by-Step Expansion

##### Step 1: Apply the Global Power Property
Look at the outermost structure of the expression. The entire rational argument is wrapped in brackets and raised to the power of $\frac{2}{3}$.
*   **The Identity Rule:** $\log(M^r) = r \cdot \log(M)$
*   **Action:** Bring the global exponent $\frac{2}{3}$ all the way down to the front of the logarithm to serve as a multiplier for the entire upcoming expansion. Use large brackets to keep it grouped.
$$\frac{2}{3} \cdot \log \left[ \frac{(x-4)^2}{x^2 - 9} \right]$$
*   *Why we do this:* This clears the outer layer of the expression, allowing you to split the internal fraction safely without mismanaging the power.
##### Step 2: Factor the Denominator
Professor Leonard strongly emphasizes checking all polynomial arguments for basic factoring opportunities before splitting them apart.
*   **Analysis:** The denominator $x^2 - 9$ is a **difference of squares**. It can be factored cleanly into $(x - 3)(x + 3)$.
*   **Action:** Rewrite the expression with the factored denominator.
$$\frac{2}{3} \cdot \log \left[ \frac{(x-4)^2}{(x - 3)(x + 3)} \right]$$
##### Step 3: Split the Rational Structure (Quotient & Product Properties)
Dismantle the fraction into separate log terms using the standard rule: **Factors from the numerator yield positive log terms, while factors from the denominator yield negative (subtracted) log terms.** Keep the global coefficient $\frac{2}{3}$ outside the group for now.
*   **Action:** Separate the three individual factors: $(x-4)^2$, $(x-3)$, and $(x+3)$.
$$\frac{2}{3} \left[ \log\big((x-4)^2\big) - \log(x - 3) - \log(x + 3) \right]$$
*   *Why we do this:* Both $(x-3)$ and $(x+3)$ reside in the denominator, meaning they are dividing the expression and must both carry a negative sign when expanded.
##### Step 4: Apply the Internal Power Property
Examine the newly separated terms. The first argument still contains an exponent of $2$.
*   **Action:** Swing the exponent $2$ down to the front of its specific log term.
$$\frac{2}{3} \left[ 2\log(x - 4) - \log(x - 3) - \log(x + 3) \right]$$
##### Step 5: Distribute the Global Coefficient
To finalize the expansion, distribute the fractional multiplier $\frac{2}{3}$ to each individual log term inside the brackets.
*   First term: $\frac{2}{3} \cdot 2\log(x-4) = \frac{4}{3}\log(x-4)$
*   Second term: $\frac{2}{3} \cdot (-\log(x-3)) = -\frac{2}{3}\log(x-3)$
*   Third term: $\frac{2}{3} \cdot (-\log(x+3)) = -\frac{2}{3}\log(x+3)$

$$\frac{4}{3}\log(x - 4) - \frac{2}{3}\log(x - 3) - \frac{2}{3}\log(x + 3)$$

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Difference of Squares Oversight:**
> Leaving the denominator un-factored as $-\log(x^2 - 9)$ is incomplete. In Precalculus and Calculus, you are expected to reduce arguments down to their simplest linear binomial factors whenever algebraically possible.

> [!WARNING]
> **Internal Operator Restrictions:**
> Never try to expand addition or subtraction trapped inside a binomial argument, such as rewriting $\log(x-4)$ into $\log(x) - \log(4)$. These terms are completely unbreakable and must remain intact.

---
#### Final Fully Expanded Form
$$\frac{4}{3}\log(x - 4) - \frac{2}{3}\log(x - 3) - \frac{2}{3}\log(x + 3)$$
## 2026-May-19 - How to Combine Logarithms (Precalculus - College Algebra 60) :
https://www.youtube.com/watch?v=YrU8fYchnIU&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP
### How to Combine (Condense) Logarithms

Condensing (or combining) logarithms is the exact reverse process of expansion. It takes a long, linear chain of multiple logarithmic terms and compresses them into one single logarithm containing a unified algebraic argument.

---
#### The Global Goal of Condensing
To merge multiple logs of the same base until you are left with exactly **one** log expression with a coefficient of 1.

* **The Golden Prerequisite:** You can *only* combine logarithms that share the exact same base (e.g., all are $\log_3$, all are $\ln$, or all are common $\log$). If the bases do not match, they cannot be merged.

---
#### The Order of Operations for Condensing
To avoid structural errors, apply the expansion steps completely in reverse.

[Step 1: Move Coefficients Up] —> [Step 2: Handle Fractions / Multiplications] —> [Step 3: Convert to Radicals]

---
#### Step-by-Step Methodology

##### Step 1: Apply the Power Property (Clear Front Coefficients)
Before you can merge any separate logs together, the space directly in front of every logarithm must be completely clear.
* **Action:** Take any scalar multiplier or fraction sitting in front of a log and swing it up to become an exponent on that log's internal argument.
* **Template:** $r \cdot \log_a(M) \implies \log_a(M^r)$
##### Step 2: Apply the Product and Quotient Properties (The Fast Fraction Trick)
Once all coefficients are cleared, merge the terms into a single log argument. Professor Leonard teaches a highly efficient shortcut to process the entire string of terms simultaneously rather than working painstakingly left-to-right:
1.  Write down one single log symbol with the matching base and draw a large fraction bar next to it.
2.  Scan your terms:
    * If a log term has a **positive** sign in front of it, its argument goes into the **numerator** (top) of your fraction as a multiplied factor.
    * If a log term has a **negative** sign in front of it, its argument goes into the **denominator** (bottom) of your fraction as a multiplied factor.
##### Step 3: Simplify and Convert Rational Exponents
Look inside your newly unified argument. Perform any necessary polynomial multiplication or factoring cleanup. Finally, change any fractional exponents back into standard radical forms.
* $x^{1/2} \implies \sqrt{x}$
* $(y+2)^{2/3} \implies \sqrt[3]{(y+2)^2}$

---
#### Comprehensive Condensing Example
$$2\log_3(x) + \frac{1}{2}\log_3(y) - 3\log_3(z)$$

1.  **Move Coefficients Up:** $\log_3(x^2) + \log_3(y^{1/2}) - \log_3(z^3)$
2.  **Merge (Fraction Trick):** $\log_3 \left( \frac{x^2 \cdot y^{1/2}}{z^3} \right)$
3.  **Convert to Radicals:** $\log_3 \left( \frac{x^2\sqrt{y}}{z^3} \right)$

---
#### Critical Pitfalls to Avoid

> [!CAUTION]
> **The Multi-Log Fractional Error:**
> $\log_a(M) - \log_a(N) \neq \frac{\log_a(M)}{\log_a(N)}$
> Condensing subtraction creates a single logarithm containing an internal fraction. Writing a fraction made of two separate logarithms is a major structural error.

> [!WARNING]
> **The Double-Negative Denominator Trap:**
> Given $\log(a) - \log(b) - \log(c)$, notice that *both* $b$ and $c$ are preceded by subtraction signs. This means *both* arguments belong in the denominator, multiplied together: $\log\left(\frac{a}{b \cdot c}\right)$.

### Condensing $\frac{1}{2}\log_3(x) - 3\log_3(x)$

This entry demonstrates how to combine two logarithmic terms with identical bases and identical arguments into a single, simplified logarithmic expression.

---
#### Step-by-Step Condensing

##### Step 1: Move Coefficients Up (Power Property)
Before merging, the space in front of each logarithm must be cleared by moving the scalar coefficients to the exponent position of the arguments.
* **Action:** Move $\frac{1}{2}$ and $3$ up as powers.
$$\log_3(x^{1/2}) - \log_3(x^3)$$
##### Step 2: Merge into a Single Log (Quotient Property)
Because the two terms are separated by subtraction, they combine into a single logarithm where the arguments form a fraction.
* **The Identity Rule:** $\log_a(M) - \log_a(N) = \log_a\left(\frac{M}{N}\right)$
* **Action:** Place the positive term's argument in the numerator and the negative term's argument in the denominator.
$$\log_3\left( \frac{x^{1/2}}{x^3} \right)$$
##### Step 3: Simplify the Internal Argument (Exponent Rules)
Since the bases of the exponential terms ($x$) are the same, simplify the fraction by subtracting the exponents.
* **Rule:** $\frac{x^A}{x^B} = x^{A-B}$
* **Calculation:** $\frac{1}{2} - 3 = \frac{1}{2} - \frac{6}{2} = -\frac{5}{2}$
$$\log_3(x^{-5/2})$$
##### Step 4: Final Formatting (Radicals and Positive Exponents)
To finish the note, rewrite the expression using a radical and move the negative exponent to the denominator if a positive exponent is preferred.
* **Radical Form:** $\log_3\left( \frac{1}{x^{5/2}} \right) \implies \log_3\left( \frac{1}{\sqrt{x^5}} \right)$

---
#### Alternative Method: Combining Like Terms First
Professor Leonard often points out that if the base **and** the argument are identical, you can treat the logs like "apples."
1.  **Identify Like Terms:** Both terms are $\log_3(x)$.
2.  **Subtract Coefficients:** $(\frac{1}{2} - 3) \log_3(x)$
3.  **Result:** $-\frac{5}{2}\log_3(x)$
4.  **Move Coefficient Up:** $\log_3(x^{-5/2})$

> [!TIP]
> **Check Your Work:** Both methods lead to the same result. If you see identical arguments ($x$ and $x$), combining them as like terms first is usually the faster path.

---
#### Final Condensed Form
$$\log_3\left( \frac{1}{\sqrt{x^5}} \right)$$
### Condensing $\log_4(x^2 - 1) - 5\log_4(x + 1)$

This entry outlines the step-by-step process of combining two base-4 logarithms into a single expression, including the essential algebraic simplification of the argument.

---
#### Step-by-Step Condensing

##### Step 1: Move Coefficients Up (Power Property)
Before merging the logarithms, ensure the front of each log term is clear.
* **Action:** Move the coefficient $5$ to the exponent position of the argument $(x+1)$.
$$\log_4(x^2 - 1) - \log_4((x+1)^5)$$
##### Step 2: Merge into a Single Log (Quotient Property)
The subtraction sign indicates that these terms should be merged into a single logarithm containing a fraction.
* **Action:** Place the positive term's argument in the numerator and the subtracted term's argument in the denominator.
$$\log_4 \left( \frac{x^2 - 1}{(x+1)^5} \right)$$
##### Step 3: Factor the Argument
Professor Leonard emphasizes that you are not "done" until the internal argument is as simple as possible. Look for factoring opportunities.
* **Analysis:** The numerator $x^2 - 1$ is a **difference of squares**.
* **Factoring:** $x^2 - 1 = (x - 1)(x + 1)$
$$\log_4 \left( \frac{(x - 1)(x + 1)}{(x+1)^5} \right)$$
##### Step 4: Simplify the Fraction
Cancel out common factors between the numerator and denominator to reach the final form.
* **Action:** Cancel one $(x + 1)$ from the top and bottom.
$$\log_4 \left( \frac{x - 1}{(x+1)^4} \right)$$

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Negative Sign Placement:**
> When moving the coefficient $5$ in Step 1, only move the number, not the negative sign. The subtraction is the "glue" that tells you the argument belongs in the denominator during Step 2.

> [!WARNING]
> **Incomplete Simplification:**
> Leaving the answer as $\log_4 \left( \frac{x^2 - 1}{(x+1)^5} \right)$ is often considered incorrect in a Precalculus or Calculus context. Always check for polynomial factors that can be reduced.

---
#### Final Condensed Form
$$\log_4 \left( \frac{x - 1}{(x+1)^4} \right)$$
### Condensing $\ln\left(\frac{x}{x-1}\right) + \ln\left(\frac{x+1}{x}\right) - \ln(x^2 - 1)$

This entry demonstrates the systematic method for condensing multiple natural logarithms into a single, simplified term by managing fractions and factoring polynomials.

---
#### Step-by-Step Condensing

##### Step 1: Clear Front Coefficients
Check the front of each $\ln$ term for scalar multipliers.
* **Observation:** All coefficients are currently 1. No exponents need to be moved.
##### Step 2: Merge into a Single Log (The Fraction Trick)
Apply the rule: **Positive log arguments go in the numerator; negative (subtracted) log arguments go in the denominator.** * **Action:** Combine the three terms into one large $\ln$ argument.
$$\ln \left[ \frac{\left(\frac{x}{x-1}\right) \cdot \left(\frac{x+1}{x}\right)}{(x^2 - 1)} \right]$$
##### Step 3: Simplify the Internal Numerator
Before dealing with the main denominator, simplify the product of the two fractions at the top.
* **Calculation:** $\frac{x}{x-1} \cdot \frac{x+1}{x}$
* **Action:** The $x$ in the numerator and the $x$ in the denominator cancel out.
$$\frac{x+1}{x-1}$$
* **Current State:** $\ln \left[ \frac{\frac{x+1}{x-1}}{x^2 - 1} \right]$
##### Step 4: Manage the Complex Fraction and Factor
To simplify the division, treat it as multiplying by the reciprocal of the denominator.
* **Reciprocal:** $\frac{x+1}{x-1} \cdot \frac{1}{x^2 - 1}$
* **Factor:** Recognize $x^2 - 1$ as a **difference of squares**: $(x-1)(x+1)$.
$$\frac{x+1}{x-1} \cdot \frac{1}{(x-1)(x+1)}$$
##### Step 5: Final Reduction
Cancel out the common $(x+1)$ terms from the top and bottom.
* **Top:** $x+1$ becomes $1$.
* **Bottom:** $(x-1) \cdot (x-1)$ becomes $(x-1)^2$.
$$\frac{1}{(x-1)^2}$$

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **Denominator Placement:**
> Even though $(x^2 - 1)$ is a single term, it is being subtracted. This means it *must* join the denominator of the unified log. When combined with the fractions already present, it effectively multiplies the existing denominator.

> [!WARNING]
> **Internal Factor Cancellation:**
> Always look for "hidden" cancellations. In this problem, failing to factor the difference of squares would leave the expression in an unsimplified state, which does not meet the standard for a final answer in Precalculus.

---
#### Final Condensed Form
$$\ln \left[ \frac{1}{(x-1)^2} \right]$$
*Which can also be written as:* $-2\ln(x-1)$
### Condensing $21\log_3 \sqrt[3]{x} + \log_3 9 + 2\log_3 x - \log_3 9$

This entry demonstrates how to condense a multi-term base-3 logarithmic expression by identifying additive inverses and applying exponent rules.

---
#### Step-by-Step Condensing

##### Step 1: Identify and Cancel Additive Inverses
Before performing any logarithmic properties, scan the expression for identical terms with opposite signs.
* **Observation:** The expression contains $+ \log_3 9$ and $- \log_3 9$.
* **Action:** These terms sum to zero and cancel each other out immediately.
$$21\log_3 \sqrt[3]{x} + 2\log_3 x$$
##### Step 2: Convert Radicals to Rational Exponents
Rewrite the root as a fractional power to make the upcoming Power Property step easier to calculate.
* **Action:** Convert $\sqrt[3]{x}$ to $x^{1/3}$.
$$21\log_3 (x^{1/3}) + 2\log_3 x$$
##### Step 3: Move Coefficients Up (Power Property)
Clear the space in front of each logarithm by moving the scalar coefficients to the exponent position.
* **Action:** Move $21$ and $2$ up as powers.
$$\log_3 ((x^{1/3})^{21}) + \log_3 (x^2)$$
##### Step 4: Simplify the Internal Exponents
Apply the power-to-a-power rule: $(x^a)^b = x^{a \cdot b}$.
* **Calculation:** $\frac{1}{3} \cdot 21 = 7$.
$$\log_3 (x^7) + \log_3 (x^2)$$
##### Step 5: Merge into a Single Log (Product Property)
Since the two terms are separated by addition, they combine into a single logarithm where the arguments are multiplied together.
* **The Identity Rule:** $\log_a(M) + \log_a(N) = \log_a(M \cdot N)$
* **Action:** Multiply the internal arguments.
$$\log_3 (x^7 \cdot x^2)$$
##### Step 6: Final Reduction
Apply the product rule for exponents: $x^a \cdot x^b = x^{a+b}$.
* **Calculation:** $7 + 2 = 9$.
$$\log_3 (x^9)$$

---
#### Alternative Evaluation Check
Look at the result: $\log_3 (x^9)$. While this is the condensed form, the Power Property could also be used to write this as $9\log_3 x$ if the goal was expansion. For condensing purposes, we keep it as a single log.

> [!TIP]
> **Check for Cancellation Early:**
> As seen in Step 1, identifying that $\log_3 9$ and $-\log_3 9$ cancel out saves significant time. Even if you had evaluated them (as $2 - 2$), the result remains the same.

---

#### Final Condensed Form
$$\log_3 (x^9)$$

### Condensing $2\log(x+1) - \frac{1}{4}\log(x-1) + \frac{3}{8}\log(2x+3) - \frac{1}{5}\log x - 4\log 2 + \log 12$

This entry demonstrates how to condense a long, multi-term logarithmic expression using Professor Leonard’s efficient "Fraction Trick" methodology.

---

#### Step-by-Step Condensing

##### Step 1: Move Coefficients Up (Power Property)
Before merging, the coefficient in front of every logarithm must be moved to the exponent of its argument.
* **Action:** Apply $r \cdot \log(M) \implies \log(M^r)$ to all terms.
$$\log(x+1)^2 - \log(x-1)^{1/4} + \log(2x+3)^{3/8} - \log(x^{1/5}) - \log(2^4) + \log(12)$$

##### Step 2: Simplify Constant Powers
Evaluate any purely numerical arguments to simplify the expression before the final merge.
* **Calculation:** $2^4 = 16$.
$$\log(x+1)^2 - \log(x-1)^{1/4} + \log(2x+3)^{3/8} - \log(x^{1/5}) - \log(16) + \log(12)$$

##### Step 3: Merge into a Single Log (The Fast Fraction Trick)
Draw one large log symbol and a single fraction bar. Sort the arguments based on the sign in front of their respective log terms.
* **Numerator (Positive Logs):** $(x+1)^2$, $(2x+3)^{3/8}$, and $12$.
* **Denominator (Negative Logs): $(x-1)^{1/4}$, $x^{1/5}$, and $16$.
$$\log \left[ \frac{12(x+1)^2(2x+3)^{3/8}}{16(x-1)^{1/4}x^{1/5}} \right]$$

##### Step 4: Simplify Coefficients and Convert to Radicals
Finalize the note by reducing numerical fractions and converting rational exponents back into roots.
* **Numerical Reduction:** $\frac{12}{16} = \frac{3}{4}$.
* **Convert to Roots:** * $(2x+3)^{3/8} \implies \sqrt[8]{(2x+3)^3}$
    * $(x-1)^{1/4} \implies \sqrt[4]{x-1}$
    * $x^{1/5} \implies \sqrt[5]{x}$

---

#### Final Condensed Form
$$\log \left[ \frac{3(x+1)^2 \sqrt[8]{(2x+3)^3}}{4 \sqrt[4]{x-1} \sqrt[5]{x}} \right]$$

> [!TIP]
> **The Denominator Rule:**
> Notice that even though $-\log(16)$ and $-\log(x^{1/5})$ are separate terms, they both end up in the denominator multiplied together. As Professor Leonard says: "If it's minus, it goes on the bottom; if it's plus, it goes on the top."

---

#### Summary Table of Properties Used
| Property              | Formula                       |
| :-------------------- | :---------------------------- |
| **Power Property**    | $r \log M = \log M^r$         |
| **Product Property**  | $\log M + \log N = \log(MN)$  |
| **Quotient Property** | $\log M - \log N = \log(M/N)$ |
## 2026-May-20 - How to Change the Base of a Logarithm (Precalculus - College Algebra 61) : 
https://www.youtube.com/watch?v=tgcFt8zGnNE&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=64
### How to Change the Base of a Logarithm

The Change of Base Formula is a vital computational tool that allows you to rewrite any logarithm into a different base. Historically, this was necessary because calculators only possessed buttons for Common Logs ($\log_{10}$) and Natural Logs ($\ln$).

---
#### The Change of Base Formula
To change $\log_{b}M$ into a new base $a$:

$$\log_{b}M = \frac{\log_{a}M}{\log_{a}b}$$
**The "Memory Trick":**
* The **Argument** ($M$) is "higher" in the original expression, so it goes in the **Numerator**.
* The **Base** ($b$) is "lower" in the original expression, so it goes in the **Denominator**.
- Use this Anemonic - Mnemonic Device : The **Argument Goes in the Attic** (Numerator) and the **Base Goes in the Basement** (Denominator)
---
#### Why Use Change of Base?

1.  **Calculator Evaluation:** Most calculators cannot directly compute $\log_{3}7$. By changing the base to $10$ or $e$, you can find the decimal approximation.
2.  **Standardizing Expressions:** If an equation contains logarithms with different bases (e.g., one term is $\log_{2}$ and another is $\log_{8}$), you must change them to a common base to combine or solve them.
3.  **Simplification:** Some complex logarithmic products can be simplified by converting everything to Natural Logs and cancelling terms.

---
#### Common Application: The "Calculator Move"
When solving for a decimal value, you generally choose base $10$ or base $e$. Both will yield the exact same result.

**Example: Evaluate $\log_{5}12$**

* **Using Common Log (Base 10):**
    $$\frac{\log(12)}{\log(5)} \approx 1.544$$
* **Using Natural Log (Base $e$):**
    $$\frac{\ln(12)}{\ln(5)} \approx 1.544$$

---
#### Step-by-Step Procedure

##### Step 1: Identify your $M$ and $b$
Look at the expression $\log_{b}M$. Explicitly note which value is the argument and which is the base.
##### Step 2: Choose your New Base
* Choose **Base 10** ($\log$) or **Base $e$** ($\ln$) if you need a decimal.
* Choose a base that matches other logs in your problem if you are simplifying.
##### Step 3: Set up the Fraction
Place the log of the argument over the log of the old base using your new chosen base.
##### Step 4: Evaluate or Simplify
Use a calculator for decimals, or use logarithmic properties to simplify the resulting fraction if the numbers are powers of the same base.

---
#### Critical Pitfalls to Avoid

> [!CAUTION]
> **The Single-Log Fraction Error:**
> The Change of Base formula results in a fraction of **two separate logarithms**: $\frac{\log M}{\log b}$. 
> It is **NOT** equal to $\log\left(\frac{M}{b}\right)$. The Quotient Property and the Change of Base Formula are frequently confused but are mathematically distinct operations.

> [!WARNING]
> **Argument/Base Swap:**
> Ensure the original base $b$ always ends up in the denominator. A common error is accidentally flipping the fraction to $\frac{\log b}{\log M}$, which will result in the reciprocal of the correct answer.

---
#### Summary Table

| Goal                  | Original    | Change of Base Setup        |
| :-------------------- | :---------- | :-------------------------- |
| **Decimal (Common)**  | $\log_{b}M$ | $\log(M) / \log(b)$         |
| **Decimal (Natural)** | $\log_{b}M$ | $\ln(M) / \ln(b)$           |
| **Algebraic Shift**   | $\log_{2}x$ | $\log_{8}(x) / \log_{8}(2)$ |
### Evaluating $\log_{\sqrt{5}}(7)$ using Change of Base

This entry demonstrates the calculation of a logarithm with an irrational base by converting it into a form compatible with standard calculators.

---
#### Step-by-Step Evaluation

##### Step 1: Identify the Argument and the Base
Before setting up the fraction, identify the "Attic" and "Basement" components.
* **Argument ($M$):** $7$ (This goes in the **Attic/Numerator**)
* **Base ($b$):** $\sqrt{5}$ (This goes in the **Basement/Denominator**)
##### Step 2: Set up the Change of Base Formula
Choose either Common Log ($\log$) or Natural Log ($\ln$). Professor Leonard typically uses $\ln$ for these evaluations.
* **Formula:** $\log_b M = \frac{\ln M}{\ln b}$
* **Setup:** $$\frac{\ln(7)}{\ln(\sqrt{5})}$$
##### Step 3: Simplify the Denominator (Optional but Recommended)
To make the calculation cleaner, convert the square root into a rational exponent and use the Power Property.
* $\sqrt{5} = 5^{1/2}$
* $\ln(5^{1/2}) = \frac{1}{2}\ln(5)$
* **Revised Setup:**
$$\frac{\ln(7)}{\frac{1}{2}\ln(5)}$$

##### Step 4: Calculator Evaluation
Perform the division to find the decimal approximation.
* $\ln(7) \approx 1.9459$
* $\ln(\sqrt{5}) \approx 0.8047$
* **Division:** $1.9459 \div 0.8047 \approx 2.418$

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The "Basement" Error:**
> Ensure the $\sqrt{5}$ is inside its own logarithm in the denominator. A common mistake is writing $\frac{\ln(7)}{\sqrt{5}}$, which is mathematically incorrect.

> [!TIP]
> **Check Your Work:**
> You can verify the result by raising the original base to your answer: $(\sqrt{5})^{2.418}$. It should equal approximately $7$.

---

#### Final Evaluated Form
$$\frac{\ln(7)}{\ln(\sqrt{5})} \approx 2.418$$
### Evaluating $\log_{\pi}(e)$ using Change of Base

This entry demonstrates the calculation of a logarithm involving two transcendental constants ($\pi$ and $e$) by converting the expression into a format suitable for calculator evaluation.

---
#### Step-by-Step Evaluation

##### Step 1: Identify the Argument and the Base
Apply the "Attic and Basement" mnemonic to determine the structure of the fraction.
* **Argument ($M$):** $e$ (The argument goes in the **Attic/Numerator**).
* **Base ($b$):** $\pi$ (The base goes in the **Basement/Denominator**).
##### Step 2: Apply the Change of Base Formula
While you can use any base, choosing the Natural Log ($\ln$) is the most efficient path here because the argument is $e$.
* **Formula:** $\log_b M = \frac{\ln M}{\ln b}$
* **Setup:** $$\frac{\ln(e)}{\ln(\pi)}$$
##### Step 3: Simplify the Numerator
Recall the **Identity Property** of logarithms: when the base of the log matches the argument, the expression evaluates to 1. Since $\ln$ is a base-$e$ logarithm:
* $\ln(e) = 1$
* **Revised Setup:**
$$\frac{1}{\ln(\pi)}$$
##### Step 4: Calculator Evaluation
Perform the final division using the decimal value for $\ln(\pi)$.
* $\ln(\pi) \approx 1.1447$
* **Calculation:** $1 \div 1.1447 \approx 0.8736$

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Constant Confusion:**
> Do not confuse $e$ and $\pi$. Even though they are both famous constants, the formula requires them to stay in their specific positions. Swapping them to $\frac{\ln(\pi)}{\ln(e)}$ would result in $\ln(\pi)$, which is the reciprocal of the correct answer.

> [!TIP]
> **Why Choose Natural Log?**
> If you had used the Common Log ($\log_{10}$), the setup would be $\frac{\log(e)}{\log(\pi)}$. Both $\log(e)$ and $\log(\pi)$ would require calculator steps. By choosing $\ln$, the numerator simplifies to $1$ automatically, reducing the margin for input error.

---

#### Final Evaluated Form
$$\frac{1}{\ln(\pi)} \approx 0.8736$$
## 2026-May-22 - Solving Logarithms with Common Bases (Precalculus - College Algebra 62) :
https://www.youtube.com/watch?v=82fonULPl64&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=65
### Solving Logarithms with Common Bases

This technique focuses on solving logarithmic equations by utilizing the **One-to-One Property**. This property allows you to "drop" the logarithms from an equation if both sides consist of exactly one logarithm with the same base.

---
#### The One-to-One Property of Logarithms
If two logarithms with the identical base $b$ are equal to each other, then their arguments must also be equal.

$$\log_b(M) = \log_b(N) \implies M = N$$

---
#### The Step-by-Step Solving Strategy

##### Step 1: Condense Both Sides
Before you can apply the One-to-One property, you must have **exactly one** logarithm on the left and **exactly one** logarithm on the right.
* Use the **Product Property** to combine addition into multiplication.
* Use the **Quotient Property** to combine subtraction into division.
* Use the **Power Property** to move coefficients to the exponents.
##### Step 2: Ensure Bases Match
Verify that the base on the left ($b$) is identical to the base on the right ($b$). If the bases do not match, this property cannot be applied directly.
##### Step 3: "Drop" the Logs (Set Arguments Equal)
Once the equation is in the form $\log_b(M) = \log_b(N)$, remove the log symbols and set the arguments equal to each other:
$$M = N$$
##### Step 4: Solve the Resulting Equation
Solve the remaining algebraic equation (which will typically be linear or quadratic).
##### Step 5: Check for Extraneous Solutions (CRITICAL)
Logarithms have a restricted domain: **the argument must always be greater than zero ($> 0$).**
* Plug your solution(s) back into the **original** logarithmic arguments.
* If a solution results in taking the log of a negative number or zero, that solution is **extraneous** and must be discarded.

---
#### Comprehensive Example

$$\log_3(x) + \log_3(x-8) = \log_3(9)$$

1.  **Condense the Left Side:**
    $$\log_3(x(x-8)) = \log_3(9)$$
2.  **Apply One-to-One Property:**
    $$x(x-8) = 9$$
3.  **Solve the Quadratic:**
    $$x^2 - 8x - 9 = 0$$
    $$(x - 9)(x + 1) = 0$$
    $$x = 9, \quad x = -1$$
4.  **Check for Extraneous Solutions:**
    * Test $x = 9$: $\log_3(9)$ and $\log_3(9-8)$ are both logs of positive numbers. (Valid)
    * Test $x = -1$: $\log_3(-1)$ is the log of a negative number. (**Extraneous**)

**Final Answer:** $x = 9$

---
#### Critical Pitfalls to Avoid

> [!CAUTION]
> **The "Log Drop" Error:**
> You cannot drop logs if there are multiple logs on one side. For example, in $\log(x) + \log(2) = \log(10)$, you **cannot** simply say $x + 2 = 10$. You must condense first: $\log(2x) = \log(10) \implies 2x = 10$.

> [!WARNING]
> **The Constant Term Trap:**
> This property only works if every term in the equation is a logarithm. If the equation is $\log_b(M) = N$ (where $N$ is a constant), you must use the **Definition of a Logarithm** ($b^N = M$) to solve it instead.

---
#### Summary of Necessary Properties
| Property     | Formula                               |
| :----------- | :------------------------------------ |
| **Product**  | $\log_b(M) + \log_b(N) = \log_b(MN)$  |
| **Quotient** | $\log_b(M) - \log_b(N) = \log_b(M/N)$ |
| **Power**    | $P\log_b(M) = \log_b(M^P)$            |
### Solving $\log_4(x+2) = \log_4(8)$ via the One-to-One Property

This entry demonstrates the simplest application of the One-to-One Property, where logarithms are already isolated on both sides of the equation.

---
#### Step-by-Step Solution

##### Step 1: Verify the Structure
Before proceeding, ensure the equation meets the criteria for the One-to-One Property:
1.  Exactly one log term on the left and one on the right.
2.  The bases are identical (both are base 4).
3.  The coefficients in front of both logs are exactly 1.
##### Step 2: Apply the One-to-One Property
Since the logarithmic functions are identical, their arguments must also be equal to satisfy the equation.
* **The Identity Rule:** $\log_b(M) = \log_b(N) \implies M = N$
* **Action:** "Drop" the logs and set the arguments equal.
$$x + 2 = 8$$

##### Step 3: Solve for $x$
Solve the remaining linear equation.
* **Action:** Subtract 2 from both sides.
$$x = 6$$
##### Step 4: Check for Extraneous Solutions
Always verify that the result keeps the original argument positive.
* **Test:** Plug $x = 6$ into the original argument $(x + 2)$.
* **Check:** $6 + 2 = 8$. Since $8 > 0$, the solution is valid.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Addition Distraction:**
> A common mistake is trying to "subtract" $\log_4$ from both sides as if it were a variable. Remember that $\log_4$ is a function; we are using the property of that function to equate the arguments.

---

#### Final Solution
$$x = 6$$
### Solving $3\log_2(x) = -\log_2(27)$ via the One-to-One Property

This entry demonstrates how to solve a logarithmic equation by condensing both sides into single logarithms with identical bases, allowing the arguments to be set equal.

---
#### Step-by-Step Solution
##### Step 1: Clear Front Coefficients (Power Property)
Before applying the One-to-One property, the logarithms on both sides must have a coefficient of exactly 1.
* **Action:** Move the $3$ on the left and the $-1$ (from the negative sign) on the right up to the exponent positions of the arguments.
$$\log_2(x^3) = \log_2(27^{-1})$$
##### Step 2: Apply the One-to-One Property
Since we now have exactly one $\log_2$ on each side, we can "drop" the logs and set the arguments equal to each other.
* **The Identity Rule:** $\log_b(M) = \log_b(N) \implies M = N$
* **Action:**
$$x^3 = 27^{-1}$$

##### Step 3: Solve for $x$
Rewrite the negative exponent as a fraction and solve the resulting power equation.
* **Rewrite:** $x^3 = \frac{1}{27}$
* **Action:** Take the cube root ($\sqrt[3]{\quad}$) of both sides to isolate $x$.
$$x = \sqrt[3]{\frac{1}{27}}$$
$$x = \frac{1}{3}$$

##### Step 4: Check for Extraneous Solutions
Logarithmic arguments must always be positive ($>0$). You must verify the solution in the **original** equation.
* **Test:** Plug $x = \frac{1}{3}$ back into the original argument on the left side: $3\log_2(x)$.
* **Check:** Since $\frac{1}{3} > 0$, the argument remains valid.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Negative Sign Trap:**
> You cannot "drop the logs" if a negative sign is still sitting in front of the log. $\log_2(x^3) = -\log_2(27)$ is not the same as $x^3 = -27$. The negative sign must be moved to the exponent first.

> [!WARNING]
> **Domain Restrictions:**
> If the algebra had resulted in a negative number (e.g., $x = -1/3$), it would be an **extraneous solution** because you cannot take the logarithm of a negative number in the real number system.

---
#### Final Solution
$$x = \frac{1}{3}$$
### Solving $\log_a(x-1) - \log_a(x+6) = \log_a(x-2) - \log_a(x+3)$ via the One-to-One Property

This entry demonstrates solving a logarithmic equation where both sides contain multiple terms that must be condensed before the One-to-One Property can be applied.

---
#### Step-by-Step Solution

##### Step 1: Condense Both Sides (Quotient Property)
Before we can "drop" the logs, we must have exactly one logarithm on the left and exactly one on the right. Since both sides involve subtraction, we apply the Quotient Property.
* **The Identity Rule:** $\log_a(M) - \log_a(N) = \log_a\left(\frac{M}{N}\right)$
* **Action:** Rewrite both sides as single logarithms containing fractions.
$$\log_a\left( \frac{x-1}{x+6} \right) = \log_a\left( \frac{x-2}{x+3} \right)$$
##### Step 2: Apply the One-to-One Property
Now that we have the form $\log_a(M) = \log_a(N)$, we can set the internal arguments equal to each other.
* **Property:** $\log_a(M) = \log_a(N) \implies M = N$
* **Action:**
$$\frac{x-1}{x+6} = \frac{x-2}{x+3}$$

##### Step 3: Solve the Rational Equation (Cross-Multiply)
To clear the fractions, cross-multiply the numerators and denominators.
* **Action:** $(x-1)(x+3) = (x-2)(x+6)$
* **Expand (FOIL):**
$$x^2 + 3x - x - 3 = x^2 + 6x - 2x - 12$$
$$x^2 + 2x - 3 = x^2 + 4x - 12$$
##### Step 4: Isolate $x$
Simplify the equation by moving all variable terms to one side and constants to the other.
* **Action:** Subtract $x^2$ from both sides (they cancel out).
$$2x - 3 = 4x - 12$$
* **Action:** Subtract $2x$ from both sides and add $12$ to both sides.
$$9 = 2x$$
$$x = 4.5 \quad \text{or} \quad x = \frac{9}{2}$$
##### Step 5: Check for Extraneous Solutions
Verify that $x = 4.5$ keeps all original logarithmic arguments positive ($>0$).
* **Check Arguments:**
    1. $(4.5 - 1) = 3.5$ (Positive)
    2. $(4.5 + 6) = 10.5$ (Positive)
    3. $(4.5 - 2) = 2.5$ (Positive)
    4. $(4.5 + 3) = 7.5$ (Positive)
* **Result:** Since all arguments remain positive, the solution is valid.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Condensing Requirement:**
> Never try to "drop the logs" term-by-term. You cannot say $(x-1) - (x+6) = (x-2) - (x+3)$. Logarithms must be condensed into a single "block" on each side first.

---
#### Final Solution
$$x = 4.5$$
### Solving $\log_3 x - 2 \log_3 5 = \log_3 (x+1) - 2 \log_3 10$ via the One-to-One Property

This entry demonstrates solving a logarithmic equation by using the Power and Quotient properties to condense both sides into single logarithms before equating the arguments.

---
#### Step-by-Step Solution
##### Step 1: Move Coefficients Up (Power Property)
Before condensing the subtraction into division, clear the numbers in front of the logs by moving them to the exponent positions.
* **Action:** Move the $2$ on the left and the $2$ on the right up as powers.
$$\log_3 x - \log_3 (5^2) = \log_3 (x+1) - \log_3 (10^2)$$
* **Simplify Constants:**
$$\log_3 x - \log_3 25 = \log_3 (x+1) - \log_3 100$$
##### Step 2: Condense Both Sides (Quotient Property)
Combine the terms on each side into a single logarithm. Since the terms are separated by subtraction, they form fractions.
* **The Identity Rule:** $\log_b M - \log_b N = \log_b (\frac{M}{N})$
* **Action:**
$$\log_3 \left( \frac{x}{25} \right) = \log_3 \left( \frac{x+1}{100} \right)$$

##### Step 3: Apply the One-to-One Property
Now that we have exactly one $\log_3$ on each side, we can "drop" the logs and set the internal arguments equal.
* **Property:** $\log_b M = \log_b N \implies M = N$
* **Action:**
$$\frac{x}{25} = \frac{x+1}{100}$$
##### Step 4: Solve the Rational Equation
Clear the fractions by cross-multiplying or by multiplying both sides by a common denominator ($100$).
* **Action:** Multiply both sides by $100$.
$$100 \left( \frac{x}{25} \right) = 100 \left( \frac{x+1}{100} \right)$$
$$4x = x + 1$$
* **Isolate $x$:**
$$3x = 1$$
$$x = \frac{1}{3}$$
##### Step 5: Check for Extraneous Solutions
Ensure the result keeps the original logarithmic arguments positive ($>0$).
* **Test:**
    * Left side: $\log_3(1/3)$ → Argument $1/3$ is positive.
    * Right side: $\log_3(1/3 + 1) = \log_3(4/3)$ → Argument $4/3$ is positive.
* **Result:** The solution is valid.

---

#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **Premature Log Dropping:**
> Never try to solve this as $x - 25 = x + 1 - 100$. You **must** condense the logarithms into single expressions on each side before the log symbols can be removed.

---
#### Final Solution
$$x = \frac{1}{3}$$
### Solving $3(\log_7 x - \log_7 2) = 2 \log_7 4$ via the One-to-One Property

This entry demonstrates solving a logarithmic equation by distributing coefficients and using the Power and Quotient properties to condense both sides into single logarithms.

---
#### Step-by-Step Solution
##### Step 1: Distribute or Move the Coefficient
You have two options here: distribute the $3$ or move the entire $3$ up as a power for the condensed log. Following the standard procedural flow:
* **Action:** Move the $3$ and the $2$ to the exponent positions using the Power Property.
$$\log_7 (x - \log_7 2)^3 \text{ is incorrect.}$$
* **Correct Action (Professor Leonard Style):** Move the coefficients up first.
$$3\log_7 x - 3\log_7 2 = 2\log_7 4$$
$$\log_7 (x^3) - \log_7 (2^3) = \log_7 (4^2)$$
* **Simplify Constants:**
$$\log_7 (x^3) - \log_7 8 = \log_7 16$$
##### Step 2: Condense the Left Side (Quotient Property)
Combine the two logarithms on the left into a single logarithm. Since they are separated by subtraction, the arguments form a fraction.
* **The Identity Rule:** $\log_b M - \log_b N = \log_b \left(\frac{M}{N}\right)$
* **Action:**
$$\log_7 \left( \frac{x^3}{8} \right) = \log_7 16$$
##### Step 3: Apply the One-to-One Property
Now that we have exactly one $\log_7$ on each side, we can "drop" the logs and set the internal arguments equal.
* **Property:** $\log_b M = \log_b N \implies M = N$
* **Action:**
$$\frac{x^3}{8} = 16$$
##### Step 4: Solve for $x$
Isolate the $x^3$ term and then take the cube root.
* **Action:** Multiply both sides by $8$.
$$x^3 = 16 \cdot 8$$
$$x^3 = 128$$
* **Action:** Take the cube root of both sides.
$$x = \sqrt[3]{128}$$
* **Simplify the Radical:** Since $128 = 64 \cdot 2$ and $64$ is $4^3$:
$$x = 4\sqrt[3]{2}$$
##### Step 5: Check for Extraneous Solutions
Ensure the result keeps the original logarithmic arguments positive ($>0$).
* **Test:** Plug $x = 4\sqrt[3]{2}$ into the original argument $\log_7 x$.
* **Check:** $4\sqrt[3]{2}$ is a positive value. The solution is valid.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **Power Property Errors:**
> Ensure that the coefficient applies to the *entire* argument. When we moved the $3$ in Step 1, it became the exponent for $x$ and $2$ individually after distribution, or you could have condensed $(x/2)$ first and raised the whole fraction to the $3rd$ power. Both lead to $x^3/8$.

---
#### Final Solution
$$x = 4\sqrt[3]{2}$$
## 2026-May-23 - Solving Logarithmic Equations with Exponentials (Precalculus - College Algebra 63) :
https://www.youtube.com/watch?v=jNUyVClUQfc&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=64
### Solving Logarithmic Equations with Exponentials

This technique is used when an equation contains a logarithm on one side and a constant (non-logarithm) on the other. Because you cannot use the One-to-One Property to "drop" the logs, you must transform the equation into its exponential form to isolate the variable.

---
#### The Fundamental Definition
To solve these equations, you must be able to convert between logarithmic and exponential forms fluently:

$$\log_b(M) = N \iff b^N = M$$

**The "Claw" or "Circle" Method:**
1. Start at the **Base** ($b$).
2. Swing around to the **other side** of the equals sign to pick up the **Exponent** ($N$).
3. Set it equal to the **Argument** ($M$).

---
#### The Step-by-Step Solving Strategy

##### Step 1: Isolate the Logarithm
Before you can convert to an exponential, the logarithm must be completely alone on one side of the equation.
* **Undo Addition/Subtraction:** Move any trailing constants to the other side.
* **Undo Multiplication:** Divide by any coefficients in front of the log.
* **Result:** You should have the form $\log_b(\text{something}) = \text{number}$.
##### Step 2: Condense if Necessary
If there are multiple logs on one side and a constant on the other, use the Product or Quotient properties to merge them into **one single log** first.
##### Step 3: Rewrite in Exponential Form
Apply the definition $\log_b(M) = N \implies b^N = M$. This "releases" the variable from inside the logarithmic function.
##### Step 4: Solve for $x$
The resulting equation will be algebraic (linear, quadratic, etc.). Solve using standard methods.
##### Step 5: Check for Extraneous Solutions (MANDATORY)
Since the domain of a logarithm is $(0, \infty)$, you must ensure your answer does not cause the argument of any **original** logarithm to be zero or negative.

---
#### Comprehensive Example

$$\log_2(x) + \log_2(x-2) = 3$$

1.  **Condense:** $\log_2(x(x-2)) = 3$
2.  **Rewrite:** $2^3 = x(x-2)$
3.  **Evaluate Power:** $8 = x^2 - 2x$
4.  **Solve Quadratic:** $x^2 - 2x - 8 = 0 \implies (x-4)(x+2) = 0$
5.  **Check:** * $x = 4$: Both $\log_2(4)$ and $\log_2(4-2)$ are positive. (**Valid**)
    * $x = -2$: $\log_2(-2)$ is undefined. (**Extraneous**)

**Final Answer:** $x = 4$

---
#### Critical Pitfalls to Avoid

> [!CAUTION]
> **The Base Assumption:**
> If a base is not written (e.g., $\log(x) = 2$), it is the **Common Log** (base 10). If it is written as $\ln(x)$, it is the **Natural Log** (base $e$). 
> * $\log(x) = 2 \implies 10^2 = x$
> * $\ln(x) = 2 \implies e^2 = x$

> [!WARNING]
> **Premature Conversion:**
> Never try to convert to exponential form while there is still a coefficient in front of the log. 
> * Incorrect: $2\log_3(x) = 4 \implies 3^4 = 2x$
> * Correct: $\log_3(x) = 2 \implies 3^2 = x$

---
#### Summary of Necessary Forms
| Log Form        | Exponential Form |
| :-------------- | :--------------- |
| $\log_b(M) = N$ | $b^N = M$        |
| $\ln(M) = N$    | $e^N = M$        |
| $\log(M) = N$   | $10^N = M$       |
### Solving $\log(x+6) = 1$ via Exponential Conversion

This entry demonstrates how to solve a logarithmic equation when one side is a constant. Because there is no logarithm on the right side to "drop," we must use the definition of a logarithm to rewrite the equation in exponential form.

---
#### Step-by-Step Solution

##### Step 1: Identify the Base
When a logarithm is written as "$\log$" without a visible subscript, it is the **Common Logarithm**.
* **The Hidden Base:** $10$
* **Rewrite for Clarity:** $\log_{10}(x+6) = 1$
##### Step 2: Rewrite in Exponential Form
Apply the fundamental definition: $\log_b(M) = N \iff b^N = M$. Use the "Circle" or "Claw" method to release the argument from the logarithm.
* **Base:** $10$
* **Exponent:** $1$
* **Argument:** $x+6$
* **Action:** $$10^1 = x + 6$$
* ##### Step 3: Solve for $x$
Evaluate the power and isolate the variable using inverse operations.
* **Simplify:** $10 = x + 6$
* **Action:** Subtract $6$ from both sides.
$$x = 4$$
##### Step 4: Check for Extraneous Solutions
Verify that the result keeps the original argument positive ($> 0$).
* **Test:** Plug $x = 4$ into the original argument $(x + 6)$.
* **Check:** $4 + 6 = 10$. Since $10 > 0$, the solution is valid.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Base 10 Assumption:**
> Forgetting that the base is $10$ is the most common error in this problem type. Students often mistakenly use the number on the right side as the base or assume the base is $e$. 

> [!WARNING]
> **Isolating First:**
> If there had been a number in front of the log (e.g., $2\log(x+6) = 1$), you would have to divide by that number *before* converting to exponential form.

---
#### Final Solution
$$x = 4$$
### Solving $3\log_2(x-1) + \log_2 4 = 5$ via Condensing (Professor Leonard Method)

In the video, Professor Leonard demonstrates that you can solve these by condensing the left side into a single logarithm using the Power and Product properties before converting to an exponential.

---
#### Step-by-Step Solution

##### Step 1: Move the Coefficient (Power Property)
Before combining the logarithms, the coefficient in front of the first log must be moved to the exponent of the argument.
* **Action:** Move the $3$ to the power of $(x-1)$.
$$\log_2(x-1)^3 + \log_2 4 = 5$$
##### Step 2: Condense the Left Side (Product Property)
Since the two logarithms have the same base and are being added, combine their arguments into a single logarithm using multiplication.
* **The Identity Rule:** $\log_b M + \log_b N = \log_b (M \cdot N)$
* **Action:**
$$\log_2 [4(x-1)^3] = 5$$
##### Step 3: Rewrite in Exponential Form
Now that the left side is a single logarithm and the right side is a constant, apply the definition of a logarithm to "release" the argument.
* **Base:** $2$
* **Exponent:** $5$
* **Argument:** $4(x-1)^3$
* **Action:**
$$2^5 = 4(x-1)^3$$
##### Step 4: Solve for $x$
Evaluate the power and use inverse operations to isolate $x$.
* **Evaluate $2^5$:** $32 = 4(x-1)^3$
* **Divide by 4:** $$8 = (x-1)^3$$
* **Take the Cube Root:** $$\sqrt[3]{8} = \sqrt[3]{(x-1)^3}$$
$$2 = x - 1$$
* **Final Step:** Add $1$ to both sides.
$$x = 3$$
##### Step 5: Check for Extraneous Solutions
Verify that the result keeps the original argument positive ($> 0$).
* **Test:** Plug $x = 3$ into the original argument $(x-1)$.
* **Check:** $3 - 1 = 2$. Since $2 > 0$, the solution is valid.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Multiplication Order:**
> When condensing in Step 2, ensure the coefficient ($4$) is multiplied by the *entire* argument $(x-1)^3$. Do not accidentally multiply the $4$ inside the parentheses before handling the exponent.

---
#### Final Solution
$$x = 3$$
### Solving $\log(2x+1) = 1 + \log(x-2)$ via Exponential Conversion

This problem follows Professor Leonard's strategy for equations where some terms are logarithms and others are constants. To solve these, you must move all logarithms to one side to condense them before converting to exponential form.

---
#### Step-by-Step Solution

##### Step 1: Isolate the Logarithms
To apply logarithmic properties, move all log terms to the left side and leave the constant on the right.
* **Action:** Subtract $\log(x-2)$ from both sides.
$$\log(2x+1) - \log(x-2) = 1$$
##### Step 2: Condense the Left Side (Quotient Property)
Since the logs share the same base (Base 10) and are separated by subtraction, combine them into a single logarithm using division.
* **The Identity Rule:** $\log_b M - \log_b N = \log_b \left(\frac{M}{N}\right)$
* **Action:**
$$\log \left( \frac{2x+1}{x-2} \right) = 1$$
##### Step 3: Rewrite in Exponential Form
Identify the base of the common log (10) and use the "Circle" method to convert the equation into its exponential equivalent.
* **Base:** $10$
* **Exponent:** $1$
* **Argument:** $\frac{2x+1}{x-2}$
* **Action:**
$$10^1 = \frac{2x+1}{x-2}$$
##### Step 4: Solve the Rational Equation
Eliminate the fraction by multiplying both sides by the denominator $(x-2)$.
* **Action:** $10(x-2) = 2x + 1$
* **Distribute:** $10x - 20 = 2x + 1$
* **Isolate $x$:** * Subtract $2x$ from both sides: $8x - 20 = 1$
    * Add $20$ to both sides: $8x = 21$
    * Divide by 8:
$$x = \frac{21}{8} \quad \text{or} \quad x = 2.625$$
##### Step 5: Check for Extraneous Solutions
Verify the result in the **original** logarithmic arguments. Both must be positive ($>0$).
1.  **Argument 1:** $2(2.625) + 1 = 6.25$ (Positive)
2.  **Argument 2:** $2.625 - 2 = 0.625$ (Positive)
* **Result:** The solution is valid.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Constant Trap:**
> Do not try to "drop the logs" while the constant $1$ is present. You cannot say $(2x+1) = 1 + (x-2)$. The One-to-One property only works when the equation is $\text{log} = \text{log}$. Because of the $1$, you **must** condense and convert to exponential form.

> [!WARNING]
> **Base Awareness:**
> Always remember that "$\log$" without a subscript is base 10. If you accidentally used $e$ or $2$ as the base, the entire algebraic path would be incorrect.

---
#### Final Solution
$$x = 2.625$$
### Solving $\log_6(x+4) = 1 - \log_6(x+3)$ via Exponential Conversion

In this problem, Professor Leonard demonstrates how to handle an equation where logarithms are split across both sides of the equals sign along with a constant. The goal is to group the logs, condense them, and then convert to exponential form.

---
#### Step-by-Step Solution

##### Step 1: Isolate the Logarithms
Move all logarithmic terms to the left side of the equation to isolate the constant ($1$) on the right.
* **Action:** Add $\log_6(x+3)$ to both sides.
$$\log_6(x+4) + \log_6(x+3) = 1$$
##### Step 2: Condense the Left Side (Product Property)
Since the two logarithms share the same base ($6$) and are being added, combine their arguments into a single logarithm using multiplication.
* **The Identity Rule:** $\log_b M + \log_b N = \log_b (M \cdot N)$
* **Action:**
$$\log_6 [(x+4)(x+3)] = 1$$
##### Step 3: Rewrite in Exponential Form
Apply the definition of a logarithm to "release" the arguments from the log function.
* **Base:** $6$
* **Exponent:** $1$
* **Argument:** $(x+4)(x+3)$
* **Action:**
$$6^1 = (x+4)(x+3)$$
##### Step 4: Solve the Quadratic Equation
Expand the right side and set the equation to zero to solve for $x$.
* **Expand (FOIL):** $6 = x^2 + 3x + 4x + 12$
* **Simplify:** $6 = x^2 + 7x + 12$
* **Set to Zero:** $x^2 + 7x + 6 = 0$
* **Factor:** $(x+6)(x+1) = 0$
* **Possible Solutions:** $x = -6, \quad x = -1$
##### Step 5: Check for Extraneous Solutions
Verify both potential solutions in the **original** logarithmic arguments. All arguments must be strictly positive ($>0$).
1.  **Test $x = -6$:**
    * $\log_6(-6+4) = \log_6(-2)$ → **Undefined.**
    * Result: $x = -6$ is **Extraneous**.
2.  **Test $x = -1$:**
    * $\log_6(-1+4) = \log_6(3)$ (Positive)
    * $\log_6(-1+3) = \log_6(2)$ (Positive)
    * Result: $x = -1$ is **Valid**.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Addition/Multiplication Confusion:**
> When moving $\log_6(x+3)$ to the left side, it becomes addition. When you condense that addition, the arguments must be **multiplied**. A common error is mistakenly adding the arguments $(x+4) + (x+3)$, which is algebraically incorrect.

> [!WARNING]
> **Checking the Original:**
> Always check your answers in the original arguments before any properties were applied. Even if your algebra is perfect, one or more solutions may be invalid due to the domain of logarithmic functions.

---
#### Final Solution
$$x = -1$$
### Solving $\log_4(x^2-9) - \log_4(x+3) = 3$ via Exponential Conversion

This problem follows Professor Leonard's method for solving equations where one side contains multiple logarithms and the other side contains a constant. We must condense the logarithms into a single term before converting the entire equation into its exponential form.

---
#### Step-by-Step Solution

##### Step 1: Condense the Left Side (Quotient Property)
Since the two logarithms have the same base ($4$) and are separated by subtraction, combine them into a single logarithm by dividing the arguments.
* **The Identity Rule:** $\log_b M - \log_b N = \log_b \left(\frac{M}{N}\right)$
* **Action:**
$$\log_4 \left( \frac{x^2-9}{x+3} \right) = 3$$
##### Step 2: Simplify the Argument (Optional but Recommended)
Before converting to exponential form, notice that the numerator is a **difference of squares** ($x^2 - 3^2$). Simplifying now makes the resulting algebra much easier.
* **Factor:** $\frac{(x-3)(x+3)}{x+3}$
* **Cancel:** The $(x+3)$ terms cancel out (noting that $x \neq -3$).
* **Simplified Equation:**
$$\log_4(x-3) = 3$$
##### Step 3: Rewrite in Exponential Form
Apply the fundamental definition of a logarithm: $\log_b(M) = N \iff b^N = M$. Use the "Circle" method to release the argument from the log.
* **Base:** $4$
* **Exponent:** $3$
* **Argument:** $x-3$
* **Action:**
$$4^3 = x - 3$$

##### Step 4: Solve for $x$
Evaluate the power and isolate the variable.
* **Evaluate $4^3$:** $64 = x - 3$
* **Action:** Add $3$ to both sides.
$$x = 67$$
##### Step 5: Check for Extraneous Solutions
Verify that the result keeps the **original** logarithmic arguments strictly positive ($>0$).
1.  **Argument 1:** $67^2 - 9$ (Clearly positive)
2.  **Argument 2:** $67 + 3 = 70$ (Positive)
* **Result:** The solution is valid.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Condensing Requirement:**
> You cannot "drop the logs" because there is a constant ($3$) on the right side. You must condense the left side into one "log block" so that you can apply the exponential conversion.

> [!TIP]
> **Simplifying Early:**
> If you chose not to simplify the fraction in Step 2, you would have solved $4^3 = \frac{x^2-9}{x+3} \implies 64 = \frac{x^2-9}{x+3}$. Multiplying by $(x+3)$ would lead to a quadratic equation $64x + 192 = x^2 - 9$. While this would still lead to $x = 67$, factoring the difference of squares first is significantly faster and less prone to calculation errors.

---
#### Final Solution
$$x = 67$$
### Solving $\ln(x+1) - \ln(x) = 2$ via Exponential Conversion

This problem follows Professor Leonard's method for handling Natural Logarithms ($\ln$). Since there is a constant on the right side, we must condense the left side into a single logarithm and then convert it into its exponential form using the base $e$.

---
#### Step-by-Step Solution

##### Step 1: Condense the Left Side (Quotient Property)
The two logarithms have the same base (base $e$) and are separated by subtraction. We combine them into a single natural logarithm by dividing the arguments.
* **The Identity Rule:** $\ln M - \ln N = \ln\left(\frac{M}{N}\right)$
* **Action:**
$$\ln\left( \frac{x+1}{x} \right) = 2$$
##### Step 2: Rewrite in Exponential Form
Recall that $\ln$ is the logarithm with base $e$. Apply the definition $\ln(M) = N \iff e^N = M$ to release the argument from the logarithm.
* **Base:** $e$
* **Exponent:** $2$
* **Argument:** $\frac{x+1}{x}$
* **Action:**
$$e^2 = \frac{x+1}{x}$$
##### Step 3: Solve for $x$
Treat $e^2$ as a constant (approximately $7.389$) and use algebraic steps to isolate $x$.
* **Action (Multiply by $x$):** $x e^2 = x + 1$
* **Action (Group $x$ terms):** Subtract $x$ from both sides.
$$x e^2 - x = 1$$
* **Action (Factor out $x$):**
$$x(e^2 - 1) = 1$$
* **Action (Divide):**
$$x = \frac{1}{e^2 - 1}$$
##### Step 4: Calculator Evaluation (Optional)
To get a decimal approximation for your notes:
* $e^2 - 1 \approx 7.389 - 1 = 6.389$
* $1 \div 6.389 \approx 0.1565$
* **Result:** $x \approx 0.1565$
##### Step 5: Check for Extraneous Solutions
Verify the result in the **original** arguments.
1.  **Argument 1:** $x + 1 \rightarrow 0.1565 + 1 = 1.1565$ (Positive)
2.  **Argument 2:** $x \rightarrow 0.1565$ (Positive)
* **Result:** Since both arguments are positive, the solution is valid.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Base $e$ Reminder:**
> When working with $\ln$, the base is always $e$. A common mistake is to accidentally use $10$ or $2$ as the base during the exponential conversion step.

> [!WARNING]
> **The Factoring Step:**
> In Step 3, many students get stuck at $xe^2 - x = 1$. Remember that you must factor out the $x$ to isolate it when it appears in multiple terms on one side of the equation.

---
#### Final Solution
$$x = \frac{1}{e^2 - 1} \approx 0.1565$$
### Solving $\log_9(7x - 5) = \log_3(x+1)$ via Change of Base

This problem presents a unique challenge: the bases are not identical ($9$ and $3$). To use the One-to-One property, we must first manipulate one of the logarithms so that both sides share the same base.

---
#### Step-by-Step Solution

##### Step 1: Standardize the Bases
We need to change the $\log_9$ term into a $\log_3$ term (or vice versa). Since $9 = 3^2$, it is easier to convert the base $9$ logarithm.
* **Property (Change of Base):** $\log_b M = \frac{\log_c M}{\log_c b}$
* **Action:** Convert the left side to base $3$.
$$\frac{\log_3(7x - 5)}{\log_3 9} = \log_3(x+1)$$
* **Evaluate the Denominator:** Since $3^2 = 9$, $\log_3 9 = 2$.
$$\frac{\log_3(7x - 5)}{2} = \log_3(x+1)$$
##### Step 2: Clear the Fraction and Move Coefficients
To use the One-to-One property, the logarithms must have a coefficient of $1$.
* **Action (Multiply by 2):** $\log_3(7x - 5) = 2\log_3(x+1)$
* **Action (Power Property):** Move the $2$ to the exponent of the argument.
$$\log_3(7x - 5) = \log_3(x+1)^2$$
##### Step 3: Apply the One-to-One Property
Now that the bases are identical and the logarithms are isolated, we can set the arguments equal to each other.
* **Property:** $\log_b M = \log_b N \implies M = N$
* **Action:**
$$7x - 5 = (x+1)^2$$
##### Step 4: Solve the Quadratic Equation
Expand the right side and move all terms to one side to set the equation to zero.
* **Expand:** $7x - 5 = x^2 + 2x + 1$
* **Set to Zero:** $x^2 - 5x + 6 = 0$
* **Factor:** $(x - 3)(x - 2) = 0$
* **Possible Solutions:** $x = 3, \quad x = 2$
##### Step 5: Check for Extraneous Solutions
Verify that both solutions keep the **original** logarithmic arguments positive ($>0$).
1.  **Test $x = 3$:**
    * Left: $7(3) - 5 = 16$ (Positive)
    * Right: $3 + 1 = 4$ (Positive)
    * **Valid.**
2.  **Test $x = 2$:**
    * Left: $7(2) - 5 = 9$ (Positive)
    * Right: $2 + 1 = 3$ (Positive)
    * **Valid.**

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **Mismatched Bases:**
> You **cannot** set $(7x-5) = (x+1)$ immediately because the bases are different. Always look for a common power (like $3$ and $9$ or $2$ and $4$) to unify the bases first.

> [!TIP]
> **Alternative Perspective:**
> You could also rewrite the right side by realizing $\log_3(x+1) = \log_{3^2}(x+1)^2 = \log_9(x+1)^2$. This is a "shortcut" version of the change of base property that Professor Leonard often uses to quickly match bases.

---
#### Final Solution
$$x = 3, \quad x = 2$$
### Solving $\log_{16} x + \log_4 x + \log_2 x = 7$ via Change of Base

This problem features three different bases ($16$, $4$, and $2$). Following Professor Leonard's strategy, we must convert all terms to a single common base before they can be condensed. Since $16$ and $4$ are both powers of $2$, we will convert everything to base $2$.

---
#### Step-by-Step Solution

##### Step 1: Standardize to Base 2
Use the Change of Base Formula: $\log_b M = \frac{\log_c M}{\log_c b}$.
* **Convert $\log_{16} x$:** $\frac{\log_2 x}{\log_2 16} = \frac{\log_2 x}{4}$ (since $2^4 = 16$)
* **Convert $\log_4 x$:** $\frac{\log_2 x}{\log_2 4} = \frac{\log_2 x}{2}$ (since $2^2 = 4$)
* **The Equation becomes:**
$$\frac{\log_2 x}{4} + \frac{\log_2 x}{2} + \log_2 x = 7$$
##### Step 2: Clear the Fractions
Multiply the entire equation by the Least Common Denominator (LCD), which is **4**, to eliminate the denominators.
* **Action:** $4 \left[ \frac{\log_2 x}{4} + \frac{\log_2 x}{2} + \log_2 x \right] = 4(7)$
* **Distribute:**
$$\log_2 x + 2\log_2 x + 4\log_2 x = 28$$
##### Step 3: Combine Like Terms
Since all terms are now $\log_2 x$, we can simply add their coefficients ($1 + 2 + 4$).
* **Action:**
$$7\log_2 x = 28$$

##### Step 4: Isolate the Logarithm
Divide both sides by $7$ to prepare for exponential conversion.
* **Action:**
$$\log_2 x = 4$$
##### Step 5: Rewrite in Exponential Form
Apply the definition $\log_b M = N \iff b^N = M$ to solve for $x$.
* **Base:** $2$
* **Exponent:** $4$
* **Argument:** $x$
* **Action:**
$$2^4 = x$$
##### Step 6: Solve and Check
* **Solve:** $x = 16$
* **Check:** Plugging $x = 16$ into the original arguments ($\log_{16} 16$, $\log_4 16$, $\log_2 16$) results in all positive arguments.
* **Verification:** $1 + 2 + 4 = 7$. The solution is valid.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **Base Choice:**
> While you could convert everything to base 16, it would involve working with fractional exponents (like $x^{1/4}$). Converting to the smallest common base (base 2) keeps the coefficients as whole numbers, which is significantly easier to manage algebraically.

> [!WARNING]
> **Coefficient Errors:**
> When clearing fractions in Step 2, do not forget to multiply the "standalone" $\log_2 x$ and the constant on the right side of the equals sign by the LCD.

---
#### Final Solution
$$x = 16$$
### Solving $2(\log_4 x)^2 + 3 \log_8 x = \log_2 16$ via Change of Base and Substitution

This problem features multiple bases ($4, 8, 2$) and a squared logarithmic term. Following Professor Leonard's strategy, we first standardize all bases to the smallest common base ($2$) and then use substitution to solve the resulting quadratic equation.

---

#### Step-by-Step Solution

##### Step 1: Simplify the Constant
Evaluate the logarithm on the right side immediately to clean up the equation.
* **Calculation:** $\log_2 16$ asks "2 to what power is 16?" $\rightarrow 2^4 = 16$.
* **Rewrite:** $2(\log_4 x)^2 + 3 \log_8 x = 4$

##### Step 2: Standardize to Base 2
Use the Change of Base Formula: $\log_b M = \frac{\log_c M}{\log_c b}$.

* **Convert $\log_4 x$:** $\frac{\log_2 x}{\log_2 4} = \frac{\log_2 x}{2}$
* **Convert $\log_8 x$:** $\frac{\log_2 x}{\log_2 8} = \frac{\log_2 x}{3}$

**Substitute these back into the equation:**
$$2\left( \frac{\log_2 x}{2} \right)^2 + 3\left( \frac{\log_2 x}{3} \right) = 4$$

##### Step 3: Simplify the Expressions
* **Handle the Squared Term:** $\left( \frac{\log_2 x}{2} \right)^2 = \frac{(\log_2 x)^2}{4}$
* **The Equation becomes:** $2 \left( \frac{(\log_2 x)^2}{4} \right) + \log_2 x = 4$
* **Reduce Fractions:** $\frac{1}{2}(\log_2 x)^2 + \log_2 x = 4$

##### Step 4: Use U-Substitution
To make the quadratic easier to see, let **$u = \log_2 x$**.
$$\frac{1}{2}u^2 + u = 4$$
* **Clear the Fraction:** Multiply everything by $2$.
$$u^2 + 2u = 8$$
* **Set to Zero:** $u^2 + 2u - 8 = 0$
* **Factor:** $(u + 4)(u - 2) = 0$
* **Solve for $u$:** $u = -4, \quad u = 2$

##### Step 5: Back-Substitute to Solve for $x$
Now replace $u$ with $\log_2 x$ and convert to exponential form.

1.  **Case 1: $\log_2 x = -4$**
    * $2^{-4} = x$
    * $x = \frac{1}{16}$

2.  **Case 2: $\log_2 x = 2$**
    * $2^2 = x$
    * $x = 4$



##### Step 6: Check for Extraneous Solutions
Verify both results in the **original** arguments.
* **Test $x = \frac{1}{16}$:** Argument is positive. (**Valid**)
* **Test $x = 4$:** Argument is positive. (**Valid**)

---

#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **Squaring the Entire Log:**
> Remember that $(\log_4 x)^2$ is NOT the same as $\log_4 (x^2)$. You cannot move the $2$ to the front using the Power Property. You must treat the entire log as a single unit being squared.

> [!WARNING]
> **Denominator Squaring:**
> In Step 3, when squaring $\frac{\log_2 x}{2}$, ensure you square the denominator ($2^2 = 4$) as well as the numerator. Forgetting to square the denominator is a frequent calculation error.

---

#### Final Solution
$$x = 4, \quad x = \frac{1}{16}$$
### Solving $\log_2 x = 3 - \log_6 x$ via Change of Base and Algebraic Isolation

This problem is a "Level 3" logarithmic equation because the bases ($2$ and $6$) are not powers of each other. Following Professor Leonard's strategy for mismatched bases, we must use the Change of Base formula to convert everything to a single base (usually base 10 or natural log) to isolate $x$.

---
#### Step-by-Step Solution

##### Step 1: Group the Logarithms
Move all terms containing $x$ to one side of the equation.
* **Action:** Add $\log_6 x$ to both sides.
$$\log_2 x + \log_6 x = 3$$
##### Step 2: Apply Change of Base Formula
Since $2$ and $6$ don't share a common integer base, convert both to **Natural Log ($\ln$)** or **Common Log ($\log_{10}$)**. We will use $\ln$ here.
* **Property:** $\log_b M = \frac{\ln M}{\ln b}$
* **Action:**
$$\frac{\ln x}{\ln 2} + \frac{\ln x}{\ln 6} = 3$$

##### Step 3: Factor out the Common Term
Both terms on the left side share $\ln x$. Factor it out to begin isolating the variable.
* **Action:**
$$\ln x \left( \frac{1}{\ln 2} + \frac{1}{\ln 6} \right) = 3$$
##### Step 4: Isolate $\ln x$
Divide both sides by the entire quantity inside the parentheses. 
* **Action:**
$$\ln x = \frac{3}{\left( \frac{1}{\ln 2} + \frac{1}{\ln 6} \right)}$$
##### Step 5: Convert to Exponential Form
Now that $\ln x$ is isolated, rewrite the equation in exponential form using base $e$.
* **Base:** $e$
* **Exponent:** The entire right side of the equation.
* **Action:**
$$x = e^{\left[ \frac{3}{\frac{1}{\ln 2} + \frac{1}{\ln 6}} \right]}$$
##### Step 6: Decimal Approximation
To provide a concrete answer for your notes, evaluate the expression:
* $\frac{1}{\ln 2} \approx 1.4427$
* $\frac{1}{\ln 6} \approx 0.5581$
* $\text{Denominator} \approx 2.0008$
* $\ln x \approx \frac{3}{2.0008} \approx 1.4994$
* $x = e^{1.4994} \approx 4.479$
##### Step 7: Check for Extraneous Solutions
Verify that $x \approx 4.479$ keeps the original arguments positive.
* **Check:** Both $\log_2(4.479)$ and $\log_6(4.479)$ have positive arguments. 
* **Result:** The solution is valid.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **The Condensing Trap:**
> You **cannot** use the Product Property to say $\log(2 \cdot 6)x = 3$. The Product Property only applies when the bases are identical. If the bases are different, you must use Change of Base before any algebraic combining can occur.

> [!WARNING]
> **Rounding Errors:**
> When solving these in your calculator, do not round the values of $\ln 2$ or $\ln 6$ early. Keep the full decimals in your calculator until the very final step to ensure your value for $x$ is accurate.

---
#### Final Solution
$$x = e^{\left[ \frac{3}{\frac{1}{\ln 2} + \frac{1}{\ln 6}} \right]} \approx 4.479$$
## 2026-May-24 - Solving Exponential Equations with Logarithms (Precalculus - College Algebra 64) :
https://www.youtube.com/watch?v=rDcLCA2W-UI&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=65
### Solving Exponential Equations with Logarithms

When exponential equations cannot be solved using common bases (e.g., $3^x = 5$), we must use logarithms. Logarithms are the inverse operation of exponentials and allow us to "bring down" variables from the exponent.

---
#### 1. Four Methods for Basic Equations (Single Exponential)
For an isolated exponential like $3^{x+1} = \frac{5}{8}$, there are four equivalent ways to solve:

1.  **Direct Logarithmic Notation:** Rewrite the exponential form directly into logarithmic form.
    * $\text{Base}^E = A \iff \log_{\text{Base}}(A) = E$
    * $\log_3(\frac{5}{8}) = x + 1 \implies x = \log_3(\frac{5}{8}) - 1$
2.  **Common Log ($\log$) on Both Sides:** Take the base-10 log of both sides and use the Power Property to move the exponent to the front.
3.  **Natural Log ($\ln$) on Both Sides:** (Most Preferred) Take the base-$e$ log of both sides. This is often preferred because it is shorter to write and easily accessible on all calculators.
4.  **Matching Log Base:** Take the log of both sides using the same base as the exponential (e.g., $\log_3$ for $3^x$) to invoke the inverse property $\log_b(b^x) = x$.

---
#### 2. Advanced Equations (Different Bases & Multiple X's)
When you have two different bases (e.g., $2^{x-1} = 5^{1-2x}$), you **must** use a logarithm on both sides.

**The Mandatory Process:**
* **Step 1:** Take the Natural Log ($\ln$) of both sides.
* **Step 2:** Use the Power Property to move exponents to the front as coefficients.
    * *Crucial:* Keep exponents in parentheses: $(x-1)\ln 2 = (1-2x)\ln 5$.
* **Step 3:** Distribute the $\ln$ values (which are just constants).
* **Step 4:** Group all terms with $x$ on one side and constants on the other.
* **Step 5:** Factor out $x$ and divide to isolate the variable.

---
#### 3. Equations Involving $e$
If the equation involves base $e$ (e.g., $e^{x+3} = \pi^x$), always use the Natural Log ($\ln$).
* Because $\ln(e) = 1$, the term $\ln(e^{x+3})$ simplifies immediately to $x+3$.
* This significantly reduces the algebraic steps required compared to using $\log_{10}$.

---
#### 4. The Substitution Technique (Quadratic Form)
When an equation has three terms and looks like a quadratic (e.g., $49^x + 11(7^x) + 5 = 0$), use $u$-substitution.

* **Recognition:** Look for one base that is the square of another ($49^x$ is $(7^x)^2$).
* **Setup:** Let $u = 7^x$. Rewrite as $u^2 + 11u + 5 = 0$.
* **Solve:** Solve for $u$ using factoring or the Quadratic Formula.
* **Back-Substitute:** Set $7^x$ equal to your $u$ values.

---
#### 5. Critical Warnings & Domain/Range
* **Extraneous Solutions:** An exponential function $a^x$ (where $a > 0$) can **never** result in a negative number or zero.
    * If your algebra leads to $2^x = -6$, that branch of the solution is **invalid**.
* **The Parentheses Rule:** When moving an exponent like $(x+1)$ to the front of a log, you **must** use parentheses. Failure to distribute the log to both terms is the most common error in this domain.
* **Logarithmic Form vs. Calculator Form:** $\log_3(5)$ is an "exact solution." $\frac{\ln 5}{\ln 3}$ is the "change of base" form used for calculator approximation.

---
#### Final Exact Solution Example
For $e^{x+3} = \pi^x$:
1.  $\ln(e^{x+3}) = \ln(\pi^x)$
2.  $x + 3 = x \ln \pi$
3.  $3 = x \ln \pi - x$
4.  $3 = x(\ln \pi - 1)$
5.  $x = \frac{3}{\ln \pi - 1}$

### Solving $8 \cdot 3^{x+1} = 5$ (Four Methods)

In the Professor Leonard video, he demonstrates that while there are multiple algebraic paths to solve a single exponential equation, they all lead to the same numerical value. The first step for **all** methods is to isolate the exponential term.

**Preliminary Step: Isolate the Exponential**
* Divide both sides by $8$:
$$3^{x+1} = \frac{5}{8}$$
---
#### Method 1: Direct Logarithmic Notation
This is the most straightforward "definition-based" move. You convert the exponential form directly into a logarithm.
* **Property:** $b^E = A \iff \log_b(A) = E$
* **Apply:**
$$\log_3 \left( \frac{5}{8} \right) = x + 1$$
* **Solve for $x$:**
$$x = \log_3 \left( \frac{5}{8} \right) - 1$$

---
#### Method 2: Common Log ($\log$) on Both Sides
This method is useful for calculators that only have a "Log" button (Base 10).
* **Action:** Take the log of both sides.
$$\log(3^{x+1}) = \log \left( \frac{5}{8} \right)$$
* **Power Property:** Move the exponent to the front.
$$(x+1)\log 3 = \log \left( \frac{5}{8} \right)$$
* **Isolate $x$:**
$$x+1 = \frac{\log(5/8)}{\log 3} \implies x = \frac{\log(5/8)}{\log 3} - 1$$
---
#### Method 3: Natural Log ($\ln$) on Both Sides
This is the **preferred method** for higher-level math (Calculus) because it is faster to write and handles base $e$ naturally.
* **Action:** Take the natural log of both sides.
$$\ln(3^{x+1}) = \ln \left( \frac{5}{8} \right)$$
* **Power Property:**
$$(x+1)\ln 3 = \ln \left( \frac{5}{8} \right)$$
* **Isolate $x$:**
$$x+1 = \frac{\ln(5/8)}{\ln 3} \implies x = \frac{\ln(5/8)}{\ln 3} - 1$$
---
#### Method 4: Matching Log Base ($\log_3$) on Both Sides
This method uses the Inverse Property of logarithms to "cancel out" the base.
* **Action:** Take $\log_3$ of both sides.
$$\log_3(3^{x+1}) = \log_3 \left( \frac{5}{8} \right)$$
* **Inverse Property:** $\log_b(b^x) = x$
$$x+1 = \log_3 \left( \frac{5}{8} \right)$$
* **Isolate $x$:**
$$x = \log_3 \left( \frac{5}{8} \right) - 1$$
---
#### Summary of Results
All four methods yield the same exact value. Methods 2 and 3 are essentially the **Change of Base** formula versions of Method 1 and 4.

> [!IMPORTANT]
> **The Parentheses Rule:** As emphasized in the video, when you move $(x+1)$ to the front of the log, you **must** keep it in parentheses. This ensures that if you choose to distribute the log instead of dividing, the algebra remains correct.

**Final Exact Solution:**
$$x = \frac{\ln(5/8)}{\ln 3} - 1 \approx -1.4118$$
### Solving $2^{x+1} = 5^{1-2x}$ via Natural Logarithms

When variables appear in the exponents of two different bases ($2$ and $5$), and those bases cannot be written as a common base, we must take the logarithm of both sides. As shown in the video, using the Natural Log ($\ln$) is the most efficient path.

---
#### Step-by-Step Solution
##### Step 1: Take the Natural Log ($\ln$) of Both Sides
Apply $\ln$ to both sides of the equation to prepare for the Power Property.
$$\ln(2^{x+1}) = \ln(5^{1-2x})$$
##### Step 2: Move Exponents to the Front (Power Property)
Move the exponents down as coefficients. 
> [!IMPORTANT]
> **Video Rule:** You must keep the exponents in parentheses to ensure the $\ln$ values are distributed correctly later.
$$(x+1)\ln 2 = (1-2x)\ln 5$$
##### Step 3: Distribute the Logarithms
Treat $\ln 2$ and $\ln 5$ as constants and distribute them into their respective parentheses.
$$x \ln 2 + \ln 2 = \ln 5 - 2x \ln 5$$
##### Step 4: Group the $x$ Terms
Move all terms containing $x$ to the left side and all constant terms to the right side.
* **Action:** Add $2x \ln 5$ to the left; subtract $\ln 2$ from the right.
$$x \ln 2 + 2x \ln 5 = \ln 5 - \ln 2$$
##### Step 5: Factor out $x$
Since both terms on the left share $x$, factor it out to prepare for division.
$$x(\ln 2 + 2 \ln 5) = \ln 5 - \ln 2$$
##### Step 6: Isolate $x$
Divide both sides by the entire parenthetical expression $(\ln 2 + 2 \ln 5)$.
$$x = \frac{\ln 5 - \ln 2}{\ln 2 + 2 \ln 5}$$

---
#### Optional Simplification (Log Properties)
You can use the Power and Quotient properties to condense the answer into a single logarithm:
1.  **Numerator:** $\ln 5 - \ln 2 = \ln(5/2) = \ln 2.5$
2.  **Denominator:** $\ln 2 + \ln(5^2) = \ln 2 + \ln 25 = \ln(2 \cdot 25) = \ln 50$
3.  **Result:** $x = \frac{\ln 2.5}{\ln 50}$
4.  **Change of Base (Reverse):** $x = \log_{50}(2.5)$

---
#### Critical Pitfall to Avoid
* **The Distribution Error:** A common mistake is to only multiply the $x$ by the logarithm and forget to multiply the constant (the $+1$ or $-1$). As Professor Leonard noted, the parentheses are your "insurance policy" against this mistake.

---
#### Final Solution
**Exact Form:**
$$x = \frac{\ln 5 - \ln 2}{\ln 2 + 2 \ln 5}$$

**Approximate Form:**
$$x \approx 0.2345$$
### $e^{x+3} = \pi^{x}$ via Natural Logarithms

When dealing with equations involving base $e$, using the Natural Log ($\ln$) is the most efficient strategy because $\ln(e) = 1$. This simplifies the algebra significantly compared to using other bases.

---
#### Step-by-Step Solution

##### Step 1: Take the Natural Log ($\ln$) of Both Sides
Apply $\ln$ to both sides to access the exponents.
$$\ln(e^{x+3}) = \ln(\pi^{x})$$
##### Step 2: Use the Inverse and Power Properties
* **Left side:** The inverse property $\ln(e^u) = u$ allows the base and the log to cancel out.
* **Right side:** Use the Power Property to move $x$ to the front as a coefficient.
$$x + 3 = x \ln \pi$$
##### Step 3: Group the $x$ Terms
Move all terms containing the variable $x$ to one side of the equation.
* **Action:** Subtract $x$ from both sides.
$$3 = x \ln \pi - x$$
##### Step 4: Factor out $x$
Factor out the common $x$ term on the right side to isolate it from the constants.
$$3 = x(\ln \pi - 1)$$
##### Step 5: Isolate $x$
Divide both sides by the quantity $(\ln \pi - 1)$.
$$x = \frac{3}{\ln \pi - 1}$$

---
#### Key Observations from the Video
* **Efficiency of $\ln$:** Using $\ln$ with base $e$ eliminates the need to distribute a logarithm on the left side, which would be necessary if using $\log_{10}$.
* **Exact vs. Approximate:** $\frac{3}{\ln \pi - 1}$ is the "Exact Solution." 
* **Calculator Tip:** When evaluating, ensure the denominator is in parentheses: `3 / (ln(π) - 1)`.

---
#### Final Solution
**Exact Form:**
$$x = \frac{3}{\ln \pi - 1}$$

**Approximate Form:**
$$x \approx 20.728$$
### Solving $2^{2x} + 2^{x+2} - 12 = 0$ via Substitution

This problem features three terms and exponentials that cannot be combined or isolated. Following the substitution method shown in the video, we look for a way to rewrite the terms so they share a common exponential, typically resulting in a quadratic form.

---
#### Step-by-Step Solution

##### Step 1: Rewrite Terms to Match Exponentials
We want to manipulate the first two terms so they both contain $2^x$.
* **Term 1 ($2^{2x}$):** Using the Power of a Power rule $(b^m)^n = b^{mn}$, we rewrite $2^{2x}$ as $(2^x)^2$.
* **Term 2 ($2^{x+2}$):** Using the Product Rule $b^m \cdot b^n = b^{m+n}$ in reverse, we rewrite $2^{x+2}$ as $2^x \cdot 2^2$.
    * $2^x \cdot 2^2$ simplifies to $4(2^x)$.

**The Rewritten Equation:**
$$(2^x)^2 + 4(2^x) - 12 = 0$$
##### Step 2: Use U-Substitution
To make the quadratic structure visible, we substitute a variable for the exponential.
* **Let $u = 2^x$**
$$u^2 + 4u - 12 = 0$$
##### Step 3: Solve the Quadratic Equation
Factor the trinomial to find the values of $u$.
* **Factor:** $(u + 6)(u - 2) = 0$
* **Solve for $u$:**
    * $u = -6$
    * $u = 2$
##### Step 4: Back-Substitute to Solve for $x$
Replace $u$ with the original $2^x$ to find the real solution for $x$.

1.  **Case 1: $2^x = -6$**
    * **Check Range:** An exponential function ($2^x$) always yields a positive result. It can never equal a negative number.
    * **Result:** No solution from this branch (Extraneous).

2.  **Case 2: $2^x = 2$**
    * Since $2$ is the same as $2^1$, we can use the One-to-One property of common bases.
    * **Result:** $x = 1$

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **Range vs. Domain:**
> As noted in the video, $2^x = -6$ is a "range issue" for the exponential. If you tried to solve it with logs, you would get $\log_2(-6) = x$, which is a "domain issue" because you cannot take the log of a negative number.

> [!TIP]
> **Commutative Property:**
> $2^{2x}$ could also be written as $(2^2)^x$, which is $4^x$. However, that doesn't help us match the $2^x$ in the second term. Always choose the rewrite that matches the smaller exponential base.

---
#### Final Solution
$$x = 1$$
### Solving $2(49^x) + 11(7^x) + 5 = 0$ via Substitution

This problem follows the "Level 4" pattern from Professor Leonard's lecture, where one base is the square of another ($49 = 7^2$). We use substitution to convert the exponential equation into a standard quadratic equation.

---
#### Step-by-Step Solution

##### Step 1: Rewrite to Identify the Common Base
We need both exponential terms to share the same base, which is $7$.
* **Rewrite $49^x$:** Since $49 = 7^2$, we can write $49^x$ as $(7^2)^x$.
* **Power Property:** Because multiplication is commutative ($2 \cdot x = x \cdot 2$), $(7^2)^x$ is equivalent to $(7^x)^2$.
**The Equation becomes:**
$$2(7^x)^2 + 11(7^x) + 5 = 0$$
##### Step 2: Apply U-Substitution
To see the quadratic structure clearly, we replace the exponential term with $u$.
* **Let $u = 7^x$**
$$2u^2 + 11u + 5 = 0$$
##### Step 3: Solve the Quadratic Equation
Factor the trinomial using the "ac" method ($2 \cdot 5 = 10$; factors of $10$ that add to $11$ are $10$ and $1$).
* **Factor:** $(2u + 1)(u + 5) = 0$
* **Solve for $u$:**
    * $2u + 1 = 0 \implies u = -1/2$
    * $u + 5 = 0 \implies u = -5$
##### Step 4: Back-Substitute and Analyze the Range
Now we replace $u$ with $7^x$ to solve for $x$.

1.  **Case 1:** $7^x = -1/2$
2.  **Case 2:** $7^x = -5$
**Critical Range Check:**
As Professor Leonard emphasized, an exponential function $a^x$ (with a positive base) **can never produce a negative output**.
* The range of $7^x$ is $(0, \infty)$.
* Since both $-1/2$ and $-5$ are negative, they are outside the range of the exponential function.

---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **No Solution vs. Incorrect Algebra:**
> It is common for substitution problems to yield "No Solution." This happens when the quadratic step produces negative $u$ values. Don't assume you made a mistake; rather, recognize that the exponential function simply cannot reach those values.

> [!WARNING]
> **Domain Trap:**
> If you tried to solve $7^x = -5$ by taking the log of both sides, you would get $\log_7(-5) = x$. This results in a **domain error** on your calculator, confirming that there is no real number solution.

---
#### Final Solution
**No Real Solution**
### Solving $3^x - 14 \cdot 3^{-x} = 5$ via Substitution

This problem features a negative exponent, which Professor Leonard treats as a "fractional" issue. The strategy is to eliminate the negative exponent to create a quadratic structure that can be solved via $u$-substitution.

---
#### Step-by-Step Solution

##### Step 1: Rewrite the Negative Exponent
Recall that $a^{-n} = \frac{1}{a^n}$. Rewrite the second term to see the fraction clearly.
$$3^x - \frac{14}{3^x} = 5$$
##### Step 2: Clear the Fraction (Multiply by the LCD)
To get the equation into a form we can solve, multiply every term on both sides by the denominator, $3^x$.
* **Term 1:** $3^x \cdot 3^x = (3^x)^2$
* **Term 2:** $3^x \cdot \left(\frac{14}{3^x}\right) = 14$
* **Right Side:** $5 \cdot 3^x = 5(3^x)$
**The resulting equation:**
$$(3^x)^2 - 14 = 5(3^x)$$
##### Step 3: Rearrange into Standard Quadratic Form
Move all terms to one side to set the equation to zero.
$$(3^x)^2 - 5(3^x) - 14 = 0$$
##### Step 4: Apply U-Substitution
Substitute $u$ for the exponential term to make the quadratic easier to handle.
* **Let $u = 3^x$**
$$u^2 - 5u - 14 = 0$$
##### Step 5: Solve the Quadratic Equation
Factor the trinomial.
* **Factor:** $(u - 7)(u + 2) = 0$
* **Solve for $u$:**
    * $u = 7$
    * $u = -2$
##### Step 6: Back-Substitute to Solve for $x$
Now, replace $u$ with $3^x$ and evaluate each case.

1.  **Case 1: $3^x = 7$**
    * Since $7$ is not a power of $3$, convert to logarithmic form.
    * **$\log_3 7 = x$** (Exact Solution)
    * **$x = \frac{\ln 7}{\ln 3}$** (Calculator Form)

2.  **Case 2: $3^x = -2$**
    * **Check Range:** An exponential function ($3^x$) cannot produce a negative result.
    * **Result:** No solution from this branch (Extraneous).
---
#### Critical Warnings & Common Pitfalls

> [!CAUTION]
> **Multiplying Both Sides:**
> When clearing the fraction in Step 2, a common error is forgetting to multiply the constant on the right side ($5$). You must multiply **every** term in the equation by $3^x$.

> [!WARNING]
> **The Negative Exponent Trap:**
> Do not attempt to take the log of the equation while it still has a subtraction sign (e.g., $\ln(3^x - 14 \cdot 3^{-x})$). Log properties do not allow you to split a logarithm across subtraction or addition. Substitution is the only valid path here.

---
#### Final Solution
**Exact Form:**
$$x = \log_3 7$$

**Approximate Form:**
$$x \approx 1.771$$
## 2026-May-25 - Review of Compound Interest (Precalculus - College Algebra 65) :
https://www.youtube.com/watch?v=N1k25doMFww&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=67
### Review of Compound Interest

Compound interest occurs when interest is earned not only on the initial principal but also on the interest accumulated from previous periods. In this lecture, Professor Leonard covers the two primary formulas used to calculate future value based on how often interest is applied.

---
#### 1. Discrete Compound Interest Formula
This formula is used when interest is compounded at specific intervals (annually, monthly, daily, etc.).

$$A = P\left(1 + \frac{r}{n}\right)^{nt}$$

**Variables Defined:**
* **$A$:** Future Value (the amount of money in the account after $t$ years).
* **$P$:** Principal (the initial amount invested or borrowed).
* **$r$:** Annual Interest Rate (must be expressed as a **decimal**; e.g., $5\% = 0.05$).
* **$n$:** Number of compounding periods per year.
* **$t$:** Time in **years**.

**Common Values for $n$:**
* Annually: $n = 1$
* Semi-annually: $n = 2$
* Quarterly: $n = 4$
* Monthly: $n = 12$
* Daily: $n = 365$

---
#### 2. Continuous Compound Interest Formula
As the number of compounding periods ($n$) approaches infinity, we transition from discrete compounding to continuous compounding. This involves the mathematical constant $e$ (Euler's number, $\approx 2.718$).

$$A = Pe^{rt}$$

**When to use:** Use this formula only when the problem explicitly states interest is compounded **"continuously."**

---
#### 3. Solving for Different Variables
Professor Leonard emphasizes that while finding $A$ is simple arithmetic, finding $P$ or $t$ requires more advanced algebra.

* **Solving for $P$ (Present Value):**
    * If you know the target amount ($A$) you want in the future, you can solve for $P$ by dividing $A$ by the entire growth factor:
    $$P = \frac{A}{(1 + r/n)^{nt}}$$
* **Solving for $t$ (Time):**
    * Since $t$ is in the exponent, you **must** use logarithms ($\ln$) to solve.
    * **Step 1:** Isolate the exponential part by dividing by $P$.
    * **Step 2:** Take the natural log ($\ln$) of both sides.
    * **Step 3:** Use the Power Property to bring $t$ down and solve.

---
#### 4. Effective Annual Yield (APY)
The Effective Annual Yield (or Annual Percentage Yield) is the actual interest rate earned in one year after accounting for compounding. It allows you to compare two different accounts with different compounding frequencies.

**Formula:**
$$Y = \left(1 + \frac{r}{n}\right)^n - 1$$

* The yield will always be slightly higher than the nominal rate ($r$) if $n > 1$.
* This formula is essentially the standard compound interest formula where $P = 1$ and $t = 1$, minus the original principal.

---
#### 5. Critical Tips & Common Pitfalls

> [!CAUTION]
> **Rounding Errors:**
> Never round the intermediate steps in your calculator (like the $1 + r/n$ part). Keep the full decimal in your calculator until the very final step to avoid "rounding drift," which can significantly change the dollar amount in large investments.

> [!IMPORTANT]
> **The Rate Trap:**
> Always convert percentages to decimals immediately. Using "$5$" instead of "$0.05$" in the formula will result in a mathematically impossible growth rate.

> [!TIP]
> **Units of Time:**
> $t$ must always be in years. If a problem gives you "6 months," you must use $t = 0.5$.
### Compound Interest Problem: $3,000$ at $9.25\%$ for $2.5$ years

Following Professor Leonard's methodology, we will solve this using both the Discrete Compound Interest formula and the Continuous Compound Interest formula. 

**Given Information:**
* **$P$ (Principal):** $3,000$
* **$r$ (Annual Rate):** $9.25\% = 0.0925$
* **$t$ (Time in years):** $2.5$ (since $2 \frac{1}{2} = 2.5$)
* **$n$ (Compounding periods):** $12$ (Monthly)

---
#### Method 1: Discrete Compound Interest (Monthly)
We use the discrete formula because the problem specifies a finite compounding period (monthly).
**1. Set up the formula:**
$$A = 3000 \left( 1 + \frac{0.0925}{12} \right)^{(12 \cdot 2.5)}$$
**2. Simplify the exponent:**
$$12 \cdot 2.5 = 30$$
**3. Simplify the rate fraction (Keep exact decimals):**
$$\frac{0.0925}{12} \approx 0.0077083333$$
**4. Solve inside the parentheses:**
$$A = 3000 (1.0077083333)^{30}$$
**5. Final Calculation:**
$$A \approx 3000 (1.259203)$$
$$A \approx 3777.61$$

---
#### Method 2: Continuous Compound Interest
Even though the problem says "monthly," we solve using the continuous formula to compare how much more interest is earned when compounding never stops.

**1. Set up the formula:**
$$A = Pe^{rt}$$
$$A = 3000 \cdot e^{(0.0925 \cdot 2.5)}$$
**2. Simplify the exponent:**
$$0.0925 \cdot 2.5 = 0.23125$$
**3. Evaluate the exponential part:**
$$A = 3000 \cdot e^{0.23125}$$
$$A \approx 3000 \cdot 1.260174$$
**4. Final Calculation:**
$$A \approx 3780.52$$
---
#### Comparison of Results

| Compounding Method | Formula | Total Amount ($A$) |
| :--- | :--- | :--- |
| **Monthly ($n=12$)** | $P(1+r/n)^{nt}$ | **$3,777.61** |
| **Continuous** | $Pe^{rt}$ | **$3,780.52** |

> [!IMPORTANT]
> **Observation:** > Continuous compounding yielded **$2.91** more than monthly compounding. As Professor Leonard points out in the video, the difference between "very frequent" compounding (like daily or monthly) and "continuous" compounding is often surprisingly small.

> [!CAUTION]
> **Rounding Warning:**
> When calculating $(1 + 0.0925/12)$, do **not** round to $1.01$. If you round too early, your final dollar amount will be significantly off. Always use the full decimal string in your calculator.

### Solving for Present Value ($P$): Target $800$ Daily

This problem asks "How much should be invested," which means we are solving for the **Principal ($P$)**. A common point of confusion in this specific problem is the phrase "earn $800$ daily"—Professor Leonard clarifies that this usually refers to the **Total Interest Earned ($I$)**, meaning the final amount ($A$) would be $P + 800$. However, if $800$ is the **Future Value ($A$)** target, we solve directly for $P$.

**Given Information:**
* **$A$ (Future Value):** $800$
* **$r$ (Annual Rate):** $8.5\% = 0.085$
* **$t$ (Time in years):** $3.25$ (since $3 \frac{1}{4} = 3.25$)
* **$n$ (Compounding periods):** $365$ (Daily)

---
#### Method 1: Discrete Compound Interest (Daily)
**1. Set up the formula:**
$$800 = P \left( 1 + \frac{0.085}{365} \right)^{(365 \cdot 3.25)}$$
**2. Simplify the exponent ($nt$):**
$$365 \cdot 3.25 = 1186.25$$
**3. Isolate $P$:**
To isolate $P$, we divide the total amount ($A$) by the entire growth factor.
$$P = \frac{800}{\left( 1 + \frac{0.085}{365} \right)^{1186.25}}$$
**4. Final Calculation:**
* Inside parentheses: $1 + 0.000232877 \approx 1.000232877$
* Raise to power: $(1.000232877)^{1186.25} \approx 1.31818$
$$P = \frac{800}{1.31818}$$
$$P \approx 606.90$$

---
#### Method 2: Continuous Compound Interest

**1. Set up the formula:**
$$800 = P \cdot e^{(0.085 \cdot 3.25)}$$
**2. Simplify the exponent ($rt$):**
$$0.085 \cdot 3.25 = 0.27625$$
**3. Isolate $P$:**
$$P = \frac{800}{e^{0.27625}}$$
**4. Final Calculation:**
* Evaluate $e^{0.27625} \approx 1.318187$
$$P = \frac{800}{1.318187}$$
$$P \approx 606.89$$
---
#### Comparison of Results

| Compounding Method | Formula | Principal Needed ($P$) |
| :--- | :--- | :--- |
| **Daily ($n=365$)** | $A / (1+r/n)^{nt}$ | **$606.90** |
| **Continuous** | $A / e^{rt}$ | **$606.89** |

> [!IMPORTANT]
> **The Inverse Relationship:**
> Notice that as the compounding frequency increases (from daily to continuous), the amount of initial money you need to reach your goal **decreases** (though only by a cent here). This is because the money is working harder for you.

> [!CAUTION]
> **Calculator Order of Operations:**
> When solving for $P$, many students accidentally multiply $A$ by the growth factor. Remember: to move the growth factor to the other side of the equation, you **must divide**.

### Solving for Time ($t$): Doubling an Investment at $4.5\%$

When a problem asks "how long," we are solving for **$t$**. Because $t$ is located in the exponent, we must use logarithms to isolate it. To "double" an investment means that our Future Value ($A$) will be twice our Principal ($P$), or $A = 2P$.

**Given Information:**
* **$A$ (Future Value):** $2P$ (or simply use $A=2$ and $P=1$)
* **$r$ (Annual Rate):** $4.5\% = 0.045$
* **$n$ (Compounding periods):** $4$ (Quarterly)
* **$t$ (Time):** Unknown variable

---
#### Method 1: Discrete Compound Interest (Quarterly)

**1. Set up the formula:**
$$2P = P \left( 1 + \frac{0.045}{4} \right)^{4t}$$
**2. Isolate the Exponential (Divide by $P$):**
Notice the $P$ cancels out on both sides, which is why the initial amount doesn't matter for doubling time.
$$2 = (1.01125)^{4t}$$
**3. Take the Natural Log ($\ln$) of Both Sides:**
$$\ln(2) = \ln(1.01125^{4t})$$
**4. Use the Power Property to bring $4t$ down:**
$$\ln(2) = 4t \cdot \ln(1.01125)$$
**5. Solve for $t$:**
Divide both sides by $4 \cdot \ln(1.01125)$.
$$t = \frac{\ln 2}{4 \ln 1.01125}$$
$$t \approx \frac{0.6931}{4(0.011187)}$$
$$t \approx 15.49 \text{ years}$$
---
#### Method 2: Continuous Compound Interest
**1. Set up the formula:**
$$2P = Pe^{0.045t}$$
**2. Isolate the Exponential (Divide by $P$):**
$$2 = e^{0.045t}$$
**3. Take the Natural Log ($\ln$) of Both Sides:**
$$\ln(2) = \ln(e^{0.045t})$$
**4. Use the Inverse Property ($\ln(e^x) = x$):**
$$\ln(2) = 0.045t$$
**5. Solve for $t$:**
$$t = \frac{\ln 2}{0.045}$$
$$t \approx \frac{0.6931}{0.045}$$
$$t \approx 15.40 \text{ years}$$

---
#### Comparison of Results

| Compounding Method | Formula | Time to Double ($t$) |
| :--- | :--- | :--- |
| **Quarterly ($n=4$)** | $\frac{\ln 2}{n \ln(1+r/n)}$ | **15.49 Years** |
| **Continuous** | $\frac{\ln 2}{r}$ | **15.40 Years** |

> [!IMPORTANT]
> **The Constant Factor:**
> As Professor Leonard demonstrates, the "doubling time" is independent of the amount of money you start with. Whether you start with $\$1$ or $\$1,000,000$, it will take exactly $15.49$ years to double at this quarterly rate.

> [!TIP]
> **Rule of 72 Shortcut:**
> You can estimate this by dividing $72$ by the interest rate ($72 / 4.5 = 16$). Our calculated answers of $\approx 15.5$ years show that the Rule of 72 is a very close approximation for these types of problems!

### Finding the Effective Rate (APY) for $9.75\%$ Compounded Monthly

The "Effective Rate" (or Annual Percentage Yield) represents the actual interest rate earned in one year after compounding is taken into account. Following Professor Leonard's method, we treat this as finding the interest earned on $\$1$ over exactly $1$ year ($t=1$).

**Given Information:**
* **$r$ (Nominal Rate):** $9.75\% = 0.0975$
* **$n$ (Compounding periods):** $12$ (Monthly)
* **$t$ (Time):** $1$ year
* **$P$ (Principal):** $1$ (used as a base to find the percentage increase)

---
#### Method 1: Discrete Effective Rate (Monthly)

To find the effective rate, we use the growth portion of the compound interest formula and subtract the original $100\%$ ($1$) to see only the increase.
**1. Set up the formula:**
$$Y = \left( 1 + \frac{r}{n} \right)^n - 1$$
$$Y = \left( 1 + \frac{0.0975}{12} \right)^{12} - 1$$

**2. Simplify the inner fraction:**
$$\frac{0.0975}{12} = 0.008125$$
**3. Add and apply the exponent:**
$$Y = (1.008125)^{12} - 1$$
$$Y \approx 1.101977 - 1$$
**4. Convert to a percentage:**
$$Y \approx 0.101977 \implies 10.20\%$$

---
#### Method 2: Continuous Effective Rate

For continuous compounding, the formula simplifies significantly because it relies purely on the constant $e$.

**1. Set up the formula:**
$$Y = e^r - 1$$
$$Y = e^{0.0975} - 1$$
**2. Evaluate $e$:**
$$e^{0.0975} \approx 1.102408$$
**3. Subtract the original $1$:**
$$Y \approx 1.102408 - 1$$
$$Y \approx 0.102408$$
**4. Convert to a percentage:**
$$Y \approx 10.24\%$$

---
#### Comparison of Results

| Compounding Method | Formula | Effective Rate (APY) |
| :--- | :--- | :--- |
| **Monthly ($n=12$)** | $(1 + r/n)^n - 1$ | **10.20%** |
| **Continuous** | $e^r - 1$ | **10.24%** |

> [!IMPORTANT]
> **The Takeaway:**
> While the "advertised" (nominal) rate is $9.75\%$, the compounding effect means you actually earn $10.20\%$ over the course of the year. This is why banks often advertise the APY for savings accounts—it looks more attractive than the nominal rate.

> [!TIP]
> **Why $P=1$ and $t=1$?**
> Professor Leonard explains that since we only care about the *rate* of growth, the starting amount is irrelevant. By using $1$ for $P$ and $1$ for $t$, the formula isolates the growth factor itself.

## 2026-May-26 - Exponential Growth and Decay (Precalculus - College Algebra 66) :
https://www.youtube.com/watch?v=rO-C48LY2KY&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=68
### Exponential Growth and Decay

Exponential growth and decay models describe quantities that change at a rate proportional to their current value. While these models are mathematically identical to continuous compound interest ($A = Pe^{rt}$), they use different notation to reflect scientific contexts like biology, chemistry, and physics.

---
#### 1. The General Model
The standard formula for growth and decay is:

$$A(t) = A_0 e^{kt}$$
**Variables Defined:**
* **$A(t)$:** The amount of the substance or population after time $t$.
* **$A_0$:** The initial amount (the amount present at $t = 0$).
* **$k$:** The **growth/decay constant** (relative rate of change).
    * If **$k > 0$**, the model represents **Growth** (e.g., bacteria, investments).
    * If **$k < 0$**, the model represents **Decay** (e.g., radioactive substances, cooling).
* **$t$:** Time (units must be consistent with the rate $k$).
---
#### 2. Key Concept: Doubling Time
Doubling time is the amount of time required for a population to twice its original size ($A(t) = 2A_0$).

**The Shortcut Formula:**
$$t = \frac{\ln 2}{k}$$
* This formula is derived by setting $2A_0 = A_0 e^{kt}$, dividing by $A_0$, and taking the natural log of both sides.
* Notice that doubling time depends **only** on the rate $k$, not on the starting amount $A_0$.
---
#### 3. Key Concept: Half-Life
Half-life is the time required for a quantity to fall to half of its initial value ($A(t) = \frac{1}{2}A_0$). This is most common in radioactive decay problems.

**The Shortcut Formula:**
$$t = \frac{\ln(0.5)}{k} \quad \text{or} \quad k = \frac{\ln(0.5)}{\text{half-life}}$$

* Because $\ln(0.5)$ is negative, and $k$ is negative for decay, the resulting time $t$ will always be positive.
---
#### 4. The Two-Step Problem Strategy
Professor Leonard emphasizes that most problems are "two-step" processes because the growth constant $k$ is rarely given directly.

* **Step 1: Find $k$.** Use a known data point (e.g., "In 5 hours, the population grew to 500") and the initial amount $A_0$ to solve for $k$ using logarithms.
* **Step 2: Answer the Question.** Use the $k$ you just found to predict a future amount $A(t)$ or to find the time $t$ required to reach a specific target.

---
#### 5. Newton’s Law of Cooling
This is a specific application for objects cooling (or warming) to match the temperature of their surroundings.

$$T(t) = T_s + (T_0 - T_s)e^{-kt}$$
**Variables:**
* **$T(t)$:** Temperature of the object at time $t$.
* **$T_s$:** Temperature of the **surroundings** (ambient temperature).
* **$T_0$:** **Initial** temperature of the object.
* **$k$:** A positive constant representing the cooling rate.

---
#### 6. Critical Tips & Common Pitfalls

> [!CAUTION]
> **The Sign of $k$:**
> In decay problems, your algebra will naturally produce a negative value for $k$. If you are solving for $k$ and you get a positive number for a substance that is disappearing, check your division or log steps.

> [!IMPORTANT]
> **Rounding $k$:**
> The constant $k$ is extremely sensitive. If you round it to only two decimal places, your final answer for a large population or long time period will be wildly inaccurate. **Store the exact value of $k$ in your calculator's memory.**

> [!TIP]
> **Units of Time:**
> Ensure $t$ and $k$ use the same units. If $k$ is "per hour," your $t$ must be in hours. If the problem gives you minutes, convert them to hours (e.g., 20 mins = 1/3 hour).

### Solving $C(t) = 100e^{0.045t}$

This problem follows the standard exponential growth/decay model $A(t) = A_0 e^{kt}$. Following Professor Leonard's methodology, we will break down the components of the equation and solve for specific time and amount targets.

---
#### 1. Growth or Decay?
To determine if the model represents growth or decay, we look at the constant $k$ in the exponent.
* **Analysis:** The constant is $0.045$.
* **Rule:** Since $k > 0$ (positive), the function represents **Growth**.
#### 2. Initial Amount?
The initial amount $A_0$ is the coefficient sitting in front of the base $e$. It represents the value when $t = 0$.
* **Analysis:** $C(0) = 100e^{0.045(0)} = 100(1)$.
* **Result:** The initial amount is **100**.
#### 3. Amount After 5 Days?
This is a straightforward evaluation problem where we plug in $t = 5$.
* **Set up:** $C(5) = 100e^{0.045(5)}$
* **Simplify Exponent:** $0.045 \cdot 5 = 0.225$
* **Calculate:**
$$C(5) = 100e^{0.225}$$
$$C(5) \approx 100(1.2523)$$
* **Result:** **$\approx 125.23$**

---
#### 4. How Long to Reach 140?
Here, we are given the future amount $C(t) = 140$ and must solve for $t$.
* **Step 1: Set up the equation.**
$$140 = 100e^{0.045t}$$
* **Step 2: Isolate the exponential part.** Divide both sides by $100$.
$$1.4 = e^{0.045t}$$
* **Step 3: Take the natural log ($\ln$) of both sides.**
$$\ln(1.4) = \ln(e^{0.045t})$$
* **Step 4: Use the Inverse Property.** $\ln(e^u) = u$.
$$\ln(1.4) = 0.045t$$
* **Step 5: Solve for $t$.**
$$t = \frac{\ln(1.4)}{0.045}$$
* **Result:** **$\approx 7.48$ days**

---
#### 5. How Long to Double?
To double the initial amount ($100$), the target amount is $200$. 
* **Step 1: Set up the equation.**
$$200 = 100e^{0.045t}$$
* **Step 2: Isolate the exponential.**
$$2 = e^{0.045t}$$
* **Step 3: Take the $\ln$ of both sides.**
$$\ln(2) = 0.045t$$
* **Step 4: Solve for $t$.**
$$t = \frac{\ln 2}{0.045}$$
* **Result:** **$\approx 15.40$ days**

---
#### Summary of Results
| Question              | Answer               |
| :-------------------- | :------------------- |
| **Growth or Decay?**  | Growth ($k = 0.045$) |
| **Initial Amount?**   | 100                  |
| **Amount at $t=5$**   | 125.23               |
| **Time to reach 140** | 7.48 Days            |
| **Doubling Time**     | 15.40 Days           |

> [!TIP]
> **Professor Leonard's Shortcut:**
> For any doubling time problem with base $e$, you can jump straight to $t = \frac{\ln 2}{k}$. In this case, $t = \frac{\ln 2}{0.045}$.
### Finding a Formula for Bacteria Growth

In this example from the lecture, we are asked to find the specific growth formula for a population that doubles every 3 hours. Since a doubling time is provided, our goal is to solve for the growth constant $k$.

---
#### Step 1: Establish the General Model
We start with the standard exponential growth formula:
$$A(t) = A_0 e^{kt}$$
#### Step 2: Use the Doubling Information
To "double" means the final amount $A(t)$ is twice the initial amount $A_0$.
* **Target:** $A(t) = 2A_0$
* **Time ($t$):** 3 hours
**Plug these into the formula:**
$$2A_0 = A_0 e^{k(3)}$$

#### Step 3: Isolate the Exponential
Divide both sides by $A_0$. Notice that the actual starting population doesn't matter; the ratio will always be 2 for a doubling event.
$$2 = e^{3k}$$
#### Step 4: Solve for $k$ using Logarithms
Take the natural log ($\ln$) of both sides to "bring down" the exponent.
$$\ln(2) = \ln(e^{3k})$$
$$\ln(2) = 3k$$
**Isolate $k$:**
$$k = \frac{\ln 2}{3} \approx 0.2310$$
#### Step 5: Write the Final Formula
Substitute the value of $k$ back into the general model. Following Professor Leonard's advice, we usually leave $k$ in its exact form ($\frac{\ln 2}{3}$) to avoid rounding errors in later calculations.

**The Final Formula:**
$$A(t) = A_0 e^{\left(\frac{\ln 2}{3}\right)t}$$

---

#### Key Takeaways

> [!TIP]
> **The Doubling Shortcut:**
> You can jump straight to $k = \frac{\ln 2}{\text{doubling time}}$. Here, the doubling time was 3, so $k = \frac{\ln 2}{3}$.

> [!IMPORTANT]
> **Alternative Form:**
> Using exponent rules, $e^{\ln 2}$ is just $2$. This means the formula can also be written as:
> $$A(t) = A_0 (2)^{t/3}$$
> This version is often more intuitive: it says the population is the initial amount times 2, raised to the power of how many "3-hour blocks" have passed. However, in Precalculus, instructors usually want the base-$e$ version derived above.
### Solving Half-Life Problems (Radium & Carbon-14)

Following Professor Leonard's "Two-Step" strategy, we first use the half-life to solve for the decay constant $k$, and then use that $k$ to answer the specific question. Both problems utilize the exponential model: $A(t) = A_0 e^{kt}$.

---
#### Problem 1: Radium Decay
**Given:** Half-life = $1690$ years, $A_0 = 20\text{g}$.
**Find:** Amount after $50$ years ($t=50$).

**Step 1: Find $k$**
Using the half-life shortcut: $k = \frac{\ln(0.5)}{\text{half-life}}$
$$k = \frac{\ln(0.5)}{1690} \approx -0.000410146$$


**Step 2: Solve for $A(50)$**
$$A(50) = 20e^{\left(\frac{\ln 0.5}{1690}\right)(50)}$$
$$A(50) = 20e^{-0.020507}$$
$$A(50) \approx 20(0.97969)$$
**Result:** **$\approx 19.59\text{g}$**

---
#### Problem 2: Carbon-14 Dating
**Given:** Half-life = $5730$ years, $A(t) = 30\%$ of $A_0$ (which is $0.30A_0$).
**Find:** Time when the tree died ($t$).

**Step 1: Find $k$**
$$k = \frac{\ln(0.5)}{5730} \approx -0.000120968$$
**Step 2: Solve for $t$**
Set up the equation where the current amount is $30\%$ of the original:
$$0.30A_0 = A_0 e^{kt}$$
Divide by $A_0$:
$$0.30 = e^{kt}$$
Take the natural log ($\ln$) of both sides:
$$\ln(0.30) = kt$$
Substitute $k$ and solve for $t$:
$$t = \frac{\ln(0.30)}{(\ln 0.5 / 5730)}$$
$$t = \frac{-1.20397}{-0.000120968}$$
**Result:** **$\approx 9,952.8$ years ago**

---
#### Key Takeaways

> [!TIP]
> **Why $k$ is negative:**
> In both problems, $k$ is a negative value. This is mathematically required for "Decay." If your $k$ is positive, you are modeling growth, which would mean your radioactive material is magically increasing over time!

> [!CAUTION]
> **The Precision Rule:**
> As Professor Leonard warns, do **not** round $k$ to a few decimal places. In Problem 2, a small change in $k$ can shift the age of the tree by hundreds of years. Always use the exact fraction or store the full number in your calculator.

> [!IMPORTANT]
> **Percentage as Decimals:**
> When a problem says "$30\%$ remains," always use $0.30$. If it says "$30\%$ was lost," then $70\%$ remains, and you must use $0.70$.
### Newton’s Law of Cooling: The Turkey Problem

This problem uses **Newton’s Law of Cooling**, which models how the temperature of an object changes relative to the temperature of its surroundings. Professor Leonard emphasizes that the object doesn't just decay toward zero; it decays toward the **ambient temperature** ($T_s$).

---
#### Step 0: Identify the Variables
* **$T_s$ (Surroundings):** $30^\circ\text{C}$
* **$T_0$ (Initial Temp):** $100^\circ\text{C}$
* **Data Point:** After $5$ minutes ($t=5$), the temperature is $80^\circ\text{C}$.
* **Goal:** Find $t$ when the temperature is $50^\circ\text{C}$.

---
#### Step 1: Set up the General Formula
$$T(t) = T_s + (T_0 - T_s)e^{-kt}$$
Plug in the known temperatures to simplify the equation:
$$T(t) = 30 + (100 - 30)e^{-kt}$$
$$T(t) = 30 + 70e^{-kt}$$

---
#### Step 2: Solve for the Cooling Constant ($k$)
Use the data point $(5, 80)$ to isolate $k$.
1.  **Set up:** $80 = 30 + 70e^{-k(5)}$
2.  **Isolate the exponential:** Subtract $30$, then divide by $70$.
    $$50 = 70e^{-5k}$$
    $$\frac{5}{7} = e^{-5k}$$
3.  **Take the Natural Log ($\ln$):**
    $$\ln(5/7) = -5k$$
4.  **Solve for $k$:**
    $$k = \frac{\ln(5/7)}{-5} \approx 0.06729$$
---
#### Step 3: Solve for the Target Time ($t$)
Find $t$ when $T(t) = 50^\circ\text{C}$.
1.  **Set up:** $50 = 30 + 70e^{-kt}$
2.  **Isolate the exponential:** Subtract $30$, then divide by $70$.
    $$20 = 70e^{-kt}$$
    $$\frac{2}{7} = e^{-kt}$$
3.  **Take the Natural Log ($\ln$):**
    $$\ln(2/7) = -kt$$
4.  **Solve for $t$:**
    $$t = \frac{\ln(2/7)}{-k}$$
    Substitute the exact value of $k$ from Step 2:
    $$t = \frac{\ln(2/7)}{[\ln(5/7) / -5]}$$
**Final Calculation:**
$$t \approx 18.61 \text{ minutes}$$

---
#### Key Takeaways

> [!IMPORTANT]
> **The Difference Term:**
> Note that $T_0 - T_s$ ($70^\circ$) represents the **initial temperature difference**. Newton's Law says that this *difference* is what decays exponentially, not the absolute temperature of the turkey.

> [!CAUTION]
> **Total Time vs. Additional Time:**
> The answer $18.61$ minutes is the **total time** since the turkey came out of the oven. If the question asked "how much *longer*," you would subtract the $5$ minutes that have already passed.

> [!TIP]
> **Ambient Limit:**
> Mathematically, as $t \to \infty$, the term $70e^{-kt}$ goes to $0$, and the turkey's temperature $T(t)$ approaches $30^\circ\text{C}$. It can never naturally cool below the temperature of the house.
## 2026-May-28 - Introduction to Sequences (Precalculus - College Algebra 67) :
https://www.youtube.com/watch?v=c5D7BJ-R41I&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=69
### Introduction to Sequences

A sequence is a mathematical list of numbers that follows a specific pattern or rule. In this lecture, Professor Leonard transitions from continuous functions to discrete mathematics, where we deal with individual "steps" rather than a smooth curve.

---
#### 1. What is a Sequence?
A sequence is essentially a function where the **domain** is restricted to the set of positive integers (1, 2, 3, ...). Instead of using $f(x)$, we use the notation $a_n$.

* **Terms ($a_n$):** The individual numbers in the list.
* **Index ($n$):** The position of the term in the list.
    * $a_1$: The 1st term
    * $a_2$: The 2nd term
    * $a_n$: The $n$-th term (also called the **General Term**)

---
#### 2. Defining Sequences
There are two primary ways to define a sequence:

**A. Explicit Formulas**
The $n$-th term is defined directly by its position ($n$). You can find any term (like the 100th term) without knowing the terms before it.
* *Example:* $a_n = 2n + 1$
* To find the 5th term: $a_5 = 2(5) + 1 = 11$.

**B. Recursive Formulas**
Each term is defined based on the term(s) that came before it. You must be given a starting point ($a_1$).
* *Example:* $a_1 = 4$; $a_n = a_{n-1} + 3$
* To find the 2nd term ($a_2$), you take $a_1$ and add 3.
* *Drawback:* To find the 100th term, you would have to calculate all 99 terms before it.

---
#### 3. Factorial Notation ($n!$)
Sequences frequently use factorials. A factorial is the product of all positive integers from $n$ down to 1.
* **Definition:** $n! = n \cdot (n-1) \cdot (n-2) \cdots 3 \cdot 2 \cdot 1$
* *Special Case:* $0! = 1$ (by definition).

**Simplifying Factorials:**
Professor Leonard emphasizes "expanding" the larger factorial until it matches the smaller one so you can cancel them out.
* *Example:* $\frac{10!}{8!} = \frac{10 \cdot 9 \cdot 8!}{8!} = 10 \cdot 9 = 90$

---
#### 4. Alternating Sequences
If the signs of the terms switch back and forth between positive and negative, the sequence is "alternating." This is caused by a factor of $(-1)^n$ or $(-1)^{n+1}$.
* $(-1)^n$: Starts negative if $n=1$ (Odd indices are negative).
* $(-1)^{n+1}$: Starts positive if $n=1$ (Even indices are negative).

---
#### 5. Summation Notation (Sigma $\Sigma$)
To represent the sum of a sequence, we use the Greek letter Sigma.

$$\sum_{i=1}^{k} a_i$$

* **$i$:** The index of summation (the "counter").
* **$1$:** The lower limit (where to start).
* **$k$:** The upper limit (where to stop).
* **$a_i$:** The formula for the terms.

---
#### 6. Critical Tips & Common Pitfalls

> [!CAUTION]
> **Index Starting Points:**
> While $n=1$ is the standard starting index, some sequences or summations start at $n=0$. Always check the bottom of the Sigma or the problem description to see where the "first" term actually begins.

> [!IMPORTANT]
> **Factorial Expansion:**
> When simplifying something like $\frac{(n+1)!}{n!}$, remember that $(n+1)!$ is just $(n+1) \cdot n!$. The $n!$ terms cancel out, leaving you with just $n+1$.

> [!TIP]
> **Recognizing Patterns:**
> When asked to find a formula for a given list of numbers, look for common patterns:
> * Differences are the same? (Linear: $an + b$)
> * Multiplied by the same number? (Exponential: $r^n$)
> * Perfect squares? ($n^2$)
### Finding the First 5 Terms of $a_n = (-1)^{n-1} \left(\frac{n}{2n-1}\right)$

To find the terms of this sequence, we substitute the values $n = 1, 2, 3, 4, 5$ into the general term formula. This sequence features an **alternating factor**, which causes the signs of the terms to switch back and forth.

---
#### Step-by-Step Term Calculation

**For $n = 1$:**
$$a_1 = (-1)^{1-1} \left(\frac{1}{2(1)-1}\right) = (-1)^0 \left(\frac{1}{1}\right) = (1)(1) = 1$$

**For $n = 2$:**
$$a_2 = (-1)^{2-1} \left(\frac{2}{2(2)-1}\right) = (-1)^1 \left(\frac{2}{3}\right) = (-1)\left(\frac{2}{3}\right) = -\frac{2}{3}$$

**For $n = 3$:**
$$a_3 = (-1)^{3-1} \left(\frac{3}{2(3)-1}\right) = (-1)^2 \left(\frac{3}{5}\right) = (1)\left(\frac{3}{5}\right) = \frac{3}{5}$$

**For $n = 4$:**
$$a_4 = (-1)^{4-1} \left(\frac{4}{2(4)-1}\right) = (-1)^3 \left(\frac{4}{7}\right) = (-1)\left(\frac{4}{7}\right) = -\frac{4}{7}$$

**For $n = 5$:**
$$a_5 = (-1)^{5-1} \left(\frac{5}{2(5)-1}\right) = (-1)^4 \left(\frac{5}{9}\right) = (1)\left(\frac{5}{9}\right) = \frac{5}{9}$$

---
#### The Resulting Sequence
The first five terms are:
$$1, -\frac{2}{3}, \frac{3}{5}, -\frac{4}{7}, \frac{5}{9}$$

---
#### Critical Tips & Observations

> [!TIP]
> **The Alternating Pattern:**
> The factor $(-1)^{n-1}$ is a "switch." 
> * When $n$ is **odd**, the exponent $(n-1)$ is **even**, making the term **positive**.
> * When $n$ is **even**, the exponent $(n-1)$ is **odd**, making the term **negative**.

> [!IMPORTANT]
> **Zero Power Rule:**
> In the first term calculation, we have $(-1)^0$. Remember that any non-zero number raised to the zero power is always **1**.

> [!WARNING]
> **Recognizing the Fraction:**
> Notice the denominator is always one less than twice the numerator. If you were asked to find the formula from the list, you would look for that $2n-1$ relationship in the odd numbers $(1, 3, 5, 7, 9)$.
### Finding the General Term ($a_n$) for the Sequence: $1, \frac{1}{2}, \frac{1}{4}, \frac{1}{8}, \dots$

In this example, we are working backward. Given a list of terms, we must identify the pattern to create an **explicit formula**. Professor Leonard suggests looking at the relationship between the term's position ($n$) and the value of the term.

---
#### Step 1: Analyze the Pattern
Let's list the terms and their indices ($n$):
* $n=1 \implies a_1 = 1$
* $n=2 \implies a_2 = 1/2$
* $n=3 \implies a_3 = 1/4$
* $n=4 \implies a_4 = 1/8$

**Observation:** Each denominator is a power of $2$. 
* $1/2 = 1/2^1$
* $1/4 = 1/2^2$
* $1/8 = 1/2^3$
#### Step 2: Relate the Exponent to the Index ($n$)
Notice that the exponent of the $2$ is always **one less** than the position ($n$):
* When $n=2$, the exponent is $1$.
* When $n=3$, the exponent is $2$.
* When $n=4$, the exponent is $3$.

Following this pattern, for $n=1$, the denominator should be $2^0$. Since $2^0 = 1$, the first term matches perfectly ($1/1 = 1$).
#### Step 3: Write the General Formula
Combining these observations, the formula for the $n$-th term is:
$$a_n = \frac{1}{2^{n-1}}$$

Alternatively, using the property $(a/b)^n = a^n/b^n$, you can write it as:
$$a_n = \left(\frac{1}{2}\right)^{n-1}$$
---
#### Key Takeaways

> [!TIP]
> **Geometric Patterns:**
> When each term is found by multiplying the previous term by a constant (in this case, $1/2$), it is a **Geometric Sequence**. The general form for these is often $a_n = a_1(r)^{n-1}$.

> [!IMPORTANT]
> **The Zero Exponent:**
> Always check your formula against $n=1$. Many students accidentally write $1/2^n$, but for $n=1$, that would give $1/2$. Subtracting $1$ from the index ($n-1$) is the standard way to "shift" the starting value.

> [!WARNING]
> **Recursive vs. Explicit:**
> While you could define this recursively as $a_n = \frac{1}{2} a_{n-1}$, Professor Leonard usually looks for the **explicit** version first, as it allows you to find any term (like the 50th) instantly.
### Finding the General Term ($b_n$) for the Sequence: $2, -4, 6, -8, 10, \dots$

In this problem, we are looking for a formula that generates both the absolute values of the numbers and the alternating signs. Professor Leonard recommends splitting the problem into two parts: the "number part" and the "sign part."

---
#### Step 1: Analyze the Absolute Values (The Numbers)
Ignoring the negative signs, look at the list: $2, 4, 6, 8, 10$.
* $n=1 \implies 2$
* $n=2 \implies 4$
* $n=3 \implies 6$
* $n=4 \implies 8$

**Observation:** These are all multiples of $2$. Each term is simply the index ($n$) multiplied by $2$.
* **Number Part:** $2n$
#### Step 2: Analyze the Alternating Signs
The signs of the terms are: $(+), (-), (+), (-), (+)$.
* When $n$ is **odd** ($1, 3, 5$), the term is **positive**.
* When $n$ is **even** ($2, 4$), the term is **negative**.
To get this effect, we use the factor $(-1)$ raised to a power.
* If we used $(-1)^n$, the first term ($n=1$) would be negative.
* Since we want the first term to be positive, we need an even exponent when $n=1$. We can use **$n+1$** or **$n-1$**.

**Sign Part:** $(-1)^{n+1}$
#### Step 3: Combine the Parts
Multiply the "sign part" by the "number part" to get the full explicit formula:
$$b_n = (-1)^{n+1}(2n)$$
---
#### Key Takeaways

> [!TIP]
> **The Sign Switch:**
> * Use $(-1)^n$ if you want **even** terms to be positive and **odd** terms to be negative.
> * Use $(-1)^{n+1}$ (or $n-1$) if you want **odd** terms to be positive and **even** terms to be negative.

> [!IMPORTANT]
> **Check your work:**
> Always test the formula with $n=2$ to ensure the sign is correct:
> $b_2 = (-1)^{2+1}(2 \cdot 2) = (-1)^3(4) = -4$. 
> It matches the sequence!

> [!WARNING]
> **Linear vs. Exponential:**
> Because the numbers increase by adding ($+2$ each time) rather than multiplying, this is an arithmetic-based pattern ($2n$) rather than a power-based pattern (like $2^n$).

### Finding the General Term ($a_n$) for the Sequence: $-\frac{2}{3}, \frac{4}{9}, -\frac{8}{27}, \frac{16}{81}, \dots$

This sequence involves fractions with powers in both the numerator and denominator, as well as alternating signs. To solve this like Professor Leonard, we analyze the "Sign," the "Numerator," and the "Denominator" as three separate patterns.

---
#### Step 1: Analyze the Signs
The signs are: $(-), (+), (-), (+)$.
* When $n=1$, the sign is negative.
* When $n=2$, the sign is positive.
* **Rule:** Since the odd positions are negative, we use the simplest alternating factor: **$(-1)^n$**.
#### Step 2: Analyze the Numerators
Looking at the numbers: $2, 4, 8, 16$.
* $n=1 \implies 2^1$
* $n=2 \implies 4 = 2^2$
* $n=3 \implies 8 = 2^3$
* **Rule:** The numerator is simply **$2^n$**.
#### Step 3: Analyze the Denominators
Looking at the numbers: $3, 9, 27, 81$.
* $n=1 \implies 3^1$
* $n=2 \implies 9 = 3^2$
* $n=3 \implies 27 = 3^3$
* **Rule:** The denominator is **$3^n$**.
#### Step 4: Combine into One Formula
We can string these three rules together:
$$a_n = (-1)^n \frac{2^n}{3^n}$$
**Simplifying the Formula:**
Since both the numerator and denominator are raised to the power of $n$, and the negative sign can be absorbed into the fraction, we can use the Power of a Quotient rule to write it more cleanly:
$$a_n = \left(-\frac{2}{3}\right)^n$$

---
#### Key Takeaways

> [!TIP]
> **The "Clean" Version:**
> Whenever the sign, numerator, and denominator all share the same exponent $n$, you can group them into a single set of parentheses. This is the most efficient way to write a **Geometric Sequence**.

> [!IMPORTANT]
> **Check the First Term:**
> Always verify $n=1$ immediately. 
> $a_1 = (-2/3)^1 = -2/3$. 
> Since this matches our list exactly, we don't need an $n-1$ shift.

> [!WARNING]
> **Base Sensitivity:**
> Because the base $(-2/3)$ is negative, the terms will always bounce between positive and negative. Because the absolute value $(2/3)$ is less than 1, the terms will get smaller and smaller (approach zero) as $n$ increases.

### Finding the General Term ($b_n$) for the Sequence: $1, 3, 5, 7, 9, \dots$

This is a classic sequence of **odd numbers**. To find the explicit formula like Professor Leonard, we look for a linear relationship between the position ($n$) and the value.

---
#### Step 1: Analyze the Pattern
Let's look at the "distance" between the terms:
* $1 \xrightarrow{+2} 3 \xrightarrow{+2} 5 \xrightarrow{+2} 7 \xrightarrow{+2} 9$

**Observation:** There is a **common difference** of $2$. In sequence math, a constant addition means the formula will be **linear** (similar to $y = mx + b$).
#### Step 2: Set up the Linear Form
Because the terms increase by $2$ every time the index $n$ increases by $1$, the "slope" or rate of change is $2$. This gives us the first part of our formula:
* **Part 1:** $2n$
#### Step 3: Adjust for the Starting Value
Now we test our "Part 1" formula with $n = 1$:
* If $n = 1$, then $2(1) = 2$.
* However, our actual first term is **$1$**.

To get from our result ($2$) to the target ($1$), we need to subtract $1$.
* **Adjustment:** $2n - 1$
#### Step 4: Verify the Formula
Let's test the formula $b_n = 2n - 1$ with $n = 4$:
* $b_4 = 2(4) - 1 = 8 - 1 = 7$.
* It matches the 4th term in our list!

**The Final Formula:**
$$b_n = 2n - 1$$
---
#### Key Takeaways

> [!TIP]
> **The Arithmetic Sequence Shortcut:**
> For any sequence with a common difference ($d$), the formula is always:
> $a_n = a_1 + (n-1)d$.
> For this problem: $1 + (n-1)2 = 1 + 2n - 2 = \mathbf{2n - 1}$.

> [!IMPORTANT]
> **Identifying Odd vs. Even:**
> * **Even Numbers:** $2n$ (starts at 2, 4, 6...)
> * **Odd Numbers:** $2n - 1$ (starts at 1, 3, 5...)

> [!WARNING]
> **Check the "y-intercept":**
> In $y = mx + b$, $b$ is the value at $x = 0$. In sequences, if you find the "0-th" term (going back one step from the first term), it often gives you the constant for your formula.
> (e.g., $1 - 2 = -1$. So the formula is $2n - 1$).

## 2026-May-29 - Introduction to Series and Summation Notation (Precalculus - College Algebra 68) :
https://www.youtube.com/watch?v=Ipz9xXeoaRc&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=69
### Introduction to Series and Summation Notation

A **Series** is the result of adding the terms of a sequence together. While a sequence is just a list of numbers ($a_1, a_2, a_3, \dots$), a series is the **sum** of those numbers ($a_1 + a_2 + a_3 + \dots$).

---
#### 1. Summation (Sigma) Notation
To represent a series concisely, we use the Greek letter **Sigma ($\Sigma$)**.
**Components:**
* **Index of Summation ($i, j, \text{ or } k$):** The "counter" variable.
* **Lower Limit:** The starting integer value for the index (usually $1$ or $0$).
* **Upper Limit ($n$):** The ending integer value for the index.
* **General Term ($a_i$):** The formula used to generate each term in the sum.

---
#### 2. Finite vs. Infinite Series
* **Finite Series:** Has a specific ending point ($n$). You can calculate a single numerical total.
* **Infinite Series:** Goes on forever ($\infty$).
    * Notation: $\sum_{i=1}^{\infty} a_i$
    * These only have a finite sum if the terms "shrink" fast enough to **converge**.

---
#### 3. Properties of Summation
Professor Leonard highlights three key properties that allow us to manipulate sums algebraically:

1. **Constant Multiple Rule:** You can pull a constant coefficient *outside* the sigma.
   $$\sum_{i=1}^{n} c \cdot a_i = c \sum_{i=1}^{n} a_i$$
2. **Sum/Difference Rule:** You can split a sigma across addition or subtraction.
   $$\sum (a_i \pm b_i) = \sum a_i \pm \sum b_i$$
3. **Constant Value Sum:** If you sum a constant $c$, $n$ times:
   $$\sum_{i=1}^{n} c = n \cdot c$$
---
#### 4. The Power Sum Formulas
For certain common series, we use "shortcuts" so we don't have to add every term manually. These are essential for Calculus.
* **Sum of the first $n$ integers:**
  $$\sum_{i=1}^{n} i = \frac{n(n+1)}{2}$$
* **Sum of the first $n$ squares:**
  $$\sum_{i=1}^{n} i^2 = \frac{n(n+1)(2n+1)}{6}$$
* **Sum of the first $n$ cubes:**
  $$\sum_{i=1}^{n} i^3 = \left[ \frac{n(n+1)}{2} \right]^2$$

---
#### 5. Two-Step Problem Strategy
1. **Expand:** Write out the first few terms by plugging in the index values to understand the pattern.
2. **Evaluate:** Use the formulas above or arithmetic to find the total sum.

---
#### Critical Tips & Common Pitfalls

> [!CAUTION]
> **The Index Starting Point:**
> If the index starts at $i=0$ and goes to $n$, there are actually **$n+1$** terms. If it starts at $i=1$, there are **$n$** terms. This affects the "Constant Value Sum" rule!

> [!IMPORTANT]
> **Order of Operations:**
> Calculate the general term $a_i$ for the specific index *before* adding.
> *Example:* In $\sum i^2$, you square the number first, then add it to the next squared number.

> [!TIP]
> **Linearity:**
> If you have a complex formula like $\sum (3i + 2)$, use the properties to turn it into $3\sum i + \sum 2$. This allows you to use the $n(n+1)/2$ shortcut for the $i$ part.

### Summation Power Formulas (The Shortcuts)

When dealing with a finite series, adding every term individually is inefficient. Professor Leonard uses these formulas as "shortcuts" to find the total sum ($S_n$) instantly, provided the sum starts at $k=1$.

---
#### 1. Sum of a Constant ($C$)
If you add the same constant number $C$ for $n$ terms, you are simply performing multiplication.
$$\sum_{k=1}^{n} C = C \cdot n$$
* **Special Case ($C=1$):**
  $$\sum_{k=1}^{n} 1 = n$$
  *(If you add "1" ten times, the result is 10).*


---
#### 2. Sum of the First $n$ Integers ($k$)
This formula calculates the sum $1 + 2 + 3 + \dots + n$.
$$\sum_{k=1}^{n} k = \frac{n(n+1)}{2}$$


---
#### 3. Sum of the First $n$ Squares ($k^2$)
This formula calculates the sum $1^2 + 2^2 + 3^2 + \dots + n^2$.
$$\sum_{k=1}^{n} k^2 = \frac{n(n+1)(2n+1)}{6}$$


---
#### 4. Sum of the First $n$ Cubes ($k^3$)
This formula calculates the sum $1^3 + 2^3 + 3^3 + \dots + n^3$.
$$\sum_{k=1}^{n} k^3 = \left[ \frac{n(n+1)}{2} \right]^2$$
*(Notice that this is exactly the same as the "Sum of $k$" formula, just squared).*


---
#### Key Takeaways

> [!IMPORTANT]
> **The $k=1$ Requirement:**
> These specific formulas **only** work if the lower limit of the summation is $1$. If the sum starts at $k=0$ or $k=5$, you must adjust the series before applying these rules.

> [!TIP]
> **Using Linearity:**
> If you have a complex sum like $\sum (k^2 + 3k)$, Professor Leonard recommends splitting it into $\sum k^2 + 3\sum k$. This allows you to plug the formulas into each part separately.

> [!CAUTION]
> **The Variable $n$:**
> In these formulas, $n$ represents the **Upper Limit** (the last number you plug in). Always identify $n$ first before starting your calculation.

### Evaluating the Series: $\sum_{k=1}^{12} (k^3 - 4k^2 + 5k + 7)$

To solve this like Professor Leonard, we use the **Properties of Summation** to break the large, complex sigma into four smaller, manageable parts. We will then apply the power sum formulas where $n = 12$.

---
#### Step 1: Distribute the Sigma
Using the sum and difference properties, we rewrite the expression:
$$\sum_{k=1}^{12} k^3 - 4\sum_{k=1}^{12} k^2 + 5\sum_{k=1}^{12} k + \sum_{k=1}^{12} 7$$


---
#### Step 2: Apply the Power Sum Formulas ($n = 12$)

**Part A: The Cubes term ($\sum k^3$)**
Formula: $\left[ \frac{n(n+1)}{2} \right]^2$
$$\left[ \frac{12(13)}{2} \right]^2 = [6 \cdot 13]^2 = 78^2 = \mathbf{6,084}$$

**Part B: The Squares term ($-4\sum k^2$)**
Formula: $-4 \left[ \frac{n(n+1)(2n+1)}{6} \right]$
$$-4 \left[ \frac{12(13)(25)}{6} \right] = -4 [2 \cdot 13 \cdot 25] = -4 [650] = \mathbf{-2,600}$$

**Part C: The Linear term ($5\sum k$)**
Formula: $5 \left[ \frac{n(n+1)}{2} \right]$
$$5 \left[ \frac{12(13)}{2} \right] = 5 [6 \cdot 13] = 5 [78] = \mathbf{390}$$

**Part D: The Constant term ($\sum 7$)**
Formula: $C \cdot n$
$$7 \cdot 12 = \mathbf{84}$$

---
#### Step 3: Combine the Results
Now, we add all the evaluated parts together:
$$6,084 - 2,600 + 390 + 84$$

**Calculation:**
* $6,084 - 2,600 = 3,484$
* $3,484 + 390 = 3,874$
* $3,874 + 84 = 3,958$

**Final Answer:**
$$\mathbf{3,958}$$

---
#### Key Takeaways

> [!IMPORTANT]
> **The Constant Factor:**
> Notice in Part D that we didn't just write "7." Because the sigma tells us to add 7 for every step from 1 to 12, we must multiply the constant by $n$.

> [!TIP]
> **Arithmetic Order:**
> When calculating the squares ($\sum k^2$), Professor Leonard always recommends dividing the $n(n+1)(2n+1)$ by 6 *before* multiplying by the coefficient out front (in this case, 4). This keeps the numbers smaller and easier to manage without a calculator.

> [!CAUTION]
> **Check the Exponents:**
> It is a common mistake to mix up the formulas for $k^2$ and $k^3$. Always double-check your formula sheet before plugging in $n$:
> * $k^2 \implies \text{division by } 6$
> * $k^3 \implies \text{division by } 2, \text{ then squared}$

### Evaluating Series with Adjusted Limits: $\sum_{k=4}^{24} k^3$

When a summation does not start at $k=1$, we cannot directly use the standard power sum formulas. Following Professor Leonard’s method, we treat this as a "subtraction" problem: calculate the total sum from $1$ to $24$, and then subtract the "missing" part from $1$ to $3$.

---
#### Step 1: The Subtraction Property
We rewrite the series to isolate the desired range:
$$\sum_{k=4}^{24} k^3 = \sum_{k=1}^{24} k^3 - \sum_{k=1}^{3} k^3$$

#### Step 2: Calculate the Total Sum ($\sum_{k=1}^{24} k^3$)
Using the formula $\left[ \frac{n(n+1)}{2} \right]^2$ with $n=24$:
* Sum $= \left[ \frac{24(25)}{2} \right]^2$
* Sum $= [12 \cdot 25]^2$
* Sum $= [300]^2 = \mathbf{90,000}$
#### Step 3: Calculate the "Missing" Sum ($\sum_{k=1}^{3} k^3$)
Using the formula with $n=3$:
* Sum $= \left[ \frac{3(4)}{2} \right]^2$
* Sum $= [6]^2 = \mathbf{36}$
#### Step 4: Final Subtraction
Subtract the missing sum from the total sum:
$$90,000 - 36 = \mathbf{89,964}$$

---
#### Key Takeaways

> [!IMPORTANT]
> **Why Subtract 1 to 3?**
> If you need the sum from $4$ to $24$, you want to include $4, 5, 6, \dots, 24$. The sum from $1$ to $24$ includes all those numbers *plus* $1, 2,$ and $3$. By subtracting the sum of $1, 2, 3$, you are left exactly with the range you need.

> [!TIP]
> **Check the Boundary:**
> A common mistake is subtracting the sum up to $4$. Remember, you want to keep $k=4$ in your final answer, so you must only subtract up to $k=3$.

> [!CAUTION]
> **Formula Applicability:**
> These power sum formulas only work when the lower limit is $1$. This subtraction technique is the standard way to "force" any range of summation to start at $1$ so the formulas can be applied.

## 2026-May-30 - Arithmetic Sequences (Precalculus - College Algebra 69) :
https://www.youtube.com/watch?v=bxGmjouB6t4&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=71
### Arithmetic Sequences

An arithmetic sequence is a sequence where the difference between consecutive terms is constant. This constant value is known as the **common difference** ($d$).

---
#### 1. The Defining Property
A sequence is arithmetic if every term $a_n$ can be generated by adding $d$ to the previous term $a_{n-1}$.
* **Recursive Definition:** $a_n = a_{n-1} + d$
* **Common Difference ($d$):** $d = a_n - a_{n-1}$

---
#### 2. The Explicit Formula
While recursive formulas are useful for understanding the pattern, the **explicit formula** allows us to calculate any term $n$ directly without knowing all the preceding terms.

**The Formula:**
$$a_n = a_1 + (n - 1)d$$

**Why it works:** To get to the $n$-th term, you start at the first term ($a_1$) and "add the difference" ($d$) a total of $(n-1)$ times. For example, to get to the 5th term, you add $d$ four times.

---
#### 3. Arithmetic Sequence as a Linear Function
Professor Leonard emphasizes that arithmetic sequences are essentially **linear functions** with a restricted domain of positive integers.
* If you compare $a_n = a_1 + (n-1)d$ to the slope-intercept form $y = mx + b$:
    * The common difference **$d$** acts as the **slope** ($m$).
    * The sequence values increase or decrease at a steady, linear rate.

---
#### 4. The Sum of an Arithmetic Series
When you add the terms of an arithmetic sequence together, you get an **arithmetic series**. Calculating this manually for a large number of terms is tedious, so we use the sum formulas.

**Sum Formula 1 (Using first and last term):**
$$S_n = \frac{n(a_1 + a_n)}{2}$$
**Sum Formula 2 (Using only first term and common difference):**
$$S_n = \frac{n}{2}[2a_1 + (n-1)d]$$
---
#### Critical Tips & Common Pitfalls

> [!TIP]
> **Finding $d$:**
> Always subtract the first term from the second ($a_2 - a_1$). Even if the numbers look obvious, doing this calculation ensures you catch negative differences (e.g., $10, 7, 4 \dots \implies d = -3$).

> [!IMPORTANT]
> **The $(n-1)$ Trap:**
> A very common error is using $n$ instead of $(n-1)$ in the explicit formula. Always remember: if you are at term 1, you haven't added the difference yet ($n-1 = 0$).

> [!CAUTION]
> **Series vs. Sequence:**
> A **sequence** is the list of numbers itself (separated by commas). A **series** is the sum of those numbers (separated by plus signs). Ensure you know which one the problem is asking for before applying the sum formulas.

## 2026-May-31 - Arithmetic Series (Precalculus - College Algebra 70) :
https://www.youtube.com/watch?v=XdXQjHsl4q0&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=72
### Arithmetic Series

An **Arithmetic Series** is the sum of the terms of an arithmetic sequence. While the sequence is the list (e.g., $1, 3, 5, 7$), the series is the evaluated total (e.g., $1 + 3 + 5 + 7 = 16$).

---
#### 1. The Sum Formulas
Professor Leonard provides two primary ways to find the sum ($S_n$) of the first $n$ terms.

**Formula 1: The "Pairing" Method**
If you know the first term ($a_1$) and the last term ($a_n$), use this formula. It is based on the idea of pairing the first and last terms, which always sum to the same value.
$$S_n = \frac{n(a_1 + a_n)}{2}$$

**Formula 2: The "Direct" Method**
If you only have the first term ($a_1$) and the common difference ($d$), use this version.
$$S_n = \frac{n}{2}[2a_1 + (n-1)d]$$

---
#### 2. Determining $n$ (The Number of Terms)
Often, a problem will give you a series like $5 + 8 + 11 + \dots + 50$ without telling you how many terms ($n$) there are. You must solve for $n$ first.

**The Strategy:**
Use the arithmetic sequence formula ($a_n = a_1 + (n-1)d$) and solve for $n$.
1. Plug in $a_n$ (the last term).
2. Plug in $a_1$ (the first term).
3. Plug in $d$ (the common difference).
4. Solve the linear equation for $n$.

---
#### 3. Summation Notation for Arithmetic Series
Arithmetic series can be written using sigma notation. If the general term inside the sigma is linear (e.g., $3k + 2$), you know it is an arithmetic series.

**Steps to evaluate $\sum_{k=1}^{n} (ak + b)$:**
1. Find the first term ($a_1$) by plugging in the lower limit.
2. Find the last term ($a_n$) by plugging in the upper limit.
3. Identify $n$ (the number of terms: top - bottom + 1).
4. Apply the sum formula $S_n = \frac{n(a_1 + a_n)}{2}$.

---
#### Critical Tips & Common Pitfalls

> [!TIP]
> **The Gauss Trick:**
> Professor Leonard often shares the legend of Carl Friedrich Gauss, who calculated the sum of $1$ to $100$ instantly by realizing $1+100=101, 2+99=101, \dots$ and that there are $50$ such pairs. This is the exact logic behind Formula 1.

> [!CAUTION]
> **Counting the Terms:**
> If a series goes from $k=5$ to $k=20$, do **not** assume $n=15$. The number of terms is always $( \text{Upper Limit} - \text{Lower Limit} + 1 )$.
> *Example:* $20 - 5 + 1 = 16$ terms.

> [!IMPORTANT]
> **Sequence vs. Series:**
> * **Arithmetic Sequence ($a_n$):** Tells you the *value* of the $n$-th term.
> * **Arithmetic Series ($S_n$):** Tells you the *sum* of all terms up to $n$.
> Always verify which the question is asking for before plugging in values.

### Finding the Sum of the Arithmetic Series: $60 + 64 + 68 + 72 + \dots + 120$

To solve this like Professor Leonard, we identify this as an arithmetic series because the difference between consecutive terms is constant. We will use the formula $S_n = \frac{n(a_1 + a_n)}{2}$, but first, we must find the number of terms ($n$).

---
#### Step 1: Identify Known Variables
* **First term ($a_1$):** $60$
* **Last term ($a_n$):** $120$
* **Common difference ($d$):** $64 - 60 = 4$
#### Step 2: Solve for the number of terms ($n$)
We use the explicit formula for an arithmetic sequence: $a_n = a_1 + (n - 1)d$
1. **Set up the equation:**
   $120 = 60 + (n - 1)4$
2. **Subtract $60$ from both sides:**
   $60 = (n - 1)4$
3. **Divide by $4$:**
   $15 = n - 1$
4. **Solve for $n$:**
   $n = 16$
There are **16 terms** in this series.
#### Step 3: Calculate the Sum ($S_n$)
Now, use the sum formula $S_n = \frac{n(a_1 + a_n)}{2}$:
1. **Plug in the values:**
   $S_{16} = \frac{16(60 + 120)}{2}$
2. **Simplify the parentheses:**
   $S_{16} = \frac{16(180)}{2}$
3. **Finish the calculation:**
   $S_{16} = 8(180) = \mathbf{1,440}$

---
#### Key Takeaways

> [!IMPORTANT]
> **Always Find $n$ First:**
> Many students attempt to guess $n$ by just dividing $120/4$. This is incorrect! Always use the formula $n = \frac{a_n - a_1}{d} + 1$ to ensure accuracy.

> [!TIP]
> **Gauss's Pairing Method:**
> Notice that $60 + 120 = 180$. The pair inside ($64 + 116$) also equals $180$. You have 16 terms, which means you have 8 pairs of 180. $8 \times 180 = 1,440$. This is the logic the formula is built on!

> [!CAUTION]
> **Verify the Sequence:**
> Always quickly check that the difference is truly constant for the whole list. If the difference changed halfway through, it wouldn't be an arithmetic series, and this formula would not apply.

## 2026-June-02 - Geometric Sequences (Precalculus - College Algebra 71) :
https://www.youtube.com/watch?v=qyHCnYewdrQ&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=73
### Geometric Sequences

A geometric sequence is a sequence where each term is found by multiplying the previous term by a fixed, non-zero number called the **common ratio** ($r$).

---
#### 1. The Defining Property
Unlike arithmetic sequences that add a common difference, geometric sequences rely on a common ratio.
* **Recursive Definition:** $a_n = a_{n-1} \cdot r$
* **Common Ratio ($r$):** $r = \frac{a_n}{a_{n-1}}$



---
#### 2. The Explicit Formula
To find any specific term ($n$) without calculating all the terms before it, we use the explicit formula.

**The Formula:**
$$a_n = a_1 \cdot r^{n-1}$$

**Why it works:** To reach the $n$-th term, you start with the first term ($a_1$) and multiply it by the ratio ($r$) a total of $(n-1)$ times.

---
#### 3. Growth Characteristics
Professor Leonard emphasizes how the value of $r$ fundamentally changes the behavior of the sequence:
* **$r > 1$:** The sequence grows rapidly (Exponential Growth).
* **$0 < r < 1$:** The sequence shrinks, approaching zero (Exponential Decay).
* **$r < 0$:** The sequence **alternates** between positive and negative values (because multiplying by a negative flips the sign).

---
#### 4. Geometric Sequences vs. Arithmetic
It is critical to distinguish between the two:
* **Arithmetic:** Constant *addition* (linear pattern).
* **Geometric:** Constant *multiplication* (exponential pattern).

---
#### Critical Tips & Common Pitfalls

> [!TIP]
> **Finding $r$:**
> Always divide the second term by the first ($a_2 / a_1$). Even if the numbers look easy, using division ensures you handle fractions and negative ratios correctly (e.g., $10, -5, 2.5 \dots \implies r = -0.5$).

> [!IMPORTANT]
> **The $(n-1)$ Exponent:**
> Just like the arithmetic sequence uses $(n-1)$ to count the number of "steps" of addition, the geometric formula uses $(n-1)$ to count the number of "steps" of multiplication. If you are on the 1st term, $n-1 = 0$, and $r^0 = 1$, correctly leaving you with just $a_1$.

> [!CAUTION]
> **The Common Ratio $r=0$:**
> By definition, geometric sequences do not have a common ratio of $0$, as this would make all subsequent terms zero, which is trivial and not typically studied in this context. Always ensure $r \neq 0$.

### Identifying Geometric Sequences

Professor Leonard teaches us that to determine if a sequence is geometric, we must check if there is a **constant ratio** ($r$) between every consecutive term. If the ratio $r = \frac{a_n}{a_{n-1}}$ is the same for the entire list, it is a geometric sequence.

---
#### 1. Analyzing the Provided Sequences

Let's test each sequence from your image to see which ones are geometric.
**Sequence A: $2, -6, 18, -54, 162, \dots$**
* Test ratios:
    * $\frac{-6}{2} = -3$
    * $\frac{18}{-6} = -3$
    * $\frac{-54}{18} = -3$
* **Result:** Since the ratio is consistently $-3$, this is a **Geometric Sequence** with $r = -3$.
**Sequence B: $2, 9, 16, 23, 30, \dots$**
* Test ratios:
    * $\frac{9}{2} = 4.5$
    * $\frac{16}{9} \approx 1.77$
* **Result:** The ratios are not constant. (Note: This is an **Arithmetic Sequence** with $d = 7$).
**Sequence C: $1, 2, 4, 7, 11, 16, 22, \dots$**
* Test ratios:
    * $\frac{2}{1} = 2$
    * $\frac{4}{2} = 2$
    * $\frac{7}{4} = 1.75$
* **Result:** The ratios are not constant. (Note: This is a sequence where the *difference* increases by 1 each time).
**Sequence D: $7, 14, 28, 56, \dots$**
* Test ratios:
    * $\frac{14}{7} = 2$
    * $\frac{28}{14} = 2$
    * $\frac{56}{28} = 2$
* **Result:** Since the ratio is consistently $2$, this is a **Geometric Sequence** with $r = 2$.

---
#### Summary Table

| Sequence | Type | Common Ratio ($r$) |
| :--- | :--- | :--- |
| $2, -6, 18, -54, 162, \dots$ | Geometric | $-3$ |
| $2, 9, 16, 23, 30, \dots$ | Not Geometric | N/A |
| $1, 2, 4, 7, 11, 16, 22, \dots$ | Not Geometric | N/A |
| $7, 14, 28, 56, \dots$ | Geometric | $2$ |


---
#### Key Takeaways

> [!TIP]
> **The Division Test:**
> To find $r$, always perform division: $a_2 \div a_1$. If you get a different answer when you test $a_3 \div a_2$, then it is not a geometric sequence.

> [!IMPORTANT]
> **Negative Ratios:**
> As seen in the first sequence ($2, -6, 18 \dots$), a negative ratio creates an alternating sign pattern. This is a hallmark of geometric sequences where $r < 0$.

> [!CAUTION]
> **Visual Traps:**
> Just because a sequence grows quickly (like Sequence C: $1, 2, 4, 7 \dots$) does not automatically make it geometric. Always perform the division test to confirm the ratio is constant before labeling it "geometric."

### Finding the General Formula for a Geometric Sequence

To determine the explicit formula $a_n = a_1 \cdot r^{n-1}$ for the sequence $-3, 1, -\frac{1}{3}, \frac{1}{9}, \dots$, we must identify the first term ($a_1$) and the common ratio ($r$).

---
#### 1. Identify the Components
* **First term ($a_1$):** By inspection, $a_1 = -3$.
* **Common ratio ($r$):** Calculate the ratio by dividing the second term by the first term:
    $$r = \frac{a_2}{a_1} = \frac{1}{-3} = -\frac{1}{3}$$
* **Verify the ratio:** Check with the next terms:
    $$r = \frac{a_3}{a_2} = \frac{-1/3}{1} = -\frac{1}{3}$$
    Since the ratio is consistent, this is a valid **Geometric Sequence**.
#### 2. Construct the Explicit Formula
Plug $a_1$ and $r$ into the standard form $a_n = a_1 \cdot r^{n-1}$:
$$a_n = -3 \cdot \left(-\frac{1}{3}\right)^{n-1}$$
#### 3. Simplifying the Formula (Optional)
We can simplify this by recognizing that $-3$ is the inverse of $1/3$:
* $-3 = -1 \cdot 3^1$
* $a_n = -1 \cdot 3^1 \cdot \left(\frac{-1}{3}\right)^{n-1}$

Alternatively, leave it in the standard form, as it clearly shows the starting value and the decay/alternating ratio.

---
#### Key Takeaways

> [!TIP]
> **Handling Negative Ratios:**
> When the ratio $r$ is negative (in this case, $-1/3$), the sequence will always alternate signs. Always place the negative ratio inside parentheses $(r)^{n-1}$ to ensure the negative sign is applied correctly across the power $n-1$.

> [!IMPORTANT]
> **Check your work:**
> Always verify the formula with the second term ($n=2$):
> $a_2 = -3 \cdot (-1/3)^{2-1} = -3 \cdot (-1/3)^1 = -3 \cdot (-1/3) = 1$.
> It matches!

> [!CAUTION]
> **Base vs. Exponent:**
> Be careful not to multiply the $a_1$ ($-3$) into the ratio ($-1/3$) before applying the exponent. The exponent $n-1$ only applies to the ratio $r$, not to the first term $a_1$.

### Finding the First Term ($a_1$) of a Geometric Sequence

In this problem, we are given the 6th term ($a_6 = 243$) and the common ratio ($r = -3$). To find the first term, we work backward using the explicit formula for a geometric sequence.

---
#### 1. Identify the Formula and Variables
The formula is:
$$a_n = a_1 \cdot r^{n-1}$$

Given information:
* $a_6 = 243$
* $r = -3$
* $n = 6$
#### 2. Substitute and Solve
Substitute the known values into the equation:
$$243 = a_1 \cdot (-3)^{6-1}$$

Simplify the exponent:
$$243 = a_1 \cdot (-3)^5$$

Calculate $(-3)^5$:
$$(-3) \cdot (-3) \cdot (-3) \cdot (-3) \cdot (-3) = -243$$

Now, solve for $a_1$:
$$243 = a_1 \cdot (-243)$$
$$a_1 = \frac{243}{-243}$$
$$a_1 = -1$$

---
#### Key Takeaways

> [!IMPORTANT]
> **Working Backward:**
> If you are missing the first term, simply plug in the values you have for any other term ($a_n$) and the ratio ($r$), then solve the resulting algebraic equation for $a_1$.

> [!TIP]
> **Exponent Rules:**
> Be very careful with the exponent. Since $n=6$, the exponent is $6-1 = 5$. Because 5 is an odd number, a negative base raised to that power will remain negative.

> [!CAUTION]
> **Sign Errors:**
> A common mistake is losing the negative sign when dividing $243 / -243$. Always remember that a positive divided by a negative results in a negative value.

### Finding the General Formula for a Geometric Sequence Given Two Terms

When you are not given the first term ($a_1$) or the common ratio ($r$), you can use two known terms to solve for them systematically.

---
#### 1. Set Up the System of Equations
Using the formula $a_n = a_1 \cdot r^{n-1}$, we write an equation for each known term:
* For $a_3 = 1/3$: 
  $$1/3 = a_1 \cdot r^{3-1} \implies 1/3 = a_1 \cdot r^2$$
* For $a_6 = 1/81$:
  $$1/81 = a_1 \cdot r^{6-1} \implies 1/81 = a_1 \cdot r^5$$
#### 2. Solve for the Common Ratio ($r$)
Divide the second equation by the first equation to eliminate $a_1$:
$$\frac{a_1 \cdot r^5}{a_1 \cdot r^2} = \frac{1/81}{1/3}$$

The $a_1$ terms cancel out, leaving:
$$r^3 = \frac{1}{81} \cdot \frac{3}{1}$$
$$r^3 = \frac{3}{81} = \frac{1}{27}$$

Take the cube root of both sides:
$$r = \sqrt[3]{1/27} = \frac{1}{3}$$
#### 3. Solve for the First Term ($a_1$)
Substitute $r = 1/3$ back into the first equation ($1/3 = a_1 \cdot r^2$):
$$1/3 = a_1 \cdot (1/3)^2$$
$$1/3 = a_1 \cdot (1/9)$$

Multiply both sides by 9 to isolate $a_1$:
$$a_1 = 9 \cdot (1/3) = 3$$
#### 4. Final Explicit Formula
Now that we have $a_1 = 3$ and $r = 1/3$, the formula is:
$$a_n = 3 \cdot \left(\frac{1}{3}\right)^{n-1}$$

---
#### Key Takeaways

> [!TIP]
> **The Division Trick:**
> Dividing the equation for the higher term by the equation for the lower term is the fastest way to eliminate $a_1$. This is the standard procedure whenever you are given two arbitrary terms in a geometric sequence.

> [!IMPORTANT]
> **Exponent Calculation:**
> When you divide $r^5 / r^2$, remember the exponent rule $x^a / x^b = x^{a-b}$. Here, $5 - 2 = 3$, which is why we ended up with $r^3$.

> [!CAUTION]
> **Check your terms:**
> Always write the higher-indexed term on top in the division to keep your ratio power positive ($r^3$ instead of $r^{-3}$). It makes the math significantly easier to visualize.

## 2026-June-03 - Geometric Series (Precalculus - College Algebra 72) :
https://www.youtube.com/watch?v=_yDqkrbd5mk&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=74
### Geometric Series

A **Geometric Series** is the sum of the terms of a geometric sequence. While the sequence represents the list (e.g., $2, 6, 18, 54$), the series is the result of adding those terms together ($2 + 6 + 18 + 54 = 80$).

---
#### 1. The Sum Formula (Finite)
To find the sum of the first $n$ terms of a geometric series ($S_n$), we use a formula that relies on the first term ($a_1$), the common ratio ($r$), and the number of terms ($n$).

**The Formula:**
$$S_n = a_1 \left( \frac{1 - r^n}{1 - r} \right)$$
---
#### 2. Evaluating a Geometric Series
To use the formula correctly, you need three components. If you are given the series in summation notation, you must identify them first:
1. **$a_1$:** The first term (usually found by plugging the lower limit of the sum into the general formula).
2. **$r$:** The common ratio (the value being raised to the power of the index).
3. **$n$:** The number of terms (Upper Limit - Lower Limit + 1).

---
#### 3. Infinite Geometric Series
A fascinating property of geometric series occurs when $n$ goes to infinity. If the absolute value of the ratio is less than 1 ($|r| < 1$), the terms shrink toward zero, allowing the series to **converge** to a finite sum.

**The Infinite Sum Formula:**
$$S = \frac{a_1}{1 - r}$$

**Constraint:** This formula **only** works if $|r| < 1$. If $|r| \ge 1$, the sum will grow toward infinity and the series is said to **diverge**.

---
#### Critical Tips & Common Pitfalls

> [!TIP]
> **Check the Ratio:**
> Before calculating an infinite sum, always verify $|r| < 1$. If you are given a ratio like $r = 2$ or $r = -3$ for an infinite series, the answer is simply that the series **diverges** (no sum exists).

> [!IMPORTANT]
> **Order of Operations:**
> When using the finite formula $S_n = a_1 \frac{1 - r^n}{1 - r}$, calculate the exponent ($r^n$) first, then subtract from $1$. Be extremely careful if $r$ is negative—use parentheses so the negative sign is handled correctly by the exponent.

> [!CAUTION]
> **Summation Indices:**
> When using summation notation, if the series starts at $k=0$ instead of $k=1$, your calculation for $a_1$ and $n$ will change. Always test the lower limit of the sum to identify the true first term, and always count your terms carefully.

### The Finite Geometric Series Formula

This formula is a "shortcut" that allows you to calculate the sum of a geometric series ($S_n$) without having to manually add up every single term.

---
#### 1. The Full Formula
$$S_n = \sum_{k=1}^{n} a_1 \cdot r^{k-1} = a_1 \left( \frac{1 - r^n}{1 - r} \right)$$

---
#### 2. Definition of Parts
* **$\sum_{k=1}^{n}$**: The summation notation indicating you are adding up terms from the 1st term ($k=1$) to the $n$-th term.
* **$a_1$**: The **first term** of the sequence. This is the starting value.
* **$r$**: The **common ratio**. This is the number you multiply by to get from one term to the next.
* **$n$**: The **number of terms** you are adding together.
* **$a_1 \cdot r^{k-1}$**: The general formula for the $k$-th term of a geometric sequence.

---
#### 3. How to Use It
To use this formula effectively, follow these three steps as Professor Leonard demonstrates:
1. **Identify $a_1$**: Plug $k=1$ into the general term formula.
2. **Identify $r$**: Determine the common ratio by dividing any term by the previous term ($a_2 / a_1$).
3. **Identify $n$**: Determine how many terms are being summed. 

---
#### Key Takeaways

> [!TIP]
> **The Power of the Shortcut:**
> If you needed to find the sum of the first 50 terms of a sequence, manually adding them would take forever. This formula reduces that entire process to a single calculation.

> [!IMPORTANT]
> **Formula Limitation:**
> This specific formula only works if your series starts at **$k=1$**. If the summation starts at a different number, you must adjust the bounds or calculate the starting term accordingly.

> [!CAUTION]
> **Division by Zero:**
> Notice that the formula has $(1-r)$ in the denominator. This means the formula is only valid if **$r \neq 1$**. If $r = 1$, the series is just adding the same number ($a_1$) over and over, and you would simply use $n \cdot a_1$ instead.

### Summing the Geometric Series: $\sum_{k=1}^{n} \frac{3^k}{9}$

To find the sum of this series, we follow Professor Leonard's method of identifying the first term ($a_1$), the common ratio ($r$), and applying the finite geometric series formula.

---
#### 1. Analyze the General Term
The series is given by $\sum_{k=1}^{n} \frac{3^k}{9}$. 

To identify $a_1$ and $r$ clearly, we can rewrite the term $\frac{3^k}{9}$ into a form that highlights the exponent structure.
* $a_1 = \frac{3^1}{9} = \frac{3}{9} = \frac{1}{3}$
* $a_2 = \frac{3^2}{9} = \frac{9}{9} = 1$
* $a_3 = \frac{3^3}{9} = \frac{27}{9} = 3$

By examining the sequence $\frac{1}{3}, 1, 3, \dots$, we can see that:
* **$a_1 = \frac{1}{3}$**
* **$r = 3$** (since $1 \div \frac{1}{3} = 3$ and $3 \div 1 = 3$)

---
#### 2. Apply the Sum Formula
We use the formula: $S_n = a_1 \left( \frac{1 - r^n}{1 - r} \right)$

Substitute our values:
$$S_n = \frac{1}{3} \left( \frac{1 - 3^n}{1 - 3} \right)$$

Simplify the denominator ($1 - 3 = -2$):
$$S_n = \frac{1}{3} \left( \frac{1 - 3^n}{-2} \right)$$

Distribute the constant factor:
$$S_n = \frac{1 - 3^n}{-6}$$

Finally, distribute the negative sign to clean up the denominator:
$$S_n = \frac{3^n - 1}{6}$$

---
#### 3. Alternative Notation
the series can also be written in the standard geometric form $a_1(r)^{k-1}$:
$$\sum_{k=1}^{n} \frac{1}{3}(3)^{k-1}$$

This explicitly shows $a_1 = \frac{1}{3}$ and $r = 3$, confirming that our identification in Step 1 was correct.


---
#### Key Takeaways

> [!TIP]
> **Check your First Term:**
> Always write out the first few terms of the summation ($k=1, k=2, k=3$). This prevents errors in identifying $a_1$ and $r$ and acts as a quick check for your formula.

> [!IMPORTANT]
> **The Common Ratio:**
> The common ratio is the base being raised to the power of the index. In $\frac{3^k}{9}$, the base is $3$. If the term were $\frac{3^{2k}}{9}$, the ratio would be $3^2 = 9$.

> [!CAUTION]
> **Formula Validity:**
> This formula works for all $r \neq 1$. Since our $r=3$, the formula is valid. If your ratio had been 1, the sum would simply be $n \cdot a_1$.

### Evaluating Infinite Geometric Series

To solve these infinite geometric series, we use the formula for the sum of an infinite geometric series:
$$S = \frac{a_1}{1 - r}$$
**Critical Condition:** This formula only works if the absolute value of the common ratio is less than one ($|r| < 1$). If $|r| \ge 1$, the series diverges.

---
#### 1. Evaluating $\sum_{k=1}^{\infty} 8 \left( \frac{1}{3} \right)^{k-1}$
* **Identify $a_1$:** When $k=1$, $8(\frac{1}{3})^0 = 8(1) = 8$.
* **Identify $r$:** $r = \frac{1}{3}$. Since $| \frac{1}{3} | < 1$, the series converges.
* **Calculate Sum:**
  $$S = \frac{8}{1 - 1/3} = \frac{8}{2/3} = 8 \cdot \frac{3}{2} = \mathbf{12}$$
#### 2. Evaluating $\sum_{k=1}^{\infty} \frac{1}{2} (3)^{k-1}$
* **Identify $a_1$:** $\frac{1}{2}(3)^0 = \frac{1}{2}$.
* **Identify $r$:** $r = 3$.
* **Determine Convergence:** Since $|3| \ge 1$, this series **diverges**. It does not have a finite sum.
#### 3. Evaluating $\sum_{k=1}^{\infty} 3 \left( -\frac{2}{3} \right)^{k-1}$
* **Identify $a_1$:** $3(-\frac{2}{3})^0 = 3(1) = 3$.
* **Identify $r$:** $r = -\frac{2}{3}$. Since $| -\frac{2}{3} | = \frac{2}{3} < 1$, the series converges.
* **Calculate Sum:**
  $$S = \frac{3}{1 - (-2/3)} = \frac{3}{1 + 2/3} = \frac{3}{5/3} = 3 \cdot \frac{3}{5} = \mathbf{\frac{9}{5}}$$
---
#### Key Takeaways

> [!IMPORTANT]
> **Check Convergence First:**
> Always look at your ratio ($r$) before doing any algebra. If $|r| \ge 1$, stop immediately—the series diverges. This is a common "trick" question to see if you understand the convergence condition.

> [!TIP]
> **Don't let the fraction confuse you:**
> When $r$ is a fraction like $-2/3$, the denominator $1 - r$ becomes $1 - (-2/3)$, which is $1 + 2/3$. Always watch those double negatives!

> [!CAUTION]
> **The $k=1$ Starting Point:**
> These formulas assume the index starts at $k=1$. If your series starts at a different number, you must calculate the first term ($a_1$) by plugging in that specific starting value for $k$.

### Evaluating Infinite Geometric Series

To evaluate these series, we use the sum formula for an infinite geometric series:
$$S = \frac{a_1}{1 - r}$$
**Important:** This formula only works if $|r| < 1$. If $|r| \ge 1$, the series diverges and has no finite sum.

---
#### 1. Evaluating $\sum_{k=1}^{\infty} \frac{1}{9} \left( -\frac{5}{4} \right)^{k-1}$
* **Identify $r$:** The common ratio is $r = -\frac{5}{4}$.
* **Check Convergence:** $|r| = |-\frac{5}{4}| = 1.25$. Since $1.25 \ge 1$, the series **diverges**.
#### 2. Evaluating $\sum_{k=1}^{\infty} 3 \left( \frac{2}{3} \right)^k$
* **Identify $a_1$:** Plug in $k=1$:
  $a_1 = 3(\frac{2}{3})^1 = 3 \cdot \frac{2}{3} = 2$.
* **Identify $r$:** The common ratio is $r = \frac{2}{3}$. Since $|\frac{2}{3}| < 1$, the series converges.
* **Calculate Sum:**
  $$S = \frac{a_1}{1 - r} = \frac{2}{1 - 2/3} = \frac{2}{1/3} = 2 \cdot 3 = \mathbf{6}$$
---
#### Key Takeaways

> [!IMPORTANT]
> **Always Check Convergence:** > Before applying the formula $S = \frac{a_1}{1 - r}$, you must verify that the absolute value of the ratio is less than 1. As seen in the first example, if the ratio is greater than 1 (or less than -1), the series will not sum to a finite number.

> [!TIP]
> **Starting Index:**
> Notice that for the second series, the index $k$ starts at $1$ and the term is $(2/3)^k$. If the exponent were $(k-1)$, $a_1$ would be 3. Because it is $k$, $a_1$ is $3 \cdot (2/3) = 2$. **Always plug in the starting $k$ value to find the true $a_1$.**

> [!CAUTION]
> **Ratio Identification:** > Make sure you are correctly identifying the base of the exponent as $r$. If there is a constant coefficient outside the parenthesis, it is *not* part of the ratio; it is part of the first term $a_1$.

## 2026-June-04 - Proof by Mathematical Induction (Precalculus - College Algebra 73) :
https://www.youtube.com/watch?v=x5cWX-EyLEI&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=74
### Proof by Mathematical Induction

Mathematical Induction is a powerful technique used to prove that a statement or formula is true for all positive integers ($n = 1, 2, 3, \dots$). Professor Leonard often uses the analogy of a line of dominoes: if you can knock over the first one, and you can guarantee that any falling domino will knock over the next one, then all the dominoes will eventually fall.

---
#### 1. The Two-Step Process
To prove a statement $P(n)$ is true for all $n \ge 1$, we must satisfy two conditions:

* **Step 1: The Base Case**
    Show that the statement is true for the starting value, usually $n = 1$. This is the "first domino."
* **Step 2: The Inductive Step**
    Assume the statement is true for some arbitrary positive integer $k$ (this is the **Inductive Hypothesis**). Then, use that assumption to prove the statement must also be true for the next integer, $k + 1$.

---
#### 2. The Mechanics of the Inductive Step
This is where most of the work happens. You are trying to show:
* **Given:** $P(k)$ is true.
* **Goal:** Show that $P(k+1)$ is also true.
**General Workflow:**
1. Write down $P(k)$ exactly as the formula is stated, replacing $n$ with $k$.
2. Write down what $P(k+1)$ *should* look like (by replacing $n$ with $k+1$).
3. Start with the left side of $P(k+1)$.
4. Manipulate it so that you can substitute your Inductive Hypothesis ($P(k)$) into the expression.
5. Simplify until it matches the right side of $P(k+1)$.

---
#### 3. Why Induction Works
Induction effectively "chains" the truth. If $P(1)$ is true, and the Inductive Step proves that $P(1) \implies P(2)$, then $P(2)$ is true. If $P(2) \implies P(3)$, then $P(3)$ is true, and so on, reaching infinity.

---
#### Critical Tips & Common Pitfalls

> [!TIP]
> **The Target:**
> Always write down your "Goal" (the $P(k+1)$ statement) on the side of your paper. It keeps you focused on where the algebra needs to end up.

> [!IMPORTANT]
> **Don't Forget the Hypothesis:**
> You **must** explicitly state, "Assume $P(k)$ is true." You are not proving $P(k)$ is true; you are using it as a tool to bridge the gap to $P(k+1)$.

> [!CAUTION]
> **Algebraic Errors:**
> Induction proofs are rarely about "new" calculus concepts; they are about algebra. Be extremely careful when adding the $(k+1)$-th term to your sum, and ensure your factoring/distribution is correct.

### Proof by Mathematical Induction: $1 + 3 + 5 + \dots + (2n - 1) = n^2$

To prove this formula is true for all positive integers $n$, we follow the two-step process of mathematical induction.

---
#### 1. The Base Case ($n=1$)
We must show the statement holds for the first term.
* Left side (sum of the first term): $1$
* Right side (formula $n^2$): $1^2 = 1$
Since $1 = 1$, the base case is **true**.

---
#### 2. The Inductive Step
**Inductive Hypothesis:** Assume the statement is true for some positive integer $k$:
$$1 + 3 + 5 + \dots + (2k - 1) = k^2$$
**Goal:** Show that the statement must be true for $k+1$. That is, we want to prove:
$$1 + 3 + 5 + \dots + (2k - 1) + (2(k+1) - 1) = (k+1)^2$$
**Proof:**
Start with the sum of the first $k+1$ terms:
$$[1 + 3 + 5 + \dots + (2k - 1)] + (2(k+1) - 1)$$
Substitute our Inductive Hypothesis ($k^2$) for the bracketed part:
$$k^2 + (2(k+1) - 1)$$
Simplify the expression:
$$k^2 + 2k + 2 - 1$$
$$k^2 + 2k + 1$$
Factor the resulting quadratic:
$$(k+1)^2$$
This matches our goal! Since we have shown the base case is true and that if it holds for $k$ it must hold for $k+1$, the statement is **proven true** by induction for all $n \ge 1$.

---
#### Key Takeaways

> [!TIP]
> **The Goal is Crucial:**
> Always write down your goal ($P(k+1)$) on the side of your page before you start the inductive step. It tells you exactly where your algebra needs to lead.

> [!IMPORTANT]
> **The "Next" Term:**
> When moving from $k$ to $k+1$, remember that you are adding one *additional* term to the existing sum. If your formula for the $k$-th term is $(2k-1)$, your $(k+1)$-th term is found by substituting $(k+1)$ into that expression: $(2(k+1)-1)$.

> [!CAUTION]
> **Don't skip the Substitution:**
> You must clearly show where you replace the sum of the first $k$ terms with your hypothesis ($k^2$). This substitution is the heart of the inductive proof.

### Proof by Mathematical Induction: $1 + 5 + 9 + \dots + (4n - 3) = 2n^2 - n$

To prove this formula is true for all positive integers $n$, we follow the two-step process of mathematical induction.

---
#### 1. The Base Case ($n=1$)
We must show the statement holds for the first term.
* Left side (sum of the first term): $1$
* Right side (formula $2n^2 - n$): $2(1)^2 - 1 = 2 - 1 = 1$
Since $1 = 1$, the base case is **true**.

---
#### 2. The Inductive Step
**Inductive Hypothesis:** Assume the statement is true for some positive integer $k$:
$$1 + 5 + 9 + \dots + (4k - 3) = 2k^2 - k$$

**Goal:** Show that the statement must be true for $k+1$. That is, we want to prove:
$$1 + 5 + 9 + \dots + (4k - 3) + (4(k+1) - 3) = 2(k+1)^2 - (k+1)$$

**Proof:**
Start with the sum of the first $k+1$ terms:
$$[1 + 5 + 9 + \dots + (4k - 3)] + (4(k+1) - 3)$$

Substitute our Inductive Hypothesis ($2k^2 - k$) for the bracketed part:
$$(2k^2 - k) + (4(k+1) - 3)$$

Simplify the expression:
$$2k^2 - k + 4k + 4 - 3$$
$$2k^2 + 3k + 1$$

Factor the resulting quadratic:
$$(2k + 1)(k + 1)$$
$$2k^2 + 2k + k + 1 = 2k^2 + 3k + 1$$

Alternatively, expand the target expression $2(k+1)^2 - (k+1)$:
$$2(k^2 + 2k + 1) - k - 1$$
$$2k^2 + 4k + 2 - k - 1$$
$$2k^2 + 3k + 1$$

Since both sides match, the statement is **proven true** by induction for all $n \ge 1$. 

---
#### Key Takeaways

> [!TIP]
> **The Goal is Crucial:**
> Always write down your goal ($P(k+1)$) on the side of your page before you start the inductive step. It tells you exactly where your algebra needs to lead.

> [!IMPORTANT]
> **The "Next" Term:**
> When moving from $k$ to $k+1$, remember that you are adding one *additional* term to the existing sum. If your formula for the $k$-th term is $(4k-3)$, your $(k+1)$-th term is found by substituting $(k+1)$ into that expression: $(4(k+1)-3)$.

> [!CAUTION]
> **Don't skip the Substitution:**
> You must clearly show where you replace the sum of the first $k$ terms with your hypothesis ($2k^2 - k$). This substitution is the heart of the inductive proof.

# 2026June05-Trigonometry :
## 2026-June-05 - Introduction to Angles (Precalculus - Trigonometry 1) :
https://www.youtube.com/watch?v=c41QejoWnb4&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=76
### Introduction to Angles

Trigonometry begins with the formal definition of an angle. In this context, an angle is formed by the rotation of a ray about its endpoint.

---
#### 1. Fundamental Components
* **Vertex:** The fixed endpoint.
* **Initial Side:** The starting position of the ray.
* **Terminal Side:** The final position of the ray after rotation.
* **Positive Rotation:** Counter-clockwise rotation.
* **Negative Rotation:** Clockwise rotation.

---
#### 2. Position and Measurement
* **Standard Position:** An angle is in standard position when its vertex is at the origin $(0,0)$ of the Cartesian plane and its initial side lies along the positive x-axis.
* **Quadrantal Angles:** Angles whose terminal side falls on one of the axes (e.g., $0^\circ, 90^\circ, 180^\circ, 270^\circ$).
* **Coterminal Angles:** Angles that share the same initial and terminal sides but differ by multiples of a full rotation ($360^\circ$ or $2\pi$ radians).
  * *Example:* $30^\circ$ and $390^\circ$ ($30^\circ + 360^\circ$) are coterminal.

---
#### 3. Units of Measure
* **Degrees:** Based on a full circle being $360^\circ$.
* **Radians:** Based on the radius of a circle. One radian is the measure of a central angle that intercepts an arc equal in length to the radius. A full circle is $2\pi$ radians.
* **Conversion:** * Degrees to Radians: Multiply by $\frac{\pi}{180^\circ}$
  * Radians to Degrees: Multiply by $\frac{180^\circ}{\pi}$

---
#### Key Takeaways

> [!TIP]
> **Coterminal Calculation:**
> To find a coterminal angle, simply add or subtract $360^\circ$ (or $2\pi$) as many times as needed. If you want the "smallest positive coterminal angle," keep subtracting $360^\circ$ until you are within the range $[0, 360^\circ)$.

> [!IMPORTANT]
> **Direction Matters:**
> Always pay attention to the direction of the arc. A counter-clockwise arc is positive; a clockwise arc is negative. This distinction is vital when determining which quadrant an angle resides in.

> [!CAUTION]
> **Calculator Settings:**
> One of the most common mistakes in trigonometry is having your calculator in the wrong mode. Always ensure your calculator is set to **DEG** when working with degrees and **RAD** when working with radians.

## 2026-June-06 - Converting Degrees, Minutes, and Seconds (Precalculus - Trigonometry 2) :
https://www.youtube.com/watch?v=U40Afn37QC4&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=77
### Converting Degrees, Minutes, and Seconds (DMS)

While decimal degrees are standard in many scientific contexts, navigation and surveying often use the Degrees, Minutes, and Seconds (DMS) system. This system breaks down a single degree into smaller, more precise units.

---
#### 1. The DMS Units
* **Degrees ($^\circ$):** The primary unit.
* **Minutes ($'$):** One degree is divided into 60 minutes. ($1^\circ = 60'$)
* **Seconds ($''$):** One minute is divided into 60 seconds. ($1' = 60''$)
* **Conversion factor:** Therefore, one degree contains $60 \times 60 = 3,600$ seconds. ($1^\circ = 3600''$)

---
#### 2. Converting DMS to Decimal Degrees
To convert an angle like $D^\circ M' S''$ into a single decimal value:
$$Decimal = D + \left( \frac{M}{60} \right) + \left( \frac{S}{3600} \right)$$

* **Steps:**
    1. Keep the degrees ($D$) as the whole number.
    2. Divide the minutes ($M$) by 60.
    3. Divide the seconds ($S$) by 3,600.
    4. Sum all three components.

---
#### 3. Converting Decimal Degrees to DMS
To convert a decimal degree (e.g., $45.123^\circ$) back to DMS:
* **Steps:**
    1. The whole number part is your **Degrees** ($45^\circ$).
    2. Take the decimal remainder ($0.123$) and multiply by 60: $0.123 \times 60 = 7.38$. The whole number is your **Minutes** ($7'$).
    3. Take the remaining decimal from that result ($0.38$) and multiply by 60 again: $0.38 \times 60 = 22.8$. Round to the nearest whole number for your **Seconds** ($23''$).
    4. Result: $45^\circ 7' 23''$.

---
#### Key Takeaways

> [!TIP]
> **Check your Rounding:**
> Seconds are usually expressed as a whole number in standard DMS notation. If your calculation results in $22.8''$, rounding to $23''$ is common unless extreme precision is required.

> [!IMPORTANT]
> **The Base 60 Logic:**
> Remember that this is a sexagesimal (base-60) system, similar to how we measure time. Think of it as: $1 \text{ hour} = 60 \text{ minutes}$, and $1 \text{ minute} = 60 \text{ seconds}$. This conceptual link makes the math intuitive.

> [!CAUTION]
> **Don't lose the Degrees:**
> A common error is discarding the degree part ($D$) during the conversion. Always ensure your final decimal degree is larger than your original degree component.

### Converting DMS to Decimal Degrees

To convert Degrees, Minutes, and Seconds (DMS) into a decimal degree value, you break each unit down into a fraction of a degree. As shown in the provided image, we have the angle $61^\circ 42' 21''$.

---
#### 1. The Conversion Formula
To turn DMS back into degrees, apply the following logic:
* **Degrees:** Keep as the whole number.
* **Minutes:** Multiply by $\frac{1}{60}$ (since there are 60 minutes in a degree).
* **Seconds:** Multiply by $\frac{1}{3600}$ (since there are 60 seconds in a minute, and 60 minutes in a degree: $60 \times 60 = 3600$).

The formula is:
$$Decimal Degrees = Degrees + \left( Minutes \cdot \frac{1}{60} \right) + \left( Seconds \cdot \frac{1}{3600} \right)$$

---
#### 2. Step-by-Step Calculation for $61^\circ 42' 21''$

**Step 1: Degrees**
$$61^\circ$$
**Step 2: Minutes to Degrees**
$$42' \cdot \frac{1}{60} = \frac{42}{60} = 0.7^\circ$$
**Step 3: Seconds to Degrees**
$$21'' \cdot \frac{1}{3600} = \frac{21}{3600} \approx 0.0058333^\circ$$
**Step 4: Summation**
$$61^\circ + 0.7^\circ + 0.0058333^\circ = \mathbf{61.7058333^\circ}$$

---
#### Key Takeaways

> [!TIP]
> **Why 3600?**
> A common point of confusion is why we divide seconds by 3600. Remember that one minute is $1/60$ of a degree, and one second is $1/60$ of a *minute*. Therefore, to get from seconds directly to degrees, you must divide by $60 \times 60$, which equals $3600$.

> [!IMPORTANT]
> **Check your Precision:**
> When converting seconds, the decimal can sometimes go on for a long time (as seen with $21/3600$). Always carry at least 4 to 6 decimal places during your calculation to ensure accuracy in your final result.

> [!CAUTION]
> **Do not add all components together before dividing:**
> A frequent error is trying to add the degrees, minutes, and seconds together before performing the division by 60 and 3600. Always perform the division (or multiplication by the fraction) *first*, then perform the addition at the very end.

### Converting DMS to Decimal Degrees

To convert Degrees, Minutes, and Seconds (DMS) into a decimal degree value, we break each sub-unit down into a fraction of a degree. Based on the provided image, we have the angle $101^\circ 3' 51''$.

---
#### 1. The Conversion Formula
To convert DMS back into degrees using fractional multiplication:
* **Degrees:** Keep as the whole number.
* **Minutes:** Multiply by $\frac{1}{60}$ (since $1^\circ = 60'$).
* **Seconds:** Multiply by $\frac{1}{3600}$ (since $1' = 60''$, making $60 \times 60 = 3600$ seconds in a degree).

$$\text{Decimal Degrees} = \text{Degrees} + \left( \text{Minutes} \cdot \frac{1}{60} \right) + \left( \text{Seconds} \cdot \frac{1}{3600} \right)$$

---
#### 2. Step-by-Step Calculation for $101^\circ 3' 51''$

**Step 1: Extract the components**
* $\text{Degrees} = 101$
* $\text{Minutes} = 3$
* $\text{Seconds} = 51$
**Step 2: Convert Minutes to Degrees**
$$3' \cdot \frac{1}{60} = \frac{3}{60} = 0.05^\circ$$
**Step 3: Cnvert Seconds to Degrees**
$$51'' \cdot \frac{1}{3600} = \frac{51}{3600} = 0.0141667^\circ$$
**Step 4: Combine the parts**
$$101^\circ + 0.05^\circ + 0.0141667^\circ = \mathbf{101.0641667^\circ}$$
---
#### Key Takeaways

> [!TIP]
> **Watch the Placeholders:**
> Notice how $3$ minutes turns into $0.05^\circ$. It is critical to keep track of the leading zeros in your decimals so that your values don't accidentally shift place values during addition.

> [!IMPORTANT]
> **Why we multiply by $\frac{1}{3600}$:**
> Multiplying by $\frac{1}{3600}$ is mathematically identical to dividing by $60$ twice (once to turn seconds to minutes, and a second time to turn those minutes to degrees). 

> [!CAUTION]
> **Don't drop the whole degrees:**
> Ensure that the final decimal portion ($0.0641667^\circ$) is tacked onto your original starting degree value ($101^\circ$), rather than substituting it.

### Converting Decimal Degrees to DMS

To convert decimal degrees into Degrees, Minutes, and Seconds (DMS) notation, we systematically isolate each unit. Given the angle $18.255^\circ$, follow these steps:

---
#### 1. Step-by-Step Calculation for $18.255^\circ$

**Step 1: Extract the Degrees**
The whole number portion of the decimal is your degree value.
* **Degrees:** $18^\circ$
**Step 2: Calculate the Minutes**
Take the remaining decimal portion ($0.255$) and multiply by $60$ (since $1^\circ = 60'$).
$$0.255 \cdot 60 = 15.3'$$
The whole number becomes your minutes:
* **Minutes:** $15'$
**Step 3: Calculate the Seconds**
Take the decimal remainder from the minutes calculation ($0.3$) and multiply by $60$ again (since $1' = 60''$).
$$0.3 \cdot 60 = 18''$$
The result is your seconds:
* **Seconds:** $18''$

**Final DMS Value:** $\mathbf{18^\circ 15' 18''}$

---
#### Key Takeaways

> [!TIP]
> **Working Backwards:**
> To verify your work, you can turn the DMS notation back into decimal degrees by multiplying the sub-units by their fractional equivalents: $18^\circ + (15 \cdot \frac{1}{60}) + (18 \cdot \frac{1}{3600}) = 18 + 0.25 + 0.005 = 18.255^\circ$.

> [!IMPORTANT]
> **The Base 60 Logic:**
> Degrees are structured in a sexagesimal (base-60) system, identical to how we keep track of hours, minutes, and seconds in time. 

> [!CAUTION]
> **Handling Remainders:**
> Always make sure to strip away the whole number *before* multiplying by 60 for the next step. For example, in Step 3, you must use $0.3$, not $15.3$. Multiplying the whole number again will ruin your calculation.

### Converting Decimal Degrees to DMS

To convert decimal degrees into Degrees, Minutes, and Seconds (DMS) notation, we systematically isolate each unit. Given the angle $29.411^\circ$, follow these steps:

---
#### 1. Step-by-Step Calculation for $29.411^\circ$
**Step 1: Extract the Degrees**
The whole number portion of the decimal is your degree value.
* **Degrees:** $29^\circ$
**Step 2: Calculate the Minutes**
Take the remaining decimal portion ($0.411$) and multiply by $60$ (since $1^\circ = 60'$).
$$0.411 \cdot 60 = 24.66'$$
The whole number becomes your minutes:
* **Minutes:** $24'$
**Step 3: Calculate the Seconds**
Take the decimal remainder from the minutes calculation ($0.66$) and multiply by $60$ again (since $1' = 60''$).
$$0.66 \cdot 60 = 39.6''$$
Rounding to the nearest whole second gives:
* **Seconds:** $40''$

**Final DMS Value:** $\mathbf{29^\circ 24' 40''}$

---
#### Key Takeaways

> [!TIP]
> **Working Backwards:**
> To verify your work, you can turn the DMS notation back into decimal degrees by multiplying the sub-units by their fractional equivalents: $29^\circ + (24 \cdot \frac{1}{60}) + (40 \cdot \frac{1}{3600}) = 29 + 0.4 + 0.0111... \approx 29.411^\circ$.

> [!IMPORTANT]
> **The Base 60 Logic:**
> Degrees are structured in a sexagesimal (base-60) system, identical to how we keep track of hours, minutes, and seconds in time. 

> [!CAUTION]
> **Isolating Remainders:**
> Always make sure to drop the whole number *before* multiplying by 60 for the next step. For example, in Step 3, you must use $0.66$, not $24.66$. Multiplying the whole number again will throw off your calculation completely.

## 2026-June-07 - Introduction to Radians (Precalculus - Trigonometry 3) :
https://www.youtube.com/watch?v=EWd_FtOfyPc&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=79
### Introduction to Radians

While degrees divide a circle into 360 arbitrary parts, radians are a more "natural" way to measure angles based on the geometry of the circle itself. 

---
#### 1. Defining the Radian
A radian is the measure of a central angle that intercepts an arc with a length equal to the circle's radius ($r$).

* **Visualizing the definition:** If you take a radius of a circle and "bend" it along the circumference, the angle formed by that arc length is exactly $1$ radian.
* **Full Rotation:** Since the circumference of a circle is $C = 2\pi r$, a full rotation ($360^\circ$) contains exactly $2\pi$ radians.

---
#### 2. Relationship between Degrees and Radians
Because both units measure rotation, we use the fundamental equivalence:
$$180^\circ = \pi \text{ radians}$$
This relationship allows us to create conversion factors:
* **Degrees to Radians:** Multiply by $\frac{\pi}{180^\circ}$
* **Radians to Degrees:** Multiply by $\frac{180^\circ}{\pi}$

---
#### 3. Common Radian Measures
Memorizing these key angles is essential for trigonometry:
* $0^\circ = 0$ radians
* $90^\circ = \frac{\pi}{2}$ radians
* $180^\circ = \pi$ radians
* $270^\circ = \frac{3\pi}{2}$ radians
* $360^\circ = 2\pi$ radians

---
#### Key Takeaways

> [!TIP]
> **Unit Cancellation:**
> When converting, think of the units like algebraic variables. If you have degrees and want radians, multiply by $\frac{\text{radians}}{\text{degrees}}$ so the "degree" units cancel out.

> [!IMPORTANT]
> **Why Radians?**
> You might wonder why we switch from degrees. Radians simplify many formulas in higher mathematics (like Calculus). For example, the formula for arc length ($s = r\theta$) is only valid when $\theta$ is measured in radians.

> [!CAUTION]
> **Calculator Mode:**
> Always verify your calculator mode before performing trigonometric operations. If the problem involves $\pi$ or fractions of $\pi$, ensure your calculator is set to **RAD** mode. Using **DEG** mode for radian inputs will result in incorrect answers.

## 2026-June-08 - Converting Radians and Degrees (Precalculus - Trigonometry 4) :
https://www.youtube.com/watch?v=sCwcbZSZL5o&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=80
### Converting Radians and Degrees

Converting between degrees and radians is a core skill in trigonometry, relying on the relationship where a full circle is $360^\circ$ or $2\pi$ radians.

---
#### 1. The Conversion Factors
The relationship $180^\circ = \pi \text{ radians}$ provides the two primary conversion factors:
* **Degrees to Radians:** Multiply by $\frac{\pi}{180^\circ}$
* **Radians to Degrees:** Multiply by $\frac{180^\circ}{\pi}$
Since 1 degree is equal to $\frac{\pi}{180\degree}$ simply seperate the 'degree' by multiplying/factoring it out and then replacing it with  $\frac{\pi}{180\degree}$ to get your radians
---
#### 2. Examples
**Degrees to Radians:**
To convert $60^\circ$:
$$60^\circ \cdot \frac{\pi}{180^\circ} = \frac{60\pi}{180} = \frac{\pi}{3} \text{ radians}$$
**Radians to Degrees:**
To convert $\frac{3\pi}{4}$ radians:
$$\frac{3\pi}{4} \cdot \frac{180^\circ}{\pi} = 3 \cdot \frac{180^\circ}{4} = 3 \cdot 45^\circ = 135^\circ$$

---
#### 3. Key Takeaways

> [!TIP]
> **Unit Cancellation:**
> Always set up your conversion so the unit you are trying to *eliminate* is in the denominator. If you start with degrees, put $180^\circ$ on the bottom to cancel out the degree symbol.

> [!IMPORTANT]
> **Simplifying Fractions:**
> When converting, you will often end up with large fractions (e.g., $\frac{60\pi}{180}$). Always reduce these fractions to their simplest form to maintain clarity in your work.

> [!CAUTION]
> **The $\pi$ Constant:**
> Remember that $\pi$ is just a number (approximately $3.14159$). If you are converting from radians and the $\pi$ symbol is missing (e.g., $2$ radians), simply multiply by $\frac{180^\circ}{\pi}$ as usual and calculate the decimal value.

### Introduction to Radians: The Geometric Derivation

Professor Leonard explains that a radian is defined by the relationship between the radius ($r$) and the arc length ($s$). To understand why a full rotation is $2\pi$ radians, we look at the geometric derivation:
#### The Derivation Steps
1. **Define the Arc Length ($s$):** The distance traveled along the circumference of a circle is defined as $s = r \cdot \theta$, where $\theta$ is the angle in radians.
2. **Relate to Circumference ($C$):** For a full rotation of a circle, the arc length ($s$) is equal to the total circumference ($C$). We know from geometry that $C = 2\pi r$.
3. **Set the Equations Equal:** Since $C = s$, we set the two definitions for the full rotation equal to each other:
   $$2\pi r = r \cdot \theta$$
4. **Solve for $\theta$:** Dividing both sides by $r$:
   $$\theta = 2\pi$$
   This proves that a full rotation ($360^\circ$) is exactly $2\pi$ radians.

---
#### Key Concepts
* **The Radian Definition:** $1 \text{ radian} = \frac{s}{r}$. When the arc length $s$ is exactly equal to the radius $r$, the angle $\theta$ is $1$ radian.
* **The "Natural" Unit:** Because the radius cancels out in the ratio $\frac{s}{r}$, radians are unitless. They describe a ratio of lengths rather than an arbitrary division of a circle (like $360^\circ$).

---
#### Key Takeaways

> [!TIP]
> **Why it matters:**
> This derivation is the foundation for all circular motion and trigonometric functions in Calculus. Understanding that $2\pi$ radians is just a consequence of the circumference formula ($2\pi r$) makes the transition away from degrees much more intuitive.

> [!IMPORTANT]
> **Radian vs Degree:**
> * Degrees are human-made (based on the approximate number of days in a year).
> * Radians are inherent to the geometry of circles.

> [!CAUTION]
> **Check the units:**
> Always remember that the formula $s = r\theta$ **only** works if $\theta$ is in radians. If you use degrees, the math will not align with the geometry of the circle.

### Summary: The Definition of Radians ($\theta = \frac{s}{r}$)

The formula $\theta = \frac{s}{r}$ is the mathematical definition of a radian. It relates an angle's measure to the geometry of a circle by comparing the arc length to the radius.

---
#### 1. Variable Breakdown
* **$\theta$ (Theta):** The measure of the central angle in **radians**.
* **$s$ (Arc Length):** The distance traveled along the edge (circumference) of the circle.
* **$r$ (Radius):** The distance from the center of the circle to the edge.
---
#### 2. Why this Formula is Significant
* **Unitless Measurement:** Because $s$ and $r$ are both lengths (e.g., inches, centimeters), dividing them cancels the units. This makes $\theta$ a "pure" ratio, which is why radians are preferred in higher mathematics and physics over degrees.
* **The Radian Identity:** When the arc length $s$ is exactly equal to the radius $r$, the formula becomes $\theta = \frac{r}{r} = 1$. This is the literal definition of **1 radian**.
* **Direct Scaling:** The formula shows that for a fixed radius, the angle $\theta$ is directly proportional to the arc length $s$. If you double the arc length, you double the angle.

---
#### 3. Key Takeaways

> [!TIP]
> **Radian Requirement:**
> The most common error in trigonometry and physics is using this formula while the angle is in degrees. This formula **only** produces a valid result when $\theta$ is measured in radians.

> [!IMPORTANT]
> **Rearranging for Arc Length:**
> By multiplying both sides by $r$, you get the widely used Arc Length formula: $s = r\theta$. This is essential for calculating distances along circular paths (like the distance a tire travels or the path of a satellite).

> [!CAUTION]
> **Constant Radius:**
> This formula only applies to circles or circular arcs where the radius $r$ is constant. It cannot be applied directly to ellipses or irregular curves without calculus-based adjustments.

### Introduction to Radians: The Geometric Derivation (Timestamped)

Professor Leonard derives the radian by showing that it is a ratio derived from the circumference of a circle. 

---
#### 1. The Derivation Logic (Reference: [05:00 - 15:30])
Professor Leonard builds the definition of a radian by comparing the arc length to the radius:

* **[05:00] The Arc Length Formula:** He establishes $s = r\theta$, stating that for this to be true, $\theta$ **must** be in radians.
* **[08:00] Defining a Full Rotation:** He draws a full circle and notes that a full rotation covers the entire circumference. 
* **[10:00] The Circumference Link:** He sets the general arc length formula equal to the specific circumference formula:
$$\text{Arc Length} = \text{Circumference}$$
  $$r\theta = 2\pi r$$
* **[12:00] Solving for $\theta$:** He divides both sides by $r$:
  $$\frac{r\theta}{r} = \frac{2\pi r}{r}$$
  $$\theta = 2\pi$$
* **[14:00] The Conclusion:** He concludes that one full rotation ($360^\circ$) is exactly $2\pi$ radians, which is how we arrive at the conversion factor.

---
#### 2. Why Radians are Preferred
* **Dimensionless Ratios:** Leonard emphasizes that because $\theta = \frac{s}{r}$, the units of length cancel out. This makes the radian a "pure number" in math, which is why it simplifies derivatives and integrals in Calculus.
* **Comparison to Degrees:** He notes that degrees ($360^\circ$) are historical/arbitrary (based on a year), whereas radians are based on the actual physical properties of circles.

---
#### 3. Key Takeaways

> [!TIP]
> **Unit Cancellation Check:**
> When using $s = r\theta$, if you have a radius in centimeters and an angle in radians, the result is in centimeters. If you accidentally use degrees, you are essentially multiplying a length by a "unitless degree symbol," which results in mathematically nonsensical units.

> [!IMPORTANT]
> **The Constant Requirement:**
> Leonard highlights that $s = r\theta$ is only valid when $\theta$ is in radians. If a problem provides degrees, you **must** convert to radians first. There is no workaround.

> [!CAUTION]
> **Calculator Mode:**
> He explicitly demonstrates that calculating $\sin(90)$ in degrees gives $1$, but in radians it gives $\approx 0.89$. Always check your calculator's RAD/DEG setting before starting a problem.

### Converting Degrees to Radians

Following Professor Leonard's methodology, to convert degrees to radians, we multiply by the ratio $\frac{\pi}{180^\circ}$. This works because $180^\circ = \pi$ radians; effectively, we are multiplying by $1$.

---
#### 1. Conversion Method
$$\text{Radians} = \text{Degrees} \cdot \left( \frac{\pi}{180^\circ} \right)$$

---
#### 2. Step-by-Step Calculations

**A. $60^\circ$**
$$60^\circ \cdot \frac{\pi}{180^\circ} = \frac{60\pi}{180} = \mathbf{\frac{\pi}{3} \text{ radians}}$$

**B. $150^\circ$**
$$150^\circ \cdot \frac{\pi}{180^\circ} = \frac{150\pi}{180} = \mathbf{\frac{5\pi}{6} \text{ radians}}$$

**C. $-45^\circ$**
$$-45^\circ \cdot \frac{\pi}{180^\circ} = -\frac{45\pi}{180} = \mathbf{-\frac{\pi}{4} \text{ radians}}$$

**D. $107^\circ$**
$$107^\circ \cdot \frac{\pi}{180^\circ} = \mathbf{\frac{107\pi}{180} \text{ radians}}$$
*(Note: $107$ is a prime number, so the fraction cannot be simplified further.)*

---
#### Key Takeaways

> [!TIP]
> **Simplify, Simplify, Simplify:**
> Professor Leonard emphasizes reducing your final fraction. Always look for the greatest common divisor between the numerator and denominator (e.g., $150/180$ both divide by $30$).

> [!IMPORTANT]
> **Keep $\pi$ in the Result:**
> In trigonometry, we almost always express radians in terms of $\pi$ rather than converting to a decimal. This maintains exact precision.

> [!CAUTION]
> **Signs Matter:**
> If your degree is negative, your radian result must also be negative. The rotation direction is preserved during the conversion.

### Converting Radians to Degrees

Following Professor Leonard's methodology, to convert from radians to degrees, we multiply by the ratio $\frac{180^\circ}{\pi}$. Since $\pi \text{ radians} = 180^\circ$, this conversion factor is essentially equal to $1$, allowing us to change units without changing the angle's measure.

---
#### 1. Conversion Method
$$\text{Degrees} = \text{Radians} \cdot \left( \frac{180^\circ}{\pi} \right)$$

---
#### 2. Step-by-Step Calculations

**A. $\frac{\pi}{6}$ radians**
$$\frac{\pi}{6} \cdot \frac{180^\circ}{\pi} = \frac{180^\circ}{6} = \mathbf{30^\circ}$$

**B. $\frac{3\pi}{2}$ radians**
$$\frac{3\pi}{2} \cdot \frac{180^\circ}{\pi} = 3 \cdot \frac{180^\circ}{2} = 3 \cdot 90^\circ = \mathbf{270^\circ}$$

**C. $-\frac{3\pi}{4}$ radians**
$$-\frac{3\pi}{4} \cdot \frac{180^\circ}{\pi} = -3 \cdot \frac{180^\circ}{4} = -3 \cdot 45^\circ = \mathbf{-135^\circ}$$

---
#### Key Takeaways

> [!TIP]
> **The $\pi$ Cancellation:**
> A major indicator that your setup is correct is that the $\pi$ in the numerator and the $\pi$ in the denominator will cancel each other out. If $\pi$ remains in your final answer, re-check your conversion factor.

> [!IMPORTANT]
> **Order of Operations:**
> While you can multiply the entire numerator first (e.g., $3 \cdot 180 = 540$), Professor Leonard often prefers to simplify the fraction first (e.g., $\frac{180}{2} = 90$) to keep the numbers smaller and easier to manage mentally.

> [!CAUTION]
> **Preserve the Sign:**
> Just as with degree-to-radian conversion, the negative sign must be carried through the entire process. A negative radian measure will always result in a negative degree measure.

### Converting Radians to Degrees: Methodical Approach

To convert radians to degrees, we apply the conversion factor $\left( \frac{180^\circ}{\pi} \right)$. This method effectively uses the identity that $180^\circ = \pi \text{ radians}$ to cancel out the $\pi$ and leave you with degrees.

---
#### 1. Conversion Formula
$$\text{Degrees} = \text{Radians} \cdot \left( \frac{180^\circ}{\pi} \right)$$

---
#### 2. Step-by-Step Calculations

**A. $\frac{7\pi}{3}$ radians**
$$\frac{7\pi}{3} \cdot \left( \frac{180^\circ}{\pi} \right)$$
* The $\pi$ values cancel out.
* Divide $180^\circ$ by $3$ to get $60^\circ$.
* $7 \cdot 60^\circ = \mathbf{420^\circ}$
**B. $4$ radians**
$$4 \cdot \left( \frac{180^\circ}{\pi} \right)$$
* Since there is no $\pi$ in the input to cancel, you must multiply the values and divide by $\pi$.
* $\frac{720^\circ}{\pi} \approx \mathbf{229.18^\circ}$

---
#### Key Takeaways

> [!TIP]
> **Recognizing the "Radiant" Form:**
> Professor Leonard often notes that when $\pi$ is present in the radian measure, the conversion is straightforward because the $\pi$ will cancel out. When $\pi$ is *not* present (like in the case of $4 \text{ radians}$), you are converting to a value that involves the transcendental number $\pi$, which will result in a decimal approximation.

> [!IMPORTANT]
> **Algebraic Simplification:**
> Always look to simplify the fractions before performing the final multiplication. Reducing the fraction $\frac{180}{3}$ to $60$ first makes the multiplication step much easier and less prone to errors than multiplying $7 \cdot 180$ first.

> [!CAUTION]
> **Calculator Precision:**
> When converting "pure" radians like $4$, you will need to use the $\pi$ button on your calculator to get an accurate decimal. Using a truncated value like $3.14$ will introduce rounding errors into your degree measure.

## 2026-June-09 - Area of a Sector, Angular Velocity, Applications (Precalculus - Trigonometry 5) :
https://www.youtube.com/watch?v=x6wnYbOBCic&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=80
### Area of a Sector, Angular Velocity, and Applications

Professor Leonard explores how trigonometric formulas—specifically arc length, sector area, and linear/angular velocity—apply to real-world physics, using the rotation of the Earth as his primary example.

---
#### 1. Arc Length and Longitude ([00:00:00] - [09:30])
Arc length ($s = r\theta$) allows us to calculate distances between two points on a sphere (like Earth) provided they lie on the same "great circle" (same longitude).

* **The Logic:** Because longitude lines pass through the center of the Earth, they form a great circle with a constant radius ($r \approx 3960$ miles).
* **Calculation:** If you have two locations on the same longitude, the distance between them is the arc length of the angle $\theta$ (the difference between their latitudes).
* **Crucial Rule:** Professor Leonard stresses that $\theta$ **must be in radians**. If provided in degrees, you must multiply by $\frac{\pi}{180^\circ}$ before plugging it into $s = r\theta$.

---
#### 2. Area of a Sector ([09:30] - [21:40])
To find the area of a portion of a circle (a "slice" or sector), he derives the formula by comparing the sector to the full circle.

* **Derivation:** He sets up a proportion: $\frac{\text{Sector Area}}{\theta} = \frac{\text{Total Area}}{\text{Full Rotation}}$. Since a full rotation is $2\pi$, he yields the formula:
  $$\text{Area} = \frac{1}{2}r^2\theta$$
* **Application:** When given a radius and an angle (in degrees), convert the angle to radians first. For example, $120^\circ$ becomes $\frac{2\pi}{3}$ radians, allowing for precise calculation of the area in square units (e.g., meters squared).

---
#### 3. Angular and Linear Velocity ([21:40] - [36:57])
He defines the speed of an object rotating on a sphere, explaining the difference between "spinning" and "moving."

* **Angular Velocity ($\omega$):** The rate at which the angle changes over time ($\omega = \frac{\theta}{t}$). For Earth, every point completes one full rotation ($2\pi$ radians) in $24$ hours, so $\omega = \frac{2\pi}{24} = \frac{\pi}{12}$ rad/hr.
* **Linear Velocity ($v$):** The actual speed (distance/time) an object moves along its circular path ($v = r\omega$).
* **Key Insight:** Your linear velocity ($v$) depends on your latitude. Because the Earth is a sphere, the radius ($r$)—your distance from the axis of rotation—shrinks as you move toward the poles. Consequently, people at the equator spin faster ($>1000$ mph) than people at higher latitudes ($<800$ mph).

---
#### Key Takeaways

> [!TIP]
> **The Unit Trap:**
> Professor Leonard consistently warns against using degrees in these formulas. He points out a "hidden $\frac{1}{\text{radian}}$" in the derivation of these formulas that necessitates the use of radians to ensure the units (miles, meters) cancel out correctly.

> [!IMPORTANT]
> **Radius Definition:**
> When calculating velocity on Earth, the "radius" ($r$) is not the distance to the center of the Earth, but the **perpendicular distance to the axis of rotation**. This is why your speed changes based on your latitude.

> [!CAUTION]
> **Degrees vs. Radians:**
> If you are plugging degrees into $s=r\theta$ or $A=\frac{1}{2}r^2\theta$, you will get nonsensical results. Always convert your input to radians first, or verify your calculator is in **RAD** mode.
### Arc Length Calculation: City Distance

**Question:** If I live at $48.685701^\circ$ Latitude and have to travel to a city at $43.602646^\circ$ Latitude (both at the same longitude), how far apart are the cities if the radius of the Earth $r = 3960 \text{ miles}$?

**Answer:** To find the distance between the two cities, we use the arc length formula $s = r \cdot \theta$.
1.  **Find the angle ($\theta$):**
    $\theta = 48.685701^\circ - 43.602646^\circ = 5.083055^\circ$
2.  **Convert to radians:**
    Since the formula requires radians, multiply by $\frac{\pi}{180^\circ}$:
    $5.083055^\circ \cdot \left( \frac{\pi}{180^\circ} \right) \approx 0.08872 \text{ radians}$
3.  **Calculate arc length ($s$):**
    $s = 3960 \text{ miles} \cdot 0.08872 \text{ radians} \approx 351.33 \text{ miles}$

---
**Key Takeaways:**
* **Formula:** $s = r\theta$
* **Constraint:** $\theta$ must be in radians.
* **Requirement:** Both points must lie on a "great circle" (same longitude) for this specific arc length formula to apply.

To find the distance between the two cities on a sphere, we use the arc length formula $s = r \cdot \theta$, based on the provided values:
* **Radius ($r$):** $3960 \text{ miles}$
* **Angle ($\theta$):** Difference in latitude: $48.685701^\circ - 43.602646^\circ = 5.083055^\circ$

---
#### 1. The Conversion Step
Professor Leonard emphasizes that the arc length formula **only** functions when $\theta$ is in radians. To convert the degree measurement to radians, we multiply by the ratio $\frac{\pi}{180^\circ}$:
$$5.083055^\circ \cdot \left( \frac{\pi}{180^\circ} \right) \approx 0.08872 \text{ radians}$$

---
#### 2. Calculate Arc Length
Using the converted angle, we solve for the distance ($s$):
$$s = 3960 \text{ miles} \cdot 0.08872 \text{ radians} \approx 351.33 \text{ miles}$$

---

#### Key Takeaways

> [!IMPORTANT]
> **Great Circle Requirement:**
> This calculation is only valid because both cities lie on the same longitude, allowing the path between them to be treated as an arc on a "great circle" (a circle that passes through the center of the sphere).

> [!CAUTION]
> **Degree vs. Radian Formula:**
> Plugging degrees directly into the arc length formula is a common error that leads to incorrect results because the formula relies on the radian-based definition of circular measure.

### Area of a Sector Calculation: r = 3m, theta = 120 degrees

**Question:** Find the area of a sector with a radius $r = 3 \text{ m}$ and a central angle $\theta = 120^\circ$.
**Answer:** To find the area, we use the formula $A = \frac{1}{2}r^2\theta$, noting that Professor Leonard emphasizes this formula **only** works when $\theta$ is in radians.
1. **Convert degrees to radians:**
   Multiply the angle by $\frac{\pi}{180^\circ}$ to convert:
   $120^\circ \cdot \left( \frac{\pi}{180^\circ} \right) = \frac{120\pi}{180} = \frac{2\pi}{3} \text{ radians}$

2. **Calculate the Area ($A$):**
   Substitute $r = 3$ and $\theta = \frac{2\pi}{3}$ into the formula:
   $A = \frac{1}{2} \cdot (3)^2 \cdot \left( \frac{2\pi}{3} \right)$
   $A = \frac{1}{2} \cdot 9 \cdot \left( \frac{2\pi}{3} \right)$
   $A = 3\pi \text{ m}^2 \approx 9.425 \text{ m}^2$

---
**Key Takeaways:**
* **Formula:** $A = \frac{1}{2}r^2\theta$
* **Crucial Rule:** The angle $\theta$ must be in radians.
* **Unit Check:** Inputting meters for $r$ results in square meters ($m^2$) for the area, confirming the unit consistency.
### Area of a Sector Calculation: A = 8m^2, r = 6m
**Question:** Find the central angle ($\theta$) in radians for a sector with an area $A = 8 \text{ m}^2$ and a radius $r = 6 \text{ m}$.
**Answer:** To find the angle, we use the sector area formula $A = \frac{1}{2}r^2\theta$. We rearrange the formula to solve for $\theta$:
1. **Rearrange the formula:**
   $A = \frac{1}{2}r^2\theta$
   $2A = r^2\theta$
   $\theta = \frac{2A}{r^2}$

2. **Substitute the known values ($A = 8, r = 6$):**
   $\theta = \frac{2 \cdot 8}{6^2}$
   $\theta = \frac{16}{36}$

3. **Simplify the result:**
   $\theta = \frac{4}{9} \text{ radians}$

---
**Key Takeaways :**
* **Formula:** $\theta = \frac{2A}{r^2}$
* **Units:** Since area is $m^2$ and $r^2$ is $m^2$, the units cancel out, leaving the angle as a dimensionless number in **radians**.
* **Conversion:** If you needed this in degrees, you would multiply by $\frac{180^\circ}{\pi}$, but radians is the standard unit for this formula.
### Linear Velocity on Earth: Step-by-Step Breakdown

Professor Leonard calculates the linear velocity (speed) of an object on the Earth's surface by considering Earth's rotation around its axis.

---
#### 1. Fundamental Formulas
* **Angular Velocity ($\omega$):** The rate at which the angle changes over time.
  $$\omega = \frac{\theta}{t}$$
* **Linear Velocity ($v$):** The speed along the arc length path.
  $$v = \frac{s}{t} = r \cdot \omega$$
  *(Substituting $s = r \cdot \theta$ into the velocity formula creates $v = r \cdot \frac{\theta}{t}$, which simplifies to $v = r \cdot \omega$.)*

---
#### 2. Determine Angular Velocity ($\omega$)
Every point on Earth completes one full rotation ($2\pi$ radians) in $24$ hours.
$$\omega = \frac{2\pi \text{ radians}}{24 \text{ hours}} = \frac{\pi}{12} \text{ rad/hr}$$

---
#### 3. Calculate Linear Velocity ($v$)
The linear velocity depends on your distance ($r$) from the axis of rotation, not the center of the Earth.

**Example: Professor Leonard's Latitude ($48.6^\circ$ N)**
* At this latitude, the radius ($r$) from the axis is approximately $3,000 \text{ miles}$.
* **Calculation:**
  $$v = 3,000 \text{ miles} \cdot \frac{\pi}{12} \text{ rad/hr}$$
  $$v \approx 785 \text{ mph}$$

**Example: At the Equator**
* At the equator, the radius ($r$) from the axis is approximately $3,960 \text{ miles}$.
* **Calculation:**
  $$v = 3,960 \text{ miles} \cdot \frac{\pi}{12} \text{ rad/hr}$$
  $$v \approx 1,037 \text{ mph}$$
---
#### Key Takeaways for Anki

> [!IMPORTANT]
> **Variable $r$:** Your speed is not constant; it depends on your distance from the axis of rotation. The closer you are to the equator, the larger your radius, and the faster you are traveling.

> [!CAUTION]
> **Axis vs. Center:** Do not use the distance to the center of the Earth ($3,960 \text{ miles}$) for every calculation. You must use the distance to the axis of rotation, which varies by latitude.
## 2026-June-10 - Trigonometric Functions and the Unit Circle (Precalculus - Trigonometry 6) :
https://www.youtube.com/watch?v=__nefjOhVks&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=80
### Trigonometric Functions and the Unit Circle

Professor Leonard defines trigonometric functions through two primary approaches: the **Right Triangle** approach and the **Unit Circle** approach. Understanding both is essential because they represent the same underlying relationships between angles and side ratios.

---
#### 1. The Right Triangle Approach
 Trigonometric functions relate an angle ($\theta$) to the ratio of two sides of a right triangle.
* **Key Concept:** Due to the properties of **similar triangles**, the ratio of sides remains constant regardless of the triangle's size, provided the angle is the same.
* **Definitions:**
    * **Sine ($\sin$):** $\frac{\text{Opposite}}{\text{Hypotenuse}}$
    * **Cosine ($\cos$):** $\frac{\text{Adjacent}}{\text{Hypotenuse}}$
    * **Tangent ($\tan$):** $\frac{\text{Opposite}}{\text{Adjacent}}$ or $\frac{\sin(\theta)}{\cos(\theta)}$

---
#### 2. The Unit Circle Approach
 A unit circle has a **radius of $1$**. When superimposed on an $xy$-axis, it allows us to define trigonometric functions based on coordinates rather than arbitrary side lengths.
* **Arc Length ($t$):** On a unit circle with radius $r=1$, the arc length $t$ is numerically equal to the central angle $\theta$ (when measured in radians).
* **Defining Functions using $(x, y)$ coordinates:**
    * **$\sin(t) = y$** (The $y$-coordinate)
    * **$\cos(t) = x$** (The $x$-coordinate)
    * **$\tan(t) = \frac{y}{x}$**

---
#### 3. Reciprocal Functions
Reciprocal functions are the multiplicative inverses of the primary trig functions.
* **Cosecant ($\csc(t)$):** $\frac{1}{\sin(t)} = \frac{1}{y}$
* **Secant ($\sec(t)$):** $\frac{1}{\cos(t)} = \frac{1}{x}$
* **Cotangent ($\cot(t)$):** $\frac{1}{\tan(t)} = \frac{x}{y}$

---
#### 4. Quadrant Angles and Undefined Values
Quadrant angles ($0^\circ, 90^\circ, 180^\circ, 270^\circ$) occur at the axes.
* **Undefined Values:** Occur whenever you divide by zero. For example, $\tan(90^\circ)$ is undefined because the $x$-coordinate is $0$.
* **Range:** Because $\sin$ and $\cos$ are defined as coordinates on a unit circle, their values are strictly bounded between $-1$ and $1$.

---
#### 5. Example: Finding Values from a Point
 If given a point $(x, y)$ on the unit circle (e.g., $(-\frac{1}{2}, \frac{\sqrt{3}}{2})$), you can determine all six trig functions:
1.  **Identify:** $\sin(\theta) = y$ and $\cos(\theta) = x$.
2.  **Calculate Tangent:** Divide $y/x$.
3.  **Reciprocate:** Find the reciprocal values to obtain $\csc, \sec, \cot$.
    * *Note: Rationalize denominators where necessary (e.g., $\frac{1}{\sqrt{3}} \rightarrow \frac{\sqrt{3}}{3}$).*

---
#### Key Takeaways for Anki
* **The "Magic" of Radians:** The identity $s = r\theta$ is only simplified to $s = \theta$ when $r=1$ and $\theta$ is in **radians**.
* **Coordinate Mapping:** $\cos$ is always the $x$-value, and $\sin$ is always the $y$-value.
* **Repetition:** Trig functions have a "period" and repeat their values after a full rotation ($2\pi$).

## 2026-June-12 - How to Use the Unit Circle in Trigonometry (Precalculus - Trigonometry 7) : 
https://www.youtube.com/watch?v=GdRZfemxTFI&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=83
### Trigonometric Functions and the Unit Circle

Professor Leonard defines trigonometric functions through two primary approaches: the **Right Triangle** approach and the **Unit Circle** approach. Understanding both is essential because they represent the same underlying relationships between angles and side ratios.

---
#### 1. The Right Triangle Approach
 Trigonometric functions relate an angle ($\theta$) to the ratio of two sides of a right triangle.
* **Key Concept:** Due to the properties of **similar triangles**, the ratio of sides remains constant regardless of the triangle's size, provided the angle is the same.
* **Definitions:**
    * **Sine ($\sin$):** $\frac{\text{Opposite}}{\text{Hypotenuse}}$
    * **Cosine ($\cos$):** $\frac{\text{Adjacent}}{\text{Hypotenuse}}$
    * **Tangent ($\tan$):** $\frac{\text{Opposite}}{\text{Adjacent}}$ or $\frac{\sin(\theta)}{\cos(\theta)}$

---
#### 2. The Unit Circle Approach
 A unit circle has a **radius of $1$**. When superimposed on an $xy$-axis, it allows us to define trigonometric functions based on coordinates rather than arbitrary side lengths.
* **Arc Length ($t$):** On a unit circle with radius $r=1$, the arc length $t$ is numerically equal to the central angle $\theta$ (when measured in radians).
* **Defining Functions using $(x, y)$ coordinates:**
    * **$\sin(t) = y$** (The $y$-coordinate)
    * **$\cos(t) = x$** (The $x$-coordinate)
    * **$\tan(t) = \frac{y}{x}$**

---
#### 3. Reciprocal Functions
Reciprocal functions are the multiplicative inverses of the primary trig functions.
* **Cosecant ($\csc(t)$):** $\frac{1}{\sin(t)} = \frac{1}{y}$
* **Secant ($\sec(t)$):** $\frac{1}{\cos(t)} = \frac{1}{x}$
* **Cotangent ($\cot(t)$):** $\frac{1}{\tan(t)} = \frac{x}{y}$

---
#### 4. Quadrant Angles and Undefined Values
Quadrant angles ($0^\circ, 90^\circ, 180^\circ, 270^\circ$) occur at the axes.
* **Undefined Values:** Occur whenever you divide by zero. For example, $\tan(90^\circ)$ is undefined because the $x$-coordinate is $0$.
* **Range:** Because $\sin$ and $\cos$ are defined as coordinates on a unit circle, their values are strictly bounded between $-1$ and $1$.

---
#### 5. Example: Finding Values from a Point
 If given a point $(x, y)$ on the unit circle (e.g., $(-\frac{1}{2}, \frac{\sqrt{3}}{2})$), you can determine all six trig functions:
1.  **Identify:** $\sin(\theta) = y$ and $\cos(\theta) = x$.
2.  **Calculate Tangent:** Divide $y/x$.
3.  **Reciprocate:** Find the reciprocal values to obtain $\csc, \sec, \cot$.
    * *Note: Rationalize denominators where necessary (e.g., $\frac{1}{\sqrt{3}} \rightarrow \frac{\sqrt{3}}{3}$).*

---
#### Key Takeaways for Anki
* **The "Magic" of Radians:** The identity $s = r\theta$ is only simplified to $s = \theta$ when $r=1$ and $\theta$ is in **radians**.
* **Coordinate Mapping:** $\cos$ is always the $x$-value, and $\sin$ is always the $y$-value.
* **Repetition:** Trig functions have a "period" and repeat their values after a full rotation ($2\pi$).
### Evaluating $\tan(6\pi)$
Following Professor Leonard's method of evaluating trigonometric functions for angles that are not explicitly on the unit circle:
* **Step 1: Determine Coterminal Angles**
    * Since $6\pi$ represents multiple full rotations ($3$ full rotations of $2\pi$), we can subtract multiples of $2\pi$ to find an angle within the standard $[0, 2\pi)$ range.
    * $6\pi - 2\pi = 4\pi$
    * $4\pi - 2\pi = 2\pi$
    * $2\pi$ is coterminal with $0$.
* **Step 2: Identify Coordinates**
    * At $0$ (or $2\pi$), the point on the unit circle is $(1, 0)$.
    * $x = 1$ (which is $\cos(0)$)
    * $y = 0$ (which is $\sin(0)$)
* **Step 3: Calculate Tangent**
    * Tangent is defined as $\frac{y}{x}$ (or $\frac{\sin(\theta)}{\cos(\theta)}$).
    * $\tan(6\pi) = \frac{0}{1}$
    * **$\tan(6\pi) = 0$**
### Evaluating $\sec(-\pi)$

Following Professor Leonard's method of evaluating trigonometric functions for angles that are not explicitly on the unit circle or that require coterminal identification:
* **Step 1: Determine the Coterminal Angle**
    * $-\pi$ represents a clockwise rotation of a half-circle.
    * We can find the coterminal angle by adding $2\pi$ to $-\pi$.
    * $-\pi + 2\pi = \pi$.
    * Therefore, $\sec(-\pi)$ is coterminal with $\sec(\pi)$.
* **Step 2: Identify Coordinates**
    * At $\pi$, the point on the unit circle is $(-1, 0)$.
    * $x = -1$ (this is $\cos(\pi)$)
    * $y = 0$ (this is $\sin(\pi)$)
* **Step 3: Calculate Secant**
    * Secant is defined as the reciprocal of cosine: $\sec(\theta) = \frac{1}{\cos(\theta)} = \frac{1}{x}$.
    * $\sec(-\pi) = \frac{1}{-1}$
    * **$\sec(-\pi) = -1$**
### Evaluating $\sin(45^\circ) + \cos(60^\circ)$
Following Professor Leonard's method of using the unit circle to perform arithmetic with trigonometric functions:
* **Step 1: Identify Individual Values**
    * Locate $45^\circ$ (or $\pi/4$) on the unit circle. Sine is the $y$-coordinate.
        * $\sin(45^\circ) = \frac{\sqrt{2}}{2}$
    * Locate $60^\circ$ (or $\pi/3$) on the unit circle. Cosine is the $x$-coordinate.
        * $\cos(60^\circ) = \frac{1}{2}$
* **Step 2: Perform the Addition**
    * Substitute the identified values into the expression:
        * $\frac{\sqrt{2}}{2} + \frac{1}{2}$
    * Since they share a common denominator of $2$, combine the numerators:
        * **$\frac{1 + \sqrt{2}}{2}$**
### Evaluating $\csc(45^\circ)\tan(60^\circ)$

Following Professor Leonard's method of solving trigonometric expressions by breaking them down into their primary functions (sine, cosine, and tangent) and applying the unit circle:
* **Step 1: Identify Individual Values**
    * **$\csc(45^\circ)$:** Since $\csc$ is the reciprocal of $\sin$, first find $\sin(45^\circ)$.
        * $\sin(45^\circ) = \frac{\sqrt{2}}{2}$
        * Therefore, $\csc(45^\circ) = \frac{1}{\sin(45^\circ)} = \frac{2}{\sqrt{2}}$.
        * Rationalizing the denominator: $\frac{2}{\sqrt{2}} \cdot \frac{\sqrt{2}}{\sqrt{2}} = \frac{2\sqrt{2}}{2} = \sqrt{2}$.
    * **$\tan(60^\circ)$:** Tangent is $\frac{y}{x}$ (or $\sin/\cos$).
        * $\sin(60^\circ) = \frac{\sqrt{3}}{2}$
        * $\cos(60^\circ) = \frac{1}{2}$
        * $\tan(60^\circ) = \frac{\sqrt{3}/2}{1/2} = \sqrt{3}$.
* **Step 2: Multiply the Results**
    * Substitute the values back into the expression:
        * $\csc(45^\circ) \cdot \tan(60^\circ) = \sqrt{2} \cdot \sqrt{3}$
    * **$= \sqrt{6}$**
### Evaluating $3\csc\left(\frac{\pi}{3}\right) + \cot\left(\frac{\pi}{4}\right)$

Following Professor Leonard's method of solving trigonometric expressions by breaking them down into their primary functions (sine, cosine, and tangent) and applying the unit circle:
* **Step 1: Identify Individual Values**
    * **$\csc\left(\frac{\pi}{3}\right)$:** Since $\csc$ is the reciprocal of $\sin$, first find $\sin\left(\frac{\pi}{3}\right)$.
        * At $\frac{\pi}{3}$, the point on the unit circle is $\left(\frac{1}{2}, \frac{\sqrt{3}}{2}\right)$.
        * $\sin\left(\frac{\pi}{3}\right) = \frac{\sqrt{3}}{2}$.
        * $\csc\left(\frac{\pi}{3}\right) = \frac{1}{\sin\left(\frac{\pi}{3}\right)} = \frac{2}{\sqrt{3}}$.
        * Rationalizing the denominator: $\frac{2}{\sqrt{3}} \cdot \frac{\sqrt{3}}{\sqrt{3}} = \frac{2\sqrt{3}}{3}$.
    * **$\cot\left(\frac{\pi}{4}\right)$:** Since $\cot$ is the reciprocal of $\tan$, first find $\tan\left(\frac{\pi}{4}\right)$.
        * At $\frac{\pi}{4}$, the point on the unit circle is $\left(\frac{\sqrt{2}}{2}, \frac{\sqrt{2}}{2}\right)$.
        * $\tan\left(\frac{\pi}{4}\right) = \frac{\sqrt{2}/2}{\sqrt{2}/2} = 1$.
        * $\cot\left(\frac{\pi}{4}\right) = \frac{1}{\tan\left(\frac{\pi}{4}\right)} = \frac{1}{1} = 1$.
* **Step 2: Combine the Results**
    * Substitute the values back into the expression:
        * $3\left(\csc\left(\frac{\pi}{3}\right)\right) + \cot\left(\frac{\pi}{4}\right) = 3\left(\frac{2\sqrt{3}}{3}\right) + 1$
        * The $3$s cancel out: $2\sqrt{3} + 1$.
    * **$= 2\sqrt{3} + 1$**
### Evaluating $\sin\left(\frac{11\pi}{2}\right)$

Following Professor Leonard's method of evaluating trigonometric functions for angles that involve multiple revolutions:
* **Step 1: Determine the Coterminal Angle**
    * $\frac{11\pi}{2}$ is greater than one full revolution ($2\pi$ or $\frac{4\pi}{2}$). 
    * We can simplify this by subtracting multiples of $2\pi$ until we reach an angle on the unit circle.
    * Subtracting $2\pi$ ($\frac{4\pi}{2}$): $\frac{11\pi}{2} - \frac{4\pi}{2} = \frac{7\pi}{2}$
    * Subtracting $2\pi$ ($\frac{4\pi}{2}$) again: $\frac{7\pi}{2} - \frac{4\pi}{2} = \frac{3\pi}{2}$
    * Therefore, $\frac{11\pi}{2}$ is coterminal with $\frac{3\pi}{2}$ (or $270^\circ$).
* **Step 2: Identify Coordinates**
    * At $\frac{3\pi}{2}$, the point on the unit circle is $(0, -1)$.
* **Step 3: Solve for Sine**
    * Sine is defined as the $y$-coordinate of the point on the unit circle.
    * $\sin\left(\frac{11\pi}{2}\right) = \sin\left(\frac{3\pi}{2}\right) = -1$
    * **$\sin\left(\frac{11\pi}{2}\right) = -1$**
### Evaluating $2\sin\left(\frac{\pi}{4}\right) + 3\tan\left(\frac{\pi}{4}\right)$

Following Professor Leonard's method of solving trigonometric expressions by identifying coordinates on the unit circle:
* **Step 1: Identify Individual Values**
    * Locate $\frac{\pi}{4}$ (or $45^\circ$) on the unit circle.
    * The coordinates at this angle are $\left(\frac{\sqrt{2}}{2}, \frac{\sqrt{2}}{2}\right)$.
    * **$\sin\left(\frac{\pi}{4}\right)$:** This is the $y$-coordinate, which is $\frac{\sqrt{2}}{2}$.
    * **$\tan\left(\frac{\pi}{4}\right)$:** This is $\frac{y}{x}$, which is $\frac{\sqrt{2}/2}{\sqrt{2}/2} = 1$.
* **Step 2: Perform the Arithmetic**
    * Substitute the values back into the expression:
        * $2\left(\sin\left(\frac{\pi}{4}\right)\right) + 3\left(\tan\left(\frac{\pi}{4}\right)\right)$
        * $2\left(\frac{\sqrt{2}}{2}\right) + 3(1)$
    * Simplify the terms:
        * The $2$s in the first term cancel out, leaving $\sqrt{2}$.
        * The second term is $3$.
    * **$= \sqrt{2} + 3$**
### Using a Calculator for Trigonometric Values

Following Professor Leonard's method for calculating values not found on the unit circle, you must ensure your calculator is set to the correct mode (**Degrees** or **Radians**) before inputting your values.
* **1. $\sin(28^\circ) \approx$**
    * **Mode**: Ensure your calculator is set to **Degrees**.
    * **Calculation**: $\sin(28) \approx 0.469$
* **2. $\cot\left(\frac{\pi}{12}\right) \approx$**
    * **Mode**: Ensure your calculator is set to **Radians**.
    * **Calculation**: Since many calculators lack a `cot` button, use the reciprocal of tangent: $1 / \tan(\pi/12)$.
    * **Result**: $\approx 3.732$
* **3. $\sin(1^\circ) \approx$**
    * **Mode**: Ensure your calculator is set to **Degrees**.
    * **Calculation**: $\sin(1) \approx 0.017$
* **4. $\sin(1) \approx$**
    * **Mode**: Ensure your calculator is set to **Radians**. (Note the lack of a degree symbol indicates radians).
    * **Calculation**: $\sin(1 \text{ rad}) \approx 0.841$

---
### Solving for a Point $(-3, 4)$ not on the Unit Circle
If a point is not on the unit circle, you must find the radius ($r$) using the Pythagorean theorem before calculating trigonometric ratios.

* **Step 1: Find $r$**
    * $r = \sqrt{x^2 + y^2} = \sqrt{(-3)^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5$.
* **Step 2: Calculate Ratios**
    * Instead of just $x$ or $y$, use the radius to normalize the values:
    * **$\sin(\theta) = \frac{y}{r} = \frac{4}{5}$**
    * **$\cos(\theta) = \frac{x}{r} = \frac{-3}{5}$**
    * **$\tan(\theta) = \frac{y}{x} = \frac{4}{-3} = -\frac{4}{3}$**
## 2026-June-14 - Basic Properties of Trigonometric Functions (Precalculus - Trigonometry 8) :
https://www.youtube.com/watch?v=_dTRpq_yGIc&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=84
### Summary of Basic Properties of Trigonometric Functions

This summary covers the core relationships, domains, ranges, and periodicity of trigonometric functions as presented by Professor Leonard.

---
#### 1. Fundamental Relationships
Trigonometric functions relate an angle ($\theta$) to specific coordinates on the unit circle:
* **Sine ($\sin\theta$):** The $y$-coordinate.
* **Cosine ($\cos\theta$):** The $x$-coordinate.
* **Tangent ($\tan\theta$):** The ratio $\frac{y}{x}$.

**Reciprocal Functions:**
* **Cosecant ($\csc\theta$):** $\frac{1}{y}$
* **Secant ($\sec\theta$):** $\frac{1}{x}$
* **Cotangent ($\cot\theta$):** $\frac{x}{y}$

---
#### 2. Domain and Range
Domain is determined by angles that yield defined outputs, excluding values where the denominator is zero.

| Function | Domain | Range |
| :--- | :--- | :--- |
| **Sine** | All real numbers | $[-1, 1]$ |
| **Cosine** | All real numbers | $[-1, 1]$ |
| **Tangent** | All except $\frac{\pi}{2} + k\pi$ | $(-\infty, \infty)$ |
| **Cosecant** | All except $k\pi$ | $(-\infty, -1] \cup [1, \infty)$ |
| **Secant** | All except $\frac{\pi}{2} + k\pi$ | $(-\infty, -1] \cup [1, \infty)$ |
| **Cotangent** | All except $k\pi$ | $(-\infty, \infty)$ |

---
#### 3. Periodicity and Identities
The period represents the interval over which function outputs repeat.
* **Period of $2\pi$:** Sine, Cosine, Cosecant, Secant.
* **Period of $\pi$:** Tangent, Cotangent.

**Key Identities:**
* $\sin(\theta + 2\pi k) = \sin\theta$
* $\cos(\theta + 2\pi k) = \cos\theta$
* $\tan(\theta + \pi k) = \tan\theta$

---
#### 4. Simplifying Angles (Calculation Shortcut)
To simplify large angles, one can subtract multiples of the period until the angle falls within the standard unit circle interval $[0, 2\pi)$ or $[0, \pi)$.

* **Shortcut Method:**
    1.  Multiply the angle's denominator by the function's period (e.g., $2\pi$ for sine, $\pi$ for tangent).
    2.  Divide the numerator of your original angle by this value.
    3.  The **remainder** becomes the new numerator for your simplified angle.

---
#### 5. Quadrant Signs (Mnemonic: ASTC)
The signs of trigonometric functions depend on the quadrant of the angle:
* **Quadrant I:** All positive.
* **Quadrant II:** Sine/Cosecant are positive.
* **Quadrant III:** Tangent/Cotangent are positive.
* **Quadrant IV:** Cosine/Secant are positive.

## 2026-June-15 - Reciprocal Identities in Trigonometry (Precalculus - Trigonometry 9) :
https://www.youtube.com/watch?v=98jDUsZ2JYA&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=85
### Summary: Reciprocal Identities in Trigonometry
This summary details the relationships, utility, and application of reciprocal identities in trigonometry based on the instructional series by Professor Leonard.

---
#### 1. Fundamental Reciprocal Relationships
Trigonometric functions are pairs of reciprocals. Understanding these is essential for simplifying expressions and solving for missing functions:

* **Sine and Cosecant:** $\csc\theta = \frac{1}{\sin\theta}$ [00:01:19]
* **Cosine and Secant:** $\sec\theta = \frac{1}{\cos\theta}$ [00:01:45]
* **Tangent and Cotangent:** $\cot\theta = \frac{1}{\tan\theta}$ or $\frac{\cos\theta}{\sin\theta}$ [00:01:59]

*Note:* Reciprocal identities simply require flipping the fraction. They do not change the sign of the value. [00:02:52]

---
#### 2. Unit Circle vs. Similar Triangles
You can interpret trigonometric functions either as points on a unit circle or as sides of a right triangle. Due to properties of **similar triangles**, these interpretations yield identical ratios. [00:07:00]

* **Unit Circle:** Relates angles to coordinates $(x, y)$ where the radius ($r$) is 1. [00:00:33]
* **Arbitrary Circle/Triangle:** Relates angles to $(x, y)$ where the radius ($r$) can be any value. The ratios remain consistent (e.g., $\sin\theta = \frac{y}{r}$). [00:20:52]

---
#### 3. Solving for Missing Trigonometric Functions
To determine the remaining trigonometric functions given limited information, follow these steps:

1.  **Identify the Quadrant:** Use the signs of the given functions to locate the angle's quadrant. [00:03:53]
    * **Q I:** All positive. [00:08:42]
    * **Q II:** Sine/Cosecant positive. [00:08:48]
    * **Q III:** Tangent/Cotangent positive. [00:08:58]
    * **Q IV:** Cosine/Secant positive. [00:09:07]
2.  **Use Pythagorean Identity:** If one function is known, use the relationship $x^2 + y^2 = r^2$ to find the missing side. [00:13:54]
3.  **Account for Signs:** When taking square roots, ensure the chosen sign for the missing side matches the quadrant identified in step 1. [00:28:40]

---
#### 4. Practical Application Example
Given $\sec\theta = 2$ and $\sin\theta < 0$:
* **Quadrant:** Since $\sec\theta$ (and thus $\cos\theta$) is positive and $\sin\theta$ is negative, the angle is in **Quadrant IV**. [00:40:05]
* **Find $x, y, r$:**
    * $\sec\theta = \frac{r}{x} = \frac{2}{1} \implies r=2, x=1$. [00:41:41]
    * $1^2 + y^2 = 2^2 \implies y^2 = 3 \implies y = -\sqrt{3}$ (negative due to Q IV). [00:42:47]
* **Remaining Functions:**
    * $\sin\theta = \frac{y}{r} = -\frac{\sqrt{3}}{2}$ [00:44:19]
    * $\tan\theta = \frac{y}{x} = -\sqrt{3}$ [00:45:04]
    * $\csc\theta = -\frac{2\sqrt{3}}{3}$, $\cot\theta = -\frac{\sqrt{3}}{3}$ [00:45:15]

### Evaluating Trigonometric Functions via Reciprocal Identities

Following Professor Leonard's method, we find the remaining four trigonometric functions using the given values:
* **$\sin\theta = \frac{4}{5}$**
* **$\cos\theta = -\frac{3}{5}$**

---
#### 1. Identify the Quadrant
* Sine ($y$) is **positive**, and Cosine ($x$) is **negative**.
* This maps the angle $\theta$ directly to **Quadrant II**.
* In Quadrant II, we expect $\csc\theta$ to be positive, while $\sec\theta$, $\tan\theta$, and $\cot\theta$ must be negative.

---
#### 2. Step-by-Step Calculations

**A. Find $\csc\theta$**
* Cosecant is the reciprocal function of sine.
$$\csc\theta = \frac{1}{\sin\theta} = \mathbf{\frac{5}{4}}$$
**B. Find $\sec\theta$**
* Secant is the reciprocal function of cosine. Reciprocating a value does not alter its sign.
$$\sec\theta = \frac{1}{\cos\theta} = \mathbf{-\frac{5}{3}}$$
**C. Find $\tan\theta$**
* Tangent compares the two given boundaries by taking the quotient of sine over cosine ($\frac{y}{x}$).
$$\tan\theta = \frac{\sin\theta}{\cos\theta} = \frac{\frac{4}{5}}{-\frac{3}{5}}$$
* Multiplying by the reciprocal denominator cancels out the $5$s:
$$\tan\theta = \frac{4}{5} \cdot \left(-\frac{5}{3}\right) = \mathbf{-\frac{4}{3}}$$
**D. Find $\cot\theta$**
* Rather than setting up a complex fraction again, simply flip the value found for tangent.
$$\cot\theta = \frac{1}{\tan\theta} = \mathbf{-\frac{3}{4}}$$
### Evaluating Trigonometric Functions via Reciprocal Identities

Following Professor Leonard's method, we find the remaining four trigonometric functions using the given values:
* **$\sin\theta = \frac{\sqrt{3}}{2}$**
* **$\cos\theta = \frac{1}{2}$**

---
#### 1. Identify the Quadrant
* Sine ($y$) is **positive**, and Cosine ($x$) is **positive**.
* This maps the angle $\theta$ directly to **Quadrant I**.
* In Quadrant I, all trigonometric functions are positive.

---
#### 2. Step-by-Step Calculations

**A. Find $\csc\theta$**
* Cosecant is the reciprocal function of sine.
$$\csc\theta = \frac{1}{\sin\theta} = \frac{1}{\frac{\sqrt{3}}{2}} = \frac{2}{\sqrt{3}}$$
* Rationalizing the denominator:
$$\csc\theta = \frac{2}{\sqrt{3}} \cdot \frac{\sqrt{3}}{\sqrt{3}} = \mathbf{\frac{2\sqrt{3}}{3}}$$
**B. Find $\sec\theta$**
* Secant is the reciprocal function of cosine.
$$\sec\theta = \frac{1}{\cos\theta} = \frac{1}{\frac{1}{2}} = \mathbf{2}$$
**C. Find $\tan\theta$**
* Tangent compares the two given values by taking the quotient of sine over cosine ($\frac{y}{x}$).
$$\tan\theta = \frac{\sin\theta}{\cos\theta} = \frac{\frac{\sqrt{3}}{2}}{\frac{1}{2}}$$
* Multiplying by the reciprocal denominator:
$$\tan\theta = \frac{\sqrt{3}}{2} \cdot 2 = \mathbf{\sqrt{3}}$$
**D. Find $\cot\theta$**
* Cotangent is the reciprocal of tangent.
$$\cot\theta = \frac{1}{\tan\theta} = \frac{1}{\sqrt{3}}$$
* Rationalizing the denominator:
$$\cot\theta = \frac{1}{\sqrt{3}} \cdot \frac{\sqrt{3}}{\sqrt{3}} = \mathbf{\frac{\sqrt{3}}{3}}$$
### Solving for Missing Variables via Pythagorean Identity

Following Professor Leonard's method, we treat the given ratio as $\sin\theta = \frac{y}{r}$ to determine the missing components of the right triangle.

* **Given:** $\sin\theta = \frac{12}{13}$
#### 1. Identify Components
* **$y = 12$** (the vertical side)
* **$r = 13$** (the hypotenuse)
#### 2. Solve for $x$
Using the Pythagorean theorem ($x^2 + y^2 = r^2$):
* $x^2 + 12^2 = 13^2$
* $x^2 + 144 = 169$
* $x^2 = 25$
* **$x = \pm 5$** (We must consider $\pm$ because the quadrant is not specified).
#### 3. Determine Final Values
Depending on the quadrant (which would be provided to select between positive or negative $x$), the remaining values are calculated as follows:
* **$\cos\theta = \frac{x}{r} = \pm \frac{5}{13}$**
* **$\tan\theta = \frac{y}{x} = \pm \frac{12}{5}$**
* **$\csc\theta = \frac{r}{y} = \frac{13}{12}$**
* **$\sec\theta = \frac{r}{x} = \pm \frac{13}{5}$**
* **$\cot\theta = \frac{x}{y} = \pm \frac{5}{12}$**

*Note: Without a specified quadrant, all values dependent on $x$ retain the $\pm$ notation to account for all possible orientations.*
### Evaluating Trigonometric Functions for $\sec\theta = 2$ and $\sin\theta < 0$

Following Professor Leonard's method, we determine the remaining trigonometric functions by identifying the quadrant and using the Pythagorean identity.

---
#### 1. Identify the Quadrant
* **$\sec\theta = 2$**: Since $\sec\theta$ is positive, the angle must be in a quadrant where $\cos\theta$ is positive (Quadrants I or IV).
* **$\sin\theta < 0$**: Since $\sin\theta$ is negative, the angle must be in a quadrant where $y$ is negative (Quadrants III or IV).
* **Conclusion**: The angle $\theta$ resides in **Quadrant IV**.

---
#### 2. Determine Components
* Using $\sec\theta = \frac{r}{x} = \frac{2}{1}$, we identify:
    * $r = 2$
    * $x = 1$
* Use the Pythagorean theorem ($x^2 + y^2 = r^2$) to solve for $y$:
    * $1^2 + y^2 = 2^2$
    * $1 + y^2 = 4 \implies y^2 = 3$
    * $y = -\sqrt{3}$ (Negative sign chosen because $\theta$ is in Quadrant IV).

---
#### 3. Calculate Remaining Functions
* **$\sin\theta = \frac{y}{r} = \mathbf{-\frac{\sqrt{3}}{2}}$**
* **$\cos\theta = \frac{1}{\sec\theta} = \mathbf{\frac{1}{2}}$**
* **$\csc\theta = \frac{1}{\sin\theta} = \frac{1}{-\frac{\sqrt{3}}{2}} = \mathbf{-\frac{2\sqrt{3}}{3}}$**
* **$\tan\theta = \frac{y}{x} = \frac{-\sqrt{3}}{1} = \mathbf{-\sqrt{3}}$**
* **$\cot\theta = \frac{1}{\tan\theta} = \frac{1}{-\sqrt{3}} = \mathbf{-\frac{\sqrt{3}}{3}}$**
## 2026-June-17 - Pythagorean Identities for Trigonometric Functions (Precalculus - Trigonometry 10) :
https://www.youtube.com/watch?v=huP3v7iZuLM&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=87
### Summary: Pythagorean and Even/Odd Trigonometric Identities

This lecture covers even and odd identities, the derivation of Pythagorean identities from the unit circle, and techniques for simplifying complex trigonometric expressions.

---
#### 1. Even and Odd Trigonometric Identities
* **Definitions**:
    * **Even Functions**: Symmetric about the y-axis; opposite inputs yield equal outputs ($f(-\theta) = f(\theta)$).
    * Cosine and Secant are the only even trigonometric functions.
    * **Odd Functions**: Symmetric about the origin; opposite inputs yield opposite outputs ($f(-\theta) = -f(\theta)$).
    * Sine, Cosecant, Tangent, and Cotangent are odd.
* **Application**: Knowing these identities allows for easier manipulation of negative angles.
    * For even functions, you can change the sign of the input without altering the function's value.
    * For odd functions, changing the input sign requires changing the function's sign.

---
#### 2. Derivation of Pythagorean Identities
The Pythagorean identities are rooted in the equation of a unit circle ($x^2 + y^2 = 1$) and the definitions $\cos\theta = x$ and $\sin\theta = y$.

* **Primary Identity**: $\sin^2\theta + \cos^2\theta = 1$.
* **Other Identities**:
    * Divide by $\sin^2\theta$ to get: $1 + \cot^2\theta = \csc^2\theta$.
    * Divide by $\cos^2\theta$ to get: $\tan^2\theta + 1 = \sec^2\theta$.
* **Utility**: These are essential for converting between functions and simplifying expressions, especially in calculus.

---
#### 3. Advanced Angle Simplification
When dealing with angles larger than a single rotation ($2\pi$ or $360^\circ$), use the period of the function to reduce the angle.
* **Technique**: Divide the numerator of the angle by the (denominator $\times$ period).
* The remainder of this division, when placed over the original denominator, identifies the simplified angle on the unit circle.

---
#### 4. Simplifying Expressions with Identities
Strategies for simplifying expressions include:
* **Identify Matches**: Recognize $\sin^2\theta + \cos^2\theta$ or $\sec^2\theta - \tan^2\theta$ patterns immediately to collapse them to $1$.
* **Unify Functions**: If an expression contains mixed functions, convert everything to sines and cosines to look for cancellations.
* **Strategy**:
    1.  Simplify angles using even/odd identities or period reduction.
    2.  Rewrite terms in sines and cosines if necessary to identify potential simplifications.
### Summary: The Pythagorean Identity

The Pythagorean identity is a fundamental relationship in trigonometry, derived directly from the equation of a circle and the Pythagorean theorem. It establishes the link between the sine and cosine of an angle $\theta$.

---
#### 1. Derivation from the Unit Circle
* **Circle Equation**: The equation for a unit circle (a circle with a radius of $r=1$) is given by $x^2 + y^2 = 1$. * **Trigonometric Definitions**: On the unit circle, any point $(x, y)$ can be defined by an angle $\theta$ such that $x = \cos\theta$ and $y = \sin\theta$.
* **Substitution**: By substituting these definitions into the circle equation, we get $(\cos\theta)^2 + (\sin\theta)^2 = 1$.
* **Identity**: Using standard notation for trigonometric powers, this simplifies to the primary Pythagorean identity:
$$\sin^2\theta + \cos^2\theta = 1$$

---
#### 2. Corollaries
From this primary identity, we can derive additional useful expressions for manipulating trigonometric equations:
* $\sin^2\theta = 1 - \cos^2\theta$
* $\cos^2\theta = 1 - \sin^2\theta$

### Summary: The Pythagorean Identity

The Pythagorean identity is a fundamental relationship in trigonometry, derived directly from the equation of a circle and the Pythagorean theorem. It establishes the link between the sine and cosine of an angle $\theta$.

---
#### 1. Derivation from the Unit Circle
* **Circle Equation**: The equation for a unit circle (a circle with a radius of $r=1$) is given by $x^2 + y^2 = 1$. * **Trigonometric Definitions**: On the unit circle, any point $(x, y)$ can be defined by an angle $\theta$ such that $x = \cos\theta$ and $y = \sin\theta$.
* **Substitution**: By substituting these definitions into the circle equation, we get $(\cos\theta)^2 + (\sin\theta)^2 = 1$.
* **Identity**: Using standard notation for trigonometric powers, this simplifies to the primary Pythagorean identity:
$$\sin^2\theta + \cos^2\theta = 1$$

---
#### 2. Corollaries
From this primary identity, we can derive additional useful expressions for manipulating trigonometric equations:
* $\sin^2\theta = 1 - \cos^2\theta$
* $\cos^2\theta = 1 - \sin^2\theta$
### Summary: The Pythagorean Identity for Cosecant and Cotangent

In addition to the primary identity, we can derive further Pythagorean identities by dividing the fundamental identity $\sin^2\theta + \cos^2\theta = 1$ by other trigonometric functions. 

---
#### 1. Derivation of the Identity
To derive the identity involving cotangent and cosecant, we divide every term of the primary Pythagorean identity by $\sin^2\theta$:
$$\frac{\sin^2\theta}{\sin^2\theta} + \frac{\cos^2\theta}{\sin^2\theta} = \frac{1}{\sin^2\theta}$$

* **Simplification**:
    * $\frac{\sin^2\theta}{\sin^2\theta}$ simplifies to $1$.
    * $\frac{\cos^2\theta}{\sin^2\theta}$ simplifies to $\cot^2\theta$.
    * $\frac{1}{\sin^2\theta}$ simplifies to $\csc^2\theta$.

This yields the identity:
$$1 + \cot^2\theta = \csc^2\theta$$

---
#### 2. Corollaries
From this identity, we can rearrange the terms to create useful forms for substitution:
* $\cot^2\theta = \csc^2\theta - 1$
* $\csc^2\theta - \cot^2\theta = 1$
### Summary: The Pythagorean Identity for Tangent and Secant

In addition to the primary identity, we can derive further Pythagorean identities by dividing the fundamental identity $\sin^2\theta + \cos^2\theta = 1$ by other trigonometric functions.

---
#### 1. Derivation of the Identity
To derive the identity involving tangent and secant, we divide every term of the primary Pythagorean identity by $\cos^2\theta$:
$$\frac{\sin^2\theta}{\cos^2\theta} + \frac{\cos^2\theta}{\cos^2\theta} = \frac{1}{\cos^2\theta}$$


* **Simplification**:
    * $\frac{\sin^2\theta}{\cos^2\theta}$ simplifies to $\tan^2\theta$.
    * $\frac{\cos^2\theta}{\cos^2\theta}$ simplifies to $1$.
    * $\frac{1}{\cos^2\theta}$ simplifies to $\sec^2\theta$.

This yields the identity:
$$\tan^2\theta + 1 = \sec^2\theta$$

---
#### 2. Corollaries
From this identity, we can rearrange the terms to create useful forms for substitution:
* $\tan^2\theta = \sec^2\theta - 1$
* $\sec^2\theta - \tan^2\theta = 1$
### Simplifying Trigonometric Expressions

Following the methods for simplifying expressions using Pythagorean, reciprocal, and odd/even identities, here are the solutions:

---
#### 1. $\tan\left(-\frac{37\pi}{4}\right)$
* **Apply Odd Identity**: Tangent is odd, so $\tan(-\theta) = -\tan(\theta)$.
* **Reduce Angle**: The period of tangent is $\pi$. Divide $37$ by the denominator $4$ to find the remainder: $37 \div 4 = 9$ remainder $1$. 
* **Calculation**: $-\tan\left(\frac{\pi}{4}\right) = -(1) = \mathbf{-1}$.

---
#### 2. $\sin^2(40^\circ) + \cos^2(40^\circ)$
* **Apply Pythagorean Identity**: For any angle $\theta$, $\sin^2\theta + \cos^2\theta = 1$.
* **Result**: Since the angles match, the expression simplifies to **$1$**.

---
#### 3. $\sec^2(18^\circ) - \tan^2(18^\circ)$
* **Apply Pythagorean Identity Corollary**: We know $\tan^2\theta + 1 = \sec^2\theta$, which rearranges to $\sec^2\theta - \tan^2\theta = 1$.
* **Result**: Since the angles match, the expression simplifies to **$1$**.

---
#### 4. $\tan\left(\frac{\pi}{4}\right) - \frac{\sin\left(\frac{\pi}{4}\right)}{\cos\left(\frac{\pi}{4}\right)}$
* **Apply Quotient Identity**: Tangent is defined as $\frac{\sin\theta}{\cos\theta}$.
* **Substitution**: The expression becomes $\tan\left(\frac{\pi}{4}\right) - \tan\left(\frac{\pi}{4}\right)$.
* **Result**: Subtracting the same value from itself equals **$0$**.

---
#### 5. $\sin(\pi)\csc(\pi)$
* **Apply Reciprocal Identity**: Cosecant is the reciprocal of sine, $\csc\theta = \frac{1}{\sin\theta}$.
* **Substitution**: $\sin(\pi) \cdot \frac{1}{\sin(\pi)}$.
* **Result**: This simplifies to **$1$** (provided $\sin(\pi) \neq 0$; however, note that $\sin(\pi) = 0$, making $\csc(\pi)$ undefined).
### Simplifying Trigonometric Expressions

Following the techniques for simplifying expressions using reciprocal and odd/even identities, here are the solutions:

---
#### 1. $\sec\left(-\frac{\pi}{18}\right) \cos\left(\frac{37\pi}{18}\right)$
* **Simplify Angles**: 
    * Since secant is an even function, $\sec(-\theta) = \sec(\theta)$, so $\sec\left(-\frac{\pi}{18}\right) = \sec\left(\frac{\pi}{18}\right)$.
    * For $\cos\left(\frac{37\pi}{18}\right)$, the period is $2\pi$ ($36\pi/18$). Dividing $37$ by $36$ gives a remainder of $1$, so $\cos\left(\frac{37\pi}{18}\right) = \cos\left(\frac{\pi}{18}\right)$.
* **Calculate**: The expression becomes $\sec\left(\frac{\pi}{18}\right) \cdot \cos\left(\frac{\pi}{18}\right)$. Since $\sec\theta = \frac{1}{\cos\theta}$, this is $\frac{1}{\cos(\pi/18)} \cdot \cos(\pi/18) = \mathbf{1}$.

---
#### 2. $\frac{\sin(-20^\circ)}{\cos(380^\circ)} + \tan(20^\circ)$
* **Simplify Angles and Functions**:
    * Sine is an odd function, so $\sin(-20^\circ) = -\sin(20^\circ)$.
    * For $\cos(380^\circ)$, subtract the period of $360^\circ$ to get $\cos(20^\circ)$.
* **Calculate**: The expression becomes $\frac{-\sin(20^\circ)}{\cos(20^\circ)} + \tan(20^\circ)$.
    * Since $\frac{\sin\theta}{\cos\theta} = \tan\theta$, this is $-\tan(20^\circ) + \tan(20^\circ) = \mathbf{0}$.
## 18-June-2026 - The Graphs of Sine and Cosine (Precalculus - Trigonometry 11) :
https://www.youtube.com/watch?v=3HHgZopzL_s&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=85
### The Graphs of Sine and Cosine

This summary covers the fundamental properties, origins, and graphical characteristics of sine and cosine functions as presented by Professor Leonard.

---
#### 1. Fundamental Concept: Relating the Unit Circle to the Graph
The core challenge in graphing these functions is translating the unit circle into a Cartesian coordinate system.
* **Input (x-axis)**: The $x$ on the graph represents an angle or arc length on the unit circle (measured in radians). Because it is a unit circle, arc length equals central angle, allowing for real numbers to be mapped directly to angles.
* **Output (y-axis)**: The $y$ output is the value of the sine or cosine of that angle.
* **Key Distinction**: The $x$ on the graph is *not* the $x$-coordinate from the unit circle; it is the independent variable (angle/arc length).

---
#### 2. The Sine Graph ($y = \sin(x)$)
The sine function maps the angle to the $y$-coordinate on the unit circle. * **Domain & Range**: Domain is all real numbers $(-\infty, \infty)$; range is $[-1, 1]$.
* **Symmetry**: Odd function (symmetric about the origin).
* **Period**: $2\pi$.
* **Key Features**:
    * **X-intercepts**: Occur at the ends and the center of each period ($0, \pi, 2\pi, \dots$).
    * **Peaks**: Relative maximums and minimums occur at the quarters of the period ($\frac{\pi}{2}, \frac{3\pi}{2}$).

---
#### 3. The Cosine Graph ($y = \cos(x)$)
The cosine function maps the angle to the $x$-coordinate on the unit circle.
* **Domain & Range**: Domain is all real numbers; range is $[-1, 1]$.
* **Symmetry**: Even function (symmetric about the $y$-axis).
* **Period**: $2\pi$.
* **Key Features**:
    * **X-intercepts**: Occur at the quarters of the period ($\frac{\pi}{2}, \frac{3\pi}{2}$).
    * **Peaks**: Relative maximums/minimums occur at the ends and the center of the period ($0, \pi, 2\pi$).

---
#### 4. Summary of Graphing Strategy
When graphing transformations in the future, the following approach is recommended:
1.  **Identify the Period**: Adjust the scale based on the period.
2.  **Mark Key Points**:
    * **For Sine**: Plot x-intercepts at the ends and center; use the quarters for the amplitude peaks.
    * **For Cosine**: Plot x-intercepts at the quarters; use the ends and center for the amplitude peaks.
3.  **Apply Transformations**: Multiply key points by the amplitude to stretch, compress, or reflect the graph.

## 2026-June-19 - Graphing Transformations with Sine and Cosine (Precalculus - Trigonometry 12) :
https://www.youtube.com/watch?v=dyXT5KMCrPk&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=86
### Summary: Graphing Transformations with Sine and Cosine

This lecture outlines a systematic, five-step process for graphing transformations of sine and cosine functions. Professor Leonard emphasizes using a structured approach that applies the same logic to all trig functions, regardless of complexity.

---
#### 1. The General Graphing Steps
To graph $y = a \cdot \sin(\omega x) + k$ or $y = a \cdot \cos(\omega x) + k$ (excluding phase shifts for now), follow this order:

1.  **Find the Period ($T$):** The period is calculated by dividing the standard period ($2\pi$ for sine/cosine) by the coefficient $\omega$ in front of $x$ ($T = 2\pi / \omega$).
2.  **Vertical Shift ($k$):** Identify any constant added or subtracted at the end. This shifts the entire function up or down.
3.  **Graphic Organizer (The Shifted Axis):** If a vertical shift is present, draw a dotted horizontal line at $y = k$. Treat this line as your new "x-axis" for plotting.
4.  **Mark Period & Quarters:** Plot the period on the horizontal axis. Divide it into halves and quarters. These divisions locate where key features of the graph occur.
5.  **Plot Intercepts & Key Points:**
    * **Sine Intercepts:** Occur at the ends and center of the period.
    * **Cosine Intercepts:** Occur at the quarters of the period.
    * **Key Points (Peaks/Valleys):** Use the remaining marks not used as intercepts. Multiply original peak/valley values ($\pm 1$) by the amplitude $a$ to stretch, compress, or reflect the graph.

---
#### 2. Key Transformations Explained
* **Period Adjustment ($\omega$):** Multiplying the input by $\omega$ causes horizontal compression (if $\omega > 1$) or stretching (if $\omega < 1$).
* **Amplitude ($a$):** The coefficient $a$ stretches or compresses the output. If $a$ is negative, it reflects the graph across the shifted axis.
* **Handling Negative Arguments**: 
    * Never divide the period by a negative $\omega$. 
    * Use **Even/Odd identities** first: For sine (odd), pull the negative out as a coefficient; for cosine (even), the negative disappears within the function.

---
#### 3. Important Considerations
* **Graphic Organizer Utility**: Drawing a dotted line at the vertical shift $k$ and marking the period divisions in relation to it is the most reliable way to avoid errors when plotting.
* **Phase Shifts**: Note that this lecture excludes horizontal phase shifts ($x - h$), which will be addressed in future lessons.
* **Graphing Multiple Cycles**: To graph more than one period, extend the horizontal axis and continue the pattern by adding the period $T$ to the existing key points.
### y = 3sin(x)

To graph $y = 3\sin(x)$, follow the structured process used by Professor Leonard.
* **Step 1: Find the Period**
    * The original period for sine is $2\pi$.
    * You divide the standard period by the number multiplied by $x$ (the coefficient $\omega$).
    * In this case, $\omega = 1$, so the period is $2\pi / 1 = 2\pi$.
    * Mark this period on your x-axis.
* **Step 2: Divide the Period**
    * After marking the period ($2\pi$), cut it in half to get $\pi$.
    * Cut each of those sections in half to create the quarters of your period: $\pi/2$ (first quarter) and $3\pi/2$ (third quarter).
* **Step 3: Identify Intercepts**
    * Sine functions have x-intercepts at the ends and the center of the period.
    * For this graph, place points at $0$, $\pi$, and $2\pi$.
* **Step 4: Determine Key Points**
    * The key points (peaks and valleys) occur at the quarters of the period that are not x-intercepts.
    * The original sine key points are $(\pi/2, 1)$ and $(3\pi/2, -1)$.
    * Since $a = 3$, you multiply these outputs by $3$ to determine your new key points.
    * The new key points are $(\pi/2, 3)$ and $(3\pi/2, -3)$.
* **Step 5: Plot and Graph**
    * Plot the intercepts and the transformed key points.
    * The amplitude of $3$ vertically stretches the original sine graph, showing how high the peak goes above the x-axis and how low the valley goes.
### y = -4cos(x)

To graph $y = -4\cos(x)$, follow this step-by-step process:

* **Step 1: Find the Period**
    * The standard period of a cosine function is $2\pi$.
    * Divide $2\pi$ by the coefficient $\omega$ (the number in front of $x$). Since $\omega = 1$, the period is $2\pi / 1 = 2\pi$.
    * Mark $2\pi$ on your x-axis.
* **Step 2: Divide the Period**
    * Cut the period ($2\pi$) in half to get $\pi$.
    * Cut each section in half again to find the quarters: $\pi/2$ (first quarter) and $3\pi/2$ (third quarter).
* **Step 3: Identify Intercepts**
    * Cosine functions have x-intercepts at the quarters of the period.
    * Mark points at $\pi/2$ and $3\pi/2$.
* **Step 4: Determine Key Points**
    * The key points (peaks and valleys) occur at the ends and the center of the period ($0, \pi, 2\pi$).
    * Originally, cosine has peaks/valleys at $1, -1, 1$.
    * Multiply these original outputs by your amplitude coefficient, $a = -4$.
    * New key points:
        * $0 \cdot (-4) \rightarrow (0, -4)$
        * $-1 \cdot (-4) \rightarrow (\pi, 4)$
        * $1 \cdot (-4) \rightarrow (2\pi, -4)$
* **Step 5: Plot and Graph**
    * The negative sign reflects the graph, turning what would have been a peak into a valley, and vice versa. The $4$ stretches the graph vertically by a factor of $4$.
    * Plot the intercepts and the transformed key points to complete the cycle.
### y = sin(3x)
To graph $y = \sin(3x)$, follow the structured process used by Professor Leonard.
* **Step 1: Find the Period**
    * The original period for sine is $2\pi$.
    * You divide the standard period by the coefficient of $x$ ($\omega = 3$).
    * The period is $2\pi / 3$. Mark this value on your x-axis.
* **Step 2: Divide the Period**
    * Take the period ($2\pi / 3$) and cut it in half to get $\pi / 3$.
    * Cut each section in half again to find the quarter points:
        * First quarter: $(\pi/3) / 2 = \pi / 6$
        * Third quarter: $(\pi/6) + (\pi/3) = 3\pi / 6 = \pi / 2$
* **Step 3: Identify Intercepts**
    * Sine functions have x-intercepts at the ends ($0$ and $2\pi/3$) and the center ($\pi/3$) of the period.
    * Place these three points on your graph.
* **Step 4: Determine Key Points**
    * The key points (peaks and valleys) occur at the quarters of the period that are not x-intercepts.
    * The original sine key points are $(\text{first quarter}, 1)$ and $(\text{third quarter}, -1)$.
    * These points are $(\pi/6, 1)$ and $(\pi/2, -1)$.
    * There is no vertical stretch/amplitude change (a = 1), so these points remain as identified.
* **Step 5: Plot and Graph**
    * The coefficient of $3$ inside the argument creates a horizontal compression, making the sine wave repeat more frequently than the standard sine graph.
    * Plot the intercepts and the key points to complete the cycle.
### y = cos(-2x)

To graph $y = \cos(-2x)$, we use Professor Leonard's methodology, incorporating the specific property that cosine is an even function.
* **Step 1: Simplify using Even Function Property**
    * Since cosine is an even function, $\cos(-\theta) = \cos(\theta)$.
    * Therefore, we rewrite the function as: $y = \cos(2x)$. This avoids the issues of trying to divide by a negative number.
* **Step 2: Find the Period**
    * The standard period for cosine is $2\pi$.
    * Divide $2\pi$ by the coefficient $\omega = 2$.
    * The period is $2\pi / 2 = \pi$. Mark $\pi$ on your x-axis.
* **Step 3: Divide the Period**
    * Cut the period ($\pi$) in half to get $\pi/2$.
    * Cut each section in half again to find the quarter points:
        * First quarter: $(\pi/2) / 2 = \pi/4$
        * Third quarter: $(\pi/4) + (\pi/2) = 3\pi/4$
* **Step 4: Identify Intercepts**
    * Cosine functions have x-intercepts at the quarter points.
    * Place points at $\pi/4$ and $3\pi/4$.
* **Step 5: Determine Key Points**
    * Key points (peaks and valleys) occur at the ends and the center of the period ($0, \pi/2, \pi$).
    * The original cosine pattern is peak ($1$), valley ($-1$), peak ($1$).
    * There is no amplitude change, so the key points are $(0, 1)$, $(\pi/2, -1)$, and $(\pi, 1)$.
* **Step 6: Plot and Graph**
    * Plot the intercepts and key points. The transformation shows a horizontal compression compared to the parent cosine function.
### y = -sin(x/8)

To graph $y = -\sin(x/8)$, follow the structured process used by Professor Leonard.
* **Step 1: Find the Period**
    * The original period for sine is $2\pi$.
    * Divide $2\pi$ by the coefficient of $x$ ($\omega = 1/8$).
    * The period is $2\pi / (1/8) = 16\pi$. Mark $16\pi$ on your x-axis.
* **Step 2: Divide the Period**
    * Take the period ($16\pi$) and cut it in half to get $8\pi$.
    * Cut each section in half again to find the quarter points:
        * First quarter: $4\pi$
        * Third quarter: $4\pi + 8\pi = 12\pi$
* **Step 3: Identify Intercepts**
    * Sine functions have x-intercepts at the ends ($0$ and $16\pi$) and the center ($8\pi$) of the period.
    * Place these three points on your graph.
* **Step 4: Determine Key Points**
    * The key points (peaks and valleys) occur at the quarters of the period that are not x-intercepts.
    * Originally, sine has a peak ($1$) at the first quarter and a valley ($-1$) at the third quarter.
    * Because of the coefficient $-1$ (the negative sign), the outputs are multiplied by $-1$:
        * First quarter point: $(4\pi, -1)$
        * Third quarter point: $(12\pi, 1)$
* **Step 5: Plot and Graph**
    * The coefficient $1/8$ causes a horizontal stretch, making the wave appear much wider. 
    * The negative sign reflects the graph across the x-axis, turning the standard sine curve upside down.
    * Plot the intercepts and the reflected key points to complete the cycle.
### y = 3cos(4x) + 1

To graph $y = 3\cos(4x) + 1$, follow the step-by-step process used by Professor Leonard:

* **Step 1: Find the Period**
    * The original period for cosine is $2\pi$.
    * Divide $2\pi$ by the coefficient of $x$ ($\omega = 4$).
    * The period is $2\pi / 4 = \pi/2$. 
* **Step 2: Account for Vertical Shift**
    * The $+1$ at the end indicates a vertical shift up $1$ unit.
    * Draw a dotted horizontal line at $y = 1$. This line serves as your "new x-axis" (a graphic organizer) to plot your points.
* **Step 3: Mark Period and Quarters**
    * Place the period ($\pi/2$) on your x-axis (and along the dotted line).
    * Divide the period into quarters:
        * Half of the period: $\pi/4$
        * First quarter: $\pi/8$
        * Third quarter: $3\pi/8$
* **Step 4: Identify Intercepts**
    * For cosine, the x-intercepts (relative to the shifted axis) occur at the quarters of the period.
    * Place points on your dotted line at $\pi/8$ and $3\pi/8$.
* **Step 5: Determine Key Points**
    * The key points for cosine (peaks and valleys) occur at the ends ($0, \pi/2$) and the center ($\pi/4$) of the period.
    * The original cosine values are peak ($1$), valley ($-1$), peak ($1$).
    * Multiply these values by the amplitude ($a = 3$):
        * At $x = 0$: $1 \cdot 3 = 3$. Add the vertical shift ($+1$), so the point is $(0, 4)$.
        * At $x = \pi/4$: $-1 \cdot 3 = -3$. Add the vertical shift ($+1$), so the point is $(\pi/4, -2)$.
        * At $x = \pi/2$: $1 \cdot 3 = 3$. Add the vertical shift ($+1$), so the point is $(\pi/2, 4)$.
* **Step 6: Plot and Graph**
    * Plot these key points relative to your shifted axis ($y=1$).
    * The graph shows a horizontal compression due to the $4x$ and a vertical stretch/shift due to the $3\cos(x) + 1$.
### y = 4sin((π/2)x) - 2
To graph $y = 4\sin(\frac{\pi}{2}x) - 2$, follow the systematic process used by Professor Leonard:
* **Step 1: Find the Period**
    * The standard period for sine is $2\pi$. 
    * Divide $2\pi$ by the coefficient $\omega = \pi/2$.
    * $2\pi \div (\pi/2) = 2\pi \cdot (2/\pi) = 4$.
    * The period is $4$.
* **Step 2: Account for Vertical Shift**
    * The $-2$ at the end indicates a vertical shift down $2$ units.
    * Draw a dashed horizontal line at $y = -2$. This serves as your new "x-axis" (graphic organizer) for the graph.
* **Step 3: Mark Period and Quarters**
    * Plot the period ($4$) on the horizontal axis.
    * Divide the period into quarters:
        * Half of the period: $2$
        * First quarter: $1$
        * Third quarter: $3$
* **Step 4: Identify Intercepts**
    * Sine functions have x-intercepts at the ends ($0, 4$) and center ($2$) of the period.
    * Relative to your shifted axis ($y = -2$), plot points at $x = 0, 2, 4$ along that line.
* **Step 5: Determine Key Points**
    * The key points (peaks and valleys) occur at the quarters of the period ($1, 3$).
    * The original sine key points are $1$ and $-1$.
    * Multiply these by the amplitude $a = 4$:
        * First quarter: $1 \cdot 4 = 4$. Adjust for vertical shift: $4 - 2 = 2$. Point: $(1, 2)$.
        * Third quarter: $-1 \cdot 4 = -4$. Adjust for vertical shift: $-4 - 2 = -6$. Point: $(3, -6)$.
* **Step 6: Plot and Graph**
    * Plot the intercepts at $(0, -2), (2, -2), (4, -2)$ and the key points at $(1, 2)$ and $(3, -6)$.
    * The graph shows a horizontal stretch (period increased to 4), a vertical stretch (amplitude 4), and a vertical shift down 2.
### y = -3cos((π/4)x) + 2

To graph $y = -3\cos(\frac{\pi}{4}x) + 2$, follow the systematic process used by Professor Leonard:
* **Step 1: Find the Period**
    * The standard period for cosine is $2\pi$.
    * Divide $2\pi$ by the coefficient $\omega = \pi/4$.
    * $2\pi \div (\pi/4) = 2\pi \cdot (4/\pi) = 8$.
    * The period is $8$.
* **Step 2: Account for Vertical Shift**
    * The $+2$ at the end indicates a vertical shift up $2$ units.
    * Draw a dashed horizontal line at $y = 2$. This line acts as your new "x-axis" (a graphic organizer) for plotting the rest of your points.
* **Step 3: Mark Period and Quarters**
    * Plot the period ($8$) on the horizontal axis.
    * Divide the period into quarters:
        * Half of the period: $4$
        * First quarter: $2$
        * Third quarter: $6$
* **Step 4: Identify Intercepts**
    * Cosine functions have x-intercepts at the quarters of the period.
    * Relative to your shifted axis ($y = 2$), plot points at $x = 2$ and $x = 6$ along that line.
* **Step 5: Determine Key Points**
    * The key points (peaks and valleys) occur at the ends ($0, 8$) and center ($4$) of the period.
    * The original cosine values are peak ($1$), valley ($-1$), peak ($1$).
    * Multiply these by the amplitude $a = -3$:
        * At $x = 0$: $1 \cdot (-3) = -3$. Adjust for vertical shift: $-3 + 2 = -1$. Point: $(0, -1)$.
        * At $x = 4$: $-1 \cdot (-3) = 3$. Adjust for vertical shift: $3 + 2 = 5$. Point: $(4, 5)$.
        * At $x = 8$: $1 \cdot (-3) = -3$. Adjust for vertical shift: $-3 + 2 = -1$. Point: $(8, -1)$.
* **Step 6: Plot and Graph**
    * Plot the intercepts at $(2, 2)$ and $(6, 2)$ and the key points at $(0, -1), (4, 5),$ and $(8, -1)$.
    * The graph shows a horizontal stretch (period increased to 8), a vertical stretch (amplitude 3), a vertical reflection (due to the negative sign), and a vertical shift up 2.
## 2026-June-20 - How to Graph Tangent and Cotangent (Precalculus - Trigonometry 13) :
https://www.youtube.com/watch?v=8eMEBrPYJ0I&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=88
### Graphing Tangent and Cotangent

This summary covers the foundational concepts for graphing tangent and cotangent functions, emphasizing how to identify their behavior before applying transformations.
* **Tangent Function ($y = \tan(x)$)**
    * **Origin:** Derived from the unit circle ratio $y/x$.
    * **Period:** The period is $\pi$. Unlike sine and cosine which repeat every $2\pi$, tangent repeats every $\pi$ because the ratio $y/x$ yields the same values in alternating quadrants (e.g., Q1 and Q3 have positive results; Q2 and Q4 have negative results).
    * **X-Intercepts:** Occur at $0 + k\pi$. The intercept is at the origin $(0,0)$ and repeats every $\pi$.
    * **Vertical Asymptotes:** Occur where the denominator $x=0$ on the unit circle (at $\pi/2 + k\pi$). These asymptotes create domain restrictions: all real numbers except $\pi/2 + k\pi$.
    * **Range:** $(-\infty, \infty)$.
    * **Shape:** An "S-curve" symmetric about the origin (an odd function).
    * **Key Points on One Period (e.g., $-\pi/2$ to $\pi/2$):**
        * Ends: Vertical Asymptotes.
        * Center: X-intercept $(0,0)$.
        * First Quarter: $(-1)$.
        * Third Quarter: $(1)$.
* **Cotangent Function ($y = \cot(x)$)**
    * **Origin:** The reciprocal ratio $x/y$.
    * **Period:** Also $\pi$.
    * **X-Intercepts & Asymptotes:** These are effectively "swapped" compared to tangent because cotangent is the reciprocal.
        * Vertical Asymptotes: Occur where $y=0$ (at $0 + k\pi$).
        * X-Intercepts: Occur where the tangent function has asymptotes (at $\pi/2 + k\pi$).
    * **Range:** $(-\infty, \infty)$.
    * **Key Points on One Period (e.g., $0$ to $\pi$):**
        * Ends: Vertical Asymptotes.
        * Center: X-intercept $(\pi/2, 0)$.
        * First Quarter: $(1)$.
        * Third Quarter: $(-1)$.
* **Transformation Strategy (Preview)**
    * To graph transformed versions, identify the period first.
    * For tangent, the base cycle is typically viewed on $[-\pi/2, \pi/2]$.
    * For cotangent, the base cycle is typically viewed on $[0, \pi]$.
    * Always place vertical asymptotes at the ends of the period, the intercept at the center, and use the quarter-period points to determine the vertical stretch or reflection.
## 2026-June-16 - Graphing Transformations with Tangent and Cotangent (Precalculus - Trigonometry 14) : 
https://www.youtube.com/watch?v=i4rr_J1VbkY&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=88
### Graphing Transformations with Tangent and Cotangent

To graph transformed tangent and cotangent functions, Professor Leonard recommends a systematic approach similar to sine/cosine graphing.
* **Core Principles**
    * **Vertical Shift ($b$):** The constant added/subtracted after the function ($y = a \cdot \text{trig}(...x) + b$). This moves the entire graph up or down.
    * **Period:** * Formula: $\text{Period} = \pi / \omega$ (where $\omega$ is the coefficient of $x$).
        * Tangent: Centered at $0$. Divide the period by $2$ and go that distance to the left and right of $0$.
        * Cotangent: Starts at $0$. Go a full period to the right.
    * **Vertical Stretch/Compression/Reflection:** The coefficient '$a$' multiplies the outputs of the key points. If negative, it reflects the graph.
* **Step-by-Step Graphing Method**
    1.  **Identify Vertical Shift:** If present, draw a dashed horizontal line at $y = b$. This serves as a "new x-axis" (graphic organizer).
    2.  **Determine Period:** Calculate $\pi / \omega$. Mark the start and end of the period on the horizontal axis.
    3.  **Find Key Features:**
        * Divide the period into quarters to identify the First Quarter, Center, and Third Quarter.
        * Vertical Asymptotes: Always at the ends of the period.
        * X-Intercept: At the center of the period (plot on the dashed vertical shift line).
    4.  **Calculate Transformed Key Points:**
        * Tangent: First Quarter $(-1)$, Third Quarter $(1)$.
        * Cotangent: First Quarter $(1)$, Third Quarter $(-1)$.
        * Multiply these base values by '$a$' and adjust for the vertical shift ($+b$).
    5.  **Plot and Repeat:** Place key points and sketch the "S-curve" (tangent) or reflected curve (cotangent). Use the calculated period to draw additional cycles.
* **Summary Table**

| Feature | Tangent ($\tan x$) | Cotangent ($\cot x$) |
| :--- | :--- | :--- |
| **Period** | $\pi$ | $\pi$ |
| **Center of Period** | $0$ (Shifted if necessary) | $0$ to $\pi$ |
| **First Quarter Key Point** | $-1 \rightarrow (-a + b)$ | $1 \rightarrow (a + b)$ |
| **Third Quarter Key Point** | $1 \rightarrow (a + b)$ | $-1 \rightarrow (-a + b)$ |
| **Asymptote Location** | Ends of period | Ends of period |
### y = 3tan(x)

To graph $y = 3\tan(x)$, follow the structured methodology taught by Professor Leonard:

* **Step 1: Identify Vertical Shift**
    * There is no number added or subtracted outside the function. The vertical shift is $0$. The graph remains centered on the x-axis.
* **Step 2: Find the Period**
    * Tangent has a standard period of $\pi$.
    * With $\omega = 1$, the period is $\pi / 1 = \pi$.
    * Because tangent is centered at $0$, the period spans from $-\pi/2$ to $\pi/2$.
* **Step 3: Mark Period and Quarters**
    * **Vertical Asymptotes:** Occur at the ends of the period ($x = -\pi/2$ and $x = \pi/2$).
    * **X-intercept:** Occurs at the center of the period ($x = 0$).
    * **Quarters:** The halfway point between the center and the asymptotes are the quarter points ($x = -\pi/4$ and $x = \pi/4$).
* **Step 4: Determine Key Points**
    * Tangent's original key points are:
        * First Quarter: $(-\pi/4, -1)$
        * Third Quarter: $(\pi/4, 1)$
    * Since $a = 3$, multiply the output values by $3$:
        * First Quarter point: $(-\pi/4, -3)$
        * Third Quarter point: $(\pi/4, 3)$
* **Step 5: Plot and Graph**
    * Sketch the vertical asymptotes at $x = -\pi/2$ and $x = \pi/2$.
    * Plot the x-intercept at $(0, 0)$.
    * Plot the transformed key points at $(-\pi/4, -3)$ and $(\pi/4, 3)$.
    * Draw the S-curve passing through these points. The graph is vertically stretched compared to the standard tangent function.
### y = -2tan(3x) + 1

To graph $y = -2\tan(3x) + 1$, follow Professor Leonard’s systematic transformation process:

* **Step 1: Identify Vertical Shift**
    * The $+1$ indicates a vertical shift up $1$ unit.
    * Draw a dashed horizontal line at $y = 1$. This acts as your new baseline/graphic organizer.
* **Step 2: Find the Period**
    * The period of a tangent function is $\pi / \omega$. Here, $\omega = 3$.
    * Period = $\pi/3$.
    * Since tangent is centered at $0$ (no phase shift), divide the period by $2$ to find the bounds:
        * Right bound: $(\pi/3) \div 2 = \pi/6$
        * Left bound: $-\pi/6$
* **Step 3: Mark Period and Quarters**
    * **Vertical Asymptotes:** Occur at the ends of the period ($x = -\pi/6$ and $x = \pi/6$).
    * **X-intercept:** Occurs at the center ($x = 0$). Plot this on your dashed line at $(0, 1)$.
    * **Quarters:** The halfway points between the center and the asymptotes ($x = -\pi/12$ and $x = \pi/12$).
* **Step 4: Determine Key Points**
    * Standard tangent key points are: First Quarter $(-1)$, Third Quarter $(1)$.
    * Apply the multiplier $a = -2$ (which stretches and reflects):
        * First Quarter point: $(-1) \cdot (-2) = 2$. Add vertical shift: $2 + 1 = 3$. Point: $(-\pi/12, 3)$.
        * Third Quarter point: $(1) \cdot (-2) = -2$. Add vertical shift: $-2 + 1 = -1$. Point: $(\pi/12, -1)$.
* **Step 5: Plot and Graph**
    * Sketch vertical asymptotes at $x = -\pi/6$ and $x = \pi/6$.
    * Plot the center point at $(0, 1)$.
    * Plot the key points at $(-\pi/12, 3)$ and $(\pi/12, -1)$.
    * Draw the curve. Note that the negative coefficient reflects the graph, making it decrease rather than climb.
### y = 3cot(1/2 x) - 2

To graph $y = 3\cot(1/2 x) - 2$, follow Professor Leonard’s structured method for cotangent transformations:

* **Step 1: Identify Vertical Shift**
    * The $-2$ indicates a vertical shift down $2$ units.
    * Draw a dashed horizontal line at $y = -2$. This line serves as your graphic organizer, where the x-intercept will effectively be located.
* **Step 2: Find the Period**
    * The period of a cotangent function is $\pi / \omega$. Here, $\omega = 1/2$.
    * Period = $\pi \div (1/2) = 2\pi$.
    * Unlike tangent, cotangent starts at $0$. Therefore, the period spans from $x = 0$ to $x = 2\pi$.
* **Step 3: Mark Period and Quarters**
    * **Vertical Asymptotes:** Occur at the ends of the period ($x = 0$ and $x = 2\pi$).
    * **Center of Period:** $x = \pi$.
    * **Quarters:** The halfway points between the center and the asymptotes ($x = \pi/2$ and $x = 3\pi/2$).
* **Step 4: Determine Key Points**
    * Standard cotangent key points are: First Quarter $(1)$, Third Quarter $(-1)$.
    * Apply the multiplier $a = 3$ (vertical stretch):
        * First Quarter point: $(1) \cdot 3 = 3$. Add vertical shift: $3 - 2 = 1$. Point: $(\pi/2, 1)$.
        * Third Quarter point: $(-1) \cdot 3 = -3$. Add vertical shift: $-3 - 2 = -5$. Point: $(3\pi/2, -5)$.
    * The x-intercept (center) is at $(\pi, -2)$.
* **Step 5: Plot and Graph**
    * Sketch vertical asymptotes at $x = 0$ and $x = 2\pi$.
    * Plot the center point on the dashed line at $(\pi, -2)$.
    * Plot the key points at $(\pi/2, 1)$ and $(3\pi/2, -5)$.
    * Draw the decreasing cotangent curve through these points. The horizontal stretch (due to the $1/2$ coefficient) makes the graph wider than the standard cotangent function.
### y = -cot((π/4)x) + 1

To graph $y = -\cot(\frac{\pi}{4}x) + 1$, follow Professor Leonard’s systematic process for cotangent transformations:

* **Step 1: Identify Vertical Shift**
    * The $+1$ indicates a vertical shift up $1$ unit.
    * Draw a dashed horizontal line at $y = 1$. This acts as your "new x-axis" or baseline for plotting key points and intercepts.
* **Step 2: Find the Period**
    * The standard period of a cotangent function is $\pi$.
    * Use the formula: $\text{Period} = \pi / \omega$. Here, $\omega = \pi/4$.
    * $\text{Period} = \pi \div (\pi/4) = \pi \cdot (4/\pi) = 4$.
    * Cotangent is not centered at $0$; it starts at $0$. Therefore, the period spans from $x = 0$ to $x = 4$.
* **Step 3: Mark Period and Quarters**
    * **Vertical Asymptotes:** Occur at the start and end of the period ($x = 0$ and $x = 4$).
    * **Center of Period:** $x = 2$.
    * **Quarters:** The halfway points between the center and the asymptotes are $x = 1$ and $x = 3$.
* **Step 4: Determine Key Points**
    * Standard cotangent key points are: First Quarter $(1)$, Third Quarter $(-1)$.
    * Apply the multiplier $a = -1$ (which reflects the graph):
        * First Quarter point: $(1) \cdot (-1) = -1$. Add vertical shift: $-1 + 1 = 0$. Point: $(1, 0)$.
        * Third Quarter point: $(-1) \cdot (-1) = 1$. Add vertical shift: $1 + 1 = 2$. Point: $(3, 2)$.
    * The x-intercept (center) is at $(2, 1)$, plotted on the dashed baseline.
* **Step 5: Plot and Graph**
    * Sketch vertical asymptotes at $x = 0$ and $x = 4$.
    * Plot the center point at $(2, 1)$.
    * Plot the transformed key points at $(1, 0)$ and $(3, 2)$.
    * Draw the curve. The negative coefficient reflects the function, causing it to climb rather than decrease, resembling a tangent-like curve in orientation, but maintaining the cotangent's starting position.
## 2026-June-23 - How to Graph Cosecant and Secant (Precalculus - Trigonometry 15) :
https://www.youtube.com/watch?v=kYIKNTXaf_E&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=91
### Graphing Cosecant and Secant Transformations

Professor Leonard’s primary strategy is to graph the reciprocal function (sine for cosecant, cosine for secant) first, using a dashed line, and then use that as a guide to construct the target graph.
* **Core Principles**
    * **Reciprocal Relationship:**
        * $\csc(x) = 1 / \sin(x)$
        * $\sec(x) = 1 / \cos(x)$
    * **Vertical Asymptotes:** Occur at every point where the base sine or cosine function has an x-intercept (where the function equals $0$).
    * **Points of Intersection:** The graphs of $\csc(x)$ and $\sec(x)$ touch their base functions at their local maxima ($1$) and local minima ($-1$).
    * **Range:** $(-\infty, -1] \cup [1, \infty)$ (for standard functions).
* **Step-by-Step Graphing Method**
    1. **Identify Base Function:** Determine if you need to graph sine (for cosecant) or cosine (for secant).
    2. **Graph Transformations on the Base:**
        * Apply vertical shifts, period adjustments ($2\pi / \omega$), and vertical stretches/reflections to the base sine or cosine function. 
        * *Tip:* Always draw this base function as a dashed line.
    3. **Construct Reciprocal Features:**
        * **Vertical Asymptotes:** Draw vertical dashed lines through every x-intercept of the base function.
        * **Local Max/Min:** Place points on the base function's peaks and valleys. These are the "vertex" points where the cosecant/secant curves turn.
    4. **Sketch the Curves:** Draw "U-shaped" branches opening upward from the base function's maxima and downward from the base function's minima, approaching the vertical asymptotes.
* **Summary Table**

| Feature | Cosecant ($\csc x$) | Secant ($\sec x$) |
| :--- | :--- | :--- |
| **Base Function** | Sine ($\sin x$) | Cosine ($\cos x$) |
| **Period** | $2\pi$ | $2\pi$ |
| **Asymptotes at x-intercepts of:** | Sine ($0, \pm\pi, \pm 2\pi, \dots$) | Cosine ($\pm\pi/2, \pm 3\pi/2, \dots$) |
| **Range** | $(-\infty, -1] \cup [1, \infty)$ | $(-\infty, -1] \cup [1, \infty)$ |

### y = 4sec(1/2 x)

To graph $y = 4\sec(\frac{1}{2}x)$ using Professor Leonard’s methodology, you must first convert the function to its reciprocal base to use as a guide. Since $\sec(x) = 1/\cos(x)$, we will graph $y = 4\cos(\frac{1}{2}x)$ first.

* **Step 1: Identify Vertical Shift**
    * There is no vertical shift (no constant added/subtracted). The baseline remains the x-axis ($y = 0$).
* **Step 2: Find the Period**
    * The base period for cosine is $2\pi$.
    * Use the formula: $\text{Period} = 2\pi / \omega$. Here, $\omega = 1/2$.
    * $\text{Period} = 2\pi \div (1/2) = 4\pi$.
    * *Recommendation:* Draw at least one full period ($0$ to $4\pi$) and half a period to the left ($-2\pi$ to $0$) to ensure you have a complete view of the secant branches.
* **Step 3: Sketch the Base (Cosine) Function**
    * Use a dashed line to graph $y = 4\cos(\frac{1}{2}x)$.
    * **Key Points for Cosine:**
        * Start (0): $(0, 4)$
        * First Quarter: $(\pi, 0)$ [x-intercept]
        * Middle: $(2\pi, -4)$
        * Third Quarter: $(3\pi, 0)$ [x-intercept]
        * End: $(4\pi, 4)$
* **Step 4: Construct Secant Features**
    * **Vertical Asymptotes:** Draw dashed vertical lines through every x-intercept of the base cosine function ($x = \pi, 3\pi, -\pi, -3\pi, \dots$).
    * **Turning Points:** Use the peaks and valleys of the cosine function.
        * From the peak at $(0, 4)$, draw a "U-shaped" branch opening upward.
        * From the valley at $(2\pi, -4)$, draw a "U-shaped" branch opening downward.
        * From the peak at $(-2\pi, 4)$, draw a branch opening upward.
* **Step 5: Final Graph**
    * The solid lines representing the secant function will exist in the regions defined by the asymptotes, approaching infinity as they near $x = \pm\pi, \pm3\pi, \dots$.
### y = -2csc((2π/3)x) - 2

To graph $y = -2\csc(\frac{2\pi}{3}x) - 2$, follow Professor Leonard’s methodology by first graphing the reciprocal sine function.
* **Step 1: Identify Vertical Shift**
    * The $-2$ indicates a vertical shift down $2$ units.
    * Draw a dashed horizontal line at $y = -2$. This serves as your "new x-axis" (graphic organizer) for the base sine function.
* **Step 2: Find the Period**
    * The period for a sine/cosecant function is $2\pi / \omega$. Here, $\omega = \frac{2\pi}{3}$.
    * Period = $2\pi \div (\frac{2\pi}{3}) = 2\pi \cdot (\frac{3}{2\pi}) = 3$.
    * Note: The period is $3$. You can graph multiple cycles (e.g., $0$ to $3$, $3$ to $6$).
* **Step 3: Sketch the Base (Sine) Function**
    * Graph $y = -2\sin(\frac{2\pi}{3}x) - 2$ as a dashed line.
    * **Key Features:**
        * X-intercepts (relative to the shift): Occur at the start ($x=0$), middle ($x=1.5$), and end ($x=3$) of the period. Plot these on the $y = -2$ line.
        * Quarter Points:
            * First Quarter ($x = 0.75$): Originally at $1$. Apply multiplier $a = -2$ and shift $-2$. Point: $(0.75, 1 \cdot -2 - 2) = (0.75, -4)$.
            * Third Quarter ($x = 2.25$): Originally at $-1$. Apply multiplier $a = -2$ and shift $-2$. Point: $(2.25, -1 \cdot -2 - 2) = (2.25, 0)$.
* **Step 4: Construct Cosecant Features**
    * **Vertical Asymptotes:** Draw vertical dashed lines through every "x-intercept" of your base sine function ($x = 0, 1.5, 3, \dots$).
    * **Turning Points:** Use the peaks and valleys of the sine graph:
        * From the local maximum at $(2.25, 0)$, draw a "U-shaped" branch opening upward.
        * From the local minimum at $(0.75, -4)$, draw a "U-shaped" branch opening downward.
* **Step 5: Final Graph**
    * The solid cosecant curves exist between the asymptotes, bouncing off the local extrema of the sine wave.
## 2026-June-24 - How to Graph Phase Shifts of Trigonometric Functions (Precalculus - Trigonometry 16) :
https://www.youtube.com/watch?v=bE5PFI-ibT8&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=91
### Graphing Trigonometric Phase Shifts

Professor Leonard emphasizes a structured, step-by-step approach to graphing trigonometric functions that include horizontal (phase) shifts. The key is ensuring the function is in the "proper form" before beginning any graphing steps.
* **Crucial Prerequisite: Proper Form**
    * Before graphing, you **must** factor out the coefficient of $x$ to make its coefficient $1$.
    * Example: $y = 3\sin(2x - \pi)$ becomes $y = 3\sin(2(x - \pi/2))$.
    * This reveals the actual phase shift. If the coefficient of $x$ is not $1$, your identification of the phase shift and period will be incorrect.
* **Step-by-Step Graphing Methodology**
    1. **Vertical Shift:** Identify any constant added or subtracted at the very end of the function. Draw a dashed horizontal line at this $y$-value to serve as your "new x-axis."
    2. **Phase Shift:** Identify the shift inside the parentheses.
        * Remember: The shift is **opposite** of the sign shown (e.g., $(x - \pi/2)$ is a shift **right** by $\pi/2$).
    3. **Find the Period:** Calculate the period using the formula $\text{Period} = (\text{original period}) / \omega$.
        * Sine/Cosine: $2\pi / \omega$
        * Tangent: $\pi / \omega$
    4. **Determine Cycle Boundaries:** Add the period to the phase shift to find where the first period ends. 
    5. **Find Key Points:** Identify the center and quarter points of the period. Use your knowledge of the base function (sine/cosine/tangent) to plot these points relative to your shifted axes. Apply any amplitude (vertical stretch) or reflection factors.
* **Special Considerations**
    * **Odd/Even Functions:** If a negative coefficient exists inside the argument (e.g., $\sin(-2x + \dots)$), use the function's property to simplify:
        * **Sine (Odd):** $\sin(-x) = -\sin(x)$. You can pull the negative out front (reflecting the graph).
        * **Cosine (Even):** $\cos(-x) = \cos(x)$. You can simply drop the negative inside (no reflection).
    * **Calculations:** Don't hesitate to use a calculator for the fractions involved in finding center/quarter points, but keep $\pi$ in the expression.
* **Summary of Transformation Priorities**
    * Vertical shift first (sets the baseline).
    * Phase shift second (sets the starting point on the x-axis).
    * Period calculation third (sets the horizontal span).
    * Key points last (plotting the shape based on the base function).
### y = 3sin(2x - π)

To graph $y = 3\sin(2x - \pi)$ using Professor Leonard's methodology, follow these steps to ensure the transformations are accurate:
* **Step 1: Put into Proper Form**
    * Before identifying shifts, factor the coefficient of $x$ out of the argument.
    * $y = 3\sin(2(x - \pi/2))$
    * This reveals the transformations:
        * **Amplitude:** $3$ (Vertical stretch)
        * **$\omega$:** $2$
        * **Phase Shift:** $\pi/2$ to the **right** (opposite of the negative sign).
* **Step 2: Identify Transformations**
    * **Vertical Shift:** None ($0$).
    * **Phase Shift:** $\pi/2$ (Right).
    * **Period:** $\text{Period} = 2\pi / \omega = 2\pi / 2 = \pi$.
* **Step 3: Graphing Setup**
    * The period is $\pi$. The cycle starts at the phase shift ($\pi/2$).
    * End of the first cycle: $\text{Phase Shift} + \text{Period} = \pi/2 + \pi = 3\pi/2$.
    * Divide the cycle ($\pi/2$ to $3\pi/2$) into four parts to find the quarter-points:
        * Start: $\pi/2$
        * First Quarter: $3\pi/4$
        * Center: $\pi$
        * Third Quarter: $5\pi/4$
        * End: $3\pi/2$
* **Step 4: Determine Key Points**
    * Sine starts at an intercept, reaches a maximum, returns to an intercept, reaches a minimum, and ends at an intercept.
    * **Intercepts:** $(\pi/2, 0)$, $(\pi, 0)$, and $(3\pi/2, 0)$.
    * **Maximum (First Quarter):** $(3\pi/4, 3)$ (Amplitude of $3$).
    * **Minimum (Third Quarter):** $(5\pi/4, -3)$ (Amplitude of $3$).
* **Step 5: Sketching**
    * Plot the intercepts at $\pi/2, \pi,$ and $3\pi/2$ on the x-axis.
    * Plot the maximum at $(3\pi/4, 3)$ and the minimum at $(5\pi/4, -3)$.
    * Draw the smooth sine wave connecting these points.
### y = 2cos(4x + 3π) + 1

To graph $y = 2\cos(4x + 3\pi) + 1$ using Professor Leonard’s methodology, follow these steps:
* **Step 1: Put into Proper Form**
    * Factor the coefficient of $x$ ($4$) out of the argument inside the function.
    * $y = 2\cos(4(x + \frac{3\pi}{4})) + 1$
    * This reveals the transformations:
        * **Vertical Shift:** $+1$ (Shift up 1)
        * **Amplitude:** $2$
        * **$\omega$:** $4$
        * **Phase Shift:** $3\pi/4$ to the **left** (opposite of the positive sign).
* **Step 2: Identify Transformations**
    * **Vertical Shift:** Up 1 unit. Draw a dashed horizontal line at $y = 1$ to serve as your graphic organizer/new x-axis.
    * **Phase Shift:** $3\pi/4$ (Left). This marks the starting $x$-coordinate of the first period.
    * **Period:** $\text{Period} = 2\pi / \omega = 2\pi / 4 = \pi/2$.
* **Step 3: Graphing Setup**
    * The period is $\pi/2$. The cycle starts at the phase shift ($x = -3\pi/4$).
    * End of the first cycle: $\text{Phase Shift} + \text{Period} = -3\pi/4 + \pi/2 = -3\pi/4 + 2\pi/4 = -\pi/4$.
    * Divide the cycle ($-3\pi/4$ to $-\pi/4$) into four parts to find the quarter-points:
        * Start: $-3\pi/4$
        * First Quarter: $-5\pi/8$
        * Center: $-4\pi/8 = -\pi/2$
        * Third Quarter: $-3\pi/8$
        * End: $-\pi/4$
* **Step 4: Determine Key Points**
    * Cosine starts at a maximum, goes to an x-intercept, reaches a minimum, returns to an x-intercept, and ends at a maximum. Apply the amplitude ($2$) and the vertical shift ($+1$):
        * **Start (Max):** $(-3\pi/4, 2(1) + 1) = (-3\pi/4, 3)$
        * **First Quarter (Intercept):** $(-5\pi/8, 0(2) + 1) = (-5\pi/8, 1)$
        * **Center (Min):** $(-\pi/2, 2(-1) + 1) = (-\pi/2, -1)$
        * **Third Quarter (Intercept):** $(-3\pi/8, 0(2) + 1) = (-3\pi/8, 1)$
        * **End (Max):** $(-\pi/4, 2(1) + 1) = (-\pi/4, 3)$
* **Step 5: Sketching**
    * Draw a dashed horizontal line at $y=1$. 
    * Plot the points determined in Step 4 relative to this line.
    * Connect the points with a smooth cosine curve.
### y = 2cos(-2πx - 4) + 3

To graph $y = 2\cos(-2\pi x - 4) + 3$ using Professor Leonard’s methodology, you must first manipulate the function into the proper form to account for the reflection and phase shift.

* **Step 1: Put into Proper Form**
    * Factor the coefficient of $x$ ($-2\pi$) out of the argument.
    * $y = 2\cos(-2\pi(x + \frac{4}{2\pi})) + 3$
    * Simplify the phase shift term: $y = 2\cos(-2\pi(x + \frac{2}{\pi})) + 3$
    * **Use Even Function Property:** Cosine is an even function, meaning $\cos(-A) = \cos(A)$. We can drop the negative sign inside the argument without changing the function's output:
    * $y = 2\cos(2\pi(x + \frac{2}{\pi})) + 3$
    * Now the function is in proper form, revealing:
        * **Vertical Shift:** $+3$ (Shift up 3)
        * **Amplitude:** $2$
        * **$\omega$:** $2\pi$
        * **Phase Shift:** $2/\pi$ to the **left** (opposite of the positive sign).
* **Step 2: Identify Transformations**
    * **Vertical Shift:** Up 3 units. Draw a dashed horizontal line at $y = 3$ to serve as your new baseline.
    * **Phase Shift:** $2/\pi$ (Left). This is the starting $x$-coordinate of the first period.
    * **Period:** $\text{Period} = 2\pi / \omega = 2\pi / (2\pi) = 1$.
* **Step 3: Graphing Setup**
    * The period is $1$. The cycle starts at the phase shift ($x = -2/\pi$).
    * End of the first cycle: $\text{Phase Shift} + \text{Period} = -2/\pi + 1$.
    * Divide the cycle ($-2/\pi$ to $1 - 2/\pi$) into four parts to find the quarter-points:
        * Start: $-2/\pi$
        * First Quarter: $-2/\pi + 1/4$
        * Center: $-2/\pi + 1/2$
        * Third Quarter: $-2/\pi + 3/4$
        * End: $-2/\pi + 1$
* **Step 4: Determine Key Points**
    * Cosine starts at a maximum, goes to an intercept, reaches a minimum, returns to an intercept, and ends at a maximum. Apply the amplitude ($2$) and the vertical shift ($+3$):
        * **Start (Max):** $(-2/\pi, 2(1) + 3) = (-2/\pi, 5)$
        * **First Quarter (Intercept):** $(-2/\pi + 1/4, 2(0) + 3) = (-2/\pi + 1/4, 3)$
        * **Center (Min):** $(-2/\pi + 1/2, 2(-1) + 3) = (-2/\pi + 1/2, 1)$
        * **Third Quarter (Intercept):** $(-2/\pi + 3/4, 2(0) + 3) = (-2/\pi + 3/4, 3)$
        * **End (Max):** $(-2/\pi + 1, 2(1) + 3) = (-2/\pi + 1, 5)$
* **Step 5: Sketching**
    * Draw a dashed horizontal line at $y=3$. 
    * Plot the points determined in Step 4 relative to this baseline.
    * Connect the points with a smooth cosine curve.
## 2026-June-26 - Introduction to Inverse Trigonometric Functions (Precalculus - Trigonometry 17) :
https://www.youtube.com/watch?v=ih01YszlraY&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=92
### Introduction to Inverse Trigonometric Functions

This summary covers the fundamental concepts of inverse trigonometric functions, focusing on why they are necessary, how they are defined, and the importance of domain restriction for invertibility.
* **The Necessity of Inverse Functions**
    * Standard trigonometric functions (sine, cosine, tangent) take an angle as an input and output a ratio of triangle sides.
    * Inverse trigonometric functions perform the opposite operation: they take a ratio as an input and output the corresponding angle.
    * These tools are required to solve for unknown angles in right triangles when only side lengths are known.
* **Domain Restriction and Invertibility**
    * A function must be one-to-one to have an inverse, meaning it must pass the horizontal line test.
    * Because all trigonometric functions are periodic, they repeat their outputs infinitely, failing the horizontal line test in their natural state.
    * To define inverse functions, we must restrict the domains of the original functions to intervals where they are one-to-one:
        * **Sine:** Restricted to $[-\pi/2, \pi/2]$. The inverse, $\arcsin(x)$, has a range of $[-\pi/2, \pi/2]$.
        * **Cosine:** Restricted to $[0, \pi]$. The inverse, $\arccos(x)$, has a range of $[0, \pi]$.
        * **Tangent:** Restricted to $(-\pi/2, \pi/2)$. The inverse, $\arctan(x)$, has a range of $(-\pi/2, \pi/2)$.
* **Notation and Terminology**
    * Inverse functions are often written with a $-1$ exponent (e.g., $\sin^{-1}(x)$).
    * It is crucial to distinguish between $\sin^{-1}(x)$ (the inverse function, also known as $\arcsin(x)$) and $(\sin(x))^{-1}$ (the multiplicative reciprocal, or $1/\sin(x) = \csc(x)$).
    * The value returned by an inverse function within the defined restricted range is referred to as the "principal value."
* **Key Concepts for Evaluation**
    * **Composition:** If $x$ is within the restricted domain of a function $f$, then $f^{-1}(f(x)) = x$. If $x$ falls outside this domain, one must find an equivalent angle within the restricted range that produces the same ratio.
    * **Unit Circle:** Evaluating inverse functions often involves identifying the correct angle on the unit circle that corresponds to the given ratio, while respecting the boundaries of the restricted domain.
    * **Calculators:** When using a calculator to evaluate an inverse trig function, it will consistently return an angle located within the defined principal range.
## 2026-June-27 - How to Use Inverse Trigonometric Functions (Precalculus - Trigonometry 18) :
https://www.youtube.com/watch?v=6PB76VMNiX0&list=PLDesaqWTN6ESsmwELdrzhcGiRhk5DjwLP&index=94
### How to Use Inverse Trigonometric Functions

This summary details the application of inverse trigonometric functions, focusing on domain restrictions, compositions, and evaluation strategies as taught by Professor Leonard.
* **Core Principles**
    * **Standard vs. Inverse Functions:** * Standard trig functions: Input = angle; Output = coordinate/ratio on a unit circle.
        * Inverse trig functions: Input = coordinate/ratio on a unit circle; Output = angle.
    * **Domain Restriction:** To make trigonometric functions one-to-one (invertible), we must restrict their domains:
        * **Sine:** $[-\pi/2, \pi/2]$
        * **Cosine:** $[0, \pi]$
        * **Tangent:** $(-\pi/2, \pi/2)$
    * **The Importance of Restrictions:** Without these specific domain cuts, the functions would fail the horizontal line test, resulting in a single input producing multiple outputs (a non-function). All inverse evaluations must fall within these restricted ranges.
* **Composition of Functions and Inverses**
    * When composing a function with its inverse, they simplify (cancel) to the argument $x$, **provided** the domain of the inside function is satisfied.
    * **Case 1: Inverse outside the function ($f^{-1}(f(x)) = x$):**
        * You must ensure $x$ is within the restricted domain of $f$.
        * If $x$ is outside the restricted domain, you cannot simply cancel. Instead, you must find an equivalent angle (or ratio) within the restricted domain that yields the same coordinate/ratio.
    * **Case 2: Function outside the inverse ($f(f^{-1}(x)) = x$):**
        * You must ensure $x$ is within the domain of the inverse function ($f^{-1}$).
        * For $\sin^{-1}(x)$ and $\cos^{-1}(x)$, $x$ must be in $[-1, 1]$.
        * If $x$ is outside this range, the expression is **undefined** because no angle on the unit circle can produce a coordinate outside the range $[-1, 1]$.
* **Evaluation Methodology**
    * **Understanding the Question:** When asked for $\sin^{-1}(0)$, interpret it as: "What angle, within the restricted range, produces a y-coordinate of 0?"
    * **Unit Circle Utilization:** Always look at the unit circle restricted to the specific quadrants applicable to the inverse function being used:
        * **Sine/Tangent:** Quadrants IV and I ($-\pi/2$ to $\pi/2$).
        * **Cosine:** Quadrants I and II ($0$ to $\pi$).
    * **Calculators:** Use only when dealing with non-standard values (e.g., $\sin^{-1}(1/8)$). Always ensure the calculator is set to **radians**.
* **Handling Values Outside Domain Restrictions**
    * When faced with a composition like $\sin^{-1}(\sin(9\pi/8))$ where the input is outside the restricted domain:
        * 1. Locate the angle on the unit circle.
        * 2. Identify the corresponding coordinate/ratio.
        * 3. Find the equivalent angle that produces that same coordinate/ratio *within* the restricted domain.
        * 4. Cancel once the input is adjusted to fit the domain.
* **Summary Table of Restricted Ranges**

| Function       | Restricted Domain   | Range (Principal Value) |
| :------------- | :------------------ | :---------------------- |
| $\sin^{-1}(x)$ | $[-1, 1]$           | $[-\pi/2, \pi/2]$       |
| $\cos^{-1}(x)$ | $[-1, 1]$           | $[0, \pi]$              |
| $\tan^{-1}(x)$ | $(-\infty, \infty)$ | $(-\pi/2, \pi/2)$       |
### Trigonometric Composition Identities

The following identities hold true when the input $x$ is within the restricted domain of the inside function.
* **$\sin^{-1}(\sin x) = x$**
    * Valid for $x \in [-\pi/2, \pi/2]$.
* **$\sin(\sin^{-1} x) = x$**
    * Valid for $x \in [-1, 1]$.

* **$\cos^{-1}(\cos x) = x$**
    * Valid for $x \in [0, \pi]$.
* **$\cos(\cos^{-1} x) = x$**
    * Valid for $x \in [-1, 1]$.

* **$\tan^{-1}(\tan x) = x$**
    * Valid for $x \in (-\pi/2, \pi/2)$.
* **$\tan(\tan^{-1} x) = x$**
    * Valid for $x \in (-\infty, \infty)$.

### Inverse Trigonometric Evaluation Problems

Based on the unit circle definitions and restricted domains ($y = \sin^{-1}x \in [-\pi/2, \pi/2]$; $y = \cos^{-1}x \in [0, \pi]$; $y = \tan^{-1}x \in (-\pi/2, \pi/2)$):

* **$\sin^{-1}(0) = 0$**
    * Looking for the angle in $[-\pi/2, \pi/2]$ where the $y$-coordinate is $0$.
* **$\cos^{-1}(1) = 0$**
    * Looking for the angle in $[0, \pi]$ where the $x$-coordinate is $1$.
* **$\tan^{-1}(-1) = -\pi/4$**
    * Looking for the angle in $(-\pi/2, \pi/2)$ where $\frac{y}{x} = -1$.
* **$\cos^{-1}(-1) = \pi$**
    * Looking for the angle in $[0, \pi]$ where the $x$-coordinate is $-1$.
* **$\tan^{-1}(0) = 0$**
    * Looking for the angle in $(-\pi/2, \pi/2)$ where $\frac{y}{x} = 0$.
* **$\sin^{-1}(\frac{\sqrt{2}}{2}) = \pi/4$**
    * Looking for the angle in $[-\pi/2, \pi/2]$ where the $y$-coordinate is $\frac{\sqrt{2}}{2}$.
* **$\cos^{-1}(-\frac{\sqrt{3}}{2}) = 5\pi/6$**
    * Looking for the angle in $[0, \pi]$ where the $x$-coordinate is $-\frac{\sqrt{3}}{2}$.
### Inverse Trigonometric Evaluation Problems

Based on the unit circle definitions and restricted domains ($y = \sin^{-1}x \in [-\pi/2, \pi/2]$; $y = \cos^{-1}x \in [0, \pi]$; $y = \tan^{-1}x \in (-\pi/2, \pi/2)$), here are the solutions:

* **$\sin^{-1}(-\frac{\sqrt{3}}{2}) = -\frac{\pi}{3}$**
    * Looking for the angle in $[-\pi/2, \pi/2]$ where the $y$-coordinate is $-\frac{\sqrt{3}}{2}$.
* **$\sin^{-1}(-\frac{\sqrt{2}}{2}) = -\frac{\pi}{4}$**
    * Looking for the angle in $[-\pi/2, \pi/2]$ where the $y$-coordinate is $-\frac{\sqrt{2}}{2}$.
* **$\tan^{-1}(\sqrt{3}) = \frac{\pi}{3}$**
    * Looking for the angle in $(-\pi/2, \pi/2)$ where $\frac{y}{x} = \sqrt{3}$.
* **$\tan^{-1}(\frac{\sqrt{3}}{3}) = \frac{\pi}{6}$**
    * Looking for the angle in $(-\pi/2, \pi/2)$ where $\frac{y}{x} = \frac{\sqrt{3}}{3}$ (rationalized form of $\frac{1}{\sqrt{3}}$).

#### Approximate Values (Calculator required, set to radians)
* **$\sin^{-1}(\frac{1}{8}) \approx 0.125$**
* **$\cos^{-1}(\frac{\sqrt{2}}{3}) \approx 1.08$**
* **$\tan^{-1}(-3) \approx -1.25$**
### Inverse Trigonometric Composition Problems

To solve these compositions, we must ensure the argument of the inside function lies within the restricted domain of the trigonometric function. If it does not, we must find an equivalent angle within the restricted domain that yields the same trigonometric value.

* **$\cos^{-1}(\cos \frac{4\pi}{5}) = \frac{4\pi}{5}$**
    * Since $4\pi/5$ is within the restricted domain of cosine $[0, \pi]$, the functions cancel directly.

* **$\sin^{-1}(\sin -\frac{3\pi}{7}) = -\frac{3\pi}{7}$**
    * Since $-3\pi/7$ is within the restricted domain of sine $[-\pi/2, \pi/2]$, the functions cancel directly.

* **$\cos^{-1}(\cos -\frac{\pi}{3}) = \frac{\pi}{3}$**
    * $- \pi/3$ is outside the restricted domain $[0, \pi]$.
    * Because cosine is an even function, $\cos(-\pi/3) = \cos(\pi/3)$.
    * Since $\pi/3$ is within the restricted domain, the expression simplifies to $\pi/3$.

* **$\cos^{-1}(\cos -\frac{5\pi}{3}) = \frac{\pi}{3}$**
    * $-5\pi/3$ is outside the restricted domain.
    * We find a coterminal angle within $[0, \pi]$ that has the same $x$-coordinate (cosine value).
    * $-5\pi/3 + 2\pi = \pi/3$.
    * Since $\pi/3$ is within the restricted domain, the expression simplifies to $\pi/3$.

