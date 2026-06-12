---
tags:
  - review
  - ECE140
sr-due: 2025-09-20
sr-interval: 3
sr-ease: 250
TARGET DECK: ECE 140
---
*Key Concepts:*
___

Norton and Thevenin circuits are equivalent circuits for voltage and current sources, respectively. They involve a resistor in series (For Thevenin) and in parallel (For Norton).

---
In both cases, the resistance stays the same. You then use a set value (The voltage or current, which must stay the same.) to calculate the new current or voltage source.

---
Importantly, the behaviour and characteristics (Voltage, current, resistance) Looking into the terminals of the source are equivalent between forms for any given load. 

---
Derivation of Norton and thevenin:

Consider the forms:![[Pasted image 20260611221956.png]]

For the Thevenin form, the voltage across the load is given by:

$V_{out}=V_{t} \frac{R_{0}}{R + R_{0}}$

For the Norton:

$V_{out}=I_{n}\frac{RR_{0}}{R_{0}+R}$

We want the equivalent circuits, ie the voltage across any given load is the same for both circuits, and thus we need $V_{Thevenin}= I_{Norton}R$.

It just so happens that this works out very nicely with the basic characteristics of each equivalent. In other words, you can fix the resistor, and calculate for the value of a Voltage / Current source based on what the voltage / current is for the other equivalent. 

$V_{t}= I_{n}R$ Find the voltage change across Norton current source
$I_{n}=\frac{V_{t}}{R}$  (Derived from above line) Find the current across the Thevenin current source if it was shorted (Shorted is just a computation convenience).

#TODO finish the above. 

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

