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
Given a line with some uniform distribution of charges, we can calculate the total charge at any given point like so:

![[Pasted image 20260615143104.png|375]]

We know that for point placed away from this line, the horizontal displacement component is constant, and the y component changes. 

Using the already known equation for E field in cartesian coordinates, we get:

$\vec{E} = k\frac{Q}{x^2 + y^2}\frac{x\hat{x} + y\hat{y}}{\sqrt{x^2 + y^2}}$

By symmetry, we can say that all vertical components of the resulting E field will be cancelled out across the line of symmetry (In this specific case). Thus we get:

$\vec{E} = kx\frac{Q}{(x^2 + y^2)^\frac{3}{2}}$

Where $\vec{E}$ is measured solely in the x direction (Positive to left). Convince yourself that the polarity will be flipped if the Q is negative, and similarily the force will be flipped if q is opposite polarity to Q.

Now, we want to sum all components of electric field from the line based on some infinitesimal charge along the direction of the line. We can express this charge as $dQ = \rho dy$. Thus the integral becomes:

$\vec{E} = kx\rho \displaystyle \int^{1/2}_{-1/2} \frac{1}{(x^2 + y^2)^{\frac{3}{2}}}dy$

This evaluates to:

$\vec{E}  = \frac{k\rho y}{x\sqrt{x^2 + y^2}} \bigg\rvert^{1/2}_{-1/2}$

---
E field at x >> L

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

