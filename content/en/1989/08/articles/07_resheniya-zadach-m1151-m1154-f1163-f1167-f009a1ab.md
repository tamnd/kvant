---
id: 1989-8-resheniya-zadach-m1151-m1154-f1163-f1167-f009a1ab
issue: kvant_1989_8
year: 1989
number: "8"
title: Solutions to problems M1151—M1154; F1163—F1167
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 41
page_labels: 32-39
tag: BJMW
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5d650edca96b39d087d7b30ba78042d47a1e6fb4d1f011fecafa2b74ffeba73b
prompt_sha256: draft-1
translated_from: content/ru/1989/08/articles/07_resheniya-zadach-m1151-m1154-f1163-f1167-f009a1ab.md
source_content_sha256: 6298fd91411eb4fad0737cd964c73e1a30c4907c31b05719eee49163a58fbb55
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

end of the rod - 100 °C. After 1 minute, the temperature leveled off and turned out to be 200 °C. Estimate the amount of heat that the rod consumed during this time. The specific heat of iron is 460 J/(kg K), rod weight is 15 g.

A. R. Zilberman

F1185. A uniformly charged cube creates an electric field of intense $E_0$ at its vertex. A cube half the size is removed from the cube (Fig. 2). What will the field strength be now at point $A$?

I. Yu. Poteryayko

F1186. At what value of the capacitance of the capacitor $C_x$ in the circuit shown in figure 3, the phase shift between the applied voltage and the current in the external circuit will be zero at any source frequency? The inductance of the coil is $L$, the resistance of each resistor is $R$. All elements of the circuit are considered ideal.

V. E. Skorovarov

F1187. A sleigh with a length of $L=2$ m and a height of $H=0,5$ m travels in a straight line at a speed of $v=10$ m/s. A tent with a camera is installed at a distance of $d=10$ m from the road, and photography is taken at the moment of maximum merging.

The camera has a single-lens lens with a focal length of $F=5$ cm. The shutter speed (i.e., the time during which each part of the camera is illuminated) is reflected in this camera using a slit shutter, which operates as follows. Along the film frame, a vertical slit moves at a constant speed $v_0=1$ m/s, the width of which can be reduced until the required shutter speed is obtained. Kadar size $24\times 36$ mm. What is the length to height ratio of a fairly sharp caney image obtained on film?

M. G. Gavrilov

Problem solutions
M1151 — M1154, F1163 — F1167

a) This equality is easily proven by induction. For $n=1$ it is true: $\frac{1\cdot 2!}{2} = \frac{3!}{2} - 2=1$. Assuming that it has been proven for $n=k$, let’s check that it is also true for $n=k+1$:

$$\frac{1\cdot 2!}{2} + \frac{2\cdot 3!}{2^2} + \dots + \frac{k(k+1)!}{2^k} + \frac{(k+1)(k+2)!}{2^{k+1}} =$$

$$= \frac{(k+2)!}{2^k} + \frac{(k+1)(k+2)!}{2^{k+1}} - 2 =$$

$$= \frac{(k+3)!}{2^{k+1}} - 2.$$

b) Answer: $\frac{(n+3)!}{3^n}$ - c. This can be proven by in-

⟦folio 33⟧

The induction is the same as in part a), but this reasoning can be formulated somewhat differently. Note that each term of the sum can be written as a difference

$$\frac{(k+3)!}{3^k} - \frac{(k+2)!}{3^{k-1}} = \frac{(k+2)!(k+3-3)}{3^k} = \frac{k(k+2)!}{3^k}.$$

Let us write down a number of such equalities for $k=1, 2, ..., n$ and add them term by term; we get:

$$\frac{(n+3)!}{3^n} - 3! = \frac{1 \cdot 3!}{3} + \frac{2 \cdot 4!}{3^2} + \dots + \frac{n(n+2)!}{3^n}.$$

Similarly, for any natural number $d$ from the equality

$$\frac{(k+d)!}{d^k} - \frac{(k+d-1)!}{d^{k-1}} = \frac{k(k+d)!}{d^k}$$

it is possible to generalize the results of problems a) and 6):

$$\frac{1 \cdot d!}{d} + \frac{2 \cdot (d+1)!}{d^2} + \dots + \frac{n(n+d)!}{d^n} = \frac{(n+d)!}{d^n} - d!$$

N. V. Vasiliev, V. N. Zhokha

M1152. Let $h$ and $l$ be the altitude and altitude drawn from vertex $A$ of triangle $ABC$. Let us continue the bissertis until it intersects with the circumcircle at point $L$ (see figure) and draw the diameter $LN$ of this circle. It is perepidicular to the chord $BC$, since $L$ is the midpoint of the arc $BC$, so $\angle ALN$ is equal to the angle $\varphi$ between $h$ and $l$. Hence,

$$h/l = \cos \varphi = AL/LN = (AI+IL)/2R \geq \sqrt{AI \cdot IL}/R,$$

where $I$ is the center of the inscribed circle of triangle $ABC$. It remains to prove that $AI \cdot IL = 2rR$.

Let us drop the peripidicular $ID$ from the point $I$ to the side $AB$, then $ID = r$ and $AI = r/\sin(\angle A/2)$. At the same time, $IL = LC$, since in the triangle $LIC$ each of the angles of the vertices $I$ and $C$ is equal to $(\angle A + \angle C)/2$ (the first as the external angle of the triangle $AIC$, and the second is equal to $\angle ICB + \angle BCL = \angle C/2 + \angle BAL)$. But $LC$ is the chord of the circumscribed circle on which the angle rests $LAC$ equals $\angle A/2$, so $LC = 2R \sin(\angle A/2)$ So,

$$AI \cdot IL = \frac{r}{\sin(\angle A/2)} 2R \sin(\angle A/2) = 2rR.$$

From the solution it is clear that our inequality turns into equality when $AI = IL$, i.e. when the straight line $OI$ connecting the centers of the inscribed and circumscribed circles is perepidicular to the bissertis $l$.

Among other solutions, we see a trigonometric one, using the formula $r = 4R \sin \frac{\angle A}{2} \sin \frac{\angle B}{2} \sin \frac{\angle C}{2}$ and the equality $\varphi = \frac{|\angle B - \angle C|}{2}$. We will leave the details of this decision to the readers.

C. Verceanu, V. N. Dubrovsky

⟦folio 34⟧

M1153. What is the largest number of turns that can contain a closed route of a rook that goes around all the cells of an 8x8 chessboard once?

Fig. 1.

Fig. 2. Fig. 3.

M1154. Prove that if a quadrilateral is inscribed in a circle and described by the circumference of the circle, then a line drawn through the centers of these circles passes through the point of intersection of the diagonals of the quadrilateral.

Answer: 56 turns. A route with 56 turns is shown in figure 1. Let us prove that this number cannot be represented.

Let's call a square of the board a corridor for a given route if the rook does not make a turn in it. Note that from each pair of cells adjacent to the corner cells, at least one is a corridor - otherwise, in the cell diagonally adjacent to the corresponding corner cell, the rook appears twice (Fig. 2).

Let's cut the board into 4 4x4 squares. Each of them has a corridor adjacent to the corner cell. Let us show that besides it there is at least one more corridor. The distance to the right is the lower left square and let's assume that cell a2 is a corridor. Let's assume that there are no other corridors in this square. Then it is obvious that the route sequentially passes through cells b2, b1, a1, a2, a3, b3, b4 (Fig. 3). The next cell will be a4, otherwise we will never get into it (or the route will not be closed). Now you can similarly continue the route in the other direction: b2, c2, c1, d1, d2, e2. From the obtained figure it is clear that the route must contain the section d3_c3_c4, therefore, one of the cells - d3 or c4 - is a corridor (this is proven in the same way as for corner cells - see the beginning of the solution).

So, the number of corridors is no less than 2×4=8, and the number of turns is no more than 64-8=56.

M. G. Khovanov

Let us introduce the following notation: ABCD is a given quadrilateral; 2α, 2β, 2γ, 2δ—the values ​​of its angles at vertices A, B, C, D; O and I, R and r are the centers of the circumcircle and incircle and their radii, P is the point of intersection of the diagonals (see figure). To determine this, we will assume that the angles 2α and 2β are not obtuse, which means that 2γ=π-2α and 2δ=π-2β are not acute. Let us show that then the points O and I lie inside the angle APB and the ratios of the distances from these points to the side of this angle (diagonals) are the same: ρ(O, BD)/ρ(O, AC) = ρ(I, BD)/ρ(I, AC) (the letter ρ denotes the distances). From here, obviously, the statement of the problem will follow.

Point O lies on the same side of BD as point A, (or non-chair on BD) since angle BCD is not acute. Point I also lies on this side of BD, since the angle at vertex I of the quadrilateral BCDI is equal to

$$2\pi - \beta - 2\gamma - \delta = \pi - (\beta + \delta) + \pi - 2\gamma = \frac{\pi}{2} + 2\alpha \leq \pi$$

(you teach that β+δ=π/2).

Similarly, we check that both points - O and I - lie on the same side of point B relative to AC. Therefore, these points lie inside angle APB.

Further, the ratio of the distances from O and I to BD is equal to the ratio of the areas of triangles OBD and IBD

$$\frac{S_{OBD}}{S_{IBD}} = \frac{OB \cdot OD \sin \angle BOD}{IB \cdot ID \sin \angle BID}.$$

⟦folio 35⟧

But $OB=OD=R$, $\angle BOD=2\angle BAD=4\alpha$ (the central angle is twice the corresponding inscribed angle), $IB=r/\sin \beta$, $ID=r/\sin \delta=r/\cos \beta$ (see the mark) and, as we have shown, $\angle BID=\pi/2+2\alpha$. Hence,

$$\frac{\rho(O, BD)}{\rho(I, BD)} = \frac{R^2 \sin 4\alpha \sin \beta \cos \beta}{r^2 \sin (\pi/2+2\alpha)} = \frac{R^2 \sin 2\alpha \cos 2\alpha \sin 2\beta}{r^2 \cos 2\alpha} = \frac{R^2}{r^2} \sin 2\alpha \sin 2\beta.$$

From the symmetry of the problem it is clear that the ratio $\rho(O, AC)/\rho(I, AC)$ is equal to the same value, therefore $\rho(O, BD)/\rho(O, AC) = \rho(I, BD)/\rho(I, AC)$, which is what needed to be proven.

In general, an “inscribed-circumscribed” quadrilateral has a number of red properties. Let us present some of them that are closely related to this task.

Let $Q_1$ be a quadrilateral with vertices at the points of tangency of the inscribed-circumscribed quadrilateral $ABCD$ with the inscribed circle, and $Q_2$ be a quadrilateral bounded by perpendiculars to the segments $IA$, $IB$, $IC$, $ID$ at their ends. Then 1) diagonals $Q_1$ are perpendiculars and intersect at the same point $P$ as diagonals $ABCD$; 2) quadrilaterals $Q_1$ and $Q_2$ are prepared, and the center of the preparation lies on the straight line $PI$; 3) on the same line lie the circumcenter of the quadrilateral $Q_2$ and the centers of gravity of the quadrilaterals $Q_1$ and $Q_2$.

V. N. Dubrovsky

F1163. Due to the low friction coefficient, the automat cannot move on ice with rooting exceeding in modulus $a=0,5$ m/$c^2$. According to the conditions of the execution, the driver needs to get from point $A$ in the shortest time to point $B$, located on a straight line perpendicular to the direction of the automatic speed (Fig. 1). What is the minimum possible time if the distance is $AB=375$ m and the lowest speed is $v = 10$ m/$c$? What trajectory should the automatic machine move in this case? Answer similar questions for the case when the filish is at the point $C$, $BC=200$ m.

Let us move to a reference system in which the automaton accumulates at the initial moment of time, and the point $B$ moves with a constant speed $v$. In this reference system, the automaton for the fastest meeting with the point $B$ is very long and must move along a certain straight line with a constant rooting equal to $a$. The direction of the straight line is determined by the fact that at some points $D$ a collision must occur. For triangle $ABD$ (Fig. 2), denoting $AB=b$, we have

$$b^2 + (vt)^2 = \left(\frac{at^2}{2}\right)^2.$$

Solving this equation, we find

$$t = \sqrt{\frac{2v^2}{a^2} + \sqrt{\left(\frac{2v^2}{a^2}\right)^2 + \frac{4b^2}{a^2}}} = 50 \text{ с.}$$

Since the optimal movement of the automaton is uniformly accelerated, its trajectory in the reference frame associated with the earth will be a parabola.

The strategy for meeting point $C$ as quickly as possible is similar to that discussed above. However, to find the time until the meeting at point $E$ (Fig. 3), we will have to solve the equation of a general quadrilateral

$$b^2 + (vt+c)^2 = \left(\frac{at^2}{2}\right)^2,$$

⟦folio 36⟧

where $c = BC$, or

$$t = \sqrt[4]{\frac{4}{a^2} \left(b^2 + (vt + c)^2\right)}.$$

This equation can be solved approximately using the integration method, the essence of which is as follows. Suppose we need to solve an equation of the form $f(t) = t$. As an approximate value, we take some value $t = t_0$ and compose the sequence

$$t_1 = f(t_0), \ t_2 = f(t_1), \ ..., \ t_n = f(t_{n-1}).$$

If this sequence has limit $S$ and the function $f(t)$ is continuous at the point $S$, then $S$ is the root of equation (*).

In our case, under the condition $t_0 = 0$, the sequence will look like

$$t_1 = f(t_0), \ t_2 = f(t_1), \ ...$$

$$..., \ t_n = \sqrt[4]{\frac{4}{a^2} \left(b^2 + (vt_{n-1} + c)^2\right)}.$$

Substituting numerical values, we arrive at the result

$$t \approx 59,2 \text{ с.}$$

Moreover, as a more detailed study of the sequence shows, at $n = 4$ one percent accuracy is sufficient, and every two additional steps (calculating the two subsequent terms of the sequence) improve the accuracy tenfold.

For the case of an arbitrary location of the physical point when solving equation (*), where $c = BC$ can be preceded by both a plus and a minus sign, a certain caution must be observed due to the possible inconsistency of the solution and the correct choice of the zeroth approximation of iteration.

And one more note. Moving along a parabola with a constant acceleration vector will, of course, require considerable speed from the driver.

A. N. Korotkov, E. N. Yunosov

F1164. Built-in structures using so-called pre-directed reinforced concrete structures. The production of such a beam is carried out as follows. A steel rod with length $l_1$ is stretched to length $l_2$, after which it is filled with liquid concrete. After the concrete has hardened, the rod is freed from tension

Let the length of the reinforced concrete beam after the tensile device is removed from the steel rod be equal to $l_0$ ($l_1 < l_0 < l_2$). In this case, the rod grows by values ​​$\Delta l_1 = l_0 - l_1$, and the hardened concrete slope by values ​​$\Delta l_2 = l_2 - l_0$. According to Hooke's law, for such a deformation of the rod, a force is required

$$F_1 = E_1 S_1 \Delta l_1 / l_1,$$

where $S_1$ is its cross-sectional area, $E_1$ is the Young’s modulus of the steel. Likewise, concrete requires force to deform.

$$F_2 = E_2 S_2 \Delta l_2 / l_2,$$

where $S_2$ and $E_2$ are the cross-sectional area and modulus

⟦folio 37⟧

Vacation efforts. Find the length of the educational reinforced concrete beam and its Young model. The cross-sectional areas of the rod and beam and Young's model of steel and concrete are considered known. How is pre-directed reinforced concrete better than plain reinforced concrete?

Young concrete block (without rod). Naturally, in the absence of external forces, the force of concrete rolling is balanced by the tension of the rod:

$$F_1 = F_2.$$

From here, using the previous expressions, we find the required length of the reinforced concrete beam

$$l_0 = \frac{E_2 S_2 + E_1 S_1}{E_1 S_1/l_1 + E_2 S_2/l_2}.$$

To determine the Young model $E_0$ of a reinforced concrete beam, we calculate the force that is necessary to distance the beam by values ​​$\Delta l_0$. With such deformation, the rod will grow by $\Delta l_1 + \Delta l_0$ (compared to the original length $l_1$), and the tensile force will be equal to

$$F'_1 = E_1 S_1 (\Delta l_0 + \Delta l_1)/l_1.$$

The concrete beam will slope by $\Delta l_2 - \Delta l_0$ (compared to its original length $l_2$), and the force of its slope will be equal to

$$F'_2 = E_2 S_2 (\Delta l_2 - \Delta l_0)/l_2.$$

(If $\Delta l_0 > \Delta l_2$, then $F'_2$ will be the tensile force rather than the rolling force of the concrete.) The resultant force required to stretch a reinforced concrete beam is

$$F_0 = F'_1 - F'_2 = E_1 S_1 (\Delta l_0 + \Delta l_1)/l_1 - E_2 S_2 (\Delta l_2 - \Delta l_0)/l_2,$$

or, given the equality $E_1 S_1 \Delta l_1/l_1 = E_2 S_2 \Delta l_2/l_2$, -

$$F_0 = E_1 S_1 \Delta l_0/l_1 + E_2 S_2 \Delta l_0/l_2.$$

Let's take $\Delta l_0$ out of brackets, multiply and divide by $S_2/l_0$ (counting $S_1 \ll S_2$) and get

$$F_0 = \left( (E_1 S_1/l_1 + E_2 S_2/l_2) \frac{l_0}{S_2} \right) S_2 \frac{\Delta l_0}{l_0}.$$

It is easy to see that the expression in the outer brackets is the Young model of the reinforced concrete beam $E_0$. Using the formula for $l_0$, we find

$$E_0 = E_2 + \frac{S_1}{S_2} E_1.$$

It is interesting to note that the same Young model will be found for a beam made without pre-tensioning the rod. The advantage of pre-guided reinforced concrete is that the concrete base in such structures experiences slope deformation, even if the structure itself as a whole experiences tensile deformation. Since the rolling strength of concrete is significantly greater than its tensile strength, the likelihood of cracks forming in the concrete base is significantly reduced.

V. I. Klyachin

F1165. From an infinite square conductive grid with resistance

Let's start with points $A$ and $B$. Let's redraw the diagram as shown in Fig. 2. Connect two identical point sources to points $A$ and $B$ of the diagram (Fig. 3)

⟦folio 38⟧

For each edge r, part of the conductors was removed - as shown in figure 1. Find the resistance between points A and B, B and C, A and C.

Fig. 1.
Fig. 2.
Fig. 3.
Fig. 4.
Fig. 5.

F1166. In the circuit shown in figure, the keys $K_1$ are closed (with the key $K_2$ closed), and at the moment when the charge on the capacitor $C_1$ becomes maximum, the keys $K_2$ are opened. Find the maximum value of two identical resistors with resistance $R \gg r$ (we will neglect the internal resistance of the sources). Let's put $r=1$ Ohm and select the values ​​of $E$ and $R$ so that $E/R=1$ A.

Let us first consider connecting only one source to point A and obtain the following branching circuit to node A point $I_1=\frac{E}{(R+r_x)} \approx 1$ A (here $r_x$ is the desired resistance between points A and B) - figure 4. Then leaving only the source with EMF $E_2$, we obtain a signal when current $I_2=\frac{E}{(R+r_x)} \approx 1$ A flows from node B. This current flows from three nodes closest to B and goes through the source to “infinity” (Fig. 5).

Now let's connect both sources to points A and B. Then from the principle of superposition and from the condition $R \gg r$ we obtain that the current $I_{AB}=(I_1+I_2)/3=2/3$ A will flow through the conductor $AB$ and the voltage on the conductor will be equal

$$U_{AB}=\frac{2}{3}A \cdot 1\text{ Ом}=\frac{2}{3}\text{ В}.$$

On the other hand, a total voltage $2E$ is applied to the circuit and a current $I \approx 2E/(2R)=1$ A flows into it. Therefore,

$$R_{AB}=\frac{U_{AB}}{I}=\frac{2}{3}\text{ Ом}.$$

The case when an external voltage is applied to points A and C is similar to the previous one:

$$R_{AC}=\frac{2}{3}\text{ Ом}.$$

We just have to find the resistance between points B and C. Connecting only one source to point B gives that current $I_1/3$ will flow along edge $AB$, and current $I_1/6$ will flow along edge $BC$. Connecting then to node C the second source, taking into account the messages of sigmetry and the principle of superposition, gives

$$U_{BC}=1\text{ Ом} \left( \frac{1}{3}A+\frac{1}{6}A \right)+1\text{ Ом} \left( \frac{1}{3}A+\frac{1}{6}A \right)=1\text{ В}$$

And

$$R_{BC}=\frac{U_{BC}}{I}=1\text{ Ом}.$$

S. S. Krotov

After the switch $K_1$ is closed, the capacitor $C_1$ is charged, and the charge of the capacitor $C_2$ remains equal to zero, since $C_2$ is short-circuited.

At the moment when the charge $q_1$ of the capacitor $C_1$ becomes maximum, the current in the circuit turns out to be zero. Let us find the magnitude of the charge $q_{1\text{max}}$, based on energy messages: the work of the current source is equal to the energy of the electric field of the capacitor $C_1$ -

⟦folio 39⟧

nal charge of the capacitor $C_2$. The parameters of the circuit elements indicated on figure are considered given.

$$q_{1 \max} U_0 = \frac{q_1^2 \max}{2 C_1},$$

where

$$q_{1 \max} = 2 C_1 U_0.$$

After opening the key $K_2$, this charge becomes “locked” on the capacitor plates $C_1$ and $C_2$ shorted together. Suppose that some time after opening, a charge $q_2$ appears on the capacitor $C_2$. If we assume that the charge of capacitor $C_1$ continued to increase, then its charge $q_1$ will be related to the charge $q_2$ by matching

$$q_1 = q_{1 \max} + q_2.$$

To find the maximum charge of the capacitor $C_2$, we again use the law of conservation of energy: the work of the battery after opening the switch $K_2$ is equal to the increment in the energy of the capacitors -

$$q_{2 \max} U_0 = \frac{(q_{1 \max} + q_{2 \max})^2}{2 C_1} + \frac{q_2^2 \max}{2 C_2} - \frac{q_1^2 \max}{2 C_1},$$

where

$$q_{2 \max} = - \frac{2 C_1 C_2 U_0}{C_1 + C_2}.$$

The sign “—” means that our assumption regarding the increase in charge $q_1$ is not correct, the charge on the capacitor $C_1$ will decrease. In this case, there will be “—” on the top plate of the capacitor $C_2$, and “+” on the bottom plate.

V. V. Mozhaev

F1167. A long train, driven by inertia, climbs a hill with an angle of $\alpha$. When the composition is completely left, half of its length is on the slide (see figure). How long did it take from the start of the climb to the stop? Train length $L$, residence time.

Let the mass of the entire train be $M$, and the length of the part of the train that was squeezed onto the hill be $x$. Then the mass of this part is $Mx/L$.

Let's select the coordinate axis $X$ with its origin at the base of the slide and direct it up the slide. Let us write down Newton’s second law for the composition in projections onto the selected axis:

$$Ma = - \frac{Mx g \sin \alpha}{L},$$

or, considering that $a = x''$,

$$x'' = - \frac{g \sin \alpha}{L} x.$$

This equation is nothing more than the equation of harmonic oscillations with a period of $T = 2\pi \sqrt{L/(g \sin \alpha)}$. The time $t$ for the train to move before stopping is equal to a quarter of the oscillation period, i.e.

$$t = \frac{T}{4} = \frac{\pi}{2} \sqrt{\frac{L}{g \sin \alpha}}.$$

A. I. Buzdin
