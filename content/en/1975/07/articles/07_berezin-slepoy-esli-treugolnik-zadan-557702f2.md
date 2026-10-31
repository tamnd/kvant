---
id: 1975-7-berezin-slepoy-esli-treugolnik-zadan-557702f2
issue: kvant_1975_7
year: 1975
number: "7"
title: If a triangle is given...
authors:
  - Березин В. Н.
  - Слепой В. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 38
page_last: 41
page_labels: 36-39
tag: RQ87
lang: en
source: kvant_digital
extraction: vision
content_sha256: 319fe090417a434789e6e024efacce27830a024a9283395ff9bd2f79b303b199
prompt_sha256: draft-1
translated_from: content/ru/1975/07/articles/07_berezin-slepoy-esli-treugolnik-zadan-557702f2.md
source_content_sha256: e4181b68623421e559c340ec0521596e3dcadfc5157041b8b3e3a96210c584c5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

If a triangle is given...

V. N. Berezin, V. I. Slepoy

In general, in geometric tasks one has to deal with angles of 30°, 45°, 60°, ...; but there are also problems where angles of 80°, 40° and even 47° occur! We are almost talking about such problems.

All problems discussed in this article involve a triangle lying in the same plane and a point connected to its vertices by segments. Known are considered to be either some angles between straight lines, or some metric relationships between straight segments, or both. It is required to determine some unknown angle (marked on the corresponding drawing with a question mark and a red bow).

The main notations in the note are standard, but sometimes auxiliary notations are useful when solving problems. This is, first of all, “coloring” equal segments in the same (not black) color and highlighting with color those parts of the plane that are useful to pay attention to when solving a problem.

Let's start with the simplest task.

Task 1. Given an equilateral triangle ABC and a point D outside it, the length of the segment BD is equal to the side $\Delta ABC$, and $\widehat{DBC}=40^\circ$ (see Fig. 1). Find $\widehat{ADC}$.

It's easy to calculate (do it yourself) that $\widehat{ADC}=30^\circ$. The interesting thing is that $\widehat{DBC}$ can be anything (and not necessarily equal to 40°); $\widehat{ADC}$ still remains equal to 30°.

Now solve this problem.

Task 2. Given an equilateral triangle ABC ($|BC|=|CA|$, see Fig. 2) with an angle BAC less than 60°, and a point D.make that the segment AD forms an angle with the side AC of the triangle equal to the difference between the angle of 60° and the angle BAC (maybe

Fig. 1.
Fig. 2.

⟦folio 37⟧

Fig. 3.

the line AC serves as the bisectis of angle DAE), with $|AD| = |AB|$. Find $\widehat{ADC}$ (it turns out to be equal to 30° again).

The following problem was presented at the XV Moscow Mathematical Olympiad.

Problem 3. From vertices A and C of equilateral triangle ABC with vertex angle $\widehat{ABC} = 20^\circ$ (Fig. 3), draw two straight lines until they intersect with the opposite sides of the triangle at points D and E, respectively, so that angle CAD is equal to 60°, and angle ACE is equal to 50°. Determine angle ADE.

Solution. From equilateral triangles congruent to triangle ABC, let us form a regular 18-gon $ACC_1C_2 \dots C_{15}C_{16}$ (see Fig. 4) with center at vertex B of the original triangle. Let's draw the diagonals $AC_8, AC_6, CC_9, CC_{12}, C_1C_{12}, C_1C_{16}, C_4C_{16}$ of this 18-gon. Diagonals $AC_6$ and $C_1C_{12}$ are symmetrical with respect to diagonal $CC_9$ and intersect at point D. Similarly, it is proved that diagonals $CC_{12}, C_4C_{16}$ and $AC_8$ intersect at the common point E. Now note that $[C_4C_{16}]$ and $[BC_1]$ are diagonals of a rhombus $BC_4C_1C_{16}$; therefore, the segment $C_4C_{16}$ is perpendicular to the segment $BC_1$ and passes through its middle; but since $\Delta BC_1D$ is equilateral ($\triangle DBC_1 \cong \triangle DC_1B$), then $C_4C_{16}$ contains its height, and therefore passes through point D. Now it is already clear that $\widehat{ADE} = 30^\circ$ (it is equal to half the sum of the arcs $AC_{16}$ and $C_4C_6$ of the circle in which our regular 18-gon is inscribed).

By the way, note that angle ECD is also equal to 30° and that triangle AEC is equilateral ($|AE| = |AC|$).

⟦folio 38⟧

Fig. 6.

Let us now generalize the conditions of Problem 3.
Problem 4. On sides AB and BC of triangle ABC, points E and D are taken corresponding to 马克, which is $\widehat{ADE} = \widehat{ECD} = 30^\circ$. It is known that triangle AEC is equilateral ($|AE| = |AC|$; Fig. 5). Assuming that $\widehat{ABC} = \alpha$, find the remaining angles of triangle ABC. What could be the angle $\alpha$?

Solution. Figure 5 tells you how to construct a triangle ABC from given points on the plane A, E and D and $\widehat{ADE} = 30^\circ$, in accordance with the conditions of the problem. Let us continue the segments AC and EC until they intersect with the circle circumscribed around the triangle AED, at points

Fig. 7.

G and F respectively (at figure 5 is a circle centered at $O_1$).

Triangle ACF is similar to triangle CEB ($\widehat{AFC} = \widehat{EDA} = \widehat{ECB} = 30^\circ$; $\widehat{ACF} = 180^\circ - \widehat{GCF} = 180^\circ - \widehat{ACE} = 180^\circ - \widehat{AEC}$); means $\widehat{FAC} = \alpha$. Therefore $\widehat{ACB} = \widehat{ACE} + 30^\circ = \alpha + 30^\circ + 30^\circ = \alpha + 60^\circ$, $\widehat{CAB} = 120^\circ - 2\alpha$.

Now, applying equality we get that $\alpha < 60^\circ$.

Now - the promised task, in which an angle of 47° occurs.

Problem 5. In the quadrilateral BGEC (BE and GC are its diagonals, see figure 6) $\widehat{EBC} = 30^\circ$, $\widehat{BCG} = 26^\circ$, $\widehat{GCE} = 51^\circ$, $\widehat{GEB} = 13^\circ$. The name will be fulfilled by BGC.

Solution. On the sides BC and EC of this quadrilateral we will construct a regular triangle: $\triangle BAC$ and $\triangle EFC$ (on figure 7 their contours are indicated by the corresponding red and blue). From point E, on the side GE, we plot a segment DE such that $|DE| = |EC|$, and connect points A with points D and E. We obtain a regular triangle ADE, equal to triangle EFC (the whole fi-

⟦folio 39⟧

The group BAEC is symmetrical with respect to (BE)).

Let's connect point F with point B, point D with points B and C (see Fig. 8). Triangle ADB is equal to triangle AEC (on two sides and the angle between them); since ΔAEC is equigonal, then ΔADB is also equigonal. Triangles ADB and BFC are symmetric relative to (BE), and therefore also equal; $\widehat{BAD} = \widehat{BCF} = 17^\circ$. This means that $\widehat{ADB} = 146^\circ$ and $BDE = 360^\circ - \widehat{ADB} - 60^\circ = 154^\circ$, that is, $\widehat{BDC} = 180^\circ - \widehat{BDE} = 180^\circ - 154^\circ = 26^\circ = \widehat{BCG}$, and therefore a circle can be drawn around the quadrilateral BGDC. Angle BGC and angle BDC in this circle are based on the same arc and are therefore equal.

But $\widehat{BDC} = 154^\circ - \widehat{EDC}$, where $\widehat{EDC}$ is the base angle of the equilateral triangle DEC, whose vertex angle is 86°; therefore, $\widehat{EDC} = 47^\circ$, and $\widehat{BDC} = \widehat{BGC} = 107^\circ$.

The condition of this problem can also be generalized.

Problem 5'. In the quadrilateral BGEC (BE and GC are its diagonals)

$$\widehat{EBC} = 30^\circ, \widehat{GCB} = \alpha, \widehat{GEB} = \frac{\alpha}{2},$$

$$\widehat{GCE} = 90^\circ - \frac{3}{2}\alpha.$$
