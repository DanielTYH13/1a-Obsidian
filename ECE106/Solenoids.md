---
tags:
  - review
  - ECE106
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: ECE106 U1
---
*Key Concepts:*
___

Solenoids are many many loops of current carrying wire stacked on top of each other into a coaxial cylinder.

For computational efficiency, ideal solenoids will be assumed to be ideal wires with infinite length.

---
B Field inside a solenoid. (My derivation)

The B Field inside an ideal solenoid is constant. This can be shown by using symmetry and treating the cylinder as a collection of cross rectangular cross sections opposing to each other across the axis. 

Since each loop of wire is closed, we can use ampere's law as a box around each of the cross sectional lines. 

This behaves the same as using ampere's law on an infinite plane. By using ampere's law on both lines, we can come up with a B field in the middle of the field to be:

$\vec{B} = \frac{\mu_{0}J}{2}\cdot 2 = \mu_{0}J =\frac{\mu_{0}{IN}}{L}$ (Inside the solenoid) ($I_{total} = IN$)
$\vec{B} = 0$ (Outside the solenoid)

This is similar to how we derived the field inside the capacitor. Down to the geometry of the derivation. 

![[Pasted image 20260805123901.png|475]]

---
B Field inside a solenoid (Prof Derivation)

The B field inside an ideal solenoid is constant. This can be shown using ampere's law.

Draw a cross section of a rectangle that pass through the side of the solenoid and is collinear with the axis.

Since each loop of wire is closed, we can use Ampere's law.

$\displaystyle \oint_{C}\vec{B}\cdot \bar{dL} = \mu_{0}I_{enc}$
$I_{enc} = I_{loop}N$

The field at any point is constant by propogating symmetry. Moreover, the direction is coaxial, cancelling out the side lines. Finally, the solenoid is assumed to be infinite, so the field outside the solenoid is 0. 

$\vec{B} = \frac{\mu_{0}IN}{L}$           


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

