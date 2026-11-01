---
id: 1987-2-resheniya-zadach-m1006-m1009-f1017-f1022-ff64ee49
issue: kvant_1987_2
year: 1987
number: "2"
title: Solutions to problems M1006—M1009; F1017—F1022
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 37
page_labels: 24, 25, 26, 27, 28, 29, 30, 31, 33, 35
tag: 2C2D
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8f2e576e3f89f9585433e9307cf96ac11cc7292b691141e8df0a2f60e5ec5642
prompt_sha256: draft-1
translated_from: content/ru/1987/02/articles/07_resheniya-zadach-m1006-m1009-f1017-f1022-ff64ee49.md
source_content_sha256: d84d6d0274d3c8dc7b60a98ae2d81791756837c6d1889349728ee54cd52e07cb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

M1006. Two straight lines are drawn through two vertices of a triangle, dividing it into three triangles and a quadrilateral.
a) Can the areas of all be quadrilaterals?
b) Which three of these parts can have equal areas?
How many times is the area adb of the quadrilateral?

Problem solutions
M1006—M1009; F1017—F1022

The solution will use the following almost-evaluated number many times
Lemma. The ratio in which a line drawn through the vertex of a triangle divides its area adb is equal to the ratio in which it divides its base (see Fig. 1).

a) Answer: they cannot. Even if only three triangles of the partition were equal in size (we don’t need the assumption about the size of the area of ​​the quadrilateral), then according to the lemma, the segments dividing this triangle should be dividing each other in half (Fig. 2), i.e. they would be diagonals of parallels. But this is impossible, since two opposite sides of this “parallelogram” lie on intersecting straight lines - the sides of this triangle.

b) Answer: a quadrilateral and any two partition triangles can be equal in area; the ratio of the area of ​​the 4th part to the area of ​​each of the three equal parts can be equal to either 3 or $\sqrt{5}-2$.

Let us introduce the notation as in figure 3. From the solution of problem a) it is clear that one of the equal parts is the quadrilateral CLPK, the other is one of the triangles APL and BPK; we will assume that this is triangle APL (the case of triangle BPK is considered in exactly the same way). The third part is the triangle BPK or APB; these two cases must be considered separately.

⟦folio 25⟧

Let us denote the area of ​​three equal parts by $s$ ($s=S_{CLPK}=S_{APL}$), the area of ​​the 4th part by $s_1$. To find the required relation $s_1/s$, we express in two ways the relations in which the points $L$ and $K$ divide the sides $AC$ and $BC$, through the area using the lemma:

$$\frac{CL}{LA} = \frac{S_{CLB}}{S_{LAB}} = \frac{S_{CLP}}{S_{LAP}},$$

$$\frac{CK}{KB} = \frac{S_{CKA}}{S_{KBA}} = \frac{S_{CKP}}{S_{KBP}},$$

(*)

and the incoming soda areas are through $s$, $s_1$ and $x=S_{CPL}$.

In the first case (Fig. 3, a) we have:

$$\frac{2s}{s+s_1} = \frac{x}{s}, \frac{2s}{s+s_1} = \frac{s-x}{s}.$$

From here it is easy to find that $x=s/2$, $s_1/s=3$.

In the second case (Fig. 3, b) the system will be written as follows:

$$\frac{s+s_1}{2s} = \frac{x}{s}, \frac{2s}{s+s_1} = \frac{s-x}{s}.$$

The first of these equations gives $x=(s+s_1)/2$; Substituting this expression into the second equation, we find that the relation $s_1/s$ satisfies the quadratic equation $(s_1/s)^2+4(s_1/s)-1=0$, i.e. $s_1/s=\sqrt{5}-2$.

It remains to check that if we divide the sides of the triangle $ABC$ in the ratios

$$CL : LA=CK : KB=2s : (s+s_1)=1 : 2$$

in the 1st case and

$$CL : LA=BK : KC=(s+s_1):2s=(\sqrt{5}-1)/2$$

in the 2nd case, then the corresponding three parts of the partition will indeed be equal in size. Using equalities (*), this is quite easy to do in the 1st case and somewhat more difficult in the 2nd. For the 2nd case, we will give a different reasoning, explaining why the number $\alpha=(\sqrt{5}-1)/2$ appeared in our problem. (The number $\tau=\frac{1}{\alpha}=\frac{\sqrt{5}+1}{2}$ is the meaning of the “golden solution”.) Note that our statement is, as we say, afficine, i.e. it contains only such geometric concepts and quantities that are preserved during parallel design: a straight line, the ratio of the lengths of segments of one straight line, equality of areas, etc. (On the contrary, concepts such as angle values, the ratio of the lengths of the sides of a triangle or, say, a bic sector, are not preserved under projections - and are not included in our statement.) And since any triangle can be transformed into a triangle of a given shape with the help of some parallel projection (think why!), it is enough to check our statement only for triangles of one, most convenient type. As such a “good” triangle, we take the triangle $ABC$, formed by two diagonals and the sides of a regular pentagon (Fig. 4). It is not difficult to show that the ratio of the sides of a regular pentagon to its diagonal is $\alpha$. From here it is clear that on figure 4

$$CL : LA=BK : KC=BD : AC=\alpha;$$

and at the same time $S_{APB}=S_{APL}=S_{CKPL}$, since it is very clear that $BP=PL$, and the triangle $APL$ is simply equivalent to the quadrilateral $CKPL$.

G. A. Galperin,
A. P. Savin

⟦folio 26⟧

M1007. Prove that triangles with side lengths a, b, c and a₁, b₁, c₁ are similar if and only if
$$\sqrt{a a_1} + \sqrt{b b_1} + \sqrt{c c_1} = \sqrt{(a_1 + b_1 + c_1)(a + b + c)}.$$

After squaring both sides of the equality being proved and several transformations, it is reduced to the form
$$(\sqrt{a b_1} - \sqrt{a_1 b})^2 + (\sqrt{c a_1} - \sqrt{c_1 a})^2 + (\sqrt{b c_1} - \sqrt{b_1 c})^2 = 0,$$
and therefore, it is equivalent to the equalities $a/a_1 = b/b_1 = c/c_1$, i.e., similar to triangles.

Another proof can be obtained, then, that the left side is equal to the scalar product of vectors with coordinates $(\sqrt{a}, \sqrt{b}, \sqrt{c})$ and $(\sqrt{a_1}, \sqrt{b_1}, \sqrt{c_1})$ and cannot be greater than the right side, which is equal to the product of the lengths of these vectors; equality is possible only when the angle between the vectors is zero, i.e. they are proportional to each other.

Essentially, in the second argument we use the so-called Cauchy-Bunyakovsky inequality:
$$x_1 y_1 + x_2 y_2 + \dots + x_n y_n \leq \sqrt{(x_1^2 + x_2^2 + \dots + x_n^2)(y_1^2 + y_2^2 + \dots + y_n^2)},$$
which turn into equality only when the sets of numbers $(x_1, \dots, x_n)$ and $(y_1, \dots, y_n)$ are proportional (we have $n=3$, $(x_1, x_2, x_3) = (\sqrt{a}, \sqrt{b}, \sqrt{c}), (y_1, y_2, y_3) = (\sqrt{a_1}, \sqrt{b_1}, \sqrt{c_1})$).

V. P. Chuchin, V. N. Dubrovsky

M1008. The staircase consists of 2n+1 steps. On the pinnix steps there is one stone. The two take turns also hitting the stones. The first one can move any stone up to the first free step, and the second one can move the stone down one step if it is free. The goal of the first is to place the stone on the top step. can a second one fit him?

Answer: maybe.

To avoid confusion, we will write the numbers of the actors in the task (their “names”) with a capital letter. The rule of action for the Second is this: he always places a stone on the step that was vacated after the First’s move (this is always possible, since the stone on the next step was either lying before the move

Fig. 1. Fig. 2.

The First - and remained there after this move, or ended up there as a result of the First's move). If the Second follows this rule, then after any move of the First and the answer of the Second, either nothing will change (Fig. 1), or on some section of the ladder, all steps of which, except the top one, are occupied, the second step will be freed and a stone is placed on the top (Fig. 2). It is clear that in this case the lower step is always occupied and cannot form groups of two or more consecutive point steps (not counting, of course, the steps above the upper stone; from the very beginning of the free steps lying below the upper (n-th) stone, before any move of the First there are not more than n - 1, i.e. the two upper steps will be free, and the First cannot occupy the upper step.

S. L. Eliseev, N. N. Konstantinov

M1009. The bisector of the parallelogram ABCD intersects the lines BC and

Let us denote the center of the SKL circle by O; it is enough for us to prove that $\angle BOD = \angle BCD$ (see figure). Let us first note that the segments AB and BK, as well as LC

⟦folio 27⟧

CD at points K and L respectively. Prove that the center of the circle through points C, K and L lies on the circle through points B, C and D.

F1017. The world's largest network telephone has a mirror with a diameter of D = 6 m as an object. How long will it take for, comparing the photos taken on this telephone, to notice the mutual rotation of our Galaxy and the Andromeda nebula around a common center of mass? Distance to Andromeda R=1.42·10¹¹ R₀, where R₀ is the radius of the Earth’s orbit. The masses of the Galaxy and Andromeda are equal, respectively, M₇=2.5·10¹¹ M₀, M₄=3.6·10¹¹ M₀, where M₀ is the mass of the Sun. Photoefficiency is carried out in visible light at a wavelength λ=5·10⁻⁷ m.

F1018. The boat, calling near the shore of a large lake (the coastline is straight), suddenly became untied, and the wind blew it at a constant speed v₀=2.5 km/h at an angle α=15° to the birch tree. Will you be able to catch up with the boat if your speed and SK are equal, since in triangle ABK the angles on side AK are equal (∠BAK=∠KAD=∠AKB), and straight line LC is parallel to AB. This, in part, implies the equality of triangles OKC and OCL (OK=OC=OL, KC=CL). Let's rotate the plane around point O so that triangle OKC coincides with triangle OCL. Then the beam KC will be aligned with the bow CL, so the angle between these beams, i.e. ∠BCD, is equal to the angle of rotation. At the same time, point B during this rotation will move to D, since KB=AB=CD, therefore, the angle BOD is also equal to the angle of rotation; Thus, the equality of angles BOD and BCD is proved.

Figure in the margin illustrates the case when AB>BC, and the angle BAD is acute, however, our reasoning is applicable in all other cases without any changes.

The minimum angular distance between two objects at which they can be observed separately is determined by diffraction and is approximately equal to λ/D. In order to notice that Andromeda has changed its position, it must move exactly at this angle:

$$\varphi_0 \approx \frac{\lambda}{D} = \frac{5 \cdot 10^{-7}}{6} \text{ рад} \approx 8 \cdot 10^{-8} \text{ рад.}$$

If the period of revolution of the Galaxy and Andromeda around the center of mass is T, then the rotation through the angle φ₀ occurs in the time:

$$\tau = \frac{T}{2\pi} \varphi_0.$$

Period T can be found from the generalized (in a school astronomy textbook it is called refined) Kepler’s III law:

$$\left(\frac{T}{T_2}\right)^2 \left(\frac{M_1+m_1}{M_2+m_2}\right) = \left(\frac{R_1}{R_2}\right)^3.$$

Writing it down for the Earth-Sun and Galaxy-Andromeda systems and neglecting the mass of the Earth, we obtain:

$$\left(\frac{T}{T_0}\right)^2 \left(\frac{M_\Gamma+M_A}{M_0}\right) = \left(\frac{R}{R_0}\right)^3,$$

where T₀=1 year (earthly).

From equations (1), (2) and (3) we find:

$$\tau = \frac{\lambda}{2\pi D} T_0 \left(\frac{R}{R_0}\right)^{3/2} \left(\frac{M_0}{M_\Gamma+M_A}\right)^{1/2} \approx 10^3 \text{ лет.}$$

V.E. Belonuchkin

Suppose that at the moment of detection of the catarrh object you were on the shore at point O (see figure), and the catarrh, having come off at point E, moves along the straight line EF, making an angle α=15° with the linear birch, at a speed v₀=2.5 km/h. To answer the question of the problem, let’s construct the boundary of the reachability region - the area in which, after time t after the start of your movement, you can find yourself by “combining” walking and swimming. This boundary (see figure) is an arc AB of a circle with radius |OA|=

⟦folio 28⟧

on the shore $v_1=4$ km/h, in the water - $v_2=2$ km/h? At what speed of catarrh is this generality possible?

$$= |OB|=v_2t$$ and two segments tangent to this circle - CA and DB, and $|OC|=|OD|=v_1t$ (the construction of this boundary was described in detail in the article “On optimal trajectories of movement” in «Kvant» No. 6 for 1982, p. 30). After time $\Delta t$, the boundary of the accessibility region will take a new position $C'A'B'D'$, and $|CC'|=|DD'|=v_1 \cdot \Delta t$, $|AA'|=|BB'|=v_2 \cdot \Delta t$. It is easy to understand that if the projection of the speed of the catarrh onto the direction OA (in this direction the flat section of the boundary of the accessibility region propagates at a speed of $v_2$) is greater than the speed of $v_2$, then you will never agree. The minimum value of the speed of the catarrh, at which it is no longer possible to catch up with the catarrh, is determined from the condition (see Fig.ok)

$$v_{\min}\cos \beta=v_2,$$ where $\beta=\varphi-a$.

Since $\varphi=\arcsin \frac{v_2}{v_1}=\arcsin \frac{1}{2}=30^\circ$, $\cos \beta=\cos 45^\circ=\frac{1}{\sqrt{2}}$, and

$$v_{\min}=v_2\sqrt{2}\approx 2.8$$ km/h.

When the boat is moving at a speed of $v_0=2.5$ km/h ($v_0<v_{\min}$), the projection of the speed of the boat on the direction OA is less than $v_2$, therefore, no matter how long you stay on the shore, you can catch up with the boat with a seasoned movement strategy (the boundary of the accessibility area will definitely catch up with the boat).

S. S. Krogov

F1019. A small cylindrical vessel with base area S is lowered into a large vessel with a liquid whose density is $\rho_1$, in which a tube of length l (Fig.1) is left; The walls of the vessels are rigidly fastened to each other. A colored liquid with density $\rho_2$ ($\rho_2>\rho_1$) is poured into a small vessel to a height H so that the liquid levels in the large and small vessels coincide. At some point in time, the hole in the tube of liquid with density $\rho_2$ will flow into a larger vessel until the pressure at point A (Fig.2) from the liquid with density $\rho_1$ becomes equal to the pressure of the liquid with density $\rho_2$. From this condition it is easy to find the mass of liquid that will flow out of the small vessel for the first time.

To do this, we write down the equilibrium conditions (see Fig.2):

$$\rho_1g(H+l)=\rho_2g(h+l)=\rho_2g(H-\Delta h+l),$$

(1)

where $\Delta h=(H-h)$ is a decrease in the liquid level in a small vessel. From here

$$h=\frac{\rho_1}{\rho_2}H-\frac{\rho_2-\rho_1}{\rho_2}l,$$

And

$$\Delta m=\rho_2 \cdot \Delta h \cdot s=(\rho_2-\rho_1)(H+l)s$$

(s is the area of ​​the base of the small vessel).

To project a further solution, we will make some proposals.

1. The cross-sectional area of ​​a large vessel of the present is large that if liquid flows out of a small vessel or flows into it, then the level of liquid in the large vessel does not change.

2. The dynamism of the tube and the length of its present are small, so that the volume of this tube in comparison with the volumes of the vessels can be neglected, i.e. when the liquid from

⟦folio 29⟧

the tube leaks out, the liquid level in the small sauce does not change.

At first glance, it may seem that after the pressures at point $A$ are equalized, the process should stop; but that's not true. This situation is unsustainable. Let us assume that a liquid of density $\rho_1$ flows into the tube to a small height $\Delta x$ (Fig. 3); then the pressure at point $A'$ on the side of liquid with density $\rho_1$ will be greater than the pressure at point $A'$ on the side of liquid with density $\rho_2$.

Indeed, the pressure at point $A'$ on the side of a liquid with density $\rho_1$ will be equal to $p_1 = \rho_1 g(H + l - \Delta x)$, and on the side of a liquid with density $\rho_2 - p_2 = \rho_2 g(h + l - \Delta x)$; the difference between these pressures

$$\Delta p = p_1 - p_2 = (\rho_2 - \rho_1) g \cdot \Delta x$$

will move the liquid upward, since $\rho_1 g(H + l) = \rho_2 g(h + l)$ is the equilibrium condition (see (1)). Liquid with density $\rho_1$ will be in a small sauce until the pressures above and below at point $B$ (see Fig. 3) are equalized. A liquid with density $\rho_1$ will float above a liquid with density $\rho_2$ (according to the conditions of the problem, they do not mix).

Let us write down the equilibrium condition at the point $B$:

$$\rho_1 g H = \rho_1 g \Delta h_1 + \rho_2 g h,$$

where $\Delta h_1$ is the height of the liquid with density $\rho_1$, which is in a small sauce.

From (1) and (2) we find: $\Delta h_1 = \frac{\rho_2 - \rho_1}{\rho_1} l$, and

$$\Delta m_1 = (\rho_2 - \rho_1) l s.$$

Now that the reason for the flow of liquid from one sauce to another has become clear, let’s write the equilibrium equations in a more general case. Let us assume that equilibrium at point $B$ occurs at the moment when

$$\rho_1 g H = \rho_1 g h_1 + \rho_2 g h_2,$$

where $h_1$ is the height of liquid with density $\rho_1$ and $h_2$ is the height of liquid with density $\rho_2$ in a small sauce (Fig. 4). We already know that the equilibrium position is unstable, and liquid will flow out of the small sauce until the pressures at point $A$ equalize, which means that

$$\rho_1 g(H + l) = \rho_1 g h_1 + \rho_2 g(h'_2 + l).$$

From (3) and (4) we obtain: $\Delta h_2 = h_2 - h'_2 = \frac{\rho_2 - \rho_1}{\rho_2} l$, and

$$\Delta m_2 = (\rho_2 - \rho_1) l s.$$

When the pressures at point $A$ are equal, the position is unstable, and liquid of density $\rho_1$ will flow out in a small sauce until the pressures at point $B$ equalize, which means that

$$\rho_1 g H = \rho_1 g h'_1 + \rho_2 g h'_2.$$

From (4) and (5) we obtain: $\Delta h_3 = h'_1 - h_1 = \frac{\rho_2 - \rho_1}{\rho_1} l$, and

$$\Delta m_3 = (\rho_2 - \rho_1) l s = \Delta m_2.$$

This means that each time the same mass of liquid will flow out of the small sauce and into the text

$$\Delta m = (\rho_2 - \rho_1) l s.$$

Note that the volumes of liquid that flow from the sauce will vary; Why is this so, think for yourself.

V. E. Skorovarov

⟦folio 30⟧

F1020. A moving piston divides the cylinder into two equal parts with a volume of $V_0=10^{-3}$ m³. One part contains dry air, the other contains water vapor and $m=4$ g of water. As the cylinder slowly heats up, the piston begins to move. After the piston moved 1/4 of the length of the cylinder, the movement stopped. What mass of water vapor was in the vessel before heating? What is the mass of air in the container and its initial temperature? At what temperature did the piston stop moving? The dependence of saturated water vapor pressure on temperature is given in the table.

| $t, \text{°C}$ | $p_H \cdot 10^{-5}$, Pa |
| :--- | :--- |
| 100 | 1 |
| 120 | 2 |
| 133 | 3 |
| 152 | 5 |
| 180 | 10 |

F1021. In the circuit shown at figure, $R=100$ Ohm, $C=10$ mF, $U_0=10$ V, the internal resistance of the battery and the resistance of the ampere are negligible. Klioch K periodic temperature is negligible. Klioch K periodic temperature is negligible. Klioch K periodic temperature is negligible. Klioch K periodic temperature is negligible.

F1020. A moving piston divides the cylinder into two equal parts with a volume of $V_0=10^{-3}$ m³. One part contains dry air, the other contains water vapor and $m=4$ g of water. As the cylinder slowly heats up, the piston begins to move. After the piston moved 1/4 of the length of the cylinder, the movement stopped. What mass of water vapor was in the vessel before heating? What is the mass of air in the container and its initial temperature? At what temperature did the piston stop moving? The dependence of saturated water vapor pressure on temperature is given in the table.

| $t, \text{°C}$ | $p_H \cdot 10^{-5}$, Pa |
| :--- | :--- |
| 100 | 1 |
| 120 | 2 |
| 133 | 3 |
| 152 | 5 |
| 180 | 10 |

The movement of the piston will stop when all the water has evaporated; in this case, to the left and right of the piston there will be gases (air and water vapor), the state of which is described by the Mendeleev-Clapeyron equation. It is easy to understand that before this, when the piston moved, the volume of air decreased from $V_0$ to $V_0/2$, and the water vapor remained saturated all the time.

Let the initial temperature and pressure be $T_0$ and $p_0$, the final ones - $T_1$ and $p_1$, and the mass of water vapor before heating $M$. Then we can write the following equations: for air -

$$\frac{p_0V_0}{T_0} = \frac{p_1V_0}{2T_1};$$

for steam at the initial moment -

$$p_0V_0 = \frac{M}{\mu_\pi}RT_0, \quad p_0 = p_H(t_0),$$

at the end of the process -

$$p_1\frac{3}{2}V_0 = \frac{M+m}{\mu_\pi}RT_1, \quad p_1 = p_H(t_1),$$

where $\mu_\pi$ is the molar mass of water vapor. Solving equations (1) - (3) together, we find the mass of water vapor before heating:

$$M = m/2 = 2\text{ г.}$$

Using the table given in the conditions, we will plot the dependence $p_H(t)$ for water vapor (see figure). Then the temperature $T_0$ is determined from the condition of the intersection of this graph with the line $p = \frac{M}{\mu_\pi}\frac{R}{V_0}T$, and $T_1$ with the line $p = \frac{M+m}{\mu_\pi}\frac{2R}{3V_0}$. Using this graphical solution method, we find:

$$t_0 = 140 \text{ °C}, \quad t_1 = 170 \text{ °C},$$

$$p_0 \approx 3,8 \cdot 10^5 \text{ Па.}$$

Knowing the temperature $T_0=413$ K and the values ​​$p_0$, from the Mendeleev-Clapeyron equation for water ($\mu_B = 29 \text{ г/mоль}$) we find the mass of water $M_0$:

$$M_0 = \frac{p_0V_0\mu_B}{RT_0} \approx 3,2 \text{ г.}$$

A. I. Vuzdin

When the key is closed, the capacitors are charged almost instantly (the resistance of the ampere and the internal resistance of the battery are negligible) to a voltage of $U_3 = \frac{U_0}{2}$, and when the key is closed, they are almost completely discharged. Let's explain this.

Each capacitor is discharged through resistor $R$. Discharge current at the first moment -

$$I_0 = \frac{U_3}{R} = \frac{U_0}{2R}.$$

If this current did not change, then the capacitor would be completely discharged within the time

$$\tau = \frac{q}{I_0} = \frac{CU_3}{I_0} = RC.$$

In fact, the current decreases as the capacitor discharges, and the capacitor discharges more slowly

⟦folio 31⟧

her; Formally speaking, it never completely discharges. We are not interested in its absolutely complete discharge, but in one at which it is simply $U \ll U_3$; for this it is sufficient to require that $T_{\text{pa3p}} \gg \tau$. In our case $T_{\text{pa3p}} = \tau_2 = 20 \cdot 10^{-3} \text{ c} \gg \tau = 1 \cdot 10^{-3} \text{ c}$.

Let's calculate the charge flowing through the amperor when the key is closed:

$$q_1 = \frac{U_0}{2R} \tau_1 - C \frac{U_0}{2}$$

(the voltage across the resistor is $\frac{U_0}{2}$, the current of the resistors flows through the amperor).

When open, both capacitors are discharged through the ampere:

$$q_2 = 2 \frac{CU_0}{2}$$

Average current

$$I_{\text{cp}} = \frac{q_1 + q_2}{\tau_1 + \tau_2} = \frac{-C \frac{U_0}{2} + \frac{U_0}{2R} \tau_1 + CU_0}{\tau_1 + \tau_2} = \frac{U_0}{2R} \frac{\tau_1 + RC}{\tau_1 + \tau_2} \approx 4,8 \cdot 10^{-3} \text{ A}$$

A. P. Zilberman

F1022. The black box contains a coil, a resistor and a capacitor and has three terminals. During his study, the following results were obtained.

In the circuit shown at figure 1, the ampere showed $I_1 = 0,1$ A at the oscillator frequency $v_1 = 1000 \text{ Гц}$; the current through the ampere was out of phase with the input voltage at $\Delta \varphi_1 = \pi/6$. When the generator frequency was reduced by a factor of 100, the current increased by less than 2 times. The generator frequency was returned to its previous value and a voltmeter (Fig. 2) was connected to the circuit along with the ampere. Voltmeter

There are quite a lot of possible schemes (of the three elements mentioned in the conditions for specifying) - 24. Therefore, you must first draw them and decide which of them can, in principle, satisfy the conditions set. In order not to miss any circuits, you need to intelligently classify them - for example: first, let's draw all the circuits in which only a resistor is connected to point 2 (“promises”), then only a capacitor, then only a coil. There are only 12 such circuits. Then we will draw circuits where exactly two elements are connected to this pin - there are 6 of these circuits. There are still circuits left: none of the elements is connected to the common wire - there are 5 of them, and all three elements are connected to the common wire - there is only one such circuit. (We are not considering here schemes in which points 1 or 3 are not connected - it’s clear why.)

A fairly simple analysis shows that the conditions of the task can only be satisfied by the circuit shown in figure 3. In a circuit with an ampere-ampere connected in parallel with the capacitor (see Fig. 1), you can “throw away” the capacitor - the ampere is ideal, which means that no current flows through the capacitor at all. figure 4 shows such a “simplified” diagram (Fig. 4, a) and a vector diagram of directions (Fig. 4, b). From the diagram we have:

$$\frac{X_L}{R} = tg \frac{\pi}{6} = \frac{1}{\sqrt{3}},$$

where

$$X_L = \frac{1}{\sqrt{3}} R$$

$$I_1 \sqrt{R^2 + X_L^2} = I_1 \frac{2R}{\sqrt{3}} = U_0 \Rightarrow I_1 = \frac{\sqrt{3}}{2} \frac{U_0}{R}$$

At figure 5 there is a diagram of a “black box” with a connected voltmeter (Fig. 5, a) and a direction diagram (Fig. 5, b):

⟦folio 33⟧

Fig. 1.

From here, by the way, it follows that in case of “extreme bad luck” you won’t be able to do it in less than 1002 seconds: if the desired combination of three digits is the last, then the confs with this three digits will be pressed at the 1000th, 1001st and 1002nd seconds.

The goal is clear: to arrange all three-digit codes so that each next one begins with the last two digits of the previous one, but is it achievable?

Here is a similar situation where it cannot be achieved.

Let it be known that the digits of the three-digit code are different and that these are numbers 1, 2 and 3. In other words, you need to check only 6 codes: 123, 132, 213, 231, 312 and 321. If you manage to pull them into a chain, then selecting the code will take 8 seconds. But you can’t pull them into one chain! They form two chains (which ones?), so selecting the code will take not 8, but 10 seconds (check!).

A specially selected directed graph (abbreviated as oreraf) will help us deal with a possible question and limit the sequential verification of codes. This is the name given to a finite set of points (called oreraph vertices) if some of them are connected by arrows (arrows on which the direction is indicated); in particular, if the arrows oreraf are not excluded, then it is Eulerian, and the theorem is proven.

Fig. 2.

There are net arrows connecting the vertex to itself.

Organization $T_{10}$

Let's construct a digraph with the help of which problem a) is solved. Let's take 100 points. Let's fill in their parameters with numbers: 00, 01, 02, ..., 98, 99. From point $ab$ to point $dc$ we will draw an arrow if $b=d$. For example $13\rightarrow 38$, $45\rightarrow 55$; in particular, any point with a number of two identical digital connections to itself.

Let us denote the constructed digraph $T_{10}$.

On the arrow from $ab$ to $bc$ the typical three-digit code is $abc$: $13 \rightarrow 38$, $33 \rightarrow 333$. Any three-digit code will be written exactly 1 time: say, 455 will be written on the arrow from 45 to 55. Thus, $T_{10}$ contains 10 vertices and 1000 arrows with all possible three-digit numbers. In this case, 10 arrows come out of each vertex and 10 arrows enter each vertex: arrows $ab0$, $ab1$, ..., $ab9$ come out of $ab$, arrows $0ab, 1ab$, ..., $9ab$ enter $ab$.

Following the arrows, you can get from any vertex $ab$ to any vertex $cd$:

$$ab \xrightarrow{abc} bc \xrightarrow{bcd} cd.$$

Organizations that have this property will be called connected.

Let's remember: our goal is to pull all three-digit codes into a chain; the goal will be achieved if we go around $T_{10}$ along the arrows, going through each arrow exactly 1 time.

The existence of such an object is ensured by the Euler cycle theorem.

Let us call a digraph *regular* if for each of its vertices $A$ the number of arrows leaving $A$ is equal to the number of arrows entering $A$; We will denote this number $p_A$.

Examples: in $T_{10}$ for each vertex $ab$

$$p_{ab}=10;$$

figure 1 shows two regular connected digraphs (or, if you want, one regular disconnected digraph), with $p_A=2$ for some vertices and $p_A=1$ for others.

Theorem. In any regular connected digraph there is a cycle (a closed path along arrows) passing through each arrow exactly once (Fig. 2).

We will call such cycles Eulerian.

Proof of the Euler cycle theorem

Let's take any vertex $A$ and subdem from it along the arrows in an arbitrary manner, “burning places behind us” - erasing the arrows that we have already followed. Since the arrow is a finite number, at some step we will get stuck - we will come to a dead end from which there is no way out. We cannot get stuck at vertex $B \neq A$, since the same number of arrows come out of $B$ as enter $B$. This means that the dead end is the original vertex $A$.

So, our path is the cycle $c$, starting and ending at $A$. Since we immediately erased each arrow we followed, the cycle $c$ does not go through any arrow twice.

If the cycle $c$ contains all the arrows of the digraph, then it is Eulerian, and the theorem is proven.

If not, then among the vertices through which $c$ passes there will be a vertex $A_1$ from which the unerased arrow $s_1$ sticks out (if such vertices had not been found, our digraph would not be disconnected, Fig. 3).

⟦folio 35⟧

Fig. 7.

From the Euler cycle theorem it follows:
in problem c) time $t_{\min} = 722$ s (generally at $n > 3$ time $t_{\min} = n(n-1)(n-2) + 2$ s); with $n = 3$ due to the inconsistency of $D_3$ the pop code takes an extra 2 s: $t_{\min} = \text{не 8}, \text{а 10 с}.$

So, $t_{\min}$ in problems a), 6) and c) has been found. Try using the same method to find $t_{\min}$ if
1) there are 10 buttons and it is known that at least one of the digits of the three-digit code is nine;
2) there are 10 buttons and it is known that exactly two digits of the three-digit code are the same;
3) $2 \leq k \leq n$, buttons $n$, and the code is $k$-digit;
4) There are 6 buttons, on the buttons there are numbers 0, 1, ..., 5, all numbers of the three-digit code are different and the code contains the number 5.

Let's move on to discussing the second question:

How to find a forgotten code in the least amount of time?

From the previous it follows that you can act like this.
1) Take a suitable digraph ($T_{10}, T_3$ or $D_{10}$ in problems a), 6) and c) respectively).
2) Find the Eulerian cycle e in it.
3) Arbitrarily fixing the arrow $S_1$, take the arrows coming in the cycle e after $S_1$:
$S_1, S_2, ..., S_N$,
$N = \begin{cases} 1000 \text{ в задаче a)}, \\ 27 \text{ в задаче 6)}, \\ 720 \text{ в задаче b)}. \end{cases}$
4) Write down the three-digit arrow numbers $S_1, S_2, ..., S_N$ one after the other.
Since the number $S_{i+1}$ adds only one new digit to the number $S_i$, you can only indicate it (and not the entire number $S_{i+1}$); therefore, item 4) can be replaced with this:
4' Add to the number $S_1$ the third digit of the number $S_2$, then the third digit of the number $S_3$, etc. - up to $S_N$; the resulting sequence is $\Pi$ of $(N+2)$ digits. By pressing the buttons with these numbers, one per second, in $(N+2)$ s (i.e., in $t_{\min}$ time) we will go through all the three-digit codes that require verification and, therefore, in no more than $(N+2)$ s we will find the forgotten code.

Example: the cycle $e$ in the digraph $T_3$ with the first arrow 113 (Fig. 6) corresponds to the sequence $\Pi$ of 29 digits: 113 332 331 322 321 312 311 2 221 211 1.

Since $e$ is a cycle, the first and last pair of digits in the sequence $\Pi$ are the same (this is the number of the vertex from which the arrow $S_1$ comes out and into which the arrow $S_N$ enters). Therefore, instead of writing $N+2$ numbers $\Pi$ in a line, you can write $N$ numbers in a circle (see Fig. 9, where $N=27$).

On figure 9 along the rim of the wheel (we will call it wheel $B$) there are 9 units, 9 twos and 9 tracks in a special order. This entry contains the complete solution to problem 6). It remains to draw the same replacement wheels $A$ and $B$ for problem a) and c).

Are they the same replacements? What does this mean?

Dialogue about rings $A, B$ and $B$
— So, what is the replacement wheel $B$?
- Whatever number you take on it, if you go from it clockwise, reading one number at a time, then in 29 seconds you will come across all three-digit numbers of the numbers 1, 2, 3.
- Yes, this is a substitute (and wheels $A$ and $B$ should have similar properties), but this is not what has been replaced!
- You can go counterclockwise with an equal number!

- It’s possible, but this property follows from the first one. And both of them hold for a wheel constructed from any Euler cycle $e$ in $T_n$.
— So, then the cycle $e$ on figure 6 is special?
- Yes! It is built not according to a general recipe suitable for any regular connected digraph, but according to a special algorithm used by $T_n$.
- And what does this give?
— At $n=3$ the difference is not great. And in $T_{10}$ there are already a thousand arrows, and searching for $e$ in $T_{10}$ according to the general recipe may turn out to be too long and labor-intensive - even if you use a computer.
— Is there a special algorithm that is $e$ fast?
- Yes, I undertake to write a thousand numbers on the wheel $A$ in a thousand seconds! I don’t need a computer, I don’t need to fill in what numbers I’ve already written, I only need to remember the last 3-4 digits. My sequence is almost as simple as the natural series.
- Edorov! Is the sequence of 720 numbers on the wheel $B$ also simple? Can it be written out for 720 s?
- Yes! Although it was not easy to come up with this simple sequence...
...Here we will translate this dialogue so as not to deprive the reader of the convenience of introducing the substitution of numbers for the wheel $A$ and $B$, or even in the general case - for $k$-digit codes from $n$ numbers. (There are hints hidden in the text and in the pictures that reveal the secrets of constructing and quickly writing out the sequence $\Pi$; but perhaps you won’t need them, and you will go your own way.) And we hope, having received your letters, to return to this task in one of the next issues of the magazine.

M. L. Gerver
