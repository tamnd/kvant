---
id: 1982-3-resheniya-zadach-m691-m695-f703-f707-0badb77b
issue: kvant_1982_3
year: 1982
number: "3"
title: Solutions to problems M691—M695; F703—F707
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 38
page_labels: 30, 32, 33, 34, 35, 36
tag: CICL
lang: en
source: kvant_digital
extraction: vision
content_sha256: c65f98b7d7503710e1757255ff97e7f3d189d33f779ae34378a73067385a3ee4
prompt_sha256: draft-1
translated_from: content/ru/1982/03/articles/10_resheniya-zadach-m691-m695-f703-f707-0badb77b.md
source_content_sha256: 9d9adbb6933c505774f85074d83e2815f99d74c90bda263b84074b4e29a4efba
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

P743. With what minimal velocity must a stone be thrown from height $h$ in order to clear a wall of height $H$ and thickness $l$?
O. Savchenko

P744. An apparatus in cosmic space consists of a rigid thin sphere of radius $R=2$ m, filled with gas, and also containing a sphere of radius $r=R/2$ filled with the same gas, but at higher pressure. The inner sphere is tangent to the inner surface of the apparatus. As the result of an accident, the inner sphere explodes. Find how the pressure inside the apparatus changes if the explosion displaces the apparatus by $a=0.5$ m. The mass of the shells of the spheres is negligible, the temperature assumed constant.

A. Buzdin

P745. A thermoisolated receptacle is divided into two compartments by a thermoisolated piston which moves without friction. The left compartment contains 1 mole of an ideal monoatomic gas, the other is vacuum. The piston is connected to the right wall of the receptacle by a spring (see figure Fig. 2, p. 28), whose length in unstressed state is equal to the length of the receptacle. Neglecting the heat capacity of the receptacle, piston and spring, determine the heat capacity of the system.

W. Kliachin

P746. An electric battery, working on $\beta$-radioactivity, is a metallic sphere, inside which a piece of a radioactive substance, isolated from the sphere, is placed (figure Fig. 3, p. 28). Every second $v$ atoms are decomposed. Assuming that the energy of the electrons appearing in the process of radioactive decomposition is uniformly distributed in the range between the minimal and maximum values ​​$W_{\min}$ and $W_{\max}$, find the electromotive force of the battery. What maximum current can such a battery yield? Up to what values ​​of the load’s resistance can this battery be considered a generator of current?

I. Vorobiev

P747. While their spaceship was rising to orbit, cosmonauts noticed a thin luminous layer (complete inner reflexion of light in atmosphere) at elevation $H_0$ above the earth surface. Using the graph (figure Fig. 4, p. 29) showing the dependence of the refraction coefficient $n$ on the distance $R$ from the center of the earth, how can one determine $H_0$?

O. Batischev

Problem solutions

M691—M695; F703—F707

M691. We will say that a number has property (K) if it discords the product of K consecutive natural numbers greater than 1. a) Find K such that some number N has both properties (K) and (K+2). b) Prove that a number that has both properties (2) and (4) does not exist.

a) The number $2 \cdot 3 \cdot 4=24$ has properties (1) and (3). Having added to both sides of the equality $2 \cdot 3 \cdot 4=24$ all natural numbers from 5 to 23, we get the number
$$2 \cdot 3 \cdot 4 \cdot 5 \cdot 6 \cdot \dots \cdot 23 = 5 \cdot 6 \cdot 7 \cdot 8 \cdot \dots \cdot 23 \cdot 24,$$
having properties (20) and (22). Of course, there are an infinite number of examples of this type: if $b=a(a+1)(a+2)$, then the number
$$a(a+1)(a+2) \dots (b-1) = (a+3) \dots (b-1)b$$
having properties (b-a-2) and (b-a).
There are examples of another kind: for example, the number
$$2 \cdot 3 \cdot 4 \cdot 5 \cdot 6 = 8 \cdot 9 \cdot 10$$
possessing properties (3) and (5). By adding the “processed” seven here, we get a number with properties (4) and (6):

⟦folio 32⟧

Fig. 4.

M693. Some have 1000 inhabitants. Every day, each of them shares the news they learned yesterday with all the properties. It is known that any news becomes known to all residents of the village. Prove that you can select 90 residents so that if you tell them all some news at the same time, then after 10 days it will become known to all residents of the village.

Fig. 1.

Let us associate each resident of the village with a certain point on the plane. Those points that correspond to residents familiar with each other are connected by a segment. The resulting picture is called a graph. The selected points are called vertices of the graph, and the segments connecting them are called edges.

That part of the problem condition, which requires that the news communicated to one resident of the village eventually becomes known to all its residents, corresponds to the fact that along the edges of our graph one can walk from any of its vertices to any other. Such a graph is called connected. A sequence of edges in a graph connecting two of its vertices, in which there are no repeated edges, is called a chain. If a chain begins and ends at the same vertex, it is called a cycle. figure 1 shows the chain connecting vertices A and B, as well as a cycle. A connected graph that does not contain cycles is called a tree. It really looks like a tree (Fig.2).

Let us call the distance between two vertices of the graph the number of edges in the shortest chain connecting these vertices. Note that if the graph is a tree, then any pair of its vertices is connected by only one chain.

The introduced concepts make it possible to simplify the recording of the solution to the problem. In new terms, the formulation can be rewritten as follows:

Prove that in a connected graph with 1000 vertices one can specify a set of 90 vertices such that for any vertex of the graph there is a vertex from this set whose distance is no more than 10.

Let X and Y be the two vertices of our graph that are at the greatest distance. If this distance is no more than 10, then the distance from any vertex of our graph to any other is no more than 10 - in this case, 90 vertices can be chosen arbitrarily.

Note that it is sufficient to solve our problem only for the case when the graph is a tree. Indeed, let our graph be not a tree; then it contains at least one cycle. If you remove any edge from the graph that accepts this cycle, the cycle will disappear, but the graph remains connected. Since there are only a finite number of cycles in the graph, by applying this operation several times, we will turn our graph into a tree. The set of 90 vertices of the resulting tree, which satisfies the conditions of the problem, is very convenient and will also be suitable for the first analogous graph, since adding new edges does not increase the distance between the vertices.

So, let us have a tree with 1000 vertices, X and Y are two vertices located at a maximum distance that is greater than 10. The distance of the chain connecting X and Y is: X—A1—A2—A3—...—A10—A11—...—Y. Let's take point A10 as the first point K1 of the desired set. If we collaborate between vertices A10 and A11, our tree will split into two trees. Note that the part containing vertex X contains at least 11 vertices.

Note that the distance from vertex A10 to each of the vertices of the part containing it is no more than 10 (if the distance to some vertex M is greater than 10, then the distance from M to Y will be greater than the distance from X to Y, which contradicts the fact that vertices X and Y are at the maximum distance).

The distance is now that part of the graph that contains vertex Y. This is a tree containing no more than 1000 - 11 = 989 vertices. Let's repeat the same operation with him. As a result

⟦folio 33⟧

Pis. 3.

M694. Each vertex of the cube contains a number. In one step, one is added to two numbers placed on one (any) edge. Is it possible to make all eight numbers equal to each other in a few steps like this, if numbers like figure 1 were initially placed? As in figure 2? As in figure 3?

Fig. 1.

Fig. 2.

Fig. 3.

Fig. 4.

We obtain another group of at least 11 vertices and middle ones—the point $K_2$ of the desired set, as well as a tree containing no more than 1000—2·11=978 vertices. After we perform this operation 89 times, we will get 89 groups of vertices, the distance of which to each vertex of its group does not exceed 10. What remains is a tree containing no more than 1000—89 11 = 21 vertices. Let us again consider two vertices in it that are at the maximum distance, and again take the tenth vertex in the chain connecting these vertices. Obviously, this vertex is suitable as a point $K_{90}$ of the desired set. Solution problem.

A. Savin

Color the vertices of the cube blue and red so that the ends of each edge are painted in different colors (Fig. 4). When adding ones to numbers placed on the same edge, the sums of the numbers in the blue and red vertices increase by 1, so the difference between these two sums does not change. Since in the cubes in Figures 1 and 3 this difference is not zero, they cannot lead to a cube with equal numbers at the vertices. Let us now show that if numbers are written at the vertices of the original cube and the sums of the numbers in the red and blue vertices are equal, then all eight numbers can be made equal to each other.

Let us denote by $d$ the difference between the largest and largest of the numbers written at the vertices of the cube, and by $n$ the number of numbers equal to the largest cube, then by adding one to the numbers located on the edge $A_1B_1$, we will reduce either $d$ or $n$. Continuing in this way, we will arrive at either a cube in which $d=0$, that is, all eight numbers are equal to each other, or a cube in which each number adjacent to the largest is the largest. If at the vertex $A_1$ of such a cube there is one of the largest numbers, equal to $a$, then at the vertices $B_1, D_1$ and $A_2$ the number $a+d$ is written (here $d$ is the difference between the largest and largest numbers in the new cube).

Fig. 5.

Since the sum of the numbers in the red vertices is equal to the sum of the numbers in the blue vertices, the number $a$ is written in the fourth red vertex $C_2$, and the number $a+d$ is written in the blue vertices $C_1, B_2$ and $D_2$. By adding $d$ units to the ends of edge $A_1B_1$, then to the ends of edge $C_1C_2$, edge $A_1D_1$, edge $C_2D_2$, and finally edge $A_2B_2$, we arrive at a cube whose eight numbers are all $a+2d$. For the cube at figure 2, these solutions are shown at figure 5.

Yu. Ionin

⟦folio 34⟧

M695. Can all the cells of a rectangular table be colored white and black so that there are equal numbers of white and black cells, and in each row and column there are more than 3/4 of monozoic cells?

Let's assume that coloring is required. We will call the column white or black in accordance with which color predominates in it. Similar ones will be used for strings.

Let $m_0, m_1$ be the number of white and black rows, $n_0, n_1$ the number of white and black columns of the corresponding one, $m_0 + m_1 = m, n_0 + n_1 = n$.

All cells lying at the intersection of white rows with black columns and black rows with white columns differ in color from either the column containing them or the row containing them. The number of such cells is $m_0 n_1 + m_1 n_0$. Without loss of generality, we can assume that more than half of this number of cells differs in color from the rows containing them. Again, without loss of generality, we can assume that $m_0 \leq m_1$. By condition, black lines contain more than $\frac{3}{4} m_1 n$ black cells. This means that the white lines contain less than $\frac{mn}{2} - \frac{3}{4} m_1 n$ black cells. But the black lines contain less than $\frac{1}{4} m_1 n$ white cells. Thus, the number of cells whose color differs from the color of the rows containing them is smaller.

$$\frac{mn}{2} - \frac{3}{4} m_1 n + \frac{1}{4} m_1 n = \frac{m_0 n}{2}.$$

We get inequality

$$\frac{1}{2} (m_0 n_1 + m_1 n_0) < \frac{m_0 n}{2},$$

whence $m_1 < m_0$, which contradicts the assumption regarding $m_0$ and $m_1$.

S. Konyazin, Y. Nesterenko

F703. The rocket is launched from the surface of the Earth vertically at the first escape velocity and returns to Earth not far from the launch site. How long does she spend in flight? The radius of the Earth is $R = 6400$ km.

Note. The area of ​​the ellipse c obtained from a and b is equal to $S = \pi ab$.

The trajectory of the package is represented as part of a very elongated ellipse, at one of the foci of which is the center of the Earth (see figure). The speed of the packets at the top point $D$ of the trajectory is almost zero.

According to the law of conservation of energy.

$$\frac{mv_0^2}{2} - G \frac{Mm}{R} \approx -G \frac{Mm}{2b}.$$

Here $M$ is the mass of the Earth, $m$ is the mass of the packets, $v_0 = \sqrt{GM/R}$ is the initial speed of the packets (first cosmic velocity); $-G \frac{Mm}{R}$ and $-G \frac{Mm}{2b}$ - potential energy packets at the Earth's surface (at launch) and at the top point of the trajectory. From (*) we find the larger resulting ellipse: $b \approx R$.

From Kepler’s third law (the radius vector connecting a body moving under the influence of gravity in a closed orbit with the center of gravity sweeps equal areas in equal periods of time) it follows that the ratio of the movement time $T$ along the position of the ellipse (BDC section) to the total period $T_3$ is equal to the ratio of the protection area on figure of the OBDC figure to total area of the ellipse:

$$\frac{T}{T_3} = \frac{1/2 \pi ab}{πab}.$$

⟦folio 35⟧

F704. Along two main inclined planes forming equal angles a with the horizon, a cylinder and a wedge move, touching each other (see Fig.ok). Find out how much force the wedge presses on the cylinder. The mass of the cylinder is $m_1$, the mass of the wedge is $m_2$. Trench between the cylinder and the wedge of the claim.

F705. A horizontally positioned cylindrical telloisulated vessel with a volume of $V_0 = 100$ l, filled with gel, is divided into two parts by a telloresistance piston, which can move without friction. The gas located on the left side of the vessel is given a volume of tell $\Delta Q = 100$ J. Start changing the pressure in the vessel by the moment the piston stops moving.

From here is flight $T$:

$$T = T_3 \left( \frac{1}{2} + \frac{1}{\pi} \right) = (\pi + 2) \sqrt{R/g} \approx 1 \text{ ч. 9 мин.}$$

E. Surkov

The cylinder is subject to the force of gravity $m_1\vec{g}$, the force $\vec{N}_1$ of the normal reaction from the left inclined plane and the force $\vec{R}$ of the normal reaction from the side of the wedge (the force $\vec{R}$ is directed horizontally). Let us write the equation of motion of the cylinder in projections onto the axis $X_1$, directed along the left inclined plane (see Fig.ok):

$$m_1 a_1 = m_1 g \sin \alpha - R \cos \alpha,$$

(1)

where $a_1$ is the projection of the cylinder acceleration onto the axis $X_1$.

The wedge is subject to the gravity force $m_2\vec{g}$, the normal reaction force $\vec{N}_2$ from the right inclined plane and the normal reaction force from the wedge, which, according to Newton’s third law, is equal to $-R$. Let us write the equation of motion of the wedge in projections onto the axis $X_2$, directed along the right inclined plane:

$$m_2 a_2 = -m_2 g \sin \alpha + R \cos \alpha.$$

(2)

During the movement, the wedge collides with the cylinder; therefore, if the displacement of the wedge along the $X_2$ axis is equal to $\Delta x$, then the center of the cylinder (together with the vertical edge of the wedge) will shift horizontally by $\Delta x \cdot \cos \alpha$. In this case, along the left inclined plane (along the $X_1$ axis), the center of the cylinder will shift to $\Delta x$. This means that during the movement of the wedge and the cylinder, a correspondence is achieved.

$$a_1 = a_2.$$

(3)

Solving equations (1) - (3) together, we find the force $|\vec{R}|$ with which the wedge presses on the cylinder:

$$R = \frac{2m_1 m_2}{m_1 + m_2} g \mathrm{tg} \alpha.$$

S. Krotov

After the body $\Delta Q$ is brought in, the gas in the left part of the vessel unwinds, performing work $\Delta A$. This work by the cylinder is used to increase the internal energy of the gas in the right side of the vessel. Thus,

$$\Delta Q = \Delta U_1 + \Delta A = \Delta U_1 + \Delta U_2 = \frac{3}{2} R \left( \frac{m_1}{\mu} \Delta T_1 + \frac{m_2}{\mu} \Delta T_2 \right).$$

(*)

The equilibrium condition of the piston before heating is

$$p_1 = p_2 = p,$$

equation of state of gas in the left and right parts of the vessel

$$p V_1 = \frac{m_1}{\mu} R T_1, \quad p V_2 = \frac{m_2}{\mu} R T_2,$$

where $V_1 + V_2 = V_0$. After heating, when the piston no longer moves, the pressure on the left and right sides of the equation. Let us denote the increase in pressure in the vessel $\Delta p$; Then

$$(p + \Delta p) (V_1 + \Delta V) = \frac{m_1}{\mu} R (T_1 + \Delta T_1),$$

$$(p + \Delta p) (V_2 - \Delta V) = \frac{m_2}{\mu} R (T_2 + \Delta T_2).$$

After simple transformations we get

$$\Delta p (V_1 + V_2) = R \left( \frac{m_1}{\mu} \Delta T_1 + \frac{m_2}{\mu} \Delta T_2 \right),$$

or (subject to (*))

$$\Delta p V_0 = \frac{2}{3} \Delta Q.$$

From here comes $\Delta p$:

⟦folio 36⟧

$$\Delta p = \frac{\frac{2}{3} \Delta Q}{V_0} \approx 667 \text{ H/m}^2.$$

This result can be obtained much more simply: at equilibrium, the pressure in the vessel is the same everywhere, which means that the energy density (energy per unit volume) is also the same. Therefore, the energy density mutilation is $\Delta Q/V_0$; Let us recall the well-known formula connecting the energy density of an ideal gas with pressure, and we will immediately get the answer.

A. Zilberman

F706. To horizontally move cargo over a distance of $L=20$ m, a self-propelled trolley is used, moving along horizontal rails. On a cable of length $l=5$ m, the transported load (Fig. 1) is moved to the trolley. The cart moves at uniform speed half of the time, and at uniform deceleration half of the time. Determine the possibility of the acceleration value of the trolley at which the load will remain motionless after the trolley stops at the end of the journey.

Fig. 1.

Fig. 2.

F707. The Gale telephone lens has a diameter of $D=250$ cm and a focal length of $F=160$ m. The trolley is used to photograph an artificial Earth satellite, which has a diameter of $d=200$ cm and is located at a distance of $L=320$ km.

Since the initial and final speeds of the cart are zero, and the time of uniformly accelerated motion is equal to the time of uniformly slow motion, the absolute values ​​of the accelerations for uniformly accelerated and equally slow motion are equal; therefore, the paths covered under these modes of motion are equal to each other and equal to $L/2$.

Let us consider the movement of the load when the cart moves with some constant acceleration $\vec{a}$. In this case, the load will participate in two movements: it will move with acceleration $\vec{a}$ and, in addition, perform harmonic oscillations in the coordinate system associated with the cart. The equilibrium position during these oscillations is found from the condition that the load in this position, under the action of the tension force $T$ and the gravity force $m\vec{g}$, moves along the horizontal axis with acceleration $\vec{a}$. From these conditions it is found that in the equilibrium position the three are deflected from the vertical by an angle $\alpha$ such that $tg\alpha = |\vec{a}|/|\vec{g}|$ (Fig. 2); since $\alpha$ is small, $tg\alpha \approx \alpha \approx |\vec{a}|/|\vec{g}|$.

The load will oscillate around this equilibrium position with a period of $T=2\pi \sqrt{l \cos \alpha/g} \approx 2\pi \sqrt{l/g}$, and the useful amplitude of the oscillations of the load will be equal to $\alpha$.

When the sign of the acceleration of the trolley is changed, the angle $\alpha$, which determines the deviation of the cable from the vertical in the equilibrium position, also changes sign, that is, the cable deviates by an angle $\alpha$ in the opposite direction. In order to remain motionless after the cart stops, in the middle of the journey (when the sign of the acceleration of the cart is taken into account) it must be in the initial equilibrium position, that is, $\alpha$ must be equal to zero. It follows from this that during the time $t$ the cart travels a distance $L/2$ the load must complete an integer number $n$ of complete oscillations, that is

$$t=nT, \text{ где } n=1, 2, 3, \dots$$

From the condition

$$\frac{L}{2} = \frac{at^2}{2} = \frac{an^2T^2}{2} = \frac{2\pi^2n^2al}{g}$$

we find the acceleration values ​​at which, after stopping, the load will remain motionless:

$$a_n = \frac{1}{n^2} \frac{Lg}{4\pi^2l} = \frac{1}{n^2} \text{ m/c}^2.$$

V. Mozhaev

1) The distance $f$ from the object to the satellite image plane is determined from the lens formula:

$$f = \frac{LF}{L-F} = \frac{F}{1-F/L}$$

Since $F \ll L$, we can approximately write

$$f \approx F(1+F/L).$$

Distance from object focus to image plane
