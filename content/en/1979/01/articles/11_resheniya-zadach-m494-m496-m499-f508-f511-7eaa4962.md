---
id: 1979-1-resheniya-zadach-m494-m496-m499-f508-f511-7eaa4962
issue: kvant_1979_1
year: 1979
number: "1"
title: Solutions to problems M494, M496—M499; F508—F511
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 37
page_labels: 30, 31, 33, 34, 35
tag: OD2N
lang: en
source: kvant_digital
extraction: vision
content_sha256: b214a9d9b8daf51d48772f909f42e27d7e0ce02e05afa33f7e1e4d48b98a4d66
prompt_sha256: draft-1
translated_from: content/ru/1979/01/articles/11_resheniya-zadach-m494-m496-m499-f508-f511-7eaa4962.md
source_content_sha256: 63123778ed4fcb89c63eb8d32ce163873f97a1ac125270c4d2f011a315af6029
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

Problem solutions
M494, M496—M499; F508—F511

M494. Inside the square on side 1 there are $n^2$ points. Prove that there exists a broken line containing these points whose length is less than a) 3n; b) 2n.

The idea of ​​constructing a broken line is clear from figure 1: we divide the square into $n$ vertical stripes and then discuss all the points in a “snake” manner: we pass the first stripe on the left from the top of the view, the next from the bottom up, etc. The sum of the lengths of the links of the broken line is not greater than the sum of the lengths of their projections onto the vertical and horizontal sides of the square. The sum of vertical projections, as is easy to see, does not exceed $n$, and the sum of horizontal projections can be estimated as follows. The horizontal projection of a link that does not intersect the boundaries of the strips does not exceed $1/n$, and the projection of a link that intersects $k$ of the vertical segments of the boundaries of the strips does not exceed $(k+1)/n = k/n+1/n$. The total number of vertical boundaries of the strips is $n-1$, so the sum of all $n^2-1$ horizontal projections is no more than

$(n^2-1)/n+(n-1)/n=n+1-2/n \leq n+1$.

Thus, for the length of the broken line we obtain the estimate $2n+1$.

Fig. 1. Fig. 2. Fig. 3.

Problem a) solutions, and to prove 6), you need to improve the estimate by 1.

To do this, we need to change our design. Let's divide the square into $n$ stripes of different widths $(h_1, h_2, \dots, h_n)$ so that each strip has exactly $n$ points (“border” points can be assigned to both the left and the right). Let's connect all the upper points of the stripes and all the lower points with segments of alternately red and blue colors (Fig. 2). We can choose the beginning of the snake line so that it goes either along all the blue segments or along all the red ones. The sum of horizontal projections $2(n-1)$ of red and blue segments of the broken line together is not more than 2; if we choose the color for which this sum is less than 1, we will obtain the estimate for the sum of all horizontal projections

$(n-1)(h_1+h_2+\dots+h_n)+1 \leq n$.

The sum of vertical projections, as before, is no more than $n$.

So, we have constructed a broken line of length no greater than $2n$, we decided 6).

An example of a “dense” arrangement of points at the vertices of a triangular lattice (Fig. 3; for large $n$, in order to square $1 \times 1$ $n^2$ points, you need to take the length of the side of the triangle equal to approximately $\sqrt{2/\sqrt{3}}/n$) shows that the constant $2$ under the conditions of specifying obviously not LZ (further for large $n$) replace with a number smaller than $\sqrt{2/\sqrt{3}}$.

N. Vasiliev, A. Tarmakovsky

⟦folio 31⟧

M496. Which six-digit numbers are greater: those that can be represented as the product of two three-digit numbers or those that cannot be represented?

There are only 900 three-digit numbers (from 100 to 999). Therefore, there are only $\frac{900 \cdot 899}{2} + 900 = \frac{900 \cdot 901}{2} = 405450$ pairs of (not necessarily different) three-digit numbers.

Therefore, there are no more than this number of six-digit numbers, representable as the product of two three-digit numbers. And there are 900,000 six-digit numbers in total. This means that more than half of them cannot be represented as the product of two three-digit numbers.

N. Vasiliev

M497. On sides BC, CA and AB of acute triangle ABC, arbitrary points A₁, B₁, C₁ are taken; Circles are constructed on segments AA₁, BB₁ and CC₁ as on diameters. Prove that the three common chords of pairs of these circles intersect at the point of intersection of the altitudes of triangle ABC.

The solution to this problem uses the following nice theorem:

If three circles intersect in pairs, then at , the common chords of each pair of circles (or their extensions) pass through one point or are parallel (Fig. 4).

We will first solve the problem and then give a sketch of the proof of the theorem.

Let us construct on the segments AB, AA₁ and BB₁ as on the diameters of the circle OₑB, OₑA₁ and OₑB₁, respectively. The common chord of circles OₑB and OₑA₁ is obviously the altitude AHₐ of triangle ABC (since $\widehat{AH}_A B = \widehat{AH}_A A_1 = 90^\circ$; Fig. 5). Similarly, the common chord of circles OₑB and BHₐ of triangle ABC.

It is similarly proved that the common chords of two other pairs of circles: OₑA₁ and OₑC₁, OₑC₁ and OₑB₁ pass through the point of intersection of the altitudes of triangle ABC. Solution problem.

It remains to prove the theorem.

Let's construct three spheres with centers in the plane of the circles on these circles (lying in the horizontal plane) and look at them from above. We will see three circles along which the spheres intersect (their projections on the horizontal plane are our three chords), and the point of their intersection (its projection is the desired intersection point of the chords).

V. Gutemacher

M498. For every natural number n ≥ 3 indicates the smallest k such that any n points in the plane, no three of which lie on a given line, can be separated by k lines.

Many of those who sent us a solution to this problem remembered this fact (it is not difficult to prove using induction):

k straight lines divide the plane into no more than $\frac{k(k+1)}{2} + 1$ parts (for k straight lines in general position there will be exactly $\frac{k(k+1)}{2} + 1$).

⟦folio 33⟧

F508. The period of Mercury's revolution around the Sun is 88 Earth days, and around its axis - 59 Earth days. What is the length of day and night on Mercury?

Let us denote the length of a day on Mercury by $x$ (Earth days). In one earthly day, Mercury will rotate around its axis by an angle of $\frac{360^\circ}{59}$ and will shift along its orbit (in the same direction) by an angle of $\frac{360^\circ}{88}$. The difference $\frac{360^\circ}{59} - \frac{360^\circ}{88}$ represents the angle at which Mercury will rotate relative to the Sun during one Earth day:

$$\frac{360^\circ}{59} - \frac{360^\circ}{88} = \frac{360^\circ}{x}.$$

From here

$$x \approx 179$$

A day on Mercury is approximately equal to two Mercury years.

Consequently, a Mercurian day and hour are approximately equal in length to its year.

E. Levitan

F509. The lake has a current that captures only the top layer of water. A raft with a sound-catching annapagura floats downstream. At the bottom, ahead of the current, there is a motionless source of sound. An observer on the raft discovered that the sound reached the raft in a direction making an angle of $\beta$ with the vertical. What is the angle from vertical to the true direction of the sound source? The speed of the current is $u$, the speed of sound in water is $v$. The thickness of the moving layer is much less than the thickness of the ocean.

Fig. 8.

Fig. 9.

At the boundary $AB$ of the moving layer, the sound somehow changes its direction - it is refracted (Fig. 8). The sound reaches the raft $P$ at an angle $\beta$ equal to the angle of refraction. Since the layer is thin, we can take the angle $CPS$ to be equal to the angle of incidence $\alpha$. Thus, the task is to derive the law of refraction of a sound wave at the boundary of motionless and moving media.

Let $CO$ be the direction of sound propagation in a motionless medium and $KO$ be the position of the wave surface (wave front) at some moment $t$ (Fig. 9). After a period of time $\Delta t$, the wave front will take position $K'O'$. In the same way, let us denote by $OD$ the direction of sound propagation in the upper layer of water (from the point of view observed on the raft), and by $OL$ and $O'L'$ the positions of the wave front at moments $t$ and $t + \Delta t$.

During time $\Delta t$, the wave front $KO$ moves to a distance $|MO'| = |v| \Delta t (MO' \perp KO)$, and the point of intersection of the front with the surface of the separated media moves to a distance $|OO'| = \frac{|v| \Delta t}{\sin \alpha}$. Similarly, the displacement of the point of movement of the wave front $OL$ with the interface relative to the observed wave incidence ($\alpha \rightarrow \pi/2$, $\sin \alpha \rightarrow 1$) the angle of refraction does not exceed the value

$$\beta \rightarrow \arcsin \frac{1}{1 + |u|/|v|}$$

It turns out that the same law of refraction is also true when the raft has already blown dust over the sound source. True, in this case the angle of refraction $\beta$ is greater than the angle of incidence $\alpha$, therefore, refraction is possible only at angles

⟦folio 34⟧

Denying

$$\alpha < \alpha_{\text{np}} = \arcsin \frac{1}{1 + |\vec{u}| / |\vec{v}|}.$$

At large angles, complete reflection of sound from the moving layer occurs.

G. Komkin

F510. A strong rubber mesh is stretched over the rubber ball, the threads of which are drawn along the meridians of the ball. What shape will the ball take if pressure is applied to it?

Let us consider one of the threads and select a small section of length $l$ (Fig. 10) on it. Let us denote the tension force of the thread by $\vec{T}$. The resultant $\vec{Q}$ tension forces acting on the selected area is equal in absolute value to $2|\vec{T}| \sin \frac{\alpha}{2}$.

At $l \ll R$ ($R$ is the radius of curvature of the thread at a given location) $\alpha = \frac{l}{R} \ll 1$, therefore we can assume that

$$\sin \frac{\alpha}{2} = \frac{\alpha}{2}, \quad |\vec{Q}| = \frac{l}{R} |\vec{T}|.$$

Since the selected section of the thread is in equilibrium, the sum of all forces acting on it is equal to zero. This means that a force acts on the thread from the side of the ball

$$\vec{F} = -\vec{Q}.$$

According to Newton's third law, a force acts on the ball from the side of the thread

$$-\vec{F} = -(-\vec{Q}) = \vec{Q},$$

directed towards the center of the ball.

The same number of threads $N$ passes through any parallel of the ball. For a parallel of radius $r = R \cos \varphi$ ($\varphi$ is the angle formed by the radius of the ball drawn to the parallel with the equatorial plane) is equal to $2\pi r = 2\pi R \cos \varphi$. Consequently, the number of threads passes through a section of the ball shell with area $l \times l$

$$n = \frac{N}{2\pi R \cos \varphi} l.$$

Then the pressure exerted on the shell is equal to

$$p = n \frac{|\vec{Q}|}{l^2} = \frac{N |\vec{T}|}{2\pi R^2 \cos \varphi}.$$

If the shell of the ball remained spherical, the pressure would increase with increasing angle $\varphi$. In fact, according to Pascal's law, the pressure would be increased by the same thing. This means that the shell of the ball is not spherical. It is spree along the equator than along the vertical diameter; the radius of curvature of the meridian decreases towards the equator and increases towards the pole so that $R^2 \cos \varphi = \text{const}$.

The shape of the shell resembles a pumpkin (Fig. 11). Perhaps the shape of the pumpkin is precisely explained by the presence of “reinforcing threads” and souls along its meridians?

F511. The plates of a parallel plate capacitor with area $S$ form a small angle $\alpha$ ($\alpha \ll 1$) from each other. The average distance between the plates is $b$. Draw an approximate picture of the flat lines of the electron field of the capacitor and find the capacitance of the capacitor.

An approximate picture of confluent electron lines of circles with a center at the point $O$. Indeed, the drain lines are always perpendicular to the surface of the conductor, which means they are perpendicular to the capacitor plates. From the reports of symmetrines it is very clear that they are perpendicular to the bisector of the angle formed by the plates. If a thin metal plate had been in place of the bisector, the picture of the plum lines would not have changed in any way. Reasoning in a similar way, we will come to the conclusion that drain lines should

⟦folio 35⟧

be perpendicular to any ray emanating from the point $O$ and being inside the angle $\alpha$. This means that strong lines are arcs of concentric circles.

The density of the field lines is not always the same; it decreases along the $X$ axis. This is not difficult to explain. As is known, the density of field lines is proportional to the voltage of the electric field. Let's find how the voltage changes as the coordinate $x$ increases (the origin of coordinates is located at point $B$). The work of moving a unit charge from one capacitor plate to another along the south-south strong line should be the same (this work is equal to the potential difference between the plates). Therefore, the longer the power line, the lower the voltage (force acting on a unit charge). Taking into account the smallness of the angle $\alpha$ we obtain

$$|\vec{E}| = |\vec{E}_0| \frac{b}{b + \alpha x},$$

where $\vec{E}_0$ is the voltage on power line $AB$ (where the distance between the capacitor plates is $b$), $\vec{E}$ is the voltage on the adjacent power line, separated from $AB$ by $x$, $b$ and $b + x$ - the lengths of the corresponding power lines.

The density of the power lines also changes.

Now let's find the capacitance $C$ of the capacitor. By definition

$$C = \frac{q}{U},$$

where $q$ is the charge and $U$ is the capacitor voltage. $U$ can be expressed through $|\vec{E}_0|$:

$$U = |\vec{E}_0| b.$$

It remains to express $q$.

Near the plate, the electric field is similar to the field of the plane; therefore its voltage

$$|\vec{E}| = \frac{\sigma}{2\varepsilon_0},$$

where $\sigma$ is the surface charge density, $\varepsilon_0$ is the electrical constant. From here

$$\sigma = 2\varepsilon_0 |\vec{E}| = \frac{2\varepsilon_0 |\vec{E}_0| b}{b + \alpha x}.$$

Let us denote by $l$ the “depth” of the plate and select a narrow strip of width $\Delta x$ on the plate. Its charge is equal

$$\Delta q = \sigma l \Delta x = \frac{2\varepsilon_0 |\vec{E}_0| b l}{b + \alpha x} \Delta x.$$

To find the entire charge of the plate, we need to sum up the charges of all elementary strips and go to the preposition at $\Delta x \rightarrow 0$. As a result we get

$$q = 2\varepsilon_0 b l |\vec{E}_0| \int_{-a}^{a} \frac{dx}{b + \alpha x} = \frac{2\varepsilon_0 b l |\vec{E}_0|}{\alpha} \ln \frac{b + \alpha a}{b - \alpha a}.$$

Then finally

$$C = \frac{q}{U} = \frac{2\varepsilon_0 l}{\alpha} \ln \frac{b + \alpha a}{b - \alpha a}.$$

I. Slovodetsky
