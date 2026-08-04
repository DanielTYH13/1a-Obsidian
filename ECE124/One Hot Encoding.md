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

We have that for N states, the i'th state is represented a series of 0s and a 1 in the i'th index, with a total length of N. 

Then, for any transition between two states, create a transitionary state which is the bitwise AND of the two states.

Since, by definition, for each state, there can only be 1 true bit, then the union of two bit strings, assuming they are different states, can be a maximum difference of 1 bit flip from each individual bit string.

Thus, this format of encoding the states garuntees a simple way to create a transitionary state for any two different state with a bit flip difference of 1. 

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

