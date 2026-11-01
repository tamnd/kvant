---
id: 1978-5-resheniya-zadach-m450-m454-f467-f471-78fd17d0
issue: kvant_1978_5
year: 1978
number: "5"
title: Solutions to problems M450—M454; F467—F471
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 32
page_labels: 24, 25, 26, 27, 28, 30
tag: C4MA
lang: en
source: kvant_digital
extraction: vision
content_sha256: f56a7827b3a2ba065554ee8e8d9d1d9214588eb19190e597279c796797daba1b
prompt_sha256: draft-1
translated_from: content/ru/1978/05/articles/08_resheniya-zadach-m450-m454-f467-f471-78fd17d0.md
source_content_sha256: 04aca496588f4858abde5d518cfa3b7ff170054f80fff376807ac077be7abc21
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

A heavy ball of mass $m$ is attached to one end of the rod, the other end of the rod is attached to a horizontal stiffness spring $k$ (Fig. 5). The spring does not stretch when the rod is vertical. Determine the period of small oscillations of the rod.

Yu. Levchuk

F516. A heavy disk of radius $R$ rolls on two inextensible threads wound around it. The free ends of the threads are secured (Fig. 6). The threads are constantly tense when the disk moves. At some moment, the angular velocity of the disk is $\omega$, and the angle between the threads is $\alpha$. What is the speed of the center of the disk at this moment?

A. Matveev

F517. A beam of electrons with energies of $E=1,0$ keV passes through two small capacitors located at a distance of $l=20$ cm from each other. Both capacitors are connected in parallel to one generator. By changing the frequency of the generator, the electron beam passes through this system without deflection. Determine the ratio $e/m$ for an electron if two successive frequency values ​​at which this condition is satisfied are 141 MHz and 188 MHz.

Problem solutions

M450—M454; F467—F471

M450. A system of rectangles consisting of n elements (Fig. 1) is constructed as follows. Starting from the lower rectangle forming the first edge, the upper side of each rectangle is divided in the ratio 1: 2: 3; on the three resulting segments, as on the basis of a strict rectangle, the same can be drawn as the original one, and so on - up to the very top edge. From the resulting set of rectangles, a certain subset is selected, consisting of pairwise non-congruent rectangles (one subset on figure is red). Prove that we can find a vertical line intersecting at most two of the selected rectangles.

Let us estimate the total area of ​​pairwise noncontinuous rectangles. The area of ​​each of them is equal to $S/3k^2m$, where $S$ is the area of ​​the lower rectangle, $k$ and $m$ are integers, $k \geq 0, m \geq 0, k + m \leq n$. The sum of different x numbers of the form $1/3k^2m$ does not exceed

$$1 + \frac{1}{3} + \frac{1}{3^2} + \dots + \frac{1}{3^n} +$$

$$+ \frac{1}{2} + \frac{1}{2 \cdot 3} + \frac{1}{2 \cdot 3^2} + \dots + \frac{1}{2 \cdot 3^n} +$$

$$+ \frac{1}{2^2} + \frac{1}{2^2 \cdot 3} + \frac{1}{2^2 \cdot 3^2} + \dots + \frac{1}{2^2 \cdot 3^n} + \dots + \frac{1}{2^n} + \frac{1}{2^n \cdot 3} + \frac{1}{2^n \cdot 3^2} + \dots + \frac{1}{2^n \cdot 3^n}.$$

The sum of the numbers in the columns is less than the corresponding $2,2 \cdot \frac{1}{3},2 \cdot \frac{1}{3^2},\dots$

$$\dots,2 \cdot \frac{1}{3^n},a 2 \left(1 + \frac{1}{3} + \frac{1}{3^2} + \dots + \frac{1}{3^n}\right) < 2 \cdot \frac{3}{2} = 3.$$

Not if every vertical line intersected three

⟦folio 25⟧

M451. Several points are marked on the plane that do not lie on the same straight line, and a number is written next to each one. It is known that if a line passes through or more marked points, then the sum of all numbers written near these points is equal to zero. Let's prove that all numbers are equal to zero.

For a marked point $x$, let us denote by $a_x$ the number written near it, and by $n_x$ the number of pairwise distinct straight lines connecting the point $x$ with all other marked points. Let $S$ be the sum of the numbers written near all marked points. By condition, the sum of the numbers at the marked points of each of the $n_x$ lines passing through $x$ is equal to zero. Therefore, the sum of the numbers along all these $n_x$ lines is equal to zero. On the other hand, this sum is $(n_x-1)a_x+S$, so

$$(n_x-1)a_x+S=0.$$

Suppose that for some point $x$ the number $a_x>0$. Then there is a marker point $y$, near which the number $a_y<0$ is written (prove it!). Using (1), we obtain the equality

$$(n_y-1)a_y=(n_x-1)a_x.$$

By condition, all marked points do not lie on the same line. Therefore $n_x>1$ and $n_y>1$. We have arrived at a contradiction, since in equality (2) there is not a trace on the right of a number of different signs.

F. Vainitsa

M452. Triangles $T_1$ and $T_2$ are inscribed in a circle, and the vertices of triangle $T_2$ are the midpoints of the line on which the circle is divided by the vertex of triangle $T_1$. Let us prove that in the hexagon $T_1 \cap T_2$ the diagonals connecting opposite vertices are parallel to the sides of the triangle $T_1$ and intersect at one point.

Let $A, B$ and $C$ be the vertices of triangle $T_1$, and $A', B'$ and $C'$ be the vertices of triangle $T_2$ (and $A'$ is the midpoint of arc $BC$, $B'$ is the midpoint of arc $AC$, and $C'$ - the middle of the arc $AB$, Fig. 2). The lines $AA', BB'$ and $CC'$, which are the bisectors of the angles of the triangle $T_1$, intersect at the center $O$ of the inscribed circle $T_1$ in the triangle. Let $MN$ be the diagonal connecting opposite vertices $M$ and $N$ of the hexagon $T_1 \cap T_2$ ($M=[AB] \cap [B'C']$, $N=[BC] \cap [A'B']$). Let us prove that $(MN)$ is parallel to $(AC)$ and passes through the point $O$ (the statement of the problem will follow from this). To do this, we will prove that the segments $OM$ and $ON$ are parallel to $AC$. Then $[OM] \parallel [ON] \parallel (AC)$, which implies that the points $M$, $O$ and $N$ lie on the same line parallel to $(AC)$. So, we need to prove that $[OM] \parallel (AC)$ (the proof of the parallelism of $[ON]$ and $(AC)$ is similar). Let $K=[OA] \cap [B'C']$. Note that the angle $C'KA'$ rests on arcs whose magnitudes add up to $180^\circ$ (why?), and is therefore a straight line. Thus, $[B'K]$ in triangle $OB'A$ is both a bisector and an altitude. Therefore, $[B'C']$ is the perpendicular bisector to the segment $AO$; therefore $|AM|=|OM|$ and $OAM=AOM$. But $OAM=OAC$ and, therefore, $AOM=OAC$. And this means that the segment $OM$ is parallel to the side $AC$, which is what needed to be proven.

N. Nechevaem

⟦folio 26⟧

M453. Given a set of positive numbers $\{a_1; a_2; \dots, a_n\}$. For each of its subsets, we write down the sum of the numbers included in it (we consider the sums of one, two, ..., n layers). Prove that all the written numbers can be divided into n groups so that in each group the ratio of the largest number to the smallest does not exceed 2.

It is enough to indicate $n$ segments of the form $[b_i, 2b_i]$ ($i = 1, 2, \dots, n$), the union of which contains all the sums of some of the given $n$ numbers: then the sums belonging to each segment form a group of numbers that satisfy the required conditions.

These segments can be constructed in different ways. Let's give the most beautiful method (it was pointed out by D. Bernishtein).

Let's put these numbers in ascending order: $a_1 \leqslant a_2 \leqslant \dots \leqslant a_n$, put $b_i = (a_1 + a_2 + \dots + a_i)/2$ and prove that each sum of some of the numbers $a_i$ falls into one of the segments $[b_i, 2b_i]$.

It is clear that the smallest “sum” is $a_1 \in [b_1, 2b_1]$, since $2b_1 = a_1$, and the largest is $(a_1 + \dots + a_n) \in [b_n, 2b_n]$, since $2b_n = a_1 + \dots + a_n$. It remains to prove that the case when some sum $s$ lies between $2b_k$ and $b_{k+1}$ is impossible. Let

$$s > 2b_k = a_1 + a_2 + \dots + a_k.$$

(1)

Then $s$ contains some $a_i \geqslant a_{k+1}$, that is

$$s \geqslant a_{k+1}.$$

(2)

Adding (1) and (2), we obtain $2s \geqslant a_1 + \dots + a_k + a_{k+1}$, that is, $s \geqslant b_{k+1}$. This means that $s$ cannot lie between $2b_k$ and $b_{k+1}$.

M454. We sit at a round table for 7 days. There is a mug in front of each stone. Some of these mugs contain the least amount of milk. For one of the eaters, we pour all our milk into the mugs of the others equally. Then his neighbor on the right does the same. Then we do the same for the next neighbor on the right, and so on. After the last, seventh, 第八im shared their milk with everyone else, each mug contained the same amount of milk as it had at the beginning. All mugs together contain 3 liters of milk. How much milk was initially in each mug?

The answer is shown at figure 3. Let's check it. After the gnome marked with a red dot distributes his milk equally to the others (1/7 liter each), you will again get (with a shift by one gnome) exactly the same distribution of milk; in this case, the gnome whose turn it is to pour the milk will have 6/7 liters of milk. It is clear that after seven transfusions we will return to the original distribution.

Let us now show how this answer could be made, and we will prove its only answer. Note that in the conditions of the problem the process of pouring in a circle can be considered periodically continued; therefore, all gnomes are completely equal in rights.

It is natural to first look for a distribution of milk that will be repeated (with a shift by one gnome) after one transfusion. In this case, each subsequent gnome will pour the same amount of milk as the previous one - say, 6 liters (each gnome is poured x liters). Then after the next transfusion, the one who spilled it will have 0 liters of milk, his neighbor (who spilled it in front of him) will have $x$, the next one (he had $x$ before) will have $2x$, ..., the last, seventh, gnome will have $6x$ liters. From equation $x + 2x + \dots + 6x = 3$ we find $x = 1/7$ and get the above answer.

However, it is still necessary to find out whether it could be that the gnomes pour out different amounts of milk (and the original distribution is restored only after seven transfusions). Let the $k$th dwarf pour out $6x_k$ liters of milk ($x_k$ liters each). Since gnomes have equal rights, we can assume that $x_1 \geqslant x_k$ is $k = 1, 2, \dots, 7$ for all. After seven transfusions, the 1st gnome who spilled $6x_1$ liters of milk should again have $6x_1$ liters, so $6x_1 = x_2 + x_3 + x_4 + x_5 + x_6 + x_7$. This is only possible when $x_1 = x_2 = \dots = x_7$. Thus, we come to the already dismantled hearing, when all the dwarves pour out the same amount of milk. So there are no other answers.

Note that from the general theorems of linear algebra, which underlie the theory of Markov chains, not only the only answer to this problem follows, but also the following curious fact: no matter how 3 liters of milk were initially poured, its distribution will tend (with an increase in the number of transfusions) to the distribution indicated in the answer (0, 1/7, 2/7, ..., 5/7, for the spiller - 6/7 liters). We will try to talk about these theorems in one of the next issues of Quat.

Fig. 3.

N. Vasiliev

⟦folio 27⟧

F467. The Moon is simultaneously formed from the same side from the Earth and from the Moon's satellite. The satellite's orbit is steep. The diameter of the image of the Moon on the formation obtained on Earth is 4 mm, and on the Moon’s satellite it is 250 mm. Find the period of revolution of the Moon's satellite along its orbit if the photograph was taken using identical objects with a focal length of 500 mm. Accept that the acceleration of gravity on the Moon is six times less than on Earth, and the distance from the Earth to the Moon is 380,000 km.

Fig. 4. Fig. 5.

A lunar satellite moving in a circular orbit of radius $R$ is subject to a cohesion effect from the Moon equal to $F = \gamma \frac{M_{\perp} m}{R^2}$ (m is the mass of the satellite, $M_{\perp}$ is the mass of the Moon). Considering that the acceleration of gravity on the Moon is $g_{\perp} = \gamma \frac{M_{\perp}}{r_{\perp}^2}$ ($r_{\perp}$ is the radius of the Moon), we can write

$$F = mg_{\perp} \left( \frac{r_{\perp}}{R} \right)^2.$$

This force imparts centripetal acceleration to the satellite. $|\vec{a}| = \omega^2 R = \frac{4\pi^2 R}{T^2}$, where $\omega = \frac{2\pi}{T}$ is the angular velocity of rotation of the satellite, $T$ is the period of its orbit. So, $|\vec{F}| = m|\vec{a}|$, that is

$$mg_{\perp} \left( \frac{r_{\perp}}{R} \right)^2 = m \frac{4\pi^2 R}{T^2}.$$

From here

$$T = 2\pi \frac{R}{r_{\perp}} \sqrt{\frac{R}{g_{\perp}}}.$$

This formula includes two unknown quantities - $R$ and $r_{\perp}$. We will find them by “using” photographs of the Moon obtained from the Earth and from the satellite. The image of the Moon is obtained in the focal plane of the object. The Moon is located at a distance from the Earth much greater than its diameter. Therefore, we can assume that when photographing from the Earth (Fig. 4)

$$\frac{d_1}{2r_{\perp}} = \frac{F}{L}, \quad r_{\perp} = \frac{d_1 L}{2F}$$

($d_1$ is the image diameter, $L$ is the Earth-Moon distance, $F$ is the focal length of the lens).

When photographed from a satellite (Fig. 5), the film produces an image of the part of the lunar surface limited by the tangents $OA$ and $OB$. From the similarity of triangles $OMN$ and $OCB$ we have

$$\frac{BC}{MN} = \frac{R}{ON} \Rightarrow \frac{2r_{\perp}}{d_2} = \frac{R}{a},$$

where $a = \sqrt{F^2 + \left(\frac{d_2}{2}\right)^2}$. From here

$$R = \frac{2r_{\perp}}{d_2} a = \frac{d_1 L}{d_2 F} a.$$

Substituting the found expressions for $r_{\perp}$ and $R$ into (*), we obtain

$$T = 4\pi \frac{a}{d_2} \sqrt{\frac{d_1 L}{g_{\perp} d_2 F}} a \approx 6,23 \cdot 10^4 \text{ c.}$$

I. Slovodechkiy

◆ The maximum load that the crane can withstand is determined by the tensile strength of the cable materials - the maximum stress at which the material does not yet fail.

Let us assume that all slab models are $q$ and the cross-sectional area of ​​the cable is $s$. For example, emerging

⟦folio 28⟧

What is the material if the linear dimensions of the tap, prose and slabs are 12 times larger than in the model?

with a load of one slab, equal to $\sigma = \frac{q}{s}$. According to the problem data, the strength limit of the cable material is determined by the condition

$$\frac{10q}{s} < \sigma_0 < \frac{11q}{s}$$

(1)

(the condition is that the model crane lifts 10 slabs, but the cable cannot withstand a load of 11 slabs).

When moving to a real tap and slabs, all linear dimensions increase by $n = 12$ times. This means that the weight of the plate increases by $n^3$ times, the cross-section of the cable increases by $n^2$ times:

$$Q = n^3q, S = n^2s$$

(2)

(since the density of the corresponding materials does not change). The maximum number of slabs that a real crane can lift is determined by the condition

$$\sigma_0 > N \frac{Q}{S} = N \frac{n^3q}{n^2s} = Nn \frac{q}{s},$$

(3)

where

$$N < \frac{\sigma_0}{12 \frac{q}{s}}.$$

But from correspondence (1) it follows that

$$\frac{\sigma_0}{11 \frac{q}{s}} < 1.$$

Hence,

$$N < \frac{\sigma_0}{12 \frac{q}{s}} < \frac{\sigma_0}{11 \frac{q}{s}} < 1,$$

that is, a real crane cannot lift a single slab.

S. Kromov

F469. Figure 6 is made with a strombocoptic cube formation moving along an inclined plane. The time intervals between successive lamp removals are 0.1 s. Determine the coefficient of friction of the cube on the plane.

Fig. 6.

First of all, we determine the value of the acceleration with which the cube moves. As is known, the difference between the distances $l_1$ and $l_2$ passed by a body in successive equal time intervals $\tau$ is equal to $l_2 - l_1 = |\vec{a}| \tau^2$, where $\vec{a}$ is the acceleration with which the body moves. Having determined by figure using a ruler and a given scale $l_2 - l_1$, we find

$$|\vec{a}| = \frac{l_2 - l_1}{\tau^2} \approx \frac{0,07}{(0,1)^2} \text{ м/c}^2 = 7 \text{ м/c}^2.$$

Let us now determine in which direction (up or down the inclined plane) the cube moves. The maximum acceleration with which a cube can freely slide is the acceleration imparted to it by the force of gravity in the direction of the $X$ (Fig. 7) axis in the absence of friction forces: $$|\vec{a}_{\max}| = |\vec{g}| \sin \alpha.$$ From figure we find $\sin \alpha = \frac{3}{5}$, so that

$$|\vec{a}_{\max}| = |\vec{g}| \frac{3}{5} \approx 6 \text{ м/c}^2.$$

We found that $|\vec{a}| = 7 \text{ м/c}^2$. This means that the cube moves up along the inclined plane, and the acceleration along the $X$ axis is imparted to it by the force of gravity (its projection on the $X$ axis) and the friction force directed downward on the inclined plane.

⟦folio 30⟧

In a state of equilibrium, the number of particles present in the cavity should remain constant. This means that the number of particles entering the cavity from volumes I and II must be equal to the number of particles leaving the cavity.

The number of particles entering the cavity from volume I per unit time is directly proportional to the density $n_I$ of particles in volume I and the mean square speed $\bar{v}_{KBI}$ of particles in this volume (since the processing power for any given direction is proportional to the mean square speed): $N_I \sim n_I \bar{v}_{KBI}$. The value $n_I$ is directly proportional to the pressure $p$ in volume I and inversely proportional to the value $\bar{v}^2: n_I \sim \frac{p}{v_I^2}$. In turn $\bar{v}^2_I \sim T$,

$$\bar{v}_{KBI} \sim T^{1/2}.$$

Thus,

$$N_I = \alpha p T^{-1/2},$$

where $\alpha$ is the proportional coefficient. Similarly, for the number of particles entering the cavity per unit time from volume II, we can write

$$N_{II} = \alpha p (2T)^{-1/2}.$$

The number of particles entering the cavity per unit time through two branches is equal to

$$N = 2 \alpha p_\pi T_\pi^{-1/2},$$

where $p_\pi, T_\pi$ are the corresponding pressure and temperature in the cavity. In the equilibrium state, condition $N_I + N_{II} = N$ is satisfied, that is

$$\alpha p T^{-1/2} + \alpha p (2T)^{-1/2} = 2 \alpha p_\pi T_\pi^{-1/2},$$

or

$$p T^{-1/2} + p (2T)^{-1/2} = 2 p_\pi T_\pi^{-1/2}.$$

(1)

In a state of equilibrium, the total energy of the particles in the cavity does not change with time. This means that the energy brought into the cavity per unit time by $N_I$ and $N_{II}$ particles is equal to the energy carried away by $N$ particles entering the cavity: $E_I + E_{II} = E$. Since the average energy $E_{cp}$ per particle is directly proportional to temperature, then $E_I = NE_{cpI} \sim p T^{-1/2} T = \beta p T^{1/2}, E_{II} = \beta p (2T)^{1/2}, E = 2 \beta p_\pi T_\pi^{1/2}$, where $\beta$ is the coefficient of proportionality. Thus,

$$\beta p T^{1/2} + \beta p (2T)^{1/2} = 2 \beta p_\pi T_\pi^{1/2},$$

or

$$p T^{1/2} + p (2T)^{1/2} = 2 p_\pi T_\pi^{1/2}.$$

(2)

Having solved equations (1) and (2) together, we find

$$T_\pi = T \sqrt{2}, \quad p_\pi = p \frac{\sqrt{2} + 1}{2 \sqrt{2}}.$$

I. Slobodetsky
