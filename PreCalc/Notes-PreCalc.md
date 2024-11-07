Start: 07November2024

#### Preamble:
I had no notes on any of my courses, up until now, past sean appears to have just been copying and pasting syllabus'(i?) till now, started 2 years ago, because I thought 'you need math to code' - Nope. 
Since I want to take Electrical Engineering, I need to get my math up, So I can level up IRL, and escape frozen decadent rent seeking parasite infested overpriced economic zone failed state canada
Changed notes to '.md' so I can edit in obsidian, better UI than github, looks prettier.

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
- Take $g(x)$ and wherever you see $x$ in $h(x)$, replace it with $g(x)$
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















