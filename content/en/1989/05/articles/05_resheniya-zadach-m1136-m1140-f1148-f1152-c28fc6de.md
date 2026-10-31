---
id: 1989-5-resheniya-zadach-m1136-m1140-f1148-f1152-c28fc6de
issue: kvant_1989_5
year: 1989
number: "5"
title: Solutions to problems M1136—M1140; F1148—F1152
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 33
page_last: 41
page_labels: 31-39
tag: MPO6
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5c3ab078a3454e1202187d43568db8ecb64084ec1503c992bf950069bdc223e3
prompt_sha256: draft-1
translated_from: content/ru/1989/05/articles/05_resheniya-zadach-m1136-m1140-f1148-f1152-c28fc6de.md
source_content_sha256: 1f2a96291c9d87c461f9ebd79b6c2b9c9ddebcab120e5bab87e947a94937f4ab
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 31⟧

$R = 3 \cdot 10^9 R_0$ ($R_0$ is the radius of the Earth’s orbit) mass $M_1 = 1,5 \cdot 10^{11} M_0$ ($M_0$ is the mass of the Sun) is concentrated from the center of the Galaxy. Meanwhile, the orbital period of stars located at the indicated distance from the Galactic center is $T = 3,75 \cdot 10^8$ years. Determine the “hidden mass” of the Galaxy, i.e. the mass of invisible objects inside a sphere of radius $R$. When calculating the motion of stars, the mass of the Galaxy can be considered concentrated at its center.

V. E. Belonuchkin

F1171. Electric diopole - two particles with identical masses $m$ and charges $+q$ and $-q$, enclosed at the ends of a rigid weightless rod of length $l$, rotate with an angular velocity $\omega$ in a horizontal plane around a vertical axis passing through the center $O$ of the diopole (Fig. 3). At some points, a constant magnetic field with induction $B$ directed vertically is turned on. Describe the established motion of the diopole.

S. Edrakovic (SFRY)

F1172. The inner surface of the sphere is covered with a diffuse reflector with a reflection coefficient of $r = 0,9$. The angular distribution of light reflected by a diffuse reflector is described by Lambert's law:

$$\Delta N = \frac{N}{\pi} \cdot \cos \theta \cdot \Delta \Omega,$$

where $N$ is the total number of reflected photons, $\Delta N$ is the number of reflected photons in a small solid angle $\Delta \Omega$, making an angle $\theta$ with the normal to the reflecting area. A precise light source will flash in the center of the sphere. What fraction of photons will escape through the very small rejection present in the sphere?

S. A. Khorozov

Problem solutions
M1136—M1140, F1148—F1152

M1136 *. Prove the inequality for non-negative numbers $A$, $M$, $S$
$$3 + (A + M + S) + \left( \frac{1}{A} + \frac{1}{M} + \frac{1}{S} \right) + \left( \frac{A}{M} + \frac{M}{S} + \frac{S}{A} \right) \geq \frac{3(A + 1)(M + 1)(S + 1)}{AMS + 1}.$$

Proof of the property of an artificial (but also skillful!) identical transformation for weights. Multiplying the difference between the left and right sides of the inequality by their common denominator $AMS(AMS + 1)$ and the product of the rearrangement of terms, we obtain
$$A^2M^2S^2(A + M + S) - 2AMS(AM + MS + SA) + (AM^2 + MS^2 + SA^2) + AMS(AM^2 + MS^2 + SA^2) - 2AMS(A + M + S) + (AM + MA + AS) = AM(M + 1)(SA - 1)^2 + MS(S + 1)(AM - 1)^2 + SA(A + 1)(MS - 1)^2 \geq 0,$$
Moreover, equality is obviously achieved only for $A = M = S = 1$. This solution was reported to the author of the problem by a prominent specialist in cyclic inequalities, Professor P. H. Dinanada from Singapore.

⟦folio 32⟧

M1137. In a convex null pad, all angles are equal and from a certain point located inside the null pad, all its sides are visible at equal angles. Prove that this null is correct.

Let in the $n$-gon $A_1A_2...A_n$ (see figure) all angles are equal, i.e., each of them is equal to $180^\circ(n-2)/n$, and the point $M$ is such that $\angle A_1MA_2=\angle A_2MA_3=\dots=\angle A_nMA_1=360^\circ/n$.

Then all triangles $A_1MA_2, A_2MA_3, \dots, A_nMA_1$ are similar: if $\angle MA_1A_2=\alpha, \angle A_1A_2M=\beta=180^\circ-360^\circ/n-\alpha, \angle MA_2A_3=180^\circ(n-2)/n-\beta=\alpha, \angle A_2A_3M=180^\circ-360^\circ/n-\alpha=\beta$, etc., therefore $\frac{MA_1}{MA_2}=\frac{MA_2}{MA_3}=\dots=\frac{MA_{n-1}}{MA_n}=\frac{MA_n}{MA_1}=k$.

Variable these relations, we obtain that $k^n=1$, i.e. $k=1$. (You can also argue “by contradiction”: if $k<1$, then $MA_1<MA_2<\dots<MA_n<MA_1$; if $k>1$, then $MA_1>MA_2>\dots>MA_n>MA_1$—a contradiction.) It follows that $\alpha=\beta$ and $M$ are the centers of the regular $n$-gon $A_1A_2...A_n$.

K. P. Kokhas

M1138*. Prove that for any natural number $n$ between the numbers $n^2$ and $n^2+n+3\sqrt{n}$ there are three natural numbers such that the product of two of them is divisible by the third.

For $n=1$: between 1 and 5 - numbers 2, 3, 4;
For $n=2$: between 4 and 6+3$\sqrt{2}$ - numbers 6, 8, 9 (or 5, 8, 10);
For $n=10$: $x=2$ and $a=8\cdot13=104,$ $b=9\cdot12=108,$ $c=9\cdot13=117$.

To appreciate the non-trivial nature of this problem, let's take $n=10$: try to quickly find three numbers between 100 and $[110+3\sqrt{10}]=119$, one of which divides the product of the other two! (Such a triple is indicated in the margin.) Note that for $n=1$ and $n=2$ the statement of the problem is estimated indo. For each integer $n>2$ we will look for the required three numbers in the form

$$a=(n-x)(n+x+1)=n^2+n-x^2-x,$$
$$b=(n-x+1)(n+x)=n^2+n-x^2+x,$$
$$c=(n-x+1)(n+x+1)=n^2+2n+1-x^2,$$

where $x$ is an integer; it is clear that in this case $ab$ will be divisible by $c$. Let $x$ be the largest integer for which $x^2+x<n$. Then $n^2<a<b<c$, and it remains to prove that $c<n^2+n+3\sqrt{n}$, i.e., that $n+1-x^2<3\sqrt{n}$. Suppose, for example, that $x^2\leq n-3\sqrt{n}+1$. Then $x<\sqrt{n-3/2}$ (beginning with $x^2\geq n-3\sqrt{n}+9/4$), and therefore $x+1<\sqrt{n-1/2}$. But in this case $(x+1)^2+(x+1)<(n-\sqrt{n+1/4})+(\sqrt{n-1/2})<n$, which contradicts the choice $x$.

L. D. Kurlyandchik

M1139. a) The surface of a convex polyhedron can be cut into several squares. Prove that this polyhedron has at most 8 vertices.

Our reasoning is based on the concept of curvature of a polyhedral angle - this is the name given to the quantities $2\pi-\sigma$, where $\sigma$ is the sum of its plane angles. Curvature is discussed in detail in the article by S. L. Tabachnikov in this issue of the journal, in part, the “Descartes formula” was proven there - the sum of the curvatures of all polyhedral angles of a convex polyhedron is equal to $4\pi$.

⟦folio 33⟧

6) What is the maximum number of vertices that a convex polyhedron can have, the surface of which can be cut into regular triangles?

a) The sum of plane angles at any vertex of a given polyhedron can only be equal to π/2, π or 3π/2. In fact, it is less than 2π, since the polyhedral angle at any vertex is convex. At the same time, this angle is formed by bending and gluing several right angles (corners of squares) and, perhaps, expanding the angle (if the vertex of the side of one square is considered). Therefore, the sum of its plane angles is a multiple of π/2. Thus, the curvature of a polyhedral angle at any vertex is not less than π/2, and according to Descartes’ formula, the number of vertices does not exceed 4π:(π/2)=8. An example of an 8-vertex is a cube.

6) Answer: 12. In the same way as in point a), it is proved that the curvature of a polyhedral angle at any vertex is not less than π/3, which means that the number of vertices does not exceed 4π:(π/3)=12. An example of a 12-vertex is the correct ikasdr.

V. E. Matizen

M1140. Let's draw one several intersecting curves on the plane (curves can have self-intersection points, Fig. 1). At each intersection point, there are two ways to perform a “reconstruction” (Fig. 2). If you perform a restructuring at all intersection points, you will get several intersecting curves (Fig. 3).
a) Prove that the number of intersecting curves that can be obtained is not greater than the number of regions into which the original curves divided the plane (there are 7 such regions in figure 1).

a) Let initially these curves divide the plane into areas V₁, V₂,...,Vₙ. Each of the new, rebuilt curves bounds a region consisting of several Vᵢ regions. Let us select those of the new curves that have no other new curves inside them, and mark inside each of them one of the region Vᵢ (Fig. 5). Now we will hundred these curves, among the remaining words we will select “minimal” (within which there are no other curves) and within each of them we will mark one of the areas Vᵢ that were not offset in the first step. (Obviously, it will find such areas.) Continuing in the same spirit, we associated with each new curve the areas Vᵢ inside it, offset at the appropriate step, and different areas will be associated with different curves. This means that the number of curves is not greater than the number of the region.

6) Color the original map in a checkerboard pattern, i.e., so that the outer area is white and the color of the area changes when crossing the border (Fig. 6, a). (The existence of such a coloring is easy to prove by induction. By adding one non-self-intersecting closed circuit to an already colored map,

⟦folio 34⟧

6) Is it always possible to make rearrangements so that the result is one curve?
c) Let us choose the direction of traversal on each curve and make changes in accordance with this direction so that the arrows “repel” each other (Fig. 4). can the result be one curve?

that curve, all the areas that fall within it or the parts cut off by this curve from the old areas are repainted in a different color; external coloring is preserved. In this case, the checkerboard order of colors will not be disturbed. And any closed curve can be divided into non-self-intersecting closed pieces.) Let us construct a graph (Fig. 6, 6) using a “chessboard coloring”, assigning one point to each black region - these will be the vertices of the graph, and to each intersection point of the curve - one edge: it connects the vertices corresponding

Fig. 6.

Fig. 7.

Fig. 8.

black areas that are adjacent to this point. Two methods of reconstruction are depicted on the graph by two operations: stripping an edge and contracting an edge to a point (Fig. 7).

It is clear that on the graph of the original picture it is possible to extend part of the edges so that it turns into a “tree,” that is, a graph that does not have closed chains of edges. The remaining edges can be sequentially contracted to a point. The corresponding rearrangement sequence results in a single black region. Its boundary is the desired curve (Fig. 8).

Interestingly, from the graph it is possible to reconstruct the corresponding set of curves. Think, for example, what curves correspond to the graphs shown in figure 9.

c) Each rearrangement transforms a set of oriented curves into a set of oriented curves. Let us assume that there is a sequence of rearrangements, the result of which will be a single curve. Then, before performing the last rearrangement, we arrange a set of oriented curves with a single intersection point. Such a set may consist of a single curve, the “figure of eight” shown in figure 10. However, rearranging it results in two rather than one curve.

S. L. Tabachnikov

F1148. The cylinder, with the help of a thread, the second end of which is fixed, is placed on the main inclined plane making an angle α with Zo-

Consider the moment in time when the thread is vertical. Due to the inextensibility of the thread, the lower point of its vertical section and the point of cylinder A in contact with it have the same, horizontally directed speed $\vec{v}_A$. Let us imagine the motion of the cylinder as the sum of translational motion with

⟦folio 35⟧

horizon, as shown in figure 1. At the moment when the thread was vertical, the angular velocity of the brauchen cylinder was equal to $\omega$. Determine what is equal at this moment: a) the speed of the cylinder axis; b) the speed of a point on the cylinder touching the inclined plane. The radiduce of a cylinder is $R$.

Fig. 1.

Fig. 2.

F1149. Thin long copper conductors are randomly thrown onto the conducting rails of the Tserrusch railway, closing the rails. Estimate the resistance between the rails if the distance between them is $l=5$ cm, the diameter of the conductor is $d=0,2$ mm, its length is $h=30$ cm, $N=100$ conductors are thrown.

The speed of its axis $\vec{v}_0$, directed parallel to the inclined plane (at an angle $\alpha$ to the horizon), and rotates clockwise around the axis with an angular velocity $\omega$. In this case, the speed of the point is $A$ (Fig. 2, a)

$$\vec{v}_A = \vec{v}_0 + \vec{v}'_{\text{bp}}.$$

As is easy to see, $v'_{\text{bp}} = \omega R$, $\vec{v}_A \perp \vec{v}'_{\text{bp}}$, from where we get

$$v_0 = \frac{\omega R}{\sin \alpha}.$$

A similar correspondence can be written for the point $C$ of contact of the cylinder with the inclined plane (Fig. 2, b):

$$\vec{v}_C = \vec{v}_0 + \vec{v}'_{\text{bp}},$$

or in projections onto the direction along the inclined plane:

$$v_C = v_0 - \omega R,$$

where

$$v_C = \frac{\omega R}{\sin \alpha} - \omega R = \omega R \frac{1 - \sin \alpha}{\sin \alpha}.$$

As an additional question, we suggest that you independently find the velocity values ​​of the point $A$ of the cylinder.

The step resistance of one conductor making an angle $\alpha (0 < \alpha < \pi)$ with the rails is equal to

$$r_i = \rho \frac{l_i}{S} = \rho \frac{l/\sin \alpha_i}{\pi d^2/4}.$$

For the total resistance between the rails, the correspondence is made

$$\frac{1}{R_{\text{o6ш}}} = \sum \frac{1}{r_i} = \sum \frac{\pi d^2 \sin \alpha_i}{4\rho l} = \frac{\pi d^2}{4\rho l} N(\sin \alpha_i)_{\text{cp}}.$$

The average value of $\sin \alpha_i$ can be found like this:

$$\left(\sin \alpha_i\right)_{\text{cp}} = \frac{1}{\pi} \int_0^\pi \sin \alpha \cdot d\alpha = \frac{2}{\pi}.$$

Then

$$\frac{1}{R_{\text{o6ш}}} = \frac{\pi d^2}{4\rho l} N \frac{2}{\pi} = \frac{d^2 N}{2\rho l},$$

and finally

$$R_{\text{o6ш}} = \frac{2\rho l}{d^2 N} \approx 4 \cdot 10^{-4} \text{ Ом.}$$

⟦folio 36⟧

Comment. We calculated the average value of the total resistance. Depending on how the conductors fall onto the rails, the resistance values ​​may differ more or less from the found value. Try to simulate the phenomenon using a personal computer, using a random number sensor, and evaluate the possibility of the results.

A. R. Zilberman

F1150. A body is supplied to an ideal monatomic gas enclosed inside an oil bubble. Find the warm state of the gas (per 1 mole) in this process if the pressure outside the bubble can be claimed.

The heat capacity $C$ of a physical system is the ratio of the amount of heat $\Delta Q$ that must be supplied to it to increase the temperature by $\Delta T$ to this temperature change:

$$C = \frac{\Delta Q}{\Delta T}.$$

Heat capacity can be a function of the heat transfer process, i.e., it depends on the volume $V$ of the system or on its temperature $T$. Therefore, under $\Delta Q$ and $\Delta T$ quite small (mathematically infinitesimal) values ​​of the amount of heat and temperature changes will be understood.

For a mole of an ideal gas locked under a film in a bubble, the supplied amount of heat $\Delta Q$ goes to change its internal energy $\Delta U$ and perform work $\Delta A$ against surface tension forces:

$$\Delta Q = \Delta U + \Delta A = \frac{3}{2} R \Delta T + p \Delta V.$$

Here $R$ is a universal constant, $p$ is the gas pressure equal to the pressure created under the surface tension film, $\Delta V$ is the change in the volume of the bubble when the gas in it is heated.

The pressure $p$ is determined by the surface tension coefficient $\sigma$ and the bubble radius $r$:

$$p = \frac{4\sigma}{r}.$$

This formula can be obtained as follows. Let us mentally divide the bubble into two equal halves and consider the conditions of mechanical equilibrium. The gas pressure forces that tear the ball into halves are $p \cdot \pi r^2$. The surface tension forces holding them together are $2\sigma \cdot 2\pi r$. Equating these forces, we obtain the given formula for pressure.

Now let us connect the work of the gas $p\Delta V$ with the change in its temperature $\Delta T$. Since the volume of the bubble and the pressure in it depend on the radius, it is necessary to find a connection between the change in the radius of the bubble $\Delta r$ and the change in temperature $\Delta T$. From the ideal gas equation of state $pV = RT$ we have

$$p\Delta V + V\Delta p = R\Delta T.$$

⟦folio 37⟧

Changes in volume $\Delta V$ and pressure $\Delta p$ are related to changes in radius $\Delta r$ by the following formulas:

$$\Delta V = 4\pi r^2 \Delta r, \quad \Delta p = -\frac{4\sigma}{r^2} \Delta r.$$

The postural equation of state gives

$$\frac{2}{3} \cdot 16\pi r \Delta r = R \Delta T.$$

Thus, the gas work

$$\Delta A = p \Delta V = R \Delta T - V \Delta p = R \Delta T + \frac{R \Delta T}{2} = \frac{3}{2} R \Delta T.$$

Finally we get

$$C = \frac{\Delta Q}{\Delta T} = \frac{\Delta U + \Delta A}{\Delta T} = \frac{3}{2} R + \frac{3}{2} R = 3R.$$

As can be seen from the calculation, half of the supplied heat goes to increase the gas temperature, and the second half is converted into surface energy of the film.

A. A. Sheropov

F1151*. An electrostatic voltmeter is a flat capacitor, one of the plates of which is fixed stationary, and the other can move, remaining on a parallel surface. Movable plate using a spring with a stiffness of $k = 10$ N/m. The initial distance between the plates is $d = 3$ cm, the area of ​​each plate is $S = 0,5$ m$^2$. Calculate the voltmeter scale. What is the maximum voltage that can be measured with it? Consider separately the case when the high temperature is very small and quite large.

Suppose that the movable plate has shifted by $x$ and the distance between the plates has become $d - x$. In this position, two forces act on the plate. This is electric force

$$F_{\text{эл}} = q \frac{E}{2} = \frac{\varepsilon_0 SU}{d - x} \frac{U}{2(d - x)} = \frac{\varepsilon_0 SU^2}{2(d - x)^2}$$

(here $q$ is the plate charge, $E$ is the field voltage in the capacitor, $U$ is the voltage between the plates) and the elastic force

$$F_{\text{упр}} = kx.$$

Let us write down the condition for equalizing the plate:

$$F_{\text{эл}} = F_{\text{упр}},$$ or $$\frac{\varepsilon_0 SU^2}{2(d - x)^2} = kx.$$

From here we get the equation for the electrostatic voltmeter scale:

$$U = \sqrt{\frac{2k}{\varepsilon_0 S}} x(d - x)^2,$$ where $0 \leq U < U_{\text{max}}$.

Let's find $U_{\text{max}}$. To do this, we examine the expression $U^2 = 2kx(d - x)^2 / (\varepsilon_0 S)$ to the maximum:

$$(U^2)' = \left(\frac{2k}{\varepsilon_0 S}\right)((d - x)^2 - 2(d - x)x) = 0,$$ and $x_{\text{max}} = \frac{d}{3}$.

Then

$$U_{\text{max}} = U(x_{\text{max}}) = \sqrt{\frac{8}{27} \frac{kd^3}{\varepsilon_0 S}} \approx 4,3 \cdot 10^3 \text{ B}.$$

⟦folio 38⟧

Obviously, at high friction $U_{\text{max}}$ there is a maximum variable voltage.

At low friction the calculation is satisfied. Indeed, from the equilibrium condition of the movable plate it follows that there are two equilibrium positions - on figure 1 these are $x_1$ and $x_2$, and $x_1$ corresponds to stable, and $x_2$ to unstable equilibrium. If the plate leaks $x_2$, then it will go further until it comes into contact with the stationary plate. This is precisely what limits the possibility of a variable voltage range of $U_1 < U_{\text{max}}$. Let's find her.

Let the voltage across the capacitor be $U_1$. The moving plate begins to accelerate and is left to travel a distance $x_2$. Initial capacitor energy

$$W_0 = \frac{\varepsilon_0 S}{2d} U_1^2.$$

The charge passing through the source (Fig. 2)

$$\Delta q = \frac{\varepsilon_0 S}{d - x_2} U_1 - \frac{\varepsilon_0 S}{d} U_1,$$

and source work

$$A = \Delta q U_1 = \left( \frac{\varepsilon_0 S}{d - x_2} - \frac{\varepsilon_0 S}{d} \right) U_1^2.$$

In position $x_2$ capacitor energy

$$W_1 = \frac{\varepsilon_0 S}{2(d - x_2)} U_1^2$$

and spring energy

$$W_{\text{np}} = \frac{k x_2^2}{2}.$$

Let's write down the energy balance: $W_0 + A = W_1 + W_{\text{np}}$, from where, after the simplified one, we populate

$$\frac{\varepsilon_0 S}{d(d - x_2)} U_1^2 = k x_2.$$

But $x_2$ is the equilibrium position, i.e.

$$k x_2 = \frac{\varepsilon_0 S}{2(d - x_2)^2} U_1^2.$$

From here

$$x_2 = \frac{d}{2}.$$

This value $x_2$ corresponds to stress $U_1$, which is the maximum stress for the case of very low friction:

$$U_1 = U(x_2) = \sqrt{\frac{1}{4} \varepsilon_0 S} \approx 3,9 \cdot 10^3 \text{ B}.$$

A. R. Zilberman

⟦folio 39⟧

F1152. Behind the lens at a distance of $L=4$ cm (large focal length) there is a flat mirror located perepredkulinarno to the main optical axis. In front of the lens, also peredicular to the main optical axis, there is a sheet of checkered paper (Fig. 1). On this sheet, images of its cells are obtained at two positions of the sheet relative to the line. These positions differ by $l=9$ cm. Determine the focal length of the line.

One of the positions of the sheet, when its cells - let's call them an object - are displayed by the optical system on it, is quite obvious. Indeed, if the first image created by the lens turns out to be exactly in the plane of the mirror, then during the secondary passage of the rays through the lens (after reflection from the mirror) they will converge exactly in the plane of the sheet. Thus, in this case, the distance from the line to the image of the object being created is equal to

$$f_1 = L.$$

(1)

The second position of the sheet is also not so difficult to find. It is easy to verify that if the sheet is in the focal plane of the line, then the conditions of the problem will be fulfilled. Indeed, rays coming from each line of the focal plane are converted into a parallel beam after passing through the lens. Reflected from the mirror -

Fig. 1.

Fig. 2.

Yes, these rays will remain parallel and, having passed through the lens, will converge in its focal plane. Thus, the second position of the sheet is determined by the condition

$$d_2 = F.$$

(2)

Relations (1) and (2) can be obtained more strictly. According to the conditions of the problem, rays of light from paper pass through a lens, are reflected from a mirror, pass through the lens again and fall on the same paper. Such a system is equivalent to the optical system shown in figure 2, where both lines are the same.

The image created by the first lens can be either between the lenses or to the right of lens $J_2$. In the first case, this image is a valid object for the second lens. And we can write the equation:

$$\frac{1}{d'} + \frac{1}{f'} = \frac{1}{F}, \quad \frac{1}{d''} + \frac{1}{f''} = \frac{1}{2L - f'} + \frac{1}{d'} = \frac{1}{F},$$

whence follows

$$\frac{1}{d'} + \frac{1}{f'} = \frac{1}{2L - f'} + \frac{1}{d'},$$ and $f' = L$.

In the second case, the image created by the first lens is the minimum object for the second lens,

(For the ending see p. 42)
