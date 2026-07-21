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

Two states are said to be compatible iff:

1. They have the same output 
2. For any given input valuation, they satisfy the following:
	1. Both next states are the same
	2. Both are in stable states
	3. One or both of the next states are unspecified. 

---
**Merger Diagram**

If state A is compatible with state B, and state B is compatible with state C, then state A is compatible with state C. (A proof can be constructed through case analysis).

Thus, any set of transitive pairs, ie pairs which loop to themselves , are all compatible and can be given as a single state.

A visual way to do this is through merger diagrams:

---
**Compatible vs Equivalent states**

Compatible states are different to equivalent states in that they consider unspecified fsm behavior.

Two states are equivalent if and only if they have equivalent NS for ALL input valuations, and outputs. 

Two states are equivalent if and only if they have equivalent NS for all DEFINED input valuations, and outputs

---
**Explanation of conditions**

All requirements should be fairly intuitive, with the exception of condition 2.3, of which's reasoning is given as,

Given any state machine with a certain definition, there are two reasons why a next state may be undefined:

1. It is a don't care. Or in other words, the fsm works properly regardless of the next state here. 
2. It is unreachable based on any given input pattern.

For case 1, it should make sense that we can "change" the don't care to be matching of the other state, after which we can combine them .

For case 2, we must realize that the next state is undefined because of the given input pattern. Since all FSMs must be realized to circuits, we can put whatever gate logic for the unreachable state, and it would still behave the same as we would never reach that input. It is unspecified, because it literally does not matter what goes there.

And such, we can create an equivalent state table that allows the two states to have equivalent next states, after which we can combine the states.

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

