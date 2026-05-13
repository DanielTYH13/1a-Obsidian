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

- Given a matrix $A \in M_{mxn}(\mathbb{R})$, the null space of A:
	- $null(A) = \{\vec{x} \in \mathbb{R}^n | A\vec{x} = \vec{0} \}$
		- In other words, it is the set of solutions to the homogenous linear system defined by A.
			- Immediately, $Null(A)$ will be a subspace of $\mathbb{R}^n$
			- Dim(A) = n if Rank(Dim(A)) = n
				- This means that there are n linearly independant vectors in the set of Dim(A), which also means that they can only span up to n dimensions. 
			- Dim(A) < n if Rank(Dim(A)) < n
				- This means that there are less than n linearly independant vectors in Dim(A), which means it cannot span n.

- How to find the base for Null(A).
	- Recall that Null(A) is the set of all solutions $\vec{x}$ for the homogenous system $A\vec{x} = \vec{0}$
		- When solving a linear system using an aug. matrix, we can find the general solution for any arbitrary individual solution $\vec{x}$.
		- The null space must include the 0 vector and this solution will have parameters, which if we think of as constants, is just another lin comb $B\vec{w} = Span(Null(A))$. In other words, B spans $Null(A)$.
		- B decomposed into a set of column vectors will always be linearly independant, and thus is the base of Null(A)a
		- #TODO ask Prof Trelford about this.

- Note: It follows from above that $Dim(Null(A)) = n-Rank(A)$. This is called $nullity(A)$, and is the rank of the basis of Null(A) (This is derived from [[Archive/MATH115/2/2.3/Ranks of Matrices and System Rank Theorem|SRT(2)]])
	- This is because Subspace Null(A) is the general solution to the homogenous system, which has the number of free variables n - Rank(A)
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

