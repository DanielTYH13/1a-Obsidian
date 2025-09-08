---
tags:
---
*Key Concepts:*
___
- When composing the function $(f\circ g)(x)$, the resulting domain of the function is $x\in D_{f(x)}\bigcup S_{g(x)}$, where $S$ is the set representing the domain of $g(x)$ that corresponds to a range which intersects with $D_{f(x)}$ .
	- In other words, in order for the composite function to be valid, function $g(x)$ needs to output a range which complies with the domain of $f(x)$. 
- Graphically, $f^{-1}$ is the reflection of $f$ over the line $y = x$.
- When inverting a function, the domain and the range swap.
	- A function is invertible (Meaning that its inverse is a function), if it passes the horizontal line test
	- If the function passes both the HLT and VLT, then it is one-to-one, meaning each input has only one corresponding output, and vice versa. 
- Function is even if $f(-x) = f(x)$, and odd if $f(-x) = -f(x)$
	- Even functions have symmetry across $x = 0$, whereas odd functions have rotational symmetry around the origin.

*Significant Theorems:*
___
- Any fcn who's domain is symmetric about x=0 can be expressed as the sum of an odd and even component. [1]
- $f(f^{-1}) = x$, and $f^{-1}(f) = x$. 
	- Useful for checking the correctness of an inverse function.
- $f(x) = y \iff f^{-1}(y) = x$
	- Useful for finding functions given two other functions.

*Respective Proofs*
___

T. 1:
$$
\begin{align}
f(x) & = f(x)+\frac{1}{2}f(-x)-\frac{1}{2}f(-x)
\\
f(x) &= \frac{1}{2}f(x) + \frac{1}{2}f(-x)+ \frac{1}{2}f(x) - \frac{1}{2}f(-x)
\\
f(x) &= \frac{1}{2}(f(x) + f(-x)) + \frac{1}{2}(f(x)-f(-x))
\end{align}

$$

As you can see, regardless of the sign of x, the first function will remain equivalent. On the other hand, the second function will become $\frac{1}{2}(f(-x)-f(x))$, or $\frac{-1}{2}(f(x)-f(-x))$.

*Terms and Definitions:
___

*Common Mistakes:*
___
