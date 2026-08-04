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

Define functions for voltage and current as follows:

$V(t) = V_{m}cos(\omega t + \theta_v)$
$I(t) = I_{m}cos(\omega t + \theta_I)$

Then, given that $P(t) = V(t)I(t)$, we have that:

$P(t) = \frac{V_m I_m}{2}\cos(\theta_{v}-\theta_{i}) + \frac{V_{m}I_{m}}{2} \cos(\theta_{v}- \theta_{i}) \cos(2\omega t) - \frac{V_{m}I_{m}}{2} \sin(\theta_{v}- \theta_{i}) \sin(2\omega t)$

We then define:

P = real/average power = $\frac{V_{m}I_{m}}{2}\cos(\theta_{v}- \theta_i)$
Q = reactive power = $\frac{V_{m}I_{m}}{2}\sin(\theta_{v}- \theta_i)$
pf = power factor = $cos(2\omega t)$
rf = reactive factor = $sin(2\omega t)$

Thus it becomes:

$P(t) = P + Pp_{f} - Qr_{f}$

**Note, this is the power dependent on time. It is instantaneous.**

---
Why is P called the "real power" and Q called the "reactive power"?

Using the impedence triangle, we can derive: 

- $\sin(\theta_{v}- \theta_{i}) = \frac{X}{|Z|}$
- $\cos(\theta_{v}- \theta_{i}) = \frac{R}{|Z|}$

Ie, using the phase shift angle, we can tell something about the amount of reactance / pure resistence, normalized by the overall impedence.

Using the conversion: $\frac{V_{m} I_{m}}{{2}}  = \frac{I_{m}|Z| I_{m}}{2} = {I_{rms}^2}|Z|$, we obtain:

$P = I^2_{rms} R$
$P = I^2_{rms} X$

Ie, since Voltage max contains some information about the magnitude of impedence, we obtain either the real resistence, or reactance, depending on if its sin or cos. 

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

