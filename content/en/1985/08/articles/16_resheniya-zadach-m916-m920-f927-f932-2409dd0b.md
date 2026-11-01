---
id: 1985-8-resheniya-zadach-m916-m920-f927-f932-2409dd0b
issue: kvant_1985_8
year: 1985
number: "8"
title: Solutions to problems M916—M920; F927—F932
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 45
page_last: 51
page_labels: 43, 44, 46, 47, 48, 49
tag: YUI4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 943af50c4acf636836357325a2f4ff70ba26dee36e0fc13a43ff8f923aec631e
prompt_sha256: draft-1
translated_from: content/ru/1985/08/articles/16_resheniya-zadach-m916-m920-f927-f932-2409dd0b.md
source_content_sha256: ceaa6348137e5e7516c2e4b79502320f81b64c5bc330c437bbccbfc51a4c391a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

Problem solutions
M916 — M920; F927 — F932

M916. From the middle of each side of an acute triangle, perpendiculars are dropped to the other two sides. Prove that the area of ​​a bounded or hexagon is equal to half the area of ​​a triangle.

Let us denote the vertices of this triangle by $A, B, C$, the midpoints of its sides by $A_1, B_1, C_1$, and the other three vertices of the hexagon considered in the task by $A_2, B_2, C_2$ (see figure). Note that the segments connecting the center $O$ of the circumcircle of the triangle $ABC$ with the midpoints of its sides divide our hexagon into three parallelograms $OA_1C_2B_1, OB_1A_2C_1$ and $OC_1B_2A_1$ (the segments $OA_1$ and $B_1C_2$ are parallel, since both of them were redistributed to the side $BC$; similarly $OB_1 \parallel A_1C_2$, etc.). It follows that triangles $A_1B_1C_2, B_1C_1A_2$ and $C_1A_1B_2$ are respectively equal to triangles $A_1B_1O, B_1C_1O$ and $C_1A_1O$, which means that the area of ​​the hexagon is twice the area of ​​triangle $A_1B_1C_1$, obviously equal to a quarter of the area of ​​the original triangle.

Another proof is based on the fact that the three altitudes of the triangle intersect at one point: $A_2, B_2$ and $C_2$ are the points of intersection of the altitudes of equal triangles $AB_1C_1, C_1A_1B_1$ and $B_1CA_1$, hence $\triangle A_2B_1C_1 = \triangle C_2CA_1$, $\triangle B_2A_1C_1 = \triangle C_2CB_1$, therefore, our triangle is equal in size to the parallelogram $C_1A_1CB_1$.

Note that in the case of an obtuse triangle, a similar construction leads to a self-intersecting hexagonal broken line, for which the statement will remain valid, considering the so-called “oriented area” (see the article by A.L. Toom “How many areas does a polygon have?” in «Kvant» No. 12 for 1984).

A. A. Azamov

M917. a) What is the length of the maximum series of consecutive bad tickets? b) How many such series of maximum length are there? (Ticket numbers are considered to range from 000000 to 999999 inclusive; a ticket is called lucky if the sum of the first three digits of its number is equal to the sum of the last three digits.) a) Answer: 1000. Any ticket number is between two lucky numbers equal to $1000N + N$ and $1000(N + 1) + (N + 1)$ (N and N + 1 are three-digit numbers), in which the first three digits coincide, taking into account the order, from the tray last (for a number equal to 1000A + B, where A and B are three-digit numbers, you need to take N = A if A < B, and N = A - 1 if A ≥ B). Since the difference between these lucky numbers is 1001, the length of the series of unlucky tickets cannot be more than 1000. At the same time, two series of length 1000 - from 000001 to 001000 and from 998999 to 999998, obviously consists of unlucky numbers.

b) Answer: two series; they are given in the solution to problem a).

Let us show that between any two lucky numbers $n = \overline{abcabc}^*$ and $n' = n + 1001 =$

*)The bar means decimal notation: $\overline{a_1a_2...a_n} = a_1 \cdot 10^{n-1} + a_2 \cdot 10^{n-2} + ... + a_n$.

⟦folio 44⟧

= \frac{a'b'c'a'b'c'}{(a'b'c'=abc+1)} with \frac{abc}{≠000} and \frac{abc}{≠998} there is at least one more lucky number. From here, obviously, it follows that there are no other “unfortunate series” of length 1000, except those indicated above.

If $a \neq 9$, $c \neq 0$, then such a number is $\frac{abc}{(a+1)b(c-1)}$; if $a=9$, then $a'=9$, and the required number is $\frac{a'b'c'8b_1c_1}{b_1c_1}$, where the number $b_1c_1$ is obtained by increasing one of the digits of the number $\frac{b'c'}{(b'c'≠99)}$ by 1; if $c=0$, then $c'=1$ and the required number is $\frac{a'b'c'a_2b_2}{a_2b_2}$, where $a_2b_2$ is obtained from $\frac{a'b'}{a'b'}$ by decreasing one of the digits by 1 $(\frac{a'b'}{≠00})$.

S. Yu. Orevkov

M918.* The radius of the inscribed circle of a triangle is 1, and the lengths of its sides are integers. Prove that these numbers are 3, 4 and 5.

Let in a given triangle $ABC$ the lengths of the sides $AB, BC$ and $CA$ be equal to $c, a$ and $b$, then, as is easy to see, the segments of the sides from the vertices $A, B, C$ to the points of tangency of the inscribed circle from the side are equal

$$x = \frac{b+c-a}{2}, y = \frac{c+a-b}{2}, z = \frac{a+b-c}{2}$$

(see figure for symbols). In this case, the half-perimeter $p$ of the triangle is equal to $x+y+z$. Equating the expressions for the area $S$ of a triangle using Heron’s formula -

$$S = \sqrt{p(p-a)(p-b)(p-c)},$$

and through the half-perimeter and radius $r=1$ of the inscribed circle -

$$S = pr,$$

we get that $p=(p-a)(p-b)(p-c)$ or

$$x+y+z=xyz.$$

From equalities (1) it follows that the numbers $x, y$ and $z$ are either all integers or semi-integers (that is, of the form $n+1/2$, where $n$ is an integer). In the second case, the numbers $2x, 2y$ and $2z$ must be odd, which is impossible due to equality (2) $(2x \cdot 2y \cdot 2z = 4(2x+2y+2z)=4(a+b+c)$ - an odd number is equal to an even number), and thus we must solve equation (2) in integers.

Let $x \leqslant y \leqslant z$ be used for definition, then $xyz \leqslant 3z$, that is, $xy \leqslant 3$. Going through pairs of natural numbers $(x, y)$ that satisfy this inequality (and the condition $x \leqslant y$), we obtain that either $x=y=1$, and then $2+z=z$, which is impossible; or $x=1, y=2$, and then $3+z=2z$, that is, $z=3$; or $x=1, y=3$ and $z=2<y$, which contradicts our assumption. So, $x=1, y=2, z=3$, that is $a=y+z=5, b=z+x=4, c=x+y=3$.

V. V. Praslov

M919. a) Prove the equality

$$\int_0^{\frac{1}{4}} \frac{1}{\sqrt{gx}} dx + \int_0^{1} \frac{1}{\sqrt{arctg x}} dx = \frac{\pi}{4}.$$

⟦folio 46⟧

$$z = nx^2y^2 - \frac{x^3 + y^3}{z^2} \geq nx^2y^2 - (x + y).$$

At the same time, obviously $x^3 + y^3$ is divisible by $z^2$, so
$$x^3 + y^3 \geq z^2 \geq (nx^2y^2 - (x + y))^2,$$
hence,
$$n^2x^4y^4 < 2nx^2y^2(x + y) + x^3 + y^3.$$

Dividing both sides by $nx^3y^3$, we get the required estimate
$$nxy < 2\left(\frac{1}{x} + \frac{1}{y}\right) + \frac{1}{nx^3} + \frac{1}{ny^3}.$$

It immediately follows from it that $x = 1$, because for $x \geq 2$ (and $y \geq x$) the lying part of the inequality (*) is not less than 4, and the right side is less than 3. Let’s substitute the value $x = 1$ into (*):

$$ny < 2 + \frac{2}{y} + \frac{1}{n} + \frac{1}{ny^3}.$$

This inequality can only hold for $y \leq 3$ (for $y \geq 4$ its right-hand side is less than 4). Recall that the number $x^3 + y^3 = 1 + y^3$ must be divisible by $z^2$, and $z \geq y$; it follows that $z = 1$ for $y = 1(1 + y^3 = 2)$, $z = 3$ for $y = 2(1 + y^3 = 9)$, and for $y = 3(1 + y^3 = 28)$ there are no suitable values ​​of $z$. It remains to substitute the triples of numbers (1, 1, 1) and (1, 2, 3) into the original equation and find that in the first case $n = 3$, and in the second $n = 1$.

So, the answer: for $n = 3$ $x = y = z = 1$, for $n = 1$ the equation is satisfied by the triple (1, 2, 3) and everything resulting from it by permutations.

We solve the equation to help with the structure of the equation $x^2 + y^2 + z^2 = nxyz$, which was discussed in detail in the article by M. G. Krein “The Diophantine equation of A. A. Markov” in «Kvant» No. 4 for this year. Interestingly, this equation is also solvable only for $n = 1$ and $n = 3$, but the number of its solutions in general cases is infinite. Another similar equation for the number $(x + y + z = xyz)$ is found in the solution to problem M918.

R. A. Mazov, V. N. Dubrovsky

F927. A charged particle sings through a scinitlation counter, which has the shape of a rectilinear parallel, and the scinitlator molecules lying along its trajectory emit light. Light at each point is emitted uniformly, that is, evenly in all directions. What fraction of the light energy will escape from the scinitlator into the air if the refractive index of the scinitlator substance is $n = 1,6$? Pay attention to the position of the light in the scinitlator.

Note the uresol at the apex of the cone is equal to $\Omega = 2\pi(1 - \cos \theta)$, where $\theta$ is the angle between the axis of the cone and its resulting one.

Consider a beam of light emitted from an arbitrary point inside a scinitlator.

Let $\alpha$ be the angle that this ray forms with the normal $\vec{N}$ to one of the faces of the parallel plane, to be determined on the ground by its face $A$, and $\alpha_0 = \arcsin(1/n) \approx 39^\circ$ be the limiting angle of total reflection of light at the scinitlator-air boundary.

Let us prove that for any values ​​of the refractive index $n > \sqrt{2}$ the following statements are true:

1. A beam emitted at an angle $\alpha < \alpha_0$ will certainly exit the scinitlator and, moreover, only through the face $A$.
2. No ray emitted at an angle $\alpha > \alpha_0$ can exit through the face $A$.

First of all, note that upon reflection

⟦folio 47⟧

light from faces parallel to $\vec{N}$, the angle $\alpha$ does not change (this follows directly from the law of light reflection). Further, since for $n > \sqrt{2}$ $\alpha_0 < 45^\circ$, the minimum possible angle of incidence of the beam (satisfying the condition $\alpha < \alpha_0!$) on the faces parallel to $\vec{N}$ turns out to be greater than $\alpha_0$ and, therefore, light cannot escape from the scinitillator through these faces. Thus, Statement 1 is proven.

Let's move on to the proof of the second statement. Let's consider all possible values ​​of angles $\alpha$ from 0 to $180^\circ$. In the region $\alpha_0 < \alpha < 90^\circ$, due to the following remark, it is clear that at any of these angles light cannot escape through the face $A$. At initial angles $90^\circ \leq \alpha \leq 180^\circ$, only those rays that have experienced complete reflection on the face $B$, parallel to $A$, can hit the face $A$ (but will not necessarily get there). But such rays cannot exit through the face $A$, since their angle of incidence on it is exactly the same as on the face $B$ from which they were reflected. Therefore, Statement 2 is also proven.

So, all the rays that come out of the counter are concentrated in six cones - the axis of each cone is perpendicular to one of the faces of the parallelped. The solid angle cut by all cones from the maximum solid angle equal to 4π is a fraction

$$\eta = \frac{6 \cdot 2\pi(1 - \cos \alpha_0)}{4\pi} = 3\left(1 - \sqrt{1 - \frac{1}{n^2}}\right).$$

This means that approximately 2/3 of the resulting light energy will come from the $n=1,6$ scinitytor.

S. A. Khorozov

F928. Two identical main half-chindras, the total mass of which is $m$, are suspended on an inextensible bride thread as shown in figure. What are the tension forces of the thread and the pressure force of one half-chindra on the other?

Each half-chindra is subject to the force of the weight, the tension force of the thread and the pressure force from the second half-chindra. Let us write down the semi-chindra condition:

in projections on the horizontal axis -

$$T + T \cos \alpha = N,$$

(1)

in projections on the vertical axis -

$$T \sin \alpha = \frac{mg}{2}.$$

(2)

Solving equations (1) and (2) together, we find the force $T$ of the tension of the thread and the force $N$ of the pressure of one half-chindra on the other:

$$T = \frac{mg}{2 \sin \alpha},$$

$$N = \frac{mg(1 + \cos \alpha)}{2 \sin \alpha}.$$

L. G. Markovich

⟦folio 48⟧

F929. It is known that by cooling a vessel with water and simultaneously pumping gas out of the vessel, it is possible to bring the water to a boil. Is it possible for a liquid to boil when a closed vessel containing liquid and gas is cooled?

The condition for a liquid to boil at a given temperature is that the pressure above it is equal to the pressure of saturated vapor at this temperature.

If a closed vessel with liquid and gas is cooled uniformly, then at any temperature the pressure above the liquid will be greater than the pressure of its saturated vapor by the value of the partial pressure of the gas in the vessel. In this case, the liquid will not boil when cooling.

If the vessel is cooled unevenly, so that the upper part of the vessel cools faster, the liquid may boil. This will happen when the total pressure of gas and saturated vapor above the liquid, where the temperature is lower, becomes the pressure of saturated vapor at the higher temperature that the liquid currently has.

L. A. Ashkinazi

F930. The surface charge densities on the rectangular plates of a flat capacitor are +σ and -σ. The distance between the plates is much smaller than the size of the plates. Determine the direction of the electric sectole at point A (see figure).

From the symmetry messages it is easy to show that the direction vector $\vec{E}_A$ of the electrostatic field at point A is directed perpendicular to the capacitor plates.

Indeed, mentally divide each plate into identical small sections. Let us select pairs of symmetrical (lying opposite each other) sections on two plates. For example, $\vec{E} = \vec{E}_1 + \vec{E}_1'$ of the field created by the charges of these sections at point A is directed vertically (see figure). So the total direction $\vec{E}_A$ of the field at point A is also vertical (that is, perpendicular to the capacitor plates).

Additionally, each plate of our capacitor has three more of the same plates (with the same charge density) so that point A is inside the capacitor frame with “quadruple” plates. For example, $\vec{E}_0$ of the field of such a capacitor at point A will become equal to $\vec{E}_0 = 4\vec{E}_A$, where $E_0 = \sigma/\varepsilon_0$. Hence,

$$E_A = \frac{E_0}{4} = \frac{\sigma}{4\varepsilon_0}.$$

O. Ya. Savchenko

F931. A point source is located at a distance of 2F from a lens with focal length F. A screen is located at a distance of 3F from the lens (see figure). Behind the lens there is a round plate of radius R that transmits

⟦folio 49⟧

A point on the screen lying at a distance $r$ from the optical axis $(r \leqslant R_\pi)$ receives rays emerging from the lens at a distance $2r$ from the axis. The illumination at this point of the screen (without using a plate) is equal to

$$E_0(r) = \frac{IF}{(F^2 + r^2)\sqrt{F^2 + r^2}} = \frac{IF}{(F^2 + r^2)^{3/2}}$$

(I is the luminous intensity of the source; we neglect light losses in the lens). When using a plate, the illumination at this point will be

$$E(r) = E_0(r) \cdot T(2r) = \frac{IF}{(F^2 + r^2)^{3/2}} T(2r),$$

where $T(2r)$ is the “throughput” of the plate at its points, located at a distance $2r$ from the optical axis. It is clear that the illumination at any points of the spot (regardless of $r$) will be the same if $T(2r) = k(F^2 + r^2)^{3/2}$, that is

$$T(r) = k \left(F^2 + \frac{r^2}{4}\right)^{3/2},$$

where $k$ is a certain proportionality coefficient.

Since $T(r) \leqslant 1$, the maximum possibility at all points of the spot when using a plate cannot be greater than the minimum illumination of the spot obtained without a plate. The minimum illumination without a plate is at points lying on the spot boundary, that is, at a distance of $R_\pi$ from the optical axis. These points are hit by rays emerging from the plate at a distance $R_\pi$ from the axis. Therefore, the maximum value of $k$ is determined by the condition $T(R_\pi) = 1$, that is

$$k = \frac{1}{(F^2 + R_\pi^2/4)^{3/2}}.$$

So, a spot on the screen has a uniform maximum illumination potential if the “throughput” of the plate varies along its radius according to the law

$$T(r) = \frac{1}{(F^2 + R_\pi^2/4)^{3/2}} \left(F^2 + r^2/4\right)^{3/2} = \left(\frac{4F^2 + r^2}{4F^2 + R_\pi^2}\right)^{3/2}.$$

A. A. LanUDEC
