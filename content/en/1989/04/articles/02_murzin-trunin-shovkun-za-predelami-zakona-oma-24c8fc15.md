---
id: 1989-4-murzin-trunin-shovkun-za-predelami-zakona-oma-24c8fc15
issue: kvant_1989_4
year: 1989
number: "4"
title: Beyond Ohm's Law
authors:
  - Мурзин С. С.
  - Трунин М. Р.
  - Шовкун Д. В.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2, 4, 5, 6, 7, 8
tag: YUIT
lang: en
source: kvant_digital
extraction: vision
content_sha256: faab8f3821ccb58080ed9a78268633249c179b502b30663992ef3aa8de32e968
prompt_sha256: draft-1
translated_from: content/ru/1989/04/articles/02_murzin-trunin-shovkun-za-predelami-zakona-oma-24c8fc15.md
source_content_sha256: f61dbdfde995504194aa8ca2df9223337e3b7d2c0d0642c0720fae40f69872b7
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

OUTSIDE
OMA'S LAW

Candidate of Physical and Mathematical Sciences
S. S. MURZIN,
Candidate of Physical and Mathematical Sciences
M. R. TRUNIN,
Candidate of Physical and Mathematical Sciences
D. V. SHOVKUN

"Watch out!" - a frequent user of this advice from Kozma Prutkov when it comes to the laws of physics. In particular, about the laws of physics. Let us recall, for example, Ohm's law: current is proportional to voltage. It turns out that this is not the case. And good! If this law were always observed, we would be left without many electrical and radio devices. Fortunately, Ohm's law, like most laws of physics, has a limited scope. It is outside the scope of this law that interesting physical phenomena arise that ensure the operation of these devices. These phenomena in themselves are very interesting, but today we will discuss another question: why is Ohm’s law violated?

Ohm's law

Let's connect the conductor to the electrical circuit and change the strength of the current I flowing through the conductor at different values ​​of the applied voltage U. Thus, we obtain the dependence I=I(U) - the current-voltage current of the electrical conductor. According to Ohm's law, the current strength of an electrical conductor, i.e., the current-voltage electric current, is a linear function

$$I(U) = U/R,$$

and the resistance R does not depend on U. If this is not the case (Ohm’s law is not satisfied), then the volt-ampere electric non-linear.

The simplest example of a conductor in which Ohm's law is violated is the spiral of an incandescent lamp. For a lamp with a power of 40 V, the current-voltage characteristic is shown at figure 1. The linear section is only at U<5 V, and at large values ​​of U, the current I grows more slowly than in the case of a linear dependence I(U). It is not difficult to prove why this happens. As the voltage increases, the coil heats up and its resistance increases. This example illustrates the general rule: Ohm's law is valid only at sufficiently small I and U, and at high currents and voltages it is violated.

Let's write Ohm's law in a different form. To do this, we introduce the current density values ​​j=I/S, where S is the cross-sectional area of ​​the conductor. Then

$$j = \frac{I}{S} = \frac{U}{RS} = \frac{U}{(\rho L/S)S} = \frac{1}{\rho} \frac{U}{L} = \sigma E.$$

Here $\rho$ is the resistivity of the conductor, the values ​​$\sigma=1/\rho$ are called specific conductivity, $L$ is the length of the conductor, $E=U/L$ is the electric field voltage. Ohm's law assumes a linear relationship between the current density j and the electric field voltage E. If the conductivity σ for some reason depends on the magnitude of the electric field, then the dependence of j on E becomes nonlinear, and Ohm's law is violated.

To find out the reasons for the violation of Ohm's law, consider the movement of electrons in conductors in the absence and presence of an electric field.

⟦folio 4⟧

$$\vec{u} = \frac{1}{N} \sum_{i=1}^{N} \left( \vec{v}_i - \frac{e\vec{E}}{m^*} t_i \right) = \frac{1}{N} \sum_{i=1}^{N} \vec{v}_i - \frac{e\vec{E}}{m^*} \left( \frac{1}{N} \sum_{i=1}^{N} t_i \right).$$

The value $\frac{1}{N} \sum_{i=1}^{N} \vec{v}_i$ is the average speed of the electric locomotive immediately after dissipation. Since the speed of an electric locomotive can immediately dissipate in any direction, $\frac{1}{N} \sum_{i=1}^{N} \vec{v}_i = 0$. The value $\frac{1}{N} \sum_{i=1}^{N} t_i = \tau$ has the meaning of the already familiar average free time. So, under the influence of an electric field, all electrons acquire additional speed (it is called drift), the average value of which is $u = eE\tau/m^*$, and this speed is directed parallel to the field $\vec{E}$.

Thus, in the presence of an electric field, the drift motion of the electric locomotive is superimposed on the xaotic movement, the preferential direction of movement of the electric locomotive appears - an electric current arises. If the concentration of an electric locomotive in a conductor is $n$, then the density of this current is

$$j = enu = \frac{ne^2\tau}{m^*} E.$$

On the other hand, we know that $j = \sigma E$. Means,

$$\sigma = \frac{ne^2\tau}{m^*}.$$

This formula is called Drude's formula. Ohm's law is valid if none of the quantities included in Drude's formula depends on $E$. If the concentration of an electric locomotive $n$ or the free time $t$, or the effective mass $m^*$ changes under the influence of an electric field, then Ohm’s law is violated.

When is Ohm's law true?

First of all, let us consider under what conditions the value $t$ does not change under the influence of the field $E$.

Time $t$ depends on the speed of the electric locomotive. Drift speed $u =$

$$eE\tau/m^*, \text{ появляющая при включении электрического поля, возрастает при увеличении } E. \text{ Пока электрическое поля мало, так что дрейфовая скорость } u \text{ гораздо меньше средней скоростиxaотического движения } v_0, \text{ величины } u \text{ можно пребречь и считать время } t \text{ не зависит от поля } E. \text{ Если } E \text{ велико настояло, что значение } u \text{ сравнито с } v_0, \text{ то дрейфовою скорость нужно учитывать. В этом случае скорости электровоз и, следовательно, время свободного пробета } t \text{ оказываются зависящими от электрического поля.}$$

Thus, for Ohm's law to be fulfilled, it is necessary that the condition be satisfied

$$u \ll v_0,$$

that is, the direction of the electric field in the conductor should be much less than $E = m^*v_0/e\tau$.

In semiconductors, as we have already said, $v_0 \sim 10^5$ m/s. To achieve a value of $u$ comparable to $v_0$, a field of $E \sim 10^6$ V/m must be applied to the semiconductor. This is a huge value, comparable to the direction of the field in lightning. Nevertheless, such a field can be created in semiconductors.

There is another, stronger speed limit $u$. It must be less than the speed of sound in the conductor (a $v_{38} \sim 10^3$ m/s):

$$u < v_{38}.$$

As soon as the speed $u$ reaches the value $v_{38}$, sound vibrations are excited in the crystal. In this case, the free charge time $t$ and the conductivity $\sigma$, proportional to $\tau$, may decrease. This situation is similar to a sharp increase in aerodynamic drag after an airplane overcomes a sound barrier.

So, in the field $E_{38} \geq m^*v_{38}/e\tau$ the conductivity begins to depend on the value $E$, and Ohm’s law is violated.

The effect of the electric field does not coincide only with the appearance of drift motion. It is known that when current flows through a conductor, a Joule cell is released and it heats up. Let's look at this process in more detail.

⟦folio 5⟧

Any conductor can be considered to consist of two subsystems: a crystal lattice formed by atoms of the substance, and a gas of conduction electrons filling the lattice. Electrons and lattice can be characterized by their temperatures $T_e$ and $T_p$. In the absence of an electric field, the electron gas is in thermal equilibrium with the lattice and the environment: $T_e=T_p=T_c$. The field $E$ acts on conduction electrons and heats them up first. Only then is heat transferred from the electrons to the lattice, and then to the environment. Therefore, in the presence of a field, thermal equilibrium is disrupted so that $T_e>T_p>T_c$.

If the heat transfer from the conductor to the environment is narrower than the heat transfer from electrons to atoms and, therefore, $T_e-T_p\ll T_p-T_c$, then the lattice, together with the electrons, heats up as a whole. (This situation is typical for the filament of an incandescent lamp.) The opposite case is also possible, when the electron temperature is much higher than the lattice temperature and $T_e-T_p\gg T_p-T_c$.

In metals, as we have already said, the average speed of chaotic thermal motion of electrons is practically independent of temperature. But in semiconductors, an increase in $T_e$ under the influence of an electric field means an increase in the speed $v_0$ of the thermal motion of electrons, and therefore a decrease in the free run time. If the change $\Delta v_0$ in the speed $v_0$ is small, i.e. $\Delta v_0\ll v_0$, then $v_0$ depends on $E$, and, therefore, $\tau$ on $E$ can be neglected. Condition $\Delta v_0\ll v_0$ is equivalent to the condition of small overheating $\Delta T_e$ of electrons relative to the equilibrium state:

$$\Delta T_e\ll T_e.$$

Thus, the conditions for the independence of the free charge time from the magnitude of the electric field, necessary for the fulfillment of Ohm’s law, sets the following restrictions on the scope of application of this law:

$$u \ll v_0,$$

$$u < v_{3B},$$

$$\Delta T_e\ll T_e=T_c.$$

Violation of any of these independences leads to deviation from Ohm's law. Below we will see that if the independence of $u \ll v_0$ and $\Delta T_e\ll T_e$ is violated, the electric field $E$ can also influence other quantities included in the Drude formula - the effective mass $m^*$ and the electron concentration $n$. The dependences of $m^*$ and $n$ on $E$ can significantly change the type of current-voltage characteristics of semiconductors.

Semiconductors in a strong electric field

In a sample through which current $I$ flows, power is released

$$P=I^2R=\sigma E^2LS$$

(we taught that $I=jS=\sigma ES$, $R=\varrho L/S=L/\sigma S$). Power $Q=\sigma E^2$ is released per unit volume. For the same value of $Q$, the electric field $E=$ $\sqrt{Q/\sigma}$ in semiconductors is larger than in metals, since the concentration of electrons in semiconductors and, therefore, the conductivity $\sigma$ is much lower. Consequently, it is easier to violate conditions $u<v_{3B}$, $u\ll v_0$ in them. In addition, for each electron in a semiconductor there is more power than in a metal. The electron gas heats up more slowly, and therefore independence $\Delta T_e\ll T_e$ is also violated more easily.

Violation of which of the conditions - (1), (2) or (3) - with an increase in the electric field will lead to the most significant deviation from Ohm's law depends on the type of semiconductor. For example, in CdS the $u<v_{3B}$ condition is violated first. At the same time, in the field $E_{3B}=1,4\cdot 10^5$ V/m per volt-ampere

⟦folio 6⟧

In the new characteristic $j(E)$ a kink appears (Fig. 2). If $E > E_{3B}$, this semiconductor emits sound intensely and can be used as a sound vibration generator.

In other semiconductors, such as Ge, Si, GaAs, InP, CdTe, sound is excited much weaker, and no noticeable kink is observed in the field $E_{3B}$. In these semiconductors, deviations from Ohm's law are associated with violation of condition $\Delta T_e \ll T_e$. In this case, the free beta time turns out to be inversely proportional to the field $E$, i.e. $\tau(E) \sim 1/E$, and depends on the current density and is associated only with changes in $m^*$ and $n$. In Ge and Si at $E > 10^6$ V/m on the current-voltage characteristic (Fig. 3) saturation $j(m^*, n)$ is observed, independent of $E$. In GaAs, InP, CdTe, as the electron energy increases with increasing $E$, not only does the free particle time $\tau$ decrease, but the effective mass $m^*$ also increases. An increase in $m^*$ causes a change in the interaction of electrons with the crystal lattice. As a result, in these semiconductors, starting from a certain value of the electric field $E_a$, the current density $j$ decreases with increasing $E$ (section $E_a < E < E_b$ to figure 3). In GaAs, the $j$ drop starts at $E_a = 3,2 \cdot 10^5$ V/m and continues to $E_b \approx 10$ $E_a$. In the field $E_a$ the electron drift speed is $u = j/en = 1,5 \times 10^5$ m/s.

In an even stronger field $E \sim 10^7$ V/m we violate condition $\Delta T_e \ll T_e$ and condition $u \ll v_0$ is also violated. In such a field, electrons receive energy during their free run that is sufficient to understand atoms. Fast electrons, when colliding with atoms, knock out additional electrons, which in turn are also accelerated by the field and generate new charge carriers. This process is called impact inization. The total concentration of $n$ electrons increases and, consequently, the conductivity increases. With an even greater increase in the electric field $(E > 10^7$ V/m), the concentration and conductivity increase like an avalanche, and breakdown of the semiconductor occurs.

Thus, in semiconductors in very strong fields $E$ the current density $j = \sigma E$ increases faster than according to the linear law. In particular, in Ge and Si the current saturation is replaced by its non-trapped growth, and in GaAs, InP, CdTe the current-voltage characteristic takes on a $N$-shaped form (Fig. 3); at $0 < E < E_a$ Ohm's law is satisfied, in the interval $E_a < E < E_b$ there is a falling section caused by a decrease in $\tau$ and an increase in $m^*$ in a strong electric field, and finally, in the region $E > E_b$ there is a rapid increase in $j$ due to an increase in $n$.

Gunn effect

The presence of a falling section in the current-voltage characteristic leads to an interesting phenomenon discovered by the American engineer John Gunn.

Let us apply a direction $U_0$ to a GaAs sample of length $L$ such that it ends up in the falling portion of the dependence $j(E)$. Let us assume that at first the electric field in the sample is uniform and equal to $U_0/L$. Let for some reason in the thin layer $AB$ of the sample the field $E$ turns out to be slightly larger than in the rest of the sample volume (Fig. 4). Then the drift speed of electrons $u = j/en$ inside the layer $AB$ turns out to be less than outside. Therefore, more electrons will flow to the $A$ boundary than fly away from it, and at the $B$ boundaries there will be a positive electron flow. Consequently, an additional electric field will appear in layer $AB$, directed in the same direction as the original one. Increase

⟦folio 7⟧

A decrease in the field will lead to the fact that the effective speed of the electron inside the layer will further decrease, and the field there will increase even more.

Thus, a uniform distribution of the electric field in the incident section $j(E)$ is impossible: any inhomogeneity $E$, however weak, that accidentally appears in the sample does not resolve, but grows. As a result, a narrow region (size $\delta$) of a strong field is formed, which is called an electric domain. In this case, since the voltage $U_0$ on the sample is specified, i.e.

$$E_2\delta + E_1(L-\delta) = U_0 = \text{const},$$

an increase in the field $E_2$ in the resistance domain by a decrease in the field $E_1$ outside it. There will come a moment when $E_1 < E_a$ and $E_2 > E_b$ (see Fig. 3). The operating speed inside the domain begins to decrease, and the internal speed begins to increase. The growth of the field $E_2$ in the domain will stop when these rates become equal, and the current densities in the domain and in the sample become the same:

$$j(E_1) = j(E_2) = j_0.$$

From the last two equalities it follows that the current density $j_0$ established in the sample depends on the thickness of the domain $\delta$.

Typically, a domain arises near the anode (due to the melting of contacts there are large inhomogeneities here) and, carried away by the flow of electricity inside, begins to move towards the anode with a speed of $u_0 = j_0/en$. While it moves along the sample, its size does not change, which means that the current $j_0$ does not change either. Near the anode, the domain begins to disappear, its thickness decreases, and the current in the sample increases. However, the $E_1$ field outside the domain is temporarily increased. As soon as

$$E_1$$ reaches the value $E_a$, at which a new domain is born, the current begins to decrease, and this cerpodic process is repeated (Fig. 5). The period of the bulb current in the sample is $T_0 = L/u_0$.

So, by applying a constant voltage $U_0$ to a semiconductor, we obtain an alternating current of frequency $f = 1/T_0 = u_0/L$. This is completely different from Ohm's law. In galley arsenide (GaAs) $u_0 \approx 10^5$ m/s. Using small samples ranging from one to stapicron in length, it is possible to vary the frequency of alternating current in the range of $f \sim 10^9 - 10^{11}$ Hz. Most modern ultrahigh frequency (microwave) generators operate based on the Gunn effect. These devices are used, for example, to determine the constant speed of automatic movement and in television broadcasting through artificial Earth satellites.

**Violation of Ohm's Law**

at high currents

Until now, we have considered the movement of electrons inside under the influence of only an electric field. However, it is known that the current flowing through a conductor is a source of a magnetic field. a magnetic field will arise not only outside, but also inside the conductor. For example, near the surface of a straight wire with a diameter of $d = 1$ mm at a current of $I = 10$ A, a magnetic field of $B = 4\mu_0I/d \approx 0,012$ T will arise ($\mu_0 = 4 \cdot 10^{-7}$ B·s/(A·m) – magnetic constant). The magnetic field of the current can cause a violation of Ohm's law.

An electron moving in a magnetic field is acted upon by the Lorentz force,

⟦folio 8⟧

Fig. 6.
bending its trajectory. If the field induction $\vec{B}$ is perpendicular to the speed $\vec{v}$ of the electron, then the electron’s trajectory will be a circle of radius $r=m^*v/eB$. If the angle between vectors $\vec{B}$ and $\vec{v}$ is equal to $\alpha$, then the electron will move along a spiral, the diameter of which is $d=2(m^*v/eB)\sin \alpha$, singing one turn of the spiral in time $T=2\pi m^*/eB$.

In a conductor, the movement of an electron in a spiral is possible if the free run time is $\tau \gg T$ (Fig. 6, a). In this case, the diameter of the spiral $d<vT$ is many times smaller than the distance $l=v\tau$ over which the electron will mix in time $\tau$ in the absence of a magnetic field (Fig. 6, b). Therefore, during time $\tau$ the electron appears to be locked in a tube with diameter $d$. As a result, the resistance of the conductor in a magnetic field is greater than at $B=0$. The dependence of resistance $R$ on the magnetic field created by the “own” current, thus leads to a violation of Ohm’s law.

If $\tau \ll T$, then between two successive collisions the electron motion differs little from rectilinear (Fig. 6, s); The magnetic field is practically no less than the resistance of the conductor.

The magnetic field induction $B_0$, from which the field influence becomes significant, is found from

Fig. 7.

conditions for the equality of the period of revolution of an electron in a circular orbit $T=2\pi m^*/eB_0$ free beta times $\tau: B_0=2\pi m^*/e\tau$. For GaAs $m^*=0,06$ $m_e$ and $\tau \sim 10^{-13}$ s, so $B_0 \approx 3$ T. It is practically impossible to create such a field by passing current through a semiconductor. At very low currents, the sample will be destroyed. A metal that has a very high conductivity can carry much more current. In addition, in pure metals cooled to the temperature of a liquid gel (about 4 K), the time $\tau$ can reach a value of $\sim 10^{-9}$ s, significantly longer than in semiconductors. Therefore, in metals the field $B_0$ is small - about 0.01 T. This is an example of the kind of field that occurs in a conductor with a diameter of 1 mm at a current of 10 A.

figure 7 shows the obtained experimental dependence of the resistance $R$ of a metal conductor on the current value $I$ at gel temperature. It can be seen that as the current increases, the resistance increases several times. The electric field in this experiment was less than $10^2$ V/m, which is much less than those fields $E$ in which deviations from Ohm's law are observed in semiconductors. Thus, the influence of the magnetic field of the current on the resistance is in this case the main reason for the violation of Ohm’s law.

***

We have looked at the physical principles that can lead to violation of Ohm's law in conductors. At the same time, the most important unobtained effects in conductors located in alternating electric and magnetic fields were not mentioned... But “no one will embrace the immensity.”
