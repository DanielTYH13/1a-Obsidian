---
tags:
  - "#review"
  - MATH119
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: MATH119 U1
---
*Key Concepts:*
___

When you are given a sequence that involves fractions, with growing or shrinking terms on the top of bottom, then the fastest growing terms on the numerator and denominator define the behavior of the denominator and the numerator.

This is a core concept of big O notation. It is the idea that since they grow faster, as n goes to infinity, the other terms become rounding errors (go to 0 wrt the dominating term), and thus can be ignored for infinite series. 

In other words, by deleting the non dominating terms, we can maintain the shape of the growth of the partial series approaching infinity, but also reduce the complexity greatly.

---
Example:

$\mathscr{O}\left(\displaystyle \lim_{N \to \infty} \sum^N_{n = 0} \frac{\sqrt{n} + 5}{n^2 + 17n + \sin(n)}\right) = \mathscr{O} \left(\displaystyle \lim_{N \to \infty} \sum^N_{n = 0}\frac{\sqrt{n}}{n^2}\right)$

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

