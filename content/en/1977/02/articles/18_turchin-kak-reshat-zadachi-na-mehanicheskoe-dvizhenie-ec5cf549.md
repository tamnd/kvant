---
id: 1977-2-turchin-kak-reshat-zadachi-na-mehanicheskoe-dvizhenie-ec5cf549
issue: kvant_1977_2
year: 1977
number: "2"
title: How to solve mechanical motion problems
authors:
  - Турчин Э. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 52
page_last: 55
page_labels: 50, 51, 53
tag: C4EL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 06ddc62efbd3fb04c717cdf13edc1b9924cb7bd01c45d5cf839cc1b4fe0dc949
prompt_sha256: draft-1
translated_from: content/ru/1977/02/articles/18_turchin-kak-reshat-zadachi-na-mehanicheskoe-dvizhenie-ec5cf549.md
source_content_sha256: 2cf01fe8c3f0951cf568dc5a740c8df10992f0200daa7236c27ba21249d4e2d2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

E. Turchin

How to solve mechanical motion problems

As you know, the main task of mechanics is to determine the position of the body at any time. To solve this problem, that is, to find the coordinates of the body in the selected reporting system, you need to know the initial coordinates and variables of the body. The variables can be found by knowing the initial speed and acceleration of the body at each moment. If the forces acting on the body are known, and these forces do not change with time, then the acceleration of the body is determined directly from Newton’s second law - the basic law of the diamana. Therefore, this way of solving the problem of mechanical motion is called diamantic.

When the forces acting on a body are not constant, the application of Newton's second law is associated with great mathematical difficulties. In such cases, it is convenient to use the laws of conservation, and above all, the laws of conservation of energy and momentum, which hold for closed (isolated) systems of bodies. In this case, the specific type of the law of conservation of energy depends on what forces act between the bodies of the system.

For example, if these are gravitational or elastic forces, then the total mechanical energy of the system remains unchanged. In the presence of friction, mechanical energy is not conserved, and its change is equal to the equalization of the friction forces. As a result, the internal energy of the system increases, so that the total energy, of course, does not change. Or such an example - the charged part of the movement in an electric field under the influence of the Coulomb force. In this case, the sum of mechanical and electrical energy is conserved.

If the system is not isolated, then energy and momentum may not be conserved, and the change in energy is equal to the equal value of the external forces acting on the system.

Thus, when solving a problem on mechanical motion, you can use not only the diamantic method, but also the energy method, based on the laws of conservation and change of energy. Which solution method to choose depends on the type of interaction between the bodies (or bodies and fields) included in the system, as well as on the conditions of the given problem.

Now let's look at several problems.

Task 1. After being hit with a stick, the puck gained speed $v_0$ and began to slide across the ice. Determine the distance traveled by the puck before stopping. We do not take into account air resistance, keeping the force constant, the time coefficient of the puck on the ice is equal to μ.

As it moves, the puck interacts with the Earth and ice. Since we are interested in the movement of the puck along the surface of the Earth, it is natural in the conditions of this problem to consider the Earth, and therefore the ice, to be stationary.

The fundamental existence of the puck with other bodies (for example, with the Moon, Sun, etc.). However, we will not take them into account too much.

Let's analyze the interaction of the puck with the Earth and ice. There is a granite interaction between the puck and the Earth, the measure of which is the gravitational force of the puck $mg$ (denoted by $m$ the mass of the puck). The replacement of the puck with ice can be characterized by the support reaction force (elasticity force) $\vec{N}$ and the sliding friction force $\vec{F}_{\text{тр}}$. Thus

⟦folio 51⟧

Fig. 1.

at once, three forces act on the puck, that is, exactly as many forces as it has interactions. There can be no talk of any other forces - push, throw, movement, inertia, etc., which, unfortunately, are often indicated by applicants.

Since all interactions are stationary (do not change with time), both methods of solution arise - both dynamic and energy. Let's solve the problem in several ways.

1. Dynamic method. First of all, let's make a schematic drawing (Fig. 1). Let's choose a coordinate system (XOY), note the parameters of the initial ($x_0=0, v_0$) and final ($x=|\vec{s}|, v=0$) states of the puck and the forces acting on it ($mg, \vec{N}, \vec{F}_{\text{tp}}$). Tsaibu, of course, will be considered a material point.

Let us write down the known expression for the displacement model $|\vec{s}|$ in projections on the OX and OY axes:

$$|\vec{s}| = x = \frac{v_0^2}{2|\vec{a}|}$$

and Newton's second law:

$$|\vec{a}| = \frac{|\vec{F}_{\text{tp}}|}{m}, |\vec{N}| - m|\vec{g}| = 0.$$

Taking into account the coupling equation

$$|\vec{F}_{\text{tp}}| = \mu |\vec{N}|$$

we get

$$|\vec{s}| = x = \frac{v_0^2}{2|\vec{a}|} = \frac{v_0^2 m}{2|\vec{F}_{\text{tp}}|} = \frac{v_0^2}{2\mu |\vec{g}|}.$$

II. Energy method. Let us consider the closed system puck-Earth-ice. The sliding friction force acts inside this system. In this case, the change in the mechanical energy of the system is equal to the work of the friction force:

$$(K + \Pi) - (K_0 + \Pi_0) = A_{\text{tp}}.$$

Relative to the stationary Earth (and ice), the kinetic energy of the system at the initial moment is equal to the kinetic energy of the puck:

$$K_0 = \frac{mv_0^2}{2},$$

and at the final moment it is equal to zero:

$$K = 0.$$

The potential energy of interaction between the puck and the Earth is naturally absent from the Earth’s surface, therefore

$$\Pi_0 = \Pi = 0.$$

Work of friction force

$$A_{\text{tp}} = |\vec{F}_{\text{tp}}| |\vec{s}| \cos \alpha = -\mu m |\vec{g}| |\vec{s}|,$$

since $\alpha = 180^\circ$.

Then finally

$$0 - \frac{mv_0^2}{2} = -\mu m |\vec{g}| |\vec{s}|, \text{ и } |\vec{s}| = \frac{v_0^2}{2\mu |\vec{g}|}.$$

If ice is not included in the system of interactions between bodies, then it will no longer be closed. The support reaction and friction forces are external forces for this system, and their work is equal to the change in the mechanical energy of the system. Since the angle between the force $\vec{N}$ and the displacement $s$ is equal to $90^\circ$, the work done by this force is zero, and as before

$$K - K_0 = A_{\text{tp}}$$

(you have already said that $\Pi = \Pi_0 = 0$).

If we consider only the puck, then all the forces acting on it will be external. According to the kinetic energy theorem, the work done by these forces is equal to the change in the kinetic energy of the puck. The work of gravity, like the work of the support reaction force, is equal to zero, so the expression for the change in mechanical energy is similar to the previous one.

Task 2. A particle with mass $m$ and charge $q$ moves in the electric field of the same fixed charge $Q$马克, which at a distance $R_1$ its speed $v_1$ is acute

⟦folio 53⟧

at a distance of $h_1$. Surface charge density of the plane $\sigma$, natural velocity of the particle $\vec{v}_0$. What is the minimum distance a particle can travel to planes if their charges are unambiguous?
There is no air retention.

The particle interacts with the Earth and the uniform power field of the plane. The forces characterizing these interactions—the gravitational force and the power plant force—are stationary, therefore, in principle, both methods of solving the problem are used. Let us deny the distance of only the energy solution.

Let the system include only one charged particle. Then all the forces acting on it are external, and their work is equal to the change in the kinetic energy of the particle.

At the minimum distance $h_2$ from the plane, the particle speed is zero, so the change in kinetic energy

$$\Delta K = 0 - \frac{m |\vec{v}_0|^2}{2}.$$

Work of gravity

$$A_T = m |\vec{g}| (h_1 - h_2),$$

a Work of power plant force

$$A_a = -q |\vec{E}| (h_1 - h_2) = -q \frac{\sigma}{2\varepsilon_0} (h_1 - h_2),$$

where $\vec{E}$ is the direction of the field of an infinite charged plane.

According to the kinetic energy theorem,

$$0 - \frac{m |\vec{v}_0|^2}{2} = m |\vec{g}| (h_1 - h_2) - \frac{q\sigma}{2\varepsilon_0} (h_1 - h_2).$$

From here

$$h_2 = h_1 - \frac{|\vec{v}_0|^2}{2 \left( \frac{q\sigma}{2\varepsilon_0} m - |\vec{g}| \right)}.$$

Note that if $|\vec{v}_0|^2 > 2h_1 \left( \frac{q\sigma}{2\varepsilon_0} m - |\vec{g}| \right)$, then $h_2 < 0$, that is, the particle can fall onto the plane, having a certain speed.

In conclusion, we offer several tasks for you to solve yourself.

Have a womanized

1. A small ball of mass $m=200$ e is fixed at the end of a control with a length of 1 m and a stiffness of 24 N/m. The ball and thread are moved to a horizontal position and released. When the ball passes the equilibrium position, the thread stretches by 25 cm. Determine the speed of the ball at this moment. Ignore air resistance.

2. A sled weighing 50 ke is slid down a mountain 7 m high. Determine the work done by the frictional force if the speed of the sled at the base of the mountain is 10 m/sec.

3. A rope 20 m long is thrown over a non-issom block of small radius. It hangs symmetrically and ends, and then, as a result of a slight push, begins to move along the block without friction. What will be the speed of the rope by the time it leaves the block? There is no air resistance.

4. A glass ball with a volume of 0.2 cm³ falls uniformly in water at low speed. Determine the work done by the water resistance force when the ball moves 6 cm. The density of the stack is 2.7 e/cm³.

5. An electron moving at a speed of 3.106 m/sec entered the region of a uniform power field and slowed down to a complete stop. Determine the potential difference between the stopping point and the starting point of the electron in the field. Ignore gravity and air resistance.

6. A part with charge $q$ and mass $m$, located at a distance $H$ from the plane, begins to freely fall onto the horizontal plane. What will be the speed of the particle at a distance $h < H$ from the plane? Ignore air resistance.

Note. The interaction of a charged particle with an induced charge on a plane can be replaced by the interaction of a given particle with an exact charge located symmetrically relative to the plane (see, for example, the article by G. Myakishev “Power Plant Field”, «Kvant», 1975, No. 4).
