- [ ] Create an App similar to Trig-Identities-CheatSheet with a screensaver and quiz mode of all the new calc 1 identities I need for engineering
- [ ] Create a new xournal template for practice/review of calc identities - still haven't fully remembered the ~30ish trig identities
### Calc 1 Derivative Rules

#### Basic Rules
* Constant Rule: $\frac{d}{dx}[c] = 0$
* Power Rule: $\frac{d}{dx}[x^n] = n x^{n-1}$
* Constant Multiple Rule: $\frac{d}{dx}[c \cdot f(x)] = c \cdot f'(x)$
* Sum & Difference Rule: $\frac{d}{dx}[f(x) \pm g(x)] = f'(x) \pm g'(x)$
#### Operations & Combinations
* Product Rule: $\frac{d}{dx}[f(x)g(x)] = f'(x)g(x) + f(x)g'(x)$
* Quotient Rule: $\frac{d}{dx}\left[\frac{f(x)}{g(x)}\right] = \frac{f'(x)g(x) - f(x)g'(x)}{[g(x)]^2}$
* Chain Rule: $\frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x)$
#### Exponential & Logarithmic Functions
* Exponential ($e^x$): $\frac{d}{dx}[e^x] = e^x$
* General Exponential ($a^x$): $\frac{d}{dx}[a^x] = a^x \ln(a)$
* Natural Logarithm ($\ln x$): $\frac{d}{dx}[\ln(x)] = \frac{1}{x}$
* General Logarithm ($\log_a x$): $\frac{d}{dx}[\log_a(x)] = \frac{1}{x \ln(a)}$
#### Trigonometric Functions
* $\frac{d}{dx}[\sin(x)] = \cos(x)$
* $\frac{d}{dx}[\cos(x)] = -\sin(x)$
* $\frac{d}{dx}[\tan(x)] = \sec^2(x)$
* $\frac{d}{dx}[\csc(x)] = -\csc(x)\cot(x)$
* $\frac{d}{dx}[\sec(x)] = \sec(x)\tan(x)$
* $\frac{d}{dx}[\cot(x)] = -\csc^2(x)$
#### Inverse Trigonometric Functions
* $\frac{d}{dx}[\arcsin(x)] = \frac{1}{\sqrt{1 - x^2}}$
* $\frac{d}{dx}[\arccos(x)] = -\frac{1}{\sqrt{1 - x^2}}$
* $\frac{d}{dx}[\arctan(x)] = \frac{1}{1 + x^2}$
* $\frac{d}{dx}[\text{arcsec}(x)] = \frac{1}{|x|\sqrt{x^2 - 1}}$
* $\frac{d}{dx}[\text{arccsc}(x)] = -\frac{1}{|x|\sqrt{x^2 - 1}}$
* $\frac{d}{dx}[\text{arccot}(x)] = -\frac{1}{1 + x^2}$
### Core Limit Identities & Laws - **Evaluating Trigonometric Limits** (Prof. Leonard - Calc 1, Lect 1.2)
https://www.youtube.com/watch?v=VSqOZNULRjQ&list=PLF797E961509B4EB5&index=11
- I was confused doing these yesterday, 3 hour lesson, definitely will need to review, saving for Future Sean, look up / review **Evaluating Trigonometric Limits** - also, will need to remember a bunch of new identities on top of the trig ones
#### **1. Basic Elementary Limits**
* **Limit of a Constant:**
  $$\lim_{x \to a} c = c$$
  * *Reasoning:* A constant function $y = c$ is a horizontal line. As $x \to a$ from left or right, $y$ remains $c$.

* **Limit of the Identity Function ($x$):**
  $$\lim_{x \to a} x = a$$
  * *Reasoning:* For $y = x$, direct evaluation at $x = a$ yields $a$.

---
#### **2. Limit Algebraic Laws**
Assuming $\lim_{x \to a} f(x) = L$ and $\lim_{x \to a} g(x) = M$:
* **Sum/Difference Rule:**
  $$\lim_{x \to a} [f(x) \pm g(x)] = \lim_{x \to a} f(x) \pm \lim_{x \to a} g(x) = L \pm M$$
* **Constant Multiple Rule:**
  $$\lim_{x \to a} [c \cdot f(x)] = c \cdot \lim_{x \to a} f(x) = c \cdot L$$
* **Product Rule:**
  $$\lim_{x \to a} [f(x) \cdot g(x)] = \left[\lim_{x \to a} f(x)\right] \cdot \left[\lim_{x \to a} g(x)\right] = L \cdot M$$
* **Quotient Rule:**
  $$\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)} = \frac{L}{M} \quad (\text{provided } M \neq 0)$$
* **Power Rule:**
  $$\lim_{x \to a} [f(x)]^n = \left[\lim_{x \to a} f(x)\right]^n = L^n$$

---
#### **3. Direct Substitution Property**

* **Polynomial Direct Substitution:**
  If $P(x)$ is a polynomial:
  $$\lim_{x \to a} P(x) = P(a)$$

* **Rational Function Direct Substitution:**
  If $R(x) = \frac{P(x)}{Q(x)}$ is a rational function and $Q(a) \neq 0$:
  $$\lim_{x \to a} R(x) = R(a) = \frac{P(a)}{Q(a)}$$

---
#### **4. Fundamental Trigonometric Limit Identities**

* **Sine Fundamental Limit:**
  $$\lim_{x \to 0} \frac{\sin(x)}{x} = 1 \quad \text{and} \quad \lim_{x \to 0} \frac{x}{\sin(x)} = 1$$

* **Cosine Fundamental Limit:**
  $$\lim_{x \to 0} \frac{1 - \cos(x)}{x} = 0$$

* **Generalized Matching Structural Rule:**
  $$\lim_{\text{stuff} \to 0} \frac{\sin(\text{stuff})}{\text{stuff}} = 1$$

---
#### **5. Key Algebraic Identities Used for Limit Indeterminacies ($\frac{0}{0}$)**

* **Pythagorean Identity:**
  $$\sin^2(x) + \cos^2(x) = 1 \implies 1 - \cos^2(x) = \sin^2(x)$$
* **Conjugate Multiplication for Trigonometric Expressions:**
  $$(1 - \cos(x))(1 + \cos(x)) = 1 - \cos^2(x) = \sin^2(x)$$
### Instantaneous Velocity

**From Average Velocity to Instantaneous Velocity:**

Recall that Average Velocity over a time interval $h$ is given by:
$$V_{\text{AVE}} = \frac{f(T_0 + h) - f(T_0)}{h} \quad (h = \text{TIME})$$

**Core Conceptual Question:**
> *How much time elapses in an instant?*

An "instant" means the elapsed time $h$ approaches zero ($h \to 0$).

---
**Formula for Instantaneous Velocity:**

Taking the limit as the elapsed time $h$ approaches $0$:

$$V_{\text{INST}} = \lim_{h \to 0} \frac{f(T_0 + h) - f(T_0)}{h}$$
### 2026-09-20 - Calculus 1 Lecture 2.1: Introduction to the Derivative of a Function :
https://www.youtube.com/watch?v=962lLfW-8Jo&list=PLF797E961509B4EB5&index=10
#### Calculus 1 Lecture 2.1: Introduction to the Derivative of a Function

**Overview & Core Definition**
* The derivative represents the slope of a curve at a single point (or the slope of the tangent line at that point).
* It unifies the concepts of instantaneous rate of change and instantaneous velocity.
* **Definition of the Derivative Function:**
$$f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$$
* Read as **"$f\text{ prime of }x$"**, which denotes the derivative of $f$ with respect to $x$.
### Instantaneous Velocity: $v(t) = s'(t) = \lim_{\Delta t \to 0} \frac{\Delta s}{\Delta t}$
#### **1. Conceptual Strategy & Game Plan**

To truly grasp what instantaneous velocity is, we have to contrast it with something we already know intuitively: **average velocity**.

1. **Average Velocity vs. Instantaneous Velocity:**
   * Average velocity tells you the overall rate of change over a time interval $[t_1, t_2]$:
     $$v_{\text{avg}} = \frac{\Delta s}{\Delta t} = \frac{s(t_2) - s(t_1)}{t_2 - t_1}$$
   * Graphically, average velocity is the slope of a **secant line** connecting two distinct points on a position-time graph $s(t)$.
   * However, average velocity hides all the details during the journey. If you drive $60\text{ miles}$ in $1\text{ hour}$, your average velocity is $60\text{ mph}$, but at any single moment, you might have been going $0\text{ mph}$ at a red light or $75\text{ mph}$ on the highway.

2. **Shrinking the Interval to Zero (The Limit):**
   * To find how fast you are moving at *one exact instant* $t$, we let the change in time $\Delta t$ (or $h$) shrink down closer and closer to $0$.
   * As $\Delta t \to 0$, the two points on the position graph merge into one, and the secant line becomes the **tangent line** at $t$.
   * Thus, instantaneous velocity $v(t)$ is simply the **first derivative of the position function $s(t)$**.

---
#### **2. Mathematical Formulation**

##### **Step 1: Define Position and the Difference Quotient**
Let $s(t)$ be a position function that models the displacement of an object at time $t$.

The average velocity over a small interval $[t, t + h]$ is given by:
$$v_{\text{avg}} = \frac{s(t + h) - s(t)}{h}$$

---
##### **Step 2: Take the Limit as $h \to 0$**
To get the velocity at the exact moment $t$, take the limit as the time step $h$ approaches zero:
$$v(t) = \lim_{h \to 0} \frac{s(t + h) - s(t)}{h}$$
### Problem: $f(x) = (1 + x^2) \cdot \sqrt{x}$ — Find $f'(x)$

In this example, Professor Leonard applies the **Product Rule** to differentiate a product involving a polynomial term and a square root term.

---
#### The Product Rule Formula

$$\frac{d}{dx}\left[ F(x) \cdot S(x) \right] = \left(\frac{d}{dx}[F(x)]\right) \cdot S(x) + F(x) \cdot \left(\frac{d}{dx}[S(x)]\right)$$

*(Derivative of the first times the second, plus the first times derivative of the second)*

---
#### Step-by-Step Solution

1. **Set up the Product Rule structure:**
   $$f'(x) = \frac{d}{dx}\left[1 + x^2\right] \cdot \sqrt{x} + (1 + x^2) \cdot \frac{d}{dx}\left[\sqrt{x}\right]$$

2. **Differentiate the first piece and rewrite the square root as an exponent:**
   * $\frac{d}{dx}[1 + x^2] = 2x$
   * Rewrite $\sqrt{x}$ as $x^{\frac{1}{2}}$ to prepare it for the Power Rule:

   $$f'(x) = 2x \cdot \sqrt{x} + (1 + x^2) \cdot \frac{d}{dx}\left[x^{\frac{1}{2}}\right]$$

3. **Apply the Power Rule to $x^{\frac{1}{2}}$:**
   * $\frac{d}{dx}\left[x^{\frac{1}{2}}\right] = \frac{1}{2}x^{-\frac{1}{2}}$

   $$f'(x) = 2x\sqrt{x} + (1 + x^2) \cdot \frac{1}{2}x^{-\frac{1}{2}}$$
4. **Algebraically simplify and rewrite negative exponents as fractions:**
   * Note that $x^{-\frac{1}{2}} = \frac{1}{x^{1/2}} = \frac{1}{\sqrt{x}}$
   * Therefore, $\frac{1}{2}x^{-\frac{1}{2}} = \frac{1}{2\sqrt{x}}$

   $$f'(x) = 2x\sqrt{x} + \frac{1 + x^2}{2\sqrt{x}}$$

---
#### Final Answer

$$f'(x) = 2x\sqrt{x} + \frac{1 + x^2}{2\sqrt{x}}$$
### Concept: Taking the Derivative of a Square Root — $\frac{d}{dx}[\sqrt{x}]$

In calculus, differentiating square root functions (and radicals in general) relies on converting the radical expression into fractional exponent form before applying the **Power Rule**.

---
#### 1. Core Rule & Rewrite Method
To take the derivative of $\sqrt{x}$, first rewrite the square root using an exponent:

$$\sqrt{x} = x^{\frac{1}{2}}$$

Now, apply the standard **Power Rule** ($\frac{d}{dx}[x^n] = n x^{n-1}$):

$$\frac{d}{dx}[\sqrt{x}] = \frac{d}{dx}\left[x^{\frac{1}{2}}\right]$$

$$= \frac{1}{2} x^{\left(\frac{1}{2} - 1\right)}$$

$$= \frac{1}{2} x^{-\frac{1}{2}}$$
### Summary of Core Calculus Rules & Formulas :
* **Power Rule:** $\frac{d}{dx}[x^n] = n x^{n-1}$ | **Constant Rule:** $\frac{d}{dx}[c] = 0$ | **Constant Multiple Rule:** $\frac{d}{dx}[c \cdot f(x)] = c \cdot f'(x)$ | **Sum/Difference Rule:** $\frac{d}{dx}[f(x) \pm g(x)] = f'(x) \pm g'(x)$ | **Product Rule:** $\frac{d}{dx}[f(x) g(x)] = f'(x)g(x) + f(x)g'(x)$ | **Quotient Rule:** $\frac{d}{dx}\left[\frac{f(x)}{g(x)}\right] = \frac{f'(x)g(x) - f(x)g'(x)}{[g(x)]^2}$ | **Chain Rule:** $\frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x)$ | **Square Root Shortcut:** $\frac{d}{dx}[\sqrt{x}] = \frac{1}{2\sqrt{x}}$ | **Exponential Rules:** $\frac{d}{dx}[e^x] = e^x$, $\frac{d}{dx}[a^x] = a^x \ln(a)$ | **Logarithmic Rules:** $\frac{d}{dx}[\ln(x)] = \frac{1}{x}$, $\frac{d}{dx}[\log_a(x)] = \frac{1}{x \ln(a)}$ | **Trig Rules:** $\frac{d}{dx}[\sin x] = \cos x$, $\frac{d}{dx}[\cos x] = -\sin x$, $\frac{d}{dx}[\tan x] = \sec^2 x$, $\frac{d}{dx}[\csc x] = -\csc x \cot x$, $\frac{d}{dx}[\sec x] = \sec x \tan x$, $\frac{d}{dx}[\cot x] = -\csc^2 x$ | **Inverse Trig Rules:** $\frac{d}{dx}[\arcsin x] = \frac{1}{\sqrt{1-x^2}}$, $\frac{d}{dx}[\arccos x] = -\frac{1}{\sqrt{1-x^2}}$, $\frac{d}{dx}[\arctan x] = \frac{1}{1+x^2}$ 
#### Verbal Mnemonic For Quotient Rule : 
A popular and reliable way to memorize the structure without getting terms mixed up:
Product Rule = 'P' = Positive, Quotient Rule = negative :

$$\frac{\text{Low} \cdot d(\text{High}) - \text{High} \cdot d(\text{Low})}{\text{Low}^2}$$
## Future Sean Project : Either create a 'Calc Cheatsheet' App or Create a review template for xournal++ review, or both, still need to make Anki Cards as well - Will need both the Core Calc Rules and Formulas + the Trigonometric Derivatives for the app - Basically, create the 'CheatSheet Apps' to grade my own work/passive learning via the screensaver, and create the 'Xournal++ Templates' to review, do these reviews every weeks/month until it's in my head like 'SOHCAHTOA' was
### Trigonometric Derivatives 
* **Trigonometric Derivatives**: The primary derivative formulas to memorize are $\frac{d}{dx}[\sin x] = \cos x$, $\frac{d}{dx}[\cos x] = -\sin x$, $\frac{d}{dx}[\tan x] = \sec^2 x$, $\frac{d}{dx}[\csc x] = -\csc x \cot x$, $\frac{d}{dx}[\sec x] = \sec x \tan x$, and $\frac{d}{dx}[\cot x] = -\csc^2 x$.
#### Summary Table of Trigonometric Derivatives
The six standard trigonometric derivatives must be memorized:

$$\begin{aligned}
1.\quad \frac{d}{dx}[\sin x] &= \cos x & 4.\quad \frac{d}{dx}[\csc x] &= -\csc x \cot x \\
2.\quad \frac{d}{dx}[\cos x] &= -\sin x & 5.\quad \frac{d}{dx}[\sec x] &= \sec x \tan x \\
3.\quad \frac{d}{dx}[\tan x] &= \sec^2 x & 6.\quad \frac{d}{dx}[\cot x] &= -\csc^2 x
\end{aligned}$$
### 2026-10-03 - Calculus 1 Lecture 2.6: Discussion of the Chain Rule for Derivatives of Functions :
https://www.youtube.com/watch?v=8dr1dZjfhmc&list=PLF797E961509B4EB5&index=16
- Struggled with the square roots expressions, where the exponents would flip to negative, will need to review, still haven't memorized all the identities either
#### Calculus 1 Lecture 2.6: Discussion of the Chain Rule for Derivatives of Functions

#### Overview and Purpose
The Chain Rule is a fundamental differentiation technique used to compute the derivative of a **composite function** $f(g(x))$, often described as a function inside another function. It allows us to break down complex algebraic, trigonometric, and exponential expressions into manageable outer and inner parts.

---
#### Mathematical Formulation

#### Standard Function Notation
If $y = f(u)$ is a differentiable function of $u$, and $u = g(x)$ is a differentiable function of $x$, then the composite function $y = f(g(x))$ is differentiable with respect to $x$:

$$\frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x)$$

In words: **Derivative of the outer function (evaluated at the inner function) multiplied by the derivative of the inner function.**

#### Leibniz Notation
Using Leibniz notation, the rule is expressed as:

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$$

Where:
* $y = f(u)$ (outer function)
* $u = g(x)$ (inner function)

---
#### Key Conceptual Steps

1. **Identify the Structure**: Break the given function into its outer layer $f(u)$ and inner layer $g(x)$.
2. **Differentiate the Outer Function**: Take the derivative of $f(u)$ with respect to $u$, leaving $g(x)$ untouched inside.
3. **Differentiate the Inner Function**: Find $g'(x)$.
4. **Multiply**: Compute $f'(g(x)) \cdot g'(x)$.
5. **Simplify**: Perform algebraic or trigonometric simplification where appropriate.

---
#### Generalized Power Rule (Special Case)
A common application of the Chain Rule is differentiating a function raised to a power $[g(x)]^n$:

$$\frac{d}{dx}\left[ (g(x))^n \right] = n(g(x))^{n-1} \cdot g'(x)$$
#### $y = \sqrt{5x^2 - 1}$

#### Problem
Find the derivative $\frac{dy}{dx}$ using the General Power Rule / Chain Rule.
#### Step-by-Step Solution
1. **Rewrite radical using a rational exponent**:
   $$y = (5x^2 - 1)^{1/2}$$
2. **Apply the General Power Rule to the outer function**:
   $$\frac{dy}{dx} = \frac{1}{2}(5x^2 - 1)^{-\frac{1}{2}} \cdot \frac{d}{dx}[5x^2 - 1]$$
3. **Differentiate the inner function**:
   $$= \frac{1}{2}(5x^2 - 1)^{-\frac{1}{2}} \cdot 10x$$
4. **Simplify and rewrite with radical notation in the denominator**:
   $$= \frac{5x}{\sqrt{5x^2 - 1}}$$
#### $\frac{d}{dx}\left[\sqrt{x^3 + \csc(x^3)}\right]$

#### Problem
Find the derivative $\frac{d}{dx}\left[\sqrt{x^3 + \csc(x^3)}\right]$ using the General Power Rule and Chain Rule.
#### Step-by-Step Solution
1. **Rewrite the radical expression with a fractional exponent**:
   $$\frac{d}{dx}\left[\sqrt{x^3 + \csc(x^3)}\right] = \frac{d}{dx}\left[\left(x^3 + \csc(x^3)\right)^{\frac{1}{2}}\right]$$

2. **Apply the Power Rule to the outer function, leaving the inner expression untouched**:
   $$= \frac{1}{2}\left(x^3 + \csc(x^3)\right)^{-\frac{1}{2}} \cdot \frac{d}{dx}\left[x^3 + \csc(x^3)\right]$$
3. **Differentiate the terms inside the brackets (applying the Chain Rule to $\csc(x^3)$)**:
   $$= \frac{1}{2}\left(x^3 + \csc(x^3)\right)^{-\frac{1}{2}} \cdot \left[3x^2 + \left(-\csc(x^3)\cot(x^3) \cdot \frac{d}{dx}[x^3]\right)\right]$$
4. **Complete the derivative of the innermost term**:
   $$= \frac{1}{2}\left(x^3 + \csc(x^3)\right)^{-\frac{1}{2}} \cdot \left[3x^2 - \csc(x^3)\cot(x^3) \cdot (3x^2)\right]$$
5. **Factor out $3x^2$ and simplify into radical fraction form**:
   $$= \frac{3x^2\left(1 - \csc(x^3)\cot(x^3)\right)}{2\sqrt{x^3 + \csc(x^3)}}$$
#### $\frac{d}{dx}\left[\left(3 + x^2\cot(x^2)\right)^{-3}\right]$

#### Problem
Find the derivative $\frac{d}{dx}\left[\left(3 + x^2\cot(x^2)\right)^{-3}\right]$ using the General Power Rule, Product Rule, and Chain Rule.
#### Step-by-Step Solution
1. **Apply the Power Rule to the outer function**:
   $$\frac{d}{dx}\left[\left(3 + x^2\cot(x^2)\right)^{-3}\right] = -3\left(3 + x^2\cot(x^2)\right)^{-4} \cdot \frac{d}{dx}\left[3 + x^2\cot(x^2)\right]$$
2. **Differentiate the inside expression (the derivative of the constant $3$ is $0$, apply Product Rule to $x^2\cot(x^2)$)**:
   $$= -3\left(3 + x^2\cot(x^2)\right)^{-4} \cdot \left[\frac{d}{dx}[x^2]\cot(x^2) + x^2 \cdot \frac{d}{dx}[\cot(x^2)]\right]$$
3. **Differentiate $x^2$ and apply the Chain Rule to $\cot(x^2)$**:
   $$= -3\left(3 + x^2\cot(x^2)\right)^{-4} \cdot \left[2x\cot(x^2) + x^2\left(-\csc^2(x^2) \cdot \frac{d}{dx}[x^2]\right)\right]$$
4. **Complete the derivative of the innermost term**:
   $$= -3\left(3 + x^2\cot(x^2)\right)^{-4} \cdot \left[2x\cot(x^2) + x^2\left(-\csc^2(x^2) \cdot 2x\right)\right]$$
5. **Simplify terms inside the bracket**:
   $$= -3\left(3 + x^2\cot(x^2)\right)^{-4} \cdot \left[2x\cot(x^2) - 2x^3\csc^2(x^2)\right]$$
6. **Factor out $2x$ and write with a positive exponent in the denominator**:
   $$= \frac{-6x\left(\cot(x^2) - x^2\csc^2(x^2)\right)}{\left(3 + x^2\cot(x^2)\right)^4}$$

### 2026-10-06 - Calculus 1 Lecture 2.7: Implicit Differentiation :
https://www.youtube.com/watch?v=RUS4mKo9tBk&list=PLF797E961509B4EB5&index=15
#### Lecture Notes: Calculus 1 – Lecture 2.7: Implicit Differentiation (Professor Leonard)

#### Key Concepts & Definitions
- **Explicit Functions**: An equation where $y$ is isolated on one side and explicitly defined strictly in terms of $x$ (e.g., $y = 3x^2 + 4$).
- **Implicit Equations**: An equation where $y$ and $x$ are mixed together and $y$ is not isolated (e.g., $x y + y = x$).
- **Implicit Equations & Multiple Functions**: An implicit equation can implicitly define more than one function of $x$. 
  * *Example*: $x^2 + y^2 = 4 \implies y = \pm\sqrt{4 - x^2}$ (represents both an upper and lower semicircle).
- **Core Principle of Implicit Differentiation**: Treat $y$ as an unknown function of $x$ (i.e., $y = f(x)$). Every time you differentiate a term containing $y$ with respect to $x$, you **must** apply the Chain Rule, multiplying by $\frac{dy}{dx}$.

---
#### General Steps for Implicit Differentiation
1. **Differentiate Both Sides**: Take $\frac{d}{dx}$ of both sides of the equation with respect to $x$.
   * Differentiating an $x$ term yields standard derivatives (since $\frac{dx}{dx} = 1$).
   * Differentiating a $y$ term yields its standard derivative multiplied by $\frac{dy}{dx}$ (due to the Chain Rule).
2. **Isolate $\frac{dy}{dx}$ Terms**: Group all terms containing $\frac{dy}{dx}$ on one side of the equation and move all other terms to the opposite side.
3. **Factor Out $\frac{dy}{dx}$**: Factor $\frac{dy}{dx}$ out of the terms on the isolated side.
4. **Solve for $\frac{dy}{dx}$**: Divide both sides by the remaining algebraic expression to solve for $\frac{dy}{dx}$.

---
#### Example 1: Basic Implicit Differentiation
##### Problem
Find $\frac{dy}{dx}$ for $x^3 + y^3 = 5$.
##### Step-by-Step Solution
1. **Take the derivative of both sides with respect to $x$**:
   $$\frac{d}{dx}\left[x^3 + y^3\right] = \frac{d}{dx}[5]$$
2. **Differentiate term-by-term using the Power Rule and Chain Rule**:
   $$\frac{d}{dx}[x^3] + \frac{d}{dx}[y^3] = 0$$
   $$3x^2 + 3y^2 \cdot \frac{dy}{dx} = 0$$
3. **Move non-$\frac{dy}{dx}$ terms to the right side**:
   $$3y^2 \cdot \frac{dy}{dx} = -3x^2$$
4. **Isolate $\frac{dy}{dx}$**:
   $$\frac{dy}{dx} = \frac{-3x^2}{3y^2} = -\frac{x^2}{y^2}$$

