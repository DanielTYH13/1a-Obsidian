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

If you have a function of form $f(x) = g(\phi(x))$, where the derivative of $g(x)$ is easily differentiable whereas $f(x)$ is not, then you can create and equivalent taylor polynomial for $f(x)$ by creating one for $g(x)$ and evaluating at $\phi(x)$.

$\left. P_{g(\phi(x))} = P_{g(x)}\right|_{\phi(x)}$

This is because it is fundamentally the same question to ask:

What is $g(\phi(x))$ at $x = a$? and what is $g(x)$ at $x = \phi(a)$. The functions themselves are different, growing differently with respect to the main variable, but this is accounted for when you substitute in $\phi(a)$

This is also why you need chain rule for differentiation of a composed function, but can directly substitute for polynomial approximations. 

For example, take $f(x) = e^{t^2}$. $f(x)$ grows faster than $g(x) = e^x$ wrt to t and x, but we evaluate one at $t = a < x = t^2 = a^2$

![[Pasted image 20260802164325.png]]

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

