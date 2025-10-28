---
tags:
  - "#review"
  - MATH115
---
*Key Concepts:*
___
- The dot product is given by: $\vec{x} \cdot \vec{y} = x_{1}y_{1}+\dots+x_{n}y_{n}$
- Geometrically, the dot product is given by: $\vec{x} \cdot \vec{y} = \| \vec{x} \| \|\vec{y}\|\cos{\theta}$

*Significant Theorems:*
___
- Properties of dot products:
	- ==$\vec{x}\cdot\vec{y} \in \mathbb{R}^n$== Dot products in $\mathbb{R}^n$ are closed
	- ==$\vec{x}\cdot\vec{y} = \vec{y}\cdot\vec{x}$== The dot product is commutative
		- This can be trivially proven by using commutivitiy of scalar-scalar multiplication to rearrange the order of the components in the dot product, and then using the definition of the dot product.
	- ==$\vec{x}\cdot\vec{0} = 0$== Any vector dotted with the 0 vector is 0
		- This is pretty self explanatory, all components are multiplied by 0, thus giving a sum of 0.
	- ==$\vec{x}\cdot\vec{x} = \|\vec{x}\|^2$== The dot product of a vector with itself is its norm squared
		- This is given by: $$
\begin{align}
\vec{x}\cdot\vec{x} &= x_{1}x_{1}+\dots+x_{n}x_{n} \\
& = x_{1}^{2}+\cdots+x_{n}^{2} \quad \text{This erases all of the positive or negatives, essentially absoluting it}\\
& = \sqrt{x_{1}^{2}+\cdots+x_{n}^{2}}^{2}\\
& = \|\vec{x}\|^{2} \quad \text{Definition of the norm of a vector}
\end{align}
	$$
	- ==$(c\vec{x})\cdot\vec{y} = c(\vec{x}\cdot \vec{y})$== The dot product 
		- This is true because all corresponding terms of $\vec{x}$ and $\vec{y}$ are multiplied together along with c. This means that you can use the vector distributive property to factor out c, giving you the definition for $\vec{x}\cdot\vec{y}$.
	- ==$\vec{w}\cdot(\vec{x}\pm\vec{y}) = (\vec{w}\cdot\vec{x}) \pm (\vec{w}\cdot\vec{y})$ ==
		-  This is true because the LHS expands to $\vec{w}\cdot\begin{bmatrix}x_{1}+y_{1}\\ \vdots \\ x_{n}+y_{n}\end{bmatrix}$
		- Once you do this vector, it becomes a vector of w_n times (x_n + y_n). You can then use scalar distributive property, and then use the scalar commutative and associative property to group all w_nx_n terms together, and same for w_ny_n. Then, by definition of dot product, you get the RHS.
*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

