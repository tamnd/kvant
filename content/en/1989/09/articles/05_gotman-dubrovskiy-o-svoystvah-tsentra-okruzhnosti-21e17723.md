---
id: 1989-9-gotman-dubrovskiy-o-svoystvah-tsentra-okruzhnosti-21e17723
issue: kvant_1989_9
year: 1989
number: "9"
title: On the properties of the center of an excircle
authors:
  - Готман Э. Г.
  - Дубровский В. Н.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 40
page_last: 41
page_labels: 38-39
tag: 8DH8
lang: en
source: kvant_digital
extraction: vision
content_sha256: f77e9cbb1cebcedbf10a82dec429260d9ef75f6d178902c895a08dbdc288a124
prompt_sha256: draft-1
translated_from: content/ru/1989/09/articles/05_gotman-dubrovskiy-o-svoystvah-tsentra-okruzhnosti-21e17723.md
source_content_sha256: 82e73ce52bc777efee73c82ee3e1bc74c318b303db4ca216e8074baed1567906
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

On the properties of the center of the outer circle

In this note we will provide a solution to problem M1146. This task in itself is not difficult. But upon closer examination, a long chain of generalizations emerges behind it.

M1146. Point K is the midpoint of side AB of equilateral triangle ABC. Points M and N are taken on sides AC and BC so that ∠MKN=60°. Prove that the perimeter of triangle MCN is equal to half the perimeter of triangle ABC.

Let us immediately take a general case. Let K be a point on the bisector of angle MCN of magnitude γ, with points K and C lying on opposite sides of MN (Fig. 1). Then the following conditions are equivalent:

(1) ∠MKN=(π−γ)/2,
(2) MN=PM+QM, where P and Q are the projections of point K onto the sides of the angle.

Problem M1146 is obtained from here at γ=60° (Fig. 2): in this case, the angle MKN in equality (1) is equal to 60°, and property (2) is equivalent to the equality CM+MN+NC=CP+CQ=2CK cos 30°=3AB/2, i.e. the statement of the problem. Note, by the way, that at γ = 90° problem M851 arises (see «Kvant» No. 3 for 1984).

One proof of the equivalence of (1) and (2) can be obtained by checking △KPM for the angle π−γ in the circle of point K (Fig. 3). As a result, it will go to △KQL (∠PKQ=π−γ), where L is some point on the line CN, and ∠MKL=∠MKQ+∠QKL=

= ∠MKQ+∠PKM=π−γ, NL=NQ+QL=NQ+MP. Therefore, each of conditions (1) and (2) is equivalent to the equality of triangles MKN and LKN. Indeed, these triangles have a common side KN and equal sides KM and KL, and in addition, due to (1) - equal angles (∠MKN=(π−γ)/2 and ∠LKN=∠LKM=∠LKM−∠NKM=π−γ-(π−γ)/2, and due to (2) - equal sides MN and NL=NQ+QL=NQ+MP.

The second proof of the equivalence of (1) and (2) reveals the geometric meaning of the point K. It turns out that conditions (1) and (2) mean that

(3) K is the center of the outer circle of the triangle CMN, i.e. the circle tangent to side MN and extended to sides CM and CN.

In fact, if K is the center of this circle, then P and Q are the points of its tangency with the lines CM and CN. Let R be the point of tangency of the circle with MN (Fig. 4), then, obviously, MP=MR, NQ=NR, and, therefore, property (2) is satisfied. And from the equality of triangles KPM and KRM, KQM and KRN it follows that ∠MKN=∠PKQ/2=(π−γ)/2, i.e. condition (1) is satisfied. Conversely, let the point K satisfy, for example, conditions (1). Let us insert a circle with center K into the corner MCN and draw a tangent M′N′ parallel to MN to it. According to what has been proven, ∠M′KN′=(π−γ)/2 = ∠MKN, but this is only possible if M′=M, N′=N. Thus, from (1) follows (3). It is similarly proven that from (2) follows (3).

⟦folio 39⟧

So, for all tangents $MN$ to the circle inscribed in the angle $C$ with center $K$, drawn from the side of the vertex of the angle, the magnitude of the angle $MKN$, as well as the perimeter of the triangle $CMN$ are constructed (and are equal, respectively, $(\pi - \gamma)/2$ and $CP + CQ = 2CK \cos(\gamma/2)$). Another constant value for all these segments is the product of the ratios in which the points $M$ and $N$ divide the segments $CP$ and $CQ$:

$$\frac{CM \cdot CN}{MP \cdot NQ} = \frac{1}{\sin^2(\gamma/2)}$$

To prove this, we replace that $MK$ and $NK$ are the bisectors of the exterior angles $PMN$ and $QNM$ of the triangle $CMN$ (see Fig. 4). Let's put $\angle CMN = \alpha$, $\angle CNM = \beta$, then from triangles $PKM$ and $CKM$ we get $\angle PKM = \alpha/2$, $\angle CKM = \beta/2$.

According to the theorem of sines

$$\frac{CM}{MP} = \frac{\sin(\beta/2)}{\sin(\alpha/2) \sin(\gamma/2)}$$

$$\frac{CN}{NP} = \frac{\sin(\alpha/2)}{\sin(\beta/2) \sin(\gamma/2)}$$

From these equalities (4) immediately follows.

Another beautiful property of our configuration is revealed if we draw the segment $PQ$ and distance the triangle $RUV$, where $U$ and $V$ are the intersection points of $PQ$ with $KM$ and $KN$ (Fig. 5):

$$U \cap V = \text{основания высот треугольника } KMN, \text{ причем треугольник } RUV \text{ подобен треугольнику } CNM \text{ с коэффициентом } 1/\sin(\gamma/2).$$

Let us outline the proof using a similarity transformation. First, we draw the bisectors of all (internal and external) angles of the triangle $CMN$ and note, in addition to $K$, two more points of their intersection - the centers $K_1$ and $K_2$

Two out-of-shape circles of the triangle $CMN$ (see Fig. 5). Since the bisectors of adjacent angles are perepidiculars, the points $C, M, N$ are the bases of the altitudes of the triangle $KK_2K_1$. Therefore, it is enough for us to indicate a similarity transformation with a coefficient of $k = \sin(\gamma/2)$, transforming $\triangle KK_1K_2$ into $\triangle KNM$ and at the same time $\triangle MNC$ into $\triangle VUR$. Such a transformation is the composition $F$ of the symmetrical relative bisector $l$ of the angle $MKN$ and with the center $K$ and the coefficient $k$.

Indeed, in this case the transformations

$$1^\circ$$ point $K$ remains in place, and lines $KK_1$ and $KK_2$ pass into each other, and $F(K_1) = N$, $F(K_2) = M$ (enter $KN/KK_1 = KM/KK_2 = \cos \angle MKN = \sin(\gamma/2) = k$);

$$2^\circ$$ $F(C) = R$ (since $F(\triangle KK_1K_2) = \triangle KNM$, and $KC$ and $KR$ are the heights of these triangles);

$$3^\circ$$ line $KP$ goes into line $KC$ (they are symmetrical with respect to $l$), and $F(R) = E$, where $E$ is the intersection point of $KC$ and $PQ$ ($KE/KR = KE/KP = \cos \angle PKC = k$), and, therefore.

$$4^\circ$$ straight line $MN$ goes into straight line $PQ$, which means $F(M) = V$, $F(N) = U$.

Try to independently find a “traditional” proof of statement (5) (with auxiliary circles, counting angles, etc.), and also solve the following problem.

1. Prove that conditions (4) and (5) are equivalent to (1), (2) and (3).

2. Show that if in our configuration we take the point $K$ from the very beginning on the same side as the point $C$ from the line $MN$, then conditions (2), (4), (5) will still be equivalent to each other, as well as the conditions

$$\begin{align*}
(1') & \angle MKN = (\pi + \gamma)/2 \\
(3') & K - центр вписанной окружности треугольника CMN.
\end{align*}$$

E. G. Gotman, V. N. Dubrovsky
