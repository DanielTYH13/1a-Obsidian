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

Given the disk of charge:

![[Pasted image 20260615151432.png|450]]

We have that for any charge on the disk,

$\vec{E} = k\frac{Q}{r^2 + y^2} \frac{r \hat{r} + y\hat{y}}{\sqrt{r^2 + y^2}}$

An infinitesimal charge Q can be represented $dQ = \rho dr$. Thus the double integral becomes integrating from r=0 to r=R and then integrating from 0 to $2\pi$

$\vec{E} = k\frac{Q}{r^2 + y^2} \frac{r \hat{r} + y\hat{y}}{\sqrt{r^2 + y^2}}$
$\vec{E} = k\frac{Q}{(r^2 + y^2)^{\frac{3}{2}}} y\hat{y}$

$\vec{E}_{t}= \displaystyle \int^{2\pi}_{0}\int^{R}_{0} \frac{ y k \rho}{(r^2 + y^2)^\frac{3}{2}} drd\theta$

Notice that the e field of each line does not depend on $\theta$, and thus the second integral is just the multiple of the inner integral by $2\pi$

The integral evaluates to:

![[Pasted image 20260615152338.png|725]]

---
Values of the E field in special cases.

Notice that for a very large R, we get a constant E field. Similarily, for y is very small, we get a constant E field. 

This means that for an infinite disk, and being infinitely close to the disk, we get a constant E field of $\frac{\rho}{2 \epsilon_0}$, irrespective of distance.

It so happens that this relationship shows for all points on a disk, leading to all electric field lines being parallel. 

![[Pasted image 20260615152758.png]]

*Examples (Excluding inline examples)* 
___

Try deriving using Gauss's law for the infinite plane case or the close to plane case. 

*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

