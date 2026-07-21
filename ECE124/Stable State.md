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

An ASC is said to be in stable state if all internal (significant) signals stop changing.

Stable states can be found in an excitation table by finding inputs where the current state matches with the next state.

---
It is important to dictate stable states as in ASCs, we do not have the luxury of being able to change multiple inputs at once. Thus we must know which states we can "reach" through stable state movement. 

Also, we are not able to prevent skipping over states by accident, and thus must know which inputs allow us to remain on a state. 

For example, if the inputs 01 on state c traverse to state d, but state d does not have a stable state for input 01, then it will immediately jump off of state d (At the same time as the gate delay, but irl this is an unpredictable time)

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

