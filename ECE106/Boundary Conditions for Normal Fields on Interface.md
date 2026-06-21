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

The normal E field along an interface are related by:

$\vec{D}_{1} + \vec{D}_{2} = \rho$
$\epsilon_{1} \vec{E_{1}} + \epsilon_{2} \vec{E_{2}} = \rho$

Ie, the normal E field is discontinous if surface charge density does not equal 0, and continous otherwise. 

---
Derivation

Create a Gaussian pillbox enclosing an interface.

![[Pasted image 20260620173015.png]]

We have that

$\Phi \epsilon = \displaystyle \int_{s}\vec{D} \cdot \overline{dA} = Q_{e}$
$\displaystyle \int_{sides}\vec{D} \cdot \overline{dA} + \int_{top+bottom}\vec{D} \cdot \overline{dA} = Q_{e}$

If we shrink the size of the sides towards zero, the pillbox remains gaussian and we get 

$\displaystyle \int_{top}\vec{D} \cdot \overline{dA} + \int_{bottom}\vec{D} \cdot \overline{dA} = Q_{e}$

Assuming the pillbox is small enough that the field is approximately constant across the top and bottom, we have:

$\vec{D_{1}} \cdot \hat{A_{t}} A_{t}+ D_{2}\cdot \hat{A_{b}} A_{b} = Q_{e}$
$\vec{D_{n1}} A_{t}+ D_{n2} A_{b} = Q_{e}$
$\vec{D_{n1}} + D_{n2} = \frac{Q_{e}}{A} = \rho$

Since we assume that the charge lies only on the interface, we can simplify into rho. For an infinitesimaly small pillbox, we do not need to worry about the scope of surface charge density, and only look at it at a point.

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

