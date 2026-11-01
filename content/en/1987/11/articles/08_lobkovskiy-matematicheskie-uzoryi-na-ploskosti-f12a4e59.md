---
id: 1987-11-lobkovskiy-matematicheskie-uzoryi-na-ploskosti-f12a4e59
issue: kvant_1987_11
year: 1987
number: "11"
title: Mathematical patterns on a plane
authors:
  - Лобковский А. Э.
rubric: raznoe
rubric_sub: Разное
page_first: 23
page_last: 23
page_labels: "21"
tag: FRPB
lang: en
source: kvant_digital
extraction: vision
content_sha256: a9b80fde581e94ceb186658b2aef36d8f1bb875438bef7dcedfa65a192d4fbd6
prompt_sha256: draft-1
translated_from: content/ru/1987/11/articles/08_lobkovskiy-matematicheskie-uzoryi-na-ploskosti-f12a4e59.md
source_content_sha256: 686f700797f4c1297dd01a6448e66f45725efa71f20a21821a44054ac1bdeaf5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

Mathematical patterns on a plane

A. E. LOVKOVSKY

Recently, in applied mathematics, work has appeared related to the study of the patterns that appear on the display screen if each point of the plane is colored in one color or another according to a certain rule. Coloring rules can be very diverse.

The algorithm discussed here is so simple that it can easily be implemented on a computer by a novice programmer. It looks like this: for a point in the plane $(x; y)$, the values ​​$c = [f(x, y)]$ are calculated, where $f(x, y)$ is the selected coordinate function, and square brackets denote the integer part of the number; if the number $c$ is odd, the dot is painted over, if it is even, then not.

The entire plane will then be divided into finite one-dimensional regions. The size of the region decreases with distance from the origin. Therefore, on a computer where the size of a point on the screen may be larger than the size of such an area, it is not always possible to accurately restore the real picture. In fact, in our algorithm, the entire plane is divided into cells, and each cell is painted with the same color as its center. Therefore, if there were several different areas on the territory of the cell, then the resulting figure will differ from the true one. By reducing the size of the cell, i.e. increasing the image scale, we improve the accuracy of reproduction. The corresponding Basic program for screen $X \times Y$ looks like this:

10 INPUT $S$
20 FOR $x=0$ TO $X$
30 FOR $y=0$ TO $Y$
40 IF (INT($f(x, y)/S$)) mod 2=1 THEN PLOT $(x, y)$
50 NEXT $y$
60 NEXT $x$
The role of scale here is played by the quantities $S$.

In the pictures shown on the second page of the cover, you see the patterns obtained with different $S$ for $f(x, y) = x^2 + y^2$ (Fig. 1, ​​a-e), $f(x, y) = xy$ (Fig. 2, a-e), $f(x, y) = x^2 - y^2$ (Fig. 3, a-e).

The pronounced periodicity, which can be seen at small $S$ in all graphs, oddly enough, is an expense of our reproduction method. The period on all cards is equal to $S$ for even $S$ and $2S$ for odd. Let's prove this using the example $f(x, y) = x^2 + y^2$. Indeed, the color of the point

$$\begin{align*}
(x_1; y_1) &= (x + kS; y + lS) \\
(k, l) &= \text{целые числа}
\end{align*}$$

is determined by the expression:

$$\frac{x_1^2 + y_1^2}{S} = \frac{(x + kS)^2 + (y + lS)^2}{S} = \frac{x^2 + y^2}{S} + S(2k + 2l + k^2S + l^2S).$$

It can be seen that the fractional parts of the numbers $(x_1^2 + y_1^2)/S$ and $(x^2 + y^2)/S$ coincide, and therefore, for even $S$, the color of the point $(x_1; y_1)$ (i.e., the parity of the expression $[(x_1^2 + y_1^2)/S]$) coincides with the color of the point $(x; y)$ for any $k$ and $l$, and for odd $S$ only for $k$ and $l$ of the same parity. We propose to prove to the reader the fact that this period is the shortest.

In all the presented graphs, the number $S$ is even. You can see for yourself that if $S$ is odd, the black and white circles will be black.

One can endlessly admire the diversity that arose with such a seemingly primitive method of constructing figure. For $f(x, y) = x^2 + y^2$, in addition to a pronounced family of circles with a period of $T$, one can see many more (more than 10) less contrasting families of circles located at the nodes of a square lattice with a period of $T/2, T/3, T/4, T/5, T/7, T/9$ and even $T/11$. It would be interesting to answer the following questions: why “secondary” circles arise, what are the periods of their lattices (if they are periodic at all), etc.

All of the above also applies to the graphs $c$ $f(x, y) = xy$ and $f(x, y) = x^2 - y^2$, with the difference that in these figures we see families of hyperbolas.

In conclusion, I would like to wish the reader success with this interactive problem, experimenting with different $f(x, y)$, for example $x^3 + y^3$ or arctg $(x + y)$.
