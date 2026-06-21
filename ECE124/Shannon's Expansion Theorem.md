---
tags:
  - review
  - ECE124
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: ECE124 U1
---
*Key Concepts:*
___

Shannon's expansion states that for any function $f(w_{0}, w_{1}, w_{2}, \ldots) = w_{0}'f(0, w_{1}, w_{2}, \ldots) + w_{0}f(1, w_{1}, w_{2}, \ldots)$

---
There are two ways to think of this. 1st is to interpret each w_0 term as asking "Is w_0 true/false"? If so, then the evaluate the function where w_0 is true/false.

Another way of thinking about it is by truth table. For example, state f in terms of w_2, w_3 when w_1 is 0 and 1, respectively.

![[Pasted image 20260616184903.png]]

You can see how when w_1 is either 0 or 1, the possible values collapse, and the function is only evaluated at w_1 = 0 or 1.

---
Further expansion:

For any general function, you can continue to use Shannon's expansion until the system is sufficiently reduced. All functions can be expanded until the whole function is evaluated at certain points, at which it becomes a lookup table / mux in of itself. 

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

