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