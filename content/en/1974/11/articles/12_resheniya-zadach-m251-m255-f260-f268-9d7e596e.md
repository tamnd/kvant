---
id: 1974-11-resheniya-zadach-m251-m255-f260-f268-9d7e596e
issue: kvant_1974_11
year: 1974
number: "11"
title: Solutions to problems M251—M255; F260—F268
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 52
page_labels: 42-50
tag: 4TC4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0ca2a46087a576fadccef26cdccbd3e322445cb4a37dda76cc84f9964d72e20d
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/12_resheniya-zadach-m251-m255-f260-f268-9d7e596e.md
source_content_sha256: a73af4a0205cffd82f96336d0c20b60abc6353742d8eb28a6eafaacff0dc3513
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Problem solutions
M251—M255; F260—F268

M251. Given n chips of several colors, with no more than n/2 chips of each color. Let us prove that they can be considered on a circle mak, so that no two chips of the same color are adjacent.

First solution: We will assume that if there are two chips of the same color next to each other, then they are connected by an arc. Then we need to prove that there is such an arrangement of chips on a circle in which there are no friends.

Let there be some arrangement of chips in a circle; Let us prove that the chips can be rearranged in such a way that the number in the new arrangement decreases.

In fact, let, for example, in an arrangement two black pieces are connected by an arc. Then he will definitely find two black chips on the circle, standing next to each other. Indeed, if next to each black chip there were black ones, and two more black ones stood next to each other, then there would be more than half of the black chips, and this contradicts the condition.

Let us now take one of the mentioned non-black chips and place it between two black ones. At the same time, the number of friends in the new arrangement will once again decrease. Since the number friend in the arrangement cannot be less than zero, then in the end we will get an arrangement of chips on a circle without friends.

Second solution. We will prove the statement of the problem by induction on the number k of different colors. When k=2, the statement is obvious: in this case there must be $\frac{n}{2}$ chips of each color, and they can be arranged in black order. If we have k=3 tokens of colors, say, red, black and green, we will act like this. Let's start placing those chips that are the most, for example red ones, one after another in odd places. When the red chips run out, we will continue to place black chips in odd places. It is clear that with chips of two colors we will exhaust all the odd spaces, put the rest of the black chips between the red ones, and put green chips on the free (even) spaces (Fig. 1).

If the number of chips is k≥4, then he will find two colors such that there will be no more than n/2 chips of these two colors. By repainting these tokens into one color, we obtain a set of tokens of (k-1) colors for which the induction hypothesis is satisfied. By arranging them around the circle so that the condition is met and returning to the original color, we obtain the desired arrangement of chips of k colors.

Third solution. Let's take n knights, give each a token, and declare two knights enemies if they have reached tokens of the same color, and friends if they have different ones. Then the conditions of problem M250, a; therefore, knights with chips can be placed around a round table.

V. L. Gutemacher

For the solution to problem M252, see the article by A. A. Egorov “Lattices and regular polygons”, which we will place in «Kvant» No. 12 for 1974.

M253. Three points are given on the plane, which are the corresponding centers of the inscribed, circumscribed and one of the outer circles of the triangle. How to reconstruct a triangle from this data?

(Recall that the outside circle of a triangle is called a circle tangent to one of the sides of the triangle and extended by the other two sides.)

Let us denote the vertices of the desired triangle by the letters A, B and C, and the centers of the circumscribed, inscribed and extruded circles by the letters O, O₁ and O₂, respectively (Fig. 2).

Note that the straight line O₁O₂ passing through the centers of the incircle and excircle is the bicector of angle A of triangle ABC, that is, the straight line O₁O₂ must pass through vertex A. Easy

⟦folio 43⟧

Fig. 2.
realize that $\Rightarrow O_1BO_2 = \Rightarrow O_1CO_2 = \pi/2$. Therefore, the points $B$ and $C$ lie on the circle $s$ with diameter $O_1O_2$; Let's denote the center of this circle (that is, the middle of the segment $O_1O_2$) by beech $S$. Since the point $O$ is the center of the circumscribed circle, it is located on the perpendicular passing through the middle of the segment $BC$. But the segment $BC$ is a chord of the circle $s$, so this perpendicular must pass through the center of the circle $s$, that is, through the point $S$.

So, if the points $O$ and $S$ do not coincide, then the line $OS$ is perpendicular to side $BC$ of the exclusion triangle and passes through its midpoint.

It remains to take advantage of the fact that the intersection point of the perpendicular passing through the middle of the side $BC$ and the bisecting angle $A$ (that is, the point $S$) is located on a circle circumscribed around the triangle $ABC$ (see Fig. 2). Therefore, we can construct a circle (with center $O$) from the description (its radius through the point $SO$). The second point of intersection of this circle with the line $O_1O_2$ is the vertex $A$ of the exclusion triangle. The points at which the circle intersects the circle $s$ is a constraint on the location of points $O$, $O_1, O_2$ is the only one.

L. G. Limanov

M254. Highest value $\sqrt{0,11111\ldots11111}$
with precision: $a) 100$ decimal places; $b) 101$ decimal places; $v) 200$ decimal places.

We present a solution that allows us to calculate this root with an accuracy of 301 decimal places.

Let's transform this number as follows:

$$\frac{1}{3} \sqrt{0,999\ldots999} = \frac{1}{3} \sqrt{1-10^{-100}}.$$

Then

$$\sqrt{1-10^{-100}} < 1 - 0,5 \cdot 10^{-100}.$$

Let us refine this estimate: find a positive number $a$ such that the inequality

$$\sqrt{1-10^{-100}} < 1 - 0,5 \cdot 10^{-100} - a \cdot 10^{-200}.$$

To do this, let’s square both sides of inequality (2):

$$1-10^{-100} < 1 + 0,25 \cdot 10^{-200} + a^2 \cdot 10^{-400} - 10^{-100} - 2a \cdot 10^{-200} + a \cdot 10^{-300};$$

simplifying, we get

$$0 < (0,25-2a) + a \cdot 10^{-100} + a^2 \cdot 10^{-200}.$$

For inequality (2) to hold, it suffices to take $a=0,125+10^{-102}$. Indeed, in this case the values ​​of $a$ and the expression $0,25-2a+a \cdot 10^{-100}$ are positive.

Thus, we arrive at the estimate:

$$\sqrt{1-10^{-100}} < 1 - 0,5 \cdot 10^{-100} - 0,125 \cdot 10^{-200} - 10^{-302}.$$

To evaluate the number $\sqrt{1-10^{-100}}$ first, choose the number $b$ so that the inequality holds

$$\sqrt{1-10^{-100}} > 1 - 0,5 \cdot 10^{-100} - b \cdot 10^{-200},$$

equivalent

$$0 > (0,25-2b) + b \cdot 10^{-100} + b^2 \cdot 10^{-200}.$$

For inequality (4) to hold, it suffices to set $b=0,125+10^{-101}$.

We get the following estimate:

$$\sqrt{1-10^{-100}} > 1 - 0,5 \cdot 10^{-100} - 0,125 \cdot 10^{-200} - 10^{-301}.$$

From estimates (3) and (5) it follows that

$$0,9\ldots949\ldots98 < \sqrt{1-10^{-100}} < 0,9\ldots949\ldots98$$

Until then we get

$$\sqrt{0,11\ldots11} = 0,33\ldots3166\ldots62499\ldots9\ldots,$$

and all 301 decimal places are correct.

A similar solution to this problem was sent by our reader S. Domoryad.

S. T. Bercolako

⟦folio 44⟧

Fig. 3. Cloud spheres filled with light are those from which you can draw a tangent to another sphere.

M255. AB and CD are different tangents to two given balls (A and C belong to the surfaces of the same ball, B and D belong to others). Prove that the projections of the segments AC and BD onto the line passing through the centers of the balls are equal.

Let $O_1$ and $O_2$ be the centers of the balls, $|O_1A| = |O_1C| = r_1$ and $|O_2B| = |O_2D| = r_2$ their radii, $|O_1O_2| = d$, $|AB| = l$, $|CD| = m$, $\Rightarrow AO_1O_2 = \varphi$, $\Rightarrow CO_1O_2 = \psi$.

Then the length of the projected segment AC onto the straight line $O_1O_2$ is equal to
$$\|AO_1\| \cos \varphi - |CO_1| \cos \psi| = |r_1 \cos \varphi - r_1 \cos \varphi|.$$ (1)

By the cosine theorem for $\triangle AO_1O_2$ (Fig. 3)
$$|AO_2|^2 = r_1^2 + d^2 - 2r_1 d \cos \varphi.$$ (2)

Since the angle $ABO_2$ (between the tangent and the radius) is right,
$$|AO_2|^2 = |AB|^2 + |B_2O|^2 = l^2 + r_2^2.$$ (3)

From (2) and (3) we obtain
$$2dr_1 \cos \varphi = r_1^2 + d^2 - r_2^2 - l^2.$$ (4)

Similarly find
$$2dr_1 \cos \psi = r_1^2 + d^2 - r_2^2 - m^2.$$ (5)

From (1), (4) and (5) it follows that the projection of the segment AC onto $O_1O_2$ has length
$$\frac{|l^2 - m^2|}{2d}.$$

It is clear that the projected segment BD has the same length.

Let us present another solution to this problem, which reveals its geometric background more clearly. The plane analogue of problem M255 (Fig. 4) suggests that the tangents should be located so that their midpoints project to the same point on the line $O_1O_2$, that is, that all the midpoints of the tangents to two given balls should lie in the same plane, perpendicular to the line of cents. We will prove a more general statement.

Fig. 4. The projections of the segments AC and BD onto the line centers are the same if the midpoints AB and CD are projected into the same point P.

Theorem. All points M, the tangents of which to two given balls have the same length, lie in the same plane, perpendicular to the line of cents $O_1O_2$ and intersecting $O_1O_2$ at the highest point P, for which
$$|PO_1|^2 - |PO_2|^2 = r_1^2 - r_2^2.$$ (6)

Note that the last equality determines the position of the point P on the line $O_1O_2$ uniquely: if on the line $O_1O_2$ we choose a coordinate system so that the points $O_1$ and $O_2$ receive coordinates 0 and d, then the x coordinate of the point P is uniquely determined from the equation $x^2 - (x - d)^2 = r_1^2 - r_2^2$:
$$x = \frac{r_1^2 - r_2^2 + d^2}{2d}.$$

Now let's prove the theorem. The most remarkable thing here is that we can immediately go to the plane problem: after all, from point M to each ball we can draw many—a whole “cone”—tangents, very indo, equal in length, and we can always choose those of them that lie in the plane $MO_1O_2$ (Fig. 5). In this Fig. 5. The lengths of all tangents drawn from point M to each ball are the same.

⟦folio 45⟧

Fig. 6. The difference in the squares of distances from $M$ to the centers of the circles of constant. Therefore, the point $M$ belongs to a certain straight line, perpendicular to the line of centers (the radical axis of two circles).

the plane (Fig. 6) also contains the projection $M'$ of the point $M$ onto the line $O_1O_2$.

From the equality of tangent lengths

$$\sqrt{|MO_1|^2 - r_1^2} = \sqrt{|MO_2|^2 - r_2^2}$$

it follows that

$$|MO_1|^2 - |MO_2|^2 = r_1^2 - r_2^2.$$

Using the fact that the triangles $MM'O_1$ and $MM'O_2$ are rectangular, we obtain

$$|M'O_1|^2 - |M'O_2|^2 = r_1^2 - r_2^2,$$

that is, for the point $M'$ the same equality (6) is satisfied as for the point $P$; as we already said, in this case $M'$ must match $P$. Thus, the point $M$ lies in the plane perpendicular to the line of centers and passing through the point $P$, defined by equality (6) (this plane is called the radical plane of the two given spheres). The theorem has been proven.

I. F. Sharytsin, N. B. Vasiliev

To the solution problem M218. In «Kvant» No. 4 for this year, we offered readers a summary of problem M218. The editors have received several letters. The most complete solution was sent by V. L. Rabinovich.

Let us recall the formulation of the problem, give the answer and indicate the main idea of ​​the solution.

Task. At what most $c_n$ for any positive $x_1, \dots, x_n$ the inequality is true

$$(x_1 + x_2 + \dots + x_n)^2 \geq c_n (x_1 x_2 + x_2 x_3 + \dots + x_n x_1))?$$

Answer: $c_2 = 2, c_3 = 3, c_n = 4$ for $n \geq 4$, while in the case of $n = 2, 3, 4$ the inequality is true for any $x_1, \dots, x_n$.

Let us prove that the inequality

$$(x_1 + x_2 + \dots + x_n)^2 \geq 4 (x_1 x_2 + x_2 x_3 + \dots + x_n x_1))$$

(2)

true for positive $x_1, x_2, \dots, x_n$ at $n \geq 4$.

For $n = 4$, inequality (2) is true for any $x_1, x_2, x_3, x_4$. In fact,

$$(x_1 + x_2 + x_3 + x_4)^2 - 4 (x_1 x_2 + x_2 x_3 + x_3 x_4 + x_4 x_1) = ((x_1 + x_3) + (x_2 + x_4))^2 - 4 (x_1 + x_3) \times (x_2 + x_4) = (x_1 - x_2 + x_3 - x_4)^2 \geq 0.$$

Let us prove that if inequality (2) is true for $n$ positive numbers, then it is also true for $(n + 1)$ positive numbers.

We can assume that $x_{n+1}$ is the smallest of $x_1, x_2, \dots, x_{n+1}$. Then

$$(2x_1 - x_{n+1}) (2x_n - x_{n+1}) \geq 0.$$

Adding this inequality to (2), we get

$$(x_1 + x_2 + \dots + x_n)^2 + x_{n+1}^2 + 4x_1 x_n - 2x_1 x_{n+1} - 2x_{n+1} x_n \geq 4 (x_1 x_2 + x_2 x_3 + \dots + x_{n-1} x_n + x_n x_1),$$

where

$$(x_1 + x_2 + \dots + x_n)^2 + 2x_{n+1} (x_1 + x_n) + x_{n+1}^2 \geq 4 (x_1 x_2 + \dots + x_{n-1} x_n + x_n x_1) - 4x_1 x_n + 4x_n x_{n+1} + 4x_{n+1} x_1 = 4 (x_1 x_2 + \dots + x_n x_{n+1} + x_{n+1} x_1),$$

especially

$$(x_1 + x_2 + \dots + x_{n+1})^2 = (x_1 + \dots + x_n)^2 + 2x_{n+1} (x_1 + x_2 + \dots + x_n) + \dots + x_n) + x_{n+1}^2 > 4 (x_1 x_2 + \dots + x_n x_{n+1} + x_{n+1} x_1).$$

V. L. Gutemacher

F260. Direct angular directions of magnitude $U_0$ and diameter $T$ are supplied to the input of the circuit (Fig. 7, a). The period of pulse rotation is $T$ (Fig. 7, b). The name of the drawing is very many periods of direction on the capacitor, if during the period the direction on the capacitor changes very little.

When equilibrium is established in the circuit, the direction, and therefore the charge on the capacitor, will not change. That is, an increase

⟦folio 46⟧

Fig. 8.

charge when charging will be equal to decrease in charge when charging.
When charging a capacitor during time τ, the direction on it is equal to
$$U_C = U_0 - I_3 r.$$
Since the charge on the capacitor changes very little over the period, we can consider the charging current constant and equal to
$$I_3 = \frac{\Delta q}{\tau},$$
where $\Delta q$ is the change in charge. Thus,
$$U_C = U_0 - \frac{\Delta q}{\tau} r.$$ (1)

When charging, the capacitor discharges through resistance $R$ during time $T - \tau$, so $U_C = I_p R$, where is the charging current
$$I_p = \frac{\Delta q}{T - \tau}.$$
Therefore, while charging
$$U_C = \frac{\Delta q}{T - \tau} R.$$ (2)

Solving (1) and (2) together, we obtain
$$U_C = U_0 \frac{R\tau}{(R - r)\tau + rT}.$$

F261. We float at the interface between two liquids with different densities, so we dive into the lower liquid to a depth of $h$, a molstomic relish with a thin diom. The relish is filled to the top with the top liquid. The outer radius of the savor is $R$, the inner radius is $r$. In the bottom of the relish, the depth of friendship of the relish appears after it is possible to move the liquid together into it?

Let us write down the equilibrium condition of the glass in the first case (Fig. 8, a):
$$mg + m_1 g = F_{B1}.$$
Here $m$ is the mass of the glass, $m_1 = \rho_1 \pi r^2 l$ is the mass of the liquid inside the glass ($l$ is the height of the glass), $F_{B1}$ is the buoyant force.

Fig. 9.

If a body floats on the interface between two liquids so that in the first liquid there is a part of the body with a volume of $V_1$, and in the second - $V_2$, then a buoyancy force equal to
$$F_B = \rho_1 g V_1 + \rho_2 g V_2.$$
Indeed, you can mentally divide the body into two parts along the interface between the liquids and consider each part separately. This, of course, does not change the position of the body or the forces acting on it. Thus,
$$F_{B1} = \rho_1 g \pi R^2 (l - h) + \rho_2 g \pi R^2 h.$$
Then the equilibrium condition is written as follows:
$$mg + \rho_1 g \pi r^2 l = \rho_1 g \pi R^2 (l - h) + \rho_2 g \pi R^2 h.$$ (1)

When a hole appears in the bottom of the glass, the bottom liquid will flow into the glass, displacing the top liquid. This will happen until the level of the liquid boundary coincides with the level of the liquid boundary in the glasses (Fig. 8, 6). And in this case, the stack will be in equilibrium, so we can write an equality similar to equality (1):
$$mg + \rho_1 g \pi r^2 (l - x) + \rho_2 g \pi r^2 x = \rho_1 g \pi R^2 (l - x) + \rho_2 g \pi R^2 x.$$ (2)

From (1) and (2) we find
$$x = h \frac{R^2}{R^2 - r^2}.$$

We found that the answer does not depend on the mass of the glass or on the densities of the liquids. This may come as a surprise. After all, the glass is heavy, and the upper medium, for example, is possible, it is clear that after the hole appears, the glass will sink. However, the answer to the problem is correct. The fact is that when solving, we routinely assumed that $h < l$ and $x < l$ (with $h \geq l$ or $x \geq l$ the glass will sink). These conditions, together with equalities (1) and (2), make it possible to find the relationship between the density of the glass materials and the densities of liquids at which equilibrium of the glass is possible in both the first and second cases.

F262. A thin-walled cylindrical glass with a thin bottom, closed with weightless material

⟦folio 47⟧

Fig. 10.

thin piston. There is a spring between the piston and the bottom of the glass. Inside the glass there is air at atmospheric pressure $p_0$. The glass floats in water, as shown in figure 9, and the distance from the surface of the water to the piston is $l_1$, the depth of the glass is $l_2$. Piston area $S$, spring stiffness $k$, water density $ρ$. What is the maximum depth to which a glass can be placed under water so that it can still float up? Neglect the volume of the spring.

At the initial moment, the glass floats on the surface of the water. This means that the gravity force acting on it is balanced by the buoyant Archimedean force:

$$mg = \rho g l_2 S.$$

When the glass is immersed at first, the buoyant force will increase. But when the piston reaches the water level, the force of water pressure begins to stir the piston down to the bottom of the glass. In this case, the volume of the glass, and therefore the buoyant force, will decrease. Obviously, the maximum immersion depth of the glass is the depth at which the buoyant force, as at the initial moment, is equal to the force of gravity acting on the glass:

$$mg = \rho g x S.$$

Here $x$ is the height of the piston from the bottom of the glass (Fig. 9, b). Moreover, from (1) and (2)

$$x = l_2.$$

On the other hand, the value $x$ is related to the immersion depth of the glass $h$. Let us write down the equilibrium condition for the piston. It is acted on from above by the force of atmospheric pressure $p_0 S$ and the force of hydrostatic pressure $\rho g (h - x) S$, and from below by the elastic force of the spring $k \Delta x = k (l_1 + l_2 - x)$ and the force of air pressure in the glass $p S$. It is natural to assume that the air temperature under the piston does not change (it is equal to the water temperature), therefore, from the Boyle-Mariotte law

$$p_0 (l_1 + l_2) = px,$$

where

$$p = p_0 \frac{l_1 + l_2}{x}.$$

Fig. 11.

Thus, we can write

$$p_0 S + \rho g (h - x) S =$$

$$= k (l_1 + l_2 - x) + \frac{p_0 (l_1 + l_2) S}{x}.$$

Substituting $x = l_2$ here, we get:

$$p_0 S + \rho g (h - l_2) S = k l_1 + p_0 S \left( \frac{l_1}{l_2} + 1 \right),$$

where

$$h = \frac{p_0 S l_1 + k l_1 l_2 + \rho g l_2^2 S}{\rho g S_2}.$$

F263. Frosted glass (one of the surfaces is smooth, the other is polished) is applied to the drawing: once with the smooth surface up, the other time down. In one case the good one is visible, in the other it is impossible to make out. Why?

The rough surface of the flow scatters the light falling on it evenly in all directions. If the glass lies on a drawing of a smooth surface (Fig. 10, a), then rays coming from both the lines of the drawing and from clean places reach each point of the rough surface of the glass. Light fluxes coming from such different parts of the drawing are then scattered in all directions equally, and from each part of the drawing rays coming from both the lines of the drawing and from clean places enter the eye. Therefore, different areas of the flow appear equally bright, and the drawing cannot be made out.

If the glass is facing the drawing of the matte surface (Fig. 10, b), then the matte surface turns out to be unevenly illuminated. Rays coming from different points on the surface enter the eye without intersecting, and the drawing is easy to make out.

F264. Two identical round flat metal plates, arranged as shown in figure 11, are treated at an angle

⟦folio 48⟧

howl speed $\omega$ in opposite directions in the maximum field, perepredular to the planes of the plates. The maximum field induction is $B$, the distance between the plates is $a$. The axes of the plates are connected by a wire. The most muscular distribution of charge density on the plates.

The rotating plates form a flat capacitor with an uneven charge distribution along the plates. If you select sections of plates with area $S$ that are identically located opposite each other, then it is not difficult to find the capacitance of the capacitor that these sections form. It is equal to $C = \frac{\varepsilon_0 S}{a}$. Since the charge of such a capacitor is equal to $Q=CU$, where $U$ is the potential difference between the sections, it is clear that we can easily determine the charge density in the section $\sigma = \frac{Q}{S} = \frac{CU}{S} = \frac{\varepsilon_0 U}{a}$ if we can calculate $U$. Let's try to do this.

The charge $q$, which is located at a distance $x$ from the center of the plates, is acted upon by two forces: the Lorentz force $F_\pi = qvB = q\omega xB$ and the force $F_\alpha = qE$ from the electric field, which arises in the plate due to the uneven distribution of charges over the disk. The resultant forces $F_\pi$ and $F_\alpha$ create a centripetal acceleration $a = \omega^2 x$ for the charge. Therefore, according to Newton's II law

$$F_\pi + F_\alpha = ma.$$ (1)

Since the disks rotate in different directions, the Lorentz force acting on charges that are located at the same distance from the centers of the disks is directed in different directions in different disks. Therefore, if for the first disk

$$qE - q\omega xB = m\omega^2 x,$$ (2)

then for the second disk

$$qE + q\omega xB = m\omega^2 x^*).$$ (3)

From these equilibrium conditions we find the direction of the field at distances $x$ from the centers of the disks. They are equal to $(\omega B + \frac{m}{q}\omega^2)x$ in the first disk and $(\omega^2 \frac{m}{q} - \omega B)x$ in the second. IN

*) The directions of forces $F_\alpha$ in disks depend on the magnitude of $\omega$. If $\omega$ is small, so $m\omega^2 x < q\omega xB$, then the directions of the forces $F_\alpha$ in the disks are opposite, if $m\omega^2 x > q\omega xB$, then the forces $F_\alpha$ in different disks are directed in the same direction. This can be seen from equations (2) and (3).

Fig. 12.

⟦folio 49⟧

Fig. 13.

directed to the right, that is, in the direction opposite to the possibility of moving the boy relative to the sled.

The boy does not move vertically, but we will consider his horizontal movement together with the sled to be uniform. Then we can write the following equalities:

$$T \sin \alpha + N - Mg = 0,$$
$$T \cos \alpha - F_{TP} = 0,$$

where $F_{TP} = k_1 N$ ($k_1$ is the friction coefficient of the boy on the sled).

From here

$$k_1 = \frac{T \cos \alpha}{Mg - T \sin \alpha}.$$

We will find the tension force of the rope $T$, the distance of movement of the entire system boy - sled as a whole (Fig. 13, b). For the vertical direction we can write:

$$T \sin \alpha + N_1 - (M + m)g = 0,$$
$$T + T \cos \alpha - F_{TP_1} = 0.$$

Here $N_1$ is the support reaction force, $F_{TP_1} = k N_1$ is the friction force of the sled on the snow. From these equalities

$$T = \frac{k (M + m) g}{1 + \cos \alpha + k \sin \alpha}.$$

Then finally

$$k_1 = \frac{T \cos \alpha}{Mg - T \sin \alpha} = \frac{k (M + m) \cos \alpha}{M (1 + \cos \alpha) - km \sin \alpha}.$$

F266. The U-shaped wheelhouse moves at a constant speed $v$ parallel to the surface of the liquid (Fig. 14). The cross-section of the lower part of the cabin, lowered into the water, is $S_1$, and the upper part, located above the water, is $S_2$. What force is applied to the chopping block? Liquid density $ρ$. Friction and wave formation on the surface of the liquid claim.

It is convenient to solve the problem in a coordinate system associated with the tube. In this system, the liquid at the bottom of the tube moves with speed $v$.

During time $\Delta t$, a volume of water $V = S_1 v \Delta t$ with mass $m = \rho S_1 v \Delta t$ enters the tube. The momentum of this water is

$$mv = \rho S_1 v^2 \Delta t.$$

Since the liquid does not accumulate in the tube, during time $\Delta t$ the same mass of liquid flows out of the upper tube. But the speed $u$ of the flowing liquid is already different. Since the volume of liquid entering the tube is equal to the volume of liquid flowing out of the tube, then

$$S_1 v = S_2 u.$$

From here

$$u = v \frac{S_1}{S_2},$$

and the momentum of water flowing out of the tube is equal in absolute value

$$mu = \rho S_2 u^2 \Delta t = \rho v^2 \frac{S_1^2}{S_2} \Delta t,$$

a is directed in the direction opposite to the direction of the impulse of the flowing water.

Thus, during time $\Delta t$ the momentum of water in the tube changes by the following values:

$$\Delta (mv) = mv - (-mu) = \rho S_1 \left( \frac{S_1}{S_2} + 1 \right) v^2 \Delta t.$$

According to Newton's second law, the force acting on the water in the tube is

$$F = \frac{\Delta (mv)}{\Delta t} = \rho S_1 \left( \frac{S_1}{S_2} + 1 \right) v^2.$$

Fig. 14.

⟦folio 50⟧

A force of the same absolute magnitude, but directed in the other direction (according to Newton’s third law), acts on the tube from the liquid side.

F267. A spherical spacecraft moves around the Sun in a circular orbit. What is the temperature of the ship if the energy emitted per unit horse from the surface of the Sun and the ship is proportional to the temperature of their absolute temperatures? The astronauts who are on the ship see the Sun at an angle of 30°. The surface temperature of the Sun is taken to be 6000° K.

In thermal equilibrium, when the temperature of the ship does not change, the energy received by the ship per unit time from the Sun is equal to the energy emitted by the ship itself in the surrounding space in the same unit of time:

$$W_{\text{изл}} = W_{\text{полл}}.$$

The energy emitted by a ship is proportional to the surface area of ​​the ship $S_K = 4\pi R_K^2$ ($R_K$ is the radius of the ship) and the fourth power of temperature $T_K$ and is equal to

$$W_{\text{изл}} = k S_K T_K^4 = 4k\pi R_K^2 T_K^4,$$

where $k$ is the proportionality coefficient, the same for both the ship and the Sun.

Now determines the energy the ship receives from the Sun. Energy equal to $k T_K^4$ is emitted per unit surface of the Sun; all the sun emits energy

$$W_c = 4k\pi R_c^2 T_c^4,$$

spreading evenly in all directions.

At a distance of $l$ from the Sun, where the spacecraft is located, this energy passes through a sphere with surface area

$$S = 4\pi l^2.$$

Energy equal to $\frac{W_c}{S}$ passes through a unit surface area of ​​this sphere. The cross-sectional area of ​​the ship is $\pi R_K^2$, so energy enters the ship

$$W_{\text{полл}} = \frac{W_c}{S} \pi R_K^2 = \frac{W_c}{4\pi l^2} \pi R_K^2 = k \frac{\pi R_c^2 R_K^2}{l^2} T_c^4.$$

Since Cosmians see the Sun at angle $\alpha = 30^\circ$ and this angle is small, then

$$\frac{\alpha}{2} = \frac{R_c}{l}$$

And

$$W_{\text{полл}} = \frac{k\pi R_K^2 \alpha^2 T_c^4}{4}.$$

So, the equality of the energy emitted and absorbed by the ship will be written as follows:

$$4k\pi R_K^2 T_K^4 = \frac{k\pi R_K^2 \alpha^2 T_c^4}{4}.$$

From here

$$T_K = \frac{T_c}{2} \sqrt{\alpha} \approx 270^\circ \text{K}.$$

We found that the temperature of the ship does not depend on its radius and is determined only by the angle $\alpha$ at which the Sun is visible. This angle is equal to the angle at which the Sun is visible from Earth. Therefore, the temperature of the spaceship turns out to be of the same order of magnitude as the temperature of the Girant “spaceship” - the Earth.

F268. To determine the relative temperature of the gas at a constant volume and at constant pressure and supply temperature, it is necessary to determine the amount of gas, the initial temperature, volume and pressure of which are equal to the corresponding $T_0$, $V_0$ and $p_0$, is heated with a flame wiring through which an electric valve passes for a certain time, once at a constant volume $V_0$, and the gas reaches pressure $p_1$, another time at constant pressure $p_0$, and the gas object becomes equal to $V_1$. Show that $\frac{c_p}{c_V} = \frac{(p_1 - p_0) V_0}{(V_1 - V_0) p_0}$.

Since the wiring is heated by the same current for the same time, the gas in both cases produces the same amount of heat.

If a gas is heated at constant volume, then the amount of heat received by the gas is equal to

$$Q = c_V m(T - T_0).$$

Let us write the equation of state of the gas:

$$p_0 V_0 = nRT_0$$

And

$$p_1 V_0 = nRT.$$

Here $n$ is the number of moles of gas, $T$ is the gas temperature at pressure $p_1$.

From here

$$T - T_0 = \frac{V_0 (p_1 - p_0)}{n},$$

And

$$Q = c_V m \frac{V_0 (p_1 - p_0)}{n}.$$

(1)
