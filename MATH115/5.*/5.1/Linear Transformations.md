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

- A transformation is defined to be linear iaoi the following are true for $\vec{x}, \vec{y} \in \mathbb{R}, c \in \mathbb{R}$, and assuming the domain / codomain for the transformation f(x):
	- $f(\vec{x} + \vec{y})$ = $f(\vec{x}) + f(\vec{y})$
	- $f(c\vec{x})$ = $cf(\vec{x})$

- A good way to encapsulate this is checking if the following is true:
	- $f(c_{1}\vec{x} + c_{2}\vec{y}) = c_{1}f(\vec{x}) + c_{2}f(\vec{y})$.
	- This encapsulates both of the conditions for linearity. 

- It follows that linear transformations preserves:
	- Zero vectors: $T(0 \vec{x}) = 0T(\vec{x}) = \vec{0}$
	- Negatives: $T(-\vec{x}) = -T(\vec{x})$

- Relating linear and matrix transformations:
	- Given the transformation T(x) is linear, then for $T(\vec{x})$, 
		- $T(\vec{x}) = T(x_{1}\vec{e_{1}} + \cdots + x_{n}\vec{e_{n}})$
		- $T(\vec{x}) = x_{1}T(\vec{e_{1}}) + \cdots x_{n}T(\vec{e_{n}})$
		- $T(\vec{x}) = [T]\vec{x}$, where $[T]$ is the matrix composed of collumns $T(\vec{e_{1}}), \ldots, T(\vec{e_{n}})$
			- $[T]$ is the standard matrix of $T(\vec{x})$
	- It follows that any linear transformation can be expressed as a matrix transformation.
	- Theorem: A transformation is linear iaoi it can be represented as a matrix transformation.

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

