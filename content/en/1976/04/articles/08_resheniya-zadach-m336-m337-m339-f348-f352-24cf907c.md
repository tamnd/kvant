---
id: 1976-4-resheniya-zadach-m336-m337-m339-f348-f352-24cf907c
issue: kvant_1976_4
year: 1976
number: "4"
title: Solutions to problems M336, M337, M339; F348—F352
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 41
page_labels: 32, 34, 35, 36, 37, 38, 39
tag: HG16
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9158098958d591e336c53a59a8d084dc18819f2faf136fccc4cb45e83ab7677a
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/08_resheniya-zadach-m336-m337-m339-f348-f352-24cf907c.md
source_content_sha256: 5c4166dc3fd7a5dc76cb6e60282696247fdfb9d82e0afe01f6e48c2324001adc
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

Problem solutions
M336, M337, M339; F348—F352

M336. In the given plane there is a finite set of polygons, each two of which have a common point. Let us prove that there is a line that has a common point with each of these polygons.

Fig. 1.

M337. Given an equilateral triangle ABC with a side of length 1. The first steps are to select point X on side AB, the second - point Y on side BC, then the first - point Z on side AC.
a) The goal of the first cerrok is to obtain a triangle XYZ with the largest area, the second - with the largest area. What is the largest area to provide first?
b) The goal of the first cerrok is to obtain a triangle XYZ with the largest perimeter, the second - with the largest perimeter. What is the largest perimeter the first can provide?

Let's project all the polygons onto some horizontal line m. The projection of each polygon will be a segment. Among the right ends of these segments, we select the leftmost one (let it be the right end A of the projection of the polygon M - see Figure 1) and draw a line l through it, perpendicular to the line m. The prime l intersects all polygons, since the lower polygon cannot lie entirely to the left of it (then the right end of its projection would be to the left of A), and the lower one cannot lie entirely to the right (since then it would not have common points with the polygon M).

S. Fomin

Fig. 2.

Fig. 3.

a) Let us first prove that the second player’s strategy is to place point Y on side BC, so that line XY is parallel to side AC. Indeed, if (XY') || (AC), and Y∈[BY'] (see Fig. 2), then the first player, with his second move, places point Z at vertex C; then SXYC > SXY'C, since these triangles have the same height, but the base of the first is larger. If Y∈[Y'C], then the first player will put point Z at vertex A, and again there will be SXYA > SXY'A, since these triangles have the same base, and the y height of triangle XYA is greater (Fig. 3).

Therefore (XY) || (AC), and where on [AC] the first player places point Z, nothing depends:

$$S_{XYZ} = S_{XYA} = \frac{1}{2} \cdot |XY| \cdot (H - h),$$

(here H = \frac{\sqrt{3}}{2} is the height of triangle ABC, h is the height of triangle XBY). Expressing |XY| through h, we get that the required area is a square triangle from h. This trinomial takes a maximum value of $\frac{H^2 \sqrt{3}}{12} =$

⟦folio 34⟧

Fig. 7.

M339*). Given a horizontal strip on a plane, the edges of the strip are parallel lines, and n straight lines intersect this strip. Every two of these n straight lines intersect inside the strip and no straight lines pass through the same point. The distance is all paths starting at the bottom edge of the strip, going according to the data of a straight line and ending at the top edge, having the maximum property: one along the maximum of the path, we are always going up; the other is straight to the point of intersection, we must go to another straight line. Let us prove that among the maxima

a) there are paths consisting of at least n segments;
b) there are paths passing along at most $\frac{n}{2} + 1$ straight;
c) there are paths passing through all n that are straight.

Fig. 8.

By squaring both sides of the equation (*), we get:

$$2x^2 - 3x + 2 = 2(1 - x)\sqrt{x^2 + x + 1},$$

where

$$8x^3 - 17x^2 + 8x = 0,$$

$$x = |AE| = \frac{17 - \sqrt{33}}{16}$$

(check that this is a valid root of the equation (*)). The required perimeter is equal to

$$2|EC| = 2\sqrt{x^2 - x + 1} = \frac{3}{8}\sqrt{2(17 - \sqrt{33})}.$$

M. Bronstein

Let us denote the points of intersection of the straight lines with the lower edge of the strip in order (from left to right) by $A_1, A_2, \dots, A_n$ (Fig. 7). We denote the points of intersection of the same lines with the upper edge of the strip as $B_1, B_2, \dots, B_n$.

Let's list some properties of the path that are mentioned in the conditions.

1°. There is exactly one path along each segment of each straight line. Indeed, the correct ones, formulated in the conditions, allow the only way to continue the path up and down to the edges of the strip.

2°. There are n different paths: each point $A_1, \dots, A_n$ has its own path. Let's put them in order: 1st, 2nd, ..., nth.

3°. A path starting at point $A_k$ ends at point $B_k$. In fact, according to the rules, each path at the point of intersection of lines goes to another line, therefore (Fig. 8) paths cannot intersect each other, but only touch at their vertices. Thus, the $k$th path divides the stripe into two regions - the left one, in which all paths numbered $i < k$ are located, and the right one, in which all paths numbered $i > k$ are located. Therefore the $k$th path will end at $B_k$ (Fig. 9).

Let us proceed to the proof of individual statements of the problem.

a) Let us calculate the total number of segments in all paths together in two ways. On the one hand, each line is divided into n segments, since it is crossed by n-1 other lines; therefore, the total number of segments is $n^2$. On the other hand, we must obtain the same sum $n^2$ by adding the number of segments in all n paths (we use $1^\circ$ and $2^\circ$ here). It follows that at least one of the paths has at least n segments.

b) Let's estimate the number of segments in two extreme paths: 1st and nth. These paths, very indo, bound convex sets: the first is the set of points lying in all lines, the last is the set of points lying in all lines (Fig. 10). It is clear that the first path lies to the left of the broken line $A_1PB_1$, the last one to the right of the broken line $A_nPB_n$, where $P$ is the intersection point of ($A_1B_n$) and ($A_nB_1$), and only the initial and final segments of both paths lie on the straight lines $A_1B_n$ and $A_nB_1$. As for each of the remaining n-2 straight lines $A_2B_{n-1}, A_3B_{n-2}, \dots, A_{n-1}B_n$, they can have

*) For the solution to problem M338, see the article by Yu. Ionin and L. Kurlyandik “Ponsk invariant”, published in «Kvant», 1976, No. 2.

⟦folio 35⟧

F348. The spacecraft approaches the Moon along a parabolic trajectory, almost touching the lunar surface. To move to a stellating circular orbit (i.e., a circular orbit very close to the surface of the Moon), at the moment of greatest closeness with the Moon, the frost thruster is turned on. Determine how much the ship's speed will change when performing this maneuver. Acceleration of gravity on the surface of the Moon $g_{\pi} \approx 1,7 \text{ m/сек}^2$, radius of the Moon $R_{\pi} \approx 1,7 \cdot 10^6 \text{ m}$.

Additional question. Try to estimate what part of the ship's largest mass should be complex fuel if we select a product with a relative speed of $v = 4 \cdot 10^3 \text{ m/сек}$.

When bodies move in the gravitational field of a planet (or star), the total mechanical energy (i.e., the sum of kinetic and potential energy) is conserved. Depending on the value of the total energy $E$, the trajectories have a different character$^*$.

At $E < 0$ the body cannot move to an infinitely large distance; in this case, its trajectory has the form of an ellipse (Kepler's first law). At $E > 0$ the body moves away to infinity, having an extra supply of kinetic energy (hyperbolic trajectory). At $E = 0$ the body also goes to infinity, but in this case its speed at infinity becomes zero; the trajectory of the body has the form of a parabola.

When moving along a parabolic trajectory, the speed of the body approaching the planet is equal to the second cosmic speed. This is the name given to the minimum speed at which a body, starting from the surface of a planet, can move away from it to an infinite distance. For the point of greatest intensity with the Moon (Fig. 11) we can write:

$$E = K + \Pi = \frac{mv^2}{2} - \gamma \frac{M_{\pi} m}{R_{\pi}} = \frac{mv^2}{2} - g_{\pi} R_{\pi} m = 0.$$

Here $v_{\pi}$ is the speed of the ship at the moment of greatest acceleration with the Moon (second escape velocity); $\Pi = -\gamma \frac{M_{\pi} m}{R_{\pi}}$ is the potential energy of the ship near the Moon$^{**}$.

*) See, for example, the article by K. Kovalenko and M. Crane “Ballistic problem in space”, 1973, No. 5.

**) See, for example, the article by S. Kozel “Physical analogues”, 1975, No. 11.

⟦folio 36⟧

For speed $v_{II}$ we get:

$$v_{II} = \sqrt{2g_{\text{Л}}R_{\text{Л}}} \approx 2,4 \cdot 10^3 \text{ m/сек.}$$

During the braking process, the speed of the ship must, according to the given condition, decrease to the first cosmic speed (for the Moon) $v_I$. This speed can be determined from the condition of the ship moving in a circular orbit:

$$\frac{mv_I^2}{R_{\text{Л}}} = \gamma \frac{M_{\text{Л}}m}{R_{\text{Л}}^2} = g_{\text{Л}}m; \quad v_I = \sqrt{g_{\text{Л}}R_{\text{Л}}} \approx 1,7 \cdot 10^3 \text{ m/сек.}$$

Thus, the speed of the ship should change by amounts

$$\Delta v = v_{II} - v_I \approx 0,7 \cdot 10^3 \text{ m/сек.}$$

To answer the (additional) question and estimate the mass $m$ of the burned fuel, we can use the law of conservation of momentum. Let us assume for calculation control that products of sort mass $m$ were ejected from the nozzle in packages in the form of one portion with a relative speed $v$. Let us write the law of conservation of momentum in the reporting system associated with a ship moving at speed $v_{II}$:

$$(M_0 - m)\Delta v = mv,$$

where $M_0$ is the initial mass of the ship. From here

$$m = \frac{\Delta v}{v + \Delta v} M_0 \approx 0,15 M_0,$$

i.e., the burned fuel should be approximately 15% of the original mass of the ship.

You can find the fuel mass more strictly. To do this, you need to use the Tsiolkovsky formula. This formula expresses the change in the speed of the spacecraft $\Delta v$ through the ratio of its initial $M_0$ and final $M$ masses:

$$\Delta v = v \ln \frac{M_0}{M}$$

(v is the relative speed of the variety's product source). From here

$$M = M_0 e^{-\frac{\Delta v}{v}} = M_0 e^{-0,175} \approx 0,84 M_0,$$

i.e., the burned fuel is approximately 16% of the initial mass of the ship.

Note that the Tsiolkovsky formula takes into account the continuous process of sourcing products from the nozzle packages, so the result obtained with its help is more accurate.

S. Kozel

F349. One kilomole of an ideal monatomic gas under normal conditions is transferred from state 1 to state 2 in two ways: $1 \rightarrow 3 \rightarrow 2$ and $1 \rightarrow 4 \rightarrow 2$ (Fig. 12). The name of the amount of heat output that must be generated by the gas in these two processes.

According to the first law of thermodynamics, the amount of thermal energy $Q$ imparted to the gas goes towards changing the internal energy of the gas $\Delta U$ and doing work $A$ by the gas:

$$Q_I = \Delta U_I + A_I, \quad Q_{II} = \Delta U_{II} + A_{II}.$$

Here index I refers to process $1 \rightarrow 3 \rightarrow 2$, and index II refers to process $1 \rightarrow 4 \rightarrow 2$.

Since the gas is monatomic, then for one mole

$$U = \frac{3}{2} RT, \quad \Delta U = \frac{3}{2} R\Delta T.$$

This shows that the change in the internal energy of a gas during the transition from state 1 to state 2 depends only on the change in gas temperature $\Delta T = T_2 - T_1$ and does not depend on

⟦folio 37⟧

the way in which gas is transferred from one state to another. Hence,

$$\Delta U_1 = \Delta U_{II} = \Delta U = \frac{3}{2} R (T_2 - T_1).$$

In order to find the gas temperatures $T_1$ and $T_2$, we write the equation of state of an ideal gas for states 1 and 2 (see Fig. 12):

$$p_0 V_0 = RT_1, \quad 2 p_0 \cdot 2 V_0 = RT_2,$$

where

$$T_2 - T_1 = \frac{3 p_0 V_0}{R}, \quad \Delta U = \frac{9}{2} p_0 V_0.$$

Now let's find the work of the gas $A_1$ and $A_{II}$. In the first case (process $1 \rightarrow 3 \rightarrow 2$), the gas does not do work in section $1 \rightarrow 3$, but during isobaric expansion in section $3 \rightarrow 2$ the gas does work

$$A_1 = p \Delta V = 2 p_0 (2 V_0 - V_0) = 2 p_0 V_0.$$

In the second case (process $1 \rightarrow 4 \rightarrow 2$), the gas does work only in section $1 \rightarrow 4$:

$$A_{II} = p_0 (2 V_0 - V_0) = p_0 V_0.$$

Thus,

$$Q_1 = \Delta U + A_1 = \frac{13}{2} p_0 V_0,$$

$$Q_{II} = \Delta U + A_{II} = \frac{11}{2} p_0 V_0.$$

The ratio of the amount of heat is

$$\frac{Q_1}{Q_{II}} = \frac{13}{11}.$$

F350. The name of the direction on resistance $R$ in the circuit shown in figure 13, depends on the value of this resistance. E. d. c. all sources are equal to $\mathcal{E}$, their internal resistances are $r$. The diode of the sieves is ideal (its resistance in the forward direction is zero, and in the reverse direction it is infinitely large).

Fig. 15.

If the resistance $R$ is large, the current, and the flow through it, is very small, and the potential difference between points $B$ and $A$ (see Fig. 13) is close to $2\mathcal{E}$. In this case, the potential l of point $B$ is higher than the potential of point $C$ (equal to $\mathcal{E}$, if we consider the potential of point $A$ to be equal to zero), the diode is closed, and the current does not flow through the circuit section $ACB$. Then this circuit can be replaced in a simple circuit with two sources connected in series with resistance $R$ (Fig. 14). In this circuit there is a current $I = \frac{2\mathcal{E}}{2r + R}$, and the direction drop across the resistance $R$ is equal to

$$U_R = \frac{2\mathcal{E} R}{2r + R}.$$

As the resistance $R$ decreases, the current in the circuit increases, the direction drop across the internal resistances of the sources increases, and the potential difference between points $B$ and $A$ decreases. This will happen until the potential of point $B$ becomes equal to the potential of point $C$, i.e. while the diode remains closed. The diode will open at the moment when the direction between points $B$ and $C$ becomes zero, and between points $B$ and $A$ - $\mathcal{E}$. This means that at this moment the direction drop across the resistance $R$ is equal to $\mathcal{E}$, i.e.

$$\frac{2\mathcal{E} R}{2r + R} = \mathcal{E},$$ or $R = 2r$.

Now let's find the direction at resistance $R$ when $R < 2r$. In this case, the diode resistance is zero, and the circuit can be represented as shown in figure 15.

⟦folio 38⟧

In this case
$$U'_R = I'R = \mathcal{E} - I_1 r = 2\mathcal{E} - I_2 \cdot 2r,$$
$$I' = I_1 + I_2.$$

From here
$$I' = \frac{4\mathcal{E}}{2r + 3R} \text{ и } U'_R = \frac{4\mathcal{E}R}{2r + 3R}.$$

Thus,
$$U_R = \frac{2\mathcal{E}R}{2r + R} \text{ при } R \geq 2r,$$
$$U_R = \frac{4\mathcal{E}R}{2r + 3R} \text{ при } R \leq 2r.$$

F351. With a weak impact, the function of the ball against the wall is its deformation x, which is much less than the radius of the ball R, and it is possible, with a good approximation, that the air pressure p in the ball does not change during the impact.

Neglecting the elasticity of the tire, estimate the time of impact of the ball with the wall. Carry out a numerical calculation for a knot when the mass of the ball is m = 0.5 kg, the pressure in it is p = 2 atm and the radius R = 12.5 cm.

Let's look at the dreams that affect the ball during impact. These are the reaction force from the wall N and the atmospheric pressure force Fa.

According to Newton's third law, the force N is numerically equal and oppositely directed from the left of the ball to the wall Fd. Since the elasticity of the ball tire can be neglected, then
$$N = F_d = pS = p\pi r^2$$
($S = \pi r^2$—the area of ​​contact of the ball with the wall, see Fig. 16). The force N is directed perpendicular to the wall, i.e. horizontally to the right.

In order to find the atmospheric pressure, the volume of the contact surface of the ball with the surrounding influence is divided into small areas with an area of ​​$\Delta s_i$. Each area is affected by the atmospheric pressure $\Delta F_i$ (Fig. 17), the direction is perpendicular to the surface and is equal in abscilot value $\Delta F_i = p_0 \Delta s_i$ ($p_0$—atmospheric pressure). Thanks to symmetry, it is clear that the vertical processes of all forces $\Delta F_i$ add up to zero, so the equilibrium of the ball $= \sum \Delta F_i$ is directed horizontally to the left and is equal in magnitude (see Fig. 17)
$$F_a = \sum \Delta F_i \cos \alpha = p_0 \sum \Delta s_i \cos \alpha.$$
The value $\Delta s_i \cos \alpha$ is the projection of the plane, and $\sum \Delta s_i \cos \alpha$ is the sum of such processes, equal to the projection of the plane of contact of the ball with the surrounding influence,
$$\sum \Delta s_i \cos \alpha = \pi r^2, \text{ и } F_a = p_0 \pi r^2.$$
Let’s now find the abscylotic value of dreams F = N + Fa:
$$F = N - F_a = (p - p_0) \pi r^2 = (p - p_0) \pi [R^2 - (R - x)^2] = (p - p_0) \pi (2Rx - x^2).$$
Since the deformation of the ball x is small compared to its radius R, the values ​​$x^2$ can be neglected in comparison with the values ​​2Rx. Then F = 2πR (p - p_0) x, or taking into account that this force is directed opposite to the deformation,
$$F = -2\pi R (p - p_0) x = -kx.$$
Thus, the force F is proportional to the magnitude of the deformation x ($k = 2\pi R (p - p_0)$ is the coefficient of proportionality; it does not change during the impact), i.e., it is elastic in nature. Under the influence of such sleep, the body can oscillate with a period of $T = 2\pi \sqrt{\frac{m}{k}}$, where m is the body mass.

⟦folio 39⟧

Obviously, the time t of the ball colliding with the wall is exactly equal to half the period of oscillation, i.e.

$$\tau = \frac{T}{2} = \pi \sqrt{\frac{m}{k}} = \sqrt{\frac{\pi m}{2R(p-p_0)}} \approx 8 \cdot 10^{-3} \text{ сек}.$$

◆

Let us find an expression for the voltage across the load in the general case.

Let us denote by $R_1$ and $R_2$ the resistances of the parts of the rheostat into which the engine divides it, and redraw the circuit as shown in figure 19.

The voltage on the load is equal to the voltage on the section $AB$, containing resistances $R$ and $R_2$ connected in parallel. They can be replaced by one equivalent resistance $R_3 = \frac{R R_2}{R + R_2}$.

The voltage across this equivalent resistance (and therefore across the load) is obviously equal to $U = IR_3$, where $I = \frac{U_{BX}}{R_1 + R_3} - \text{tok в цепи}, \text{ т. е. } U = U_{BX} \frac{R_3}{R_1 + R_3}$.

Since $R_1 = R - R_2$, then

$$U = U_{BX} \frac{R_3}{R - R_2 + R_3} = U_{BX} \frac{R R_2}{R^2 - R_2^2 + R R_2}.$$

Divide the numerator and denominator in this formula by $R^2$:

$$U = U_{BX} \frac{\alpha}{1 - \alpha^2 + \alpha}, \text{ где } \alpha = \frac{R_2}{R}.$$

In the original circuit $R_2 = R/2$, i.e. $\alpha_1 = 1/2$ and the voltage across the load

$$U_1 = U_{BX} \frac{1}{2(1 - 1/4 + 1/2)} = \frac{2}{5} U_{BX}. \tag{1}$$

When the voltage at the input of the circuit doubles, the voltage across the load

$$U_2 = 2U_{BX} \frac{\alpha_2}{1 - \alpha_2^2 + \alpha_2}, \tag{2}$$

where $\alpha_2$ is the new value of $R_2/R$.

But according to the conditions of the problem, the voltage at the load in general cases should be the same. Therefore, according to equalities (1) and (2)

$$\frac{2}{5} U_{BX} = 2U_{BX} \frac{\alpha_2}{1 - \alpha_2^2 + \alpha_2}.$$

From here

$$\alpha_2^2 + 4\alpha_2 - 1 = 0.$$

Solving this equation, we get

$$\alpha_2 = -2 \pm \sqrt{4+1} = -2 \pm \sqrt{5}.$$

Since $\alpha_2 > 0$, it is equal to $\sqrt{5} - 2$. Therefore, the engine needs to be moved so that

$$R_2 = (\sqrt{5} - 2) R.$$

N. Slovodechkiy
