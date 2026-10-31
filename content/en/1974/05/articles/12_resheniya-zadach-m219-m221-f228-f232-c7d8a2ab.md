---
id: 1974-5-resheniya-zadach-m219-m221-f228-f232-c7d8a2ab
issue: kvant_1974_5
year: 1974
number: "5"
title: Solutions to problems M219—M221; F228—F232
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 52
page_last: 58
page_labels: 50-56
tag: 3RI2
lang: en
source: kvant_digital
extraction: vision
content_sha256: fa68ccaf120aebe71baa97de237679ebeab1100b7d815c45010419916cbf8f09
prompt_sha256: draft-1
translated_from: content/ru/1974/05/articles/12_resheniya-zadach-m219-m221-f228-f232-c7d8a2ab.md
source_content_sha256: f2d28bf66a49b8179903408db0e54b224cfd60bd308f5372cc14f085350f57a5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

Problem solutions

M219—M221; F228—F232

M219. There are 4 points given in space that do not lie in the same plane. How many different paralleled lines are there for which these points serve as vertices?

First, let's solve a similar plane problem. Given three points that do not lie on the same line. How many different paralleled lines are there for which these points serve as vertices?

This problem is much simpler than the spatial one. The answer is: 3 parallelograms.

You can verify this, for example, like this. Suppose that a parallelogram has three given points as vertices. Then one of them (C on Fig. 1) plays a special role: it is connected to two other points by the sides of the parallelogram (and those two are a diagonal). It is clear that any of the three given points can be “assigned” to such a point C, after which the parallelogram is constructed in a unique way (Fig. 2).

Let us now move on to the spatial problem. The most remarkable thing about it is the answer: 29 parallelopeds.

1st solution. First, as expected in a “construction” problem, let’s do a little analysis, that is, imagine that a paralleloped (having four given points as vertices) has been built.

Of the eight vertices of a paralleloped, four vertices that do not lie on the same face can be identified in four different ways *), as shown in Figures 3, a, b, c, 2. To distinguish these methods, it is enough, for example, to look

*) The words “essentially different” can be given the following precise meaning: two 4-subsets of vertices are considered essentially different if it is impossible to map a set of eight vertices onto itself so that the vertices of one face go into the vertices of one face, and a subset of four vertices goes into one another. It was possible to continue the solution in this language, but we chose a more clear way of presentation.

⟦folio 51⟧

Fig. 4.

connected to the point $B''$ - and both rigid faces, and thus the parallelepid, will be uniquely defined. In total, in this case, 12 parallelepids can be built.

$\theta$) Here is one rigid face containing three of the four points, and the quadruple point $C'$ should obviously be the opposite vertex of the parallelepid with respect to point $C$ - the “main” vertex of the rigid face. You can assign any of the four points to the role $C$, and any of the other three to the role $C'$. After this, the rigid edge, and then the entire parallelepid, is constructed uniquely. So, we get 12 more parallelepids.

$\varepsilon$) There are no rigid faces, and therefore, as is easy to prove, each face must have two selected points that do not lie on the same edge. When a set of four points is partitioned into two subsets of two points each, it is necessary to construct three pairs of intersecting straight lines (diagonals of opposite faces of the parallelepid), and therefore three pairs of planes parallel to each other, the intersection of which produces the desired parallelepid. Here there is only one (this is not surprising, since the roles of all points are exactly the same).

Adding, we get the answer: $4 + 12 + 12 + 1 = 29$. On figure 4 all 29 pieces are reproduced.

Let us now present the second solution to the problem (then the answer turns out completely differently, which already guarantees against error), but let us return for a moment to the plane problem.

Answer “3” can also be justified this way. Note that the “midlines” of the future parallelogram (straight lines, parallel sides and located in the middle between them) are straight lines equidistant from all three given points. Having two such “averages”

⟦folio 52⟧

Fig. 5.

are straight, it is easy to construct a parallelogram - just draw parallel lines through these points. There are three lines in total that are equidistant from the three given points (they go along the middle lines of the triangle with the vertices at the given points). You can select two of them in three ways (Fig. 5).

2nd solution. The three “middle planes” of the desired parallelopped (planes equidistant from all eight of its vertices) must satisfy the following conditions:

1° each of them is equidistant from these four points;

2° all three planes intersect at one point.

Conversely, if we avoid specifying a triple of planes that satisfy the conditions 1° and 2°, then the parallelopped in which they serve as “middle” is determined uniquely: it is enough to identify through four points all the different planes parallel to each plane from this triple, and the parallelopped is ready.

First, let's find out: how many planes $p$ are there that are equidistant from the four given points $K, L, M, N$ (not lying in the same plane)? Let's prove that it's seven. Indeed, it is enough to indicate which points lie on one side of $p$ and which ones lie on the other. It is possible that there will be three points on one side and one on the other (four planes), and it is possible that there will be two points on both sides (three planes).

It is easy to see how to construct all these planes: they all intersect the edges of the KLMN tetrahedron in the middles, and its faces along the midlines (four planes intersect the tetrahedron along a triangle, and three along a parallelogram, Fig. 6).

Three planes out of seven we can choose in $C_3^7 = \frac{7 \cdot 6 \cdot 5}{1 \cdot 2 \cdot 3} = 35$ ways. Each of these three satisfies the 1° condition; system to find out how many of these three are “bad”, not satisfying the 2° condition, that is, parallel to one straight line.

Fig. 6.

Using the fact that the line of intersection of each two of the seven planes either connects the midpoints of two opposite edges of the KLMN tetrahedron (there are three such cases in it - the intersection of two planes), or is parallel to one of the edges of the tetrahedron (and three of the seven planes are parallel to each edge), we obtain that there are as many “bad” tracks as there are six edges in the tetrahedron.

Subtracting, we get the answer: 35 - 6 = 29.

N. B. Vasiliev

M220. The king of the general chessboard is $8 \times 8$, raising on each pole once and returning with the last move to the original square. (The king follows the general rules: in one move he can move horizontally, vertically or diagonally to any adjacent square.) When we drew his path, sequentially connecting the valuable fields that he passes through, it turned out to be a closed broken line without self-intersection. What is the shortest and greatest length it can have? (The side of the cell is equal to one).

The king made 64 moves. Since each square of the move is equal to either one or $\sqrt{2}$, then the length of the entire path is set to be at least 64. (A path of length 64 actually exists - see the example at figure 7.) Let us now show that the length of the king’s path cannot be greater than $28 + 36 \sqrt{2}$. To do this, it is enough to show that the king’s path contains at least 28 “direct” moves. The distance is two adjacent king exits to the border of the field. It is easy to say that these field boundaries must be connected, otherwise the king's path turns out to be self-intersecting (see Fig. 8; construct a line to prove this statement). Since the color of these fields differs, and when moving diagonally the color does not change, then there must be a “direct” path between the two connecting exits to the border. Since there are 28 boundary fields, there are also 28 exits to the boundary, and therefore, there are indeed at least 28 straight moves. From the example of the king’s path given in

⟦folio 53⟧

Fig. 7. Fig. 8. Fig. 9.

figure 9, it follows that you can get by with exactly 28 “direct” moves.

**M221.** They put an ink on the paper. For each point of the blot, the shortest distance from the border of the blot, as well as the greatest distance from the border of the blot, was determined. Among all the smallest distances, we chose the largest $r_0$, and among the largest samples, the smallest $R_0$. What shape does the blot have if $r_0 = R_0$?

Let $A$ be the point of the blot, the shortest distance from which to the border of the blot is $r_0$. Then a circle of radius $r_0$ with center at point $A$ is contained inside the blot (if this circle were not completely contained within the blot, then some point on the border of the blot would be inside the circle, and the distance to it from point $A$ would be less than $r_0$, which contradicts the choice $r_0$ - see Fig. 10).

Similarly, if $B$ is a point of the blot, the greatest distance from which to the border of the blot is $R_0$, then the entire blot is contained in a circle of radius $R_0$ centered at point $B$ (Fig. 10).

So, the first circle constructed is contained in the blot, and the blot, in turn, is contained in the second circle. But by condition $r_0 = R_0 = \rho$, it follows that the circles coincide; We know that points $A$ and $B$ coincide, and the blot has the shape of a circle with the center at point $A (= B)$ of the r section.

**G. A. Galperin**

**F228.** At the end of the doxy of length $L$ and mass $M$ there is a short block of mass $m$ (Fig. 11). The board can slide without any problems along the horizontal plane. The coefficient of claim for the block sliding on the doxie surface is $m$. What speed $v_0$ must be communicated to the doxa so that it slips out of the nod block?

Fig. 11.

Since the doxa is only allowed to slide by the lump, then at the initial moment the block will slide relative to the plane, and the doxa has a speed of $v_0$. In the horizon direction, only the sliding claims forces $F_{tr.}$ and $F_{tr.6}$ act on the block and doxa. Between them (Fig. 12). These forces are equal in absolute value $\mu m g$ and impart accelerations to the block and doxa equal to the corresponding

$$a_6 = \frac{\mu m g}{m} = \mu g,$$

$$a_7 = -\frac{\mu m g}{M} = -\mu \frac{m}{M} g.$$

Thus, the speed of the bar will increase over time, while the speed of the doxie will decrease.

If the initial speed of the doxie does not start, then some time after the start of movement the speeds of the bar and doxie will become equal, after which the bar and doxie will move.

⟦folio 54⟧

Fig. 12.

move as one whole, that is, at the same speed. If the difference between the variable of the block and the board at this moment is equal to the length of the block (Fig. 12), then the block will subsequently move, being on the edge of the board. The block will slide off the board if this difference in the variable is greater than $L$.

Let's find the speed $v$ of the joint motion of the block and the board. Since external forces do not act on the board-bar system in the horizontal direction, the momentum of this system does not change over time. Therefore $Mv_0 + m \cdot 0 = (M + m)v$, from where

$$v = \frac{M}{M + m} v_0.$$

To find the variable value of the board and the block, we will use a formula that connects the speeds of the body $v_1$ and $v_2$ at some moments of time with its acceleration $a$ and change $s$ during the time between these moments:

$$v_2^2 - v_1^2 = 2as.$$

The initial speed of the block is $v_1 = 0$, and at the moment when the speeds of the block and the board become equal, $v_2 = v$. Therefore, the magnitude of the change in the block at this moment is equal to

$$s_0 = \frac{v^2}{2a_0} = \frac{M^2v_0^2}{2(M + m)^2\mu g}.$$

Similarly, we find the magnitude of the board change:

$$s_1 = \frac{v^2 - v_0^2}{2a_1} = \frac{M(m + 2M)v_0^2}{2\mu g(M + m)^2}.$$

The block will slide off the board if

$$s_2 - s_0 > L,$$

or

$$\frac{M(m + 2M)}{2\mu g(M + m)^2}v_0^2 - \frac{M^2}{2(M + m)^2\mu g}v_0^2 > L.$$

From here we find what $v_0$ should be:

$$v_0 > \sqrt{2\mu gL(1 + \frac{m}{M})}.$$

F229. A homogeneous monstrous washer lying on a horizontal rough surface has free mechanical movement with an angular velocity of $\omega_0$ and a translational velocity of $v_0$ (Fig. 13). What trajectory does the center of the puck follow? In which case will the puck travel a longer distance to stop: at $\omega_0 = 0$ or at $\omega_0 \neq 0$ ($v_0$ is the same in general cases)?

To find the trajectory of the center of the puck, it is necessary to find out what forces are acting on the puck. Since the washer is on a rough surface, it is obvious that the only force that acts on the washer in the horizontal plane is the friction force, which is always directed opposite to the possible movement of the body. Each point of the puck simultaneously participates in two movements: translational and medical. Therefore, the magnitude and direction of the resulting velocity for each point of the arch. This means that the friction forces acting on different parts of the washer are different. Therefore, to determine the resulting friction force, we will divide the washer into elementary sections and consider the forces acting on them.

Let us select two identical sections of the washer 1 and 2, located symmetrically relative to the diameter of the washer, perpendicular to the direction of speed $v_0$ (Fig. 14). These areas are subject to the same abscissa friction value $|F_1| = |F_2| = kmg$ ($m$ is the mass of the part, $k$ is the friction coefficient). the directions of the friction forces $F_1$ and $F_2$ are different. Let's find these directions.

The speed of each of the sections is equal to the sum of the speeds of the translational movement of the center of the washer $v_0$ and the linear speed of the medical motion of this section relative to the center of the washer $u$, perpendicular to the radius $R$ drawn to this section from the center of the washer.

⟦folio 55⟧

Since $R_1 = R_2$, then $|\mathbf{u}_1| = |\mathbf{u}_2| = \omega^2 R$, that is, the linear velocities are equal in magnitude. In addition, the angles that the velocities $\mathbf{u}_1$ and $\mathbf{u}_2$ make with the direction of the vector $\mathbf{v}_0$ are the same. This means that the velocities $\mathbf{v}_1$ and $\mathbf{v}_2$ of the 1st and 2nd points involved are equal in abscylotic magnitude, make the same angles $\beta$ with the direction of the vector $\mathbf{v}_0$, but are deviated from the direction of the vector $\mathbf{v}_0$ in different directions. The strong trines are $\mathbf{F}_1$ and $\mathbf{F}_2$ and the directions are opposite to the vectors $\mathbf{v}_1$ and $\mathbf{v}_2$ respectively. Their vertical components are obviously equal in abscylotic value, but directed in opposite directions, so their sum is zero. Consequently, the total trinium force acting on the symmetrical elementary sections of the washer is equal to the sum of the horizontal components and the direction is opposite to the vector $\mathbf{v}_0$.

Considering other similar pairs of elements, we will come to the conclusion that the resulting trinium force acting on the entire disk is also directed opposite to the speed $\mathbf{v}_0$. This force can change the abscilottic value of the speed of translational motion of the center of the washer, but cannot change its direction (the acceleration imparted to the washer by the trinic force is directed opposite to the speed of the center of the washer). Consequently, the trajectory of the puck will be a straight line.

If at the initial moment $\omega_0 = 0$, then all the trinic forces acting on the elementary sections of the washer are directed equally, that is, against the speed $\mathbf{v}_0$. Therefore, the resulting trinium force, equal to their sum, is greater in magnitude than in the previous case. The magnitude of the acceleration will also be large.

Therefore, let the distance traveled by the puck before stopping be less in the case when $\omega_0 = 0$, and more when $\omega_0 \neq 0$.

F230. On a system consisting of two balls of mass $m$ connected by a spring, showing an overhead horizontal surface, we fly into a ball of mass $M$ (Fig. 15) from the left. By searching for any abscilotically elastic blow. Most empirically mass ratio

Fig. 14.

$$\gamma = \frac{m}{M}, \text{ при котором уdar произойдет раз.}$$

After the collision of balls 1 and 2, ball 1 will move forward with a certain constant speed. The center of mass of the system of balls 2 and 3 will also move translationally at a constant speed, and, in addition, balls 2 and 3 will wheel relative to their center of mass. In order to answer the question whether balls 1 and 2 will collide a second time, you need to find the dependence of the coordinates of these balls on time and see if these coordinates can coincide.

Let's assume that the blow is instantaneous. In this case, it will occur in the same way as the collision of two free balls not connected with other bodies, and you can use the law of conservation of momentum and energy *). Let us denote the speed of ball 1 before the collision as $v_0$, its speed after the collision as $v_1$, and the speed of ball 2 after the collision as $v_2$. Then we can write

$$Mv_0 = Mv_1 + mv_2,$$

$$\frac{Mv_0^2}{2} = \frac{Mv_1^2}{2} + \frac{mv_2^2}{2}.$$

From these equations it is not difficult to find $v_1$ and $v_2$:

$$v_1 = v_0 \frac{M - m}{M + m} = v_0 \frac{1 - \gamma}{1 + \gamma},$$

$$v_2 = v_0 \frac{2M}{M + m} = v_0 \frac{2}{1 + \gamma}.$$

After the collision of the first ball, it will move uniformly, but with speed

$$v_{\text{ц}} = \frac{v_2}{2} = v_0 \frac{1}{1 + \gamma}$$

(since balls 2 and 3 are the same). This means that the coordinate of the center of mass changes with time according to the formula

*) The impact time $t$ must be such that the mixture of ball 2 and the deformation of the spring can be ignored. To do this, the following inequality must be satisfied: $t \ll T$, where $T$ is the period of wheeling of ball 2 relative to the center of mass of balls 2 and 3.

⟦folio 56⟧

Let us consider the motion of balls 2 and 3 in a coordinate system associated with their center of mass. In this system, at the initial moment, the balls move towards each other with speeds equal in abscylotic value, therefore, in the future, each of the balls will perform harmonious rotation (relative to the center of mass) according to the law:

$$x = A \sin \omega t.$$

If the stiffness of half the spring is designated $k$, then the frequency of these vibrations is $\omega = \sqrt{k/m}$. The amplitude of oscillations $A$ can be found using the law of conservation of energy. At the initial moment, the spring is not deformed, ball 2 has a speed of $\frac{v_2}{2}$ and an energy of $\frac{mv_0^2}{2(1+\gamma)^2}$. Let us equate this energy to the energy of the spring deformation of the spring at the moment when the deviation of the ball from the equilibrium position is maximum and is equal to the amplitude of oscillations $A$:

$$\frac{mv_0^2}{2(1+\gamma)^2} = \frac{kA^2}{2}.$$

From here we find $A$:

$$A = \sqrt{\frac{mv_0^2}{(1+\gamma)^2k}} = \frac{v_0}{(1+\gamma)\omega}.$$

Now we can write down the dependence of the coordinates of ball 2 on time in a coordinate system associated with the horizontal plane:

$$x_2 = v_0t + A \sin \omega t = v_0 \frac{1}{1+\gamma} t + \frac{v_0}{(1+\gamma)\omega} \sin \omega t.$$

Balls 1 and 2 will collide again if the equality $x_1 = x_2$ is possible, that is

$$v_0 t \frac{1-\gamma}{1+\gamma} = \frac{v_0 t}{1+\gamma} \left(1 + \frac{1}{\omega t} \sin \omega t\right),$$

Fig. 17.

or

$$\sin \omega t = -\gamma \omega t.$$

It is convenient to solve such equations graphically. Let's draw graphs for the right and left sides of the last equation as a function of $\varphi = \omega t$ (Fig. 16). Solutions of the equation are determined by the points of intersection of the straight line $y = \gamma \varphi$ and the sine wave $y = \sin \varphi$. Obviously, a solution exists if $\gamma \leq \gamma_1 \approx tg \gamma_1$. From figure it is clear that

$$\gamma_1 \approx \frac{1}{\left(\frac{3}{2} \pi\right)} \approx 0.21,$$

that is, the mass ratio is approximately 0.21.

F231. A charged metal ball of radius $R$ is cut into two parts along a plane located at a distance $h$ from the center (Fig. 17). Find the force with which these parts repel. Full chest of the ball $Q$.

Since the ball is metal, the load $Q$ will be distributed evenly over its surface, so in the future we will talk about a loaded sphere. In order to determine the force acting on the sides of the bottom, we will divide this part of the sphere into elementary parts and first find the force $F_i$ acting on one of such sections (Fig. 18):

$$F_i = qE,$$

where $q$ is the back section of the field created by the entire torso part of the sphere. Value $q = \frac{Qs_i}{4\pi R^2}$, where $s_i$ is the area of ​​the loaded area.

As is known, the direction of the field outside the sphere at its surface is equal to

$$E_c = \frac{1}{4\pi \varepsilon_0} \frac{Q}{R^2},$$

and the direction of the field inside the sphere is zero. From the principle of superposition it follows that the field both inside and outside the sphere consists of the field of a selected area of ​​the sphere and the field of the repulsive sphere. Let's count
