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