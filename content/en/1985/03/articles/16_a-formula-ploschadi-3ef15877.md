---
id: 1985-3-a-formula-ploschadi-3ef15877
issue: kvant_1985_3
year: 1985
number: "3"
title: Area formula
authors:
  - А. П.
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 34
page_last: 35
page_labels: 32-33
tag: Z10O
lang: en
source: kvant_digital
extraction: vision
content_sha256: bff96113a9a391a39e21cefdb520350a2c8e210a876b210b1eb369ae3613aa1a
prompt_sha256: draft-1
translated_from: content/ru/1985/03/articles/16_a-formula-ploschadi-3ef15877.md
source_content_sha256: 6be446314d94329b307ff63484919189bf4a17e46ee7af117548505dec109862
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 32⟧

Kaleidoscope "Quaita"

P. L. Chebyshev

“Bringing theory closer to practice produces the most beneficial results, and it is not just practice that produces this; the sciences themselves develop under its influence: it opens up for them new subjects for research or new aspects in subjects that have long been known...”
P. L. Chebyshev

* * *
Pafnuty Lvovich Chebyshev (1821-1894) - great Russian mathematician and mechanic. He has outstanding results in many areas of mathematics. In particular, he showed that the number of $n$ primes, not exceeding their number $n$, is more accurately described by the dependence: $\pi(n) \approx n/\log n$. Chebyshev developed a theory of approximation of functions by polynomials and made a huge contribution to the development of probability theory. At the same time, he paid a lot of attention to applied mathematics and mechanics. His works on the rational cutting of fabric, the structure of geographical maps, and the flight of artillery shells are known.

P. L. Chebyshev’s research on the theory and design of hinge mechanisms is very interesting, to which he devoted 15 of his works. He invented and designed about 40 different mechanisms, including the “plantigrade machine”,

quantum 3
1985

or, as it was called, a “mechanical horse”, a boat with a rowing mechanism, regulators for a steam engine (see photo), an arithmetic meter and much more.

P. L. Chebyshev was also an outstanding teacher. He trained many talented mathematicians who formed the St. Petersburg mathematical school, the traditions of which are still alive today.

Let's draw some polygon on checkered paper with vertices at the grid nodes, for example, like the one on figure 1. Now let's try to calculate its area. How to do this? Probably, the past is divided into right triangles and straight lines, the areas of which are easy to calculate, and add up the results. Carrying out sequential calculations, we find that the area of ​​our polygon is 20.5, if we take the area of ​​\u200b\u200bone square of checkered paper as a unit of area. But if we remember that the side of such a square is 0.5 cm, which means its area is equal to a quarter of a square centimeter, the area of ​​an equal polygon in square centimeters will be equal to 20.5/4 = 5.125 cm².

The method we used is simple, but very

⟦folio 33⟧

Area formula

cumbersome, in addition, it is not suitable for all polygons. Thus, the polygon on figure 2 can no longer be divided into right triangles and rectangles in the same way as we did with the previous polygon. You can, for example, try to add our polygon to a “good” one, that is, to one whose area we can calculate in the described way, then subtract the areas of the added parts from the resulting number.

However, it turns out that there is a very simple formula that allows you to calculate the areas of polygons with vertices at the nodes of a square grid:

$$S = B + \Gamma / 2 - 1,$$

where $S$ is the area of ​​the polygon, expressed in the areas of unit grid squares, $\Gamma$ is the number of grid points lying on the boundary of the polygon, and $B$ is the number of grid points lying inside the polygon. For polygon

Fig. 1.

Fig. 2.

Fig. 3.
