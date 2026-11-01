---
id: 1982-7-zilberman-istochnik-s-otritsatelnyim-vnutrennim-soprotivleniem-4f65baa0
issue: kvant_1982_7
year: 1982
number: "7"
title: Source with "negative" internal resistance
authors:
  - Зильберман А. Р.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 56
page_last: 57
page_labels: 54-55
tag: Y5N3
lang: en
source: kvant_digital
extraction: vision
content_sha256: f78f79be90146766f1b3df984b835d83fab42799c5531666ff3c310642293363
prompt_sha256: draft-1
translated_from: content/ru/1982/07/articles/12_zilberman-istochnik-s-otritsatelnyim-vnutrennim-soprotivleniem-4f65baa0.md
source_content_sha256: 3950f0e08dc7444ca502e5095adedde8c5685cbb296daf99e2a4aa7b871babe4
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 54⟧

A. Zilberman

Source
with "negative"
internal
sports

Many interesting questions arise in connection with the properties of sources in which the dependence of voltage on current differs from the general dependence $U = \mathcal{E} - rI$ ($\mathcal{E} - \text{ЭДС}, r$ is the internal resistance of the source). We will look at some of these questions using example problem F727.

F727. The dependence of voltage on current for a certain source of electrical energy is shown in figure 1. Plot a graph of the voltage versus the voltage at which the source is closed versus the voltage resistance.

Let's connect a resistor with resistance $R$ to the source. The voltage on it is related to the current by a simple relationship - $U_H = RI$. On the same figure, which shows the dependence $U(I)$ of the source voltage on the current through it, for example, the straight line $U_H = RI$. The intersection point of the graph $U(I)$ and the straight line $U_H = RI$ excludes current and voltage. For a common source, in which the pressure voltage is lower, the higher the current, no more problems arise - there is only one intersection point and the result of the determination is unambiguous.

Fig. 1.

Fig. 2.

Fig. 3.

⟦folio 55⟧

(It is interesting to note that by using such sources, it is possible to obtain an independent amount of chain. Okay, for this you need a second source.

For a conventional source, for example, on which the current consumption decreases as the current consumption increases, it is possible to determine the values ​​of the internal resistance - by the ratio of changes in output voltage to changes in current:

$$r = -\frac{\Delta U}{\Delta I}$$

In our case, in a certain area - in the section $bd$ of dependence $U(I)$ - the internal resistance of the source turns out to be negative. In this case, section $bd$ is so large that even the total resistance of the circuit ($r + R$) turns out to be negative. Hence the instability of the “middle” point and other “oddities” (including the possibility of obtaining independent oscillations: the “negative” resistance can compensate for the loss in the oscillatory system; naturally, all this happens without violating the law of conservation of energy - due to the energy of the source).

How is it possible to obtain the entire curve dependence $U(I)$, if both with a decrease and with an increase in resistance

Dispersal of chips

(For the beginning, see p. 28)

take on the task d). It turns out that these concepts are enough to deal with the Kontsevich problem for any set $G$. Moreover, there is an algorithm (quite suitable for computer programming) that makes it possible to solve Kontsevich’s problem for $G$ in a finite number of steps - either to establish its unsolvability, or to indicate the sequence of normal moves freed by $G$. This algorithm is based on the following messages.

Let us reduce the release problem to the normalization problem with the initial position $A$. Then we draw horizontal and vertical lines limiting the given position $A$ from above and to the right; we obtain a rectangle $m \times n$ containing all the tokens of the position - the so-called rectangle of the problem ($A_{ij} \geq 0$, and $A_{ij} = 0$ for $i > m$ or $j > n$). Moving the straight lines two cells to the right and up, we obtain the located rectangle $P$ of problem $(m + 2) \times (n + 2)$. Our algorithm is as follows.

Having a position, construct an extended rectangle $P$ and perform the necessary moves (in any order - say, horizontally, in the 1st cell, then in the 2nd, etc.).

Fig. 8.

If you need to place a chip beyond $P$, then the problem is unsolvable. Otherwise, by performing all the necessary moves, we will obtain its solution (within the limits of $P$!).

Lack of space does not allow us to provide proof of the stated fact. Perhaps readers will be able to prove it. We recommend that Correspondence School Programming students write a program that solves Kontsevich’s problem in the general case.
