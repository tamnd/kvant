---
id: 1991-11-rafailov-kak-izluchat-radiovolnyi-d4c1ec0e
issue: kvant_1991_11
year: 1991
number: "11"
title: How to emit radio waves?
authors:
  - Рафаилов А.
rubric: shkola-v-kvante
page_first: 35
page_last: 37
page_labels: 33-35
lang: en
source: kvant_digital
extraction: vision
content_sha256: be9fd24e49dd76f07bf6b8e16fb0d753d6d72657cfce38b157bd7dcb0e4fe246
prompt_sha256: draft-1
translated_from: content/ru/1991/11/articles/12_rafailov-kak-izluchat-radiovolnyi-d4c1ec0e.md
source_content_sha256: 8f6cc0d405a24c7f7c5e3a375adaac3cb7eff80452a73dc11d2a79e5679ef4e0
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 33⟧

How to emit radiovolts?

Before emitting radiovolts - electromagnetic oscillations determine frequencies, you need to obtain these oscillations. This can be done using a continuous oscillation generator. But how to ensure that the presence of oscillations can be recognized far from the generator is the topic of this note.

Let's formulate the problem more specifically: what needs to be connected to the output of the continuous oscillation generator for an electromagnetic wave to run from it? This question is not simple, it can be easily guessed that the elements for the role of a radiating antenna are not suitable. Here, for example, is a resistor. If we connect it to the output of the generator, then all the energy that it receives from the generator will be completely converted into heat. A capacitor is also not suitable for the role of an antenna - the average power it receives from the generator is exactly zero (the phase shift between voltage and current is equal to four periods). This means that he simply has nothing to emit - after all, when emitting electromagnetic waves, energy must be transmitted from the source in all directions. The same is true for the inductor.

Thus, in order for the power to be optimized from the generator, the phase shift between current and voltage must be changed - it should not be the fourth period. This can be achieved, for example, by connecting a capacitor and resistor in series. However, nothing useful will happen for us: now the loads (capacitor and resistor) are optimized by the energy generator, but all this energy is completely converted into heat. Try to see this for yourself - for such a simple circuit it will not cause difficulties. It turns out that for arbitrary LCR circuits (for example, like on figure 1) this rule holds: all the power that the circuit receives from the source goes into

⟦folio 34⟧

---
running_head:
folio:
---

tello. In this case, the dependence of instantaneous power on time has the form
$p = u(t)i(t) = U_0 \cos \omega t \cdot I_0 \cos (\omega t + \varphi)$,
where $\varphi$ is the phase shift between current and voltage. After simple trionometric transformations, it is easy to find the average power consumed from the source over a period (and therefore over a long period of time):

$$P_{cp} = \frac{1}{2} U_0 I_0 \cos \varphi = UI \cos \varphi.$$

This is exactly the power that turns into heat.

Note, by the way, that the maximum value of instantaneous power is greater than the value $P_{cp}$, and at phase shifts close to $90^\circ$ - many times. This means that the source must be able to develop an instantaneous power significantly higher than that which is taken from it on average. This situation sometimes arises in practical electrical engineering - when connecting fluorescent lamps, electric motors, etc. With fluorescent lamps this happens because the current through the lamp is set by the serial connection of the inductor and the phase shift is close to $90^\circ$ (Fig. 2). Excessive load on the electrical network is extremely undesirable, as it leads to additional losses in the form of heat and forces the use of expensive wires. The position can be corrected by connecting a capacitor of a suitable capacitance in parallel (this requires tuning for resonance!). In this case, the coil and the capacitor will exchange energy with each other during the entire period - “extra” energy is pumped between them, and the network - the source of energy entering the load - releases only the amount of energy that turns into heat.

So, circuits of this kind (LCR circuits) are not suitable for the role of an antenna. The problem is to make the phase shift between current and voltage in the circuit different from $90^\circ$, but not at the expense of heat generation, i.e. without resistors. It turns out that if the dimensions of the load circuit components are small compared to the wavelength, nothing can be done. But with large load elements, an additional phase shift can be obtained due to the delay in wave propagation.

Let a capacitor be used as a load, the resistance of which (for alternating current of a given frequency) is optimal for a given generator. Now let's start increasing the delay by changing the capacitor gases. But you cannot simply increase the size of the capacitor plates - its capacity becomes larger. To maintain capacity, you will have to increase the distance between the plates. Strictly speaking, a large capacitor is no longer a capacitor. The phase shift now corresponds to a different circuit, and power will be required from the generator, although there are no resistors and no heat is generated. Consequently, the energy from the generator must go somewhere, namely, be radiated into space.

⟦folio 35⟧

---
running_head:
folio:
---

To obtain the most radiated power, you need to optimize the size and configuration of the antenna. If such an antenna consists, for example, of two rods - long and thin, then the optimal length of each of them should be equal to four wavelengths, the rod should be directed along one straight line, and the terminals of the non-damped oscillation generator should be connected as shown in figure 3. Such antennas are often used for televisions. In essence, the applied and transmitting antennas do not differ from each other (only for very powerful transmitters it is necessary to make special transmitting antennas, taking into account high directions and high currents supplied to the antenna for transmission).

If the dimensions of the antenna are chosen correctly, then no “extra” load is created for the radio transmitter generator and the energy coming from it is radiated into space. However, these wishes are easy to satisfy only for stationary radio transmitters and not very low transmission frequencies (for which the wavelength is not too long). For portable radio stations this is not always possible - the antenna turns out to be much shorter than necessary for optimal coordination with the generator.

In this case, you can “lighten the fate” of the generator by connecting in series with the antenna an inductor coil (that’s what they call an extension coil) - a resistance capacitance
The resistance of a short antenna wire will be counteracted by the inductive reactance of the coil.

The antenna can also consist of several conductors - by choosing the length and position of these conductors and supplying them with currents from the generator in the required phases, it is possible to ensure that the radiation occurs primarily in a given direction (“directional” antenna). This is an example of the use of integration for technical purposes. By the way, it is not at all necessary to connect all the conductors to the generator - the current that arises in the conductor due to the fact that it is in the electromagnetic field of the main antenna may be quite sufficient for our purposes. All this applies to the applied antenna, which most often includes a main conductor - a “vibrator” (the origin of this term should be clear) and several additional, unconnected conductors of strictly defined sizes and locations (they are called “director” and “reflector”, their number and the accuracy of selection depends on the direction of the antenna).

It turns out that it is possible to select the configuration of a complex antenna so that it operates satisfactorily not only at a strictly defined frequency, but also over the entire frequency range. This is absolutely necessary, for example, for receiving television - after all, it is not very convenient to have its own antenna for each channel. However, if the channel frequencies are widely separated or the antenna is very far from the telecentre, you have to use several separate, well-tuned antennas.

A. Rafailov
