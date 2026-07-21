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

An ASC does not have a clock signal. All signals are unrestricted by clocks.

An implication of this is that they do not have standard storage elements.

ASCs have feedback loops, which create a memory effect as it simulates a constant "input" which retains the state. 

---
Any circuit with input, combinational logic, output, and a feedback loop is considered to be an ASC. This includes SR and gated latches.

![[Pasted image 20260703083828.png|500]]

---
ASCs are modelled with a delay element to differentiate the current state from the next state, since there is not ff. (And helps define oscillations).

It also helps simulate real delays in the gates. 

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

