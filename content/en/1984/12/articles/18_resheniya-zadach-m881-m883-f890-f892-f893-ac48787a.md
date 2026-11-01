---
id: 1984-12-resheniya-zadach-m881-m883-f890-f892-f893-ac48787a
issue: kvant_1984_12
year: 1984
number: "12"
title: Solutions to problems M881—M883; F890, F892, F893
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 41
page_labels: 36-39
tag: 278G
lang: en
source: kvant_digital
extraction: vision
content_sha256: f3d2ba488e496920814ba852345cf430e0f5138659fdf056f0ff1f0a1beb24ce
prompt_sha256: draft-1
translated_from: content/ru/1984/12/articles/18_resheniya-zadach-m881-m883-f890-f892-f893-ac48787a.md
source_content_sha256: 261714ddfdb2478d64f98eddebde3ceb04e56035224b61a4fc3b10a728ae4b1f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

Problem solutions

M881. Prove that the sum of the distances from an arbitrary point in the plane to three vertices of an isosceles trapezoid is greater than the distance from this point to four vertices.

Fig. 1.

Fig. 2.

M882. The sum of three integers a, b and c is 0. Prove that the number $2a^4 + 2b^4 + 2c^4$ is the square of an integer.

M883. What is the smallest number of colors that must be used to color the cells of an infinite sheet of checkered paper so that a) any two cells at a distance b are covered in different colors? (The distance between squares is the smallest number of grid lines, horizontal and vertical, that a rook must cross on its way from one square to another.) b) any four squares forming a Γ (Fig. 1) figure were covered in four different colors?

Fig. 1.

Fig. 2.

Fig. 3.

Let, for the purpose of definition, $MA$ be the largest of the distances from the point $M$ to the vertices of the equilateral trapezoid $ABCD$ (Fig. 1). By the triangle inequality $MA \leq AC + MC$ and $BD \leq MB + MD$, and for any point $M$ of the plane at least one of these inequalities is true. Adding the inequalities and learning that $AC = BD$, we get $MA \leq MB + MC + MD$.

This solution has a red geometric interpretation: by applying triangles $AMC$ and $BMD$ to each other so that their equal sides $AC$ and $BD$ are aligned, we obtain a quadrilateral (Fig. 2); the statement of the problem will coincide with the fact that each of its sides is smaller than the others (this statement is also true in cases where one or both triangles $AMC$, $BMD$ degenerate into segments).

S. E. Rukin

◆ Using the condition $a + b + c = 0$, we obtain that $a^4 + b^4 + c^4 = a^2(b + c)^2 + b^2(c + a)^2 + c^2(a + b)^2 = 2(a^2b^2 + b^2c^2 + c^2a^2) + 2abc(a + b + c) = (a^2 + b^2 + c^2)^2 - a^4 - b^4 - c^4$, whence $2a^4 + 2b^4 + 2c^4 = (a^2 + b^2 + c^2)^2$.

L. D. Kurlyandchik, S. V. Fomin

◆ a) Answer: 4 colors. An example of coloring a checkered plane in 4 colors, in which any two cells at a distance b are given different colors, is presented in figure 2.

To prove that it is impossible to get by with fewer colors, it is enough to consider the 4 cells shown in figure 3. Any two of them are located at a distance of 6 from each other and, therefore, they should all be in different colors.

b) Answer: 8 colors. The proof scheme repeats point a): we need to give an example of an 8-color

*) For the solution problem F891, see the note “Electrical capacity is a property of a conductor” on p. 40.

⟦folio 37⟧

coloring book (shown in figure 4) and explain why seven colors are not enough.

Consider a 7-cell figure on figure 5,a. Any two of its cells can be covered with one “letter Γ” of four cells, so all its cells must be multi-colored. Therefore, in the figure at figure 5,6 cells marked with asterisks, with a 7-color coloring, should be the same color (because the remaining 6 cells need to be painted in 6 different colors). Then, very indo, in any infinite lattice with a step of 3 cells (Fig. 6) all cells should be colored with one color, and the remaining cells of the plane with other colors. But in this case, you will need not 7, but 9 colors (according to the number of such lattices covering the plane).

A. G. Pechkovsky, I. V. Itenberg

F890. Iron crystals at temperatures up to 910 °C consist of elematrine cells having the shape of a cube with an edge length of $a_1=2,87 \cdot 10^{-10}$ m. The iron cells are located at the vertices of the cube and in its center (Fig. 1). This type of element - with a volumetric cubic lattice - is called alpha iron ($Fe_a$). At temperatures above 910 °C, the cells of an iron crystal are a bordered cube with an edge length of $a_2=3,63 \cdot 10^{-10}$ m. The cells are located at the vertices of the cube and at the centers of its faces (Fig. 2). This type of element is called gamma iron ($Fe_\gamma$). However, what is the density of iron in these states? The relative atomic mass of iron is $μ=55,847$.

Let's first determine how many atoms of the element there are in each cube cell. If you mentally cut out one elementary cube, then each vertex will contain 1/8 atoms (each vertex is common to 8 cups). There are 8 such vertices. Therefore, per cube cell $Fe_a$ there are $\frac{1}{8} \cdot 8+1=2$ atoms (taking into account the central atoms).

There are $\frac{1}{8} \cdot 8+\frac{1}{2} \cdot 6=4$ atoms per elementary cell $Fe_\gamma$, since there are $\frac{1}{2}$ atoms for each occurrence, and there are 6 faces.

The volume of $V_a=(2,87 \cdot 10^{-10})^3 \text{ m}^3 \approx 23,64 \cdot 10^{-30} \text{ m}^3,$ per alpha-iron cell per gamma-iron cell is $V_\gamma=(3,63 \cdot 10^{-10})^3 \text{ m}^3 \approx 47,83 \cdot 10^{-30} \text{ m}^3.$

Mass of one atoms of iron—

Fig. 1. Fig. 2.

⟦folio 38⟧

$$m = \frac{55,847 \cdot 10^{-3}}{6,02 \cdot 10^{23}} \text{ кг} \approx 9,28 \cdot 10^{-26} \text{ кг}$$

(6.02·10²³ mol⁻¹ is Avogadro’s constant). Thus, the densities of Fe₄ and Fe₇ are equal, respectively,

$$\varrho_a = \frac{2m}{V_a} \approx \frac{2 \cdot 9,28 \cdot 10^{-26}}{23,64 \cdot 10^{-30}} \text{ кг/м}^3 \approx 7850 \text{ кг/м}^3,$$

$$\varrho_\gamma = \frac{4m}{V_\gamma} \approx \frac{4 \cdot 9,28 \cdot 10^{-26}}{47,83 \cdot 10^{-30}} \text{ кг/м}^3 \approx 7760 \text{ кг/м}^3,$$

and $\varrho_a > \varrho_\gamma$.

I. M. Nizamov

F892. A ray of light directed along the radius falls on a glass ball of radius R. At a distance r from the center of the ball, light is scattered evenly in all directions on a small air bubble formed during the manufacture of the ball. Determine the dependence of the fraction of light emerging from the ball on r. Stack refractive index n. Neglect light losses in the glass.

Fig. 1.

Fig. 2.

As a result of scattering by the bubble, the beam deviates by an angle β from its initial direction and falls on the glass-air interface at an angle α (Fig. 1). If it turns out that $\sin \alpha > \frac{1}{n}$, then total internal reflection will occur at the boundary. The second time the beam falls on the glass-air boundary again at an angle α, total internal reflection will occur again, etc. Thus, the beam that has experienced total internal reflection at the glass-air boundary after scattering will not leave the ball. Let us find at what values ​​of the deviation angle β this occurs.

According to the sine theorem (see Fig. 1),

$$\frac{r}{\sin \alpha} = \frac{R}{\sin \beta}.$$

Substituting sin α, we find:

$$\beta_1 = \arcsin \left( \frac{R}{rn} \right),$$

(1)

$$\beta_2 = \pi - \arcsin \left( \frac{R}{rn} \right).$$

Total internal reflection of a beam that has experienced everything and is deflected when scattered through angles β that satisfy the conditions

$$\beta_1 < \beta < \beta_2.$$

All other beams leave the ball after scattering.

Since the beam is scattered uniformly on the bubble in all directions, the fraction η of light emerging from the ball is equal to the ratio of the areas of two spherical segments (at figure 2 they are shaded) to the total area of ​​the sphere of originating radius, the center of which coincides with the center of the bubble:

$$\eta = \frac{2 \cdot 2 \pi \rho h}{4 \pi \varrho^2} = \frac{h}{\varrho}.$$

As can be seen from figure 2,

$$h = \varrho (1 - \cos \beta) = \varrho (1 - \sqrt{1 - \sin^2 \beta}) = \varrho \left(1 - \sqrt{1 - \left(\frac{R}{rn}\right)^2}\right).$$

Thus,

$$\eta = 1 - \sqrt{1 - \frac{1}{r^2} \left(\frac{R}{rn}\right)^2}.$$

⟦folio 39⟧

At $r < \frac{R}{n}$, expressions (1) - (3) lose their meaning - in this case, none of the rays scattered by the bubble experiences total internal reflection, and all the light comes out of the ball.

A. A. LanUDEC

At the initial moment of time, the vector $\vec{v}$ of the ball’s velocity is directed vertically. Since the wind speed near the Earth's surface is zero, the speed of the ball at low altitudes of rise (and at small $\alpha(t)$) is constant and equal to $\vec{v}$. Consequently, for small $\alpha$ depends $\alpha(t)$ is determined by the correspondence

$$\text{tg} \alpha(t) \approx \alpha(t) \approx \frac{v t}{L}.$$

Let the elevation angle change by $\Delta \alpha$ over a short period of time $\Delta t$. From (1) it follows that $\Delta \alpha/\Delta t = v/L$, whence

$$v = L \frac{\Delta \alpha}{\Delta t}.$$

The relationship $\Delta \alpha/\Delta t$ can be found from the graph of the relationship $\alpha(t)$. It is determined by the slope of the tangent to the curve $\alpha(t)$ at point $\alpha=0$ (see Fig. 1). Expressing $\alpha$ in radians, we find the value $\Delta \alpha/\Delta t$ from the graph and, substituting it in (2), we find the speed of the charazonde at small $\alpha$:

$$v = 10^3 \frac{50 \cdot 2\pi}{360 \cdot 3 \cdot 60} \text{ m/c} \approx 4,85 \text{ m/c}.$$

(The accuracy of determining $v$ depends on the accuracy of constructing the tangent. For a given scale on figure 1, the values ​​of $v$ lie within $4,8 \div 5,0 \text{ m/c.})$

In time $t_1=7$ min=420 s the ball rises to a height

$$h = v t_1 \approx 2000 \text{ m}.$$

As can be seen from figure 1, at this moment $\alpha(t)$ reaches its maximum value. This means that at height $h$ the ball’s velocity vector is directed along the line of sight drawn from the observation point. Therefore, the angle of inclination of the vector $\vec{v}_h$ to the horizon is equal to $\alpha(t_1)=60^\circ$. The vertical projection $\vec{v}_h$ is equal to $v=4,85 \text{ m/c}$, and the horizontal projection is the wind speed $u_h$ at height $h$. Means,

$$u_h = v \text{ ctg} 60^\circ \approx \frac{4,85}{\sqrt{3}} \text{ m/c} \approx 2,8 \text{ m/c}.$$

V. V. Mozhaev
