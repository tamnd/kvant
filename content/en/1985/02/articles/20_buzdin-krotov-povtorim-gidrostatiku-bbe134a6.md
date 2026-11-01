---
id: 1985-2-buzdin-krotov-povtorim-gidrostatiku-bbe134a6
issue: kvant_1985_2
year: 1985
number: "2"
title: Let's repeat hydrostatics
authors:
  - Буздин А. И.
  - Кротов С. С.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 55
page_labels: 48, 51, 52, 53
tag: RJNC
lang: en
source: kvant_digital
extraction: vision
content_sha256: ed78adbac50f744f876e7498c7f20353c52f73cee672da1e13118e67ab33877b
prompt_sha256: draft-1
translated_from: content/ru/1985/02/articles/20_buzdin-krotov-povtorim-gidrostatiku-bbe134a6.md
source_content_sha256: 60a81c0ce10a3478501d16211d69c28cfc0dfc1fb7314ffb4da8e3970b5fc9ab
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

Let's repeat hydrostatics

Candidate of Physical and Mathematical Sciences
A. I. BUZDIN,
Candidate of Physical and Mathematical Sciences
S. S. KROTOV

The school curriculum in physics is structured in such a way that, having become acquainted with the topic “Hydrostatics” in the sixth grade, students never return to it. Apparently, it is generally accepted that this topic is not difficult. But, as the experience of entrance exams shows, problems and questions on hydrostatics often confuse applicants.

What's the matter here? From our point of view, this is due to the fact that in the sixth grade, schoolchildren are not yet ready to grasp all the subtleties of physics, they are just getting acquainted with it. However, when composing questions and tasks for the exams, it is assumed that the applicant has rethought many topics, including hydrostatics, from a more general position, taking into account knowledge of the entire physics course.

In this article, we wanted to recall the basic laws of hydrostatics and consider several specific tasks and questions that in different years were included in exam papers or asked to applicants during the oral exam.

Liquid and gases, when moving as a whole, represent a mechanical system, the parts of which interact with each other through only pressure forces. Indeed, when a liquid (hereinafter, when we talk about liquid, we mean gas too) is at rest, viscosity does not appear - liquid friction occurs only when layers of liquid move relative to each other or relative to a solid body.

For a liquid, as is known, Pascal's law is satisfied: the pressure exerted on the liquid is transmitted without change to each point of the liquid. If the liquid is under the influence of gravity only, the pressure p increases with the immersion depth h according to the law p=ρgh, where Q is the density of the liquid. Therefore, different parts of the body immersed in liquid experience different pressure forces. As a result of their combined action, a buoyant force (Archimedean force) will arise. According to Archimedes' law, a body completely immersed in a liquid is pushed upward with a force equal to the weight of the liquid it displaces (that is, the weight of the liquid in the volume of this body).

Let us immediately draw attention to the fact that Archimedes' law does not apply when the immersed body is tightly pressed against the walls or bottom of the vessel. For example, it is known that a submarine that has sunk to the bottom of a sheet is pressed to the bottom by the force of hydrostatic pressure, and is not pushed upward at all.

Let us now turn to consideration of specific tasks and issues.

Question 1. On one of the targets of the balanced scales there is a stand with water and a tripod with a load suspended from it (Fig. 1). What happens to the balance of the scale if the string is extended so much that the weight ends up in the water?

Many applicants believe that the balance will be disrupted. As a reason, they name the buoyant force acting on the load according to Archimedes' law and reducing the tension of the thread, and therefore the force of pressure of the shativa on the scale. Others believe that once immersed in water, the weight will press down on it with added force or, equivalently, increase the water level in the glass and thereby increase the pressure on the bottom of the glass, causing the left cup to move.

To get the correct answer, it is enough that the contents of the cup do not change depending on the position of the load - outside the water or in the water, and therefore the balance of the scales is maintained. But what was wrong with the previous reasoning?

When lowering a load into the water, the tension of the thread will actually decrease -

⟦folio 51⟧

and the angle that the board makes with the horizon (with the surface of the water) is α. Then F_b=2xρ_0Sg and Mg=ρSlg. Since we are interested in the minimum value of the board-to-stone coefficient, we can assume that F_tp=μN.

Since the board is in equilibrium, the sum of all forces acting on the board is zero. Let's write this condition by projecting all the forces onto the directions of the tangent to the board and the normal to it:

$$2xρ_0Sg \sin α - ρlSg \sin α + μN=0,$$
$$2xρ_0Sg \cos α - ρlSg \cos α + N=0.$$

Dividing these equations term by term, we find that μ=tan α.

On the other hand, as can be seen from figure 4,

$$tg α=H/\sqrt{(l-2x)^2-H^2}.$$

The value of x can be found from the condition that the sum of the moments of all forces acting on the board is equal to zero. It is most convenient to consider the moments of forces relative to the point of contact of the board and the stone (point O), since in this case the moments of the tray forces and the support reaction will be equal to zero.

The line of action of the Archimedean force passes through the center of mass of the immersed part of the board, which means its length relative to point O is equal to (l-x)×cos α. The gravity field is equal to (l/2)cos α. The condition for the total moment of forces to be equal to zero has the form

$$qlS(l/2)cos α - ρ_02xS(l-x)cos α=0,$$

or

$$x^2-lx+ρl^2/(4ρ_0)=0.$$

From here is

$$x=(l/2)(1-\sqrt{1-ρ/ρ_0})$$

(the second root should be discarded, since it does not satisfy the conditions 2x<l).

Then we finally get

$$μ=H/\sqrt{l^2(1-ρ/ρ_0)-H^2}.$$

The task stated that the board was thin. How was this used in the solution?

Note that the question of the moment of buoyant force excludes the stability of floating bodies. In shipbuilding, there is a special concept of the metacenter - the point of intersection of the line of action of the buoyant force in the inclined position of the ship with the plane of its symmetry (Fig. 5). The metacenter (point M) must not fall below the center of gravity of the ship (point O), otherwise the rotational moment of the Archimedean force will not be able to return the ship to an upright position.

Problem 3. Water is poured into an aquarium of rectangular cross-section (water density q=10^3 kg/m³) to a height H=0.5 m. Determine the force acting on the wall of the aquarium with a length of l=1 m, and the moment of pressure on this wall relative to its lower edge.

In this case, the pressure changes with the immersion depth h, and changes according to the linear law p=ρgh.

There is no doubt that the equilibrium of all pressure forces is directed horizontally. What is its model equal to? Obviously, when answering this question, uses the formula F=pcpS, where S=lH is the area of ​​resistance of water with the wall, and pcp=ρgH/2 is the average pressure equal to the pressure at the middle of the depth. And this answer is certainly correct. However, not every applicant can explain why this particular pressure is used as the average. Let's try to do this.

Let us consider a rectangular prism (made of materials of density q) with a height l, at the base of which lies a right equilateral triangle with sides H. Let us place this prism on a horizontal surface

⟦folio 52⟧

(Fig. 6). It is easy to see that the force of pressure of the prism on the surface coincides in absolute value with the force of water pressure on the side surface of the aquarium (due to the identical distribution of pressure over the contact surface). But the pressure force of a prism is its weight, so

$$F_\pi = \rho g H \frac{H}{2} l = (\rho g \frac{H}{2}) (l H) = 1250 \text{ H}.$$

So, what is valid for the average water pressure is the pressure at the middle of the depth.

The second question of the problem is more complex, since the pressure changes with depth, and the plenchi correspond to the codes of the pressure forces also depends on the depth. Referring to the analogy with the previous result, it is sometimes proposed to use the average pressure force and the “average” captivity equal to $H/2$ to find the moment of pressure forces. But this is completely wrong. To get the correct answer, you really need to use an analogy, but an analogy with the sign mentioned above. For it, the desired moment is the product of the gravitational force of the prism on the captivity relative to the straight line $AA'$ (see Fig. 6). The line of action of gravity is at a distance $H/3$ from the edge $AA'$ (in a homogeneous triangle the center of mass is at the point of intersection of the medians), therefore

$$M_\pi = \rho g \frac{H}{2} l H \frac{H}{3} \approx 208,3 \text{ H} \cdot \text{m}.$$

When solving the problem, we ignored and did not take into account atmospheric pressure. Think about it, could it change the answer? And one more thing: how does the force of pressure on the wall change if this wall is made of rubber?

Question 4. What happens to the depth of a ball floating in a pool of water if the wall begins to accelerate into the water?

Consider a system of water plus a ball floating in it. Let it move with acceleration $a$. This acceleration is created due to the difference between the pressure forces $N_a$ from the side of the glass bottom and the gravitational force of the system $(M+m)g$, where $M$ is the mass of water, and $m$ is the mass of the ball:

$$N_a - (M+m)g = (M+m)a.$$

While the system was digging, the pressure force $N_0$ on the bottom of the glass was determined by the correspondence

$$N_0 - (M+m)g = 0.$$

Comparing the forces $N_a$ and $N_0$, we see that

$$\frac{N_a}{N_0} = \frac{a+g}{g}.$$

Let us show that the pressure at any point in the liquid has increased by the same number of times. Let us select a “water” cylinder with a cross section $\Delta S$, one of the bases of which coincides with the surface of the water, and the other is at a depth $h$. Let us write down the equation of motion of this cylinder in the vertical direction:

$$p_h \Delta S - \rho \Delta Shg = \rho \Delta Sha,$$

where $p_h$ is the water pressure at depth $h$, $\rho$ is the density of water. We see that

$$p_h = \rho (g+a)h,$$

that is, compared to the static case, it increased $(g+a)/g$ times. Consequently, the force equations are pushed out in the same number of times.

Let us now write down the equation of vertical motion of the ball:

$$\rho V_a g \frac{a+g}{g} - mg = ma.$$

From here we obtain that the volume $V_a$ of the immersed part of the ball during the accelerated upward movement of the glass does not depend on the acceleration of the system and is equal to $V_a = m/\rho$.

Consequently, the depth of the ball's immersion in water will not change.

Problem 4. An aquarium in the shape of a cube with edge $L$, up to half

⟦folio 53⟧

filled with water and set in motion with horizontal rooting $\vec{a} (a < g)$. Assuming that by the time the aquartzum-water system began to move, the water as a whole had not splashed, determine the shape of the water surface and the pressure at point M (Fig. 7).

Let's say right away that the surface of the water will be part of a plane inclined to the horizon at an angle $\alpha$. Now let's justify this and find the angle $\alpha$.

Let us select a small volume of liquid with mass $\Delta m$ near an arbitrary point A of the water surface. The separating pressure forces from all other water will be perpendicular to the surface at a given location. Let it be equal to $\vec{N}$ and form an angle $\alpha$ with the vertical. Then the selected area of ​​the surface (since it is small, it can be considered flat) forms the same angle $\alpha$ with the horizon (why?).

Let's write down the equations of motion for our volume of water, projecting all the forces and accelerations onto the vertical and horizontal axes:

$$N \cos \alpha - \Delta mg = 0,$$
$$N \sin \alpha = \Delta ma.$$

From here we get

$$tg \alpha = a/g$$

— the angle of inclination of the surface does not depend on the choice of point A and is determined only by the ratio $a/g$.

Let us now select a plane in the water that is parallel to the surface of the water and is vertically separated from it by a distance $h$. Let us show that at all its points the water pressure $p_h$ will be determined by the formula $p_h = \rho gh$. Indeed, let us select an inclined cylinder in water with a generatrix of length $h$ and bases $\Delta S$. This volume does not move vertically, therefore the sum of the projections of all forces acting on it in the vertical direction is zero:

$$\rho gh \Delta S \cos \alpha - p_h \Delta S \cos \alpha = 0,$$

where the first term is the force of the cylinder’s gravity, and the second is the vertical projection of the pressure force on the lower base of the cylinder. From here we get

$$p_h = \rho gh.$$

Thus, constant pressure surfaces will be planes parallel to the free surface of the water.

To find the pressure at point $M$, note that due to the incompressibility of water, point $B$ (middle) remains in place. Hence,

$$p_M = \rho g \left( \frac{L}{2} + \frac{L}{2} tg \alpha \right) = \rho \frac{L}{2} (a + g).$$

Have we used the condition $a < g$ anywhere? Find what will be the force of water pressure on the walls and up to the aquarium during its accelerated movement?

* * *

As we part with the reader, we hope that when preparing for the entrance exams, he will be attentive to the topic “Hydrostatics” and will not want to divide the section “Floating bodies subject to buoyant forces.”

At the right

1. The mercury manometer (Fig. 8) consists of two tubes with cross-sectional area $S_1$ and $S_2$, with $S_1/S_2 = 2$. By how much did the variable pressure change if the mercury level in the left colley rose by $\Delta h = 10$ mm?

2. A glass disc fell into a barrel of water. Its diameter is $D = 30$ cm, thickness $h = 5$ mm, glass density $\rho = 2,6 \cdot 10^3$ kg/m³. To get it out, they lowered a tube with a diameter of $d = 10$ cm into the barrel, pressed it tightly against the disk, pumped out the water and began to slowly lift it up. Determine to what distance to the surface of the water you can raise the disk in this way.

3. A funnel of mass $M$, shaped like a truncated cone with base radius $R$, stands on the table. The edge of the funnel is pressed tightly to the table surface. How much water will be poured into the water tank by the time it is lifted from the table, if the height of the water level in the water tank at this moment is $h$?

4. A cylindrical weight suspended from the diameter is lowered into water until the water level in the vessel changes by $\Delta h = 8$ cm (Fig. 9). The diameter indication changed to $\Delta F = 0,5$ N. Determine the cross-section of the vessel.

5. A piece of ice floats in a vessel with water, with a lead pellet frozen in the middle. Ice mass $M$, pellet mass $m$. The temperature of the water in the vessel is $0^\circ C$. What is the least amount of heat that must be supplied to the system for the pellet to begin to sink? Density of lead $Q_2$, ice $Q_1$, specific heat of fusion of ice $\lambda$.

6. The density of the salt solution changes with depth according to the law $\rho = \rho_0 + Ah$, where $\rho_0 = 1$ g/cm³, $A = 0,02$ g/cm⁴. Two balls connected with a thread are dropped into the mixture. The volume of the balls is $V_1 = 0,1$ cm³ and $V_2 = 0,2$ cm³, their masses are $m_1 = 0,13$ g and $m_2 = 0,34$ g. The immersion depth of the first ball in a state of equilibrium turns out to be equal to $h_1 = 20$ cm. In this case, the thread is natural. Determine the length of the thread.

7. Where does the gas burn hottest - on the first or last floor of a four-chamber residential building?

8. A wooden ball floats in a glass filled to the top with water and closed at the top. How will the pressure force of the ball on the lid change if the vessel is set in motion with the rooted surface upward?
