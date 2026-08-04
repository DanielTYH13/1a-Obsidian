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

Race conditions occur in an FSM when two or more state variables change during a transition. 

This is because in real circuits, the state variable cannot change at the same time. Thus, for a period of time, the FSM's state will be in a state which has different behavior than expected, thus "throwing off" the transition to a different destination.

---

If the race condition, regardless of the order of change, results in the correct final state, then it is benign. 

If it doesn't, then it obviously isn't.

---

The solution to this is to ensure that all transitions only change at most one state variable at a time - as long as the final destination is preserved. 

This can be done through:

- The use of [[Unstable State Synthesis]]
- The use of [[Equivalent State Synthesis]]
- [[One Hot Encoding]]
 
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

