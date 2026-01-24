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

- FTC1:  If f(x) is cts on $[a, b]$, then the function:
	- $\displaystyle F(x) = \int_{a}^{x}f(t)dt$ is cts and candiff on $[a,b]$, and $F'(x) = f(x)$, ie the function $\frac{d}{dx}\displaystyle \int_{a}^x f(t)dt = f(x)$  
		- Note that x is not the dummy variable.
	- In other words, if the integral and the derivative "undo" each other. 
	- Note: The lower bound must be a constant, and the upper bound must be the variable x, found in both the integral and the derivative. 

- Chain rule with FTC1:
	- Given the function $F(u(x)) = \displaystyle \int^{u(x)}_{a}f(t)dt$, then
	- $F'(u) = \frac{{dF}}{{du}} \frac{{du}}{{dx}}$, and thus by FTC1: 
	- $F'(u) = f(u)\cdot u'(x)$

- Using FTC1 with two function bounds:
	- Given $\frac{d}{dx}\displaystyle \int^{u(x)}_{h(x)}f(t)dt$, then using the [[Properties of the Definite Integral]], we have 
	- $\displaystyle \frac{d}{dx} \left( \int^0_{h(x)}f(t)dt + \int^{u(x)}_0f(t)dt\right)$, which is 
	- $\displaystyle \frac{d}{dx} \left(-\int^{h(x)}_0f(t)dt + \int^{u(x)}_0f(t)dt\right)$, which is 
	- $-f(h)\cdot h' + f(u) \cdot u'$

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

