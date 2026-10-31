---
id: 1976-5-belyiy-klyuch-k-resheniyu-podobnyie-treugolniki-4febba7c
issue: kvant_1976_5
year: 1976
number: "5"
title: The “key” to the solution is similar triangles
authors:
  - Белый С. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 59
page_last: 62
page_labels: 57, 60
tag: IVDE
lang: en
source: kvant_digital
extraction: vision
content_sha256: ab655ae1abc3b785612b8d60a2879d31c6f12f81325659f74d81d7939a22eebc
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/12_belyiy-klyuch-k-resheniyu-podobnyie-treugolniki-4febba7c.md
source_content_sha256: ae70afb25494bd2c06935835b034c8e732a881c5a305b008eb9b82eef55c51f6
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 57⟧

Any problem (not only mathematical!) seems to us more or less difficult only until we manage to find the “key” to the solution. When solving geometric problems, such a “key” is often similar triangles. In one problem, such triangles are given in the conditions, in others they are “disguised” and therefore are not immediately noticeable; There are also problems in which there are no such triangles at all; to obtain them, you need to make some additional constructions.

“Starting to “see” such triangles is very useful - they usually make solving a problem easier.

Before reading the solutions to the problems discussed below, try to solve each of them yourself.

Task 1. Inside triangle ABC, an arbitrary point O is taken and three lines parallel to the sides of the triangle are drawn through it. These lines divide triangle ABC into six parts, of which triangle A'B'C' is formed.

The radii of the circles inscribed in these triangles are equal to $r_1, r_2, r_3$; The radius of a circle inscribed in triangle ABC is equal to r. Prove that $r = r_1 + r_2 + r_3$.

It is immediately clear that the constructed triangles are similar to triangle ABC (see Fig. 1), therefore

$$\frac{r_1}{r} = \frac{FO}{AC}; \quad \frac{r_2}{r} = \frac{ED}{AC}; \quad \frac{r_3}{r} = \frac{OH}{AC}.$$

Adding these equalities term by term, we get

$$\frac{r_1 + r_2 + r_3}{r} = \frac{FO + ED + OH}{AC} = \frac{AE + ED + DC}{AC} = 1,$$

whence $r_1 + r_2 + r_3 = r$.

Problem 2. Prove that the altitudes of an acute triangle are bicsectrices of the triangle formed by the segments connecting the bases of the altitudes.

From the similarity of triangles $AB'B$ and $AC'C$ (see Fig. 2) it follows that $\frac{AC'}{AB'} = \frac{AC}{AB}$, therefore triangles $AC'B'$ and $ABC$ are similar, since they have a common angle A, and the sides enclosing this angle are proportional. Similarly, we can prove that the triangles $CA'B'$ and $ABC$, $BA'C'$ and $ABC$ are similar. Therefore, $\triangle AB'C' = \triangle CB'A' = \triangle ABC$, hence $\triangle C'B'B' = \triangle A'B'B'$. Similarly, it is proved that $A'A$ and $C'C$ are bicectors of triangle $A'B'C'$.

⟦folio 60⟧

Fig. 8.

Problem 8 (MIPT, 1970). In ABCD (AB and CD are bases) AB = a, CD = b (a < b). The circle passing through vertices A, B and C touches side AD. Find the diagonal AC.

Note that $\Rightarrow ACD = \Rightarrow BAC$ (as lying crosswise), $\Rightarrow ABC = \Rightarrow CAD$ (both of them change the positive arc AEC, see Fig. 8). Therefore, triangles ABC and CAD are similar. Therefore $\frac{AB}{AC} = \frac{AC}{DC}$, hence $AC = \sqrt{ab}$.

Problem 9 (MAI, 1972). In ABCD, diagonals AC and BD are drawn, intersecting at point F. From vertex C, a straight line CK is drawn, parallel to the lateral side AD, and we intersect BD at point L so that DF = BL. Find the AB:CD ratio.

Let us denote the required relation by $x$. Then from the similarity of triangles AFB and CFD (see Fig. 9) we obtain $\frac{AB}{CD} = \frac{AF}{CF} = \frac{FB}{DF} = \frac{FL + LB}{DF} = \frac{FL + DF}{DF}$, whence $\frac{FL}{DF} = x - 1$. On the other hand, from the similarity of triangles ADF and CLF

$$\frac{FL}{DF} = \frac{FC}{AF} = \frac{1}{x}.$$

Therefore, to determine $x$ we obtain the quadratic equation $x^2 - x - 1 = 0$, whence $x = \frac{1 + \sqrt{5}}{2}$ (since $x > 0$).

Problem 10 (MIPT, 1973). In triangle ABC, through base D of height BD, a straight line is drawn parallel to side AB until it intersects with side BC at point K. Find the ratio BK:KC if the area of ​​triangle BDK is $\frac{3}{16}$ of the area of ​​triangle ABC.

Let us denote the required relation by $x$. Let's do DL || BC (see Fig. 10) and note that $x = \frac{BK}{KC} = \frac{AD}{DC}$. Next, we solve the problem of using similar triangles ABC, ALD and DKC: on one side, $S_{\triangle ALD} + S_{\triangle DKC} = S_{\triangle ABC} - 2S_{\triangle BDK} = \frac{5}{8} S_{\triangle ABC}$, and on the other, $S_{\triangle ALD} + S_{\triangle DKC} = S_{\triangle ABC} \cdot \frac{x^2 + 1}{(x + 1)^2}$, from here we get the equation $\frac{x^2 + 1}{(x + 1)^2} = \frac{5}{8}$, or $3x^2 - 10x + 3 = 0$, $x_1 = 3$, $x_2 = \frac{1}{3}$.
