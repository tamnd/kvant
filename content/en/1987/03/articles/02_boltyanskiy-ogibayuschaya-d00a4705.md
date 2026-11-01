---
id: 1987-3-boltyanskiy-ogibayuschaya-d00a4705
issue: kvant_1987_3
year: 1987
number: "3"
title: Envelope
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2, 4, 5, 7
tag: 9Q3M
lang: en
source: kvant_digital
extraction: vision
content_sha256: 254c4020303ed99ce6087e21283be0463262c64c30da4f25c244a36795c635b9
prompt_sha256: draft-1
translated_from: content/ru/1987/03/articles/02_boltyanskiy-ogibayuschaya-d00a4705.md
source_content_sha256: 8eb296017cb9bcd2d8f94a685b986e76e1ae788dee111db7732ebb94359a0e27
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

ENVELOPE
Corresponding Member of the Academy of Pedagogical Sciences of the USSR
V. G. VOLTYANSKY

figure 1 shows a closed convex line $L$. This line is the main line, i.e. at each point of this line a tangent can be drawn to it. The set (or, as another way of saying it, “family”) of all tangents to the line $L$ is denoted by $T$. figure 2 shows several lines belonging to the $T$ family (i.e., tangent to the line $L$). These straight lines seem to “go around” the lines $L$; therefore, the line $L$ is said to be the envelope of the family of lines $T$.

We can also pose the opposite question: given a certain family of lines $T$, we need to find the envelope of this family, i.e., a line that touches all lines of the family $T$. The problem of finding the envelope part occurs in mathematics and its applications. The solution to this problem will be discussed here.

Envelope of a family of lines

Let's return to figure 2. Line $L$ divides the plane into two regions, internal and external. Through each point $M_0$, lying in the outer region $E$, there pass two lines of the family $T$ (i.e., tangents to the line $L$), and through the point $M_1$, lying in the inner region $J$, there is not a single tangent. Through each point $M$ of the line $L$ there passes one line of the family $T$ (tangent).

This circumstance will help us find a similar method for finding the envelope. To do this, we associate each line from the family $T$ with some real number $\alpha$ as its “number” (more precisely, a parameter). Namely, having fixed the initial point $A$ on the line $L$, we associate the straight line $l \in T$ tangent to the curve at the point $M$ (Fig. 3), the number (parameter) $\alpha$, equal to the length of the arc $AM$ of the line $L$. There are also other ways to associate each straight line $l$ of the family $T$ with a certain parameter value.

The direct line (from the family $T$), which is associated with the value of the parameter $\alpha$, is denoted by $l(\alpha)$; let the equation of this line have the form

$$A(\alpha)x + B(\alpha)y + C(\alpha) = 0. \quad (1)$$

Let us now recall (see Fig. 2) that different numbers of lines of the family $T$ can pass through different points. How can we find out how many values ​​of the parameter $\alpha$ there are for which the equality is true? In other words, we need to solve for $\alpha$ the equation

$$A(\alpha)x_0 + B(\alpha)y_0 + C(\alpha) = 0. \quad (2)$$

For example, if it turned out that equation (2) is quadratic with respect to $\alpha$, then it would be understandable why two lines of the family $T$ pass through some points (the equation has two different real roots $\alpha_1, \alpha_2$), and through some points there are no

⟦folio 4⟧

In other cases, for example, it is easier geometrically to see which line is an envelope than to write an equation of a straight line that belongs to a family and equate the discriminant to zero.

Example 3. Given an angle (smaller than the unfolded angle). The family T consists of all lines cutting off the triangle of the constructed permeter 2p from this angle. Find the female of this family.

Solution. Let us plot on the sides of a given angle O the segments OA and OB, having length p (Fig. 7), and consider the circle Γ tangent to the side of the angle at points A and B. Any tangent l to the circle Γ (drawn so that the point O and the circle Γ are on opposite sides of it) has the required property, i.e. l∈T, since
$$OP + OQ + PQ = OP + OQ + PS + SQ = OP + OQ + PA + QB = OA + OB = 2p.$$
If the line l' does not touch the arc AB of the circle Γ, then the triangle it cuts off has either a smaller or a larger perimeter, i.e. this line does not belong to the family T. So, the family T consists of all lines tangent to the arc AB of the circle Γ, and the envelope of this family is the arc AB.

Curve family envelope

Let us now note that in the questions discussed above, the fact that the family T consists of straight lines was not used. The only important thing was that the line of the family T depends on the parameter α, with respect to which the lying part of the equation is a quadratic trinomial. The following example confirms this.

Example 4. At point O there is an anti-aircraft gun from which projectiles can be fired (with a given initial velocity v₀) at any angle to the horizon. Determine the firing zone (pretenbrets air resistance).

Solution. It is enough to consider points located in the same vertical plane. If u is the horizontal component of the initial velocity of the projectile fired from the gun at the moment t=0, then the vertical component is equal to $$\sqrt{v_0^2 - u^2}.$$ The horizontal projection of the projectile S (point P on figure 8) moves uniformly with the speed u, i.e. at the moment t the abscissa of the projectile is equal to x=ut. the vertical projection moves according to the law y=\sqrt{v_0^2 - u^2}·t-gt²/2, from where (taking into account that t=x/u) the projectile trajectory is found:

$$y = \sqrt{v_0^2 - u^2} \cdot \frac{x}{u} - \frac{gx^2}{2u^2}.$$

Isolating the term containing the radial and squaring it, we obtain (after multiplying by u⁴):

$$u^4 (x^2 + y^2) - u^2 x^2 (v_0^2 - gy) + g^2 x^4/4 = 0.$$

The left side depends on the parameter α=u² and is a quadratic trinomial with respect to α. Equating the discriminant of this trinomial to zero, we obtain the envelope equation

⟦folio 5⟧

yushi family $T$ of all projectile trajectories:

$$x^4(v_0^2 - gy)^2 - (x^2 + y^2)\cdot g^2x^4 = 0,$$

or, after dividing by $x^4$ and simplifying,

$$y = \frac{v_0^2}{2g} - \frac{g}{2v_0^2}x^2.$$

This deviation is called *safety parabola* (above it, flight is safe); the vertex of this parabola is at point (0; $v_0^2/2g$), and the branches are directed downward, since the coefficient of $x^2$ is negative (Fig. 9).

An important class of problems associated with the construction of circles related to a family arises from *Prince Huydesq* (“Physics-10”, paragraph 37, p. 96). We do not touch upon these problems here (see «Kvant», 1982, No. 6, p. 30).

Task 1.

1. All possible straight lines $ax + by = 1$ are considered, where the coefficients $a, b$ satisfy the condition $a^2 + b^2 = 1$. Find the divergence of this family of lines.

2. Find the divergence of the family of lines $y = 2\alpha x - \alpha^2$.

3. In the given plane there is a straight line $d$ and a point $A$ that does not belong to it. For each point $M \in d$, a straight line $l_M$ is considered, which is the axis of the symmetrical point $A$ and $M$. Find the highest value of the family of all straight lines $l_M$.

4. Find the (algebraic) boundary of the family of lines $(x - \alpha)^2 + y^2 - 1 = 0$ and give the geometric field of the result.

5. Consider a family of circles (Fig. 10)

$$(x - \alpha)^2 + y^2 = b^2 \left(1 - \frac{\alpha^2}{c^2}\right),$$

where $b, c$ is the positive number data and $a$ is the parameter ($|a| \leq c$). Prove that the boundaries of this family of circles are ellipses described by the equation

$$\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1 \quad (\text{где } a^2 = b^2 + c^2).$$

6. We consider the straight line $l(\alpha)$, defined by the equation

$$y - \alpha x + \frac{a}{2\sqrt{2}}(\alpha^2 - 1) = 0,$$

where $a$ is a given positive number and $a$ is a parameter ($|a| < 1$).

a) Find the points $P, Q$ of intersection of this line with the bisectors of the first and second coordinate angles and prove that $OP + OQ = a$.

b) Find the boundary of the family of lines $l(\alpha)$ and make sure that this boundary is represented by the arc of a parabola.

b) Given a right angle; We consider all possible straight lines cutting off this angle of the triangle, for which the sum of the lengths of the legs is equal to $a$. Prove that the boundaries of this family of lines are represented by arcs of a parabola.

7. We consider the straight line $l(\alpha)$, defined by the equation

$$bx(1 + \alpha^2) + ay(1 - \alpha^2) - 2\alpha ab = 0,$$

where $a, b$ are given positive numbers and $a$ is a parameter.

a) Find the points $P, Q$ of intersection of this line with lines $y = bx/a, y = -bx/a$ and prove that $OP \cdot OQ = a^2 + b^2, S_{\triangle OPQ} = ab$.

b) Prove that the boundary of the family of lines $l(\alpha)$ is the zunepbola described by the equation

$$\frac{x^2}{a^2} - \frac{y^2}{b^2} = 1.$$

b) Direct $y = bx/a, y = -bx/a$ are called acsimptotami of the specified general ball; prove that an arbitrary tangent to a hyperbola defines, together with acsimptotami, a triangle of constant area $S = ab$.

8. We consider the straight line $l(\alpha)$, defined by the equation

$$bx(\alpha^2 - 1) + 2\alpha ay + ab(\alpha^2 + 1) = 0,$$

where $a, b$ are given positive numbers; and $a$ is a parameter. Prove that the boundary of the family of lines $l(\alpha)$ is the ellipsis described by the equation in task 5.

9. Find the best value for the family of parabolas $y = \alpha^2x^2 - 2\alpha$ (where $a$ is a parameter). Make a drawing.

10. Find the boundary of the family of circles $x^2 + (y - \alpha)^2 = \alpha$ (where $a$ is a parameter). Make a drawing.

11. Find the boundary of the family of circles $(x - \alpha)^2 + y^2 = \alpha^2/5$ (where $a$ is a parameter). Make a drawing.

12. Find the best value for the family of parabolas $y = 2\alpha x^2 - \alpha^2$ (where $a$ is a parameter). Make a drawing.

13. Find the best value for the family of parabolas $y = \alpha x^2 + (1/\alpha - \alpha)$ (where $a$ is a parameter); make a drawing.

14. Find the best value for the family of parabolas $y = -\alpha x^2/4 + (\alpha + 1/\alpha)$ (where $a$ is a parameter); make a drawing.

Let's use an arbitrary

Now we will consider another, more general way of finding the rebounds, which is also applicable in the case when the left side of the equation is not a quadratic trinomial with respect to the parameter $a$. This method is based on the use of the concept of arbitrary.

Let the family of lines be given by the equation

$$f(\alpha, x, y) = 0,$$

where $f$ is some expression (for example

⟦folio 7⟧

or in a circle, the center of which is at the point $x = -v\alpha$ of the x-axis, and the radius is $\sqrt{(u\alpha)^2 - h^2}$ (Fig. 12). The circumference of this circle limits on the ground the zone in which (at the control moment) the sound produced by the aircraft when passing point $A_\alpha$ is located. The equation of this circle is
$$ (x + v\alpha)^2 + y^2 = (u\alpha)^2 - h^2. $$
Taking the unification of all these circles, we obtain a zone of convergence that is educational at the control point. And in order to find the boundary of the superfluity zone, it is necessary to find a strong (Fig. 13) family of circles (9). We write equation (9) in the form (4):
$$ \alpha^2 (v^2 - u^2) + 2\alpha xv + (x^2 + y^2 + h^2) = 0. $$
Taking the derivative with respect to $\alpha$, we obtain
$$ 2\alpha (v^2 - u^2) + 2xv = 0. $$
Finally, we determine $\alpha$ from the last correspondence and substituting it into (10), we obtain the envelope equation:
$$ u^2 x^2 - (v^2 - u^2) y^2 = h^2 (v^2 - u^2). $$
This equation describes the *Ziegerbola*; we need to take only its left branch, since we must consider circles (9) only at $\alpha > 0$. (Note that the same envelope equation can be obtained in the same way by taking the discriminant of the quadratic trinomial (10).)

Exercise
15. Find the envelope of the family of parabolas $y = \alpha^3 x^2 - 3\alpha$ (where $\alpha$ is a parameter). Make a drawing.
16. Find the envelope of the family of lines $y = \alpha^3 x - 3\alpha^2/2$.
17. Find the envelope of the family of lines $y = 4\alpha^3 x - 3\alpha^4$.
18. Find a family of lines whose envelope is the line $y = x^6$.
19. Find the envelope of the family of circles $(x - \cos \alpha)^2 + (y - \sin \alpha)^2 = 1/4$. Make a drawing.
20. Solve the problem about the zone of excess if the plane flies (so at supersonic speed) in a straight line inclined to the ground at an angle $\phi$.

Discriminant curve
Let us note in conclusion that if a certain family of lines (4) is given, then the line $L$, obtained by eliminating the parameter $\alpha$ from equation (8) (it is called *discriminant curve*), can, in addition to the envelope point, also contain the construction of a point. So, in example 4, the discriminant curve, as is easy to check, contains, in addition to the safety parabola, linear $x = 0$ (ordinat axis). The part of this axis located below the point $y = v^2/2g$ can, in a sense, be considered “tangent” to the trajectory that receives upward during a vertical shot, but the upper part of the ordinat axis (above this point) is located outside the firing zone and is in no way connected with the trajectories of the projectiles.

In general, the discriminative curve (not counting its “extraneous pieces”) separates from each other the areas through which a different number of family lines pass. In addition, the discriminative curve may contain “extraneous pieces” of singular points of the lines of the family (for example, points of their self-intersection). figure 14 shows a family of lines
$$ (x - \alpha)^3 + 3 (x - \alpha) y^2 - 3 ((x - \alpha)^2 - y^2) = 0. $$
These lines (called *Cartesian sheets*) are obtained from each other by parallel translations along the abscissa axis. Each line has a special point (self-intersection point). The discriminative curve in this case consists of three parallel lines: straight line $y = 0$ (the set of self-intersection points of all our lines) and straight lines $y = -k$ and $y = k$, where $k = \sqrt{2\sqrt{3} - 3}$ (envelopes). Through each point outside the strip $-k \leq y \leq k$ there passes one line of the family, through each point of the discriminant curve there are two, and through each point there are three.
