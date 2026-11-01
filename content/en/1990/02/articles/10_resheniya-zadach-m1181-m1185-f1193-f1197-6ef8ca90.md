---
id: 1990-2-resheniya-zadach-m1181-m1185-f1193-f1197-6ef8ca90
issue: kvant_1990_2
year: 1990
number: "2"
title: Solutions to problems M1181—M1185; F1193—F1197
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 35
page_last: 42
page_labels: 33, 34, 36, 37, 38, 39, 40
lang: en
source: kvant_digital
extraction: vision
content_sha256: dae06189474e4328a95ce9bd76aff5fcd7fa8fe305fc6c8678d7ec26254240a7
prompt_sha256: draft-1
translated_from: content/ru/1990/02/articles/10_resheniya-zadach-m1181-m1185-f1193-f1197-6ef8ca90.md
source_content_sha256: 9a0834e7886b0d22ef6933e4e1ce28fa0740de91491c6cde74330f417c64ae5f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

---
running_head:
folio:
---

Problem solutions
M1181 — M1185, F1193 — F1197

Let's color the board fields as shown in figure. Since there is exactly one piece on each horizontal line, there are 4 pieces on the red and yellow fields. Likewise, there are also 4 pieces on the blue and yellow fields. Therefore, the figure on the red fields is the same as on the blue ones, and their total number is even. But the red and blue squares are the black squares of the original chess coloring.

B. Arbitrary

M1182. In some roses there were n≥3 starlings, and all distances between starlings varied. Each of them contains a yellow starling. At each moment, some of them left their starlings and flew to others, so that again there was a starling in each starling. Moreover, if the distance between each pair of starlings was less than the distance between the other pair (one starling can be counted in different pairs), then after the flight the distance between the first pair of starlings turned out to be greater than the distance between the second pair. Under what conditions is this possible?

Answer: with n=3.
Let us prove that any starling either remains in place or changes places with others.

Let the starling from the starling $A_1$ fly to $A_2$, from $A_2$ to $A_3$, etc. The number of starlings is finite, therefore in the sequence $A_1, A_2, A_3$, ... repetitions begin, and $A_1$ will be repeated first (if, say, $A_3$ appears again, then immediately before it there should be $A_2$, and before $A_2$—$A_1$, i.e. $A_1$ occurs again earlier). Let us assume that $A_i \neq A_1$ at $1 < i \leq k$, $A_{k+1} = A_1$ and that the smallest of the distances $A_1A_2, A_2A_3, ..., A_kA_1$ is, for example, $A_1A_2$. From the fact that $A_1A_2$ is less than all other distances $A_iA_{i+1}$, it follows by condition that $A_2A_3$ is greater than all other distances $A_iA_{i+1}$, and hence that $A_3A_4$ is less than all other distances $A_iA_{i+1}$, i.e. $A_3A_4 = A_1A_2$. But all distances $A_iA_j$ are different, therefore $A_3 = A_1$. In other words, if the starling has already left the starling $A_1$, then it changes places with the starling from $A_2$.

Fig. 1.
Fig. 2.

⟦folio 34⟧

---
running_head:
folio:
---

If $n \geq 4$, then, obviously, you can choose 4 birdhouses, the flights between which are arranged in one of the ways shown in figure 1. In any case, the distances between starlings $A$ and $B$, $C$ and $D$ do not change after the flight, while by condition the smaller distance should become big.

For the case $n=3$ an example is given in figure 2.
A. Berzins, V. Dubrovsky

M1183. Each of the seven little ones went to the ice cream kiosk 3 times on Sunday. It is known that every two of them met near the kiosk. Prove that at some points three small ones met there at the same time.

Let the statement of the problem be false and let $\Delta_1, \Delta_2, \dots, \Delta_n$ be a non-intersecting interval of time during which two small dogs are near the kiosk. At the initial moment of each of the intervals $\Delta_2, \Delta_3, \dots, \Delta_n$ at least one small person approached the kiosk, at the initial moment of the interval $\Delta_1$ - either one (if there was already a small person near the kiosk) or two (if there were never any small people near the kiosk). Consequently, the total number $s$ of arrivals to the kiosk of all seven small shops is no less than $n+1$. Since from only 7 small ones it is possible to form $7 \cdot 6/2=21$ different pairs, and according to the condition, every two small ones meet at the kiosk, $n \geq 21$. Therefore, $s \geq 22$. On the other hand, $s=7 \cdot 3=21$. Contradiction.

A. Anjans

M1184. On all edges of an arbitrary terazdrade, a point is selected. Through each point lying on the edges emerging from one vertex, we draw a plane. Prove that if three of them are tangent to the inscribed ball, then the fourth plane is tangent to the inscribed ball.

Consider the terazdr $ABCD$ and take the points $K, L, M, P, Q, T$ on its edges, as shown in figure. Let the planes $KMP, MLT$ and $LKQ$ touch the ball inscribed in the terastron, and let the plane $PTQ$ not touch this ball. Let, for the purpose of definition, the inscribed ball intersect the plane $PTQ$. Let us draw through $PQ$ a plane tangent to the inscribed ball and denote by $T_1$ the point of intersection of this plane with the edge $DC$.

Consider the convex polyhedron (octahedron) $KMLPQTT_1$. For convenience, color the faces $KMP, MLT, LKM$ and $PQT_1$ black, and the remaining faces will be empty white. The faces that do not belong to the surface of the terazdra $ABCD$ are painted black, while the faces that belong to the surface $ABCD$ are white. Note that no pair of black faces has a common edge. As for white faces, there is one exception: the edge $T_1T$ is common to two white faces. All faces of our octahedron touch one ball. Let's take a tangency point in each face and connect it to all the vertices of this face. Each face will be divided into triangles. In this case, each black triangle corresponds to an equal white triangle in the adjacent face, which has a common side with it. White triangles have one exception - a pair of equal white triangles at edge $T_1T$.

⟦folio 36⟧

---
running_head:
folio:
---

matches $s$; on our figure this happened at $n = 5$.

2) From the data of the equation it immediately follows that $x_1 = x_n$, $x_2 = x_{n-1}$, $x_3 = x_{n-2}$, ...: in fact, from the first and last it is clear that $x_1 = x_n = 1/s$, from the second and penultimate - that $x_1 + x_2 = 1/(s - x_1) = 1/(s - x_n) = x_{n-1} + x_n$, i.e. $x_2 = x_{n-1}$, etc. This symmetry is immediately visible from figure 1, since hyperbola of symmetrine relative to the head of bisserris $y = s - x$.

The second remark allows us to briefly write down the solution for small $n$.

a) $n = 3$. Then $s = 2x_1 + x_2 = x_1 + s_1$. From the equation $x_1(x_1 + s_1) = 1$, $s_1^2 = 1$ we find $s_1 = 1$, $x_1^2 + x_1 - 1 = 0$, from where (since $x_1 > 0$)

$$x_1 = \frac{\sqrt{5} - 1}{2}, x_2 = 1 - x_1 = \frac{3 - \sqrt{5}}{2}, x_3 = x_1.$$

6) $n = 4$. Then $s = 2x_1 + 2x_2 = 2s_1$. From the equation $2x_1s_1 = 1$, $s_1(2s_1 - x_1) = 1$ we find $2s_1^2 = 1 + x_1s_1 = 3/2$, $s_1 = \sqrt{3}/2$, from where

$$x_1 = \frac{\sqrt{3}}{3}, x_2 = \frac{\sqrt{3}}{2} - \frac{\sqrt{3}}{3} = \frac{\sqrt{3}}{6}, x_3 = x_2, x_4 = x_1.$$

Note that in the case of $n = 2$ the answer is found immediately:

$$2x_1^2 = 1, x_1 = x_2 = \sqrt{2}/2.$$

To a geometry connoisseur, these numbers evoke the idea that the random numbers $n = 2$, $n = 3$ and $n = 4$ are somehow related to the corresponding angles $45^\circ$, $36^\circ$ and $30^\circ$. In fact, we will see (see figure 2) that for any $n$ there is a solution to the system associated with the angle $\alpha = 180^\circ/(n + 2)$. From the first remark it follows that this solution is unique.

Let's construct an equilateral triangle $A_0OA_n$ with sides $A_0O = OA_n = 1$ and angles $\alpha = 180^\circ/(n + 2)$ at the base; based on $A_0A_n$ we mark the points $A_1, A_2, ..., A_{n-1}$ so that the segments $A_0A_1, A_1A_2, ..., A_{n-1}A_n$ are visible from the vertex $O$ at equal angles $\alpha$. Let us prove that the lengths of these segments $x_1, x_2, ..., x_n$ satisfy our system. It is convenient to draw another ray OP through the point $O$, parallel to $A_0A_n$ ($\angle POA_0 = \alpha$). Triangles $A_0OA_k$ and $A_nA_{k-1}O$ are similar ($\angle A_0 = \angle A_n = \alpha$, $\angle A_0OA_k = k\alpha = \angle POA_{k-1} = \angle OA_{k-1}A_n$), with sides $A_0O = 1$ and $A_0A_k = x_1 + ... + x_k$ of the first corresponding to sides $A_{k-1}A_n = x_k + ... + x_n$ and $OA_n = 1$ of the second, from which we obtain the equation

$$(x_1 + ... + x_k)(x_k + ... + x_n) = 1.$$

So, the existence of a solution is proven. Using the theorem of sines, it is easy to obtain explicit formulas: since $OA_0 = 1$,

$$\angle A_0OA_k = k\alpha, \angle A_0A_kO = 180^\circ - \angle POA_k = 180^\circ - (k + 1)\alpha,$$

from $\Delta OA_{k-1}A_k$ and $\Delta OA_0A_k$ we get.

⟦folio 37⟧

---
running_head:
folio:
---

$$\frac{x_k}{\sin \alpha} = \frac{OA_k}{\sin k\alpha}, \frac{OA_k}{\sin \alpha} = \frac{1}{\sin (k+1)\alpha},$$
where:
$$x_k = \frac{\sin^2 \alpha}{\sin k\alpha \sin (k+1)\alpha} \quad (k=1, 2, ..., n; \alpha = \frac{\pi}{n+2}).$$

In particular, for $n=10$ we have $\alpha = \frac{\pi}{12}$; with the numbers $\sin k\alpha$ for $k=1, 2, ..., 6$ equal to the corresponding $\sqrt{\frac{1}{2} - \frac{\sqrt{3}}{4}}, \frac{1}{2}, \frac{\sqrt{2}}{2}, \frac{\sqrt{3}}{2}, \sqrt{\frac{1}{2} + \frac{\sqrt{3}}{4}}, 1$ (and sized, $\sin (12-k)\alpha = \sin k\alpha$). Substituting these values ​​into the general formula, we obtain the answer indicated in the margin.

N. Vasiliev, V. Protasov

F1193. In space there is a cube. At this moment, the face ABCD is horizontal (Fig. 1), and the velocities of points A and B are directed vertically downwards and are equal modulo v. It is known that the speed of point C at this moment is modulo 2v. What is the maximum speed that other cubes can have at this moment?

Consider point C. It is easy to report that at a given moment the velocity vector of this point is vertical (this follows from the fact that both the translational and vertical components of the velocity of point C are vertical). In this case, the velocity vector of point C can be directed both upward (case a) and downward (case 6).

Let's start with case a). Obviously, there is a point on line BC whose velocity at a given moment is zero. Indeed, if the translational component of the velocity of all points of the cube is equal to v and directed downward, then the vertical component of point C is equal to 3v and directed vertically upward. Then at a distance $a/3$ from point B, where $a$ is the length of the edge of the cube, there will be a point O, the vertical component of the velocity of which is equal to v and directed upward. Therefore, the total speed of point O at a given moment is zero. This point is called the exchange center of rotation. But if point O is not moving at a given moment, then the point with the maximum distance from point O will have the maximum speed. Obviously, point E satisfies this condition. Since
$$\frac{v_E}{v_C} = \frac{OE}{OC} \quad \text{и} \quad OE = \sqrt{a^2 + \left(\frac{2}{3} a\right)^2} = \frac{\sqrt{13}}{3} a,$$
we get
$$v_E = v_C \frac{OE}{OC} = v \sqrt{13} \approx 3,6v.$$

⟦folio 38⟧

---
running_head:
folio:
---

In case 6) the instantaneous center of rotation of the face BCEF - point $O'$ (see Fig. 2) - lies outside the edge BC at a distance $BO' = a$ to the right of point B. Point E will again have the maximum speed, and

$$v_E = v_C \frac{O'E}{O'C} = 2v \frac{\sqrt{a^2 + (2a)^2}}{2a} = v\sqrt{5} \approx 2,2v.$$

So, for both possible directions of the velocity vector of point C, the maximum value of the velocity will have the points of the cube lying on the edge, which is parallel to the straight line AB and passes through the vertex E.

S. Krotov

F1194. The capillary is made of two thin glass tubes with internal diameters $d_1$ and $d_2$ (see figure). Into it there is a large quantity of water with a mass of M. The Koeda capillary was placed horizontally if the liquid “crept” into the thin part, and when it was installed vertically - if the water flowed out of it. Under what conditions will there be part in a thick tube and part in a thin tube between the axis of the capillary and the vertical tube? Coefficient of surface tension of water σ, density of water Q. Wetting is considered complete.

The maximum value of the angle between the axis of the capillary and the vertical corresponds to the case when almost all drops of water end up in the thin part of the capillary. In this case, the length of the water column

$$l_{\max} = \frac{M}{\rho \pi d_2^2/4},$$

and its height

$$h_{\max} = l_{\max} \cos \alpha_{\max}.$$

Then the equilibrium condition will be equality

$$p_{\text{атм}} - \frac{4\sigma}{d_1} = p_{\text{атм}} - \frac{4\sigma}{d_2} + \rho g l_{\max} \cos \alpha_{\max},$$

where is it from?

$$\alpha_{\max} = \arccos \frac{\pi \sigma d_2}{Mg} \left(1 - \frac{d_2}{d_1}\right).$$

The minimum value of the angle between the capillary axis and the vertical one will correspond to the case when it is practically

⟦folio 39⟧

---
running_head:
folio:
---

Virtually the entire drop is located in the wide part of the capillary. Similar to the previous one, we find

$$\alpha_{\min} = \arccos \frac{\pi \sigma d_1}{Mg} \left( \frac{d_1}{d_2} - 1 \right).$$

A. Zilberman

F1195. A vertical pipe with a height of $H=1$ m and a cross-sectional area of ​​$S=50$ cm$^2$ is open at both ends. A heater with a power of $N=100$ W is installed at the bottom of the pipe. What speed of the upward flow will be established in the pipe? Assume that the heater does not ignite the cross-section of the pipe. Atmospheric pressure $p_0=1$ atm, outside temperature is room temperature. The molar heat of air at a constant volume is $C_V=2,5$ R, where $R$ is the universal gas constant.

Obviously, heating leads to a decrease in air density, and the Archimedean force acting on hot air lifts it upward, i.e. an upward flow of air occurs in the pipe.

Let's break the problem into two parts.

1) Let the air density in the pipe $\rho$, the density of the surrounding air $p_0$ ($\rho < p_0$). What will be the speed of uniform movement of air in the pipe?

Let us denote the pressure of the upper end of the pipe (see figure) $p_0$. Then, near the lower end, the pressure inside the pipe will be $p_0 + \rho gH$, and outside $p_0 + \rho gH > p_0 + \rho gH$. It turns out that near the bottom hole of the pipe, pressure having zero speed is sucked into the pipe, where its pressure drops and the speed increases to a certain value $v$. Let's find it using the Bernoulli equation:

$$\rho \frac{v^2}{2} + p = \text{const},$$ or $$\frac{\rho v^2}{2} + p_0 + \rho gH = p_0 + \rho gH,$$

where do we get it from

$$v = \sqrt{2 \frac{\rho_0 - \rho}{\rho}} gH.$$

2) Knowing the power of the heater $N$, we find the ratio $(\rho_0 - \rho)/\rho$.

An air flow $\rho vS$ (mass per unit time) or $\frac{\rho}{M} vS$ (amount of substance per unit time) passes past the heater. Heating occurs at constant pressure, so

$$N = \frac{\rho}{M} vSC_p \Delta T,$$

where $C_p = C_V + R = 7/2$ R, and $\Delta T$ is equal to the difference in temperature inside the pipe (after the heater) and outside. At constant pressure and at $\Delta T/T \ll 1$

$$\frac{\rho_0 - \rho}{\rho} = - \frac{\Delta \rho}{\rho} \approx \frac{\Delta T}{T}.$$

Thus,

$$v^2 = 2 \frac{\rho_0 - \rho}{\rho} gH = 2 \frac{\Delta T}{T} gH = \frac{2NMgH}{T\rho vSC_p},$$

or

$$v^3 = \frac{2NMgH}{T\rho SC_p} = \frac{2NgHR}{pSC_p} = \frac{4}{7} \frac{NgH}{pS} \approx \frac{4}{7} \frac{NgH}{p_0S}.$$

(Continued on page 42)

⟦folio 40⟧

---
running_head:
folio:
---

I don't inject myself
I affirm that
just one look
for recognition
spectrum gives
opportunity
F. Talbot
