---
tags:
  - review
  - ECE124
sr-due: 2026-09-20
sr-interval: 100
sr-ease: 250
TARGET DECK: ECE124 U1
---
*Key Concepts:*
___

The product of sums is a way of converting a truth table into a boolean function. 

---

Intuitively, this follows from D'Morgan's law, which indicates that:

$\neg (pq) = \neg p + \neg q$

In other words, you let p, q be a case where the function is false. By taking the logical and of all false terms, you ensure the resultant function is true if and only if the inputs do not produce false on the truth table.  

---

You can think of all inputs as a universal set U, which is evenly split into two sets with no overlap: The set of inputs for which the function is true ($S_{t}$), and the set of inputs for which the function is false ($S_f$) (You can expand this to multiple sets for multibit outputs)
Then POS is the inverse of the sets of all negatives. Since $U  = S_{t} \bigcup S_{f}$, then $\overline{S_{f}} = S_{t}$

This is defined as $S_{t} = \{x \in U | \forall x_{0}\in S_{f},  x \ne x_{0} \}$ 

Logically, this becomes a product of sums, where the product is the "forall", and the sums is the "$\ne$", since for any $x[i] \ne x_{0}[i] \implies x \ne x_{0}$

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

