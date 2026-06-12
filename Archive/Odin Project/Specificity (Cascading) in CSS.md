---
tags:
  - "#review"
  - "#flashcards"
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
---
*Key Concepts:*
___

Specificity defines which CSS rules are added, and which are ignored, in the case of a conflict.

Between any number of conflicting rules, (In general), the rule with the highest specificity is chosen.

Specificity primarily depends on the selector and the quantity of selectors:
- (Highest to lowest specificity)
	1. Identifiers (IDs)
	2. Classes
	3. Types
1. When there are two rules with the same selector, then the quantity is checked.
	1. 2 chained / child relationship classes are prioritized over 1 class.
	2. 1 class selector + 1 type selector are prioritized over 1 class selector
2. Any selector with higher specificity automatically beats other rules with only lower specificity selectors, regardless of their quantity. 

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

