---
id: 1971-2-resheniya-73f46c08
issue: kvant_1971_2
year: 1971
number: "2"
title: Solutions to problems M21—M25; F29—F34
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 28
page_last: 38
page_labels: 26, 28, 29, 30, 31, 32, 33, 34, 35, 36
tag: LMKE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5491921b0ed96247ffe1faeedd90240a088b008c92b74460a40d6d966ad886ef
prompt_sha256: draft-1
translated_from: content/ru/1971/02/articles/06_resheniya-73f46c08.md
source_content_sha256: 4c750e3bb793bea2025a71011190b5fc92d23ea716a0c687d0018f81521ab25a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

SOLUTIONS

In this section of the magazines we continue to publish solutions to problems from the puzzle «Kvant». Some of these problems are difficult even for mathematicians and physicists. Many of them give rise to a conversation about a whole class of problems, about methods of approaching certain phenomena. Each solution is a short separate article, and we recommend that you get acquainted with it even for those who have not tried to solve problems before.

In most cases, we indicate the names of the readers who sent us the most successful solutions, but, of course, we will not be able to answer everyone who sent us letters.

M21
Inside the square, on side 1, there are several circles, the sum of their lengths is 10. It is impossible to prove that there is a straight line. Then each point on side AB is covered by at most three projections of circles (Fig. 1), otherwise a line passing through the point and perpendicular to AB would intersect more than three circles. Consequently, the sum of all projections, that is, the sum of the lengths of the diameters of the circles, does not exceed 3; therefore, the sum of the lengths of the circles does not exceed 3π, while according to the condition it is equal to 10>3π. The resulting contradiction proves the statement of the problem.

This decision was added by D. Grigoriev from Leningrad and N. Rasshin from Moscow.

The following more general statement can be proven in the same way. Let us call the diameter of a convex figure the width of the narrowest strip in which this figure can be placed. (It can be shown that this definite is valid for any bounded figure.) Then, if inside a figure with diameter h there are n figures whose sum of diameters is greater than kh, then there is a straight line that intersects at least k + 1 of these figures.

⟦folio 28⟧

Let's rewrite the square of this expression as follows:

$$P_n^2 = \frac{1^2}{2^2} \cdot \frac{3^2}{4^2} \cdot \frac{5^2}{6^2} \cdot \dots \cdot \frac{(2n-1)^2}{(2n)^2} = \frac{1}{2} \cdot \frac{3^2}{2 \cdot 4} \cdot \frac{5^2}{4 \cdot 6} \cdot \dots \cdot \frac{(2n-1)^2}{(2n-2) \cdot 2n} \cdot \frac{1}{2n}.$$

Since for any integer $k > 1$

$$\frac{(2k-1)^2}{(2k-2) \cdot 2k} = \frac{(2k-1)^2}{(2k-1)^2 - 1} > 1,$$

That

$$P_n^2 > \frac{1}{2} \cdot \frac{1}{2n} \text{ и } P_n > \frac{\sqrt{2}}{2} \cdot \frac{1}{\sqrt{2n}}.$$

On the other hand, since always

$$\frac{(2k-1)(2k+1)}{(2k)^2} = \frac{(2k)^2 - 1}{(2k)^2} < 1,$$

That

$$P_n^2 = \frac{3}{2^2} \cdot \frac{3.5}{4^2} \cdot \frac{5.7}{6^2} \cdot \dots \cdot \frac{(2n-1)(2n-3)}{(2n-2)^2} \cdot \frac{2n-1}{(2n)^2} < \frac{3}{4} \cdot \frac{1}{2n} \text{ и}$$

$$P_n < \frac{\sqrt{3}}{2} \cdot \frac{1}{\sqrt{2n}}.$$

A slightly different solution was proposed by D. Gritsoriev (this solution was also leaked by other readers of the magazine). Let us consider together with this expression

$$P_n = \frac{1}{2} \cdot \frac{3}{4} \cdot \frac{5}{6} \cdot \dots \cdot \frac{2n-3}{2n-2} \cdot \frac{2n-1}{2n}$$

the following:

$$Q_n = \frac{1}{2} \cdot \frac{2}{3} \cdot \frac{4}{5} \cdot \dots \cdot \frac{2n-4}{2n-3} \cdot \frac{2n-2}{2n-1}.$$

Since each of the factors of the product $Q_n$ is not greater than the corresponding factor $P_n$, then $P_n > Q_n$ and, consequently, $P_n^2 > P_nQ_n = \frac{1}{4n}$, that is, $P_n > \frac{\sqrt{2}}{2} \cdot \frac{1}{\sqrt{2n}}.$

On the other side,

$$R_n = \frac{1}{2} \cdot \frac{4}{5} \cdot \frac{6}{7} \cdot \dots \cdot \frac{2n-2}{2n-1} \cdot 1 > P_n,$$

poseable $P_n^2 < P_nR_n = \frac{3}{8n}$ and $P_n < \frac{\sqrt{3}}{2} \cdot \frac{1}{\sqrt{2n}}.$

It would seem more natural to find $R_n$ not with 1/2, but with 2/3. But then for $P_n$ the result will be a rougher estimate than required in the conditions of the problem. On the contrary, if we leave in $R_n$ not one, but more factors equal to the first factors $P_n$, then for $P_n$ we get a more accurate estimate of the form $P_n < \frac{c}{\sqrt{n}}$, where $c$ is some number less than $\sqrt{\frac{3}{8}}$. The same remark applies to evaluation from the other side.

There is also a solution based on the method of mathematical induction. It was on the example of this problem that E. G. Nikolaev’s note “The Case with the Method of Mathematical Induction” (see «Kvant» No. 7, 1970, p. 37 and «Kvant» No. 12, 1970, p. 58) said that sometimes a stronger inequality is easier to prove by induction than a weaker one.

⟦folio 29⟧

From the proven inequalities it follows that the value $P_n$ tends to zero as $n$ increases, and the value $P_n \sqrt{n}$ lies between $\frac{1}{2}$ and $\frac{1}{2} \sqrt{\frac{3}{2}}$. It can be proven (see, for example, problems 145, 160, 161 in the book by A. M. Yaglom and I. M. Yaglom “Non-elementary problems in an elementary presentation”, GITTL, M., 1954) that as $n \to \infty$ $P_n$ tends to a limit equal to $\sqrt{\frac{1}{\pi}}$.

**M24**

Prove that any fraction $\frac{m}{n}$, where $0 < \frac{m}{n} < 1$, can be represented as

$$\frac{m}{n} = \frac{1}{q_1} + \frac{1}{q_2} + \frac{1}{q_3} + \dots + \frac{1}{q_r},$$

where $0 < q_1 < q_2 < \dots < q_r$ are integers and each $q_k$ ($k=2, 3, \dots, r$) is divisible by $q_{k-1}$.

Which fraction $\frac{m}{n}$ can be divided and the denominator by their most common divisor, replaced by an irreducible fraction equal to it. For example, $\frac{288}{504} = \frac{4.72}{7.72} = \frac{4}{7}$. In what follows we will consider only such irreducible fractions.

Let us prove the statement of the problem by induction on $m$. For $m=1$ it is obvious: the fraction $\frac{m}{n}$ itself already has the desired form. Now we will prove that if the statement of the problem is true for all fractions with numerators less than $m$, then it is also true for fractions with a numerator equal to $m$. Let $\frac{m}{n}$ be such a fraction ($1 < m < n$). Divide $n$ by $m$ with remainder; you get the quotient ($d_0-1$) and the remainder ($m-k$), that is

$$n = m (d_0-1) + (m-k) = md_0-k,$$

where $d_0 > 1$ and $0 < k < m$. Let's rewrite (1) like this: $md_0=n+k$, or

$$\frac{m}{n} = \frac{1}{d_0} \left( 1 + \frac{k}{n} \right).$$

Since $0 < k < m$, the fraction $\frac{k}{n}$ can be represented in the desired form:

$$\frac{k}{n} = \frac{1}{d_1} + \frac{1}{d_1 d_2} + \dots + \frac{1}{d_1 d_2 \dots d_r},$$

where $d_1, d_2, \dots, d_r$ are some natural numbers greater than 1. From (2) and (3) we get

$$\frac{m}{n} = \frac{1}{d_0} + \frac{1}{d_0 d_1} + \frac{1}{d_0 d_1 d_2} + \dots + \frac{1}{d_0 d_1 d_2 \dots d_r}.$$

The fraction $\frac{m}{n}$ is presented in the required form.

Note that from our solution to the problem it is not difficult to extract a simple algorithm - the rule of how to represent any given fraction as a sum (3). Let's demonstrate it with one example. Let us be given the fraction $\frac{5}{7}$:

$$7 = 2.5 - 3; \quad \frac{5}{7} = \frac{1}{2} \left( 1 + \frac{3}{7} \right);$$

$$7 = 3.3 - 2; \quad \frac{3}{7} = \frac{1}{3} \left( 1 + \frac{2}{7} \right);$$

$$7 = 4.2 - 1; \quad \frac{2}{7} = \frac{1}{4} \left( 1 + \frac{1}{7} \right).$$

⟦folio 30⟧

So,

$$\frac{5}{7} = \frac{1}{2} + \frac{1}{2.3} + \frac{1}{2.3.4} + \frac{1}{2.3.4.7} = \frac{1}{2} + \frac{1}{6} + \frac{1}{24} + \frac{1}{168}.$$

Of course, they can find several representations in the form (3), for example:

$$\frac{3}{8} = \frac{1}{4} + \frac{1}{8} = \frac{1}{3} + \frac{1}{24}.$$

The solution to this problem was sent by D. Gritsorye.

M25

In a set consisting of $n$ elements, $2^{n-1}$ subsets are selected, each three of which have a common element. Prove that all these subsets have a common element.

In total, in the set $A$, consisting of $n$ elements, there are $2^n$ different subsets, including the set and the set itself $A$ (see the article by N. Ya. Vilenkin “Combinatorics”, «Kvant» No. 1, 1971). We will denote different subsets $A$ by the letters $B, C, \dots$, the intersection of the set $B$ and $C$, that is, a set composed of common elements $B$ and $C$, is usually denoted as follows: $B \cap C$; the additional subset $B$ to the entire set $A$, that is, the set composed of all those elements $A$ that are not included in $B$, is denoted as follows: $\bar{B}$.

By condition, $2^{n-1}$ subsets were selected, that is, half of all possible ones, and each of the selected subsets, the intersection of any two (and even three) of them is not empty. Therefore, from each pair of subset $(B, \bar{B})$, complementary to each other up to $A$, exactly one is chosen. Further, if $B$ and $C$ are chosen, then $D = B \cap C$ is also chosen, since $\bar{D}$ cannot be chosen (all three subsets $\bar{D}, B$ and $C$ cannot have common elements, since the common elements $B$ and $C$ are contained in $D$). Using this very strong indication, we can prove that if $B_1, B_2, \dots, B_k$ are chosen, then the intersection of all these subsets $B_1 \cap B_2 \cap \dots \cap B_k$ is also chosen. Therefore, the intersection of all $2^{n-1}$ chosen subsets also belongs to the chosen subset, which means it is not empty.

Thus, we have proven that only such a subset system satisfies the conditions of the problem: some element $a$ of the set $A$ is fixed and all subsets containing this element are selected.

N. B. Vasiliev

F29

Find the rate of evaporation per unit surface area of ​​water into vacuum at temperature $20^\circ\text{C}$. (The saturated vapor pressure at this temperature is 17.5 mm Hg.) How long will it take for the water in the room to evaporate if filled to the top in an ordinary tea saucer? The evaporation of a small amount of water practically does not change the air humidity in the room, which is equal to 70%.

In order to solve the problem, you need to find the number of liquid molecules leaving 1 cm$^2$ of its surface in 1 second. By multiplying it by the mass of water molecules, we can find out the evaporation rate, that is, the mass of water evaporating per unit surface area of ​​​​water in 1 second.

Bydem reason like this. If there were saturated steam above the liquid, then the number of liquid molecules leaving it in 1 second would be the same as in the absence of steam. At the same time, one day, exactly the same number of molecules entered the liquid as came out of it. This allows us to calculate

⟦folio 31⟧

how many molecules fly out of water in 1 second, since finding the number of molecules entering the liquid is quite simple.

Let's use the following model of an ideal gas: all gas molecules have the same speed $v$, and each of the molecules can move only in one of three mutually perpendicular directions along the coordinate axes (Fig. 4). Moreover, the number of molecules moving in each of these three directions is the same. If one of the coordinate axes is perpendicular to the liquid, then in time $\tau$ a mass of vapor enters the liquid, which is located at a distance $l = v \cdot \tau$ from it. Let there be $n$ vapor molecules in a unit volume, then $N = \frac{1}{6} nv\tau S$ vapor molecules fall on a surface area with an area $S$: along the coordinate axis perpendicular to the surface of the liquid, $\frac{1}{3}$ part of the vapor molecules located in the volume $v\tau S$ moves, and the speed of half of them is directed away from the liquid. If the mass of vapor molecules is $m$, then in time $\tau$ a mass of vapor $M = \frac{1}{6} nv\tau Sm$ enters the liquid. $n \cdot m$ is the vapor density $\rho$. That's why

$$M = \frac{1}{6} v\tau S\rho.$$

The speed of steam molecules can be expressed in terms of its pressure and density. Consider a cubic vessel with edge $l$ and faces perpendicular to the coordinate axes (Fig. 4). During the elastic collision of vapor molecules with a wall, its momentum changes by $2mv$ - before the collision the momentum of the molecule is $mv$, and after the collision it is $mv$: the molecule moves away from the wall. Since time $t = \frac{2l}{v}$ passes between two successive collisions of a molecule with the same wall, then, in accordance with Newton’s second law, we can assume that an average force $f = \frac{2mv}{2l} = \frac{mv^2}{l}$ acts on the molecule from the side of the wall. According to Newton's third law, a force of the same magnitude acts on the wall. Since along each of the axes of motion there are $N = \frac{1}{3} nl^3$ molecules, each of which contributes to the pressure on the wall, the total force acting on the wall is equal to

$$F = \frac{mv^2}{l} \cdot \frac{1}{3} nl^3 = \frac{1}{3} nml^2v^2,$$

and the vapor pressure on the wall is equal to

$$P = \frac{F}{l^2} = \frac{1}{3} nmv^2 = \frac{1}{3} \rho v^2.$$

⟦folio 32⟧

Therefore
$$v = \sqrt{\frac{3P}{\rho}}.$$

Substituting this expression for $v$ into formula (*), we get
$$M = \frac{1}{6} \tau S \rho \sqrt{\frac{3P}{\rho}}.$$

Let us also express the density of the vapor in terms of its pressure. They are related by the Clapeyron equation:
$$P = \frac{\rho}{\mu} RT,$$

where $\mu$ is the mass of one gram-molecule of vapor, $T$ is its temperature, and $R = 8,3 \frac{\partial \kappa}{\partial \rho} - \text{газовая постоянная}.$

From this formula we find that $\rho = \frac{P \mu}{RT}$. Therefore $M = \frac{1}{6} \tau S \frac{P \mu}{RT} \sqrt{\frac{3RT}{\mu}}.$

Thus, if there is steam above a liquid, then per unit of its surface in 1 second a mass of steam equal to
$$\frac{M}{\tau S} = \frac{1}{6} P \sqrt{\frac{3\mu}{RT}}.$$

This means that the rate of evaporation of liquid into vacuum is equal to
$$\frac{1}{6} P \sqrt{\frac{3\mu}{RT}}.$$

Substituting here the numerical values ​​$T = 293^\circ \text{K}$, $\mu = 18 \frac{\kappa_2}{\kappa_0 \text{м}^2}$ and $P = 2,3 \cdot 10^3 \frac{\mu}{m^2}$ ($P$ is the saturated vapor pressure at $T = 293^\circ \text{K}$), we obtain that the evaporation rate is $14,8 \cdot 10^{-8} \frac{\kappa_2}{m^2 \cdot \text{сек}}.$

We could solve the problem more accurately, taking into account that molecules move at different speeds and in all possible directions *). This, however, would not change the qualitative result that we obtained. Only the numerical factor in the last formula would change.

Now it is not difficult to find the time during which the water in the room will evaporate after being poured into a tea saucer. In this case, with uniform surfaces of the liquid, molecules with a total mass equal to $\frac{1}{6} P_0 \sqrt{\frac{3\mu}{RT}} \left( P_0 = 10^{-5} \frac{\mu}{m^2} \right)$ fly out in 1 sec, and a vapor mass equal to $\frac{1}{6} P \sqrt{\frac{3\mu}{RT}}$, where $P = \eta \cdot P_0 = 0,7P_0$, enters the liquid. Thus, the rate of liquid evaporation is
$$\frac{1}{6} \left( P_0 - P \right) \sqrt{\frac{3\mu}{RT}}.$$

If the surface area of ​​water is $S$ and its mass is $M$, then all the water will evaporate in time
$$t = \frac{M}{\frac{1}{6} S \left( P_0 - P \right) \sqrt{\frac{3\mu}{RT}}}.$$

*) Such a calculation is given in the article by Ya. A. Smorodinsky “Ideal Gas” («Kvant» No. 10, 1970).

⟦folio 33⟧

Assuming that the saucer contains 100 $e$ of water, its diameter is 10 $cm$, the air temperature in the room is $17^\circ C=290^\circ K$ (at this temperature $P_0 = 2,3 \cdot 10^3 \frac{H}{M^2}$ and $P = 1,6 \cdot 10^3 \frac{H}{M^2}$), we find $t=1$ sec.

The result was paradoxical. Where did we go wrong? The magnitude of the vapor pressure near the surface of the water. Here the steam pressure is significantly greater than in the room. In a thin layer near the surface, the vapor is almost saturated. Only thanks to this does the water evaporate slowly enough.

The example we looked at shows how important it is when solving a physical problem to understand the “physics” of the phenomenon, that is, to understand what can and cannot be neglected.

F30

The film camera and film projector produce 8 frames per second. On the movement screen there is an automatic vehicle with wheels, the actual diameter of which is 1 m. The images of the wheels make 2 revolutions per second. What is the speed of the automatic?

Since the images of the wheels are rotated by 2 turns during the time during which 8 frames pass through the projector, then on each frame the wheel must be rotated by $\frac{2}{8} = \frac{1}{4}$ turns compared to the previous one. Moreover, the images of the automatic vehicle wheels on the screen can rotate both “forward” and “backward,” although the automatic vehicle itself moves in both the first and the second, serving in the same direction (Fig. 5). The wheels on the screen rotate “forward” if the speed of movement of the automatic vehicle is such that during the time between frames $\tau = \frac{1}{8} c$ the wheels of the automatic vehicle make $n$ full and another $\frac{1}{4}$ revolutions around the axis. If in $t$ the wheels make $n$ full and $\frac{3}{4}$ revolutions around the axis, then the images of the wheels on the screen will rotate “backwards”. Thus, the angular speed of the automaton is either $\omega_{\text{вп}} = \frac{\left(n + \frac{1}{4}\right) 2\pi}{\frac{1}{8}} \frac{pa\partial}{c} = 16 \left(n + \frac{1}{4}\right) \pi \frac{pa\partial}{c}$ or $\omega_{\text{н}} = 16 \left(n + \frac{3}{4}\right) \pi \frac{pa\partial}{c}$. This means that the wheel axles, and with them the automatic vehicle, moves at a speed of $v = 16 \left(n + \frac{1}{4}\right) \pi R \frac{m}{c}$ (in which case the wheel images rotate “forward”) or at a speed of $u = 16 \left(n + \frac{3}{4}\right) \pi R \frac{m}{c}$ (in this case the wheel images rotate “backward”). Substituting $n = 1, 2, 3, \dots$ into these formulas, we will get the answers

$$v_1 \approx 12,6 \frac{m}{c} = 45 \frac{km}{час}, \quad v_2 \approx 223 \frac{km}{час}, \quad u_1 \approx 136 \frac{km}{час}, \quad u_2 \approx 316 \frac{km}{час}, \dots$$

⟦folio 34⟧

Moreover, since the automatic speed cannot be more than 140 $\frac{\kappa M}{\mu ac}$, it is equal to 45 $\frac{\kappa M}{\mu ac}$ if the wheel images are rotated “forward”, or 136 $\frac{\kappa M}{\mu ac}$ if the wheels on the screen are not rotated “backwards”.

The correct solution was sent by Nikolay Ilyin (Zakhal village, Ekhirit-Bulagat district, Irkutsk region).

F31

How does light pressure orient a spherical spaceship relative to the Sun, one half of which is mirrored and the other half black, so that the radiation from the Sun is completely absorbed? The center of the ship's gravity is at the center of the sphere.

Let's assume that the ship is oriented so that the sun's rays fall on both the specular and black areas of its surface (Fig. 6). Light pressure is due to the fact that photons hitting surfaces change their momentum. If light hits a mirror surface, it is reflected so that the law of reflection is satisfied: the angle of incidence of the light beam is equal to the angle of reflection. It is easy to report that in this case the photon momentum changes to a vector perpendicular to the surface of the ship, that is, running along the radius. In accordance with Newton's second and third laws (see the previous problem), a force equal to the change in the momentum of the photon beam per unit time acts on the ship. This force is directed along the radius of the ship. It does not create a moment that turns the ship so that the mirror surface of the ship is facing the Sun.

The pressure on the blackened surface of the ship is a different matter. Since it absorbs radiation from the Sun, the force acting on the ship when a photon falls is directed along the beam. This force creates a moment that turns the ship so that the mirror surface of the ship is facing the Sun.

Obviously, the position of the ship, in which its blackened surface faces the Sun, will also be an equilibrium position. However, this equilibrium position is unstable. If for some random reason the ship has a little surface relative to the Sun, then it will turn around until it turns to the mirror side of the Sun.

F32

A square block of wood floats on the surface of the water. Which of the two equilibrium positions shown in figure 7 will be stable? The density of the materials from which the block is made is equal to half the density of water.

A system presented to itself always occupies a position in which its center of mass is in the lowest position. Since the density of the materials of the block is equal to half the density of water, then in both cases half of the cube and the centers of gravity of the cups are immersed in the body

⟦folio 35⟧

are at the same height. It's a different matter with the center of gravity of water. When a block is immersed, we move to the surface the water whose place is occupied by the submerged part of the block. In the first case, the center of mass of the displaced volume of water is at a distance of 0.25 a from its surface, and in the second, at a distance equal to $\frac{1}{3} \frac{a \sqrt{2}}{2} =$

$$= \frac{1}{6} a \sqrt{2} \approx 0,23 a,$$

where $a$ is the edge of the block. This means that in the second case the change in the potential energy of water when the cube is immersed is less than in the first. Therefore, in the second case, the potential energy of water is also less. This means that the block will float in position II.

♦ 33

Two beads with masses $m_1$ and $m_2$ can slide along a smooth horizontal wire ring without friction. At first, the beads were connected by a thread and there was a rolled spring between them. The thread is burned out. After the beads begin to move, the spring is removed. In what place do so many beads accumulate at the same time? The beads become completely elastic.

The spring imparts the same amount of motion to both beads, since it acts on them for the same time with the same force:

$$m_1 v_1 = m_2 v_2$$

(1)

where $v_1$ and $v_2$ are the coastal beady velocities. Therefore, for the paths $l_1$ and $l_2$, traversed by the beads before the first collision, we also have $m_1 l_1 = m_2 l_2$. After the collision, the total momentum of the beads should still remain zero. That's why

$$m_1 v_1' = m_2 v_2'.$$

(2)

Having written the law of conservation of energy

$$\frac{m_1 v_1^2}{2} + \frac{m_2 v_2^2}{2} = \frac{m_1 v_1'^2}{2} + \frac{m_2 v_2'^2}{2},$$

(3)

Using (1) and (2) we easily find that after the impact there are $v_1' = v_1$ and $v_2' = v_2$.

Thus, as a result of the collision, the velocities of the beads do not change in magnitude, but only change their directions to the opposite. But then it is clear that the next collision will occur in the place where the movement of the beads began, etc. The eleventh collision will occur in the same place where the first one occurred, that is, at the point the ratio of the distances to which from the origin of coordinates (along the arc of a circle) is equal to the ratio of the masses of the beads.

♦ 34

figure 8 shows a drip electrostatic machine (Kelvin generator). Drops of water charged to potential $\phi_0$ fall from the tube into the fields of an insulated metal ball of radius $R$. How does the maximum potential to which a ball can be charged depend on the height of the drops?

Once in the ball, the drops will release their contaminants evenly over the surface of the ball. In this case, an electric field will arise, transforming the fall of the drops, since the drops and the ball are contaminated with the same sign.

The speed of the drop near the surface of the ball can be found using the law of conservation of energy. The energy of a drop $E$ consists of kinetic energy, potential energy in the field and electrostatic energy in the field of the ball.

⟦folio 36⟧

It is known that the electric field of a uniformly charged sphere outside it is the same as that of an exact charge, equal in magnitude to the charge of the sphere and located at its center. Therefore, the potential energy of the exact charge $q$ in the field of a uniformly charged sphere with charge $Q$ is equal to $qQ/d$, where $d$ is the distance of the charge to the center of the sphere.

The energy of the drop at the beginning of the
division $E_0 = mgh + \frac{qQ}{h-R}$, where $h$ is the height of the drop falling from the table surface ($h > 2R$).

At the surface of the ball the energy of the drop is

$$E_1 = \frac{mv^2}{2} + 2Rmg + \frac{qQ}{R}.$$

Equating these energies, we find

$$\frac{mv^2}{2} = mg(h - 2R) - qQ \frac{h - 2R}{R(h - R)}.$$

As the charge of the ball $Q$ increases, the speed of the drop $v$ at its surface decreases. Obviously, the ball will stop charging when this speed becomes zero. The next drops will no longer be able to enter the ball. From this condition we find the limiting charge of the ball:

$$Q = \frac{mgR(h - R)}{q}.$$

Using the well-known electrostatic formulas $Q = \phi R$ and $q = \phi_0 r$, for the limiting potential of the ball we obtain

$$\phi = \frac{mg(h - R)r}{2\phi_0}.$$

When deriving this formula, we assumed that the ball would not overflow with liquid before it charged to the found limiting potential. However, if, for example, the drops are large enough, then the opposite can always happen: the ball will overflow, but the drops will still be able to fall into it. In this case, the limiting potential of the ball is also easy to find.

If the radius of a drop is $r$, and the radius of a ball is $R$, then the ball will be filled when $N = (R/r)^3$ drops hit it. In this case, the charge of the ball will be equal to $Q = qN$, where $q = r\phi_0$ is the charge of one drop, and the maximum potential of the ball is $\phi' = Q/R = \phi_0 R^2/r^2$.

Obviously, in drop electrostatic machines the ball is guided completely, since this results in a higher ultimate potential.

The correct solution was sent by A. Egorov from Moscow and N. Efimov from Vinnitsa (Ukrainian SSR).

I. Sh. Slovodechkiy
