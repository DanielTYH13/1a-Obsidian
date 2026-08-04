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

There are three recursive steps necessary to determing NNEPIs. 

---
Row Domination

If a PI's range is a subset of another PI, then it is said to be dominated by the other PI.

To find NNEPIs, we remove the row of the dominated PI. 

Both PIs could potentially be NNEPIs for the intersection of the given terms they cover. However, this is done as to maximize coverage with minimal cost (Inverse freedom property).

---
Collumn domination

If a collumn's contents is a subset of another collumn, then it is said to be dominated by the other collumn.

To find NNEPIs, we remove the dominating collumn. 

We do this because this means that there exists at least one PI which covers that collumn and another, whereas the other PI which covers this collumn does not cover another. Thus, we get rid of the dominating collumn to explicitly remove the requirement of the less comprehensive PI to cover it.

This way, unless it is necessary for another minterm, it won't accidentally be favoured over a more effecient PI to cover a given minterm.

---

We eliminate a row and add it to the cover when it becomes essential. This way, and stop this process when there are no more prime implicants in the table. 

This method ensures that all suboptimal PIs are eliminated recursively until no more can be eliminated, thus determining a NNEPI.

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

