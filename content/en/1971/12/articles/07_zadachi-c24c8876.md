---
id: 1971-12-zadachi-c24c8876
issue: kvant_1971_12
year: 1971
number: "12"
title: Problem M116—M120; F128—F132
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 33
page_last: 40
page_labels: 31, 32, 34, 35, 37, 38
tag: MDFJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7c5eb0d4879de0060e66bcfdf44b6d6dc0120f0b483c1f80bc99efae3695e195
prompt_sha256: draft-1
translated_from: content/ru/1971/12/articles/07_zadachi-c24c8876.md
source_content_sha256: 86bbd6d744709928f1b31cdd8ddbba9ab60adb3c506e60322870b482ece5af2d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 31⟧

TASKS

M116. Prove that if you connect the midpoints of successive sides of a convex $n$-gon $M$ (Fig. 1), then the resulting polygon
a) perimeter is not less than half of perimeter $M$ ($n \geqslant 3$);
6) the area is at least half the area $M$ ($n \geqslant 4$).
G. A. Galperin

Fig. 1.

M117. Several people observe the snail for $t$ minutes. Each one is observed for approximately 1 minute and then, during this minute, the snail crawls approximately 1 meter. At no point in time was the snail left unobserved. What kind of path could she have crawled in these $t$ minutes?

Try solving this problem first for small values ​​of $t$, such as $t=2,5$.

N. N. Konstantinov

M118. With four sides of a chessboard of size $n \times n$, a border two fields wide is constructed.

Prove that this border can be bypassed by a chess knight by raising on each square once and only once, if and only if $n-1$ is a multiple of 4.

Y. I. and Y. Y. Sorkinyi

M119. Prove that if you select a point on each face of a convex polygon and draw from this point a vector that is directed perpendicular to the corresponding face to the outside and whose length is equal to the area of ​​this face, then the sum of such vectors will be equal to zero.

N. B. Vasiliev

M120. In some sets, the operation * is introduced, which assigns each two elements $a$ and $b$ of this set an element $a*b$ from this set. It is known that
1) for any three elements $a$, $b$ and $c$
$a*(b*c) = b*(c*a)$;
2) if $a*b = a*c$, then $b=c$;
3) if $a*c = b*c$, then $a=b$.
Prove that the operation *
a) commutative, that is, for any two elements $a$ and $b$
$a*b = b*a$;
6) associative, that is, for any three elements $a$, $b$ and $c$
$(a*b)*c = a*(b*c)$.

S. A. Yanovskaya

⟦folio 32⟧

Fig. 2.

F128. A thin homogeneous stick is classified so that it rests on two planes inclined to the horizon at angles α and β; the angle between the planes is 90° (Fig.2). What will happen to the wand? What will be its final position if the friction between the stick and the planes is very small?

B. B. Bukhovtsev

F129. A body located at point A inside a stationary hollow sphere. In what case does it reach the lower point B of the sphere more quickly: if it slides along the surface of the sphere or if it slides along straight AB? Friction in both cases is negligible, the initial velocity of the body is zero and the distance AB is much less than the radius of the sphere.

G. L. Komkin

F130. Inside the smooth sphere there is the smallest loaded ball. What is the size of the contamination?

placed at the bottom point of the sphere so that the ball is held at its top point? The diameter of the sphere is d, the charge of the ball is q, and its mass is m.

G. L. Komkin

F131. A light glass tube of length l and cross-section s, filled entirely with rue and sealed at one end, is located horizontally in a tank with rue near the surface of the rue. What minimum work must be done in order to move the tube to a vertical position in which its open end will touch the surface of the rut?

F132. A cylinder of mass m was untwisted and placed between two closed planes located at an angle of 2α to each other (Fig. 3). Knowing that the coefficient of friction between the cylinder and the planes is equal to k, determine the forces with which the cylinder acts on the walls.

Fig. 3.

⟦folio 34⟧

Note that in more modern algebra textbooks the equality of polynomials is usually understood as the equality of the corresponding coefficients (after reduction to the standard form $a_0 + a_1x + a_2x^2 + \dots + a_nx^n$). If all the equalities in our problem are understood this way, then in the transition from (3) to (4) the word “obviously” must be replaced with the word “by definition”. We will devote separate notes in «Kvant» next year to a detailed discussion of what a polynomial is and how to accurately define various operations on polynomials.

A. L. Toom

M75

a) Prove that in any convex polyhedron the sum of the lengths of all edges is greater than triple the diameter. (The diameter of a polyhedron is called the smallest possible segment with ends at the vertices of the polyhedron).

b) Prove that for any two vertices $A$ and $B$ of a convex polyhedron there are three broken lines, each of which goes along the edges of the polyhedron from $A$ and $B$ and no two go along the same edge.

b) Prove that if two edges are cut in a convex polyhedron, then for any two of its vertices $A$ in $B$ there is a broken line, and a line from $A$ to $B$ along the remaining edges.

d) Prove that in problem 6) it is possible to choose three broken lines that pairwise do not have common vertices, with the exception of the ends $A$ and $B$.

Obviously, problem d) implies problem 6), and problem 6) implies c) and a)*. We will sketch short proofs of a) and b) and solve d).

a) Let $AB$ be the diameter of $M$. Let's project all edges $M$ onto $AB$. Let's see how many points are projected into some point $C$ lying inside $AB$. If through $C$ we draw the plane $P$ perpendicular to $AB$, then $P$ will intersect $AB$ along the convex polygon. The vertices of this polygon (and there are at least three of them!) are the intersection points $P$ with the edges $M$ and, therefore, at least three edges $M$ are projected into each internal point of the segment $AB$. From here it is easy to derive the statement of problem a).

When solving problem b) and d) we will use the following intuitively obvious statement: for any two vertices $A$ and $B$ of the convex polyhedron $M$ there is a path from $A$ to $B$ along the edges $M$. We leave the proof to the reader.

*) We also note that using the Ford-aFalerson theorem on the maximum flow and minimum cut (see «Kvant» No. 4, 1970, p. 24, problem 4) it is easy to derive 6); it is enough to apply this theorem to the network formed by the edges of a polyhedron (which edge is counted twice—“there” and “back”).

b) Let the edges $r_1$ and $r_2$ be cut. Obviously, there is a path $L_1$ connecting the ends of $r_1$ and not passing through $r_2$. Indeed, two faces are attached to the edge $r_1$. Edge $r_2$ does not lie on at least one of these faces, so $L_1$ can be taken to be a path along its boundary. Similarly, for the edge $r_2$ there is a path $L_2$. Let us now consider two arbitrary vertices $A$ and $B$. As mentioned above, there is a path $L$, and a path from $A$ to $B$ along the edges $M$. By replacing the edge $r_1$ in the path $L$ with the path $L_1$, and the edge $r_2$ with the path $L_2$ (if, of course, these edges meet in $L$), we obtain the desired path along the remaining edges. Note that this path may have self-computations, which, however, are not difficult to establish.

d) As was said above, for any two vertices $A$, $B$ of a convex polyhedron there is a path from $A$ to $B$, and a path along the edges. Let's call the length of such a path the number of edges of which it consists, and call it the distance between $A$ and $B$ - let's denote it by $d(A,B)$ - the length of the shortest (by the number of edges) path. To prove the statement of the problem, we fix the point $A$ and will carry out induction on the distance between the points $A$ and $B$. If $d(A,B) = 1$, then $A$ and $B$ lie on the same edge, and the statement is obvious, since one can go from $A$ to $B$ along the edge $AB$ and the faces of two faces adjacent to $AB$. Let us assume that the statement has been proven for all vertices lying from $A$ at a distance $n-1$. Let $d(A,B) = n-1$ and $d(B',B) = 1$. Let's consider all faces containing $B'$. The set of all edges belonging to all such edges consists of “radushkas” (edges with endpoint $B'$) and a “ring” (which forms the remaining edges). However, one of the vertices of the ring is the point $B$. By the induction hypothesis, there is a path $l_1, l_2, l_3$ from $A$ to $B'$ that has no pairwise common points except the ends. Obviously, each of these three paths passes through at least one vertex of the ring. Such vertices of the ring are called vertices $A_1$ and $A_2$ (one of them may be vertex $B$). There are two possible cases.

Case 1. Occupy vertices $A_1$ and $A_2$ belong to different paths, say $l_1$ and $l_2$. Then we construct the path from $A$ to $B$ as follows. The first path: from $A$ to $A_1$ to $l_1$, then from $A_1$ to $B$ along the ring (note that by constructing the point $A_1$ in the last section we do not intersect with paths $l_2$ and $l_3$. The second path: from $A$ to $A_2$ to $l_2$, then from $A_2$ to $B$ along the ring. The third path: from $A$ to $B'$ to $l_3$, then along the edge $B'B$. Obviously, the three paths constructed in pairs have no common points except the ends.

Case 2. Occupy vertices $A_1$ and $A_2$ belong to the same path, say $l_1$.

⟦folio 35⟧

Let us then determine which of these vertices will be equal when moving from $A$ to $B^1$ along $l_1$ and take the segment $l'_1$ of the path $l_1$ from $A$ to the first of these vertices. After this, the distance is three paths $l'_1, l_2, l_3$, the distance of the set of vertices of the bulb occupied by path $l'_1, l_2, l_3$ and we will again carry out the previous calculations in relation to these tramuts. If we encounter case 1, then we will construct the required paths in the manner described above, but if we encounter case 2 again, then we will construct the distance of the new triple path $l'_1, l_2, l_3$. If case 2 arises for this triple, then we will distance a new triple, etc. Since we are moving further along the column and there are vertices on the column that belong to the paths $l_2$ and $l_3$, then at some step we will get case 1 and the required paths from $A$ to $B$ will be constructed. Problem d) solution. An even stronger statement is true: for any two vertices $A$ and $B$ one can find three chains of faces that do not have common faces and in each of which the first face contains the vertex $A$, the last one contains the vertex $B$, and neighboring faces have a common edge.

A. G. Kushiirenko

M76

In a company of $n$ people, every two strangers have two mutual acquaintances, and every two acquaintances there are no more mutual acquaintances. Prove that in this company each person knows the same number of people and has a common edge.

For each person, $X$ will be denoted by $m_X$ the number of his acquaintances.

Let $A$ and $B$ be familiar (Fig. 1). Let us denote by $M_A$ the set of acquaintances, and $A, M_B$ is the set.

Fig. 1.

The cruelty of acquaintances $B$. Let's prove that

(1) $M_A$ and $M_B$ do not have common elements,
(2) each of $M_A$ has exactly one acquaintance in $M_B$ and
(3) each of $M_B$ has exactly one acquaintance in $M_A$.

Statement (1) immediately follows from the condition: $A$ and $B$ cannot have common acquaintances. Let's prove (2); (3) proves similarly. Let $X \in M_A$ (this notation means “$X$ belongs to the set $M_A$”). Or $X$ is $B$, and then, according to (1), he has only one acquaintance in $M_B$ - $A$ himself. Or $X \neq B$, then, according to (1), $X$ is unfamiliar with $B$, and, therefore, $X$ and $B$ must have, in addition to $A$, exactly one common acquaintance, that is, $X$ has exactly one acquaintance in $M_B$, which is what needs to be proven. From (2) and (3) it follows that a one-to-one correspondence can be established between the sets $M_A$ and $M_B$, therefore $m_A = m_B$.

So, if $A$ and $B$ are familiar, then $m_A = m_B$. If $A$ and $B$ are unfamiliar, then they have a common friend $C$, and, therefore, $m_A = m_B$.

$A$ sent us much clearer solutions of this type. Zinchenko from Arkhangelsk, V. Lozinov and A. Slinkin from Moscow, A. Karimov from Ufa, K. Radyunov from Irkutsk, V. Pronin from Odessa, V. Faimelevy from Armavir, S. Gritsoryan from Baku.

Many readers have solved the inchete problem. For each person $A$ let $M_A$ denote the set of his acquaintances, and $N_A$ the set of those not acquainted with $A$. Then each element from $N_A$ can be associated with a pair of elements from $M_A$ (those with whom he is familiar), and it is not difficult to prove that this correspondence between the set $N_A$ and the set of all possible pairs of elements $M_A$ will be one-to-one. Consequently, if $M_A$ contains $m_A$ elements, then $N_A$ contains $\frac{m_A(m_A-1)}{2}$, and in total there are $n = 1 + m_A + \frac{m_A(m_A-1)}{2}$ people in the company. This equality is true for any person $A$. But the equation

$$n = 1 + x + \frac{x(x-1)}{2}$$

has (at $n > 1$) only one positive root, therefore $m_A$ is the same for all $A$. (A similar solution is analyzed in A. Leman’s book “Collection of Moscow Mathematical Optimization Problems”, problem XXIII, 11, 10, 3).

It is interesting to find out at what $n$ such companies actually exist. We do not know the complete answer to this question. We have seen that $n = \frac{m(m+1)}{2} + 1$, where $m$ is the number of acquaintances of one person, but not for any such $n$ company is essential. For example, it is not difficult to prove

⟦folio 37⟧

Fig. 6.

This answer was added by O. Zaumyslov (Zelenograd, Moscow region), A. Zeleny (Izmanl, Odessa region), V. Rozhkin (Perm), N. Fedin (Omsk), A. Demidov (Moscow), A. Zhukov (Kirovsk, Khariza district, Donetsk region), V. Kovtun (Kyiv), A. Vorobyov (Torzhok Kalininskaya region).

F85

Is it possible to check a closed process (cycle) with an ideal gas so that points A and B (Fig. 7) lie on the same isotherm?

The temperatures $T_1$ and $T_2$, which correspond to the isotherms drawn at figure, and the volume $V_1$ (or $V_3$) are given. Temperatures $T_1$ and $T_2$ define two isotherms:

$$pV = \frac{m}{\mu}RT_1 \quad \text{and} \quad pV = \frac{m}{\mu}RT_2$$

(m is the mass of the gas, μ is the mass of one gram molecule of it, R is the gas constant). Since the volume $V_1$ is given, we know points C and E of the cycle: volume $V_1$ and $V_3$ ($V_3 = V_1 \frac{T_2}{T_1}$), temperatures $T_1$ and $T_2$, and pressure $p_2 = \frac{m}{\mu}RT_1V_1$.

All other points in the cycle can be determined.

Fig. 7.

View only when we specify one of the points - B or A.

We will assume that we have a given volume $V_2$. It defines point B ($P_B = P_2$, $V_B = V_2$, $T_B = T_1 \frac{V_2}{V_1}$) and point D ($V_D = V_2$, $T_D = T_2$, $p_D = p_3 = \frac{m}{\mu} \frac{R T_2}{V_2}$). Point A lies on the isochore AD and on the isobar AC. Therefore $p_A = p_3 = \frac{m}{\mu} \frac{R T_2}{V_2}$, $V_A = V_1$ and $T_A = T_2$, $\frac{V_1}{V_2}$.

The gas temperatures at points A and B are the same if $V_2$ is chosen so that

$$T_2 \frac{V_1}{V_2} = T_1 \frac{V_2}{V_1},$$

that is, if $V_2 = V_1 \sqrt{\frac{T_2}{T_1}}$. The gas temperature at points A and B of the cycle in this case is equal to $T = \frac{p_2V_2\mu}{mR} = \sqrt{T_1T_2}$ (since $p_2V_2 = p_2V_1 \sqrt{\frac{T_2}{T_1}}$ and $p_2V_1 = \frac{m}{\mu} RT_1$).

The correct solution is the addition of N. Fedin (Omsk).

F86

In Millikan's experiment, the position of drops with mass $10^{-5}$ e is determined with an accuracy of 10 μm. What is the uncertainty in determining its speed?

Due to the uncertainty principle $\Delta p \Delta x \geq h$. Therefore $\Delta v \geq \frac{h}{m \Delta x}$. That is, the speed of the drop cannot be changed with an accuracy greater than $10^{-16}$ cm/sec.

This answer was added by B. Glukhovsky (Sverdlovsk), B. Kovtun (Kyiv) and A. Zlomnik (Zhukovsky, Moscow region).

I. Sh. SLOBODECHY

F87

Source of spherical waves of motion on water surfaces with speed u. Draw pictures of waves on surface water when the wave speed v is greater and less than the speed of the source.

Waves generated on surface water by a stationary source; have the form of concentric circles (Fig. 8, a). If the source is moving, then the waves that it generates at later moments in time are mixed in the direction of movement of the source. Let the speed of the source be less than the speed of the waves. Then the wave front will surround the source, and the wave pattern will be as shown in figure 8, b. However, if the speed of the source is greater than the speed of wave propagation, then the wave front can no longer

⟦folio 38⟧

Fig. 8.

can overtake the source, and the waves will travel inside the angle formed by two rays emanating from the source (Fig. 8, c). The magnitude of the angle is easily found from figure. During the time during which the source travels the distance AO, the front of the wave emitted at point A travels the distance AB, and $\frac{AB}{AO} = \frac{v}{u}$. That's why

$$\sin \alpha = \frac{v}{u}.$$

The correct solution was sent by A. Zlomnik (Zhukovsky, Moscow region), V. Kovtun (Kyiv), N. Fedin (Omsk), A. Demidov (Moscow), A. Zeleny (Izmail, Odessa region), O. Zamyslova (Zelenograd, Moscow region), G. Zaitsev (Gagra), V. Belov (Vologda), N. Sidelev (Tsiropinsk, Kherson region), O. Trunov (Jalal-Abad Kyrgyzstan, USSR), G. Furman (Chernivtsi, Ukrainian SSR), S. Araslanova (Nikhne-Ivkino, Kumensky district, Kirov region).

L. G. Aslamaov

F88

A vessel filled with sand moves with horizontal acceleration, as a result of which the surface of the sand is inclined to the horizon at a certain angle. The top of the vessel is closed with a lid. How will this angle change if the vessel is filled to the top with water?

Consider a fluid element with mass Δm (Fig. 9). Two forces act on it: the force of gravity Δmg and the force N - the resultant of the pressure forces from the surrounding fluid. Under the influence of these forces, the fluid element moves horizontally with acceleration a. This means that the resultant forces Δmg and N are directed horizontally and equal to Δma. For this to be possible, the force N must make an angle α with the vertical such that tanα = $\frac{a}{g}$.

These considerations do not depend on where exactly the liquid element is isolated. Let's choose

Fig. 9.

 it on the surface. Then it is clear that it is in equilibrium relative to the vessel and water only if the surface of the liquid is perpendicular to the force N: otherwise the component of the force N, parallel to the surface of the liquid, will cause the element of liquid we have identified to move along the surface. So, the surface of the liquid in a moving vessel is inclined to the horizon at an angle α = arctan $\frac{a}{g}$.

Let now a liquid element with mass Δm be inside the liquid. Let's assume that we placed together a body with the same volume, but with a density less than the density of water. It is clear that in this case our body will float in the direction of the force N. It follows that, unlike a vessel at rest, the lines of constant pressure are not horizontal, but make an angle α with the horizon. Obviously, the constant pressure in the rode that we need in the vessel will be the same. Therefore, it is clear that the angle of inclination of the liquid interface will be the same as the angle of inclination of the surface of the surface before adding water to the vessel: α = arctg $\frac{a}{g}$.

This is natural. The observer, who is on the cart, will say that the liquid behaves as if the vessel would end, and the forces and gravitational acceleration g' in its coordinate system are directed at an angle α to the vertical. In a vessel at rest, the fluid interface is perpendicular to the force of the fluid, regardless of the shape of the vessel.

The correct solution was sent by A. Aleksandrov (Glazov, UASSR), V. Belov (Vologda), Y. Intin (Rechnitsa, Gomel region, VSSR), V. Kovalev (Kommunarsk, Voroshilgovgrad region), A. Karimov (Ufa), S. Araslova (Nikhne-Ivkino, Kumensky district, Kirov region), A. Demidov (Moscow), N. Fedin (Omsk), E. Dolev (Moscow), L. Bratsinsky (Frunze).

I. Sh. Slobodetsky
