---
id: 1975-7-resheniya-zadach-m296-m299-f303-f311-f299-a4ec2acc
issue: kvant_1975_7
year: 1975
number: "7"
title: Solutions to problems M296—M299; F303—F311, F299
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 52
page_labels: 42-50
tag: 9HEV
lang: en
source: kvant_digital
extraction: vision
content_sha256: a62519b08e3d148a473e0dbdecf3f7b7ff9fd768e3da8f85c3f53fdae3ee96f9
prompt_sha256: draft-1
translated_from: content/ru/1975/07/articles/09_resheniya-zadach-m296-m299-f303-f311-f299-a4ec2acc.md
source_content_sha256: 85d50e5657a08c416736a1f8cf603910259b29ddccadc8daa1eb1dd34c4156d9
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

⟦rubric⟧
Problem solutions

## Problem solutions
M296 — M299; F303 — F311, F299

**M296.** An n × n table contains n² numbers whose sum is non-negative. Prove that you can rearrange the columns of the table so that the sum of n numbers along the diagonal going from the lower left to the upper right is non-negative.

⟦figure⟧
Fig. 1.

**M299.**\*) For what n can a regular n-gon be placed on a sheet of paper in a line so that all the vertices lie on the lines? (Lines are parallel straight lines located at equal distances from each other.)

⟦column⟧

Let's call this table transformation a *cyclic shift*: the 1st column is moved to the place of the 2nd, the 2nd to the place of the 3rd, . . . , finally, the last, nth - in place of the 1st. Let us denote by $s_0$ the sum of numbers that are on the diagonal of the table (in red cells on Fig. 1), by $s_1$ the sum of numbers that will fall on the diagonal after a cyclic shift (in blue cells), by $s_2$ the sum of numbers that will fall on the diagonal if the cyclic shift is repeated again (in yellow cells), and in general by $s_k$ is the sum of numbers that will fall on the diagonal if the cyclic shift is performed k times. It is clear that the sum of all numbers in the table is equal to

$$s = s_0 + s_1 + \ldots + s_{n-1},$$

because if you do a cyclic shift 0, 1, . . . , n - 1 time, then during this time each number in the table will be on the diagonal exactly once (and if you do it n times, you will get the original arrangement).

By condition, s is non-negative, therefore, some $s_k$ must be non-negative. Having performed a cyclic shift k times, we obtain the required permutation of columns.

◆

Let's assume that we managed to place a regular n-gon on lined paper. Let O be the center of this polygon. Let's rotate the plane through an angle $360°/n$ with the center at point O and draw in one drawing both the previous and new (resulting after the rotation) parallel lines (Fig. 2; there is no need to draw the n-gon twice, since it is aligned with itself after such a rotation). Now each vertex of the n-gon lies at the intersection point of two grid lines, that is, the n-gon was placed in such a way that all its vertices fell into the nodes of a certain lattice; but, as proven in the article by A. A. Egorov “Lattices and regular polygons” («Kvant», 1974, No. 12), this is only possible with n=3,4 or 6.

Thus, only with these n can a regular n-gon be placed on lined paper.

N. B. Vasiliev

⟦figure⟧
Fig. 2.

---
*) The solution problem M297 is contained in the note by V. M. Fishman “Solving problems using geometric transformations”, problem M298 - in the note by V. N. Vaguten “Close fractions”, which will be published in «Kvant» No. 8, 1975.

⟦folio 43⟧

**F303.** *A point source of light is located at some distance under a thin collecting lens (Fig. 3). Where and how should a plane mirror be installed so that a parallel beam of light emerges from the lens in the direction shown by the arrow? Construct the course of rays.*

⟦column⟧

Let $F'F''$ be the focal plane of the lens. Let us draw a secondary optical axis $AA'$ parallel to the direction specified by the arrow (see Fig. 3). If the light source is located in the focal plane of the lens at the point $S'$ of its intersection with the $AA'$ axis, then the lens collects its rays into a parallel beam directed along the $AA'$ axis, that is, a parallel beam of light emerges from the lens in the direction indicated by the arrow.

In our case, the source for the lens will be the image of the source $S$ in a plane mirror. To this image

⟦figure⟧
Fig. 3.

was at point $S'$, the mirror should be located in the middle of the segment $SS'$ perpendicular to it. The path of the rays is shown in figure 3.

◆

**F304.** *The pump supplies a mass $m$ of water per hour to a height $H$ through a pipe with a diameter of $d$. What should be the power of pump $N$? Is it possible to supply a mass of $m$ water per hour to a height of $H$ using a pump of lower power?*

⟦figure⟧
Fig. 4.

⟦column⟧

During time $\Delta t$, the pump supplies a mass of water $m\Delta t$ to height $H$, performing work $A$ equal to the change in the mechanical energy of water. Since the water below did not have kinetic energy, and the pump “drives” it through the pipe at a certain speed $v$, then

$$A = \frac{(m\Delta t)v^2}{2} + (m\Delta t)gH.$$

Therefore, the pump power is $N = \dfrac{mv^2}{2} + mgH$.

Let's find the speed $v$. During time $\Delta t$, a volume of water $V = v\Delta t\dfrac{\pi d^2}{4}$ passes through a cross-section of a pipe of area $S = \dfrac{\pi d^2}{4}$, the mass of which is equal to $v\Delta t\dfrac{\pi d^2}{4}\rho$ ($\rho$ is the density of water). On the other hand, this mass is equal to $m\Delta t$, that is, $v\dfrac{\pi d^2}{4}\rho = m$, hence $v = \dfrac{4m}{\pi d^2\rho}$.

Thus, the pump power

$$N = \frac{8m^3}{\pi^2 d^4\rho^2} + mgH.$$

Is it possible to supply the same mass of water per hour to the same height $H$ using a pump of lower power? From the expression for $N$ it is clear that the larger the diameter of the pipe $d$, the less the required pump power.

But you can reduce the amount of required power without changing the values ​​of the parameters specified in the problem statement. Let's cut off the entire upper part of the pipe at a certain height $h \ll H$. Let the water flow out of the rest of the pipe

⟦folio 44⟧

with some speed $u$ (see Fig. 4).

The pump power required for this is $N' = \frac{mu^2}{2}$ (since $h \ll H$, potential energy $mgh$ is neglected). In order for water to rise to a height of $H$, it is necessary that its speed when leaving the pipe be no less than $u = \sqrt{2gH}$. Thus, it is possible to supply a mass of water $m$ per hour to a height $H$ using a pump with a power

$$N' = m \frac{u^2}{2} = mgH < N.$$

F305. An L-shaped glass capillary of radius $r$, completely wetted with water (Fig. 5), was lowered into a vessel with water. The dependence of the coefficient of surface loading of water on temperature is shown in figure 6. In what temperature range will all the water be removed from the vessel if $r=0,1$ mm, $h=14,1$ cm $uH=15$ cm? Neglect the thickness of the glass.

In order for water to flow out of the vessel through the capillary, it must first of all rise along the right elbow of the capillary to its horizontal section. At the initial moment, the height of the rise should be equal to $h$, and at the end, when almost all the water has already flown out of the vessel, the liquid should rise to a height of $h+l$, where $l$ is the height of the initial water level in the vessel. This is possible if the surface tension coefficient $\sigma$ is such that the height of the water rise in a capillary of radius $r$ is not less than $h+l$, that is

$$\frac{2\sigma}{\rho gr} > h+l,$$ or $\sigma > \frac{1}{2} \rho gr (h+l).$

Having risen in the right knee, water fills the left knee, at the end of which a convex meniscus is formed, and can hold a certain column of water. The water in the upper part of the capillary (from its horizontal section to the water level in the vessel) is in equilibrium, therefore the forces of additional pressure under the meniscus must hold a column of water with a height of $H+l$ at the initial moment and a height of $H$ at the final moment. The radius of the meniscus cannot be less than the radius of the capillary $r$, which means that the additional pressure under the meniscus cannot be greater than $\frac{2\sigma}{r}$. Consequently, water will flow out of the capillary if the hydrogrowth pressure is greater than the additional pressure, that is

$$\rho g (H+l) > \frac{2\sigma}{r},$$ or $\sigma < \frac{1}{2} \rho gr (H+l).$

Thus, water will flow out of the vessel through the capillary if

$$\frac{1}{2} \rho gr (h+l) < \sigma < \frac{1}{2} \rho gr (H+l),$$

or

$$\frac{1}{2} \rho gr h < \sigma < \frac{1}{2} \rho gr H.$$

In order to move from the range of surface tension coefficient values ​​to the temperature range, we use the graph shown on figure 6. From the graph it is clear that the dependence of $\sigma$ on $T$ is linear, that is

$$\sigma = \sigma_0 + \alpha T,$$

where $\sigma_0 = 76 \text{ дин/cм}$. At temperature $T=20^{\circ}\text{C}$ $\sigma = 73 \text{ дин/cм}$, therefore,

⟦folio 45⟧

$$73 \text{ дин/см} = 76 \text{ дин/см} + \alpha \cdot 20 \text{град},$$
where
$$\alpha = -0{,}15 \text{ дин/(см} \cdot \text{град)}.$$

The boundary values ​​of the range $\sigma$ are equal to

$$\sigma_{\min} = \frac{1}{2}\rho g r h = 70{,}5 \text{ дин/см},$$

$$\sigma_{\max} = \frac{1}{2}\rho g r H = 75 \text{ дин/см}.$$

Now let’s write equation (*) for temperatures $T_{\max}$ and $T_{\min}$, corresponding to values ​​$\sigma_{\min}$ and $\sigma_{\max}$:
$$70{,}5 = 76 - 0{,}15\,T_{\max},$$
$$75 = 76 - 0{,}15\,T_{\min}.$$
From here
$$T_{\max}\approx 36{,}7°C \quad \text{и} \quad T_{\min}\approx 6{,}7°C.$$

So, all the water will flow out of the vessel through the capillary if
$$6{,}7°C < T < 36{,}7°C.$$

⟦figure⟧
Fig. 7.

F306. figure 7 shows a diagram of a thermal wattmeter $(r_1 \ll r,\ r_1 \ll R_{\mathrm{н}})$. A thin wire $AB$, heated by current, is thrown over a block pulled upward by a spring. There is an arrow attached to the block that turns when you turn the block. Show that the rotation of the device arrow is directly proportional to the current power $P$ consumed by the load $(R_{\mathrm{н}})$.

Consider that: 1) the amount of heat that the heated wire gives off to the environment is proportional to the temperature difference between the wire and the environment; 2) the change in the resistance of sections of wire $AB$ due to elongation and changes in their temperature is negligible.

⟦figure⟧
Fig. 8.

⟦column⟧

◆

The angle of rotation of the device pointer is proportional to the difference in the elongations of the wire sections $AC$ and $CB$. These extensions are determined by the currents flowing through the corresponding sections.

Let us denote by $I_0$ the current flowing through the load $R_{\mathrm{н}}$, and connect with it the currents $I_1$ and $I_2$ flowing through sections $CB$ and $AC$. Let us redraw the electrical circuit for connecting the wattmeter, as shown in figure 8. Since the resistance of the wire is much less than the resistance $r$, we will assume that the resistances of sections $AC$ and $CB$ of this wire are included in the values $r$, so the resistances of the circuit sections $DC$ and $KC$ are equal $r$.

Since the voltages at resistance $R_{\mathrm{н}}$ and at resistance $r$ of section $KC$ are equal, then

$$I_0 R_{\mathrm{н}} = I_1 r, \quad \text{или} \quad I_1 = I_0 \frac{R_{\mathrm{н}}}{r}.$$

Current $I_2 = \dfrac{U_{DC}}{r}$, where $U_{DC}$ is the voltage at section $DC$. It is equal to $U_{DC} = U_{KC} + I_3 r_1$, where $U_{KC} = I_0 R_{\mathrm{н}}$, and

$$I_3 = I_0 + I_1 = I_0\left(1 + \frac{R_{\mathrm{н}}}{r}\right).$$

Then

$$I_2 = I_0\left(\frac{R_{\mathrm{н}} r_1}{r^2} + \frac{r_1}{r} + \frac{R_{\mathrm{н}}}{r}\right).$$

Let us now see how the elongation of the wire is related to the current that flows through this wire. At thermal equilibrium, the amount of heat released in the wire is equal to the amount of heat given to the medium:
$$I^2 R = k\Delta t,$$
where $\Delta t$ is the temperature difference between the wire and the medium, $R$ is the resistance of half the wire and $k$ is the proportionality coefficient. On the other hand, an increase in the length of the wire occurs according to the law
$$l = l_0(1 + \alpha\Delta t),$$
where $\alpha$ is the coefficient of thermal expansion of the wire. From the last two equalities

$$\Delta l = l_0\alpha\Delta t = \frac{I^2 R}{k} l_0 \alpha = k_1 I^2$$

⟦folio 46⟧

$\left(k_1 = l_0 \alpha \frac{R}{k}\right)$, that is, the extension of the wiring is proportional to the square of the current strength. This means that the extension of section $CB$ of wiring is $\Delta l_1 \sim I_1^2$, and section $AC$ of wiring is $\Delta l_2 \sim I_2^2$.

Thus, the angle of rotation of the instrument needle, associated with the difference between the extended sections $AC$ and $CB$, is proportional to the value
$$I_2^2 - I_1^2 = I_0^2 \left( \frac{r_1^2}{r^2} + \frac{r_1^2}{r^2} \frac{R_H^2}{r^2} + 2 \frac{r_1^2}{r^2} \frac{R_H}{r} + 2 \frac{r_1}{r} \frac{R_H^2}{r^2} + 2 \frac{R_H}{r} \frac{r_1}{r} \right).$$

Since $r_1 \ll r$, then $\frac{r_1}{r} \ll 1$ and the first, second and third terms can be neglected compared to the four and fifth. In addition, in order for the connection of a wattmeter to have virtually no effect on the voltage at the load, $r$ must be much larger than $R_H$. This means $\frac{R_H}{r} \ll 1$ and $\left(\frac{R_H}{r}\right)^2 \ll \frac{R_H}{r}$, so four terms can be neglected compared to the fifth. As a result we get
$$I_2^2 - I_1^2 = 2 I_0^2 R_H \frac{r_1}{r^2} = 2 \frac{r_1}{r^2} P,$$

that is, the difference $I_2^2 - I_1^2$ is proportional to the power released by the load. Consequently, the difference in the lengths of the wiring sections and, accordingly, the angle of rotation of the device arrow is proportional to the current power consumed by the load.

$\blacksquare$

Let us observe being at point $O$ (Fig. 9), see the plane at point $A$ and hear the sound emitted by the plane at the moment when the plane was at point $B$. Let us denote by $t$ the time during which the sound from point $B$ must be located, then $BO = ct$ and $BA = vt$. From right angle triangle $AOK$
$$tg\varphi = \frac{KB + BA}{KO} = tg\alpha + \frac{vt}{ct \cos\alpha}. \tag{1}$$

By squaring equality (1), denoting $tg\varphi - tg\alpha$ by $x$ and taking into account that $\cos\alpha = \frac{1}{\sqrt{1 + tg^2\alpha}}$, we obtain
$$x^2 - 2 \frac{tg\varphi}{1 - \frac{c^2}{v^2}} x + \frac{1}{\cos^2 \varphi \left(1 - \frac{c^2}{v^2}\right)} = 0. \tag{2}$$

From here
$$x_{1,2} = \frac{tg\varphi}{1 - \frac{c^2}{v^2}} \pm \sqrt{\frac{tg^2\varphi}{\left(1 - \frac{c^2}{v^2}\right)^2} - \frac{i}{\cos^2 \varphi \left(1 - \frac{c^2}{v^2}\right)}} \tag{3}$$

Moreover, equation (1) is satisfied only by positive values ​​of $x$.

Let us first consider the case when the speed of the aircraft $v$ is less than the speed of sound $c$. Since $c^2/v^2 > 1$, then $x_1 > 0$ and $x_2 < 0$, that is, only one value $x = x_1$ is suitable. The “seeing” plane simply lags behind the visible one.

⟦folio 47⟧

An interesting solution in the case of a supersonic aircraft ($v > c$). Equation (2) has real roots only for $\cos \phi < \frac{c}{v}$, and both roots ($tg\phi > 0$) are positive at once. What does this mean? Let's look at this in more detail.

Fig. 11.

Which point in the aircraft's trajectory is the source of the spherical sound wave. The envelope of the wave fronts is a finite surface (Fig. 10) that moves forward at the aircraft speed $v$. The observed person will hear the sound for the first time at the moment when one comes to point $O$

Fig. 12.

from wave fronts. If the plane at this moment is at point $A_0$, then the observer will hear the sound coming towards him from point $B_0$ (Fig. 11). From figure 11 it is clear that $\sin \alpha_0 = \cos \phi_0 = \frac{ct}{vt} = \frac{c}{v}$. As the plane moves away, the angle $\phi$ increases, and $\cos \phi$ decreases (so, indeed, the plane is heard at angles $\phi$ such that $\cos \phi \leq \frac{c}{v}$).

Starting from this moment, the fronts of sound waves emitted by the aircraft at two different points of its trajectory will arrive at point $O$ (Fig. 12). At the moment when the plane is at point $A$, the observer will hear the sound that was emitted by the plane at points $B_1$ and $B_2$ (angles $\alpha_1$ and $\alpha_2$ are determined from formula (3)), that is, now two wave fronts pass through point $O$. Thus, as the aircraft moves away from point $A_0$, it will seem to the observer that two sound sources are moving in different directions from point $B_0$.

⟦folio 48⟧

F308. A fomometer is a sheet of paper with a greasy stain on it. This sheet is placed between two renal light sources. The luminous intensity of one source $I_1 = 20$ sv, the luminous intensity of another source $I_2$ will have to be determined. To do this, first select the distances $l_1$ and $l_2$ sources from the sheet of masks so that the foam does not stand out against the background of the paper when viewed from the side of the first source. Turned outLOB that $l_2 = 2l_1$. Then the distances $l_1$ and $l_2$ masks are selected so that the foam does not stand out against the background of the paper when viewed from the side of the second source. Turned outLOB that $l_1' = l_2' = l$. Determine the luminous intensity of the second source.

The sheet is placed peredicular to the line connecting the sources.

Podd with a Kazka. Each section of paper can be characterized by its transmittance and light reflectance.

The stain does not stand out against the background of the paper if the light fluxes $\Phi_\pi$ and $\Phi_6$, corresponding to the units of area of ​​the spot and clean paper and the contact with the eye observed, are the same. Paper and paper reflect and transmit light falling on them diffusely, that is, evenly in all directions. Therefore, it is very important that the light fluxes $\Phi_\pi$ and $\Phi_6$ are proportional to the illumination of the paper $E_\pi$ and the illumination of the paper $E_6$, respectively.

If you look at the spot from the side of the first source, then the illumination of the spot is the sum of the illumination due to the rays coming from the first source and passing through the spot $-E_2 = \alpha_\pi \frac{I_2}{l_2^2}$ ($\alpha_\pi$ is the transmittance coefficient of the spot):

$$E_\pi = E_1 + E_2 = r_\pi \frac{I_1}{l_1^2} + \alpha_\pi \frac{I_2}{l_2^2}.$$

Similarly, if the coefficient of light reflection by clear areas of paper is $r_6$, and the transmittance coefficient of these areas is $\alpha_6$, then the illumination of clean areas of paper is equal to

$$E_6 = r_6 \frac{I_1}{l_1^2} + \alpha_6 \frac{I_2}{l_2^2}.$$

Equating $E_\pi$ and $E_6$, we obtain the equation

$$r_\pi \frac{I_1}{l_1^2} + \alpha_\pi \frac{I_2}{l_2^2} = r_6 \frac{I_1}{l_1^2} + \alpha_6 \frac{I_2}{l_2^2},$$

or, given that $l_2 = 2l_1$,

$$4r_\pi I_1 + \alpha_\pi I_2 = 4r_6 I_1 + \alpha_6 I_2.$$

In the same way, we can obtain the illumination conditions for the paper and clean paper for the second case, when the paper is viewed from the side of the second source:

$$\alpha_\pi \frac{I_1}{l_1^2} + r_\pi \frac{I_2}{l_2^2} = \alpha_6 \frac{I_1}{l_1^2} + r_6 \frac{I_2}{l_2^2}.$$

Since in this case $l'_1 = l'_2$, then

$$\alpha_\pi I_1 + r_\pi I_2 = \alpha_6 I_1 + r_6 I_2.$$

Two equations (2) and (4) include five unknowns; it is impossible to determine all of them. However, one of them can be found, namely $I_2$. To do this, we intersect in equation (2) the terms containing $I_1$ into the left side of the equation, and the terms containing $I_2$ into the right side. We get

$$4I_1(r_\pi - r_6) = I_2(\alpha_6 - \alpha_\pi).$$

Let us construct similarly from equation (4):

$$I_1(\alpha_6 - \alpha_\pi) = I_2(r_\pi - r_6).$$

Having now determined the relation $\frac{\alpha_6 - \alpha_\pi}{r_\pi - r_6}$ from equation (5) and substituted it into equation (6), we obtain

$$\frac{4I_1}{I_2} = \frac{I_2}{I_1},$$ or $I_2 = 2I_1 = 40$ st.

⟦folio 49⟧

F309. The snake crawled halfway into a stationary narrow tube lying on a plane. The seaming half of the snake wriggles arbitrarily along the plane. Considering the snake to be a thin, uniform cinre of length $l$, find in which area the center of softness of the entire snake may be.

Fig. 13.

The center of gravity of the half of the snake that is in the pipe is located at a distance $\frac{l}{4}$ from the edge of the pipe. Its coordinates $(x_1, y_1)$ are (Fig. 13)

$$x_1 = -\frac{l}{4} \text{ и } y_1 = 0.$$

The center of gravity of the second half of the snake, arbitrarily wriggling along the plane, can be located at any point inside a circle of radius $\frac{l}{4}$ centered at the origin, that is, its coordinates $(x_2, y_2)$ satisfy the inequality

$$x_2^2 + y_2^2 \leq \left(\frac{l}{4}\right)^2.$$

Since the masses of both parts of the snake are the same, the coordinates of the center of gravity of the entire snake are determined by the following relations:

$$x_\mu = \frac{x_1 + x_2}{2} = \frac{x_2}{2} - \frac{l}{8}, \quad y_\mu = \frac{y_1 + y_2}{2} = \frac{y_2}{2}.$$

From these equalities we express $x_2$ and $y_2$ in terms of $x_\mu$ and $y_\mu$:

$$x_2 = 2x_\mu + \frac{l}{4}, \quad y_2 = 2y_\mu.$$

Substituting these values ​​into inequality (*), we get

$$\left(2x_\mu + \frac{l}{4}\right)^2 + 4y_\mu^2 \leq \left(\frac{l}{4}\right)^2, \quad \text{или} \quad \left(x_\mu + \frac{l}{8}\right)^2 + y_\mu^2 \leq \left(\frac{l}{8}\right)^2.$$

This means that the center of gravity of the entire snake can be located at any point in a circle of radius $\frac{l}{8}$ with a center whose coordinates are $x = -\frac{l}{8}$ and $y = 0$ (at Fig. 13 this circle is protected).

F310. The ends of the spring are fixed. How, without releasing the ends of the spring, can you deform it so that the spring tends to a) shorten after this treatment?

Let's first consider a loose spring and let's deform it, that is, stretch or compress it. Quantitatively, the deformation can be characterized by the magnitude of the abscult deformation $\Delta l = |l - l_0|$ ($l_0$ is the length of the spring in the undeformed state) or the value of the relative deformation $\frac{\Delta l}{l_0}$. What happens to the spring after the external forces stop acting? It turns out that two cases are possible: either the deformation completely disappears (the spring restores its length), or it partially remains, that is, residual deformation results (the length of the spring is not restored). In the first case, the deformation is called elastic, and in the second - plastic. What determines whether the deformation will be elastic or plastic? Experience shows that the nature of the deformation depends, first of all, on the magnitude of the deformation itself (as well as on the material of the spring and on the state of this material - on its temperature, previous processing, etc.). At small relative deformations, the spring is elastic, that is, it completely restores its shape and size after its ends are released. If the relative deformations are large, the spring becomes plastic and residual deformation occurs. The length of the spring becomes greater than $l_0$ if the spring is stretched, and less than $l_0$ if it is skimmed. Let's use these properties of the spring to solve the problem.

⟦folio 50⟧

Let's take the spring fixed at the ends by the coil, which is closer to one end of the spring than to the other, and move this coil to the far end of the spring. However, part of the spring turns out to be stretched, and the other - rolled. In this case, their absolute deformations $\Delta l$ will be the same, but their relative deformations will be different. The relative deformation $\frac{\Delta l}{l_{01}}$ of the short part of the spring will be greater than the relative deformation $\frac{\Delta l}{l_{02}}$ of the long part of the spring:

$$\frac{\Delta l}{l_{01}} > \frac{\Delta l}{l_{02}}.$$

This means that it is also possible to match $\Delta l, l_{01}$ and $l_{02}$, so that the deformation of the long part of the spring will still be elastic, and the short part will already be plastic. After such “processing”, the length of the long part (which was rolled) remains the same, and the length of the short part (which was stretched) will increase. The length of the entire spring in the unformed state will also increase. Consequently, the spring attached to the ends will tend to lengthen.

Similarly, if a coil of a spring is considered to be twisted to the near end of the spring and external forces are also applied so that the deformation of the long (stretched) part of the spring is elastic, and the deformation of the short (sloping) part is flexible, then the spring after processing will tend to shorten.

♦

Since the magnetic field changes with time, an emf appears in the circuit. induction $E$. The induced current in the circuit is equal to

$$I = \frac{E}{R},$$

where $R$ is the loop resistance. Loop resistance $R = \rho \frac{l}{s}$. Obviously $m = dls$. From here

$$s = \frac{m}{ld} \text{ и } R = \rho \frac{d}{m} l^2,$$

that is, the loop resistance is proportional to the square of the loop length.

E.m.f. induction excited in the circuit is equal to

$$E = \frac{\Delta \Phi}{\Delta t} = \frac{\Delta B}{\Delta t} S = kS,$$

where $S$ is the area covered by the contour. E.m.f. $E$ the larger the area $S$. For a given contour length, the circular area covered by the contour has the largest area. Therefore, E. d.s. maximum if the contour is a circle. Let us denote the radius of this circle by $r$, then

$$S = \pi r^2 \text{ и } E = k\pi r^2.$$

In this case

$$l = 2\pi r \text{ и } R = \rho \frac{4\pi^2 r^2}{m}.$$

Pozny finally

$$I = \frac{E}{R} = \frac{km}{4\pi\rho d}.$$

This is the maximum current in the circuit.

I. Sh. Slobodetsky
