---
id: 1976-7-resheniya-zadach-m351-m353-f358-f361-65335dbe
issue: kvant_1976_7
year: 1976
number: "7"
title: Solutions to problems M351—M353; F358—F361
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 37
page_labels: 30, 32, 33, 34, 35
tag: LM4D
lang: en
source: kvant_digital
extraction: vision
content_sha256: d997c1329eed8cb344154c6fe2b6fbaa736cd2fc726e3f39e28cace28f9d5474
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/10_resheniya-zadach-m351-m353-f358-f361-65335dbe.md
source_content_sha256: 1b8c1e3e2eff0323572b927a69deac39df45fa1b5a229f1f6adc22ec60a84ef1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

What is the maximum fraction of the satellite's mass that the mass of the interplanetary station can make up? (The potential energy of a body of mass $m$ in the gravitational field of a body of mass $M$ is equal to $U = -\gamma \frac{mM}{r}$). (10kl.)

F407. The driver of a passenger train moving at a speed of $v_1 = 108$ km/h noticed a freight train at a distance of $s_0 = 180$ m ahead moving in the same direction at a speed of $v_2 = 32,4$ km/h. The driver immediately turned on the brake, due to which the passenger train began to move with an acceleration of $a = -1,2$ m/sec². Is this acceleration enough to prevent the trains from colliding? (8 grades)

Problem solutions

M351—M353, F358—F361

M351. Reconstruct the sky-man if three points are offset on the plane: $O$ is the center of the circumcircle, $P$ is the center of gravity and $H$ is the base of one of the altitudes of the triangle.

Fig. 1.

Fig. 2.

Let $ABC$ be the desired triangle. Consider the congruent triangle $AB_1C$ (Fig. 1). Note that:
1) The line $BB_1$ is parallel to the straight line $AC$.
2) The point $B_1$ lies on the circle circumscribed around the triangle $ABC$.
3) Point $B$ lies on a circle with diameter $B_1H$.
4) The intersection point of the median $BM$ of the triangle $ABC$ with the segment $B_1H$ coincides with the point $P$ and divides the segment $B_1H$ in the ratio 2:1.

The first three properties are very similar. Let us prove the fourth property. Let the segments $BM$ and $B_1H$ intersect at some point $N$. Triangles $BB_1N$ and $MHN$ are obviously similar. Moreover, it is not difficult to establish that $|BB_1| = 2|MH|$. It follows that $|BN| = 2|NM|$ and $|B_1N| = 2|NH|$. And since $BM$ is the median of triangle $ABC$ and point $N$ divides it in the ratio 2:1, then this point is the center of gravity of triangle $ABC$, which is what needed to be proven.

Let us now move on to constructing the triangle $ABC$.

Use property 4), construct the point $B_1$. To do this, draw a straight line $PH$ and lay off a segment $PB_1$ from the point $P$, equal in length to 2|PH|.

Let's draw a circle with a center at point $O$ and radius $|OB_1|$. Based on property 2), this circle will be circumscribed around the triangle $ABC$. In particular, the point $B$ lies on it. Based on property 3), the point $B$ lies on a circle with diameter $|B_1H|$. Let's draw this circle. The intersection point of the constructed circles will be points $B$ and $B_1$ (Fig. 2).

The last points are $B$ and $B_1$ and draw through the point $H$ a straight line parallel to the segment $BB_1$. Based on property 1) on this line there are points $A$ and $C$, which are the points of its intersection with the already constructed circle circumscribed around the triangle $ABC$. Thus, the triangle $ABC$ is constructed. Show on your own that given the points $O$, $P$ and $H$ the triangle $ABC$ can be uniquely reconstructed.

A. Savin

⟦folio 32⟧

To prove point c) we will use the understandable scalar product of vectors: $a \cdot b = |a| \cdot |b| \cos(\alpha, \beta)$ (for its properties, see p. 21). From the definition it follows that the product of unit vectors is equal to the cosine of the angle between them. Let us denote by $e_a, e_b, e_c$ and $e_d$ the unit vectors having the same directions as the vectors $a, b, c$ and $d$, respectively. It's easy to see that

$$\cos \alpha + \cos \beta + \cos \gamma + \cos \phi + \cos \psi = -\frac{1}{2}((e_a + e_b + e_c + e_d) \cdot (e_a + e_b + e_c + e_d)) + 2 = -\frac{1}{2}k \cdot k + 2 = -\frac{|k|^2}{2} + 2,$$

(1)

where $k = e_a + e_b + e_c + e_d$.

From equality (1) it follows that the sum of the cosines of two angles of a tetrahedron does not exceed 2 and is equal to 2 if and only if $k = e_a + e_b + e_c + e_d = 0$. But since $a + b + c + d = 0$ is always, in the case of $k = 0$ we obtain that the lengths of the vectors $a, b, c$ and $d$ are equal, i.e., that all faces are of equal size. From the equal size of the faces of the tetrahedron it follows that they are congested (see solution problem M319, «Kvant», 1975, No. 12). Therefore, to complete the proof of the statement in point c), it remains to show that the sum of cosines written on the left side of equality (1) is positive, or that $|k| < 2$.

For convenience, we will assume that $|a| = 1, |b| \leq 1, |c| \leq 1$ and $|d| \leq 1$. Then $e_a = a, |k| = |a + b + c + d| + (e_b - b) + (e_c - c) + (e_d - d)| \leq |e_b - b| + |e_c - c| + |e_d - d| = 3 - |b| - |c| - |d| \leq 3 - |b + c + d| = 3 - |a| = 2$. Equality can only occur if all vectors $a, b, c$ and $d$ are collinear; since this is not the case, $|k| < 2$, and all statements in point c) are proven.

To prove point d) we note that the condition $|AB| + |CD| = |BC| + |DA|$ is necessary and sufficient for the existence of a ball touching the edges $AB, BC, CD$ and $DA$ (the proof of this fact is similar to the proof of the necessity of the sufficient condition $|AB| + |CD| = |BC| + |DA|$ so that a circle can be described around a flat quadrilateral $ABCD$). Let $O$ be the center of this ball (assume that the point $O$ is inside the tetrahedron). We have (Fig. 5):

$$(n.l. OAB, \hat{n.l. ABC}) = (n.l. OBC, \hat{n.l. ABC}),$$
$$(n.l. OAB, \hat{n.l. ABD}) = (n.l. OAD, \hat{n.l. ABD}),$$
$$(n.l. ODC, \hat{n.l. BCD}) = (n.l. OBC, \hat{n.l. BCD}),$$
$$(n.l. ODC, \hat{n.l. ACD}) = (n.l. OAD, \hat{n.l. ACD}).$$

Adding these equalities, we obtain statement d).

The case when the point $O$ is inside the tetrahedron is treated similarly.

I. Sharyshchin

F358. A non-hydrogen rod of length $l$ can stand against a vertical wall, forming an angle of at least $45^\circ$ with the floor. Friction coefficient

⟦folio 33⟧

the rod against the floor and the wall is 1/√3. At what height is the center of the soft rod?

Pris. 6.

Pris. 7.

they must prevent the rod from rotating counterclockwise. Therefore, these forces are directed as shown in figure 6. We assume that the gravitational force mg is applied at a point located at the desired height h.

In order for a body to be in equilibrium, it is necessary that the sum of the projections of all forces applied to the body in any direction and the sum of the moments of these forces relative to any fixed axis are equal to zero. Let us write down the equilibrium conditions for the projections of forces in the horizontal and vertical directions and for the moments of forces relative to the axis passing through the lower point of the rod perpendicular to the plane of the drawing:

$$N_2 - F_1 = 0,$$

$$F_2 + N_1 - mg = 0,$$

$$mgh \text{ ctg} \alpha - F_2 l \cos \alpha - N_2 l \sin \alpha = 0.$$

In the case of rest, the absolute values ​​of the dry friction forces are related to the absolute values ​​of the normal pressure forces by the following inequalities:

$$F_1 \leqslant \mu N_1, \quad F_2 \leqslant \mu N_2,$$

where $\mu = \frac{1}{\sqrt{3}}$ is the coefficient of friction of the rod on the floor and on the wall. For the limiting case when $\alpha = 45^\circ$,

$$F_1 = \mu N_1 \text{ и } F_2 = \mu N_2.$$

From equalities (1)–(4) we obtain

$$h = l \frac{\mu (\mu + tg \alpha) \sin \alpha}{\mu^2 + 1} = \frac{\sqrt{2} (1 + \sqrt{3})}{8} l \approx 0,48 l.$$

If $\mu = \sqrt{3}$, as was erroneously indicated in the conditions of the problem, then $h = (3 + \sqrt{3}) \sqrt{2} \frac{l}{8} \approx 0,84 l$, while the top end of the rod is located at a height $H = l \frac{\sqrt{2}}{2} \approx 0,71 l.$

This problem can be solved more easily if you use the “rule of three forces”. This rule is that when a body is in equilibrium, to which three forces lying in the same plane are applied, the line of action of these forces must intersect at one point. Otherwise, the total moment of these forces relative to any axis perpendicular to the mentioned plane will be different from zero, and the body will not be in equilibrium.

The three forces acting on the rod are the forces $Q_1 = F_1 + N_1, \quad Q_2 = F_2 + N_2$ and the gravitational force mg. Vector $Q_1$ is directed at an angle $\beta \leqslant \text{arctg} \mu$ to vector $N_1$ (Fig. 7). Vector $Q_2$ makes the same angle with vector $N_2$, i.e. vectors $Q_1$ and $Q_2$ are perpendicular to each other. In the limiting case $\beta = \text{arctg} \mu$. From figure 7 it is clear that $h = (AB - AC) \sin \alpha$. But $AC = AD / \cos \alpha = AO \cos \beta / \cos \alpha = AB \cos (\alpha + \beta) \cos \beta / \cos \alpha$. Then

$$h = AB \sin \alpha - AB \cos (\alpha + \beta) \cos \beta \text{tg} \alpha = l \sin \alpha \sin \beta (\sin \beta + \text{tg} \alpha \cos \beta).$$

Substituting $\alpha = 45^\circ$ and $\beta = \text{arctg} \mu = 30^\circ$, we get the same answer: $h = \frac{\sqrt{2} (1 + \sqrt{3})}{8} l \approx 0,48 l.$

⟦folio 34⟧

F359. In a cylindrical sauce under the piston there is saturated water vapor at a temperature of t = 20 °C. When changing the speed, a quantity of money Q = 20 kcal was released into the cylinder. How much work was done by external forces acting on the piston?

When the piston is slowly pushed into a cylindrical vessel, the saturated steam condenses. In order for the processes to be heat-thermic, the heat released during condensation must be removed. If initially the mass of water vapor in the vessel was $m_1$, and then $m_2$, then the amount of heat released

$$Q = L \left( m_1 - m_2 \right),$$

where $L = 539$ kcal/kg is the specific heat of water vaporization.

The value $L$ known from the tables was obtained experimentally, while the evaporation of water is carried out under conditions of constant pressure. Consequently, the consumption of heat is quantitatively equal to the sum of the increase in the internal (potential) energy of water and the work of expansion of water vapor. When steam condenses, the same amount of heat is also released.

The mass of steam in a vessel can be expressed in terms of its volume using the Mendeleev-Clapeyron equation:

$$m_1 = \frac{\rho \mu}{RT} V_1, \quad m_2 = \frac{\rho \mu}{RT} V_2.$$

Here $p$ is the saturated vapor pressure at temperature $T = 293 °C$ ($t = 20 °C$), $V_1$ and $V_2$ are the initial and subsequent volumes of the vessel, respectively, $\mu = 0,018$ kcal/mol is the molar mass of water vapor. Thus,

$$Q = \frac{\rho \mu L}{RT} \left( V_1 - V_2 \right).$$

The work done on steam by external forces is

$$A = p \left( V_1 - V_2 \right).$$

Solving the system of equations (1) and (2), we obtain

$$A = \frac{QRT}{L\mu} \approx 5020 \text{ дж.}$$

F360. To change the acceleration, a curved tube filled with water is used, in which there is an air bubble (Fig. 8). The tube is bent to suit the circumference. How is the position of the bubble related to the acceleration of the tube?

The Archimedes force is the result of solving the pressure forces applied to a body while in a liquid. Consequently, this force is always directed perpendicular to the surface of equal pressure, in the direction of decreased pressure. For surfaces of equal pressure, distance is a slightly different problem. Let a vessel of rectangular cross-section move with constant acceleration $a$ (Fig. 9). Let us show that in this case the surfaces of equal pressure, and hence the surface of the liquid in the vessel, are planes making an angle $\alpha = \arctg (a/g)$ with the horizon.

Let us select two very thin columns of liquid $AC$ and $CB$ in the liquid such that points $A$ and $B$ lie on a line inclined to the horizon at an angle $\alpha$. Let's compare the pressures at points $A$ and $B$. To do this, we write Newton’s second law for the column $AC$ in the projection onto the vertical axis, and for the column $CB$ – in the projection onto the horizontal axis:

$$p_C S - \rho gh S - p_A S = 0, \quad p_C S - p_B S = \rho lSa.$$

Here $p_A$, $p_B$, $p_C$ are pressures at their corresponding points, $S$ is the cross-sectional area of ​​each of the columns, $h$ is the height of column $AC$, $l$ is the length of column $CB$. Taking into account the fact that $tg \alpha = h/l = a/g$, we get

$$p_A = p_B.$$

⟦folio 35⟧

Thus, the Archimedes force, perpendicular to the surface of equal pressure, amounts to a vertical angle of $\alpha = \text{arctg} (a/g)$ (see Fig. 9).

In a curved tube, surfaces of equal pressure are located in the same way. Therefore, the bubble will move relative to the tube when the tangential component of the Archimedes force becomes equal to zero. The final position of the bubble is shown at figure 8, where

$$\alpha = \text{arctg} (a/g).$$

F361. A straight conductor of length $l$ and mass $m$ is suspended on two springs with stiffnesses $k$ in a horizontal uniform magnetic field with induction $B$ (Fig. 10). When the key K is closed, the capacitor $C$, charged to the difference placed $U$, is closed to the conductor and discharged. In this case, vibrations of the conductor arise. Determine the amplitude of these oscillations if the discharge time of the capacitor is much less than the oscillation period of the conductor.

When current $I$ flows through a conductor of length $l$, located in a magnetic field with induction $B$, a force $F = IBl$ acts on the conductor, directed in our case up or down. For a short period of time $\Delta t$, during which the current can be considered approximately constant, a force impulse acts on the conductor

$$F \Delta t = IBl \Delta t = Bl \Delta q,$$

where $\Delta q = I \Delta t$ is the charge flowing through the conductor in the same short period of time. A force impulse changes the amount of motion (impulse) of the conductor by the amount

$$\Delta p = m \Delta v = F \Delta t = Bl \Delta q.$$

During the entire time the current flows, i.e. during the discharge of the capacitor, the conductor acquires an impulse

$$p = mv = \sum m \Delta v = \sum Bl \Delta q = Blq.$$

Here $q = CU$ is the total charge passing through the cross section of the conductor (capacitor charge).

According to the conditions of the problem, the conductor receives the impulse $p$ in a short time, so that its mixing during this time can be neglected. The tension forces of the springs also remain unchanged and balance the gravitational force of the conductor. Consequently, during the initial current, the work of all forces except the electric force $F$ can be neglected. All subsequent movements are determined by the state of the system at the end of the current. This mode of motion is usually called ballistic (for example, a ballistic pendulum, a ballistic galvanometer, etc. are known).

The conductor on springs is a spring magnet. Considering its initial position to be an equilibrium position with zero potential energy, we write the law of conservation of energy for the initial state and the state of the largest deviation during oscillation with amplitude $A$:

$$\frac{mv^2}{2} = 2 \frac{kA^2}{2}.$$

This equation together with the equation

$$mv = BlCU$$

determines the amplitude of oscillations:

$$A = \frac{BlCU}{\sqrt{2km}}.$$

B. Bukhovce
