---
id: 1978-5-aslamazov-napryazhennost-napryazhenie-potentsial-1548aede
issue: kvant_1978_5
year: 1978
number: "5"
title: Tension, tension, potential
authors:
  - Асламазов Л. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 40
page_last: 45
page_labels: 38-43
tag: E62W
lang: en
source: kvant_digital
extraction: vision
content_sha256: 64fa520fb69ca28880978c925f75f9496dce235cdcda6f6360dff090210c7d4d
prompt_sha256: draft-1
translated_from: content/ru/1978/05/articles/13_aslamazov-napryazhennost-napryazhenie-potentsial-1548aede.md
source_content_sha256: 320f2f4e5dbfbdcc5df5d98330ac84739499ab52255804a6d8626924897d8dd6
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

Voltage, potential

Each point of the electric field is characterized by a vector quantity - field strength. The field voltage $\vec{E}$ at a given point is equal to the force acting on a positive test charge placed at this point and the relative unit of charge. This is the force characteristic of the electric field.

When an electric charge moves in a field, work is done. An electrostatic field has a very important property - potentiality: the work done to move a charge from one point in the field to another does not depend on the shape of the trajectory. This allows us to introduce the concept of voltage (or potential difference). The voltage $U$ between two points of the field *) is equal to the work done by the electric field to move a unit positive charge from one point to another.

Unlike tension, which determines at a single point, tension characterizes two points of the field. If you fix one point, choosing it as the beginning of the cutoff, then any point in the field will have a certain voltage in relation to the selected point. It's on

*) By the words “field”, “electric field” here and in what follows we will mean an electrostatic field, that is, a field created by stationary charges.

tension is called *potential f*. Obviously, the beginning of the cutoff corresponds to zero potential. Most often, zero potential is assigned to a point infinitely distant from the charge created by the field. In this case, the potential f at some point in the field is equal to the work done by the electric field to move a positive charge per unit from this point to infinity. This is the energy characteristic of the electric field.

Sometimes it is more convenient to specify a scalar quantity at each point—potential φ—than a vector quantity—tension $\vec{E}$. Naturally, these two quantities must be related to each other.

Let us first consider a uniform electric field. Its voltage $\vec{E}$ is the same at all points; force, lines and fields - parallel straight lines (Fig. 1). Let's find the potential difference between points $B$ and $D$. The potential $\varphi_B$ of a point $B$ is equal to the work done by a unit moving a charge from this point to infinity. The shape of the trajectory does not matter when calculating the work, so we will move the charge first along the segment $BC$, then along the segment $CD$, and then from the point $D$ to infinity. The force acting on a unit charge from the electric field is equal to the intensity. On the segment $BC$, the work of this force is equal to $El$, where $E$ is the projection of the tension vector on the force line, and $l$ is the length of the segment $BC$. On the segment $CD$ the force does not do any work, since it is perpedicular to the displacement. Finally, the work done by a unit to move a charge from point $D$ to infinity is equal to potential $\varphi_D$. Therefore: $\varphi_B = El + \varphi_D$, or for the potential difference:

$$\varphi_B - \varphi_D = El.$$ (1)

In order for formula (1) to give the correct sign of the potential difference, the value $l$ must be assigned a certain sign depending on the location of the points $B$ and $C$ on the field line. We will assume that $l$ is the projection of the vector $BD$ onto the direction of the field line. Then

⟦folio 39⟧

the sign is positive if point $C$ lies “lower” along the field line than point $B$, and negative in the opposite case. For the case depicted in figure 1, ​​$l > 0$, and the potential difference is $\varphi_B - \varphi_D > 0$, which corresponds to a decrease in potential along the field line ($\varphi_D < \varphi_B$).

So, in a uniform electric field there is a simple relationship between the direction and the potential difference, given by formula (1).

What is the relationship between potential and direction in the case of a non-uniform electric field? In such a field, the directionality of $\vec{E}$ changes from the point $k$ of the point. Let, for simplicity of calculation, the change in direction occur only in one direction, which will take the axis $OX$ (Fig. 2). Then the direction of the field $\vec{E}$ depends only on the coordinate $x : \vec{E} = \vec{E}(x)$. It is clear that in small areas of space there is little direction, and the electric field there can be approximately considered uniform. Let's take close points $B$ and $D$ and find the potential difference between them. Let's use formula (1). The potential, like the directionality, depends only on the coordinate $x^*$: $\varphi_B - \varphi_D =$

*) Since $x$ is coincidentally equipotential, since when a unit of charge moves in this plane, the electric field does not work.

Fig. 1.

Fig. 2.

Fig. 3.

$= \varphi(x_B) - \varphi(x_D)$. The projection of the vector $\vec{BD}$ onto the axis $OX$ is equal to the difference between the coordinates of the point $D$ and $B$: $l = x_D - x_B$. Thus, for close points $B$ and $D$ we obtain:

$$\varphi(x_B) - \varphi(x_D) \approx E(x_B) \times (x_D - x_B),$$

or

$$E(x_B) \approx -\frac{\varphi(x_D) - \varphi(x_B)}{x_D - x_B}.$$

In order for formula (2) to become accurate, it is necessary to direct the point $B$ to the point $D$ and find the limit to which the right side tends when the points move together indefinitely:

$$E(x_B) = -\lim_{x_D \to x_B} \frac{\varphi(x_D) - \varphi(x_B)}{x_D - x_B}.$$

It is easy to see that the right side of formula (3) is an arbitrary potential taken with the opposite sign. Thus, in a non-uniform electric field, the relationship between potential and direction at each point is as follows:

$$E(x) = -\varphi'(x).$$

The minus sign in formula (4) means that the potential decreases along the field line: since the projection of the direction on the field line is $E(x) > 0$, $\varphi'(x) < 0$, which means the potential decreases.

If we direct the graph of the dependence of $\varphi$ on $x$, then the tangent of the angle of inclination $\alpha$ of the tangent to the graph at each point is equal to an arbitrary $\varphi'(x)$ at this point (Fig. 3). Therefore, we can say that the direction of the electric field is determined by the slope of the tangent to the potential graph.

Let us now consider several specific problems.

Task 1. A sphere of radius $R$ has a charge $Q$. Find dependency

⟦folio 40⟧

tension and placed on the distance r from the center of the sphere. Draw graphs.

Let us first find the direction of the field. There is no electric field inside the sphere: at $r < R$ $E = 0$. Outside the sphere, the direction of the field is the same as that of an exact charge Q placed at the center of the sphere: at $r > R$ the projection of the direction to the chosen direction from the center is $E = \frac{1}{4\pi\varepsilon_0} \frac{Q}{r^2}$, where $\varepsilon_0$ is the electric constant. On the surface of the sphere, at $r = R$, the rolling pin experiences an electric field $\Delta E = \frac{1}{4\pi\varepsilon_0} \frac{Q}{R^2}$. The dependence of $E$ on $r$ graphics is shown in figure 4, a.

The magnitude of the rolling pin $\Delta E$ can be expressed in terms of the surface charge density $\sigma = \frac{Q}{4\pi R^2}$ (equal to the charge per unit surface area of ​​the sphere):

$$\Delta E = \frac{1}{4\pi\varepsilon_0} \frac{Q}{R^2} = \frac{\sigma}{\varepsilon_0}.$$

Note that this is a general property of the electric field: on a charged surface, its projection onto the normal direction always experiences a rollover $\Delta E = \frac{\sigma}{\varepsilon_0}$, regardless of the shape of the surface.

Let us now find out how the potential $\varphi$ changes depending on $r$. We already know that at any point the tangent of the angle of inclination of the tangent to the graph of the potential must coincide with the value of the projection of the directionality (taken with the opposite sign). At $0 < r < R$ $E = 0$, and therefore at all these points the potential tangent to the graph must be horizontal. This means that in section $0 < r < R$ the potential does not change: $\varphi = const$.

Outside the sphere, at $r > R$, the derivative $\varphi'(r) = -E(r)$ is negative and its magnitude kills with distance $r$. Therefore, the potential must kill with distance, tending to zero at $r \to \infty$. Indeed, the further away the point at which we are looking for the potential is located, the less work there is to carry a unit of charge from this point to infinity. The magnitude of the potential $\varphi$ at $r > R$ is the same as that of an exact charge placed at the center of the sphere:

$$\varphi = \frac{1}{4\pi\varepsilon_0} \frac{Q}{r}.$$

Can a potential experience a rolling pin on the surface of a sphere, that is, at $r = R$? Obviously not. The rolling potential would be aware that when moving a unit charge between two obvious points 1 and 2, the electric field would do finite work: $\varphi_1 - \varphi_2 = E(R) \times (r_2 - r_1)$ must remain finite at $(r_2 - r_1) \to 0$, which is impossible. Thus, the potential does not experience rolling pins.

The graph of $\varphi$ versus $r$ is shown in figure 4, b.

Task 2. A ball of radius R is uniformly charged throughout its entire volume. The total charge of the sphere is Q. Draw graphs on the surface of r versus the center of the sphere.

Such a ball can be imagined as consisting of a large number of thin charged spheres, thrown into one another. Each sphere does not create a field inside itself, but outside it creates a field the same as the exact charge placed at its center. Therefore, outside the ball, at $r > R$, the directivity is the same as the directivity of the field of the exact charge Q placed at the center of the ball:

$$E = \frac{1}{4\pi\varepsilon_0} \frac{Q}{r^2}.$$

Fig. 4.

⟦folio 41⟧

Inside the ball, at a distance $r < R$, the field is created only by spheres with radii from 0 to $r$ (for a sphere of large radius, the considered point is inside them). Therefore, the direction at a distance $r$ from the center of the ball is the same as the direction of the field of the exact charge $Q_r$ placed at the center of the ball, where $Q_r$ is the total charge of all spheres with radii from 0 to $r$, that is, the charge of a ball of radius $r$. If a ball of radius $R$ has a charge $Q$, then a ball of radius $r$ will have a charge $Q_r = Q \frac{r^3}{R^3}$. Thus, inside the ball the direction of the field $E = \frac{1}{4\pi\varepsilon_0} \frac{Q}{R^3} r$ is linear with the distance.

On the surface of the ball, at point $r = R$, the direction does not experience a shock. This is in accordance with the general rule, since the surface charge plane in this case is zero: the ball is charged uniformly, and an infinitesimal charge falls on an infinitely thin layer of the surface.

A plot of $E$ versus $r$ is shown in figure 5, a.

Let us now draw a graph of the potential. The derivative of the potential $\varphi'(r) = -E(r)$ is always negative ($E \ge 0$). Therefore, as $r$ increases, the potential should kill monotonically. At point $r = 0$ the derivative of the potential is zero. Consequently, the tangent to the graph at this point is horizontal: at point $r = 0$ the potential has a maximum. At point $r = R$ neither the potential nor its derivative experiences any jumps. The first follows from the general rule for potential; we have already discussed the second above. Therefore, the curves depicting the dependence of the potential on the distance at $r < R$ and $r > R$ must be conjugated at point $r = R$—smoothly transition into one another without a break. At $r \to \infty$ the potential is $\varphi \to 0$. The graph of $\varphi$ versus $r$ is presented at figure 5, b.

Task 3. Two planes are located parallel to each other at a distance $d$ and charged with surface charge densities $\sigma_1$ and $\sigma_2$, respectively. Draw graphs of the dependence of the field strength and placed on the coordinate $x$ (the OX axis is perpendicular to the plane). Distance between cases of same-same (Fig. 6, a) and dissimilar (Fig. 7, a) charges on planes.

Each plane creates a uniform electric field on both sides of itself, the direction of which is $\vec{E} = \frac{\sigma}{2\varepsilon_0}$. Using the principle of superposition, for the case of single charges we arrive at the graph shown in figure 6, b, and for dissimilar charges - to the graph in figure 7, b. The jumps in intensity again correspond to the general rule:

$$\Delta E = \frac{\sigma}{\varepsilon_0}.$$

The corresponding graphs for potentials are shown in Figures 6, c and 7, c. In certain sections of the dependence, the potential on the coordinate is linear, since the direction of the field is constant. Kinks appear in those places where the field intensity experiences a jump.

Note that in this potential the potential does not tend to zero at $x \to \infty$. This is obviously due to the fact that the plane is infinite. In reality, the dimensions of real plates are always limited; this causes the potential to drop with increasing distance from the plates.

Task 4. Two identical parallel planes have charges $+q$ and $-q$. How does the difference change?

⟦folio 42⟧

potentials U between the plates as the distance d between them increases? Draw a graph of U versus d.

As long as the distance between the plates is significantly less than their sizes, such a system can be considered a flat capacitor. Then U = $\frac{q}{C} = \frac{q}{\varepsilon_0 S}$ is the direction of the linear distance (the initial section at figure 8). This corresponds to the fact that the field direction E = $\frac{U}{d}$ = const.

As soon as the distance between the plates becomes comparable to the dimensions of the plates, an electric field appears outside the space between the plates. Then the so-called edge effects become significant, and the dependence of the potential on distance is quite complex. However, it is qualitatively clear that, due to the weakening of the field in the region between the plates, the direction will increase more slowly than according to the linear law (middle section at figure 8). With a further increase in the distance between the plates, it becomes much larger than their sizes. Then each plate can already be considered an isolated body, and its potential is $\varphi = \frac{q}{C_0}$, where $C_0$ is the capacity of the extended plate. Thus, at very large distances the potentials are placed no longer depend on the distance between the plates (the graph of U versus d at figure 8 has a horizontal asymptote).

Edge effects often turn out to be significant when solving electrostatic problems related to the law of conservation of energy. The distance, for example, is this version of the electron accelerator:

Problem 5. In the plates of a flat capacitor charged to

⟦folio 43⟧

It turns out that such an accelerator will not work - the edge efficiency is not taken into account. Outside the capacitor, there is always a weak electric field that slows down the electron as it moves around the circle. The negative work of the field in this case is exactly equal to the positive work when accelerating an electron in a capacitor: work in an electrostatic field does not depend on the shape of the trajectory. The magnetic field does not do any work (the Lorentz force is perpendicular to the speed of motion of the electron). Therefore, the total work done by all forces acting on the electron, when it returns to the initial point, will be equal to zero, and the kinetic energy of the electron will not change. The accelerator will not work.

Exercises

1. Can there exist an electrostatic field in which the strong lines are parallel straight lines, and the directional absolute value changes only in the direction perpendicular to the lines of force (Fig. 10)?

2. Two concentric metal spheres of radii $R_1$ and $R_2$ have charges $Q_1$ and $Q_2$ respectively. Find the direction and potential of the electric field at an arbitrary distance $r$ from the center of the sphere. Draw graphs of $E$ versus $r$ and $\varphi$ versus $r$. Consider the case of like and unlike charges. What do the graphs look like for case $Q_1 = -Q_2$ (spherical capacitor)?

3. A point charge $q$ is surrounded by a metal sphere of radius $R$ with a charge $Q$. Find the direction of the field and the potential at an arbitrary distance $r$ from the charge $q$, if it is at the center of the sphere; draw graphs of $E$ versus $r$ and $\varphi$ versus $r$. How do the graphs change if the charge is shifted from the center of the sphere? Solve the same problem for the case where the metal sphere is replaced.

4. An electron flies into the space between the plates of a flat capacitor so that its speed makes an acute angle with the direction of the lines of force. Then, when moving in the capacitor, it will slow down and fly out at a lower speed; its kinetic energy will decrease. Will this increase the energy of the capacitor?

5. Two identical capacitors of capacity $C$ each, one of which is charged to the direction $U$, and the second is not charged, are connected in parallel. Find the energy of the system before and after connecting the capacitor. Why are these energies not equal?

6. A point charge $q$ is located outside an uncharged metal sphere of radius $R$ at a distance $d$ from its center. Find the potential of the sphere.
