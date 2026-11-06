---
id: 1990-7-miheev-vraschayuschayasya-zhidkost-21e70558
issue: kvant_1990_7
year: 1990
number: "7"
title: Rotating fluid
authors:
  - Михеев П. М.
rubric: laboratoriya-kvanta
rubric_sub: Лаборатория «Кванта»
page_first: 53
page_last: 54
page_labels: 51-52
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0b4809a2939f89ce392e11f5c45a15053af1fc72bd775ec3db4acd935e6adc06
prompt_sha256: draft-1
translated_from: content/ru/1990/07/articles/17_miheev-vraschayuschayasya-zhidkost-21e70558.md
source_content_sha256: b323e154474ab72bf24b8bb821be79b74f41acfa440bb17fa886394b9c504c37
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 51⟧

---
running_head:
folio:
---

Rotating fluid

P. MIKHEEV

The University of Maryland, located near the US capital, has an amazing museum that displays a large collection of physical specimens. You can spend hours looking at experiments, studying various mechanisms, pressing buttons that activate them, just watching and being amazed. Here's one example.

The author of this article, Pavel Mikheev, is one of fifteen Soviet schoolchildren taking part in the first Soviet-American summer physics and mathematics school (July 1989, USA).

In front of you is a flat plate with a metal rim. The plate is filled with blue liquid. There are wires in the center of the vessel. It would seem that there is nothing special, except that the liquid in the plate... is swirling. maybe it's some kind of special liquid?

Having become interested in the vision, we looked for a promotion to the “installation”, and returned home and made it in the school physics room.

Look at the photo shown here. The glass walls of the vessel are lined with a metal strip (foil) from the inside, and a metal rod is placed in the center of the vessel. The wires connected to the rod and foil go to a current source, for which we used a rectifier, which gives an output voltage of about 9 V at a current of 0.3 A. The blue liquid filling the vessel is a 5-10% solution of copper sulfate in water. (You can also use other electrolytes, for example, also an aqueous solution, but sodium flakes.) The vessel is placed on a permanent magnet, which creates a magnetic field with an induction of about $10^{-3}$ T in the immediate vicinity of its surface. That's all the equipment.

By connecting the electrodes (rod and foil) to an electric current source, we actually observed the vessel. The rotation was not very fast, but completely noticeable to the eye. Let's try to oblige the surprised.

Molecules $\text{CuSO}_4$ in water dissociate naons $\text{Cu}^{2+}$ and $\text{SO}_4^{2-}$. When electrodes are connected to a source in a vessel, an electric field arises, directed radially from the center of the vessel to its periphery (if the rod serves as an anomer and the foil as a cathode). Copper ions and acid residue begin to mix towards the corresponding electrodes, and the magnetic field, directed vertically (and practically uniform near the surface of the magnet), causes them to bend their trajectories, which

⟦folio 52⟧

---
running_head:
folio:
---

and leads to rotation of the entire liquid. That's the whole quality side.
Now let's make some quantitative estimates.
First, let's talk about the radial component of the speed of inov $v_R$. As is known, the current density in an electrolyte is the sum of the densities created by ions of both signs:
$$j = n_+ q v_+ + n_- q v_-$$
where $n_+$ and $n_-$ are the concentrations of positive and negative ions, respectively (it is clear that in our case they are equal, i.e. $n_+ = n_- = n$), $q$ is the absolute value of the charge of each ion, $v_+$ and $v_-$ are the speed of their ordered movement. For the sake of estimation, we will assume that these speeds are the same for common engines: $v_+ = v_- = v_R$. Since the current strength $I$ is related to the density $j$ by correspondence $I = jS$, where $S = 2\pi Rh$ (R is the cross-sectional radius of the vessel, $h$ is the height of the liquid in the vessel) is the area of ​​the cathode, we obtain
$$I = (2nqv_R)(2\pi Rh) = 4\pi nqRhv_R.$$
In concentration
$$n = \frac{N}{V} = \frac{m}{M} N_A \frac{1}{\pi R^2 h},$$
where $m$ is the mass of copper sulfate, $M$ is its molar mass, $N_A$ is Avogadro’s constant. The charge of inov is $q = 2e$ (e is the charge of the electron). Then we get
$$I = 4\pi \frac{mN_A}{M\pi R^2 h} 2eRhv_R,$$ and $v_R = \frac{MIR}{8emN_A}$.

Taking $M = 0,064$ kg/mol, $q = 3,2 \times 10^{-19}$ Kl, $m \sim 0,01$ kg, $R \sim 0,1$ m and $I = 0,3$ A, we find the values ​​of the radial component of the speed of movement of the vehicles:
$$v_R \approx 3 \cdot 10^{-7} \text{ м/c}.$$
A moving particle in a magnetic field is acted upon by the Lorentz force, whose role is to bend the trajectory of the ins, which causes rotation of the entire fluid. But between layers of moving fluid there are always resistance forces, called viscous friction forces. They tend to slow down the layer that moves faster and accelerate the layer that moves slower. The action of these two forces - the Lorentz force and the viscous friction force - will lead to the fact that very soon after the start of rotation, the tangential component $v_R$ of the speed at a distance $r$ from the center of practical stops changing over time. What will it be equal to? Let's make an assessment.
Consider a limited volume of liquid $V_i$ (Fig. 1). The charge located in this region is acted upon by the Lorentz force
$$F_{Ji} = q_i Bv_R,$$
Where
$$q_i = 2qnV_i = 2qn\pi r^2 h.$$
What can be said about the force of viscous friction? From the most general reports, as well as from our experience, it is obvious that the maximum tangential velocity of particles is achieved at the axis of rotation, and as the distance $r$ increases, the speed of the floating decreases. Since the force of viscous friction is determined by the difference in the speed of movement of neighboring layers, it is clear that it should depend on how quickly the speed changes when moving from layer to layer, in our case - as the distance from the center of the vessel increases, and on the contact area. Thus:
$$F_{tp} = -\eta \frac{dv_r}{dr} S_i,$$
where $\eta$ is the so-called coefficient
