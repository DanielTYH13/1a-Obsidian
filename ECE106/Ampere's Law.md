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
André-Marie Ampère discovered that the line integral of the magnetic field enclosing a current carrying **closed path** will be the same regardless of path.

$\displaystyle \int_{R}\vec{B} \cdot \bar{dl} = \mu_{0}I_{enc}$, where $I_{enc}$ is the current captured by any surface with bounds of the contour for the line integral.

The capturing surface's form does not matter, as $I_{enc} = \displaystyle \int_{S}J \cdot \bar{dA}$ is defined by a cross product, which compensates for deformed surfaces creating more cross section with the current carrying wire. It is a theorem that you can prove.

This is very similar to Gauss's law for electric fields!

---
Assuming we know that the line integral is irrespective of path, we can derive the integral using the most straight forward way - a circle in polar coordinates:

$\displaystyle \int_{0}^{2\pi}\frac{\mu_{0}I}{2\pi r}\hat{\phi} \cdot \bar{dl} =$
$\displaystyle \int_{0}^{2\pi}\frac{\mu_{0}I}{2\pi r}\hat{\phi} \cdot r d\phi \hat{\phi} =$ This is a great example to build intution of the Jacobian.
$\displaystyle \frac{\mu_{0}I}{2\pi r} r\int_{0}^{2\pi} \hat{\phi} \cdot d\phi \hat{\phi} =$ 
$\displaystyle \frac{\mu_{0}I}{2\pi} \int_{0}^{2\pi} d\phi \hat{\phi} =$ The dot product when two vectors are collinear is product of the magnitudes
$\displaystyle \frac{\mu_{0}I}{2\pi } 2\pi =$
$\displaystyle \mu_{0}I$

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

