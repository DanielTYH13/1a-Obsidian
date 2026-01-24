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
- In order to approximate the area under a curve, we "Slice" it into rectangles:
	- Each rectangle is represented as $f(x_{i})\Delta x$
	- ![[Pasted image 20251202193205.png]]

- Turning rectangle-slice approximations into exact area:
	- We can refine this approximation by taking a larger amount of smaller rectangles:
		- ![[Pasted image 20251202193333.png|475]]
	- The limit of this approximate area as the number of rectangles goes to infinity is the exact area under the curve.
	- This is represented as $\displaystyle \lim_{n\to \infty} \sum^n_{n=1}f(x_i)dx$
		- Breaking down this notation:
			- f(x) is the function
			- dx is analogous to $\Delta x$, and is the width of each rectangle. 
				- Since we take the limit as n goes to infinity, we change it to "dx" to show that it is infinitesimally small. 
			- $x_i$ is the endpoint of each rectangle.
				- It is found by adding a multiple of dx to the lower bound
					- By addig dx in different ways, we can take different endpoints:
						- [[Midpoint Integral]]
						- [[Left Endpoint Integral]]
						- [[Right Endpoint Integral]]
			- By summation notation, n represents the number of rectangles to take. 

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

