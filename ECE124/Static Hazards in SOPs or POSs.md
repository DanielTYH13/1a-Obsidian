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

Given an SOP or POS, there are individual terms dictate the output for a given input.

In real life, signal propogation is not instant. Thus, if one term goes to 0 or 1, while another does the same, there may be a period of time where both terms are inactive. 

During this time, the output of the circuit is wrong, as the defined behavior is not being realized.

---
This behaviour can be visualized on a Karnaugh map, where any adjacent edges are possible locations where inputs can change, output should remain the same, yet due to a discrepency in timing, the output does not. 

---

The solution is typically to add another term which activates for any inputs bordering the transition. This way, there is ample time for another term to "carry the transition" and keep the output high while the others switch. 

Note that even this can fail if transitions are quick enough. For example, if inputs change quickly enough from any location on the K map, transition states can be skipped and thus static hazards may occur. 

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

