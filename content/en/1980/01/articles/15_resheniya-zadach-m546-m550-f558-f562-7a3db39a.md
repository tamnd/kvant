---
id: 1980-1-resheniya-zadach-m546-m550-f558-f562-7a3db39a
issue: kvant_1980_1
year: 1980
number: "1"
title: Solutions to problems M546—M550; F558—F562
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 35
page_last: 41
page_labels: 33, 37, 38, 39
tag: WCEA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6bd7dccaaa47bc20f7fbe763e3fe27c403dc3b6eb7a1aa988ff3d7fc8b962875
prompt_sha256: draft-1
translated_from: content/ru/1980/01/articles/15_resheniya-zadach-m546-m550-f558-f562-7a3db39a.md
source_content_sha256: df77c25bc7b7e696da3b1e7c80968ea8a313225a1d54388cc90006a3cf646200
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

M546. From an arbitrary point M of the circle circumscribed about the rectangle, we dropped perpendiculars MP and MQ to its two opposite sides and perpendiculars MR and MT to the extensions of the other two sides. Prove that the perpendiculars PR and QT are straight, others, others, others. And their point of intersection belongs to the diagonals of the rectilinear.

M547. In order for the equation $\frac{1}{x} - \frac{1}{y} = \frac{1}{n}$, where $n$ is a natural number, to have an unique solution in the natural numbers $x$, $y$, it is necessary and sufficient that $n$ be simple. Prove it.

Let us denote by $M_1$ and $P_1$ the points of intersection of the segments $MT$ and $MP$ with the given circle (see Fig.). Since the angles $MMP_1$ and $ADC$ are right angles, the angles $M_1AP_1$ and $AM_1C$ are also right angles and the quadrilateral $AP_1CM_1$ is a rectangle. On the other hand, quadrilaterals $AM_1TQ$ and $ARPP_1$ are parallelograms (pairs of segments $M_1T$, $AQ$ and $AR$, $PP_1$ are parallel and equal in length). Pozny $(AM_1) \parallel (TE)$ and $(AP_1) \parallel (RP)$. It follows that $(TE) \perp (RP)$.

The second statement of problem $(E \in (AC))$ is equivalent to observing the rectangles $AP_1CM_1$ and $AGEF$. Let's show that they really are bleached.

Indeed, all angles marked at figure are congruent; let them be equal in magnitude to $a$. Then, if $|AM_1| = a$ and $|CM_1| = b$, then $|AF| = |AR| \sin a = |PP_1| \sin a = |CP_1| \sin^2 a = a \sin^2 a$ and similarly $|AG| = b \sin^2 a$, that is, $\frac{|AM_1|}{|CM_1|} = \frac{|AF|}{|FE|}$.

Pozny $E \in [AC]$.

I. Klumova

◆ From the equation $\frac{1}{x} - \frac{1}{y} = \frac{1}{n}$ it follows that $\frac{1}{x} > \frac{1}{n}$, that is, $x < n$. Therefore, if $n = 1$, then there is no solution in natural numbers. Let $n \neq 1$, then $x = n - i$, $0 < i < n$, and $\frac{1}{n - i} - \frac{1}{n} = \frac{1}{y}$. Hence $y = \frac{n(n - i)}{i}$. However, there is always a solution (in natural numbers): it is obtained at $i = 1: x = n - 1, y = n(n - 1)$.

Now let $n$ be prime and $i > 1$. Then the numbers $n$ and $i$ are coprime and the numbers $n - i$ and $i$ are also coprime, and therefore the numbers $n(n - i)$ and $i$ are also coprime (convince yourself of this by considering, for example, the sum $n(n - i) + ni$. Poznym, if $n$ is prime, and $i > 1$, we get $y = \frac{n(n - i)}{i} \notin \mathbb{N}$. This means that for a simple $n$, $i = 1$ is necessary, and our equation has a unique solution.

If $n$ is a composite: $n = n_1n_2$, then putting, for example, $i = n_1$, we obtain, in addition to the solution $x = n - 1$, $y = n(n - 1)$, one more: $x = n - n_1$, $y = n_2(n - n_1)$. This completely proves the statement of the problem.

A. Dantselyan

◆ Let’s immediately solve point c) of the problem. To do this, first of all create:

There are $n$ points on the circle. Through the center of such $n - 2$ a straight line is drawn from them, perpendicular to the chord, connecting the remaining points. Prove that all such lines pass through one point.

But what is the center of such $k$ points? Let us give a definition: the center of such $k$ points $A_1, A_2, \dots, A_k$ is such a point $G$ such that

$$\overrightarrow{GA_1} + \overrightarrow{GA_2} + \dots + \overrightarrow{GA_k} = \overrightarrow{0}.$$

⟦folio 37⟧

riding bikes, blue - traveling on foot. On this figure the movement graphs of one of the vehicles leaving $A$ and one of the vehicles leaving $A$ are highlighted (broken lines $AC_3D_3B$ and $AA_2B_3B$). It can be seen from the graph that the time it takes to move each vehicle is $t_{\min}$.

Case $m=2$, $n=3$ is propagated to figure 2: the graph of the movement of the first magnitude is shown in this color; red - second and black - third ERO.

S. Krotov

F558. A small heavy ball flies through a hole inside the main sphere of the same mass, passing at a distance of $R/2$ from the center of the sphere ($R$ is the radius of the sphere). After the ball enters, the hole automatically closes. Assuming the collisions between the ball and the sphere to be absolutely elastic, find the trajectories of the ball and the center of the sphere in the reporting system in which the sphere was originally dug. Determine the parameters of these trajectories and mark on them the points at which collisions occur.

Fig. 1.

Fig. 2.

Fig. 3.

Let the ball fly into the hole with a speed $\vec{v}$ relative to the reporting system in which the sphere was first dug. It is obvious that all movements will occur in the plane where the vector $\vec{v}$ and the center of the sphere lie.

The masses of the ball and the sphere are equal, therefore the center of mass of the system will move with a speed of $\vec{v}/2$ along a straight line lying in the same plane at a distance of $R/4$ from the center of the sphere. Since there are no external forces acting on the system, the movement of the center of mass will not change even if there are any collisions within the system.

According to the conditions of the problem, the collisions are absolutely elastic and the surfaces are smooth. This means that the tangential projection of the ball’s velocity relative to the sphere remains unchanged, but the normal one changes sign to the opposite. Consequently, with each collision, the model of the velocity vector of the ball relative to the sphere does not change and remains equal to $|\vec{v}|$, and the angles of incidence and reflection are congruent. The trajectory of the ball relative to the sphere has the form of an equilateral triangle on the side $R\sqrt{3}$ (shown in red at figure 1), and the time intervals between successive collisions are $R\sqrt{3}/|\vec{v}|$.

The center of mass of the system relative to the sphere moves at half the speed, and its trajectory is also an equilateral triangle, but from the side $R\sqrt{3}/2$ (shown in black at figure 1).

Now let's consider a progressively moving reporting system, where it is not the sphere that is stationary, but the center of mass of the system. The velocities of the ball and the center of the sphere in this system are identical in magnitude, which is equal to $|\vec{v}|/2$, and the movement occurs along the trajectories depicted by the corresponding colors on figure 2 and 3.

In conclusion, it remains to go to the original system of the report, where the sphere was initially dug, the ball moves with a speed of $\vec{v}$, and the center of mass still moves with a speed of $\vec{v}/2$ (Fig. 4). For such a transition, it is necessary to add the vector $\vec{v}/2$ to all the velocity vectors shown in Figures 2 and 3. It turns out that before the first collision (after the “zero”, triangular, sixth, $3n$th) the ball moves with a speed equal in magnitude to $|\vec{v}|$ and directed parallel to the speed (and trajectory) of the center of mass, and a disagreement $R\sqrt{3}$ occurs. The sphere will accumulate during this period of time.

After the first (fourth, seventh,..., $(3n+1)$th) collision, the ball’s velocity vector is directed at an angle $-\pi/3$ to the velocity vector of the center of mass and is equal in magnitude to

⟦folio 38⟧

Before the second collision, the ball travels a distance $R\sqrt{3}/2$. The corresponding speed of the sphere is directed at an angle of $\pi/6$ to the same vector, and its model is equal to $|\vec{v}|\sqrt{3}/2$. The sphere travels the path $3R/2$.

After the second (fifth, eighth,..., $(3n+2)$th) collision, the velocity vectors of the ball and the center of mass make an angle $\pi/3$ and are equal to $|\vec{v}|/2$ according to the model. The path of the ball is the same, that is, $R\sqrt{3}/2$. The final speed of the sphere at this time is $\pi/6$, speed model $|\vec{v}|\sqrt{3}/2$, path $3R/2$.

Then the picture repeats, that is, between the third and fourth collisions the sphere ends again, and the ball moves with a speed of $\vec{v}$, etc.

B. Bukhovtsev

F559. According to Bethe's theory, the carbon cycle of stellar thermonuclear reactions consists of the following reactions:

$$p + ^{12}C \rightarrow ^{13}N + \gamma,$$
$$^{13}N \rightarrow ^{13}C + e^{+} + v,$$
$$p + ^{13}C \rightarrow ^{14}N + \gamma,$$
$$p + ^{14}N \rightarrow ^{15}O + \gamma,$$
$$^{15}O \rightarrow ^{15}N + e^{+} + v,$$
$$p + ^{15}N \rightarrow ^{12}C + ^{4}He.$$

Start the energy released during the formation of a mole of a body.

The Bethe cycle results in a gel nucleus formed from four protons:

$$4p \rightarrow ^{4}He + 2e^{+} + 3\gamma + 2v.$$

By calculating the energies of the parts on the left and right using the formula $E = mc^2$, we find the energy released during the synthesis of one nucleus of a gel atom ($m_p = 1,6724 \cdot 10^{27}$ kg, $m_{He} = 6,6439 \cdot 10^{27}$ kg, $m_{e} = 0,9108 \cdot 10^{30}$ kg, $c = 3 \cdot 10^8$ m/s):

$$E_{выд} = (4m_p - m_{He} - 2m_{e})c^2 = 0,3951 \cdot 10^{-11}$$ J.

When a mole of gel is formed, energy is released

$$W = E_{выд}N_A \approx 2,4 \cdot 10^9$$ kJ

(here $N_A \approx 6 \cdot 10^{23}$ mol $^1$ is Avogadro’s number).

F560. A flat infinite jet of thickness $d_0$ extends nod onto the plane (Fig. 1). The speed of the jet is $\vec{v}$, its density is $\rho$. What stream does the jet break up into?

Let us denote by $d_1$ and $d_2$ the thicknesses of the formed jets (Fig. 2), and by $\vec{v}_1$ and $\vec{v}_2$ their velocities. Since the same mass of liquid passes through the cross section of the first falling jet in one second as through the cross section of both formed jets, then

$$\rho d_0 v = \rho d_1 v_1 + \rho d_2 v_2$$

(1)

(here $v, v_1$ and $v_2$ are molly of the corresponding speeds).

Let us select the so-called liquid flow tube (it is shown in color on figure 2) and consider its section between sections $I$ and $II$. In a short time $\Delta t$ the same mass of liquid flows through section $I$ in an area $\Delta s$, and through section $II$ in an area $\Delta s_1$.

$$\Delta m = \rho \Delta s v \Delta t = \rho \Delta s_1 v_1 \Delta t.$$

The change in the kinetic energy of this mass of liquid is equal to the work $A$ of the pressure forces $\vec{F}$ and $\vec{F}_1$. If when passing through $I$ the work is positive, then when passing through $II$ it is negative, therefore

$$A = F v \Delta t - F_1 v_1 \Delta t = p \Delta s v \Delta t - p_1 \Delta s_1 v_1 \Delta t,$$

where $F$ and $F_1$ are the moles of pressure forces, and $p$ and $p_1$ are the pressures in sections $I$ and $II$, respectively.

But the pressure in both the left and right jets is equal to the pressure in the falling jet (all jets have a free flat surface and the pressure in them is equal to atmospheric pressure), that is, $p = p_1$. Besides,

$$\Delta s v \Delta t = \Delta s_1 v_1 \Delta t = \frac{\Delta m}{\rho}.$$

⟦folio 39⟧

Thus,

$$A = p \frac{\Delta m}{\rho} - p \frac{\Delta m}{\rho} = 0,$$

and the change in kinetic energy of the mass $\Delta m$ of the liquid is zero, that is, $v_1 = v$. In exactly the same way it can be shown that $v_2 = v$. Therefore, from equality (1) we obtain

$$d_0 = d_1 + d_2.$$

(2)

Since there are no external horizontal forces acting on the fluid, the horizontal projection of the momentum of the flowing fluid must remain constant:

$$mv \cos \alpha = m_1 v_1 - m_2 v_2,$$

where $m \sim d_0$, $m_1 \sim d_1$, $m_2 \sim d_2$ and $v = v_1 = v_2$. Hence,

$$d_0 \cos \alpha = d_1 - d_2.$$

(3)

From equalities (2) and (3) we obtain

$$d_1 = d_0 \cos^2 \frac{\alpha}{2} \quad \text{и} \quad d_2 = d_0 \sin^2 \frac{\alpha}{2}.$$

◆ a) The force acting along the equator on the lower part of the bathing suit is equal to the weight of a column of water above the upper hemisphere (Fig. 1). The volume of this column is equal to the volume of a cylinder with radius $R$ and height $H$ without the volume of a hemisphere with radius $R$, so the water weight model is equal to

$$P = \rho g \left( H \pi R^2 - \frac{2}{3} \pi R^3 \right).$$

The tension that the bathing suit seam must withstand is equal to

$$\sigma_a = \frac{P}{2 \pi R} = \frac{1}{2} \rho g \left( HR - \frac{2}{3} R^2 \right).$$

b) At a distance of two small planes with area $\Delta s$ each, located at a distance $h$ above and below the center of the sphere (Fig. 2). The upper plane is acted upon by a force $\overrightarrow{F_1}$, the model of which is $F_1 = \rho g (H - h) \Delta s$. The projection of this force on the horizontal plane is equal to

$$F_1 \cos \alpha = \rho g (H - h) \Delta s \cos \alpha.$$

The force $\overrightarrow{F_2}$ acts on the lower plane, its model $F_2 = \rho g (H + h) \Delta s$, and the projection on the horizontal plane is equal to

$$F_2 \cos \alpha = \rho g (H + h) \Delta s \cos \alpha.$$

The sum of these projections does not depend on $h$ and is equal to

$$2 \rho g H \Delta s \cos \alpha.$$

But $\Delta s$ cos $\alpha$ is the projection of the plane $\Delta s$ on the vertical plane. It follows that the sum of $F$ horizontal force projections acting on the entire right hemisphere is equal to the product of $2 \rho g H$ by half the flat section of the hemisphere passing through the vertical diameter:

$$F = 2 \rho g H \frac{1}{2} \pi R^2 = \rho g H \pi R^2.$$

The tension that the bathing suit seam must withstand is equal to

$$\sigma_a \approx \sigma_6 = \frac{1}{2} \rho g HR = 10^8 \text{ H/m}.$$
