---
id: 1990-6-zilberman-yavlenie-samoinduktsii-7c0d63f7
issue: kvant_1990_6
year: 1990
number: "6"
title: Self-induction phenomenon
authors:
  - Зильберман А. Р.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 65
page_last: 68
page_labels: 63, 64, 66
lang: en
source: kvant_digital
extraction: vision
content_sha256: c7c9d0a7e09fd9a0084d1030322d6090b60acaf4620dcf63e300e7687a80262e
prompt_sha256: draft-1
translated_from: content/ru/1990/06/articles/15_zilberman-yavlenie-samoinduktsii-7c0d63f7.md
source_content_sha256: 3a229f6834eb02bd71446a8e45ae639307f440170228a94b402ec9ffbe5fd669
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 63⟧

---
running_head:
folio:
---

The phenomenon of self-indulgence

A. ZILBERMAN

Let's start with a standard problem, which is found in almost all problems.

Problem 1. Parallel conducting rails are connected by a resistor with resistance R and placed in an external magnetic field, the induction of which is equal to $B_0$ and is overridden by the plane of the rails (Fig. 1). Another conductor, closing the rails, moves along them at a constant speed $v_0$. Assuming that all the resistance of the circuit is concentrated in the resistor, find the induced current flowing through the circuit.

Let us present a general solution. The current is determined by the electromotive force of induction, and it is determined by the change in magnetic flux. In a short period of time $\Delta t$ the conductor will change to $v_0\Delta t$, the flux will change to $\Delta \Phi = B_0lv_0\Delta t$, and the current will be equal

$$I = \frac{\mathcal{E}}{R} = \frac{\Delta \Phi / \Delta t}{R} = \frac{B_0lv_0}{R}.$$

Attention! This solution contains a major error and the answer is incorrect! Think about it - did we all learn when we were calculating magnetic flux? Of course not. Magnetic flux $\Phi$

Fig. 1.

63

⟦folio 64⟧

---
running_head:
folio:
---

Faraday's horse is a total flux, which is determined not only by the external field, but also by the field of its own current - the induction current. But perhaps in this case the induction field (and its flow) can be neglected? But this already depends on how high the resistance of the resistor $R$ is. With a very high resistance, the induction current will be very small and will not noticeably affect the EMF. If $R$ is not large, the induction current cannot be neglected, otherwise you can make a mistake many times over. Things will be very bad in case $R=0$ (superconducting circuit) - the magnetic flux of the own current becomes definite. In general, the phenomenon of self-niduction (this is what we are talking about) cannot be neglected - the induction current adds to the total magnetic flux and this addition is important. (Often they try to ignore this simply because it is not very easy to check the corresponding calculation.)

Self-niduction is a special case of the general phenomenon of electromagnetic induction; it is distinguished rather by tradition. In its pure form, the phenomenon of self-niduction is found in electrical engineering and radio engineering, where the circuit is usually depicted on diagrams in the form of a coil (and resistors, regardless of their specific device, look identical rectangles on the diagrams). It must be borne in mind that a magnetic field arises around any current-carrying conductor, which means that in any case we can talk about magnetic flux, magnetic field energy, etc. In other words, even a small piece of wire has a certain inductance, which cannot always be neglected.

Let's look at another useful problem.

Problem 2. A flat circuit is made of wire having a total resistance of $r$; its area is $S$ and inductance is $L$. Initially, the circuit is placed in a uniform magnetic field with an induction equal to $B_0$ and directed perpendicular to the plane of the circuit.

The outer field is removed very quickly. What will be the current in the circuit immediately after turning off the external field? How much total charge will flow along the circuit over a long period of time?

The initial value of the magnetic flux in an arbitrary circuit was equal to $\Phi_0 = B_0 S$, but after the field was removed abruptly, the flux could not instantly change and a current arose in the circuit, which copied the change in flux:

$$I_0 = \frac{\Phi_0}{L} = \frac{B_0 S}{L}.$$

If the circuit were superconducting, the current would not change further, remaining equal to $I_0$. However, in our case there is resistance $r$, which means the voltage drop is $U = I_0 r$. Emerging induced emf

$$E = U = \frac{B_0 S r}{L}.$$

Now, due to the presence of resistance, the current in the circuit begins to decrease. At the same time, the induced emf will also decrease - if it remained unchanged, the current would decrease according to a linear law and drop to zero in time

$$\tau = \frac{LI_0}{rI_0} = \frac{L}{r}.$$

Please note that this period of time does not depend on the initial magnetic field and is determined only by the parameters of the circuit itself - its inductance and omnichemic resistance. Of course, during this time the current will not drop to zero - the lower the current, the lower the induced emf and the slower the current will drop. Formally speaking, it will never fall to zero at all, however, over a time 3-5 times longer than $\tau$, it will decrease many times, and its energy (it is due to this energy that the current in the circuit is maintained) also constitutes a very small part of the initial value. In general, in practice we can assume that the time it takes for the current to drop to zero in a circuit with a coil is (3-5)$\tau$.

We have not answered one more question - what charge will flow along the contour over a long period of time. If you answer

⟦folio 66⟧

---
running_head:
folio:
---

the carcass (the diode is ideal as long as it is open, the coil and the capacitor are connected in parallel) returns, the current drops. The diode will close the moment the current drops to zero. There is no energy loss, which means we can use the conservation law:

$$\frac{LI^2_H}{2} = \frac{CU^2_m}{2}, U_m = \frac{U_0 t}{\sqrt{LC}} = 10^3 \text{ В}.$$

If it were not for the diode, oscillations would occur in the circuit, and in our case, the energy accumulated in the circuit would be pumped into the capacitor.

If the switch is closed and opened periodically, then the capacitor voltage can be used to power high-voltage circuits, which is often done (of course, using electronic rather than mechanical switches).

And finally, let's look at the last problem.

Problem 5. Through a coil whose inductance is 2L, a constant current $I_0$ flows from an external source. A parallel circuit made up of a capacitor with capacitance $C$ and an inductance coil $L$ is connected parallel to the first coil, after which the external circuit (Fig. 3) is opened. What is the maximum capacitor voltage? What is the maximum value of the current through the inductance coil $L$?

When the circuit is connected, the capacitor will not charge, and the inductance $L$ will not consume current through the coil, since at a constant current $I_0$ the voltage between the ends of the 2L inductance coil is zero. Changes will begin after opening the external circuit: the capacitor will begin to charge, and a current will appear through the inductance coil $L$ (Fig. 4).

Exercises

1. A resistor with resistance $R=100 \Omega$ is connected in parallel with an inductance coil $L=2 \Gamma$. At this moment, current $I_0=1 \text{ A}$ flows along this circuit. After what time does the current drop to $I=0.99 \text{ A}$? How much heat will be released in the resistor during this time? How much heat will be released in the resistor over the next 5 seconds?

2. The coil consists of 10 turns of thin wire wound on a wooden cylinder close to each other (the resulting thickness of the coil is significantly less than the diameter of the cylinder). Let's wind one more turn in the same direction. How many times will the inductance increase? What if we wind this turn by changing the winding direction to the opposite?
