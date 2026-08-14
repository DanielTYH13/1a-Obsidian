---
tags:
  - review
  - ECE108
sr-due: 2026-09-18
sr-interval: 42
sr-ease: 230
TARGET DECK: ECE 108
---
*Key Concepts:*
___

Posets, or Partially Ordered Sets, are given as $\mathscr{P}(S, \preceq)$, where S is a the partially ordered set and R is the relation.


R must satisfy the following requirements

- R is [[Reflexive Relations|reflexive]]
- R is [[Transitive Relations|transitive]]
- R is [[Antisymmetric Relations|antisymmetric]]

Thus, the elements in the set S are related as a hierarchy. This is because:

- Reflexivity means that 
- Transitivity means that all top nodes are connected to downstream nodes
- Antisymmetry means that elements are related "downstream" only, and that there are no circular structures
	- For a node $n$ downstream of a higher node $n_{0}$, there must exist $\langle n_{0}, n\rangle \in R$ by transitivity. And by antisymmetry, that means that $\langle n, n_{0}\rangle \notin R$

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

