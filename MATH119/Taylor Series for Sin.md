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

For the sin function, we can express a taylor polynomial of degree n centered at $x_{0}$ as $\displaystyle \sum_{k= 0}^{n} \frac{(-1)^k (x)^{2k + 1}}{(2k + 1)!}$ (The even terms are cancelled out, as sin(0) = 0).

Therefore, we can have taylor polynomials with the highest derivative's degree of 2n + 1. We can express the remainder as

$|R| \le \left|k\frac{x^{2n + 2}}{(2n + 2)!}\right|$, where K is obviously 1, so 
$|R| \le \left|\frac{x^{2n + 2}}{(2n + 2)!}\right|$

So we ask, what is the limit of the error as the degree of the taylor polynomial goes to infinity? 

In this case, we can use squeeze theorem: $0 < \frac{x^{2n+2}}{(2n+2)!} < \frac{x^n}{n!}$, where  $\frac{x^n}{n!}$ goes to zero at $n \to \infty$, and thus the error goes the zero.
	
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

