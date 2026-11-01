---
id: 1982-2-skorovarov-peremennyiy-elektricheskiy-tok-03e844a7
issue: kvant_1982_2
year: 1982
number: "2"
title: Alternating electric current
authors:
  - Скороваров В. Е.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 41
page_last: 44
page_labels: 39-42
tag: 90KB
lang: en
source: kvant_digital
extraction: vision
content_sha256: 07bb057c2afc4027bd4ee3fac8307137a0a2e06f685a3accd2b8e61fec01b772
prompt_sha256: draft-1
translated_from: content/ru/1982/02/articles/13_skorovarov-peremennyiy-elektricheskiy-tok-03e844a7.md
source_content_sha256: 2be07a1cb5535c0fb6919dc3145a3de07cae30ec4ae9db25ef642669bc884f0a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

Alternating electric current

Alternating current is widely used in industry (plants and factories) and in the general lighting network.

It is known that Ohm's law is satisfied for the built-in current - the current strength in a homogeneous section of the circuit is directly proportional to the applied voltage. In alternating current circuits, the current also depends on the source voltage, but according to a more complex law, since voltage and current change over time. The law of voltage change can be complex, but the most widespread and practical applications are those whose voltage changes according to a harmonic law. For example, like this:

$$u = U_m \cos \omega t,$$

where $U_m$ is the voltage amplitude, $\omega$ is the cyclic frequency, $\omega t = \varphi$ is the oscillation phase. Note that in our country, the frequency adopted for all its territories is $v = \omega/2\pi = 50$ Hz.

An AC electrical circuit consists of a current source and various elements such as storage lamps, electrical devices, capacitors, coils, electric motors, and transformers.

The main task of studying alternating current is the calculation of electrical circuits, that is, determining the current strength at a given voltage of the current source and given parameters of the circuit elements.

In the general case, the current in the circuit, like the source voltage, changes with time according to the harmonic law

$$i = I_m \cos(\omega t + \varphi).$$

The current amplitude $I_m$ and the phase shift $\varphi$ between current and voltage depend on the parameters of a given circuit.

Let us first consider the simplest electrical circuits, consisting of a source and one element - active resistance, capacitor or coil. When connected to a source of active resistance, an alternating current will appear in the circuit, the amplitude of which is equal to the amplitude of the voltage divided by the active resistance: $I_{RM} = U_m/R$, and the phase coincides with the phase of the voltage. In a circuit with a capacitor, the current in phase determines the voltage at $\pi/2$, and the amplitude of the current $I_{CM} = U_m \omega C$, where $C$ is the capacitance of the capacitor. The current arising in the coil with inductance $L$ lags in phase from the voltage by $\pi/2$, and its amplitude is $I_{LM} = U_m / (\omega L)$.

It is convenient to calculate electrical circuits using vector diagrams of currents and voltages. Let us construct vector diagrams for the distances of the simplest case (Fig. 1). Let's start with the known voltage vector $\vec{U}_m$ and position it horizontally. Since the current through the active resistance is in phase with the voltage, we will direct the current vector $\vec{I}_{RM}$ in the same way as the vector $\vec{U}_m$. The current in the circuit with the capacitor determines the phase voltage for the fourth period; therefore, the current vector $\vec{I}_{CM}$ should be directed vertically upward. Finally, the current in the coil lags behind the voltage by

⟦folio 40⟧

Fig. 2.

π/2, therefore the current vector $I_{LM}$ must be directed vertically downwards.

Note that all relations obtained for the amplitudes of currents and voltages are also valid for their effective values. Vector diagrams can also be constructed using the effective values ​​of currents and voltages.

Now let's look at the following problem:

Task 1. Determine the current strength in the circuit shown in figure 2, a. Consider the parameters of the circuit elements and voltage of the power source as specified.

First, consider a section of the circuit containing a parallel connection of a resistor with resistance $R_1$ and a capacitor em with resistance $C$. Let's construct a vector diagram for it, considering the voltage $U_1$ in this section to be known (Fig. 2, b). We find that the current in the circuit is equal to the sum of the currents through the first resistor and capacitor:

$$\overrightarrow{I} = \overrightarrow{I_{R1}} + \overrightarrow{I_C}.$$

The amplitude of this current is equal to

$$I = \sqrt{I_{R1}^2 + I_C^2} = \sqrt{\left(\frac{U_1}{R_1}\right)^2 + \left(U_1 \omega C\right)^2} = U_1 \sqrt{\frac{1}{R_1^2} + (\omega C)^2}.$$

The same current flows through a resistor with resistance $R_2$, so the voltage across it is equal

$$U_2 = IR_2.$$

It is obvious that the vector sum of $U_1$ and $U_2$ is equal to the voltage $\overrightarrow{U}$ at the source terminals:

$$\overrightarrow{U}_1 + \overrightarrow{U}_2 = \overrightarrow{U}.$$

Let us project the vector $\overrightarrow{U}_2$ on the coordinate axes $X$ and $Y$ and find

$$U_{2x} = U_1 \frac{R_1}{R_2}, \quad U_{2y} = U_1 R_1 \omega C.$$

From the vector diagram it can be seen that

$$U^2 = \left(U_1 + U_{2x}\right)^2 + U_{2y}^2,$$

or

$$U = U_1 \sqrt{\left(1 + \frac{R_1}{R_2}\right)^2 + \left(R_1 \omega C\right)^2}.$$

Finally, from equalities (1) and (2) we obtain

$$I = U \sqrt{\frac{1 + \left(R_2 \omega C\right)^2}{\left(R_1 + R_2\right)^2 + \left(R_1 R_2 \omega C\right)^2}}.$$

The power released in electrical circuits is of great practical importance. In the case of direct current, for any section of the circuit, the power is determined by the product of voltage and current. AC power depends on the effective values ​​of current and voltage, as well as on the phase shift between current and voltage in this section:

$$P = UI \cos \varphi,$$

where cos φ is the power factor.

As you know, in order to get maximum power from a DC source, you need to connect a load whose resistance is equal to the internal resistance of the source. The AC source also has internal resistance, and it is not only active, but also inductive. It is interesting to know what kind of load needs to be connected in order to obtain maximum active power in the AC circuit. The answer to this question is given by the following problem:

Task 2. What should the voltage parameters be in order for the power consumed at the voltage to be maximum? The active resistance of the source is $R$, its inductance is $L$.

Since the power released at voltage depends on the phase shift between current and voltage, it is natural to assume that a capacitor in series with the active resistance of the voltage is turned on more (to compensate

⟦folio 41⟧

This is due to the phase shift created by the source inductance).

Let us denote by $\mathcal{E}$ the electromotive force of the source, by $R_{\mathrm{H}}$ the active voltage resistance and by $C$ the capacitance of the capacitor. Then current will flow in the circuit

$$I = \frac{\mathcal{E}}{\sqrt{(R_{\mathrm{H}}+R)^{2} + (\omega L-1/\omega C)^{2}}},$$

and active power will be released at the load

$$P = U_{\mathrm{H}} I \cos \varphi = I^{2} R_{\mathrm{H}} = \frac{\mathcal{E}^{2} R_{\mathrm{H}}}{(R_{\mathrm{H}}+R)^{2} + (\omega L-1/\omega C)^{2}}.$$

Obviously, for any value of $R_{\mathrm{H}}$ the power will be the most or otherwise the equality

$$\omega L - \frac{1}{\omega C} = 0.$$

This means that the capacitance of the capacitor must be equal to

$$C = \frac{1}{\omega^{2} L}.$$

In this case the power is equal

$$P = \frac{\mathcal{E}^{2} R_{\mathrm{H}}}{(R_{\mathrm{H}}+R)^{2}}.$$

To find the maximum power depending on the resistance $R_{\mathrm{H}}$, we equate the derivative of $P$ to $R_{\mathrm{H}}$ to zero:

$$P'(R_{\mathrm{H}}) = \frac{\mathcal{E}^{2} ((R_{\mathrm{H}}+R)^{2} - 2 R_{\mathrm{H}} (R_{\mathrm{H}}+R))}{(R_{\mathrm{H}}+R)^{4}} = 0.$$

From here

$$R_{\mathrm{H}} = R, \quad P_{\text{max}} = \frac{\mathcal{E}^{2}}{4 R}.$$

Note that we obtained exactly the same relationships as for the built current.

* * *

The transformer occupies a special place in alternating current circuits. This is a device that transfers electrical energy from one circuit to another and at the same time converts currents and voltages. This is where the name “transformer” comes from, that is, “converter”. The operating principle of the transformer is based on the phenomenon of electromagnetic induction, so it can only operate on alternating current.

The transformer consists of a closed ferromagnetic core on which two (sometimes more) coils of copper wire are wound. Coils are often called transformer windings. However, of them, the primary one is connected to the source, the other, the secondary one, is connected to the load. (However, such a separation of the windings is conditional, because depending on the operating mode, the connection may be the opposite.) The coils can be wound on the core in two ways: in one direction or in different directions. Depending on this, the voltage on the windings will change in the same or opposite phases. To determine the operating conditions at the end of the winding and assume that at any time the voltage between the beginning and end of each winding has the same polarity. In pictures and drawings, the beginning of the winding is usually marked with an asterisk.

Calculating an electrical circuit with a real transformer is very difficult. To control the disorder, the so-called ideal transformer. (Note that the results of calculations of ideal and real transformers practically coincide.) First, we will assume that the windings have no active resistance, therefore the front voltage in them is zero, and the equality is satisfied

$$\frac{U_{1}}{U_{2}} = \frac{\mathcal{E}_{1}}{\mathcal{E}_{2}} = \frac{n_{1}}{n_{2}} = K.$$

Here $U_{1}$ and $U_{2}$ are voltages, $\mathcal{E}_{1}$ and $\mathcal{E}_{2}$ are induced emf, $n_{1}$ and $n_{2}$ are the number of turns in the primary and secondary windings of the corresponding; $K = n_{1}/n_{2}$—transformation coefficient. Secondly, we will not take into account the energy loss due to heat generation not only in the windings, but also in the core of the transformer. This means that the power that enters the primary winding is equal to the power that leaves the secondary winding to the load, or, in other words, the sum of the incoming and outgoing power is zero:

$$U_{1} I_{1} + U_{2} I_{2} = 0,$$

where $I_{1}$ and $I_{2}$ are the currents in the primary and secondary windings of the corresponding one.

⟦folio 42⟧

From two equalities we obtain

$$I_1 n_1 + I_2 n_2 = 0.$$
The importance of this simple formula allows the following task:

Problem 3. A transformer having the number of turns in the primary winding $n_1$, and in the secondary winding $n_2$, is connected to an alternating current source with emf $\mathcal{E}$ and internal resistance $R_B$. The wire with resistance $R_H$ is connected as shown in figure 3. Determine the voltage per voltage per voltage.

Let us denote by $U_1$ and $U_2$, $I_1$ and $I_2$ the effective values ​​of voltage and currents in the primary and secondary windings, respectively, and by $I_0$ the effective values ​​of the current in the source. Let at some moment of time the currents be directed as shown in figure 3. Then

$$I_0 R_B = \mathcal{E} - U_1, \quad I_2 R_H = U_1 - U_2,$$
$$I_0 = I_1 + I_2, \quad \frac{U_1}{U_2} = \frac{n_1}{n_2}, \quad I_1 n_1 + I_2 n_2 = 0.$$

The first three equalities are no different from similar equalities for direct current circuits and recording, taking into account the sign rule for EMF, currents and voltage drops. The voltage signs on the windings are selected depending on the position of the beginning and end of the winding. The condition is that the voltage is considered positive if, when going around the corresponding circuit, the end of the winding is encountered first. So, if the contours of the primary and secondary circuits of a given transformer are bypassed, for example, clockwise, then the voltages $U_1$ in the first and $U_2$ in the second equations must be written with a “minus” sign. In the fourth equation, the signs $U_1$ and $U_2$ are always taken to be positive. The signs of the currents in the windings in the fifth equation are chosen as follows: the current is considered positive if it is at

Fig. 3.

straightened from the beginning of the winding to its end, and printed - in the opposite case.

By circling all five equations in the system and solving it, we find the current $I_2$, and therefore the direction on the load:

$$U_H = I_2 R_H = \mathcal{E} \frac{R_H n_1 (n_1 - n_2)}{(n_1 - n_2)^2 R_B + R_H n_1^2}.$$

Exercises

1. Determine the current strength in the circuit shown in figure 4. Consider the location of the power source and the parameters of the circuit elements as given.

Fig. 4.

2. A circuit consisting of two identical resistors with resistance $R$, an inductor $L$ and a capacitor $C$ is connected, as shown in figure 5, to a sinusoidal current generator of variable frequency. Find correspondences between the parameters of the circuit elements at which the target will behave like a resistor having only active resistance at any frequency.

Fig. 5.

3. When transmitting electrical energy over long distances, inductance is primarily responsible for the transmitted power. Assuming that the power plant generator creates an EMF $\mathcal{E}$, the transmission line has an inductance $L$, and the direction of the system should be $U$, determine the maximum active power that can be transmitted in this case.

Fig. 6.

4. A transformer having the number of turns in the primary winding $n_1$, and in the secondary winding $n_2$, and two resistors with resistances $R_1$ and $R_2$ are connected to an alternating current source with voltage $U$ as shown in figure 6. Determine the voltage on the windings of the transformer and the current through resistors.
