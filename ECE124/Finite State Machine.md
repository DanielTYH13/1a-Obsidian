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

A finite state machine (FSM) is a synchronous circuit with a set of n states, of which can alternate between each other. 

Implemented as a circuit, there is a 
1. Combinational circuit that modifies the next state based on the current state.
2. Set of latches which store the state.
3. A combinational circuit to dictate the output based on the state (And in the [[Mealy Machine]], the inputs)

The number of latches n needed for m states is: $n = ceil|log_{2}(m)|$

The output of the circuit is defined as Z.

![[Pasted image 20260630150546.png]]

Note that as long as we don't define a path to undefined states based on current state and input, it will never reach undefined behavior so long we implement the logic properly.

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

