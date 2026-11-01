---
id: 1984-10-belkin-postoyannyiy-i-peremennyiy-elektricheskiy-tok-f2e77e26
issue: kvant_1984_10
year: 1984
number: "10"
title: Direct and alternating electric current
authors:
  - Белкин И. К.
rubric: shkola-v-kvante
page_first: 30
page_last: 31
page_labels: 28-29
tag: 812G
lang: en
source: kvant_digital
extraction: vision
content_sha256: e367491b808239a7c08ab55ed0b79a73b4069b40d53093bae952f56c5fd89b7c
prompt_sha256: draft-1
translated_from: content/ru/1984/10/articles/11_belkin-postoyannyiy-i-peremennyiy-elektricheskiy-tok-f2e77e26.md
source_content_sha256: 3346da8bc46b67f56ae83511e739e5ee44a6df6c6db2b700d47de5f3ba531692
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

Direct and alternating electric current

For a long time, the only source of electric current was a galvanic element, which appeared at the very beginning of the 19th century. In the circuit connected to such a source, a constant electric current flows.

Success in the study of electromagnetism led to the invention of the alternating current generator, and since then it has been alternating current that has become the basis of modern electrical power engineering.

Why? Why is alternating current “better” than direct current?

Alternating current, like direct current, is the ordered movement of charged particles, in particular in metals - electrons. But in an alternating current circuit, electrons change the direction of their ordered movement many times. The low mass of electrics allows them to “have time” to change the direction of movement not only 100 times per second, as happens in an industrial network, but also ten million times per second, as, for example, in radio station antennas.

If alternating current flows in the electrical circuit, the target must be connected to a source of alternating emf. It acts here as a periodic driving force, and the current in the circuit performs forced oscillations, of course, with the frequency of the driving force. If the EMF in the source changes with time according to the law $e = \mathcal{E}_m \cos \omega t$ and the source is connected to a target with active resistance $R$, then the current also changes according to the cosine law (“Physics 10”, § 17):

$$i = \frac{e}{R} = \frac{\mathcal{E}_m}{R} \cos \omega t = I_m \cos \omega t.$$

Here $\mathcal{E}_m$ and $I_m$ are the amplitudes (maximum values) of the EMF and current strength. But the properties of the cosine function are such that on average during the oscillation period the current strength is zero. This, however, does not mean that such a current is useless and does not manifest itself in anything. Because although on average the current is zero, the square of the current is not zero. And the power of the current is determined precisely by the square of the current. At any moment of time, the alternating current power in a circuit with active resistance is expressed by the equality

$$p = i^2 R = I_m^2 R \cos^2 \omega t.$$

The average value of the squared cosine over a period is not zero, but $1/2$, so the average power

$$\bar{p} = \bar{i}^2 R = \frac{1}{2} I_m^2 R = \left( \frac{I_m}{\sqrt{2}} \right)^2 R.$$

The value $I = I_m / \sqrt{2}$ is called the effective value of the current. In our case, power can also be expressed in terms of voltage across the resistance:

$$p = \frac{u^2}{R}, \bar{p} = \frac{\bar{u}^2}{R} = \frac{1}{2} \frac{U_m^2}{R} = \frac{U^2}{R},$$

where $U = U_m / \sqrt{2}$ is the effective voltage value.

This condition is one of the negative properties of alternating current. After all, the wires through which current flows must be designed for the maximum current value, and practical ones use a little more than 2/3 of this value. There are other negative consequences. The phenomenon of electromagnetic induction leads, for example, to the fact that alternating current in wires is not distributed evenly over the entire cross-section, but mainly near the surface. (This phenomenon is called a skin effect, it is not discussed in Physics 10. Characteristically, the depth of penetration of alternating current depends on many factors, including the frequency of oscillations. Thus, at a frequency of 50 Hz in a copper conductor, this depth is ≈ 9 mm. With increasing frequency, the penetration depth of the current decreases.) Due to the fact that not all cross-sections of wires are used, their resistance implements. Further, alternating current, like direct current, is surrounded by a magnetic field, but an alternating field. And such a field, according to the law of electromagnetic induction, causes in neighboring

⟦folio 29⟧

wires and other conductive materials carry electrical currents, resulting in wasted energy consumption.

All these disadvantages are completely absent from direct current. Why does alternating current almost completely dominate in technology and in everyday life?

First of all, the very principle of operation of electric generators is such that it is the variable EMF that arises in them (“Physics 10”, § 23). But that's not the point. Using a simple device, you can make the same generator a source of direct current. The main reason for the “popularity” of alternating current is due to the fact that electrical energy comes to be transmitted from places where it is produced (power plants) to places where it is consumed and often over long distances. In this case, part of the transmitted energy is inevitably lost in the form of heat, through which it is transmitted in power transmission lines (PTL). To ensure that losses are not too high, it turns out that high voltage must be used for transmission.

The need for high voltage can be seen from the following simple calculation. Let us assume that electrical power $P=66$ kW is transmitted from the power plant to the city under a voltage of 220 V (this is the voltage that is usually used by the consumer). Let the power line resistance be 0.4 Ohm. Then the current strength in the power line is $I=66000 \text{ Вт}/220 \text{ В}=300 \text{ А}$, and the amount of heat released in the line is $Q=I^2R=(300 \text{ А})^20,4 \text{ Ом}=36000 \text{ Вт}$. A large proportion of the transmitted power (54.5%) will be lost as heat in the power lines! Now let’s imagine that the same power is transmitted along the same power line at a voltage of 22000 V. Now the current in the circuit will be equal to $I=66000 \text{ Вт}/22000 \text{ В}=3 \text{ А}$, and the amount of heat released will be $Q=(3 \text{ А})^20,4 \text{ Ом}=3,6 \text{ Вт}$. The requirement is only about 0.005%! That is why electrical energy is always transmitted along power lines at very high voltages - 110,220,330,400,500 and even 750 kilovolts.

But at the terminals of power plant generators, the voltage is significantly lower - only a few thousand volts. This means that at the beginning of the power transmission line this voltage must be increased, and before distributing the energy among consumers, it must be lowered so that the consumer receives it at a voltage of 220 volts. Such an increase and decrease in voltage is possible only for alternating current. This is done using a device that operates on the basis of the phenomenon of electromagnetic induction - transformers (“Physics 10”, § 24). The existence of transformers is perhaps the only reason for the increased use of alternating current in technology.

However, the disadvantages of alternating current, which were outlined above, make us think about whether it is still possible to use direct current, of course, also high voltage, to transmit electrical energy? This is not easy to do. Indeed, first you need to convert the alternating voltage, after increasing it, into direct voltage (rectifiers are used for this), and then at the other end of the power line, convert the alternating direct voltage into alternating voltage (this can be done using devices called inverters), so that the voltage can be lowered to the value you need to consume. However, such a direct current power line with a voltage of 400 kV is already operating in the USSR.

What has been said in this note cannot be interpreted as saying that direct current is “good” current, and alternating current is “bad”. Both are natural phenomena, and they cannot be assessed with the words “better” or “worse”. The above only means that direct current is optimal for transmitting energy over long distances. And if the use of alternating current for this purpose is still being transformed, this is explained by the fact that the conversion of alternating current into direct current and vice versa is still a difficult task, which, however, is being successfully solved. For a technician, both currents are equally necessary and useful. In some cases direct current is indispensable, for example where electrolysis is used. But without alternating currents there would be no radio communications, television, etc. Rephasing the famous children's poem, we can say: all sorts of currents are needed!
