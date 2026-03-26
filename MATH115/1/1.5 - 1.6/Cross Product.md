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

- The cross product only exists in $\mathbb{R}^3$ and $\mathbb{R}^7$?, and not in any other dimension.

- In order to calculate the cross product of two vectors in $\mathbb{R}^3$, follow to the following shorthand:
	- Arrange the two vector as so: $\begin{bmatrix}x_{1} \\ x_{2}\\ x_{3}\end{bmatrix} \times \begin{bmatrix} y_{1}\\ y_{2}\\ y_{3} \end{bmatrix}$
	- Begin by "Blocking out the first row"
	- Multiply the top left by the bottom right, then subtract by the top right multiplied by the bottom left. 
	- Repeat for all rows
	- Then, add the sum of the first row's operation, subtract the second, and add the third. 

- The cross product of two non-collinear vectors will always be orthogonal to those two vectors.
	- This can be proven by the identity
		- $\vec{x} \cdot (\vec{x}\times\vec{y}) = 0$
		- $\vec{y} \cdot (\vec{x}\times\vec{y}) = 0$
	- This can be proven, but not necessary (Just show that any general eq $\vec{y} \cdot (\vec{x}\times\vec{y}) = 0$, using algebra)

- The properties of the Cross Product: (For $\vec{w}, \vec{x}, \vec{y} \in \mathbb{R}$, and $c \in \mathbb{R}$)
	- $\vec{x} \times \vec{y} \in \mathbb{R}^3$. Any two vectors crossed with each other lives in R^3
	- $\vec{x} \times \vec{0} =  \vec{0} \times \vec{x} = \vec{0}$
	- $\vec{x} \times \vec{x} = 0$
		- $\vec{x} \times t\vec{x} = 0$
	- $\vec{x} \times \vec{y} = -(\vec{y} \times \vec{x})$: This is called anti-commutivity
	- $(c\vec{x})\times \vec{y} = c(\vec{x} \times \vec{y}) = \vec{x} \times (c\vec{y})$
	- $\vec{w} \times (\vec{x} \pm \vec{y}) = (\vec{w} \times \vec{x}) + (\vec{w} \times \vec{y})$: Left commutitivity
	- $(\vec{x} \pm \vec{y})\times \vec{w} = (\vec{x} \times \vec{w}) + (\vec{y} \times \vec{w})$: Right commutitivity
	- *Warning*: The cross product is not associative. Therefore, when finding the cross product between multiple vectors, you must use brackets. Otherwise, it will be ambiguous. 

- Since vectors are non-positional, vectors that share the same point can be dispersed to those which don't, and vice versa. 



*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

