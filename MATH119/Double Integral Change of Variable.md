---
tags:
  - "#review"
  - MATH119
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: MATH119 U1
---
*Key Concepts:*
___

For a double integral, you can change the variable to go from a messy domain to a clean domain (Ie, where the bounds of integration are constant):

![[Pasted image 20260612134046.png|400]]

---
The Jacobian:

The Jacobian matrix is a differential matrix (And thus a linear transformation which is one to one) mapping any du, dv in u, v space to dx, dy in x, y space. 

The Jacobian matrix is given as: $\frac{\partial (x, y)}{\partial (u, v)} = \left[ \begin{smallmatrix} \frac{\partial x}{\partial u} & \frac{\partial x}{\partial u} \\ \frac{\partial x}{\partial u} & \frac{\partial x}{\partial u}\end{smallmatrix}\right]$

Thus, to map from a differential A (dA) in u, v space to x, y space, we scale dudv by the det of the jacobian, which is by definition the stretching factor of a linear transformation. 

This is analogous to 1D change of variable, which is given by $du = u'(x)dx$, where $u'(x)$ is the scaling factor for $du$ at any $x$ in the x domain.

---
Changing Bounds

You start a double integral change of variable by looking at the bounds, and seeing what type of transformation will give rectangular bounds. This usually comes first before substitution.

Ex. in the case of a semicircle, sides of the semicircle can be represented as:

$y = \pm$
which can be represented $r, \theta = \arctan(\frac{a}{0})$


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

