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

The tangential component of the E field along the interface between two mediums are always equal. 

---
Derivation:

For any closed path, we have that $\displaystyle \int_{l} \vec{E} \cdot \overline{dl}$ = 0. This can be thought of as a version of conservation of energy, since E is conservative. 

Then, for any interface layer, we can draw a rectangle around the interface like so:

![[Pasted image 20260620171939.png]]

Where the integral then becomes (The integrand has been ommitted for brevity)

$\displaystyle \int^d_{a} + \int^c_{d} + \int^b_{c}+\int^a_{b} = 0$

Then, if we shrink the width of the rectangle to an infinitesimal amount, the integral from c to b and a to d dissapear, as we are integrating over 0 distance:

$\displaystyle \int^c_{d} +\int^a_{b} = 0$

Then, assuming the rectangle is small enough, we assume E field to be constant across the path, thus 

$\vec{E_{1}} \cdot \hat{dl_{1}} dl_{1} + \vec{E_{2}} \cdot \hat{dl_{2}} dl_{2} = 0$
$\vec{E_{1t}} dl_{1} - \vec{E_{2t}} dl_{2} = 0$
$\vec{E_{1t}} = \vec{E_{2t}}$

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

