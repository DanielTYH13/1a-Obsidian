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

Thm: Matrix Equality Theorem (MET):
- Given matrices $A, B \in M_{mxn}(\mathbb{R})$, $\vec{x}\in \mathbb{R}^n$ $A = B \implies$For all vectors $\vec{x},$ $A\vec{x} = B\vec{x}$
	- Follow up: Prove that if for one vector $\vec{x}$ where $A\vec{x} \ne B\vec{x}$, then $A \ne B$. 
		- Hint, maybe use MET to show that if the identity vectors work, then all others must work? ==Exer.==
- Proof:
	- ==Given that $A\vec{x} = B\vec{x}$ for all vectors $\vec{x} \in \mathbb{R}^n$, then $A\vec{e}_{i}= B\vec{e}_i$,  where $\vec{e}_i$ is the identity vector for the row $i = 1, \ldots, n$. Since $A\vec{e}_{i}= \vec{a}_{i,}A\vec{e}_{i}= \vec{b}_i$, then we have $A = \begin{bmatrix}\vec{a}_{i} & \cdots & \vec{a}_{n}\end{bmatrix} = \begin{bmatrix} \vec{b}_{1} & \cdots & \vec{b}_{n} \end{bmatrix} = B$== (Exer, do this proof pls :D)
	- QED!


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

