---
id: 1990-7-honsberger-staraya-yaponskaya-teorema-383b0734
issue: kvant_1990_7
year: 1990
number: "7"
title: Old Japanese theorem
authors:
  - Хонсбергер Р.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 56
page_last: 59
page_labels: 54-57
lang: en
source: kvant_digital
extraction: vision
content_sha256: e6fe95c192a81f34ce694bb961025eb8a334226a303e2b05f6ba3051b4dbb26c
prompt_sha256: draft-1
translated_from: content/ru/1990/07/articles/18_honsberger-staraya-yaponskaya-teorema-383b0734.md
source_content_sha256: 0078a7629a0c3d33cd7519a405b32b2afacc9f97a7c3bdab198eb4801849bb61
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 54⟧

---
running_head:
folio:
---

Old
Japanese theorem
R. HONSWERGER

We offer you a translation of a short excerpt from the wonderful book of Russian Honsberg “Mathematical Zhelchuzhniki”. We hope that this book will appear on bookstore shelves soon.

Japanese mathematicians have an ancient tradition: they write down their discoveries on tablets, which are then displayed in temples - in honor of the gods and in honor of the authors of these discoveries. (This was discussed by Roger Johnson in his book Advanced Euclid Geometry.)

In 1800, in one of the Japanese temples, a beautiful theorem appeared on a tablet:

Divide a convex polygon inscribed in a circle into triangles by drawing all the diagonals from one of its vertices. Let us inscribe a circle in each of the resulting triangles. The sum of the radii of all these circles is a constant value, independent of the choice of the vertex of the polygon.

It turns out that the same sum of radii is obtained for any other method of dividing a given polygon into triangles (Fig. 2). Below we will see that both of these problems are easily solved using the amazing theorem of L. Carnot (1753-1823).

11before formulating Carnot’s theorem, let’s agree on something. Let us describe around an arbitrary triangle $A_1A_2A_3$ a circle with center $O$ (Fig. 3). Of course, the point $O$ does not always belong to the triangle itself. Therefore, considering the distance $OO_i$ ($i=1, 2, 3$) from the point $O$ to the side of the triangle, it is reasonable to assume that this value can be either positive or negative. We will assume that the distance $OO_i$ is negative if and only if the segment $OO_i$ lies entirely outside the triangle (Fig. 4). This “rule of signs” ensures that the “sum” of the areas (with appropriate signs) of triangles $OA_1A_2, OA_2A_3, OA_3A_1$ always turns out to be equal to the area of ​​triangle $A_1A_2A_3$.

Carnot's theorema states*):

*) For the proof of Carnot's theorem, see the editor's commentary.

Fig. 1.

⟦folio 55⟧

---
running_head:
folio:
---

The sum of the distances from the center of the circle circumscribed around the triangle to the side of the triangle is equal to the sum of the radii of the circumscribed circle and the inscribed circle, i.e. $OO_1 + OO_2 + OO_3 = R + r$, where $R$ is the radius of the circumscribed circle, and $r$ is the radius of the circumscribed circle in the triangle.

Let's return to our “pearl” - to the theorem about an inscribed polygon divided into triangles. Let's renumber these triangles, and let $r_i$ be the radius of the circle inscribed in the triangle with number $i$, and $OO_1^i, OO_2^i, OO_3^i$ be the distance from the center $O$ of the great circle to the side $i$ of the triangle. Then by Carnot’s theorem $r_i + R = OO_1^i + OO_2^i + OO_3^i$. Therefore, the sum of radii $r_i$ that interests us can be written as follows:

$$S = (OO_1^{(1)} + OO_2^{(1)} + OO_3^{(1)}) + (OO_1^{(2)} + OO_2^{(2)} + OO_3^{(2)}) + \dots - R - R - \dots - R.$$

The number of triangles into which our polygon is divided does not depend on the method of division; more precisely, for any division of a convex $n$-gon with disjoint diagonals into triangles, the result is a $(n-2)$ triangle. Therefore, the quantity $R - R - \dots - R$ included in the sum $S$ is the same for all partitions, namely $(2-n)R$. It remains only to show that for all methods of partitioning the sum $S' = (OO_1^{(1)} + OO_2^{(1)} + OO_3^{(1)}) + \dots + (OO_1^{(n-2)} + OO_2^{(n-2)} + OO_3^{(n-2)})$ is the same.

But this is done in one minute.

Consider an arbitrary diagonal $PQ$. It is the common side of two triangles of the partition (Fig. 5). In this case, the rependlcur $OO'$ necessarily turns out to lie entirely outside one of these triangles. So including $S'$ in the sum from all such “distances” will be zero, since the partition $OO'$ is included in the sum $S'$ twice, but once with a flat sign, and the second time with a minus sign. Thus, the sum $S'$ is simply equal to the sum of the lengths of the lines from the point $O$ to the sides of the given polygon. It is clear that this value is constant.

⟦folio 56⟧

---
running_head:
folio:
---

From the editor. Lazare Carnot, whose theorem R. Honsberg refers to, is known in the world not only for his mathematical work, but also for his vibrant political activity in France during the era of the Great French Revolution. He was then called the “organizer of victories.” Under Napoleon, he was the Minister of War and the Minister of the Interior of France.

Physicists are well aware of the name of L. Carnot’s son, Sadi Carnot, one of the founders of thermodynamics.

L. Carnot's theorem itself is a magnificent mathematical gem, and we could not help but provide its proof here. The most elegant known proof of L. Carnot’s theorem is based on the theorem of Ptolemy, who lived in Alexandria (Egypt) in the 2nd century AD and became famous primarily for his astronomical works. He created a geometric system of the world, which was generally accepted until the appearance of the works of Copernicus. Unlike Carnot, practically nothing is known about the life of Ptolemy.

Ptolemy's theorem goes like this:
The product of the lengths of the diagonals of an inscribed quadrilateral is equal to the sum of the products of the lengths of the opposite sides of this quadrilateral.

For example, she proves it this way:

Let us choose point E on the diagonal AC so that angle ABE is equal to angle DBC (Fig. 6). Then the triangles ABE and DBC turn out to be similar, since their angles at vertex B are equal in

Fig. 6.

structure, and the angles at the vertices A and D lie on the same circle and rest on the arc BC.

If we denote the side lengths by a, b, c, d, the lengths of the diagonals by e and f (Fig. 6), and the length of the segment AE by x, then from the similarity of these triangles it follows that

$$a/x = e/c, \text{ или } ac = ex.$$

Similarly, triangles ABD and EBC are similar. Their angles at vertex B are equal in construction, and the angles at vertices D and C rest on the arc AB. From the similarity it follows that

$$e/d = b/(f-x), \text{ или } bd = ef - ex.$$

But ex = ac, therefore bd = ef - ac, i.e.

$$ef = ac + bd.$$

Ptolemy's theorem has been proven. Let's move on to the proof of Carnot's theorem. Let ABC be the triangle under consideration (Fig. 7), the center O of the circumscribed circle lies inside it, and the points K, L and M, respectively, are the midpoints of the side AB, BC and AC. By construction, segments OK, OL and OM are perpendicular to these sides, and segments KL, LM, KM are the midlines of triangle ABC. If we construct a circle on the segment AO as a diameter, then points K and M will lie on it, since the angles AKO and AMO are right angles. Therefore, Ptolemy’s theorem can be applied to the quadrilateral AKOM:

$$AO \cdot KM = AK \cdot OM + AM \cdot KO.$$

But AO = R, KM = a/2, AK = c/2, AM =

⟦folio 57⟧

---
running_head:
folio:
---

= b/2. Therefore, this equality can be rewritten as follows:
$$a \cdot R/2 = c \cdot OM/2 + b \cdot KO/2.$$
Considering similar quadrilaterals BLOK and CMOL, we obtain two more equalities:
$$b \cdot R/2 = b \cdot OL/2 + a \cdot OK/2,$$
$$c \cdot R/2 = b \cdot OL/2 + a \cdot OM/2.$$
Let's add one more obvious equality (r is the radius of the circle inscribed in triangle ABC):
$$(a + b + c) \cdot r/2 = a \cdot OL/2 + b \cdot OM/2 + c \cdot OK/2.$$
Now adding the last four equalities, we get:
$$(a + b + c) \cdot (R + r)/2 = (a + b + c) \times (OM + OK + OL)/2,$$
$$\times (OM + OK + OL)/2,$$
from which the statement of Carnot's theorem immediately follows.
If the triangle ABC is obtuse with an obtuse angle A (Fig. 8), then together with the four equalities we wrote, we should write the following:
$$\frac{a \cdot R}{2} = \frac{c \cdot OM}{2} + \frac{b \cdot OK}{2},$$
$$\frac{a \cdot OK}{2} = \frac{c \cdot OL}{2} + \frac{b \cdot R}{2},$$
or
$$\frac{b \cdot R}{2} = \frac{a \cdot OK}{2} - \frac{c \cdot OL}{2},$$
$$\frac{a \cdot OM}{2} = \frac{b \cdot PO}{2} + \frac{c \cdot R}{2},$$
or
$$\frac{c \cdot R}{2} = \frac{a \cdot OM}{2} - \frac{b \cdot OL}{2},$$
$$\frac{(a + b + c)r}{2} = \frac{b \cdot OM}{2} + \frac{c \cdot OK}{2} - \frac{a \cdot OL}{2}.$$
Adding these four equalities, we get:
$$\frac{(a + b + c)(R + r)}{2} = \frac{(a + b + c)}{2} \times (OK + OM - OL);$$
This is the statement of Carnot's theorem for an obtuse triangle.
The publication was prepared by A. Savin

(For the beginning, see p. 48)

"Wave Diffraction" (1-86),
“Diffraction of light by a circular response” (11-89),
"Polarization of Light" (1-87),
"What is a rainbow?" (12-84),
“What can a microscope do?” (1-85),
“How to see the invisible?” (3—85),
"Rays and Waves" (11-85),
"X-Rays" (4-84).

Elements of the theory of relativity
“On the time machine and the theory of relativity” (3-88).

Quantum physics
“Photoelectric effect and quanta” (2-84),
“Substitute a little regarding the photo-fect” (1-89),
"Absolutely black body" (2-85).

Atomic physics
“Rutherford’s experiments and the phenomenon of radioactivity” (4-85),
"Alpha particles and Rutherford's experiments" (3-89),
"Two mysteries of beta decay" (5-85),
“Charge of the atomic nucleus and Mendeleev’s periodic table of elements” (3-84),
“On nuclear matter” (3-86),
“Nuclear Spectra” (3—87),
“Droplet model of the nucleus” (5—86),
“Antihilation of couples” (5-84).
