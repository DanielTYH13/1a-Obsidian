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

- Recall - sinh(x) is odd and cosh(x) is even

- Is tanh(x) odd or even?
	- When dividing an odd function by an even one, you are dividing the entire odd function "symmetrically" over its domain. Therefore, it will remain symmetric, however still be odd.
		- There is no way to go from odd -> even, as this would imply an even function that differently modifies the odd function on each side of the y axis. This directly contradicts the definition of an even function. 

- Finding sinh(x) and cosh(x) from tanh(x)
	- Consider that tanh(x) = $\frac{sinh(x)}{cosh(x)}$ = $\frac{a}{b}$
	- Resultingly, this means that $sinh(x)=\frac{a}{b}cosh(x)$
	- *Now, since we have two functions, it is impossible to find sinh(x) or cosh(x) in relation to the constants given - which are our tools to finding the values of the functions.* 
		- *As such, we need to remove one of the two functions using hyperbolic trig identities:* $cosh^2(x) - sinh^2(x) = 1$
	- $-sinh^2(x) = -\frac{a}{b}cosh^2(x)$
		- *First square, and then negate both sides*
	- $cosh^2(x)-sinh^2(x) = cosh^2(x)-\frac{a}{b}cosh^2(x)$
		- *Add $cosh^2(x)$ to both sides to fulfill the identity, and thus removing $sinh(x)$*
	- $1 = cosh^2(x)-\frac{a}{b}cosh^2(x)$
	- $1 = cosh^2(x)(1-\frac{a}{b})$
	- $cosh(x) = \sqrt{\frac{1}{1-\frac{a}{b}}}$
	- *Then, using the value of $cosh(x)$, you can then use the definition of $tanh(x)$ to find sinh(x).*

Example: Finding $sinh(arctanh(x))$ in terms of x
1. $sinh(arctanh(x))$ - *This is what we are trying to find in terms of x*
2. Let $u = arctanh(x)$ *We try to simplify the equation so we can easily turn it into different forms*
3. $tanh(u) = tanh(arctanh(x)) = x$ - *We are trying to find sinh(u) in terms of some other function. We know sinh(u) exists in tanh(u)*
4. $\frac{sinh(u)}{cosh(u)} = x$
5. $sinh(u) = xcosh(u)$ - *Presto! We have sinh(u) in respsect to another function. Now we can try to find sinh(u) in terms of x*
	1. *Note, it should always be your intuition to find one thing in respect to another, different thing, when encountering these types of questions. This allows you to make logical deductions that would cancel out and give you 0=0*
6. $sinh^2(x)-cosh^2(u) = 1$ - *Now, we just need to find cosh(u) in terms of x, which is much easier given that we have an identity that is helpful in removing sinh(u)*
7. $(xcosh(u))^2 - cosh^2(u) = 1$
8. $x^2cosh^2(u) - cosh^2(u) = 1$
9. $cosh^2(u)(x^2-1) = 1$
10. $cosh(u) = \frac{1}{\sqrt{x^2-1}}$
11. $sinh(u) = sinh(arctanh(x)) = xcosh(u) = \frac{x}{\sqrt{x^2-1}}$ - *Voila!*


*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

- *Given that $tanh(x) = \frac{a}{b}$, do not assume that this means that $sinh(x) = a$ and $cosh(x) = b$*
	- When dividing $sinh(x)$ and $cosh(x)$, the denominators reduce, and information is lost.
		- For example, given $sinh(x),cosh(x)$, you can manipulate any constant value such that their denominators are the same. Then, when you divide the two, the denominators cancel out.

*Terms and Definitions:*
___

