---
id: 1979-9-resheniya-zadach-m528-m529-f538-f541-3bcc6f04
issue: kvant_1979_9
year: 1979
number: "9"
title: Solutions to problems M528, M529; F538—F541
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 30
page_labels: 24, 25, 26, 28
tag: T94V
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7f61db688d9bed46ac4e4a7f4caca2392a275f3276adfd969aab101733992d38
prompt_sha256: draft-1
translated_from: content/ru/1979/09/articles/10_resheniya-zadach-m528-m529-f538-f541-3bcc6f04.md
source_content_sha256: c4e941ba32bb8af880ff755a3f8231a07dfa3cb5b6ac8aba91b6d8b7d0003d1b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

Problem solutions

M528, M529; F538 — F541

M528. There is a piece on each square of the chessboard. The chips must be rearranged so that the distance between each pair of chips does not decrease compared to the distance between them at the original location. How many ways can this be done? (Consider the distance between the tokens being compressed between the centers of the cells they occupy.)

Fig. 1.

Fig. 2.

Let us prove, first of all, that a rearrangement of tokens is required to preserve the distances between any two tokens. This can be done in many different ways.

First way. The sum of all pairwise distances between chips does not change. It follows that none of the distances can increase (indeed, if after rearranging the chips the distance between each pair of chips has not decreased, then since the sum of all distances is constant, there will be chips the distance between which will decrease, which contradicts the conditions of the rearrangement).

Second way. Corner pieces A, B, C, D (Fig. 1) must still remain corner pieces, since the distance from each of them to the piece in the opposite (diagonal) corner cannot change (this distance is equal to the length of the diagonal of the board, maximum: $|AC| = |BD| \ge |KL|$, where K and L are arbitrary squares). So these four pieces still occupy the four corners of the board, and their new positions A', B', C', D' are still four consecutive vertices of the square (Fig. 2). Then the distances from the token M to the side of the square ABCD must be equal to the distances from its image - the token M' - to the corresponding sides of the square A'B'C'D': otherwise the distances from M to each of the two adjacent sides of the square would not increase, and one of them would strictly decrease; but then the distance to the common top of these sides should also decrease.

From our proofs it is clear that the necessary rearrangement of the tokens determines some movement of the square ABCD on itself. Such self-alignments exist in everything (including the identical one, in which all points remain in place): vertex A can fall into any of the other four, and vertex B can fall into one of its two neighboring vertices.

Note that the main result of the problem admits the following red generalization: if f is a continuous mapping of a closed orange set (on the plane or in space) into itself such that for any two points M, N

$$\rho(f(M), f(N)) \ge \rho(M, N),$$

(*) but for any two points M and N the inequality (*) will be equality. However, the proof of this fact is quite difficult (see N. Burbak and “General Topology” (Moscow, “Nauka”, 1975), problem 11 to § 2 of Chapter IX).

N. Vasiliev

M529. a) Polygon M' is the image of a convex polygon M at the same time with coefficient k = -1/2. Prove that there is a parallel translation of T by making T(M') ⊂ M.
b) For what coefficients of nometry k < 0 is true, similar to the statement for a convex polygon M in space?

a). At first glance, there is uncertainty in the conditions of the problem: it is not said what kind of ready-made polygon M' is created. We invite the reader to prove the following lemma about our polygons M, M': the image of the polygon M' under any parallel transfer can be obtained from M of some nometry with coefficient k (but with a different center), and, conversely, the image of the polygon M under any nometry with coefficient k can be obtained from M by some parallel transfer.

Let's move on to the solution. Let us choose among the vertices of the polygon M at (say, A, B and C), forming triangle ABC over the largest possible area (such will be found, since M is a finite number of vertices). Let O be the intersection point of the medians of triangle ABC. Distance image M'' of a polygon M at ready-type Γ with center O and coefficient k = -1/2 (Fig. 3). How do we

⟦folio 25⟧

noted, polygon $M''$ can be obtained from polygon $M'$ by parallel translation. It is clear that if $M''$ turns out to lie inside the triangle $ABC$ (and, moreover, inside the polygon $M$), then the problem will be solved.

Consider the triangle $A'B'C'$ formed by the midlines of the triangle $ABC$. Since $\Delta A'B'C' = \Gamma (\triangle ABC)$, the points $A', B', C'$ are the vertices of the polygon $M''$, with the triangle $A'B'C'$ having the maximum area among the triangles formed by the vertices of the polygon $M''$. Let now some vertex - say, $X$ - of the polygon $M''$ be in the triangle $ABC$, for example, on opposite sides of $[AB]$ (Fig. 4). But then the triangle $XA'C'$, obviously lying inside the polygon $M''$, would have an area greater than the triangle $ABC$, which is impossible. So, $M'' \subset \triangle ABC$.

Problem a) has been solved.

6) The solution to point 6) of the problem almost completely repeats what was stated above. First of all, if the word “polygon” is replaced by “polyhedron”, then the lemma will be correct. Further, the role of the triangle $ABC$ (maximum area) will be played by the tetrahedron $ABCD$, the vertices of which are the vertices of the polyhedron $M$, and the volume is the maximum among the volumes of all such tetrahedra. The role of the center is prepared $O$ perfectly plays the center of gravity of the tetrahedron $ABCD$ (as is known, it divides the segments connecting the vertices of the tetrahedron with the centers of gravity of opposite faces, in a ratio of 1:3). The attentive reader has probably already guessed that the statement in paragraph 6) will be true if we put $k = -1/3$. Since, obviously, it is even more true for $-1/3 \leq k < 0$, to completely solve the problem it remains to show that it is impossible to reduce the value of $k = -1/3$. To prove the denial of any statement, it is enough to refute it in some particular case. Let us refute it when the polyhedron $M$ is a regular tetrahedron.

To do this, let us prove the following statement: let $ABCD$ be a regular metrahedron and $A'B'C'D'$ its image with coefficient $k' > -3$ (Fig. 5); the center prepares, as we have seen, does not play a role); There is no parallel transfer in which the image of the metrahedron $ABCD$ would lie inside the metrahedron $A'B'C'D'$.

In fact, let us draw through the vertices of the tetrahedron $ABCD$ planes parallel to the opposite faces of the tetrahedron (through the vertex $A$ there is a plane parallel to the face $BCD$, etc.). The polyhedron (let's denote it $A''B''C''D''$), formed by these planes, will be a regular tetrahedron, preparing the metrahedron $ABCD$ with the coefficient of preparation $k'' = -3$ (the center is prepared - in the center of gravity of the tetrahedron $ABCD$). This means that this new tetrahedron is “larger” than the $A'B'C'D'$ tetrahedron (at least in volume)

⟦folio 26⟧

and therefore cannot be “pushed” into it by any parallel transfer. Let us now assume that there is a parallel translation $T$ such that $T$ ($ABCD$) $\subset A'B'C'D'$. Let’s “push” the edges of the terrahedron $A'B'C'D'$ “inward” a little, leaving them parallel to itself, up to touching the vertices of the image of the terrahedron $ABCD$ with a parallel translation $T$ (that is, with the vertices of the terrahedron $T$ ($ABCD$)). The resulting terrahedron is obviously congested by the earlier construction of the terrahedron $A''B''C''D''$ (“larger” than the terrahedron $A'B'C'D'$) and lies inside the terrahedron $A'B'C'D'$, which is impossible. This means that the required parallel transfer does not exist.

Note that the correct tetrahedron $ABCD$ was needed only for clarity.

For polytopes other than a terrahedron, the value of $k = -1/3$ can be reduced; for example, for centrally symmetrical convex bodies (not necessarily polyhedra), the “minimum” preparation coefficient is equal to -1. Thus, the edges and the coefficient of preparation can serve as a measure of the “asymmetry” of a convex body. Similar questions are discussed in the brochure by B. Grew and Baum in “Etides on combinatorial geometry and the theory of convex bodies” (M., “Nauka”, 1971) and in the book by V. G. Boltyansky and I. M. Yaglom “Viupklitse fizura” (M. - L., Gostekhidat, 1951).

In addition to the above solution to problem a), we know two more of its solutions: the first is very simple, but uses the “difficult” Helly theorem (see the solution to problem 19 from the indicated book by Boltyansky and Yaglom; there you can also find an analysis and application of Helly’s theorem); in the second preparation, the center of gravity O of the polygon $M$ is taken as a plane. It is very easy to verify that O has the required properties.

N. Netsvetaev

F538. A heavy rope is suspended at points $A$ and $B$ (Fig. 6). The absolute value of the tension force of the rope at point $C$ is 20 N. Find the mass of the rope.

Let us denote $m$ the mass of the rope, $\vec{T}_A$ and $\vec{T}_B$ the forces of tension of the rope at points $A$ and $B$. (The pushing forces at each point are directed tangentially to the rope). Since the rope is in equilibrium, the sum of the forces acting on it is zero:

$$\vec{T}_A + \vec{T}_B + mg = 0.$$

The sum of the projections of the forces acting on the rope on any axis, in part on the vertical axis $OY$, is also equal to zero. Hence,

$$T_{Ay} + T_{By} - m|\vec{g}| = 0,$$

where

$$m = \frac{T_{Ay} + T_{By}}{|\vec{g}|}.$$

Thus, in order to determine the mass of the rope, $T_{Ay}$ and $T_{By}$ must be determined. Let's find them.

The CB section of the rope is in equilibrium. This means that the sum of the projections onto the horizontal axis $OX$ of the tension force acting on the rope at points $C$ and $B$ is equal to zero:

$$T_{Cx} + T_{Bx} = 0.$$

Let us draw the forces $\vec{T}_C$ (Fig. 7) on an arbitrary convenient scale. It is directed tangentially to the rope at point $C$. Let us find the projection of the force $\vec{T}_C$ onto the axis $OX$. Now we draw a tangent to the rope at point $B$. The force $\vec{T}_B$ is directed along this tangent. On the horizontal axis we plot the projection of the force $T_{Bx}$ onto the axis $OX$, which is equal to $-T_{Cx}$. Having restored the perpendicular at point $K$ to the re-

⟦folio none⟧

Fig. 7.

Fig. 8.

section with a tangent at point $B$, we find the force $\vec{T}_B$. Now it is not difficult to find the projection of the force $\vec{T}_B$ on the vertical axis. It is determined by the length of the segment $KE$, taking into account the scale in which we drew the force $\vec{T}_C$. In our case $T_{By} \approx 22$ N.

Similarly, the force $\vec{T}_A$ of pulling the rope at point $A$ (Fig. 8) is constructed and its projection onto the axis $OY$ is found. In our case, it is equal to $\approx 9$ N.

Thus, $m = \frac{22 + 9}{9,8} \text{ кг} \approx 3,2 \text{ кг}$.

I. Slobodetsky

F539. figure 9 shows two closed thermodynamic cycles carried out with an ideal monatomic gas: $1 \rightarrow 2 \rightarrow 3 \rightarrow 4 \rightarrow 1$ and $1 \rightarrow 5 \rightarrow 6 \rightarrow 4 \rightarrow 1$. Which cycle has a higher efficiency? How many times?

The efficiency of the cycle is equal to the ratio of the work $A$ performed by the gas to the amount of heat $Q$ imparted to the gas per cycle. Numerically, the work is equal to the area limited by the cycle schedule. For the first cycle -

$$A_1 = (2 p_0 - p_0)(2 V_0 - V_0) = p_0 V_0,$$

for the second cycle -

$$A_2 = (4 p_0 - p_0)(2 V_0 - V_0) = 3 p_0 V_0.$$

Let's find the heats $Q_1$ and $Q_2$. In the first case, heat is transferred to the gas in sections $1-2$ and $2-3$. In this case, the gas heats up, and in section $2-3$ it also does work $A' = 2 p_0 V_0$. Therefore, $Q_1 = A' + \Delta U'$, $\Delta U'$ is the change in the internal energy of the gas. Since the gas temperature is minimum at point $1$ and maximum at point $3$, and the heat capacity of one kilomole of an ideal monatomic gas is $\frac{3}{2} R$,

$$\Delta U' = \frac{3}{2} R v (T_3 - T_1).$$

Here $v$ is the number of kilomoles of gas, $T_1 = \frac{p_0 V_0}{\nu R}$, $T_3 = \frac{4 p_0 V_0}{\nu R}$. Therefore $\Delta U' = \frac{9}{2} p_0 V_0$ and $Q_1 = \frac{13}{2} p_0 V_0$. Similarly, we find for the second cycle $A' = 4 p_0 V_0$ (in the area $5-6$), $\Delta U'' = \frac{3}{2} R v (T_6 - T_1) = \frac{21}{2} p_0 V_0$ and $Q_2 = \frac{29}{2} p_0 V_0$. Using the data obtained, we find:

$$\eta_1 = \frac{2}{13}, \eta_2 = \frac{6}{29}, \eta_1 / \eta_2 \approx 0,74.$$

A. Zilberman

⟦folio 28⟧

F540. Two inductance coils $L_1$ and $L_2$ are connected in parallel. The coils will have maximum points in the coils if a capacitor with a capacitance of $C$ (Fig. 10), pre-charged to a voltage of $U$?

Fig. 10.

Since the coils are connected in parallel, the voltage across them is the same: $U_{L_1} = U_{L_2}$. But $U_{L_1} = L_1 \frac{\Delta I_1}{\Delta t}$, $U_{L_2} = L_2 \frac{\Delta I_2}{\Delta t}$.

Hence,

$$L_1 \frac{\Delta I_1}{\Delta t} = L_2 \frac{\Delta I_2}{\Delta t}.$$

(1)

At the initial moment, the points in both coils are equal to zero, therefore from (1) it follows that the points $I_1$ and $I_2$ at any moment of time are such that

$$L_1 I_1 = L_2 I_2.$$

(2)

(This means that the maximum currents in the coils are reached simultaneously.)

It is clear that points $I_1$ and $I_2$ are maximum when the capacitor is charged. From the law of conservation of energy it follows that at this moment

$$\frac{CU^2}{2} = \frac{L_1 I_1^2}{2} + \frac{L_2 I_2^2}{2}.$$

(3)

From equations (2) and (3) we find:

$$I_1 = U \sqrt{\frac{L_2 C}{L_1 (L_1 + L_2)}}, I_2 = U \sqrt{\frac{L_1 C}{L_2 (L_1 + L_2)}}.$$

O. Savchenko

F541. The gap of the spark generator (Fig. 11) is adjusted to voltage $U$, and the resistance $R$ of the resistor is selected to the maximum; Determine the average power released across the resistor if the capacitor is successfully discharged during charging.

Fig. 11.

For steady source operation of the spark generator, it is necessary that the discharge in the spark gap does not affect the process of charging the capacitor. This is possible in the case when the time of charging the capacitor through the spark gap is much less than the time of charging it from the source to voltage $U$.

In this case, at zero voltage across the capacitor, there is no current in the spark gap, and the gap is restored to its dielectric property. The next breakdown will occur when the voltage across the gap, and therefore across the capacitor, reaches $U$.

During the time the capacitor is charged to voltage $U$, the battery does $A = q\varepsilon$ work, where $q = CU - \varepsilon$ is done on the capacitor. According to the law of conservation of energy $A = Q + CU^2/2$, where $Q - \varepsilon$ is the energy released during the charging of the capacitor on the resistor, $CU^2/2 - \varepsilon$ is the energy stored in the capacitor. Thus,

$$CU\varepsilon = Q + CU^2/2,$$

where

$$Q = CU\varepsilon (1 - U/2\varepsilon).$$

Since the charging time of the capacitor through the spark gap is short, it is possible to avoid the energy released during this time on the resistor.

If in 1 second the capacitor is charged $n$ times, then the average power released on the resistor is equal to

$$N = nCU\varepsilon \left(1 - \frac{1}{2} \frac{U}{2}\varepsilon\right).$$

P. Zubkov
