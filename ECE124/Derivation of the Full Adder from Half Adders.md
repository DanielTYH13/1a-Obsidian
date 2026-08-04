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

Consider the sum of $x_{i}\cdot 2^n+y_{i}\cdot 2^n+c_{i}\cdot 2^n$, where each variable is a binary bit. We wish to represent this as $C\cdot 2^{n+1} + S\cdot 2^{n}$.

For any half adder, $\text{HA}(x\cdot 2^n, y\cdot 2^n) = c\cdot 2^{n+1} + s\cdot 2^n$, $c = x \wedge y$ and $s = x \oplus y$. We abbreviate c and s to abstract from the half adder.

We can guess that a full adder must be chained half adders, so we attempt to introduce half adders.

$x_{i}\cdot 2^n+y_{i}\cdot 2^n+c_{i}\cdot 2^n =$              The definition of a full adder (Addition of 3 inputs)
$\hat{c}\cdot 2^{n+1} + \hat{s} \cdot 2^n +c_{i}\cdot 2^n =$              Where $\hat{c}, \hat{s}$ are the carry and sum outputs of the half adder for $x_{i}\cdot 2^n+y_{i}\cdot 2^n$
$\hat{c}\cdot 2^{n+1} + \check{c}\cdot 2^{n+1} + \check{s}\cdot 2^n$

In the full adder truth table, we have that if:

$\hat{s} = 0 \implies \check{c} = 0$
$\hat{s} = 1 \implies \hat{c} = 0$

Thus, we have for the value table of $(\hat{c} + \check{c})\cdot 2^{n+1}$, $\hat{c} = 1 \wedge \check{c} = 1$ is unreachable. Thus, we never reach a next degree of 2. Thus, $\hat{c} + \check{c} = \hat{c} \vee \check{c}$

Then, the full adder becomes:

$(\hat{c} + \check{c})\cdot 2^{n+1} + \check{s}\cdot 2^n$ for $HA(x, y) = \hat{c}\cdot 2^{n+1} + \hat{s}\cdot 2^n$ and $HA(\hat{s}, c_{i}) = \check{c}\cdot 2^{n+1} + \check{s}\cdot 2^n$

Thus we have converted the full adder expression to a half adder expression.

![[Pasted image 20260804104236.png|500]]

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

