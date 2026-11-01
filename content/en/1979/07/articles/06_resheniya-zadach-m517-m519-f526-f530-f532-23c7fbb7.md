---
id: 1979-7-resheniya-zadach-m517-m519-f526-f530-f532-23c7fbb7
issue: kvant_1979_7
year: 1979
number: "7"
title: Solutions to problems M517—M519; F526, F530—F532
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 34
page_labels: 24, 25, 27, 28, 29, 30, 31, 32
tag: QMC1
lang: en
source: kvant_digital
extraction: vision
content_sha256: d532c3578cada994a809524984347730763846ecb001001c08282f8eb80f6bd1
prompt_sha256: draft-1
translated_from: content/ru/1979/07/articles/06_resheniya-zadach-m517-m519-f526-f530-f532-23c7fbb7.md
source_content_sha256: 219b2b0def20f0214126e982df2dd2d44bdb0b813dad4673a25478859a4dc994
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

F587. A conductor of mass $M$ and length $l$ is suspended from the dielectric at its ends using two identical conducting weightless springs with a common stiffness coefficient $k$. An emkosti capacitor $C$ is connected to the upper ends of the springs. The entire structure hangs in a uniform magnetic field with induction $\vec{B}$, perpendicular to the plane from the equilibrium position and is released. Determine the further movement of the conductor in the vertical plane. Neglect the resistance, self-inductance and capacitance of the conductors. (10)

D. Futorsky

Problem solutions

M517—M519; F526, F530—F532.

We need the following simple lemma: let triangles $ABC_1$ and $ABC_2$ have a common base $[AB]$ of length $R$; model

1) if vertices $C_1$ and $C_2$ lie on opposite sides of $[AB]$, then

$$S_{ABC_1} + S_{ABC_2} \leq \frac{1}{2} R \cdot |C_1C_2| \quad (\text{рис. 1, a})$$

2) if vertices $C_1$ and $C_2$ lie on the same side of $[AB]$, then

$$|S_{ABC_1} - S_{ABC_2}| \leq \frac{1}{2} R \cdot |C_1C_2| \quad (\text{рис. 1, 6})$$

Prove this lemma yourself.

Let's now start solving the problem. Let $A_1A_2 \dots A_n$ be a $n$-gon inscribed in a circle with center $O$; $B_1B_2 \dots B_n$ is the second $n$-gon (with vertices at the marked points), with $B_1 \in [A_1A_2]$, $B_2 \in [A_2A_3]$, etc.; let $P$ be its perimeter. Consider the triangles $OA_1B_1$, $OB_1A_2$, $OA_2B_2$, ..., $OB_nA_1$. If the center of the circle $O$ belongs to the polygon $A_1A_2 \dots A_n$, then these triangles do not overlap in pairs and their union gives the polygon $A_1A_2 \dots A_n$ (Fig. 2), so the area $S$ of the polygon $A_1A_2 \dots A_n$ is equal to the sum of the areas of these triangles. According to the lemma, the areas of two such triangles with a common base $[OA_k]$ do not exceed
dit $\frac{1}{2} |OA_k| \cdot |B_{k-1}B_k| = \frac{1}{2} R \cdot |B_{k-1}B_k|$ (we believe
of course, $B_0 = B_n$), so

$$S = (S_{OB_1A_2} + S_{OA_2B_2}) + \dots + (S_{OB_nA_1} + S_{OA_1B_1}) \leq \frac{1}{2} R (|B_1B_2| + \dots + |B_nB_1|) = \frac{1}{2} RP, \quad (1)$$

whence $P \geq 2S/R$.

If the center $O$ lies in the non-polygon $A_1A_2 \dots A_n$, say, on opposite sides of it from the chord $A_nA_1$ (Fig. 3), then the areas of triangles $OA_nB_n$ and $OB_nA_1$ are included in the sum forming the area $S$, with a minus sign:

$$S = (S_{OB_1A_2} + S_{OA_2B_2}) + \dots + (S_{OB_n-1A_n} - S_{OA_nB_n}) + (S_{OA_1B_1} - S_{OB_nA_1}).$$

Applying the lemmy again, we obtain the required inequality.

⟦folio 25⟧

In conclusion, we note that if the sides $B_{k-1}B_k$ of the polygon $B_1B_2 \dots B_n$ are perpendicular to the corresponding radius $OA_k$, then inequality (1) turns into an equality, so that in this case the polygon $B_1B_2 \dots B_n$ has the smallest possible perimeter $2S/R$. We invite the reader, to use this, to prove that the triangle $B_1B_2B_3$, inscribed in a given acute triangle $A_1A_2A_3$, has a minimum perimeter of a moeda and a molko moreda, when $B_i$ ($i=1, 2, 3$) are the bases of the height of the triangle $A_1A_2A_3$.

V. Dubrovsky

**Fig. 3.**

**M518. The numbers $x_1, x_2, \dots, x_n$ belong to the segment $[a; b]$ and $0 < a < b$. Proof of inequality**

$$\left( x_1 + x_2 + \dots + x_n \right) \times \left( \frac{1}{x_1} + \frac{1}{x_2} + \dots + \frac{1}{x_n} \right) \leq \frac{(a+b)^2}{4ab} n^2.$$

**Fig. 4.**

**Fig. 5.**

Let us first outline the geometric idea of ​​one of the shortest proofs.

Consider on the plane $Oxy$ $n$ the points $\left( x_i; \frac{1}{x_i} \right)$, $i = 1, 2, \dots, n$. These points lie on the hyperbola $y = \frac{1}{x}$, and by condition $a \leq x_i \leq b$. Point $M^*(x^*; y^*)$ with coordinates $x^* = \frac{x_1 + x_2 + \dots + x_n}{n}, y^* = \frac{\frac{1}{x_1} + \frac{1}{x_2} + \dots + \frac{1}{x_n}}{n}$ (1)

— center of gravity $n$ of identical material points $\left( x_i; \frac{1}{x_i} \right)$. Therefore, it belongs to a convex figure bounded by two hyperbolas and a line segment with endpoints at points $A\left( a; \frac{1}{a} \right)$ and $B\left( b; \frac{1}{b} \right)$ (Fig. 4).

The product $x^*y^*$ is the area of ​​the rectangle shaded on figure 4 - the maximum is sufficient when the point $M^*$ falls in the middle of the segment $AB$. Indeed, it is clear that if $(x^*; y^*)$ does not lie on $[AB]$, then the area can be increased by moving the point $M^*$ onto the segment $AB$. And for the point $(x; y)$ of this segment $y$ is a linear function of $x$, therefore, the area $s(x)=xy$ is a square trinomial of $x$. Since $s(x)$ takes the same values $s(a)=s(b)=1$ at $x=a$ and $x=b$, and $s(0)=0$ (Fig. 5), the maximum $s(x)$ is achieved after the disk $x=a$ and $x=b$ - at $x=\frac{a+b}{2}$, $y=\frac{1}{2}\left(\frac{1}{a}+\frac{1}{b}\right)$.

Hence $x^*y^* \leq \frac{a+b}{2} \cdot \frac{\frac{1}{a}+\frac{1}{b}}{2} = \frac{(a+b)^2}{4ab}$, which is what needs to be proved.

The only thing that needs a more mathematical justification is the fact that the “center of gravity”—the point with coordinates (1)—lies on the same segment $AB$. Note that the equation of the line $AB$ has the form $aby+x=a+b$ (check that the points $A$ and $B$ lie on this line), so the main step of our proof is the inequality

$$aby^*+x^* \leq a+b.$$ (2)

Now everyone is ready to briefly formulate the proof (to which we could limit ourselves): for each $i$

$$\frac{ab}{x_i} + x_i \leq a+b,$$ (3)

since $(x-a) (x-b) \leq 0$ is for $x \in [a; b]$. Slu-

⟦folio 27⟧

If $\alpha \in I$, then also $\frac{1}{\alpha} \in I$. Let $\gamma > 1$ be the correct end of this single segment. Then $\gamma - 1$ is its left end and must be $\gamma - 1 = \frac{1}{\gamma}$. From this we find that $\gamma = \frac{\sqrt{5} + 1}{2}$ (this number is known as the “golden section”). The distance is $(i, j)$ such that $\frac{i}{j} = \alpha \in ]\gamma - 1; \gamma[$ (Fig. 6), and $\frac{i}{j} \neq 1$. Let's assume that $i > j$; then $\alpha \in ]\gamma - 1; \gamma[$. In this situation, the player has a single move $(i, j) \rightarrow (i - j, j)$, for which

$$\alpha' = \frac{i - j}{j} = \frac{i}{j} - 1 = \alpha - 1 < \gamma - 1,$$

that is, this single move leads to a situation with the relation $\alpha'$ outside the integral $]\gamma - 1; \gamma[$. In addition, the game does not end on this move.

Let now $\frac{m}{n} = \alpha \notin ]\gamma - 1; \gamma[$ and $\frac{m}{n} \notin Z$ (the case when the relation $\frac{m}{n}$ is an integer is described above); let us put, for definiteness, $m > n$. There is a $k \in Z$ such that $\frac{m}{n} - k \in ]\gamma - 1; \gamma[$, so after the move $(m, n) \rightarrow (m - kn, n)$ we get a situation with a ratio that is in the integral $]\gamma - 1; \gamma[$ and is not equal to one (since $m/n \notin Z$).

From here we get a winning strategy for a beginner in the game. If $\frac{m}{n} \in Z$, then he wins with his first move. If $\frac{m}{n} \notin Z$ and $\frac{m}{n} \notin ]\gamma - 1; \gamma[$, then with each move he adds a property so that the relation $\frac{m_k}{n_k}$ falls into the integral $]\gamma - 1; \gamma[$, after which his opponent can make a single move, leading again to a situation with a relation outside the specified integral. It is clear that in the end the beginner plays. On figure 7, red dots correspond to winning situations $(m, n)$, black ones to losing ones.

Thus, statement 6) of the problem is true for all $\alpha > \gamma$ ($\gamma = \frac{\sqrt{5} + 1}{2}$).

A. Slinko

When solving this problem, as is often the case not only in elementary mathematics, but also in server-based mathematical research, a “guessed” answer helped us a lot: at some points we assumed that all rational non-integer points of some integral of unit length are losing ones, and after that we quickly added the research to the end. But in this problem we can do without such an additional step: the number $\gamma$ arises in it naturally from the following reasoning. As already noted, all losing points belong to the integral $]1/2; 2[$. It is also easy to say that if point $x \in ]1; 2[$ is losing (winning), then point $x - 1$ is winning (losing). Therefore, all points of the integral $]1; 3/2[$ are losing, and we only have to study the points of the integral $]3/2; 2[$. Let's assume that point $x \in ]3/2; 2[$ is a losing one. Then the points $x - 1$ and $1/(x - 1)$ are winning, and $1/(x - 1)$ is less than 1.

⟦folio 28⟧

Therefore, $1/(x-1)-1=(2-x)/(x-1)$ is a losing point. So, if point $x \in ]3/2; 2[$ is a losing one, then point $(2-x)/(x-1)$ is also a losing one. Let's draw a graph of the function $(x-1)/(2-x)$ (Fig. 8). figure 8 shows how to use point $x$ to find point $(x-1)/(2-x)$. During the transformation $x \rightarrow (x-1)/(2-x)$ there is a fixed point - the root of the equation $x^2-x-1=0$, which belongs to the interval $]3/2; 2[$ (this is the number $\gamma$). It is easy to prove that if a point is located to the right of point $\gamma$, torations and (repetitions) of our transformation will sooner or later take it beyond point 2. (One of the possible proof schemes is given in figure 9: the tangent of the angle of inclination of the black straight line passing through the fixed point $(\gamma; \gamma^2-\gamma-1)$ is equal to 2, and the tangent to the curve $(x-1)/(2-x)$ goes in a circle - make sure in this.)
Therefore, all points from the interval $]\gamma; 2[$ are winning and, therefore, all points from the intervals $]\gamma; \infty[$ and $0; \gamma^{-1}]$ are winning. Similarly, if we assume that some point from the interval $]3/2; \gamma[$ is a winning one, then by increasing it we get a point from the interval $]1; 3/2[$, which means that all points from the interval $]1; \gamma[$ are losing ones. Of course, this solution is more cumbersome. However, it is also more respectable!

F526. Place the melt-insulated walls of the flask and the thermometer is evacuated to a pressure of $p=10^{-5}$ atm (at room temperature). The capacity of the flask is 1 liter, the surface area of ​​the flask is $S=600\text{ cm}^2$. Estimate the time during which tea is at maximum thermosestim from $90^\circ\text{C}$ to $70^\circ\text{C}$. Water capacity $c=4,2 \cdot 10^3$ J/(sq.K); universal gas constant $R=8,3$ J/(K mol). I know how to ignore me through a traffic jam.

Heat is removed from the inner wall of the flask (from tea) by gas molecules remaining in the cavity between the inner and outer walls of the flask. This is why they turn off the walls so that the gas remaining there does not form a continuous heat-conducting medium, that is, so that the molecules move between the walls without colliding with each other.

We will assume that after colliding with the wall the molecule has on average an energy proportional to the temperature of the wall. After removal from the outer wall, the kinetic energy of the translational motion of the molecule is $\varepsilon_1 \sim 3/2$ $kT_K$, where $T_K$ is room temperature; after removing it from the inner wall $\varepsilon_2 \sim 3/2$ $kT'$, where $T'$ is the temperature of the tea. This temperature changes all the time. However, the inversion of the change $T'$ is not VELik ($\Delta T=363\text{K} - 343\text{K} = 20\text{K}$). Therefore, for evaluation, we can assume that $\varepsilon_1 \sim 3/2$ $kT_C$, where $T_C=353\text{K}$ is the average value of the hot wall temperature.

Consequently, each molecule, when removed from the hot wall, “takes” energy from the tea

$$\Delta \varepsilon \sim 3/2 k (T_C - T_K).$$

The number of molecules contained with a hot wall per unit time is proportional to $1/2 n |v_x| S$, where $n$ is the density of gas molecules, $|v_x|$ is the average molecule velocity of molecules on the $OX$ axis perpendicular to the wall. Number of molecules hitting the wall in time $\Delta t$,

$$N \sim 1/2 n |v_x| S \Delta t.$$

These molecules will take energy from the tea

$$\Delta E = N \Delta \varepsilon \sim 3/4 n |v_x| Sk (T_C - T_K) \Delta t.$$

Obviously, this energy is equal to the change $\Delta U$ of the internal energy of tea during the time $\Delta t$: $\Delta E = \Delta U$. Because

$$\Delta U = Mc\Delta T,$$

where $\Delta T$ is the change in tea temperature,

$$3/4 n |v_x| Sk (T_C - T_K) \Delta t \sim Mc\Delta T.$$

From here

$$\Delta t \sim \frac{4Mc\Delta T}{3n |v_x| Sk (T_C - T_K)}.$$

⟦folio 29⟧

Assuming that $\sqrt{v_x} \sim \sqrt{RT_K/\mu}$, and taking into account that $n = p/k T_K$ (this follows from the Mendeleev-Clapeyron equation), we finally find:

$$\Delta t \sim \frac{4Mc\Delta T \sqrt{\mu T_K}}{3p(T_c - T_k)S\sqrt{R}}.$$

Substituting numerical values ​​($M = 1$ kg, $\Delta T = 20$ K, $T_K = 293$ K, $p = 1$ Pa, $\mu = 29.10^{-3}$ kg/mol, etc.), we obtain $\Delta t \sim 3.10^4$ with $\sim 10$ h.

A. Stasenko

F530. In the diagram shown at figure 10, $\%_0 > \%_1$. Determine the charge that the battery will read and the resistance of the pebble is zero. The diode is ideal (its forward resistance is zero, its reverse resistance is infinity); The capacitor was not charged before the switch was closed.

Fig. 10.

We will assume that the diode begins to conduct current when the potential at the anode is greater than that at the cathode. In this case, the resistance of the diode will be zero and the voltage drop across it will also be zero.

Let us consider the process that occurs in the circuit after closing the key $K$, in stages.

1. The current flowing through the inductance $L$ charges the capacitor. At a certain value of current $I_1$ the capacitor is charged to voltage $\%_1$. Charge of the capacitor $q_1 = C\%_1$, energy of the capacitor $W_1 = C\%_1^2/2$, energy of the magnetic field of the inductance $LI_1^2/2$. The work done by the battery by this time is $A = q_1\%_1$.

2. Although the voltage on the battery $\%_1$ and on the capacitor are the same, the capacitor continues to charge - due to the energy of the magnetic field of the inductance. At a certain value of current $I_0$ the capacitor is charged to voltage $\%_0$. Charge of the capacitor $q_0 = C\%_0$, energy of the capacitor $W_0 = C\%_0^2/2$, energy of the magnetic field of the inductance $LI_0^2/2$.

The work done by battery $\%_1$ during stages 1 and 2 is $A_1 = q_0\%_1 = C\%_0\%_1$.

3. From the moment the voltage across the capacitor becomes $\%_0$, current begins to flow through the diode into the battery $\%_0$. The voltage on the capacitor does not change from this moment, its energy remains equal to $W_0 = C\%_0^2/2$.

Consequently, the energy $LI_0^2/2$, which has inductance in the magnetic field, begins to decrease - it goes to do the work of moving the charge to the battery $\%_0$.

4. The energy of the magnetic field of inductance is equal to zero. The energy of the capacitor is still $W_0 = C\%_0^2/2$. Some charge $Q$ passed through battery $\%_0$. Battery energy $\%_0$ increased by $\Delta W = Q\%_0$.

During stages 3 and 4, battery $\%_1$ performed work $A_2 = Q\%_1$.

So, during the entire process the battery $\%_1$ has done the following work:

$$A_{\%_1} = A_1 + A_2 = C\%_0\%_1 + Q\%_1.$$

This work went into communicating the energy of $W_0 = C\%_0^2/2$ to capacitor $C$ and increasing the energy of battery $\%_0$ by $\Delta W = Q\%_0$. According to the law of conservation of energy

$$A_{\%_1} = W_0 + \Delta W,$$

*) Since $\sqrt{v_x^2} = \frac{1}{3} \sqrt{v^2} = \frac{1}{3} \frac{3RT_K}{\mu}$, then $\sqrt{v_x^2} = \sqrt{\frac{RT_K}{\mu}}$.

Although $\sqrt{v_x^2} \neq |v_x|$, however $\sqrt{v_x^2} \sim \sqrt{v_x^2}$. Therefore, we will assume that $\sqrt{v_x^2} \sim \sqrt{\frac{RT_K}{\mu}}$.

⟦folio 30⟧

$$C_0^2 E_1 + Q E_1 = \frac{C_0^2}{2} + Q E_0.$$

From here is $Q$ flowing through battery $E_0$:

$$Q = \frac{C_0^2 (2 E_1 - E_0)}{2 (E_0 - E_1)}.$$

And not. From the obtained result it is clear that charge will flow through the battery $E_0$ only if $E_1 < E_0 < 2 E_1$. If $E_0 > 2 E_1$, then the capacitor will not charge in any way to voltage $E_0$. In other words, the maximum voltage to which the capacitor can be charged in the circuit shown in figure 11 is $2 E_0$.

Let at some current $I$ the voltage on the capacitor be $U$, its charge $q = CU$. From the law of conservation of energy $q E = CU E$ = $\frac{LI^2}{2} + \frac{CU^2}{2}$ is found

$$\frac{LI^2}{2} = \frac{CU}{2} (2 E - U).$$

The capacitor charging process will stop when the current in the circuit becomes zero. In this case, as can be seen, $U = U_{\max} = 2 E$.

V. Skorovarov

F531. Geysers can be thought of as large underground reservoirs filled with groundwater and heated by the earth's surface (Fig. 12). The exit from them to the surface of the earth is through a narrow channel, which during the “quiet” period is almost completely filled with water. Considering that the “active” period begins when we fill the underground reservoir with water, and that during an eruption the channel is filled with milky steam that is thrown out, we can estimate what part of the water the reservoir heats up during a single-zone eruption. Channel depth $h = 90$ m; water temperature $\lambda = 2,26 \cdot 10^6$ J/kg; water temperature $c = 4,2 \cdot 10^3$ J/(kg K). The dependence of saturated water pressure on temperature is shown in figure 13.

Fig. 12.

Fig. 13.

⟦folio 31⟧

(M is the mass of the appeared steam) we find

$$\frac{\Delta M}{M} \approx \frac{c(t-t_0)}{\lambda} \approx 0,15.$$

The above solution is an estimate, since it does not take into account a number of factors that in practice can slightly change the result obtained. For example, the solution does not take into account the supply of the body to water from heated layers during the “active” period, as well as the entry of new portions of water into the reservoir through underground channels during the eruption.

S. Kozel

F532. The softener is a light rod of length l with a load of mass M at the end. Attached to the other end of the rod is a light cylindrical bushing a with an internal radius r, which is pushed onto the horizontal axis b (Fig. 14). The coefficient of friction between the bushing and the axle is μ. Determine the angle of deviation of the rod from the vertical in the equilibrium position.

Fig. 14.

Fig. 15.

Obviously, when the axis b rotates counterclockwise, the load M is displaced to the right of the vertical O'O passing through the center of the axis. In this case, point A (Fig. 15), at which the magnetic sleeve is in contact with the axis, is shifted from the top point of the axis in the direction opposite to the direction of rotation of the axis. Let's show it.

When a magnet is in equilibrium, the sum of the moments of all forces acting on it is zero. The magnetic force is acted upon by the gravitational force $\vec{P} = \vec{Mg}$ applied to the load M, the normal reaction force of the N axis and the sliding friction force $\vec{F}_{TP}$ applied to the bushing A. The moments of the forces $\vec{N}$ and $\vec{F}_{TP}$ relative to point A are equal to zero. Consequently, the moment of force $\vec{P}$ relative to this point must be equal to zero. This means that point A must lie on the line of action of the force $\vec{P}$, that is, it must be shifted to the right from the top point of the axis.

Note that even with a large angle of friction coefficient μ, the load M in equilibrium cannot be deviated from the vertical O'O by a distance greater than the radius r of the sleeve a. This can be seen from figure 15.

Let us find the angle α that determines the position of point A. Since, when the magnet is in equilibrium, the vector sum of forces $\vec{F}_{TP}$ and $\vec{N}$ is directed vertically upward (the sum of forces $\vec{F}_{TP}$, $\vec{N}$ and $\vec{P}$ must be equal to zero), then

$$\mathrm{tg} \alpha = \frac{F_{TP}}{N} = \frac{\mu N}{N} = \mu$$

($F_{TP}$, N are the moduli of $\vec{F}_{TP}$ and $\vec{N}$).

Let us now find the angle φ that the magnet rod makes with the vertical O'O in the equilibrium position. As can be seen from figure 15,

$$\sin \varphi = \frac{|OB|}{r+l} = \frac{r \sin \alpha}{r+l}.$$

Considering that

$$\sin \alpha = \frac{\text{tg} \alpha}{\sqrt{1 + \text{tg}^2 \alpha}} = \frac{\mu}{\sqrt{1 + \mu^2}},$$

we find (see (1))

$$\sin \varphi = \frac{r}{r+l} \frac{\mu}{\sqrt{1 + \mu^2}}.$$

Please note that the magnitude of the magnetic deflection angle is determined only by the value of the friction coefficient and the size of the rod and bushing and does not depend on the mass of the load M and the rotation speed of the axis.

In the limiting case μ = 0, formula (2) gives φ = 0, that is, in the absence of a tray, the magnet occupies a vertical position in equilibrium. With the increase in the strength of the trey, that is

⟦folio 32⟧

as $\mu \rightarrow \infty$, the set $\mu/\sqrt{1+\mu^2}$ tends to one and sin $\varphi \rightarrow r/(r+l)$. This means that the magnitude of the deviation of the load $M$ to the right from the vertical $O'O$ (that is, the length of the segment $OB$ by figure 15) tends to $r$ (see (1)).

It is remarkable that such a matrix, if brought out of balance, will perform an insignificant amount. When the axis rotates quickly enough, the sliding friction force acting on the bushing in any direction of motion of the matrix is ​​directed towards the rotation of the axis and only leads to a displacement of the average position by an angle $\varphi$ from the vertical.

Note that there is one more equilibrium position of the matrix on the rotating axis - a position in which the load $M$ is located above the axis, and the rod is deflected from the vertical to the right by the same angle $\varphi$. But this equilibrium position, as is easy to see, is unstable.

If the axis on which the matrix bushing is mounted is fixed motionless (does not rotate), then, thanks to the force of static friction, the value of which can take any value from zero to $\mu N$, the matrix can be in equilibrium in any position deviated from the vertical within the sector with an angle $\varphi$, determined by the same formula (2). This is the so-called stagnation area (Fig. 16). If you deflect the matrix by an angle greater than the limiting one (greater than $\varphi$) and release it, then, having performed a somewhat oscillating subdivide with amplitude, the matrix will remain somewhere inside the stagnation area. Matrix stopping can occur at any point in the stagnation region, depending on the initial conditions. It is interesting to note that the same sector of equilibrium positions also exists for an “inverted” matrix on a fixed axis.

E. Butnikov, A. Bykov, A. Kondratov.

(For the beginning, see p. 20)

S. Guzov (Lviv) 26; V. Jaloyan (Urtsadzor village, Armenian SSR) 16, 19a), 21, 24; O. Dimitriev (Saratov) 16a), 21, 23a), 26, 28, 30a); V. Dobrov (Angarsk) 28, 30a); S. Dovbysh (Moscow) 16, 18, 19, 21; E. Dyuzhikova (Arkhangelsk) 16a); I. Elishevich (Chernigov) 21; A. Ermodin (Petrozavodsk) 21, 22, 26, 28, 29; I. Zverovich (Minsk) 16a); E. Zimanov (Alma-Ata) 21, 22, 25; T. Zozrabyan (village Delaris, Armenian SSR) 26; M. Ibraemov (Shusha) 16a), 27; P. Ivanov (Villyuysk) 26; O. Izhboldin (Leningrad) 16a), 6), 21-24, 26-30; R. Izmailov (Baku) 16, 18, 19, 21-29; F. Kabdykairov (Alma-Ata) 18, 19a), 21, 26, 28; S. Kaazan (Leningrad) 16, 21; A. Kaazarman (Beloretsk) 26; S. Kalashnikov (Ryazan) 16a), 6); A. Kanel (Moscow) 21, 23, 24, 26, 28, 30a); V. Kanterman (Vilnius) 16a); A. Kaplan (Sumgant) 16, 18, 19a), 21, 22, 24, 26-28, 30a); G. Karadulin (Yerevan) 16, 18, 19a), 21, 22, 24-28, 29a); A. Kelarev (Sverdlovsk) 16, 19, 21, 23, 26-29, 30a); I. Kechov (Sukhumin) 16a); S. Kodan (Leningrad) 28; G. Kokov (Tbilisi) 26; A. Koldatsov (Tbilisi) 26, 28; S. Koleva (NRB) 18; A. Kolmytsev (Angarsk) 30a); Yu. Kordyukov (Moscow) 26, 27, 30a); A. King (Tashkent) 166), 22, 23; S. Kochemov (p/o Druzhba, Krasnodar Territory) 21, 24; O. Kravets (Voronezh) 16a), 26-28, 30a); V. Krikukhin (Makhachkala) 26; S. Krilov (Veliky Ustog) 28; I. Krikov (Ivan-

(Continued on page 43)
