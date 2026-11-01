---
id: 1977-1-resheniya-zadach-m379-m381-m384-f387-f392-0fd881b0
issue: kvant_1977_1
year: 1977
number: "1"
title: Solutions to problems M379, M381—M384; F387—F392
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 37
page_labels: 27, 28, 29, 30, 32, 35
tag: SMUD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5d29bfe3b662c7be1c1caceb4419435f25470cde16185e137482e8d953d4c26c
prompt_sha256: draft-1
translated_from: content/ru/1977/01/articles/11_resheniya-zadach-m379-m381-m384-f387-f392-0fd881b0.md
source_content_sha256: 433bfa5330f38e24cb3d48e9ea6d82b5b223946463a0c8baf9046ebad6b4b2da
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 27⟧

F434. What is the amount of heat in resistance $R$ when equilibrium is established after closing the switch $K$ (Fig. 2), if the capacitor was pre-charged to a potential difference $2U$? E.m.f. source $U$, capacitance of the capacitor $C$. The internal resistance of the source is negligible.

F435. In the setup shown in figure 3, the coupling $M$ is attached to two identical springs with spring constants $k=10 \text{ н/м}$. The coupling can slide along the horizontal rod $AB$ without friction. The installation rotates with a constant angular velocity $\omega=4,4 \text{ rad/сек}$ around a vertical axis passing through the middle of the rod. Find the period of small oscillations of the coupling. Coupling weight $m=0,2 \text{ ке}$.

At what value $\omega$ will there be no vibrations of the coupling?

F436. The density of a gas consisting of a mixture of helium and argon at pressure $152 \text{ кн/м}^2$ and temperature $27^\circ\text{C}$ is equal to $2,00 \text{ ке/м}^3$. How many atoms of helium are there in the $1 \text{ cm}^3$ gas mixture?

F437. A wire frame in the shape of a right triangle with an angle $\alpha=30^\circ$ is placed in a vertical plane as shown in figure 4. Two weights with masses $m_1=0,1 \text{ ке}$ and $m_2=0,3 \text{ ке}$ connected to each other by a thread can slide along the wire without friction. What is the tension of the thread and the angle $\beta$ in the equilibrium position of the weights? Is this equilibrium stable?

Problem solutions
M379, M381 — M384; F387 — F392

M379. On each of several pieces of randomly shaped paper there is a mark (of arbitrary shape). Let's call a blotter suitable for a given piece if it can be stirred inside the piece so that it covers the blotter. Let a set of blotters in the shape of circles of different radii have the maximal property: for any two given pieces there is a blotter suitable for each of them. Prove that the model in this set contains one blotter suitable for all pieces.

Consider one piece of paper. Let $p$ and $P$ be blotters of the smallest and largest radii suitable for a given piece.

Let us prove that a round blotter $P$ of any intermediate radius is also suitable for this piece. (Note that for blotters of a different shape - for example, for padded rectangles - a similar statement is, generally speaking, false.) Let the circles $p$ and $P$ be located on the piece so that each of them covers the blotter. Then the circle $P$ can be arranged so that it is contained in the union and contains the intersection of $p$ and $P$ (Fig. 1):

klyaska $\subset (p \cap P) \subset \Pi \subset (p \cup P) \subset \text{кусок}$.

Let us now prove the statement of the problem. Let us put in correspondence with each of the given $n$ pieces a segment $[r, R]$ of the numerical axis, where $r$ and $R$ are the radii of the smallest and least suitable blotter for it. According to the conditions, any two segments have a common point.

Let $p$ be the largest of the left ends of these segments; this number $p$, very indo, is not less than the left end of any from-

⟦folio 28⟧

cutting and not greater than the smallest right endpoint, that is, $\rho$ belongs to all $n$ segments.

The number $\rho$ is the radius of some of our blotters. It has been proven that it will be suitable for all pieces.

In the final part of the solution, we used the one-dimensional version of the theory. Hell, for convex figures on the plane: if any three of the $n$ convex figures have a common point, then all $n$ figures have a common point - for convex figures on a line, i.e. for segments, it is enough to require that any two have a common point.

N. Vasiliev

The solution to problem M380 will be published in the next issue of our magazine.

M381. 6 educational class activists and 30 different commissions. Each two commissions differ in composition, but necessarily “overlap”, that is, they have a common name. Let us prove that it is possible to form another commission that intersects with each of these 30 commissions.

Fig. 1.

M382. Given a polynomial $f(x) = x^n + a_1x^{n-1} + a_2x^{n-2} + \dots + a_n$ with the target coefficients and natural numbers $k$ and $p$. Let us prove that if none of the numbers $f(k), f(k+1), \dots, f(k+p)$ is divisible by $p+1$, then the equation $f(x) = 0$ has no rational roots.

It is not difficult to show that a set of $n$ has exactly $2^n$ subsets. In particular, six activists could, in principle, make up 64 commissions (including the “empty” commission).

Let us divide all possible 64 subsets of the set of activists into pairs; in each pair there are two disjoint subsets $A$ and $A',$ the union of which is all these sets (Fig. 2). Since there are 32 pairs, and the commission is 30, then in each pair both subsets are not empty and are not commissions. Consider one of these subsets $A$. If it intersects with all 30 commissions, then the problem is solved. If it does not intersect with any commission $B$, then the second subset from the selected pair $A$ contains this commission $B$, and since $B$ intersects with all other commissions, then the subset $A \supset B$ is considered - even more so.

In conclusion, we note that more than 32 commissions, subject to the conditions of creation, are generally impossible (prove it!).

S. Fomin

First of all, note that if the equation $f(x) = 0$ has a rational root, then this root is an integer. Indeed, let $p/q$, where $p$ and $q$ are coprime, be the root of our equation. Then $p^n + a_1p^{n-1}q + a_2p^{n-2}q^2 + \dots + a_nq^n = 0$, which implies that $p$ is not coprime with $q$.

Let us now assume that the equation $f(x)$ is the integer root $x_0 = m$, that is, $f(m) = 0$. Then, by Bezout’s theorem, we can represent the polynomial $f(x)$ in the form

$$f(x) = (x - m)g(x),$$

where $g(x)$ is a polynomial with integer coefficients.

Substituting in accordance with (*) together $x$ the values ​​$k, k+1, \dots, k+p$, we obtain

$$f(k) = (k - m)g(k),$$

$$f(k+1) = (k+1 - m)g(k+1),$$

$$f(k+p) = (k+p - m)g(k+p).$$

Since one of the $p+1$ consecutive integers $k - m, k+1 - m, k+2 - m, \dots, k+p - m$ is divisible by $p+1$, then one of the numbers $f(k), f(k+1), \dots, f(k+p)$ is divisible by $p+1$. It follows from this that the polynomial discussed in the problem does not have integer roots.

T. Raikov

⟦folio 29⟧

M383. Let $a$ and $b$ be two natural numbers. Let us prove that if $ab$ is integer, then we can also find natural numbers $c$ and $d$, that $a^2 + b^2 + c^2 = d^2$, and if $ab$ is not integer, then the maxims $c$ and $d$ cannot be found.

Fig. 3.

M384. Two identically oriented squares $OABC$ and $OA_1B_1C_1$ have a common vertex $O$. Let us prove that the lines $AA_1$, $BB_1$ and $CC_1$ pass through one point.

Fig. 4.

F387. Two bellosipedis in circus edum with identical linear velocities $v$ along circles of radii $R_1$ and $R_2$, the centers of which are at a distance $l$ from each other ($l < R_1 + R_2$). One of the bellosipedisms moves clockwise, the other counterclockwise. Namely described by the speeds of bellosipedisms (in the coordinate system associated with one of them) at the moment when they are both on linear lines passing through the centers of the circle, at points: a) $A_1$ and $A_2$; b) $A_1$ and $B_2$; c) $B_1$ and $B_2$; f) $B_1$ and $A_2$ (Fig. 5).

1). Let $ab$ be even.

a) If $a$ and $b$ are of different parities (one is even, the other is not), then $a^2 + b^2 = 2N + 1$. Then we put $c = N$, $d = N + 1$. We get
$$d^2 - c^2 = (d + c)(d - c) = 2N + 1 = a^2 + b^2.$$

6) If $a$ and $b$ are both even, then $a^2 + b^2 = 4N$. In this case we put $d = N + 1$, $c = N - 1$. Then
$$d^2 - c^2 = (d + c)(d - c) = 2N \cdot 2 = a^2 + b^2.$$

2). Let $ab$ be odd: $ab = 2n + 1$. Then the numbers $a$ and $b$ are both odd, and their sum is even: $a + b = 2m$. We have:
$$a^2 + b^2 = (a + b)^2 - 2ab = 4m^2 - 4n - 2,$$
that is, $a^2 + b^2$ is divisible by 2, but not divisible by 4. Therefore, $a^2 + b^2 \neq d^2 - c^2$ is not divisible by any natural $c$ and $d$: if $c$ and $d$ are of the same parity (both even or both odd), then $d^2 - c^2 = (d + c)(d - c)$ is divisible by 4, and if $d$ and $c$ is of different parity, then $d^2 - c^2$ is not divisible by 2.

M. Gerver

Our solution will show that a similar statement is true for regular $n$-gons with a common vertex, and in general for similar inscribed $n$-gons $OAB \dots Z$ and $OA_1B_1 \dots Z_1$.

Let us describe circles around both $n$-gons. Let them intersect at points $O$ and $L$ (Fig. 3). If straight line $l$, passing through $L$, rotates uniformly around $L$ with angular velocity $\omega$, then the second points of intersection $M$ and $M_1$ of straight line $l$ with both circles of motion of each along its own circle uniformly with angular velocity $2\omega$ (degree magnitudes $\overline{OM}$ and $\overline{OM}_1$ are twice the degrees of magnitude $\widehat{MLO} = \widehat{M_1LO}$). Thus, the point $M_1$ passes the vertices $O$, $A_1$, $B_1$, ..., $Z_1$ of the polygon $OA_1B_1 \dots Z_1$ exactly at those moments in time when $M$ passes, respectively, the vertices $O$, $A$, $B$, ..., $Z$ of polygon $OAB \dots Z$. From here it is clear that all lines $AA_1$, $BB_1$, ..., $ZZ_1$ intersect at one point - point $L$, the second point of intersection of the circles circumscribed around $(рис. 4)$.

N. Vasiliev

In the problem statement, the speed of each vertex $O$, $A_1$, $B_1$, ..., $Z_1$ of the polygon $OA_1B_1 \dots Z_1$ is given exactly at those moments of time when $M$ passes, respectively, the vertices $O$, $A$, $B$, ..., $Z$ polygon $OAB \dots Z$. From here it is clear that all lines $AA_1$, $BB_1$, ..., $ZZ_1$ intersect at one point - point $L$, the second point of intersection of the circles circumscribed around $(рис. 4)$.

The condition requires finding a relative coordinate system (associated, for example, with a circus arena). This speed is usually called absolute speed.

According to the condition, it is required to find the relative speed of the magnitude of its speed in relation to the moving coordinate system associated with one of them) at the moment when they are both on linear lines passing through the centers of the circle, at the points: a) $A_1$ and $A_2$; b) $A_1$ and $B_2$; c) $B_1$ and $B_2$; e) $B_1$ and $A_2$ (Fig. 5).

⟦folio 30⟧

The speed of the second bicycle at point $A_2$ is equal to

$$\vec{v}_{\text{пер}}^{\text{отт}} = \omega \cdot O_1 A_2 = \frac{v}{R_1} (l + R_2),$$

and at point $B_2$ -

$$\vec{v}_{\text{пер}}^{\text{отт}} = \omega \cdot O_1 B_2 = \frac{v}{R_1} (l - R_2).$$

At both points the transfer velocities are perpendicular to the direct
my $A_1 A_2$ and directed in one direction (at figure 6 -
up).

Absolute, relative and portable point velocities
related by the relation

$$\vec{v}_{\text{абс}} = \vec{v}_{\text{отт}} + \vec{v}_{\text{пер}},$$

that is, the absolute speed is always equal to the vector (geo-
metric) the sum of relative and figurative speed.
Hence,

$$\vec{v}_{\text{отт}} = \vec{v}_{\text{абс}} - \vec{v}_{\text{пер}}.$$

Let us find the relative speed of the second bicycle when it is at point $A_2$. In this case, the absolute speed is equal to $$\vec{v}_{\text{абс}} = v$$ according to the model and directed downwards (Fig. 7), and the portable speed according to the model is equal to $$\vec{v}_{\text{пер}} = \frac{v}{R_1} (l + R_2)$$ and directed upwards. Therefore

$$\vec{v}_{\text{отт}} = v + \frac{v}{R_1} (l + R_2) = v \frac{R_1 + R_2 + l}{R_1}.$$

This speed has been adjusted downwards. The result obtained does not depend on the point at which the first movement is located at a given moment.

At the moment when the second speed is at point $B_2$, $$\vec{v}_{\text{абс}} = v, \quad \vec{v}_{\text{пер}} = \frac{v}{R_1} (l - R_2)$$ and both speeds are directed equally (upward to figure 7). Therefore, at this moment the speed of the second bicycle relative to the first is equal according to the model

$$\vec{v}_{\text{отт}} = v - \frac{v}{R_1} (l - R_2) = v \frac{R_1 + R_2 - l}{R_1}$$

and directed upwards. This result also does not depend on what point the first movement is located at a given moment.

The speed of the first bicycle is determined in a completely similar way in the coordinate system associated with the second. At point $A_1$ it is directed downward and equal according to the model

$$\vec{v}_{\text{отт}} = v \frac{l + R_1 + R_2}{R_2},$$

and at point $B_1$ the relative speed is directed upward and, according to the model, is equal to

$$\vec{v}_{\text{отт}} = v \frac{R_1 + R_2 - l}{R_2}.$$

F388. In a vertical cylinder of variable cross-section (Fig. 8) there are moles of air between the pistons. The masses of the pistons are $m_1$ and $m_2$, their areas are $S_1$ and $S_2$, respectively. The parts are connected by a rod $l$ and are located at equal distances from the joint

⟦folio 32⟧

Fig. 11.

at figure 10, can be replaced by the equivalent circuits shown at figure 12. In this case (Fig. 12, a)
$$R_{AB} = R_{BC} = R + R_1 \text{ и } R_{AC} = 2R.$$

Fig. 12.

We will find resistances $R_{A'B'}$ and $R_{A'C'}$ by successively replacing several resistors connected in parallel or in series with one resistance. For participant $A'B'$ (Fig. 13)
$$R_{A'B'} = 2r + R^{***} = 2r + \frac{rR^{**}}{r + R^{**}} =$$
$$= 2r + \frac{r(R + R^*)}{r + R + R^*} = 2r + r \frac{R^2 + 2R_1R + R_1r + Rr}{(r + R)^2 + 2(r + R)R_1}.$$

When calculating resistance $R_{A'C'}$, we take into account that points $O$ and $E$ (Fig. 14), due to the symmetrical circuit, have the same potential, and therefore resistance $R_1$ can simply be excluded. As a result we get
$$R_{A'C'} = 2r + R' = 2r + \frac{2rR}{r + R}.$$
Since $R_{AC} = R_{A'C'}$,
$$2R = 2r + \frac{2rR}{r + R},$$
where
$$R = \frac{1}{2}r(1 + \sqrt{5}).$$

Fig. 13.

⟦folio 35⟧

l. The coefficient of debate between the dock and the cylinders is k. Prove that if the dock, which is in an equilibrium position, should remain silent in the horizontal direction, it will perform a harmonious oscillation, and find the period of these oscillations. What will be the motion of the dock if the direction of the cylinders is reversed?

Fig. 17.

Fig. 18.

When the cylinders rotate in the direction indicated in the conditions, the force applied from the left cylinder is directed to the right, and from the right cylinder - to the left (see Fig. 17). If the dock is in equilibrium, then the friction forces are equal modulo. Consequently, the normal reaction forces of each of the cylinders are also equal. This means that the center of gravity of the docks in equilibrium is at the same distance from each of them.

Let the dock now be displaced from its equilibrium position by a distance $x < l/2$, for example, to the right (Fig. 18).

In this position, the normal pressure forces $\vec{N}_1$ and $\vec{N}_2$ will no longer be equal to each other, and therefore will not compensate each other and the dry friction forces $\vec{F}_1$ and $\vec{F}_2$. The resulting force $\vec{F}_1 + \vec{F}_2$ will impart horizontal acceleration to the dock.

Let's find it by calculating the preliminary $|\vec{N}_1|$ and $|\vec{N}_2|$ from the condition of the absence of vertical acceleration:

$$|\vec{N}_1| + |\vec{N}_2| - M |\vec{g}| = 0$$

and the conditions for the moment of external forces of the relative axis passing through the point $B$ to be equal to zero:

$$|\vec{N}_2| \left( \frac{l}{2} - x \right) - |\vec{N}_1| \left( \frac{l}{2} + x \right) = 0.$$

From here

$$|\vec{N}_1| = M |\vec{g}| \left( \frac{1}{2} - \frac{x}{l} \right), \quad |\vec{N}_2| = M |\vec{g}| \left( \frac{1}{2} + \frac{x}{l} \right).$$

Therefore, the process F of the resulting force on the X axis directed to the right is equal to

$$F = |\vec{F}_1| - |\vec{F}_2| = k |\vec{N}_1| - k |\vec{N}_2| = - \frac{2kM |\vec{g}|}{l} x.$$

We see that the resulting force is proportional modulo to the displacement $x$ docks from the equilibrium position and is directed in the direction opposite to the displacement, that is, to the equilibrium position. Thus, this force is a restoring force, similar to that generated when a pendulum oscillates. Consequently, the dock makes harmonious vibrations.

The period of oscillation can be found by writing the equation of motion of the dock. For X-axis projections

$$Ma_x = - \frac{2kM |\vec{g}|}{l} x, \quad a_x = - \frac{2k |\vec{g}|}{l} x.$$

The modulus of the proportionality coefficient between displacement and acceleration is the square of the cyclic oscillation frequency:

$$\omega_0^2 = \frac{2k |\vec{g}|}{l}.$$

Oscillation period

$$T = \frac{2\pi}{\omega_0} = 2\pi \sqrt{\frac{l}{2k |\vec{g}|}}.$$

When the direction of rotation of the cylinders is reversed, the resulting horizontal force will also change its direction. When mixing the dock, this force will not return it to the equilibrium position, but, on the contrary, will take it away the more, the greater the initial mixing. As a result, the dock will come off the cylinders.

The device under consideration was first proposed by Professor N. E. Zhukovsky and bears his name.

B. Bukhovtsev
