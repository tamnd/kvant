---
id: 1988-11-12-shteynberg-realnyiy-gaz-i-ego-uravnenie-sostoyaniya-4fcce5ae
issue: kvant_1988_11-12
year: 1988
number: 11-12
title: Real gas and its equation of state
authors:
  - Штейнберг А. С.
rubric: shkola-v-kvante
page_first: 54
page_last: 55
page_labels: 52-53
tag: 2INT
lang: en
source: kvant_digital
extraction: vision
content_sha256: a06bae3936cb017cb669ca7dd0f12907c593f313123409a1e2c17570c55efb46
prompt_sha256: draft-1
translated_from: content/ru/1988/11-12/articles/16_shteynberg-realnyiy-gaz-i-ego-uravnenie-sostoyaniya-4fcce5ae.md
source_content_sha256: e23a3ece7f1c4db86039700172f0a3ef7c9a7e69ceda3fe64222b46ba2d51a92
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

passes through the center of gravity of the body, being in balance.

There is one important case of a parallel system of forces, when an equal force cannot be found. This will be the case for two parallel forces that are equal in magnitude and opposite in direction. This system is called *napa forces*. An attempt to find the point of application of a pair of forces leads to division by zero - it was not possible to find this point. A pair of forces has one interesting property: its moment is the same about any axis of rotation (check this). It turns out that any system of forces whose sum is equal to zero has this property (a pair of forces is a special case of such a system).

But it is precisely such systems of forces that we are interested in when we talk about the conditions of equilibrium of a body (statics). However, from the condition - the sum of forces is equal to zero. An important consequence follows from this: the equation of moments, i.e., the second equilibrium condition - the sum of moments is equal to zero, can be written in this case with respect to any point, including those not located inside the body. This point should be selected from the messages about the ease of obtaining the equation (it is convenient to take it, for example, at the intersection of the linear action of several forces, especially those that we do not want to find).

A.R. Zilberman

Real gas and its equation of state

In the famous poem by I. S. Nikitin “Morning” there are such beautiful lines:

...It’s quiet and deserted all around.
The tropics are slightly dewy.
If you touch a bush with your shoulder, it suddenly appears on your face
Silvery dew will sprinkle from the leaves.

The picture of the present is familiar to everyone, which usually does not raise any questions. And they exist.

Where does dew come from in the morning? It's no secret - it is formed during renal cooling from water vapor, which is always in the air. But why then do oxygen and nitrogen - the main gases of the atmosphere - not fall out in the form of dew? And in general, can any gas become a liquid? If yes, under what conditions?

These are the simplest questions, but there are also quite subtle ones. For example, this one. If we consider water vapor to be an ideal gas, then how can we explain its “reincarnation” into a state of the same liquid molecules - water? Indeed, in an ideal gas, molecular interaction is reduced to rather rare collisions of molecules with each other, and in a liquid this interaction manifests itself literally at every step: the practical incompressibility of the liquid, its surface tension, etc. In addition, water vapor, nitrogen, oxygen and other gases in the ideal gas model are completely “the same,” however, only water vapor grows. Why? All these examples show that to explain the transformation of gas into liquid, one must “stock up” with a completely different model of gas.

As you know, the ideal gas model works flawlessly either at high temperatures, when the chaotic thermal motion of the table is intense, so that the molecules move without paying attention to each other, or at low densities, when there is too much distance between the molecules so that they can “feel” each other. As the gas cools or collapses, the influence of molecular interactions becomes more noticeable, and this is when the gas can turn into a liquid. Thus, in order to transfer a place from gas to liquid, it is necessary to take into account the existence of the force of molecular interaction in the gas. The corresponding model is called real gas. The equation of state of a real gas can most easily be obtained by introducing the correction

⟦folio 53⟧

ki on the interaction of molecules in the Mendleyev-Clapeyron equation.

If the distance between the molecules is small, they repel each other sharply. (This is why, for example, it is difficult to liquid.) This is easy to understand by imagining molecules in the form of billiard balls, which have their own volume. So, the first correction is for the size of the molecules.

According to the ideal gas equation, volume $V$ depends on pressure $p$ according to the law

$$V = \frac{vRT}{p},$$

where $T$ is the absolute temperature, $R$ is the universal gas constant, and $v$ is the number of moles of gas. This means that at very high pressure the volume decreases to almost zero. And billiard balls can only be compressed to a certain minimum volume, which is proportional to their number. Therefore we can write

$$V = \frac{vRT}{p} + vb.$$

Here $b$ is a constant that determines the total volume of all “hard” molecules that make up one moldan gas (as more accurate calculations show, the constant $b$ is equal to quadruple the volume of molecules). Now, no matter how much pressure increases, the volume of a mole of gas never becomes $b$.

We have not yet learned all the manifestations of molecular interaction. Just as billiard balls by themselves do not coalesce into large groups, so gas molecules would never come together to “organize” a dense liquid if they were not hiding from each other (at distances greater than the diameter of the liquid ball). Tensile forces prevent molecules from flying apart and lead to a decrease in pressure compared to that with which the gas would act on the walls of the vessel in their absence. Let us denote this reduced pressure by $\Delta p$. Then we get

$$p = \frac{vRT}{V-vb} - \Delta p.$$

Let's try to estimate $\Delta p$, assuming that it is associated with a change in the impulse

(compared to the case of no interaction) transmitted to the walls when gas molecules are removed from them. The molecules adjacent to the walls are subject to tension forces towards the remaining gas molecules, directed into the depths of the vessel and therefore reducing their speed. These forces, to a first approximation, are proportional to the density of the gas (at very high rarefaction they disappear altogether). Roughly, we can assume that the change in momentum transmitted to the wall when one molecule is removed is also proportional to the density. But the average number of impacts on the walls per unit time also increases in proportion to the density. Therefore, the decrease in pressure $\Delta p$ turns out to be proportional to the volume of the vessel:

$$\Delta p = \frac{a v^2}{V^2},$$

where $a$ is a constant coefficient for a given gas.

The final equation of state of a real gas takes the form:

$$p = \frac{vRT}{V-vb} - \frac{a v^2}{V^2},$$

or, as it is explained,

$$\left( p + a \frac{v^2}{V^2} \right) (V-vb) = vRT.$$

This is the famous van der Waals equation, which first saw the light in 1873 in the scientist’s work “On the continuity of the gaseous and liquid states” (Nobel Prize 1910).*)

In van der Waals theory, each gas is characterized by its own parameters $a$ and $b$, which can be determined from experiment. Here are their values ​​for some gases:

| Substance | $a$, $H \cdot m^4 \cdot mol^{-2}$ | $b$, $m^3 \cdot mol^{-1}$ |
| :--- | :--- | :--- |
| water $H_2O$ | 0,5464 | 0,305 $\cdot 10^{-4}$ |
| nitrogen $N_2$ | 0,1390 | 0,391 $\cdot 10^{-4}$ |
| oxygen $O_2$ | 0,1370 | 0,318 $\cdot 10^{-4}$ |
| hydrogen $H_2$ | 0,0244 | 0,266 $\cdot 10^{-4}$ |

*) You can read in detail about the famous Dutch scientist and the equation that bears his name in the note by V. E. Yavelov “Van der Waals and his equation” («Kvant», 1987, No. 7).
