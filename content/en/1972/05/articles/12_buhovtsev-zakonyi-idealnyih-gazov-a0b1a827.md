---
id: 1972-5-buhovtsev-zakonyi-idealnyih-gazov-a0b1a827
issue: kvant_1972_5
year: 1972
number: "5"
title: Ideal gas laws
authors:
  - Буховцев Б. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 52
page_labels: 45-50
tag: CXX7
lang: en
source: kvant_digital
extraction: vision
content_sha256: cf249e0ab2f307997161cbe9ab65b341a1f2aa9c95f3e8fcd8c4849c1d348e3a
prompt_sha256: draft-1
translated_from: content/ru/1972/05/articles/12_buhovtsev-zakonyi-idealnyih-gazov-a0b1a827.md
source_content_sha256: ed7c2de964d5ba0bb47c90618c8c7cfda3cd9a051912036862582bba586856ef
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

What quantities can characterize the state of an ideal gas?

Assuming that we know the chemical composition of the gas and its mass, we can use such parameters as volume $V$ occupied by the gas, pressure $P$, temperature $T$ of the gas to describe its state. The relationship between these parameters of ideal gases reflects the basic laws: Boyle-Mariotte law, Gay-Lussac law, Charles law and Clapeyron-Mendleev law. Having obtained equations that describe these laws, we can practically solve any problems in which we are interested in the physical state of an ideal gas.

Boyle-Mariotte Law

$$PV = \text{const.}$$

(1)

This correspondence between pressure and gas volume was first established by the English physicist Boyle in 1662. In 1676, independently of Boyle, the French physicist Mariotte established the same relationship between pressure and gas volume. Equality (I), expressing the Boyle-Mariotte law, is satisfied only under certain conditions: the temperature of the gas remains unchanged, its mass is constant and the chemical composition of the gas does not change. In addition, the temperature should not be too low and the pressure not too high.

Different states of a gas at the same temperature can be represented on a graph (the so-called $P-V$-diagram) by points. The locus of such points is a hyperbola (this can also be seen from correspondence (I)).

It can also be considered as a graph of a process occurring at a constant temperature - the so-called isothermal process (Fig. 1). The curve describing an isothermal process is called isotherm.

Here it is important to remember that by placing a point on the graph, we thereby completely determine the state of the gas: its pressure, volume and temperature. This means that the gas is in a state of equilibrium at every moment (thermal equilibrium range). Consequently, all processes described by equations and depicted on graphs are assumed to proceed very slowly or, as they say, quasi-statically.

Let's consider an example of a typical problem using the Boyle-Mariotte law.

Exercise. In the middle of a narrow horizontal tube sealed at the common ends (Fig. 2) there is a column of mercury $h=25$ cm long. Mercury separates two columns of air in the tube, each $l_0=1$ m long. Air pressure $P_0=76$ cm·cm., temperature remains constant. At what distance $x$ will the mercury rod move if the tube is placed vertically?

Fig. 1.

⟦folio 46⟧

Fig. 2.

Solution and e. The distance between two columns separately acts in a standing vertical tube and we apply the Boyle-Mariotte law to each of them (cross-sectional area of ​​the tube S):

$$P_0 l_0 S = P_1 (l_0 + x) S,$$
$$P_0 l_0 S = P_2 (l_0 - x) S.$$

From the condition of mechanical equilibrium of the tube stem, it follows that when the tube is in a vertical position, the pressure in the lower column affects

$$P_2 = P_1 + \rho gh$$

(ρ is the density of mercury). Substituting this value $P_2$ into (2), we obtain a quadratic equation, solving which we find that

$$x = \left( -\frac{P_0}{\rho g} + \sqrt{\left(\frac{P_0}{\rho g}\right)^2 + h^2} \right) \times \frac{l_0}{h} \approx 16 \text{ (cm)}$$

(a negative root value has no meaning).

It is interesting to note that when calculating the unknown $x$, we do not need information about the density of mercury $\rho$, nor about the correspondence between pressure units. The fact is that, by definition, the pressure is $P$, which creates 1 cm pm. cm., equals $P = \rho g \cdot 1$ cm.

Therefore, $\frac{P}{\rho g} = 76$ cm without any additional intersections.

So, the state of a gas with the same temperature corresponds to a certain isotherm in the diagram $P$ - $V$. Another constant temperature corresponds to another isotherm. How is it located in relation to the first?

It is impossible to answer this question based on the Boyle-Mariotte law alone. You need to know one more of the dependencies: either $V(t)$ or $P(t)$.

The dependence of the volume $V$ of a gas on temperature at constant pressure was studied by the French scientist Gay-Lussac. In 1802, he published the law of isobaric ($P = \text{const}$) expansion of gases.

According to Gay-Lussac's law, at constant pressure, constant mass and constant chemical composition of a gas, its volume $V$ at temperature $t$ (Celsius scale) is equal to

$$V = V_0 + \beta V_0 t,$$

or

$$V = V_0 (1 + \beta t),$$

(II)

where $V_0$ is the volume occupied by the gas at $0^\circ\text{C}$. In a similar way it was found that

$$\beta = \frac{1}{273} \varepsilon \rho \delta^{-1}.$$

Thus, when the temperature of a gas increases by one degree, its volume increases by the same amount, equal to $\frac{V_0}{273}$. Consequently, the graph of Gay-Lussac's law, that is, the graph of the dependence of $V$ on $t$ at constant pressure (isobar) is a straight line. Taking this into account, it is possible to solve problems similar to the following without calculations.

Task a. When a gas is heated from temperature $t^\circ\text{C}$ to temperature $(t+1)^\circ\text{C}$ at constant pressure, the volume of the gas increases by $\frac{1}{300}$ of the original, that is, by $\frac{1}{300} V_t$. Under what conditions can this happen?

Solution and e. When heated from $0^\circ\text{C}$ to $1^\circ\text{C}$, the volume of gas increases by $\frac{1}{273} V_0$, that is, by $\frac{1}{273}$ of the original, and becomes equal

$$V_1 = V_0 + \frac{1}{273} V_0 = \frac{274}{273} V_0.$$

When heated from $1^\circ\text{C}$ to $2^\circ\text{C}$, the volume again increases by the same amount $\frac{1}{273} V_0$, which is already

⟦folio 47⟧

$\frac{1}{274}$ part of volume $V_1$. When heated from $2^\circ$ C to $3^\circ$ C, the volume returns to $\frac{1}{275} V_2$, from $3^\circ$ C to $4^\circ$ C to $\frac{1}{276} V_3$, etc. (Fig. 3). In general, when heated from $t^\circ$ C to $(t+1)^\circ$ C, the volume returns to $\frac{1}{273+t}$ of the initial one. It follows that heating is arbitrary from $27^\circ$ to $28^\circ$ C.

Let's consider another problem.

Exercise. At a temperature of $t_1=25^\circ$ C, the gas occupies a volume of $V_1=1,5$ liters. What volume $V_2$ will the gas occupy if it is heated to $t^2=125^\circ$ C at constant pressure?

Solution. Volumes $V_1$ and $V_2$ are related to the volume of gas at $0^\circ$ With correspondences

$$V_1 = V_0(1 + \beta t_1), \quad V_2 = V_0(1 + \beta t_2).$$

From here

$$V_2 = \frac{1 + \beta t_2}{1 + \beta t_1} V_1 = \frac{\frac{1}{\beta} + t_2}{\frac{1}{\beta} + t_1} V_1 = \frac{273 + t_2}{273 + t_1} V_1 \approx 2(\lambda).$$

Solutions to both problems show that it is convenient to move to another temperature scale (the Kelvin scale), the zero of which (absolute zero) lies below the Celsius scale by $273^\circ$. Since it is at this point that the extensions of all isobars intersect

Fig. 3.

Fig. 4.

⟦folio 48⟧

On the graph of the dependence of $P(t)$ at $V=\text{const}$, Charles’s law is expressed by straight lines (isochores) intersecting the $t$ axis at point $t=-273^\circ\text{C}$. Moving on to the absolute temperature scale, we obtain a simple form of writing Charles’s law:

$$\frac{P}{T}=\text{const}$$

This dependence is easily obtained from the Boyle-Marriott and Gay-Lussac laws using two transitions $V \rightarrow V'$ at $T_1=\text{const}$ and $T_1 \rightarrow T_2$ at $P_2=\text{const}$ (Fig. 5).

Any real gas obeys the mentioned gas law only approximately. Believing that these are the law

Fig. 5.

Fig. 6.

We are carried out precisely, we consider the gas ideal. In this country only such gases are discussed.

Let's give an example of a problem using Charles's law. The pressure gauge on the oxygen cylinder shows $P_1=95\text{ am}$ in a room with a temperature of $t_1=17^\circ\text{C}$. The cylinder was taken out to the barn, where at a temperature of $t_2=-13^\circ\text{C}$ the pressure gauge reading became $P_2=85\text{ am}$. Was there any loss of oxygen during transfer?

The solution to the equality test is $\frac{P_1}{T_1}=\frac{P_2}{T_2}$, valid for $m=\text{const}$ (Answer: there was no loss.)

The more complex behavior of a gas, when pressure, volume, and temperature changes, can be easily seen on the graph. Let's consider, for example, this problem.

Task. Some processes occurring with an ideal gas are depicted on a graph of pressure versus temperature in the form of a circle. It is required to divide the circle with the smallest number of points into parts corresponding to processes, in each of which any of the quantities $P, V$ and $T$ changes monotically (that is, increases or decreases.).

Solution. The points corresponding to the highest and highest pressure are points $a_1$ and $a_2$ of tangency of the circle with the vertical isotherms (Fig. 6). The points at which the highest and highest pressure is achieved are points $b_1$ and $b_2$ of contact of the circle with the horizontal isobars. Isochores on the graph $P(T)$ are depicted as straight lines passing through the origin of coordinates. The smaller the volume, the larger the isochore. Two isochores tangent to the circle give two more points $c_1$ and $c_2$. The entire circle is thus divided into six curves depicting the required processes.

From the above it is clear that the parameters that determine the state of a given mass of gas of an unchanged chemical state ($P, V$ and $T$) are related to each other. If two quantities are known

⟦folio 49⟧

We can find what I require. The equation that determines the relationship between temperature, volume and pressure is called the equation of state of a gas.

Clapeyron-Mendeleev equation

To obtain this equation, connect two arbitrary states of an ideal gas. Let, for example, a gas be transferred from the state $P_1$, $V_1$, $T_1$ to the state $P_2$, $V_2$, $T_2$. For the transition it uses processes already known to us. Using only two processes, transition 1-2 (Fig. 7) can be achieved in six ways (1-3-2, 1-4-2, 1-5-2, 1-6-2, 1-7-2, 1-8-2). Let's consider the first of them. Process 1–3 is isochoric, that is, $V_1 = V_3$. Therefore $\frac{P_1}{T_1} = \frac{P_3}{T_3}$.

Process 3-2 is isothermal ($T_2 = T_3$) and therefore $P_3V_3 = P_2V_2$. Multiplying all four correspondences, we get

$$\frac{P_1V_1}{T_1} = \frac{P_2V_2}{T_2}.$$

We took the initial and final states of the gas completely arbitrarily. Therefore, for a given mass of gas of an unchanged chemical state, we can write

$$\frac{PV}{T} = B = \text{const.}$$

Equation (IV) establishes a simple relationship between the pressure, volume and temperature of a given mass of gas. It completely describes the state of the gas.

Fig. 7.

side of an ideal gas. This equation was first deduced by Clapeyron, circling the laws of Boyle - Mariotte and Gay-Lussac. The Clapeyron equation makes it possible to solve problems in which there is a relationship between the properties of the state of a gas at a constant mass.

Let's look at a simple example.

Exercise. A cylindrical vessel filled with gas is divided into two parts by a movable partition so that the volume ratio of the parts is 2:3. Will the gas temperature in the changing part become equal to $T_1 = 227^\circ\text{C}$, and in the larger part - $T_2 = 60^\circ\text{C}$? Let's make a claim.

Solution. For gas in less than part $\frac{PV_1}{T} = \frac{P'V'_1}{T_1}$. For gas mostly $\frac{PV_2}{T} = \frac{P'V'_2}{T_2}$. From here

$$\frac{V'_1}{V'_2} = \frac{V_1}{V_2} \cdot \frac{T_1}{T_2} = \frac{2}{3} \cdot \frac{273 + 227}{273 + 60} \approx 1.$$

There is only one step left to make the equation of state of ideal gases universal. It is necessary to take into account the mass of the gas and its chemical “individual”. This step was taken by the Great Russian chemist D.I. Mendeleev. He used the law discovered in 1811 and concluded by the scientist A. Avogadro, which concluded that all gases, regardless of their chemical nature, at the same pressure and temperature, occupy the same volume if they are taken in quantities proportional to their molecular weight. In particular, at $0^\circ\text{C}$ ($T_0 = 273^\circ\text{K}$) and pressure $P = 1$ amm, the gas volume is $V_0\mu = 22,4$ $m^3/\text{kmоль} = 22,4$ $l/\text{моль}$. Knowing this, we can calculate the constant $B$ in equation (IV). It is proportional to the number of moles of gas. This number is found by dividing the mass of the gas by the molecular mass: $v = \frac{m}{\mu}$.

⟦folio 50⟧

The proportionality coefficient $R = \frac{P_0 V_0 \mu}{T_0}$ is called the universal gas constant. Counting gives for $R$ the value

$$R = 8,3 \cdot 10^3 \frac{\partial x/\partial p}{\partial T} = 0,082 \cdot \lambda \cdot \alpha m/\alpha p \cdot \alpha m.$$

Thus, the equation of state of an ideal gas, which is called the Mendeleev-Clapeyron equation, is written as

$$PV = \frac{m}{\mu} RT.$$

Any problem of calculating processes in ideal gases can be solved almost automatically if we immediately write down equation (V) for each state of the gas. But equation (V) allows us to solve problems of a different type.

Task a. The vapor density of a neokoto compound of carbon and hydrogen is equal to $\rho = 2,5$ e/l at a temperature of $t = 10^\circ$ C and a pressure of $P = 760$ mm. see What connection is this?

Solution e. From equation (V) the molecular weight of the compound can be found:

$$\mu = \frac{mRT}{PV} = \frac{\rho RT}{P} \approx 58 \left(\frac{e}{\mu}\right).$$

Butane isomers $C_4H_{10}$ have this molecular weight.

Let's consider one more problem.

Task a. Assuming that of the total mass of air, 75% is nitrogen, and 25% is oxygen, determine how much air is released from a room with a volume of 50 $m^3$ when the temperature rises from $17^\circ$ C to $27^\circ$ C. The atmospheric pressure is normal ($P_0 = 1$ atm).

Solution e. Molecular mass of air

$$\mu = \frac{0,75m + 0,25m}{\frac{0,75m}{\mu_1} + \frac{0,25m}{\mu_2}} \approx 29 \left(\frac{\kappa e}{\mu}\right).$$

Change in air mass in a room

$$\Delta m = \frac{\mu P_0 V}{RT_2} - \frac{\mu P_0 V}{RT_1} =$$

$$= \frac{\mu P_0 V T_0}{P_0 V 0 \mu} \left(\frac{1}{T_2} - \frac{1}{T_1}\right) \approx -2 \left(\kappa e\right).$$

Exercises

1. The barometer gives incorrect readings due to the arrival of a small amount of air over the room. At a pressure of 755 mm. see barometer shows 748 mm. cm., and at 740 mm. cm -- 736 mm. cm. What pressure will the barometer show if the actual pressure is 760 mm. cm?

2. How did the gas pressure change during the process depicted in Fig. 8?

Fig. 8.

3. The reporting state shown at figure 9 is immersed in warm water. Describe the behavior of rutini in a pressure gauge.

4. A free-sliding, gas-tight piston holds media

Fig. 9.

pumped out sauce with two perfect springs. When gas was introduced into one of the wedges of the sauce at a temperature of $T_1 = 300^\circ$ K, the length of this part of the sauce turned out to be $x_1 = 0,2$ mm, and after heating the gas to $T_2 = 750^\circ$ The wedge of the same part became $x_2 = 0,25$ mm. What will be the length of $x_3$ at $T_3 = 1200^\circ$ K?

5. Derive equation (IV) using the processes 1-4-2, 1-5-2, 1-7-2, or 1-8-2 (see Fig. 7).

6. The 20.5 liter cylinder contains a mixture of hydrogen and helium. The mass of the mixture is 13 e, the temperature is 27°C, the pressure is 5.4 atm. Determine the mass of hydrogen and the mass of helium.
