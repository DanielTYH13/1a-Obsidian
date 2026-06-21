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

Mathematically, it does not matter what polarity you use for opposing voltages. However, like any coordinate system, it is useful to add specifications.

It is useful to do something like (This way is better as it matches the definiton of Voltage, which is the drop in voltage):
Positive - Drop in voltage from in to out (current direction)
Negative - Increase in voltage from in to out (current direction) 

Or equally (But worse), 

Positive - Increase in voltage from in to out (current direction)
Negative - Drop in voltage from in to out (current direction) 

This way, when working out power for components without polarity (+, -), you can calculate voltage drop using KVL and then use [[Power Absorption or Development Convention | opposing polarities]] to find the power. 

![[Pasted image 20260613172933.png]]
-10 + 30 + V_current = 0
V_current =  -20 (Growth by 20)
P = V_dropxCurrent = -20x8 = -160

and equally, 

10 - 30 + V_current = 0
V_current = 20 (Growth by 20)
P = V_dropxCurrent = -20x8 = -160 


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

