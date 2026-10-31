---
id: 1975-1-dorofeev-otnosheniya-otrezkov-ploschadey-i-obemov-20250db1
issue: kvant_1975_1
year: 1975
number: "1"
title: Relationships between segments, areas and volumes
authors:
  - Дорофеев Г. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 57
page_last: 61
page_labels: 55-59
tag: 49O9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0a3dcfd4c692599125fd4ef88b25ba0ee444ac200e1d96607b9fb6d39384dc12
prompt_sha256: draft-1
translated_from: content/ru/1975/01/articles/17_dorofeev-otnosheniya-otrezkov-ploschadey-i-obemov-20250db1.md
source_content_sha256: 80efba6a3da1b5f2506983e0fb413cb391592e53ada155487c93a51d95c1b86c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

## Relationships between segments, areas and volumes
G. V. Dorofeev

The school geometry course program, as is known, is structured in such a way that students in the ninth and tenth grades solve mainly problems in stereometry, and planimetric problems appear in their practice only in connection with the use of trigonometry. This, of course, is completely natural, but this state of affairs does not have the best effect on entrance exams: applicants, having coped well with problems that can be subject to direct (sometimes very cumbersome) trigonometric calculations, become stumped by relatively simple problems, the solution of which only requires active knowledge of standard and, in general, well-known theorems of planimetry.

This leads to an obvious conclusion: when preparing for entrance exams, special attention should be paid to activating the geometric knowledge acquired in grades 6–8; more problems that require “purely geometric” ideas should be solved.

Let us emphasize right away that we are not talking about any opposition between purely geometric and trigonometric methods for solving problems. On the contrary, it is their reasonable combination that can be most successful, and then in exams there will be no desire to solve a simple geometric problem using puzzling calculations or, conversely, to consider numerous similar triangles in problems where the introduction of trigonometric functions is a natural and justified path to a solution. Learning to intelligently combine these methods is the main task when preparing for entrance exams.

In this article we will look at problems related to dividing segments, areas and volumes in some respect. We will make sure that tasks of this kind are not at all difficult and, in any case, their objective complexity does not correspond to the difficulties that they usually cause for applicants.

Let's start with a very simple problem, which, however, very few applicants have solved.

Problem 1 (MSU, geological department, 1964). *Point K divides the median AD of triangle ABC in a ratio of 3:1, counting from the vertex. In what ratio does line BK divide the area of ​​triangle ABC?*

It is not difficult to notice that triangles $BAE$ and $BEC$ (Fig. 1) have a common vertex, and their bases lie on the same straight line, so that the required ratio of their areas is equal to the ratio of the lengths of the segments $AE$ and $EC$, and thus, it is required to find out in what ratio the straight line $BE$ divides the side $BC$.

⟦column⟧

It seems quite obvious that the direct computational path (introduce, for example, auxiliary

⟦figure⟧
Fig. 1.

⟦folio 55⟧

body elements - lengths of sides or sizes of angles) is associated with great difficulties and is unlikely to lead to success. At the same time, a purely geometric idea of ​​a solution is naturally sought. In fact, we need to find out in what ratio one side of the angle $DAC$ is divided, and we know that its second side is divided into 4 equal segments. And now the theorem about dividing the sides of an angle by parallel lines cannot help but come to mind, and, of course, it is completely natural to draw straight lines parallel to $BK$ through the points of dividing the median. Then four equal segments appear on side $AC$. As for the fifth segment $FC$, we still need to take advantage of the fact that $AD$ is the median, so $DF$ is the midline of triangle $BCE$, and therefore $FC = EF$.

Thus, side $AC$ is divided into 5 equal segments, and the required ratio is $3 : 2$.

If we further think about the proposed solution, it becomes clear that a more general problem can be solved in the same way: instead of the relation $3 : 1$, we can consider an arbitrary division of the segment $AD$, and moreover, what is essential in the solution is not that $AD$ is the median, but only that the point $D$ divides $BC$ in a certain ratio.

Solve this more general problem yourself.

⟦figure⟧
Fig. 2.

⟦folio 56⟧

⟦column⟧

Problem 2. *On the lateral sides $AB$ and $AC$ of the isosceles triangle $ABC$ the points $K$ and $L$ are taken so that $AK : KB = 2$, $AL : LC = 1/2$. In what ratio does the line $KL$ divide the height $AD$?*

The idea of ​​solving this problem is the same as the previous one, and the solution itself is obvious from figure 2: the required ratio is $2x : (x + y)$, and by condition $\dfrac{2x}{x + 2y} = \dfrac{1}{2}$, whence $3x = 2y$, and therefore,

$$\frac{2x}{x + y} = \frac{2}{1 + \dfrac{y}{x}} = \frac{4}{5}.$$

And again it turns out that in fact we were solving a more general problem: we needed the equality of the sides of the triangle $ABC$ only in order to consider the height $AD$ to be a median, so that in a similar way we can solve the problem for an arbitrary triangle in which it is known in what ratio the points $D$, $K$ and $L$ divide its sides.

Very often, in tasks offered to applicants, it becomes necessary to calculate the area of ​​the cut-off part of a polygon or the volume of the cut-off part of a polyhedron if the dividing points of the sides or edges are somehow specified. The following statements are extremely useful in these problems:

(1) *If in the triangle $ABC$ $AK = \alpha AB$, $AL = \beta AC$, then*

$$S_{\triangle AKL} = \alpha\beta S_{\triangle ABC}.$$

(2) *If in a triangular pyramid $SABC$ $SK = \alpha SA$, $SL = \beta SB$, $SM = \gamma SC$, then $V_{SKLM} = \alpha\beta\gamma V_{SABC}$.*

Statement (1) is most simply proven by using the formula for the area of ​​a triangle $S = \dfrac{1}{2} bc \sin A$, and statement (2) - by the method of “sequential cutting”: from pyramid $SABC$ one must go to pyramid $SABM$, then to $SALM$ and to $SKLM$. This idea leads to a simple solution to the following problem.

Problem 3 (MSU, geological department, 1968). *In the triangle $ABC$ the bisectors $AD$ and $CF$ of the angles $BAC$ are drawn*

⟦figure⟧
Fig. 3.

⟦figure⟧
Fig. 4.

and $ACB$. *Find the ratio of the areas of triangles $ABC$ and $AFD$, if $AB = 21$, $AC = 28$, $CB = 20$.*

Triangle $AFD$ (Fig. 3) can be obtained from $ABC$ as follows: first triangle $ADB$ is cut off, and from it triangle $AFD$. To calculate the required ratio, we use the theorem that the bisector of the internal angle of a triangle divides the opposite sides into parts proportional to the adjacent sides. We have

$$\frac{BD}{DC} = \frac{BA}{AC} = \frac{3}{4}\ ,\qquad \frac{BF}{FA} = \frac{BC}{CA} = \frac{5}{7}\ ,$$

from where (using derived proportions)

$$\frac{BD}{BC} = \frac{3}{7}\ ,\qquad \frac{BF}{BA} = \frac{5}{12}\ .$$

Hence,

$$S_{\triangle AFD} = \frac{7}{12}\cdot S_{\triangle ABD} = \frac{7}{12}\cdot\frac{3}{7}\times$$

$$\times S_{\triangle ABC} = \frac{1}{4}\,S_{\triangle ABC},$$

so the required ratio is 4.

Problem 4 (MSU, Faculty of Biology, 1970). *Given a triangle $ABC$ of area 1. On its medians $AK$, $BL$ and $CM$ points $P$, $Q$ and $R$ are taken respectively, so that*

$$AP = PK,\ \ BQ = \frac{1}{2}\,QL,\ \ CR = \frac{5}{4}\,RM.$$

*Find the area of ​​triangle $PQR$.*

Let $O$ be the intersection point of the medians (Fig. 4); we calculate the required area as the sum of the areas of three ma-

⟦column⟧

small triangles with vertex $O$. Triangle $OPQ$ is obtained from triangle $OAB$ by cutting off the segments $OP$ and $OQ$ on its sides; at the same time

$$AP = \frac{1}{2}\,AK,\quad AO = \frac{3}{2}\,AK,\ \text{так что}$$

$$OP = \frac{1}{6}\,AK = \frac{1}{4}\,AO. \qquad \text{Аналогично,}$$

$$OQ = \frac{1}{2}\,OB,\ \text{поэтому}$$

$$S_{\triangle OPQ} = \frac{1}{8}\,S_{\triangle OAB}\,.$$

On the other hand, it is easy to see that $S_{\triangle AOB} = \dfrac{1}{3}\,S_{\triangle ABC}$, so

$$S_{\triangle OPQ} = \frac{1}{24}\,.$$

Calculating the areas of triangles $OPR$ and $OQR$ in a similar way, we obtain that $S_{\triangle PQR} = \dfrac{1}{12}$.

Problem 5 (MSU, Faculty of Chemistry, 1970). *In a right triangular prism $ABCA_1B_1C_1$, which has $AC = 6$, $AA_1 = 8$, through the vertex $A$ there is a plane intersecting the edges $BB_1$ and $CC_1$, respectively, at points $M$ and $N$. In what ratio does this plane divide the volume of the prism if $BM = MB_1$ and $AN$ is the bisector of the angle $CAC_1$?*

It is easy to see that the ratio of the volumes of the pyramids $ACBMN$ and $ACBB_1C_1$ is equal to the ratio of the areas of their bases, and to find this ratio it is necessary to find in what ratio the point $N$ divides the edge $CC_1$

⟦folio 57⟧

(Fig. 5). The last relation is easily found: by the Pythagorean theorem $AC_1 = 10$ and by the bisector theorem $CN : NC_1 = 3 : 5$.

Now it is not difficult to calculate that $S_{CBMN} : S_{CBB_1C_1} = 7 : 16$, and therefore
$$V_{ACBMN} = \frac{7}{16}\, V_{ACBB_1C_1}.$$

On the other hand, the pyramid $ACBB_1C_1$ is complemented to the entire prism by the pyramid $AA_1B_1C_1$, the volume of which is $^1/_3$ the volume of the prism, so that the volume of the pyramid $ACBB_1C_1$ is equal to $^2/_3$ the volume of the prism. Therefore, the volume of the pyramid $ACBMN$ is $^7/_{24}$ of the volume of the prism, and the required ratio is $7 : 17$.

Problem 6 (MSU, Faculty of Computational Mathematics and Cybernetics, 1973). *The sphere passes through points A, B, C, D and intersects the segments SA, SB, SC and SD at points $A_1$, $B_1$, $C_1$, $D_1$ respectively. It is known that $SD_1 = 9/4$, $DD_1 = 47/36$, the ratio of the areas of triangles $SA_1B_1$ and $SAB$ is* $15 : 32$, *the ratio of the volumes of pyramids $SB_1C_1D_1$ and $SBCD$ is* $1701 : 4096$, *and the ratio of the volumes of pyramids $SA_1B_1C_1$ and $SABC$ equals* $105 : 256$. *Find segments $SA_1$, $SB_1$, $SC_1$.*

It is easy to understand that the problem is about a quadrangular pyramid

⟦column⟧

$SABCD$, on the edges of which the points $A_1$, $B_1$, $C_1$, $D_1$ (Fig. 6) are taken. To solve the problem, we reduce the confusing data on the relationships between areas and volumes to the relationships of the corresponding segments.

Having drawn up a system of equalities
$$\frac{SA_1}{SA}\cdot\frac{SB_1}{SB} = \frac{15}{32}, \qquad \frac{SB_1}{SB}\cdot\frac{SC_1}{SC}\cdot\frac{SD_1}{SD} = \frac{1701}{4096},$$
$$\frac{SA_1}{SA}\cdot\frac{SB_1}{SB}\cdot\frac{SC_1}{SC} = \frac{105}{256}$$

and given that $SD_1 : SD = 81 : 128$, we find
$$\frac{SA_1}{SA} = \frac{5}{8}, \qquad \frac{SB_1}{SB} = \frac{3}{4}, \qquad \frac{SC_1}{SC} = \frac{7}{8}.$$

On the other hand, the segments $SA$, $SB$, $SC$, $SD$ are secants to the sphere, which is discussed in the problem statement, and therefore the products of these secants with their external parts are equal to the square of the tangent to the sphere drawn from the point $S$ (here we use the obvious, but not proven statement about the tangent and secant for the sphere, its analogy with the corresponding statement for a circle is not, of course, a proof; prove this statement yourself). Thus, $SA_1\cdot SA = SB_1\cdot SB =$
$$= SC_1\cdot SC = SD_1\cdot SD = \frac{9}{4}\cdot\frac{128}{36} = 8.$$

⟦figure⟧
Fig. 5.

⟦figure⟧
Fig. 6.

⟦folio 58⟧

Now it is not difficult to find the required segments:

$$SA_1 = \sqrt{5}, \quad SB_1 = \sqrt{6}, \quad SC_1 = \sqrt{7}.$$

Exercises

**1** (MSU, Faculty of Biology, 1970). The following points are taken on the sides of a convex quadrilateral $ABCD$ of area 1: $K$ on $AB$, $L$ on $BC$, $M$ on $CD$ and $N$ on $DA$. In this case, $AK : KB = 2 : 1$, $BL : LC = 1 : 3$, $CM : MD = 1 : 1$, $DN : NA = 1 : 5$. Find the area of ​​hexagon $AKLCMN$.

**2** (MSU, Faculty of Biology, 1972). In triangle $ABC$, bisectors $AD$ and $BE$ intersect at point $O$. Find the ratio of the area of ​​triangle $ABC$ to the area of ​​quadrilateral $ODCE$, knowing that $BC = a$, $AC = b$, $AB = c$.

**3** (MSU, Faculty of Chemistry, 1972). In triangle $ABC$, angle $A$ is equal to $45^\circ$, and angle $C$ is acute. From the middle of side $BC$ a perpendicular $NM$ is dropped onto side $AC$. The areas of triangles $NMC$ and $ABC$ are in the ratio $1 : 8$. Find the angles of triangle $ABC$.

**4** (MSU, Faculty of Biology, 1972). In parallelogram $ABCD$, point $E$ bisects side $CD$, the bisector of angle $ABC$ intersects segment $AE$ at point $O$. Find the area of ​​the quadrilateral $OBCE$, knowing that $AD = a$, $DE = b$, $\sphericalangle ABO = \alpha$.

**5** (MSU, Faculty of Chemistry, 1970). The plane intersects the side edges $SA$, $SB$, $SC$ of the pyramid $SABC$ at points $K$, $L$, $M$, respectively. In what ratio does this plane divide the volume of the pyramid if $SK : KA = SL : LB = 2 : 1$ and the median $SN$ of the triangle $SBC$ is bisected by this plane?

**6** (MSU, Faculty of Chemistry, 1970). The plane intersects the edges $A_1B_1$, $B_1C_1$ and $BC$ of the triangular prism $ABCA_1B_1C_1$ at points $M$, $N$ and $P$ respectively. In what ratio does this plane divide the volume of the prism if $B_1M : A_1B_1 = 1 : 2$, $B_1N : B_1C_1 = 2 : 3$, $BP : CB = 1 : 3$?

**7.** Formulate statements 1 and 2 from the article (p. 56) for the case when the points $K$, $L$, $M$ lie not on the sides (edges) themselves, but on their extensions.

**8.** (MSU, Faculty of Computational Mathematics and Cybernetics, 1973). Points $A$, $B$, $C$, $D$, $E$, $F$ lie on a sphere of radius $\sqrt{2}$. The segments $AD$, $BE$ and $CF$ intersect at the point $S$, located at a distance of 1 from the center of the sphere. The volumes of pyramids $SABC$ and $SDEF$ are related as $1 : 9$, pyramids $SABF$ and $SDEC$ as $4 : 9$, pyramids $SAEC$ and $SDBF$ as $9 : 4$. Find the segments $SA$, $SB$, $SC$.

**9.** Points $K$, $L$, $M$ divide sides $AB$, $BC$ and $CA$ of triangle $ABC$ respectively in relation to $\alpha : \beta$, $\gamma : \delta$, $\rho : \sigma$ (counting each time from the vertex mentioned first), and $\alpha + \beta = \gamma + \delta = \rho + \sigma = 1$. In what ratio does the line $KM$ divide the segment $AL$? In what ratio does the line $BM$ divide $CK$?

⟦column⟧
