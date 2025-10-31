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

- Given a matrix $A \in M_{mxn}(\mathbb{R})$, the column space of A:
	- $Col(A) = \{A\vec{x} | x\in \mathbb{R} \}$
		- Or in other words, the span of A if A was a set of its column vectors
		- This is why it is named the Column Space. 
	- It is immediately true that since this is a [[Matrix-Vector Multiplication|matrix-vector product]], then the resulting space will be a subspace of $\mathbb{R}^m$

- Finding the base for Col(A)
	- Recall that Col(A) = $\{A\vec{x}|x\in \mathbb{R}^n \} = \mathrm{Span}(\vec{a_{1}},\ldots, \vec{a_{n}})$
	- Recall that by reduction thm, $\mathrm{Span}(Basis(A)) = Span(\vec{a_{1}}, \ldots , \vec{a_{n}}) = Col(A)$
	- Then, $Basis(Col(A)) = Basis(\vec{a_{1}}, \ldots, \vec{a_{n}})$ 
	- Use extraction thm to find $Basis(\vec{a_{1}}, \ldots, \vec{a_{n}})$

- Note: It follows from above that $Dim(Col(A)) = Rank(A)$

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

