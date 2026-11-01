---
id: 1978-8-malov-vsegda-li-ottalkivayutsya-protivopolozhno-napravlennyie-toki-5e8d134c
issue: kvant_1978_8
year: 1978
number: "8"
title: Do oppositely directed currents always repel?
authors:
  - Малов Н. Н.
rubric: osnovnye-stati
page_first: 25
page_last: 27
page_labels: 23-25
tag: TI55
lang: en
source: kvant_digital
extraction: vision
content_sha256: b00ab2c697e2a461968bf2572396a0f0ad012e42bd0ccdb95de8ddad904926a2
prompt_sha256: draft-1
translated_from: content/ru/1978/08/articles/06_malov-vsegda-li-ottalkivayutsya-protivopolozhno-napravlennyie-toki-5e8d134c.md
source_content_sha256: a1e8a0bd814bbee5d58a9f44971ca38cb727271eef052846620be219060bd1ce
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 23⟧

In 1820, the great French physicist Amperator discovered the magnetic interaction of electric currents. In particular, he established that when a current passes through two parallel wires, they attract each other when both currents are directed in the same way, and repel each other if the directions of the currents are mutually attracted.

This can be seen in experience. Thus, in § 114 of the physics textbook for grade 9, the corresponding experiment is described: two vertical parallel wires with their lower ends are connected to a current source (battery), the upper ends are short-circuited, and a noticeable repulsion is observed between the wires (Fig. 1).

It also says that the wires do not interact until their ends are closed (more precisely, no noticeable interaction is detected). However, since the wires are energized, there should be (and indeed are) electric charges on the surface, and of opposite signs. Therefore, between the wires - before their ends are closed - there must be electrical attraction.

What changed after the circuit was closed? The potential difference has changed: slightly if the source has low internal resistance (compared to the resistance of the wires), or strongly if the internal resistance is relatively high, a current has arisen in the circuit. In accordance with the change in the potential difference, the magnitude of the surface charges also changed, but they necessarily remained on the wires. This means that the electrical attraction must remain even after the circuit is closed. Why didn’t it appear in the experiments? Apparently, it was small compared to magnetic repulsion.

The Emperor himself spoke quite decisively on this matter. The source of current in the experiments of Amperas was a voltaic column - a series of galvanic elements connected in series, imperfect scales from a modern point of view. An electric jack was connected to the clamps of Ampere's voltaic pole. With an unloaded pole (with an open circuit), the electric jack gave a noticeable deviation. When the wires under study were connected to the pole, a current arose in the circuit, and the readings of the electric juice sharply decreased (we now understand that this was caused by the high internal resistance of the voltaic column).

Having noted this decrease, and also having discovered the interaction of wires with current even at a great distance from the source, Ampera concluded that the interaction of currents he discovered “has no relation” to electrical interaction. Others

⟦folio 24⟧

In words, he believed that magnetic interaction is inherent in moving, and electrical interaction is inherent in electric at rest.

It should be noted that in 1820 there was no precise instrument for measuring charges, voltages, and currents (by the way, it was Ampere who invented one of the first galvanometers, based on the interaction of a conductor with a current and a magnetic needle).

The units of these quantities had not yet been determined, there was no definite concept of electrical resistance, and Ohm's law was discovered five years later. Therefore, for its time, Ampere’s statement was, of course, meaningful. It correctly reflected the state between magnetic and electric forces under the conditions of Ampere’s experiments: strong magnetic interaction and weak electrical interaction.

But does such a correspondence always exist? Is magnetic interaction always stronger than electrical interaction? To answer these questions, let's do some small calculations.

Consider an electrical target (Fig. 2) of two parallel wires of length $l$, located at a distance $h \ll l$ from each other and having a small resistance $R_\pi$ (line resistance). The left ends of the wires are connected to a source providing voltage $U$, and the right ends are shorted to a load resistance $R_\pi$. When a circuit is closed, currents flow through parallel wires in opposite directions. Let us first find the force $\vec{F}_M$ of their magnetic interaction.

Let one of the currents, for example, the current flowing through the upper wire, create a magnetic field $\vec{B}$, and the other current is in this field.

Firstly, the induction of a magnetic field in a vacuum is always proportional to the field-creating current $I$ in the conductor. Secondly, it decreases with distance from the conductor. A rigorous calculation carried out for a straight conductor with current shows that the magnetic field induction at a point located at a distance $h$ from the conductor passes directly $I$ and inversely proportional to $h$.

According to Ampere’s law, on a small section of a wire of length $\Delta l$, through which current $I$ flows (in other words, on the current element $I \Delta l$), from the side of the magnetic field $\vec{B}$, which makes an angle $\alpha$ with the current element, a magnetic force $\vec{F}_M$ also acts, which

$$\left| \vec{F}_M \right| = \left| \vec{B} \right| \left| I \Delta l \right| \sin \alpha.$$

In our case, $\alpha = 90^\circ$, and the magnetic field is directly proportional to $I$ and inversely proportional to $h$, therefore

$$\left| \vec{F}_M \right| = k_1 \frac{I^2}{h} \Delta l,$$

where $k_1$ is a proportional coefficient, independent of current.

The direction of this force is determined by the right of the left hand. (Check that the wires respond to each other in this case.)

Now about the force $\vec{F}_a$ of electrical attraction. Let us denote by $\lambda$ the electric charge per unit length of each wire. Charges on one wire are a source of an electric field acting on a charge $\lambda \Delta l$ located on an element of length $\Delta l$ of the other wire.

It can be shown that

$$\left| \vec{F}_a \right| = k_2 \frac{\lambda^2}{h} \Delta l,$$

where $k_2$ is a proportional coefficient, independent of current. Indeed, the force acting on a charge in an electric field is proportional to the voltage of the electric field and the magnitude of the charge. It turns out that the field voltage created for a line of loaded wires is proportional to the charge density $\lambda$ and inversely proportional

⟦folio 25⟧

distance from it (distance $h$ in this case). Try to show it yourself.

The surface charge on the wires is, of course, proportional to the voltage $U$, so equality (2) can be rewritten as follows:

$$\left| \vec{F}_3 \right| = k_3 \frac{U^2}{h} \Delta l,$$

(3)

where $k_3$ is the new proportionality coefficient (independent of $U$).

Let us find the ratio of magnetic and electric forces using equalities (1) and (3):

$$\frac{\left| \vec{F}_M \right|}{\left| \vec{F}_3 \right|} = \frac{k_1 I^2 \Delta l/h}{k_3 U^2 \Delta l/h} = k \frac{I^2}{U^2}.$$

Using Ohm's kon, we come to an important conclusion - the force ratio is determined by the square of the circuit resistance $R = R_\pi + R_H$:

$$\frac{\left| \vec{F}_M \right|}{\left| \vec{F}_3 \right|} = k \frac{1}{R^2}.$$

Rigorous calculation gives the following values ​​for the coefficient $k$:

$$k = 10^5 - 5 \cdot 10^5 (\Omega^2).$$

Poznoy appreciates that for small circuit resistances ($R \ll 500 \Omega$), the magnetic forces turn out to be larger than the electric ones. These are the conditions that were present in Ampere’s experiments, and they are also created when demonstrating the interaction of wires with current.

But with sufficiently large resistances ($R \gg 500 \Omega$), electrical forces come to the fore.

This can be confirmed by experience that does not require sophisticated equipment. Two thin copper wires 25-30 cm long and about 0.1 mm in diameter are stretched between two insulating planes (made of dry wood, getinkas, etc.); The distance between the wires is not large: 3-5 mm. All four ends of the wiring are covered with cassettes mounted on the plans. A hole with a diameter of about 1 cm is cut in the middle part of the stand carrying the plans.

The wires are located vertically in the plane of the Earth's magnetic meridin, that is, in the plane where the horizontal magnetic needle is located, freely turning around the vertical axis. In this case, the Earth's magnetic field will have virtually no effect on the magnetic repulsion of the wires.

A screen will be located parallel to the plane of the wiring at a distance of 3-4 m from them. Using a powerful light source and a converging lens, a section of the line opposite the above-mentioned hole is projected onto the screen. On the screen, in those places where an enlarged image of the wiring is obtained, two black (or colored) threads are pulled, disturbing the initial position of the wiring.

Then two observations are made:

1. One end of the line is connected to a small (several ohms) resistance or simply short-circuited. The other end will be connected to the battery (3-6 V) through an ampere and a rheostat (10 Ohm, 1 A). Slowly reducing the resistance of the rheostat, the current is brought to 0.9-1 A. Since in this case the electrical forces are small and the magnetic forces are relatively large, repulsion of the wires is observed on the screen.

2. One end of the line is connected to a high resistance (3 MOhm, 3 W). The other end, being careful, will be connected to a low-power high voltage source (2-3 kV) (for example, to a school voltage converter “Digit 1”). In this case, a current of the order of milliamps is obtained in the line; Magnetic forces, compared to the first experiment, decrease approximately a million times. The electric force increases by the same factor. The repulsion of the line wires will mix in the field without their attraction to each other.

Note that in modern powerful high-fiber lines for transmitting electrical energy, the electrical forces of interaction between the wires are rapidly magnetic. However, both of them are usually small compared to the gravity force coming to the same section of the line $\Delta l$. Therefore, when designing electrical energy transmission lines, electric and magnetic forces are not taken into account externally.
