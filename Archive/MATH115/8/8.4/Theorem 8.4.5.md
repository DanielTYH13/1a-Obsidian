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

- Given a matrix $A\in M_{nxn}(\mathbb{R})$, then the sum of the algebraic multiplicity of each distinct eigenvalues must equal to n:
	- $a_{\lambda 1} + \cdots + a_{\lambda k} = n$
	- This makes sense as the [[Archive/MATH115/8/8.2/Characteristic Polynomials|characteristic polynomial]] will be of degree n, and thus must have n real or imaginary roots. 

- Given a matrix $A\in M_{nxn}(\mathbb{R})$, the sum of the geometric multiplicity of each distinct eigenvalues satisfies:
	- $k \le g_{\lambda 1} + \cdots + g_{\lambda k} \le n$
		- It is garunteed for each eigenvalue to have at least one eigenvector, which means at least a geometric multiplicity of one for every eigenvalue k. 
		- It is at max possible for each eigenvalue to have an equal $a_{\lambda i}$ and $g_{\lambda i}$, and by part 1, this means that the max would be n.
			- Ie, the sum of the geometric multiplicities only equals n if $a_{\lambda i} = g_{\lambda i}$ for all i. 

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

