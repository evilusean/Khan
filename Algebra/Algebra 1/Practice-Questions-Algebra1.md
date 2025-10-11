### Synthetic Division - Practice Questions  :
#### Date: 2025-10-10
#### Subject: Synthetic Division

#### Underlying Formula (Division Algorithm) The goal is to express the result in the form: $$\frac{P(x)}{D(x)} = Q(x) + \frac{R}{D(x)}$$ Where $P(x)$ is the dividend, $D(x)$ is the divisor, $Q(x)$ is the quotient, and $R$ is the remainder.

---
#### The Method: Synthetic Division Synthetic division is a shortcut for dividing a polynomial by a linear factor $\mathbf{x - c}$. We only work with the coefficients. 
**Step 1: Setup** 
1. **Find the root $c$:** Set the divisor $x + 2 = 0 \implies \mathbf{c = -2}$. 
2. **List Coefficients:** Write the coefficients of the dividend $P(x)$, ensuring a **zero placeholder** for every missing power ($x^3$ and $x$): $$P(x) = 2x^4 + \mathbf{0}x^3 + 5x^2 + \mathbf{0}x - 7$$ Coefficients: $\mathbf{2, 0, 5, 0, -7}$. $$\begin{array}{c|ccccc} -2 & 2 & 0 & 5 & 0 & -7 \\ & & & & & \\ \hline & & & & & \end{array}$$ **Step 2: Calculate (Multiply and Add)** 
3. Bring down the first coefficient ($\mathbf{2}$). 
4. **Multiply** the number below the line by $c$ ($-2$) and place the result in the next column. 
5. **Add** the column vertically. 
6. Repeat (Multiply, Add) until the last column is complete. $$\begin{array}{c|ccccc} -2 & 2 & 0 & 5 & 0 & -7 \\ & & -4 & 8 & -26 & 52 \\ \hline & \mathbf{2} & \mathbf{-4} & \mathbf{13} & \mathbf{-26} & \mathbf{45} \end{array}$$ **Step 3: Interpretation** 1. **Remainder ():** The last number is the remainder. $$R = 45$$ 2. **Quotient ():** The remaining numbers are the coefficients of the quotient. Since $P(x)$ was degree 4, $Q(x)$ is degree $4 - 1 = 3$. $$Q(x) = 2x^3 - 4x^2 + 13x - 26$$ **Step 4: Final Answer Form** Substitute the values into the formula $\mathbf{Q(x) + \frac{R}{D(x)}}$: $$2x^3 - 4x^2 + 13x - 26 + \frac{45}{x + 2}$$

#### Question 1
- [x] Completed ✅ 2025-10-10
- [ ] Correct
- [x] Added to Anki ✅ 2025-10-10
Use synthetic division to find the quotient $Q(x)$ and the remainder $R$ when the polynomial $P(x) = 2x^4 + 5x^2 - 7$ is divided by the binomial $D(x) = x + 2$. Write your final answer in the mixed form $Q(x) + \frac{R}{D(x)}$.
#### Question 2
- [x] Completed ✅ 2025-10-10
- [ ] Correct
- [x] Added to Anki ✅ 2025-10-10
Perform synthetic division to divide the polynomial $P(x) = 6x^3 - 7x^2 + 5x - 8$ by the binomial $D(x) = 2x - 1$. State the correct final quotient $Q(x)$ and the remainder $R$.
#### Question 3
- [x] Completed ✅ 2025-10-10
- [ ] Correct
- [x] Added to Anki ✅ 2025-10-10
Given the polynomial $P(x) = 3x^5 - x^4 + 10x^3 - 2x + 5$, use synthetic division with the divisor $D(x) = x - 1$ to accomplish two things:
1.  Determine the remainder $R$.
2.  State the quotient $Q(x)$.
What does the Remainder Theorem tell you about the value of $P(1)$?
#### Date: 2025-10-10
#### Subject: Synthetic Division (Set 2)

#### Question 4
- [x] Completed ✅ 2025-10-10
- [ ] Correct
- [x] Added to Anki ✅ 2025-10-10
Use synthetic division to evaluate $P(-3)$ for the polynomial $P(x) = x^4 - 6x^3 + 2x^2 - 4x + 10$. What does the result tell you about the linear factor $(x+3)$?

#### Question 5
- [x] Completed ✅ 2025-10-10
- [ ] Correct
- [x] Added to Anki ✅ 2025-10-10
The volume $V(x)$ of a rectangular prism is given by the polynomial $V(x) = 3x^3 + 14x^2 + 7x - 6$. If one side length is known to be $(3x - 1)$, use synthetic division to find the polynomial $A(x)$ representing the area of the base (i.e., the quotient of the division).

#### Question 6
- [x] Completed ✅ 2025-10-10
- [ ] Correct
- [x] Added to Anki ✅ 2025-10-10
A polynomial division resulted in the quotient $Q(x) = x^3 - 5x + 8$ and the remainder $R = -2$. If the divisor was $D(x) = x + 4$, write the original dividend $P(x)$ in standard form. (Hint: Use the formula $P(x) = D(x) \cdot Q(x) + R$).

#### Date: 2025-10-11
#### Subject: Synthetic Division (Beginner)

#### Question 7
- [x] Completed ✅ 2025-10-11
- [x] Correct ✅ 2025-10-11
- [ ] Added to Anki
Use synthetic division to divide the polynomial $P(x) = x^3 + 5x^2 - x - 25$ by the binomial $D(x) = x - 2$. Find the remainder $R$ and the quotient $Q(x)$.

#### Question 8
- [x] Completed ✅ 2025-10-11
- [x] Correct ✅ 2025-10-11
- [ ] Added to Anki
Given the polynomial $P(x) = x^4 - 2x^3 + 7x - 4$, perform synthetic division using the divisor $D(x) = x + 1$. What are the coefficients of the resulting quotient $Q(x)$?

#### Question 9
- [x] Completed ✅ 2025-10-11
- [x] Correct ✅ 2025-10-11
- [ ] Added to Anki
Perform synthetic division to divide $P(x) = 2x^3 - 3x^2 + 4x - 1$ by $D(x) = x - 3$. What is the remainder $R$? Based on the Remainder Theorem, what does this tell you about the value of $P(3)$?

#### Date: 2025-10-11
#### Subject: Synthetic Division (Set 3)

#### Question 10
- [x] Completed ✅ 2025-10-11
- [ ] Correct
- [x] Added to Anki ✅ 2025-10-11
The division of a polynomial $P(x) = 4x^3 + ax^2 - 19x + 6$ by the binomial $D(x) = x - 2$ results in a remainder of $R = 0$. Use synthetic division and the Remainder Theorem to find the value of the unknown coefficient $a$.

#### Question 11
- [x] Completed ✅ 2025-10-11
- [ ] Correct
- [x] Added to Anki ✅ 2025-10-11
Perform synthetic division to divide the polynomial $P(x) = 9x^5 + 12x^4 - 2x^2 + 5$ by the binomial $D(x) = 3x + 4$. State the quotient $Q(x)$ in standard form and the remainder $R$. (Remember to use zero placeholders and to adjust the quotient).

#### Question 12
- [ ] Completed
- [ ] Correct
- [ ] Added to Anki
Find the quotient $Q(x)$ and the remainder $R$ when $P(x) = x^4 - 10x^3 + 5$ is divided by $D(x) = x - 10$. Write your final answer in the mixed form $Q(x) + \frac{R}{D(x)}$. (Be careful with missing terms and coefficients.)