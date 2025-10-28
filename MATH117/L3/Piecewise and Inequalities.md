---
tags:
  - "#review"
  - MATH117
---
*Key Concepts:*
___
- When working with Piecewise inequalities, split the work into ==cases where the domain of certain values of x correspond to different resolutions of the piecewise function.==
	1. An easy way to visualize this is by using a ==number line.==
		1. When you are working with piecewise inequalities, always list ==critical points on a number line== to see when the overall behavior (Form of the piecewise functions) changes. Then, create ==individual inequalities that for each interval.==
	2. Then find solutions for each individual piecewise inequality case.
	3. Once you have finished solving the inequality, find the intersection between the ==solutions to the inequality and the respective domain for that case==
		1. This is because both of the following are true for the inequality to be valid
			1. For each inequality case, given:
				1. $D_{case}$ is the set of values that cause this specific inequality to be true.
				2. $S_{case}$ is the set of all real values that satisfy this specific inequality
			 The set $T_{case}$ is the set of solutions for that case ==$\iff$ $T \subseteq D_{case} \land T\subseteq S_{case}$ which is equivalent to $T \subseteq (D_{case} \cap S_{case})$==
				- Therefore, the set of all solutions in that interval $T$ is simply $T = (D_{case} \cup S_{case})$
			2. In other words, there are two conditions that need to be true:
				1. For all $x \in S$, $x$ must satisfy the inequality:
				2. For all $x\in S$, $x$ must cause the piecewise function to "collapse" into the respective inequality case.
					1. If x is outside of the domain, then it is possibly a distinct inequality.
	5. Finally, union all of the intersections to find your final answer. <!--SR:!2000-01-01,1,250!2000-01-01,1,250!2025-10-20,1,230!2000-01-01,1,250!2000-01-01,1,250!2000-01-01,1,250-->

- Heaviside functions:
	- Heaviside functions are defined as the piecewise function: $H(t) = \left\{ \begin{array}{ll}0 \space for \space x<0\\ 1\space for \space 0 \le x\end{array}\right.$
		- Using this definition of the heaviside function, it is possible to condense piecewise functions into one-line functions using transformations:
			- ==$f(x)H(x-k)$==: =="Enable" f at the point x = k==
			- ==$f(x)(1-H(x-k))$==: =="Disable" f at the point x = k==

-  Note: When solving for inequalities with rational functions on one side and 0 on the other side, you must ==evaluate all places where the sign might change==
	- This includes ==terms on the denominator where the sign might change==
		- You are not only ==looking for where the function is possibly zero, but also where it is completely undefined==
	- IE: Look for POI where the function is ==0 or DNE==

*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

