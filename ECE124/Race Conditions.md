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

For n state variables changing, there are $2^n$ possible states reachable in the change. We always assume that in real life, state variables can change at different times, thus introducing probability of landing on any of these possible states during a state change

For the $n = 1$ case, this means there are only 2: The current and the next state $\implies$ 0 possibility of reaching unintended states.

For $n > 1$, we have extra cases outside of the current and next. Thus, there exists a probability of landing on an unintended case, at which state variable logic changes, thus "throwing" the fsm off expected behavior.

This is why we need to limit to $n = 1$ case. 

---

We always assume that in real life, state variables can change at different times, thus introducing probability
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

