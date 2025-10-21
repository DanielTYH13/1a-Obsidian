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
- [[Systems of Linear Equations]] can be represented as a ==matrix-vector== product.
	- Given a system of linear equations in n variables and m equations, given coefficient matrix $A = M_{mxn}(\mathbb{R})$, variable vector $\vec{x}\in \mathbb{R}^n$, and constant vector $\vec{b}$, the system can be represented as:
		- ==$A \vec{x} = \vec{b}$==
	- The form $A\vec{x} = \vec{b}$ expands as such, where $a_j$ is the jth collumn of the matrix A:
		- $x_{1}\vec{a}_{1} + x_{2}\vec{a}_{2}+ \cdots + x_{n}\vec{a}_{n}=\vec{b}$
		- Where each variable x is ==distributed over all of the coefficients== of the corresponding ==collumn vector==
		- Using vector addition, ==this can then be summed into a new vector of dimensionality $\mathbb{R}^m$, which is the variable representation of b.==
			- Each component of the vector has ==$n$ variables multiplied by coefficients specified in A.==
		- Set equal to constant vector, the whole system becomes equivalent to a ==system of linear equations.==
		- Exer==.== Illustrate the above for the general linear system of 3 equations and 3 variables. <!--SR:!2000-01-01,1,250!2025-10-24,3,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250--> 

- Note: With the matrix $A\vec{x} = \vec{b}$ where $A \in M_{mxn}(\mathbb{R})$, $\vec{b}\in \mathbb{R}^m$
	- This is because $\vec{b}$ is the matrix-vector product, which is dependant on m ([[Matrix-Vector Multiplication]]).

- Def'n Sol'n to a Matrix Equation of a Linear System:
	- The constant vector $\vec{s}$ is a solution ==to the linear system represented by $A\vec{x} = \vec{b} \iff A\vec{s} = \vec{b}$ ==

- The above is a def'n. The following is a thm:
	- Given a coefficient matrix $A \in M_{mxn}(\mathbb{R})$, $\vec{x}\in \mathbb{R}^n$ $\vec{b}\in \mathbb{R}^m$,
		- The linear system $A\vec{x} = \vec{b}$ is consistent $\iff$ ==the vector $\vec{b}$ can be expressed as a linear combination of the collumns of A.==
		- If $\vec{a_{1}} \cdots \vec{a_{n}}$ are the columns of matrix A and $\vec{s} = \begin{bmatrix}s_{1} \\ s_{2} \\ \vdots \\ s_{n}\end{bmatrix}$, then $\vec{x} = \vec{s}$ is a solution $\iff$ ==$s_{1}\vec{a_{1}} + s_{2}\vec{a_{2}}+ \cdots + s_{n}\vec{a_{n}} = \vec{b}$==
			- You are assigning a constant to each collumn.
			- Each collumn represents ==the coefficients of one variable.==
			- The ==same constant== is distributed over all coefficients.
			- This represents ==setting all variables $x_{n}$ as that one constant $s_{n}$. ==
			- Do this for all of them, and you have found ==a set of values for x that satisfy the system.==


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

