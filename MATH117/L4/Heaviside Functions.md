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

Enable at t: ==$H(x-t)f(x)$==
- This will "Enable" f(x) starting at point t:
	- For all values $x < t$, the argument for H(x) will be ==negative==
		- This means it will be disabled.
	- For all values $x \ge t$, the argument for H(x) will be ==$\ge 0$==, or in other words, ==positive or equal to 0==
		- This means it will activate.

Disable: ==$1f(x) - H(x-t)f(x)$== or ==$f(x)(1-H(x-t))$==
- This inverses the behavior of the "Enable" function. 
- It multiplies f(x) by ==1== for all values up until x = t, where it multiplies f(x) by ==0==
- ![[Pasted image 20251019182618.png|241]]

Enable -> Disable: ==$H(x-t)f(x) - H(x-k)f(x)$== or ==$f(x)(H(x-t)-H(x-k))$==
- This enables the function at x = t, and then disables at x = k.
- It is derived from ==adding the enable and disable functions==
	- In this case, the coef 1 in the disable function is the ==enable function past the point t==
- ![[Pasted image 20251019182655.png]]

Disable -> Enable: $1f(x) - H(x-t)f(x) + H(x-k)f(x)$ or ==$f(x)(1 - H(x-t)+H(x-k))$==
- This is the same as ==enable -> disable==, its just that it first ==disables and then enables==

Note: The endpoint can be swapped around. For example, H(x) could be defined as $1 \space \mathrm{for} \space x > 0$, instead of $1 \space \mathrm{for} \space x \ge 0$, and the ==endpoint would change, allowing you to change behavior at end points in piecewise functions.==

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

