---
id: 1991-4-zatakavay-teorema-ptolemeya-i-nekotoryie-trigonometricheskie-sootnosheniya-00d00e1a
issue: kvant_1991_4
year: 1991
number: "4"
title: Ptolemy's theorem and some trigonometric relations
authors:
  - Затакавай В. В.
rubric: shkola-v-kvante
page_first: 44
page_last: 45
page_labels: 42-43
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5e1bb66b96de99482ca30d27c592a09db2f1d347641fbccbeb867d472deed422
prompt_sha256: draft-1
translated_from: content/ru/1991/04/articles/14_zatakavay-teorema-ptolemeya-i-nekotoryie-trigonometricheskie-sootnosheniya-00d00e1a.md
source_content_sha256: 7f8a1c4843652889520dc770ab5a40bae74e2b8328b730332ea316977de426e1
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 42⟧

---
running_head:
folio:
---

Mathematics 9-11
The published note is addressed to ninth graders.

Ptolemy's theorem
and some
trigonometric
compliance

About 2000 years ago, when
carrying out astronomical observations
Denia, the ancient Greeks noticed that
the length of the chord depends on the size
the corresponding arc. Production
measuring chord lengths for different
central angles and calculating the relative
ratio of their length to radius, ancient
river scientist Ptolemy compiled
table of these relations. It was
one of the first trigonometric
tables of satisfied sines of angles from 0° to 90°.

Ptolemy calculated the chord of an additional (up to 180°) arc along the chord
given arc (Fig. 1), applying theo-
rheme of Pythagoras. From a modern point
point of view, it's the same as if
he used the formula $\sin^2\alpha + \cos^2\alpha = 1$, since $AC = 2R \sin \alpha$, $BC = 2R \sin \beta = 2R \sin \left(\frac{\pi}{2} - \alpha\right) = 2R \cos \alpha$, and $AB = 2R$. So he compiled the tables
double cosines of angles from 0° to 90°.

Ptolemy was also able to find the chord of the half arc ($t. e. 2 \sin \frac{\alpha}{2}$) from the chord of the additional arc (i.e., from 2 cos $\alpha$). His reasoning build-
concluded that $OD = \frac{1}{2} BC$ (OD -
middle line $\triangle ABC$), then $OD = R \cos \alpha$, hence $MD = R - R \cos \alpha$. In turn, $AM =$

⟦folio 43⟧

---
running_head:
folio:
---

$= 2R \sin \frac{\alpha}{2}$. Using metric relations in a right triangle, we obtain $AM^2 = MD \cdot MK$. Taking into account the fact that $MK = 2R$, we get $4R^2 \sin^2 \frac{\alpha}{2} = (R - R \cos \alpha) \cdot 2R$, or
$$\sin^2 \frac{\alpha}{2} = \frac{1 - \cos \alpha}{2}.$$
Now we call this formula the polygonal degree formula.
Another great achievement of Potolemaus is that he proved a geometric theorem, which is now called Potolemaus's theorem.
Theorem. The product of the diagonals of a cyclic quadrilateral is equal to the sum of the products of its opposite sides (Fig. 2).
Proof. Let us take a point $M$ on the diagonal $AC$ such that $\angle ABM = \angle CBD$. Since $\angle CDB = \angle MAB$ are inscribed, triangles $BCD$ and $ABM$ are similar. Therefore $\frac{BD}{AB} = \frac{CD}{AM}$, i.e.
$$AB \cdot CD = AM \cdot BD.$$ (*)
From the fact that $\angle ABD = \angle MBC$ by construction, and $\angle BCM = \angle ADB$ as inscribed, it follows that $\triangle ABD \sim \triangle MBC$. So, $\frac{AD}{CM} = \frac{BD}{BC}$ or
$$AD \cdot BC = BD \cdot CM.$$ (**)
Adding equalities (*) and (**) term by term, we obtain
$$AB \cdot CD + AD \cdot BC = BD(AM + CM) = BD \cdot AC,$$
Q.E.D.

Using Potolemaus' theorem, we can derive some trigonometric formulas.
Let us inscribe the quadrilateral $ABCD$ into a circle in such a way that one of its sides is the diameter of this circle (Fig. 3).
Let $\angle AOC = 2\alpha$, $\angle AOD = 2\beta$, then $AC = 2R \sin \alpha$, $AD = 2R \sin \beta$, $BC = 2R \cos \alpha$, $BD = 2R \cos \beta$, $CD = 2R \sin (\alpha - \beta)$.
Using Potolemaus' theorem and learning that $AB = 2R$, we get
$$2R \cdot 2R \sin (\alpha - \beta) + 2R \cos \alpha \cdot 2R \sin \beta = 2R \sin \alpha \cdot 2R \cos \beta,$$
or
$$\sin (\alpha - \beta) = \sin \alpha \cos \beta - \cos \alpha \sin \beta.$$
Derive the formula for calculating $\sin (\alpha + \beta)$ yourself. (Hint: Inscribe a quadrilateral in a circle so that its diagonal is the diameter.)
So, we have two important trigonometric formulas:
$$\sin (\alpha - \beta) = \sin \alpha \cos \beta - \cos \alpha \sin \beta,$$
$$\sin (\alpha + \beta) = \sin \alpha \cos \beta + \cos \alpha \sin \beta.$$
Let's stack them up. We get
$$\sin (\alpha - \beta) + \sin (\alpha + \beta) = 2 \sin \alpha \cos \beta,$$
or
$$\sin \alpha \cos \beta = \frac{1}{2} (\sin (\alpha - \beta) + \sin (\alpha + \beta)).$$ (1)
By adding and subtracting formulas for the cosine of the sum (or difference) of two angles, we can obtain two more formulas:
