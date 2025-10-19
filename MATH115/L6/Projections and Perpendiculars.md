---
tags:
  - "#review"
  - MATH115
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
---
*Key Concepts:*
___

Projection Definition:
- Given two vectors: $\vec{u},\vec{v}\in\mathbb{R}^n$, such that the vector $\vec{u} = \vec{u_{x1}} + \vec{u_{x2}}$, where $\vec{u_{x1}}$ is a scalar mult. of $\vec{v}$ and $\vec{u_{x2}}$ is orthogonal to $\vec{v}$
- The projection of $\vec{u}$ on to $\vec{v}$ is the scalar multiple $c$ in $\vec{v} = c\vec{u}$
- The algebraic definition is: $proj_{\vec{v}}\vec{u} = \frac{\vec{u}\cdot\vec{v}}{\|\vec{v}\|^2}\vec{v}$
	- Note that this can also be defined as $proj_{\vec{v}}\vec{u} = \frac{\vec{u}\cdot\vec{v}}{\vec{v}\cdot\vec{v}}\vec{v}$
		- This is because the dot product of two vectors onto itself is ==its norm squared==
-
- ![[Pasted image 20251003150851.png|225]]
<!--SR:!2025-10-06,1,230-->

Perpendicular Definition:
- Given two vectors: $\vec{u},\vec{v}\in\mathbb{R}^n$, such that the vector $\vec{u} = \vec{u_{x1}} + \vec{u_{x2}}$, where $\vec{u_{x1}}$ is a scalar mult. of $\vec{v}$ and $\vec{u_{x2}}$ is orthogonal to $\vec{v}$
- The perpendicular of $\vec{u}$ onto $\vec{v}$ is $\vec{u} - proj_{\vec{v}}\vec{u}$
	![[Pasted image 20251003150851.png|225]]

Derivation of the Projection:
- Given that we set up the following conditions for the projection:
	- $\vec{u} = \vec{u_{1}} + \vec{u_2}$
	- $\vec{u_{1}} = t\vec{y}$
	- $\vec{u_{2}}\cdot\vec{v}= 0$
- Our goal is to determine t, and thus find the projection onto v.
	- $0 = \vec{u_{2}}\cdot\vec{v}$
	- $0 = (\vec{u}-\vec{u_{1}})\cdot \vec{v}$
	- $0 = \vec{u}\cdot\vec{v} - \vec{v}\cdot\vec{u_1}$
	- $0 = \vec{u}\cdot\vec{v} - \vec{v}\cdot(t\vec{v})$
	- $0 = \vec{u}\cdot\vec{v} - (\vec{v}\cdot\vec{v})t$
	- $0 = \vec{u}\cdot\vec{v} - t\|\vec{v}\|^2$
	- $t = \frac{\vec{u}\cdot\vec{v}}{\|\vec{v}\|^2}$
	- ==$proj = t\vec{v} = \frac{\vec{u}\cdot\vec{v}}{\|\vec{v}\|^2}\vec{v}$==

Derivation of the formula of a vector perpendicular:
- The vector perpendicular is the vector projection of $\vec{u}$ onto the vector $\vec{k}$, which is perpendicular with $\vec{v}$: $perp_{\vec{v}}\vec{u} = proj_{\vec{k}}\vec{u}$ where $\vec{k}\cdot\vec{v} = 0$ and $\|\vec{v}\| = \|\vec{k}\|$
	- This is geometrically equivalent to the ==component of $\vec{u}$ that is orthogonal to $\vec{v}$.== Since ==$proj_\vec{v}\vec{u}$ is collinear with $\vec{v}$, then $\vec{u} - proj_{\vec{v}}\vec{u}$ is the $perp_\vec{v}\vec{u}$==
	- 

*Examples (Excluding inline examples)* 
___

*Significant Theorems:
___

Definition of a Vector projection:
- Let $\vec{u}, \vec{v} \in \mathbb{R}^n$
- The projection of $\vec{u}$ onto $\vec{v}$ is defined as either:
	- ==$proj_{\vec{v}}\vec{u} = \frac{\vec{u}\cdot\vec{v}}{\|\vec{v}\|^2}\vec{v}$==
	- ==$proj_\vec{v}\vec{u} = \frac{\vec{u}\cdot\vec{v}}{\vec{v}\cdot\vec{v}}\vec{v}$==

Definition of a Vector Perpendicular:
- Let $\vec{u}, \vec{v} \in \mathbb{R}^n$
- The perpendicular of $\vec{u}$ onto $\vec{v}$ is defined as:
	- $\vec{u} - proj_\vec{v}\vec{u}$


*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

