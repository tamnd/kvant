---
id: 1978-3-ovchinnikov-prinadlezhnost-tochek-pryamoy-i-ploskosti-ecf29961
issue: kvant_1978_3
year: 1978
number: "3"
title: Belonging of points to a line and a plane
authors:
  - Овчинников С. В.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 55
page_labels: 48, 49, 50, 52, 53
tag: XKRD
lang: en
source: kvant_digital
extraction: vision
content_sha256: a48bca1be5b26819e1c1b752fd02900bd748f2716025cdb5251ef145e6b9f024
prompt_sha256: draft-1
translated_from: content/ru/1978/03/articles/18_ovchinnikov-prinadlezhnost-tochek-pryamoy-i-ploskosti-ecf29961.md
source_content_sha256: 54ea9db5ca115c0ddf6ffd234d0543994b2bd479195c299b96a36a292ccb3beb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

S. Ovchinnikov

Belonging of points to a line and a plane

When solving geometric problems, he often uses the condition that points belong to a straight line or plane. The use of vectors allows us to write these conditions in a simple and compact form. At the same time, in solving the problem there is often no need for rather cunning additional constructions.

In this note, we will derive conditions for points to belong to a line and a plane, and consider examples of their application. Let's start by solving the following problem.

Problem 1 (Faculty of Economics, Moscow State University, 1975). Given triangle ABC. Points M and N are taken on sides AB and BC, respectively; $|AB| = 5|AM|$, $|BC| = 3|BN|$. Segments AN and CM intersect at point O. Find the ratio of the areas of triangles AOC and ABC.

Solution (Fig. 1). Because

$$\frac{S_{AOC}}{S_{ABC}} = \frac{S_{AMC}}{S_{ABC}} \cdot \frac{S_{AOC}}{S_{AMC}} = \frac{|AM|}{|AB|} \cdot \frac{|OC|}{|MC|} = \frac{1}{5} \cdot \frac{|OC|}{|MC|},$$

It is enough for us to determine in what ratio the point O divides the segment MC. Let us draw ME, $E \in [BC]$, parallel to AN; then $\frac{|EN|}{|BN|} = \frac{|AM|}{|AB|} = \frac{1}{5}$.

But $|BN| = \frac{1}{3}|BC|$, where $|EN| = \frac{1}{15}|BC|$ comes from. Next,

$$\frac{|OC|}{|MC|} = \frac{|NC|}{|EC|} = \frac{2/3|BC|}{2/3|BC| + 1/15|BC|} = \frac{10}{11}.$$

Means,

$$\frac{S_{AOC}}{S_{ABC}} = \frac{1}{5} \cdot \frac{10}{11} = \frac{2}{11}.$$

Note that the majority of applicants were unable to figure out the additional construction of ME || AN and therefore did not solve this problem.

Let's consider another solution based on the result of problem 254 of the Geometry 9 textbook. Let us formulate this result as follows:

Theorem 1. For any choice of point O, the equality

$$\overrightarrow{OC} = \alpha \overrightarrow{OA} + (1 - \alpha) \overrightarrow{OB}$$

(1)

for some number α it is necessary and sufficiently conditional that the points A, B and C ($A \neq B$) belong to the same line. At the same time $\overrightarrow{BC} = \alpha \overrightarrow{BA}$.

Fig. 1.

Fig. 2.

⟦folio 49⟧

Figure 2 illustrates Theorem 1. Note that the value of the coefficient $\alpha$ determines the position of the point on the straight line $(AB)$. If $0 \leqslant \alpha \leqslant 1$, then the point $C$ is between $A$ and $B$; if $\alpha > 1$, then the point $A$ is between $C$ and $B$ and, finally, if $\alpha < 0$, then the point $B$ is between $A$ and $C$. The coefficient $\alpha$ plays the role of a free-knowing coordinate on the straight line $(AB)$: the origin of coordinates is the point $B$, and the scale is given by the segment $BA$, so that the point $A$ has coordinate one.

Let's return to problem 1, denote $\overrightarrow{BA} = \vec{p}$ and $\overrightarrow{BC} = \vec{q}$. Then $\overrightarrow{BM} = \frac{4}{5} \vec{p}$ and $\overrightarrow{BN} = \frac{1}{3} \vec{q}$. Since the point $O$ belongs to the lines $AN$ and $CM$, then
$$\overrightarrow{BO} = \alpha_1 \overrightarrow{BM} + (1 - \alpha_1) \overrightarrow{BC} = \alpha_2 \overrightarrow{BA} + (1 - \alpha_2) \overrightarrow{BN},$$
i.e.
$$\frac{4}{5} \alpha_1 \vec{p} + (1 - \alpha_1) \vec{q} = \alpha_2 \vec{p} + \frac{1}{3} (1 - \alpha_2) \vec{q},$$
where
$$\begin{cases} \frac{4}{5} \alpha_1 = \alpha_2, \\ 1 - \alpha_1 = \frac{1}{3} (1 - \alpha_2). \end{cases}$$
Solving the resulting system, we find $\alpha_1 = \frac{10}{11}, \alpha_2 = \frac{8}{11}$. By Theorem 1
$$\overrightarrow{CO} = \alpha_1 \overrightarrow{CM} = \frac{10}{11} \overrightarrow{CM},$$
where

Fig. 3.

Fig. 4.

⟦folio 50⟧

$$= \frac{10}{3}.$$ Denoting $BCD$ by φ, from the triangle $ECF$ we find $\cos \varphi = \frac{1}{10}$ using the cosine theorem. Given the value of cosф, we calculate the diagonals $|AC| = \sqrt{45}$ and $|BD| = \sqrt{37}$ using the cosine theorem.

Problem 3*). Given a triangle $ABC$ and a point $M$ on side $BC$. Prove that $|AM| \cdot |BC| \leq |AB| \cdot |MC| + |AC| \cdot |BM|$.

Solution (Fig. 4). We have $\overrightarrow{AM} = \alpha \overrightarrow{AB} + (1-\alpha) \overrightarrow{AC}$.

Since $\alpha = \frac{|MC|}{|BC|}$, then $1-\alpha = \frac{|BM|}{|BC|}$. Next, $\left| \overrightarrow{AM} \right| = \left| \alpha \overrightarrow{AB} + (1-\alpha) \overrightarrow{AC} \right| \leq \alpha \left| \overrightarrow{AB} \right| + (1-\alpha) \left| \overrightarrow{AC} \right| = \frac{|MC|}{|BC|} \cdot |AB| + \frac{|BM|}{|BC|} \cdot |AC|$, from which the statement of the problem follows.

Theorem 1 allows the following generalization to the case of space.

Theorem 2. Let $A, B$ and $C$ be pairwise distinct points that do not lie on the same line. For any choice of point $O$ the equality
$$\overrightarrow{OD} = \alpha \overrightarrow{OA} + \beta \overrightarrow{OB} + (1-\alpha-\beta) \overrightarrow{OC} \text{ является необходимым и достаточно условием принадлежности точки } A, B, C \text{ и } D \text{ одной плоскости}.$$
Proof 1) Sufficiency. Let (2) be fulfilled. We find $\overrightarrow{OD} - \overrightarrow{OC} = \alpha (\overrightarrow{OA}-\overrightarrow{OC}) + \beta (\overrightarrow{OB}-\overrightarrow{OC})$, from where $\overrightarrow{CD} = \alpha \overrightarrow{CA} + \beta \overrightarrow{CB}$. Thus, the vectors $\overrightarrow{CA}, \overrightarrow{CB}$ and $\overrightarrow{CD}$ are coplanar and, therefore, the points $A, B, C$ and $D$ belong to the same plane.

2) Necessity. If $A, B, C$ and $D$ belong to the same plane, then the vectors $\overrightarrow{CA}, \overrightarrow{CB}$ and $\overrightarrow{CD}$ are coplanar. Since the points $A, B$ and $C$ are pairwise distinct and do not lie on the same line, the vectors $\overrightarrow{CA}$ and $\overrightarrow{CB}$ are non-collinear.

*) This problem was proposed by I. Sharygin.

Fig. 5.

⟦folio 52⟧

Subtract the volumes of pyramids $LAFN$ and $DB_1KM$. Let $V$ be the volume of the prism. From previous calculations we know the correspondences between the heights $|LA_1|$, $|DB_1|$, $|LA|$ of the pyramids $LA_1EM$, $LAFN$, $DB_1KM$ and the height of the prism, as well as the correspondences between the areas of the bases. This makes it easy to find that $V_{LA_1EM} = \frac{3}{8}V$, $V_{LAFN} = \frac{1}{72}V$ and $V_{MKB_1D} = \frac{1}{48}V$, whence the volume of the polyhedron $AEKB_1DNAF$ is equal to $\frac{3}{8}V - \frac{1}{72}V - \frac{1}{48}V = \frac{49}{144}V$. So, the cutting plane divides the volume of the prism in a ratio of 49:95.

Note, firstly, that in our solution the condition that the prism is correct was not used anywhere. Secondly, our solution method is also suitable in the case when the points $E$ and $N$ are not the midpoints of the edges $A_1C_1$ and $AB$, while the solution with additional constructions *) makes significant use of this circumstance (the prime $EP$ intersects $BB_1$ at the point $D$ because $|A_1E| = |EC_1|$).

An attentive reader may have noticed, comparing Theorems 1 and 2, that in Theorem 1 the coefficient $\alpha$ was dado simply a geometric origin, while the geometric meaning of the coefficients $\alpha$ and $\beta$ in Theorem 2 remains unclear. We have taken advantage of this gap in one important particular case, leaving the generalization to the reader.

Theorem 3. If, under the conditions of Theorem 2, the point $D$ lies in the triangle $ABC$, then from the equality
$$\overrightarrow{OD} = \alpha \overrightarrow{OA} + \beta \overrightarrow{OB} + (1 - \alpha - \beta) \overrightarrow{OC} \text{ следует}$$
$$\begin{cases} \alpha = S_{BDC}: S_{ABC}, \\ \beta = S_{ADC}: S_{ABC}, \\ 1 - \alpha - \beta = S_{ADB}: S_{ABC}. \end{cases}$$

*) Compare the solution to this problem with that given in the book by G.V. Dorofeev, M.K. Potapov, N.Kh. Rozov “Mathematics manual for constructing problems”, Moscow, 1976, section 3, § 6, task 7 (p. 514).

⟦folio 53⟧

Fig. 8.

Proof (Fig. 8). As follows from the proof of Theorem 2 $\vec{CD} = \alpha \vec{CA} + \beta \vec{CB}$. Let's put $\vec{CK} = \alpha \vec{CA}$, $\vec{CL} = \beta \vec{CB}$. From figure 8 it is clear that $S_{ADC} : S_{ABC} = \beta$ and $S_{BDC} : S_{ABC} = \alpha$. From these equalities it easily follows that $S_{ADB} : S_{ABC} = 1 - \alpha - \beta$.

Task and

1. (Geofak, Moscow State University, 1966). Point $K$ divides median $AD$ of triangle $ABC$ in a ratio of 3:1, counting from the vertex. In what ratio does the line $BK$ divide the plane of triangle $ABC$?

2. (Geofak, Moscow State University, 1974). Given a regular quadrangular line $PABCD$ with vertex $P$. On the edges $PA$ and $PC$ the points $K$ and $M$ are taken, respectively, and $|AK| : |KP| = 1:3$, $|CM| = |PM|$. Find the ratio in which the edge $PB$ is divided by the plane drawn through the points $D$, $K$ and $M$.

3. (Chemistry Department, Moscow State University, 1970). The plane passes through the vertex $A$ of the base of the triangular line $SABC$, bisects the median $SK$ of the triangle $SAB$, and intersects the median $SL$ of the triangle $SAC$ at the point $D$ such that $|SD| = \frac{1}{2} |DL|$. In what ratio does this plane divide the volume of a straight line?

Amendment. There was a typo in the conditions problem M483, which describes the problem «Kvant» («Kvant», 1978, No. 1). Below we place the correct condition for this problem. The deadline for sending its decision is extended until May 1, 1978.

4. (Geofak, Moscow State University, 1976). In the parallelogram $ABCD$ with diagonals equal to $|AC| = 6$ and $|BD| = 24$, a segment $EF$ is drawn connecting the point $E$ of the diagonal $AC$ with the point $F$ of the side $BC$. Points $E$ and $F$ are chosen such that $\frac{|FC|}{|BF|} = \frac{1}{2}, \frac{|EA|}{|EF|} = \frac{1}{3}$. It is known that the point $M$ of intersection of the diagonal $BD$ with the segment $EF$ divides it in the ratio $\frac{|EM|}{|MF|} = \frac{1}{2}$. Find the sides of the parallelogram.

5. Given a triangle $ABC$. On the side $AB$ we take the point $D$, and on the side $BC$ we take the points $E$ and $F$ so that $|AD| : |DB| = 3:2, |BE| : |EC| = 1:3$ and $|BF| : |FC| = 4:1$. In what ratio does the line $(AE)$ divide the segment $DF$?

6. (Mekhmat, Moscow State University, 1964). Given a cube $ABCDA_1B_1C_1D_1$, where $AA_1, BB_1, CC_1, DD_1$ are the side edges. In what ratio does the volume of the cube divide by the plane passing through the vertex $A$, the middle of the edge $BC$ and the center of the face $DCC_1D_1$?

7. (Mekhmat, Moscow State University, 1965). Given a regular quadrangular line $SABCD$ with vertex $S$. A plane is drawn through the midpoints of edges $AB, AD$ and $CS$. In what ratio does this plane divide the volume of a straight line?

8. Inside the triangle $ABC$ the point $O$ is taken. Lines $(AO), (BO)$ and $(CO)$ intersect sides $BC$, $CA$ and $AB$, respectively, at points $P$, $Q$ and $R$. Prove that

$$\frac{|AR|}{|RB|} \cdot \frac{|BP|}{|PC|} \cdot \frac{|CQ|}{|QA|} = 1.$$

9. Points $P$ and $Q$ divide sides $BC$ and $CA$ of triangle $ABC$ in the given ratios:

$$\frac{|BP|}{|PC|} = a, \quad \frac{|CQ|}{|QA|} = b.$$

Let $O$ be the intersection point of lines $AP$ and $BQ$. Find the ratio of the plane quadrilateral $OPCQ$ to the plane triangle $ABC$.

10. Let $OABC$ be a triangular line with vertex $O$, and $M$ a point inside triangle $ABC$. Then

$$|OM| \cdot S_{ABC} \leq |OA| \cdot S_{MBC} + |OB| \cdot S_{MAC} + |OC| \cdot S_{MAB}.$$

M483. a) Prove that the ratio of the square of the radius of the inscribed circle of a right triangle to the sum of the squares of the lengths of medians drawn from acute angles does not exceed 1/20.

6) What is the most significant meaning this relationship can take?
