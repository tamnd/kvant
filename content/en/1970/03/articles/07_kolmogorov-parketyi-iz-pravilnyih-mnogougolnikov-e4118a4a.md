---
id: 1970-3-kolmogorov-parketyi-iz-pravilnyih-mnogougolnikov-e4118a4a
issue: kvant_1970_3
year: 1970
number: "3"
title: Parquets made of regular polygons
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 27
page_last: 28
page_labels: 25-26
tag: WWZ6
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2e7cf3c935527b42809eec32380d005a98d45eccad393c3105987d2551883d82
prompt_sha256: draft-1
translated_from: content/ru/1970/03/articles/07_kolmogorov-parketyi-iz-pravilnyih-mnogougolnikov-e4118a4a.md
source_content_sha256: 94cb08ee0ea26b99fcff68196ee0c07e637357fbe1e0840763e22ec63bc8a9a8
translation_model: draft
translation_run: en-draft-test
translation_quality: draft
---

⟦folio 25⟧

For example, at Fig. 2, 6, rotating the entire grid of vertices and sides that makes up the parquet of hexagons, squares and triangles 60° around the center of one of the hexagons, we get the same grid of vertices and sides. The center of each hexagon of this parquet is the “center of the sixth order symmetry”*).

Problem 1. Find all symmetry centers of the 4th, 3rd and 2nd order of the parquet shown at Fig. 2, a.

WHAT IS CORRECT PARQUET
From a symmetry point of view, our definition of parquet is not too far off. It allows parquets that do not have any symmetry. Taking a common parquet of hexagons (Fig. 1, c), you can “spoil” it by subdividing some of the hexagons into six triangles. It is easy to understand that the result will be “parquet” again in the sense of our definition. But it can be proven (try it!) that by subdividing, for example, three hexagons, as shown in figure 3, and leaving all the rest undivided, we get a parquet floor that is completely devoid of symmetry. To install ugly, insufficiently symmetrical parquet floors, we use the following definition:

A parquet is called regular if it can be superimposed on itself in such a way that any given vertex of it can be superimposed on any other given vertex of it.

Task 2. Prove that the parquets presented in Figures 1 and 2 are correct and build as many correct parquets as possible on your own.

*) A point O is called the nth-order symmetry center of a certain figure if, when this figure is rotated around O by $\frac{360^\circ}{n}$, it overlaps itself.

⟦folio 26⟧

MAIN OBJECTIVE

It turns out that all the variety of correct parquet floors can be described. If the length $h$ of the side of the parquet polygons is given, then there is a finite number of different (non-overlapping) regular parquets. I don’t want to tell you exactly how much.

Listing them all and thereby answering the question about their number is the main task that you have to solve.

SOME GUIDELINES

The solution to the natural problem begins with the use of parquet tops. A regular $n$-gon has $n$ exterior angles (Fig. 4), the sum of which is equal to four right angles (see this for yourself). Therefore, each angle of a regular $n$-gon is equal to

$$\alpha_n = 2d - \frac{4d}{n} = 2\left(1 - \frac{2}{n}\right)d.$$

Polygons with a sum of angles equal to 4d must converge at the vertex of the parquet. So,

$$\alpha_3 = \frac{2}{3}d, \alpha_4 = d, \alpha_6 = \frac{4}{3}d, \alpha_8 = \frac{3}{2}d$$

and for the parquets shown in Fig. 1 and 2, we have:

$$4\alpha_4 = 4d,$$

$$6\alpha_3 = 4d,$$

$$3\alpha_6 = 4d,$$

$$\alpha_4 + 2\alpha_8 = 4d,$$

$$\alpha_3 + 2\alpha_4 + \alpha_6 = 4d.$$

In the general case, denoting by $m_n$ the number of applications to the vertex of $n$-gons, we should obtain

$$\sum m_i\alpha_i = 4d,$$

(1)

where in the sum we include terms with those numbers $i$ for which $m_i > 0$ and $\alpha_i = 2\left(1 - \frac{2}{i}\right)d$.

Our first task is to find all solutions to equation (1) with integers $m_i > 0$. Equation (1), reducing by 2d, can be conveniently written in the form

$$\sum m_i\left(1 - \frac{2}{i}\right) = 2.$$

For each solution to equation (2), one must use the corresponding
