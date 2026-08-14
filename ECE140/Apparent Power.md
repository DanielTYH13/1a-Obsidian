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
___

We can represent power as the product of the voltage and current phasors.

$V = V_{rms} \angle \theta_{v}$
$I = I_{rms} \angle \theta_{i}$

$S = VI^* = V_{rms}I_{rms} \angle(\theta_{v}-\theta_{i})$

The "$^*$" is called a complex conjugate because it is the conjugate of $\theta_{v}- \theta_{i}$, and thus you must take the conjugate of $I^*$ if you are looking for an expression of I wrt V, and leave it if V wrt I (depending on you reference point).

If you expand this using eulers identity, it so happens to work out that the real, and imaginary components of this phasor will be the magnitude of real and reactive power given in [[AC Instananeous Power]].

![[Pasted image 20260811193354.png|350]]

---

Multiplication of the phasors of two signals does not provide a sinusoidal signal, so it's output cannot be taken literally.

That being said, we can represent signals non literally as their root mean square phase shifted by a given angle. Where the root mean square is like the dc equivalent of the signal. 

When we take the product of these two phasors, we get a new phasor with the "dc equivalent" preserved as the product of the 2 rms values, and with a phase shift. 

While this is not a literal representation of the signal, all information encoded in the multiplicands have also be preserved in the product.

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

