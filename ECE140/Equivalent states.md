---
tags:
  - review
  - ECE140
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: ECE 140
---
*Key Concepts:*
___
IMPORTANTLY

States are said to be equivalent if they:
1. Have identical outputs
2. Have the same next states. 

An FSM is an abstract concept where states are *defined* as the characteristic location the FSM is in. Thus, if all next state and output behavior is the same, the FSM is functionaly and strictly in the same characteristic state. Thus those two states can be combined.

Note that you cannot simply erase one of the two states. All links to this equivalent state must be preserved. It is simply a matter of not needing to define the state twice. 

---
States can be reduced through partitioning. 

We can create superstates initially based on outputs. These are the states which "have the potential to be equal".

Then, we propogate downwards to find whether all states within point the same superstates, and create new superstates if they do not. 

This will garuntee that eventually, we will have certain superstates which have all equal internal states. 

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

