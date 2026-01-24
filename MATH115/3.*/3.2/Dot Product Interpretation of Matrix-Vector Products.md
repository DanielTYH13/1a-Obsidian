---
tags:
  - "#review"
  - "#flashcards"
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
---
*Key Concepts:*
___

- Given the general matrix $A \in M_{mxn}(\mathbb{R})$, $\vec{v} \in \mathbb{R}^n$, the matrix vector product can be thought of as:
	- Transposing an ==individual row of A==
	- Multiplying each component of the transposed row ==with the respective component of $\vec{v}$==
	- ==Summing== those components
		- This gives you the i'th ==component of the resultant vector.== 
	- Repeating ==$m$== times. 
- This is functionally equivalent to ==taking the dot product of each row and $\vec{v}$.==
	- Given the matrix $A \in M_{mxn}(\mathbb{R})$, you can represent A as $A = \begin{bmatrix} \vec{a_{1}} & \vec{a_{2}} & \cdots & \vec{a_{n}}\end{bmatrix}$
		- However, we cannot use the dot product method with this form, as we have the collumns instead of rows of $A$.
			- To represent the matrix A in terms of its rows:
				- Take ==its transpose $A^T = \mathrm{transpose}(A)$==
				- Represent $A^T$ as ==a row vector of collumn vectors:==
				- ==$A^T = \begin{bmatrix}\vec{a^T_1}&\vec{a^T_2}&\cdots&\vec{a^T_m}\end{bmatrix}$==
			- From this point, we have ==$A\vec{v}=\begin{bmatrix}\vec{a^T_{1}}\cdot \vec{v} \\ \vec{a^T_{2}}\cdot \vec{v} \\ \vdots \\ \vec{a^T_{n}}\cdot \vec{v}\end{bmatrix}$==

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

