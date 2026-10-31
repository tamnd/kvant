---
id: 1973-2-resheniya-zadach-m146-m150-f164-f169-f862e2a1
issue: kvant_1973_2
year: 1973
number: "2"
title: Solutions to problems M146—M150; F164—F169
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 49
page_last: 65
page_labels: 47, 48, 49, 50, 54, 55, 56, 59, 61, 62, 63
tag: X3IH
lang: en
source: kvant_digital
extraction: vision
content_sha256: bc5c3ac43f0ce4e727e9193ce26d35dabb16ae9dfb0653a1b6021f456b84dc7c
prompt_sha256: draft-1
translated_from: content/ru/1973/02/articles/11_resheniya-zadach-m146-m150-f164-f169-f862e2a1.md
source_content_sha256: 84cf7cfea5fb2f5d133252849d1ba7ddba2ff14476d1c61eb65a79e1d3375fec
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

Problem solutions

M146—M150; F164—F169

M146. a) At the vertices of a regular 7-gon, it is considered through a section of the vertices with tokens of the same color (if the color were drawn, then the polygon would have an even number of sides).

a) It is clear that among seven vertices he will definitely find two neighboring vertices with tokens of the same color (if the colors were drawn, then the polygon would have an even number of sides).

Let us denote these vertices by $A_1$ and $A_2$. We can assume that the sides of the chips are white (Fig. 1). Note that there are three vertices, each of which, together with the vertices $A_1$ and $A_2$, is an equilateral triangle; let's denote them by $A_0$, $A_3$ and $B$. If one of them contains a white chip, then the corresponding triangle - $A_0A_1A_2$, - $A_3A_1A_2$ or $BA_1A_2$ - is the desired one. If all three vertices have black chips, then triangle $A_0A_3B$ is the desired one.

The same reasoning is valid for any regular $n$-gon with odd $n \geq 5$ (the role of $A_0$, $A_3$ is played by the vertices adjacent to $A_1$ and $A_2$, and the role of $B$ is the midpoint of the larger of the arcs $A_1A_2$).

6) For $n = 8$ the statement is false. An example of the arrangement of black and white chips, in which no three chips of the same color are located at the vertices of an equilateral triangle, is shown in Fig. 2, b, c, e); Other examples are possible.

b) Answer: The statement is true for $n = 5$, $n = 7$ and $n \geq 9$.

The example depicted in figure 2 shows that the statement is true for $n = 3, 4, 6, 8$. We proved above that it is true for $n = 5$, $n = 7$ and for large odd $n$. Let us prove that it is true for all $n \geq 9$.

Suppose that for some distance of tokens at the vertices of a regular $n$-gon the statement is false. First of all, it is clear that somewhere there will be two adjacent vertices with chips of the same color - if the color of the chips is black, then the required equilateral triangle will already be found among the heel of successive vertices. We can assume that these are vertices $A_4$ and $A_5$ with large-colored chips (Fig. 3). Then sequential

| We are considering | We draw a conclusion |
| :--- | :--- |
| $A_3A_4A_5$ and $A_4A_5A_6$ | $A_3$ and $A_6$ are black |
| $A_3A_6A_9$ | $A_9$ – white |
| $A_1A_5A_9$ and $A_5A_7A_9$ | $A_1$ and $A_7$ are black |
| $A_1A_2A_3$ and $A_6A_7A_8$ | $A_2$ and $A_8$ - white |
| $A_2A_5A_8$ | contradiction |

It can be shown that a stronger statement is also true: for any partition of the set {1, 2, ..., 9} into two subsets, at least in one of the subsets there will be numbers from which one is equal to the other two. We have proven this

⟦folio 48⟧

Fig. 3.

assertion under the additional assumption that 4 and 5 belong to the same subset. Other cases are similar.

**M147.** Let us prove that if a quadrilateral ABCD, circumscribed in a circle, is such that the tangents to the circle at points A and C intersect on the extension of the diazonal BD, then
a) the tangents at points B and D intersect along the continuation of the diazonal AC;
b) the bissertrices of the interior angles A and C of the quadrilateral intersect on the diazonal BD (and the nodes B and D - on AC).

a) Let A, B and C be three points on the circle, K the intersection point of the tangents drawn at points A and C. Let us find the conditions that determine the position of the point D of the intersection of the straight line BK with the circle (Fig. 4).

$$\triangle ABK \sim \triangle DAK: \text{угол } K \text{ у этих треугольников общий, а } \triangle BAK = \triangle ADK, \text{ поскольку каждый из них изменяется положенной дуги } AB. \text{ Поэтому}$$

$$\frac{AB}{AD} = \frac{BK}{AK} = \frac{AK}{DK}$$

(at the same time we proved the well-known theorem: $AK^2 = BK \cdot KD$).

Likewise $\triangle CBK \sim \triangle DCK$, and therefore

$$\frac{BC}{CD} = \frac{BK}{CK} = \frac{CK}{DK}$$

(at the same time we proved the well-known theorem: $AK^2 = BK \cdot KD$).

The right-hand sides in (1) and (2) are equal because $AK = CK$, hence

$$\frac{AB}{BC} = \frac{AD}{CD}$$

(note that the ratio $AD/CD$ increases monstonically as point D moves along a circular arc from A to C. Indeed, by the sine theorem applied to $\triangle ACD$ (Fig. 5))

$$\frac{AD}{CD} = \frac{\sin C}{\sin A} = \frac{\sin (180^\circ - D - A)}{\sin A} = \sin (180^\circ - D) \cdot \text{ctg } A - \cos (180^\circ - D);$$

here $180^\circ - D$ is a constant value, $\sin (180^\circ - D) > 0$, and $\text{ctg } A$ monotically decreases as $A$ increases from 0 to $180^\circ - D$, that is, when point D moves from C to A. It follows that condition (3) corresponds to one definition of the position of point D (for given A, B and C).

Thus, conditions (3) are not only necessary, but also sufficient for points B, D and the intersection point of the tangents constructed at points A and C to lie on the same straight line.

In the same way, it can be proven that the conditions necessary and sufficient for the tangents drawn at points B and D to intersect on the line AC can be written as follows:

$$\frac{BA}{DA} = \frac{BC}{DC}.$$

But conditions (3) and $(3')$ obviously coincide:

$$AB \cdot CD = BC \cdot AD.$$

This makes the statement of problem a) obvious.

6) Let $L_1$ be the point of intersection of the bissertrix of angle A of triangle BAD with line BD (Fig. 6). Then, as is known,

$$\frac{BL_1}{L_1D} = \frac{AB}{AD}.$$

Similarly, if $L_2$ is the point of intersection of the bissertrix of angle C with BD, then

$$\frac{BL_2}{L_2D} = \frac{BC}{CD}.$$

Pozny from condition (3) it follows that

$$\frac{BL_1}{L_1D} = \frac{BL_2}{L_2D}.$$

But each value $\frac{BL}{DL}$ corresponds to one point L on the segment BD,

⟦folio 49⟧

since when the point $L$ moves from $B$ to $D$ this value increases monotically. Therefore, points $L_1$ and $L_2$ coincide.

**M148. The sequence $x_0, x_1, x_2, \dots$ is defined by the following conditions: $x_0 = 1$, $x_1 = \lambda$, for any $n > 1$**

$$(\alpha + \beta)^n x_n = \alpha^n x_n x_0 + \alpha^{n-1} \beta x_{n-1} x_1 + \alpha^{n-2} \beta^2 x_{n-2} x_2 + \dots + \beta^n x_0 x_n.$$

Here $\lambda, \alpha, \beta$ are given positive numbers. Assigning $x_n$ and finding out at which $n$ the value $x_n$ will be the most.

Let us write down the equalities defining $x_n$ for the first few values ​​of $n > 1$ (using the conditions $x_0 = 1$):

$$[(\alpha + \beta)^2 - \alpha^2 - \beta^2] x_2 = \alpha \beta x_1^2,$$

$$[((\alpha + \beta)^3 - \alpha^3 - \beta^3] x_3 = \alpha^2 \beta x_2 x_1 + \alpha \beta^2 x_1 x_2,$$

$$[((\alpha + \beta)^4 - \alpha^4 - \beta^4] x_4 = \alpha^3 \beta x_3 x_1 + \alpha^2 \beta^2 x_2^2 + \alpha \beta^3 x_1 x_3.$$

From here we find (using the conditions $x_1 = \lambda$):

$$x_2 = \frac{\lambda^2}{2}, \quad x_3 = \frac{\lambda^3}{2 \cdot 3}, \quad x_4 = \frac{\lambda^4}{2 \cdot 3 \cdot 4}.$$

It is natural to assume that

$$x_n = \frac{\lambda^n}{n!},$$

where $n! = 1 \cdot 2 \cdot \dots \cdot n$. Let us prove by induction that this is true for all $n$ (if we assume, as is customary, that $0! = 1! = 1$, then the formula $x_n = \frac{\lambda^n}{n!}$ is true for $n = 0$ and $n = 1$).

We can take it to be known that $x_k = \frac{\lambda^k}{k!}$ for all $k \leq n - 1$. Then from the equalities

$$[((\alpha + \beta)^n - \alpha^n - \beta^n] x_n = \sum_{k=1}^{n-1} \alpha^n - k \beta^k x_{n-k} x_k = \sum_{k=1}^{n-1} \frac{\alpha^n - k \beta^k \lambda^n - k \lambda^k}{(n-k)! k!} = \frac{\lambda^n}{n!} \sum_{k=1}^{n-1} C_n^k \alpha^n - k \beta^k = \frac{(\alpha + \beta)^n - \alpha^n - \beta^n}{n!} \frac{\lambda^n}{n!}$$

it follows that $x_n = \frac{\lambda^n}{n!}$ since $\alpha > 0$ and $\beta > 0$ and the common factor of the left and right sides is positive at $n > 1$.

We use the above formula

$$C_n^k = \frac{n!}{k!(n-k)!}$$

for binomial expansion coefficients

$$(a + b)^n = \sum_{k=0}^{k=n} C_n^k a^{n-k} b^k,$$

which is described in the article by V. N. Vaguten (see pp. 27-34).

Let's find out at what $n$ the value $x_n$ is the most, does not exceed $\lambda$, from here we get the answer to the question of the problem: the value $x_n$ takes the most at $n = [\lambda]$ ($[\lambda]$ is the most integer, does not exceed $\lambda$); if $\lambda$ is an integer, then $x_{[\lambda]-1} = x_{[\lambda]}$ are the two largest numbers of the sequence $x_n$.

At figure 7 a graph of the sequence $n \rightarrow x_n$ for $\lambda = 2,5$ is given for illustration.

**M149. Let $O$ be the power of the intersection of the quadrilateral ABCD by the diagonal lines. Prove that**

a) if the perimeters of triangles ABC, BCD, CDA and DAB are equal, then ABCD is a rectangle;

b) if the perimeters of triangles ABO, BCO, CDO and DAO are equal, then ACBD is a rhombus.

a) Let us denote the sides and diagonals of the quadrilateral as shown in Fig. 8. From the equalities

$$x_1 + x_2 + y_1 = x_3 + x_4 + y_1,$$

$$x_2 + x_3 + y_2 = x_1 + x_4 + y_2,$$

adding them to each other (and subtracting one from the other), we find: $x_2 = x_4, x_1 = x_3$. Therefore, ABCD is a parallelogram.

⟦folio 50⟧

Fig. 8.

From equality
$$x_1 + x_2 + y_1 = x_2 + x_3 + y_2 = x_2 + x_1 + y_2$$
It follows that $y_1 = y_2$, that is, $ABCD$, is rectangular.

6) On each diagonal $AC$, $BD$ we choose the larger of the segments on which it is divided by the point $O$. We can assume, changing the notation if necessary, that $AO \geq OC$, $BO \geq OD$ (Fig. 9). Then the perimeter of triangle $AOB$ is not less than the perimeter of triangle $COD$, and equality is possible only if $AO = OC$ and $BO = OD$. (In order to verify this, it is enough to construct a triangle $A'OB'$, symmetrical to the triangle $AOB$ relative to the point $O$; $A'OB'$ embraces $COD$.) But if $AO = OC$ and $BO = OD$, then from the equality of the perimeters it immediately follows that $AB = BC = CD = DA$, that is $ABCD$ - rhombus.

N. B. Vasiliev

M150. From the numbers 1, 2, ..., $k$ all possible sets $(a_1, a_2, ..., a_n)$ of length $n$ are made (it’s easy to see that there are $k^n$ of them). Choose two wishes $P$ and $Q$ as the maximum (the same set should be included in $P$ and $Q$). It is known that if we take an arbitrary set $(p_1, p_2, ..., p_n)$ from $P$ and an arbitrary set $(q_1, q_2, ..., q_n)$ from $Q$, then they will coincide at least in one place (maybe $p_i = q_i$ for some $i$). Then there are at most $k^{n-1}$ sets in either $P$ or $Q$.

Fig. 10.

Prove this statement
a) for $k = 2$ and any $n$;
b) for $n = 1, 2, 3$ and any $k$;
c) for arbitrary $k \geq 2$ and $n \geq 1$.

Try to find other restrictions on the number of elements in the subsets $P$ and $Q$ related to the maximum conditions.

a) $k = 2$. We call the set $\bar{d}$ opposite to the set $d$ if $\bar{d}$ is obtained from $d$ by replacing all 1s with 2s and 2s with 1s. Let $\bar{M}$ denote the set of all sets opposite the set of $M$. The sets $d$ and $\bar{d}$ do not coincide in any place. Therefore, if $d$ is included in $P$, then $\bar{d}$ cannot be included in $Q$. This means that $\bar{P}$ and $Q$ do not contain identical sets. Therefore, either $\bar{P}$ or $Q$ contains no more than half of all sets. But $P$ and $\bar{P}$ have the same number of sets. This means that either $P$ or $Q$ contains no more than half of all sets, that is, no more than $2^{n-1}$ sets.

Fig. 9.

6) For $n = 1$ the statement is obvious.
For $n = 2$ the problem can be formulated as follows: $k^2$ points are placed on the plane at the nodes of the square lattice $(k-1) \times (k-1)$ (Fig. 10). Some of these points need to be painted red, some - blue so that any of the red and blue points lie either in the same column or in the same line (that is, situation c) is impossible). However, a point can be painted in both colors (case d). Need to

⟦folio 54⟧

Fig. 13.

mitigation of states. Melloisoller cylinder from the environment.

The piston is released, and after equilibrium is established, the volume occupied by the gas will double. How will the temperature of the gas and its pressure change? The heat capacity of the cylinder, piston and spring is pretentioso small.

According to the first law of thermodynamics, the amount of heat Q imparted to the gas is equal to the sum of the change in the internal energy of the gas ΔU and the work A performed by it:

$$Q = \Delta U + A.$$ (1)

But in this case, the vessel is thermostatic and Q = 0. Consequently,

$$\Delta U + A = 0.$$ (2)

That is, the work of the gas is done by reducing its internal energy, so we can immediately say that the temperature of the gas decreases.

Let at first the gas temperature be $T_1$, pressure $P_1$ and volume $V_1$, and after the piston is released and equilibrium is established, the gas parameters become corresponding $T_2$, $P_2$ and $V_2$, and $V_2 = 2V_1$ (by condition).

The change in internal energy of an ideal gas is proportional to the change in gas temperature and is equal to

$$\Delta U = c_v (T_2 - T_1),$$ (3)

where $c_v$ is the temperature of 1 mole of gas at constant volume.

Further, the work done by the gas is equal to the change in the potential energy of the deformation spring:

$$A = \frac{kx^2}{2}$$ (4)

(x is the piston displacement).

Let us express the values ​​of $\frac{kx^2}{2}$ in terms of gas parameters.

Since the piston is at rest after establishing equilibrium, the spring force $F = kx$ is equal to the gas pressure force $P_2S$ (S is the surface area of ​​the piston):

$$kx = P_2S.$$ (5)

The pressure of a gas is related to the temperature of its internal gas state. For one mole of gas

$$P_2V_2 = RT_2.$$ (6)

Since the volume of gas during its distribution increased, and the change in gas volume is $Sx$, then $V_2 = 2Sx$, and therefore,

$$2P_2Sx = RT_2.$$ (7)

Taking into account correspondences (5) and (7), we can write

$$kx = \frac{RT_2}{2x}$$ (8)

$$kx^2 = \frac{RT_2}{2}.$$ (9)

Thus, the work done by the gas is equal to

$$A = \frac{kx^2}{2} = \frac{RT_2}{4}.$$ (10)

Let's substitute expressions (3) and (10) into equality (2):

$$c_v (T_2 - T_1) + \frac{1}{4}RT_2 = 0.$$

From here

$$T_2 = T_1 \frac{1}{1 + \frac{1}{4} \frac{R}{c_v}}.$$ (11)

Indeed, $T_2$ is less than $T_1$.

Now let's see how the gas pressure changes. According to the equation of gas state, the initial gas pressure $P_1$, its volume $V_1 = \frac{V_2}{2}$ and temperature $T_1$ were related by the formula

$$P_1 \frac{V_2}{2} = RT_1.$$

Dividing this equality by equality (6), we obtain

$$\frac{P_1}{P_2} = 2 \frac{T_1}{T_2} = 2 \left(1 + \frac{1}{4} \frac{R}{c_v}\right),$$

$$P_2 = \frac{P_1}{2 \left(1 + \frac{1}{4} \frac{R}{c_v}\right)}$$

The pressure also decreased.

F167. We connect an ideal ammeter to the output of the “black box”. If we connect a battery with e.g. to the input of the “box”. d.s. E and internal resistance r, then it can be exactly 2 times less than in the case when two batteries connected in series are connected to the input of the box. Draw the simplest possible diagram of the internal structure of a “black box”.

⟦folio 55⟧

Fig. 14.

An internal circuit cannot consist only of resistance. Indeed, consider the circuit shown in figure 14, where $R$ is the resistance of the “box”.
When connecting one source, current must flow through the amplifier

$$I = \frac{E}{R + r},$$

(1)

and when two sources are connected - current 2I, and

$$2I = \frac{2E}{R + 2r}.$$

(2)

Equations (1) and (2) are incompatible. They have no solution for any $R$. Indeed, dividing equation (1) by (2), we obtain

$$\frac{1}{2} = \frac{R + 2r}{2(R + r)}$$

or

$$R + r = R + 2r,$$

but this is impossible.

Connecting a resistor parallel to the input or output of the box does not help either. (Show it!). Therefore, the internal circuit must include an “active” element - a current source.

Fig. 15.

Let us consider one of the possible schemes shown in figure 15 and show that it satisfies the conditions of the problem.

When connecting one battery to the input of the box, the current will increase through the amperage

$$I_1 = \frac{E + E_1}{r + r_1},$$

and when connecting two - current

$$I_2 = \frac{2E + E_1}{2r + r_1}.$$

Since $I_2 = 2I_1$, then

$$\frac{2(E + E_1)}{r + r_1} = \frac{2E + E_1}{2r + r_1}.$$

From here we will find

$$E_1 = -E \frac{2r}{3r + r_1}.$$

This equality connects e. d.s. source $E_1$ and its internal resistance $r_1$. The sign "—" means that the source is an internal source.

F168. The six-minute pencil was silent along the horizontal plane, as shown in figure 16. At what values ​​of the time coefficient $\alpha$ between the pencil and the plane will the pencil slide along the plane without healing?

Two forces act on a moving pencil from the sides of the plane: the normal reaction force of the plane $N$ and the friction force $F_{TP}$. Since the pencil should not move in the vertical direction, the force $N$ is equal in abscimal value to the force:

$$N = mg.$$

The friction force is equal to $F_{TP} = \alpha N = \alpha mg$.

Consider the moment when the pencil began to roll, turning around the edge $A$. In this case, both forces—force $N$ and force $F_{TP}$—are applied to edge $A$. If the equal force $R$ of these forces passes below the center of gravity of the pencil, that is, below the axis of the pencil, then the moment of this force relative to the axis of the pencil causes the pencil to rotate. If the force $R$ passes above the axis, then the pencil will not rotate.

Thus, the conditions for the pencil not to rotate:

$$tg \beta = \frac{N}{F_{TP}} > tg 60^\circ,$$

or

$$\frac{mg}{\alpha mg} > \sqrt{3}.$$

⟦folio 56⟧

Fig. 17.

From here we find what the friction coefficient should be:

$$\alpha < \frac{1}{\sqrt{3}}.$$

Many of the readers who sent us letters solved this problem by trying a coordinate system associated not with a plane, but with a pencil. This is a non-inertial coordinate system, and in it the pencil is still subject to strong inertia.

$$F_{\pi} = ma,$$

where $a$ is the acceleration of the pencil relative to the plane.

Since this acceleration imparts to the pencil the force of friction on the plane $F_{\pi} = \alpha mg$, then $a = \alpha g$, and therefore $F_{\pi} = m\alpha g$. The pencil rotates around edge $A$ (instantaneous axis of rotation), if the moment of force $F_{\pi}$ relative to this point is greater than the moment of force of the weight (Fig. 17), that is, if

$$F_{\pi} \cdot \frac{a \sqrt{3}}{2} > \frac{1}{2} mg,$$ or

$$\alpha mg \sqrt{3} > mg.$$

From this we get that the pencil rolls without rotating if

$$\alpha < \frac{1}{\sqrt{3}}.$$

F169. For long-distance space communications, a satellite with a volume of $V=100$ m³, filled with air under normal conditions, is used. Meterorim we break through the rejected area $S=1$ cm² in its body. Estimate the time after which the pressure inside the satellite will change by 1%. The gas temperature remains unchanged. The universal gas constant is 8.3·10³ J/deg·kmol.

To estimate, we can assume that each of the air molecules in the satellite can move only along one of three mutually perpendicular axes, one of which is perpendicular to the plane of rejection (such a simplified model is often used in the kinetic theory of gases). Then, at any moment, 1/3 of all air molecules in the satellite moves along this axis, and the speed of half of these molecules, that is, 1/6 of all molecules, is directed toward rejection. Of these, in time $t$, those molecules that are at a distance $l = \bar{v}t$ from the rejection will be rejected and will fly out of the satellite, that is, molecules located at the initial moment in volume $V_0 = S\bar{v}t$, where $\bar{v}$ is the mean square velocity of the molecules (Fig. 18). (We assume for the assessment that all molecules move with the same abscylotic velocities, equal to the mean square velocity $\bar{v}$). If the number of molecules per unit volume is $n$, then in just $t$ time the

$$N = \frac{1}{6} S\bar{v}t n \text{ молекул.}$$

Since the molecules are ejected from the satellite, the number of molecules per unit volume will change. This change is

$$\Delta n = \frac{N}{V} = \frac{1}{6} \frac{S\bar{v}t n}{V}.$$

This correspondence can be rewritten as

$$\frac{\Delta n}{n} = \frac{1}{6} \frac{S\bar{v}t}{V}$$

or

$$\tau = 6 \frac{\Delta n}{n} \frac{V}{S\bar{v}}.$$

According to the conditions of the problem, the air temperature in the satellite remains unchanged. As follows from the Clapeyron-Mendleev equation of state for an ideal gas, in this case the pressure is proportional to the gas density (and therefore the number of molecules per unit volume): $P \sim n$. That's why

$$\frac{\Delta P}{P} = \frac{\Delta n}{n} = 0,01.$$

Taking into account the expression for the mean square speed of molecules

$$\bar{v} = \sqrt{\frac{3RT}{\mu}},$$

⟦folio 59⟧

Solution. In this case, let the solutions be suggested by the symmetry of this equation with respect to sin x, cos x. Explicitly identifying the simplest symmetric polynomials for sin x and cos x (the expressions sin x + cos x, sin x cos x), we write the equation in the form

$$(\sin x + \cos x) - 4 \sin x \cdot \cos x + \sin x \cdot \cos x (\sin x + \cos x) = 2.$$

Let sin x + cos x = u; then $u^2 - 1 = 2 \sin x \cdot \cos x$ and the equation has the form

$$u (u^2 - 4 u + 1) = 0,$$

whence $u_1 = 0, u_2 = 2 + \sqrt{3}, u_3 = 2 - \sqrt{3}$.

The equation sin x + cos x = u can be easily solved, and since |u| = |sin x + cos x| = |\sqrt{2} \cos \left( x - \frac{\pi}{4} \right)| \leqslant \sqrt{2}, then the root $u_2 = 2 + \sqrt{3}$ is not suitable.

Answer: $x = -\frac{\pi}{4} + k\pi; x = \frac{\pi}{4} \pm \arccos \frac{2 - \sqrt{3}}{\sqrt{2}} + 2l\pi$.

The next group of examples shows that to successfully solve the problems proposed in the application exams, it is not enough to be able to reduce an equation to one of the known types (equations reducible to a single trigonometric function, homogeneous, symmetric, etc.).

Example 4 (MIPT, 1970). Solve the equation

$$\sin x + 2 \cos x = \cos 2x - \sin 2x.$$

Solution. Passing to equation (1) to the argument x using the formulas sin 2x = 2 sin x cos x and cos 2x = $\cos^2 x - \sin^2 x = 1 - 2 \sin^2 x$, we obtain

$$\sin x + 2 \sin^2 x + 2 \cos x + 2 \sin x \cos x - 1 = 0.$$

Equation (2) could be reduced to an algebraic equation for u using the so-called universal stand $u = \mathrm{tg} \frac{x}{2}$, expressing sin x and cos x in terms of u. It is easy to see that in this case we obtain the equation

$$3 u^4 + 2 u^3 - 6 u^2 - 6 u - 1 = 0.$$

We will not find the roots of this equation, although this could be done, but we will try to find a shorter solution based on the factorization of the left side of the equation.

Equation (2) has the root sin x = -1 (in this case cos x = 0), so the left side of the equation can be factorized:

$$(1 + \sin x)(2 \sin x + 2 \cos x - 1) = 0.$$

Answer: $x = -\frac{\pi}{2} + 2k\pi; x = -\frac{\pi}{4} + (-1)^n \arcsin \frac{1}{2 \sqrt{2}} + \pi n$.

Comment. It should be emphasized that the factorization method in combination with other methods is one of the most effective examples of solving trigonometric equations.

⟦folio 61⟧

Before we move further in this direction, let's simplify equation (7) by drinking.

Noticing that $tg^2 x + ctg^2 x = -2 + \frac{4}{\sin^2 2x}$, we find

$$\frac{1}{\sin^2 2x} = 1 - \frac{1}{\sqrt{3}} \frac{\cos 2x}{\sin 2x}$$

and further, transforming, we get $\sqrt{3} \cos^2 2x + \sin 2x \cdot \cos 2x = 0$. The last equation is easy to solve.

Answer: $x = \frac{\pi}{4} + \frac{k\pi}{2}$; $x = -\frac{\pi}{6} + \frac{l\pi}{2}$ (it is easy to check that for these values ​​of $x$ we have $\sin 2x \neq 0$).

The solution has been obtained, but for comparison, let’s complete the solution to equation (7). The first one has so far led us to equation (8). Grouping terms having a factor of $\sqrt{3}$ gives the equation

$$(u^2 - 1) \left[ \sqrt{3} (u^2 - 1) - 2u \right] = 0,$$

which has roots: $u_1 = 1; u_2 = -1; u_3 = \sqrt{3}; u_4 = -\frac{1}{\sqrt{3}}$.

It is easy to verify that these roots lead to the same answer.

Comment. There is no doubt that in this case, transforming the equation by passing to the argument $2x$ is preferable to substituting $u = tg x$. We have once again seen that increasing the argument of the trigonometric functions included in the equation leads to its simplification.

Let's look at an example of a different type.

Example 8: Solve the equation

$$tg (120^\circ + 3x) - tg (140^\circ - x) = 2 \sin (80^\circ + 2x).$$

Solution. When finding a reasonable way to solve equation (9), obviously, you should pay special attention to the arguments of the trigonometric functions included in the equation. The connection between the arguments becomes clear if we notice that $tg (140^\circ - x) = -tg (x + 40^\circ)$. Now the expediency of using the replacement $x + 40^\circ = t$ is beyond doubt. Using this replacement, the original equation is transformed to the form $tg 3t + tg t = 2 \sin 2t$, or

$$\frac{\sin 4t}{\cos t \cdot \cos 3t} = 2 \sin 2t.$$

Since $\sin 4t = 2 \sin 2t \cos 2t$, equation (10) can be represented as

$$\frac{2 \sin 2t (\cos 2t - \cos 3t \cdot \cos t)}{\cos t \cdot \cos 3t} = 0.$$

Let's transform the expression in parentheses using the formula

$$\cos 2t = \cos (3t - t) = \cos 3t \cdot \cos t + \sin 3t \cdot \sin t.$$

Then the problem will be reduced to finding those solutions to the equation

$$\sin t \cdot \sin 2t \cdot \sin 3t = 0,$$

⟦folio 62⟧

which satisfy the conditions $\cos t \cdot \cos 3t \neq 0$, that is, to the solution of the equation $\sin 3t = 0$.

Answer: $x = -40^\circ + \frac{n\pi}{3}$.

Example 9. Solve the equation

$$\cos 3x + \cos \frac{5x}{2} = 2.$$

Solution. If we transform the left side of this equation using the sum of cosines formula, we obtain the equation $\cos \frac{x}{4} \cdot \cos \frac{11x}{4} = 1$. Since for any $\alpha$ the inequality $|\cos \alpha| \leq 1$ is valid, the resulting equation can have a solution only if the condition is satisfied

$$\begin{cases} \cos \frac{x}{4} = 1, \\ \cos \frac{11x}{4} = 1 \end{cases}$$ or $$\begin{cases} \cos \frac{x}{4} = -1, \\ \cos \frac{11x}{4} = -1. \end{cases}$$

In this way it would be possible to find a solution to the original equation. However, another, simpler path also leads to the goal.

The left side of the equation can equal two only in the case when the equality $\cos 3x = 1$ and $\cos \frac{5x}{2} = 1$ occur simultaneously.

Finding the solution to the first equation ($x = \frac{2k\pi}{3}$) and substituting it into the second, we obtain $\cos \frac{5k\pi}{3} = 1$, whence $k = 6m$.

Answer: $x = 4m\pi$.

The following examples require the ability to use the concept of absolute value.

Example 10 (MIPT, 1971). Solve the equation

$$\text{tg}x + \frac{1}{9}\text{ctg}x = \sqrt{\frac{1}{\cos^2x} - 1} - 1.$$

Solution. The right side of equation (11) can be written as follows: $\sqrt{\text{tg}^2x} - 1 = |\text{tg}x| - 1$. A serious mistake would be to discard the modulus sign (unfortunately, quite a few applicants solving this example made this mistake). Equation (11) takes the form

$$\text{tg}x + \frac{1}{9}\text{ctg}x = |\text{tg}x| - 1.$$

Let's consider two cases: $\text{tg}x > 0$, $\text{tg}x < 0$ (for $\text{tg}x = 0$ the left side of the equation becomes meaningless).

a) If $\text{tg}x > 0$, then equation (12) is reduced to the form $\text{ctg}x = -9$, which implies that $\text{ctg}x < 0$, which contradicts the condition $\text{tg}x > 0$. In this case there is no solution.

b) If $\text{tg}x < 0$, then, assuming $u = \text{tg}x$, from (12) we find $18u^2 + 9u + 1 = 0$, whence

$$u_1 = -\frac{1}{6}; \quad u_2 = -\frac{1}{3}.$$

⟦folio 63⟧

Both values ​​found are negative, so the condition $tg x < 0$ is satisfied.

Answer: $x = -\arctg \frac{1}{6} + n\pi; \quad x = -\arctg \frac{1}{3} + m\pi$.

Example 11. Solve the equation

$$\sin x + \sqrt{3} \cos x = \sqrt{2 + \cos 2x + \sqrt{3} \sin 2x}.$$

(13)

Solution. Since the right side of the equation is non-negative, the condition must be satisfied

$$\sin x + \sqrt{3} \cos x \geq 0.$$

(14)

If we get rid of the radical by squaring both sides of equation (13), we obtain the equation

$$\sin^2 x + 3 \cos^2 x + 2 \sqrt{3} \sin x \cos x = 2 + \cos 2x + \sqrt{3} \sin 2x,$$

which after the equation takes the form

$$\cos 2x = \cos 2x.$$

(15)

We received the same gesture. This does not mean, however, that the original equation is satisfied by all values ​​of $x$, since equation (15) is only a consequence of equation (13). Equations (13) and (15) become equivalent if condition (14) is satisfied. Thus, the solutions to equation (13) are all values ​​of $x$ satisfying inequality (14), and only these values. Solving inequality (14) is not difficult.

Answer: $-\frac{\pi}{3} + 2\pi n \leq x \leq \frac{2\pi}{3} + 2\pi n$.

Comment. There are several ways to reach this answer. We have $2 + \cos 2x + \sqrt{3} \sin 2x = \left[ 1 + \cos \left( 2x - \frac{\pi}{3} \right) \right] = 4 \cos^2 \left( x - \frac{\pi}{6} \right)$, and therefore the original equation takes the form $\cos \left( x - \frac{\pi}{6} \right) = \left| \cos \left( x - \frac{\pi}{6} \right) \right|$. We again come to conditions (14).

Exercises

Solve equations:
1. (MIPT, 1969). $\sin^4 x + \sin^3 x \cdot \cos x + \sin^2 x \cos^2 x + \sin x \cdot \cos^3 x + \cos^4 x = 1$.
2. $\sin^3 x (1 + \text{ctg} x) + \cos^3 x (1 + \text{tg} x) = 2 \sqrt{\sin x \cos x}$.
3. (MIPT, 1971). $\cos^2 x + \cos^2 2x = \cos^2 3x$.
4. $\cos \frac{4x}{3} = \cos^2 x$.
5. (MIPT, 1970). $\sqrt{1 - 2 \text{tg} x} - \sqrt{1 + 2 \text{ctg} x} = 2$.
