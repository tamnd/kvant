---
id: 1976-9-resheniya-zadach-m361-m363-f369-f372-452f2f48
issue: kvant_1976_9
year: 1976
number: "9"
title: Solutions to problems M361—M363; F369—F372
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 51
page_last: 56
page_labels: 49-54
tag: DQUO
lang: en
source: kvant_digital
extraction: vision
content_sha256: 547038ab82bf40679d6226567bac7428866784b87236aa85c497a3035bb29e9f
prompt_sha256: draft-1
translated_from: content/ru/1976/09/articles/15_resheniya-zadach-m361-m363-f369-f372-452f2f48.md
source_content_sha256: 32b65fd29a69bf10987f78d9b711611a293623f43823e21b9ee50e0a66bf7a65
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 49⟧

Problem solutions

M361. Two cerams to the next ceram. A rectangle of $m \times n$ cells is highlighted on checkered paper. Each person takes turns crossing out all the cells of some horizontal row - in lines. Note that after crossing out a column (row), the remaining cells can be considered located in a rectangle in which the number of columns (respectively, rows) is one less. From figure 1 it is clear that based on which particular column (or row) is crossed out, we can therefore assume that this is one of the outermost columns (or rows).

Let us show that if the numbers $m$ and $n$ of rows and columns in the original rectangle are of different parities, then if played correctly, the beginner wins.

The beginner's strategy is as follows: he crosses out a row or column so that he is left with a rectangle with an even number of rows and an even number of columns (since in the original rectangle the numbers of rows and columns had different parities, he can always do this). After any move of the second game, a smaller rectangle remains, in which again the numbers of columns and rows have different parities. The beginner again crosses out a row or column so that there remains a rectangle with an even number of rows and columns, etc. In the end, after the second move, the game is left with a rectangle with either one row or one column, by crossing which the beginner wins.

Note that if there is only one column (or row) in the initial rectangle, then the beginner, by crossing out this column (row), wins.

FROM the above reasoning it follows that if $m$ and $n$ have the same parity and neither of them is equal to one, then the second player wins, since the starter with any move left him with a rectangle in which the number of rows and columns has different parities.

A. Savin

Fig. 1.

M362. We feed a row of the convex quadrilateral $ABCD$ into three equal parts and connect the segments corresponding to the points on the interconnected rows. Prove that the “average” plush of the quadrilateral is 9 times smaller than the plush of the quadrilateral $ABCD$.

Fig. 2.

We will call the cells in the vertical row columns, and the cells in the horizontal row rows. Note that after crossing out a column (row), the remaining cells can be considered located in a rectangle in which the number of columns (respectively, rows) is one less. From figure 1 it is clear that based on which particular column (or row) is crossed out, we can therefore assume that this is one of the outermost columns (or rows).

Let us show that if the numbers $m$ and $n$ of rows and columns in the original rectangle are of different parities, then if played correctly, the beginner wins.

The beginner's strategy is as follows: he crosses out a row or column so that he is left with a rectangle with an even number of rows and an even number of columns (since in the original rectangle the numbers of rows and columns had different parities, he can always do this). After any move of the second game, a smaller rectangle remains, in which again the numbers of columns and rows have different parities. The beginner again crosses out a row or column so that there remains a rectangle with an even number of rows and columns, etc. In the end, after the second move, the game is left with a rectangle with either one row or one column, by crossing which the beginner wins.

Note that if there is only one column (or row) in the initial rectangle, then the beginner, by crossing out this column (row), wins.

FROM the above reasoning it follows that if $m$ and $n$ have the same parity and neither of them is equal to one, then the second player wins, since the starter with any move left him with a rectangle in which the number of rows and columns has different parities.

A. Savin

We will solve a more general problem - we will prove that if the sides $AB$ and $DC$ are divided into $m$, $BC$ and $AD$ - into $n$ equal parts ($m$ and $n$ are odd; Fig. 2), then the area of the central quadrilateral $ABCD$. I. Let us first prove that each of the segments connected by the rows of the quadrilateral $ABCD$ is divided into equal parts.

To do this, let us check the validity of this more general statement: if the points $K \in [AB], L \in [DC], M \in [AD], N \in [BC]$ are such that

$$\frac{|AK|}{|KB|} = \frac{|DL|}{|LC|} = \alpha, \frac{|AM|}{|MD|} = \frac{|BN|}{|NC|} = \beta,$$

we can intersect $P$ segments $KL$ and $MN$ and divide them in the same ratios

$$\frac{|MP|}{|PN|} = \alpha, \frac{|KP|}{|PL|} = \beta.$$

This is easy to verify using vectors, but we will use mechanical messages. Let us place at points $A, B, C$ and $D$ loads with masses $1, \alpha, \alpha\beta$ and $\beta$ corresponding

⟦folio 50⟧

but (Fig. 3) and we will find in two ways the center of gravity of these four loads. The center of gravity of loads $A$ (1) and $B$ ($\alpha$) lies at point $K$, weights $D$ ($\beta$) and $L$ ($\alpha\beta$) - at point $L$; This means that the center of gravity of all four weights lies at point $P'$, dividing the segment $KL$ in relation to $\frac{|KP'|}{|P'L|} = \frac{\beta + \alpha\beta}{1 + \alpha} = \beta$.

Similarly, combining the loads $A$ (1) and $D$ ($\beta$), $B$ ($\alpha$) and $C$ ($\alpha\beta$) into pairs, we prove that the center of gravity of these loads lies at the point $P'' \in [MN]$, for which $\frac{|MP''|}{|P''N|} = \alpha$.

Since the center of gravity belongs to both $KL$ and $MN$, it must coincide with the point of intersection of these segments: $P' = P'' = P$. Thus equalities (*) are proved.

II. Let us now prove the following statement: if the sides $AB$ and $CD$ of a convex quadrilateral $ABCD$ are divided into $k$ equal parts and connect the corresponding points (Fig. 4), then the areas of the resulting quadrilaterals $S_1$, $S_2, \dots, S_k$ constitute an arithmetic progression. Indeed, let us divide each quadrilateral diagonally into two triangles - red and blue, as shown in figure 5. The areas of the blue triangles form an arithmetic progression (their bases lying on $AB$ are congruent, and the heights form an arithmetic progression) and so do the areas of the red triangles. By adding two arithmetic progressions term by term, we always get an arithmetic progression.

III. Let's return to the original problem. Let us write in the cells of the table $m \times n$ the areas of the corresponding quadrilaterals on which $ABCD$ is divided. After this, the following statement is followed to such respect: if in a table of $m$ rows and $n$ columns (m and $n$ odd) numbers are written, in each column and in each row forming an arithmetic progression, then the number in the central cell is mn times less than the sum of all the numbers in the table.

To prove it, it is enough to note that the sum of the numbers in each row is $n$ times the average number of this row, and the sum of the numbers in the middle column is $m$ times the number in the central cell.

N. Vasiliev

M363. Two parabolas with parallel axes intersect at points $A_0$ and $B_0$. On the first of them we take the points $A_1$, $A_2$, ... $A_{2n}$; on the second there are points $B_1$, $B_2$, ... $B_{2n}$, so $A_0A_1 \parallel B_0B_1$, $A_1A_2 \parallel B_1B_2$, ... $A_{2n-1}A_{2n} \parallel B_{2n-1}B_{2n}$. Let us prove that $A_{2n}B_0 \parallel B_{2n}A_0$.

Let $y = px^2 + qx + r$ and $y = p'x^2 + q'x + r'$ be the equation of the given parabolas (Fig. 7). If $a_i, b_i$ are the abscissas of the point $A_i, B_i$, then the angular coefficient of the chord $A_iA_j$ of the first parabola is given by the formula

$$\frac{(pa_i^2 + qa_i + r) - (pa_j^2 + qa_j + r)}{a_i - a_j} = p(a_i + a_j) + q,$$

and, similarly, the angular coefficient of the chord $B_iB_j$ of the second parabola is given by the formula $p'(b_i + b_j) + q'$.

It follows from the condition that

$$p(a_0 + a_1) + q = p'(b_0 + b_1) + q',$$

$$p(a_1 + a_2) + q = p'(b_1 + b_2) + q',$$

$$p(a_{2n-1} + a_{2n}) + q = p'(b_{2n+1} + b_{2n}) + q'$$

Since $A_0B_0$ is a common chord of parabolas, then $p(a_0 + b_0) + q = p'(a_0 + b_0) + q'$. (*)

Multiplying the term-by-term equalities (1), (3), ..., (2n - 1) by -1 and adding them with the equalities (*), (2), (4), ..., (2n), we obtain $p(a_{2n} + b_0) + q = p'(b_{2n} + a_0) + q'$.

This means that $A_{2n}B_0 \parallel B_{2n}A_0$.

⟦folio 51⟧

F369. Three identical charged balls are held together by non-conducting threads forming a right triangle BAC (Fig. 7). Knot ABC is equal to α, BC = l. With what acceleration will the charges begin to move if the thread BC is cut? The charges of the balls are equal to q, the masses are m.

Consider the movement of balls in the XOY coordinate system; The X axis will be directed along category AC, the Y axis along category AB (see Fig. 7).

Since balls A and C are connected by a thread, they move along the X axis as a single unit. Let us write the equation of motion of the system of balls, projecting external forces acting on the system onto the X axis. These are the forces F₂ and F₁ - the forces of interaction between balls A and C with ball B. The force F₂ is directed perpendicular to the X axis, and its projection onto this axis is equal to 0. The projection of the force F₁ onto the X axis is equal to F₁ sin α. Hence,

$$F_1 \sin \alpha = 2 m a_x.$$

Hence the projections of the accelerations of balls A and C onto the X axis are equal

$$a_{Ax} = a_{Cx} = a_x = \frac{F_1}{2m} \sin \alpha = \frac{q^2}{8\pi\varepsilon_0 ml^2} \sin \alpha.$$

Similarly, for a system of balls A and B, also connected by a thread, we get

$$a_{Ay} = a_{By} = \frac{F_1}{2m} \cos \alpha = \frac{q^2}{8\pi\varepsilon_0 ml^2} \cos \alpha.$$

Then the absolute value of the acceleration of ball A is equal to

$$a_A = \sqrt{a_{Ax}^2 + a_{Ay}^2} = \frac{q^2}{8\pi\varepsilon_0 ml^2}.$$

Vector a_A makes an angle β with the X axis such that

$$tg\beta = \frac{a_{Ay}}{a_{Ax}} = ctg\alpha.$$

Now consider ball B. Let us write down the equation of motion for it along the X axis. The tension force of the thread AB and the force acting from the ball A are directed along the Y axis, and their projections on the X axis are equal to zero. Hence,

$$a_{Bx} = \frac{F_1}{m} \sin \alpha = \frac{q^2}{4\pi\varepsilon_0 ml^2} \sin \alpha.$$

Then the acceleration model of ball B

$$a_B = \sqrt{a_{Bx}^2 + a_{By}^2} = \frac{q^2}{8\pi\varepsilon_0 ml^2} \sqrt{1 + 3 \sin^2 \alpha}$$

And

$$tg\gamma = \frac{a_{By}}{a_{Bx}} = \frac{1}{2} ctg\alpha.$$

Carrying out similar reasoning for ball C, we obtain

$$a_{Cy} = \frac{F_1}{m} \cos \alpha = \frac{q^2}{4\pi\varepsilon_0 ml^2} \cos \alpha,$$

$$a_C = \sqrt{a_{Cy}^2 + a_{Cy}^2} = \frac{q^2}{4\pi\varepsilon_0 ml^2} \sqrt{1 + 3 \cos^2 \alpha},$$

$$tg\delta = \frac{a_{Cy}}{a_{Cy}} = 2 ctg\alpha.$$

F370. Tube, como diameter
the swarm is much smaller than its length,
rolled into a thorny branch of radius R.
The ring is placed vertically

⟦folio 52⟧

but the liquid is also filled, except for a small area near point A (Fig. 8), in which the upper path is located. The bubble begins to float. This is his speed at the moment when he passes point B. The length of the path is l. Neglect the pressure of water on the walls of the vessel.

Fig. 8.

F371. We shoot a cannonball of mass M = 200 kg with a cannonball of mass m = 20 kg at an angle α = 30° to the horizontal. The powder charge is r = 0.5 kg *), its temperature is q = 1000 kcal. At the moment the cannonball leaves the cannon, Baron Monhausen looks at it. Its mass is μ = 70 kg. How close will the cannonball with Monhausen fall with the same charge of gunpowder? How much do you need to increase the charge of gunpowder in order for Monhausen to hit the same place where the cannonballs hit before emodo? K. n. d. shot acceptance equal to η = 10%. Assume that the gun is on a flexible surface on which it can slide without friction.

* ) There was a typo in the conditions of the task (see «Kvant», 1975, No. 12).

or From the law of conservation of energy it follows that

$$\frac{mv^2}{2} = \Delta \Pi.$$

Here m is the mass of the liquid in the tube, mv²/2 is the change in the kinetic energy of the liquid, and ΔΠ is the change in its potential energy.

In order to find ΔΠ, consider a portion of liquid in the volume of air, path upper. Let's denote its mass by m₁. During the time the path passes from point A to point B (see Fig. 8), this portion of liquid moves from B to A, i.e., falls to a height of 2R. The position of the rest of the liquid mass does not change. Hence,

$$\Delta \Pi = m_1 g \cdot 2R.$$

Then

$$\frac{mv^2}{2} = 2 m_1 g R.$$

Hence, taking into account the next relation

$$\frac{m}{m_1} = \frac{2 \pi R - l}{l},$$

we'll finally get it

$$v = 2 \sqrt{\frac{g R i}{2 \pi R - l}}.$$

Since l ≪ 2πR,

$$v \approx \sqrt{\frac{2 g l}{\pi}}.$$

I. Slobodetsky

◆

First of all, let's find out what happens to the cannonball, the cannon and the smooth horizontal surface on which the cannon is located during the firing process. Strictly speaking, the shot lasts for some finite time, although very short.

If the gun-surface system is sufficiently “soft,” i.e., deformation of the system is possible, and the firing time is much less than the nature of the time of this deformation, then the phenomenon develops in two stages. First, the interaction of the core with the gun, moving in all directions, occurs, and then the interaction of the gun with the surface (which we are not interested in further). Obviously, in this case the angle of emission of the cannonball relative to the Earth is equal to the angle of inclination of the gun barrel α.

If the gun-surface system is absolutely “rigid”, then after firing the gun will not acquire a vertical component of speed (I hear the same thing when a gun, fixedly attached to the surface, shoots vertically upward) and will move only horizontally. In this case, the angle of emission of the cannonball β will no longer be equal to the angle of installation of the barrel α.

Let's consider the first case. Let us denote by V the speed of the gun after firing, and by v the speed of the cannonball relative to the Earth. Let's introduce the horizontal (OX) and vertical (OY) coordinate axes. Let us write down the law of conservation of momentum of the cannonball-cannon system for projection onto the horizontal and vertical axes:

$$mv_x = MV_x, \quad mv_y = MV_y.$$

From here

$$V_x = \frac{m}{M} v_x \quad и \quad V_y = \frac{m}{M} v_y.$$

⟦folio 53⟧

The law of conservation of energy, taking into account the efficiency coefficient η (we will consider the total mechanical energy of the system, i.e., the kinetic energy of the core and gun, to be useful), gives

$$\frac{m \left(v_x^2 + v_y^2\right)}{2} + \frac{M \left(V_x^2 + V_y^2\right)}{2} = \eta q r,$$

or, using correspondences (1),

$$v^2 = \frac{2 \eta q r}{m (1 + m / M)}.$$

Let us find the further subsequent (1),

$$L = \frac{v^2 \sin 2 \alpha}{g} = \frac{2 \eta q r \sin 2 \alpha}{mg (1 + m / M)}.$$

Now let Baron Munchausen surrender to the cannonball immediately after firing, and let the pillar do this elegantly (he is no stranger to this!), which does not change the direction of the cannonball’s speed: the baron’s initial speed is zero. Using the law of conservation of momentum once again, we find the velocity modulus $v_1$ of the baron–nucleus system:

$$mv = (m + \mu) v_1, \text{ и } v_1 = \frac{m}{m + \mu} v = \frac{v}{1 + \mu/m}.$$

The flight range $L_1$ of this system will be equal to

$$L_1 = \frac{v_1^2 \sin 2 \alpha}{g} = \frac{1}{(1 + \mu/m)^2} \frac{v^2 \sin 2 \alpha}{g} = L \frac{1}{(1 + \mu/m)^2}.$$

Consequently, the nucleus with Munchausen will fall close to

$$\Delta L = L - L_1 = L \left[ 1 - \frac{1}{(1 + \mu/m)^2} \right] \approx 1600 \text{ м}.$$

In order to get to the regime point, the baron must pour more gunpowder into the cannon. Terrier the speed of the core with the baron should become equal to $v$, and the new speed $v'$ of one core, according to expression (4), should increase accordingly:

$$v' = v (1 + \mu/m), \text{ и } v'^2 = v^2 (1 + \mu/m)^2.$$

Since the gunpowder charge is proportional to the square of the core velocity (expression (2)), the new gunpowder charge will be equal to

$$r' = r (1 + \mu/m)^2 \approx 10 \text{ кц}.$$

Thus, the powder charge must be increased by $r' - r \approx 9,5 \text{ кц}.$

We offer you a calculation for the case of a “rigid” gun system - the surface is carried out independently.

A. Smasenko

◆

We present two solutions to this problem—graphical and analytical.

Let us construct an image predmeta $MN$ in an arbitrary system of two thin positive linз (Fig. 9). To do this, consider the course of two rays emerging from the point $N$. Let one beam $(AB)$ go parallel to the optical axis of the system, and the second pass through the optical center of the first lens. The scale of the image will be determined by the point of intersection of these rays after passing through the lens system.

When the distance from predmeta to the system changes (object $M_1 N_1$ to figure 9), the path of the ray $AB$ does not change. Ouch-

⟦folio 54⟧

Fig. 9.

Fig. 10.

it can be seen that if the ray $AB$, after passing through the lens system, passes parallel to the optical axis, then the size of the image will not depend on the distance from the object to the system (Fig. 10). But this is possible only in the case when the ray $AB$, having passed through $\varGamma_1$, intersects the focus of the lens $\varGamma_2$, i.e. when the right focus of the first lens coincides with the left focus of the second lens. Thus,

$$l = F_1 + F_2.$$

This lens system is called telephone.

This result can also be arrived at analytically. The transverse magnification $\varGamma$ given by a thin lens is equal to

$$\varGamma = \frac{f}{d} = \frac{F}{d - F} = \frac{f - F}{F}.$$

Here $d$ is the distance from the object to the lens, $f$ is the distance from the lens to the image and $F$ is the focal length of the lens.

For a system of two lenses we can write

$$\varGamma = \varGamma_1 \varGamma_2 = \frac{f_1 - F_1}{F_1} \frac{F_2}{d_2 - F_2}.$$

But $d_2 = l - f_2$, therefore

$$\varGamma = \frac{F_2}{F_1} \frac{f_1 - F_1}{l - f_1 - F_2}.$$

From this it is clear that $\varGamma$ does not depend on $f_1$ (and therefore on $d_1$) if

$$\frac{f_1 - F_1}{l - f_1 - F_2} = \text{const}.$$

This is only possible when $l = F_1 + F_2$.

E. Kuznetsov
