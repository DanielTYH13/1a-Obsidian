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

Taylors theorem is the expression for error by the taylor polynomial set at x=a.
- $|R_{n,a}(x)| = \left| f(x) - T_{n,a}(x)\right|$

Taylors Ineq tells you the upper bound for the error 
- $max|R_{n,a}(x)|$

Rmk: $f(x) = T_{n,a}(x) + R_{n,a}(x)$

---
Taylors Theorem:

Suppose we have f(x) is n+1 differentiable on the interval containing a, then

- $R_{n,a}(x) = \frac{f^{(n+1)}(c)}{(n+1)!}(x-a)^{n+1}$ For some c between a and x. Differential Form
- $R_{n,a}(x) = \displaystyle \frac{1}{n!} \int^x_{a} (x-t)^n f^{(n+1)}(t)dt$ Integral form

The restriction is required as a taylor integral of degree n contains the n+1 order derivative of f. 

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

