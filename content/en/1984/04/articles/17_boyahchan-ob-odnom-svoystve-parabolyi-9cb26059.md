---
id: 1984-4-boyahchan-ob-odnom-svoystve-parabolyi-9cb26059
issue: kvant_1984_4
year: 1984
number: "4"
title: About one property of a parabola
authors:
  - Бояхчан Г. Г.
rubric: raznoe
page_first: 52
page_last: 52
page_labels: "50"
tag: IIZB
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6e4185b7df6d58cab122f078bb6f96d506ac611f36e7acc9207fd5530ccc02d5
prompt_sha256: draft-1
translated_from: content/ru/1984/04/articles/17_boyahchan-ob-odnom-svoystve-parabolyi-9cb26059.md
source_content_sha256: ca956b6999f307b76dcfb2047ad3861d9927db20ddbb8780cdc7298185c8a08a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

About one property of a parabola

G. G. BOYAKHCHAN

On the parabola $y=ax^2$ we consider three points $A, B, C$, the projections of which on the axis $Ox$ are equidistant from each other: $|A_1B_1|=|B_1C_1|=m$ (Fig. 1). Let's find the area of ​​triangle $ABC$.

To do this, let us denote by $x_1, x_2, x_3$ the abscissa of the point $A, B, C$, respectively. By condition $x_2=x_1+m, x_3=x_1+2m$. The trapezoid $A_1ACC_1$ is made up of a triangle $ABC$ and two trapezoids $A_1ABB_1$ and $B_1BCC_1$, so

$$S_{ABC}=S_{A_1ACC_1}-(S_{A_1ABB_1}+S_{B_1BCC_1}),$$

where

$$A_{ABC}=\frac{ax_1^2+a(x_1+2m)^2}{2}\cdot 2m-\frac{ax_1^2+a(x_1+m)^2}{2}\cdot m-\frac{a(x_1+m)^2+a(x_1+2m)^2}{2}.$$

Bringing similar terms, we get the simplest formula:

$$S_{ABC}=am^3.$$

It turned out that the required area does not depend on the abscissa of the point $A$, but only on the distance $m$ between neighboring points (and on the parameter $a$, which determines the circularity of the parabola).

Let us now consider the general case—the empty abscissas $x_1, x_2, x_3$ of the points $ABC$ are arbitrary. If $x_1<x_2<x_3$, then you can guess exactly the same as in the previous example (see Fig. 1). We get

$$S_{ABC}=\frac{ax_1^2+ax_2^2}{2}(x_3-x_1)-\frac{ax_1^2+ax_2^2}{2}(x_2-x_1)-\frac{ax_2^2+ax_3^2}{2}(x_3-x_2),$$

or, after bringing similar members,*

$$S_{ABC}=\left|\frac{a}{2}\left(x_1-x_2\right)\left(x_2-x_3\right)\left(x_3-x_1\right)\right|.$$

It is easy to check (we leave the verification to the reader) that for all other relationships between the abscissas, formula (2) remains valid. This formula shows that the area of ​​a triangle with vertices on a fixed parabola depends only on the differences between the abscissas of its vertices. When a triangle slides along a parabola, changing shape but keeping the differences between the abscissas of the vertices unchanged, its area does not change. It turns out that only a parabola has this property, but we will not prove this.

As a task, we invite the reader to find evidence of the three following elements of formula (2):

1. If all the vertices of a convex polygon lying on the parabola $y=ax^2$ are translated along the parabola while preserving the difference of their abscissas, then the area of ​​the polygon does not change.
2. The area $S$ of a segment of a parabola $y=ax^2$ bounded by a segment whose ends have abscissas $x_1$ and $x_2$ (Fig. 3) is equal to

$$S=\frac{a}{6}\left(x_1-x_2\right)^3.$$

Indication e. See Fig. 3. Area of ​​a curved trapezoid

$$A_1ABB_1$$ is found as the integral of $\int x_1^2ax^2dx.$

3. The previous results (formulas (1) and (2), corollaries 1 and 2) remain in force if the parabola $y=ax^2$ is replaced by a general parabola $y=ax^2+bc+c$.

Indication e. There is a movement that turns one parabola into another.

*) The model sign is not needed in the case of $x_1<x_2<x_3$, but is required in other cases (check this!)
