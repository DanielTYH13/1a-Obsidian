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

An issue with the TFF is that the signal has to propogate through all TFFs to flip the one at the end. Thus, there is a delay for change throughout all. Logic gates operate significantly quicker than TFFs. 

From the [[Asynchronous TFF counter]], we know that a bit will only toggle if and only if the previous bit switched from 1 to 0 in the previous clock cycle. 

Propogating downwards from bit n, we can tell that this necessarily means that for $b_{n}$ to toggle, all $b_{1}\ldots b_{n-1}$ must be one. Ie, $b_n$ toggles if and only if all previous bits are 1 in the previous cycle.

Thus, we can use AND gates to represent this in a synchronous fashion:

![[Pasted image 20260620184146.png]]

---
Enable and Clear

![[Pasted image 20260620184259.png]]

Setting the Enable to 0 just prevents any toggle in the first TFF, and thus the rest. 

Clear (Active low) just allows you to reset the counter to 0.

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

