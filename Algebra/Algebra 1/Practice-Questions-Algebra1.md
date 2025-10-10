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