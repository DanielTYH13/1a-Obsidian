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

We have the identity that for any carry output $c_{i +1} = g_{i} + p_{i}c_{i}$

Thus, we have 
$c_{0} = c_{0}$
$c_{1} = g_{0}+p_{0}c_{0}$
$c_{2} = g_{1}+p_{1}(g_{0} + p_{0}c_{0}) = g_{1}+ p_{1}g_{0}+ p_{1}p_{0}c_{0}$
$c_{3} = g_{2} + p_{2}(g_{1}+ p_{1}g_{0}+ p_{1}p_{0}c_{0}) = g_{2} + p_{2}g_{1} + p_{2}p_{1}g_{0}+p_{2}p_{1}p_{0}c_{0}$

Etc.

The point is that each of these expression for the next carry are dependant only on $p_{i}, g_{i}, c_{0}$. All $p_{i}, g_{i}$ are calculated based on input in parallel with gate delay of 1. Moreover, since all carries can be expressed wrt $c_{0}$, then instead of rippling, we can calculate $c_{0}$ once to then calculate all $c_{i}$ across the adder, thereby reducing time. 

Thus, the gate delay for an add calculation is 1 + 2 + 1 = 4.

The major downside is that the gate fan-in increases quickly wrt n bits. Thus, this is an expensive and impractical implemention for high bit adders. 

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

