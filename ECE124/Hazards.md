---
tags:
  - review
  - ECE124
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: ECE124 U1
---
*Key Concepts*

Hazards are when a circuit (almost always a sequential circuit) temporarily has an output that is not expected for the given state or input. 

They are caused by uneven propogation of signals throughout the circuit. This is describe in more detail in the [[Static Hazards in SOPs or POSs]]

---

In sequential circuits, a momentary discrepency in the outputs of the circuits governing state variables can cause the FSM to settle into an unexpected state, causing unpredictable behavior.

---

There are two types of hazards:

1. Static Hazards
2. Dynamic Hazards

A Static hazard is one which occurs when the output of a sequential circuit should stay constant. 

Ie, 1-0-1 or 0-1-0

A dynamic hazard is one which occurs during a transition between 0 to 1 or vice versa:

Ie, 1-0-1-0 or 0-1-0-1

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

