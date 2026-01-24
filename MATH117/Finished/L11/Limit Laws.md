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
Limit laws can only be used ==if the limit exists==. This assumption is required to apply limit laws.

Defn': Balancing Term:
- If the denominator of a function (Or any term) approaches infinity, in order for a limit to exist, there needs to be ==a term that opposes that term, such that it does not go to infinity==

Defn': Vert asymp:
- A vert asymp exists at $x = a$ if the RHS or LHS limit as x approaches a is $\pm \infty$

**Important**: If a limit goes to $\pm \infty$, it is ==DNE==. However, we don't always state this. <!--SR:!2025-10-22,3,250--> 

Evaluating Limits that are in Indeterminate Form:
- Evaluating Rational Functions:
	- Multiply by ==the conjugate:==
	- Ex.
		- $\displaystyle \lim_{x\to -\infty}(\sqrt{x^2-x}+x) \cdot \frac{\sqrt{x^2-x}-x}{\sqrt{x^2-x}-x}$
		- $\displaystyle \lim_{x\to -\infty}(\frac{x^2-x-x^2}{\sqrt{x^2-x}-x})$
		- Still Undeterminate
- Evaluating limits at infinity
	- Multiply by ==the reciprical of the highest power divided by itself:==
	- Note: To use this method, the reciprocal must be divided by ==another reciprocal==. Elsewise, it will be multiplying it by something other than 1
	- Ex.
		- $\displaystyle \lim_{x\to -\infty}\left(\frac{x^2-x-x^2}{\sqrt{x^2-x}-x}\cdot\frac{\frac{1}{x}}{\frac{1}{x}} \right)$
		- $\displaystyle \lim_{x\to -\infty}\left(\frac{\frac{x}{x}}{\frac{\sqrt{x^2-x}}{x}-\frac{x}{x}}\right)$
		- $\displaystyle \lim_{x\to -\infty}\left(\frac{-1}{-\frac{\sqrt{x^2-x}}{x}-1}\right)$ Note that the radical becomes negative as the limit is at negative infinity - this is a restriction that you must first consider as it will otherwise break the radical (-x = (-1)(x))
		- $\displaystyle \lim_{x\to -\infty}\left(\frac{-1}{-\sqrt{\frac{x^2}{x^2}-\frac{x}{x^2} }-1}\right)$ Note that you can distribute denominators into radicals by treating the denominator as its reciprocal
		- $\displaystyle \lim_{x\to -\infty}\left(\frac{-1}{-\sqrt{1-0 }-1}\right)$ Note that you can distribute denominators into radicals by treating the denominator as its reciprocal
		- $\displaystyle \lim_{x\to -\infty}\left(\frac{-1}{-2}\right)$ Note that you can distribute denominators into radicals by treating the denominator as its reciprocal
		- $\frac{1}{2}$		
 
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

