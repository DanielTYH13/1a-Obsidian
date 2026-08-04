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
Using the imaginary plane, we can represent cos and sin as the real parts of an imaginary function:

Phase: $r e^{j\phi}$
- It is a static point along the circle. Like the 0th degree term in a polynomial.
Function with Frequency: $r e^{j\omega t}$
- It is a function with "speed" (frequency) in relation to time

This lends to easy computation of phase shift:

$re^{j\omega t}e^{i\phi} = r e^{j \omega t + \phi}$

Later, you can use the functions $R\{\}$ and $I\{\}$ to extract the sin and cosine signals you need. 

---
What does the imaginary part represent?

Not anything tangible. It depends on your interpretation, and interpretation is subjective. But one interpretation is that the imaginary part of the function is just a byproduct of the coordinate system. It is just there to facilitate the use of imaginary exponentials, and doesn't actually mean anything. 
Impedance is defined as $\frac{V(t)}{I(t)}$. 

For a capacitor circuit, it is given as $\frac{1}{j\omega c}$

For an inductor circuit, it is given as $j \omega L$

Mathematically, it is the phase difference between the voltage and the current (90 degree phase shift, by j)

---
Why do we do this?

Sin and cosine are the vertical and horizontal components of a cirle wrt the angle. Thus, we can represent sin and cosine wrt time, as the components of a point travelling on a circle with constnat angular velocity. 

The complex plane lends itself to very convenient and elegent mathematical operations of the circle [[Imaginary Plane Notation]]. 

To borrow these operations, we use the fundamental relationship of sin, cosine with the circle to represent them in the imaginary plane. 

This allows us to avoid cumbersome use of sin and cosine functions themselves and creates a very elegent representation of signals.

Intuitively, think of a point on a circle as a point along a cycle. All properties relate to this point. Thus, we can represent all said properties as points on a circle - on the cycle - in the imaginary space.

The imaginary circle is just another coordinate domain, just like the polar domain, the cylindrical domain, the cartesian domain.

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

