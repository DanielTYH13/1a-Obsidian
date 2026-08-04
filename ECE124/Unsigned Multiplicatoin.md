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

For any two bit strings $s_{1}, s_{2}$ of n length, multiplication is a process which is a series of partial sums as follows:

$s_{1}\cdot 2^0 \wedge s_{2}[0] + s_{1}\cdot 2^1 \wedge s_{2}[1] + \cdots + s_{1}\cdot 2^{n-1} \wedge s_{2}[n-1]$

For example, 

$1110 * 1011 = 1110 + (11100)\cdot 1 + (111000)\cdot 0 + (1110000)\cdot 1 = 10011010$. 

This is the same as decimal multiplication. 

---
We can implement a circuit representation of this form for n bits through a partial sum bit, which is given as:

$FA(\text{Previous value at binary place}, s_{2}[k] \wedge s_{1}[k])$

Where each set of full adders is shifted across by one place. 
	![[Pasted image 20260804120533.png|500]]

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

