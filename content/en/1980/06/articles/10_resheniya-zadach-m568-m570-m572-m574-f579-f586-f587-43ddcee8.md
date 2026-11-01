---
id: 1980-6-resheniya-zadach-m568-m570-m572-m574-f579-f586-f587-43ddcee8
issue: kvant_1980_6
year: 1980
number: "6"
title: Solutions to problems M568, M570—M572, M574; F579, F586, F587
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 22
page_last: 29
page_labels: 20, 21, 23, 24, 26, 27
tag: U3O8
lang: en
source: kvant_digital
extraction: vision
content_sha256: a54ccf4e3262cc9c2f9a55953a8e0fb384881ac5f98485231eabd8bd88ca2d0c
prompt_sha256: draft-1
translated_from: content/ru/1980/06/articles/10_resheniya-zadach-m568-m570-m572-m574-f579-f586-f587-43ddcee8.md
source_content_sha256: 006203e37c185d5512be2c0eacc91e74d96855799cb787afd25007180c42cfb7
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 20⟧

M568. Design of convex quadrilateral ABCD intersect at point O. Prove that
a) if the radius of the circle inscribed in triangles AOB, BOC, COD and DOA are equal to each other, then ABCD is a rhombus;
b) if the radius of the circle inscribed in triangles ABC, BCD, CDA and DAB are equal to each other, then ABCD is a rectangle.

Fig. 1.

Fig. 2.

Fig. 3.

Let $r$ be the radius, $O_1$ and $O_2$ the centers of the circles inscribed in triangles AOB and COD; $P, Q, R, S$ are the points of tangency of these circles from the sides AO, BO, CO, DO of these triangles (Fig. 1).

Let us first prove that the quadrilateral ABCD is a parallelogram. To do this, it is enough to establish that its diagonals AC and BD are bisected by point O.

Let's assume that this is not the case. Let, for example, $|AO| > |OC|$. We will prove that this inequality implies the inequalities $|BO| < |OD|$ and $|BO| > |OD|$, which is impossible.

From the inequality $|AO| > |OC|$ it follows that $|AP| > |CR|$, since $|OP| = |OR|$; from $|O_1P| = |O_2R|$ follows $O_1AP < O_2CR$, and therefore $BAO < DCO$. Therefore, $ABO > CDO$ and $BQ < DS|$, but that means $|BO| < |OD|$.

Repeating the above reasoning for triangles BOC and AOD (Fig. 2; do it yourself), we obtain that $DAO < BCO$, hence $ODA > CBO$, and, therefore, $|DS_1| < |BQ_1|$, that is, $|BO| > |OD|$.

The resulting contradiction proves that $|AO| = |OC|$. It is also proved that $|BO| = |OD|$. So quadrilateral ABCD is a parallelogram.

From the equality of the areas of triangles AOB and BOC (we use the well-known formula $S = pr$) we obtain

$$\frac{1}{2}r(|AO| + |OB| + |AB|) = \frac{1}{2}r(|OC| + |OB| + |BC|),$$

whence $|BC| = |AB|$, that is, the quadrilateral ABCD is a rhombus.

6) First decision. Let (Fig. 3) $A_1$ and $A_2$, $B_1$ and $B_2$, $C_1$ and $C_2$, $D_1$ and $D_2$ be the tangent points of the circles inscribed in the triangles ABD, ABC, BCD, CDA, from the side of the quadrilateral ABCD; $O_1, O_2, O_3, O_4$ are the centers of these circles; $P, Q, R, S$ — points of tangency of the circles from the diagonal AC and BD; $r$ — radius of circles.

First, we will prove an interesting fact in itself: for an arbitrary convex quadrilateral ABCD, the lengths of the segments between the tangent points lying on opposite sides of the quadrilateral are equal, that is, $|A_1B_2| = |C_1D_2|$ and $|B_1C_2| = |A_2D_1|$.

Let us first make sure that figure 3 is “correct”, that is, that the location of the tangent points on the sides of the quadrilateral is exactly the same as shown in figure 3.

Consider, for example, the triangles ABD and ACD and prove that the point $A_2$ lies closer to the point $A$ than the point $D_1$.

To do this, it is enough to prove that $|AA_2| + |DD_1| < |AD|$.

It's easy to see that

$$|AA_2| = \frac{|AB| + |AD| - |BD|}{2}$$

$$|DD_1| = \frac{|AD| + |CD| - |AC|}{2}$$

Adding these equalities, we get

$$|AA_2| + |DD_1| = |AD| + \frac{|AB| + |CD| - |BD| - |AC|}{2}$$

But $|AB| + |CD| < |BD| + |AC|$ (prove it!) and therefore

$$|AA_2| + |DD_1| < |AD|$$

Now we prove that $|A_2D_1| = |B_1C_2|$ and $|D_2C_1| = |A_1B_2|$.

⟦folio 21⟧

Using the property of tangent segments (Fig. 3), we obtain

$$|BD| = |BP| + |PD| = |BA_1| + |DA_2| =
= |BB_2| + |A_1B_2| + |DD_1| + |A_2D_1|.$$ (1)

On the other side,

$$|BD| = |BR| + |RD| = |BB_1| + |B_1C_2| + |DD_2| + |D_2C_1| =
= |BB_2| + |B_1C_2| + |DD_1| + |D_2C_1|.$$ (2)

Equating expressions (1) and (2), we obtain

$$|A_1B_2| + |A_2D_1| = |B_1C_2| + |D_2C_1|.$$ (3)

Carrying out exact calculations for the diagonal AC, we obtain

$$|A_2D_1| + |D_2C_1| = |A_1B_2| + |B_1C_2|.$$ (4)

Now adding equalities (3) and (4), we get

$$|A_2D_1| = |B_1C_2|.$$

Therefore, also $|D_2C_1| = |A_1B_2|$.

Until now we have not used the equality of the radii of inscribed circles, so the result we obtained is valid for an arbitrary convex quadrilateral.

Now let's finish solving the problem.

Since the centers of the circles are equally distant from the corresponding sides, we obtain $(O_1O_2) \parallel (AB)$ and $(O_3O_4) \parallel (CD)$; and since $|O_1O_2| = |A_1B_2|$ and $|O_3O_4| = |C_1D_2|$, we get $|O_1O_2| = |O_3O_4|$.

Similarly, $|O_2O_3| = |O_1O_4|$ and, therefore, the quadrilateral $O_1O_2O_3O_4$ is a parallelogram, and since the sides of the quadrilateral ABCD are parallel to the parallelogram, the quadrilateral ABCD is also a parallelogram.

Equating the expressions for the areas of triangles ABD and ABC, we obtain

$$\frac{1}{2} r (|AB| + |BD| + |AD|) = \frac{1}{2} r (|CD| + |AD| + |AC|),$$

whence $|BD| = |AC|$.

Thus, the diagonals of parallelogram ABCD are equal in length, which means that ABCD is a rectangle.

Second solution. As in the first solution, we will first prove that the quadrilateral ABCD is a parallelogram.

To do this, draw straight lines through points B and D, parallel to side AC (Fig. 4), and put on them, on one side of line BD, segments BB' and DD' of length $|AC|$.

The quadrilateral BB'DD' is obviously a parallelogram. It is easy to see that triangles BCB', B'CD', CD'D are congruent to triangle ABC, ABD and ACD, respectively, so the radii of the circles inscribed in all quadrilaterals into which the parallelogram is divided by segments CB, CB', CD and CD' are equal.

Let us prove that point C coincides with point E of the intersection of the diagonal of the parallelogram BB'D'D'.

In fact, if this is not the case, then point C belongs to one of the triangles into which the parallelogram is divided by its diagonals (at figure 4 this is triangle DED'). In this case, the radius of the circle inscribed in triangle DED' will be greater than r, and the radius of the circle inscribed in triangle BEB' will be less than r, which contradicts the congruence of triangles DED' and BEB'.

Thus, point C coincides with the intersection point E of the diagonal of the parallelogram BB'D'D' and therefore $[DC] \parallel [AB]$ and $[AD] \parallel [BC]$, that is, the quadrilateral ABCD is a parallelogram.

To complete this solution, it is sufficient to check the reasoning already carried out at the end of the first solution.

A. Egorov

⟦folio 23⟧

M571. The decreasing sequence $(x_n)$ of positive numbers is such that for any natural number $n$
$$\frac{x_1}{1} + \frac{x_2}{2} + \frac{x_3}{3} + \dots + \frac{x_n}{n} < 3.$$

We will prove a stronger statement: for our sequence for any natural number $n$
$$\frac{x_1}{1} + \frac{x_2}{2} + \frac{x_3}{3} + \dots + \frac{x_n}{n} < 2.$$
Indeed, since $x_i > 0$,
$$\sum_{k=1}^{n} \frac{x_k}{k} \leq \sum_{k=1}^{(n+1)^2-1} \frac{x_k}{k} = \sum_{k=1}^{n} \sum_{m=k^2}^{(k+1)^2-1} \frac{x_m}{m}.$$
Since the sequence $(x_n)$ is a killing sequence,
$$\sum_{k=1}^{n} \frac{x_k}{k} \leq \sum_{k=1}^{n} x_k^2 \left( \sum_{m=k^2}^{k^2+k-1} \frac{1}{m} + \sum_{m=k^2+k}^{k^2+2k} \frac{1}{m} \right) \leq$$
$$\leq \sum_{k=1}^{n} x_k^2 \left( \frac{k}{k^2} + \frac{k+1}{k^2+k} \right) = 2 \sum_{k=1}^{n} \frac{x_k^2}{k} \leq 2,$$
which is what was required.

Estimate 2 is already unimprovable: we invite readers to prove on their own that for any $c < 2$ one can find a killing sequence of positive numbers such that for any positive integer $n$
$$\sum_{k=1}^{n} \frac{x_k^2}{k} \leq 1 \text{ и } \sum_{k=1}^{n} \frac{x_k}{k} > c.$$

3. Chanturia

⟦folio 24⟧

M572. The kangaroo jumps along the coordinate plane $x \geq 0$, $y \geq 0$ Oxy in the following way: from point $(x; y)$ the kangaroo can jump to point $(x+1; y-1)$ or to point $(x-5; y+7)$, and jumps. From what initial points $(x; y)$ can a kangaroo not jump to a point located at a distance greater than 1000 from the origin? Draw the set of all such points $(x; y)$ and find its area.

![Graph](image)

M574. A finite sequence $a_1, a_2, \dots, a_n$ of the numbers 0 and 1 must satisfy the following condition: for any integer $k$ from 0 to $n-1$, the sum $a_1 a_{k+1} + a_2 a_{k+2} + \dots + a_n - k a_n$ is an odd number. a) Come up with a sequence for $n=25$. b) Prove that such a sequence exists for some $n>1000$.

Another formulation of problem M574:
Find a sequence $e_1 < e_2 < \dots < e_i$ of natural numbers such that each number from 1 to $e_i - e_1$ can be represented as the difference $e_j - e_i$ of some of these numbers in an odd number of ways.

The answer is the "step triangle" $T$ (see Fig.): it contains two boundary half-closed intervals $[0; A], [0; B]$ (where $A$ and $B$ are the points with coordinates (5; 0) and (0; 5), respectively), but does not contain any other boundary points (the points of the ten segments bounding the "steps"). Its area is obviously 15.

It is enough to prove, firstly, that a kangaroo cannot leave the “triangle” $T$, and, secondly, that from the remaining points of the angle $x \geq 0, y \geq 0$ it can move as far away from the origin as possible. The first is obvious: finding $T$, the kangaroo can only make jumps of type (1; -1), and is therefore inevitable to end up on the $Ox$ axis. To prove the second statement, note that the combination of jumps (1; -1) and one jump (-5; 7) gives “jump” (0; 2); therefore, a kangaroo located in area $M_1 = \{(x; y) | x \geq 0, y \geq 5\}$ will easily run vertically upward, repeating this combination of six jumps many times. If the kangaroo is in area $M_2 = \{(x; y) | x \geq 1, 5 > y \geq 4\}$, then four jumps (1; -1) and one jump (-5; 7) follows, the kangaroo will fall into area $M_1$, from where it can already run away. Similarly, finding four more jumps of the “escape area” $M_3, M_4, M_5, M_6$

$$M_6 = \{(x; y) | x \geq 5 - k, k + 1 > y \geq k\}, k = 3, 2, 1, 0.$$

A. Sosinsky

First decision. It's easy to come up with the following sequence of four numbers: $A_1 = 1101$. To construct the desired sequence of twenty-five numbers, we use $A_1$ three times, and separate $A_1$ with zeros like this:
$$A_2 = 1101 000 1101 00000000 1101.$$

This construction can be continued further: if the sequence $A = (a_1, a_2, \dots, a_n)$ satisfies the conditions, then the sequence

$$B = \begin{bmatrix} A & 00...0 & A & 00...0 & A \\ n & n-1 & n & 3n-2 & n \end{bmatrix},$$

consisting of three sets of $A$ and two sets of zeros also satisfies it.

Let us prove a more general fact: together with the sequences $A = (a_1, a_2, \dots, a_n)$ and $C = (c_1, c_2, \dots, c_m)$, the sequence $B$ of length $(2n-1)(m-1)+n$ from $m$ “blocks” satisfies the conditions for specifying:

$$B = \begin{bmatrix} a_1 c_1, & a_2 c_1, & \dots, & a_n c_1, & 0, 0, \dots, 0, \\ a_1 c_2, & a_2 c_2, & \dots, & a_n c_2, & 0, 0, \dots, 0, \\ \dots & \dots & \dots & \dots & \dots \\ a_1 c_m-1, & a_2 c_m-1, & \dots, & a_n c_m-1, & 0, 0, \dots, 0, \\ a_1 c_m, & a_2 c_m, & \dots, & a_n c_m \end{bmatrix};$$

here the $j$th block repeats the sequence $A$ if $c_j = 1$, and zero if $c_j = 0$.

Let $k = (2n-1) q+r$ be an integer, where $q=0; r=0, 1, \dots, n-1$ or $-n < r < n, 0 < q < m$ (q and r are integers). Then, when the sequence $B$ is shifted into $k$ places, the $j$th block $(a_1 c_j, a_2 c_j, \dots, a_n c_j)$ will intersect only with the $(j+q)-m$ block of the original sequence, and with a displacement of $r$ units in the index

⟦folio 26⟧

M574 will be obtained if a sequence of 0 and 1 is located on a circle and require that for any k the sum of pairwise products of targets spaced at k is odd. If you manage to get a result on this task, write to us about it.

F579. In the circuit shown at figure, $R_1 = 10$ Ohm, $R_2 = 20$ Ohm, $R_3 = 15$ Ohm, for example in an alternating current network $U = 10$ V. Determine the power that is allocated to resistors with resistance $R_2$ and $R_3$.

![Circuit diagram](image)

When using the alternating current diode $T$, the diode is closed, and alternating current $I = \frac{U}{R_1 + R_2}$ flows through resistor $R_2$. During time $T/2$ energy is released on resistor $R_2$

$$W' = I^2 R_2 \frac{T}{2} = \frac{U^2 R_2 T}{2(R_1 + R_2)^2}.$$

The second useful period diode is open. The total resistance of resistors $R_2$ and $R_3$ connected in parallel is $R_0 = \frac{R_2 R_3}{R_2 + R_3}$. For example, these resistors are equal to $U_0 = \frac{U}{R_1 + R_0} R_0$.

During this useful period, the corresponding energy is allocated to resistors $R_2$ and $R_3$

$$W'' = U_0^2 R_2 \frac{T}{2} = \frac{U^2 R_0 T}{2(R_1 + R_0)^2},$$

$$W_3 = U_0^2 R_3 \frac{T}{2} = \frac{U^2 R_0 T}{2(R_1 + R_0)^2}.$$

The average powers allocated to resistors $R_2$ and $R_3$ for a full period are equal to the corresponding

$$N_2 = \frac{W' + W''}{T} = \frac{U^2 R_2}{2(R_1 + R_2)^2} + \frac{U^2 R_0}{2R_2(R_1 + R_0)^2},$$

$$N_3 = \frac{W_3}{T} = \frac{U^2 R_0}{2R_3(R_1 + R_0)^2}.$$

Substituting the numerical values ​​of the quantity $U, R_1, R_2, R_3$, we find

$$N_2 \approx 1,6 \text{ Вт}, \quad N_3 \approx 0,7 \text{ Вт}.$$

G. Kotkin

F586. The telloisulated vessel is opened to a high vacuum. The monatomic ideal gas surrounding the vessel has a temperature of $T_0$. At some point the tap is opened and the vessel is filled with gas. What temperature $T$ will the gas have in the vessel immediately after filling?

To understand how the temperature changes when a vessel is filled with gas, it is necessary to consider the origin of energy transformations. When the tap is opened, some portion of gas is pushed into the vessel in response to the pressure of the surrounding gas. Thanks to the work of these forces, the gas released into the vessel acquires the kinetic energy of directed maximum motion - it enters the vessel as a stream. When it meets the walls of the vessel and the jet of gas that has already entered the vessel, the directional one weakens and eventually dissipates. In this case, the kinetic energy of the ordered movement of the gas in the chip is converted into internal energy, that is, the energy of the chaotic thermal movement of its molecules.

All this happens so quickly that the heat exchange of the gas entering the vessel with the surrounding gas and walls can be neglected. Therefore, for the entire process under consideration

⟦folio 27⟧

The first law of thermodynamics has the form: the work $A$ of the pressure forces of the surrounding vessel on the gas entering the vessel is equal to the change in the internal energy $\Delta U$ of the gas entering:
$$A = \Delta U.$$

When filling a small evacuated vessel, the pressure and temperature in the surrounding gas atmosphere remain unchanged. Therefore, to find the work $A$ imagines that our evacuated vessel is inside a large cylinder with a movable piston (see Fig.). The cylinder is filled with gas whose temperature is $T_0$; gas pressure in the cylinder $p_0$. The process of filling the vessel corresponds to the movement of the piston to the right at constant pressure $p_0$. The layer acting on the left on the piston does the work $p_0V_0$, where $V_0$ is the volume “displaced” when the piston moves. This work will be equal to the intersence of the work of external forces on the gas poured into the vessel, since the internal energy of the gas that does not enter the vessel remains unchanged. Let us pay attention to the fact that the volume $V_0$ does not coincide with the internal volume of the filled vessel, since the temperature $T$ of the gas into the vessel differs from $T_0$.

Using the equation of state of an ideal gas, work $A$ can be expressed in terms of temperature $T_0$ and the amount of gas $v$ entering the vessel:

$$A = p_0V_0 = vRT_0.$$

The change in internal energy $\Delta U$ of the gas entering the vessel is equal to

$$\Delta U = v \times \frac{3}{2}R(T - T_0).$$

Substituting expressions (2) and (3) into the equation of the first law of thermodynamics (1), we obtain

$$T = \frac{5}{3}T_0.$$

Thus, the temperature of the gas filling the evacuated vessel is higher than the temperature of the gas surrounding the vessel. Note that the result obtained does not depend on either the volume of the vessel or the pressure $p_0$. The temperature of the gas in the vessel also does not depend on whether the vessel is filled to the end until the pressure in it is equal to the gas pressure in the environment, or the valve is shut off equally.

E. Butikov, A. Bykov, A. Kondratev

F587. A conductor of mass $M$ and length $l$ is suspended from the dielectric at its ends using two identical conducting permanent springs with a common stiffness coefficient $k$. A capacitor $C$ is connected to the upper ends of the springs. The entire structure rises in a uniform magnetic field with induction $B$, perendicular to the plane of the structure.

The conductor is displaced in the vertical plane from the equilibrium position and released. Determine the further movement of the conductor in the vertical plane. The resistance, self-inductance and capacitance of the conductors are pretentious.

Let's direct the coordinate axis $X$ vertically down; We will take the equilibrium position of the rod as the origin of coordinates (see Fig.ok).

Let $x_0$ be the extension of each spring in this position. According to Newton's P law

$$Mg - kx_0 = 0.$$

When the rod is moved from its equilibrium position, the force remains unchanged, but the elastic force changes. Consequently, after the rod is released, it begins to move with acceleration towards the equilibrium position. Since this movement occurs in a magnetic field, an induced emf $\mathcal{E} = Bvl$ arises in the rod, where $v = \dot{x}$ the speed of the rod varies with Q, time. Current appears in the circuit and the capacitor charges. Since the resistance of the conducting springs is zero, the direction towards the capacitor is $\mathcal{E}$ and the charge $q$ of the capacitor is $\mathcal{C}\mathcal{E} = CBvl$. Therefore, the current in the circuit at any time is equal to

$$i = \dot{q} = C\dot{\mathcal{E}} = CB\dot{v}l = CB\ddot{x}l.$$

A rod carrying a current in a magnetic field is acted upon by a force $F$
