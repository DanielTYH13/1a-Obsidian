---
tags:
  - review
  - ECE124
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: ECE124 U1
---
*Key Concepts:*
___

The two's complement is like the 1's complement, but converting from positive to negative is given as

$x_{-} = 2^n - x_{+}$.

In other words, take the 1's complement, and add 1. 

Similarily, to go from negative to positive, subtract 1 and then flip. To quickly identify negative numbers, subtract 1 and count the 0s. 

The two's complement is mirrored. In other words, for positive values, the higher the absolute magnitude of the bit string, the higher the represented number. 

Since negatives are defined by a subtraction, for negative values, the lower the absolute magnitude of the bit string, the lower the magnitude of the represented number.

Since negatives are defined by subtraction across the max value, there is a natural symmetry at $b_{n-1} = 0$, where all values for $b_{n-1} = 0$ are mapped to the $b_{n-1} = 1$ domain (not exactly, as the negative domain is slightly larger), and thus we assign $b_{n-1} = 0$ as positive and vice versa. This way, it is also a sign bit, allowing us to easily tell the polarity.

---
Why 2's complement?

The 2's complement has the best endpoints, and properties for addition and multiplication.

Firstly, it is self similar at 0. For example, given 0000, it's negative complement is given as $1111 + 1 = 0000$. In other words, there is only one 0.

However, this shifts the bounds, and adding 1 is why they are $[-2^{n-1}, 2^{n-1}+1]$

Secondly, carries past the n'th bit, as long as they aren't overflows, do not affect the calculation.

---
How to detect overflows?

Two numbers in 2's complement will overflow if and only if they are both the same sign, and their magnitude is past the bounds, thus causing a flip in the sign bit. 

Expressed as a boolean expression, $\text{overflow} = xys' \wedge x'y's$, where $x, y, s$ are the polarity of the two inputs and their sum. 

The reason that two inputs of opposite sign cannot overflow is because they cancel each other to some extent, and since they are defined by the 2's complement, the magnitude of either must stay within the bounds.

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

