---
tags:
  - review
  - ECE124
sr-due: 2026-11-22
sr-interval: 100
sr-ease: 250
TARGET DECK: ECE124 U1
---
*Key Concepts:*
___

To prevent race conditions, we need to have only one state variable changing at any given time. 

An FSM of n state variables can be represented in the nth dimensional cartesian space, with existing diagonals of dimension n (Max concurrent variable change of n). Thus we can represent a race condition free version with a $n+1$ dimension cube. 

The states must be unstable so that the FSM transitions directly towards the intended state. 

---
For example, given a state A transitioning to B with 2 state variables, then we need 1 unstable state, U, where U's valuation for the input is B. 

Thus, U immediately evaluates to B on transition to U.

So, we have A -> U -> B.

---

If you plot each state with lines between them on a cartesian grid, then diagonals represent race conditions, as they change in more than one direction (each unit vector representing a change in a bit).

Thus, for 2D, a square represents a race condition free FSM. 
For 3d, a cube represents a race conditions free FSM.
For 4d, it is a tesseract, etc.

Thus, a trick to help find race condition free FSMs is to represent the states as a cube, where there are no diagonals, and all gaps are filled using unstable states to ensure that there are connections between all stable states. 

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

