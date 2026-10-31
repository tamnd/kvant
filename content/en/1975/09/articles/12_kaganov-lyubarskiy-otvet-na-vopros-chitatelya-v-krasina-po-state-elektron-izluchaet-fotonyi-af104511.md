---
id: 1975-9-kaganov-lyubarskiy-otvet-na-vopros-chitatelya-v-krasina-po-state-elektron-izluchaet-fotonyi-af104511
issue: kvant_1975_9
year: 1975
number: "9"
title: '[Answer to a question from reader V. Krasin regarding the article “Electron emits photons”]'
authors:
  - Каганов М. И.
  - Любарский Г. Я.
rubric: raznoe
page_first: 47
page_last: 48
page_labels: 45-46
tag: 0DKA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3bb26a481055cd837f3178e50773854e6f87e5729013937889fbfbc3d167febf
prompt_sha256: draft-1
translated_from: content/ru/1975/09/articles/12_kaganov-lyubarskiy-otvet-na-vopros-chitatelya-v-krasina-po-state-elektron-izluchaet-fotonyi-af104511.md
source_content_sha256: 485768a8b7b065d64f8ce2a1d58d0d3d6cc1c0a42127406b5e2c8df4a39735ec
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

## Ask - we answer

In this issue of the magazine we publish an answer to a question from our reader V. Krasin, a 10th grade student at a Moscow school.

Dear editors!

The article “Electron Emits Photons” («Kvant», 1974, No. 12) talks about how an accelerated charged particle emits electromagnetic energy, and provides a formula for calculating the intensity of this radiation:

$$I = 2e^2a^2/3c^3 \quad (*)$$

(e is the charge, and is the acceleration of the particle).

On the other hand, an example is given of a direct current flowing along a curved circuit, and it is said that “such a current creates a constant magnetic field, but does not radiate.”

What I read raised two questions in my mind:

1) Why, when moving along a curved conductor, and therefore with acceleration, do electrons not emit?

2) Doesn't the absence of radiation, even in the case of current flowing through a straight conductor, contradict the classical electronic theory of metals? According to this theory, current carriers in metals are free electrons, which move chaotically in the absence of an electric field. Under the influence of the electric field, ordered motion is superimposed on the chaotic motion, such that the average speed of the electrons is different from zero. An electron moving along a conductor experiences collisions with ions of the crystal lattice, giving them all the energy accumulated during movement between collisions (this energy is released in the form of heat). The average speed of electrons does not change with time if a constant current flows through a conductor. But in the intervals between collisions the electron moves at an accelerated rate, and therefore it must radiate.

⟦column⟧

Below we publish the answer from the authors of the article “An electron emits photons.”

These questions arose due to inaccurate wording in the article.

Let's start with the second question. V. Krasin briefly and correctly described the process of current passing through metal. We, using exactly the ideas that he outlined, will carry out a small calculation.

Consider a straight conductor carrying a direct current. Let's select 1 $см^3$ of this conductor, calculate the energy emitted in 1 second $N$ by electrons moving in this section of the conductor, and compare it with the amount of heat released every second in this volume. Since between collisions each electron moves with acceleration $a = eE/m$ (e is the charge of the electron, m is its mass, E is the electric field strength), it emits energy. According to formula (1) of the cited article, the intensity of this radiation is equal to

$$I = \frac{2e^2a^2}{3c^3} = \frac{2e^4E^2}{3c^3m^2},$$

and the radiation intensity of N electrons is respectively

$$NI = \frac{2Ne^4E^2}{3c^3m^2}.$$

According to the Joule-Lenz law, the amount of heat released in a conductor with resistance R in 1 s is equal to $i^2R$. Current value i

45

⟦folio 46⟧

can be expressed through the current density $j$: $i=jS$ ($S$ is the cross-sectional area of ​​the conductor). The current density is related to the electric field strength: $j = \lambda E$, where $\lambda$ is the electrical conductivity. (Recall that $\lambda = \dfrac{1}{\rho}$, where $\rho = \dfrac{RS}{L}$ is the resistivity of a conductor of length $L$ and cross section $S$.) Then the amount of heat released every second in 1 $см^3$ of a conductor, the volume of which is $V$, is equal

$$Q = \frac{i^2 R}{V} = \lambda E^2 .$$

Let us express $\lambda$ through the parameters of electrons, based on the classical theory of conductivity. If the average speed of directional motion of electrons is $\bar v$, then the current density is $j = eN\bar v$. On the other hand, $j = \lambda E$, so $\lambda = \dfrac{eN\bar v}{E}$.

Let's find what the speed $\bar v$ is equal to.

Moving with acceleration $eE/m$, by the end of the free path the electron acquires speed $v_{max} = a\tau = \dfrac{eE}{m}\tau$ ($\tau$ is the free path time). The average speed of directional movement is $\bar v = \dfrac{1}{2} v_{max} = \dfrac{1}{2}\dfrac{eE}{m}\tau$.

Time $\tau$ can be found as the ratio of the electron free path $l$ to the speed $v_{\text{т}}$ of its thermal motion (the speed of directed motion $\bar v$ is many times less than the speed of chaotic motion $v_{\text{т}}$), that is

$$\tau = \frac{l}{v_{\text{т}}} . \qquad \text{Поэтому} \qquad \bar v = \frac{1}{2}\frac{eE}{m}\frac{l}{v_{\text{т}}} .$$

Therefore, $\lambda = \dfrac{1}{2}\dfrac{e^2 Nl}{mv_{\text{т}}}$. 1 $см^3$ conductor generates heat every second

$$Q = \frac{1}{2}\frac{e^2 Nl}{mv_{\text{т}}} E^2 .$$

Let us now find the ratio of the energy emitted by electrons to the heat released: $\dfrac{NI}{Q} = \dfrac{4}{3}\dfrac{e^2 v_{\text{т}}}{mc^3 l}.$

Let's give this expression more

⟦column⟧

visual representation by introducing the classical electron radius $r_e = e^2/mc^2$:

$$\frac{NI}{Q} = \frac{4}{3}\frac{r_e}{l}\cdot\frac{v_{\text{т}}}{c} .$$

Let us estimate the magnitude of this relationship. Since $r_e = 2,5\cdot 10^{-13}$ cm, the mean free path $l$ is not less than $10^{-6}см$, and the average speed of thermal motion of the electron is $v_{\text{т}} \approx 10^8$ $см/с$, then

$$\frac{NI}{Q} \approx 10^{-9} (!)$$

It can be seen how little radiation is caused by the accelerated movement of electrons between collisions. In principle it can be detected, but in most practical matters this radiation does not play any role.

Now let's turn to the first question of V. Krasin's letter. Let us consider a curved conductor, for example, a conductive circuit shaped like a circle of radius $r$. For the chaotic motion of electrons, the shape of the conductor is, naturally, not significant, since the mean free path, as a rule, is significantly less than its smallest size, especially the radius of the circle $r$ (the electron “does not know” between collisions whether the conductor is curved or not). But on average, the electron, of course, moves in a circle, and therefore with an acceleration of $\bar v^2/r$. However, this acceleration is very small, less even than the acceleration $a = eE/m$ between collisions. Let's check this statement. From inequality $\dfrac{eE}{m} \gg \dfrac{\bar v^2}{r}$ we can go to inequality $\bar v \ll v_{\text{т}}\dfrac{r}{l},$

which is obviously satisfied, since $r \gg l$, and $v_{\text{т}} \gg \bar v$ (the value of $\bar v$ can be easily estimated using the expression for the current density and the fact that $N \approx 10^{22} \div 10^{23}$ $см^{-3}$).

It is clear that radiation associated with accelerated motion in curved areas can, of course, be ignored.

M. Ts. Kaganov, G. Ya. Lyubarsky
