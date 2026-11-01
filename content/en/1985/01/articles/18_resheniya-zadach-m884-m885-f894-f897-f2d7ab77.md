---
id: 1985-1-resheniya-zadach-m884-m885-f894-f897-f2d7ab77
issue: kvant_1985_1
year: 1985
number: "1"
title: Solutions to problems M884, M885; F894—F897
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 47
page_last: 52
page_labels: 45-50
tag: UR8E
lang: en
source: kvant_digital
extraction: vision
content_sha256: f3383c350d49bda34fb2a6fc1697ea7a5640ff928be0204d4d27616edfd5d96c
prompt_sha256: draft-1
translated_from: content/ru/1985/01/articles/18_resheniya-zadach-m884-m885-f894-f897-f2d7ab77.md
source_content_sha256: 5e7d673b062898cb85afa82ef515fc654c726eb2fc15769cea185b3c55bfb476
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

mirror, the lens and the object are enclosed in a case made of translucent plastic (Fig. 2). This system generates two images of the object and an image of the lens. Both images of the object have the same size, independently of the distance between the lens and the object. What is the enlargement of the lens' image?

E. P. Kuznetsov

Problem solutions

M884, M885; F894—F897

The solution is based on the following consideration: if $A(a; f(a))$ and $B(b; f(b))$ are two points on the graph of the function (Fig. 1), then the rectangle $\Pi(A, B)$ with diagonal $AB$ covers the graph section from $A$ to $B$, and its area $S$ satisfies the inequality $2\sqrt{S} \leq l+h$, where $l=b-a$ is the length of its base, and $h=f(b)-f(a)$ is its height; this inequality is essentially an inequality about the argumentative mean and the geometric mean $\sqrt{lh} \leq (l+h)/2$.

This consideration can be used in two ways. Let us temporarily assume that $f(0) = 0$, $f(1) = 1$.

1) Let us extend the function $f$ to the entire positive value so that it remains continuous and monotonic (for example, we can put $f(x) = x$ with $x > 1$). Let $A_0$ be the starting point of the graph (with coordinates $(0; 0)$). Let us also consider the points $A_1, ..., A_m$ on the graph, so that the area of ​​the rectangle $\Pi(A_{i-1}; A_i)$, $i=1, 2, ..., n$ is equal to $1/n^2$; the existence of such points obviously follows from the continuity and monotonicity of the functions $f$. For each of these rectangles, the sum of the length of the base and the height is not less than $2\sqrt{1/n^2}=2/n$, therefore the sum of the coordinates of the point $A_n$ (equal, corresponding to the sum of the length of the bases of all rectangles and the sum of their heights) is not less than 2. Consequently, at least one of these coordinates is not less than 1, which means that the constructed $n$ rectangles cover the graph.

2) Let us select points $B_0, B_1, ..., B_n$ on the graph of the function $f$, starting from $B_0$ $(0; 0)$, so that the sum of the length of the base and the height of each of the rectangles $\Pi(B_{i-1}, B_i)$, $i=1, ..., n$ is equal to $2/n$. (It is easy to see that $B_i$ is the point of intersection of the line $y=2i/n-x$ with the graph, in particular, $B_n$ is the end of the graph - point $(1; 1)$; see Fig. 2.) By virtue of the above estimate, the area of ​​each of the rectangles does not exceed $1/n^2$. Enlarging them if necessary so that their areas are exactly equal

⟦folio 46⟧

1/n², we get the required coverage.

If f(0) > 0 or f(1) < 1, we supplement the graph with vertical segments connecting the point (0; 0) with its beginning (0; f(0)) and (1; 1) with the end (1; f(1)) (Fig. 3). You will get a continuous curve connecting the points (0; 0) and (1; 1), to which both of the above explanations can be applied practically without changes.

The same example allows us to state the problem for any (possibly discontinuous) function f: at discontinuity points, the graph is complemented to a continuous curve by a segment (red segment at figure 4). However, a strict justification in this case is somewhat beyond the scope of the school curriculum.

N. B. Vasiliev,
V. N. Dubrovsky,
S. Yu. Orevkov

**M885*. For each natural number n, we denote by p(n) the number of partitions of n into the sum of natural summands (partitions that differ only in the order of the summands are considered identical). The collection of partitions of numbers in a given partition is called its parsing.

a) Prove that the sum q(n) of the spreads of all partitions of the number n is equal to 1 + p(1) + p(2) + ... + p(n-1).

b) Prove that this sum is not greater than √2n p(n).

4-4
4-3+1 ↔ 1-1
4-2+2 ↔ 2-2
4-2+1+1 ↔ 2-1+1
4-1+3 ↔ 3-3
4-1+2+1 ↔ 3-2+1
4-1+1+1+1 ↔ 3-1+1+1

a) The division of the number n into the sum of natural terms will be called displaced if one of the terms is isolated from the rest (underlined); We will consider the displaced partitions, which are excellent only in the order of the subdivisions, to be identical. (On figure on the left are all offset partitions of the number 4; the highlighted ones are shown in red.) Note that if k is the spread of some partition (unoffset), then k offset partitions can be obtained from this partition. Therefore, the total number of offset partitions of n is equal to q(n). On the other hand, if from any eliminated partition, except the partition consisting of a single element, the underline element is removed, the result will be a partition of a certain number less than n. And vice versa, if m < n, then from any partition of the number m one can unambiguously restore the offset partition of the number n: it is necessary to add the summand n-m to the partition of the number m and underline it (in figure there is a one-to-one correspondence between the offset partitions of the number 4, except for the partition 4 = 4, and partitions of numbers less than 4). But the number of partitions of numbers less than n is equal to p(1) + p(2) + ... + p(n-1). Therefore, q(n) - 1 = p(1) + p(2) + ... + p(n-1).

In other words, the idea of ​​this solution can be stated as follows: if we add one term n-m to each of p(1) + p(2) + ... + p(n-1) partitions of the numbers m = 1, 2, ..., n-1, then we will get each partition of the number n (except for trival n=n) as many times as its spread.

6) It is enough to prove that the spread of any partition of the number n into the sum of natural summands does not exceed √2n. Let's prove this statement. Let a₁, ..., aₙ be all distinct terms included in some partition (with parsing k), and 0 < a₁ < ... < aₙ. Then, on the one hand,

⟦folio 47⟧

$$a_1 + a_2 + \dots + a_k \leq n, \text{ а, с другой стороны, } a_1 \geq 1, \quad a_2 \geq 2, \quad \dots, \quad a_k \geq k \quad (\text{действительно, } a_1 \geq 1; \quad a_2 > a_1 \geq 1, \quad \text{следовательно, } a_2 \geq 2; \quad a_3 > a_2 \geq 2, \quad \text{следовательно, } a_3 \geq 3, \quad \text{и т. д.}).$$
Therefore $n \geq a_1 + a_2 + \dots + a_k \geq 1 + 2 + \dots + k = k(k+1)/2 \geq k^2/2$, that is $k \leq \sqrt{2n}$.

S. Yu. Orevkov

F894. In one of the projects, it is planned to use a solar sail with an area of ​​$S=1$ km$^2$ for spacecraft flights in the Solar System. The sail unfolds as the vehicle moves around the Sun in Earth's orbit, the radius of which is $R_3=1,5\cdot 01^8$ km. With further movement, the sail is constantly oriented perpendicular to the sun's rays, the pressure of which in the earth's orbit is $p=10^{-5}$ Pa.
1) At what mass of the spacecraft can it fly away from the Solar System?
2) At what maximum mass can the vehicle reach the orbit of Mars, whose radius is $R_M=2,3\cdot 10^8$ km? The gravitational influence of the Earth and other planets is not taken into account.
The product of the mass of the Sun and the gravitational constant $M_C G=1,3\cdot 10^{11}$ km$^3/c^2$.

◆ When the solar sail is deployed, the solar tension force and the pressure force of the sun's rays act on the apparatus. Evaluating the result of these schemas -

$$F_{\varphi} = G \frac{M_C m}{R_3^2} - p S = G \frac{M_C m}{R_3^2} - \frac{G m R_3^2 p S}{G m R_3^2} = G \frac{(M_C - p SR_3^2/G m) m}{R_3^2}.$$

We see that the pressure of the sun's rays seems to reduce the strength of the device's tension towards the Sun - this force turns out to be the same as if the Sun had not a mass $M_C$, but a slightly smaller effective mass equal to

$$M_{\varphi} = M_C - \frac{p SR_3^2}{G m}.$$

Using the introduced effective mass, we can further solve the problem without taking into account the pressure of solar rays.

Total energy of a spacecraft in the boundary field of a body with mass $M_{\varphi}$ —

$$E = \frac{mv^2}{2} - G \frac{m M_{\varphi}}{R}.$$

According to the law of conservation of energy, this energy at any point in the spacecraft’s orbit should be equal to

$$E = \frac{mv^2}{2} - G \frac{m M_{\varphi}}{R_3},$$

where $v_3$ is the speed that the vehicle had at the moment of opening the sail at a distance $R_3$ from the Sun. We will find this speed from the equation of motion of the apparatus in the Earth's orbit under the influence of the force of the Sun:

$$\frac{mv^2}{R_3} = G \frac{m M_C}{R_3^2} \Rightarrow v_3 = \sqrt{G \frac{M_C}{R_3}}.$$

Thus,

$$E = G \frac{m}{R_3} \left( \frac{M_C}{2} - M_{\varphi} \right) = G \frac{m}{R_3} \left( \frac{p SR_3^2}{G m} - \frac{M_C}{2} \right).$$

The device can fly away from the solar system if $E \geq 0$, that is, provided

$$\frac{p SR_3^2}{G m} - \frac{M_C}{2} \geq 0.$$

From here the apparatus is located

⟦folio 48⟧

Maybe:

$$m \leq \frac{2pSR_3^2}{GM_C} \approx 3,46 \cdot 10^3 \text{ кг.}$$

With a larger mass, the device will move in closed orbits.

Let the orbit of the apparatus touch the orbit of Mars for a certain mass $m_1$. (Of all possible masses $m$, at which the apparatus reaches the orbit of Mars (crosses it), $m_1$ is the maximum.) In this case, the orbit of the apparatus is an ellipse, the major axis of which is equal to $R_3+R_M$ (see figure). At the points of contact, the speed of the vehicle is perpendicular to the radius vector of the vehicle.

According to the law of conservation of energy

$$\frac{m_1v_3^2}{2} - G \frac{m_1M_3\phi}{R_3} = \frac{m_1v_2^2}{2} - G \frac{m_1M_3\phi}{R_M} \Rightarrow v_3^2 - v_M^2 = 2GM_3\phi \left( \frac{1}{R_3} - \frac{1}{R_M} \right).$$

According to Kepler's second law

$$v_3R_3 = v_MR_M \Rightarrow v_M = v_3 \frac{R_3}{R_M}.$$

Substituting this expression for $v_M$ into (*) and taking into account that $v_3 = \sqrt{G \frac{M_C}{R_3}}$, after several transformations we obtain:

$$2M_3\phi R_M = M_C(R_M + R_3),$$

or

$$2 \left( M_C - \frac{pSR_3}{Gm} \right) R_M = M_C(R_M + R_3).$$

From here we find the maximum mass $m_1$ of the device at which the device can reach the orbit of Mars

$$m_1 = \frac{2pSR_3^2}{GM_C} \frac{R_M}{R_M-R_3} \approx 10^4 \text{ кг.}$$

V. A. Danilin

F895. One of the legends about the origin of the asteroid belt goes back to the ancient Rechensk legend about the son of the sun Gelyus - Phaethon, struck by Zeus (Jupiter). According to this theory, a swarm of stone swarms, from which the planet Fazton was supposed to form, came very close to Jupiter. Under the influence of Jupiter's gateway swarm, the swarm split into separate swarms - asteroids. The swarm radius was estimated to be approximately 10⁴ km; the mass of the swarm (total mass of asteroids) is 10⁶ times less than the mass of Jupiter.

How far from the center of Jupiter would the swarm have to travel before it began to fall apart?

Let's look at the block closest to Jupiter. The collapse of the swarm means that the distance between this clump and the center of the swarm will increase.

The swarm as a whole falls on Jupiter with acceleration, which is imparted to it by the force of Jupiter’s attraction:

$$ma_1 = G \frac{mM}{R^2} \Rightarrow a_1 = G \frac{M}{R^2},$$

where $m$ is the mass of the swarm, $M$ is the mass of Jupiter, $R$ is the distance between the centers of the swarm and Jupiter. The block moves under the influence of the attractive force of Jupiter and the attractive force acting on it from the swarm as a whole. The acceleration with which the block moves towards Jupiter is

$$a_2 = G \frac{M}{(R-r)^2} - G \frac{m}{r^2};$$

where $r$ is the radius of the swarm. If $a_2 > a_1$, then the distance between the block and the center of the swarm will increase with time

⟦folio 49⟧

men - the swarm disintegrates. From this condition we get:

$$\frac{M}{(R-r)^2} - \frac{m}{r^2} > \frac{M}{R^2}.$$

Using $r < R$, we find:

$$\frac{2rM}{R^3} > \frac{m}{r^2} \Rightarrow R < r^3 \sqrt{\frac{2M}{m}} \approx 1,26 \cdot 10^6 \text{ км}.$$

V. E. Belonchkin

F896. In a closed vessel there is saturated water, steam at a temperature of 100 °C and the remaining water. Mass of steam $M = 100 \text{ г}$, mass of water $m = 1 \text{ г}$. The vessel is heated until all the water has evaporated. To what temperature should the vessel be heated? How much heat will this require? The pressure of saturated water vapor increases by 3.7 kPa with an increase in temperature of 1 °C. The specific heat of evaporation of water is $r = 2,25 \cdot 10^6$ J/kg, the specific heat of water steam is $c_V = 1,38 \cdot 10^3$ J/(kg K).

◆ Let us first determine to what temperature the vessel must be heated so that all the water evaporates.

Let us write the equation of state of steam under the initial conditions of water and steam in the vessel will be $p_2 + \Delta p$. According to the conditions of the problem $\Delta p = \alpha \cdot \Delta T$, where $\alpha = 3,7$ kPa/K. Taking advantage of this, we write the equation of state of steam at temperature $T_2$:

$$p_2 V = \frac{M + m}{\mu} RT_2,$$

or

$$(p_1 + \alpha \cdot \Delta T) V = \frac{M + m}{\mu} R (T_1 + \Delta T).$$

Solving (1) and (2) together, we find $\Delta T$:

$$\Delta T = \frac{m T p}{M T a - M p - m p} \approx 0,29 \text{ K}.$$

Thus, to evaporate all the water, the suud must be heated to a temperature of 100.20 °C. The amount of heat required for this can be found from the heat balance equation:

$$Q = r m + c_V (M + m) \cdot \Delta T \approx 2290 \text{ Дж}.$$

A. I. Buzdin

◆ Let us write down the equation of particle motion at points $A$ and $B$:

$$m a_A = q E_A, \quad m a_B = q E_B.$$

It follows that

$$\frac{a_A}{a_B} = \frac{E_A}{E_B},$$

that is, the ratio of particle accelerations at points $A$ and $B$ is equal to the ratio of the directional field created by the polyring at these points. On the other hand, from the conditions of the problem we actually know the relationship of the potential field at points $A$ and $B$. Indeed, according to the law of conservation of energy

$$\frac{m v_A^2}{2} = q \varphi_A, \quad \frac{m v_B^2}{2} = q \varphi_B$$

(since at infinity the particle energy is zero), and

⟦folio 50⟧

$$\frac{\varphi_A}{\varphi_B} = \frac{v_A^2}{v_B^2} = n^2.$$

Let's try to express the relation $E_A/E_B$ through the known relation $\varphi_A/\varphi_B$.

The volume was mentally divided into many elemental sections with a charge of $\Delta Q$ each ($Q$ is the charge of the entire half-ring). Let $\Delta \varphi_B$ and $\Delta E_B$ be, respectively, the potential and intensity of the field created at point $B$ by a section that is located at a distance $Q$ from this point (see figure). Then

$$\Delta \varphi_B = k \frac{\Delta Q}{\varphi} = k \frac{\Delta Q}{2r \cos \alpha}, \quad \Delta E_B = k \frac{\Delta Q}{\varphi^2} = k \frac{\Delta Q}{4r^2 \cos^2 \alpha}.$$

The projection of the vector $\vec{E}_B$ on the horizontal axis $x$ is equal to

$$\Delta E_{Bx} = \Delta E_B \cos \alpha = k \frac{\Delta Q}{4r^2 \cos \alpha} = \frac{\Delta \varphi_B}{2r}.$$

From the symmetry messages it is clear that the field strength $\vec{E}_B$ at point $B$ is directed along the $x$ axis. Consequently, the value $E_B$ is equal to the sum of the projections $\Delta E_{Bx}$ of the field strengths created by all elementary sections, that is

$$E_B = \sum \Delta E_{Bx} = \sum \frac{\Delta \varphi_B}{2r} = \frac{\varphi_B}{2r}.$$

Regarding the values ​​of $\varphi_A$ and $E_A$, then

$$\varphi_A = \frac{Q}{r}, \quad E_A = \frac{2Q}{\pi r^2} = \frac{2\varphi_A}{\pi r}$$

(get these matches yourself).

So, $E_A/E_B = 4\varphi_A/\pi\varphi_B$, and the ratio of particle accelerations at points $A$ and $B$ is equal to

$$\frac{a_A}{a_B} = \frac{4}{\pi} \frac{\varphi_A}{\varphi_B} = \frac{4}{\pi} n^2.$$

V. T. Karpetyan

**Top Quark and Top the Tiger**

(For the beginning, see p. 41)

it was possible to guess from the results of measurements of the momenta of all charged particles. Since the recorded event is associated with the decay of a practically stationary $W$-boson, the total momentum of all particles in the decay should be equal to zero. However, the measured momentum of charged particles turned out to be non-zero,

from which the conclusion was drawn about the presence of neutrinos.

Nibaulier's reliable decoding of the event in question is that during the collision of a proton with an antiproton, a part was born consisting of two quarks - the top quark $t$ and the beautiful antiquark $b$. The top quark decays according to the scheme

$$t \rightarrow b + \mu^+ + v$$

(here $\mu^+$ is a positive mu-meon), and $b$ and $b$ for two particle beams. Now we have to wait for the result.

The mass of the top quark was estimated to correspond to an energy of about 40 GeV (the mass of a calcium nucleus!).*) This, of course, is less than the mass of a tiger cub, even a newborn one, but in the “zoo of particles” the top quark is a record holder.

I'M WITH.

*) This estimate of the mass of the top quark is obtained if we assume that the mass of the ispilon meson is equal to the mass of two $b$-quarks (5 GeV + 5 GeV = 10 GeV), and the mass of the newborn (≈ 50 GeV) is equal to the mass of the $b$-quark and the top quark.
