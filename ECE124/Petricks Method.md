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

Petricks method is given as:

1. Develop a POS that returns true when a cover is made.
2. Factor into SOP form. 
3. Find the minimum product.
4. That is the minimum cover.

Petricks method is difficult to do manually, but is very rote and therefore can be implemented easily using computers.

---

The POS can be developed as follows:

For every minterm, take the sum of all the PIs that cover it. Then take the product of all these sums. 

This works because:

Say a PI is represented as $PI_{n}$. Then we can interpret the term $PI_{n}$ as true if $PI_{n}$ is included in our cover, and therefore, the minterm is covered.

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

