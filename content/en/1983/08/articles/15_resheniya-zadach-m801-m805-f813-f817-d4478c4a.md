---
id: 1983-8-resheniya-zadach-m801-m805-f813-f817-d4478c4a
issue: kvant_1983_8
year: 1983
number: "8"
title: Solutions to problems M801—M805; F813—F817
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 52
page_last: 57
page_labels: 50-55
tag: AJ22
lang: en
source: kvant_digital
extraction: vision
content_sha256: 627c9163da6f2735049106e8403a9f61bbc78fb5324aa7c225ce32d0d5997967
prompt_sha256: draft-1
translated_from: content/ru/1983/08/articles/15_resheniya-zadach-m801-m805-f813-f817-d4478c4a.md
source_content_sha256: 91383e6c037e7d5f10c8575cddd15a527c54b68d1237384629694c98b1fa51eb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

P832*. A square undeformable superconducting frame of side $a$ is placed horizontally in a non-uniform magnetic field whose induction in space is given by
$$B_x = -kx, B_y = 0, B_z = kz + B_0.$$
The mass of the frame is $m$, its inductivity is $L$. At the initial moment the centre of the frame is at the origin with sides parallel to the $X$ and $Y$ axes. How will the frame move after it is released and where will it be after time $t$?
O. Yu. Nikishina

Problem solutions

M801—M805; F813—F817

Note that the integral part of the number $a \geqslant 1$ is equal to the number of natural numbers less than or equal to $a$. Specifically, $[\sqrt{n}] + [\sqrt[3]{n}] + \dots + [\sqrt[n]{n}] = [\log_2 n] + [\log_3 n] + \dots + [\log_n n]$ ($[x]$ means the integer part of the number $x$).

The right side is treated similarly: $[\log_m n] - 1$ is the number of natural $x \geqslant 2$ such that $x \leqslant \log_m n$, that is, $m^x \leqslant n$. That's why
$$([\log_2 n] - 1) + ([\log_3 n] - 1) + \dots + ([\log_n n] - 1) = N$$
(for $m > n$, $y \geqslant 2$ the inequality $m^y \leqslant n$ obviously does not hold).

So, both sides of our equality are equal to $N + n - 1$.
V. V. Kasil

M802. On the sides AB and BC of triangle ABC, as on the central sides, right-angled triangles APB and BQC with identical vertex angles $B$ are constructed outside it. Find the smiles of triangle PQK, where $K$ is the midpoint of side AC.

Answer: $\hat{P} = \hat{Q} = \beta, \hat{K} = 180^\circ - 2\beta$.

This problem belongs to a fairly large group of problems that consider triangles (or other polygons) of a given shape, built on the sides of another triangle (or polygon); Probably the most famous of them is the so-called “Napoleon problem” - to prove that the centers of right triangles constructed on the sides of an arbitrary triangle outside it themselves form a right triangle. Typically, these problems can be solved using plane transformation composition.

Consider two subdivision transformations (Fig. 1):
$$F_p = H_p^k \circ R_p^{90},$$ where $k = |PB|:|PA|$, is the composition of the rotation of $R_p^{90}$ around $P$ by $90^\circ$ and is prepared with the center $P$ and the coefficient $k$, and $F_q = H_q^k \circ R_q^{90}$ (such transformations are called rotation geometries or spiral subdivisions). Their composition $F = F_q \circ F_p$ leaves the point $K$ in place (this explains the choice of just such transformations; we will give the proof a little later). Let $F_p(K) = K_1$ (Fig. 2), then $F_q(K_1) = K$. Triangles $KPK_1, KQK_1$ and APB are matched to each other as right triangles with the same ratio of legs ($|KP|:|PK_1| = |KQ|:|QK_1| = k = |PA|:|PB|$). And since $KK_1$ is the common hypotenuse of triangles $KPK_1$ and $KQK_1$, they are congruent, so $|KP| = |KQ|$. Therefore, $\hat{PKQ} = 360^\circ - 2\cdot 90^\circ - 2\beta$, $\hat{KPQ} = \hat{KQP} = (180^\circ - (180^\circ - 2\beta))/2 = \beta$.

It remains to prove that $K$ is a fixed point of the transformation of the subdivision $F$. Note the following properties of $F$:

⟦folio 51⟧

1) $F$ — displacement (because the similarity coefficient $F$ is equal to $k \cdot \frac{1}{k} = 1$);

2) When moving $F$, any ray turns into the opposite direction (with tomathety, the directions of the rays are preserved; when rotated, any ray rotates by an angle equal to the rotation angle, therefore the total rotation angle of any ray during transformation $F$ is equal to $90^\circ + 90^\circ = 180^\circ$);

3) $F(A) = C$ ($F_P(A) = B$ by choice $F_P$, and $F_Q(B) = C$ because $BQC = 90^\circ$ and $|QC|:|QB| = |PA|:|PB| = 1/k$).

This implies that $F$ is the central symmetry of $Z_K$ with center $K$ and, in particular, $F(K) = K$.

Try the same method to solve the “Napoleon problem”.

V. N. Dubrovsky

M803. The sum of two rational numbers $x$ and $y$ is a natural number, the sum of their inverse numbers $1/x$ and $1/y$ is also a natural number. What could $x$ and $y$ be?

Answer: $(x, y) = (1, 1), (1/2, 1/2), (2, 2)$. Let's represent the numbers $x$ and $y$ as irreducible fractions: $x = \frac{a}{b}, y = \frac{c}{d}$. Then $x + y = \frac{ad + bc}{bd}$ is a natural number. Therefore, $ad + bc$ is divisible by $b$, and since $a$ and $b$ are coprime numbers, $d$ is divisible by $b$. On the other hand, $ad + bc$ is divisible by $d$, so $b$ is divisible by $d$. It follows that $b = \pm d$. Likewise, $\frac{1}{x} + \frac{1}{y} = \frac{ad + bc}{ac}$ is a natural number, so $a = \pm c$. Thus, $x = y$ or $x = -y$. The second case is impossible, since by condition $x + y \ge 1$. In the first case, $x + y = 2x = 2a/b$ and $2/x = 2b/a$ are natural numbers. that is, $a$ and $b$ are divisors of two, and $a/b > 0$. Therefore, $a/b = 1/1 = 1$, or $a/b = 1/2$, or $a/b = 2/1 = 2$.

A. P. Savin

M804. Point $O$ is the midpoint of the axis of a right circular cylinder, $A$ and $B$ are diametrically opposite points on the circle of the lower base of the cylinder, $C$ is a certain point on the circle of the upper base that does not lie in the plane $OAB$. Prove that the sum of two angles of a triangular angle $OABC$ (with vertex $O$) is 2π.

Let $D$ be a point on the circle of the upper base of the cylinder, diametrically opposite to point $C$ (Fig. 1). We prove that trihedral angles $OABC, OBCD, OCDA$ and $ODAB$ with a common vertex $O$ are pairwise congruent. Since each three of these angles share a common edge ($OA, OB, OC$ or $OD$) and the sum of their dihedral angles at that edge is, very indo, equal to 2π, the sum of all their 12 dihedral angles is $4 \cdot 2\pi = 8\pi$. Therefore, the sum of the dihedral angles of each of them, in particular the angle $OABC$, is equal to $8\pi/4 = 2\pi$.

To prove the congruence of these trihedral angles, we note that the opposite edges of the triangle $ABCD$ are pairwise equal ($|AB| = |CD|$ as the diameters of congruent circles, and the edges $AC$ and $BD$, as well as $AD$ and $BC$ are mutually symmetrical with respect to the cylinder; (see Fig. 1). A since the point $O$ is equidistant from all the vertices of the triangle, $\triangle OAB \cong \triangle OCD, \triangle OAC \cong \triangle OBD$ and $\triangle OAD \cong \triangle OBC$. Therefore, the trihedral angles under consideration have corresponding equal plane angles, and therefore are congruent. The concircularity of trihedral angles can be proven explicitly by substituting that the lines connecting the midpoints of the edges $AC$ and $BD$, as well as $AD$ and $BC$, like the common dilinda, are the congruence axes of triangle $ABCD$.

The tetrahedron $ABCD$ with congruent faces, which will help us solve the problem, has many remarkable properties. There is a large list of its properties in the article by V. E. Matizen in «Kvant» No. 6 for this year.

I. K. Zhuk

⟦folio 52⟧

M805*. a) On sides BC, CA, AB of triangle ABC, points A₁, B₁, C₁ are chosen, respectively, so that segments AA₁, BB₁ and CC₁ intersect at one point. Prove that S₁A₁B₁C₁ ≤ S₁ABC/4.

6) On the faces BCD, CDA, BDA, ABC of triangle ABC, points A₁, B₁, C₁, D₁ are chosen, respectively, so that the segments AA₁, BB₁, CC₁, DD₁ intersect at one point. Prove that V₁A₁B₁C₁ ≤ V₁ABCD/27.

Fig. 1.

Fig. 2.

Fig. 3.

First of all, we will prove several simple but very useful lemmas about the relationship between the areas of triangles and the volumes of tetrahedra.

(1) If straight line MM₁ intersects straight line KL at point P (Fig. 1), then

$$S_{KLM}: S_{KLM_1} = |MP|: |M_1P|.$$

This follows from the obvious equality hₘ:hₘ₁ = |MP|: |M_1P|, where hₘ and hₘ₁ are the heights of the triangles KLM and KLM₁.

(2) If points L₁ and M₁ lie on lines KL and KM (Fig. 2), then

$$S_{KLM}: S_{KL_1M_1} = \frac{|KL| \cdot |KM|}{|KL_1| \cdot |KM_1|}.$$

Indeed, S_{KLM}: S_{KL_1M_1} = (S_{KLM}: S_{KL_1M}) \cdot (S_{KL_1M}: S_{KL_1M_1}) = (|KL|: |KL_1|) \cdot (|KM|: |KM_1|) due to (1).

(3) If straight line NN₁ intersects the KLM plane at point P, then

$$V_{KLMN}: V_{KLMN_1} = |NP|: |N_1P|.$$

(Proved similarly to (1).)

(4) If points L₁, M₁, N₁ lie on lines KL, KM, KN, then

$$V_{KLMN}: V_{KL_1M_1N_1} = \frac{|KL| \cdot |KM| \cdot |KN|}{|KL_1| \cdot |KM_1| \cdot |KN_1|}$$

(Proved analogously to (2).)

Let's move directly to solving the problem.

a) Let O be the intersection point of the segments AA₁, BB₁ and CC₁; S, Sₐ, Sₑ and Sₒ are the areas of triangles ABC, OBC, OCA and OAB (Fig. 3). Then by (1)

$$\frac{|OA|}{|OA_1|} = \frac{|AA_1| - |OA_1|}{|OA_1|} = \frac{S}{S_A} - 1 = \frac{S - S_A}{S_A}.$$

Similar relationships hold for segments BB₁ and CC₁. Thus,

$$\frac{|OA_1|}{|OA_1|} = \frac{S_A}{S - S_A}, \frac{|OB_1|}{|OB_1|} = \frac{S_B}{S - S_B}, \frac{|OC_1|}{|OC_1|} = \frac{S_C}{S - S_C}.$$

Divide the volume of $\triangle A_1B_1C_1$ into three triangles by segments OA₁, OB₁ and OC₁ and estimate the area of ​​each of them separately.

In effect (2)

$$S_{OA_1B_1} = S_{OAB} \cdot \frac{|OA_1| \cdot |OB_1|}{|OA| \cdot |OB|} = S_C \cdot \frac{S_A S_B}{(S - S_A)(S - S_B)} = \frac{S_A S_B S_C}{(S - S_A)(S - S_B)(S - S_C)}.$$

$$\cdot (S - S_C) = k \cdot (S - S_C).$$

Adding this equality with similar equalities for triangles OB₁C₁ and OC₁A₁, we obtain:

$$S_{A_1B_1C_1} = k((S - S_C) + (S - S_A) + (S - S_B)) = 2kS.$$ (*)

To estimate k, we write “inequalities about means” for Sₐ and Sₑ, Sₑ and Sₒ, Sₒ and Sₐ:

$$\sqrt{S_A S_B} \leq \frac{S_A + S_B}{2}, \sqrt{S_B S_C} \leq \frac{S_B + S_C}{2}, \sqrt{S_C S_A} \leq \frac{S_C + S_A}{2}$$

and their variables:

$$S_A S_B S_C \leq (S_A + S_B)(S_B + S_C)(S_C + S_A)/8 = (S - S_C)(S - S_A)(S - S_B)/8.$$ (*)

Thus k ≤ 1/8 and S₁A₁B₁C₁ ≤ S₁ABC/4.

6) We will give only a general outline of the proof - it repeats the reasoning of point a) almost word for word.

Let O be the intersection point of these segments, V, Vₐ, Vₑ, Vₒ and Vₒ the volumes of triangle ABCD, OBCD, OCDA, ODAB and OABC (Fig. 4). User Lemma (3)

⟦folio 53⟧

F813. Three weightless hinged rods of length a, each hinged at points A and B lying on the same horizontal (see figure); $|AB|=2a$. To the suspension joint C, a mass of mass m. At what minimum force applied to hinge D will the middle rod maintain a horizontal position?

F814. A ball of radius R lies on a smooth horizontal surface of the cart. The cart begins to move with speed $v_0$. Starts a horizontal projection of the ball's speed at the moment it hits the floor.

and (4) (instead of (1) and (2) in part a)), it is easy to show that $V_{A1B1C1D1} = 3kV$,
(cf. (*)), where
$$k = \frac{V_A V_B V_C V_D}{(V - V_A)(V - V_B)(V - V_C)(V - V_D)}.$$

The "inequalities of means" variable for all four rows composed of the numbers $V_A, V_B, V_C$ and $V_D$:
$$\sqrt[3]{V_A V_B V_C} \leq \frac{1}{3} (V_A + V_B + V_C) = \frac{1}{3} \Pi V - V_D), \dots, \text{ получим}$$
(cf. (**)), which is $k \leq 1/81$, and therefore $V_{A1B1C1D1} \leq V_{ABCD}/27$.

R. P. Ushakov

◆
Since joint C is in equilibrium, the sum of the forces acting on it is zero. Therefore (see figure),
$$(m + m_\omega)g \sin \alpha = T_2 \cos \alpha,$$
(1)
where $m_\omega$ is the mass of the hinge. From the equilibrium condition of the hinge D and the horizontal middle rod condition it follows that
$$T_2 \cos \alpha = F \cos \beta + m_\omega g \sin \alpha.$$ (2)
From (1) and (2) we obtain
$$F = \frac{T_2 \cos \alpha - m_\omega g \sin \alpha}{\cos \beta} = \frac{mg \sin \alpha}{\cos \beta} \geq mg \sin \alpha.$$
Thus, the minimum force $\vec{F}_{\min}$ at which the middle rod maintains a horizontal position is equal in abscile value to $mg \sin \alpha = mg/2$ and is directed perpendicular to rod BD.

S. K. Strokov

Let us present another solution to this problem, sent by reader A.P. Zubatkin.

The external forces acting on the system are: the reaction forces applied at points A and B from the side of the “ceiling”, equal to the corresponding $|\vec{T}_1|$ and $|\vec{T}_3|$ and directed along the rods AC and BD; gravity forces $m_\omega g$ applied to the hinges; force $mg$, equal to the weight of the load; force $\vec{F}$ applied to hinge D. Since the system is in equilibrium, the sum of the moments of all forces about any point must be equal to zero. Let us write this condition for point O (see figure):
$$mg a \sin \alpha + m_\omega g a \sin \alpha = Fa \cos \beta + m_\omega g a \sin \alpha.$$
From here
$$F = \frac{mg \sin \alpha}{\cos \beta} \Rightarrow F_{\min} = mg \sin \alpha = mg/2, \vec{F} \perp [BD].$$

◆
Let us consider the motion of a ball in a reference frame moving with speed $\vec{v}_0$. In this system the ball moves with speed $v_0$. From the moment the center of the ball is exactly above the edge of the cart, and until the moment the center of the ball comes off, it moves along a circle of radius R with the center at the point of contact (while the ball does not rotate around its own center). Let us find the angle α (see figure) at the moment of separation. To do this, we will use the law of conservation of energy and Newton's second law.
Let u be the velocity of the center of the ball at the moment of separation. Then
$$\frac{mu^2}{2} = \frac{mv_0^2}{2} + mgR(1 - \cos \alpha) \quad (m - масса шара)$$

⟦folio 54⟧

(law of conservation of energy),
$$\frac{mu^2}{R} = mg \cos \alpha$$

(Newton's second law). From (1) and (2) we find
$$\cos \alpha = \frac{1}{3} \left( \frac{v_0^2}{gR} + 2 \right), u = \sqrt{\frac{1}{3} \left( v_0^2 + 2gR \right)}.$$
Since $\cos \alpha \leq 1$, it is clear that at $v_0^2 \geq gR$ the separation will occur immediately at the moment when the center of the ball is above the extreme point of the cart, and the horizontal projection of the speed of the ball $u_r$ when falling on the floor will be equal to zero. If $v_0^2 < gR$, then
$$u_r = v_0 - u \cos \alpha = v_0 - \frac{1}{3Rg} \sqrt{\frac{1}{3} \left( v_0^2 + 2gR \right)^3}.$$
A. R. Zilberman

F815. The lower end of a capillary of radius $r=0,2$ mm and length $l=8$ cm is immersed in water, the temperature of which is constant and equal to $0^\circ C$. The temperature of the upper end of the capillary is $t_0=100^\circ C$. The temperature dependence of the surface tension coefficient $\sigma(t)$ of water is given in the table. To what height will the water rise in the capillary? The conductivity of the capillary is much greater than the conductivity of the water in it; body exchange with the surrounding influence can be neglected.

◆ Let $x$ be the height of the water column in the capillary. The temperature of the capillary and, therefore, the water at this height is, obviously,
$$t_x = t_0 \frac{x}{l}.$$
Water in the capillary is held by surface tension. If $\sigma(t_x)$ is the surface tension coefficient at temperature $t_x$, then
$$x = \frac{2\sigma(t_x)}{\varrho g r},$$
where $\varrho$ is the density of water. From here is
$$\sigma(t_x) = \frac{\varrho g r x}{2} = \frac{\varrho g r l t_x}{2 t_0}.$$
Temperature $t_x$ at the level of maximum water rise

<table><thead><tr><th>$t,^\circ C$</th><th>$\sigma, \frac{\text{mH}}{M}$</th></tr></thead><tbody><tr><td>0</td><td>76</td></tr><tr><td>20</td><td>73</td></tr><tr><td>50</td><td>67</td></tr><tr><td>90</td><td>60</td></tr></tbody></table>

⟦folio 55⟧

F816. In the circuit shown in figure, the resistances of the resistors are the same and equal to $R = 60$ Ohm, the diodes are ideal. A battery producing a voltage of $U = 12$ V will be connected to points $A$ and $B$ for a time of $t_1 = 1$ s. Then, placing the strip in places, connect the battery to the circuit for a time of $t_2 = 5$ s. Find the amount of heat released in the circuit.

The conditions of the problem do not say which strips connect the battery to points $A$ and $B$ for time $t_1$, so we will consider two possible connection options.

1) First, the “flat” battery is connected to point $A$, and the “minus” battery is connected to point $B$. Since the diodes are ideal, their resistance is zero, and all three resistors are connected in parallel to each other. The total resistance of the circuit is $R_1 = R/3 = 20$ ohms. During time $t_1$ the amount of heat will be released in the circuit

$$Q_1 = \frac{U^2}{R_1} t_1 = 7,2 \text{ Дж.}$$

When the strip was placed in places, there was no flow through the diodes, and all three resistors turned out to be connected in series. The total resistance of the circuit is equal to $R_2 = 3R = 180$ Ohm. During time $t_2$ the amount of heat will be released in the circuit

$$Q_2 = \frac{U^2}{R_2} t_2 = 4 \text{ Дж.}$$

The total amount of emissions in the heat chain is equal to $Q = Q_1 + Q_2 = 11,2 \text{ Дж.}$.

2) If first the “minus” of the battery is connected to point $A$, and the “flat” is connected to point $B$, then

$$Q_1' = \frac{U^2}{3R} t_1 \approx 0,8 \text{ Дж.}$$

$$Q_2' = \frac{3U^2}{R} t_2 \approx 36 \text{ Дж.}$$

$$Q' = Q_1' + Q_2' \approx 36,8 \text{ Дж.}$$

L. II. Bakanina

F817. figure shows the dependence of the refractive index $n$ on the coordinate. A narrow monochromatic beam of light falls on the interface between media $I$ and $II$. At what angles does light enter medium III?

From the law of refraction it follows that along the trajectory of the ray the value $n(x) \cdot \sin \alpha_x$ remains constant (here $\alpha_x$ is the angle of incidence of the ray on the interface, which corresponds to the coordinates $x$). Since the refractive index first decreases in the second medium, the angles of incidence $\alpha_x$ will increase as the trajectory approaches the boundary, which corresponds to coordinates $x_1$. In this case, the tangents to the beam path will approach the vertical. If the angle of incidence in the second medium reaches $90^\circ$, then the beam will not exit this medium. If the angle of incidence is less than $90^\circ$ even at the boundary with coordinate $x_1$, where the value $n(x_1)$ is minimal, the beam will move from medium II to medium III.

Let at some initial angle of incidence $\alpha_0$ ($\alpha_0$ is the angle of incidence on the interface between the media $I$ and $II$) the angle of incidence of the beam on the boundary $x_1$ reaches $90^\circ$. Then

$$n_1 \sin \alpha_0 = n(x_1) \cdot \sin 90^\circ \Rightarrow \sin \alpha_0 = \frac{1,2}{1,4} \approx 0,86, \alpha_0 \approx 60^\circ.$$

Consequently, at angles $\alpha \geq \alpha_0$, a ray of light will not be able to pass into medium III. At angles $0 \leq \alpha < 60^\circ$ a ray of light is transmitted into medium III.

V. V. Mozhaev
