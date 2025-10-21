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

- Def'n: Given the matrix $A = \begin{bmatrix} \vec{a}_{1} & \vec{a}_{2} & \cdots & \vec{a}_{n}\end{bmatrix}$ and $\vec{x} \in {\mathbb{R}}^n$, the matrix-vector product $A\vec{x} = x_{1}\vec{a}_{1} + \cdots + x_{n}\vec{a}_{n}$.
	- Ie, given a matrix A, the product of the matrix is the ==linear combination where the component vectors are the collumn vectors of A and the coefficients are the scalar components of vector X==
		- This also means that the form $A\vec{x}=\vec{b}$ can be used to ==define linear systems of equations.== **Exer, expand the general form of $A\vec{x}=\vec{b}$** **into a system of linear equations.**
- Note -> in order for a vector matrix product to be defined, the vector MUST ==live in $\mathbb{R}^n$, where n is the number of collumns in the matrix.==
	- For example, if you try to multiply a vector in $\mathbb{R}^3$ and a matrix in $M_{mx2}$, then it is undefined as there is no corresponding collumn vector from the matrix for component 3 of the vector. 
- Given matrix $A \in M_{mxn}(\mathbb{R})$, and $\vec{v}\in \mathbb{R}^n$, the resulting matrix-vector product has dimenionality of $\mathbb{R}^{m}$.
	- This is because ==regardless of the # of collumns n, the matrix product is defined such that each row corresponds to a component of the resultant vector==
		- This is much easier to understand using the [[dot product interpretation of matrix-vector products]]

- #TODO Explain why matrix vector mult is defined in this way. 

- #TODO consolidate below information with above information

- There are a few ways to define matrix-vector mult between $A = \begin{bmatrix}\vec{a}_{1} & \vec{a}_{2} & \cdots & \vec{a}_{n} \end{bmatrix} \in M_{mxn}(\mathbb{R}), \vec{x}\in \mathbb{R}^n$:
	- 1. (Simplest way). Take the transpose of the column vector $\vec{x}$, ==and multiply $\vec{a}_{j}$ by the $\vec{x}_{j}$ component. Then, add all of $\vec{a}_j$ to get the matrix-vector product.==
		- Visually, this looks like =="Appending" the row vector onto the top of the matrix, and then taking the scalar product of the corresponding components of x down onto each component of the column vectors, then adding up all the rows of this new matrix.==
	- 2. (This builds upon 1.) Take the transpose of ==each row vector $\vec{a}_{i}$, and then take the dot product of $a_{i}^T$ with $\vec{x}$. ==
		- This is identical to 1, ==just that you're transposing the matrix first==
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

