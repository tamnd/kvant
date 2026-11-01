---
id: 1979-1-gabovich-vektoryi-pomogayut-na-ekzamene-44128586
issue: kvant_1979_1
year: 1979
number: "1"
title: Vectors help in the exam
authors:
  - Габович И. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 51
page_labels: 45, 47, 48, 49
tag: YCER
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4e4629c9c9ea9492260b7cedd403b11452c0bcc16857c2f33d94813c93ac61ad
prompt_sha256: draft-1
translated_from: content/ru/1979/01/articles/16_gabovich-vektoryi-pomogayut-na-ekzamene-44128586.md
source_content_sha256: 147580f88b1b028ee08593afe0f97d9ebd0151d4d741aa775622025db810f6ac
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

This article presents four important vector relationships and shows, using the materials of the 1977-1978 entrance exams as an example, how to apply them when solving competitive problems.

Basic ratio. In triangle ABC, point D is taken on side AC so that |AD|:|DC| = m:n. Then
$$\overrightarrow{BD} = \frac{n}{m+n} \overrightarrow{BA} + \frac{m}{m+n} \overrightarrow{BC}^*).$$ (1)

Proof. We have (Fig. 1)
$$\overrightarrow{AC} = \overrightarrow{BC} - \overrightarrow{BA},
\overrightarrow{AD} = \frac{m}{m+n} \overrightarrow{AC} = \frac{m}{m+n} \overrightarrow{BC} - \frac{m}{m+n} \overrightarrow{BA},
\overrightarrow{BD} = \overrightarrow{BA} + \overrightarrow{AD} = \overrightarrow{BA} + \frac{m}{m+n} \overrightarrow{BC} -
\frac{m}{m+n} \overrightarrow{BA} = \frac{n}{m+n} \overrightarrow{BA} + \frac{m}{m+n} \overrightarrow{BC}.$$
Problem 1 (MSU, Faculty of Economics, 1978). In the triangle KLM, point A is taken on the side KL so that |KA|:|AL| = 1:3; point B is taken on the LM side so that |LB|:|BM| = 4:1. Let C be the point of intersection of the lines KB and MA. It is known that the area of ​​triangle KLC is 2. Find the area of ​​triangle KLM.

*) In a slightly different form, this formula is considered in the article by S. Ovchinnikov («Kvant», 1978, No. 3, p. 48). See also the article by V. Boltyansky in «Kvant» 1978, No. 10, p. 14.

Solution. Let's put $S_{\Delta KLB} = S$. Then (Fig. 2) is obviously $S_{\Delta KLM} = \frac{4}{5} S$. Let us introduce the vectors $\overrightarrow{KL}$ and $\overrightarrow{KM}$. Based on (1) we have
$$\overrightarrow{KB} = \frac{1}{5} \overrightarrow{KL} + \frac{4}{5} \overrightarrow{KM}.$$
Let $\overrightarrow{KC} = x\overrightarrow{KB}$, where $0 < x < 1$. Then
$$\overrightarrow{KC} = \frac{x}{5} \overrightarrow{KL} + \frac{4x}{5} \overrightarrow{KM}.$$ (2)

Let $|AC|:|CM| = m:n$. Then from the triangle AKM using the same formula (1) we have
$$\overrightarrow{KC} = \frac{n}{m+n} \overrightarrow{KA} + \frac{m}{m+n} \overrightarrow{KM} =
\frac{n}{m+n} \frac{1}{4} \overrightarrow{KL} + \frac{m}{m+n} \overrightarrow{KM}.$$ (3)

Due to the unique decomposition of the vector in two non-collic vectors from (2) and (3) we obtain the system
$$\begin{cases} \frac{x}{5} = \frac{n}{4(m+n)} \\ \frac{4x}{5} = \frac{m}{m+n}, \end{cases}$$ or
$$\begin{cases} \frac{4x}{5} = \frac{n}{m+n} \\ \frac{4x}{5} = \frac{m}{m+n}. \end{cases}$$

Fig. 1.

Fig. 2.

⟦folio 47⟧

$$\overrightarrow{MN}^2 = \frac{4}{9} a^2 + \frac{a^2}{9} = \frac{5a^2}{9},$$

where

$$|MN| = \frac{a \sqrt{5}}{3}.$$

Let us now answer the second question of the problem. Let $|D_1M|:|MA| = p$.

Then

$$\overrightarrow{MN} = \frac{1}{p+1} \overrightarrow{D_1D} + \frac{p}{p+1} \overrightarrow{AB_1} =$$

$$= -\frac{a}{p+1} \vec{k} + \frac{2ap}{p+1} \vec{j} + \frac{ap}{p+1} \vec{k} =$$

$$= \frac{2ap}{p+1} \vec{j} + \frac{a(p-1)}{p+1} \vec{k},$$

$$\overrightarrow{MN}^2 = \frac{4a^2p^2}{(p+1)^2} + \frac{a^2(p-1)^2}{(p+1)^2} =$$

$$= \frac{a^2(5p^2-2p+1)}{(p+1)^2}.$$

Obviously, $|MN|$ will have the smallest value at the value $p$ at which the function reaches it

$$y = \frac{5p^2-2p+1}{(p+1)^2}.$$

The reader can easily check (using an arbitrary one) that this will happen for $p = \frac{1}{3}$. Substituting this value into the last expression for $\overrightarrow{MN}^2$ and taking the root, we find the required minimum distance:

$$\frac{a \sqrt{2}}{2}.$$

III basic relationship. Given a metrahedron ABCD and in the plane of its face ABC a point M. Prove that for the decomposition

$$\overrightarrow{DM} = \alpha \overrightarrow{DA} + \beta \overrightarrow{DB} + \gamma \overrightarrow{DC}$$

equality holds

$$\alpha + \beta + \gamma = 1^*).$$

Solution. Let us assume that point M lies inside triangle ABC (Fig. 5). Let us draw a line through points A and M, to which side BC intersects at point E. Let point E divide side BC in the ratio

$$*)\text{ В несколько ином виде это соотношение имеется в цитированной статье C. Овчинникова.}$$

Fig. 5.

$m:n$, i.e. $|BE|:|EC| = m:n$. Then according to formula (1)

$$\overrightarrow{DE} = \frac{m}{m+n} \overrightarrow{DC} + \frac{n}{m+n} \overrightarrow{DB}.$$

Let, further, point M divide the segment AE in relation to $p:q$, i.e. $|AM|:|ME| = p:q$. Then

$$\overrightarrow{DM} = \frac{p}{p+q} \overrightarrow{DE} + \frac{q}{p+q} \overrightarrow{DA} =$$

$$= \frac{p}{p+q} \left( \frac{m}{m+n} \overrightarrow{DC} + \frac{n}{m+n} \overrightarrow{DB} \right) +$$

$$+ \frac{q}{p+q} \overrightarrow{DA} = \frac{q}{p+q} \overrightarrow{DA} + \frac{p}{p+q} \times$$

$$\times \frac{n}{m+n} \overrightarrow{DB} + \frac{p}{p+q} \frac{m}{m+n} \overrightarrow{DC}.$$

So, the vector $\overrightarrow{DM}$ is decomposed into the vectors $\overrightarrow{DA}, \overrightarrow{DB}$ and $\overrightarrow{DC}$. An indefinite calculation of the sum of the coefficients in this expansion gives

$$\frac{q}{p+q} + \frac{p}{p+q} \frac{n}{m+n} +$$

$$+ \frac{p}{p+q} \frac{m}{m+n} = \frac{q}{p+q} + \frac{p}{p+q} = 1,$$

which is what was required. The remaining cases (point M lies outside triangle ABC or on one of its sides) are similar and we omit them.

Problem 3 (MIPT, 1978). The edge length of a regular metrahedron ABCD is $a$. Point E is the midpoint of edge CD, point F is the midpoint of height BL of face ABD. The segment MN with the ends of the lines AD and BC intersects the line EF and falls over it. Let's find the length of this segment.

Solution. Let us introduce the vectors $\overrightarrow{AB} = \vec{b}; \overrightarrow{AC} = \vec{c}; \overrightarrow{AD} = \vec{d}$ (Fig. 6). Note that $\|\vec{b}\| = \|\vec{c}\| = \|\vec{d}\| = a$ and

⟦folio 48⟧

Fig. 6.

$\overrightarrow{b}, \overrightarrow{c} = \overrightarrow{c}, \overrightarrow{d} = \overrightarrow{d}, \overrightarrow{b} = \frac{\pi}{3}$. Since $E$ is the midpoint of edge $DC$, then $\overrightarrow{AE} = \frac{1}{2}(\overrightarrow{c} + \overrightarrow{d})$.

Likewise,
$\overrightarrow{AF} = \frac{1}{2}(\overrightarrow{b} + \overrightarrow{AL})$,
but $\overrightarrow{AL} = \frac{1}{2}\overrightarrow{d}$, therefore
$\overrightarrow{AF} = \frac{1}{2}\overrightarrow{b} + \frac{1}{4}\overrightarrow{d}$.

Dallee,
$\overrightarrow{EF} = \overrightarrow{AF} - \overrightarrow{AE} = \frac{1}{2}\overrightarrow{b} + \frac{1}{4}\overrightarrow{d} - \frac{1}{2}\overrightarrow{c} - \frac{1}{2}\overrightarrow{d} = \frac{1}{2}\overrightarrow{b} - \frac{1}{2}\overrightarrow{c} - \frac{1}{4}\overrightarrow{d}$.

Let $\overrightarrow{AM} = m\overrightarrow{d}, \overrightarrow{BN} = n\overrightarrow{BC}$, (9) where $0 < m < 1$ and $0 < n < 1$. From the last equality it immediately follows $|BN| : |NC| = n : (1 - n)$.

Then, based on (1),
$\overrightarrow{AN} = n\overrightarrow{c} + (1 - n)\overrightarrow{d}$.

Dallee, $\overrightarrow{MN} = \overrightarrow{AN} - \overrightarrow{AM}$, from where $\overrightarrow{MN} = n\overrightarrow{c} + (1 - n)\overrightarrow{d}$. (11)

Since, by condition, the segments $EF$ and $MN$ are perpendicular, then $\overrightarrow{EF} \cdot \overrightarrow{MN} = 0$, or
$\left( \frac{1}{2}\overrightarrow{b} - \frac{1}{2}\overrightarrow{c} - \frac{1}{4}\overrightarrow{d} \right) \times \left( (1 - n)\overrightarrow{b} + n\overrightarrow{c} - m\overrightarrow{d} \right) = 0$.

Taking into account the replacement made above regarding the models of the vectors $\overrightarrow{b}, \overrightarrow{c}$ and $\overrightarrow{d}$ and the angles between them, we will open the brackets on the left side of this equality.

We get
$2m - 4n + 1 = 0$. (12)

By virtue of the main relation III, $\overrightarrow{AN} = \alpha\overrightarrow{AF} + \beta\overrightarrow{AE} + \gamma\overrightarrow{AM}$, (13) and $\alpha + \beta + \gamma = 1$.

Let us substitute in (13) instead of $\overrightarrow{AF}, \overrightarrow{AE}$ and $\overrightarrow{AM}$ their expressions through $\overrightarrow{b}, \overrightarrow{c}$ and $\overrightarrow{d}$, i.e. (7), (6), (9):

$\overrightarrow{AN} = \frac{\alpha}{2}\left(\overrightarrow{b} + \frac{1}{2}\overrightarrow{d}\right) + \frac{\beta}{2}\left(\overrightarrow{c} + \overrightarrow{d}\right) + \gamma m\overrightarrow{d} = \frac{\alpha}{2}\overrightarrow{b} + \frac{\beta}{2}\overrightarrow{d} + \left(\frac{\alpha}{4} + \frac{\beta}{2} + \gamma m\right)\overrightarrow{d}$.

Due to the unique decomposition of the vector into three given non-plan vectors $(\overrightarrow{b}, \overrightarrow{c}, \overrightarrow{d})$, from here and from (10) we obtain the system
$\frac{\alpha}{2} = 1 - n; \frac{\beta}{2} = n; \frac{\alpha}{4} + \frac{\beta}{2} + \gamma m = 0,$
solving which we get
$\alpha = 2 - 2n, \beta = 2n, \gamma = -\frac{1 + n}{2m}$.

Using the relation $\alpha + \beta + \gamma = 1$, we get from here
$2m - n = 1 = 0$.

Solving this equation together with (12), we find $n = \frac{2}{3}$ and $m = \frac{5}{6}$. It remains to substitute these values ​​into expression (10) for $\overrightarrow{MN}$; we get
$\overrightarrow{MN} = \frac{2}{3}\overrightarrow{c} + \frac{1}{3}\overrightarrow{b} - \frac{5}{6}\overrightarrow{d}$;

after a simple calculation we find $|MN| = \frac{a\sqrt{23}}{6}$.

IV basic ratio. If $M$ is the point of intersection of the triangle medians $ABC$ and $O$ is an arbitrary point in space, then the equality holds:
$\overrightarrow{OM} = \frac{1}{3}\left(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC}\right)$.

This relationship is formulated and proven in the textbook “Geometry 9” (§ 22, problem 2).

Problem 4 (Kiev Polytechnic Institute, 1978). A circle is circumscribed around an equilateral triangle whose side is $a$. Prove,

⟦folio 49⟧

Chimo the sum of squared distances from an arbitrary point on the circle to the vertices of this triangle is equal to $2a^2$.

Solution. Let $D$ be an arbitrary point on the circle (Fig. 7). Let's put $|DA| = x; |DB| = y; |DC| = z$.

Then, by the cosine theorem, we have:
from $\Delta ADB: a^2 = x^2 + y^2 - xy,$
from $\Delta BDC: a^2 = y^2 + z^2 - yz,$
from $\Delta ADC: a^2 = x^2 + z^2 + xz$.

Adding these equalities piece by piece, we get
$3a^2 = 2(x^2 + y^2 + z^2) - xy - yz + zx.$ (14)

By virtue of the IV main relation
$\overrightarrow{DO} = \frac{1}{3} (\overrightarrow{DA} + \overrightarrow{DB} + \overrightarrow{DC})$,

where $O$ is the center of the circle.

By squaring both sides of this equality, we get
$|\overrightarrow{DO}|^2 = \frac{1}{9} (\overrightarrow{DA}^2 + \overrightarrow{DB}^2 + \overrightarrow{DC}^2) + 2\overrightarrow{DA} \cdot \overrightarrow{DB} + 2\overrightarrow{DB} \cdot \overrightarrow{DC} + 2\overrightarrow{DC} \cdot \overrightarrow{DA})$.

Since $|DO|$ is the radius of a circle circumscribed about an equilateral triangle whose side is equal to $a$, then $|\overrightarrow{DO}|^2 = |DO|^2 = \frac{1}{3} a^2$.

Because
$\frac{a^2}{3} = \frac{1}{9} (x^2 + y^2 + z^2 + xy + yz - zx)$

or
$3a^2 = x^2 + y^2 + z^2 + xy + yz - zx$.

Adding this equality by parts with (14), we get
$6a^2 = 3(x^2 + y^2 + z^2)$,
where
$x^2 + y^2 + z^2 = 2a^2$.

Reader «Kvant» preparing for exams may ask: does he have the right to use “basic relations” when solving exam problems? Of course, yes! However, for the relation I-III it is necessary to enter the using relation in the examination paper. (For the IV relation, of course, it is enough to refer to the textbook.)

To get used to using basic relationships on your own, we recommend solving the following exercises. Of these, 1-2 are solved with the help of I, 3-4 with the help of II, 5-6 with the help of III.

Exercises

1 (MIPT, 1970). In a triangle, $ABC$ bicsectiris $A1$ divides side $BC$ in the ratio $|BD|: |CD| = 2:1$. In what ratio does the median $CE$ divide this bicsectiris?

2 (MSU, Faculty of Biology, 1973). Through the midpoint $M$ of side $BC$ of parallelogram $ABCD$, the area of ​​which is 1, and the vertex $A$, a straight line is drawn intersecting the diagonal $BD$ at point $Q$. Find the area of ​​the quadrilateral $QMCD$.

3 (MIPT, 1977). All edges of the regular feature $ABCA_1B_1C_1$ have length $a$. Consider segments with ends on the diagonals $BC_1$ and $CA_1$ of the side faces, parallel to the plane $ABB_1A_1$.

1) One of these segments is drawn through the point $M$ of the diagonal $BC_1$ such that $|BM|: |BC_1| = 1:3$. Find its length.

2) Find the shortest length of all segments under consideration.

4 (MIPT, 1977). The base side $ABCD$ of a regular straight line $SABCD$ has length $a$, and the side edge has length 2a. Consider segments with ends on the diagonal $BD$ of the base and the side edge $SC$, parallel (SAD).

Find the shortest length of all segments under consideration.

5 (MIPT, 1978). In the correct direct feature $ABCA_1B_1C_1$, the length of the side of the base is 4a, the length of the side edge is $a$. Points $D$ and $E$ are the midpoints of edges $A_1B_1$ and $BC$. The segment $MN$ with ends on the lines $AC$ and $BB_1$ intersects the line $DE$ and is perpendicular to it. Find the length of this segment.

6 (MIPT, 1978). The length of the cube edge $ABCDA_1B_1C_1D_1$ is equal to $a$. Points $P, K, L$ are the midpoints of edges $AA_1, A_1D_1, B_1C_1$, respectively, points $Q$ are the center of face $CC_1D_1D$. The segment $MN$ with ends on the lines $AD$ and $KL$ intersects the line $PQ$ and is perpendicular to it. Find the length of this segment.
