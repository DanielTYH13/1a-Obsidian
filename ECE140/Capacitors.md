---
tags:
  - review
  - ECE140
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: ECE 140
---
*Key Concepts:*
___

Capacitors are components that "Resist changes in voltage". They use the principle of electric fields to do this. 

The precise definition of a Capacitor's behaviour is given by:

$I = C \frac{\text{d}V}{\text{d}t}$

---
In terms of impedence

- The value of $\frac{1}{C}$ is the scaling factor from I to V
- The derivative of voltage is the phase shifting factor.

This explains the formula for a capacitors impedence

$Z = -j\frac{1}{\omega C}$

---
Some consequences of this:

- Voltage cannot be discontinuous, as this would require an infinite current.
- Current can be discontinuous. 

---
Phase change:

You can subsitute an expression for V to find I wrt to V:

$I = C\frac{dv}{dt}$
$v(t) = \sin(t)$
$I = C \cos(t)$
$I = C \sin(t + \frac{\pi}{2})$

Therefore, in a purely capacitive case, current "leads" voltage by a phase shift of pi/2.

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

