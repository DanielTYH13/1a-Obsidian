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

Lagranges method says that for an continuous and differentiable function $\mathbb{R}^2 \to \mathbb{R}$ $f(x)$, along some constraint $g(x, y) = c$, then critical points all lie at the solution of the system of equations obtained through:

$\nabla f = \lambda \nabla g$
$g(x, y) = c$

and 

$\nabla g = 0$
$g(x, y) = c$

---
Geometric Interpretation

The whole backing of Lagrange's method is that all critical points will lie on areas where the constraint is tangent to the respective level curve of the function. This proof is left unstated here, but it is helpful to think about it as walking up a hill. 

To stop walking up / down, you must intersect the angle of walking parallel to the hill (where the gradient vectors are parallel). Thus, only at these points there is extrema in your path along the hill (not always, imagine an inflection point). Thus, only at these points can extrema exist on the function along the constraint.

Continuing:
- $g(x, y) = c$ can be rearranged to be $y = h(x)$, and it is just a 2 variable function that lies on the xy plane (It is the constraint).
- In the form $g(x, y) = c$, it resembles the level curve of some 3d function g(x, y).
- Allowing g(x, y) to be its own function is just a computational convenience, enabling us to easily compute the tangent vector for any level curve along g(x, y)

Process:
- Setting $\nabla f = \lambda \nabla g$ finds all points where level curves for f and g are parallel, including along g(x, y) = c
	- Think of each level curve along g(x, y) as an infinite collection of  constraints, of which don't matter. g(x, y) is simply a convenience because it contains the constraint we want.
- Setting g(x, y) eliminates, all non constraint curves



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

