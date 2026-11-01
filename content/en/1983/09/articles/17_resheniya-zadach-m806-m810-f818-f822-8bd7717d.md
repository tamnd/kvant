---
id: 1983-9-resheniya-zadach-m806-m810-f818-f822-8bd7717d
issue: kvant_1983_9
year: 1983
number: "9"
title: Solutions to problems M806—M810; F818—F822
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 49
page_labels: 42-47
tag: 8MIU
lang: en
source: kvant_digital
extraction: vision
content_sha256: 454ca946189f27847ce11aca16e6d5aa2c52cfe404f95eaf2f29a8a9e5327f52
prompt_sha256: draft-1
translated_from: content/ru/1983/09/articles/17_resheniya-zadach-m806-m810-f818-f822-8bd7717d.md
source_content_sha256: c508927e056f9fe82d7610619c6fd3114fb22ae9d7b865ac4bdf0a2f81aa8e2f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

Problems M824, M825 and R833—R837 were proposed at the final round of the All-Union School Olympiad.

E. I. Butikov

P835. A heater was placed in a glass of water and the water temperature registered as a function of time (see table).

1) By how many degrees will the water cool in 1 min, if the heater is turned off when the temperature is $t_1 = 50$ °C?

2) Will the water boil, if the heater is turned on long enough? The power of the heater is assumed constant.

| Time, $\tau$ min | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Temperature, $t$ °C | 20 | 26.2 | 31.8 | 36.8 | 41.4 | 45.6 | 49.3 | 52.7 | 55.8 | 58.5 | 61.1 |

A. R. Zilberman

P836. The plate A of a flat capacitor is motionless, the plate B is joined by a spring to the wall and can move, remaining parallel to A (see figure Fig. 4). After the switch K is turned on, the plate B begins to move and stops in a new equilibrium position, the distance between the plates decreasing by $\alpha_1 = 10\%$. How would the equilibrium distance between the plates have changed if the switch K was turned on only for a brief period of time? It is assumed that the plate B does not have enough time to move noticeably during this period.

A. I. Buzdin

P837. A laser anemometer is used to measure the velocity of particles which move through two intersecting coherent laser light beams (see figure Fig. 5). The light reflected by the particles is registered by the photoelement $\Phi$ and is transformed into an electric impulse. The particles move perpendicularly to the bisector of the angle $\alpha = 60^\circ$ between the beams. In what direction did a particle move, if a periodic signal of frequency $v = 320$ kHz was registered (for laser beam wavelength $\lambda = 0.63$ mkm).

V. V. Mojaev

Problem solutions

M806—M810; F818—F822

M806. a) Prove that if $a_1 + \frac{a_2}{2} + \frac{a_3}{3} + \ldots + \frac{a_n}{n} = 0$, then the polynomial $a_n x^{n-1} + a_{n-1} x^{n-2} + \ldots + a_2 x + a_1$ has a root between 0 and 1.

b) Prove that if for some $p > 0$

$$\frac{a_1}{p+1} + \frac{a_2}{p+2} + \frac{a_3}{p+3} + \ldots + \frac{a_n}{p+n} = 0,$$

then this polynomial also has a root between 0 and 1.

Let us first prove the following statement: if a differentiable function $f(x)$ turns into a field at points $x = 0$ and $x = 1$, then its derivative must turn into a field at some interior point from zero and, therefore, is taken at the point $x_0$ lying inside the segment [0; 1].

This is obvious if the function $f(x)$ is also effectively equal to 0 on the interval [0; 1]. Otherwise, we will consider the points at which it takes its largest and smallest value on this segment. (Such points exist according to the Weierstrass theorem - see the textbook “Algebra and Analysis 9-10”, paragraph 28 - or the function $f(x)$, being differentiable, is continuous.) However, these values ​​must be zero and, therefore, taken at the point $x_0$ lying inside the segment [0; 1].

Thus, $x_0$ is the extremum point of the function $f(x)$ on the interval [0; 1] [1, and by Fermat’s theorem (“Algebra and beginnings of analysis 9-10”, paragraph 26) $f'(x_0) = 0$.

Let us use the proven statement to solve the problem.

a) Consider the function $f(x) = a_1 x + \frac{a_2}{2} x^2 + \ldots + \frac{a_n}{n} x^n$.

By condition, $f(1) = a_1 + \frac{a_2}{2} + \ldots + \frac{a_n}{n} = 0$, in addition, $f(0) = 0$.

⟦folio 43⟧

According to the proven statement, $f'(x_0) = 0$ for some $x_0$ from the interval $]0; 1[$. It remains to note that $f'(x) = a_1 + a_2x + \dots + a_nx^{n-1}$.

6) The proof is the same as in part a) with the difference that instead of the function $f(x)$ we must take $g(x) = \frac{a_1}{p+1}x^{p+1} + \frac{a_2}{p+2}x^{p+2} + \dots + \frac{a_n}{p+n}x^{p+n}$ and take into account that in the equality $g'(x_0) = x_0^p(a_1 + a_2x_0 + \dots + a_nx_0^{n-1}) = 0$ the set $x_0^p$ is non-zero.

A. Gokhberg, M. Ovetsky

**M807. a) From an arbitrary point $M$ inside an equilateral triangle, perpendiculars $MK_1$, $MK_2$, $MK_3$ are dropped onto its sides. Prove that the sum of the vectors $MK_1 + MK_2 + MK_3$ is equal to $\frac{3}{2} \vec{M}O$, where $O$ is the center of the triangle.

6) From an arbitrary point $M$ perpendiculars $MK_1$, ..., $MK_n$ are dropped to all sides correctly in a knot or their extension. Prove that

$$\vec{MK}_1 + \dots + \vec{MK}_n = \frac{n}{2} \vec{M}O,$$

its $O$ is the center of the $n$-node.

8) From an arbitrary point $M$ inside a regular terrahedron, perpendiculars $MK_1$, $MK_2$, $MK_3$, $MK_4$ on its face are dropped. Prove that

$$\vec{MK}_1 + \vec{MK}_2 + \vec{MK}_3 + \vec{MK}_4 = \frac{4}{3} \vec{M}O,$$

its $O$ is the center of the terrahedra.

Fig. 1.

Fig. 2.

a) Let us draw lines parallel to the sides of the triangle through the point $M$ and designate the points of intersection of these lines on the side of the triangle, as shown in figure 1.

It is clear that $2\vec{MK}_1 = \vec{MA}_1 + \vec{MA}_2$, $2\vec{MK}_2 = \vec{MB}_1 + \vec{MB}_2$, $2\vec{MK}_3 = \vec{MC}_1 + \vec{MC}_2$ and at the same time, $\vec{MC}_1 + \vec{MB}_2 = \vec{MA}$; $\vec{MC}_2 + \vec{MA}_1 = \vec{MB}$ and $\vec{MA}_2 + \vec{MB}_1 = \vec{MC}$. Pozny

$$2(\vec{MK}_1 + \vec{MK}_2 + \vec{MK}_3) = \vec{MA} + \vec{MB} + \vec{MC} = 3\vec{MO} + \vec{OA} + \vec{OB} + \vec{OC}.$$

But, obviously, $\vec{OA} + \vec{OB} + \vec{OC} = \vec{0}$, therefore, $2(\vec{MK}_1 + \vec{MK}_2 + \vec{MK}_3) = 3\vec{MO}$, which is what was required.

6) Let us first prove that if $O$ is the center of the regular polygon $A_1...A_n$, then $\vec{OA}_1 + \dots + \vec{OA}_n = \vec{0}$.

In fact, when rotated by $\frac{360^\circ}{n}$ around $O$, the vertex $A_1$ will go to $A_2$, $A_2$ to $A_3$, ..., $A_n$ to $A_1$, and the vector $\vec{s} = \vec{OA}_1 + \vec{OA}_2 + \dots + \vec{OA}_n$ to $\vec{OA}_2 + \vec{OA}_3 + \dots + \vec{OA}_n + \vec{OA}_1 = \vec{s}$, that is, it will not change. Pozny $\vec{s} = \vec{0}$.

Let us drop the perpendiculars $OP_1$, ..., $OP_n$ to the sides of the given regular polygon $(OP_i \parallel MK_i)$, then drop the perpendiculars $MB_i$ from the point $M$ onto the lines $OP_i$ (if $n$ is even, the lines $OP_i$ and $OP_{i+n/2}$ $i=1, 2, \dots, n/2$ are the same as $B_i = B_{i+n/2}$; see Fig. 2 for $n=6$). Since $\vec{MK}_i = \vec{B}_iP_i = \vec{B}_iO + \vec{OP}_i$ and $P_1P_2...P_n$ are proper $n$-knots with center $O$,

$$\vec{MK}_1 + \vec{MK}_2 + \dots + \vec{MK}_n = (\vec{B}_1O + \vec{B}_2O + \dots + \vec{B}_nO) + (\vec{OP}_1 + \vec{OP}_2 + \dots + \vec{OP}_n) = \vec{B}_1O + \vec{B}_2O + \dots + \vec{B}_nO.$$

(1)

Let us prove that the points $B_1$, ..., $B_n$ lie on a circle with diameter $MO$ (for $\vec{MB}_iO = 90^\circ$), therefore it is enough to prove that the corner vertex of any of the arcs on which this circle is divided by the points $B_1$, ..., $B_n$ is equal to $360^\circ/n$. Let $B_iB_j$ be one of these arcs and let it not contain the point $O$. Then $\angle B_iOB_j$ is one of $2m$ equal angles into which the plane $m$ of lines $OB_i = OP_i$ is divided (see Fig. 3, where $n=m=5$, $i=2$, $j=4$). Therefore, $B_iOB_j = 180^\circ/m$ and $B_iB_j = 360^\circ/m$. The arc containing the point $O$ also has magnitudes $360^\circ - (m-1) \cdot 360^\circ/m = 360^\circ/m$.

From what has been proved it follows that $\vec{O}_1B_1 + \dots + \vec{O}_1B_n = \vec{0}$, and according to (1)

$$\vec{MK}_1 + \dots + \vec{MK}_n = \vec{B}_1O_1 + \vec{B}_2O_1 + \dots + \vec{B}_nO_1 + n\vec{O}_1O = \frac{n}{2} \vec{MO}.$$

Note that this problem can also be solved using the method of item $a$.

c) It is enough to prove that the projections of the vectors $\vec{MK}_1 + \dots + \vec{MK}_n$ and $\frac{4}{3} \vec{MO}$ onto some two intersecting planes coincide. (Indeed, it follows that

⟦folio 44⟧

that two projections of the difference $\vec{d}$ of these vectors are equal to the null vector, that is, the vector $\vec{d}$ redistributed uranium simultaneously to two intersecting planes, and therefore $\vec{d} = 0$).

These planes can be chosen so that the proof is reduced to the plane case—problem a). Namely, we draw the plane $p$ through the point $M$, redistribute the uranium, say, $\vec{MK}_4$, and project the vectors $\vec{MK}_i$, $i=1, 2, 3$ (Fig. 4) onto it. Each of them forms an angle $\gamma$ with the plane $p$, equal to the angle between the height and the lateral face of the regular tetrahedron $(\cos^2 \gamma = \frac{8}{9})$, therefore the projection of the vector $\vec{MK}_i$ is equal to $\vec{MH}_i = \frac{8}{9} \vec{MQ}_i$, where $Q_i$ is the projection of the point $M$ on the corresponding side of the triangle, resulting in the section of the tetrahedron by the plane $p$. Let $O'$ be the center of this triangle, then, according to a),

$$\vec{MH}_1 + \vec{MH}_2 + \vec{MH}_3 = \frac{8}{9} (\vec{MP}_1 + \vec{MP}_2 + \vec{MP}_3) =$$

$$= \frac{8}{9} \cdot \frac{3}{2} \vec{MO}' = \frac{4}{3} \vec{MO}'.$$

It remains to note that the left side of this equality is the projection of the sum $\vec{MK}_1 + \ldots + \vec{MK}_4$ onto the plane $p$ (the projection of the sum of vectors is equal to the sum of their projections), and the right side is the projection of the vector $\frac{4}{3} \vec{MO}$. The same reasoning is also valid for planes parallel to other faces of the tetrahedron.

Try to solve problem a) in a similar way, reducing the two-dimensional case to a one-dimensional one using projection.

Let us outline another solution to problem b) (which can also be adapted to problems a) and 6)). Consider the difference vector $\vec{d} = (\vec{MK}_1 + \vec{MK}_2 + \vec{MK}_3 + \vec{MK}_4) - \frac{4}{3} \vec{MO}$ as a function of the vector $\vec{a} = \vec{MO}$. It is easy to check that the statement of the problem is true for the vertices $A_1, A_2, A_3, A_4$ of the tetrahedron, hence $\vec{d}(A_iO) = 0$. Moreover, $\vec{d}(\vec{a})$ is a linear vector function, that is, $\vec{d}(\vec{a} + \vec{b}) = \vec{d}(\vec{a}) + \vec{d}(\vec{b})$ and $\vec{d}(k\vec{a}) = kd(\vec{a})$. (Indeed, the sum of the vectors $\vec{MK}_i$ is equal to the sum of the projections of the vector $\vec{MO}$ onto four straight lines, redistributing uranium to the sides of the $n$-gon. But it is easy to see that the projection of a vector onto a straight line is a linear function of this vector.) It follows that $\vec{d}(\vec{a}) = 0$ for any vector $\vec{a}$, since it can always be represented in the form $k_1\vec{A}_1O + k_2\vec{A}_2O + k_3\vec{A}_3O$.

V. V. Prasolov

**M808. On an endless sheet of checkered paper, two people paint a current cell: the first paints some cell red, the second paints some (uncolored) cells blue, then again the first one (uncolored) turns red, the second paints a cell blue, etc. The first passion is for some four red cells to be located at the vertices of a square (with sides parallel to each other).

Answer: the second player will not be able to place to the first player at any $k$.

It is convenient to solve a problem from the end. It is clear that the first player (we will call him $K$ - “red”) will win if in some of his moves he immediately creates $k+1$ “incomplete” squares, at three vertices of each of which there are red cells, and at the fourth - uncolored. Then after the answer of the second player (let’s call him $C$ - “blue”) at least one of the four vertices remains uncolored and, having colored it, $K$ will receive a “red square”. Examples of such winning positions are shown in Figures 1, a - for the general case - and 1, b - for $k=1$ (in the latter case, $K$ can act in the same way as in the general case, for an arbitrary $k \geqslant 1$, but it also has a more economical path to victory, using the symmetry of the square lattice).

⟦folio 45⟧

niyam grid). Will the second one be able to place a) for k=1; 6)* for k=2; 8)* for some k>2?

Fig. 1. Calling positions for the first cerraq a) for arbitrary k≥1; 6) at k=1. Cells united by frames are neither red nor blue. An asterisk is placed on the last cell, painted with feather cerroc.

Fig. 2.

Let's explain how K should play to get these positions.

a) Let a and a' be the first cells colored by players K and C (Fig. 2), respectively. In the second move, K colors cell b, which is in the same column as a, so that the distance between cells b and a is greater than between a' and a. After the response move C, one of the cells c and c₁ of the same column (see figure 2), for example, c, will remain uncolored. It is colored by K in the third move. Similarly, in the fourth move K colors cell d or d₁. Let's say he colored d, then consider the columns containing cells e, f, g and h. One of them, for example, containing e, is free from blue cells, because there are only four blue cells and one of them - a' - is not included in these columns. By coloring e, player K will receive position figure 1, ​​6 (squares a, b₁ c and e on figure 2).

6), c) Player K starts by coloring N cells of one row, not paying attention to the distances between them (the number N depends on k; we will clarify it below). Then, under the first row, K selects a row in which there are no blue cells, and colors the cells in it that are exactly under the red cells of the first row (as long as there are still some uncolored red or blue among them). Under the second line, K selects the third (free from blue cells) and colors the cells in it that are under the red cells of the second line, etc. Having filled n lines in this way (we will determine the number n later), K must choose a straight line l passing along the diagonals of the cells (Fig. 3) under all the colored cells (red and blue), and color on it k + 1 cells standing exactly under the cells of the last one, nth line. Since for every new red cell there are k blue ones, for this it is enough that the nth row has k²+k+1 red cells. (Then, in response to the first k cells of line l, which are colored by K, C will color k² cells, after which at least one more uncolored cell will remain under the red cells of the nth row on line l.) Red cells on line l, together with the cells of one of the n rows lying above them and cell a at the intersection of this line with line l (Fig. 3) and form the winning “wedge” shown in figure 1, a. Just select this line so that cell a and all the cells below it are not blue. And this can always be done if the line clearings n are greater than the number of blue cells on the line l and below it, which does not exceed (k+1)k=k²+k, for example, when n=n²+k+1.

So, the number N must be so large that player K can fill n=k²+k+1 lines in the indicated way and color n cells in the last one. We can take N=(k+1)ⁿ·k+1. Indeed, as we have seen, in order for K to color k+1 cells on line l, in the nth row it was necessary to color (k+1) k+1 cells red; it is similarly proven that for this to happen, the (n−1)th row must contain (k+1)²·k+1 red cells, the (n−2)th row must contain (k+1)³·k+1, ..., and the first line must contain (k+1)ⁿ·k+1 red cells.

Note that this solution is close to the solution of problem M750 («Kvant», 1982, No. 12; see also the article by S. N. Bespamyatnykh in «Kvant» No. 6 for this year).

D. G. Azov

⟦folio 46⟧

M809. Find the amount
$$\frac{1}{2!} + \frac{2}{3!} + \dots + \frac{n-1}{n!}$$

(the product $1 \cdot 2 \cdot 3 \cdot \dots \cdot k$ is denoted by $k!$).

Answer: $1 - \frac{1}{n!}$. It is quite easy to get the answer if you represent the $k$-th term of the required sum in the form $\frac{k}{(k+1)!} = \frac{(k+1) - 1}{(k+1)!} = \frac{1}{k!} - \frac{1}{(k+1)!}$. We have
$$\frac{1}{2!} + \frac{2}{3!} + \dots + \frac{n-1}{n!} = \left(1 - \frac{1}{2!}\right) + \left(\frac{1}{2!} - \frac{1}{3!}\right) + \dots + \left(\frac{1}{(n-1)!} - \frac{1}{n!}\right) = 1 - \frac{1}{n!}.$$

V. V. Proizvolov

M810*. Prove that any convex polygon $M$ can contain a rectilinear area of ​​at least $1/4$ of the area of ​​the polygon $M$.

Let $A$ and $B$ be the vertices of the polygon $M$, $|AB| = d$ that are most distant from each other (the segment $AB$ can be a diagonal or a side). Let's take a point on the segment $AB$ at a distance $x$ from $A$ ($0 \leqslant x \leqslant d$) and draw a line through it perpendicular to $AB$. Since the polygon $M$ is convex, this line will intersect with it along a segment (possibly degenerating into a point), the length of which will be denoted by $l(x)$. Let $CD$ be the largest of such segments, $|CD| = l_0$ (see figure). It's clear that

$$S(M) = \int_0^d l(x) dx \leqslant \int_0^d l_0 dx = l_0 \cdot d.$$

Consider a quadrilateral $KLPQ$ with vertices at the midpoints of the sides of the quadrilateral $ABCD$. Two of its sides (at figure - $KL$ and $PQ$) are the midlines in triangles $ABC$ and $ABD$ and are therefore parallels to $AB$ and equal in length to $d/2$; similarly, the other two sides are parallel $CD$ and equal in length $l_0/2$. Therefore, $KLPQ$ is a straight-level area of ​​$dl_0/4$ and $S_{KLPQ} \geqslant S(M)/4$.

It remains to note that the straight-level $KLPQ$ is contained in $ACBD$, and $ACBD$ in $M$, since $M$ is a convex polygon.

The resulting estimate does not appear to be accurate. However, the author failed to improve it. Perhaps readers will do this.

F. V. Vainitein

F818. Two rigid rods of length $l$ are hinged at point $A$ (see figure). The rod $BA$ is rigidly fixed at the point $B$, and the point $C$ of the rod $AC$ can slide without friction along the guide $BC$. The rod $BA$ begins to heal in the plane figure around the point $B$ with a constant angular velocity $\omega$. What will be the maximum speed and acceleration of point $C$, if at the initial moment the rods are extended along the guide ($BAC = \pi$)?

Since they are rigid, at any moment of time the projections of the velocities of points $A$ and $C$ onto the direction $AC$ must be equal, that is (see figure)

$$v_A \cos \beta = v_C \cos \alpha.$$

Here $v_A = \omega l$ is the speed of point $A$, $v_C$ is the speed of point $C$ at a given point in time, $\alpha = \omega t$ is the angle that the rod $BA$ ($AC$) makes with the guide $BC$ at a given point in time ($\alpha \leqslant \frac{\pi}{4}$, $\beta = \frac{\pi}{2} - 2\alpha$; at $\alpha \geqslant \frac{\pi}{4}$ $\beta = 2\alpha - \frac{\pi}{4}$). So,

$$v_A \sin 2\alpha = v_C \cos \alpha \Rightarrow v_C = 2v_A \sin \alpha = 2v_A \sin \omega t,$$

that is, the speed of the point $C$ changes with time according to a harmonic law. The value of $v_C$ is maximum at $t = 0$, that is, at the initial moment of time:

$$a_C \max = 2v_A \omega = 2\omega^2 l.$$

L. G. Markovich

⟦folio 47⟧

F819. Three small bodies, the masses of which are in the ratio 3:4:5 (the mass of the body itself is equal to m), are held at three different points on the inner surface of a smooth hemispherical part of radius R, which is fixed at the lowest point on a horizontal surface. At some point the bodies are released and presented to themselves. What is the maximum amount of body that can be released in such a system? At what initial position of the bodies will this happen? All collisions of bodies are absolutely inelastic.

F820. The A-B-C-A process is carried out over one mole of an ideal monatomic gas (Fig. 1). Determine the efficiency of the cycle.

Fig. 1.

Fig. 2.

In order for the amount of heat released to be maximum, the following conditions must be met:

1) the potential energy of the body at the initial moment should be as maximum as possible;
2) the bodies must collide simultaneously at the lowest point of the bowl;
3) the speed of the bodies immediately after the collision must be zero.
If these conditions are met, the entire supply of initial potential energy will turn into heat.

Consequently, the bodies at the initial moment must be located on the bowl at a height R above its lowest point. The location of the body must be such that their total momentum before the collision is equal to zero (then after the collision, the collapsed body remains motionless at the bottom point of the bowl). Since the values ​​of the body’s impulses at any moment of time are in the ratio 3:4:5, the location of the body at the initial moment should be the same as at figure (a top view is shown at figure). The amount of body that will be released in the system is maximum and equal to 4mgR.

S. K. Strokov

The cycle efficiency η is determined by the ratio of the work A performed by the gas during the cycle to the amount of heat Q supplied to the gas during this time:

η = A/Q.

The work done by the gas is numerically equal to the area of ​​triangle ABC (see Fig. 1):

$$A = p_0 V_0 / 2$$

To find Q, consider each section of the cycle separately. In section AB the ishore process is underway. The gas does no work, and the internal energy increases by amounts

$$\Delta U_{AB} = 3 / 2 R (T_B - T_A) = 3 / 2 p_0 V_0.$$

According to the first law of thermodynamics, this increase in internal energy occurs due to the supply of a certain amount of heat

$$Q_{AB} = \Delta U_{AB} = 3 / 2 p_0 V_0.$$

In the CA section, an isobaric process occurs in which the gas is compressed, that is, it does negative work, and the internal energy of the gas decreases. Thus, in this area the gas is separated rather than received.

Let us now find out what is happening in section BC. Here the gas expands and therefore does positive work. The internal energy of the gas first increases and then decreases. Consequently, up to a certain moment the gas receives heat from the outside, and then the heat is released outside. Let us denote the “border” point by the letter D and find its parameters. Let point O be the current point of section BC (Fig. 2) and its parameters - p, V and T. On segment BO, the gas performs work numerically equal to the area of ​​the trapezoid shaded on figure 2:

$$A_{BO} = (p_0 + p / 2) (V - V_0),$$

in this case, its internal energy changes by values

$$\Delta U_{BO} = 3 / 2 R (T - T_B) = 3 / 2 (pV - 2p_0V_0).$$

According to the first law of thermodynamics, an amount of heat must be transferred to the gas

$$Q_{BO} = A_{BO} + \Delta U_{BO} = (p_0 + p / 2) (V - V_0) + 3 / 2 (pV - 2p_0V_0).$$
