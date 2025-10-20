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

- Given the sets A and B, $A = B \iff A \subseteq B \land  B \subseteq A$. 
	- This is used when proving that the Span of a set is equal to another set. For example, if Span(S) = $\mathbb{R}^n$. 
		- You just need to prove subseteq twice. [[Proving Subsets of Vector Sets (In particular for Spanning Sets)|See how to prove that one set is a subset or equal to another]].

- 2: Proving $\mathrm{Span}(S)\subseteq \mathbb{R}^n$.
	- Using the (1) from [[Spanning Set Theorems]], we know that given $\vec{v}\in \mathbb{R}^n$ and the arbitrary variable vector $\vec{x} \in \mathbb{R}^n$, then 
		- $\vec{v} \in \mathrm{Span}(S) \iff A\vec{x} = \vec{v}$ is defined and consistent. (Meaning that $A\in M_{mxk}(\mathbb{R}), m = n$ - or in other words, the dimensionality of each vector in the spanning set must be n). If $m < n$, then it is impossible to achieve a lin comb of dimensionality $n$.
			- To prove that this is always true, then use [[Ranks of Matrices|SRT(3)]].
			- Reduce to REF, and if the rank of $Span(S) = n$, then by SRT(3), the system is consistent for all given vectors in $\mathbb{R}^3$
			- 

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

