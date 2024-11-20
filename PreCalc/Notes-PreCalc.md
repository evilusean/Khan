Start: 07November2024

#### Preamble:
I had no notes on any of my courses, up until now, past sean appears to have just been copying and pasting syllabus'(i?) till now, started 2 years ago, because I thought 'you need math to code' - Nope. 
Since I want to take Electrical Engineering, I need to get my math up, So I can level up IRL, and escape frozen decadent rent seeking parasite infested overpriced economic zone failed state canada
Changed notes to '.md' so I can edit in obsidian, better UI than github, looks prettier.

### [Unit 1: Get ready for limits and continuity](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity)
#### 1:Limits and Continuity-2024-11-07
##### Evaluating Functions-2024-11-07 :
https://www.youtube.com/watch?v=kvGsIo1TmsM&t=2s&ab_channel=KhanAcademy
- Function = Takes an input and returns an output. - will be deterministic - you can not associate 2 different outputs to one input, or it won't be a function
- $f(x)$ \#most used way to describe a function
- $y = x + 1$ \#This can also be a function
###### Worked example: Evaluating functions from equation
https://www.youtube.com/watch?v=Id6UovYjd-M&t=58s&ab_channel=KhanAcademy
$f(x) = 49 - {x}^{2}$ =24
###### Worked example: Evaluating functions from graph
https://www.youtube.com/watch?v=kzYtx_AqzjM&ab_channel=KhanAcademy
find on a graph : $f(-1)$ =6
##### Evaluating Discrete Functions-2024-11-07:
https://www.youtube.com/watch?v=Ddw8u7nNmKs&ab_channel=KhanAcademy
$y=h(x)$ 
- When `x = 4` what is `y = ?` y = 3
- given the input, what is the output, it's easy on graphs, cause you just look up the x-axis, and find y
###### Worked example: evaluating expressions with function notation :
https://www.youtube.com/watch?v=uaPm3Tpuxbc
$-2 * f(-6) + g(1)$
#### 2:Inputs and outputs of a function-2024-11-07
###### Worked example: matching an input to a function's output (graph):
https://www.youtube.com/watch?v=0Rmmynff5Yc
find $g(x) = -2$ = -9
###### Worked example: two inputs with the same output (graph):
https://www.youtube.com/watch?v=qSktOkaW6EA&ab_channel=KhanAcademy
What is the value other than -5 for which $f(x) = f(-5)$ x = 4
#### 3:Composing functions-2024-11-07
###### Intro to composing functions:
https://www.youtube.com/watch?v=wUNWjd4bMmw&ab_channel=KhanAcademy
$f(x) = {x}^{2}-1$
- composing function = to build up a function by composing one function of others function, *nested functions* = $f(g(2))$ = Take the number 2, put it through the function `g` take that output an d put it through `f`
- in the video he has a chart where he is getting his $g(t)$ and a graph for $h(2)$ - so can't work out the formula
###### Intro to composing functions-Text :
[Link](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:untitled-447/a/introduction-to-function-composition)
 the amount of corn, `C`, in kilograms (kg), that he expects to produce if he plants corn on `a` acres of land.
- $C(a) = 7500a - 1500$
- If he planted 2 acres : $C( 2) = 7500( 2)-1500= {13{,}{500}}$ 
What Cam really wants to know is how much money he will make from selling this corn. So he uses the following function to predict the amount of money, `M` in dollars, that he will earn from selling `c` kilograms of corn.
- $M(c) = 0.9c - 50$
So if Cam produces `13,500kg` of corn, he can expect to make 
- $M({13{,}500})=0.9({13{,}500})-50=\${12{,}100}$
Notice that Cam has to use _two_ separate functions to get from acres planted to expected earnings. The first function, `C`, takes acres to corn, while the second function, `M`, takes corn to money.
So, to find a general rule that converts \[a\] acres directly into expected earnings, we can find the expression 
- $M(C(a))$
The function below converts acres planted directly into expected earnings. Let's use this new function to predict the amount of money that Cam would make from planting corn on two acres.
- $M(C(a))=6750a-1400$
- $M(C(2))=6750(2)-1400=\$12{,}100$
**composite function**. = Instead of substituting acres planted into the corn function, and then substituting the amount of corn produced into the money function, we found a function that takes the acres planted directly to the expected earnings.
###### Composing Functions-Text :
[Link](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:untitled-447/a/finding-and-evaluating-composite-functions)
If $f(x) = 3x - 1$ 
and $g(x) = {x}^{3}+2$ 
what is $f(g(3))$? 3 * 3 * 3 = 27 + 2 = 29 * 3 = 87 - 1 = 86
In general, to indicate function `f` composed with function `g`, we can write `f * g`, read as "`f` composed with `g`". This composition is defined by the following rule:
$(f\circ g)(x)=f(g(x))$
- - -
![[20241107062744.png]]
I'll break down how to solve this composition of functions step by step.
When we have $(h \circ g)(x)$, it means we're plugging function $g(x)$ into function $h(x)$. Let's follow the solution:
- First, we identify our functions:
- $g(x) = x + 4$
- $h(x) = x^2 - 2x$
- To find $(h \circ g)(x)$:
- *Take $g(x)$ and wherever you see $x$ in $h(x)$, replace it with $g(x)$*
- So we replace every $x$ in $h(x) = x^2 - 2x$ with $(x + 4)$
- Let's follow the steps:
- Start with $h(x) = x^2 - 2x$
- Replace $x$ with $(x + 4)$:
- $(x + 4)^2 - 2(x + 4)$
- Then expand:
- $(x + 4)^2$ becomes $x^2 + 8x + 16$ (using FOIL)
- $-2(x + 4)$ becomes $-2x - 8$
- Combine all terms:
- $x^2 + 8x + 16 - 2x - 8$
- $= x^2 + 6x + 8$ (final answer)
This is how we get the final composed function $(h \circ g)(x) = x^2 + 6x + 8$
To find $(h \circ g)(-2)$, you would simply plug in $x = -2$ into this final function:
$(-2)^2 + 6(-2) + 8 = 4 - 12 + 8 = 0$
- - - 
$f(x)=3x-5$
$g(x)=3-2x$
Evaluate $(g\circ f)(3)$
3 * 3 = 9 - 5 = 4 
-2(4) = -8 + 3 = `-5`
- - -
$f(t)=t-2$
$g(t)=t^2+5$
Find $(g\circ f)(t)$
Replace all instances of t with `t-2` so ${t}^{2}$ = $(t-2)(t-2)+5$ = `t2 -4t + 9`
- - -
$f(t)=t-2$
$g(t)=t^2+5$
Find $(f\circ g)(t)$
Replace all instances of t with ${t}^{2}+5$ = ${t}^{2}+3$ 
- *After you know the trick, it's way easier. Replace the first ones `g(t)` with the second ones* `f(t)` - I was wondering why you didn't have to balance each side of the equation at the start, it's replacement instead
###### Evaluating composite functions :
https://www.youtube.com/watch?v=lxtlwnCV-HM&ab_channel=KhanAcademy
$g(x) = {x}^{2} + 5x - 3$
$h(y) = {3(y-1)}^{2} - 5$
$(h \circ g)(-6) = ?$ you can rewrite this equation as $h(g(-6))$
`g(-6)` = (-6)(-6) + 5(-6) - 3 = 36 -30 -3 = `3` 
`h(3)` =  $3{(3-1)}^{2}-5$ = $3{(2)}^{2} -5$ = 12 - 5 = `7`
- '$\circ$' \#  the circle isn't just a weird way of saying multiply, it's actually a symbol that stands for *function composition symbol* 
###### Evaluate composite functions-2024-11-09
$g(x) = \frac{3}{x-2}$
$h(x) = 9x$
not writing out each question, each one is a pargraph. 

###### Evaluating composite functions: using graphs
https://www.youtube.com/watch?v=oORnGaJp1pk&ab_channel=KhanAcademy
Answer = 1 \# take the input of f (-5) and use that for g(-2)
###### Evaluate composite functions: graphs & tables
[Link](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:untitled-447/e/evaluate-composite-functions-from-graphs-and-tables)
###### Quiz 1:
[Link](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:untitled-447/quiz/xa350bf684c056c5c:get-ready-for-limits-and-continuity-quiz-1)
Future Sean : anything to the ${x}^{0}$ 0th power is equal to 1. I got one wrong because I assumed 0 = 0, even fractions.

#### 4:Piecewise Functions-2024-11-09 :
###### Introduction to piecewise functions
https://www.youtube.com/watch?v=tedzsRH0Jas&ab_channel=KhanAcademy
*PieceWise Function* = A function that is defined piece by piece for different intervals
for each interval or section it is defined as '$-9, -9<x\geq -5$' \# this will show that for the x axis -9 to -5, the value will be 9 on the y axis(yes, each one, it is flat), notice the ',' comma seperates the y value from x values, each interval will be multiple numbers on the x axis
- also note, that an interval is defined on the graph with an open $\circ$ circle to a closed circle
- also note, that all three cases are wrapped in the same '{' large curly brace
- open circle means that it is < or >
- closed circle means $\geq or \leq$
###### Worked example: evaluating piecewise functions
https://www.youtube.com/watch?v=hg2HR9zJFq4&ab_channel=KhanAcademy
${t}^{2} - 5t, t \geq -10$ \# this will have us replace the 't' with -10, so replace an 't'
$f(-10) = {-10}^{2}-5(-10)$ = 100 + 50 = *150*
- use the correct case for the function, there will be multiple intervals, so h(-3) would use the case with the value for -3, if that's unclear, just watch the video again around 1:45, it's only 5 mins long - don't want to write out all the superfluous stuff
${x}^{3}$ = ${-3}^{3}$ = *-27*
###### Evaluate piecewise functions :
[Link](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:piecewise-functions/e/evaluating-piecewise-functions)
###### Evaluate step functions :
[Link](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:piecewise-functions/e/evaluate-step-functions-from-their-graph)
###### Worked example: graphing piecewise functions
https://www.youtube.com/watch?v=PQiXRrT_14o&ab_channel=KhanAcademy
you can also do sloped lines, it doesn't have to be a flat interval, use formulas that include 'x'
###### Piecewise functions graphs
[Link](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:piecewise-functions/e/piecewise-graphs-linear)
###### Quiz 2:
[Link](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:piecewise-functions/quiz/xa350bf684c056c5c:get-ready-for-limits-and-continuity-quiz-2)
#### [5:Introduction to factoring-2024-11-13](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:introduction-to-factoring/v/factors-and-divisibility-in-algebra "Introduction to factoring")
###### Intro to factors & divisibility
https://www.youtube.com/watch?v=SjN3_xCJamA
*Factor* = A _factor_ of a number is a number that divides the given number evenly or exactly, leaving no remainder
What are the factors of *12*(what can multiply to get 12) = 1, 2, 3, 4, 6, 12
	`1 * 12 = 12` or `2 * 6 = 12` or `3 * 4 = 12` 
Is it divisible by a `#` ?
$(x+3)(x+7) = {x}^{2} + 10x + 21$ 
since we multiplied (FOIL) to get :
${x}^{2} + 10x + 21$ is a divisible by $(x+3) or  (x+7)$ 
$(x+3) or  (x+7)$ is a factor of ${x}^{2} + 10x + 21$
###### Intro to factors & divisibility-Text-2024-11-13:
[Link](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:introduction-to-factoring/a/intro-to-polynomial-factors-and-divisibility)
A **monomial** is an expression that is the product of constants and nonnegative integer powers of `x`, like $3x^2$. 
A **polynomial** is an expression that consists of a sum of monomials, like $3x^2+6x-1$
- In this lesson, we will explore the relationship between factors and divisibility in polynomials and also learn how to determine if one polynomial is a factor of another.
- In general, two integers that multiply to obtain a number are considered **factors** of that number.
- For example, since $14=2* 7$, we know that \[2\] and \[7\] are **factors** of 14.
- When two or more polynomials are multiplied, we call each of these polynomials **factors** of the product.
-  $2x(x+3)=2x^2+6x$. This means that `2x` and `(x+3)` are factors of $2x^2+6x$.
- Also, one polynomial is **divisible** by another polynomial if the quotient is also a polynomial.
- *Quotient* = A result obtained by dividing one quantity by another
-  $\frac{6x^2}{3x}=2x$  then $6x^2$ is divisible by `3x` and `2x`.
- In general, if $p=q*r$ for polynomials `p`, `q`, and `r`, then we know the following:
- \[q\] and \[r\] are factors of \[p\].
- \[p\] is divisible by \[q\] and \[r\].
- If something is divisible by something else then that something else is a factor
- *Why are we interested in factoring polynomials?*
- Just as factoring integers turned out to be very useful for a variety of applications, so is polynomial factorization!
- Specifically, polynomial factorization is very useful in solving quadratic equations and simplifying rational expressions.
###### Factoring with the distributive property-2024-11-13:
https://www.youtube.com/watch?v=mbb3msmX2xs&ab_channel=KhanAcademy
$4x +18$ rewrite as a product of 2 expressions (refactor it) = $2(2x) + 2(9) = 2(2x+9)$
$12 + 32y= 4(3) + 4(8y) = 4(3 + 8y)$
###### GCF factoring introduction-Quiz-2024-11-13:
[Link](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:introduction-to-factoring/e/gcf-factoring-introduction)
#### [6:Factoring quadratics intro](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:factoring-quadratics-intro/v/factoring-simple-quadratic-expression "Factoring quadratics intro")
###### Factoring quadratics as (x+a)(x+b)-2024-11-13:
https://www.youtube.com/watch?v=D3a8NnpQ2vU&ab_channel=KhanAcademy
$x^{2}-3x-10$ Factor this as the product of 2 binomials $(x+a)(x+b)$
$x^{2}+ax+bx+ab$ using FOIL this is what you should get
`ax + bx` needs to equal `-3x` and multiply to `-10`
Answer : $(x + 2)(x - 5)$
###### Factoring quadratics: leading coefficient = 1
[Link](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:factoring-quadratics-intro/a/factoring-quadratics-leading-coefficient-1)
In this lesson, you will learn how to factor a polynomial of the form $x^{2}+bx+c$ as a product of two binomials.
$(x+2)(x+4) = x^{2}+6x+8$
 *Factoring trinomials* :We can reverse the process of binomial multiplication shown above in order to factor a trinomial (which is a polynomial with 3 terms). $x^{2}+6x+8 = (x+2)(x+4)$
 - $x^{2}+5x+6 = (x+2)(x+3)$
 - $x^{2}+7x+10 = (x+2)(x+5)$
 - $x^{2}+9x+20 = (x+4)(x+5)$
 -  $x^{2}-5x+6 = (x-3)(x-2)$
 -  $x^{2}-x+6 = (x+2)(x-3)$
 *The sum-product pattern* = $(x+m)(x+n) = x^{2}+(m+n)x + m*n$
 **Can this factorization method be used to factor $2x^2+3x+1$?** = No. 
 - In general, the sum-product method is only applicable when we can actually write a trinomial as $(x+m)(x+n)$ for some integers `m` and `n`.
- This means that the leading term of the trinomial must be $x^2$ (and not, for instance, $2x^2$) in order to even consider this method. This is because the product of `(x+m)` and `(x+n)` will always be a polynomial with a leading term of $x^2$.
- not all trinomials with $x^2$ as a leading term can be factored. For example, $x^2+2x+2$ cannot be factored because there are no two integers whose sum is 2 and whose product is 2.
$x^{2}+5xy+6y^{2}$ = $(x+2y)(x+3y)$ = Uses the same process just with `y` though
 $x^4-5x^2+6$ = $(x^{2})^{2}-5x^{2}+6$ = $(x^{2}-2)(x^{2}-3)$
###### Factoring quadratics as (x+a)(x+b) (example 2)-2024-11-18
[Link-Lesson](https://www.khanacademy.org/math/get-ready-for-ap-calc/xa350bf684c056c5c:get-ready-for-limits-and-continuity/xa350bf684c056c5c:factoring-quadratics-intro/v/factoring-polynomials-1)
[Link-Course](https://www.khanacademy.org/math/get-ready-for-ap-calc)
- 2024-11-18-Just finished an email chain with admissions to university, apparently they think my grades from highschool 15 years ago are somehow relevant to how I can perform today, sorry, sweetie, some of us left highschool 15 years ago, others of us are still in highschool and like to be gatekeepers(you). I read history, economics, philosphy, and psychology for fun. The guy who didn't enjoy high school and never attended(WoW, I think my last year I had ~100 missed days ~3 months skipped, still passed, barely, I hated school, and still do. government indoctrinateSean camps/elaborate HumiliateSean ritual/conformie compliance test - I don't like people gatekeeping me who are my objective inferiors, vaxcattle, conformies) is also the guy who didn't take the mystery $cience juice because the TV told him to. We are not the same. I still haven't received one apology from the vaxcattle. Good riddance. At least I won't be spending 100k+ to be in adult daycare, infantilized idiots, surrounded by people I can't stand. If you are so smart, why are you taking experimental $hit to attend? Trust the $cience? You are the $cience. I'm the control group. Hopefully Trump Academy (free education-break the credentialism monopoly of marxists slow march through the institutions)/Trump University/TrUmp - I'm just mad that one of the few avenues to escape frozen decadent failed state of canada is closed down, where I now have to compete for coding jobs with half the GD world, some dude in punjab who hadn't seen a computer until his early 20's, now, somehow, has a masters degree in CompSci from the university of hyperBadi(or new new delhi), and is technically more employable than me, and now, with AI can LARP as competent. '"great projects/portfolio, but where is your piece of paper?"'. If a dude with a 77IQ can do it, what value is there really in that acheivement, a degree is now common. Credentialism, another beauracratic jboomer hangover, because they were too lazy to train people, and every problem they met was solved with an appeal to government. Whatever, at least I can escape canada 4 years sooner. Enjoy the indians, don't forget your boosters. Hopefully they can prop up your ponzi scheme, pay half their income in taxes, maintain a complex society and its systems. Good luck, Good bye, and Good Riddance.
- How do you avoid living in a failed state fighting for scarce resources surrounded by brainwashed idiots, and the millions of people they imported to prop up the ponzi scheme for a few more years? Get out of the state before it fails. Who did the best in Yugoslavia? The people who left. - I can't wait to not be around when the cops realize they aren't getting their pensions, and no one is paying linesmen in the middle of winter, and trucks aren't delivering because the loonie(lol, lmao) is WorthLess. That doesn't sound like a good time to me, you must stick around and clean up '"our"' mess. Nope, Lol, Lmao. Your mess, not my problem, I've received nothing but abuse for 3.5 decades, and it will take MINIMUM of 20 years to clean up, that's 55 years of suffering, for a bunch of abusive idiots, unironically not my problem, you guys have fun with that. I've already lost decades of time, because you idiots lied to me either through ignorance or malice, the results are the same, no mas, no more, you should be thankful that I am just leaving. 
- TLDR: Since I no longer am going to University, I no longer need math, I can focus more on languages/coding/escape/maybe do some EE for frEE, without a degrEE, if I have time for it. - If a person is abusive, you leave them. If a government is abusive, you leave them. If both the government and people are abusive, you, Lol, Lmao. 
- https://www.yourtango.com/sekf/berkeley-professor-says-even-outstanding-students-arent-getting-jobs
  Lol, Lmao. Just give up 4 years, and 100k for your piece of paper bro, to still not find a job, I have to compete with degree'd people to serve coffee(starbucks, tim hortons), coding= compete with half the world, who can afford to live on less than 2k a month, try living on less than 2k a month in the captured communist failed state of canada, literally impossible. Step 1) Escape. '"The system"' is fundamentally broken. The only '"winners"' are the ones who control the printing presses and the ones closest to the teat/spigot Vs Cantillion Effect. Can you compete with a central bank? Just bootstrap, and outwork the tail end of a ponzi scheme. Work hard, starve, can't afford rent or a house. Don't work hard, starve, can't afford rent or a house. Something has to give, this is untenable, this is unsustainable. P<P+I - Crack up Boom = Housing -> Insured by taxpayers(buyer of last resort, don't forget to vote) -> Banks -> Pensions -> Government Failure. = GGNoRM
  - I am jacks total and complete lack of incentive. - No one want's to work(for slave wages). Lol, Lmao. We are less free now than medieval peasents. You call this '"progress"'?  
  -  I pay half my income in taxes so a bunch of brainwashed idiots can afford(canadian MP's second highest paid in world-All in favor of giving ourselves pay raises say 'AYE', '"AYE!"', AYES HAVE IT-Democracy, Lol, Lmao.-We investigated ourselves and found no wrongdoing-Lol, Lmao.) to think up new and creative ways to make my life worse, while they get me into infinite debt, which I am the collateral on, when they create money from nothing, with interest, paid to '"bankers"', while they create artifical monopolies and scarcity, so I can barely afford food, and rent. They are raising taxes, and importing more people to suppress wages and raise housing prices. I now have to compete against half the world who use our housing market as a casino/money laundering, and '"private equity"', whom are backed by '"central banks"', to own a house, which I will never actually own, because you will never be able to stop paying taxes, or they take everything you have and throw you in jail. This is just slavery with extra steps. Whose the real idiot. The one who dilligently works to prop up that system? The 77IQ dude who is getting paid to be there by a corrupt system? The 50% whom are dependant on a corrupt bankrupt system? or the one who says 'Lol, Lmao'?
  - Oh, and even after all that, '"they"' are trying to pop off WW3, so they can do their 'Reset', and they want us to fight and die for '"them"'? Lol, Lmao. I'm just not going to do it is all, I'm just not going to die for '"them"'. HAHAHAHA
  - Ask not what you can do for your country. Ask what your country did to you.
  - No TaxASean without RepresentASean. We are under hostile foreign occupySean. 