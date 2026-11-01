---
id: 1981-9-gabovich-vspomogatelnyie-otrezki-i-uglyi-da27013d
issue: kvant_1981_9
year: 1981
number: "9"
title: Auxiliary segments and angles
authors:
  - Габович И. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 50
page_labels: 46, 48
tag: EFVJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: de4254fc87f9d46a9d068107ae627e82b6cfc386f9b1d16c9f7ffb9c6e5cfdc2
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/19_gabovich-vspomogatelnyie-otrezki-i-uglyi-da27013d.md
source_content_sha256: 99c32b4d090f363eb3a2891c2e03c032790c5dc343135a8ed4fdff9b8974edf3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

I. Gabovich

Auxiliary segments and angles

When solving geometric problems, it is often useful, in addition to the quantities given in the condition, along with auxiliary quantities (lengths of segments, angles, etc.) and expressing the desired quantity through them. Moreover, in some cases, auxiliary quantities “disappear” during the solution (for example, they are reduced), in others they are determined through the data.

Problem 1 (MIPT, 1979). The inscribed circle of triangle ABC touches its sides AC and BC, respectively, at points M and N and intersects the bisector BD at points P and Q. Find the ratio of the areas of triangles PQM and PQN if $\widehat{A} = \frac{\pi}{4}, \widehat{B} = \frac{\pi}{3}$ (Fig. 1).

Solution. Let us draw the heights $[MM_1] \perp [PQ]$ and $[NN_1] \perp [PQ]$ in triangles PQM and PQN. Since triangles PQM and PQN have a common base,

$$\frac{S_{\triangle PQM}}{S_{\triangle PQN}} = \frac{|MM_1|}{|NN_1|}.$$

Let $O$ be the center of the inscribed circle and $|OM| = |ON| = x$. Since $\widehat{BON} = \frac{\pi}{3}$ and $\triangle ONN_1$ are straight-headed, $|NN_1| = \frac{x\sqrt{3}}{2}$. Since $\widehat{C} = \frac{5}{12}\pi$, from the quadrilateral NOMC we obtain $M\widehat{ON} = \frac{7\pi}{12}$. Therefore $M\widehat{OM}_1 = \frac{\pi}{12}$. From $\triangle MOM_1$ we get $|MM_1| = x\sin \frac{\pi}{12} = x\sin \left(\frac{\pi}{3} - \frac{\pi}{4}\right) = x\frac{\sqrt{6} - \sqrt{2}}{4}$.

Answer: $\frac{\sqrt{3} - 1}{\sqrt{6}}$.

Problem 2 (MOPI, 1978). The height of a regular quadrangular paramid is 30°. A plane is drawn through the side of the base of the paramida, peredicular to the opposite face. Find the ratio of the volume of the manifolds obtained when the paramid is intersected by this plane.

Solution. It is easy to see that the quadrilateral CDMN (Fig. 2) obtained in section is a trapezoid. We draw a plane through the altitude SO and the apothem SE. This plane is perpedicular to the lateral faces SAB and SCD (how much?). Therefore $F\widehat{SO} = 30^\circ$. Since $|SF| = |SE|$ and $F\widehat{SE} = 60^\circ$, the triangle is FSE-regular. Let $|AB| = |AD| = |EF| = x$. Then $|MN| = \frac{x}{2}, |EP| = \frac{x\sqrt{3}}{2}$. Let's find the volume of the quadrangular paramid SCDMN. The segment SP is the height of this paramid (how much?), and the trapezoid CDMN is its base. Therefore $V_{SCDMN} = \frac{1}{3}|SP| \cdot S_{CDMN}$.

Since $|SP| = \frac{x}{2}$ and $S_{CDMN} = \frac{(x + \frac{x}{2})}{2} \cdot \frac{x\sqrt{3}}{2} = \frac{3x^2\sqrt{3}}{8}$, we get

⟦folio 48⟧

$\triangle SDE$ we find $|DE| = x \sin \frac{\alpha}{2}$.
$|CD| = 2x \cdot \sin \frac{\alpha}{2}$. Thus,
$V = \frac{4}{3} x^2 h \sin^2 \frac{\alpha}{2}$. Now let's express $x^2$ in terms of $h$ and $\alpha$. To do this, consider the triangle $SOD$. We have $|SD|^2 = |SO|^2 + |OD|^2$, but $|OD| = |CD| \times \frac{\sqrt{2}}{2} = x\sqrt{2} \sin \frac{\alpha}{2}$. Therefore $x^2 = h^2 + 2x^2 \sin^2 \frac{\alpha}{2}$, hence $x^2 = \frac{h^2}{\cos \alpha}$. Therefore, $V = \frac{4}{3} h^3 \frac{\sin^2 \frac{\alpha}{2}}{\cos \alpha}$.

Let us present a solution to this problem using the introduction of an auxiliary angle. Let $SDO = \varphi$. From $\triangle SDO$ we get $|DO| = h \text{ ctg } \varphi$, $|CD| = h\sqrt{2} \text{ ctg } \varphi$. Thus, $V = \frac{2}{3} h^3 \text{ ctg}^2 \varphi$. It remains to express $\text{ctg}^2 \varphi$ in terms of the angle function $\alpha$. To do this, we introduce an auxiliary segment $SD$. Let $|SD| = x$. then $|DE| = x \sin \frac{\alpha}{2}$, $|OD| = x\sqrt{2} \sin \frac{\alpha}{2}$, $\cos \varphi = \frac{|OD|}{|SD|} = \sqrt{2} \sin \frac{\alpha}{2}$. Therefore $\text{ctg}^2 \varphi = \frac{\cos^2 \varphi}{1 - \cos^2 \varphi} = \frac{2 \sin^2 \frac{\alpha}{2}}{\cos \alpha}$, which results in receiving the earlier answer.

In this case, the second solution to the problem turned out to be slightly longer than the first.

The introduction of an auxiliary segment often helps in solving problems in which an angle and some nonlinear element (for example, volume) are given and you need to find another nonlinear element (surface, cross-sectional area, volume of the original or somehow related figure).

Problem 5 (KSU, physicist, 1978). A sphere whose surface area is $S$ has a vissan cone. The angle between the generatrix of the cone and the plane of the base is equal to $\alpha$. Determine the total surface area of ​​the cone.

Solution. If the cone is a vissan into a ball, then the center of the ball lies at the height of the cone or its extension beyond the plane of the base (“Geometry 9-10”, p. 108). The main cross-section of the combination of figures under consideration

Fig. 5.

An equilateral triangle is inscribed in a great circle.

If $\alpha \geq 45^\circ$, then the center of the ball $O$ lies at the height of the cone (Fig. 5). Let $|DB| = x$; then from $\triangle DBO_1$ we find $|O_1B| = x \cdot \cos \alpha$.
$S_n = \pi |O_1B| \cdot (|DB| + |O_1B|) = \pi x \cos \alpha (x + x \cdot \cos \alpha) = 2\pi x^2 \cos \alpha \cdot \cos^2 \frac{\alpha}{2}$.

Obviously $\hat{DOE} = \hat{DBO}_1 = \alpha$ and $|DE| = \frac{x}{2}$. FROM $\triangle DOE$ we get $|DO| = \frac{x}{2} \sin \alpha$ and $S = 4\pi \cdot \frac{x^2}{4 \sin^2 \alpha} = \frac{\pi x^2}{\sin^2 \alpha}$, whence $x^2 = S \sin^2 \alpha$. Thus,
$S_n = 2S \sin^2 \alpha \cdot \cos \alpha \cdot \cos^2 \frac{\alpha}{2} = S \sin \alpha \cdot \sin 2\alpha \cdot \cos^2 \frac{\alpha}{2}$.

It is easy to see that the above arguments remain valid for $\alpha < 45^\circ$.

Exercises

1 (MIPT, 1979). In $\triangle ABC$ given $\hat{A} = \frac{\pi}{3}$, $\hat{B} = \frac{\pi}{4}$. The extensions of triangle $ABC$ intersect the circle circumscribed around it at points $M, N$ and $P$. Find the ratio of the areal $n$-gonal straight line to the volume of the Wissan ball, knowing that the circles described around the base and lateral faces of the straight line are contraventive.

2 (KPI, 1978). Find the ratio of the volume of an areal $n$-gonal straight line to the volume of a Wissan ball, knowing that the circles described around the base and lateral edges of the straight line are contraventive.

3 (KSU, mekhanite, 1978). The vertex of an area triangular straight line is the center of the sphere, which touches the plane of the base of the straight line. The ratio of the area of ​​the lateral surface of the straight line to the area surface of the sphere is equal to $\alpha$. Determine the angle of inclination of the lateral straight line to the plane of the base.
