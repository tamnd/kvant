---
id: 1988-3-varlamov-kak-v-metalle-protekaet-elektricheskiy-tok-8d34615f
issue: kvant_1988_3
year: 1988
number: "3"
title: How does electric current flow in metal?
authors:
  - Варламов А. А.
rubric: shkola-v-kvante
page_first: 43
page_last: 45
page_labels: 41-43
tag: OV61
lang: en
source: kvant_digital
extraction: vision
content_sha256: 39d2a2bae9c7066ab0c80277ccbb8d4f634b3304055adf12427e702f5de4f899
prompt_sha256: draft-1
translated_from: content/ru/1988/03/articles/17_varlamov-kak-v-metalle-protekaet-elektricheskiy-tok-8d34615f.md
source_content_sha256: 3f19475f09c405ef5cf8b80eec2c3096b2d967ee902307f5cf4fdcc7dcbf840c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 41⟧

from the second side, $\vec{F}_{21}$ - accordingly, vice versa. According to Newton's third law $\vec{F}_{12} = -\vec{F}_{21}$, therefore the change in momentum of the entire system is equal to

$$\Delta \vec{P} = m_1 \Delta \vec{v}_1 + m_2 \Delta \vec{v}_2 = (\vec{F}_1 + \vec{F}_2) \Delta t$$

— the momentum of the system changes only under the influence of external forces. On the other hand, from expression (3) it follows that

$$\Delta \vec{P} = (m_1 + m_2) \Delta \vec{v}_{\mu M}$$.

Hence, for the center of mass we obtain a correspondence similar to Newton’s second law:

$$(m_1 + m_2) \Delta \vec{v}_{\mu M} = (\vec{F}_1 + \vec{F}_2) \Delta t,$$

which can be rewritten in a more personal form:

$$\vec{F}_1 + \vec{F}_2 = (m_1 + m_2) \vec{a}_{\mu M}.$$

(4)

This is the most important thing: the center of mass moves as if it contains the entire mass of the system and all external forces are applied to it. Please note - these are external forces. The internal forces of the system do not affect the movement of its center of mass at all. That is why the movement of this point in many cases turns out to be quite simple.

This property of the center of mass has numerous applications. For example, now it is probably clear to you why the middle of a stick thrown at an angle to the horizon (which was discussed at the very beginning of the note) moves, like a stone, in a parabola. In the absence of impact friction, the external force is equal to $m\vec{g}$, and therefore the acceleration of the center of mass, like the acceleration of the stone, is equal to $\vec{g}$, regardless of whether the stick rotates.

Let's look at this example. A lifting crane delivers a heavy slab to the truss platform. To unfold this plate, two workers push it at points $A$ and $B$ with equal force (Fig. 3). Relative to what point does the plate begin to rotate? We guarantee that many of you will immediately answer this way: of course, regarding the point $C$, which lies halfway between the points $A$ and $B$.

Take your time! Correct answer: relative to point $O$—the center of mass of the plate. Look at equation (4). Since the sum of external forces is equal to

Fig. 3.

zero, which means the acceleration of the center of mass is equal to zero - it will remain at rest.

In conclusion, let’s talk about one more “convenience” of the center of mass. As follows from equation (3), in the reference system associated with the center of mass, the total momentum of the system of bodies is zero. It is clear that in such a system the movement should look simpler - after all, the system as a whole will accumulate. It is especially convenient to use this example if the system is closed. After all, then the acceleration of the center of mass is zero (see equation (4)), and the reference system associated with it is inertial. For example, the central impact of two elastic balls in such a system looks so simple that you can immediately guess the answer: after the impact, the balls disperse at the same speed with which they initially converged. Think for yourself why this is so.

A. I. Chernochan

How does electric current flow in metal?

This question usually does not cause difficulties for schoolchildren. How is it going? Yes, very simple. If a potential difference is maintained between the ends of a wire, for example a metal wire, then an electric field will arise in it. Actions on the free electrins present in the metal, this field gives them acceleration in the direction of the end of the wire whose potential is higher (the charge of the electrins is negative). The direction of movement of charges appears, which is the electric current.

⟦folio 42⟧

This is not to say that this answer is wrong. All the words in it are true. However, this seemingly exhaustive answer immediately raises a whole series of other questions and returns. Let's try to figure them out.

How do electrons move when a potential difference is created between the ends of a conductor? It would seem accelerated, because the force $\vec{F}=e\vec{E}$ ($\vec{E}$ is the direction of the electric field in the conductor) acts on them all the time. But, on the other hand, if this were really the case, then the current strength in any section of the conductor would increase over time, which contradicts Ohm’s law - with a constant direction, the current strength flowing through the conductor is constant: $I=U/R$. How is life? Let's remember the internal structure of metal.

The valence electrons of metal atoms are very weakly bound to atoms. Therefore, when the crystal lattice rotates, they easily tear off from the atoms and form a fairly dense electron gas (then only one electron comes off from each atom, then their concentration in such a gas turns out to be of the order of $n \sim 10^{29}$ $1/\text{m}^3$, which we can verify for ourselves). Reasoning above about the flow of current through a metal, we considered these electrons to be free. In a certain sense, this is true, but we should not forget about their environment - the ionic crystal lattice.

Created at the end of the 19th and beginning of the 20th centuries, the classical electronic theory of metal resistance assumed that in the process of moving under the influence of an electric field, electrons collide with ions of the crystal lattice. The averages of these collisions are also those in which the electrons transfer all the energy acquired during acceleration in the electric field to the lattice. It is also the reactions, they are called effective, and are responsible for the resistance of the metal. The remaining collisions can be ignored to understand the mechanism of current flow (after them, only the direction of the electron velocity changes, but not its magnitude).

Let the average time between collisions be $\tau$. Then we can imagine the following model of the movement of an electron in a metal in which an electric field is created. In the time interval from 0 to $\tau$, the electron moves with acceleration $a=e\vec{E}/m$, and, therefore, the projection of the speed of its directed countermovement. Then it is accelerated again by the electric field, and the process repeats. The graph of the projection of the speed of ordered movement versus time is shown in figure.

Such piecewise uniformly accelerated motion can be imagined as a uniform drift of an electron in the direction opposite to the field, with a speed of $v_{\text{cp}}=eE\tau/(2m)$. Let us calculate the current strength associated with this movement.

The number of electrons passing through the cross section $S$ of the conductor in time $\Delta t$ is $\Delta N=nSv_{\text{cp}}\Delta t$. In this case, the charge $\Delta q=e\Delta N=neSv_{\text{cp}}\Delta t$ is transferred. Therefore, current flows in the conductor

$$I=\frac{\Delta q}{\Delta t}=nev_{\text{cp}}S=\frac{ne^2\tau}{2m}SE.$$

Magnitude

$$j=\frac{I}{S}=\frac{ne^2\tau}{2m}E$$

called current density.

It turns out that the coefficient we obtained for the field direction $E$, which is composed only of the microsoptic characteristics of the metal, is nothing more than the inverse values

⟦folio 43⟧

given the resistivity of the metal $\rho$.

Well, something began to ask. However, questions still remain. Let's, for example, estimate the average speed of directional motion of electrons. Let a copper conductor with a cross section of, say, $10\text{ mm}^2$ and an electron concentration $n=1,67 \cdot 10^{29} \text{ 1/m}^3$ carry a current $I=10$ A. Then the average speed

$$v_{\text{cp}} = \frac{I}{neS} \approx 0,04 \text{ mm/c}.$$

If we determine the time between effective collisions using the experimentally known value $\rho$, it turns out that $\tau \sim 10^{-14}$ s. Therefore, if it is assumed that the path between effective collisions occurs with an average speed of $v_{\text{cp}} \sim 0,1 \text{ mm/c}$, then we come to an absurd statement: the distance between two electron collisions is $l = v_{\text{cp}} \tau \sim 10^{-18}$ m, which is many orders of magnitude less than the distance between the nearest ions in the lattice. Therefore, we again did not teach something. But we did not teach that particles of electron gas in a metal, like molecules of an ideal gas in a vessel, are in constant chaotic motion. However, if we use this analogy and substitute $v_{\text{cp}}$ into the expression for $l$ for thermal speed $v_{\tau} = \sqrt{3kT/m}$ (see § 11 of Physics 9), then all this turns out to be insufficient to agree with the experimental data (see this for yourself).

We have exhausted the possibilities of classical physics. In fact, a coherent theory of metal resistance was only constructed in the mid-twentieth century using the concepts of quantum physics. It turned out that electrons in the metal move at a gigastimmic speed $v_e \sim 0,01c$ (c is the speed of light in vacuum). This chaotic movement of part of the electron gas has a purely quantum, not thermal origin - it does not stop even at absolute zero temperature. But even at column speed of chaotic electron motion in the absence of an electric field, the average charge transfer through the extended cross section of the conductor is zero. When the electric field is turned on, this chaotic movement is superimposed by an ordered drift of electrons against the field - as already described above. The distance between two successive collisions is determined precisely by the high speed of chaotic motion and for the specific copper conductor we took is several tens (and maybe even hundreds) of international distances, which is already quite plausible.

And finally, the last necessity. According to the laws of quanta, an electron in an ideal periodic crystal lattice moves in such a way that it... never collides with the pons that form it. What then would happen to all our previous speculative constructions? How then do electrons, when moving in a crystal, transfer their energy to the lattice?

It turns out that at low temperatures electrons collide with impurity atoms and other defects that are always present in the lattice of a real crystal. By eliminating them, the resistance of the crystalline metal can be made less and less. At room temperature, electrons are mainly scattered on... lattice flasks. If in a non-moving lattice they can still “construct” their behavior in such a way as to “bypass” all periodic repeating nones, then when the latter is performed by thermal fluctuations, the electrons can no longer “follow” their chaotic movement and inevitably collide with one or the other.

Here, include what “pitfalls” we encountered when carefully considering what seemed to be such a clear question.

A. A. Varlamov
