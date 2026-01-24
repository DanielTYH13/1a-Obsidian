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
**Definition**

- The Heaviside function is a piecewise function defined as ==$H(t) = \left\{ \begin{array}{ll}0 \space for \space x<0\\ 1\space for \space x \ge 0 \end{array}\right.$==

---
**Negating Functions with Heaviside**

- You can use ==$-H(x-t)f(x)$== to achieve the identical behavior, but mirrored around $y = 0$. (T)

___
**Enabling with Heaviside**

Enable at t: ==$H(x-t)f(x)$==
- This will "Enable" f(x) starting at point t:
	- For all values $x < t$, the argument for H(x) will be ==negative==
		- This means it will be disabled.
	- For all values $x \ge t$, the argument for H(x) will be ==$\ge 0$==
		- This means it will activate. <!--SR:!2025-10-22,3,250!2025-10-22,3,250!2000-01-01,1,250-->

---
**Disabling with Heaviside**

Disable: ==$f(x) - H(x-t)f(x)$== or ==$f(x)(1-H(x-t))$==
- This inverses the behavior of the "Enable" function. 
- It multiplies f(x) by ==1== for all values up until x = t, where it multiplies f(x) by ==0==
- ![[Pasted image 20251019182618.png|241]]
---
**Enabling and Disabling with Heaviside**

Enable -> Disable: ==$H(x-t)f(x) - H(x-k)f(x)$== or ==$f(x)(H(x-t)-H(x-k))$==
- This enables the function at x = t, and then disables at x = k.
- It is derived from ==adding the enable and disable functions==
- ![[Pasted image 20251019182655.png|250]] <!--SR:!2000-01-01,1,250!2000-01-01,1,250!2025-10-22,3,250-->

Disable -> Enable: $f(x) - H(x-t)f(x) + H(x-k)f(x)$ or ==$f(x)(1 - H(x-t)+H(x-k))$==
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

