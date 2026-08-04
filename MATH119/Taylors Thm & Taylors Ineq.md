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

$\left| R_{n,a}(x)\right| \le \left |\displaystyle  K \int^x_{a}\frac{ (x-t)^n }{n!}dt\right |$

Where K is the $max(f^{n+1}(x))$ along the range of estimation $[x_{0}, x]$ if for one value, or $[x_{0}, x{0}']$ for all possible approximations within a range.

Rmk: $f(x) = T_{n,a}(x) + R_{n,a}(x)$

---
Taylors Theorem:

Suppose we have f(x) is n+1 differentiable on the interval containing a, then

- $R_{n,a}(x) = \frac{f^{(n+1)}(c)}{(n+1)!}(x-a)^{n+1}$ For some c between a and x. Differential Form
- $R_{n,a}(x) = \displaystyle  \int^x_{a}\frac{ (x-t)^n f^{(n+1)}(t)}{n!}dt$ Integral form

The restriction is required as a taylor integral of degree n contains the n+1 order derivative of f. 

This is derived from the fact that for a function, 

$f(x) = f(x_{0}) + \displaystyle \int^x_{x_{0}}f(x)dx$

This is the form of f(x) expressed as $P_{0, x_{0}}$. It can be expanded to higher degrees of the Taylor polynomial, yielding the general form.

---
Upper bound for error:

We have that the remainder (error function) is given as:
$R_{n,a}(x) = \displaystyle  \int^x_{a}\frac{ (x-t)^n f^{(n+1)}(t)}{n!}dt$

This integral would be impossible to solve without knowledge of f(x), however if we use the max of the derivative, we can treat $f^{(n+1)}(t)$ as a constant value, thus pulling it out. 

$R_{n,a}(x) \le \displaystyle  K \int^x_{a}\frac{ (x-t)^n }{n!}dt$
$\left| R_{n,a}(x)\right| \le \left |\displaystyle  K \int^x_{a}\frac{ (x-t)^n }{n!}dt\right |$

It should make sense that because we use $max(f^{n+1}(t))$ across, $[x_{0}, x]$, this upper bound should be higher than or equal to the actual error.

If we would like to obtain a bound for the error along a range, must just find the max derivative for all possible ranges $[x_{0}, x]$ along the bounds $[x_{0}, x_{0}']$. Ie, the max derivative along $[x_{0}, x_{0}']$

So it is an estimate, but a pretty accurate one in most cases.

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

