---
tags:
  - "#review"
  - MATH117
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
---
*Key Concepts:*
___

- Def. *Sequence*
	- *Informal*: Sequences are expressions with a single ==variable n==, where ==$n\in\mathbb{N}$==, and n ==increments by 1.==
	- *Formal*: Sequences are a collection of ==enumerated (Counting one-by-one) objects where order matters== and ==repetition== is allowed. 

- Divergent -> meaning that it approaches an ==*undefinable* limit==
	- Sequences that go to ==infinity== are divergent
	- Sequences that ==oscillate forever== (In most cases. Exer. Why==?==) are divergent
- Convergent -> meaning that it approaches a ==*definable* limit==

- *Limit Tools for Sequences*:
	- $\displaystyle \lim_{n \to \infty} c = c$  The limit of a constant sequence is ==the constant - it is not affected by n==
	- $\displaystyle \lim_{n \to \infty} n^p = \infty$ The limit of an exponent of n is ==infinity== where ==P > 0==
		- *For example, if $|P| < 1$*, ==*n will still approach infinity== and thus the sequence will as well* 
	- $\displaystyle \lim_{n \to \infty} \frac{1}{n^P} = 0$ where $P > 0$: 1 is divided by ==an ever increasing value==, similar to the above sequence, as long as it is not negated (p < 0)
	- $\displaystyle \lim_{n \to \infty}n^{-P} = 0$ where p > 0. This is equivalent to the above. 
	- $\displaystyle \lim_{n \to \infty} r^n = 0$ if $|r| < 1$: If r is less than 1, it will be infinitely reduced by itself. 
	- $\displaystyle \lim_{n \to \infty} r^n = \infty$ if $|r| > 1$
	
- *Limit Laws for Sequences* 
	- *This is assuming that the limits* $a_{n}\to A$ , $b_{n}\to B$
		- This is short hand form for the limit of a sequence as n approaches infinity.
	- $\displaystyle \lim_{n \to \infty} (a_{n}+b_{n}) = A + B$: This is trivial
	- $\displaystyle \lim_{n \to \infty} (ca_{n}) = cA$ where $c \in \mathbb{R}$: Considering c never changes, it will always stay a coef of the sequence $a_n$ 
	- $\displaystyle \lim_{n \to \infty} a_{n}b_{n}=AB$: This is trivial 
	- $\displaystyle \lim_{n \to \infty}\frac{a_{n}}{b_{n}} = \frac{A}{B}$ where $B \ne 0$: The limit of the quotient of sequences is the quotient of their individual limits
	- $\displaystyle \lim_{n \to \infty}a_{(n+k)}=A$: Shifting the sequence in any direction does not change the limit. 

- *Indeterminate Form*
	- Interderminate forms are forms (Typically of limits) that do not determine any new information
		- Indeterminate form oftentimes occurs when trying to evaluating a limit by evaluating the sequence at the limit, instead of approaching it
	- Ex. $\frac{\infty}{\infty}$

- *Multiplying by 1*
	- A common strategy when evaluating a limit is to multiply it by one
		- Any term divided by itself is one.
	- For example, if you have a rational with degree of 3, multiply it by $\frac{1}{n^3}$
		- This will isolate which terms have to most influence over the sequence (*This explanation is horridly unrigorous*).

*Examples (inline examples)* 
___

- Divergent Sequences:
	- $2n-1$: This sequence is divergent as it approaches infinity
	- $(-1)^n$: This sequence is divergent as it oscillates forever
- Convergent Sequences: 
	- An example of sequence that is periodic but is convergent is a damped sinusoidal function - where it oscillates, but still approaches a value
	- $\frac{1}{n}$: This sequence approaches 0 - it converges to 0.

*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

