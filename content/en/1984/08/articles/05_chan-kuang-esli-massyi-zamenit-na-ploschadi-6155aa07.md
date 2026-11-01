---
id: 1984-8-chan-kuang-esli-massyi-zamenit-na-ploschadi-6155aa07
issue: kvant_1984_8
year: 1984
number: "8"
title: If masses are replaced by areas...
authors:
  - Чан Куанг.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 37
page_last: 39
page_labels: 35, 37
tag: 18C5
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4bd0bbbe850d5e888a20e6ba67c0a6a75721d84a5a08f67c1c8fed696c91fd82
prompt_sha256: draft-1
translated_from: content/ru/1984/08/articles/05_chan-kuang-esli-massyi-zamenit-na-ploschadi-6155aa07.md
source_content_sha256: 88fb5e49afea399f49698e0ea193cf27cab53f4cbe51a7379f6eda85c0298907
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 35⟧

If the masses are replaced by planes...

CHAN KUANG

In this article we will prove several theorems that can be safely attributed to the gallstones of elementary geometry. Undoubtedly, these theorems should provide the reader with convenient formulations even just by their properties. But we are talking about them here for a different reason - they will be derived from one formula - the Lagrange formula for calculating the “moment of inertia”. Let us present it for serving three points A, B, C:
$$\alpha |PA|^2 + \beta |PB|^2 + \gamma |PC|^2 = \frac{1}{\mu} (\alpha \beta c^2 + \beta \gamma a^2 + \gamma a b^2) + \mu |PZ|^2;$$
(1)

here A, B, C and P are arbitrary points, α, β and γ are arbitrary numbers (understood as “mass” concentrated at points A, B and C), μ = α + β + γ ≠ 0, a, b, c are the lengths of segments BC, CA, AB, finally, Z is the center of mass of the system of materials of points αA, βB, γC, that is, by definition, a point that satisfies the conditions
$$\alpha ZA + \beta ZB + \gamma ZC = 0$$
(a material point is a pair (point, number), αA, βB and γC are critical designations for the materials of points (A, α), (B, β), (C, γ)). In principle, what has been said is enough both to derive formula (1) and to understand what follows. But still, we advise you to read the article by V.N. Dubrovsky “Moment of inertia in geometry” in the previous issue of the journal, where the Lagrange formula is proved (formula (7) from this article), explains how it is related to the “moment of inertia”, and some more of its geometric consequences are given, as well as the necessary properties of masses.

⟦folio 37⟧

coloring by $abc \cdot |DA| \cdot |DB| \cdot DC/4RS^2$, we get that
$$-c \cdot |DC| - a \cdot |DA| + b \cdot |DB| = 0,$$
that is
$$|DB| \cdot |AC| = |DA| \cdot |BC| + |AB| \cdot |DC|.$$

Pedal triangle area
The expression on the right side of (4) looks rather awkward, but as we will see in a moment, it makes good geometric sense. Let us drop from the point $Z$ the perpendiculars $ZA_1, ZB_1$ and $ZC_1$ to the lines $BC, CA$ and $AB$ (Fig. 5). The resulting triangle $A_1B_1C_1$ is called the pedal triangle of point $Z$. Leonhard Euler discovered that its area is equal to
$$S_{A_1B_1C_1} = \frac{1}{4} \left( 1 - \frac{|OZ|^2}{R^2} \right) S_{ABC}$$
(both squares are oriented!). Let us derive this result from our formula (4). To do this, we will prove that $S_aS_bc^2 = abcR \cdot S_{ZA_1B_1}$. Adding this equality with similar equalities for the other two terms on the right side of (4), we get:

$$R^2 - |OZ|^2 = \frac{1}{S^2} abcR \left( S_{ZA_1B_1} + S_{ZB_1C_1} \right) + S_{ZC_1A_1}$$
$$= \frac{4R^2}{S_{ABC}} S_{A_1B_1C_1},$$
which is equivalent to Euler's formula.

So, consider the expression $S_aS_bc^2$. It is clear that $|S_a| = a |ZA_1|/2$, $|S_b| = b |ZB_1|/2$, $c = 2R \sin \widehat{ACB} = 2R \sin A_1ZB_1$ (since the sides of angles $ACB$ and $A_1ZB_1$ are mutually perpendicular, their magnitudes are equal or add up to $180^\circ$). Hence,
$$|S_aS_bc^2| = abcR \cdot \frac{1}{2} |ZA_1| \|ZB_1| \sin A_1ZB_1 = abcR |S_{ZA_1B_1}|.$$

It remains to prove that the sign of the product $S_aS_b$ coincides with the sign of $S_{ZA_1B_1}$. This is easy to do by going through the four possible positions of the point $Z$ relative to the lines $AC$ and $BC$ (within each of the four angles formed by these lines, the signs $S_a, S_b$ and $S_{ZA_1B_1}$ are constant).

In conclusion, we present another ancient theorem: the base of the perpendiculars dropped from the point of the circumscribed circle of a triangle to its sides (or their extensions) lie on one straight line - the “Simson straight line” (Fig. 6).
