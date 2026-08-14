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

For a power series of form $\displaystyle \sum^{\infty}_{n=0}c_{n}(x-x_{0})^n$, then the series is garunteed to be absolutely convergent within the range:
$x \in (x_{0} - R, x_{0}+R)$

Where $R = \displaystyle \lim_{n \to \infty} \left|\frac{c_n}{c_{n+1}}\right|$

Corollary:

For $R = 0$, f(x) converges only at $x = x_{0}$
For $R = \infty$, f(x) converges everywhere. 

For a full convergence interval, the endpoints must also be tested individually

---
Derivation

We can apply the ratio test to the power series:

$\displaystyle \lim_{n \to \infty} \left|\frac{c_{n+1}(x-x_{0})^{n+1}}{c_{n}(x-x_{0})^n} \right| < 1$
$\displaystyle \lim_{n \to \infty} \left|\frac{c_{n+1}}{c_{n}}(x-x_{0}) \right| < 1$
$|x - x_{0}| < \displaystyle \lim_{n \to \infty} \left| \frac{c_n}{c_{n+1}} \right|$
$|x - x_{0}| < R$
$x \in (x_{0} - R, x_{0} + R)$ // This can be derived by case analysis. 

Thus, since we can always construct $\frac{(x- x_{0})^{n+1}}{x- x_{0}}$, we have that $x_{0}$ will always be the center of the interval of convergence.

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

