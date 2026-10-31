---
id: 1976-10-resheniya-zadach-m365-m370-f373-f377-e25cc171
issue: kvant_1976_10
year: 1976
number: "10"
title: Solutions to problems M365—M370; F373—F377
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 47
page_labels: 34, 35, 36, 37, 38, 39, 40, 43, 44, 45
tag: 6CZV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4df16b9829b242525918654f55d37d5c51c1d88b7f0eedd655c81f10e028c046
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/11_resheniya-zadach-m365-m370-f373-f377-e25cc171.md
source_content_sha256: 658a8dc4bd7b1079aa599f74aa4fb43bfedb072e4958fb98cd5baa6e2bc9b5f3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

Problem solutions

M365). a) The sum of several numbers is equal to one. Can the sum of their cubes be greater than one?
b) The same question for numbers, each of which is less than one.
c) Is it possible that the series $a_1 + a_2 + a_3 + \dots$ is coded, but the series $a_1^3 + a_2^3 + a_3^3 + \dots$ is not?
(Recall that the series $x_1 + x_2 + x_3 + \dots$ is said to be collapsible if the sequence of numbers $S_n = x_1 + x_2 + \dots + x_n$ has a limit.)

Fig. 1.

M366. Is it possible to arrange several triangles on a plane so that two vertices of each of them lie on the sides (but not at the vertices) of other triangles?

M367. Can the product of a) three b) four consecutive natural numbers equal some natural number (square, cube, etc.)?

*) Problem M364 was solved in the article by L. Beve “Minigeometry”, see «Kvant», 1976, No. 6, p. 11.

The answer to all three questions is yes. Let us give examples showing that something so random can be.

a) Two numbers: 2 and -1.

b) Eight numbers: 4/5, 4/5, -1/10, -1/10, ..., -1/10.

Their sum is 1, and the sum of the cubes is $2 \cdot (4/5)^3 - 6 \cdot (1/10)^3 = 1,018$. The following example is based on the same idea - comparing positive numbers and adding negative numbers to them - in larger quantities, but in smaller quantities.

b) Let's make a series

$$1 + (-1/2) + (-1/2) + 1/2 + (-1/4) + (-1/4) + (1/2) + (-1/4) + (-1/4) + \dots$$

as follows: after the sum 1 + (-1/2) + (-1/2) we put 2^3 = 8 sums $1/2$ + (-1/4) + (-1/4), then 3^3 = 27 sums $1/3$ + (-1/6) + (-1/6), ..., $n^3$ sums $(1/n) + (-1/2n) + (-1/2n)$, and so on. This series converges and its sum is equal to zero, since the sum $N$ of the first of its terms, where 3 ($1 + 2^3 + 3^3 + \dots + n^3$) ≤ $N \leq 3$ [1 + 2^3 + 3^3 + ... + ($n + 1$)], is not greater than $1/(n+1)$ (namely, it is either zero, or $1/(n+1)$, or $1/(n+1)$). The corresponding row of cubes diverges. Indeed, the sum of $n^3$ of the sums of $(1/n)^3 + (-1/2n)^3 + (-1/2n)^3 = 3/4n^3$ is equal to $3/4$, so the sum of the first 3 ($1 + 2^3 + \dots + n^3$) terms of the series is equal to $3n/4$.

Of course, if in the problem statement all numbers are assumed to be positive, then the answers to all three questions will be negative.

N. Vasiliev

The conditions of the problem do not stipulate that the triangles should not intersect, and some of our readers solved the problem, considering the intersection possible (in this case, the solution looks, of course, quite simple). For non-intersecting triangles, the answer to the question remains positive: figure 1 shows how 6 triangles can be arranged on a plane in the required manner.

B. Kolosov

a) Let us assume that $k(k+1)(k+2)=u^n$, $n>1$. The number $k+1$ is coprime with the numbers $k$ and $k+2$; therefore $k+1=m^n$, $k(k+2)=k^2+2k=l^n$ (this is a consequence of the Fundamental Theorem of Arithmetic on the uniqueness of the decomposition of natural numbers into prime factors). Then $(k+1)^2=k^2+2k+1=m^2n$, that is, $(m^2)^n — l^n = 1$, is a contradiction: $(a^n - b^n) = (a - b)(a^{n-1} + a^{n-2}b + \dots + b^{n-1}) \neq 1$. This means that the product of three consecutive natural numbers cannot be a power of a natural number.

b) Let us prove that in this case the answer is negative. Let us assume the opposite: let us assume that for some $k(k+1)(k+2)=u^n$.

⟦folio 35⟧

The reasoning will be the same as in task a): we construct two close numbers, each of which must be the $n$th power, and a method for contradiction. The distance is separate for $n = 2$ and $n \ge 3$.

I. $n = 2$. We have $(k^2 + 3k)(k^2 + 3k + 2) = u^2$. Denoting $k^2 + 3k + 1$ by $y$, we obtain the equality $y^2 - 1 = u^2$, which is impossible for the natural numbers $u$ and $y$.

II. $n \ge 3$. Note that either the number $k + 1$ or $k + 2$ is coprime to the other three numbers.

1) Let the number $k + 1$ be coprime with $k$, $k + 2$ and $k + 3$. Then (see solution to point a)) $k + 1 = m^n$, $k(k + 2)(k + 3) = l^n$. We have $k = m^n - 1$, $k + 2 = m^n + 1$, $k + 3 = m^n + 2$; means $(m^n - 1)(m^n + 1)(m^n + 2) = m^{3n} + 2m^{2n} - m^n - 2 = l^n$. Because $m \ge 2$ and $n \ge 3$, $2m^{2n} - m^n - 2 > 0$, that is $l^n > (m^3)^n$, or $l > m^3$. On the other hand, $(m^3 + 1)^n > m^{3n} + nm^{3n-3} > m^{3n} + 2m^{2n} - m^n - 2 = l^n$, from where $l < m^3 + 1$. So there must be $m^3 < l < m^3 + 1$, which is impossible for the naturals $m$ and $l$.

2) If the number $k + 2$ is coprime with $k$, $k + 1$ and $k + 3$, then $k + 2 = m^n$, and $k(k + 1)(k + 3) = l^n$, or $(m^n - 2)(m^n - 1)(m^n + 1) = l^n$, that is, $l^n = m^{3n} - 2m^{2n} - m^n - 2 = l^n$, whence $l < m^3 + 1$. So there must be $m^3 < l < m^3 + 1$, which is impossible for the naturals $m$ and $n$. Thus, $l < m^3$.

Let us now compare $l$ and $m^3 - 1$. To do this, we note the following. Since $m^3 > 4$, we have $m^{3n-3} > 4m^{3n-6}$; and $3n - 6 \ge n$ since $n \ge 3$. Hence $m^{3n-3} > 3m^{3n-6} + m^n$. Let us now estimate the difference between $(m^3)^n$ and $(m^3 - 1)^n: (m^3)^n - (m^3 - 1)^n = m^{3n-3} + m^{3n-6} (m^3 - 1) + m^{3n-9} (m^6 - 2m^3 + 1) + \dots + (m^3 - 1)^{n-1} > 3m^{3n-3} - 3m^{3n-6} > 2m^{3n-3} + m^n > 2m^{2n} + m^n - 2 = (m^3)^n - l^n$.

Hence $(m^3 - 1)^n < l^n$, that is, $m^3 - 1 < l < m^3$, cannot be, since $m$ and $l$ are natural.

The resulting contradiction proves our assumption: the product of four consecutive natural numbers cannot equal the power of a natural number.

D. Fleishan

M368. Prove that the intersection of three right circular cylinders of radius 1, whose descriptions are mutually perpendicular in pairs (but not necessarily intersections), is contained in a certain ball of radius $\sqrt{3}/2$

The spatial function discussed in the assignment, the intersection of three cylinders, is quite difficult to imagine. But this is not necessary: ​​the solution problem is very simple, if you translate it into the language of algebra - use the coordinate method.

Let's choose a coordinate system as follows: construct a straight parallelepidel, three edges of which go along the axes of the cylinders (to do this, you need to draw two planes through the axis of each cylinder, parallel to the axes of the other two cylinders); Let's place the origin of coordinates in the center of this parallelepidel, and direct the axes parallel to its edges (Fig. 2). Then if the point $(x, y, z)$ belongs to the interior of the cylinders, the inequalities hold for it

$$(x - a)^2 + (y + b)^2 \leq 1, (y - b)^2 + (z + c)^2 \leq 1, (z - c)^2 + (x + a)^2 \leq 1$$

(2a, 2b and 2c are the lengths of the edges of the constructed parallelepidel). Adding these inequalities, for the interior points $(x, y, z)$ of intersection of the cylinders we obtain

$$(x^2 + y^2 + z^2) + (a^2 + b^2 + c^2) \leq 3/2,$$

that is, $x^2 + y^2 + z^2 \leq 3/2$, which is what needed to be proven.

Fig. 2.

N. Vasiliev

⟦folio 36⟧

M369. Given an acute triangle ABC. O is the point of intersection of its altitudes, $\omega$ is a circle with center O lying inside this triangle. Construct triangle $A_1B_1C_1$ circumscribed about circle $\omega$ and inscribed in triangle ABC (so that $A_1 \in [BC]$, $B_1 \in [AC]$, $C_1 \in [AB]$).

Fig. 3.

Fig. 4.

M370. Let $a, b, c$ be a triple of positive numbers. Let's form a new track from them:
$$|a - b|, |b - c|, |c - a|,$$

Let us introduce the following notation: $\widehat{ABO} = \widehat{ACO} = \alpha = 90^\circ - \widehat{A}$;
$\widehat{BAO} = \widehat{BCO} = \beta = 90^\circ - \widehat{B}$, $\widehat{CAO} = \widehat{CBO} = \gamma = 90^\circ - \widehat{C}$. Let us assume that the point $B_1$ is such that the angle between the tangent $B_1C_1$ drawn from it to the circle $\omega$ and the straight line $B_1O$ is equal to $\beta$ (Fig. 3). Let's draw a tangent to $\omega$ from point $C_1 - [C_1A_1]$. Let us show that then $B_1A_1$ is also a tangent, that is, that $C_1\widehat{B_1A_1} = 2\beta$. Consider the quadrilateral $AC_1OB_1$. A circle can be drawn around it since $C_1AO = C_1B_1O = \beta$. From the fact that the quadrilateral $AC_1OB_1$ is inscribed, it follows that the angles $OAB_1$ and $OC_1B_1$ are equal, namely: $OAB_1 = OC_1B_1 = \gamma$. Hence $B_1\widehat{C_1A_1} = 2\gamma$. Similarly, it is proved that a circle can be described around the quadrilateral $C_1BA_1O$: $OC_1A_1 = OBA_1 = \gamma$. This in turn implies the equality of the angles $C_1BO$ and $C_1A_1O$: $C_1\widehat{BO} = C_1\widehat{A_1O} = \alpha$.

Let us now consider the quadrilateral $B_1OA_1C$. Let us prove that a circle can be described around it. Indeed, $B_1\widehat{OA_1} = 2\pi - (B_1OC_1 + C_1OA_1) = \alpha + \beta + 2\gamma$, so $B_1\widehat{OA_1} + \widehat{C_1} = 2(\alpha + \beta + \gamma) = \pi$. Therefore, angles $OB_1A_1$ and $OC_1A_1$ are equal as inscribed and subtended by the same chord $OA_1$: $OB_1A_1 = OCA_1 = \beta$, so $C_1\widehat{B_1A_1} = 2\beta$. Similarly, it is proved that $C_1\widehat{A_1B_1} = 2\alpha$, that is, $B_1A_1$ is indeed a tangent (and the triangle $A_1B_1C_1$ is the desired one).

All that remains is to construct a point $B_1$ from which the circle $\omega$ would be visible at an angle $2\beta$. Let's assume that the tangent $B_1C_1$ already exists. Let's draw the radius of the circle $\omega$ to the point of contact. If the radius is $r$, then the length of the segment $B_1O$ is $r/\sin \beta$. Consequently, we can obtain the points $B_1$ as a result of the intersection of the sides $AC$ of the triangle $ABC$ with the circle $C$ centers at the point $O$ of radius $r/\sin \beta$.

Which point $B_1$ of the intersection of this circle with $[AC]$ (there can be two, one or none such points) corresponds to the desired triangle $A_1B_1C_1$:

So, we have figured out how to construct a triangle $A_1B_1C_1$ whose angles $A_1, B_1, C_1$ are respectively $2\alpha, 2\beta$ and $2\gamma$. It turns out that our problem has no other solutions. In fact, we will show that from the vertex $B_1$ of the desired triangle $A_1B_1C_1$ the circle $\omega$ is visible at an angle $2\beta$.

Let $B' \in [AC]$, and let, for example, $C'B'O < \beta$ ($C'B'$ is tangent to $\omega$). Draw a circle through points $A, C'$ and $O$ (Fig. 4); then point $B'$ lies outside this circle and $B'C'O < \gamma$ (make sure this is true). If $A' \in [BC]$ and $C'A'$ are tangent to $\omega$, then $B'C'A' < 2\gamma$. Likewise, $C'A'B' < 2\alpha$, so the sum of the angles in the supposed existing triangle $A'B'C'$ (with vertex $B'$ not the same as $B_1$) is less than $2\alpha + 2\beta + 2\gamma = \pi$ - a contradiction. The case when $C'B'O > \beta$ is dealt with similarly.

D. Izaak

a) Let us prove that in this case the number 0 will definitely appear in the sequence of tracks. Let us denote the maximum number in the first triple $(a, b, c)$ by $m$. It is clear that the maximum number in each subsequent triple is at least

⟦folio 37⟧

then from this triple, according to the same rules, the next one, etc. Is the average of the numbers obtained in this way necessarily 0 if the original numbers are a) integers; b) valid?

F373. Two large balls, one of which will initially rest, experience a more elastic “oblique” collision. The line passing through the centers of the balls during a collision makes an angle of 60° with the direction of the initial movement of the impacting ball. During the collision, the ball is deformed, and part of the kinetic energy of the impacting ball turns into the potential energy of elastic deformation of the balls, which, when the balls come apart, again turns into kinetic energy. Determine the maximum part of the energy of the balls that transforms into the energy of elastic deformation during the impact. The balls are considered absolute heads.

Fig. 5.

1 is smaller than in the previous one, so the maximum number in the second triple is no more than m - 1, in the third - no more than m - 2, and so on. This cannot continue for long: no later than in the mth triple the maximum number is zero.

6) Let us give an example showing that 0 may not occur in any of the triples. Let's start with the triple ($\lambda, \lambda^2, \lambda^3$), where $\lambda$ is chosen so that the numbers in the next triple

$$|\lambda^2 - \lambda|, |\lambda^3 - \lambda^2|, |\lambda^3 - \lambda|$$

proportional to the number of the first three. Since $\lambda^2 - \lambda = \lambda(\lambda - 1), \lambda^3 - \lambda^2 = \lambda^2(\lambda - 1), \lambda^3 - \lambda = (\lambda^2 + \lambda)(\lambda - 1)$, for this we take $\lambda$ equal to the positive root of the equation $\lambda^2 + \lambda = \lambda^3$: that is, $\lambda = (1 + \sqrt{5})/2$. In this case, the $n$-th triple will be like this: $\lambda(\lambda - 1)^{n-1}, \lambda^2(\lambda - 1)^{n-1}, \lambda^3(\lambda - 1)^{n-1}$ (this is easy to check using induction), so none of the numbers will be equal to 0.

An interesting, but more difficult question: what other triples of numbers ($a, b, c$) have the property that the sequence arising from them will not contain zeros? Try to figure it out. No less interesting is a similar problem about transformations of four numbers

$$(a, b, c, d) \rightarrow (|a - b|, |b - c|, |c - d|, |d - a|).$$

N. Vasiliev

Let us denote by $v_0$ the initial velocity of the first (impacted) ball, and by $v_1$ and $v_2$ the velocities of the first and second balls at the moment of their maximum deformation. According to the law of conservation of energy

$$\frac{mv_0^2}{2} = \frac{mv_1^2}{2} + \frac{mv_2^2}{2} + \Pi,$$

where $m$ is the mass of each ball, $\Pi$ is the maximum value of the potential energy of elastic deformation of the balls.

Let us introduce the coordinate system $XOY$ and find the projections of the velocities $v_1$ and $v_2$ onto the corresponding coordinate axes. We will direct the $OX$ axis along the line connecting the centers of the balls when moving away (Fig. 5). In this direction, a general LOB elastic impact will occur between the balls. Since the system of balls is isolated, the projection of the system's momentum onto the $OX$ axis is preserved. At the initial moment this projection is equal to $mv_0 \cos \alpha$. At the moment when the deformation of the balls is maximum, the projection of their velocities onto the $OX$ axis are the same: $v_{1x} = v_{2x} = v_x$.

From the law of conservation of momentum

$$mv_0 \cos \alpha = 2mv_x,$$

or

$$v_{1x} = v_{2x} = v_x = \frac{1}{2} v_0 \cos \alpha.$$

Since the balls are absolutely smooth, their interaction along the $OY$ axis does not occur. The projection of the speed of the first ball onto this axis does not change:

$$v_{1y} = v_{0y} = v_0 \sin \alpha,$$

and the projection of the speed of the second ball remains equal to zero:

$$v_{2y} = 0.$$

Thus, the law of conservation of energy can be written as follows:

$$\frac{mv_0^2}{2} = \frac{m(v_1^2 + v_2^2)}{2} + \frac{m(v_2^2 + v_1^2)}{2} + \Pi,$$

or

$$\frac{mv_0^2}{2} = \frac{mv_0^2 \cos^2 \alpha}{4} + \frac{mv_0^2 \sin^2 \alpha}{2} + \Pi.$$

⟦folio 38⟧

F374. At the bottom of a glass of water there are several capillary tubes sealed with one end and filled with air. The diameter of the tubes is $d=0,2$ mm, the height of the water level in the glass is $h=10$ cm. When water boils, steam bubbles form at the open ends of the tubes. What is the temperature of the water at the bottom of the glass if the atmospheric pressure is $10^5$ n/m$^2$? The coefficient of surface tension of water is assumed to be 57 dynes/cm. Consider that the saturated vapor pressure of water greater than 100°C increases by 27 mm pt. Art. when the temperature rises by 1°.

From here we find the fraction of the kinetic energy of the incident ball that has been converted into the potential energy of elastic deformation:

$$\frac{\Pi}{mv_0^2/2} = \frac{\cos^2\alpha}{2} = \frac{1}{8}.$$

◆ A vapor bubble breaks away from the tube at the moment when the saturated vapor pressure $p_H$ inside the bubble is equal to the external pressure $p$ on the bubble. This external pressure consists of atmospheric pressure $p_0$, hydrostatic pressure $\rho g$ and additional pressure $2\sigma/r$ caused by the surface tension of the liquid. Here $p_0 = 10^5$ n/m$^2$, $\rho = 10^3$ ke/m$^3$ is the density of water, $\sigma = 57$ dyne/cm is the coefficient of surface tension of water and $r$ is the radius of curvature of the liquid surface at the tube. At the moment of bubble separation, $r$ is equal to the radius of the tube, that is, $r = d/2$.

Thus,

$$p_H = p_0 + \rho g h + 4\sigma/d.$$

The pressure $p_H$ differs from the saturated vapor pressure at 100°C, equal to $p_0$, by $\Delta p = p_H - p_0 = \rho g h + 4\sigma/d \approx 16$ mm rm. cm.

Therefore, the temperature $t$ of water at the bottom of the glass

$$t = 100^\circ C + \frac{16}{27} \cdot 1^\circ C \approx 100,6^\circ C.$$

I. Slobodetsky

◆ It is clear that the second block will begin to move at the moment when the elastic force of the spring $F_{yпр}$ in absolute value becomes equal to the maximum value of the static friction force $\mu m_2 g$ (Fig. 6). Distance between the feather block and find out how the elastic force of the spring changes when it moves. This block begins to move if $F > \mu m_1 g$. When the block moves, in addition to the force $F$ and the friction force $\mu m_1 g$, there is also an elastic force acting on it (see Fig. 6), which increases in absolute value as the block moves away from the initial position. Therefore, the acceleration of the block will decrease, and at the moment when $F - \mu m_1 g - F_{yпр} = 0$, it becomes zero. Then the acceleration will change sign and will be directed against the speed of the block. The speed of the block begins to decrease, at some point it will go to zero, then the block will move to the left (if, of course, the second block leaves).

It is obvious that the deformation of the spring, and therefore the elastic force, is maximum when the speed of the block is zero. And if at this moment the elastic force is equal (more precisely, slightly greater) to the maximum static friction force between the second block and the surface:

$$F_{yпр.max} = \mu m_2 g,$$

 the second block will begin to move. Let's find $F_{yпр.max}$.

Fig. 6.

⟦folio 39⟧

Since the kinetic energy of the bars at the moment under consideration is zero, the work of the forces $F$ and $\mu m_1 g$ during the entire time of movement of the first bar to the right will be equal to the change in the potential energy of the bait:

$$\frac{kx_{\text{max}}^2}{2} = (F - \mu m_1 g) x_{\text{max}}.$$

Here $k$ is the rigidity of the graft, $x_{\text{max}}$ is the maximum elongation of the graft. From here

$$F_{\text{упр.max}} = kx_{\text{max}} = 2(F - \mu m_1 g).$$

Therefore, the second block will move if

$$2(F - \mu m_1 g) = \mu m_2 g,$$

or

$$F = \mu g(m_1 + m_2/2).$$

G. Komkin

F376. An hourglass of diameter $d$ is left in a glass tube of diameter $D(D \approx d)$, sealed and filled with water. At the initial moment, the clock is at the bottom of the tube. When you turn the tube over, the watch will remain at the top of the tube for a while, then slowly lower down. Find the time during which the clock is at the top of the tube if the height of the clock is $h(h \gg d)$, its mass is $M$, the mass of sand in the clock is $m$ and the coefficient of friction of the clock on the walls of the tube is $k$. The time of transformation of the sand from the upper to the lower edge of the clock is $t$.

When turning the clock over, its center of gravity - point $C$ on figure 7 - is located above point $O$, at which the pushing out Archimedean force is applied, and the clock turns out to be “twisted”. In this case, reaction forces $N_1$ and $N_2$ and friction forces $F_{\text{тр}_1}$ and $F_{\text{тр}_2}$ act on the clock from the walls of the tube. As the sand wakes up, the forces $N_1$ and $N_2$ decrease in absolute value. The moment the clock starts to slide down,

$$F_{\text{тр}_1} = kN_1 \text{ и } F_{\text{тр}_2} = kN_2.$$

Since the clock does not move in the horizontal direction, then $N_1 = N_2 = N$. Hence,

$$F_{\text{тр}_1} = F_{\text{тр}_2} = kN.$$

Let us denote by $t$ the time from the moment the tube is turned over until the moment when the clock begins to slide relative to the tube. During this time, $x = \frac{t}{\tau}$ part of the sand woke up. Let us find the position of the center of gravity of the clock at time $t$. At the same time, taking into account that at the bottom there is the $x$th part of the sand, and at the top there is the $(1-x)$th part. If the height of the sand is $l$, then at the bottom there is a column of sand with a height of $xl$ with a mass of $xm$, and at the top there is a column of height $(1-x)l$ with a mass of $(1-x)m$. For simplicity, we will consider these columns to be cylindrical. Then, using the general rules, it is not difficult to find the position of the center of gravity of the watch:

$$OC = \frac{m}{2(M+m)}(2x^2l - hx + l - 2xl).$$

Assuming that $l = h/4$ (as shown in figure 7), we obtain

$$OC = \frac{mh}{8(M+m)}(2x^2 - 6x + 1).$$

Now let's write down the equilibrium conditions for the clock. Firstly, it is clear that $F_{\text{тр}_1} + F_{\text{тр}_2} + F_B = (M+m)g$, whence

$$F_{\text{тр}_1} = F_{\text{тр}_2} = \frac{1}{2}[(M+m)g - F_B] = \frac{g}{2}(M+m - \rho V),$$

And

$$N = \frac{g}{2k}(M+m - \rho V),$$

where $\rho$ is the density of water and $V$ is the volume of the clock.

⟦folio 40⟧

Also, $N_1 \cdot OA \cdot \cos(\alpha + \beta) + N_2 \cdot OB \cdot \cos(\alpha + \beta) + F_{\text{Tp}_1} \times OA \cdot \sin(\alpha + \beta) = F_{\text{Tp}_2} \cdot OB \cdot \sin(\alpha + \beta) + (M + m)g \cdot OC \cdot \sin \alpha$.

Since $d \approx D$ and angle $\alpha$ are small, then

$$OA \cdot \cos(\alpha + \beta) = OA \cdot \cos \beta = h/2, \quad OA \cdot \sin(\alpha + \beta) = OB \cdot \sin(\alpha + \beta) \quad \text{и} \quad OC \cdot \sin \alpha = OC \cdot \mathrm{tg} \alpha = OC \cdot (D - d)/h.$$

As a result, from equality (3) we obtain

$$N = (M + m)g \frac{D - d}{h^2} OC.$$

Substituting here the expressions for $N$ (from equality (2)) and for $OC$ (equality (1)) and solving the resulting equation for $x$, we find

$$x = \frac{1}{2} \left(3 - \sqrt{7 + 2a}\right), \quad t = x\tau = \frac{\tau}{2} \left(3 - \sqrt{7 + 2a^2}\right),$$

where $a = \frac{4h (M + m - \rho V)}{mk (D - d)}$.

I. Slobodetsky

F377. If you look squinting at distant bright lamps, you usually see vertical or slanted columns of light coming down and up from the lamp. Explain this phenomenon. Create and carry out experiments to test your explanation.

Clue. The surface of the rose is not dry. It is always covered with a layer of tear fluid.

Fig. 8.

“Along the edges of the eyelid, the tear fluid forms a small meniscus in which light rays are refracted. As shown in figure 8, $a$, the rays are refracted from the upper eyelid so that they each go bluish, and the light source receives a “tail” formed downward. In a similar way, a light “tail” appears at the lower eyelid, directed upward. The appearance of these “tails” can be clearly observed if, having closed one eye, slowly close the other, or raise and lower your head, keeping both eyes half-closed. The rays appear at the very moment when the eyelid begins to close the pupil, which is easy for a myopic person to notice, since the light source, which appears to him as a blurry circle, is at this moment partially eclipsed.

The rays are not completely parallel, even when viewed with only one eye. Look straight at the light source, and then turn your head slightly to the right and roll your eyes so that this source is again. Now the rays are directed obliquely (Fig. 8, 6). The reason seems to be that the edges of the eyelids, where they cross the pupil, are no longer horizontal, and each ray of rays is located at right angles to the edge of the eyelids. The apparent directions of the rays are consistent with this explanation. Now you can understand why the rays are not parallel if you look straight ahead: the curvature of the eyelids affects even with a small pupil width (Fig. 8, 8). Close the right edge of the pupil with your finger, and the rays located on the left will disappear.”

From the book “Light and Color in Nature” by M. Minnarma

⟦folio 43⟧

Answer and commentary to question 1

a) Such a function, of course, exists - see Fig. 3, a and 3, b (at Fig. 3, b the graph of the polynomial $y = x^4 - x^2$ is shown - confirm this by studying using an arbitrary one).

b) It turns out that such a function exists! The corresponding graphs are shown in Figures 4, a and 4, b: between the minimum points $x_1$ and $x_2$ of these functions there is a “flat hill” - a section of the graph above the segment $[a_1, a_2]$ on which the function is built. Of course, I would like to consider this slide to consist entirely of maximum points. However, the point $x_0 \in [a_1, a_2]$ does not fit our definition of a maximum - a “strict” maximum ($f(x) < f(x_0)$ for points $x \neq x_0$ in the neighborhood of $(x_0)$. But they are points of a non-strict maximum: for points $x$ in some neighborhood of the point $x_0$ the non-strict inequality $f(x) \leqslant f(x_0)$ is satisfied. It is intuitively clear that between a continuous function must have a maximum point—between two troughs there must be at least one hill! This is true, but the maximum may not be strict.

The concept of a non-sharp extremum (maximum or minimum) is convenient, but somewhat “ambiguous”: the points of the integral $|a_1, a_2|$ in Figures 4, a and 4, b can rightfully be considered points of a non-sharp minimum! Another example: a function whose graph is shown in figure 5, but not

⟦folio 44⟧

has strict extrema, but point $x_1$ is a point of non-strict maximum for it, $x_2$ is a point of non-strict minimum, and all points $x_0$ of the construction interval $|x_1, x_2|$ are simultaneously points of non-strict maximum and non-strict minimum. Analyze functions $y = |x - 1| + |x + 1|$ and $y = |x - 1| - |x + 1|$ in a similar way (their graphs are shown in Fig. 5, 6 and 5, respectively - check!).

So, along with the school concepts of maximum and minimum, the concepts of non-strict maximum and minimum are also accepted in mathematics - more general, “somewhat ambiguous” (see above), but sometimes convenient when formulating theorems. As an example, we give the following statements:

If the function $f$ is defined and non-discontinuous on the segment $[a, b]$, and we take the same values ​​at its ends, that is, $f(a) = f(b)$, then there exists a point $x_1 \in ]a, b[$,

Fig. 5.

Fig. 6.

in which the function $f$ has a maximum or minimum (possible, despite).

Figure 6 ($a, b, \theta$) illustrates this theorem, and the maxima and minima indicated on figure are strict.

Question 3. Is the stated statement true if the maximums and minimums are considered strict in milk?

In mathematical analysis textbooks for students studying maxima and minima, it is customary to understand them in a non-strict sense - for the reason stated above. In high school, you mostly have to deal with functions that have only strict maxima and maxima. This class of functions, in particular, includes polynomials and fractional rational functions. Note, for example, that the graph of figure 4, 6 cannot be the graph of a lower polynomial (unlike the graph of figure 3, 6) - try to prove this!

Answer to question 2

a) Such functions exist - for example, “saw” on figure 7, $a$, or

⟦folio 45⟧

sinusoid - graph $y = \sin x$ (Fig. 7, 6).

6) It turns out that such functions also exist. Extremum points can be “condensed” so that there are an infinite number of them on the segment $|0, 1|$. For example, on figure 8, $a$ at points $x_n = 1/n$ with even $n$ - minima, with odd - maxima. However, graph 8, $a$ does not determine the value of the function at $x = 0$. You can take $f(0) = 0$ or $f(0) = c$, but such a function will not be continuous at the point $x = 0$: the value of $f(x)$ does not tend to $f(0)$ at $x \rightarrow 0$. To obtain a continuous function, we can make the function values ​​at the extremum points $x_n$ tend to zero at $n \rightarrow \infty$, as in figure 8, 6. If we then continue

Fig. 7.

Fig. 8.

live graph, as shown in this figure, then we get an everywhere defined and continuous function that has an infinite number of extrema on the segment $|0, 1|$ - the answer to question 2, B).

Graphs similar to those shown in Figures 8, $a$ and 8, 6, of course, can be set using formulas: check, for example, what graphs of a function are

$$y = \sin \frac{1}{x} \left( \text{при } 0 < x \leq \frac{2}{\pi} \right),$$

$$y = \begin{cases} x \sin \frac{1}{x} & \text{при } x \neq 0, \\ 0 & \text{при } x = 0. \end{cases}$$

You should not think that the functions discussed in question 2 are some kind of “exceptions”. One encounters similar functions when studying various processes in physics.

In conclusion, we will ask you one more question. Obviously, if the function $x \rightarrow f(x)$ returns the trace from the point $x_0$, that is, in some intervals $|x_0 - \delta, x_0|$, and decreases to the right of this point - in the interval $|x_0, x_0 + \delta|$, then $x_0$ is the maximum point of the function $f$ (explain!).

Question 4. Is the converse true: if a continuous function $f$ has a maximum at the point $x = x_0$, then it returns the trace from the point $x_0$, and the trace from $x_0$ decreases?
