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

- When finding the area under a curve, we want to find the ==signed area==. 

- We can approximate the area under a curve by taking the sum of rectangles which compose it.
	- The rectangles are defined by the product of a constant $\Delta x$, and $f(x)$ at the multiple of $\Delta x$ from a bound of a to b: $\displaystyle \sum^n_{i = 1}f(x_{i})\Delta x$ 
		- $\Delta x$ is defined as $\frac{b-a}{n}$, which is the range of a to b divided by the number of rectangles. 
		- $f(x_{i})$ is defined as the lower bound plus some multiple of $\Delta x$. There are a few common ways to define it:
			- Right Hand Side: $x_{i} = a + i\Delta x$ 
			- Left Hand Side: $x_{i} = a + (i-1)\Delta x$
			- Mean Value: $x_{i} = a + (i-1)\Delta x +\frac{\Delta x}{2}$
				- This is equivalent to $x_{i} = a + \frac{\Delta x (2i-1)}{2}$

- Def'n: A Reimann Sum is the sum of these rectangles as n goes to infinity. In other words, it is the infinite sum of infinitesimally small rectangles from bound a to bound b.
	- $A = \displaystyle \lim_{n\to \infty}\sum^n_{i=1} f(x_i)\mathrm{d}x$
		- You may notice that the $\Delta x$ has instead become $\mathrm{d}x$. This is because at $n = \infty$, the change in x per rectangle will be infinitely small.
		- This dx term is called the differential.  

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

