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

In order to reduce the state table, we can use partitioning. 

States are said to be equivalent if they:
1. Have identical outputs
2. Have the same next states. 

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

