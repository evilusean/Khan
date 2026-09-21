- [ ] Create an App similar to Trig-Identities-CheatSheet with a screensaver and quiz mode of all the new calc 1 identities I need for engineering
- [ ] Create a new xournal template for practice/review of calc identities - still haven't fully remembered the ~30ish trig identities
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
### Representations for Derivatives

#### **1. General Derivative Functions (Derivative at any $x$)**

These notations represent the **derivative function** $f'(x)$, which yields the slope of the tangent line at any general input $x$:

* **Lagrange's Notation (Prime Notation):**
  $$f'(x)$$
  * Read as: *"f prime of x"*
  * Very common in calculus; emphasizes that the derivative is itself a new function of $x$.

* **Operator Notation (Differential Operator):**
  $$\frac{d}{dx}\left[f(x)\right]$$
  * Read as: *"the derivative with respect to x of f of x"*
  * Treats $\frac{d}{dx}$ as an action or operator being applied to the function $f(x)$.

* **Lagrange's Notation with $y$:**
  $$y'$$
  * Read as: *"y prime"*
  * Used when the function is defined in terms of $y = f(x)$. Quick and concise, though it does not explicitly specify the independent variable.

* **Leibniz's Notation:**
  $$\frac{dy}{dx}$$
  * Read as: *"dy dx"* or *"the derivative of y with respect to x"*
  * Represents the ratio of an infinitesimal change in $y$ ($dy$) to an infinitesimal change in $x$ ($dx$). Ideal for differential equations and chain rule.

---

#### **2. Derivative Evaluated at a Specific Point ($x = a$)**

When you want to calculate the derivative at a **specific numerical value** $x = a$, each of the general notations adapts as follows:

* **Prime Notation at a Point:**
  $$f'(a)$$
  * Simply substitute $a$ into the derivative function $f'(x)$.

* **Operator Notation Evaluated at a Point:**
  $$\left.\frac{d}{dx}\left[f(x)\right]\right\vert{}_{x=a}$$
  * Uses the evaluation bar $\big\vert{}_{x=a}$ to denote that after finding the derivative, you evaluate it at $x = a$.

* **$y'$ Notation at a Point:**
  $$y'(a)$$