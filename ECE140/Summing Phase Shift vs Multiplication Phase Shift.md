---
tags:
  - review
  - ECE140
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: ECE 140
---
*Key Concepts:*
---

A natural consequency from the identity:

$re^{i\phi} = r\cos \phi + jr \sin \phi$

Is that:

$e^{i \theta} \cdot re^{i\phi} = e^{i\theta} \cdot r \cos \phi + je^{i\theta} \cdot r \sin \phi$

Which is mathematically obvious but may feel weird. One is a scaling transformation, then a phase shift, while the other is the sum of a scaling operation, and a multiplication of an imaginary number?

To comfort you, just realize that the second term is another signal shifted by $\frac{\pi}{2}$, and look at the following photo:

$e^{i \theta} \cdot re^{i\phi} = e^{i\theta} \cdot r \cos \phi + e^{i\theta + \frac{\pi}{2}} \cdot r \sin \phi$

![[Pasted image 20260727175947.png]]

Neat, right? They sum to a phase shifted signal perfectly.

___

*Respective Proofs*
___
$e^{i \theta} \cdot re^{i\phi} = e^{i\theta} \cdot r \cos \phi + e^{i\theta + \frac{\pi}{2}} \cdot r \sin \phi$

*Common Mistakes:*
___

*Terms and Definitions:*
___

