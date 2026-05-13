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

- Def'n: Given the matrix $A \in M_{mxn}(\mathbb{R})$ and matrix $B \in M_{nxk}(\mathbb{R}^n)$, the matrix product ==$AB = \begin{bmatrix} A\vec{b}_{1} & A\vec{b}_{2} & \cdots & A\vec{b}_k\end{bmatrix}$==, with dimensionality ==$AB \in M_{mxk}$.==
	- (A) The matrix product of A and B exist ==$\iff \#columns_{A} = \#rows_{B}$== 
	- In other words, the k'th collumn of AB is ==the matrix-vector product of A and the k'th collumn of B.==
		- It becomes immediately clear why (A) is true.
			- Given $n = \#columns_{A} = \#rows_{B}$,
			- The k'th collumn ==lives in $\mathbb{R}^n$.==
			- The matrix $A^T$ ==has collumns that live in $R^n$==
			- If ==for any $n \ne \#columns_{A}, \space n \ne \#rows_{B}$, then the dot product is undefined.==
			- Thus ==the matrix product would be undefined.==
			- Thus, $n = \#columns_{A} = \#rows_{B}$

- Dimensionality:
	- Since the ==matrix-vector product for $A\in M_{mxn}(R), \space \vec{x}\in \mathbb{R}^n$ lives in $\mathbb{R}^m$, the matrix product== lives in m rows and k collumns.

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

