---
id: 1977-5-mamikon-obem-shara-3d609e60
issue: kvant_1977_5
year: 1977
number: "5"
title: Sphere volume
authors:
  - Мамикон М.
rubric: osnovnye-stati
page_first: 12
page_last: 15
page_labels: 10-13
tag: 8R4Z
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7fa336663753ed3d4a3f1525323d65fef71f58ea38c682e0bf8fd2e6a3000777
prompt_sha256: draft-1
translated_from: content/ru/1977/05/articles/06_mamikon-obem-shara-3d609e60.md
source_content_sha256: 2f31ebbaf9c4d13f52919341396433ae5a5dd12f20ee17df78a92a7dd68b5dc9
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

Probably every schoolchild knows well what the volume of a sphere is. Did you know that the first volume of a sphere was calculated by the ancient Greek Archimedes back in the third century BC? e.?

Archimedes found the volume of a sphere in two ways. The first method is to compile interral sums and, in essence, was very close to the modern method of integration (see “Algebra and the beginnings of analysis 10,” pp. 104, 107). The second, more elementary method of Archimedes is to use a mechanical principle that combines the principle of cross sections and the rule of leverage, which he also discovered.

Archimedes established that the volume of a sphere is one and a half times less than the volume of a cylinder circumscribed around the sphere:

$$V_{\text{ш}} = \frac{2}{3} v_{\text{ш}}.$$

Archimedes considered this result his greatest achievement. Upon completion of Archimedes, a ball inscribed in a cylinder was carved on his tomb. It was on this basis that Cicero found the tomb of Archimedes a century and a half later. Now she is lost again.

In the first part of the article we will explain how Archimedes found the volume of a sphere using his mechanical method. And then we will solve this problem number geometric.

Even before Archimedes, the principle of cross sections was known, newly known as the “Cavalieri principle” (see the article by V. Boltyansky “On the concepts of area and volume,” p. 2). This principle is as follows.

Let two bodies be given in space (see screensaver), and let any plane parallel to this one, in the section with this body, form two figures whose areas are equal to each other: $S_1 = S_2$. (In this case, the cross-section of each body, generally speaking, is variable.) Then these two bodies have equal volumes: $V_1 = V_2$.

Let's imagine that both bodies are laid out from very thin plane-parallel layers of the same thickness. If each layer of one body weighs as much as the corresponding layer in another body weighs, then both bodies as a whole weigh the same.

It is now obvious that the principle of cross sections is also valid in a more general form: if three bodies are given and in each of the plane-parallel sections the cross-sectional areas of the first two bodies are in the sum equal to the cross-sectional area of ​​the third body: $S_1 + S_2 = S_3$, then the sum of the volumes of the first two bodies is equal to the volume of the third body: $V_1 + V_2 = V_3$.

As we will see below, Archimedes, using the more general mechanical development of the principle of cross sections, sums to express the volume of the ball through the volumes of the cylinder and cone. The latter were calculated even before Archimedes. In particular, Eudoxus showed that the volume of a cone is three times

⟦folio 11⟧

Change the volume of the cylinder described around it.

Archimedes' method

Let us draw, following Archimedes, a circle of radius $R$ and a rectangle, which has a common center $O$ with the circle, on the side of length $2R$ and $4R$. Let us inscribe into this rectangle an equilateral right triangle with a right angle at the vertex $A$ (Fig. 1).

If we rotate our figure around the axis $AB$, then the circle, when rotated, forms a ball of radius $R$, the rectangle forms a circular cylinder with a base radius $2R$, and the triangle forms a cone inscribed in the cylinder with the same base.

Let us select a point $C$ on the rotation axis $AB$ at a certain distance $x$ from the point $A$ and draw a plane $\alpha$ through the point $C$, peredicular to $(AB)$. In a section with a cylinder it forms a circle of radius $2R$, in a section with a cone - a circle of radius $|CD| = |AC| = x$ (since the angle at the vertex of the cone is straight); in cross section with the ball - a circle of radius $|CE|$. From figure 1 it is clear that

$$|AE|^2 = |CE|^2 + |AC|^2 = |CE|^2 + |CD|^2.$$

On the other hand, $AE$ is the leg of the right triangle $AEB$ ($AB$ is the diameter of the circle), and then $|AE|^2 = |AB| \cdot |AC|$. Hence,

$$|AB| \cdot |AC| = |CD|^2 + |CE|^2.$$

Multiplying both sides of this equality by the number $\pi \cdot |AB|$, we get

$$\pi \cdot |AB|^2 \cdot |AC| = \pi \cdot |CD|^2 \cdot |AB| + \pi \cdot |CE|^2 \cdot |AB|.$$ (1)

The value $S_K = \pi \cdot |CD|^2$ is the area of ​​the circle resulting from the intersection of the cone with the plane $\alpha$. The value $S_{III} = \pi \cdot |CE|^2$ is the area of ​​the circle resulting from the cross section of the ball.

The area of ​​the circle resulting from the cross section of the cylinder is equal to $S_{II} = \pi \cdot |AB|^2$. Therefore, we can rewrite equality (1) as follows:

$$x \cdot S_{II} = 2R \left( S_{III} + S_{II} \right).$$ (2)

If the possible $x$ were constant, then with the help of prinizap according to the lists of sections we would express the volumes of a sphere, cone and cylinder in terms of a circle.

But the $x$ can be variable, and this greatly complicates the situation. It would seem that they will not advance further. But then Archimedes was struck by a brilliant insight, the meaning of which is as follows.

Let us plot the segment $AT : |AT| = |AB|$ on the straight line $AB$ blevо from the point $A$. Let us now imagine that the segments $AB$ and $AT$ are the arms of the lever; whose fulcrum coincides with point $A$. Then the correspondence to the circular sections of the ball $S_{III}$ and the cone $S_K$ to the point $T$, then they will “balance” with respect to the point $A$ the circular section of the cylinder $S_{II} = \pi \cdot |AB|^2$, left in its place $C^*$. Archimedes replaces that an additional correspondence is established for any other sections of a ball, cone and cylinder lying in the same “vertical” plane. It is important to note here that the sections of the ball and cone are “shaken” all the time. At the same point $T$, at a distance $2R$ from the fulcrum point of the lever $A$, and the section of the cylinder - at a distance $x$ from the fulcrum point $A$. Considering different sections of our three bodies of vertical planes (distant from the point $A$ at different distances $x$), each time we suspend the sections of the cylinder in different places (sections of the cone and sphere

*) We assume that sections $S_{III}$, $S_K$ and $S_{II}$ are made of the same material in the form of very thin round disks of equal thickness.

⟦folio 12⟧

Fig. 2.

change in magnitude as $x$ changes). By changing $x$ from zero to $2R$, i.e., the distances of the entire variable sections of the three bodies, we, accordingly, balance each three sections (see Fig. 2). As a result, at point $T$, all sections of the ball and cone are suspended on the left, and all sections of the cylinder (Fig. 3) on the right. Archimedes writes *): “If now, taking also circles, we fill both a cylinder and a ball with a cone with it, then the cylinder, remaining in the same position, will be in equilibrium with respect to the point $A$ with the ball and cone taken together, if we transfer them to the lever at $T$ and place them so that the center of gravity of each of them is under $T$.” But the center

*) It is in these considerations that a sharp combination of the principle of cross sections with the rule of mechanical equilibrium of the lever is seen.

Fig. 3.

Fig. 4.

⟦folio 13⟧

Fig. 5.

Rotating figure 4 around the vertical axis AB, we obtain a ball of radius R, a cylinder circumscribed around the ball, and a “double” circular cone inscribed in the cylinder with its vertex at the center of the ball O. These three bodies are depicted on figure 5.

Let's take a point C on the axis of rotation AB at a certain distance x from the center of the ball and draw a horizontal plane (MN) through C. This plane in section with a cylinder forms a circle of radius $|CM| = R$, in section with a cone - a circle of radius $|CD| = |OC| = x$ (since the angle at the vertex of the cone is straight) and in section with a ball - a circle of radius $|CE|$. By the Pythagorean theorem $|OE|^2 = |CE|^2 + |OC|^2$, or

$$|CM|^2 = |CE|^2 + |CD|^2.$$

Multiplying both sides of this relation by the number π, we obtain $\pi \cdot |CM|^2 = \pi \cdot |CE|^2 + \pi \cdot |CD|^2$, i.e.

$$s_ц = S_ц + s_к,$$

(3)

where $s_ц$, $S_ц$ and $s_к$ are, respectively, the areas of the circles resulting from the intersection of the cylinder, ball and cone with the plane (MN).

Relationship (3) is satisfied for any other sections of the cylinder, ball, and cone lying in the same horizontal plane. Recalling the principles of cross sections, let us move from relation (3) for planes to the same relation for volumes:

$$v_ц = V_ц + v_к.$$

Since the volume of the second cylinder is greater than the volume of the “double” cone inscribed in it (which has the same base and height), i.e. $v_к = \frac{1}{3} v_ц$, we obtain Archimedes’ result:

$$V_ц = v_ц - v_к = v_ц - \frac{1}{3} v_ц = \frac{2}{3} v_ц,$$

namely, that the volume of the sphere is one and a half times less than the volume of the described cylinder.

Exercise
figure 6 shows a sphere and a cylinder with two funnel ends at the base. The height and diameter of the base of the cylinder are equal to the diameter of the ball. Which of these two bodies weighs more?
