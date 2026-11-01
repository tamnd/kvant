---
id: 1986-9-resheniya-zadach-m981-m985-f993-f997-8ef0bbe0
issue: kvant_1986_9
year: 1986
number: "9"
title: Solutions to problems M981—M985; F993—F997
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 41
page_last: 52
page_labels: 39, 40, 41, 42, 43, 44, 47, 50
tag: BEP2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 83c13b1845ce987ea7093beb97b17cd5988d4db755bbb416ebc9fd293a42ff8b
prompt_sha256: draft-1
translated_from: content/ru/1986/09/articles/17_resheniya-zadach-m981-m985-f993-f997-8ef0bbe0.md
source_content_sha256: 154e098ff1d6a817298fc7e1cb70e9b72e78943bb100c9b970ac01836aad11a5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

U=100 V and current flows through it as plotted on figure Pisc. 4, p. 37. Determine the original inductivity of the coli. Assuming losses negligible, find the velocity of the core at time $\tau=10^{-3}$ s.

V. E. Skogovarov

P1017. The world’s largest (Soviet-made) telescope has a mirror of diameter $D=6$ m for a lens. How much time is required to register the relative rotation of our Galaxy and Andromeda about their common centre of mass by comparing photographs obtained by this telescope? The distance to Andromeda is $R=1.42 \cdot 10^{11} R_0$, where $R_0$ is the radius of Earth’s orbit. The masses of our Galaxy and Andromeda equal, respectively, $M_G=2,5 \cdot 10^{11} M_0$ and $M_A=3.6 \cdot 10^{11} M_0$, where $M_0$ is the Sun’s mass. The photographs are taken in visible light of wavelength $\lambda=5 \cdot 10^{-7}$ m.

V. E. Belonuchkin

Problem solutions

M981 — M985; F993 — F997

a) It is clear that if the number $a$ is written in $n$ units, the number $b$ is written in $k$ units and $n$ is divisible by $k$, then $a$ is also divisible by $b$. And since 1986 = $2 \cdot 3 \cdot 331$, the number $A=11...1$ of 1986 units has, in addition to the number 1 and $A$ itself, at least 6 more divisors of the same units:

$$11, 111, 111 111, \underbrace{11...1}_{331}, \underbrace{11...1}_{662}, \underbrace{11...1}_{993}$$

b) We indicate not 28, but 128 divisors of the number $A$. Note that 111111 is decomposed into 5 prime factors:

$$111111=1001 \cdot 111=3 \cdot 7 \cdot 11 \cdot 13 \cdot 37.$$

Considering that $10^{993}+1$ is divisible by $10^3+1=1001$, and $10^{993}-1$ is divisible by $10^3-1=999$ (see the same in the margins, where $n=2k+1=331$, $x=10^3$) and putting $a=10^{331}$, we get

$$A=\frac{a^6-1}{9}=(a^3+1)\frac{a^3-1}{9}=\frac{3 \cdot 7 \cdot 11 \cdot 13 \cdot 37}{1001} \cdot \frac{a^3-1}{999}.$$

The product of any set of these 7 factors will be the divisor $A$ (“the empty set” is answered by the divisor 1). Thus, we have found $2^7=128$ divisors, and they are all different. To verify this, let us prove that all 7 factors in the written expansion $A$ are pairwise simplistic. In fact, the remainder when dividing the number $a$ by $m=10^6-1$ is 10, since $10^{331}-10=10(10^6-55-1)$ is divisible by $m$; therefore, $a^3 \pm 1$ when divided by $m$ gives the remainder $10^3 \pm 1$, that is, the numbers $(a^3+1)/1001$ and $(a^3-1)/999$ are coprime with $m$ and, obviously, coprime with each other.

It is not difficult to continue the expansion of $A$ into relatively prime factors:

$$A=3 \cdot 7 \cdot 11 \cdot 13 \cdot 37 \frac{a+1}{11} \cdot \frac{a^2-a+1}{91} \cdot \frac{a-1}{9} \cdot \frac{a^2+a+1}{111}$$

(from the statement highlighted above by Chicken it follows that the factors here are integers); from this it is clear that $A$ has at least $2^9=512$ divisors. Continue this decomposition “by hand”

⟦folio 40⟧

M982. On sides AB, BC and CA of triangle ABC, squares ABB₁A₂, BCC₁B₂, CAA₁C₂ are constructed on the outer side. Prove that the redistributions to the segments A₁A₂, B₁B₂, C₁C₂, reconstructed at their midpoints, intersect at one point.

M983. In a tournament with 16 tennis players each, two play one game.
a) Give an example of the distribution of the results of a game in which any 10 participants can be placed in a circle so that each one beats its left neighbor.
b) Prove that if the condition from point a) is satisfied, then any 11 participants can be arranged in a circle in this way.

Nuyu" is already difficult. However, from Fermat's Little Theorem (given in the margin) it follows that $9A=10^{1986}-1$ is divisible by the prime number 1987. Thus, one of the last 4 components must be divisible by 1987, which means A has at least $2^{10}=1024$ divisors. Maybe one of the readers managed to raise this rating even higher?

N. V. Vasiliev, L. D. Kurlyandchik

♦ We will prove that the redistributions considered in the problem contain the medians of a certain triangle that is similar to the given triangle ABC. The statement of the problem then follows from the fact that the medians of any triangle intersect at one point.

Let us draw straight lines through the centers of the squares parallel to the sides of triangle ABC (see Fig. 1); they limit the triangle $A_0B_0C_0$ that is prepared for him. Since the lines $A_0B_0$ and $A_0C_0$ are the midpoints of the redistributor to the segments $AA_2$ and $AA_1$, the point $A_0$ of their intersection is the circumcenter of the triangle $AA_1A_2$ and, therefore, lies on the midpoint of the redistribution $p_a$ to the segment $A_1A_2$. Similarly, the midpoints of the lines $p_b$ and $p_c$ to the segments $B_1B_2$ and $C_1C_2$ pass through the points $B_0$ and $C_0$, respectively.

It remains to prove that the lines $p_a$, $p_b$, $p_c$ contain the medians of the triangle $A_0B_0C_0$. To do this, it is enough to check that they are parallel to the media of triangle ABC; for example, that the line $p_a$ is parallel to the median AM, or that $AM \perp A_1A_2$. Rotate triangle ABC by $90^\circ$ around point A so that vertex B goes to $A_2$ (Fig. 2). Let the points M and C go in this case to $M'$ and $C'$; then $M'$ is the midpoint of $A_2C'$, and A is the midpoint of $A_1C'$ ($A_1A=AC=AC', \angle A_1AC=\angle CAC'=90^\circ$). Therefore, $AM'$ is the middle line of triangle $A_1C'A_2$, that is, $AM' \parallel A_1A_2$; at the same time $AM \perp AM'$.

Another solution can be obtained from the following message: let O be the point of intersection of the medians of triangle ABC; if the segments $A_1A_2$, $B_1B_2$ and $C_1C_2$ are intersected in parallel into the vectors $\vec{AO}$, $\vec{BO}$ and $\vec{CO}$, respectively, then these three segments will connk into a triangle, and the lines $p_a$, $p_b$ and $p_c$ will be its midpoints.

V. N. Dubrovsky

♦ a) Let 16 tennis players stand in a circle and each one beat the 7 next to him in a clockwise direction (how tennis players separated by 8 places played among themselves is not significant). This distribution of results satisfies the conditions of the problem: if we randomly mark 10 tennis players in a circle - $A_1$, $A_2$, ..., $A_{10}$ (clockwise), then between $A_1$ and $A_2$, $A_2$ and $A_3$, ..., $A_{10}$ and $A_1$ there are no more than 6 tennis players, so in each of these pairs the first one won against the second one.

The number 16 in the problem statement can be replaced by any $n \geq 3$, and 10 - by any $k$ such that $(n+3)/2 \leq k \leq n$ - the example is constructed in exactly the same way. If $k<(n+3)/2$, such an example cannot be constructed.

6) Let us prove that if any $k(2<k<n)$ of $n$ tennis players who played each other one by one

⟦folio 41⟧

games, can be arranged in accordance with the conditions, then any $k+1$ points.

Let's consider a certain group of $k+1$ tennis players and remove one $-A$ from it, and arrange the remaining $k$ in a cycle (so that each one wins against the next). Let's mark those from $k$ that $A$ lost as red, and those from whom it won as blue (see figure); at least one red and at least one blue one will be found, because $A$ together with any $k-1$ tennis players can be arranged in a cycle (that is, even among any $k-1$ of our $k$ there is both a red and a blue tennis player). Now let's select any place in our loop where there is blue after red clockwise, and insert $A$ between them.

Note that for $n=16$, $k=10$ the statement of the problem remains true even if we do not require that all tennis players play each other. To verify this, it is enough from the condition that any 10 tennis players can be arranged in a cycle to derive the following consequences:

1) each won no more than 7 games;
2) among any 11 there is one who played with all 10 others.

K. P. Kokhas, N. V. Vasiliev

M984. Through an arbitrary point $K$ of the square $ABCD$ a line is checked that intersects its opposite sides $AB$ and $CD$ at points $P$ and $Q$. Prove that the intersection point of the circle passing through the points $K$, $B$, $P$ and $K$, $D$, $Q$, different from $K$, lies on the diagonal $BD$.

Let $L$ be the point of intersection of the diagonal $BD$ with the circle $DQK$. Let us prove that this point also lies on the second circle - $BPK$. To determine this, assume that points $K$ and $Q$ lie on opposite sides of $BD$, and $P$ and $K$ lie on the same side (see figure). Then, since angles $DQK$ and $DLK$ are inscribed in one circle and rest on the same arc $DK$,

$$\angle BPK = \angle PQD = \angle KLD = 180^\circ - \angle KLB,$$

that is, the quadrilateral $PKLB$ is inscribed in a circle.

Let's give another solution using rotation. Let $M$ and $N$ be the intersection points of circles $KQD$ and $KPB$ with lines $AD$ and $BC$, respectively (see figure). It is clear that $\angle MKQ = \angle PKN = 90^\circ$, that is, the segment $MN$ is perpendicular to $PQ$ and passes through the points $K$. Consider the rotation of the point $Q$ into $M$ (and the ray $QC$ into the ray $MD$). It is easy to see that in this case the turn straight line $QP$ will turn into $MN$, and straight line $AB$ into $BC$. Therefore, the points $P$ will go to $N$. Since the segments $QM$ and $PN$ are visible from the center of rotation at right angles, this center lies at the intersection of these circles. On the other hand, it is equal to the lines $AB$ and $BC$ (since the first of them goes into the second) and, therefore, lies on the diagonal $BD$.

V. N. Dubrovsky

M985. The angle between two straight lines intersecting at the point $O$ is called the angle between the northern $O$ and the non-ascending $90^\circ$. In how many ways can three straight lines $l_1$, $l_2$, $l_3$ be checked through the point $O$ in space so that the angles between $l_2$ and $l_3$, $l_3$ and $l_1$, $l_1$ and $l_2$ are respectively equal in number $\alpha_1$, $\alpha_2$, $\alpha_3$? (Two straight tracks

⟦folio 42⟧

$l_1, l_2, l_3$ and $l'_1, l'_2, l'_3$ are considered the same if they are "conloaded", that is, if there is a rotation or symmetry about the plane that translates $l'_i$ into $l'_i$, for all $i=1, 2, 3$.

Prevention: The answer depends on the magnitude of $a_1, a_2, a_3$: for example, for $a_1=a_2=a_3=30^\circ$ it is not the same as for $a_1=a_2=a_3=70^\circ$.

Each of the plane angles must be less than the sum of the other two, and the sum of all three angles must be less than $360^\circ$ (see, for example, the textbook: Geometry 9-10 / Edited by Z. A. Skorets - M.: Prosveshchenie, 1981, p. 224). In this case, a trihedral angle is determined uniquely by its flat angles (up to congestion).

Let $l_1, l_2, l_3$ be lines that satisfy the conditions of the problem. On the straight line $l_1$ we select one of the rays with the beginning $O$ - we denote it $r_1$, - and on the straight lines $l_2$ and $l_3$ - the rays $r_2$ and $r_3$, making angles of magnitude $a_2$ and $a_3$ with $r_1$ (see figure). Since the angle between lines $l_2$ and $l_3$ is $a_1$, the angle between rays $r_2$ and $r_3$ can be $a_1$ or $180^\circ-a_1$. From what has been said about trihedral angles it follows that there are at most two different (up to congestion) straight tracks with a given angle $a_1, a_2, a_3$ between them. They are obtained by extending the edges of two trihedral angles $T$ and $T'$ with flat angles $a_1, a_2, a_3$ and $180^\circ-a_1, a_2, a_3$, respectively, and for their existence it is necessary and sufficient that conditions (1) be satisfied in the first case, (2) in the second.

Note that for $a_1=90^\circ$ all our straight lines are identical ($T \cong T'$, since $a_1=180^\circ-a_1$). Of course, this is also true when $a_2=90^\circ$ - in the calculations you can simply change the numbering of the lines. So, if at least one of the angles $a_1, a_2, a_3$ is equal to $90^\circ$ and condition (1) is satisfied (or condition (2) coincides with it in this case), then our problem has a unique solution.

Finally, let all angles $a_1, a_2, a_3$ be acute and satisfy the general systems (1) and (2). Let us show that then the tracks of lines constructed from the trihedral angles $T$ and $T'$ are different. In order for two such tracks to be congested, it is necessary that the angle $T'$ be congested with the angle $T$ or, in general, any of the 8 trihedral angles with vertex $O$, the edges of which lie on the same straight lines $l_1, l_2, l_3$ as the edges of the angle $T$. It is easy to see that the plane angles of these trihedral angles can be equal to ($a_1, a_2, a_3$) (for the angle $T$ and the “vertical” angle to it), ($180^\circ-a_1, 180^\circ-a_2, a_3$), ($a_1, 180^\circ-a_2, 180^\circ-a_3$) or ($180^\circ-a_1, a_2, 180^\circ-a_3$). But the angle $T'$ has exactly 2 acute angles ($a_2$ and $a_3$), and in all the written out paths their number is 3 or 1.

A. V. Goncharov, V. N. Dubrovsky

F993. A rope is thrown through a fixed, horizontal fastening of the beam. To hold a load with a mass of $m=6$ kg, it is necessary to find the second end of the rope with a minimum force of $F_1=40$ N (see figure). With what minimum force $F_2$ must the rope be pulled so that the load begins to rise?

The weight of the load $P=mg=60$ N is significantly greater than the force $F_1$ with which the rope must be pulled. This situation is well known to us from life and is associated with the presence of tracks between the rope and the log.

In the first case (the rope is stationary), the forces of the tray are directed against the action of the weight of the load and help to hold the rope with the load. A complete calculation of the distribution of the rope forces is quite complicated, since the absolute value of the rope tension force (which determines the reaction force of the support in

⟦folio 43⟧

points of contact between the rope and the log) changes from $F_1$ (balance condition for the left end of the rope) to $P = mg$ (balance condition for the right end). However, to solve the problem, it is enough for us to note that the friction force $F_{\tau p}$, proportional at each point to the support reaction force, will be proportional to the tension force of the rope; for the definition, we will assume that $F_{\tau p}$ is proportional to the larger tension force, that is, $F_{\tau p} = kP$. This means that $F_1 = P - kP$, and the ratio of the larger tension force $P$ to the smaller $F_1$ is a constant: $P/F_1 = 1/(1-k) = \text{const}$.

In the second case, when we want to lift the load, the ends of the rope seem to change places. The friction force turns out to be directed against the action of force $F_2$ and no longer helps, but hinders. The ratio of the larger tension force $F_2$ to the smaller one $P$ should be the same as in the first case $F_2/P = P/F_1$.

From here is:

$$F_2 = \frac{P^2}{F_1} = 90 \text{ H.}$$

A. I. Buezdin

F994. The satellite explores a planet whose density is $\rho$, moving in a circular orbit with an orbital period of $T$ and its relative surface. How much of the planet's surface will remain unexplored?

◆ From the satellite, only part of the planet’s surface is visible, falling inside the cone, the vertex of which is the point at which the satellite is currently located, and the generators are tangents to the planet’s surface drawn from this point (see figure). Thus, two spherical segments remain unexplored, the area of ​​which

$$s = 2 \cdot 2\pi rh = 4\pi r^2 (1 - \cos \alpha) = 4\pi r^2 \left(1 - \sqrt{1 - \left(\frac{r}{R}\right)^2}\right),$$

where $r$ is the radius of the planet, $R$ is the radius of the satellite’s orbit. The ratio of this area to the surface area of ​​the planet is

$$\frac{s}{S} = 1 - \sqrt{1 - \left(\frac{r}{R}\right)^2}.$$

Let us express the relation $r/R$ through the data given in the conditions of the problem.

Let us write down the equation of motion of the satellite:

$$G \frac{Mm}{R^2} = ma,$$ or $a = G \frac{M}{R^2} = G \cdot \frac{4}{3} \pi r^3 \dot{\rho} \cdot \frac{1}{R^2}$.

On the other hand, $a = (2\pi/T)^2 R$. Hence,

$$\frac{4}{3} G \pi \rho \frac{r^3}{R^2} = \frac{4\pi^2}{T^2} R,$$

where

$$\frac{r}{R} = \sqrt[3]{\frac{3\pi}{G \rho T^2}}.$$

Substituting this value into (*), we find what part of the planet’s surface area remains unexplored:

$$\frac{s}{S} = 1 - \sqrt{1 - \left(\frac{3\pi}{G \rho T^2}\right)^2/3}.$$

V. V. Dorin

⟦folio 44⟧

F995. In the western capillary there is a liquid of density $\rho$. When the capillary is heated to a small level $\Delta T$, it turns out that the boundary $AB$ between the liquid and its vapor (see figure) is not connected. At the same time, the steam pressure increased by $\Delta p$. How did the density of the liquid change?

From the conditions of the problem it follows that the state of the system before and after heating corresponds to the equilibrium society of liquid and its vapor. This means that on the $p - T$-diagram, both states fall on the society curve. This curve, as is known, represents the dependence of pressure $p$ of saturated steam on temperature $T$, and this dependence is monotonic. The tangents to the curve $p$ (T) make different angles with the axis $T$. Let us select the point on the curve at which the tangent makes an angle $\alpha = \arctg \frac{\Delta p}{\Delta T}$ with the axis $T$. The values ​​$p$ and $T$ corresponding to this point uniquely determine the initial pressure and temperature of the gas.

When heated, the liquid should expand, that is, the boundary $AB$ should move to the right. The immobility of the boundary means that when heated, such a mass $\Delta m$ of liquid evaporates that the remaining liquid with density $\rho - \Delta \rho$ occupies the volume mode. As can be seen from figure, this volume is equal to the volume occupied by steam. Thus,

$$\Delta \rho = \frac{\Delta m}{V}.$$

(*)

A change in saturated vapor pressure is associated with an increase in its temperature by $\Delta T$. From the equations of state of steam at temperatures $T$ and $T + \Delta T$ -

$$pV = \frac{m}{\mu} RT,$$

$$(p + \Delta p)V = \frac{m + \Delta m}{\mu}R(T + \Delta T)$$

- we get:

$$\Delta p \cdot V = \frac{\Delta m}{\mu}RT + \frac{m}{\mu}R \cdot \Delta T + \frac{\Delta m}{\mu}R \cdot \Delta T.$$

Neglecting the term $\frac{R}{\mu}(\Delta m \cdot \Delta T)$, from here, taking into account (*) we find:

$$\Delta \rho = \frac{\mu}{R} \frac{\Delta p \cdot T - p \cdot \Delta T}{T^2}.$$

L. G. Markovich

F996. In a solid-state mass selective meter, the source emits a bunch of charged particles, which first fly freely (Fig. 1) and pass through the first sensor ($\Delta_1$), at Fig. 1.

Let a particle of mass $m$ fly out from the source with a speed $v$. Let us denote by $v_||$ the projection of this velocity onto the direction parallel to the grid $C$, and $v_⊥$ by the projection $v$ onto the direction perpendicular to the grid. As particles move behind the grid (to the right of it), $v_||$ remains unchanged, and $v_⊥$ changes from $+v_⊥$ to $-v_⊥$. According to the law of conservation of momentum (in projections onto the direction perpendicular to the grid), $F \cdot \Delta t = m \cdot \Delta v_⊥ = 2mv_⊥$, where $\Delta t$ is the time of movement of the particles behind the grid; hence $\Delta t = 2mv_⊥/F$. The total flight time is

$$T = t + \Delta t = \frac{2L}{v_⊥} + \frac{2mv_⊥}{F}$$

(*) (t is the total time of travel from sensor $\Delta_1$ to the entrance to the grid and from the exit from the grid to sensor $\Delta_2$).

⟦folio 47⟧

T. Misirnashaev (Moscow) 60; C. Mortisi (Tigroviste, SRR) 62; Y. Mustafayev (Baku) 64; S. Mushinsky (Novosibirsk) 57, 59, 62, 63, 65, 67, 68; T. Narbekov (Alma-Ata) 65; V. Neff (Donetsk) 65; Yu. Nikonorov (village of Mikhailovka, Kazakh SSR) 62, 65; O. Nits (Odeska) 60, 62, 63, 65, 67, 68; S. Okulovsky (Leningrad) 62, 64, 65; M. Pankov (Lviv) 62, 65, 67; Yu. Panchul (Kyiv) 62, 65; P. Pasmanik (Moscow) 65, 67; D. Pastur (Kharkov) 60; M. Pasumansky (Leningrad) 64; O. Pelevin (Kostroma) 62; A. Petrova (Leningrad) 57, 60; V. Pickman (Kyiv) 65; A. Pokrovsky (Kyiv) 57, 60, 62, 65, 67, 68; V. Polivov (Magnitogorsk) 57, 60; V. Pomaz (Semyonovka) 65; M. Pomerantsev (Cherkasy) 57; I. Portnoy (Odeska) 62—65, 67, 70; V. Protsak (Kyiv) 62, 64, 65, 67; V. Furry (Kharkov) 62, 64, 65, 67; V. Radulin (Chelyabinsk) 67, 68; A. Raisky (Alma-Ata) 65; I. Raskina (Vitebsk) 62, 65; S. Reznov (Kyiv) 62, 65, 67, 68; M. Rzaev (Vaku) 62; A. Roiterstein (Leningrad) 62-64; K. Rubtsov (Kyiv) 62, 65; T. Rudenko (Kyiv) 65; D. Romanin (Krasnoirsk) 57, 64; V. Sakbeev (Alma-Ata) 65; Z. Salkanova (Alma-Ata) 65; I. Samovol (Gayvoron) 60; D. Seminkhin (Kyiv) 62, 65, 68; S. Silvestrov (Kyiv) 62, 64, 65, 67; I. Simonenko (Vellike Luki) 60; K. Sinalevich (Leningrad) 65; V. Slituzhe (Dimitrovgrad) 67; S. Smirnov (Leningrad) 62—65, 67, 68, 70; V. Stolin (Vilnos) 62, 63, 67; A. Strunin (Yaroslavl) 64, 65, 67, 68; K. Styrkas (Chernogolovka village, Moscow region) 62, 64, 67; D. Seminkhin (Kyiv) 62, 65, 68; S. Silvestrov (Kyiv) 62, 64, 65, 67, 68; I. Simonenko (Vellike Luki) 60; I. Ustilovsky (Moscow) 59, 60, 62-65, 67, 68, 70; V. Fililshtein (Voronezh) 65; V. Fokin (Khabarovsk) 62, 65, 67; D. Khadzhtsev (Stara Zagora, Belarus) 62; L. Hristov (Silistra, NRB) 67; A. Chazirov (Alma-Ata) 60; E. Chernaya (Depprodzerzhinsk) 67, 70; K. Churashe (Novosibirsk) 62, 65, 67; E. Churashe (Novosibirsk) 62, 65, 67; Yu. Shampuk (Tselinograd) 62, 67; Yu. Shampuk (D. Novy Dvor, Grodno region) 67; I. Shekhtman (Kyiv) 67, 68; S. Shekhtman (Kyiv) 65; V. Shmuklerman (Odeska) 62; I. Sholev (Stara Zagora, Belarus) 65; I. Shor (Kyiv) 65; I. Shor (Kyiv) 65; P. Shrabotey (Moscow) 67; V. Shrayer (Leningrad) 62-65; P. Steinberg (Pushino) 62, 65; G. Shuzay (Zaporozhye) 65; O. Shelkov (Navon) 62, 67; I. Shenetkova (Moscow) 67; V. Elkin (Kharkov) 62, 65; Y. Efdideev (Vaku) 62; O. Yusukhno (Kyiv) 62, 63, 65; A. Yavryan (Yerevan) 67.

Physics
A. Abanov (Krasnoirsk) 68, 69, 74; U. Abakirov (Alma-Ata) 75; O. Azikova (Tselinograd) 73-75, 78, 80; A. Anisimov (Kyiv) 78, 80; F. Asmanyarova (Tselinograd) 73-75, 78, 80; T. Akhmetov (Novosibirsk) 78, 80; K. Bedov (Chelyabinsk) 68—70, 72; A. Belechky (Kyiv) 78; Yu. Beloborodov (Chelyabinsk) 80; S. Belovolov (Novosibirsk) 68, 69, 78; D. Belonov (Sverdlovsk) 70; V. Berezsky (Kyiv) 69; A. Bermus (Grozny) 75; O. Besman

⟦folio 50⟧

The position of programming and computer science is one of the current misunderstandings. There are quite a few “clever people,” I dare say, ionically, from whom you can hear “this is not computer science at all, this is pure programming.” Such a statement, from my point of view, indicates either incompetence or a methodologically incorrect position. After all, programming is an integral part of computer science.

I'll try to clarify this by stretching the question to myself. Of course, the easiest way for me to say is that my scientific specialty is programming. Because I have been programming in a broad sense for most of my adult life. At the same time, I will insist on such an expanded understanding of the word “programming”; it covers not only the writing of specific programs. But now that our computer science has a name - computer science - I must say that computer science is also my scientific specialty. I have works and reflections that relate to the subject of computer science, its connections with other sciences, with mathematics and physics, and its content in the school course. Therefore, I will briefly answer the question this way: my current scientific specialty is computer science, and a more narrow one is programming.

How do you imagine the interactions between mathematics and information?

— First of all, I want to emphasize that computer science expands the scope of mathematics. For example, such aspects of computer science as the theory of algorithms and theoretical programming, data structure, information models, and computational experiment create the basis for mathematical research. In addition to this, it is the computer that allows the most effective application of practical mathematical methods in all spheres of human activity. We can say that computer science is the way mathematicians are conquering the world.

For computer science specialists, mathematical sciences serve as the main working apparatus. But computer science itself is an integrative science, it takes not only from mathematics, but also from phenomenological sciences, linguistics, and psychology. Information occupies a special position at the end of other sciences: its goal is to reveal and overcome the basic principles of the unity of information processing in the Universe. (I will note in parentheses that cybernetwork has a similar, but not the same scope of application: to study the basic principles of information processing flows, but not in the “entire Universe”, but only in the sphere of control.)

We can say this: if physics is trying to answer the “fatal question” - why the world is structured in such a way that one can live in it, computer science answers its “fatal question” - why we can understand the world around us, master the information that objectively exists in nature. Information as a science distorts the existence of natural sign systems - information carriers in nature, and itself creates sign systems, reveals the unity of the laws of information processing in nature, in technology.

The creation of artificial intelligence is one of the tasks of computer science. In industry and technology, we free people from physical labor. Information solves a person’s problems in the information processing process, which is achieved by a thorough explanation of its functions, which are then transferred to the computer. Thus, in order to understand information, it is necessary to develop an algorithm for processing it. That's why they often say: we know it if we can program it.

I will not go deeper into the maintenance of the subject of computer science. I will only say that information is neither matter nor energy, but not the third. Any science studies some structures of nature. In a sense, studying the structure of structure is no less exciting and exciting than studying the structure of matter - my youthful hobby - which I spoke about at the beginning of our conversation.

Veseda was recorded by A. V. Sosinsky
