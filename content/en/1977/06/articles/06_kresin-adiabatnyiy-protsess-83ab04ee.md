---
id: 1977-6-kresin-adiabatnyiy-protsess-83ab04ee
issue: kvant_1977_6
year: 1977
number: "6"
title: Adiabatic process
authors:
  - Кресин В. З.
rubric: osnovnye-stati
page_first: 27
page_last: 31
page_labels: 25, 27, 28, 29
tag: 1AB0
lang: en
source: kvant_digital
extraction: vision
content_sha256: 31cb2a784ee0dd3aad55e5ede1e02361dfd79fa584d5a0827b53b740e1817629
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/06_kresin-adiabatnyiy-protsess-83ab04ee.md
source_content_sha256: 03a880eeb5239225809eb7a75ca66a9e5baa8b8f156849b1b577aa9793b80ba5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 25⟧

V. Kresin

Adiabatic process

Various branches of physics are closely related to each other. Many illustrative examples can be given. Thus, this article talks about one of the most important processes studied in molecular physics - the adiabatic process. During this process, the temperature of the gas changes. We are no longer interested in the mechanism of temperature change; This will require some knowledge of mechanics. That's why we'll start with one mechanical problem.

Reflection from a moving wall

Let us consider the following mechanical phenomenon: the ball approaches the wall with a speed $v$ and after an absolutely elastic impact changes the direction of its movement. For simplicity, we limit the case of a normal ball falling onto a wall.

If the wall is motionless, then it is clear that after the impact the direction of the speed of the ball will change to the opposite, and its absolute value $|v|$ remains unchanged.

Let us now complicate our task: the ball is adjacent to a moving wall. Let us assume that the wall is moving towards the ball with a speed of $u$ (Fig. 1). In this case, at what speed will the ball move after the collision? In order to answer this question, we reduce the problem to a well-known one - the collision of a ball with a stationary wall. In other words, we will consider the phenomenon in the reporting system associated with the wall. From the point of view of the observer in this reporting system, the speed of the ball approaching the wall will be different, namely $|v'| = |v| + |u|$. After reflection (recall that in the considered reporting system the wall will end), the velocity will change direction, but in absolute value it remains the same. To finally solve the problem, let us again switch to a stationary reporting system, connected to a ball approaching the wall relative to the wall, and the wall itself moves relative to the ground with a speed of $|u|$. Therefore, the speed of the ball relative to the ground is $|v| + 2|u|$.

Thus, as a result of elastic reflection from the moving wall, the speed of the ball returns to twice the speed of the wall.

This concludes our consideration of the auxiliary mechanical problem and moves on to the main issue - the description of the adiabatic process.

Mechanism of temperature change during an adiabatic process

Let there be an ideal gas in the cylinder under the piston (Fig. 2). The movement of the piston $AB$ allows you to arbitrarily roll down and expand

Fig. 1.

⟦folio 27⟧

This is due to the decrease in the speed of molecules when they are reflected from the receding piston.

Basic law of the adnabate process
In the adnabate process, a change in the volume of an ideal gas is accompanied by a change in its temperature. The main objective of this section of the article is to obtain a formula connecting temperature and volume during the adnabate process. To do this, we will use the molecular-kinetic picture of this process.

Let us consider the movement of some molecule of a monatomic ideal gas. Let its speed be $v$ and kinetic energy

$$\varepsilon = \frac{m |\vec{v}|^2}{2}.$$

The movement of a molecule in space can be represented as three independent movements along the $X$, $Y$ and $Z$ axes. (In this sense, they speak of three degrees of freedom of molecules.) Associated with each of these independent movements are the corresponding processes $v_x$, $v_y$ and $v_z$ of the molecular speed. Then the expression for kinetic energy can be written as follows:

$$\varepsilon = \varepsilon_x + \varepsilon_y + \varepsilon_z$$

$$= \frac{m v_x^2}{2} + \frac{m v_y^2}{2} + \frac{m v_z^2}{2}.$$ (1)

We will be interested in stacks of molecules with a descending piston (to determine the distance, the case of adnabate scatium). Therefore, we will only talk about motion along the $X$ axis (see Fig. 2). Let the piston descend at speed $\vec{u}$. The amount of energy $\varepsilon_x$ after collision with the piston becomes equal to

$$\varepsilon' = \frac{n (|v_x| + 2 |\vec{u}|)^2}{2},$$

and the change in energy

$$\Delta \varepsilon_x = \varepsilon' - \varepsilon_x = 2m |v_x| |\vec{u}| + 2m |\vec{u}|^2.$$

Usually $|\vec{u}| \ll |v_x|$. Then in the expression for $\Delta \varepsilon_x$ we can use the second term compared to the first and consider

$$\Delta \varepsilon_x = 2m |v_x| |\vec{u}|.$$ (2)

Formula (2) describes the change in the energy of one molecule as a result of one collision with the piston. Is every change per unit time of internal energy considered ideal for a gas? To answer this question, we must sum up the energy changes of all the molecules that collided within seconds with the descending piston. Let us denote by $N$ the number of gas molecules in the vessel, by $V$ the volume of the vessel and by $S$ the area of ​​the piston. For simplicity, we will assume that all gas molecules are characterized by the same numerical value of the process speed $v_x$ (in the future we will make the necessary adjustments). Moreover, at any moment of time, half of the molecules move towards the piston, and the second half - away from it (otherwise there would be a mixing of the entire gas as a whole). Within 1 second, collisions will only be experienced by those molecules that, firstly, move towards the piston and, secondly, are at a distance from it not exceeding $|v_x|^*$), that is, the number of molecules experiencing collisions is equal to

$$N' = \frac{1}{2} \frac{N}{V} |v_x| S.$$ (3)

For all $N'$ molecules, the energy after collision with the piston changes by the amount $\Delta \varepsilon_x = 2m |v_x| |\vec{u}|$ (see formula (2)). Thus, the total change in gas energy per unit time

$$\Delta E = N' \Delta \varepsilon_x$$

$$= \frac{1}{2} \frac{N}{V} |v_x| S \cdot 2m |v_x| |\vec{u}|$$

$$= 2 \frac{N}{V} \frac{m |v_x|^2}{2} |\vec{u}| S.$$ (4)

*) More strictly, this distance is equal to $|v_x| + |\vec{u}|$, but we will use the fact that $|\vec{u}| \ll |v_x|$.

⟦folio 28⟧

It is clear that the values ​​$|\vec{u}| S$ are numerically equal, but opposite in value to the volume of the vessel: $|\vec{u}| S = -\Delta V$. Then

$$\Delta E = -2 \frac{N}{V} \frac{m |v_x|^2}{2} \Delta V = -2 N \varepsilon_x \frac{\Delta V}{V}.$$

(5)

We assumed that all molecules are characterized by the same velocity projection value $v_x$. Of course, this assumption is not true. In fact, all molecules move at different speeds, and in reality there is a significant variation in the values ​​of $\varepsilon_x$. Therefore, in expression (5), instead of the energy $\varepsilon_x$, we must take the average energy value $\varepsilon_x$ over all molecules:

$$\Delta E = -2 N \varepsilon_x \frac{\Delta V}{V}.$$

(6)

The internal energy of a monatomic ideal gas containing $N$ molecules is equal to

$$E = \frac{3}{2} N k T,$$

(7)

where $k$ is Boltzmann’s constant, and $T$ is the absolute temperature of the gas. The value $\frac{3}{2} k T$ and represent the average energy value of the molecules of a monatomic ideal gas. Since molecules are composed of three independent equal movements (along those coordinate axes), it is clear that $\varepsilon_x = \frac{k T}{2}$. Let's substitute this value into expression (6):

$$\Delta E = -N k T \frac{\Delta V}{V}.$$

(8)

Let us now write another expression for $\Delta E$. Let us use formula (7) for the internal energy of an ideal gas. With adnabate scatine, the gas temperature changes. Let the gas temperature change by $\Delta T$ when the volume changes by $\Delta V$. Then the internal energy of a gas containing $N$ molecules is equal to $E' = \frac{3}{2} N k (T + \Delta T)$, and the change in internal

$$\Delta E = \frac{3}{2} N k \Delta T.$$

(9)

Equating the rules of parts of expressions (8) and (9), we arrive at the following equality:

$$-N k T \frac{\Delta V}{V} = \frac{3}{2} N k \Delta T,$$

(10)

or

$$\frac{\Delta T}{T} = -\frac{2}{3} \frac{\Delta V}{V}.$$

(11)

Formula (11) establishes connections between temperature, volume and their changes during the adnabate process.

The question arises: how should the temperature $T$ and volume $V$ of the gas be related to each other so that when they change the corresponding ones to $\Delta T$ and $\Delta V$, equality (11) is satisfied? It turns out that this connection for any $T$ and $V$ must have the form *)

$$\ln T = -\frac{2}{3} \ln V + \text{const},$$

(12)

where $\ln$ is the natural logarithm, that is, the logarithm to the base $e \approx 2,72$.

*) Tenth classicists can verify this for themselves (see, for example, “Algebra and beginning analysis 10,” paragraph 114). For other readers, we will provide a check that expression (12) actually yields expression (11).

In fact, let the temperature and volume change by small values ​​$\Delta T$ and $\Delta V$, respectively. Then from expression (12) it follows:

$$\ln (T + \Delta T) = -\frac{2}{3} \ln (V + \Delta V) + \text{const},$$

or

$$\ln T + \ln \left(1 + \frac{\Delta T}{T}\right) =$$

$$= -\frac{2}{3} \ln V - \frac{2}{3} \ln \left(1 + \frac{\Delta V}{V}\right) + \text{const}.$$

Taking equality (12) into account, we obtain

$$\ln \left(1 + \frac{\Delta T}{T}\right) = -\frac{2}{3} \ln \left(1 + \frac{\Delta V}{V}\right).$$

Now let’s use the approximate formula: for small $\alpha$ ln $(1 + \alpha) \approx \alpha$, then

$$\frac{\Delta T}{T} = -\frac{2}{3} \frac{\Delta V}{V}.$$

⟦folio 29⟧

Thus, temperature and volume during the adnabate process are related by formula (12), which is easily reduced to the form

$$\ln (TV^{2/3}) = \text{const},$$

or

$$TV^{2/3} = \text{const.}$$

(13)

This is the final sought formula, expressing the basic law of the adnabate process for a monatomic ideal gas: $T \sim \frac{1}{V^{2/3}}$.

The exponent $2/3$, appearing in expression (13), has a certain physical meaning. It can be shown (see Appendix) that

$$\frac{2}{3} = \frac{C_p}{C_V} - 1,$$

where $C_p$ is the specific heat of the gas if it is heated at constant pressure, and $C_V$ is the specific heat of the gas at constant volume. Therefore, the law describing the adnabate process (expression (13)) is usually written in the form

$$TV^{\gamma-1} = \text{const},$$

where $\gamma = \frac{C_p}{C_V}$.

We examined in detail the adnabate process for monatomic gases. But it turns out that equation (14) describes the adnabate process in the case of polyatomic gases. Only the value of quantity $\gamma$ changes. For example, for diatomic gases $\gamma - 1 = \frac{2}{5}$ (and not $2/3$, as for monatomic gases). This is due to the fact that for diatomic gases the internal energy is $E = \frac{5}{2} NkT$ (not $\frac{3}{2} NkT$).

Diatomic molecules can contain not only translational motion, but also rotation around axes passing through the center of the molecules. There is also a certain energy associated with this rotation. That's why the exponent $\gamma - 1$ turns out to be different: $\gamma - 1 = \frac{2}{5}$. We invite readers to obtain this value themselves.

Application

The magnitude of the heat capacity of a substance depends not only on its nature or temperature, but also on the conditions under which the heating process occurs. For example, when heated in a closed vessel, the volume of gas does not change, but in a vessel closed by a movable piston, the pressure remains unchanged. In this case, the supplied heat is spent not only on increasing the internal energy of the gas, but on performing distribution work. The heat in these two cases is different. In the first case, it is called the heat capacity at constant volume and is denoted $C_V$, and in the second case it is called the heat capacity at constant pressure $C_p$. It is clear that $C_p > C_V$. Let's find the difference between these quantities.

According to the law of conservation of energy, the amount of heat $Q$ supplied to the gas is equal to the sum of the changes in the internal energy of the gas $\Delta E$ and equal to the gas $A$:

$$Q = \Delta E + A.$$

For monatomic gases, the change in internal energy $\Delta E = \frac{3}{2} Nk\Delta T$. The work of gas $A$ for small changes in volume $\Delta V$ is equal to $A = p\Delta V$ (p is the gas pressure). That's why

$$Q = \frac{3}{2} Nk\Delta T + p\Delta V,$$

and thermal heat of gas

$$C = \frac{Q}{\Delta T} = \frac{3}{2} Nk + p \frac{\Delta V}{\Delta T}.$$

If the volume of a gas does not change, then its specific heat

$$C_V = \frac{3}{2} Nk.$$

If the pressure remains changed, then

$$C_p = \frac{3}{2} Nk + p \frac{\Delta V}{\Delta T} = \frac{3}{2} Nk + \frac{\Delta (NkT)}{\Delta T} = \frac{5}{2} Nk$$

(we will use the basic equation of state of an ideal gas $pV = NkT$). From here

$$C_p - C_V = Nk.$$

Then formula (10) can be written in the form

$$- (C_p - C_V) T \frac{\Delta V}{V} = C_V\Delta T,$$

or

$$\frac{\Delta T}{T} = - \left( \frac{C_p}{C_V} - 1 \right) \frac{\Delta V}{V} = - (\gamma - 1) \frac{\Delta V}{V},$$

where do we finally get

$$TV^{\gamma-1} = \text{const.}$$
