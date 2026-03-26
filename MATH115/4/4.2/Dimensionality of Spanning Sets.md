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

- Given a set of vectors $S \in \mathbb{R}^n$, the dimensionality of $\mathrm{Span}(S)$ is ==the number of linearly independent vectors bound by n.==
	- That is, the number of vectors which are ==*not* collinear and are *not* lin. combs.== of other vectors in the set, ==up to n==
		- Algebraically, this is represented like so:
			- Let $S = \{\vec{v}_{1}, \ldots , \vec{v}_{k}\} \in \mathbb{R}^n$, $u = \mathrm{Span}(S)$, $\vec{j} \in \mathbb{R}^n$. 
				- Given for all $\vec{v}_i$ are linearly independent, we have $\vec{j} \in u \iff$ ==$\vec{j} = c_{1}\vec{v}_{1}+\cdots +c_{k}\vec{v}_{k}$ for any $c_{1},\ldots,c_{k} \in \mathbb{R}^n$==
				- This can be rewritten as ==$\vec{v} = \vec{0} + c_{1}\vec{v}_{1}+\cdots +c_{k}\vec{v}_{k}$, which is just:==
					- A graphical feature that ==passes through the origin, and has k dimensions==

*Examples (Excluding inline examples)* 
___

- Lin Comb in Spanning Sets:
	- Given $u = \mathrm{Span}\left \{\begin{bmatrix}1 \\ 1 \\ 0 \\ \end{bmatrix},\begin{bmatrix}0 \\ 1 \\ 1 \\ \end{bmatrix},\begin{bmatrix} 1 \\ 2 \\ 1 \\\end{bmatrix}  \right \}$, let $\vec{v} \in u$ **Exer. Reduce the spanning set to an equivalent irreducable spanning set**==.==
	- $\vec{v} =c_{1}\begin{bmatrix}1 \\ 1 \\ 0 \\ \end{bmatrix} + c_{2}\begin{bmatrix}0 \\ 1 \\ 1 \\ \end{bmatrix}+ c_{3}\begin{bmatrix} 1 \\ 2 \\ 1 \\\end{bmatrix}$
	- $\vec{v} =c_{1}\begin{bmatrix}1 \\ 1 \\ 0 \\ \end{bmatrix} + c_{2}\begin{bmatrix}0 \\ 1 \\ 1 \\ \end{bmatrix}+ c_{3}(\begin{bmatrix} 1 \\ 1 \\ 0 \\\end{bmatrix}+\begin{bmatrix} 0 \\ 1 \\ 1 \\\end{bmatrix})$
	- $\vec{v} =(c_{1}+c_{3})\begin{bmatrix}1 \\ 1 \\ 0 \\ \end{bmatrix} + (c_{2}+c_{3})\begin{bmatrix}0 \\ 1 \\ 1 \\ \end{bmatrix}$

*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

