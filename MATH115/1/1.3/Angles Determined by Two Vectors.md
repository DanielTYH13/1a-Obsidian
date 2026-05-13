---
tags:
  - "#review"
  - "#MATH115"
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
---
*Key Concepts:*
___
- Two vectors in $\mathbb{R}^2$ or $\mathbb{R}^3$ determing an angle $\theta$ with $-\pi \le \theta \le \pi$
	- The restriction on $\theta$ removes the reflex angle, as the reflex angle will always have a magnitude greater than pi.
		- When both angles are equally spaced, the reflex angle = the internal angle. 
	- Recall: 
		- Acute angle: $0 \le \theta < \frac{\pi}{2}$ 
		- Right angle: $\theta = \pi$
		- Obtuse angle: $\pi < \theta \le \pi$
			- *This is implies that an angle of pi is obtuse, which it is.*

*Significant Theorems:*
___
1. For vectors $\vec{x}, \vec{y} \in \mathbb{R}^{2,3}, \theta \space with \space  0\le\theta\le\pi, \vec{x}\cdot\vec{y}=\|\vec{x}\|\|\vec{y}\|\cos(\theta)$. See line 11  for the reason that theta is restricted. 
2. $\cos(\theta) = \frac{\vec{x}\cdot\vec{y}}{\|\vec{x}\|\|\vec{y}\|}$ 
	- Since the norm and dot product of a vector extend in to $\mathbb{R}^n$, this can give you the angle determined between to vectors in high dimensional space. :D 

*Respective Proofs*
___
1. 
	1. Construct an acute angle with two vectors: $\vec{x}, \space \vec{y}$.
	2. The law of cosines gives: $\|\vec{x}-\vec{y}\|^{2}= \|\vec{x}\|^{2}+\|\vec{y}\|^{2} -2\|\vec{x}\|\|\vec{y}\|\cos(\theta)$ 
	3. Seperately, $\|\vec{x}-\vec{y}\|^{2}=(\vec{x}-\vec{y})\cdot(\vec{x}-\vec{y}) \quad \text{given that the norm squared of a vector is the vector dotted with itself}$
	4. Thus: $$
	\begin{split}
		\|\vec{x}-\vec{y}\|^{2} &=(\vec{x}-\vec{y})\cdot(\vec{x}-\vec{y})\\
		& = \vec{x}\cdot\vec{x} - \vec{y}\cdot\vec{x} + \vec{x}\cdot(-\vec{y}) + (-\vec{y})\cdot(-\vec{y}) \\
		& = \|\vec{x}\|^{2}+\|-\vec{y}\|^{2}-2(\vec{x}\cdot\vec{y}) \\
		 & = \|\vec{x}\|^{2}+ \|\vec{y}\|^{2} - 2(\vec{x}\cdot\vec{y})
	\end{split}
	$$
	5. Returning to the first equation gives: $$
	\begin{split}
		-2\|\vec{x}\|\|\vec{y}\|\cos(\theta) &= -2(\vec{x}\cdot\vec{y})\\
		\|\vec{x}\|\vec{y}\|\cos(\theta) &= \vec{x}\cdot\vec{y}
	\end{split}
	$$


*Common Mistakes:*
___

*Terms and Definitions:*
___

