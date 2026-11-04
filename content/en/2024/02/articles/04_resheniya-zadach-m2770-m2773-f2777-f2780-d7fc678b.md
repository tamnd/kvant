---
id: 2024-2-resheniya-zadach-m2770-m2773-f2777-f2780-d7fc678b
issue: kvant_2024_2
year: 2024
number: "2"
title: Solutions to problems M2770—M2773; F2777—F2780
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 24
page_last: 28
page_labels: 23-26
lang: en
source: kvant_digital
content_sha256: b4ced6db2e824626fcda0901a8752450e027350859ecd55cb8d49694698ab312
prompt_sha256: draft-1
translated_from: content/ru/2024/02/articles/04_resheniya-zadach-m2770-m2773-f2777-f2780-d7fc678b.md
source_content_sha256: 3aef7a961d4e790f79da12353180f8ee46d84dffaad3155adbd25c4129816315
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio none⟧

Solutions to problems M2770-M2773, F2777-F2780

M2770. A hole in the shape of a triangle was made in a square sheet of paper of area 1 (the vertices of the hole do not extend to the border of the sheet). Prove that you can cut a triangle with area 1/6 from the remaining paper.

Let's take a point inside the triangle, project the vertices of the triangle from it onto the contour of the square ABCD and connect the projections to each other. You will get a new triangle containing the original one. If at the same time two vertices of the new triangle are on the same side of the square, increase this side of the triangle so that it coincides with the side of the square (this operation may have to be repeated for two sides of the square). It is enough to prove the statement for the last triangle. Note that inside one side of the square (empty its side AD) there are no vertices of the triangle. Therefore, we can assume that the vertices K, L, M of the triangle lie respectively on the sides AB, BC, CD (see figure), perhaps some of them coincide with the vertices of the square.

⟦folio 23⟧

PROBLEM WORKER

One of the segments BL, CL is not less than 1 2. Let, for definiteness, this be a segment CL. If in this case CM t 2 3, then $S_{LCM} t 1 6$. If CM 2 3, then $S_{ADM} t 1 6$. A.Yuran

M2771. For what largest N is there an N-digit number with the following property: in its decimal notation, among any several consecutive digits, some digit occurs exactly once?

Answer: 1023. We will call numbers that have the property from the condition good. Grade. Let us prove by induction that a good number containing no more than k different digits 1 d k d 10 has no more than $2^{k} 1$ digits. From here the estimate we need will follow for k 10. (Further in the assessment we will assume that the number can begin with any digit, including 0.) The base (k 1) is obvious - only one digit is used, and it cannot be repeated. Let's perform the induction step. Let 2 d k d 10 and X be a good number containing at most k different digits. By condition, one of the numbers appears in it exactly once. Note that there are good numbers written to the left and right of this digit; each of them uses no more than k 1 different digits, therefore each of them (according to the induction assumption) contains no more than $2^{k} 1 1$ digits, and in total in our number X then no more than $2^{k} 1 1 1 2^{k} 1 1 2^{k} 1$ digits, which is what was required. Example. We will also construct an example of a good number containing k different digits 2 d k d 10, which has exactly $2^{k} 1$ digits, by induction. Base (k 2): the number 101 is suitable. Induction step. Let 3 d k d 10 and X be a good number with k 1 different digits and $2^{k} 1 1$ signs. Let's take the number a, which does not appear in this number, and add the number X to it on the left and right, we get XaX. The resulting number has $2^{k} 1$ digits, and it is good: after all, any part of it from several consecutive digits either includes the only digit a in the number, or is part of a good number X. A. Glebov

"QUANTA"

⟦column⟧

M2772. In the white squares of the chessboard 100 and 100 there are 100 bishops, among which there are white and black. They can make moves in any order and capture bishops of the opposite color. What is the smallest number of moves that is known to be sufficient to leave one bishop on the board?

Answer: 197 moves. Algorithm. We will make all moves so that bishops of both colors remain on the board, as long as there are at least two bishops. If it is possible to make an economical capture (let’s call it a move in which the bishop in one move beats an bishop of a different color standing on the same diagonal with it), we do it. Otherwise, we will do an uneconomical capture in two moves: we will choose two bishops of different colors and consider the path along which the first bishop could go to the second in two moves (there is always such a path). If there are more bishops on this path, we will find among them two bishops of different colors closest to each other, and let one of them beat the other in two moves. Initially, all bishops stand on 99 white diagonals parallel to the main white diagonal. Then one of them has at least two bishops. Let's call two of these bishops special. If the special bishops are of different colors, an economical capture is possible already on the first move along this diagonal; let's do it. Let these special elephants be the same color, say white. Then, during captures, we will beat white bishops with black bishops. After the first special bishop is taken, this restriction is removed. Note that economical withdrawal is possible immediately after this. Since there are 99 captures in total and at least one of them is economical, no more than 2 99 1 197 moves will be required. Grade. Let's place 50 bishops on the bottom and top lines of the board, the colors of the bishops are not important. Let's consider all 199 white diagonals in both directions (in particular, we also consider the corner white squares of the board to be diagonals). In this case, all 199 white diagonals will initially have bishops. During a move, the number of diagonals containing at least one bishop can

⟦folio 24⟧

---
running_head:
folio:
---

decrease by no more than 1. Indeed, the only diagonal that can “disappear” is the diagonal from which the bishop leaves to capture another bishop. At the end, when there is only one bishop left, there will be 2 occupied diagonals. In total, in this initial distance there will be at least 199 – 2 = 197 moves.

A. Gribalko

M2773. Circle $\omega$ lies inside circle $\Omega$ and touches it internally at point $T$ (Fig. 1). Let $XY$ –

Fig. 1
variable chord of the circle $\Omega$ tangent to $\omega$. Let $X'$ and $Y'$ denote the midpoints of the arcs $TY$ and $TX$ that do not contain the points $X$ and $Y$ of the corresponding one. Prove that all possible lines $X'Y'$ pass through a fixed point.

We will prove that the lines $X'Y'$ intersect the diameter $TS$ of the circle $\Omega$ at a fixed point $K$ (Fig. 2).

Let $L$ be the point of tangency between $XY$ and $\omega$. Then, as is known, $TL$ intersects $\Omega$ for the second time in the middle $Z$ of arc $XY$ (this, for example, follows from considering the preparation with center $T$, which transfers $\omega$ to $\Omega$: with this preparation $XY$ goes tangent to $\Omega$, passing through $Z$, therefore this tangent is parallel to $XY$. Therefore, $TZ$ is the bisector of the angle $XTY$, which means that $XX', YY'$ and $TZ$ intersect at one point $I$ – the center of the inscribed circle of triangle $XYT$. $X'Y'$ intersects $TZ$ at point $R$. From the equality of the angles $\angle Y'X'X = \angle TX'Y'$ and $\angle X'Y'Y = \angle TY'X'$ we understand that the triangles $X'Y'I$ and $X'Y'T$ are symmetrical with respect to $X'Y'$. Hence $TI = 2TR$ and $TZ \perp X'Y'$, that means $\angle TRK = \angle TZS = 90^\circ$.

It is enough for us to prove that $TK/TS$ has been constructed. But $TK/TS = TR/TZ = TI/(2TZ)$. Then it is enough to understand that $TI/TZ$ is built or that $ZI/ZT$ is built. By the tributary lemma $ZX = ZI$. So, it is enough to understand that $ZX/ZT = const$.

But from the preparation with center $T$ it follows that $TL/TZ = r/R$ (where $r$ and $R$ are the radius of $\omega$ and $\Omega$ respectively), and from the similarity of $ZXL \sim ZTX$ it follows that $ZL \cdot ZT = ZX^2$, revealing $\frac{R-r}{R} ZT \cdot ZT = ZX^2$. We see that the relation $ZX/ZT = \sqrt{\frac{R-r}{R}}$ has been constructed, and this completes the solution to the problem.

Note that this construction has many interesting invariants. For example, from the last considerations and the theorem of sines, it is easy to discover that the radius of the circle ($XZL$) has been constructed. A problem with such a formulation was proposed at the 2001 All-Russian Olympics (author - T. Emelnova).

P. Kozhevnikov, F. Petrov

F2777.1 A squirrel sitting on a tree branch throws a nut to a mouse located on a horizontal surface. After a while we put the nut on

1 The author of the solution to problems F2777–F2780 is V. Plis.

⟦folio 25⟧

---
running_head:
folio:
---

the surface of a mouse's paws. The direction “from the squirrel to the mouse” makes an angle β with the vertical. The initial speed of the nut is the smallest in maximoleme. What angle α does the initial velocity vector of the nut make with the horizon? Air resistance is negligible.

The horizontal flight range of a ball thrown at a speed $v_0$ from a height $h$ at an angle α to the horizontal (Fig. 1) is equal to

Fig. 1
$s = x(T) = v_0 \cos \alpha \cdot T$. The speed $v$ at the moment of fall does not depend on the angle α and is equal to $v = \sqrt{v_0^2 + 2gh}$. This follows from the law of conservation of total mechanical energy. Further, during the flight of the ball, it changes with time according to the law $\vec{v}(t) = \vec{v}_0 + \vec{g}t$. At the moment of falling $\vec{v}(T) = \vec{v}_0 + \vec{g}T$.

Let's turn to the triangle of speeds (Fig. 2) and calculate its area, which is equal to half the product of the base and the height, or half the product of the length of the sides and the sine of the angle between them:

$$\frac{1}{2} g T v_0 \cos \alpha = \frac{1}{2} v_0 v \sin \delta,$$

where $\delta$ is the angle of rotation of the velocity vector during the flight. From here we get the horizontal flight range:

$$s = \frac{1}{g} v_0 v \sin \delta.$$

In this expression, only the angle $\delta$ depends on α. Consequently, the maximum range is achieved when the velocity vector rotates through an angle $\delta = \frac{\pi}{2}$ during the flight. This range is equal to

$$s = \frac{v_0 \sqrt{v_0^2 + 2gh}}{g}.$$

Therefore, the minimum speed with which a ball should be thrown from a height $h$ to a maximum horizontal distance $s$, and therefore to a maximum distance $l = \sqrt{s^2 + h^2}$ from the starting point, is

$$v_0 \min = \sqrt{g(l - h)}.$$

With such a throw

$$tg \alpha = \frac{v_0 \min}{\sqrt{v_0^2 + 2gh}} = \sqrt{\frac{1 - \frac{h}{l}}{1 + \frac{h}{l}}} = \sqrt{\frac{1 - \cos \beta}{1 + \cos \beta}} = tg \frac{\beta}{2},$$

i.e. $\alpha = \frac{\beta}{2}$. The throwing angle is equal to half the angle that the direction towards the target makes with the vertical.

F2778. A hoop is made from rigid homogeneous wire of length L. In the first experiment, the hoop is placed on a rough horizontal surface and, with a blow, is brought into forward motion at a certain horizontal speed. During the freezing process, the displacement of each hoop is equal to s. In the second experiment (see Fig.nok) the hoop is placed on the same surface, holding it in a vertical plane, and with a blow it sets it into forward motion; at the initial moment, everything in the hoop moves at the same horizontal speed as in the first experiment. It is known that during the sliding process the angular acceleration is constant and equal to $\frac{\Delta \omega}{\Delta t} = \frac{a}{R}$, where a is the modulus of the accelerated chain of masses of the hoop. What number of revolutions in the mass chain system will we complete the hoop by the time when

⟦folio 26⟧

---
running_head:
folio:
---

the movement of the hoop will go into quality without
calling out? Friction coefficient
sliding of the hoop along the horizontal
surface is the same at all points of this
surfaces.

In the first experiment $s = \frac{v_0^2}{2\mu g}$, where $v_0$ is the initial
speed of the hoop, $\mu$ – coefficient
friction. In the second experiment, in the process of movement
speed of change of hoop impulse
equal to the sum of external forces (gravity,
support and friction reactions):

$$\frac{\Delta(m\vec{v})}{\Delta t} = m\vec{g} + \vec{N} + \vec{F}_{\text{tp}}.$$

Let's move on to projections of forces and acceleration
to the vertical and horizontal directions
leniya:

$$N = mg, F_{\text{tp}} = \mu N = \mu mg,$$

$$\frac{\Delta(mv)}{\Delta t} = -\mu mg, \quad \frac{\Delta v}{\Delta t} = -\mu g.$$

Hence, taking into account the equality $R \frac{\Delta\omega}{\Delta t} = \mu g$ it follows

$$\frac{\Delta v}{\Delta t} + R \frac{\Delta\omega}{\Delta t} = 0.$$

During rolling with slipping
the sum $v + \omega R$ remains constant, equal to
to its initial value $v_0$. At the moment
transition to rolling without slipping
$v = \omega R = 0,5v_0$. This will happen in time $t = \frac{0,5v_0}{\mu g}$ after the start. By this time
hoop rotation angle

$$\varphi = \frac{1}{2} \left( \frac{\Delta\omega}{\Delta t} \right) t^2,$$

speed

$$n = \frac{\varphi}{2\pi} = \frac{v_0^2}{16\pi\mu g R} = \frac{s}{4L}.$$

F2779. In a vertical cylinder under
contained by a light movable piston
some number of monatomic ideas
al gas. The gas was heating up slowly. IN
during the expansion process, gas contains work-
mu $A = 10U_0$, where $U_0$ – internal energy
 gas in the initial state. Let's find

ratio of averages struck
gas atoms with stacks per
unit of area per unit of time in
initial and final states. Tre-
nie sitmaite negligibly malm.

Average number of impacts per
unit area per unit time pro-
proportional to the concentration of molecules (or
inversely proportional to the volume of the cylinder) and the average speed of thermal movement of molecules, which is proportional
square root of the absolute temperature:

$$z = \frac{1}{4} nv_{\text{cp}} = \frac{1}{4} n \sqrt{\frac{3kT}{m}} \sim n\sqrt{T} \sim \frac{1}{V}\sqrt{T}.$$

Requested attitude

$$\alpha = \frac{z_0}{z_1} = \frac{v_1}{v_0} \sqrt{\frac{T_0}{T_1}}.$$

In the picture process

$$A = p_0 \left( V_1 - V_0 \right) = vR \left( T_1 - T_0 \right), v = \frac{p_0V_0}{RT_0},$$

further

$$\frac{p_0V_1}{p_0V_0} = \frac{T_1}{T_0} = \frac{V_1}{V_0} = 1 + \frac{A}{p_0V_0},$$

$$\alpha = \sqrt{1 + \frac{3}{2} \frac{A}{U_0}} = 4.$$

F2780. During the heating process, the gas
of helium in the amount of $v = 1$ mol molar
nal heat of gas C calculated with absolute temperature $T$ according to the law
$C = R \frac{T}{T_1}$, where $R = 8,31$ J/(mol K) – uni-
versal gas constant, $T_1 = 400$ K –
initial temperature. Let's find a job
mu of gas to the moment when the volume of gas
will become minimal.

Dependency $p(V)$ is represented existentially
on figure 1. By condition, in a small neighborhood
state 2 molar heat in the process of heating helium is equal to

$$C = \frac{3}{2} R,$$ occurs in this vicinity
isochoric heating to temperature
