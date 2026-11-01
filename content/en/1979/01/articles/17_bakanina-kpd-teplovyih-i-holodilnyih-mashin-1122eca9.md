---
id: 1979-1-bakanina-kpd-teplovyih-i-holodilnyih-mashin-1122eca9
issue: kvant_1979_1
year: 1979
number: "1"
title: Efficiency of heat and refrigeration machines
authors:
  - Баканина Л. П.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 52
page_last: 54
page_labels: 50-52
tag: QEB7
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7df95c3ad7faaefdd50c3bfb142f3c225aa6856f317c9206e3c83d4e8dcedb6d
prompt_sha256: draft-1
translated_from: content/ru/1979/01/articles/17_bakanina-kpd-teplovyih-i-holodilnyih-mashin-1122eca9.md
source_content_sha256: 5b7b193f1712fc018a02f627921af9dd2875ff46c3f0c691090517002bf044aa
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

Efficiency of heat and refrigeration machines

What is the efficiency of heating and refrigeration machines? Can it be more than 100%? Let's try to answer these questions.

To operate any heat engine, you need at least two heat reservoirs with different temperatures. Receiving the heat flow of a hotter reservoir (heater), the machine performs work with working heat, but at the same time part of the heat is separated to a colder reservoir (refrigerator).

The efficiency η of a heat engine is equal to the ratio of the work A performed by the machine to the amount of heat Qₙ received by its heater:

$$\eta = \frac{A}{Q_н}.$$

According to the first law of thermodynamics,

$$A = Q - \Delta U = (Q_н - Q_x) - \Delta U.$$

Here Qₓ is the amount of heat separated by the refrigerator; for heat engines the environment serves), and ΔU is the change in the internal energy of the working fluid. Since all heat engines operate in a closed cycle - the reverse Carnot cycle (the cycle runs counterclockwise; see Fig. 1), then

$$\varepsilon = \frac{T_x}{T_н - T_x}.$$

From this formula it is clear that ε can be less than, greater than or equal to 100%. Indeed, the ability to build a refrigeration machine whose heating temperature difference

*) You can read more about this, for example, in the article by S. Shamsha and E. Evenchik “The Carnot Cycle” («Kvant», 1977, No. 1).

⟦folio 51⟧

temperature between the body and the refrigerator will be greater than, less than, or equal to the temperature of the refrigerator.

The fact that e can be more than 100% sometimes raises the question: is this not violating the law of conservation of energy? In fact, there is no contradiction with the law of conservation of energy. The heat taken from the cooled body and the energy spent on doing work from the outside do not transform into each other at all, but are given to heating (usually in refrigeration machines this is the environment).

Let's look at a few specific tasks.

Problem 1. Heat engine, the working fluid of the komorosh is 1 mole of an ideal monatomic gas, we complete the cycle shown in figure 2. The efficiency of this machine is named.

The efficiency of a heat engine is equal to

$$\eta = \frac{A}{Q_H}.$$

The work $A$ per numerical cycle is equal to the area of ​​the cycle depicted in coordinates $p$, $V$ (see Fig. 2):

$$A = \frac{1}{2} p_0 V_0^2.$$

Let's find out at which parts of the cycle the gas receives heat and at which parts it releases it. Let's write down the first law of thermodynamics for any section:

$$Q_i = \Delta U_i + A_i.$$

One mole of an ideal monatomic gas has internal energy

$$U = \frac{3}{2} RT,$$

where

$$\Delta U_i = \frac{3}{2} R \Delta T_i$$

the change in internal energy in each section is determined by the change in temperature. The work $A_i$ is numerically equal to the area under the corresponding section of the cycle.

Using the ideal gas equation of state $pV = RT$ we find the gas temperatures at points 1, 2, 3:

$$T_1 = \frac{p_0 V_0}{R}, \quad T_2 = \frac{2 p_0 \cdot 2 V_0}{R} = 4 T_1,$$

$$T_3 = \frac{p_0 \cdot 2 V_0}{R} = 2 T_1.$$

In section 1–2, the gas temperature increases ($\Delta T_{12} > 0$), and the gas does positive work (the gas expands); therefore, in this area the gas receives heat. In sections 2-3 and 3-1, the gas temperature is killing, in section 2-3 no work is done at all, and in section 3-1 it is negative (the gas is skimmed off, doing work from the outside) - which means that in these sections the gas does not receive heat.

So, the gas receives heat only in section 1-2:

$$Q_H = Q_{12} = \Delta U_{12} + A_{12} = \frac{9}{2} p_0 V_0 + \frac{3}{2} p_0 V_0 = 6 p_0 V_0.$$

Then finally

$$\eta = \frac{A}{Q_H} = \frac{1/2 p_0 V_0}{6 p_0 V_0} = \frac{1}{12} \approx 8^{0.0}.$$

Problem 2. An ideal refrigeration machine has a reservoir of water at $0^\circ C$ as a refrigerator, and a reservoir of boiling water as a cutter. What work must be done to turn the cutter into steam? Specific heat of LVDA $\lambda = 340$ kJ/kg,

⟦folio 52⟧

Fig. 3.

specific heat of water vaporization $L = 2260$ kJ/kg.

An ideal refrigeration machine operates on a reverse Carnot cycle, its coefficient of performance is

$$\varepsilon = \frac{T_X}{T_H - T_X} = \frac{273 \text{ K}}{100 \text{ K}} = 2,73.$$

When 1 kg of water freezes, heat is released

$$Q_X = \lambda m = 340 \text{ кДж}.$$

The work done

$$A = \frac{Q_X}{\varepsilon} \approx 125 \text{ кДж}.$$

The heater will receive the amount of heat

$$Q_H = Q_X + A \approx 465 \text{ кДж},$$

therefore, the oil will turn into steam.

$$m_1 = \frac{Q_H}{L} \approx 0,2 \text{ кг}.$$

Problem 3. In the middle of the last century, the Angelic physicist Thomson proposed the idea of ​​so-called dynamic heating. The firebox in which the molivo is burned serves as a cutter for the heat engine; the refrigerator for this machine burns water in the heating system. By obtaining work, we will operate the refrigeration machine. For the refrigeration machine, the water in the heating system is burned with a cutter, and with a cold reserve, the mello is taken from the chamber, and the erunto water is burned. Assuming that both machines operate in ideal cycles and neglecting measurements, determine how many moles the water in the heating system will receive when 1 kg of moles is compressed. Specific heat of combustion of moliv $q$, temperature in the heat engine monk $t_1 = 200^\circ\text{C}$, water temperature in the heating system $t_2 = 60^\circ\text{C}$, temperature of erunto water $t_3 = 10^\circ\text{C}$.

In order to more clearly imagine Thomson's idea, let's draw a diagram of dynamic heating (Fig. 3).

Now we carry out the necessary calculations.

The machines are ideal, that is, they work according to the Carnot cycle. Therefore, the efficiency of a heat engine is

$$\eta = \frac{T_1 - T_2}{T_1} = \frac{140 \text{ K}}{473 \text{ K}} \approx 0,3,$$

coefficient of performance

$$\varepsilon = \frac{T_3}{T_2 - T_3} = \frac{283 \text{ K}}{50 \text{ K}} \approx 5,7.$$

When 1 kg of fuel is discarded in the firebox, energy $Q_H = q$ is released. The work performed by the heat engine is equal to

$$A = \eta Q_H = \eta q,$$

and the heat coefficient transferred in the heating system is equal to

$$Q_1 = q - A = (1 - \eta) q.$$

The refrigeration machine takes the heat coefficient from groundwater

$$Q_X = \varepsilon A = \varepsilon \eta q.$$

The water in the heating system receives a heat coefficient

$$Q_2 = Q_X + A = \eta (1 + \varepsilon) q.$$

In total, the water in the heating system receives a heat coefficient

$$Q = Q_1 + Q_2 = (1 + \varepsilon \eta) q \approx 2,7q.$$

Thus, the dynamic heating system allows, in principle (if it neglects losses), to transfer water in the heating system with a heat coefficient greater than that released in the firebox during fuel combustion! Isn't the first law of thermodynamics violated here? In no way: “excess” heat is taken from groundwater. Indeed, heat is removed from groundwater

$$Q_X = \varepsilon A = \varepsilon \eta q,$$

- as differentiated between $Q$ and $q$.

(For the ending, see p. 54)
