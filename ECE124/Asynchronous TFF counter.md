---
tags:
  - review
  - ECE124
sr-due: 2026-09-30
sr-interval: 100
sr-ease: 250
TARGET DECK: ECE124 U1
---
*Key Concepts:*
___

The TFF counter works off of the principle:

Any subsequent TFF will only flip given that the previous TFF just turned to 0:

![[Pasted image 20260620183044.png]]

This is exactly the situation where the next bit in a byte needs to go up for the counter to increase only by one. 

The only TFF that changes every time is the initial one, which matches with counting.

Once all inputs are at 1, there will be a cascade that causes the TFFs to reset to 0.

---
The down counter is identical, except that you use $\overline{Q}$ the outputs. 

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

