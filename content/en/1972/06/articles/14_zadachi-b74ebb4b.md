---
id: 1972-6-zadachi-b74ebb4b
issue: kvant_1972_6
year: 1972
number: "6"
title: Problem M146—M150; F158—F162
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 45
page_labels: 36, 39, 40, 42
tag: BIOA
lang: en
source: kvant_digital
extraction: vision
content_sha256: dd1edd537d1073d6c1fa1aa28f6f4801ad15c7b7b02dd81af6e5124b376f674a
prompt_sha256: draft-1
translated_from: content/ru/1972/06/articles/14_zadachi-b74ebb4b.md
source_content_sha256: 3d832fd0fcca5180bbe5edf9b161704fd0db07840df5f873711e8949a7bc61f4
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

TASKS

Solutions to problems can be sent no later than one and a half months after the publication of the corresponding issue of the journal to the address: 117071, Moscow V-71, Leninsky Prospekt, 15, publishing house "Nauka", editorial office of the journal «Kvant». After the address on the envelope, indicate the solutions to which problems you are sending; for example: “Problem «Kvant», M146, M148.” At the beginning of the letter, indicate your last name, first name, patronymic, home address, as well as the class and school in which you study.

M146.a) Black and white pieces are placed at the vertices of a regular 7-gon. Prove that there are three pieces of the same color lying at the vertices of an equilateral triangle.

6) Is a similar statement true for an octagon?

c) * Find out for which regular n-gons a similar statement is true and for which it is not.

A. Romanov

M147. Prove that if a quadrilateral ABCD inscribed in a circle is such that the tangents to the circle at points A and C intersect on the extension of the diagonal BD, then

a) the tangents at points B and D intersect along the continuation of the diagonal AC;

6) The bissertrixes of the interior angles A and C of the quadrilateral intersect on diagonal BD (and angles B and D on AC).

I. F. Sharyzin

M148. The sequence $x_0, x_1, x_2, \dots$ is defined by the following conditions: $x_0 = 1, x_1 = \lambda$, for any $n > 1$ $(\alpha + \beta)^n x_n = \alpha^n x_n x_0 + \alpha^{n-1} \beta x_{n-1} x_1 + \alpha^{n-2} \beta^2 x_{n-2} x_2 + \dots + \beta^n x_0 x_n$. Here $\lambda, \alpha, \beta$ are given positive numbers. Find $x_n$ and find out at which $n$ the value of $x_n$ will be greatest.

A. L. Lopshits

M149. Let $O$ be the intersection point of the diagonals of the quadrilateral ABCD. Prove that

a) if the perimeters of quadrilaterals ABC, BCD, CDA and DAB are equal, then ABCD is a rectangle;

6) if the perimeters of the quadrilaterals ABO, BCO, CDO and DAO are equal, then ABCD is a rhombus.

N. B. Vasiliev

M150*. From the numbers 1, 2, ..., $k$ all possible sets $(a_1, a_2, \dots, a_n)$ of length $n$ are made (it is easy to see that there are $k^n$ of them). Two subsets $P$ and $Q$ of such sets are selected (the same set can be included in $P$ and $Q$). It is known that if we take an arbitrary set $(p_1, p_2, \dots, p_n)$ from $P$ and an arbitrary set $(q_1, q_2, \dots, q_n)$ from $Q$, then they will coincide at least in one place (that is, $p_i = q_i$ for some $i$). Then there are at most $k^{n-1}$ sets in either $P$ or $Q$.

Prove this statement

a) for $k = 2$ and any $n$;

b) for $n = 1, 2, 3$ and any $k \geq 2$;

b) for arbitrary $k \geq 2$ and $n \geq 1$.

Try to find other restrictions on the number of elements in the subsets $P$ and $Q$ related to such conditions.

V. B. Alekseev

F158. A dumbbell located horizontally falls from a height $h$ and is removed with one of its ends on the table

⟦folio 39⟧

Let's consider the difference
$$f_1(x) - f_2(x) = f_3(x).$$
(1)

Note that $p_1 - p_2 \neq 0$, since if $p_1 - p_2 = 0$, then $R = (q_1 - q_2)^2 \geq 0$, which contradicts the conditions. Therefore, the equation $f_3(x) = 0$ has the root $\gamma = -\frac{q_1 - q_2}{p_1 - p_2}$, and, of course, $f_3(x)$ can be written as follows:
$$f_3(x) = (p_1 - p_2)(x - \gamma).$$
(2)

Moreover, as follows from (1),
$$f_1(\gamma) = f_2(\gamma).$$
(3)

Now the square trinomial $f_2(x)$ (multiplied by the coefficient $(p_1 - p_2)^2$ “divide with remainder” by $f_3(x)$, that is, we write the identity
$$(p_1 - p_2)^2 f_2(x) = f_3(x) g(x) + R.$$

It is not by chance that we use the same letter $R$: the remainder is equal to the name of the expression $R$ given in the conditions of the problem. Really,
$$(p_1 - p_2)^2 (x^2 + p_2x + q_2) = [(p_1 - p_2)x + (q_1 - q_2)][(p_1 - p_2)x + (p_1 - p_2)p_2 - (q_1 - q_2)] + (q_1 - q_2)^2 + (p_1 - p_2)(p_1q_2 - p_2q_1).$$

Substituting $\gamma$ into (4), we obtain (taking into account that $f_3(\gamma) = 0$):
$$(p_1 - p_2)^2 f_2(\gamma) = R < 0.$$

Pozny $f_1(\gamma) = f_2(\gamma) < 0$. Therefore (by property (1)) both equations have two real roots. Let us denote their correspondence by $\alpha_1, \beta_1$ and $\alpha_2, \beta_2$. Then
$$f_2(x) = (x - \alpha_2)(x - \beta_2).$$
(6)

Now, using sequentially (1), (2), (6) and (5), we get:
$$f_1(\alpha_2) f_1(\beta_2) = f_3(\alpha_2) f_3(\beta_2) = (p_1 - p_2)^2 (\alpha_2 - \gamma)(\beta_2 - \gamma) = (p_1 - p_2)^2 f_2(\gamma) = R < 0,$$
(7)

whence it follows (by property (2)) that the roots of the equation intersect.

Using graphs, the result of the problem and the main correspondence (5) in our solution can be explained in two words (Fig. 2). The algebraic background of our solution is deeper.

From our solution, and from figure 2, it is clear that the $R = 0$ model is similar when the quadratic trinomials $f_1$ and $f_2$ have a common root (or coincide). This slander can be used in problems of this type: what conditions must the numbers $\lambda$ and $\mu$ satisfy for the equation $x^2 + \lambda x - 1 = 0$ and $x^2 + \mu x - \lambda x + \mu = 0$ to have a root? It is enough to substitute the values ​​$p_1 = \lambda$, $q_1 = -1$, $p_2 = \mu - \lambda$, $q_2 = \mu$ into the expression $R$, and the required condition is ready:
$$(\mu + 1)^2 + (2\lambda - \mu)(\mu - \lambda + \mu\lambda) = 0.$$

It turns out that for two polynomials of arbitrary degree
$$f_1(x) = a_1x^n + b_1x^{n-1} + \dots + c_1,$$
$$f_2(x) = a_2x^m + b_2x^{m-1} + \dots + c_2$$

it is possible to write down a polynomial $R$ in $a_1, a_2, b_1, b_2, \dots, c_1, c_2$ such that the condition $R = 0$ is satisfied when $f_1$ and $f_2$ have a common divisor (a polynomial in $x$ of degree 1 or higher). $R$ is called the result of the polynomials $f_1$ and $f_2$.

In the higher algebra course, a compact representation of the result is given in the form of a “determinant” composed of the coefficients $f_1$ and $f_2$.

The concept of result becomes especially arbitrary when $f_1$ and $f_2$ are factorized into linear factors:
$$f_1 = a_1(x - \alpha_1)(x - \beta_1) \dots (x - \gamma_1),$$
$$f_2 = a_2(x - \alpha_2)(x - \beta_2) \dots (x - \gamma_2)$$

⟦folio 40⟧

(this is always true for a set of complexes of numbers, because any polynomial there has a root). Then, as can be proven,

$$R = R(f_1, f_2) = a_1^m a_2^n (\alpha_1 - \alpha_2)(\beta_1 - \alpha_2) \dots (\gamma_1 - \gamma_2),$$

(8)

where the product is taken over all parameters $f_1$ and $f_2$ (that is, it has $mn$ components). Check that there is $R = (\alpha_1 - \alpha_2)(\beta_1 - \alpha_2)(\alpha_1 - \beta_2)(\alpha_2 - \beta_2)$ in our problem, and think about how to use this expression $R$ through the roots (perhaps complexes!) of square trinomials to solve the problem in a different way. From equality (8) follows the following equality, which we have already encountered in a partial case:

$$R = a_1^m f_2(\alpha_1) f_2(\beta_1) \dots f_2(\gamma_1) =$$

$$= (-1)^{mn} a_2^n f_1(\alpha_2) f_1(\beta_2) \dots f_1(\gamma_2).$$

The main property of the result, taking into account complexes of roots, can be formulated as follows: $R = 0$ modda and molko modda, koeda $f_1$ and $f_2$ have a common root.

M107

a) Given a convex polygon $A_1A_2 \dots A_n$ (Fig. 3). On side $A_1A_2$ points $B_1$ and $D_2$ are taken, on side $A_2A_3$ - points $B_2$ and $D_3$, ... on side $A_nA_1$ points $B_n$ and $D_1$ so that if we construct parallelograms $A_1B_1C_1D_1$, $A_2B_2C_2D_2$, ..., $A_nB_nC_nD_n$, then the lines $A_1C_1$, $A_2C_2$, ..., $A_nC_n$ will intersect at one point. Prove that

$$A_1B_1 \cdot A_2B_2 \dots \cdot A_nB_n =$$

$$= A_1D_1 \cdot A_2D_2 \dots \cdot A_nD_n.$$

b) Prove that the converse statement is also true for the triangle: points $B_1$ and $D_2$ are chosen on the empty side $A_1A_2$, points $B_2$ and $D_3$ on the side $A_2A_3$, points $B_3$ and $D_1$ on the side $A_3A_1$ so that $A_1B_1 \cdot A_2B_2 \cdot A_3B_3 = A_1D_1 \cdot A_2D_2 \cdot A_3D_3$; then, if we construct parallelograms $A_1B_1C_1D_1$, $A_2B_2C_2D_2$, $A_3B_3C_3D_3$, then the lines $A_1C_1$, $A_2C_2$ and $A_3C_3$ will intersect at one point.

a) Let $O$ be the point of intersection. Let's write down the equality that we need to prove like this (we shift all components into the denominator, cross $A_1D_1$ at the end):

$$\frac{A_1B_1 \cdot A_2B_2 \cdot \dots \cdot A_nB_n}{A_2D_2 \cdot A_3D_3 \cdot \dots \cdot A_nD_n} = 1.$$

Now we note that the ratios of the segments $A_1B_1/D_2A_2$, $A_2B_2/D_3A_3$, ..., $A_nB_n/D_1A_1$ are respectively the ratios of the areas of triangles (we denote the area of ​​triangle $MNL$ as follows: $S(MNL))$

$$\frac{S(A_1B_1O)}{S(D_2A_2O)}, \frac{S(A_2B_2O)}{S(D_3A_3O)}, \dots, \frac{S(A_nB_nO)}{S(D_1A_1O)},$$

so the equality we need can be written like this:

$$\frac{S(A_1B_1O) \cdot S(A_2B_2O) \cdot \dots \cdot S(A_nB_nO)}{S(A_2D_2O) \cdot S(B_3D_3O) \cdot \dots \cdot S(B_nD_nO) \cdot S(A_1D_1O)} = 1;$$

⟦folio 42⟧

between points $A$ and $C$ and between points $C$ and $B$. By then solving a system of six equations in six unknowns, the resistances $r_1$, $r_2$ and $r_3$ can be found.

This method, of course, cannot be considered successful, especially since none of the readers who sent us such a solution were able to solve this system of equations in a general form. The participant in the final round of the All-Union Olympiad, who proposed this problem, also failed to solve it.

F124

Light from source $S$ on its way to the screen passes through a glass cube at rest with edge $l$ (Fig. 11). How much faster does the light reach the screen if the cube is moved at a speed of $v$? The speed of light in air is $c$, the refractive index of the stack is $n$ ($v \ll c$, $n \gg 1$).

The speed of light in glass is $c' = \frac{c}{n}$. Light passes through a glass cube in time $t = \frac{l}{c'} = \frac{\ln c}{c}$. During this time the cube moves a distance $x = vt = \frac{v \ln c}{c}$. The path of light in the air is reduced by this distance compared to the case when the cube is motionless. This means that the time it takes for the light to reach the screen is reduced by $\Delta t = \frac{x}{c} = \frac{v \ln c}{c^2}$.

Some readers have submitted a more rigorous solution to this problem, taking into account the effects associated with relativity theories. We will not analyze this decision in detail. Let us only note that when taking into account “relativistic effects,” the speed of light in a moving glass cube should be considered equal not to $c' = \frac{c}{n}$, but to $c'' = \frac{c' + v}{1 - \frac{v^2}{c^2}} = \frac{(c + nv)c}{nc - v}$.

At the same time, the length of the cube in the fixed coordinate system is equal to $l$, and $l' = l \sqrt{1 - \frac{v^2}{c^2}}$. Therefore, it is necessary to take into account not only the decrease in the path traveled by light in the air due to the movement of the cube, but also the decrease in the path traveled by light in the glass.

F125

There is water in a cylinder with a piston, inside of which at the initial moment there is a cavity of volume $V$. The gas pressure in the cavity is negligible. The piston exerts constant pressure $p$ on the body. What kinetic energy does the water acquire at the moment when the cavity disappears? The initial speed of water is zero. The force of gravity can be ignored.

The piston is acted upon by a force $F = pS$, where $S$ is the area of ​​the piston. The work done by the piston is equal to the product of this force and the displacement of the piston $x$. But the movement of the piston is associated with a change in the volume of gas in the cylinder: $x = \frac{V}{S}$. That's why

$$A = Fx = pS \frac{V}{S} = pV.$$

This work is equal to the change in the kinetic energy of water. The same result can be obtained from dimension messages. From two quantities $p$ and $V$ one can form a unique combination having the energy dimension $pV$.

F126

Estimate the maximum force that will be shown by the diameter attached to the planes covering the “Magdedburg hemispheres” (hemispheres) with radius $R$. The hemispheres are stretched in opposite directions by forces $F$. Atmospheric pressure is 1 amp.

Each of the planes is in equilibrium due to the three forces acting on it: $T$ acting from the diameter, the force $F_0 = p_0S$ of atmospheric pressure and the reaction force of the hemisphere (Fig. 12). Since at the moment when the plane breaks away from

⟦folio none⟧

hemisphere, the reaction force of the hemisphere is zero, then $T_{\text{max}} = F_0 = pS = \rho_0 \pi R^2 \approx 12.6 \cdot 10^3 \pi$.

F127

A ball is thrown into a glass of water rotating around its axis and floats on the surface of the water. Where on the surface will the ball be located?

Since the ball floats on the surface of the water, the density of the material of the ball is less than the density of water: $\rho_{\text{ш}} < \rho_{\text{в}}$.

Let us assume that the ball is at a distance $R$ from the axis of the rotating vessel. If the density of the ball were equal to the density of water $\rho_{\text{в}}$, it would be at a constant distance from the axis of rotation. The centripetal acceleration of such a ball is imparted by the resultant force of gravity and the pressure forces of the surrounding water. Since the ball moves along a circle of radius $R$, this resultant is equal to $m\omega^2 R = \rho_{\text{в}} V\omega^2 R$ (ω is the angular velocity of rotation of the vessel, V is the volume of the ball).

A ball of density $\rho_{\text{ш}}$, placed at the same point, is acted upon by the surrounding water by exactly the same force. This force imparts acceleration to the ball $a = \frac{\rho_{\text{в}}}{\rho_{\text{ш}}} \omega^2 R$, a larger centripetal acceleration necessary for rotation in a circle of radius $R$. Consequently, the ball will move towards the axis of rotation of the vessel. This means that the equilibrium position of the ball is on the axis of the vessel.

F128

A thin homogeneous stick is classified so that it rests on two planes inclined to the horizon at angles α and β, the angle between the planes is 90° (Fig. 13). What will happen with the wand? What will be its final position if the friction between the stick and the planes is very small?

Let the angle between the stick and one of the planes be equal to γ. Let us connect the center of gravity of the stick C with the vertex of the angle O and show that the length of the segment CO does not depend on the value of γ.

Let us carry out CD ⊥ OB. Triangle CDB is similar to triangle OAB. Therefore $\frac{DB}{OB} = \frac{CB}{AB} = \frac{1}{2}$. This means that DB = OD, and triangle OCD is equal to triangle CDB on two legs. It follows that the segment OC is equal to half the length of the stick at any angle γ, that is, the center of gravity of the stick C describes a circle when it moves.

A body is in equilibrium if its potential energy is minimum or maximum. However, in the position with minimum potential energy the equilibrium is stable, and in the position with maximum energy it is unstable. Therefore, the stick can be in stable equilibrium only when it lies on one of the planes. The stick will oscillate, hitting each plane in turn and then bouncing off it.

Due to the weight of the stick, it will fade, and after a sufficiently long time the stick will remain at one of the planes.

It is interesting to analyze a case where training is not enough. Try to do this yourself, and we will consider such a case in one of the upcoming issues of the magazine.

I. Sh. Slovodetsky
