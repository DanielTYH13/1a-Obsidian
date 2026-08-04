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

Determining prime implicants:

An important prerequisite is to know that the less terms in a k-map term, the more minterms it covers (the less restrictive it is).

The Tabular method of finding prime implicants works because:

1. Grouping by 1's means you can list adjacent groups, of which will be different by exactly 1. This garuntees that there will be at least one variable which has different values.

2. Merging terms which dont cares in the same places means that they will be parallel with each other. This assures that groups grow exponentially (Multiply by 2 each time)

3. It is also a property that if two groups differ by only 1 numbers of true bits, then they are adjacent (not diagonal), and therefore combineable with a K map grouping. (Exercise: What happens if you try to combine two diagonal terms?).

It is garunteed that the tabular method finds all combineable groups.

Thus, every iteration that you combine terms (eliminating variables) from groups creates new K-map terms of equal sizes. In other words, it is a recursive process which slowly eliminates variables from the most restrictive terms until it is not possible anymore. This is the exact process of reduction of an implicant. 

Therefore those without checks are those which cannot be reduced into less restrictive K maps, and therefore those which are prime implicants.

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

