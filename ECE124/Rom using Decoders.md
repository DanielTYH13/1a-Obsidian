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

Decoders are a great way to address / index. One obvious implementation to this is the ROM.

![[Pasted image 20260616190532.png]]

Data is addressed to a single position. By using a n bits to address your memory, you can uniquely identify $2^n$ positions. 

Within this rom block are a bunch of and gates, each containing some true or false value on one end and an activate wire, which is activated using the select wire. 

---
Any combinational circuits with m, n inputs and outputs necessarily has $2^m$ inputs, and corresponding n bits per input. Thus any combinational circuit can be viewed as an $2^m \times n$ ROM. In fact, this can be shown by fully reducing a function using [[Shannon's Expansion Theorem]].

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

