---
id: 1980-4-melnik-gde-raspolozheno-osnovanie-vyisotyi-726339c2
issue: kvant_1980_4
year: 1980
number: "4"
title: Where is the height base located?
authors:
  - Мельник И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 44
page_labels: 40-42
tag: JNH8
lang: en
source: kvant_digital
extraction: vision
content_sha256: 203d431b7f11d0a0773985c49417736741b922d866f057884d9fe6b8f8e292c9
prompt_sha256: draft-1
translated_from: content/ru/1980/04/articles/14_melnik-gde-raspolozheno-osnovanie-vyisotyi-726339c2.md
source_content_sha256: 23e5746a95f225f9c052a701270cfff7b296ea3a46d7767760d1df01ff364ddd
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

Where is the height base located?

When solving stereometric problems, it is important to be able to correctly determine the relative position of the elements of the figures that arise in them. Many mistakes made when solving these problems are associated with depicting the height of the paramid (or prism). The location of the base height relative to the base of the paramid (or prism) is incorrect; as a result, the person arriving will incorrectly determine the angle of inclination of the side edge to the plane of the base; he makes a mistake when constructing a linear angle with two right angles, etc.

The purpose of the problems and examples below is to teach you how to solve stereometric problems while avoiding such mistakes. To do this, at the beginning of the article we offer three tasks with a list of possible answers from which you need to choose the correct one. Of course, here you cannot limit yourself to guessing the correct answer: it needs to be justified. Once you understand these problems, you will easily be able to solve the following examples, taken from the practice of entrance exams.

Problem 1. Which point of the ABC plane is the base of the altitude of the paramid SABC if:
a) load the side ribs;
b) the side ribs form equal angles with the plane of the base;
b) the side faces form congestion angles with the plane of the base;
d) plane angles at vertex S are right;

e) mutually redistribute two pairs of opposite edges;
e) load the side ribs together and
  $ASB = ASC = 60^\circ, BSC = 90^\circ$;
g) $ACB = 90^\circ, (AC) \perp (BS)$;
h) $\vec{SO} = \frac{1}{3}(\vec{SA} + \vec{SB} + \vec{SC})$?

Possible answers:
1) the point of intersection of the medians of triangle ABC;
2) the point of intersection of its heights;
3) the center of a circle circumscribed around triangle ABC;
4) the center of the circumcircle of triangle ABC;
5) the center of a circle circumscribed by triangle ABC, or one of the outer ones *);
6) midpoint of segment BC;
7) point of line BC.

To solve a problem, it is often essential to establish whether the base of an altitude belongs to the paramide or is outside it.

Problem 2. In the SABC paramide, the angles of inclination of the side ribs to the plane of the base are loaded together. Under what condition does the base of the altitude SO of the paramid belong to triangle ABC?

Possible answers:
1) $\triangle ABC$ - equilateral;
2) $\triangle ABC$ - equilateral;
3) $\triangle ABC$ - straight or acute-angled;
4) $\triangle ABC$ - obtuse-angled;
5) in each of these cases.

Problem 3. At the base of the paramid SABCD lies the trapezoid ABCD ([BC]||[AD], |BC|<|AD|). The lateral ribs of the paramida are loaded together. Under what condition does the base of the altitude SO of the paramid lie outside the trapezoid ABCD?

Possible answers:
1) if $ABD \leq 90^\circ$;
2) if $ABD > 90^\circ$;
3) if $(BD, CA) \geq 90^\circ$;
4) if $(BA, CD) > 90^\circ$;
5) no matter what.

*)An excircle of a triangle is a circle tangent to one of its sides and extended by the other two sides.

⟦folio 41⟧

Let us now move on to an analysis of two examples typical of entrance exams.

Example 1 (KSU, 1975). The lateral edges of a triangular paramid have the same length $l$. The two plane angles at the vertex of the paramid are $\alpha$, and the third is $\beta$. Find the volume of the paramid.

Solution. Let $SABC$ be the given paramid, $\hat{ASB} = \beta$, $\hat{ASC} = \hat{BSC} = \alpha$. From the problem statement we find:

$(\triangle ASC \cong \triangle BSC) \Rightarrow$
$\Rightarrow ([AC] \cong [BC])$;

the base $O$ of the height $SO$ is in the center of the circle circumscribed around the triangle $ABC$ (problem 1). Three cases are possible (see problem 2):

a) $\hat{ACB} < 90^\circ$ – the base of the height is located inside $\triangle ABC$ (Fig. 1);
b) $\hat{ACB} = 90^\circ$ – base of height

the middle $[AB]$ (Fig. 2) will happen;
c) $\hat{ACB} > 90^\circ$ - the base of the altitude lies outside the triangle $ABC$ (Fig. 3).
Let us denote by $D$ the midpoint of the segment $AB$.

Case a). Based on the condition, we find

$$|AB| = 2l \sin \frac{\beta}{2}; \quad |SD| = l \cos \frac{\beta}{2};$$
$$|AC| = |BC| = 2l \sin \frac{\alpha}{2};$$
$$|CD| = \sqrt{4l^2 \sin^2 \frac{\alpha}{2} - l^2 \sin^2 \frac{\beta}{2}} = l \sqrt{1 - 2 \cos \alpha + \cos^2 \frac{\beta}{2}}.$$

Let's put $|OD| = x$. From triangle $SOD$
$$|SO|^2 = l^2 \cos^2 \frac{\beta}{2} - x^2;$$

from triangle $CSO$
$$|SO|^2 = l^2 - (|CD| - x)^2 = l^2 - l^2 + 2l^2 \cos \alpha - l^2 \cos^2 \frac{\beta}{2} - x^2 + 2xl \sqrt{1 - 2 \cos \alpha + \cos^2 \frac{\beta}{2}}.$$

From here
$$l^2 \cos^2 \frac{\beta}{2} - x^2 = 2l^2 \cos \alpha - l^2 \cos^2 \frac{\beta}{2} - x^2 + 2xl \sqrt{1 - 2 \cos \alpha + \cos^2 \frac{\beta}{2}};$$
$$x = l \frac{\cos^2 \frac{\beta}{2} - \cos \alpha}{\sqrt{1 - 2 \cos \alpha + \cos^2 \frac{\beta}{2}}};$$
$$h = |SO| = \sqrt{l^2 \cos^2 \frac{\beta}{2} - l^2 \frac{(\cos^2 \beta/2 - \cos \alpha)^2}{1 - 2 \cos \alpha + \cos^2 \beta/2}} = l \frac{\sqrt{\cos^2 \beta/2 - \cos^2 \alpha}}{\sqrt{1 - 2 \cos \alpha + \cos^2 \beta/2}}.$$

Means,
$$V = \frac{1}{3} Sh = \frac{1}{3} l^3 \sin \frac{\beta}{2} \sqrt{\cos^2 \frac{\beta}{2} - \cos^2 \alpha}.$$

Sweeping. Since $\hat{ASB} < \hat{ASC} + BSC$, the inequality $\beta < 2\alpha$ holds and the sub-expression is positive. Vpro-

⟦folio 42⟧

than, in problems of this kind, research into the domain of definition of the expression obtained in the answer is not required.

Case 6). This case is possible if and only if
$$\sin \frac{\beta}{2} = \sqrt{2} \sin \frac{\alpha}{2}.$$
(2)

Indeed, if $\hat{C} = 90^\circ$, $|CD| = |AD| = l \sin \frac{\beta}{2}$; $|CD| = |AC| \frac{\sqrt{2}}{2} = \sqrt{2} l \sin \frac{\alpha}{2}$ (Fig. 2).

Hence $\sin \frac{\beta}{2} = \sqrt{2} \sin \frac{\alpha}{2}$. Conversely, if $\sin \frac{\beta}{2} = \sqrt{2} \sin \frac{\alpha}{2}$, then
$$|CD| = l \sqrt{1 - 2 \cos \alpha + \cos^2 \frac{\beta}{2}} = l \sqrt{2 - 2 \cos \alpha - \sin^2 \frac{\beta}{2}} = \sqrt{2} l \sqrt{1 - \cos \alpha - \sin^2 \frac{\alpha}{2}} = \sqrt{2} l \sqrt{\sin^2 \frac{\alpha}{2}} = \sqrt{2} l \sin \frac{\alpha}{2}.$$

Therefore $\cos \hat{ACD} = \frac{|CD|}{|AC|} = \frac{\sqrt{2}}{2}$. Hence $\hat{ACD} = 45^\circ$, $\hat{C} = 90^\circ$. If $\sin \frac{\beta}{2} = \sqrt{2} \sin \frac{\alpha}{2}$, then $h = |SD| = l \cos \frac{\beta}{2}$ (Fig. 2), $V = \frac{l^2}{3} \sin^2 \frac{\beta}{2} \times l \cos \frac{\beta}{2}$, $V = \frac{l^3}{6} \sin \beta \sin \frac{\beta}{2}$.

Case c). Let's put $x = |OD|$ (Fig. 3). As in case a), we find:
$$x = l \frac{\cos \alpha - \cos^2 \frac{\beta}{2}}{\sqrt{1 - 2 \cos \alpha + \cos^2 \frac{\beta}{2}}};$$
$$h = |SO| = l \frac{\sqrt{\cos^2 \frac{\beta}{2} - \cos^2 \alpha}}{\sqrt{1 - 2 \cos \alpha - \cos^2 \frac{\beta}{2}}};$$
$$V = \frac{1}{3} l^3 \sin \frac{\beta}{2} \sqrt{\cos^2 \frac{\beta}{2} - \cos^2 \alpha}.$$

We see that the answers in cases a) and b) are the same, although they were not obtained in the same way. Moreover, in case 6) this answer is also valid, which is not difficult to check (getting rid of α in (1) using correspondence (2), we obtain (3)).

Answer:
$$V = \frac{l^3}{3} \sin \frac{\beta}{2} \sqrt{\cos^2 \frac{\beta}{2} - \cos^2 \alpha}.$$

We emphasize that a solution in which only case a) is analyzed cannot be considered complete.

Example 2. The SABC parameters are based on a triangle with $|AB| = |BC| = 20$ cm, $|AC| = 32$ cm; The angle between the plane of the base and each of the side faces is 45°. Find the volume parameters.

Solution. The basis of the height parameters is a point equal to the length of the lines AB, AC, BC, that is, the center of the circle inscribed in $\triangle ABC$, or one of the outer ones (problem 16). Therefore, the conditions of the problem are satisfied by four parameters, the bases of the heights of which are the points $O_1$, $O_2$, $O_3$, $O_4$ (Fig. 4). To calculate the volume of these parameters, it is enough to determine the heights $SO_1$, $SO_2$, $SO_3$, $SO_4$, since the base area is $S = S_{\triangle ABC} = 192$ cm². Since the side faces are inclined to the plane of the base at an angle of 45°, the height of the parameter is equal to the radius of the circle inscribed in $\triangle ABC$, or one of the outer ones, the center of which is the base of the height of the parameters.

Fig. 4.
