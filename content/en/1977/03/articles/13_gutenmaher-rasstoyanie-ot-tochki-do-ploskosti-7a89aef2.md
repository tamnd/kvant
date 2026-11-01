---
id: 1977-3-gutenmaher-rasstoyanie-ot-tochki-do-ploskosti-7a89aef2
issue: kvant_1977_3
year: 1977
number: "3"
title: Distance from point to plane
authors:
  - Гутенмахер В. Л.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 40
page_last: 41
page_labels: 38-39
tag: KY12
lang: en
source: kvant_digital
extraction: vision
content_sha256: 07cd9368591606b1079c677dafc3f423ec4e18c995a3976a8a41f3b45e340d64
prompt_sha256: draft-1
translated_from: content/ru/1977/03/articles/13_gutenmaher-rasstoyanie-ot-tochki-do-ploskosti-7a89aef2.md
source_content_sha256: fca9d8c596f91f2b96ee674d575ce1fe36d0df7a029d85f3b3a35d4d9cdeed7c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

V. Gutenmacher

Distance from point to plane

There are several problems in the Geometry 10 textbook that require you to find the distance from a given point to a given plane. Oddly enough, these problems cause some difficulties for schoolchildren (despite the fact that one of these problems - No. 28, p. 10 - is solved in the text). Therefore, we will stay on this issue in a little more detail.

New formula

Let $A(x_0; y_0; z_0)$ be a point in the coordinate space $Oxyz$ and $\alpha$ the plane defined by equation $ax+by+cz+d=0$. The distance $\rho(A, \alpha)$ from point $A$ to plane $\alpha$ is found by the formula

$$\rho(A, \alpha) = \frac{|ax_0+by_0+cz_0+d|}{\sqrt{a^2+b^2+c^2}}.$$

This formula can be described as follows:

It is necessary to substitute the coordinates of the point $A$ into the expression $ax+by+cz+d$ instead of the variables $x, y, z$. Take the modulus of the resulting number and divide it by the number $\sqrt{a^2+b^2+c^2}$.

Derivation of the formula

The derivation of formula (*) essentially repeats the solution to problem No. 28 given on p. 10-11 of the textbook “Geometry 10”.

Let us drop from the point $A(x_0; y_0; z_0)$ the relimit to the plane $\alpha$, given by the equation $ax+by+cz+d=0$; let $B$ be the point of intersection of this overflow with the plane $\alpha$; then $|AB|$ is the distance from $A$ to $\alpha$ (see figure). Let us denote by $(x_1; y_1; z_1)$ the coordinates of the point $B$; Then

$$\overrightarrow{AB} = \overrightarrow{OB} - \overrightarrow{OA} = (x_1-x_0; y_1-y_0; z_1-z_0),$$

where

$$|AB| = |\overrightarrow{AB}| = \sqrt{(x_1-x_0)^2 + (y_1-y_0)^2 + (z_1-z_0)^2}.$$

Since the vector $\overrightarrow{AB}$ is perpendicular to the plane $\alpha$, it is collinear with the vector $\vec{n}$ with coordinates $(a; b; c)$.

This means that there is a number $p$ such that

$$\overrightarrow{AB} = p \cdot \vec{n}.$$

(1)

From this equality it follows that

$$x_1-x_0 = p \cdot a, \quad y_1-y_0 = p \cdot b, \quad z_1-z_0 = p \cdot c.$$

(2)

Thus,

$$|AB| = \sqrt{p^2a^2 + p^2b^2 + p^2c^2} = |p| \cdot \sqrt{a^2 + b^2 + c^2}.$$

All that remains is to find the number $|p|$. Since the point $B$ belongs to the plane $\alpha$, then $ax_1+by_1+cz_1+d=0$. Since $x_1=x_0+pa, y_1=y_0+pb, z_1=z_0+pc$ (see correspondence (2)), for $p$ we obtain the equation

$$a(x_0+pa) + b(y_0+pb) + c(z_0+pc) + d=0,$$

from which $|p|$ is found:

$$|p| = \frac{|ax_0+by_0+cz_0+d|}{a^2+b^2+c^2}.$$

⟦folio 39⟧

Substituting the found value $|p|$ into correspondence (3), we obtain the desired formula:

$$\rho(A, \alpha) = |AB| = \frac{|ax_0 + by_0 + cz_0 + d|}{\sqrt{a^2 + b^2 + c^2}}.$$

Formula (*) allows you to easily solve any problem of calculating the distance from a point to a plane. Let's give a few examples.

Exercise
Problem 1 (*). Find the distance from point $A(-1; 3; 0)$ to plane $\alpha$ given by equation $x - 3y - 2z + 5 = 0$.

Solution. Using formula (*) we get:

$$\rho(A, \alpha) = \frac{|-1 - 3\cdot3 - 2\cdot0 + 5|}{\sqrt{1 + 3^2 + 2^2}} = \frac{|-5|}{\sqrt{14}} = \frac{5}{\sqrt{14}}.$$

Problem 2**). Calculate the distance from the origin to the plane $2x + 3y - 6z + 14 = 0$.

Solution. We need to find the distance from the point $A(0; 0; 0)$. Using formula (*) we get:

$$\rho(A, \alpha) = \frac{|2\cdot0 + 3\cdot0 - 6\cdot0 + 14|}{\sqrt{2^2 + 3^2 + 6^2}} = \frac{14}{7} = 2.$$

Problem 3. Calculate the distance between the planes $\alpha$ and $\beta$, given by the corresponding equation:

$$3x + 2y + 4z + 11 = 0$$

And

$$9x + 6y + 12z - 5 = 0.$$

Dividing both sides of the second equation by 3, we see that the planes $\alpha$ and $\beta$: $3x + 2y + 4z + 11 = 0$ and $3x + 2y + 4z - \frac{5}{3} = 0$ are parallel.

Let's take any point $A(x_0; y_0; z_0)$ belonging to the plane $\beta$: put, for example, $x_0 = y_0 = 0$, then $z_0 = \frac{5}{12}$.

*) This is problem No. 298.1) from the textbook “Geometry 10”. There is a typo in the textbook—the answer is incorrect.
**) This is problem No. 29.2) from the same textbook.

It is easy to understand that the distance between the planes $\alpha$ and $\beta$ is equal to the number $\rho(A, \alpha)$, where $A = \left(0; 0; \frac{5}{12}\right)$. Applying formula (*), we get

$$\rho(\alpha, \beta) = \rho(A, \alpha) = \frac{|3\cdot0 + 2\cdot0 + 4\cdot\frac{5}{12} + 11|}{\sqrt{3^2 + 2^2 + 4^2}} = \frac{38}{3\sqrt{29}}.$$

Sweeping. In the general case, the distance between parallel planes $\alpha$ and $\beta$:

$$ax + by + cz + d_1 = 0$$

And

$$ax + by + cz + d_2 = 0$$

is found by the formula

$$\rho(\alpha, \beta) = \frac{|d_1 - d_2|}{\sqrt{a^2 + b^2 + c^2}}.$$

Derive formula (**) by repeating the solution to Problem 3.

In conclusion, we present you with several tasks.

Task 1. Calculate the distance from point $A(1; 1; 1)$ to plane $x + y + z = 0$.

2. Calculate the distance from point $A(1; 2; 3)$ to plane $x + y + z - 6 = 0$.

3. Find the distance from point $A(x_0; y_0; 0)$ to plane $ax + by + d = 0$.

4. Find the equation of the plane located at a distance of 1 from the plane $x + y + z = 0$.

5. It is known that in a triangular paramid all the plane angles at the vertex are right angles. Find the length of its height if the lengths of its side edges are $a, b$ and $c$.
