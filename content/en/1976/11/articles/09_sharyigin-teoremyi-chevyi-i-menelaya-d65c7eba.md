---
id: 1976-11-sharyigin-teoremyi-chevyi-i-menelaya-d65c7eba
issue: kvant_1976_11
year: 1976
number: "11"
title: Theorems of Ceva and Menelaus
authors:
  - Шарыгин И. Ф.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 24
page_last: 31
page_labels: 22, 24, 25, 26, 27, 28, 29
tag: 7DBD
lang: en
source: kvant_digital
extraction: vision
content_sha256: a9af473ee709cdb14c1796caa090c6a5d55cfcfccb2ad49874468fa5d2fbdd47
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/09_sharyigin-teoremyi-chevyi-i-menelaya-d65c7eba.md
source_content_sha256: 248dcaa44178532f04d32ae4e049eb2dd0a2f95d1f9291419f2508f358d94c6d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

Geometry starts with a triangle. Taking a school textbook on geometry, we will see that the first meaningful theorems relate specifically to the triangle. All the previous ones are just axioms, definitions or the simplest consequences of them. At the dawn of its appearance, the plan was essentially the “geometry of a triangle.”

“Geometry of a Triangle” can be proud of theorems bearing the names of Euler, Toricelli, and Leibniz. At the turn of the 19th and 20th centuries, thanks to the large number of works devoted to the triangle, even a whole section of planimetrics was formed, called the “New Geometry of the Triangle.” Many of these works now look under-listed and imperfect; The terminology used in them is half-written and is found only in encyclopedias. However, some theorems of the “New Geometry” continue to live to this day. Two such theorems - Cheva's and Menelaus' - are discussed in this article *).

The theorems of Cheva and Menelaus can be called “dual” theorems: they are formulated similarly (with each theorem appearing in two areas) and proven, they are interchangeable when solving problems. The theorems of Cheva and Menelaus turn out to be especially useful in cases where it is necessary to “clarify the relationship” between points and lines - for example, to prove that some three lines intersect at one point, three points lie on the same line, etc.

*) Anyone wishing to get acquainted with the geometry of a triangle in more detail is referred to the book by S. I. Zetel “New Geometry of a Triangle” (M., Uchpedgiz, 1962).

⟦folio 24⟧

Fig. 2.

Proof. First, let's check that $R$ and $R^*$ are of the same sign. It is easy to verify that changing the direction of one of the vectors $a, b, c, a_1, b_1, c_1$ will not change the value $R^*$ ($\omega, \omega_1$), so you can choose the direction of each of them in a certain way; for example, the vectors $a, b, c, a_1, b_1, c_1$ can be considered to coincide in direction with the vectors $\overrightarrow{BC}, \overrightarrow{CA}, \overrightarrow{AB}, \overrightarrow{AA_1}, \overrightarrow{BB_1}$ and $\overrightarrow{CC_1}$ (Fig. 2). In this case, each of the three fractions included in the expression $R(\Delta, \Delta_1)$ has the same sign as the corresponding fraction included in the expression $R^*$ ($\omega, \omega_1$). For example, fractions

$$\left\{ \frac{\overrightarrow{AC_1}}{\overrightarrow{C_1B}} \right\} \text{ и } \frac{\sin \theta (\overrightarrow{b}, \overrightarrow{c_1})}{\sin \theta (\overrightarrow{a}, \overrightarrow{c_1})}$$

will be positive if the point $C_1$ is located between the points $A$ and $B$, and imprinted in the opposite case (Fig. 3 and 2).

It remains to prove that $|R(\Delta, \Delta_1)| = |R^*(\omega, \omega_1)|$. We have

$$\left\{ \frac{\overrightarrow{AC_1}}{\overrightarrow{C_1B}} \right\} = \frac{S_{\Delta ACC_1}}{S_{\Delta BCC_1}} = \frac{1/2 |AC| \cdot |CC_1| \cdot |\sin \theta (\overrightarrow{b}, \overrightarrow{c_1})|}{1/2 |BC| \cdot |CC_1| \cdot |\sin \theta (\overrightarrow{a}, \overrightarrow{c_1})|} = \times \frac{|AC|}{|BC|} \cdot \frac{|\sin \theta (\overrightarrow{b}, \overrightarrow{c_1})|}{|\sin \theta (\overrightarrow{a}, \overrightarrow{c_1})|},$$

$$\left\{ \frac{\overrightarrow{BA_1}}{\overrightarrow{A_1C}} \right\} = \frac{|AB|}{|AC|} \cdot \frac{\sin \theta (\overrightarrow{c}, \overrightarrow{a_1})|}{|\sin \theta (\overrightarrow{b}, \overrightarrow{a_1})|},$$

$$\left\{ \frac{\overrightarrow{CB_1}}{\overrightarrow{B_1A}} \right\} = \frac{|BC|}{|AB|} \cdot \frac{\sin \theta (\overrightarrow{a}, \overrightarrow{b_1})|}{|\sin \theta (\overrightarrow{c}, \overrightarrow{b_1})|}.$$

Fig. 3.

Variable these three equalities, we get that $|R(\Delta, \Delta_1)| = |R^*(\omega, \omega_1)|$. The lemma is proven.

In what follows we will need an equality that follows directly from the definition of $R^*(\omega, \omega_1)$:

$$R^*(\omega, \omega_1) = \frac{1}{R^*(\omega_1, \omega)}. \tag{4}$$

Let us now formulate the theorems of Ceva and Menelaus.

Ceva's theorem. In order for the lines $AA_1, BB_1$ and $CC_1$ to intersect at one point, it is necessary and sufficient that the equality

$$R(\Delta, \Delta_1) = 1, \tag{5}$$

or equivalent equality

$$R^*(\omega, \omega_1) = 1. \tag{5'}$$

Menelaus's theorem. In order for the points $A_1, B_1, C_1$ to lie on the same line, it is necessary and sufficient that the equality

$$R(\Delta, \Delta_1) = -1, \tag{6}$$

or equivalent equality

$$R^*(\omega, \omega_1) = -1. \tag{6'}$$

Proof of Ceva's theorem

Necessity. Let the lines $AA_1, BB_1, CC_1$ intersect at one point. Let us prove that conditions (5) and (5') are satisfied.

*) The expression $R^*(\omega_1, \omega)$ is obtained from the expression $R^*(\omega, \omega_1)$ of the mutual vectors $a$ and $a_1$, $b$ and $b_1$, $c$ and $c_1$.

⟦folio 25⟧

Fig. 4a.

Note that if the lines $AA_1$, $BB_1$ and $CC_1$ intersect at one point, then either all three points $A_1$, $B_1$ and $C_1$ lie on the sides of the triangle $ABC$, or one of the points lies on the side of the triangle, and the other two on the extensions of the corresponding sides. In the first case, all the others included in the expression $R(\Delta, \Delta_1)$ are positive, and in the second case, one of the three fractions included in $R(\Delta, \Delta_1)$ is positive, and the other two are negative, so again the expression $R(\Delta, \Delta_1)$ (and therefore $R^*(\omega, \omega_1)$ - see the lemma) is greater than zero. Let us now prove that $|R^*(\omega, \omega_1)| = 1$ (since $R^*(\omega, \omega_1) > 0$, it will follow that $R^*(\omega, \omega_1)$ is equal to one). Let us denote the intersection point of lines $AA_1$, $BB_1$ and $CC_1$ by $D$ (Fig. 4a). Applying the theorem of sines, we get

$$\frac{\sin \theta \vec{b}, \vec{c}_1}{\sin \theta \vec{b}, \vec{a}_1} = \frac{|DA|}{|DC|},$$

$$\frac{\sin \theta \vec{c}, \vec{a}_1}{\sin \theta \vec{c}, \vec{b}_1} = \frac{|DB|}{|DA|},$$

$$\frac{\sin \theta \vec{a}, \vec{b}_1}{\sin \theta \vec{a}, \vec{c}_1} = \frac{|DC|}{|DB|}.$$

Variable these equalities, we see that $|R^*(\omega, \omega_1)| = 1$. Thus the necessity is proven.

Sufficiency The proof is sufficiently verified by the method

Fig. 46.

"by contradiction." Let us assume that $R(\Delta, \Delta_1) (= R(\omega, \omega_1)) = 1$, but the lines $AA_1$, $BB_1$ and $CC_1$ do not pass through the same point (Fig. 46). Let us denote the point of intersection of lines $AA_1$ and $BB_1$ by $D_1$, and by $C'_1$ the point of intersection of lines $AB$ and $CD_1$. Since lines $AA_1$, $BB_1$ and $CC_1$ intersect at one point,

$$\left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{C'_1}B} \right\} \cdot \left\{ \frac{\overrightarrow{BA}_1}{\overrightarrow{A_1}C} \right\} \cdot \left\{ \frac{\overrightarrow{CB}_1}{\overrightarrow{B_1}A} \right\} = 1.$$

But according to the conditions

$$\left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{CB}_1} \right\} \cdot \left\{ \frac{\overrightarrow{BA}_1}{\overrightarrow{A_1}C} \right\} \cdot \left\{ \frac{\overrightarrow{CB}_1}{\overrightarrow{B_1}A} \right\} = 1,$$

where

$$\left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{CB}_1} \right\} = \left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{CB}_1} \right\}.$$

Since both the point $C_1$ and the point $C'_1$ lie on the line $AB$, it follows that the points $C_1$ and $C'_1$ coincide. Ceva's theorem is proven.

Proof of Menelaus' Theorem

Necessity. It is known that the points $A_1$, $B_1$ and $C_1$ lie on the same line. It is necessary to prove equalities (6) and (6′).

Note again that if the points $A_1$, $B_1$ and $C_1$ lie on the same line, then either they are all on the extensions $BC$, $AC$ and $AB$ side of the triangle.

⟦folio 26⟧

Fig. 5.

nickname $ABC$, or two of the points $A_1, B_1, C_1$ are on the corresponding sides, and the third is on the continuation. In both cases the expression $R(\Delta, \Delta_1)$ will be negative (make sure of this). Let us now prove that if the points $A_1, B_1, C_1$ are on the same line, then $|R(\Delta, \Delta_1)| = 1$ (since $R(\Delta, \Delta_1) < 0$, it will follow that $R(\Delta, \Delta_1) = -1$).

Let us draw through the point $B$ a line parallel to $AC$, and denote the point of its intersection with the line $B_1A_1C_1$ by $D$ (Fig. 5).

Using similarity, it is easy to obtain

$$\left\{ \frac{\overrightarrow{CA_1}}{\overrightarrow{A_1B}} \right\} = \frac{|B_1C|}{|BD|}, \quad \left\{ \frac{\overrightarrow{BC_1}}{\overrightarrow{C_1A}} \right\} = \frac{|BD|}{|AB_1|}.$$

By adding the next equality $$\frac{\overrightarrow{AB_1}}{\overrightarrow{B_1C}} = \frac{|AB_1|}{|B_1C|}$$ and variable all three equalities, we obtain that $|R(\Delta, \Delta_1)| = 1$. The necessity of the conditions of Menelaus's theorem is proven.

The proof of the sufficiency of conditions (6) and (6') of Menelaus' theorem is carried out similarly to the proof of the sufficiency of conditions (5) and (5') of Ceva's theorem.

Somewhat follows

The introduction into the formulation of the theorems of Ceva and Menelaus of two equivalent conditions (5) and (5'), (6) and (6') was made not only to facilitate the proof -

proof of these theorems. In some problems it turns out to be convenient to use one of the conditions, in others - another. Make sure of this by trying to prove the following statement yourself.

Statement 1. If three lines passing through the vertices of a triangle intersect at one point, then the lines symmetric to them with respect to the corresponding bissertrices of the triangle also intersect at one point. If three lines intersect the opposite sides of a triangle at three points located on the same line, then the lines symmetrical to them with respect to the corresponding bissertrices also intersect the opposite sides of the triangle at three points located on the same line.

If we remember equality (4), we can easily prove it.

Statement 2. If three lines passing through vertices A, B and C of triangle ABC parallel to sides $B_1C_1, A_1C_1$ and $A_1B_1$ of triangle $A_1B_1C_1$ intersect at one point, then lines passing through vertices A, $B_1$ and $C_1$ of triangle $A_1B_1C_1$ parallel to sides BC, AC and AB of triangle ABC also intersect at one point. If the lines intersect the corresponding sides of the triangle ABC at three points located on the same line, then this is also the case for the lines passing through the vertices of the triangle $A_1B_1C_1$ parallel to BC, AC and AB (Fig. 6, 7).

Prove it yourself too

Statement 3. If the lines passing through vertices A, B and C of triangle ABC perpendicular to sides $B_1C_1, A_1C_1$ and $A_1B_1$ of triangle $A_1B_1C_1$ intersect at one point, then the lines drawn from vertices A, $B_1$ and $C_1$ of triangle $A_1B_1C_1$ to lines BC, AC and AB are also perpendicular

⟦folio 27⟧

intersect at one point. If the first point of the lines intersects the corresponding sides of the triangle ABC at three points located on the same line, then the lines passing through the vertices of the triangle $A_1B_1C_1$ perpendicular to the sides of the triangle ABC intersect the corresponding sides of the triangle $A_1B_1C_1$ at three points located on the same line (Fig. 8, 9).

Let us give two more examples of using the sides of the triangle $A_1B_1C_1$ perpendicular to the sides of the triangle ABC, intersecting the corresponding sides of the triangle $A_1B_1C_1$ at three points located on the same straight line.

Proof. Let us denote the points of intersection of the lines referred to in the conditions by the letters K, L and M, respectively. We will assume that the lines $A_1A_2$ and $A_4A_5$ $A_2A_3$ and $A_5A_6$ $A_3A_4$ and $A_6A_1$ lie on the same line.

Proof. Let us denote the points of intersection of the lines referred to in the conditions by the letters K, L and M, respectively. We will assume that the lines $A_1A_2$ and $A_4A_5$ $A_2A_3$ and $A_5A_6$ $A_3A_4$ and $A_6A_1$ lie on the same line.

Let's create the following table:

| A | K | $A_1$ | $A_2$ | B |
| :--- | :--- | :--- | :--- | :--- |
| B | $A_4$ | M | $A_3$ | C |
| C | $A_5$ | $A_6$ | L | A |

The letters in each row and each column of this table correspond to points located on the same straight line.

Since points K, $A_4$ and $A_5$ lie on the same line and on sides AB, BC and CA of triangle ABC, conditions (6) must be satisfied, namely:

$$\begin{align*}
\frac{\overrightarrow{AK}}{\overrightarrow{KB}} &\cdot \frac{\overrightarrow{BA}_4}{\overrightarrow{A}_4C} \cdot \frac{\overrightarrow{CA}_5}{\overrightarrow{A}_5A} = -1.
\end{align*}$$

Likewise

$$\begin{align*}
\frac{\overrightarrow{AA}_1}{\overrightarrow{A}_1B} &\cdot \frac{\overrightarrow{BM}}{\overrightarrow{MC}} \cdot \frac{\overrightarrow{CA}_6}{\overrightarrow{A}_6A} = 1,
\end{align*}$$

⟦folio 28⟧

Since the points $A_1, A_2, A_5$ and $A_6$ lie on the same circle and the point $A$ is the intersection point of the lines $A_1A_2$ and $A_5A_6$, then $|AA_1| \cdot |AA_2| = |AA_5| \cdot |AA_6|$. Let us define for collinear vectors $\overrightarrow{AA_i}$ and $\overrightarrow{AA_j}$ the value $\{\overrightarrow{AA_i} \cdot \overrightarrow{AA_j}\}$, equal to the product of the lengths of the vectors $\overrightarrow{AA_i}$ and $\overrightarrow{AA_j}$, taken with the “+” sign if the vectors $\overrightarrow{AA_i}$ and $\overrightarrow{AA_j}$ are connected, and with the “-” sign if they are directed oppositely. Then we can rewrite the last equality in new notation as follows:
$$\{\overrightarrow{AA_1} \cdot \overrightarrow{AA_2}\} = \{\overrightarrow{AA_5} \cdot \overrightarrow{AA_6}\} =
\{A_5A \cdot A_6A\}.$$ (10)

Likewise
$$\{\overrightarrow{BA_4} \cdot \overrightarrow{BA_3}\} = \{\overrightarrow{A_1B} \cdot \overrightarrow{A_2B}\},$$ (11)
$$\{\overrightarrow{CA_5} \cdot \overrightarrow{CA_6}\} = \{\overrightarrow{A_4C} \cdot \overrightarrow{A_3C}\}.$$ (12)

Variable equalities (7) - (9) taking into account equalities (10 - (12) and the fact that, according to the definition, for example, $$\frac{\overrightarrow{BA_4}}{\overrightarrow{A_4C}} \cdot \frac{\overrightarrow{BA_3}}{\overrightarrow{A_3C}} =
\frac{\overrightarrow{BA_4} \cdot \overrightarrow{BA_3}}{\overrightarrow{A_4C} \cdot \overrightarrow{A_3C}}$$, we get $$\frac{\overrightarrow{AK}}{\overrightarrow{KB}} \times
\times \left\{\frac{\overrightarrow{BM}}{\overrightarrow{MC}}\right\} \cdot \frac{\overrightarrow{CL}}{\overrightarrow{LA}} = -1$$, which by theorem

Menelaus means that the points $K, L$ and $M$ belong to the same straight line.

The case when the lines $A_1A_2, A_3A_4$ and $A_5A_6$ intersect at one point (and thus do not form a triangle $ABC$), you can analyze on your own.

Figures 10–12 show three different cases of location of points $A_1, ..., A_6$. Of course, they do not exhaust all the possibilities.

And in conclusion - one more consequence.

Statement 5. Let two tangents $AM$ and $AN$ to the circle and two sections be drawn from the point $A$, taken outside the circle, and let $P$ and $Q$ be the points of intersection of the circle with the first section, and the points $K$

⟦folio 29⟧

u L - from the second. Then the lines PK, QL and MN intersect at one point.

Proof (Fig. 13).
Let's apply Ceva's theorem to the KLM triangle. Note that the lines PK, QL and MN intersect at one point if the equality is satisfied

$$\frac{\sin \widehat{LMN}}{\sin \widehat{NMK}} \cdot \frac{\sin \widehat{KLQ}}{\sin \widehat{QLM}} \cdot \frac{\sin \widehat{MKP}}{\sin \widehat{PKL}} = 1. \quad (13)$$

All angles appearing in the last expression are inscribed in a given circle; the sines of these angles are proportional to the lengths of the chords they subtend (for example, sin $\widehat{LMN} = \frac{|LN|}{2R}$, where R is the radius of the circle). Therefore, equality (13) is equivalent to the following equality:

$$\frac{|LN|}{|NK|} \cdot \frac{|KQ|}{|QM|} \cdot \frac{|MP|}{|PL|} = 1. \quad (13')$$

Let us show that (13') is indeed satisfied. From the similarity of triangles AMP and AMQ we obtain $\frac{|PM|}{|MQ|} = \frac{|AM|}{|AQ|}$.

From the similarity of triangles APL and AQK $$\frac{|KQ|}{|PL|} = \frac{|AQ|}{|AL|},$$ and, finally, from the similarity of triangles ALN and ANK $$\frac{|LN|}{|NK|} = \frac{|AL|}{|AM|}.$$ Multiplying the last three equalities, we obtain (13).

Note: From Statement 5 it follows that with the help of one ruler a tangent can be drawn through a given point outside the circle. The construction method is shown in figure 14.

Exercise
1. Prove that: a) the bissertrices of the exterior angles of a triangle intersect the lines,

Fig. 10.

Fig. 11.

Fig. 12.

Fig. 13.

Fig. 14.
