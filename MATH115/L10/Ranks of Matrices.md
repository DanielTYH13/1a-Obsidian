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
Def'n: The rank of a matrix is the number of leading entries for any given REF form of that matrix (==Any arbitrary [[REF and RREF Form|REF]], as it will still have the same order of the solution, ex. An inf solution will still have inf solutions regardless of its REF, and same for a unique sol'n==)
- This is denoted by Rank(A) for Matrix $A\in M_{mxn}(\mathbb{R})$
- IMPORTANT ==The rank can only be taken if you are in REF form of the matrix. This form is representative of the *nature* of a matrix. (In its most reduced form)==
- In aug. matr., the coefficient vector / matrix is ==included in the rank==. This is important to tell if the system has ==Exactly one solution==

- #TODO what if the constant vector has dimensionality greater than the matrix by more than one? Then there is the possibility that the entire augmented matrix cannot be put into REF. How do you treat a case like that?

Def'n:
- A system of m linear equations in n variables is undetermined ==$\iff m < n$==
	- ==This is because then there are not enough equations for the variables that are given==, meaning that you cannot find a unique solution for the system <!--SR:!2000-01-01,1,250!2025-10-24,3,250-->

Def'n:
- A system of m linear equations in n variables is overdetermined $\iff$ ==$m > n$==
	- Oftentimes, overdetermined systems will be inconsistent, due to an excess of restrictions. 

Theorem:
- An undetermined system that is consistent ==will have infinitely many solutions==
	- It is equivalent to ==Creating a matrix with n variables, giving m < n rows, and setting the rest to zero rows, such that some variables must become parameters==

*Examples (Excluding inline examples)* 
___

*Significant Theorems:*
___

Max Rank of a Matrix:
- The maximum rank of a matrix is the ==min(m, n)==
	- Case 1: $n < m$, then ==regardless of the rows, the diagonal ends at the side.==
	- Case 2: $m < n$, then ==regardless of the collumns, the diagonal ends at the bottom.==

System Rank Theorem (SRT)
- Let $\begin{bmatrix}A|\vec{b}\end{bmatrix}$ be the augmented matrix of a system with *m* linear eqns in *n* variables.
	- The system is consistent $\iff$ ==$Rank(A) = Rank([A|\vec{b}])$==
		- **Case 1:** The system is consistent with a unique solution $\implies$ ==Rank(A) = n, $Rank([A|\vec{b}])$ = n, n = $num_{variables}$==
			- Even if there is a 0 in $\vec{b}$, this does not matter, as the ==$Rank([A|\vec{b}])$ includes the coefficients in matrix A, which will  cause the ranks to be the same.==
			- n must equal the num of variables such that there are no ==zero rows, or free variables==
		- **Case 2:** The system is consistent with infinite solutions $\implies$ ==$Rank(A) = n-\#_{FreeVars}$ $\implies$ $Rank([A|\vec{b}]) = n-\#_{FreeVars}$==
			- The rows with free variables must ==have constants of 0 in order for the system to remain consistent==
		- **Case 3:** The system is inconsistent $\implies$ ==$Rank(A) = n - \#_{FreeVars}$, $Rank([A|\vec{b}]) > Rank(A)$==
			- There must be a ==non-zero leading entry in $[A|\vec{b}]$ which is respective to no other non-zero entry in matrix A - thus having the form 0 = non-zero, which is inconsistent.==
	- If the system is consistent, then the solution has an ==order / number of parameters equalling that of n - Rank(A)==
		- It must be ==consistent for this to be true.==
		- Note: If you can prove that there is a # of parameters ==in the solution, you can show the rank of the system== by rearranging.
		- The order of the solution is determined by this as it depends on the ==number of parameters==, or in other words, ==the number of free variables==.
	- The system is consistent for all ==$\vec{b} \in \mathbb{R}^n \iff Rank(A)=n$==
		- This is because that means that the rank of ==A is equal to all of the rows in the matrix, meaning there are no zero rows. Thus, regardless of what vector in $\mathbb{R}^n$ you put in the constant vector, it will always be consistent.==
			- Remember, if you put a 0 row in, you must also put a 0 constant in as well. <!--SR:!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2025-10-24,3,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250-->

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

