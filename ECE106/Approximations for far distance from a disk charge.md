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
For a disk charge, if Z >> r, the E field can be approximated as:

$\vec{E} = \frac{Q}{4 \pi \epsilon_{0} z^2}$

---
Given a disk charge, recall that the resultant electric field along the axis is given by:

$\vec{E} = \frac{\rho}{2 \epsilon_{0}} (1 - \frac{z}{\sqrt{z^2 + R^2}})$

We also know that for z >> r, we see that $\vec{E}$ becomes very close to, but not exactly, 0 (This is important as for things like gps, the E fields relevant are in the orders of magnitudes of -20 - n/c):

$\vec{E} = \frac{\rho}{2 \epsilon_{0}} (1 - \frac{z}{\sqrt{z^2 + R^2}})$
$\vec{E} = \frac{\rho}{2 \epsilon_{0}} (1 - \frac{1}{\sqrt{1 + (\frac{R^2}{z^2} )}})$

It helps to make an approximation for E field for z >> r by using:

$(1 + x)^n \approx 1+nx, |x| << 1$
$x =\frac{R^2}{z^2}$

$\vec{E} = \frac{\rho}{2 \epsilon_{0}} (1 - (1+x)^{-1/2})$
$\vec{E} = \frac{\rho}{2 \epsilon_{0}} \frac{R^2}{2z^2}$
	
Substituting $\rho = \frac{Q}{A} = \frac{Q}{\pi r^2}$:

$\vec{E} = \frac{Q}{4 \pi \epsilon_{0} z^2}$

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

