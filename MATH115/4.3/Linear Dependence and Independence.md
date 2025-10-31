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

- Def'n: Given the set of k vectors $S = \{\vec{v_{1}}, \ldots, \vec{v_{k} \}}\in \mathbb{R}^n$, $c_{1}, \ldots, c_{k}\in \mathbb{R}$, then the set is
	- Linearly Dependent $\iff c_{1}\vec{v_{1}} + \cdots + c_{k}\vec{v_{k}} = 0$ for not all $c = 0$. 
		- This is true because if you move ==any of the vectors over to the other side, you can then show that it is a product of the linear combinations of other vectors==
	- Linearly Independent $\iff c_{1}\vec{v_{1}} + \cdots + c_{k}\vec{v_{k}} = 0$ for $c_{1}, \ldots, c_{k} = 0$, or in other words, the trivial solution.

- Given the set of k vectors $S = \{\vec{v_{1}}, \ldots, \vec{v_{k} \}}\in \mathbb{R}^n$, $c_{1}, \ldots, c_{k}\in \mathbb{R}$ $\iff c_{1}\vec{v_{1}} + \cdots + c_{k}\vec{v_{k}} = \vec{0}$:
	- You can determine if the set S is linearly dependant or independant by representing the $\vec{0}$ as a linear system in matrix vector form: $\vec{c}A = \vec{0}$
		- $\vec{c} = \begin{bmatrix}c_{1}\\ \vdots \\ c_k\end{bmatrix}$
		- $A = \begin{bmatrix} \vec{v_{1}}& \cdots & \vec{v_{k}}\end{bmatrix}$
	- Then, by augmenting $\vec{0}$ onto the matrix $A$, you can use [[Ranks of Matrices and System Rank Theorem |SRT]] to determine the number of solutions. 
	- Theorem: Given the set S and its corresponding matrix A, the set S is linearly independant $\iff \mathrm{Rank}(A) = k$  
		- Proof: By SRT(2), the general solution to a linear system has n (which in this case is k) - Rank(A) solutions. 
		- Thus, when Rank(A) = k, there is only one solution. Namely, the $\vec{0}$ solution.
	- Corollary:
		- Given k > n, then S is linearly dependant.
			- Proof: Recall that the maximum rank of a system is $\mathrm{min}(m, n)$. Thus, if n < k, there is no way for the rank to = k, and thus to system is linearly dependant.

Thm - Dependency Theorem:
- The set S is linearly dependent $\iff$ $\vec{v_{i}} \in \mathrm{Span}(S \backslash v_{i})$ for any $i = 0, 1, \ldots, k$
	- In other words, S is linearly dependant if and only if any of its members can be represented as a linear combination of the other vectors.
	- Assuming S is linearly dependent, use the def'n:
		- $c_{1}\vec{v_{1}} + \cdots + c_{k}\vec{v_{k}} = 0$
		- You can then isolate for any non-zero vector-scalar product on one side.
		- Then, using the definition of a [[Spanning Sets|spanning set]], it becomes clear that
			- The vector you just isolated for can be represented as a linear combination of the set exclude S. 
			- By definition, this means that the vector is in $\mathrm{Span}(S\backslash \vec{v_{i}})$


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

