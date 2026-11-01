---
id: 1982-1-tugushev-elektricheskie-tsepi-s-nelineynyimi-elementami-1b72ab8b
issue: kvant_1982_1
year: 1982
number: "1"
title: Electric circuits with nonlinear elements
authors:
  - Тугушев В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 43
page_last: 46
page_labels: 41-44
tag: V4HB
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8d7303545989d35caa1fde6fd660b23a7781d80a95e8a30b5be4853b164057e3
prompt_sha256: draft-1
translated_from: content/ru/1982/01/articles/13_tugushev-elektricheskie-tsepi-s-nelineynyimi-elementami-1b72ab8b.md
source_content_sha256: 32f5ee5b16c4c63742bee1786a3f0c6fdcaeaf55aeab92706296ecdcb8b512b0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 41⟧

Physics

Mechanics: 1970 - No. 6, p. 39; 1971 - No. 2, p. 44; No. 5, p. 50; No. 9, p. 47; No. 11, p. 54; 1972 - No. 3, p. 58; No. 9, p. 51; 1973 - No. 9, p. 68; No. 11, p. 57; 1974 - No. 3, p. 52; No. 11, p. 60; 1975 - No. 1, p. 60; 1976 - No. 12, p. 40; 1977 - No. 2, p. 50; No. 3, p. 46; No. 11, p. 77; No. 12, p. 52; 1978 - No. 3, p. 54; No. 11, p. 48; No. 12, p. 42; 1979 - No. 10, p. 49; 1980 - No. 3, p. 41; No. 11, p. 38; No. 12, p. 45; 1981 - No. 1, p. 43; No. 10, p. 47.

Liquid and gases: 1972 - No. 12, p. 53.

Molecular physics, thermal phenomena: 1972 - No. 5, p. 45; 1973 - No. 1, p. 43; 1974 - No. 1, p. 60; 1976 - No. 3, p. 58; 1977 - No. 6, p. 67; 1978 - No. 1, p. 42; 1979 - No. 1, p. 50; 1981 - No. 2, p. 44; 1981 - No. 11, p. 36; 1982 - No. 12, p. 42.

Fundamentals of electrodynamics: 1972 - No. 2, p. 54; No. 4, p. 62; No. 6, p. 55; No. 6, p. 59; No. 7, p. 48; No. 7, p. 51; 1973 - No. 3, p. 50; No. 7, p. 35; 1974 - No. 5, p. 64; 1975 - No. 4, p. 41; No. 12, p. 51; 1978 - No. 4, p. 42; No. 5, p. 38; 1979 - No. 2, p. 52; No. 3, p. 45; No. 4, p. 43; 1980 - No. 6, p. 36; 1981 - No. 7, p. 39.

Oscillations and waves: 1974 - No. 6, p. 31; 1976 - No. 2, p. 51; 1981 - No. 3, p. 46.

Optics: 1971 - No. 7, p. 41; 1977 - No. 4, p. 50; 1979 - No. 5, p. 39; No. 6, p. 30; 1980 - No. 4, p. 44; 1981 - No. 5, p. 37; No. 6, p. 45.

In addition, some general issues of constructing statics: 1970 - No. 12, p. 50; 1972 - No. 6, p. 62; No. 10, p. 52; 1973 - No. 4, p. 52; No. 5, p. 43; No. 7, p. 30; 1975 - No. 5, p. 60; No. 11, p. 50; 1978 - No. 6, p. 65; 1979 - No. 7, p. 41; 1981 - No. 4, p. 40; No. 9, p. 42.

V. Tugushchev

Electric circuits with nonlinear elements

When calculating any electrical circuit, the main task is to determine the currents and voltages in all sections of the circuit. The relationship between current and voltage in each section is called the current-voltage characteristic of the section. It is caused, on the one hand, by the physical processes that occur during the movement of charges in a substance under the influence of an electric field, and on the other, by the design of the circuit itself (that is, the connection of its elements).

The simplest linear current-voltage characteristic occurs, for example, for a metal conductor:

$$U = IR,$$

where $R$ is the proportionality coefficient between voltage and current, called resistance. Resistance is determined by the material, size and temperature of the conductor.

There are, however, numerous devices and elements, the physical and design features of which lead to a nonlinear relationship between current and voltage.

⟦folio 42⟧

1. A. Let us depict on the same figure the straight line (red line) given by equation (*). Obviously, there is only one point of intersection of this line with the current-voltage characteristic of the nonlinear element; the current corresponds to it
$$I_2 = 10 \text{ мА}.$$
Problem 2. Find the current through a resistor with resistance $R_0$ in the circuit shown in figure 2, a. The current-voltage characteristic of the diode (nonlinear element) is shown in figure 2, b.

Obviously, the circuit can operate in two modes: when the diode is disabled and when the diode is open.

If the diode is inhibited, the current flows through a series chain of resistors with resistances $R_0$ and $R$, and it is equal to
$$i_1 = \frac{u(t)}{R_0 + R}.$$
In the second case, when the diode is open and the direction on it is $U_0$ and does not change with time, the current $i_1$ develops at points $A$ and $B$ so that (see Fig. 2, a)
$$i_{II} = i_1 + i_2.$$
In addition, for various sections of the circuit between points $A$ and $B$ the following equality holds:
$$U_0 + i_1 R = i_2 R,$$
$$i_2 R = u(t) - i_{II} R_0.$$
From the last three equations we find $i_{II}$:
$$i_{II} = \frac{2u(t) - U_0}{R + 2R_0}.$$
Now let's find out under what conditions modes I and II. It is clear that at the moments of opening and closing the diode, the direction in the section $AB$ should be equal to $U_0$, that is
$$i_1 R = U_0,$$ or $$\frac{u(t) R}{R_0 + R} = U_0.$$
It follows that for the directions
$$u(t) = U_0 \frac{R_0 + R}{R}.$$
There will be a change between regimes I and II. In particular, the first regime change will occur at the moment when
$$\cos \omega t = \frac{U_0}{U_M} = \frac{R_0 + R}{R} \left(U_M > U_0 \frac{R_0 + R}{R}\right).$$
A graph of the desired current versus time for $U_M = 300 \text{ В}, U_0 = 100 \text{ В}, R_0 = 10 \text{ кОм}$ and $R = 20 \text{ кОм}$ is presented at figure 2, c.
Problem 3. Current I of a two-electron tube in a certain range

⟦folio 43⟧

tense can be associated with the potential difference $U$ between the electrodes by matching $I = aU + bU^2$ at $U > 0$ ($a, b > 0$) and $I = 0$ at $U \leq 0$. Two such lamps are connected in a circuit, as shown in figure 3. The parameters $a$ and $b$ for both lamps are equal to the corresponding $a_1 = 0,06$ mA/B, $b_1 = 0,008$ mA/B$^2$ and $a_2 = 0,04$ mA/B, $b_2 = 0,002$ mA/B$^2$. Counting $\mathcal{E} = 200$V and $R = 10$kΩ, calculate the power consumed by the lamps.

The required power $P_{\text{lamп}}$ can be found from the law of conservation of energy $P_{\text{lamп}} + P_R = P_\mathcal{E}$.

Here $P_R = I_0^2 R$ is the power dissipated in the resistor ($I_0$ is the current flowing through the resistor and battery), and $P_\mathcal{E} = \mathcal{E} I_0$ is the power supplied by the battery.

According to Ohm's law,

$$I_0 = \frac{\mathcal{E} - U}{R}.$$

In addition (see Fig. 3),

$$I_0 = I_1 + I_2,$$

Fig. 3.

Fig. 4.

where $I_1$ and $I_2$ are the current in the first and second lamps, respectively.

From the last two equations, using the relationship between the currents in the lamps and the voltage on them, we obtain the quadratic relative $U$ equation

$$(a_1 + a_2) U + (b_1 + b_2) U^2 = \frac{\mathcal{E} - U}{R},$$

from which we find $U$:

$$U = \frac{-(a_1 + a_2 + 1/R)}{2(b_1 + b_2)} + \frac{((a_1 + a_2 + 1/R)^2 + 4 \mathcal{E}(b_1 + b_2)/R)^{1/2}}{2(b_1 + b_2)} \approx 35,8 \text{ В}.$$

The negative root of the quadratic equation is discarded because it does not correspond to the physical meaning of the problem: at $U < 0$ the lamps are locked and do not conduct current.

Now, from the law of conservation of energy, find the required power $P_{\text{lamп}}$ consumed by the lamps:

$$P_{\text{lamп}} = P_\mathcal{E} - P_R = \frac{(\mathcal{E} - U) U}{R} \approx 0,6 \text{ Вт}.$$

Problem 4. Draw a graph of the current in voltage $I_{\text{вых}}$ versus input voltage $U_{\text{вх}}$ in the circuit shown in figure 4, a. All diodes ($\varDelta I_1, \varDelta I_2, \dots, \varDelta I_n$) are ideal, that is, their resistance in one direction is infinitely large, and in the other - infinitely small.

Let us denote by $R$ ($R = 1000 \text{ Ом}$) the resistance of the leftmost resistor (see Fig. 4, a), by $R/2$ ($R/2 = 500 \text{ Ом}$) the resistance of all other resistors and by $\mathcal{E}(\mathcal{E} = 1 \text{ В})$ the emf of the source connected in series with the first diode.

As long as the input voltage does not exceed 1 V, all diodes are locked, and current flows only in the leftmost branch of the circuit:

$$I_{\text{вых}} 0 = \frac{U_{\text{вх}}}{R} (U_{\text{вх}} < 1 \text{ В})$$

— as the voltage increases, the current increases linearly.

As soon as the input voltage reaches 1 V, the first diode will open and a current equal to $\frac{U_{\text{вх}} - \mathcal{E}}{R/2}$ will appear through it. At the same time it depends

⟦folio 44⟧

output, the current from the input voltage will have the form

$$I_{\text{вых}} 1 = I_{\text{вых}} 0 + \frac{U_{\text{bx}} - \varepsilon}{R/2} = \frac{3U_{\text{bx}}}{R} - \frac{2\varepsilon}{R} \quad (1 \text{ В} \leqslant U_{\text{bx}} < 2 \text{ В}).$$

With a further increase in voltage, the diodes $D_1$, $D_2$, etc. will be open at the input. The graph of current $I_{\text{вых}}$ versus voltage $U_{\text{bx}}$ is shown in figure 4, 6.

Look at this graph externally and you will see that a parabola is reproduced here along straight line segments. So, using this problem as an example, you became acquainted with the operation of a free electronic device - a functional transformation (quadrator). Using a system of diodes, resistors and current sources, he models the operation of squaring a function. Such devices are used in electronic modeling of various physical processes.

Task 5. Find the relationship between current and voltage for a metal conductor, taking into account the dependence of its resistance on temperature. The rate of heat transfer into the environment is considered proportional to the temperature difference between the conductor and the environment.

The usual relationship between current and voltage $U = IR$ assumes that the resistance $R$, which depends on temperature, is taken at the temperature $T$ of the conductor. But this temperature, generally speaking, differs from the temperature $T_0$ of the environment. As a result, heat transfer occurs between the conductor and the medium, and at a small temperature difference $T - T_0$ the amount of heat output in time $\Delta t$ is given by the correspondence

$$\frac{\Delta Q_{\text{пер}}}{\Delta t} = C (T - T_0),$$

where $C$ is a constant proportionality coefficient.

As current flows, the conductor heats up. (From a microsopper point of view, this is due to the number of electrons moving in the conductor under the influence of an electric field, with the number of nans of the crystal lattice, with various defects and low-costs.) The amount of heat output in the conductor during the time $\Delta t$ is associated with the current $I$ in the conductor, with the resistance $R$ of the conductor and with the voltage $U$ on it:

$$\frac{\Delta Q_{\text{выд}}}{\Delta t} = I^2 R = \frac{U^2}{R_0 (1 + \alpha (T - T_0))}.$$

Here $R_0$ is the resistance at the temperature of the conductor $T_0$, $\alpha$ is the temperature coefficient of resistance. (If the temperature $T_0$ is close to $0^\circ C$ and the difference $T - T_0$ is small, then the dependence of the resistance on temperature can indeed be represented as $R = R_0 (1 + \alpha (T - T_0))$.)

The conductor will be heated until the rate of release of the body in the conductor is equal to the rate of heat release into the environment.

$$\frac{\Delta Q_{\text{выд}}}{\Delta t} = \frac{\Delta Q_{\text{пер}}}{\Delta t},$$

or

$$\frac{U^2}{R_0 (1 + \alpha (T - T_0))} = C (T - T_0).$$

Hence the temperature difference

$$T - T_0 = \frac{-R_0 C + (R_0^2 C^2 + 4 U^2 \alpha R_0 C)^{1/2}}{2 \alpha R_0 C},$$

and the relationship between current and voltage is

$$I = \frac{U}{R_0 (1 + \alpha (T - T_0))} = \frac{U}{R_0 \left(1 + \frac{(R_0^2 C^2 + 4 U^2 \alpha R_0 C)^{1/2} - R_0 C}{2 R_0 C}\right)}$$

(the negative value $T - T_0$ is discarded since it has no physical meaning).

Let's analyze the result. It is easy to see that at $U^2 \ll R_0 C / (4 \alpha)$ it also practically always depends, since the correction to the resistance caused by heating is always small.
