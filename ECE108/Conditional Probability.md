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

Conditional probability $Pr\{A | B\}$ is said to be the probability of A, given B.

It is defined as $Pr\{A | B \} = \frac{Pr\{A \bigcap B\}}{Pr\{B\}}$

---
Intuition

The intuition is that you ask, what is the probability that A and B happen, given that B already happened?

So you find the probability for both, then you "divide out" the probability of B so that you find the probability of A and B, "assuming that B has already happened, factoring out its probability". 

You can tell that dividing by a number $\le 1$, $\ge 0$ will cause the conditional probability to become higher, as expected.

---
Proof

$\frac{Pr\{A \bigcap B\}}{Pr\{B\}} = \frac{|A \bigcap B|}{|S|} \div \frac{|B|}{|S|} = \frac{|A \bigcap B|}{|B|} = Pr\{A | B \}$

$\frac{Pr\{A \bigcap B\}}{Pr\{B\}} = \frac{|A \bigcap B|}{|S|} \div \frac{|B|}{|S|}$

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

