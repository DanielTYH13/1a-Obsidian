---
tags:
  - review
  - ECE108
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: ECE 108
---
*Key Concepts:*
___

Multichoose is for unordered selection with replacement. Ie when an element can take more than one spot within the set.

Multichoose $(\binom{N}{n}) = \binom{N + n -1}{n}$ 
	
---
If you are choosing n elements from N elements with replacement, this is equivalent to selecting N indices to put n elements into. With the typical choose operation, you are forced to put each element in a distince indice. 

We aim to represent this scenario in a way that distinct indices can represent one index. 

A way to do this is by creating partition indexes. N - 1 partitions create N valid spots for elements to be. We then place the n elements into any given spot in between these partitions, creating an N-1 + n bit string, representing a 1 as a spot with an element in it, and a 0 as a partition.

Convince yourself that regardless of element location, this configuration will always be equivalent to N indices, each with a given amount of elements in it. 

Now, we have avoided the issue of the choose function. All cases with elements in the same virtual index are represented by distinct indexes. This becomes an equivalent situation to combination with replacement, but one which we can use the choose function on.

So we ask ourselves, how many ways can you create an N -1 + n bit string with n 1's. This just becomes a choose function of $\binom{N+n-1}{n}$.

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

