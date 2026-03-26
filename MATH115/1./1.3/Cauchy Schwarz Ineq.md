---
tags:
  - "#review"
  - MATH115
---
*Key Concepts:*
___
-  $(\vec{x} \cdot \vec{y}) \le \| \vec{x} \| \|\vec{y}\|$ 
	- The CS inequality states that given any two vectors, the absolute of the dot product is less than or equal to the product of the norms of the vectors: 
	- Geometrically, this can be proven by the identity that: $\vec{x}\cdot\vec{y} = \|\vec{x}\|\|\vec{y}\|\cos\theta$
		- Since $\cos\theta$ has a range restricted to $[-1, 1]$, the dot product will never exceed the product of the norms of the vectors.
	- Algebraic proof: i am not sure but one day I'll figure it out
	- Note: $|\vec{x}\cdot\vec{y}|\le\|\vec{x}\|\|\vec{y}\| \iff -\|\vec{x}\|\|\vec{y}\| \le \vec{x}\cdot\vec{y} \le \|\vec{x}\|\|\vec{y}\|$
		- ie, the CS ineq is true if and only if the negative product of the norms of x and y are less than or equal to x dot y are lower than or equal to the product of the norms of x and y.
			- This is useful, because even though this may seem trivial, it may be helpful to know that the RHS is true just from realizing the LHS. 
	- Also note: $-1\le \frac{\vec{x}\cdot\vec{y}}{\|\vec{x}\|\|\vec{y}\|}\le 1$
		- This can be derived from the above statement by dividing all sides by the product of the norms of the vectors
		- However, it can also be understand as a normalized vector cannot be greater than 1 or less than -1.
	
	
*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

