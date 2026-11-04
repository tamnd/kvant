---
id: 2024-1-esin-mezhdunarodnaya-fizicheskaya-olimpiada-1b2f7772
issue: kvant_2024_1
year: 2024
number: "1"
title: International Physics Olympiad
authors:
  - Есин М.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 43
page_last: 49
page_labels: 41, 42, 44, 45, 47
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9b13c8225a7560824097b45a2321f35d2826e5a5f5670126383398f0b2830816
prompt_sha256: draft-1
translated_from: content/ru/2024/01/articles/07_esin-mezhdunarodnaya-fizicheskaya-olimpiada-1b2f7772.md
source_content_sha256: c278d2b54e3e292c6fb50cf6e7786b4eda5282fefae5019b4b9179e414b38b00
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio 41⟧

---
running_head:
folio:
---

International
physical olympiad

From July 10 to July 17, 2023, the 53rd International Olympiad was held in Tokyo (Japan)
schoolchildren in physics (IPhO-2023). In this most representative world of state among
Secondary school students were received from more than 80 countries. The Russian team performed under
the Olympic flag, i.e. as a team of individual participants.
Russia was represented by five schoolchildren who passed multi-story tests and
successfully performed at national and international competitions and selections:

Vyacheslav Bobkov – Moscow, school 1589,
Roman Burtsev – Moscow region,
Physico-technical person named after P.L.Ka-
pizza,
Vsevolod Dolya – Moscow region,
Physico-technical person named after P.L.Ka-
pizza,
Alexander Erisov – Moscow region,
Physico-technical person named after P.L.Ka-
pizza,
Egor Pomanov – Moscow, Center School
pedagogical skill.

The Russian team traditionally showed
highest result and won five
gold medals.
Below are the conditions for problems of the theoretical type of the Olympiad.

From left to right: A. Ershov, V. Dollya, R. Burtsev, V. Bobkov,
E.Potapov

Theoretical tour

Task 1. Properties of column particles
(10 points)

The science of column systems is useful for
determining the properties of soil particles, since
the main part of them can be considered
like column micrometer particles
size. For example, Brownian motion
(random movements of column particles)
can be used to measure
particle size.

Part A. Movement of column particles
(1.6 points)

Let us consider the one-dimensional Brownian motion of a column particle with mass M. The equation of motion for the particle velocity v(t)
looks like this:

$$Mv' = -\gamma v(t) + F(t) + F_{\text{ВН}}(t),$$

where γ is a coefficient characterizing
resistance, F(t) – force arising
due to random collisions with molecules
water, $F_{\text{ВН}}(t)$ – external force. In part A we will
assume that $F_{\text{ВН}}(t) = 0$.

A1. Let us consider the situation when the molecule
la water encounters a particle at the moment
time t = t₀ and transmits impulse I₀. After
event F(t) = 0. If before the event v(t) = 0, then after the event v(t) = $v_0 e^{-(t-t_0)/\tau}$ for time t > t₀. Find v₀
and τ, using I₀ and the necessary parameters
from expression (1).

In the next paragraph you can express
answers via τ.

A2. There's actually a lot going on
collisions of water molecules with particles, one
after another. Collision with number i of transmission
e pulse I_i and occurs at the moment of time

⟦folio 42⟧

---
running_head:
folio:
---

$t_i$. Find $v(t)$ given that $v(0) = 0$. Explicitly state the inequality for $t_i$ that must hold for a given $t$. In the form of answers, it is not necessary to indicate this range in the expression for $v(t)$.

Part B. Effective equation of motion (1.8 points)

Previous results show that the particle velocities $v(t)$ and $v(t')$ can be treated as undefined random variables under the condition $|t - t'| \gg \tau$. Based on this, to describe one-dimensional Brownian motion, we can propose a model of random changes in speed in each time interval $\delta(\gg \tau)$, i.e.

$$v(t) = v_n (t_{n-1} < t \leq t_n),$$

where $t_n = n\delta (n = 0, 1, 2, \dots)$ and $v_n$ are random variables. This random variable satisfies the condition

$$\langle v_n \rangle = 0, \langle v_n v_m \rangle = \begin{cases} C (n = m), \\ 0 (n \neq m), \end{cases}$$

where parameter $C$ depends on $\delta$. Here $\langle X \rangle$ denotes the average value of quantity $X$. In other words, if you sample a random value $X$ an infinite number of times, then the average value of this sample will be $\langle X \rangle$.

Let us consider the change of particle $\Delta x(t) = x(t) - x(0)$ for $t = N\delta$, where $N$ is some integer.

B1. Find $\langle \Delta x(t) \rangle$ and $\langle \Delta x(t)^2 \rangle$ and express the results in terms of $C$, $\delta$, and $t$.

B2. The value $\langle \Delta x(t)^2 \rangle$ is called the root-mean-square shift. This quantity is observed in the case of Brownian motion and in the limiting case $\delta \rightarrow 0$. It can be shown that $C \propto \delta^\alpha$ and $\langle \Delta x(t)^2 \rangle \propto t^\beta$. Find the numerical values ​​of $\alpha$ and $\beta$.

Part C. Electrophoresis (2.7 points)

Electrophoresis is the transfer of charged parts in an electric field. A suspended block part with mass $M$ and charge $Q (>0)$ is placed in a narrow channel with cross section $A$ (Fig. 1,a). We are concerned with the interaction between particles, the influence of walls, liquid and ions in it, as well as gravity.

If we apply a one-dimensional electric field with intensity $E$ in the direction $a$,

$x$, the particles move and their concentration $n(x)$ (the number of parts per unit volume) becomes non-uniform (Fig. 1,b). If the electric field $E$ is then removed, then the heterogeneity disappears over time. This is due to the Brownian motion of the part. If $n(x)$ is not one-dimensional, then the number of parts moving from left to right and from right to left differ (Fig. 1,c). This results in the presence of part flux $J_D(x)$. The last quantity is the average number of parts that have a coordinate $x$ and move along the axis $x$, divided by the cross-sectional area and the time interval. The flow satisfies the relation

$$J_D(x) = -D \frac{dn}{dx}(x),$$

where $D$ is the diffusion coefficient.

For simplicity, let's assume that one half of the piece has speed $+v$ and the other half has speed $-v$. Let $N_+ (x_0) -$ be the number of parts having speed $+v$ that cross the plane $x_0$ from left to right through a unit area per unit time. Particles with speed $+v$ that cross the plane $x_0$ during the time interval $\delta$ are in the dark region (see Fig. 1,c). Since the value of $\delta$ is small, we obtain that $n(x) \approx n(x_0) + (x - x_0) \frac{dn}{dx}(x_0)$ is in this region.

C1. Find $N_+ (x_0)$, express in terms of $v$, $\delta$, $n(x_0)$ and $\frac{dn}{dx}(x_0)$.

Let us define $N_- (x_0)$ by analogy with $N_+ (x_0)$ for speeds $-v$. Then the full flow is $J_D(x_0) = \langle N_+ (x_0) - N_- (x_0) \rangle$. According to expression (2), $\langle v^2 \rangle = C$.

⟦folio 44⟧

---
running_head:
folio:
---

Fig. 4. a) Movement of a floating microbe, b) one-dimensional movement of a microbe

change occurs. Draw a qualitative graph of the average variational mixture versus time in logarithmic coordinates. Mark the position $t_*$ on it.

Let us now consider a floating microbe (Fig. 4,a). For simplicity, we will use one-dimensional motion (Fig. 4,b). We assume that these are spherical particles with radius $a$. The microbe swims at a speed of either $+u_0$ or $-u_0$, the sign is chosen randomly after a time interval of $\delta_0$, there is no correlation. The observed movement is a combination of mixing due to active movement of the microbe and mixing due to Brownian motion.

D3. Figure 5 illustrates the average mixture of $\left\langle \Delta x(t)^2 \right\rangle$ microbes. For small, large and in-between $t$

Fig. 5. Medium mixture of microbe
different power laws are satisfied. Put these expressions for each range. Express the expressions in terms of $D, u_0, \delta_0$ and $t$.

Part E. Water purification (1.5 points)

This part discusses the purification of water from soil particles by adding electrolytes for the purpose of coagulation (sticking together). Soil particles interact with each other using van der Waals sily and electrostatic sily. The latter take into account both the surface charges and the surrounding charges of the opposite

Fig. 6. a) Surface charge of a colluded particle and opposites, b) determination of distance $d$

sign (such charges are called opposites, and the resulting layer of charges is a double electric layer (Fig. 6,a)). As a result, the potential energy of interaction between particles at a distance $d$ (Fig. 6,b) is equal to

$$U(d) = -\frac{A}{d} + \frac{B\varepsilon(kT)^2}{q^2} e^{-d/\lambda},$$

where $A$ and $B$ are positive constants, $\varepsilon$ is the dielectric capacity of water, $\lambda$ is the thickness of the electrical double layer. Assuming that the ion charges are $\pm q$, the expression is true

$$\lambda = \sqrt{\frac{\varepsilon kT}{2N_A q^2 c}},$$

where $c$ is the molar concentration of ions.

E1. Addition of sodium chloride (NaCl) to the suspension causes coagulation of the kolyud particles. Determine the minimum NaCl concentration required for coagulation. It is enough to consider two particles in the absence of thermal fluctuations, i.e. $F(t) = 0$ into the equations of motion (1). Consider that instantaneous is sufficient for a given potential concentration.

Problem 2. Neutron stars (10 points)

We will discuss the stability of heavy nuclei and estimate the mass of neutron stars theoretically and from experimental data.

Part A. Mass and stability of nuclei (2.5 points)

The rest energy $m(Z,N)c^2$ of a nucleus consisting of $Z$ protons and $N$ neutrons is less than the rest energy of protons and neutrons, we will further call them nucleons, by the binding energy $B(Z,N)$. Here $c$ is the speed of light in vacuum. Ignoring small corrections, we can approximate the binding energy by the sum of the volume contribution with a coefficient of $a_V$, the surface contribution with a coefficient of $a_S$, the power plant (Coulomb) energy

⟦folio 45⟧

---
running_head:
folio:
---

gini with coefficient $a_K$ and symmetrical
term with coefficient $a_{\text{сим}}$ follows
in a general way:

$$m(Z,N)c^2 = Am_Nc^2 - B(Z,N),$$
$$B(Z,N) = a_VA - a_SA^{2/3} -$$
$$-a_K \frac{Z^2}{A^{1/3}} - a_{\text{сим}} \frac{(N-Z)^2}{A},$$

where $A = Z + N$ – mass number, $m_N$ – mass
nucleon. When calculating, use
$a_V \approx 15,8$ MeV, $a_S \approx 17,8$ MeV, $a_K \approx 0,711$ MeV
and $a_{\text{сим}} \approx 23,7$ MeV ($1$ MeV $= 10^6$ electron-
volt).

A1. Given the condition $Z = N$, determine the values ​​of $A$ at which the binding energy per one
nucleon $B/A$ maximum.

A2. If $A$ is constant, the charge number
the most stable atom $Z^*$ can be determined by maximizing $B(Z,A-Z)$. At $A = 197$
calculate $Z^*$ using equation (*).

A3. A kernel with a large $A$ can split into lighter kernels to minimize
the promising energy of peace. For simplicity, we will consider only one method of division, with
in which a kernel with parameters $(Z,N)$ splits into two identical nuclei $(Z/2,N/2)$. This
possible if the following relationship between energies is satisfied:

$$m(Z,N)c^2 > 2m(Z/2,N/2)c^2.$$

Let this correspondence be written in the form

$$Z^2/A > C_{\text{дел}} \frac{a_S}{a_K},$$

get $C_{\text{дел}}$ with two digit values.

Part B. Neutron star as a giant nucleus (1.5 points)

Very heavy nuclei with mass number $A > A_\pi$, where $A_\pi$ is the threshold value, can remain stable relative to
falls at a sufficiently high gravitational binding energy.

B1. We will assume that $N = A$ and $Z = 0$ for
sufficiently large $A$ and that equation (*)
continues to execute if added to
it gravitational binding energy. The gravitational binding energy is equal to

$$B_{\text{грав}} = \frac{3}{5} \frac{GM^2}{r},$$

where $M = m_N A$ is the mass of the nucleus, $r = r_0 A^{1/3}$ with coefficient
factor $r_0 \approx 1,1 \cdot 10^{-15}$ m = 1.1 fm – radius

kernels. For the gravitational binding energy $B_{\text{грав}} = a_{\text{грав}} A^{5/3}$, obtain the coefficient $a_{\text{грав}}$ in MeV with one significant digit. Then,
Ignoring the surface contribution to energy, evaluate $A_\pi$ to one significant figure. When calculating, use $m_N c^2 \approx 939$MeV and
$G = \hbar c/M^2$, where $M_p c^2 \approx 1,22 \cdot 10^{22}$ MeV and $\hbar c \approx 197$ MeV fm.

Part C. Neutron star in binary
system (6.0 points)

Some neutron stars are
pulsarms emitting electromagnetic waves, which we will, for simplicity,
call it light, with a constant period. Neutron stars often form binaries
systems with white dwarfs. Consider the configuration of stars shown in figure 7. Pulse of light from a neutron star $N$

Fig. 7. Configuration with x-axis along the line,
connecting N and E, a) for $x_N < 0$ and b) for
$x_N > 0$

moves towards Earth E and passes mismo white
W dwarf in a binary system. Wires
measurements with these pulses can be accurately
determine the mass W, as explained
further, with which you can evaluate
mass N.

C1. As shown in figure 8, we place
two identical stationary clocks in positions I and II, let's call them clock-I and clock-II,
the height difference of these clocks is $\Delta h(>0)$, the acceleration of gravity $g$ is constant. Also
We will consider the same freely falling clock-F. We will assume that from
Initially observe is with clock-F and
located on the same
the same height as the clock-I, its
initial speed is
zero. Since the clock
are the same, when changed they give the same
time intervals $\Delta t_F = \Delta t_I$. Then watch-F
begin to fall freely. We will work in freedom

⟦folio 47⟧

---
running_head:
folio:
---

Fig. 11. Observed time dependence
for gravitational waves

dependence of gravitational waves on times
before the collision of two stars. Select the most suitable dependency from
a) - d).

Task 3. Water and objects (10 points)
In this problem we will consider phenomena caused by the interaction of water and objects associated with the surface by tension. Part A studies movement, and parts B and C deal with statics. If necessary, you can use the fact that if the function $y(x)$ satisfies the differential equation $y''(x) = ay(x)$ (a is a positive constant), then the general solution to this equation will be $y(x) = Ae^{\sqrt{ax}} + be^{-\sqrt{ax}}$, where $A$ and $B$ are arbitrary constants.

Part A. Merging water droplets (2.0 points)
As shown in figure 12, we consider two Stationary spherical drops

Fig. 12. Merging of two drops of water and bouncing of a split drop
whether there is water on the surface of a completely non-wettable material. Initially, a row of two spherical drops of water with equal radii are placed on the surface; then these two drops merge after touching each other and form a large spherical drop of water, which suddenly jumps.

A1. The radii $a$ of both water drops before merging are equal to 100 µm. The density of water $ρ$ is $1,00 \cdot 10^3$ kg/m³. The surface tension coefficient $σ$ is equal to $7,27 \cdot 10^{-2}$ J/m². The $k$ fraction of $\Delta E$ (surface energy change) is converted to kinetic energy

the sound of a bouncing drop of water. Determine the initial bouncing velocity $v$ of the merged drop of water to within two significant figures at $k = 0,06$. During the merging process, the volume of water does not change.

Part B: Vertical Plate (4.5 points)
A flat vertical plate is immersed in water. figure 13 shows the shapes of the water surface in the case of wetted and

Fig. 13. Vertical immersed plates: a) wetted plate, b) non-wetted plate

non-wetted plates. Ignore the thickness of the plate. The surface of the plate coincides with the plane $yz$, and the horizontal surface of the water far from the plate coincides with the plane $xy$. The shape of the surface does not depend on the coordinate $y$. Let $\theta(x)$ be the angle between the water surface and the horizontal plane at point $(x,z)$ on the water surface in the $xz$ plane. Here $\theta(x)$ changes with respect to the positive direction of axis $x$ and counterclockwise rotation is considered positive. Let $\theta(x)$ be equal to $\theta_0$ at the point of contact of the plate with the water surface ($x=0$). Further, $\theta_0$ does not change due to the properties of the plate materials. The density of water $ρ$ is constant and the surface tension coefficient $σ$ is the same. The acceleration of free pressure is denoted by $g$. Atmospheric pressure $p_0$ is assumed to always remain constant. Let's determine the shape of the water surface in several steps. Note that the surface tension coefficient is in J/m² or N/m.

B1. Wetted plate distance (see Fig. 13,a). Atmospheric pressure $p_0$ is always considered constant. Note that the water pressure $p$ satisfies inequalities $p < p_0$ for $z > 0$ and $p = p_0$ for $z = 0$. Express $p$ from $z$ through $ρ$, $g$, $z$, and $p_0$.
