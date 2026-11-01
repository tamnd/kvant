---
id: 1981-10-resheniya-zadach-m666-m670-f678-f682-979a3e11
issue: kvant_1981_10
year: 1981
number: "10"
title: Solutions to problems M666—M670; F678—F682
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 41
page_labels: 34-39
tag: 7DG3
lang: en
source: kvant_digital
extraction: vision
content_sha256: d064cc5a4f61fd292988626ff8f9271f0d95bc74fc50f77e315e52b58d1701c0
prompt_sha256: draft-1
translated_from: content/ru/1981/10/articles/12_resheniya-zadach-m666-m670-f678-f682-979a3e11.md
source_content_sha256: 3066c9d59770feab5bb06b1bd81b11d68548abfc256cae363d3b5f343902bbfe
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

Problem solutions

M666. Prove that the least common multiple of $a_1 < a_2 < ... < a_n$ is $A$. Then, obviously, $\frac{A}{a_1} > \frac{A}{a_2} > ... > \frac{A}{a_n}$ are natural numbers. Therefore $\frac{A}{a_1} \geq n$, hence $A \geq n a_1$.

This estimate is accurate. Indeed, if $a_1 = \frac{n!}{n-1}$, $a_2 = \frac{n!}{n-1}$, ..., $a_n = n!$, then $A = n! = n \cdot a_1$.

A. Razborov

M667. Construct triangle ABC if its smallest angle $\hat{A}$ and segments of length $d = |AB| - |BC|$ and $e = |AC| - |BC|$ are given.

On the sides of this angle $\hat{A}$ we turn off the given segments AD of length $d$ and AE of length $e$. Telery needs to find also points B and C on these sides (behind points D and E), which is $|BD| = |BC| = |CE|$.

To do this, we first construct a figure that is ready for the required quadrilateral BCED. To do this (Fig. 1), let us plot on the line AD (on a ray not containing A) a segment DB1 of any length $q$, then in parallel we intersect the ray [DE] with a vector $\vec{q}$ of the same length $q$, directed parallel to [AE], after which on the resulting ray $l$ we mark a point $C_1$, for which $|B_1C_1| = q$. Obviously, the quadrilateral $B_1C_1E_1D$ is similar to the required quadrilateral BCED. Now drawing a line parallel to $B_1E_1$ through point E, we find point B; then drawing a line parallel to $B_1C_1$ through point B, we find point C. (It is easy to see that all constructions are always fulfilled, and in a unique way.)

Here is another solution - one that does not use the similarity method. If $O$ is the center of the circle inscribed in the desired triangle ABC, then the triangles BOD, BOC and COE are constructive (Fig. 2). All angles offset at vertex O are equal to $90^\circ + \hat{A}/2$. Therefore $D\hat{OE} = 90^\circ - 3\hat{A}/2$ (this quantity is positive at $\hat{A} < 60^\circ$). Telery, we can construct the point O as the intersection of the bisector of the angle A and the soul of the segment with ends D, E, combined with an inscribed angle of magnitude $90^\circ - 3\hat{A}/2$ (red arc at figure 2). Then, drawing rays OB and OC at the required angles to segments DO and EO, we find the two vertices of triangle ABC.

Finally, the problem can be solved and calculated: the length of the desired segment $x = |BD| = |BC| = |CE|$ is found from the quadratic equation

$$x^2 = (x+d)^2 + (x+e)^2 - 2(x+d)(x+e) \cos \hat{A},$$

after which the required segment can be constructed (based on $d, e$ and $\hat{A}$) with a compass and a ruler, combining known construction methods using given segments of length $p$ and $q$ and angle $\alpha$ of segments of length $p$ cos $\alpha$, $p \pm q$, $\sqrt{pq}$, $\sqrt{p^2 \pm q^2}$. Interestingly, the negative root of this equation also has a geometric meaning: it determines the position of another point $B_2 \in [DA)$, $C_2 \in [EA)$, for which $|B_2D| = |B_2C_2| = |C_2E|$.

N. Vasiliev

M668. The sequence $(x_i)$ is determined by the conditions $x_1 = 1$, $x_2 = 0$, $x_3 = 2$, $x_{n+1} = x_{n-2} + 2x_{n-1}$. Prove that for any

Let $m$ be any natural number. Instead of the sequence $(x_i)$, consider the sequence $(\bar{x}_i)$ of remainders from the division of $x_i$ by $m$.

From the definition of the sequence $(x_i)$ it follows that for any numbers $\bar{x}_i$, $\bar{x}_{i+1}$ and $\bar{x}_{i+2}$ one can uniquely

⟦folio 35⟧

natural number $m$ there are two adjacent terms of this sequence, each of which is divisible by $m$.

Indeed, since the number of terms of the sequence is infinite, and the number of tracks from the set of numbers {0, 1, 2, ..., $m-1$} is no more than $m^3$, it will find two matching tracks $\bar{x}_i, \bar{x}_{i+1}, \bar{x}_{i+2}$ and $\bar{x}_{i+T}, \bar{x}_{i+T+1}, \bar{x}_{i+T+2}$. But since the numbers of the first triple are uniquely determined by the numbers of the second triple, then in general for any $k$ the equalities $\bar{x}_{k+T}=\bar{x}_k, \bar{x}_{k+T+1}=\bar{x}_{k+1}, \bar{x}_{k+T+2}=\bar{x}_{k+2}$ ($T$ is the period of the sequence) will be true.

Since $\bar{x}_0=\overline{x}_3-2x_1=0, \bar{x}_{-1}=\overline{x}_2-2x_0=0, \bar{x}_{iT-1}=0$ and $\bar{x}_{iT}=0$ for any $l$. We have thereby proven that there are infinitely many pairs of adjacent terms of the sequence ($x_i$), each of which is divisible by $m$.

It is interesting to note the connection between the sequence ($x_j$) and the Fibonacci sequence ($f_i$): $f_1=1, f_2=2, ..., f_{n+2}=f_{n+1}+f_n$ at $n \geqslant 1$. The Fibonacci sequence can also be continued higher: $f_{n-1}=f_{n+1}-f_n$, so $f_0=1, f_{-1}=0$, etc. It is easy to check that $x_i=f_{i-2}+(-1)^{i-1}$. Thus, for any natural number $m$ in the sequence ($f_i+(-1)^{i-1}$), there are infinitely many pairs of adjacent terms that divide by $m$. At the same time, any two adjacent Fibonacci numbers are relatively prime*.

G. Kozlov

**M669. Quadrilateral ABCD is inscribed in a circle. Prove that a) the segment connecting two terms AB and CD is perpendicular to the segment connecting two terms BC and AD; b) the centers of the circles inscribed in triangles ABC, BCD, CDA and DAB are the vertices of the straight line.**

a) Since $NMP=\frac{1}{4}(BC+CD)=\frac{1}{2}\hat{A}, MNQ=\frac{1}{4}(AB+AD)=\frac{1}{2}\hat{C}$ (Fig. 1), $NMP+MNQ=\frac{1}{2}(\hat{A}+\hat{C})=90^\circ$, the inscription of the corresponding triangle ABC, BCD, CDA and DAB (Fig. 2) is revealed.

The triangles BMN and MO$_1N$ are congruent, so $|BN|=|NO_1|$. Likewise, $|CN|=|NO_2|$. But $|BN|=|CN|$; therefore, the triangle $O_1NO_2$ is equilateral, in which $[NQ]$ is a bissertrix. Therefore $[NQ] \perp [O_1O_2]$; means $[O_1O_2] \parallel [MP]$.

**Fig. 1.**

**Fig. 2.**

Similarly, it is proved that $[O_3O_4] \parallel [MP]$ and $[O_1O_4] \parallel [NQ] \parallel [O_2O_3]$. Thus, the quadrilateral $O_1O_2O_3O_4$ is a rectangle.

I. German, K. Malkhasyan

* (For interesting properties of the divisibility of Fibonacci numbers, see N. N. Vorobyov’s book “Fibonacci Numbers” (Series “Popular lectures in mathematics”, M., “Nauka”, 1978).

⟦folio 36⟧

M670. a) Several points are given, some pairs of which are connected by lines (the points of such pairs are called connected by them). The number of connections at each point is odd. At the initial moment, all points are colored in two colors - red and blue. Then, every minute, the points are recolored according to the following rule: each point in which the majority of connections has a different color from it changes its color; otherwise its color is preserved. Prove that there will come a moment from which some points will not change color, but some will change every minute. b) Will this statement remain true if it is not assumed that each point has an odd number of connections?

Fig. 1.

Fig. 2.

Let us call the segment $X'_i X''_j$ connecting the points of the double system a variegated edge if its ends $X'_i$ and $X''_j$ are of different colors. Let us show that if at the next moment at least one point has a variegated edge, then the number of the variegated edge of the military system will take the form... $P_{t-1}, P_t, P_{t-1}, P_t, \dots$, (Fig. 3), and this is exactly what needs to be proven in the task.

Fig. 3.

Let us call the segment $X'_i X''_j$ connecting the points of the double system a variegated edge if its ends $X'_i$ and $X''_j$ are of different colors. Let us show that if at the next moment at least one point has a variegated edge, then the number of the variegated edge of the system will take the form... $P_{t-1}, P_t, P_{t-1}, P_t, \dots$, (Fig. 3), and this is exactly what needs to be proven in the task.

⟦folio 37⟧

F678. An artillery gun fires from under cover inclined at an angle α to the horizontal (Fig. 1). The gun is located at point A at a distance l from the base of the shelter (point B). The initial velocity of the projectile is $|\vec{v}_0|$.
Assuming that the projectile trajectory lies in the figure plane, determine the maximum flight range.

Fig. 1.

Of all the possible trajectories of the projectile, we choose the one that touches the shelter. Let us consider the motion of a projectile in a coordinate system whose axes are directed as shown in figure 2. In this system, the “horizontal” (along the OX axis) projection of the initial velocity of the projectile is equal to $v_{0x} = v_0$ cos ($\varphi - \alpha$), and the “vertical” (along the OY axis) projection is equal to $v_{0y} = v_0 \sin (\varphi - \alpha)$, where $\varphi$ is the angle that makes with the horizon, the vector of the initial velocity of the projectile.

Point C, at which the trajectory of the projectile touches the shelter, determines the maximum height $h'$ of raising the projectile above the “horizon”, equal, as can be seen from figure 2, $l \sin \alpha$. At this point, the projection of the full speed $\vec{v}$ of the projectile onto the axis

Fig. 2.

$OY$ is zero and
$$h' = v_{0y}^2 / 2g'$$,
where $g' = g \cos \alpha$ is the “gravitational acceleration” in the system $XOY$ (projection of the vector $\vec{g}$ onto the “vertical” $OY$). Thus, $v_{0y}^2 = 2g' h' \Rightarrow v_0^2 \sin^2 (\varphi - \alpha) = 2(g \cos \alpha) (l \sin \alpha)$.

From here, in particular, it follows that if, according to the conditions of the problem, $2g l \sin \alpha \cdot \cos \alpha = g l \sin 2\alpha > v_0^2$, then none of the projectile trajectories will touch the shelter and the maximum flight range $L_{\max}$ will be for a projectile launched at an angle $\varphi = \pi/4$ to the horizon; at the same time $L_{\max} = v_0^2/g$.

If, according to the conditions above, the correspondence $v_0^2 \geqslant g l \sin 2\alpha$ is met, then in order for the trajectory to touch the cover, the projectile must be launched at an angle
$$\varphi_{\kappa c} = \alpha + \arcsin \frac{\sqrt{g l \sin 2\alpha}}{v_0}$$.

If, according to the conditions above, the inequality
$$\frac{v_0^2}{v_0^2 + 2g l} \leqslant \sin 2\alpha$$,
which in turn means that $\varphi_{\kappa c} \geqslant \pi/4$ (show me!), then the angle of departure of the projectile with maximum flight range $\varphi_{\beta} = \pi/4$ and $L_{\max} = v_0^2/g$. If, according to the conditions above, the inverse inequality
$$\frac{v_0^2}{v_0^2 + 2g l} > \sin 2\alpha$$,
which in turn means that $\varphi_{\kappa c} < \pi/4$, then

⟦folio 38⟧

$$L_{\max} = \frac{v_0^2}{g} \sin 2\varphi_b = \frac{v_0^2}{g} \sin 2 \left( \alpha + \arcsin \frac{\sqrt{g l} \sin 2\alpha}{v_0} \right).$$

S. Krotov

F679. An inextensible zeroch rope of linear density q and length L is thrown over the block so that the length of one zone of the hanging ends is equal to $l(l < L/2)$. The block found on the horizontal axis is a thin hoop of mass m and radius r on light knitting needles (see figure). The system is kept at rest and then released. Find the force of pressure on the axis at the first moment of time. There is little trammel between the axle and the block.

Three forces act on the block+rope system: the reaction force $\vec{R}$ in the axis of the block and the weight forces $m\vec{g}$ and $M\vec{g}$ ($M = \rho L$ is the mass of the rope). According to Newton's third law, the force $\vec{N}$ of pressure on the block axis is equal in absolute value to $|\vec{R}|$.

Let us write the equation of motion of the center of mass of the system in projections on the axes $OX$ and $OY$ (see figure):

$$\begin{align*}
(M + m)g &= R_x = (M + m)A_x, \\
R_y &= (M + m)A_y
\end{align*}$$

($A_x$ and $A_y$ are projections of the acceleration of the center of mass). Since the rope is inextensible and does not slip over the block, the accelerations of all points of the rope and the block at the first moment of time will be equal in absolute value (the initial speed of the system is zero, and the points of the rope lying on the hoop have not yet acquired the centripetal component of acceleration).

The acceleration $\vec{A}$ of the center of mass of the system is related to the acceleration $\vec{a}_i$ of all its $i$ points by the relations

$$M\vec{A} = \sum_i m_i \vec{a}_i,$$

where $M$ is the mass of the system, $m_i$ is the mass of its $i$ point. Let us write this relationship for our system in projections on the $OX$ and $OY$ axes.

In projection on the $OX$ axis

$$-M_{AC}a + M_{BD}a = (M + m)A_x,$$

since the total contribution of all products $M_{i(AB)}\vec{a}_i$ (from the rope points lying on the section $AB$) and $m_i\vec{a}_i$ (from the hoop points) in projections onto the $OX$ axis is equal to zero; this is clear from Symmetrine's messages. In the projection onto the $OY$ axis, only the product $M_{i(AB)}\vec{a}_i$ contributes. To find the projection onto the axis $OY$ of the vector $\sum_i M_{i(AB)}\vec{a}_i$, we must sum the vectors $M_{i(AB)}\vec{a}_i$, taking into account that at each point the acceleration is directed tangent to the hoop (recall that the initial velocity is zero). This summation (do it yourself) will lead us to the following result:

$$\frac{2}{\pi} M_{AB}a = (M + m)A_y.$$

Let us substitute the resulting expressions for $(M + m)A_x$ and $(M + m)A_y$ into (*) and find $R_x$ and $R_y$:

$$R_x = (M + m) \left( g - \frac{M_{BD} - M_{AC}}{M + m} a \right),$$

$$R_y = \frac{2}{\pi} M_{AB}a.$$

To determine the acceleration $a$, we write the equation of motion of individual parts of the system:

$$M_{BD}g - T_B = M_{BD}a,$$

$$T_A - M_{AC}g = M_{AC}a,$$

$$T_B - T_A = (M_{AB} + m)a,$$

where $\vec{T}_A$ and $\vec{T}_B$ are the tension forces of the rope at points $A$ and $B$ (see figure). (To obtain the last equation, consider the movements of individual parts of the rope in section $AB$ and the hoop.) From these equations one finds:

$$a = \frac{M_{BD} - M_{AC}}{M + m} g.$$

Thus,

$$R_x = (M + m) \left( g - \frac{(M_{BD} - M_{AC})^2}{(M + m)^2} g \right),$$

⟦folio 39⟧

$$R_y = \frac{2}{\pi} M_{AB} \frac{M_{BD} - M_{AC}}{M + m} g.$$

Consequently, the projections of the force $\vec{N}$ pressure on the axis at the first moment of time are equal

$$-N_x = (\varrho L + m) \left( 1 - \frac{(L - \pi r - 2l)^2 \varrho^2}{(L \varrho + m)^2} \right) g,$$

$$-N_y = 2r \varrho \frac{(L - \pi r - 2l) \varrho}{L \varrho + m} g.$$

M. Efroimsky

F680. A thin hoop of radius $R$ can be repaired by a round rod $A$, parallel to the axis of the hoop (see figure). The hoop is fitted with a small washer $B$ of mass $m$, which can move along the hoop without friction. The hoop together with the puck as a whole is deflected from the equilibrium position by an angle $\varphi_0$ and released. Determine the dependence of the interaction force between the puck and the hoop on the angle $\varphi$, formed by the radius vector OA with the vertical.

Let's consider the movement of two systems:

system I - a washer suspended on a thread of length $2R$ (mathematical matrix); washer mass $m$;

system II - a hoop of radius $R$ with a washer of mass $m$ attached to it at the lowest point.

Let us deviate the system from the equilibrium position by the same angle $\varphi_0$ and release it. Due to the law of conservation of energy, the systems will oscillate with equal amplitudes. Let us compare the speeds that the pucks will have (on the thread and on the hoop) at an angle of deviation from the vertical equal to $\varphi$.

From the law of conservation of energy for system I -

$$mg \cdot 2R(1 - \cos \varphi_0) = mg \cdot 2R(1 - \cos \varphi) + \frac{mv^2}{2},$$

for system II -

$$mg \cdot 2R(1 - \cos \varphi_0) + Mg(R + R(1 - \cos \varphi_0)) = mg \cdot 2R(1 - \cos \varphi) + Mg(R + R(1 - \cos \varphi)) + \frac{m(v')^2}{2} + 2\frac{M\left(\frac{v'}{2}\right)^2}{2}$$

(M is the mass of the hoop, $v'$ is the speed of the puck, $v'/2$ is the speed of the center of the hoop, $2M\left(\frac{v'}{2}\right)^2/2$ is the kinetic energy of the hoop) is found

$$v^2 = 4Rg(\cos \varphi - \cos \varphi_0),$$

$$(v')^2 = 4Rg(\cos \varphi - \cos \varphi_0).$$

We see that $v = v'$. Consequently, in the systems under consideration, the trajectories of movement of the pucks and the instantaneous velocities of the pucks coincide (from here, by the way, the synchronism of the oscillations of systems I and II follows). Thus, the instantaneous conditions of the washers are the same. Therefore, in absolute value, the instantaneous value of the interaction force between the hoop and the washer fixed on it will be exactly equal to the corresponding instantaneous value of the tension force of the thread $T(\varphi)$ of the mathematical matrix of length $2R$. Let's find $T(\varphi)$.

Let us write down the equation of motion of the puck on the thread:

$$T(\varphi) - mg \cos \varphi = \frac{mv^2}{2R}.$$

Substituting the resulting solution $v^2$, we find $T(\varphi)$:

$$T(\varphi) = mg(3 \cos \varphi - 2 \cos \varphi_0).$$

Thus, the force acting from the hoop on the puck attached to it is at any time directed towards the center of the hoop. And this means that if we take the system given in the task out of the equilibrium position, then with further movement the puck will always be covered with respect to the hoop, regardless of whether it is fixed on it or not. Therefore, the force of interaction between the puck and the hoop is equal to

$$N(\varphi) = mg(3 \cos \varphi - 2 \cos \varphi_0).$$

D. Belov
