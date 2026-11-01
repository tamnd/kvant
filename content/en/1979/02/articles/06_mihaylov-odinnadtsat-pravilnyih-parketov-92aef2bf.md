---
id: 1979-2-mihaylov-odinnadtsat-pravilnyih-parketov-92aef2bf
issue: kvant_1979_2
year: 1979
number: "2"
title: Eleven correct parquets
authors:
  - Михайлов О.
rubric: raznoe
page_first: 11
page_last: 16
page_labels: 9, 14
tag: SKL2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1ad152cb58a559d4c59fc4a1e60f61cc3da22052d36fda67f9049f51a46467ad
prompt_sha256: draft-1
translated_from: content/ru/1979/02/articles/06_mihaylov-odinnadtsat-pravilnyih-parketov-92aef2bf.md
source_content_sha256: e0d035168fa2f633a425c1112986e9dddea7710f2628b1df23c36477c71656ff
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

O. Mikhailov

Eleven correct parquets

In everyday life, we often see polygonal planes covered with surfaces: the floors in residential buildings are covered with parquet, the walls of bathrooms are covered with tiles, modern buildings are decorated with ornaments. The most symmetrical coverings - mathematicians call them regular parquets - have already been written in «Kvant»: in the article by A. Kolmogorov («Kvant», 1970, No. 3) the problem of classifying regular parquets was discussed. One of its possible solutions is currently being presented.

We will call a parquet the covered planes of regular polygons, in which two polygons either have a common side, or have a common vertex, or have no common points at all. A parquet is called *regular* if it can be superimposed on itself in such a way that any given vertex of it can be superimposed on any other directed vertex.

How many correct parquets are there in total? How are they built? Our task is to answer these questions.

It is easy to see that in general there are countless parquets - not necessarily correct ones - *) (show this yourself). However, just as with an infinite polygon, no more than six and no less than three polygons can converge in another parquet. Indeed, when seven or more polygons converge at one vertex, at least one angle in a regular polygon must be less than 60°, which is impossible (the minimum angle of a triangle is 60°).

*) We consider two parquets to be the difference of polygons, and with an infinite polygon of parquets there is only a finite number of regular parquets.

Sometimes in this article, for the sake of brevity, we will simply call correct parquets parquets.

The solution to our problem naturally begins with the study of the vertices of the parquet. From the definition of correctness the principle of vertex equivalence immediately follows: any two vertices are constructed identically in the sense that the stars of all vertices are the same. (A vertex star is a figure formed by all polygons containing it.)

Let us denote by $m_i$ the number of $i$-gons adjacent to the vertex, and by $\alpha_i$ the values ​​of the angle of a regular $i$-gon inside it. Then at each vertex, very/no, a matching is performed.

$$\sum m_i \alpha_i = 360^\circ = 4d,$$

where in the sum we include all terms with numbers $i$ for which at least one $i$-gon is adjacent to the vertex *).

Substituting the expression for $\alpha_i$, $\alpha_i = 2(1 - 2/i)d$ known from geometrics into this formula and reducing by 2$d$, we obtain

$$\sum m_i \left(1 - \frac{2}{i}\right) = 2.$$

Thus, the numbers $m_i$ are integer solutions to equation (1). However, as we will see below, not all integer solutions to equation (1) are realized by regular parquets!

Further, no more than six and no less than three polygons can converge at the vertex of the parquet. Indeed, when seven or more polygons converge at one vertex, at least one angle in a regular polygon must be less than 60°, which is impossible (the minimum angle of a triangle is 60°).

*) However, $m_i = 0$ for the rest $i$, so we can formally assume that we are summing over all $i$.

⟦folio 14⟧

numerical solutions, we will need the following

Lemma. At the top of a regular parquet, they cannot be maintained with different polygons, one of which has an infinite number of sides.

Indeed, let such a parquet exist (Fig. 5). Then around the odd olg the remaining $m$- and $n$-gons must go through each other. Therefore, when going around it, there are two identical polygons nearby, questions about the conditions of the lemma.

Thanks to the lemma, we can replace $k$ with $2k_1$, $m$ with $2m_1$, $l$ with $2l_1$ in (2) and go to the equation

$$\frac{1}{n_1} + \frac{1}{m_1} + \frac{1}{k_1} = 1.$$

Without loss of generality, we can propose that $k_1 < m_1 < n_1$. Then

$$\frac{1}{n_1} + \frac{1}{m_1} + \frac{1}{k_1} < \frac{3}{k_1},$$

poseable $k_1 = 2$. Therefore, $\frac{1}{n_1} + \frac{1}{m_1} = \frac{1}{2}$, whence $m_1 = 3$, $n_1 = 6$ (if $m_1 \geq 4$, then $n_1 \leq m_1$). The resulting solution $\alpha_4 + \alpha_6 + \alpha_{12}$ gives us another parquet (Fig. 6).

Parquets with four polygons at the top

In this case we arrive at the equation

$$\frac{1}{n} + \frac{1}{m} + \frac{1}{k} + \frac{1}{l} = 1.$$ (3)

We will assume that $l \leq k \leq m \leq n$. It is easy to see that then $l \leq 4$. If $l = 4$, then we arrive at the set $4\alpha_4$. If $l = 3$, then we obtain the equation

$$\frac{1}{n} + \frac{1}{m} + \frac{1}{k} = \frac{2}{3},$$

from which it is found that $k < 5$. If $k = 4$, then, since $m \geq k$, we arrive at the unique solution $m = 4$, $n = 6$. If $k = 3$, then we get two solutions: $m = 4$, $n = 12$ and $m = 6$, $n = 6$.

We will therefore be presented with four sets to examine:

$$4\alpha_4; \alpha_3 + 2\alpha_4 + \alpha_6; 2\alpha_3 + 2\alpha_6; \alpha_4 + 2\alpha_3 + \alpha_{12}.$$

The first set $4\alpha_4$ gives a trival square parquet (Fig. 7).

For the combination $\alpha_3 + 2\alpha_4 + \alpha_6$, two non-equivalent vertices are possible (Fig. 8, a, b), but only the variant $8,a$ gives the correct parquet (Fig. 8, b). Make sure for yourself that option $8,b$ does not produce any correct parquet.

For $2\alpha_3 + 2\alpha_6$ two different vertices are also possible (Fig. 9, a, b), but only the second one gives the correct parquet (Fig. 9, b). Completion of the first leads to a contradiction. Thus, there are three “four equations” of parquet:

$$4\alpha_4; \alpha_3 + 2\alpha_4 + \alpha_6; 2\alpha_3 + 2\alpha_6.$$

Parquets with fifth polygons at the top

In this case, you need to find a solution to the equation

$$\frac{1}{n} + \frac{1}{m} + \frac{1}{k} + \frac{1}{l} = \frac{3}{2}.$$ (4)

From it it is immediately clear that $j = k = l = 3$ (we assume that $j \leq l \leq k \leq m \leq n$). The result is equation $\frac{1}{n} + \frac{1}{m} = \frac{1}{2}$, which has two solutions: $m = 3$, $n = 6$ and $m = 4$, $n = 4$.

It now remains to consider the combinations found:

$$\alpha_6 + 4\alpha_3 \text{ и } 2\alpha_4 + 3\alpha_3.$$

The first of them gives the only type of vertex and the only regular parquet (Fig. 11). The second combination allows two non-equivalent vertices, each of them forming parquets (Fig. 12 and 13).

Thus, there are three “quintuple equations” of parquets:

$$4\alpha_3 + \alpha_6; (2\alpha_4 + 3\alpha_3)'; (2\alpha_4 + 3\alpha_3)''.$$

Parquets with six polygons at the top

It is quite obvious that such a parquet (Fig. 14) is the only one that receives from the combination $6\alpha_3$.

The cases listed above exhaust the entire variety of correct parquet floors. As can be seen from the above, the total number is the same.
