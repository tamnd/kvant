---
id: 1972-10-zaytsev-rabota-energiya-moschnost-ee15d48b
issue: kvant_1972_10
year: 1972
number: "10"
title: Work, energy, power
authors:
  - Зайцев И. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 60
page_labels: 52, 53, 54, 55, 57, 58
tag: 9AWP
lang: en
source: kvant_digital
extraction: vision
content_sha256: 15415f4523f29cafc434f60b9694072846cc86d556eabb55a343cefc09c7f57d
prompt_sha256: draft-1
translated_from: content/ru/1972/10/articles/13_zaytsev-rabota-energiya-moschnost-ee15d48b.md
source_content_sha256: 6470a1a627a3e1c9b7635c8b4b56c999654629816b20b7cfff37dd2fc8ec62a4
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

If a constant force $F$ acts on a moving body at an angle $\alpha$ to the direction of movement $s$ (Fig. 1), then this force does work
$$A = F \cdot s \cdot \cos \alpha,$$
(1)

where $F$ and $s$ are the modiles of the vectors $F$ and $s$.

The work of force is equal to the product of the models of force vectors and body displacement by the cosine of the angle between them.

Let us consider in detail this well-known formula. If the angle is $\alpha < \frac{\pi}{2}$, then $\cos \alpha > 0$ and the work done by the force is positive. At $\alpha = \frac{\pi}{2}$, that is, when the force $F$ is perpendicular to the displacement of the body $s$, the work done by the force $F$ is zero. (In particular, the work of the force imparting centripetal acceleration to the body is equal to zero. With uniform motion of the body in a circle, the force acting on it is perpendicular to the speed of the body.) If $\alpha > \frac{\pi}{2}$, then $\cos \alpha < 0$ and the work of the force is negative. Let's figure out what this means.

Let's take a simple case when the force $F$ is parallel to the displacement vector of the body. In this case, the body moves with acceleration $a = \frac{F}{m}$, the direction of which coincides with the direction of the force vector. If the direction of the force vector coincides with the direction of the body vector, then the speed of the body increases, and the force $F$ does positive work. If the force vector is directed opposite to the body’s displacement vector, then the body’s acceleration is directed opposite to the velocity vector and the abscissa value of the body’s speed decreases. But the work of the force in this case, as follows from formula (1), is negative ($\alpha > \frac{\pi}{2}$ and $\cos \alpha < 0$).

Consequently, the work of the force that slows down the movement of the body is negative, its speed decreases.

The product $F \cdot \cos \alpha$ is the magnitude of the projection of the force vector onto the axis along which the body displacement vector is directed (Fig. 1). Therefore, we can say that the work of force $F$ is equal to the product of the modulus of the displacement vector of the body and the projection of the force vector $F$ onto the axis parallel to the displacement vector.

Using this formulation, one can easily prove the following theorem.

Theorem 1. If several forces act on a body, then the total work done by this force is equal to the sum of the work done by the individual forces.

Indeed, if several forces $F_1, F_2, F_3, \dots$ act on a body, then these forces can always be replaced by an equal force $R = F_1 + F_2 + \dots$. Therefore, the total work done by all forces is equal to the acting force:

$$A = R \cdot s \cdot \cos \alpha = s \cdot \text{пр.} R.$$

Since the projection of the vector $R$ onto any axis is equal to the sum of the projections

⟦folio 53⟧

on this axis of vectors $F_1, F_2, \dots$, then $A = s$ (ex. $F_1 + \text{пр.} F_2 + \dots) = A_1 + A_2 + \dots$.

In particular, if two forces act on a body, equal in abscillotine magnitude and directed in opposite directions, then their work is zero. However, some of these forces do some positive work, while others do equally negative work.

It is not difficult to prove another theorem.

Theorem 2. If the chalk makes several consecutive movements: $s_1, s_2, \dots$, so that $s_1 + s_2 + \dots = s$, then the work done by the force $F$ is equal to

$$A = F \cdot s \cdot \cos \alpha,$$

where $\alpha$ is the angle between vectors $F$ and $s$. Note that the product $s \cdot \cos \alpha$ is equal to the projection of the body displacement vector onto the force vector (Fig. 2) (more correctly, the projection of the body displacement vector onto the axis parallel to the force vector). The total work done by the force $F$ is equal to

$$A = F \cdot \text{пр.} s_1 + F \cdot \text{пр.} s_2 + \dots$$

But the sum of the projections of the vectors $s_1, s_2, \dots$ onto any axis is equal to the projection of the vector $s$ onto this axis. Hence,

$$A = F \cdot \text{пр.} s.$$

Now we can conclude: if the body moved in such a way that its total displacement is zero (the body returned to the same point from which it started moving) and during the movement a constant force $F$ acted on the body, then the work done by the force is zero.

Fig. 2.

Task 1. Prove that the work of a constant force does not depend on the trajectory of the body.

No matter how the body moves from point $A$ to point $B$, its displacement is equal to the vector $AB$ (Fig. 3). Therefore, the work done by the force is $F \cdot AB \cdot \cos \alpha$, where $\alpha$ is the angle between the vectors $AB$ and $F$. This product does not depend on the trajectory of the body.

Until now, the force acting on the body has been constant. Let us now consider the work of a variable force. In this case, we can no longer use formula (1). In order to determine the work of a variable force, it is necessary to divide all movements of the body into small movements, such that the force on these movements can be considered constant. On each of such displacements $\Delta s_i$ the work is equal to

$$A_i = F_i \cdot \Delta s_i \cdot \cos \alpha_i.$$

The total work is equal to the sum of the work, we will get an approximate result. If, say, at displacement $\Delta s_i$ the force changes by 1% (or rather, not the force, but the product $F \cdot \cos \alpha_i$), then the accuracy of our calculations will also be 1%. If we need greater precision, then the movement of the body should be broken down into even smaller movements.

The case of practical importance is when the body moves in a straight line, and the force acting on the body varies according to

⟦folio 54⟧

absolute magnitude, while its direction remains the same all the time. Let, for example, a body move from one point to another in a straight line, and the force F acting on the body is always directed along this straight line, but varies from point to point as shown in the graph of the force versus coordinate x (Fig. 4). Let's find the work done by this force. Divide the movement of the body into small sections Δx_i. In each of these sections, the force will be considered constant and equal to a certain average value F_i. Then the work on the section Δx_i is

$$A_i \approx F_i \cdot \Delta x_i,$$

that is, equal to the area of ​​the rectangle from the sides F_i and Δx_i. The work along the entire path is obviously equal to the sum of the areas of such rectangles. Since as the sections Δx_i decrease, the area of ​​all shaded rectangles will tend to the area of ​​the figure under the force graph, it is clear that the work of the force is equal in this case to the area of ​​the figure under the graph of the force being shaded versus the coordinate. If this graph passes below the x-axis, the force F is negative. This means that the force vector is directed opposite to the body displacement vector. The work of this force is also negative. This means that when calculating the work, the area of ​​the figure now “above the force graph” must be taken with a minus sign. In the same way, work should be considered negative if the force graph lies above the X-axis, but the change in the coordinate of the body is negative.

So, we know how the slope is located between the body and the stop (Fig. 5) for a length Δl. Spring stiffness k. The body can move along the main plane without cracking. At the initial moment, the ends of the spring are created by a thread. Then the thread is pinched. How much work is done by the spring force of the spring by the time it passes the “equilibrium” position, at which the spring is not deformed?

What work is done by the spring force at the moment when the chalk is to the right of the equilibrium position at a distance Δl₁ from it.

Let's draw a graph of the shading of the spring force from the position of the body (its coordinates x) in the coordinate system, the origin of which coincides with the position of the body at the moment when the spring is not deformed, and the direction of the OX axis coincides with the direction of movement of the body after burning out the thread (Fig. 6). Strength

⟦folio 55⟧

The elasticity of the pressure is proportional to the deformation of the pressure:

$$F = -kx.$$

When the body coordinate is negative, the force is positive, and vice versa.

The work $A_1$ done by the elastic force applied to the moment when the body is in the equilibrium position is equal to the area $S_1$ of the pink triangle

$$A_1 = \frac{k\Delta l \cdot \Delta l}{2} = k \frac{(\Delta l)^2}{2}.$$

With further movement of the body, the direction of the elastic force is opposite to the direction of movement of the body; work is negative. To find the work done by the elastic force at the moment when the coordinate of the body becomes equal to $\Delta l_1$, you need to subtract the area of ​​the blue triangle from the plane of the pink triangle:

$$A_2 = k \frac{(\Delta l)^2}{2} - k \frac{(\Delta l_1)^2}{2}.$$

At $\Delta l = \Delta l_1$ $A_2 = 0$.

Let us now consider another hair - how the state of motion of the body changes if it is acted upon by a force $F$ that has done work $A$. We will assume that it moves rectilinearly and the force $F$ is directed along the line of motion of the body. If the displacement of the body is $s$, then

$$A = F \cdot s.$$

Force $F$ imparts acceleration $a = \frac{F}{m}$ to the body, where $m$ is the mass of the body. That's why

$$A = mas.$$

But as we know from kinematics, $as = \frac{v^2 - v_0^2}{2}$, where $v_0$ is the initial, and $v$ is the final velocity of the body. Hence,

$$A = \frac{m(v^2 - v_0^2)}{2} = \frac{mv^2}{2} - \frac{mv_0^2}{2}.$$

The quantity $\frac{mv^2}{2}$ is the kinetic energy of the body. Therefore the work

force $F$ is equal to the change in the kinetic energy of the body.

Task 3. On the chalk described in the previous problem, in addition to the elastic force, there is also the force of friction of the body on the plane. The mass of the body is equal to $m$, the coefficient of friction of the body on the plane is equal to $f$. In this case, what will be the maximum deviation of the body $\Delta l_1$ from the position at which the pressure is not distanced?

At the moment when the coordinate of the body is $x = \Delta l_1$, the speed of the body is zero, the same as at the initial moment of the body’s movement. Consequently, both the change in the kinetic energy of the body and the work of the forces acting on the body are equal to zero.

The elastic force of the surface does work

$$A_1 = \frac{k(\Delta l)^2}{2} - \frac{k(\Delta l_1)^2}{2},$$

and the friction force is work

$$A_2 = -mgf(\Delta l + \Delta l_1).$$

(The work of this force is negative, since it is directed against the movement of the body.) Therefore

$$\frac{k(\Delta l)^2}{2} - \frac{k(\Delta l_1)^2}{2} - mgf(\Delta l + \Delta l_1) = 0,$$

or

$$\frac{k}{2}(\Delta l + \Delta l_1)(\Delta l - \Delta l_1) = mgf(\Delta l + \Delta l_1),$$

from here

$$\Delta l_1 = \Delta l - \frac{2mgf}{k}.$$

Until now, when speaking about work, we have emphasized that it is the work of force. But, as we know, force acts on a given body from another body. Therefore, instead of talking about the work of a force, we can talk about the work of a body acting on a moving body with a given force, or simply about the work of a body.

A moving body can do work, for example, lift another body. In this case, the speed of movement of the body and its kinetic energy

⟦folio 57⟧

So, the work that a body can do, initially motionless, is equal to the change in its potential energy. If body $M_1$ interacts only with body $M_2$, that is, it moves only under the influence of force $F$, then its potential energy decreases, that is, its ability to do work decreases. But in this case, the kinetic energy of the body increases, and the change in kinetic energy is equal to the work done by the force $F$, and the change in potential energy is also equal to the work done by the force $F$, but it is negative.

This means that the change in potential energy is equal in magnitude to the change in kinetic energy, as their sum remains the same all the time.

We have come to a very important conclusion - the law of conservation of mechanical energy of an isolated system. Isolated, since it was important for us that the body $M_1$ was not affected by other bodies except the body $M_2$, that is, that the bodies $M_1$ and $M_2$ constitute an isolated system. If forces external to it act on a given system, then the total energy of the system changes by the amount of work done by these forces.

Let us now solve several problems.

Task 4. Throw a rope over a block, so that the ends of the rope are at the same height om

Fig. 8.

Then the block is next and the rope begins to shorten from the block under the influence of force between them. What speed will the rope have at the moment when it completely merges with the block? Rope length $l$, mass $m$.

At the initial moment of mass of the rope is $\frac{l}{4}$ from the block. At the moment when the rope cuts off the block, its center of mass will be at a distance $\frac{l}{2}$ from the block. In this case, the potential energy of the rope-Earth system will change by the following values:

$$mg \left( \frac{l}{2} - \frac{l}{4} \right) = mg \frac{l}{4}.$$

From the law of conservation of energy it follows that

$$mg \frac{l}{4} = \frac{mv^2}{2}.$$

From here

$$v = \sqrt{\frac{gl}{2}}.$$

Task 5. Force $F$ lift the mass load $m$ to a height $H$. What work does this force do? How does the potential energy of a body change?

The work done by force $F$ is equal to $F \cdot H$, and the change in potential energy is mg$H$, m is the mass of the body. The difference $FH - mgH$ went to increase the kinetic energy of the body.

Task 6. What power should the pump have for the module to transfer Q liters of water in 1 second from a well, depth h, on the surface of the earth? The area of ​​the second is rough, through which the water is thrown, s.

The water must have a speed of $v = \frac{Q}{s}$ in the pipe. This means that the pump must, in time $t$, do work equal to the change in the potential energy of the water mass $m = Q\rho t$:

$$\Delta W_\pi = mgh$$

(ρ is the density of water) and the change

⟦folio 58⟧

ee kinetic energy

$$\Delta W_K = \frac{mv^2}{2};$$

$$A = \frac{mv^2}{2} + mgh = \frac{Q^3\rho t}{2s^2} + Q\rho tgh.$$

The power of the pump is equal to the work it does in 1 second:

$$N = \frac{A}{t} = \frac{Q^3\rho}{2s^2} + Q\rho gh.$$

Energy, like work, depends on the choice of coordinate system. This is natural - after all, both the speed of the body and its displacement depend on the coordinate system.

Let us finally solve the problem in which there is a choice of coordinate system.

Problem 7. Two charges q, identical in magnitude and value, are located at a distance R from each other. To what minimum distance r can these charges approach each other if at the initial moment o one of the charges accumulates and the other moves towards it with speed v?

This problem is often solved by using a coordinate system associated with the charge that initially accumulated. In this coordinate system, the energy of the system is initially equal to the sum of its potential energy $W_\pi = \frac{q^2}{R}$ and the kinetic energy of charge motion $\frac{mv^2}{2}$

$$W = \frac{q^2}{R} + \frac{mv^2}{2}.$$

At the moment when the charges are at a minimum distance from each other, they are motionless in this coordinate system and the energy of the system is equal to its potential energy $\frac{q^2}{r}$. From the law of conservation of energy it follows that

$$\frac{q^2}{r} = \frac{q^2}{R} + \frac{mv^2}{2},$$

from here

$$r = \frac{1}{1 + \frac{mv^2R}{2q^2}}.$$

However, this decision is wrong.

The coordinate system associated with a non-uniformly moving charge is non-inertial. It cannot use a fixed coordinate system. Here, at the initial moment, the charges have speeds

$$v_1 = 0 \text{ и } v_2 = v,$$

and the energy of the system is

$$\frac{q^2}{R} + \frac{mv^2}{2} = \frac{q^2}{R} + \frac{mv^2}{2}.$$

From the law of conservation of momentum it follows that at the moment when the distance between the charges is minimal, both charges move at the same speeds, equal to $\frac{v}{2}$. The energy of the system is

$$\frac{q^2}{r} + \frac{m\left(\frac{v}{2}\right)^2}{2} + \frac{m\left(\frac{v}{2}\right)^2}{2} = \frac{q^2}{r} + \frac{mv^2}{4}.$$

From the law of conservation of energy we find:

$$r = \frac{1}{1 + \frac{mv^2R}{4q^2}}.$$

At the right

1. The wheel rolls without puncturing at speed v. Find the kinetic energy of this wheel. The mass of the wheel is m.
2. A ball of radius r = 15 mm and mass m = 5 e is immersed in water to a depth of h = 30 cm. When the ball was released, it jumped out of the water to a height h_1 = 10 cm. What part of the mechanical energy of the ball was converted into heat due to the friction of the ball against the water?
3. Using the law of conservation of energy, find the speed of liquid flow from the hole y at the bottom of the vessel if the liquid level is at a height h from the bottom.
