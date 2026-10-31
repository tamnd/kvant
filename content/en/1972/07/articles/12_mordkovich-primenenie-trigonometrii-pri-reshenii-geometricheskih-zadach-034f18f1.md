---
id: 1972-7-mordkovich-primenenie-trigonometrii-pri-reshenii-geometricheskih-zadach-034f18f1
issue: kvant_1972_7
year: 1972
number: "7"
title: Application of trigonometry in solving geometric problems
authors:
  - Мордкович А. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 45
page_labels: 40-43
tag: FAMN
lang: en
source: kvant_digital
extraction: vision
content_sha256: b2f11872843da2bf969f5e0004730da0bc379d6cba2977403be91ec441538e43
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/12_mordkovich-primenenie-trigonometrii-pri-reshenii-geometricheskih-zadach-034f18f1.md
source_content_sha256: 7b63f9517985ea860b9e25f6c3282421d83ab42cdeae6026a59911c4aadb2cc4
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Application of trigonometry in solving geometric problems

A. G. Mordkovich

When solving geometric problems, you often have to turn to trigonometry for help. Sometimes this inversion is necessary - when an angle is given and trigonometric functions of the angle are used to calculate linear elements, sometimes this inversion is desirable - when we ourselves see auxiliary angles in consideration, in order, then, using trigonometric functions, to calculate the linear elements we need or to establish some correspondence between linear elements. If we talk about the forms of application of trigonometry in solving geometric problems, then the main ones include general trigonometric transformations, the cosine theorem and, to a greater extent, the sine theorem, trigonometric identities and trigonometric equations used in trigonometric functions.

Now let's move on to considering the tasks.

Task 1. The side of the base of a regular quadrangular paramid is equal to a, the two-dimensional angle at the base is a. A ball is placed in the paramid; a tangent plane is drawn to the ball, parallel to the base of the paramid. Determine the lateral surface of the resulting truncated paramid.

Solved and e. There is no need to draw an inscribed ball on figure. It is quite enough to show the center of the ball (Fig. 1) - this is the point O of the intersection of the height of the paramid with the bisector of the linear angle SDH - and take into account that the height HH₁ of the truncated paramid is equal to the diameter of the ball.

We have: OH = r = HD tg ⇐ ODH = a/2 tg α/2,

HH₁ = 2r = a tg α/2,

S_{60k} = 4 · (AB + A₁B₁)/2 · DD₁ = 2(a + A₁B₁) · DD₁.

⟦folio 41⟧

For further calculations we need the auxiliary figure 2:

$$A_1B_1 = 2H_1D_1 = 2HE = 2(HD - DE) = 2\left(\frac{a}{2} - D_1E \cdot \text{ctg} \alpha\right) =$$

$$= a - 2HH_1 \text{ctg} \alpha = a - 2a \text{tg} \frac{\alpha}{2} \text{ctg} \alpha, \quad DD_1 = \frac{D_1E}{\sin \alpha} = \frac{HH_1}{\sin \alpha} = \frac{a \text{tg} \frac{\alpha}{2}}{\sin \alpha},$$

$$S_{60^\circ} = 2\left(a + a - 2a \text{tg} \frac{\alpha}{2} \text{ctg} \alpha\right) \cdot \frac{a \text{tg} \frac{\alpha}{2}}{\sin \alpha} = \frac{4a^2 \text{tg}^2 \frac{\alpha}{2}}{\sin^2 \alpha}.$$

Problem 2. Determine the radius of a circle if the inscribed angle with sides $a$ and $b$ rests on the arc $\alpha$.

Solution. The inscribed angle is $\frac{\alpha}{2}$. Let us denote the chord connecting the ends of the inscribed angle by $x$ (Fig. 3); then by the cosine theorem $x^2 = a^2 + b^2 - 2ab \cos \frac{\alpha}{2}$. Next, according to the sine theorem $\frac{x}{\sin \frac{\alpha}{2}} = 2R$, we open

$$R = \frac{x}{2 \sin \frac{\alpha}{2}} = \frac{\sqrt{a^2 + b^2 - 2ab \cos \frac{\alpha}{2}}}{2 \sin \frac{\alpha}{2}}.$$

Problem 3. Plane angles of a trihedral angle (Fig. 4), $SM$ is the common side of the plane angles $\alpha$ and $\beta$. Let us find the values ​​of the dihedral angle at the edge $SM$. Let us set aside the segment $SC = 1$, draw a plane through point $C$ perpendicular to the line $SM$, and denote by $A$ and $B$ the points of intersection of this plane with the rays $SN$ and $SP$. Then $\triangle ACB$ is the linear angle of the dihedral angle of interest to us.

Let $\triangle ACB = x$, then $AC = \text{tg} \alpha$, $BC = \text{tg} \beta$, $AS = \sec \alpha$, $BS = \sec \beta$. From the triangle $ABS$ by the cosine theorem we have

$$AB^2 = AS^2 + BS^2 - 2AS \cdot BS \cdot \cos \gamma,$$

that is

$$AB^2 = \sec^2 \alpha + \sec^2 \beta - 2 \sec \alpha \cdot \sec \beta \cdot \cos \gamma.$$

On the other hand, from the triangle $ABC$ by the cosine theorem we have

$$AB^2 = AC^2 + BC^2 - 2AC \cdot BC \cos x,$$

⟦folio 42⟧

that is

$$AB^2 = tg^2\alpha + tg^2\beta - 2tg\alpha tg\beta \cdot \cos x.$$

Thus,

$$\sec^2\alpha + \sec^2\beta - 2\sec\alpha\sec\beta\cos\gamma = tg^2\alpha + tg^2\beta - 2tg\alpha tg\beta\cos x,$$

where

$$\cos x = \frac{\cos\gamma - \cos\alpha \cdot \cos\beta}{\sin\alpha \cdot \sin\beta}.$$

This means that the dihedral angle opposite the plane angle $\gamma$ is equal to arccos\left(\frac{\cos\gamma - \cos\alpha \cos\beta}{\sin\alpha \sin\beta}\right). Dihedral angles are found similarly.

If three plane and three dihedral angles are considered the basic elements of a trihedral angle, then the problem considered allows us to conclude that from any three basic elements of a trihedral angle one can find the remaining three.

Problem 4. A straight line is drawn through the vertex of angle $\alpha$ at the base of an equilateral triangle, intersecting the straight side and making angle $\beta$ ($\beta < \alpha$) with the base. In what ratio does this line divide the triangle?

Solved and e. Let $AB = BC = a, DC = x, BD = a - x$ (Fig. 5). Triangles $ABD$ and $ACD$ have a common height, so their areas are related to the bases, that is, like sides $BD$ and $CD$:

$$\frac{S_{ABD}}{S_{ACD}} = \frac{a - x}{x} = \frac{a}{x} - 1.$$

Thus, to solve the problem we only need to find the relation $\frac{a}{x}$.

Let us apply the sine theorem to the triangle $ABD$

$$\frac{a - x}{\sin(\alpha - \beta)} = \frac{a}{\sin(\alpha + \beta)}.$$

From here

$$\frac{x}{a} = \frac{\sin(\alpha + \beta) - \sin(\alpha - \beta)}{\sin(\alpha + \beta)}.$$

In the end

$$\frac{S_{ABD}}{S_{ACD}} = \frac{a}{x} - 1$$

$$= \frac{\sin(\alpha + \beta)}{\sin(\alpha + \beta) - \sin(\alpha - \beta)} - 1 = \frac{\sin(\alpha - \beta)}{2\sin\beta\cos\alpha}.$$

Problem 5. All lateral faces of a regular quadrangular paramid are inclined to the base at an angle $\alpha$, and the apothem of the lateral face is $a$. Through one of the sides of the base an angle $\beta$ ($\beta < \alpha$) is drawn with the plane of the base. Calculate the cross-sectional area.

Solved and e. Let us first find out what the section (Fig. 6) is. It is parallel to the line $AB$, and the side face passing through $AB$ intersects the section. In a straight line $EF$. But if a plane intersecting the first plane is drawn through a line parallel to a certain plane, then the line of intersection is parallel to this line, and therefore to the line $CD$. So, the cross section is trapezoid.

⟦folio 43⟧

Now let's do the calculations.

We have
$$KH = SK \cdot \cos \alpha = a \cos \alpha,$$
$$KL = CD = 2 a \cos \alpha.$$

Let us apply the sine theorem to the triangle $MKL$:
$$\frac{ML}{\sin \alpha} = \frac{KL}{\sin [180^\circ - (\alpha + \beta)]},$$
where
$$ML = \frac{KL \sin \alpha}{\sin (\alpha + \beta)} = \frac{a \sin 2\alpha}{\sin (\alpha + \beta)}.$$

Let us apply the sine theorem to the triangle $MSL$:
$$\frac{SL}{\sin (\alpha + \beta)} = \frac{MS}{\sin (\alpha - \beta)},$$
$$MS = \frac{a \sin (\alpha - \beta)}{\sin (\alpha + \beta)}.$$

From the similarity of triangles $SEF$ and $ABS$ we obtain:
$$\frac{MS}{KS} = \frac{EF}{AB}.$$
From here we get
$$EF = \frac{AB \cdot MS}{KS} = \frac{2a \cos \alpha \cdot a \sin (\alpha - \beta)}{a \cdot \sin (\alpha + \beta)} =$$
$$= \frac{2a \cos \alpha \cdot \sin (\alpha - \beta)}{\sin (\alpha + \beta)}.$$

Now we have what we need to calculate the cross-sectional area. We have
$$S = \frac{1}{2} (CD + EF) \cdot ML = \frac{1}{2} \left[ 2a \cos \alpha + \frac{2a \cos \alpha \cdot \sin (\alpha - \beta)}{\sin (\alpha + \beta)} \right] \times \frac{a \sin 2\alpha}{\sin (\alpha + \beta)} =$$
$$= \frac{a^2 \sin^2 2\alpha \cdot \cos \beta}{\sin^2 (\alpha + \beta)}.$$

Problem 6. On one of the arcs $AB$ of the circle, an arbitrary point $K$ and a point $M$ are given - the middle of the arc. These points are connected by chords from points $A$ and $B$. Prove that $AK \cdot KB = AM^2 - KM^2$.

Solved and e. Let us denote the angle $KBA$ by $\alpha$, and the angle $KBM$ by $\beta$ (Fig. 7). Let us apply the sine theorem to the triangle $AKB$:
$$\frac{AK}{\sin \alpha} = 2R, AK = 2R \sin \alpha.$$ Similarly, from the triangle $AMB$ there is $AM = 2R \sin (\alpha + \beta)$, and from the triangle $KBM - KM = 2R \sin \beta$.

Let us now consider the triangle $KMB$. We have $\Rightarrow KBM = \beta, \Rightarrow MKB = = \Rightarrow MAB = \Rightarrow ABM = \alpha + \beta, \Rightarrow KMB = 180^\circ - \beta - (\alpha + \beta) = 180^\circ - (\alpha + 2\beta), KB = 2R \sin [180^\circ - (\alpha + 2\beta)] = 2R \sin (\alpha + 2\beta)$. We need to prove that $AK \cdot KB = AM^2 - KM^2$, that is, that
$$2R \sin \alpha \cdot 2R \sin (\alpha + 2\beta) = 4R^2 \sin^2 (\alpha + \beta) - 4R^2 \sin^2 \beta$$
or
$$\sin \alpha \cdot \sin (\alpha + 2\beta) = \sin^2 (\alpha + \beta) - \sin^2 \beta.$$

The problem was reduced to proving the trionometric point. It is not difficult to prove, and we leave it to the reader to do it.

Problem 7. In a triangle, one angle is twice the arc, and the sides opposite this angle differ from the arc by 2 cm. Find these sides if it is known that the triangle of the triangle is 5 cm.
