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