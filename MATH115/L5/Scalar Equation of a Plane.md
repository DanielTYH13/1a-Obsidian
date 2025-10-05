---
tags:
  - "#review"
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
---
*Key Concepts:*
___

- Given the normal $\vec{n}$ of a plane, and a known point on the plane $P(a, b, c)$:
	- Any given point $Q(x_{1}, x_{2}, x_{3})$ lies on the point if:
		- The vector $\vec{PQ}$ dotted with the normal vector $\vec{n}$ is equal to 0: $\vec{n} \cdot \vec{PQ} = 0$
			- You can conceptualize this as ensuring that the vector PQ is parallel to the plane, and since we know P lies on the plane, PQ must therefore also lie on the plane, and thus Q must also lie on the plane. 
		- We then have: $\vec{n} \cdot \begin{bmatrix} x_{1}-a \\ x_{2}-b \\ x_{3}-c\end{bmatrix} = 0$
		- Which is: $n_{1}(x_{1}-a) + n_{2}(x_{2}-b) + n_{3}(x_{3}-c) = 0$
		- $n_{1}x_{1}+n_{2}x_{2}+n_{3}x_{3}-n_{1}a-n_{2}b-n_{3}c = 0$
		- $n_{1}x_{1}+n_{2}x_{2}+n_{3}x_{3} = n_{1}a+n_{2}b+n_{3}c$
		- $n_{1}x_{1}+n_{2}x_{2}+n_{3}x_{3} = c$ where $c\in \mathbb{R}$ and c is a constant

- Given three points on a plane, you can find two non-zero non-collinear vectors which lie on the plane. You can then compute the cross product, yielding the normal vector. Since you have at least one points on the plane, you can now define the plane in scalar form.
	- The cross product does not require vectors to share any single point. This is because vectors are non-positional.

*Significant Theorems:*
___

*Respective Proofs*
___

*Common Mistakes:*
___

*Terms and Definitions:*
___

