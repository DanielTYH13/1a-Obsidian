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
Since we have a cross product, we need to figure out how to expand it into something we can integrate. 

---
The most obvious way, and arguably the most inconvenient way, is to represent each vector in its components then take the cross product.

This will work, but is cumbersome. 

---
If you are able to convert to polar coordinates, then you can use the form:

$a \times b = |a||b|sin(\theta)$

Since in the [[Biot Savart Law]], the second term is a unit vector, then it collapses to just:

$dq \vec{v} \times \vec{R} = |dq\vec{v}|sin(\theta) \vec{b}$, where $\vec{b}$ is the vector of the field.

---
This is a corrolary of the above. 

In some cases, if you are able to convert a vector into its components, then by definition, the theta between any given component and the other vector will be constant (Given that the other vectors direction also stays constant)

In this case, you can set a fixed $\theta$ and integrate using cartesian coordinates. 

Ie, you either need a known expression for theta and differentiate wrt theta, or a known theta and differentiate wrt cartesian.

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

