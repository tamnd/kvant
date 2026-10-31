---
id: 1989-3-kurlyandchik-pryamougolnyiy-treugolnik-4a166efa
issue: kvant_1989_3
year: 1989
number: "3"
title: Right triangle
authors:
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 58
page_last: 59
page_labels: 56-57
tag: UCKI
lang: en
source: kvant_digital
extraction: vision
content_sha256: ae793a277d15be61f84f7ade89a61eeafbe76b32bed4dd0555893cd187ce5590
prompt_sha256: draft-1
translated_from: content/ru/1989/03/articles/16_kurlyandchik-pryamougolnyiy-treugolnik-4a166efa.md
source_content_sha256: deb9b3c39689e8bf6e6835800cea0413d64b6c341df3da81a1dbe8edb21a5c10
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 56⟧

Right Triangle
L. D. KURLYANDCHIK

What interesting things can be said about a right-angled triangle? At first glance, nothing - everything seems to be known about him. Let's not rush, however. Reading this note, you will see many interesting and non-trivial properties of this simple figure. maybe some of you will discover other properties not mentioned here.

Almost obvious relationships

So, let ABC be a right triangle, point H the base of the altitude dropped from the vertex of right angle C (Fig. 1). As usual, we introduce the notation
AB=c, AC=b, BC=a, AH=b', BH=a',
CH=h,
∠A=α, ∠B=β.

Let us recall simple statements and relationships that you know from school.
1. Triangles BCH, ACH and ABC are pairwise similar
2. a²=a'c, b²=b'c.
From relation 2, by the way, the Pythagorean theorem follows:
a²+b²=a'c+b'c=c(a'+b')=c².
3. h²=a'b', h=ab/c.
4. Let R be the center of the inscribed circle and r be its radius (Fig. 2).

Fig. 1.

⟦folio 57⟧

Then $r = \frac{a+b-c}{2}$.

Proof. Note that the quadrilateral $RKCL$ is a square, and we use the equality of tangent segments: $c = a - r + b - r$, whence $r = \frac{a+b-c}{2}$.

5. $\angle ARB = 180^\circ - \frac{1}{2} \angle A - \frac{1}{2} \angle B = 135^\circ$.

More complex statements

Let us inscribe circles in triangles $ACH$ and $BCH$ (Fig. 3). Let their radii be $r_1$ and $r_2$ then

6. $r + r_1 + r_2 = h$.

Proof. We have $r = \frac{a+b-c}{2}$, $r_1 = \frac{h+b'-b}{2}$, $r_2 = \frac{h+a'-a}{2}$. Adding these expressions, we get what we need.

7. $r^2 = r_1^2 + r_2^2$.

Proof. From the similarity of triangles $ACH$ and $ABC$ it follows that $\frac{r_1}{r} = \frac{b}{c} = \cos \alpha$, in addition, $\frac{r_2}{r} = \frac{a}{c} = \cos \beta = \sin \alpha$. So, $r_1 = r \cos \alpha$, $r_2 = r \sin \alpha$. Therefore, $r_1^2 + r_2^2 = r^2$.

8. $AC = AQ$, $BC = BP$.

Proof. The first equality follows from the chain of equalities of angles $\angle CQA = \angle BCQ + \angle B = \frac{1}{2} \alpha + \beta = \angle ACH + \angle HCQ = \beta + \frac{1}{2} \alpha = \angle ACQ$. The second equality can be proved in a similar way.

9. Point $T$ (see Fig. 3) is the point of intersection of the altitudes (orthocenter) of triangle $CRS$ and the circumcenter of triangle $CPQ$.

Fig. 2.

Proof. BS and AT are the bisectors of angles B and A. This means that lines BS and AT are perpendiculars to CP and CQ, respectively, and bisect these segments.

10. Direct $T_1R$ and $T_1S$ are parallel to the corresponding BC and AC.

Proof. From the point $T_1$ we lower the perpendicular $T_1R_2$ to AC (Fig. 4). Let $R^*$ be the point of intersection of $TR_2$ with AT. Let us prove that $R^* = R$.

Triangles $ATT_1$ and $AR^*R_2$ are similar. Therefore $\frac{R^*R_2}{TT_1} = \frac{AR_2}{AT_1} = \cos \alpha$, and therefore $R^*R_2 = TT_1 \cos \alpha = r \cos \alpha = r_1$, i.e. point $R^*$ lies on the bisector of angle A and is removed from AC by a distance $r_1$, but this means that $R^* = R$. Similarly, it is proved that $T_1S \parallel AC$.

Exercise 1. Prove the following statement yourself:

11. Line PS is parallel to AT and line RQ is parallel to BT.

12. Triangles ATB, BSC and ARC are similar.

13. Points H and T_1 lie on a circle with diameter RS.

14. $ST_1 = RT_1$.

Proof. Since $\triangle T_1RR_1$ is a right angle and $\angle RT_1R_1 = \beta$, we have $T_1R \sin \beta = r_1 = r \sin \beta$, hence $T_1R = r$. It can be proved in a similar way that $T_1S = r$.

15. $CU = CV$.

Proof. Triangle $ST_1R$ is an equilateral right angle triangle. Therefore $\angle TS_1R = \angle CUV = 45^\circ$. And this means that the triangle $CUV$ is equilateral.

16. Points Q, S, T, R, P lie on a circle with center at point $T_1$ and radius $r$.

Proof. Points S and R lie on this circle. Let's prove
