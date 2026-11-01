---
id: 1987-6-kozel-zadachi-na-gazovyie-smesi-21cc5676
issue: kvant_1987_6
year: 1987
number: "6"
title: Problems on gas mixtures
authors:
  - Козел С. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 50
page_labels: 47-48
tag: MTNR
lang: en
source: kvant_digital
extraction: vision
content_sha256: c275d08dd11d643dffa225b082974eeddfbfea6d8a83cab555da0cd4b52ae9b0
prompt_sha256: draft-1
translated_from: content/ru/1987/06/articles/14_kozel-zadachi-na-gazovyie-smesi-21cc5676.md
source_content_sha256: befd055dcbe8bdc68c7aa21bc6f8f30000ac09acb30602b99b0eb1e55d80ba38
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

Tasks
for gas mixtures

Doctor of Physical and Mathematical Sciences
S. M. KOZEL

At the university entrance exams, applicants are first presented with problems that consider not pure gases (hydrogen, oxygen, etc.), but mixtures of several gases. These tasks are important because in practice we often have to deal with gas mixtures. For example, air consists of a mixture of nitrogen, oxygen, carbon dioxide with an admixture of other gases. Humid air also contains water vapor.

Problems on gas mixtures essentially differ little from problems on the laws of ideal gases. If, according to the conditions of the problem, the composition of the gas mixture does not change, we can consider the mixture as one ideal gas with a certain average value of the molar mass. Thus, dry air is often assigned a molar mass of $M_B=29$ g/mol, averaged over its main components. However, if the composition of the mixture changes, the concept of average molar mass loses its meaning, and there are some difficulties with using the equation of gas state of air. In this case, it is useful to introduce the concept of partial pressure - this is what is commonly called the pressure exerted by any pure gas from the mixture when all other gases are removed from the vessel.

If gases are rarefied enough (so that they can be considered ideal) and do not chemically interact with each other, the molecules of different gases have no effect on each other, and each gas in the mixture behaves as if there were no other gases at all. It follows that the total pressure of the mixture is equal to the sum of the partial pressures:

$$p=p_1+p_2+\dots+p_n.$$

This law was experimentally established by the English physicist Dalton and was named after him. Let us explain Dalton's law and the concept of partial pressure with an example.

Two different gases $A$ and $B$ are placed in two chambers of the same volume and create pressures $p_1$ and $p_2$ (see p. 48). Using a piston, gas from one chamber is pushed through a valve into another chamber. The temperature is maintained constant and the same throughout the entire system. As a result, in the second chamber it is installed

⟦folio 48⟧

Pressure $p = p_1 + p_2$. Pressures $p_1$ and $p_2$ in this case are the partial pressures of different gases, and in accordance with Dalton’s law they add up to the total pressure $p$.

Let us note again that Dalton's law is valid only for ideal gases with insignificant molecular structure. Experience shows that at extremely high pressures (on the order of tens of atmospheres) deviations from this law are observed.

If we write the Mendeleev-Clapeyron equation for each gas, then from Dalton’s law for a mixture of gases we obtain

$$pV = \left( \frac{m_1}{M_1} + \frac{m_2}{M_2} + \dots + \frac{m_n}{M_n} \right) RT,$$

or

$$pV = (v_1 + v_2 + \dots + v_n)RT,$$

where $v_i = m_i/M_i$ is the number of moles of a given gas in the mixture. This correspondence is called the equation of state of the gas mixture. Considering Avogadro's law, according to which a mole of any substance contains $N_A = 6,02 \cdot 10^{23}$ molecules ($N_A$ is Avogadro's number), the last equality can be rewritten as

$$pV = \left( v_1 N_A + v_2 N_A + \dots + v_n N_A \right) \frac{R}{N_A} T = (N_1 + N_2 + \dots + N_n) kT = NkT.$$

Here $N_i = v_i N_A$ is the number of molecules of the existing gas, $k = R/N_A = 1,38 \cdot 10^{-23}$ J/K is Boltzmann’s constant. Thus, it turns out that the pressure of a mixture of gases at a given temperature depends only on the total number of molecules and does not depend on their type. This is one of the main consequences of the molecular theory of ideal gases.

Let's consider a number of problems using Dalton's law and the equation of state of gas mixtures. All these tasks in different years were offered to applicants for the written entrance exam at the Moscow Institute of Physics and Technology.

Problem 1. $m = 3$ g of water is introduced into a vessel with a volume of $V = 10$ l, filled with dry air at a pressure of $p_1 = 10^5$ Pa and a temperature of $T_1 = 273$ K. The vessel is heated to a temperature of $T_2 = 373$ K. What is the pressure of moist air at this temperature?

The pressure of moist air in a vessel is the sum of the partial pressures of dry air and water vapor:

$$p = p_B + p_\pi.$$

At the same time

$$p_B = p_1 \frac{T_2}{T_1} = 1,37 \cdot 10^5 \text{ Pa}.$$

Considering steam to be an ideal gas with molar mass $M = 18$ g/mol and assuming that all the water will evaporate, we find

$$p_\pi = \frac{m}{M} \frac{RT_2}{V} = 0,52 \cdot 10^5 \text{ Pa}.$$

This pressure is less than the saturated vapor pressure at 373 K, which is equal to $p_\pi = 10^5$ Pa. Therefore, the steam is unsaturated, and our assumption was correct.

Thus,

$$p = p_B + p_\pi = 1,89 \cdot 10^5 \text{ Pa}.$$

Problem 2. A vessel of constant volume at a temperature of $T_1 = 300$ K contains $v_1 = 1$ molle of neon and $v_2 = 2$ molle of hydrogen. Pressure in the vessel $p_1 = 10^5$ Pa. When the temperature increased to $T_2 = 2400$ K, the pressure increased to $p_2 = 8,8 \cdot 10^5$ Pa. What part of the hydrogen molecules dissociated into atoms?

At temperature $T_1$ for a mixture of neon and molecular hydrogen we can write the equation

$$p_1 V = (v_1 + v_2) RT_1,$$

where $V$ is the volume of the vessel.

If we denote the degree of hydrogen dissociation, i.e., the ratio of the number of decayed molecules to the total number of molecules before dissociation, by $\alpha$, then at a temperature of $T_2$ there are $v_1$ moles of neon, $(1 - \alpha) v_2$ moles of molecular hydrogen and $2\alpha v_2$ moles of atomic hydrogen in the vessel. The equation of state of the gas mixture is used in the form

$$p_2 V = (v_1 + v_2)(1 + \alpha) RT_2.$$
