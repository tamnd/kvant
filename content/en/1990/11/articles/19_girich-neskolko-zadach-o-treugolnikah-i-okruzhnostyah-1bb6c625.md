---
id: 1990-11-girich-neskolko-zadach-o-treugolnikah-i-okruzhnostyah-1bb6c625
issue: kvant_1990_11
year: 1990
number: "11"
title: Several problems about triangles and circles
authors:
  - Гирич А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 48
page_last: 50
page_labels: 46-48
lang: en
source: kvant_digital
extraction: vision
content_sha256: 15c573077d524b9f71b9cb2f4f5d09b54f310fedd6160e9f6e2ef8b2c60c1507
prompt_sha256: draft-1
translated_from: content/ru/1990/11/articles/19_girich-neskolko-zadach-o-treugolnikah-i-okruzhnostyah-1bb6c625.md
source_content_sha256: 509fc0644c2cc0ba3f045a7205984706d65bf443ee9820e8db0e22a46f00eb73
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 46⟧

---
running_head:
folio:
---

Several problems about triangles and circles

A. GIRICH

In this note we will talk about a circle tangent to two sides of a triangle and a circle circumscribed around this triangle. We will call such circles half-written. We will discover a number of interesting properties of half-written circles.

As usual, we denote the long sides of the triangle $ABC$, opposite the vertices $A, B$ and $C$, by $a, b$ and $c$, respectively, the angles at these vertices are $\alpha, \beta$ and $\gamma$, the radii of the inscribed and circumscribed circle are $r$ and $R$, area triangle - $S$, its half-perimeter - $p$.

Before starting to study half-written circles, let's solve the following auxiliary problem.

Problem 1. Express the radius $R$ of the circumcircle in terms of the radius $r$ of the circumcircle and the angles $\alpha, \beta, \gamma$.

Solution. There are two known formulas for the area of ​​a triangle

$$S = \frac{abc}{4R} = rp. \tag{1}$$

By the sine theorem $a = 2R \sin \alpha, b = 2R \sin \beta, c = 2R \sin \gamma$. Substituting these expressions into (1), we get

$$2R^2 \sin \alpha \sin \beta \sin \gamma = Rr(\sin \alpha + \sin \beta + \sin \gamma),$$

but $\alpha + \beta + \gamma = \pi$, and $\sin \gamma = \sin(\alpha + \beta)$. Pozotomu

$$\sin \alpha + \sin \beta + \sin \gamma = 4 \cos \frac{\alpha}{2} \cos \frac{\beta}{2} \cos \frac{\gamma}{2}.$$

So, $2R \sin \alpha \sin \beta \sin \gamma = 4r \cos \frac{\alpha}{2} \times \cos \frac{\beta}{2} \cos \frac{\gamma}{2}$, from where we easily get

$$r = 4R \sin \frac{\alpha}{2} \sin \frac{\beta}{2} \sin \frac{\gamma}{2}.$$

Problem 2. Prove that the radius of the half-circle tangent to sides $AB$ and $AC$ of triangle $ABC$ is equal to $r/\cos^2 \frac{\alpha}{2}$.

Proof. Let $r_1$ be the radius, $I_1$ the center of the half-circle, $O$ the center of the circumcircle of triangle $ABC$ (Fig. 1). Then $OI_1 = R - r_1$, $AI_1 = r_1/\sin \frac{\alpha}{2}$, $OA = R$, $\cos \angle OAI_1 = \cos \frac{(\beta - \gamma)}{2}$ (make sure of this).

Applying the cosine theorem to the triangle $OAI_1$, we obtain after transformation

$$r_1 \cos^2 \frac{\alpha}{2} = 2R(\cos \frac{\beta - \gamma}{2} - \sin \frac{\alpha}{2}) \sin \frac{\alpha}{2}. \tag{2}$$

⟦folio 47⟧

---
running_head:
folio:
---

$$\cos \left( \frac{\beta - \gamma}{2} \right) - \sin \frac{\alpha}{2} = \cos \frac{\beta - \gamma}{2} - \cos \frac{\beta + \gamma}{2} = 2 \sin \frac{\beta}{2} \sin \frac{\gamma}{2},$$
the right side of equality (2) is equal to $4R \sin \frac{\alpha}{2} \sin \frac{\beta}{2} \sin \frac{\gamma}{2} = r$.

So, $r_1 = r / \cos^2 \frac{\alpha}{2}$.

Problem 3. Prove that the midpoint $I$ of the segment $B_1C_1$, where $B_1$ and $C_1$ are the tangent points of the half-circle with sides $AB$ and $AC$ (see Fig. 1), is the center of the incircle of the triangle $ABC$.

Proof. Obviously, the triangle $AB_1C_1$ is equilateral, and the triangle $AIC_1$ is rectangular. Pozotomu
$$AI = AC_1 \cos \frac{\alpha}{2} = r_1 \text{ ctg} \frac{\alpha}{2} \cos \frac{\alpha}{2} = r / \sin \frac{\alpha}{2}.$$
But this means that point $I$ is the center of the inscribed circle.

Problem 4. Line $B_1C_1$ touches the circumcircle of triangle $BIC$.

Proof. Let $W$ be the point of intersection of the bisector of angle $A$ with the circumcircle of triangle $ABC$ (Fig. 2.) Then $CW = WB$, $\angle CBW = \alpha/2$, so $\angle IBW = (\alpha + \beta)/2$. Also, $\angle WIB = (\alpha + \beta)/2$ (as an external angle to the triangle $AIB$). Therefore, triangle $WIB$ is equilateral. Thus, $CW = WI = WB$, i.e. $W$, is the center of the circle circumscribed about the triangle $CIB$. The statement of the problem follows from the previously proven peredicularity of $AI$ and $B_1C_1$.

Let us now draw tangents to the half-circle through the vertices $B$ and $C$. Let $K$ be the point of their intersection, and $M$ and $N$ the corresponding points of tangency (Fig. 3).

Problem 5. Prove that the lines $B_1M, C_1N, BC$ and $AK$ intersect at one point.

Proof. Let $T$ be the intersection point of the segments $B_1M$ and $BC$ (see Fig. 3). From triangles $B_1TC$ and $BMT$ we obtain (by the sine theorem)
$$\frac{CT}{\sin \angle CB_1T} = \frac{CB_1}{\sin \angle B_1TC},$$
$$\frac{BT}{\sin \angle BMT} = \frac{BM}{\sin \angle BTM},$$
but $\angle B_1TC = \angle BTM$, and $\angle BMT + \angle CB_1T = \pi$ ($\angle CB_1M = \angle B_1MK$, since $AC$ and $KB$ are tangent to the same circle). Pozotomu
$$\frac{CT}{BT} = \frac{CB_1}{BM} = \frac{CB_1}{C_1B}.$$

⟦folio 48⟧

---
running_head:
folio:
---

$\angle BC_1V_1 + \angle CB_1V_1 = 180^\circ$. Therefore, $\frac{BV_1}{CV_1} = \frac{BC_1}{CB_1}$. Similarly, we obtain (assuming that $V_2$ is the point of intersection of $MN$ with $BC$): $\frac{BV_2}{CV_2} = \frac{BM}{CN}$, but $BM = BC_1$, $CN = CB_1$. So, $\frac{BV_1}{CV_1} = \frac{BV_2}{CV_2}$, therefore $V_1 = V_2$.

Problem 7. Prove that the lines $BB_1$, $CC_1$ and $AK$ intersect at one point (see Fig. 3).

Proof. Since $B_1A = AC_1$, and, as was established earlier, $\frac{BT}{CT} = \frac{BC_1}{CB_1}$, we obtain

$$\frac{BT}{CT} \cdot \frac{CB_1}{B_1A} \cdot \frac{AC_1}{C_1B} = 1.$$

It remains to use Ceva’s theorem (on Ceva’s theorem, see the article by B. Erdriev and N. Matsaev in «Kvant» No. 3 for 1990).

In conclusion, we offer a series of tasks for independent solution.

Exercises

1. Let now $A_1, A_2, B_2, C_2$ be the points of tangency of two other (different from distances) half-circles on the side of the triangle. Prove that the intersection points of the lines $B_1C_1$ and $BC, B_2A_2$ and $AB, A_1C_2$ and $AC$ lie on the same line.

2. Let $K_1, K_2, K_3$ be the intersection points of the tangents drawn to each of the three semicircles through the vertices of the triangle. Prove that lines $AK_1, BK_2$ and $CK_3$ intersect at one point.

3. Let $D$ be the intersection point of lines $BB_2$ and $CC_2$. Prove that $D$ belongs to the median of triangle $ABC$ drawn through the vertex $A$.

4. Let $P_1, P_2, P_3$ be the tangent points of the semicircles with the circumcircle. Prove that lines $AP_1, BP_2$ and $CP_3$ intersect at one point.
