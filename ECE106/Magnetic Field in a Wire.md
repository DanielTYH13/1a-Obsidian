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

*Note, this only applies exactly to closed wires. It is only an approximation for not closed wires*.

Consider a wire which has a circular cross section. We wish to find $\vec{B}$.

We will use amperes law, and a circular contour as this maintains symmetry from the point currents. 

---
r < R (Magnetic field inside the wire).

$\displaystyle \oint_{C} \vec{B} \cdot \bar{dL} = \mu_{0}I_{enc}$

The enclosed current changes for the radius of the contour. We can use the most simple enclosing surface - a plane bounded by the countour.

$I_{enc}=\frac{I_{total}}{A_{total}}\cdot A_{plane}$       

This is a great example of how density allows us to look at individual points - to find a differential current per differential area (Which is a rate of change, actually!) and multiply it (integrate it) by the area (Or total differential area units.) 

$\displaystyle \oint_{C}\vec{B}\cdot \bar{dl} = \frac{\mu_{0} I\pi r^2}{\pi R^2}$
$\displaystyle \vec{B} \cdot \hat{dl} \oint_{C}1\cdot \bar{dl} = \frac{\mu_{0} I \pi r^2}{\pi R^2}$
$\displaystyle \vec{B} = \frac{\mu_{0} I \pi r^2}{\pi R^2 \cdot 2\pi r} = \frac{\mu_{0} I r}{2\pi R^2}$

---
r $\ge$ R (Magnetic field outside the wire).

$\displaystyle \oint_{C} \vec{B} \cdot \bar{dL} = \mu_{0}I_{enc}$
$\displaystyle \vec{B} \cdot \hat{dl} \oint_{C}1\cdot \bar{dl} = \mu_{0}I$
$\displaystyle \vec{B} \cdot \hat{dl}  = \frac{\mu_{0}I}{2\pi R}$

---
Graph:
![[Pasted image 20260805120902.png|350]]

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

