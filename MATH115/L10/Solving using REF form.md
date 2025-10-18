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
Def'n: For the augmented matrix $\begin{bmatrix}A | \vec{c}\end{bmatrix}$, the REF form is given by $\begin{bmatrix}R|\vec{d}\end{bmatrix}$. If the j'th collumn in coefficient matrix $R$ contains a leading entry, this means that ==$x_j$ is a leading variable.== ==Elsewise, $x_j$ is a free variable - as it has no restrictions.==

If a variable is a free variable, assign it a parameter, and then substitute that parameter for where the variable appears anywhere else. 
- Then, isolate for leading variables, and then turn it into a vector equation.

Turning a scalar equation into its vector form:
- ==Turn into an augmented matrix, and then follow the normal procedures for when you have free variables== 
	- This makes sense, as you are just solving for a solution that exists exactly along that scalar equation, thus it will give you the exact same equation in vector form. 

If there is at least one inconsistent row in the aug. matr:
- ==This means that there are no solutions for the entirety of the system==
- However, this doesn't mean that there is no solutions for a simpler system
	- ==Show this by simply only taking the eqns that are consistent, will reduce to a simpler system which does have solutions:==
	- ![[Pasted image 20251007130105.png|209]]

- The number of collumns to the right of the last ==leading entry in an REF form aug. matr. is the number of free variables==
	- ==This is because the number of columns depend on the number of variables. If a collumn for that variable has no leading entries, it is a free variable (Above)==

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

