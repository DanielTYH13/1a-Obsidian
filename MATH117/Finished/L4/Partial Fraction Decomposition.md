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
**What is the Partial Fraction Decomposition of a Rational Function?**

- PFD simplifies a proper rational function into the sum of proper terms. This is useful in ==problems where additive rules work out nicely, such as integrals.== (P)
	- Rational function decomposition is the opposite of combining rationals with unlike denominators.

---
**How does PFD work?**

- Decomposition of a function is the ==reverse of adding two rational functions==
	- Instead of finding an LCM to add both rationals, you ==divide into the individual components of the LCM and split the numerators instead.== (T)

---
**When to use PFD?**

- The rational function $\frac{f(x)}{g(x)}$ is in proper form $\iff$ $deg(f(x)) < deg(g(x))$
	- PFD requires the argument to be a ==proper== rational function. (P)
		- **Reasoning:** Recall that PFD is the inverse of combining rationals. PFD's purpose is to decompose into a sum of *proper* terms. The sum of an arbitrary n proper rationals will always have numerator degree less than denominator degree.
			- A great excercise is to prove this==.== 

---
**PFD Algorithm**

1. ==Factor the function completely==
2. Equate ==depending on the form of the function==
3. Compare ==coefficients== and solve for them.

---
**Forms of PFD**

- Distinct Linear
	- Denom: $(x+a)(x+b)...$
	- General decomposed form: ==$\frac{A}{x+a}+\frac{B}{x+b}...$==
- Repeated Linear
	- Denom: $(x+k)^n$
	- General decomposed form: ==$\frac{A}{x+k}+\frac{B}{(x+k)^2}+\frac{C}{(x+k)^3}\dots$==
- Distinct irreducible quadratic
	- Denom: $(ax^{2}+bx+c)\cdot(dx^{2}+ex+c)\dots$
	- General decomposed form: ==$\frac{Ax+b}{ax^{2}+bx+c}+\frac{Cx+d}{dx^{2}+ex+c}\cdots$==
- Repeated irreducible quadratic
	- Denom: $(ax^{2}+bx+c)^n$
	- General decomposed form: ==$\frac{Ax+b}{ax^{2}+bx+c}+\frac{Cx+d}{(ax^{2}+bx+c)^2}\dots$==
- Combined:
	- Denom: Can be both quadratic and linear combined together
	- General decomposed form: ==Use individual numerator coefs for the linear ones, and then linear relationships for the quadratics.== 

%% #TODO: Why are the numerators they way they are? For example, why can't the quadratic have constant numerators in their decomposed form? %%

*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

