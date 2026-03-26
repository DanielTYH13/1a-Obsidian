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

- Given the matrix $A \in M_{nxn}(\mathbb{R})$, then we have by definition of [[Eigenvalues and Eigenvectors]], 
	- $A\vec{x} = \lambda \vec{x}$
	- $A\vec{x} - \lambda \vec{x} = \vec{0}$
	- $A\vec{x} - \lambda I \vec{x} = \vec{0}$
	- $(A - \lambda I)\vec{x} = \vec{0}$
- Now, we can solve this system algebraically. 
- Some requirements:
	- We have that $\vec{x} \ne 0$ by definition of an eigenvector, as it is trivial. 
	- Thus, we also have by [[Matrix Invertibility Criteria]] that for there to be nontrivial solutions to this system, $det(A-\lambda I) = 0$, ie it is not invertible
		- It follows that matrix A is invertible iaoi 0 is not an eigenvalue of A. 

- Finding Eigenvalues:
	- Given the above, the scalar value $\lambda$ is an eigenvalue iaoi $det(A - I\lambda) = 0$

- Finding Eigenvectors:
	- For any given eigenvalue, the corresponding eigenvectors are the solutions to:
		- $(A - \lambda I)\vec{x} = \vec{0}$

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

