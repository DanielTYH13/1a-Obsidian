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

Resistance is defined as

$dR = \frac{dl}{A\sigma}$

For any conductor with constant cross section area and conductivity, 

$R = \frac{\Delta x}{A \sigma}$

And equivalently, for non constant cross section:

$R = \displaystyle \int^b_{a}\frac{b-a}{A(x)\sigma}dx$

---
Derivation

Consider a conductor with uniform cross section area and length. Then the charge within the any section of the conductor is given by:

$Q = n A \Delta x$

Where n is the electrons per volume (number density).

Then, we have that velocity of a charge is given by $dv = \frac{dx}{dt}$. So then:

$dQ = nAdvdt$
$I = \frac{dQ}{dt} = nAdv$

We can define another value, J, to be the current density:

$J = \frac{I}{A} = n dv$

However, since an E field is required to cause current, we can write conductance (How much current density is created wrt E field) as:

$\sigma = \frac{J}{E} = \frac{I}{AE}$

And it turns out that conductivity is a property intrinsic of the medium of conductance. Ie, it depends only on the material. 

Now, we want to find the correlation between Voltage and Current. 

Recall that for a constant E field along a line, we have that 

$|dV| = Edl$
$E = \frac{I}{A\sigma}$
$|dV| = \frac{I}{A\sigma}dl$
$|dV| = \frac{dl}{A\sigma}I$
$dR = \frac{dl}{A\sigma}$

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

