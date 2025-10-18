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

- It is unrigorous to define a limit as the "Behavior of a function near a point"

- Instead, we use the epsilon-delta definition of a limit:

- The ED definition is give as:
	- Give any limit L at a and any tolerance $\epsilon$, we can find a $\delta$ such that:
		- for ==$0 < |x - a| < \delta$== then
		- ==$|f(x)-L| < \epsilon$==
			- ==Note that this is for all x values within the range delta==

- In english, this is saying that:
	- For any possible tolerance, including ==infinitely close to (a, L)==, you can find a ==range of x where all values of f(x) are within that tolerance.==
		- If you are able to prove this as true, no matter how close you get to the limit the following MUST be true:
			- The one sided limits MUST exist. This is because ==The abs in the delta includes both sides, which means that it must be not DNE and also within the range==
			- The one sided limits MUST equal each other. This is because ==At infinitely near the limit, $x \pm \delta$ must be also within that infinitely small tolerance, thus $\implies$ the right and left limits are equal.
			- An example where the epsilon delta definition can be used to prove the existance of a limit:
		![[Pasted image 20251013160257.png|207]]

- Note: ==With ED limit proofs, it is always advised to sketch a drawing of the curve==

- Solving for the Delta for a single case:
	- Note: ==If you have the case where $a < x - a < b$, choose the smaller of a or b as that number will be more restrictive
		- ==This is because this is the expanded form of a absolute function. 
			- When manipulated, the ==variables a and b may change, but regardless, you must realize that it is absoluted so we must keep the most restrictive==
	- Remember that with the form $a < x - a < b$, you must ==take the abs of the smaller of a and b, as this is derived from an abs function in the first place==

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

