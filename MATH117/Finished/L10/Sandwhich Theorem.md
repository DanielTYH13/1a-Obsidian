---
tags:
  - "#review"
  - MATH117
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
---
*Key Concepts:*
___

- *Sandwhich theory gives that:*
	- Given sequences $a_n$, $b_n$, $c_n$, where $a_{n}, c_{n} \to L$
	- If $a_{n} < b_{n} < c_{n}$, then $b_{n} \to L$
		- This requirements are that the above inequality can be true after some terms, but then must be true forever. 
	![[Pasted image 20250929130652.png|291]]
	
	- This is quite useful for sequences such as $a_{n} = \frac{\sin{n}}{n}$
		- You cannot evaluate this using typical limit laws and tools, as $\displaystyle \lim_{x->\infty}\sin{x} = DNE$
			- It is oscillating.
	- Example:
		- $\displaystyle \lim_{x\to0}x^2\tan(\frac{1}{x})$
			- We cannot evaluate this as 1/x is DNE at x = 0
		- ==$\frac{-\pi}{2} \le tan(\theta) \le \frac{\pi}{2}$==
		- ==$\frac{-\pi x^2}{2} \le x^2tan(\theta) \le \frac{\pi x^2}{2}$==
		- ==$\displaystyle \lim_{x\to 0} \pm \frac{\pi x^2}{2} = 0$==
		- Therefore, ==the original limit is also 0.==

	- *Indicators for sdw thm* (Doesn't necessitates)
		- If there are any periodic functions in the numerator
		- Ex. 
			- sin(x)
			- cos(x)
			- (-1)^n
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

