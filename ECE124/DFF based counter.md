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

The DFF based counter is just a TFF counter but expanded to DFFs,

![[Pasted image 20260620184623.png]]

Something to note is that the core functionality is identical. 

For $\oplus$, if one input is TRUE, then the output is the complement of the other input. 

Ie, 
![[Pasted image 20260620184726.png]]

And thus, the output only turns to 1 when Q_i is false and all previous are TRUE, and importantly, only 0 when Q_i is true and all previous are TRUE. Ie, it only toggles when all previous inputs are TRUE.

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

