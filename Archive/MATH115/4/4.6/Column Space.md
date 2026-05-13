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
	- It is immediately true that since this is a [[Archive/MATH115/3/3.2/Matrix-Vector Multiplication|matrix-vector product]], then the resulting space will be a subspace of $\mathbb{R}^m$

- Finding the base for Col(A)
	- Recall that Col(A) = $\{A\vec{x}|x\in \mathbb{R}^n \} = \mathrm{Span}(\vec{a_{1}},\ldots, \vec{a_{n}}) = A\vec{x}$
	- Use [[Archive/MATH115/4/4.3/Extraction Theorem]] to find the basis of $\mathrm{Span}(\vec{a_{1}},\ldots, \vec{a_{n}})$ by carrying $A\vec{x}$ to rref.

- Note: It follows from above that $Dim(Col(A)) = Rank(A)$, as there will be $Rank(A)$ LI vectors in $Basis(Col(A))$.

*Examples (Excluding inline examples)* 
__

*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

