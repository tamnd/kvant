---
id: 1978-4-resheniya-zadach-m446-m448-f462-f466-17d7d74c
issue: kvant_1978_4
year: 1978
number: "4"
title: Solutions to problems M446—M448; F462—F466
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 35
page_labels: 28, 29, 31, 32, 33
tag: 2W0E
lang: en
source: kvant_digital
extraction: vision
content_sha256: f46717721ca8ea9c09f906bebde0e86d64c5a3d5ad7d62c7635604531185ee5f
prompt_sha256: draft-1
translated_from: content/ru/1978/04/articles/11_resheniya-zadach-m446-m448-f462-f466-17d7d74c.md
source_content_sha256: 8ba8ea64040881e232b2d2f99713bb6f47c5bebf440c8c70b7e10b25d34deb82
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

M446. A circle of length 1 rolls from the outside along a circle of length $\sqrt{2}$. At the initial moment of time, the point of contact of the circle is marked with a line of paint. When rolling, the painted points of mine and the other outer circle are painted by the urine with which they come into contact. How many different points of the fixed circle will be dirty by the time the moving circle makes 100 revolutions around the fixed one?

Fig. 1.

Let us first find out how many red marks will be left on the fixed circle $a$ (length $\sqrt{2}$) by the first red point $B$ of the movable circle $b$ (length 1) in $n$ revolutions.

Let's roll the circle $b$ along a straight line. Then (if we take the first red point on the line as the beginning of the report $O$) the traces of the point $B$ will fall into points with non-negative integer coordinates (Fig. 1). Now we wind the straight line around the circle $a$, starting from point $O$. Each revolution corresponds to a straight segment of length $\sqrt{2}$. It is clear that different red points of the line will go into different points of the circle $a$, since the equality $k_1 - k_2 = m \sqrt{2}$ for integers $m, k_1 \neq k_2$ is impossible (the number $\sqrt{2}$ introduced is irrational). Thus, during the first $n$ revolutions, the point $B$ will leave $[n \sqrt{2}] + 1$ traces: that is exactly the number of integer points on the segment $[0; n \sqrt{2}]$.

Let us now try to take into account all the multiple traces left on one and the other circle. At first glance

it seems that their number grows exponentially depending on the number of revolutions $n$: after each revolution, the average plane of points (the number of points per unit length) returns approximately twice - after all, traces of points from another circle are added to the red dots on each circle. However, this assumption turns out to be completely incorrect: no other red points will appear on the circle $a$, except those in which the very first point $B!$ falls. Indeed, some empty dots $B' \in b$ are colored when they come into contact with the red dot $A' \in a$. Since $A'$ is red, the first point $B$ is already in contact with it. It is clear that, having become red, $B'$ will hit the same points (distance from $A'$ at a distance of 1, 2, ... in the direction of rotation) in which $B$ has already hit after its contact with $A'$.

In the same way, it can be proven that no points will appear on the circle $b$, except for those that are covered by the very first red point $A \in a$, so that after $n$ revolutions on the circle $b$ the $(n+1)$th red dot will appear.

So, the number of red dots grows not exponentially, but only according to the linear law $[n \sqrt{2}] + 1$.

N. Vasiliev

M447. In an acute triangle $ABC$, segments $BO$ and $CO$ (ede $O$ is the center of the omitted circle) are extended until they intersect at points $D$ and $E$ with lines $AC$ and $AB$ of the triangle. It turned out that $BDE = 50^\circ$, and $CED = 30^\circ$. You can find the angles of triangle $ABC$ using the sine theorem. Let's put $EBD = \varphi$. Then $OEB = 100^\circ - \varphi$, $ABC = \varphi + 40^\circ$, $ACB = 90^\circ - \varphi$,

28

⟦folio 29⟧

$OCD = 50^\circ - \varphi, ODC = \varphi + 50^\circ;$ thus $0^\circ < \varphi < 50^\circ$.
From triangles $ODE, OBE$ and $OCD$ we find:

$$\frac{\sin 50^\circ}{\sin 30^\circ} = \frac{|OE|}{|OD|} = \frac{|OE|}{|OB|} \cdot \frac{|OC|}{|OD|} = \frac{\sin OBE}{\sin OEB} \cdot \frac{\sin ODC}{\sin OCD} =$$

$$= \frac{\sin \varphi \sin (\varphi + 50^\circ)}{\sin (100^\circ - \varphi) \sin (50^\circ - \varphi)} = 2 \sin 50^\circ,$$

The equation from which we must find $\varphi$ ($0^\circ < \varphi < 50^\circ$):

$$\frac{\sin \varphi \sin (\varphi + 50^\circ)}{\sin (100^\circ - \varphi) \sin (50^\circ - \varphi)} = 2 \sin 50^\circ,$$

equivalently follows:

$$2 \sin 50^\circ (\cos 50^\circ - \cos (150^\circ - 2 \varphi)) =$$

$$= \cos 50^\circ - \cos (50^\circ + 2 \varphi),$$

$$\sin 20^\circ - \sin (2 \varphi - 40^\circ) + 2 \sin 50^\circ \cos (2 \varphi + 30^\circ) = 0,$$

$$\cos (\varphi - 10^\circ) \sin (30^\circ - \varphi) + \sin 50^\circ \sin (60^\circ - 2 \varphi) = 0,$$

$$\sin (30^\circ - \varphi) (\cos (\varphi - 10^\circ) + 2 \sin 50^\circ \cos (30^\circ - \varphi)) = 0.$$

Since $\cos(\varphi - 10^\circ)$ and $\cos(\varphi - 30^\circ)$ are positive at $0^\circ < \varphi < 50^\circ$, the last equation has a single root $\varphi = 30^\circ$.

Hence $A\widehat{BC} = 70^\circ, A\widehat{CB} = 60^\circ$.

Next, $B\widehat{EC} = 70^\circ \Rightarrow |CE| = |CB|; \quad O\widehat{DC} = 80^\circ \Rightarrow \Rightarrow |CD| = |CO|; \quad A\widehat{DE} = 50^\circ \Rightarrow |EA| = |ED|$.

The length equalities that need to be established in the problem tell you what angles the triangle $ABC$ should have. But even knowing the answer, it is difficult to come up with a trigonometric solution given above. Instead, we can argue differently.

First of all, note that the conditions $OED = 30^\circ, ODE = 50^\circ$ determine the answer uniquely. Indeed (Fig. 3), if on a circle with center $O$ we enclose the points $B$ and $C$ so that $B\widehat{OC} = 100^\circ$, and move the point $A$ along the arc $B'\ C'$ (symmetrical arc $BC$) from point $B'$ to the point $C'$, then the point $D \in [B'\ O]$ will approach $O$, and $E \in [OC']$ will move away from $O$; in this case, the value of the angle $ODE$ will increase, and the angle $OED$ will decrease; This means that only in one position $A$ these quantities can take on the required values ​​($50^\circ$ and $30^\circ$).

Now we need to prove that a triangle with angles $A = 50^\circ, B = 70^\circ, C = 60^\circ$ satisfies the conditions, that is, that all the angles are as indicated in figure 4. This is clear for angles the others of which are not shaded. It is somewhat more difficult to prove that the red angles have the indicated values ​​(it is enough to do this for one of the angles). Let us give two proofs.

1°. It is enough to check that $DE - \text{биссектриса угла } ADB$:

$$\frac{|AE|}{|EB|} = \frac{|AE|}{|EC|} \cdot \frac{|EC|}{|EB|} = \frac{\sin 20^\circ \sin 70^\circ}{\sin 50^\circ \sin 40^\circ} =$$

$$= \frac{2 \sin 20^\circ \cos 20^\circ}{2 \sin 50^\circ \sin 40^\circ} = \frac{\sin 30^\circ}{\sin 50^\circ} = \frac{|AD|}{|DB|}$$.

Here we again use the theorem of sines. Here is a purely geometric proof.

2°. The triangle $ECB$ has symmetry because $C\widehat{EB} = C\widehat{BE}$. Let $K$ be a point symmetrical to point $O$ relative to this axis (Fig. 5). Then the triangle $KCD$ is equal to $(|KC| = |OC| = |DC| = a, K\widehat{CD} = 60^\circ)$, and therefore $|KD| =$

⟦folio 31⟧

F462. If the electronic thermostat is set to the “nylon” position, my utility will periodically turn on at $\tau_1 = 10$ s and turn off at $\tau_2 = 40$ s. At the same time, the surface of the utility is heated to a temperature of $t_1 = 100^\circ C$. If the thermostat is set to the “clap” position, my utility periodically turns on at $\tau_1 = 20$ s and turns off at $\tau_2 = 30$ s. Determine the established temperature $t_2$ of the utility surface in this position of the thermostat. Namely, to what temperature $t_3$ the switched on utility boils up if the thermostat fails.
Assume that chalk removal is proportional to the temperature and ambient air. Room temperature $t_0 = 20^\circ C$.

F463. Two ice floes are moving at random speeds of the same absolute value, one to the north, the other to the west. It is true that at any moment of time on both ice floes it is possible to arrange the clock in such a way that the velocities of the ends of the second hands relative to the Earth will be equal, and for each moment of time there is only one such arrangement. Determine how far the ice floes move per day if the length of each second hand is 1 cm. The clock dials are located horizontally.

Let $P$ be the power released in the iron. Then in time $\tau_1$ energy will be released in it
$$W_1 = P\tau_1.$$
During the time $\tau_1 + \tau_2$ the utigot releases energy
$$W_2 = \alpha (t_1 - t_0) (\tau_1 + \tau_2),$$
where $\alpha$ is the proportionality coefficient.
At a steady iron temperature $W_1 = W_2$:
$$P\tau_1 = \alpha (t_1 - t_0) (\tau_1 + \tau_2).$$
(1)

In the same way, in the mode when the thermostat is set to the “cotton” position,
$$P\tau'_1 = \alpha (t_2 - t_0) (\tau'_1 + \tau'_2).$$
(2)

Substituting the value $P$ from (1) into (2), we find $t_2$:
$$t_2 = \frac{\tau'_1}{\tau_1} \frac{(t_1 - t_0)(\tau_1 + \tau_2)}{\tau'_1 + \tau'_2} + t_0 = 180^\circ C.$$
Using similar calculations and calculations, we find $t_3$:
$$t_3 = 420^\circ C.$$
V. Skorovarov

The speed $v$ of the end of the arrow relative to the Earth is equal to the vector sum of the speed of the ice floe $v_1$ and the speed $v_2$ of the end of the arrow relative to the ice floe.

Let the vector $\vec{OA}$ on figure 9 be the speed of the ice floe; vectors $\vec{AB'}$, $\vec{AB''}$, $\vec{AB'''}$ are the speeds of the end of the hand relative to the ice floe for some clock orientations. Then the vectors $\vec{OB'}$, $\vec{OB''}$, $\vec{OB'''}$, respectively, are the velocities of the end of the arrow relative to the Earth.

It is clear that for all possible orientations of the vector $\vec{AB}$ ($\vec{AB'}$, $\vec{AB''}$, ...) the geometric locus of the points $B$ ($B'$, $B''$, ...) is a sphere (with a horizontal position of the clock - a circle) with the center at the point $A$. The possible velocities $v$ in such a “velocity space” are depicted as corresponding at point $O$ and ending at point $B$ on the sphere (or circle). The construction for the second ice floe differs by rotating the ice floe speed vector by $90^\circ$.

Fig. 9.

Fig. 10.

⟦folio 32⟧

Amendment

In «Kvant» No. 3, due to the fault of the printing house, figure to the solution problem M445 (see p. 35, Fig. 8) was reproduced incorrectly. Figure should look like this:

figure 10 shows a construction for two ice floes at once. Vectors $\overrightarrow{OA}$ and $\overrightarrow{OA'}$ are the speeds of the ice floes, and circles $S$ and $S'$ are the geometric locations of the ends of the vectors $\vec{v}$ and $\vec{v}'$ with different correspondences between the values ​​of the speeds of the ice floes and the ends of the arrows. If the velocities of the ends of the arrows are too small, then the circles $(S_1$ and $S_1')$ do not have common points and the velocities $\vec{v}$ and $\vec{v}'$ cannot be equal for any orientation of the clocks. Circles $S_3$ and $S_3'$ correspond to the case when the orientation is not unique.

The conditions of the problem correspond to the situation depicted by the tangent circles $S_2$ and $S_2'$. As can be seen from figure, in this case $\left| \vec{v} \right| = \left| \vec{v}_2 \right|$, and the speed of the ice floe is $\left| \vec{v}_1 \right| = \left| \vec{v}_2 \right| V^2$. The second hand makes one revolution in 60 seconds, therefore, its tip speed is $\left| \vec{v}_2 \right| = 2\pi l/60 \approx 0,105$ cm/s ($l=1$ cm is the length of the hand). For the speed of the ice floe we get $\left| \vec{v}_1 \right| \approx 0,15$ cm/s≈130 m/day.

V. Belonukkin

F464. figure 11 shows two closed loops: ABBA and ABGA. Both cycles were carried out with an ideal monatomic time.

1) Indicate in which sections of the cycles we receive and in which sections we give menlo.
2) Which cycle has a higher efficiency? How many times?

Consider the ABC cycle. From the $pV$-diagram it is clear that $T_B > T_B > T_A$. Consequently, in the section AB and BV the gas receives the gas, and in the section BA it is released. In this case, in the AB section the gas is heated without doing work ($\Delta V=0$), and in the BV and BA sections the gas does work equal to (the change in the internal energy of the gas per cycle is zero)

$$A_1 = Q_{AB} + Q_{BB} + Q_{BA} \quad (Q_{BA} < 0).$$

Thus, in the ABBA cycle

$$\eta_1 = \frac{A_1}{Q_{AB} + Q_{BB}}.$$

Consider the ABGA cycle. From the $pV$-diagram it is clear that $T_B > T_G > T_A$, so that in the AB section the gas receives tello, and in the BG and GA section it releases. In the HA section, the gas does work

$$A_2 = Q_{AB} + Q_{BG} + Q_{GA} \quad (Q_{BG}, Q_{GA} < 0),$$

So

$$\eta_2 = \frac{A_2}{Q_{AB}}.$$

Let's compare the values ​​of $\eta_1$ and $\eta_2$. From the $pV$-diagram it is clear that $A_1 = A_2$ (since the work done per cycle is numerically equal to the area of ​​the figure limited by the cycle graph), so that

$$\frac{\eta_1}{\eta_2} = \frac{Q_{AB}}{Q_{AB} + Q_{BB}},$$

and since $Q_{AB} + Q_{BB} > Q_{BA}$, then $\eta_2 > \eta_1$.

Let's calculate the ratio $\frac{\eta_1}{\eta_2}$. To do this, we find $Q_{AB}$, $Q_{BB}$ and $Q_{AB}$.

According to the $pV$-diagram $Q_{AB} = \Delta U_{AB}$, where $\Delta U_{AB}$ is the change in the internal energy of the gas in the AB section. For one mole of a monatomic ideal gas $\Delta U_{AB} = \frac{3}{2}R \times (T_B - T_A)$. From the equation of gas state we find $T_B = \frac{2p_0V_0}{R}$, $T_A = \frac{p_0V_0}{R}$. Thus,

⟦folio 33⟧

$$Q_{AB} = \Delta U_{AB} = \frac{3}{2} R \left( \frac{2 p_0 V_0}{R} - \frac{p_0 V_0}{R} \right) = \frac{3}{2} p_0 V_0.$$

At section $BB$ $Q_{BB} = \Delta U_{BB} + A_{BB}$, where

$$\Delta U_{BB} = \frac{3}{2} R (T_B - T_B) =$$

$$= \frac{3}{2} R \left( \frac{2 p_0 3 V_0}{R} - \frac{2 p_0 V_0}{R} \right) = 6 p_0 V_0$$

(for one mole),

$$A_{BB} = 2 p_0 2 V_0 = 4 p_0 V_0.$$

Thus,

$$Q_{BB} = 6 p_0 V_0 + 4 p_0 V_0 = 10 p_0 V_0,$$

$$Q_{AB} + Q_{BB} = 11,5 p_0 V_0.$$

But $Q_{AB} = -Q_{BA}$,

$$Q_{BA} = A_1 - (Q_{AB} + Q_{BB}) =$$

$$= p_0 V_0 - 11,5 p_0 V_0 = -10,5 p_0 V_0,$$

So

$$Q_{AB} = 10,5 p_0 V_0.$$

So,

$$\frac{\eta_1}{\eta_2} = \frac{Q_{AB}}{Q_{AB} + Q_{BB}} = \frac{10,5}{11,5} \approx \frac{21}{23}.$$

A. Zilberman

F465. In a high-voltage electrosmatic generator, charges are transferred by dielectric lentium and charge a high-voltage electrosmatic electrode with a radius of $R = 1,5$ m (Fig. 12). Estimate the maximum value of voltage and voltage that can be obtained from such a generator if the speed of the belt is $v = 20$ m/s, and its width is $l = 1$ m. Breakdown is possible when the electrosmatic field voltage is $E_0 = 30$ kV/cm.

The maximum potential to which the high-voltage spherical electrode of the generator can be charged is determined by the electrical strength of the air: the electric field voltage near the electrode surface cannot exceed the value $E_0 = 30$ kV/cm, at which breakdown occurs, that is

$$E_{\max} = E_0.$$

Therefore, the maximum possible potential per electrode is

$$\varphi_{\max} = E_{\max} R = E_0 R = 4,5 \cdot 10^6 \text{ B}.$$

(This correspondence follows from Coulomb’s law and from the expression for the Coulomb field potential.)

The maximum current that can be obtained from the generator is also determined by the electrical strength of the air. Let us denote by $\sigma$ the surface density of charges transferred by lenthium. Then the electric field voltage near the surface of the lenthium is $E = \frac{\sigma}{2\varepsilon_0}$. This value should not exceed $E_0$. Therefore, the maximum possible surface charge density on the tape is equal to

$$\sigma_{\max} = 2\varepsilon_0 E_0.$$

The maximum current is obviously equal to the maximum charge transferred by lentium per unit time, that is

$$I_{\max} = \sigma_{\max} lv = 2\varepsilon_0 E_0 lv \approx 10^{-3} \text{ A}.$$

The above calculation shows why electrostatic generators must be large.

S. Kozel
