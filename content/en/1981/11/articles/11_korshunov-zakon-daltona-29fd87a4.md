---
id: 1981-11-korshunov-zakon-daltona-29fd87a4
issue: kvant_1981_11
year: 1981
number: "11"
title: Dalton's law
authors:
  - Коршунов С. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 38
page_last: 40
page_labels: 36-38
tag: P4VE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 97cb0c397107747ba07eb6e511c780e2931d498d1cd31c34286d565a7794c973
prompt_sha256: draft-1
translated_from: content/ru/1981/11/articles/11_korshunov-zakon-daltona-29fd87a4.md
source_content_sha256: 80d0cbaaca06ac9471c4aaf92fca6e3fefef392d7ff8d2e9cc94b86f26ad6d17
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

Dalton's law

Among the problems on the laws of ideal gases, there are often problems in which we are talking about a mixture of several gases. The equation of gas state $pV = \frac{m}{\mu} RT$ is not applicable in such cases, since it is not known what the molar mass of the mixture $\mu$ is. How can this be?

Obviously, each of the gases in the mixture contributes to the total pressure. Moreover, each gas behaves independently of the others and obeys the Mendeleev-Clapeyron equation

$$p_i V = \frac{m_i}{\mu_i} RT.$$

The pressure $p_i$ created by any component when the other components are removed from the vessel is called partial pressure. The English scientist Dalton experimentally established that for sufficiently rarefied gases the pressure of the gas mixture is equal to the sum of the partial pressures of the components of the mixture:

$$p = p_1 + p_2 + \dots + p_n.$$

This law is henceforth called Dalton's law.

It is now easy to find an equation that describes the state of the gas mixture. To do this, you need to put into the equality expressing Dalton’s law the values ​​of partial pressures obtained from the Mendeleev-Clapeyron equation:

$$pV = \left( \frac{m_a}{\mu_a} + \frac{m_b}{\mu_b} \right) RT,$$

or

$$pV = \left( v_1 + v_2 + \dots + v_n \right) RT,$$

where $v_i$ is the number of moles of the corresponding component.

Let's consider several specific tasks. All of them were offered at one time during the entrance exams to the Moscow Physical Institute.

Problem 1. A closed vessel is divided into two equal parts by a solid, motionless, semi-permeable partition. A mixture of argon and hydrogen is introduced into the first half of the vessel at a pressure of $p = 1,5 \cdot 10^5$ Pa, and a vacuum is introduced into the second half. Only hydrogen can diffuse through the partition. After the end of the diffusion process, the pressure in the first half turns out to be locally equal to $p' = 10^5$ Pa. Determine the ratio of the masses of argon and hydrogen in the vessel. The molar mass of argon is $\mu_a = 40$ $\epsilon$/mol, hydrogen is $\mu_b = 2$ $\epsilon$/mol. Assume that the temperature is kept constant during the process.

The diffusion process proceeds rather quickly, therefore, immediately after introducing the mixture into the first half of the vessel, pressure $p$ is created by the mixture of gases:

$$p = p_a + p_b.$$

Here $p_a$ is the partial pressure of argon and $p_b$ is the partial pressure of hydrogen. They can be found from the equation of state:

$$p_a V = \frac{m_a}{\mu_a} RT \text{ и } p_b V = \frac{m_b}{\mu_b} RT,$$

where $V$ is the volume of half the vessel, $m_a$ and $m_b$ are the masses of argon and hydrogen, respectively, and $T$ is the temperature of the vessel. Substituting the pressures $p_a$ and $p_b$ into the expression for the pressure of the mixture $p$, we obtain

$$pV = \left( \frac{m_a}{\mu_a} + \frac{m_b}{\mu_b} \right) RT =$$

$$= \left( \frac{m_a}{m_b} + \frac{\mu_a}{\mu_b} \right) \frac{m_b}{\mu_a} RT.$$

Since we skip the partition for hydrogen, after the end of the diffusion process hydrogen will enter the weight

⟦folio 37⟧

volume of the vessel, and the density of hydrogen throughout will be the same. Consequently, exactly half of all hydrogen will remain in the first half, and its partial pressure $p'_B$ will decrease by 2 times: $p'_B = p_B/2$. The argon pressure $p_a$ will not change. Then

$$p' = p_a + p'_B,$$

or

$$p'V = \left( \frac{m_a}{\mu_a} + \frac{1}{2} \frac{m_b}{\mu_b} \right) RT = \left( \frac{m_a}{m_b} + \frac{1}{2} \frac{\mu_a}{\mu_b} \right) \frac{m_b}{\mu_a} RT. \tag{2}$$

Dividing equation (2) by equation (1), after several transformations we find the required relation:

$$\frac{m_a}{m_B} = \frac{\mu_a}{\mu_B} \frac{2p'-p}{2(p-p')} = 10.$$

Problem 2. A cylindrical vessel is divided into two parts by a movable, well-conducting body piston. At the initial moment, there is oxygen to the right of the piston, and a mixture of helium and hydrogen to the left; mass of oxygen $m_K = 32$ g. The piston is located in the middle of the vessel. The piston material, impermeable to hydrogen and oxygen, turns out to be permeable to helium, as a result of which the piston began to move and was finally located at a distance of four cylinders from the left wall. Determine the masses of helium and hydrogen in the mixture.

At the first moment, oxygen and a mixture of hydrogen and helium occupy equal volumes; the temperatures in both parts of the vessel are the same (since the piston conducts the body well); the pressures to the left and right of the piston are also the same (because the piston is in equilibrium, and the diffusion process occurs much more slowly than the pressure equalization process). This allows us to conclude that at the initial moment the number of moles of gas in both parts of the vessel is the same, that is, to the left of the piston there is 1 mole of a mixture of helium and hydrogen.

In the final state of pressure, oxygen $p_K$ and hydrogen $p_B$ turn out to be the same (since the pressure in both parts of the vessel is the same, and the piston is in equilibrium):

$$p_K = p_B.$$

From the Mendeleev-Clapeyron equation for oxygen and hydrogen we have

$$\frac{3}{4} p_K V = \frac{m_K}{\mu_K} RT \text{ и } \frac{1}{4} p_B V = \frac{m_B}{\mu_B} RT,$$

where $m_K$ and $m_B$ are the masses of oxygen and hydrogen, and $\mu_K$ and $\mu_B$ are their molar masses. From here we find the mass of hydrogen:

$$m_B = m_K \frac{\mu_B}{3\mu_K} = \frac{2}{3} \Gamma,$$

which corresponds to the number of moles $v_B = 1/3$. Therefore, the number of moles of helium is $v_r = 2/3$, and the mass of helium in the mixture is $m_r = \mu_r v_r = 8/3 \Gamma.$

Problem 3. The vessel contains a mixture of nitrogen and hydrogen. At a temperature of $T$, when nitrogen has completely disintegrated into atoms, and hydrogen is still in a molecular state, the pressure of the mixture is $p$. At a temperature of 2T, when both gases were completely dissociated, the pressure in the vessel became 3p. What is the ratio of the number of moles of nitrogen and hydrogen?

Let us denote by $v_a$ the number of moles of nitrogen in the mixture, and by $v_B$ the number of moles of hydrogen. At temperature $T$, when hydrogen is still in the molecular state, the equation takes the form

$$pV = (2v_a + v_B)RT$$

(here it is taken into account that nitrogen completely decomposed, and its number of moles doubled), and at a temperature of 2T, when both gases were completely dissociated, -

$$3pV = 2(2v_a + 2v_B)RT.$$

Dividing one equation by another, we get

$$\frac{v_a}{v_B} = \frac{1}{2}.$$

Equation of state of gas mixtures

$$pV = (v_1 + v_2 + \dots + v_n)RT$$

can be presented in another form. Indeed, the number of moles $v_i$ of each gas is equal to the ratio

⟦folio 38⟧

number of molecules $N_i$ of this gas to Avogadro's number $N_A$, therefore

$$pV = \left( N_1 + N_2 + \dots + N_n \right) \frac{R}{N_A} T.$$

If we denote the total number of molecules in the mixture by $N$ and take into account that the ratio $R/N_A$ is Boltzmann’s constant $k$, then the equation of state can be written as follows:

$$pV = NkT.$$

Note that the Mendeleev-Clapeyron equation for a one-component gas looks exactly the same. This means that this form of equation of state can be used both for one gas and for a gas mixture.

Problem 4. Tritium (an isotope of hydrogen with atomic mass $A=3$) is stored in a vessel with a volume of $V=1$ l. Tritium mass $m=1$ l. After 12 years of use, the tritium alder turns into green kernels. Find the pressure in the vessel at the end of this storage period. The gas temperature is maintained at $t=27^\circ C$. The resulting whole has an atomic mass of $A=3$.

The tritium pressure at the beginning of the storage period is

$$p_1 = \frac{N}{V} kT = \frac{m}{\mu} R \frac{T}{V}$$

(here $N$ is the number of tritium molecules, $\mu=6$ g/mol is the molar mass of tritium).

After 12 years, $N/2$ tritium molecules turn into $N$ gel molecules (each tritium molecule, like oblique hydrogen, contains 2 atoms). The pressure $p_2$ in the vessel is created by a mixture of tritium and gel, the total number of molecules of which is $N/2+N=3/2N$:

$$p_2 = \frac{3}{2} NkT = \frac{3}{2} p_1 = \frac{3}{2} \frac{m}{\mu} R \frac{T}{V} \approx 6,3 \cdot 10^5 \Pi.$$

Problem 5. There are $1 \text{ m}^3$ dry air and $1 \text{ m}^3$ moist air at the same pressure and temperature. Which air has more mass: dry or humid?

From the equation of state of the gas mixture $pV=NkT$ it follows that the number of molecules $N$ of moist and dry air is the same, since in general mixtures have the same volumes, pressures and temperatures. Dry air consists
