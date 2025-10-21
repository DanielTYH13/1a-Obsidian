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

- 1. Given the sets A and B, ==$A = B \iff A \subseteq B \land  B \subseteq A$.== **Exer. Set Equality Restrictions**
	- This is used when proving that the *Span of a set is equal to another set*. For example, if Span(S) = $\mathbb{R}^n$. 
		- You just need to prove ==subseteq twice. [[Proving Subsets of Vector Sets (In particular for Spanning Sets)|See how to prove that one set is a subset or equal to another]].==

- 2: Proving $\mathrm{Span}(S) = \mathbb{R}^n$.
	- Using  ==(1) from [[Spanning Set Theorems]]==, we know that given $\vec{v}\in \mathbb{R}^n$ and the arbitrary variable vector $\vec{x} \in \mathbb{R}^n$, then
		- $\vec{v} \in \mathrm{Span}(S) \iff$ ==$A\vec{x} = \vec{v}$ is defined and consistent.== (Meaning that ==$A\in M_{mxk}(\mathbb{R}), m = n$ - or in other words, the dimensionality of each vector in the spanning set must be n==). If $m < n$, then ==it is impossible to achieve a lin comb of dimensionality $n$==.
			- To prove that this is always true, then use ==[[Ranks of Matrices|SRT(3)]]==.
			- Reduce to REF, and if the rank of ==$Span(S) = n$, then by SRT(3), the system is consistent for all given vectors in $\mathbb{R}^n$==. <!--SR:!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2025-10-24,3,250!2000-01-01,1,250-->
		
*Examples (Excluding inline examples)* 
___

- Example for 1: **Exer - prove this then compare**==.==
	- Given $u = Span \left \{\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix}, \begin{bmatrix} -3 \\ 6 \\ -3 \end{bmatrix}\right \}$, $l = span \left \{ \begin{bmatrix} 1 \\ -2 \\ 1 \end{bmatrix} \right \}$, show that $l = u$. 
		- To prove that two sets are equal, we need to prove that $l \subseteq u \land u \subseteq l$. 
		- Let $\vec{v}$ be an arbitrary vector from u.
			- $\vec{v} = c_{1}\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix} + c_{2}\begin{bmatrix} -3 \\ 6 \\ -3 \end{bmatrix}$, $c_{1}, c_{2}\in \mathbb{R}^n$
			- $\vec{v} = c_{1}\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix} + -3c_{2}\begin{bmatrix} 1 \\ -2 \\ 1 \end{bmatrix}$
			- $\vec{v} = (c_{1}-3c_{2})\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix}$
		- Let $\vec{k}$ be an arbitrary vector from l.
			- $\vec{k} = c_{1}\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix}$
		- To show that $l \subseteq u$, show that for all arbitrary vectors $\vec{k}$, $\vec{k} \in u$
			- $\vec{k} = (c_{1}+0)\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix}$
			- $\vec{k} = c_{1}\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix}+c_{2}\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix}$, $c_{2}=0$
			- $\vec{k} = c_{1}\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix}+0\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix}$
		- To show that $u \subseteq l$, show that for all arbitrary vectors $\vec{v}$, $\vec{v} \in l$
			- $\vec{v} = (c_{1}-3c_{2})\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix}$
			- $c_{3}=(c_{1}-3c_{2})$
			- $\vec{v} = c_{3}\begin{bmatrix}1 \\ -2 \\ 1\end{bmatrix}$
		- Thus, $u = l$
	
*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

