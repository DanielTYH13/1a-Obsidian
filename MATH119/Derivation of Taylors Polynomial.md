---
tags:
  - "#review"
  - MATH119
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: MATH119 U1
---
*Key Concepts:*
___

Recall Newton's Forward Difference Formula:

$f(x) = y_{0} + \frac{\Delta y_{0}}{\Delta x}(x - x_0) + \frac{\Delta^2 y_{0}}{2\Delta x^2}(x - x_{0})(x - x_{1}) + \frac{\Delta^3 y_{0}}{6\Delta x^3}(x- x_{0})(x-x_{1})(x-x_{2})$

If we take the limit of this approximation as $\Delta x$ goes to zero, and take $\Delta y$accordingly, ie a polynomial interpolation for a set of N points that slowly converge to a single point, we get

$\left. \frac{\Delta^n y_{0}}{\Delta^n x} = \frac{\text{d}^n y}{\text{d}x^n}\right|_{y_{0}}$

This follows from the limit definition of the derivative. 

Thus, we get a new formula, which is a polynomial approximation for f(x) around a given point. It turns out that this quickly becomes very accurate. 

$T_{N, x_{0}}(x) = \displaystyle \sum^N_{n = 0} \frac{f^n(x_{0})}{n!}(x-x_{0})^n$

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

