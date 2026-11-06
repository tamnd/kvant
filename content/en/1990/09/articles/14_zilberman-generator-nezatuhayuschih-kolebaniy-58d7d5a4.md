---
id: 1990-9-zilberman-generator-nezatuhayuschih-kolebaniy-58d7d5a4
issue: kvant_1990_9
year: 1990
number: "9"
title: Continuous Oscillation Generator
authors:
  - Зильберман А. Р.
rubric: raznoe
page_first: 46
page_last: 49
page_labels: 44-47
lang: en
source: kvant_digital
extraction: vision
content_sha256: f23e887766cf4508a9e95464fead7635dfebb4c554a92c1871255808d7de7a60
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/14_zilberman-generator-nezatuhayuschih-kolebaniy-58d7d5a4.md
source_content_sha256: 5d6f44f22bffa584d9979ddf99811ab8eb37d2ae95bbb6b492d3a80596d8057c
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 44⟧

Continuous Oscillation Generator

Such generators are used in many devices - radios, televisions, tape recorders, computers, electric organs, etc. - and they come in a wide variety of parts (low frequencies in an electric organ) up to hundreds of meters (television) and even up to several gigahertz (satellite television, radars used by traffic police officers to determine automatic speed). The power that a generator can provide to a consumer ranges from several microwatts (generator in an external clock) to ten watts (television scan generator), and in some special cases the power can be such that there is no point in writing - you still won’t believe it. The form of oscillations can be as simple as sinusidal (radio local oscillator) or rectangular (computer timer), or very complex - “imitating” the sound of musical instruments (musical synthesizers).

Of course, we will not consider all this variety, but will limit ourselves to a simple example - a low-power sinusoidal generator of a moderate part (hundreds of kilohertz).

As is known, in the simplest oscillatory circuit, consisting of an ideal capacitor and an ideal coil, undamped harmonic oscillations can occur. The process equation can be easily obtained by equating (taking into account signs) the directions of the capacitor and the coil - after all, they are connected in parallel (Fig. 1):

$$\frac{q}{C} = -LI'.$$

So, flowing through the coil changes the charge of the capacitor; these quantities are related by the relation

$$I = q'.$$

⟦folio 45⟧

---
running_head:
folio:
---

Now we can write the equation
$$q'' + \frac{q}{LC} = 0.$$

The solution to this equation is well known - it is harmonic vibration. Their frequency is determined by the parameters of the oscillatory circuit: $\omega = 1/\sqrt{LC}$, and the amplitude depends only on the energy that was initially given to the circuit (and which remains constant for an ideal circuit).

What will change if the circuit elements are not ideal, as is actually the case in practice (for many years the author has never seen a single ideal coil, although he was very interested in this issue)? Let, for the sake of definition, the entire imperfection of the circuit is due to the fact that the coil, or more precisely, the wire from which it is wound, has an active (Omish) resistance $r$ (Fig. 2). In fact, of course, the capacitor also loses energy (although at not very high frequencies you can make a very good capacitor without much difficulty). And the consumer will absorb energy from the circuit, which also contributes to the damping of oscillations. However, in a word, we will assume that $r$ is an equivalent quantity responsible for all energy loss in the circuit. Then the process equation takes the form

$$LI' + rI + \frac{q}{C} = 0.$$

It is clear that it is the second term that prevents us from obtaining the desired equation of continuous oscillations. Therefore, our task is to compensate for this term. Physically, this means that additional energy must be pumped into the circuit, i.e., another EMF must be introduced. How can this be done without breaking the chain? The easiest way to use a magnetic field is to create an additional magnetic flux that produces turns in the circuit coil. To do this, not far from this coil, you need to place another coil (Fig. 3) and pass through it a current, the magnitude of which should change according to the desired law, i.e. so that this current creates just such a magnetic field that, by oscillating the coils of the circuit, creates in it such a magnetic flux, which, changing, will induce such an induced emf that exactly compensates for the unwanted term in the process equation. This whole long phrase, reminiscent of “the house that Jack built,” is simply a retelling of the Faraday law you know for the phenomenon of electromagnetic induction.

Now let's look at the current that should flow through the additional coil. It is clear that it requires a source of energy (to replenish the loss of energy in the circuit) and regulation of the device, ensuring the desired law of change in current over time. A common battery can be used as a source, and a vacuum tube or transistor can be used as a control device.

Transistors come in different types - general (they are called bioplair) and field-effect, which are

⟦folio 46⟧

---
running_head:
folio:
---

They are further divided into field-field ones with an insulated gate (they are commonly used in digital devices) and with a control $p - n$-junction. Any field-effect transistor contains a "channel" with two selections - these are imaginatively called source and drain, and its conductance is regulated by applying a control voltage to the third selection - the gate (Fig. 4). In a field-effect transistor with a control $p - n$-junction - and we will talk about it further - the gate is separated from the channel by just such a transition, for which the gate area is made of the opposite type of conductivity in relation to the channel. For example, if the channel has impurity conductivity of type $p$, then the gate has type $n$, and vice versa.

When a blocking voltage $U_3$ (Fig. 5) is applied to the junction, the cross-section of the conducting channel decreases, and when the voltage is determined - it is called the cut-off voltage - the channel is completely blocked and the current stops. The dependence of the channel current $I_к$ on the gate voltage $U_3$ is shown in figure 6. This dependence is almost the same as that of an electron tube (triode). It is important to note that the control voltage is a blocking voltage, which means that the current in the control circuit is extremely small (usually several nanoamps), and the control power is correspondingly low, which is very good. For small values ​​of the control voltage, it depends only on the voltage.

$I_к = I_0 + SU_3$,

where $S$ is a constant. For a generator, deviations from linearity are also significant, but more on that later.

figure 7 shows a schematic diagram of a continuous oscillation generator. Here, the control voltage for the field transducer is the voltage on the capacitor of the oscillatory circuit:

$$U_3 = U_c = \frac{q}{C},$$

and the current through the additional coil is

$$I_к = I_0 + \frac{Sq}{C}.$$

The additional magnetic flux is proportional to this current, and the additional EMF of the circuit is equal to an arbitrary EMF of this flux, taken with the opposite sign:

$$\mathcal{E}_и = -\Phi' = -(MI_к)' = -\frac{MS}{C}q'.$$

The minus sign here is quite conventional - the coil can be connected to a field-effect transistor either at one end or the other, and the sign of the additional EMF will change to the opposite. In a word, the additional EMF must be such as to compensate for the energy losses in the circuit. Let us write the process equation again:

$$LI' + rI + \frac{q}{C} - \frac{MS}{C}q' = 0.$$

⟦folio 47⟧

---
running_head:
folio:
---

If we choose the values ​​$M$ such that the fourth term compensates the second, then we obtain the equation
$$LI' + \frac{q}{C} = 0,$$
which corresponds to harmonic undamped oscillations.

How can you influence the values ​​of $M$? It turns out that she will be notified if large turns are wound in an additional coil or if this coil is placed closer to the circuit coil. It must be said that the coefficient $M$ sufficient for generation is quite easy to obtain in practice. It is better to choose this value with some margin - this will result in a circuit not only without losses, but even with pumping energy from an external source (with “negative” losses). When the generator is turned on, the amplitude of the oscillations will initially increase, but after some time it will settle down - the energy entering the circuit during one period will become equal to the energy lost during the same time. And indeed, with an increase in the amplitude of the direction to the capacitor (the control direction of the field-effect transistor), the transistor begins to perform worse, since with a large negative direction the current in the channel circuit stops, and with positive directions the transition begins to open, which also results in losses in the circuit. The resulting oscillation will not be entirely sinusoidal, but if the losses in the circuit are small, the distortion will be insignificant.

In order to use the resulting oscillations - and this is precisely what the generator is made for - you need to either connect directly to the circuit or wind another coil. But in both cases it is necessary to take into account the “leakage” of energy from the circuit and compensate for it among other losses.

A. Zalberman
