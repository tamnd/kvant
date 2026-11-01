---
id: 1978-1-gabovich-gornshteyn-skalyarnoe-umnozhenie-vektorov-00244565
issue: kvant_1978_1
year: 1978
number: "1"
title: Scalar vector multiplication
authors:
  - Габович И. Г.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 54
page_labels: 47, 49, 50, 51, 52
tag: 1RBG
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4669638651172d5d5be2330d5b73efdb8d0ed72cc65594edde305399c37c5def
prompt_sha256: draft-1
translated_from: content/ru/1978/01/articles/16_gabovich-gornshteyn-skalyarnoe-umnozhenie-vektorov-00244565.md
source_content_sha256: 2ce29be6e593c98c2e8a7332d2872ad3e40b5208e0753ac63b0d733546f586d0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

Scalar vector multiplication is one of the basic concepts of vector algebra. Its property is widely used in proving theories and solving problems.

In this article we will illustrate the application of scalar vector multiplication to the solution of geometric problems offered in recent years at entrance exams in the development of the study of vectors set out in the textbook “Geometry 9” edited by Z. A. Skopet. Therefore, we will not dwell on the theory of this issue. Let's move on to solving problems.

Problem 1. (MIPT, 1977). The base side of a regular triangular feature $ABCA_1B_1C_1$ has length $a$. The vertices $M$ and $N$ of the regular triangle $MNPQ$ lie on the line passing through the points $C_1$ and $B$, and the vertices $P$ and $Q$ lie on the line $A_1C$. Find:

1) volume of recognition;
2) the distance between the midpoints of the segments $MN$ and $PQ$.

Solution. Consider the vectors: $\overrightarrow{CA}, \overrightarrow{CB}, \overrightarrow{CC_1}, \overrightarrow{CA_2}$ and $\overrightarrow{BC_1}$ (Fig. 1). Let's denote $\overrightarrow{CA} = \vec{u}, \overrightarrow{CB} = \vec{v}, \overrightarrow{CC_1} = \vec{h}$ and $\overrightarrow{|h|} = h$. It follows from the condition that $\overrightarrow{|u|} = \overrightarrow{|v|} = a$.

Since in a regular tetrahedron (as, indeed, in any regular triangular primina) any two intersecting edges are mutually perpendicular, then $\overrightarrow{CA_1} \perp \overrightarrow{BC_1}$. Therefore $\overrightarrow{CA_1} \cdot \overrightarrow{BC_1} = 0$. But in our notation

$$\overrightarrow{CA_1} = \vec{u} + \vec{h} \text{ и } \overrightarrow{BC_1} = \vec{h} - \vec{v},$$

follow,

$$(\vec{u} + \vec{h}) \cdot (\vec{h} - \vec{v}) = 0,$$

$$\vec{u} \cdot \vec{h} - \vec{u} \cdot \vec{v} + \vec{h}^2 - \vec{h} \cdot \vec{v} = 0.$$

Considering that $\vec{h} \perp \vec{u}, \vec{h} \perp \vec{v}$ and $(\vec{u}, \vec{v}) = \frac{\pi}{3}$, we get

$$h^2 - \frac{a^2}{2} = 0, \text{ или } h = \frac{a}{\sqrt{2}},$$

where is the volume of recognition $V = \frac{a^2 \sqrt{3}}{4} \cdot \frac{a}{\sqrt{2}} = \frac{a^3 \sqrt{6}}{8}$.

Let $K$ and $L$ be the midpoints of the segments $PQ$ and $MN$, respectively. Let's find $|KL|$. Note that $[KL]$ is the common perpendicular of the edges $PQ$ and $MN$ (the proof itself), that is, $|KL|$ is the distance between the skew lines $CA_1$ and $BC_1$.

There are several ways to calculate the distance between intersecting lines. We will determine the required distance using scalar multiplication. At the same time, how

⟦folio 49⟧

Neither $\overrightarrow{HN}$ nor $\overrightarrow{AB}$. Let's denote: $\overrightarrow{HP} = \vec{p}$, $\overrightarrow{HQ} = \vec{q}$ and $\overrightarrow{HR} = \vec{r}$. We express the remaining vectors through $\vec{p}$, $\vec{q}$ and $\vec{r}$. Obviously $|\vec{p}| = |\vec{q}| = 2$ and $|\vec{r}| = 1$.

Let

$$|RA| = x |RF|,$$
$$|HB| = y |HN|.$$

Then $\overrightarrow{RA} = x\overrightarrow{RF}$ and $\overrightarrow{HB} = y\overrightarrow{HN}$.

Obviously, $\overrightarrow{RF} = \frac{1}{2}\vec{p} - \vec{r}$ and $\overrightarrow{HN} = \frac{1}{2}\vec{p} + \frac{1}{2}\vec{q}$ ([HN] is the median in triangle HPQ). Because

$$\overrightarrow{RA} = \frac{x}{2}\vec{p} - x\vec{r},$$
$$\overrightarrow{HB} = \frac{y}{2}\vec{p} + \frac{y}{2}\vec{q}.$$

Let us now express $\overrightarrow{AB}$ through the vectors $\vec{p}, \vec{q}$ and $\vec{r}$:

$$\overrightarrow{AB} = \overrightarrow{AR} + \overrightarrow{RH} + \overrightarrow{HB} = -\overrightarrow{RA} - \overrightarrow{HR} + \overrightarrow{HB} = -\frac{x}{2}\vec{p} + x\vec{r} - \vec{r} + \frac{y}{2}\vec{p} + \frac{y}{2}\vec{q} = \frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}.$$

Since $[AB] \perp [RF]$ and $[AB] \perp [HN]$, then $\overrightarrow{AB} \cdot \overrightarrow{RF} = 0$ and $\overrightarrow{AB} \cdot \overrightarrow{HN} = 0$. Making up a system

$$\begin{cases}
\left(\frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}\right) \times \\
\times \left(\frac{1}{2}\vec{p} - \vec{r}\right) = 0, \\
\left(\frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}\right) \times \\
\times \left(\frac{1}{2}\vec{p} + \frac{1}{2}\vec{q}\right) = 0.
\end{cases}$$

From this system, taking into account that the vectors $\vec{p}, \vec{q}$ and $\vec{r}$ are mutually perpendicular

⟦folio 50⟧

are cular, then $\overrightarrow{AC} \cdot \overrightarrow{BM} = 0$ or
$(\vec{b} - \vec{h}) \cdot (\vec{a} + \vec{h} - \vec{y}) = 0,$
$\vec{a} \cdot \vec{b} + \vec{b} \cdot \vec{h} - \vec{b} \cdot \vec{y} - \vec{a} \cdot \vec{h} -$
$-\vec{h}^2 + \vec{h} \cdot \vec{y} = 0$. (5)

As noted, $\vec{a} \cdot \vec{h} = \vec{h} \cdot \vec{y} = 0$
On the same basis $\vec{b} \cdot \vec{h} = 0$. Therefore, from (5) we have
$$\vec{a} \cdot \vec{b} - \vec{b} \cdot \vec{y} - \vec{h}^2 = 0,$$
$$ab - by - h^2 = 0,$$
$$y = \frac{ab - h^2}{b}.$$ (6)

The value $y$ from (6) is confirmed in (4)
$$h^2 = \frac{a^2b - ah^2}{b},$$

where
$$h = \frac{a\sqrt{b}}{\sqrt{a+b}}.$$

Problem 4 (Ural State University, 1971). The triangle $AOB$ is rotated in its plane around the vertex $O$ by $90^\circ$, with the vertex $A$ stepping into $A'$, and the vertex $B - bB'$. Prove that in triangle $OAB'$ the median of side $AB'$ is the height of triangle $OA'B$ (similarly, the median of side $A'B$ in triangle $OA'B$ is the height of $\Delta OAB'$).

Solution. Let $C$ be the midpoint of $[AB']$ (Fig. 4). Let us prove that $\overrightarrow{OC} \perp \overrightarrow{A'B}$, i.e. $\overrightarrow{OC} \cdot \overrightarrow{A'B} = 0$; we have

Fig. 4.

Fig. 5.

⟦folio 51⟧

$$DP = \frac{a\sqrt{6}}{3}, \quad |PQ| = |MN| = \frac{a}{2}.$$
Let $\varphi$ be the magnitude of the angle between the vectors $\overrightarrow{MN}$ and $\overrightarrow{PQ}$. Let's find the value of $\varphi$ from the definition of scalar multiplication of two vectors

$$\cos \varphi = \frac{\overrightarrow{MN} \cdot \overrightarrow{PQ}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|}.$$

Let's write down the next equality vectors

$$\overrightarrow{MN} = \overrightarrow{MD} + \overrightarrow{DN},$$

$$\overrightarrow{PQ} = \overrightarrow{DQ} - \overrightarrow{DP}.$$

Values ​​$\overrightarrow{MN}$ and $\overrightarrow{PQ}$ from (8) are substituted into (7)

$$\cos \varphi = \frac{(\overrightarrow{MD} + \overrightarrow{DN}) \cdot (\overrightarrow{DQ} - \overrightarrow{DP})}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|} = \frac{\overrightarrow{MD} \cdot \overrightarrow{DQ} + \overrightarrow{DN} \cdot \overrightarrow{DQ} - \overrightarrow{DP} \cdot \overrightarrow{MD}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|} + \frac{-\overrightarrow{DN} \cdot \overrightarrow{DP}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|}.$$

Note that $(\overrightarrow{MD}, \overrightarrow{DQ}) = \frac{2}{3}\pi$ and $(\overrightarrow{DP}, \overrightarrow{MD}) = \pi - \overrightarrow{MDP}$. It is obvious that $\cos MDP = \frac{\sqrt{6}}{3}$ and $\cos NDP = \frac{2\sqrt{2}}{3}$.

Taking into account the above, we get

**Fig. 6.**

$$\cos \varphi = \frac{-\frac{a^2}{8} + \frac{a^2}{4} + \frac{a^2}{3} - \frac{4a^2}{9}}{\frac{a}{2} \cdot \frac{a}{2}} = \frac{1}{18}.$$

$\varphi = \arccos \frac{1}{18}$ is the angle between the segments $MN$ and $PQ$.

Task 6 (MSU, mechanism, 1970). The length of each edge of the triangular pyramid $SABC$ is equal to 1, $[BD]$ is the height of the triangle $ABC$. The equilateral triangle $BDE$ lies in the plane forming an angle $\varphi$ with the edge $AC$, and the points $S$ and $E$ lie on the same side of the plane $ABC$. Find the distance between points $S$ and $E$.

Solution. Let us draw (Fig. 6) in the triangle $BDE$ the height $EM$ and connect the points $O$ and $E$. Through the point $M$ we draw $[MN] \parallel [AC]$ and $[MP] \parallel [SO]$. Since the segments $MN$ and $AC$ are parallel, they make equal angles with the plane $BDE$. Since $[MN] \perp [BD]$ and $[EM] \perp [BD]$, then $\angle EMN$, as is easy to understand, is the angle that $[MN]$ (and, therefore, $[AC]$) makes with the plane $BDE$, that is, $\hat{EMN} = \varphi$. Since $[MP] \parallel [SO]$, then $[MP] \perp (ABC)$ and therefore $[MP] \perp [BD]$ and $[MP] \perp [MN]$. Therefore $\hat{EMP} = 90^\circ + \varphi$. Obviously $\overrightarrow{SE} = \overrightarrow{SO} + \overrightarrow{OM} + \overrightarrow{ME}$.

Let's find the scalar square of the vector $\overrightarrow{SE}$:

$$\overrightarrow{SE}^2 = \overrightarrow{SO}^2 + \overrightarrow{OM}^2 + \overrightarrow{ME}^2 + 2 \cdot \overrightarrow{SO} \cdot \overrightarrow{OM} + 2 \cdot \overrightarrow{SO} \cdot \overrightarrow{ME} + 2 \cdot \overrightarrow{OM} \cdot \overrightarrow{ME}.$$

Obviously $\overrightarrow{SO} \cdot \overrightarrow{OM} = \overrightarrow{OM} \cdot \overrightarrow{ME} = 0$. As it is easy to report, $(\overrightarrow{SO}, \overrightarrow{ME}) = \hat{EMP} = 90^\circ + \varphi$, $|SE|^2 = |SO|^2 + |OM|^2 + |ME|^2 - 2 \cdot |SO| \cdot |ME| \cdot \sin \alpha$. 10).

But $|SO| = \frac{\sqrt{6}}{3}$ is like the height of a regular triangle with edge equal to 1; $|ME| = \frac{3}{4}$ – how the height is correct

⟦folio 52⟧

of the triangle from the side equal to $\frac{\sqrt{3}}{2}$; $|OM| = \frac{\sqrt{3}}{12}$ (calculate yourself).

We substitute the found values ​​$|SO|, |OM|$ and $|ME|$ into (10):

$$|SE|^2 = \left(\frac{\sqrt{6}}{3}\right)^2 + \left(\frac{\sqrt{3}}{12}\right)^2 + \frac{9}{16} - 2 \cdot \frac{\sqrt{6}}{3} \cdot \frac{3}{4} \sin \varphi = \frac{5 - 2\sqrt{6} \sin \varphi}{4},$$

$$|SE| = \frac{1}{2} \sqrt{5 - 2\sqrt{6} \sin \varphi}.$$

Problem 7 (MIPT, 1974.) The side of the base of a right triangular feature $ABCA_1B_1C_1$ is equal to $a$; the points $O$ and $O_1$ are the centers of the bases $ABC$ and $A_1B_1C_1$ respectively. The length of the orthogonal projection of the segment $AO_1$ onto the line $B_1O_1$ is equal to $\frac{5}{6}a$. Determine the height of the sign.

Solution. Let's put $|OO_1| = H$. It is obvious (Fig. 7) that $|\overrightarrow{AO}| = |\overrightarrow{OB}| = \frac{a\sqrt{3}}{3}$ and $|\overrightarrow{OB}_1| = \sqrt{\frac{a^2}{3} + H^2}$. Next $\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = |AO_1| \cdot |OB_1| \cdot \cos \varphi$. (11)

It is known that the projection of one vector onto another is equal to the length of the first vector multiplied by the cosine of the angle between the directions of the vectors, that is, $\pi \overrightarrow{OB}_1 \cdot \overrightarrow{AO}_1 = |\overrightarrow{AO}_1| \times \cos \varphi = |\overrightarrow{AO}_1| \cdot \cos \varphi$.

According to the problem conditions

$$\pi \overrightarrow{OB}_1 \cdot \overrightarrow{AO}_1 = \frac{5a}{6}.$$

Therefore, equality (11) is written as follows:

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = |OB_1| \cdot \frac{5a}{6}.$$

Let us write down the following equalities:

$$\overrightarrow{AO}_1 = \overrightarrow{AO} + \overrightarrow{OO_1},$$

$$\overrightarrow{OB}_1 = \overrightarrow{OB} + \overrightarrow{BB_1}.$$

Thus,

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = (\overrightarrow{AO} + \overrightarrow{OO_1}) \cdot (\overrightarrow{OB} + \overrightarrow{BB_1}) = \overrightarrow{AO} \cdot \overrightarrow{OB} + \overrightarrow{AO} \cdot \overrightarrow{BB_1} + \overrightarrow{OO_1} \cdot \overrightarrow{OB} + \overrightarrow{OO_1} \cdot \overrightarrow{BB_1}.$$

Since $\overrightarrow{AO} \perp \overrightarrow{BB_1}$ and $\overrightarrow{OO_1} \perp \overrightarrow{OB}$, then $\overrightarrow{AO} \cdot \overrightarrow{BB_1} = \overrightarrow{OO_1} \cdot \overrightarrow{OB} = 0.$

Moreover, $\overrightarrow{OO_1} = \overrightarrow{BB_1}$ therefore $\overrightarrow{OO_1} \cdot \overrightarrow{BB_1} = |OO_1|^2$,

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = \overrightarrow{AO} \cdot \overrightarrow{OB} + |OO_1|^2 = \frac{a\sqrt{3}}{3} \cdot \frac{a\sqrt{3}}{3} \cdot \frac{1}{2} + H^2 = \frac{a^2}{6} + H^2.$$

We substitute the found values ​​$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1$ and $|OB_1|$ into (12) $\frac{a^2}{6} + H^2 = \frac{5a}{6} \sqrt{\frac{a^2}{3} + H^2}$, whence $108H^4 = -39a^2H^2 - 22a^4 = 0$. Since $H > 0$, then $H = \frac{a\sqrt{6}}{3}$.

1 (MIPT, 1977). The base of the right triangular feature $ABCA_1B_1C_1$ is an equilateral right triangle with legs $|AC| = |BC| = a$. The vertices $M$ and $N$ of the regular tetrahedron $MNPQ$ lie on the line $CA_1$, and the vertices $P$ and $Q$ lie on the line $AB_1$. Find: 1) volume of straight lines; 2) the distance between the midpoints of the segments $MN$ and $PQ$.

2 (MIPT, 1977). The length of the cube edge $ABCDA_1B_1C_1D_1$ is equal to $a$. Point $E$ is the middle of edge $AD$. The vertices $M$ and $N$ of the regular tetrahedron $MNPQ$ lie on the line $ED_1$, and the vertices $P$ and $Q$ lie on the line passing through the point $A_1$ and intersecting the line $BC$ at the point $R$.

Find: 1) relation $|BR| : |BC|$; 2) the distance between the midpoints of the segments $MN$ and $PQ$.

3 (MIPT, 1969). In a regular tetrahedron $ABCD$, the segment $MN$ connects the midpoint of edge $AC$ with the center of face $BCD$, and the point $E$ lies at the midpoint of edge $AB$. Find the angle between the segments $MN$ and $DE$.

4 (Faculty of Physics, Moscow State University, 1963). Two segments – $AB$ of length $a$ and $CD$ of length $b$ lie on skew lines, the angle between which is $a$. The bases $O$ and $O_1$ of the common perpendicular of length $c$ to these lines divide the segments $AB$ and $CD$ so that $|OA| : |OB| = 2:3$ and $|OO_1| : |C_1D| = 3:2$. Find the lengths of the segments $BD$ and $BC$.

5 (From tasks 3FTSH). In a regular 4-angled rectangle $SABCD$, the length of the common perpendicular of the edges $SA$ and $BC$ is $d$ and its base divides the segment $BC$ in the ratio 1:3. Determine the volume of straight lines.

6 (Kyiv Polytechnic Institute, 1977). In the plane of the straight line $ABCD$ a point $M$ is given. Prove that $\overrightarrow{MA} \cdot \overrightarrow{MC} = \overrightarrow{MB} \cdot \overrightarrow{MD}$.

7 (Weight-Union Olympics 1974). Given a square $ABCD$. Points $P$ and $Q$ lie respectively on sides $AB$ and $BC$, with $|BP| = |BQ|$. Let $H$ be the base of the perpendicular dropped from the point $B$ to the segment $PC$. Prove that angle $DHQ$ is a right angle.
