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

Newton figured that for a set of N points, then you can construct an N'th degree polynomial that passes through all of the given points with the following formula:

$f(x) = \displaystyle \sum^{N}_{n = 0} \frac{\Delta^n y_{1}}{n! h^n}$

Where h is the finite differences between all of the points.

---
The derivation

This is a rough derivation, and is not rigorous.

Since we have N points, we can intuit that we need an N'th degree polynomial. 

The polynomial will have multiple terms of differing degrees, each with a coefficient to make it fit the points.

We would like, for coefficient finding purposes, to minimize the amount of coefficients present whenever we plug in a given point. 

We arrive at this form
$f(x) = a + b(x - x_{0}) + c(x - x_{0})(x-x_{1}) + d(x-x_{o})(x- x_{1})(x-x_{2})$
Plugging in the points and equating for the y values gives us the following:

$y_{0}=a$
$y_{1}= a + hb$
$y_{2}= a + 2hb + 2h^2 c$
$y_{3}= a + 3bh + 6h^2c + 6h^3d$

Now, we must find an easy way to cancel out these terms to easily equate them to real known values. We do this as so:

$\Delta y_{0}= y_{1}- y_{0}= hb$
$\Delta y_{1} = hb + 2h^2c$
$\Delta y_{2} = hb  + { 4h^2c} + 6h^3d$

$\Delta^2 y_{0}= 2h^2c$
$\Delta^2 y_{1}= 2h^2c + 6h^3d$

$\Delta^2 y_{0} = 6h^3d$

We can now equate these things and we arrive at:

$a = y_0$
$b = \frac{\Delta y_0}{h}$
$c = \frac{\Delta^2 y_{0}}{2h^2}$
$d = \frac{\Delta^3 y_{0}}{6h^3}$

At this point the pattern becoems clear. 

*Examples (Excluding inline examples)* 
___

*Significant Theorems:*

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

