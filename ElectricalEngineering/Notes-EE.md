Started : 23November2024
[Course Link](https://www.khanacademy.org/science/electrical-engineering)
# Electrical Engineering
## Preamble
I figure I'll start both math, pre-calculus for review, and Electrical Engineering at the same time, if I get in to January semester, I don't have as much time as I did with coding - scratch that - roastie gatekeepers on a highschool power trip think my grades from 15 years ago are somehow relevant, I run circles around your average normie, but I don't have a piece of paper, actual discriminASean, too smart for university, Lol, Lmao. 
## Unit 1: Intro to Electrical Engineering-2024-11-23
### Electric Current-2024-11-24
[Electric Current Video](https://www.youtube.com/watch?v=ZRLXDiiUv8Q&ab_channel=KhanAcademy)
- Charge = 2 kinds of charges `+` positive and `-`negative. 
- Electrostatics = Opposites attract. Same Repel. Negative Repels Negative, Pos Repels Pos.
- one place we get 'charges' is from copper wire `Cu 29` = 29 protons and electrons(neutral, same amount), that last orbital on copper has just one electron, which is the easiest to pull away and have it participate in conduction 
- current = `q/sec` (charge per second)
- Shockingly(heh), water does not conduct, $H^2O$ has no free electrons, you need to add some NaCl(salt) to allow it to conduct - this goes against conventional wisdom "don't be in the water when there is lightning" - `Na`(sodiums) wil go towards the `+` positive charge and the `Cl`(chlorine) will go towards the `-` charge
### Current Direction-2024-11-25
[Video Link](https://youtu.be/4frpZ4Q0q58)
- +Current = $q^-$ = Movement of charge the electrons move towards the  $q^-$ 
- $q/sec$ = amount of current flowing at any given time - flow rate
- _1747_ - `Ben Franklin` said that the charges of an electron move _1747_ - he assigned the `+` and `-` to the electron charge, before people knew there was an electron charge 
- _1897_ - `JJ Thompson` discovered the electron charge $e^-$ 150 years after Ben Franklin
- So, because of this the `-` negative symbol is actually inverted from the `+` symbol, the `-` negative symbol actually pushes out and the `+` symbol actually receives electrons - counterintuitive
- Just out of curiosity, has anyone actually seen an electron? Even with a so called 'Electron Microscope' - or is it just one of those 'trust me, bro' things that we just regurgitate to each other for decades - we can define the behaviour (+/- charges of each element +attractSean), but not what it is. - just looked it up, it is one of those 'trust me, bro' things, Lol, Lmao. We don't even know what we don't know. 
### Voltage-2024-11-25
[Video Link](https://youtu.be/k9SwNST1eW0)
[Voltage Wiki](https://en.wikipedia.org/wiki/Voltage)
- Voltage $\Delta V$= current flow rate = Latin Volt 'Roll' 'Turn' 'Round' = amount of charge per second
- Voltage = Potential Energy 
- Gravity and Voltage are similar ideas - Potential Energy from an object at the top of a mountain is converted to kinetic energy through gravity, along the way down the kinetic energy bumps into trees - Instead of a mountain, you have a battery, which delivers electrons to the top of the mountain(`-`battery), if you release it, the electrons return to the bottom of the mountain`+`, along the way down the mountain, you can put in different circuit components(resistors/capacitors/etc) - the amount of voltage is proportional to the height of the mountain, a high voltage, is a high mountain
### Conventional current direction-2024-11-26
[Video Link](https://youtu.be/17EhKw2tsu4)
- **Electron Current** = The electrons are repelled by the '-' minus voltage, and attracted to the '+' voltage
- **Conventional Current Direction** = the direction that a positive charge would move, so inverse of the *Electron Current*, confusing, but it goes out from the '+' in to the '-' - even though the electrons are traveling the opposite way, from '-' to '+' in actuality. The nomenclature uses Conventional Current Direction(even though, it's backwards), from now on when 'Current' is mentioned, it will be the Conventional Current
### Preparing to study electrical engineering-2024-11-26
[PreRequisite Links](https://www.khanacademy.org/science/electrical-engineering/introduction-to-ee/intro-to-ee/a/ee-preparing-to-study-electrical-engineering)
#### Math
##### Math fundamentals
- [Equation of a line, slope, y-intercept](https://www.khanacademy.org/math/cc-eighth-grade-math/cc-8th-linear-equations-functions)
- [Quadratic formula](https://www.khanacademy.org/math/algebra-home/alg-quadratics#alg-solving-quadratics-using-the-quadratic-formula)
- [Exponents](https://www.khanacademy.org/math/algebra-basics/core-algebra-exponent-expressions)
- [Radians](https://www.khanacademy.org/v/introduction-to-radians)
- [Vectors, vector addition](https://www.khanacademy.org/v/introduction-to-vectors-and-scalars)
- [Solving simultaneous equations](https://www.khanacademy.org/math/algebra-basics/alg-basics-systems-of-equations)
- [Complex numbers](https://www.khanacademy.org/v/introduction-to-i-and-imaginary-numbers)

##### Trigonometry

- Definitions of sine, cosine, and tangent from the sides of a triangle 
    
    (SOHCAHTOA)
    
    ![](https://cdn.kastatic.org/ka-perseus-images/a4a4527d40bc4e146c10a56730abd71db01cfd25.svg)
    $$\begin{array}{lll}
\sin \theta 
= \dfrac{\text{opposite}}{\text{hypotenuse}}\qquad
& \textbf S\text{ine is } \textbf O\text{pposite over } \textbf H\text{ypotenuse.} \\
\\
\cos \theta
= \dfrac{\text{adjacent}}{\text{hypotenuse}} 
& \textbf C\text{osine is } \textbf A\text{djacent over } \textbf H\text{ypotenuse.} \\
\\
\tan \theta
= \dfrac{\text{opposite}}{\phantom{0}\text{adjacent}\phantom{0}}
& \textbf T\text{angent is } \textbf O\text{pposite over } \textbf A\text{djacent.} \\
\end{array}$$
- For further review, see [trigonometry](https://www.khanacademy.org/math/trigonometry).

##### A few concepts from calculus

- [Limits](https://www.khanacademy.org/math/differential-calculus/limits-topic)
- [Derivative](https://www.khanacademy.org/math/calculus-home/taking-derivatives-calc)
- [Derivative notation](https://www.khanacademy.org/math/ap-calculus-ab/ab-derivative-intro/ab-derivative-intuition/a/derivative-notation-review)
These math fundamentals, and a little bit of terminology from calculus will get you all the way through resistor networks and circuit analysis methods.
#### Calculus

As we move beyond resistor circuits and start to include capacitors and inductors, we need calculus to understand how they work. Think of calculus as a _corequisite_ in parallel with electrical engineering. You don't need to have a complete calculus background to get started, but it is helpful before too long. Many students learn calculus at the same time as introductory electrical engineering classes.

These are the calculus concepts we use in electrical engineering at Khan Academy:

- [Derivative of simple functions (xⁿ where n is an integer](https://www.khanacademy.org/v/calculus-derivatives-2-5-new-hd-version) )
- [Derivative of eˣ](https://www.khanacademy.org/v/derivatives-of-sin-x-cos-x-tan-x-e-x-and-ln-x)
- [Notation for integral](https://www.khanacademy.org/v/antiderivatives-and-indefinite-integrals)
- [Integral of xⁿ](https://www.khanacademy.org/v/indefinite-integrals-of-x-raised-to-a-power)
- [Evaluating definite integrals](https://www.khanacademy.org/v/riemann-sums-and-integrals)
- [Derivative of sine and cosine](https://www.khanacademy.org/v/derivatives-of-sin-x-cos-x-tan-x-e-x-and-ln-x)
- [Line integral](https://www.khanacademy.org/v/introduction-to-the-line-integral)

Calculus kicks in when we get to circuits involving time—circuits with capacitors or inductors. We have to use calculus to get a meaningful solution.

Differential equations: When we solve first-order differential equations, we walk through the solution step by step (example: [RC](https://www.khanacademy.org/a/ee-rc-natural-response)). The most advanced problems involve second-order differential equations, and again, we go through the solution step by step.

Electrostatics: The electrostatics section has the most advanced topics we cover in electrical engineering. This sequence develops precise definitions of electric field and voltage. My goal is to have you appreciate (but not recreate) the derivations of voltage, and the field equations for point, line, and plane of charge.
#### Physics

- High school physics: [force](https://www.khanacademy.org/v/newton-s-second-law-of-motion), [energy, and work](https://www.khanacademy.org/v/introduction-to-work-and-energy)
- Force problems using vectors: [here](https://www.khanacademy.org/v/visualizing-vectors-in-2-dimensions), and [here](https://www.khanacademy.org/a/what-are-inclines).
- [Scientific notation](https://www.khanacademy.org/v/scientific-notation-old)
- [Significant figures](https://www.khanacademy.org/v/significant-figures)

#### Chemistry

- High school chemistry: [elements, atoms](https://www.khanacademy.org/v/elements-and-atoms), the [electron and nucleus](https://www.khanacademy.org/a/discovery-of-the-electron-and-nucleus), [mole](https://www.khanacademy.org/v/the-mole-and-avogadro-s-number)
### Basic electrical quantities: current, voltage, power-2024-11-26
