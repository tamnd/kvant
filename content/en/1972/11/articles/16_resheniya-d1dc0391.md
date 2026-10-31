---
id: 1972-11-resheniya-d1dc0391
issue: kvant_1972_11
year: 1972
number: "11"
title: Solutions to problems M129—M134; F148—F152
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 53
page_labels: 42, 44, 45, 46, 47, 48, 49, 50, 51
tag: CYZB
lang: en
source: kvant_digital
extraction: vision
content_sha256: 03acde31c8baa093aed9a7485e4a660372c9c2daf715e46c8f05b5125e93f388
prompt_sha256: draft-1
translated_from: content/ru/1972/11/articles/16_resheniya-d1dc0391.md
source_content_sha256: 3389207ca42649e5fe7f111442f7cf9ca097a4811f286555afb2642fd32c880a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Solutions

In this issue we publish solutions to problems M129—M134

M129
a) 12 liters of milk were poured into a bucket. How, using only 5 and 7 liter vessels, can you divide the milk into two equal parts?
b)* Solve the general problem: for what a and b can we divide (a+b) liters of milk in half, using only vessels in a liter, b liter and (a+b) liter?

TANK
I vessel 7 2 2 0 7 4 4 0 7 6
II vessel 0 5 0 2 2 5 0 4 4 5

TANK
Table 1.

To solve problem 6), we proceed as follows. Let a≥b. Let’s make a vessel with a capacity of a+b liters a reservoir, a vessel with a capacity of a liters the first vessel, and a vessel with a capacity of b liters the second vessel. Let us prove that c liters can be obtained if and only if c=ma+lb, where m and l are integers, 0≤c≤a. If a and b are integers, then it can be formed as follows: c liters can be obtained if and only if 0≤c≤a and c is divisible by the greatest common divisor of a and b (see the article by V. N. Vagten “Euclidean Algorithm and the Fundamental Theorem of Arithmetic”, «Kvant» No. 6, 1972). We solve the problem without assuming that a and b are integers; if this is known in advance, then the solution can be simplified; for example, there is no need to separately consider the cases of m>0 and m<0.

Table 2.

I a-a-b a-b a-2b a-2b d₁=a-l₁b 0 a 2a-(l₁+1)b 2a-(l₁+1)b d₂=2a-l₂b dₘ=ma-lₘb
II 0 b 0 b 0 0 d₁ d₁ b 0 0

Table 3.

To solve problem a) it is enough to provide a table (see table 1). For that

Let us denote by dₖ the remainder of division of ka by b (k=1, 2, 3, ...): dₖ=ka-lₖb, 0≤dₖ<b.

It is enough for us to prove that it is possible to obtain dₘ liters. Indeed, since dₘ=ma-lₘb is the smallest number of the form ma+lb, where l is an integer, then by adding another l+lₘ portions of b liters to dₘ, we can get the required amount

⟦folio 44⟧

Fig. 3.

must lie on the boundary of the set $V$; none of them can be inside $V$: after all, $V$ is contained in each of the stripes $\Pi_{ij}$.

The solution to problem a) is now obtained in two words. In this case, $V$ is a convex $n$-gon with vertices $A_1, A_2, \dots, A_n$. The sum of its angles is equal to $180^\circ (n - 2)$, and if each of the angles is not greater than $90^\circ$, then

$$180^\circ (n - 2) \leq 90^\circ n,$$

whence $n \leq 4$.

The solution to the problem on a plane was sent by many readers. The spatial problem is much more difficult, and we have not received a complete proof from any of the readers. Let us present a solution that was first found by the famous geometers L. Danzer and B. Grionbachum (1962).

Let us consider, in addition to the polyhedron $V$ (here $V$ can be understood as either the convex hull of the given $n$ points $A_1, A_2, \dots, A_n$ or the intersection - the common part - of all $n (n - 1)/2$ stripes $\Pi_{ij}$, there are also polyhedra:

$$V_i, \text{ получищеся из } V \text{ сдигом на вектор } \overrightarrow{A_1 A_i} (i = 1, 2, \dots, n); V_1, \text{ размещется, совпадает с } V), \text{ и } V', \text{ получищеся из } V \text{ расстоянием (гомотетей) с коэффициентом 2 и центром в точке } A_1.$$

Let us prove the following three statements.

1. The polyhedron obtained from $V$ by the vector $\overrightarrow{A_i A_j}$ has no common interior points with $V$ (that is, it can intersect with $V$ only on the boundary).

2. No two of the polyhedra $V_1, V_2, \dots, V_n$ have common interior points.

3. All $V_i$ are contained in $V'$.

Let's prove 1°. When shifting to $\overrightarrow{A_i A_j}$, stripe $\Pi_{ij}$ transforms into a new stripe, which has no common internal points with it - these two stripes only have a common boundary plane. But $V$ is contained in $\Pi_{ij}$, so 1° is all the more true.

2° change follows from 1°: it is enough to replace that $V_j$ obtained from $V_i$ by shifting to the vector $\overrightarrow{A_i A_j}$ (Fig. 4).

Fig. 4.

$$3^\circ \text{ следует из более общого факта: если } ABC \text{ — три точки выпуклого многогранника, } W \text{ и } W' \text{ — многогранник, полученный из } W \text{ растяжением в 2 раза с центром в точке } A, \text{ то четыряя вершина } D \text{ параллелограмма } ABDC \text{ (то есть точка, получшаяся из } C \text{ сдигром на вектор } \overrightarrow{AB}) \text{ принадлежит } W'.$$

This fact is easy to prove: the point $K$, from which, when stretched, $D$ is obtained - the midpoint of the segment $AD$ - is at the same time the midpoint of the segment $BC$, therefore it belongs to $W$ (after all, the polyhedron $W$ is convex), therefore $D$ belongs to $W'$ (Fig.5).

So, statements 2° and 3° are proven. Let $v$ be the volume of the polyhedron $V$. Then the volume of each of the $V_i$ points is $v$, and the volume of $V'$ is $8 v$. From 2° and 3° it obviously follows that $nv \leq 8 v$, whence $n \leq 8$.

Let us note that we have solved the problem proposed at the XIII International Olympiad (see “Quant” No. 12 for 1971, p. 54, problem 2): apparently, problem M130 6) in its entirety, the international jury considered it too difficult for the Olympiad and included only its second half.

In connection with the proven statement, a number of questions will arise that could no longer be resolved in the beautiful, but rather artificial way that we talked about. For example, what is the purest point in space that can be

⟦folio 45⟧

should be placed so that all angles of triangles with vertices at these points are acute?
From our solution it is clear that it is impossible to place 8 points (make sure of this). It is not difficult to construct an example when there are 5 points. Can there be 6 of them? 7? A more general and, probably, very difficult question is: what is the maximum number of points that can be arranged so that all angles do not exceed a given α?

If any of the readers manage to make progress in solving these issues, we will return to them again.

M131
Prove that the even points at which the angle bisectors between the extensions of opposite sides of a cyclic quadrilateral intersect its sides are the vertices of a rhombus.

We will solve the problem using the well-known theorems about the angle between two secants (Fig. 6). The notation is clear from figure 7. Since $PN$ and $QK$ are bisectors, then

$$\alpha_6 - \alpha_1 = \alpha_5 - \alpha_2,$$
$$\alpha_7 - \alpha_4 = \alpha_8 - \alpha_3.$$

Adding these two equalities, we get $\alpha_6 + \alpha_7 + \alpha_2 + \alpha_3 = \alpha_1 + \alpha_4 + \alpha_5 + \alpha_8$, therefore, the sum of the arcs in each part of the last equality is equal to half the circle. Therefore, lines $PN$ and $QK$ are perpendicular to each other. It follows that in a triangle $KPM$ the bisector of angle $P$ is simultaneous with the height; then it is also the median; triangle $KPM$ equilateral. The same can be said about the triangle $LQN$. Thus, in a quadrilateral $KLMN$ the diagonals bisect each other and are mutually perpendicular, so it is a rhombus.

N. B. Vasiliev

M132
Let $n$ numbers $x_1, x_2, \dots, x_n$ be written around a circle, each of which is equal to (+1) or (-1), and the sum of $n$ pairwise products of neighboring numbers is equal to 0 (as in problem M93, p. 42) and in general for each $n = 1, 2, \dots, n - 1$ the sum $n$ of pairwise products of numbers separated from each other by $k$ places equals 0 (i.e. $x_1x_3 + x_2x_4 + \dots = 0$, $x_1x_4 + x_2x_5 + \dots = 0$, etc.). Example for $n = 4$ dan on figure 8).

a) Prove that $n$ is the square of an integer.
b) Is there such a set of $n$ numbers for $n = 16$?

Fig. 8.

⟦folio 46⟧

Let us prove that $n$ is the square of an integer. Let's put $m = x_1 + x_2 + \dots + x_n$. Then $m$ is an integer,

$$m^2 = (x_1 + x_2 + \dots + x_n)^2 = (x_1^2 + x_2^2 + \dots + x_n^2) + (x_1x_2 + x_2x_3 + \dots + x_nx_1) + (x_1x_3 + x_2x_4 + \dots + x_{n-1} \times x_1 + x_nx_2) + \dots + x_nx_{n-1}).$$

As follows from the condition of the problem, on the right side of this equality the sum of the numbers in the first bracket is equal to $n$, and the sum of the numbers in any other bracket is equal to 0. Hence, $n = m^2$. Problem a) has been solved.

Let us determine for which $n$ we can select numbers $x_1, \dots, x_n$ that satisfy the conditions of the problem. As follows from problem M93, $n$ must be divisible by 4; This means that $n$ is the square of an even number. If $n=4$, then the following numbers can be selected: $x_1=x_2=x_3=1$, $x_4=-1$. The next possible value for $n$ is 16.

Let us prove that for $n=16$ such numbers $x_1, \dots, x_{16}$ cannot be selected.

Let us assume that numbers $x_1, \dots, x_{16}$ are given that satisfy the conditions of the problem, and try to arrive at a contradiction.

Let $m = x_1 + \dots + x_{16}$. We can assume that $m \geq 0$ (otherwise we could replace all the numbers $x_i$ with $-x_i$ without violating the conditions of the problem), as was shown, $m^2 = n = 16$, that is, $m=4$.

If $p$ of the numbers $x_i$ are equal to $1$ and $q$ are equal to $-1$, then

$$p + q = n = 16 \text{ и } p - q = m = 4.$$
So, $p=10$, $q=6$.

We will assume that the numbers $x_i$ are written at the vertices of a regular 16-gon. Let's mark with asterisks those vertices where the number $-1$ is (6 stars in total). Let us rotate the whole picture by $\frac{k}{16}$ parts of a full rotation ($k=1, 2, \dots, 15$).

Let us prove that in this case exactly 2 stars will go to the vertices where the stars were equal. Indeed, let $r$ numbers equal to $-1$ move to the places where $-1$ stood. Then the sum of $x_1x_{k+1} + x_2x_{k+2} + \dots + x_{16-k+1}x_1$ will be $(6-r)$ terms in which the first factor is $-1$ and the second $+1$, and $(6-r)$ terms in which the second factor is $-1$ and the first $+1$; that means there are $2(6-r)$ terms equal to $-1$.

Since the sum is 0, then $2(6-r) = 8$, that is, $r=2$.

Now we can reformulate our problem as follows: is it possible to place 6 stars at the vertices of a regular 16-gon so that two of them stand at opposite vertices, and for any number $k$ from 1 to 7 there would be an equal $k$ (under the distance between two points of a polymeter, the length is less than the arcs connecting them, and the length of the entire circle is taken as 16 parts; the distance between the points We will denote $X$ and $Y$ as $(XY)$.

Let us denote by $A$ and $B$ the diametrically opposite points offset by an asterisk, and by $C, D, E, F$ the other offset points. Let's calculate the sum of all distances between points $A, B, C, D, E, F$. Distance 8 occurs once, and distances from 1 to 7 occur twice—the total sum is $2(1+2+3+4+5+6+7)+8=64$.

Let's see what distances are realized between points $C, D, E, F$. Since $(AX) + (BX) = 8$ is for any point $X$, then the sum $\Sigma$ of all distances between points $C, D, E, F$ is equal to $64 - (AB) - 4 \cdot 8 = 24$. In addition, if some distance $k$ is realized between points $C, D, E, F$, this means that among the numbers $(AC), (AD), (AE), (AF) и (BC), (BD), (BE), (BF)$ occurs less than twice; but then $(8-k)$ occurs less than twice, that is, $(8-k)$ is also realized as the distance between the points $C, D, E, F$. Let's see how the points $C, D, E, F$ can be located. It is easy to check that two cases are possible.

1) Some three points (for example, $C, D, E$) form a triangle containing the center of the circle. Let $F$ lie between $C$ and $D$. Then

$$(CD) + (DE) + (CE) = 16,$$
$$(CF) + (DF) = (CD),$$

and, in addition, $(EF)$ is greater than $(CE)$ or $(DE)$. Since $(CD) + (DE) > 8$ and $(CD) + (CE) > 8$, then $\Sigma = (CD) + (DE) + (CE) + (CF) + (DF) + (EF) = 16 + (CD) + (EF) > 24$, although, as we showed earlier, this sum should be equal to 24. This means that the first case is new.

2) Points $C, D, E, F$ lie on one side of a certain diameter. Let them be arranged around the circle in the following order $C, D, E, F$. Then $(CD) + (DF) = (CF) + (CE) + (DF) + (EF) = 16$ (sum of $3(CF) + (DE)$). So, $3(CF) + (DE) = 24$. Since $CF > DE$, then $(CF) = 7$, $(DE) = 3$. If $(CD) = 1$, then $(DF) = 6$; but at the same time, the distance $2 = 8 - 6$ is not realized between the points $C, D, E, F$, which contradicts what was previously proven. If $(CD) = 2$ then although $(CF) = 7$, distance 1 is not realized. If $(CD) = 3$ then $(EF) = 1$, and this case is no different from the case $(CD) = 1$.

So, we have obtained that the distance of the asterisk in the required way (and therefore, apparently, the number that satisfies the conditions of the problem can be selected only for $n=4$.

D. N. Bernishtein

M133

One of the simplest multicellular organisms - algae "wolves" - is

⟦folio 47⟧

Fig. 9.

is a spherical shell folded into a main heptagon, hexagons and pentagons with cells (that is, cells with seven, six or five neighboring ones; three cells converge at each “vertex” (Fig. 9). There are specimens that have both quadrangular and octagonal cells, but biologists have noticed that if there are such “non-standard” cells (less than on the fifth and more than seven sides) no, then the pentagonal cells are always exactly 12 larger than the heptagonal ones (there can be several hundred and even thousands of cells in total). Could this fact be explained?

The statement of the problem follows from Euler's formula. (For Euler’s formula, see «Kvant» No. 4, 1972, p. 31 or Courant and Robbin and “What is mathematics?” M., “Prosveshcheniye”, 1967). Indeed, let us denote the number of vertices of a volvox by $B$, the number of edges by $P$, and the number of faces with $i$ vertices by $\Gamma_i$. Then, according to Euler's formula

$$2 = B - P + \Sigma \Gamma_i.$$

But $3B = \Sigma_i \Gamma_i$, since, by condition, three faces converge at each vertex, and $2P = \Sigma_i \Gamma_i$ - two faces are adjacent to each edge. Hence,

$$12 = 6B - 6P + 6\Sigma \Gamma_i = \Sigma_{2i} \Gamma_i - \Sigma_{3i} \Gamma_i + \Sigma_{6i} \Gamma_i = \Sigma (6 - i) \Gamma_i.$$

By condition, there are no non-standard faces, that is, $\Gamma_3 = \Gamma_4 = \Gamma_8 = \Gamma_9 = \ldots = 0$. Therefore, $\Gamma_5 - \Gamma_7 = 12$ is in substitutional agreement with the observations of biologists.

M134

What set of points is filled by three triangles whose three vertices lie respectively on the three sides $AB, BC$ and $AC$ of the given triangle $ABC$?

Fig. 10.

It will be convenient for us to consider not only full-fledged triangles, but also degenerate triangles. Let us first prove that any point of the blue hexagon is the center of gravity of the inscribed triangle (Fig. 10). For this we need such

Lemma. If point $O_1$ is the center of gravity of the inscribed triangle $K_1L_1M_1$, and point $O_2$ is the center of gravity of the inscribed triangle $K_2L_2M_2$, then for any point of the segment $[O_1, O_2]$ one can specify an inscribed triangle for which it is the center of gravity. Let us now place the boundaries $\frac{p_1}{3}$ at the vertices of the triangle $K_1L_1M_1$, and the boundaries $\frac{p_2}{3}$ at the vertices of the triangle $K_2L_2M_2$ (Fig. 11). The center of gravity of these hexagons coincides with the point $O_3$. On the other hand, it is the center of gravity of the boundary $\frac{p_1 + p_2}{3}$ placed at the vertices of the triangle $K_3L_3M_3$ resulting from the following pairs of boundaries $\frac{p_1}{3}, \frac{p_2}{3}$ placed at the points $K_1, K_2; L_1, L_2$ and $M_1, M_2$, respectively. Thus, based on the triangles $K_1L_1M_1$ and $K_2L_2M_2$ and an arbitrary point $O_3$ of the segment $[O_1, O_2]$, we constructed a triangle $K_3L_3M_3$, the center of gravity of which it is. The lemma is proven.

Now it is easy to prove that any point of the blue hexagon is the center

⟦folio 48⟧

Fig. 11.

gravity and some inscribed triangle. Indeed, it is enough to prove this for its vertices, and then use the lemma - with its help we can move from the vertices to the boundary, and then to any internal point. But for vertices such triangles are constructed without difficulty: these are triangles whose vertices lie at the vertices of the main triangle and two vertices merge into one.

Fig. 12.

It remains to prove that the points lying inside the triangles $AB_1C_1$, $A_1BC_2$, $A_2B_2C$ cannot be the centers of gravity of inscribed triangles. Indeed, let for some point $O$ of triangle $AB_1C_1$ be called triangle $KLM$, for which it is the center of gravity (Fig. 12). But then it divides the segment $KN$ in the ratio 1:2, which is impossible.

L. G. Limanov

In this issue we publish solutions to problems F148—F152

F148

A nucleus of mass $M$, flying at a speed $v$, disintegrates into two identical shards. The internal energy of the nucleus is $E_1$, the internal energy of each of the sockets is $E_2$ ($E_1 > 2E_2$). Determine the maximum possible angle between the velocity vector of one of the sockets and the vector $v$.

Fig. 13.

In the coordinate system associated with the center of mass of the core and moving relative to the Earth with a speed of $v$, the sedges are separated in opposite directions with equal speeds. The kinetic energy of these fragments is equal to the difference between the internal energy of the nucleus and

internal energies of osoklov. If the speed of each of the sockets is equal to $v_1$, then

$$2 \frac{mv_1^2}{2} = E_1 - 2E_2.$$

From here we find the speed of each of the shards:

$$v_1 = \sqrt{\frac{E_1 - 2E_2}{m}} = \sqrt{\frac{2(E_1 - 2E_2)}{M}}.$$

The velocity of the sedge in the coordinate system associated with the Earth is equal to the vector sum of the velocities $v$ and $v_1$. The speed $v_1$ of the socket in the coordinate system associated with the center of mass of the nucleus can have an arbitrary direction. But the vector $v'$ of the speed of the sedge in the coordinate system associated with the Earth makes the greatest angle with the vector $v$ in the case when the vector $v_1$ is perpendicular to the vector $v'$ (Fig. 12). In this case, the velocity vector of the socket $v'$ makes an angle $\alpha$ with the vector $v$ such that

$$\sin \alpha = \frac{v_1}{v} = \sqrt{\frac{2(E_1 - 2E_2)}{Mv^2}}.$$

How many times will the force of attraction of two small balls decrease, one of which

⟦folio 49⟧

Which one is charged and the other neutral, if the distance between the balls is doubled?

The charged ball is a source of an electric field that polarizes the neutral ball. As a result of polarization, the neutral ball becomes a dipole - a generally neutral ball with charges $+q'$ and $-q'$, the distance between which is equal to the diameter of the ball $2r$ (Fig. 14). The magnitude of the charge $q'$, or, as they say, the degree of polarization of the ball, is proportional to the field strength at the center of this ball, that is, the magnitude $\frac{q}{R^2}$, where $q$ is the charge of the other ball:

$$q' = \frac{\alpha q}{R^2}$$

(α is the proportionality coefficient).

Now let's find the force of interaction between the charges of the balls. This force is equal to the sum of the attractive forces between charge $q$ and charge $-q'$ and the repulsive forces between charge $q$ and charge $+q'$:

$$F = \frac{qq'}{(R-r)^2} - \frac{qq'}{(R+r)^2} = \frac{\alpha q^2}{R^2} \left( \frac{1}{(R-r)^2} - \frac{1}{(R+r)^2} \right) = \frac{\alpha q^2}{R^2} \frac{4Rr}{(R^2-r^2)^2}.$$

Since $R > r$, $r^2$ can be neglected in the denominator of the formula compared to $R^2$. As a result we get:

$$F = \frac{\alpha q^2}{R^2} \frac{4Rr}{R^4} = \frac{4\alpha q^2 r}{R^5}.$$

Thus, the force of interaction between the balls is proportional to $\frac{1}{R^5}$, where $R$ is the distance between the centers of the balls. When the distance between the balls increases by 2 times, the force of their interaction decreases by 32 times:

$$\frac{F_1}{F_2} = \frac{\frac{4\alpha q^2 r}{R^5}}{\frac{4\alpha q^2 r}{(2R)^5}} = 2^5 = 32.$$

Fig. 14.

F150

In some galaxies, a star 3 with a planet Π was discovered, making one revolution around the star in time $T_1$ and one revolution around the star in time $T_2$. The satellite of planet C makes one revolution around the star. How long does it take for the eclipse of satellite C to repeat at a given location on the planet?

All bodies rotate in the same plane.

Let in the coordinate system associated with the fixed stars, the planet and satellite rotate as shown in figure 15, and $\omega_1 = \frac{2\pi}{T_1}$ is the angular velocity of the planet’s rotation around its own spin $\omega_3 = \frac{2\pi}{T_3}$ is the angular velocity of the satellite’s rotation around spin $\omega_3$.

In a coordinate system associated with a planet, but not rotating relative to fixed distant stars, the star rotates around the planet with angular velocity $\omega_1$, as shown in figure 15, and the satellite rotates around spi $\omega_3$.

Now it will move to a coordinate system associated with the planet and rotating with it. In this coordinate system, the star rotates around the planet with an angular velocity of $\omega' = \omega_1 - \omega_2$, and the satellite with an angular velocity of $\omega'' = \omega_3 - \omega_2$.

If at some moments an eclipse of a satellite is observed on the planet, then the next eclipse of the satellite will be observed on the planet after time $t$, after which the star will be eclipsed by an angle $\varphi$, and the satellite by an angle $2\pi + \varphi$. We assume $\omega_3 > \omega_1$.

$$\varphi = \omega' t$$

And

$$2\pi + \varphi = \omega'' t.$$

From here

$$2\pi = (\omega'' - \omega') t,$$

$$t = \frac{2\pi}{\omega'' - \omega'} = \frac{2\pi}{\omega_3 - \omega_1} = \frac{T_1 T_3}{T_1 - T_3}.$$

It is clear that the next eclipse will occur when the star surfaces at an angle $2\varphi$, then when it surfaces at an angle $3\varphi$, etc. If for some integer $N$ the number $N\varphi$ is equal to an integer multiple of $2\pi$, then the $N$th eclipse attaches to the starting point. So, if $N\varphi = 2\pi m$, that is, if the number $\frac{\varphi}{2\pi}$ can be represented as an irreducible fraction

$$\frac{\varphi}{2\pi} = \frac{\omega'}{\omega'' - \omega'} = \frac{T_3(T_2 - T_1)}{T_2(T_1 - T_3)} = \frac{m}{N},$$

⟦folio 50⟧

Pis. 15.

then after a period of time
$$mt = \frac{2\pi m}{\omega'' - \omega'} = \frac{2\pi m T_3 T_1}{T_1 - T_3}$$

the eclipse will be at the same point. If the number $\frac{\varphi}{2\pi}$ and the border are on line, then $N\varphi (N = 1, 2, 3, \dots)$ will in no way be an integer multiple of 2l and therefore the shading will in no way be at the same point.

In practice, of course, the relation $\frac{\varphi}{2\pi} = \frac{\omega'}{\omega'' - \omega'} = \frac{T_3 (T_2 - T_1)}{T_2 (T_1 - T_3)}$ can only be specified approximately and has no meaning

Let's talk about whether this number is rational or irrational. But our reasoning shows that if the number $\frac{m}{N}$ has a small numerator and denominator, then the eclipse will occur almost exactly in one of the $N$ places in the plans (sequentially passing through all these $N$ places), and if not, it occurs each time in a new place.

F151

Two plane mirrors form two zero angles with a distance of 90°. A line with focal length $F$ is inserted into the corner so that the main optical axis of the line makes an angle of 45° with each mirror. The radius of the line is equal to its focal length. At this position, the image of the source is located on the main optical axis of the line at a distance of 1.5F from the line. Having written down the formula of Lina
$$\frac{1}{F} = \frac{1}{1,5F} + \frac{1}{f_1},$$
we'll find
$$f_1 = 3 F.$$
This means that point $S_1$ is at a distance of 2F from the line of intersection of the mirrors. But the rays going to the mirror $I$ are reflected from it, and if there were no mirror $II$, they would intersect at point $S_2$. Point $S_2$ is located on a straight line perpendicular to the optical axis of the line, at a distance of 2F from the line of intersection of the mirrors. Let's prove it.

Angle 1 is equal to angle 2 (as if lying crosswise) and is equal to angle 3 (this follows from the law of reflection). Therefore, angle 2 is equal to angle 3. It can also be shown that angle 4 is equal to angle 5. But it follows that the triangle $ABS_2$ is equal to the triangle $ABS_1$ - they have one common side $AB$ and the angles adjacent to this side are equal. Obviously, triangle $ABS_2$ is a reflection of triangle $ABS_1$ with respect to line $I-I$. It follows that $OS_2 = OS_1 = 2F$ and since $S_1OC = S_2OC = 45^\circ$, then $S_2OS_1 = 90^\circ$.

It is not difficult to show that the rays going to the mirror $II$ to the “minimum source”, point $S_2$, reflected, would intersect if there were no line, at point $S_3$, located on the main optical axis of the line at a distance of 2F from the line of intersection of the mirrors, that is, at a distance $F$ from the line.

⟦folio 51⟧

Fig. 16.

Point $S_3$ is the minimum source for the lens. Let's find its image $S_4$. To do this, let’s write down the lens formula again:

$$\frac{1}{F} = \frac{1}{d} + \frac{1}{f_2},$$

where $d = -F$ (since the source $S_3$ is minimal), $a$ $f_2$ is the distance from the lens to the image $S_4$.

From the last equation we find

$$f_2 = 0,5 F.$$

Thus, the image $S_4$ of source $S$ given by the system will be at a distance of 0.5 $F$ from the lens.

F152

The volume of a gas pool formed as a result of a deep underwater explosion fluctuates with a period proportional to $pa\rho bEc$, where $p$ is the pressure, $\rho$ is the density of water and $E$ is the total energy of the explosion. Find $a$, $b$ and $c$.

It is known that

$$T \sim pa\rho bEc.$$

The quantity on the left in this formula has the time dimension $[c]$. The quantity on the right should have exactly the same dimension. Let's write down the dimensions of all quantities:

$$p \rightarrow \left[ \frac{H}{m^2} \right] \rightarrow \left[ \frac{\kappa_2}{m \cdot c^2} \right]; \quad \rho \rightarrow \left[ \frac{\kappa_2}{m^3} \right];$$

$$E \rightarrow [\partial \kappa] \rightarrow \left[ \frac{\kappa_2 \cdot m^2}{c^2} \right].$$

The product $\rho a\rho bEc$ has the dimension

$$\left[ \frac{\kappa_2}{m \cdot c^2} \right]^a \left[ \frac{\kappa_2}{m^3} \right]^b \left[ \frac{\kappa_2 \cdot m^2}{c^2} \right]^c \rightarrow [\kappa_2]^{a+b+c} [m]^{-a-3b+2c} [c]^{-2a-2c}.$$

In order for the dimension of this product to be $[c]$, it is necessary that

$$-2a - 2c = 1,$$

$$a + b + c = 0,$$

$$-a - 3b + 2c = 0.$$

Solving this system of equations, we find

$$a = -\frac{5}{6}; \quad b = \frac{1}{2}; \quad c = \frac{1}{3}.$$

Hence,

$$T \sim p^{-\frac{5}{6}} \rho^{\frac{1}{2}} E^{\frac{1}{3}}.$$

I. Sh. Slobodetsky.
