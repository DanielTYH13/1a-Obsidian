---
tags:
  - review
  - ECE140
sr-due: 2026-11-06
sr-interval: 100
sr-ease: 250
TARGET DECK: ECE 140
---
*Key Concepts:*
___

Inductors are components that "Resist changes in current". They use the principle of magnetic fields to do this. 

The precise definition of an inductors behaviour is given by:

$V = L \frac{\text{d}I}{\text{d}t}$

---
In terms of impedence:

- L is the scaling factor from I to V
- The derivative of current is the phase shifting factor.

This matches with the formula for impedence of inductors, which is given as:

$Z = j\omega L$

---
Some consequences of this:

- Current cannot be discontinuous, as this would require an infinite voltage.
- Voltage can be discontinuous. 

---
Phase change:

You can find V wrt to I by letting I be a function of time (I = sin(t))

$V = L \frac{dI}{dt}$
$V = L \cos(t)$
$V = L \sin(t + \pi/2)$

Therefore, in the purely inductive case, I follows V by a phase shift of pi/2

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

