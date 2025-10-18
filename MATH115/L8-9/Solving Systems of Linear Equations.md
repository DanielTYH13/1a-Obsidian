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

Definition: A consistent system
- A system is consistent if it ==has at least one solution== 

Definition: An inconsistent System:
- A system is inconsistent if it ==Has no solutions==

Solving a Lin System using Elementary Row Operations:
- When trying to solve a Lin Sys., we try to make the system easier to solve without changing its solutions. While we may change the equations themselves, their solutions remain constant - and that is what matters. 
- The elementary row operations are a set of operations that you can use to manipulate a lin sys without changing the solutions. They are:
	- ==Swapping two Rows==
	- ==Adding or Subtracting two rows==
	- ==Multiplying a row by a non-zero scalar==
		- You may not multiply a row by a zero scalar, as this is equivalent to ==simply erasing that equation==
- Note, ==you are allowed to perform more than one elementary row operation at once==.

Defn': Augmented Matrices:
- An augmented matrix denoted as $[A|\vec{b}]$, where A is the coefficient matrix of the lin sys and $\vec{b}$ is the constant collumn vector of the lin. sys. Moreover, ==the order of the variables in each collumn of the coefficient matrix should be consistent. Ie, if $x_1$ is in the j'th collumn, all other rows should have $x_1$ for their j'th entry.==
	- There are cases where $\vec{b}$ can be swapped out for ==a constant matrix==, however this will not be discussed in this note. 
- The purpose of an augmented matrix is to ==preserve the meaning of the lin sys, while making it easier to work with== 
	- This is because ==we only manipulate the coefficients and constants of a lin sys. when we are trying to solve it. Thus, we can discard the variables==
- Ex: ![[Pasted image 20251005192243.png]]

Defn': Augmented Matrices Cont'd:
- The matrix $A\in M_{mn}(\mathbb{R})$ contain the coefficients ahead of each variable of each equation in the lin sys. These variable must be ordered such that ==each variable in each eqn is in the same collumn as other eqns==

Note: The ideal form of an augmented matrix after using EMO is the identity matrix followed by some constant matrix. 

A if the Aug. Matr. has the row $\begin{bmatrix}0&0&0&|&0\end{bmatrix}$, and the rank of the system is 1 less than the number of variables, and the rest of the system is consistent, then the system ==has infinitely many solutions==
- This is because all values of any variable in the system satisfy this condition, and one of the variables is unrestricted

Defn': Leading Entry -> ==The first non-zero entry in a single row of a matrix==







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

