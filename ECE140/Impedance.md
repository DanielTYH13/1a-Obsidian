---
tags:
  - review
  - ECE140
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: ECE 140
---
*Key Concepts*
___
Impedence is given as an imaginary number, where there is a real part and an imaginary part:

$Z = R + jX$
R is resistance 
X is reactance

Physically, some of the signal is only scaled, and some of it is scaled and also phase shifted. 
- The resistence scales it some amount
- The reactance also scales it, but phase shifts it too
- The sum of the two signals results in a total scaling and shifting.

The properties of impedence are the same as normal resistance.
- In series, they add
- In parallel, you take the reciprocal of the sum of the reciprocals.

Resistors: Z = R
Capacitors: $Z = \frac{1}{j\omega C}$
Inductors: $Z = j\omega L$

---

You can convert from form $a + jb$ into form $r e^{i\theta}$, where $r = \sqrt{a^2 + b^2}$, $\theta = \arctan(\frac{b}{a})$. This is derived from a triangle.

Magnitude of impedence is just given by |Z|. It is the real multiple of the impedence if you turn it into $e^{j\theta}$.

The Angle of impedence is given by $\angle Z$. It is the phase shift and is $\theta$ if you convert impedence into form $r e^{i\theta}$

---
What is impedence, exactly? 

Impedence is the relationship between voltage and current, when either or is not constant (V or I is a function of time). We assume that this function is sinusoidal. 

For purely resistive circuits, this would not matter. Current and Voltage are related to each other by a scaling factor, and either changes wrt the other instantly. Thus, they are the two signals are always in phase with each other, and impedence is as simple as a scaling factor.

However, when capacitors or inductors are introduced, they cause phase shift between voltage and current [[ECE140/Capacitors|Capacitors]], [[Inductors]]. 

Thus, the relationship $\frac{V(t)}{I(t)}$ is not a constant anymore. It is a function that depends on time, which scales either V or I to fit with the phase and scaling shift. t

Imaginary numbers are the perfect fit for this. Since they encapsulate sin and cos function with easy algebra, you can easily determine the real part of $\frac{V(t)}{I(t)}$ if you represent V and I in imaginary exponential form. 

---
Remark:

Isn't it great how well the use of imaginary exponents works in this context?

And it happens that this *must* be true. If we derive $\frac{V(t)}{I(t)}$, we must end up with an expression that gives us $V(t) = \frac{V(t)}{I(t)} I(t)$. It is just that the algebraic properties of imaginary exponents works out so nicely, that this becomes a few line calculation instead of an identity riddled proof. 

*Examples (Excluding inline examples)* 
___

*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

