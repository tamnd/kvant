---
id: 1975-12-myakishev-raschet-uchastka-tsepi-soderzhaschego-e-d-s-61096a5a
issue: kvant_1975_12
year: 1975
number: "12"
title: Calculation of the section of the chain containing e. d.s.
authors:
  - Мякишев Г. Я.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 57
page_labels: 51-55
tag: 0F4U
lang: en
source: kvant_digital
extraction: vision
content_sha256: cd2ef4db2cb982be2d0e814b34e29511e5bb67451658748ebc41ab38fadd8da0
prompt_sha256: draft-1
translated_from: content/ru/1975/12/articles/13_myakishev-raschet-uchastka-tsepi-soderzhaschego-e-d-s-61096a5a.md
source_content_sha256: 0de92004627975980e0b312f023aec141743f47116a37834d176310f2761364b
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

G. Ya. Myakitsev

Calculation of the circuit section containing E.M.S.

The greatest difficulties in solving problems involving the construction of electric current arise when there is a current source in the section of the circuit considered in the problem.

Ohm's law

If a section of the circuit contains only total resistance $R$, then Ohm’s law has the following form:

$$I = \frac{U}{R}$$

(1)

The most serious, but nevertheless quite common mistake is that this law is used to find the current strength in a section of a circuit containing a current source, or in other words, E. M. S. In fact, the current strength in such a section depends not only on the voltage $U_{12}$ at the ends of the section (1 - the initial, 2 - the end points of the section), but also on the E. M. S. €:

$$I = \frac{U_{12} + €}{r}$$

(2)

(r is the internal resistance of the current source).

This is Ohm's law for the section of the circuit containing E.M.F.

The quantities included in formula (2): current $I$, voltage $U_{12}$ and E.M.S. € are algebraic, i.e. they can be both positive and negative. Only resistance $r$ is always positive. The main source of errors when using this law is the incorrect choice of the sign of a particular quantity. To avoid mistakes when placing signs, you must adhere to general rules that are valid in all cases without exception.

First you need to select an (arbitrary) positive traversal direction in the loop. The current strength in the area under consideration will be positive if the direction of the current (i.e., the direction of movement of positive charges) coincides with the selected direction *. The e.m.f. will be positive if the work done by the side to move a single positive charge in a given section of the circuit is positive. (In the case of a galvanic cell or battery, the E.M.F. is positive if the charge moves inside the negative electrode source to the positive one). Finally, under voltage $U_{12}$ on a section of the circuit, one must remember the potential difference between the initial 1st and final 2 points of the section: $U_{12} = \varphi_1 - \varphi_2$.

To better understand the meaning of formula (2), let us examine in detail two applications:

*) If the direction of the current is not known in advance (before solving the problem), then it can be chosen arbitrarily. After solving the problem, you will get a positive or negative current value. In the first case, this means that we have chosen the direction of the current correctly. In the second case, the direction of the current is opposite to the chosen one.

⟦folio 52⟧

⟦figure⟧
Fig. 1.

measure - discharging and charging the battery.

DISCHARGE AS KUMULATOR. At figure 1 the dotted frame highlights the section of the chain with e. d.s. With the chosen direction of bypass counterclockwise $I>0$, $\mathscr{E}>0$, and $U_{12}<0$ (since the potential of point *1* - the negative pole of the battery is less than the potential of point *2* - the positive pole), i.e. electric forces do negative work \*). Therefore, equation (2) for the modules will be written as follows:

$$|I| = \frac{|\mathscr{E}| - |U_{12}|}{r},$$

or

$$|U_{12}| = |\mathscr{E}| - |I|r.$$

---
\*) If there were other sources in the circuit under consideration, connected accordingly, then the case $U_{12}>0$ would be possible.

⟦figure⟧
Fig. 2.

⟦column⟧

⟦figure⟧
Fig. 3.

The voltage is equal to e. d.s. source minus the voltage drop across the section resistance.

The resulting formula, in particular, shows that for an open circuit ($I=0$) e. d.s. modulo equal to the voltage at the terminals of the current source. Therefore e. d.s. can be measured using a voltmeter connected to an open circuit source. You just need to remember that there will be some inaccuracy. An ordinary voltmeter has, although very large, but still not infinitely large resistance, so current flows through the voltmeter and $Ir \neq 0$, so that in fact the measured voltage is somewhat less than e. d.s.

CHARGING K U M U L I T O R A. The battery charging circuit is shown in figure 2. Let’s choose the direction of bypassing the circuit clockwise. Then $I>0$, $U_{12}>0$, but $\mathscr{E}<0$. At the same time

$$|I| = \frac{|U_{12}| - |\mathscr{E}|}{r}, \quad \text{или} \quad |U_{12}| = |\mathscr{E}| + |I|r.$$

The voltage on the battery is greater than its e. d.s. by the amount of voltage drop across the internal resistance of the battery.

Let us now consider several specific problems.

Problem 1. *Two elements whose electromotive forces are $\mathscr{E}_1 = 6$v and $\mathscr{E}_2 = 4$v and internal resistances $r_1 = 0{,}25$ ohm and $r_2 = 0{,}75$ ohm,*

⟦figure⟧
Fig. 4.

⟦figure⟧
Fig. 5.

*connected according to the circuit shown in figure 3. What is the potential difference between points 1 and 2? Neglect the resistance of the connecting wires.*

Let’s agree to consider the direction of traversal counterclockwise to be positive. Full e. d.s. circuit is equal to $\mathscr{E} = |\mathscr{E}_1| - |\mathscr{E}_2|$, and the current in the circuit

$$I = \frac{\mathscr{E}}{r_1 + r_2} = \frac{|\mathscr{E}_1| - |\mathscr{E}_2|}{r_1 + r_2}\ .$$

Ohm's law for the upper section of the chain between points *1* and *2* will be written as

$$U_{12} = Ir_1 - \mathscr{E}_1 = -\frac{|\mathscr{E}_1| r_2 + |\mathscr{E}_2| r_1}{r_1 + r_2} =$$
$$= -5,5\ в.$$

The minus sign indicates that the potential of point *1* is less than the potential of point *2*.

The same result can be obtained by applying Ohm's law to the lower part of the circuit:

$$U_{21} = Ir_2 - \mathscr{E}_2 =$$
$$= \frac{|\mathscr{E}_1| r_2 + |\mathscr{E}_2| r_1}{r_1 + r_2} = 5,5\ в,$$

Task 2. *Graphically depict the approximate course of the potential along a closed circuit with a galvanic element, shown in figure 1.*

Let the circuit be open at first, so the current and voltage drops in the external circuit and inside the source

⟦column⟧

are equal to zero. At the electrode-electrolyte boundaries in the source, there are potential jumps $\Delta U_1$ and $\Delta U_2$ (see Fig. 4). The sum of these jumps is equal to e. d.s. element: $\mathscr{E} = \Delta U_1 + \Delta U_2$.

When the circuit is closed, the potential jumps at the electrode-electrolyte boundaries do not change. But the potential of the electrolyte no longer remains constant, but decreases in the direction of the current, that is, from the negative electrode to the positive. The magnitude of the voltage drop across the internal resistance is $U_r = Ir$.

figure 5 shows an approximate graph of potential distribution in a closed circuit. The segment $AC$ depicts the potential of the positive electrode relative to some arbitrarily chosen zero level. The segment $BF$ corresponds to the potential of the negative electrode. The distance between the electrodes is $AB$. The segments $AE$ and $BD$ are the electrolyte potentials near the positive and negative electrodes. The slanted line $DE$ represents the potential drop inside the element. Its value $U_r$ is represented by the segment $DK$. Curve $CMF$ gives an idea of ​​the potential drop in the external circuit across resistance $R$. This voltage drop $U_R = IR$ is represented by the line segment $LF$. Segments $CE = LK = \Delta U_1$ and $DF = \Delta U_2$ correspond to jumps in

⟦folio 53⟧

⟦folio 54⟧

potential at the electrode-electrolyte boundaries*).

The CMFDEC line, depicting the path of the potential in the entire circuit, is closed. This means that the total work of the power plant field on a closed path is equal to zero. Indeed, the field does positive work in the CMF and DE sections and negative work in those places where there are upward potential jumps (FD and EC). In absolute value, positive work is equal to negative work. When a unit positive charge moves along a chain, the positive work is $U_r + U_R = DK + LF$ and the negative work is $\Delta U_1 + \Delta U_2 = \mathcal{E} = LK + DF$. But $DK + LF = LK + DF$, i.e. $U_r + U_R = \mathcal{E}$, which represents Ohm's law for the entire circuit.

The question may arise: what causes the release of heat in the circuit? In all areas, except for the electrode-electrolyte boundaries, only power plant forces act. At the boundaries, where there are potential jumps, there are also external (in this case chemical) forces acting, and the negative work of the power plant forces is equal to the positive work of external forces. Therefore, the positive work of power plant forces in the rest of the circuit turns out to be uncompensated. Due to this work, heat is released.

Figure 5 allows you to find the source of Ohm's law for the section of the chain containing e. d.s. As can be seen from figure, the direction model is $|U_R| = LF = LK - FK = LK - (DK - DF) = (LK + DF) - DK = |\mathcal{E}| - |I|r$, i.e. the direction at the source terminals is equal to e. d.s. minus the padence of the direction of the internal source.

*) figure 5 shows the case when the potential jump CE is greater than the potential jump DF. Of course, the opposite case is also possible.

Current power

By definition, the current power in circuit section 1-2 is equal to

$$P = IU_{12}.$$

This formula is valid for any section of the circuit (hereinafter containing a current source). Other expressions for power:

$$P = I^2R \text{ и } P = \frac{U_{12}^2}{R}$$

suitable only for a homogeneous area with a total resistance $R$. However, errors quite often occur when formulas (4) are written for a section containing e. d.s.

Let us pay attention to one more feature of the section of the circuit with a current source. For a homogeneous area, the power is always positive (indeed, $P = I^2R > 0$). The energy coming to this area from the outside increases its internal energy and is then transferred to surrounding bodies in the form of heat (the Joule-Lenz law is satisfied).

If there is e. d.s. in a section the power can be either positive or negative. For clarity, let us turn once again to the processes of charging and discharging the battery.

As we have already said, when charging a battery, the current and direction are the same in sign (this goes in the direction of the lost potential, as in a homogeneous section of the circuit), and the sign of e. d.s. opposite sign of current strength. Therefore, power $P = IU_{12}$ is positive, i.e. the battery consumes power from the outside. What does it spend on? Let's rewrite the expression for power in a different form. Since $U_{12} = Ir - \mathcal{E}$, then

$$P = I^2r - I\mathcal{E} = I^2r + |I||\mathcal{E}|.$$

The first term is the expression known from the Joule-Lenz law for the amount of heat released in the accumulator per unit time. And the second term is the work per unit time performed

⟦folio 55⟧

against third-party (chemical) forces; Due to this work, the chemical energy of the battery increases. Thus, the energy consumed from outside is partially released in the form of heat, and partially goes to increase the energy of the battery.

When the battery is discharged, the signs of the current and voltage are opposite (so the battery goes in the direction of increasing potential), and the signs of the current and e. d.s. are the same. Therefore power

$$P = IU_{12} = -|I| |U_{12}| = I^2r - |I| |E|$$

negative. This means that power is not supplied to this section from the outside, but rather, the battery supplies power to the external circuit. In this case, of course, part of the power $(I^2r)$ consumed by the battery is released in the form of heat at its internal resistance. The rest of the power is given to the external circuit.

It should be supported that the above calculations (in particular, formulas (5) and (6)) are valid regardless of the origin of the emission. d.s. in the area under consideration.

Now let's look at this problem.

Problem 3. What is the maximum mechanical power $P_m$ that a serial *) DC motor connected to a network with a voltage of $U = 120$ V can develop if the resistance of its windings is $r = 20$Om?

When the motor armature rotates in a magnetic field, an e-wave appears in its winding. d.s. inductance $E$, therefore (similar to the case of charging a battery)

$$|U| = |I|r + |E|.$$

Then the total power $P$ consumed by the motor is equal to

$$P = IU = I^2r + |I| |E|.$$

Frequent power $P_T = I^2r$ is the amount of heat released into the volume

*) A serial motor is an electric motor whose windings are connected in series.

Fig. 6. a) $E_1 > E_2$, $r_1 < r_2$; b) $E_1 = E_2$, $r_1 = r_2$.

skeins per unit of time. The second term in expression (8) represents the mechanical power $P_{mex}$. Let us express the current strength $I$ from (7):

$$|I| = \frac{|U| - |E|}{r}$$

Substituting the resulting value into the expression for mechanical power, we get:

$$P_{mex} = |I| |E| = \frac{|U| |E| - E^2}{r}.$$

The voltage $U$ and winding resistance $r$ are given, and e. d.s. inductance $E$ can vary, for example, depending on the rotation speed of the motora. The problem requires finding the maximum mechanical power $P_m$ of the motor, and expression (9) has a maximum at $E = \frac{U}{2}$ (see, for example, «Kvant» 1974, No. 5, p. 65). Therefore, finally

$$P_m = \frac{U^2}{4r} = 180 \text{ bm}.$$

Fig. 7. a) $E_1 > E_2$; b) $E_1 = E_2$.
