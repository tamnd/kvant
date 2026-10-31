---
id: 2017-5-kanunnikov-algebra-i-geometriya-kompleksnyih-chisel-83900e56
issue: kvant_2017_5
year: 2017
number: "5"
title: Algebra and geometry of complex numbers
authors:
  - Канунников А. Л.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 30
page_last: 34
tag: QA6M
lang: en
source: kvant_digital
extraction: native
content_sha256: 625f4ae6d4cae37a04782c1361c8485216e35b2b5dc189bbed9f12c8e9c5f6ca
prompt_sha256: draft-1
translated_from: content/ru/2017/05/articles/04_kanunnikov-algebra-i-geometriya-kompleksnyih-chisel-83900e56.md
source_content_sha256: 127f727af035f172a0849cc3ed9d9bcee0a1c6e16a3c937555320534cc71c4c5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

SCHOOL AT KVANT

Algebra and geometry of complex numbers

A.KANUNIKOV

We recommend reading this article after the article “The Magic of Complex Numbers” (p. 5) or in parallel with it. The plots of that article often followed the same scenario: geometric methods were used to solve an algebraic problem behind the scenes, and the finished result appeared like a rabbit out of a hat. What problems about complex numbers can pure algebra solve and where are the limits of its application? What problems do geometric methods help with, and how do complex numbers and geometry enrich each other? We will talk about all this in the article. But our main goal - since this is the heading “School in «Kvant» - is to teach you, dear reader, techniques for working with complex numbers, algebraic and geometric methods for solving problems that would be based on a solid theoretical basis. Don't try to understand everything at once. Work on the article thoughtfully, slowly, return to “The Magic of Complex Numbers” (secrets being revealed?). Discuss the material with teachers and friends, and most importantly, solve problems; answers and instructions are provided for most of them (p. 51).

Algebra of complex numbers

§1. Definition and properties in questions and answers

We will not redefine the initial concepts, expecting you to be familiar with them (see p. 5). Better yet, read more detailed introductions to complex numbers from various sources, such as [2–5]. We really don’t see the point of them

⟦column⟧

repeat. Let’s better answer the most common questions from the series “What did you want to know (clarify) but were afraid to ask.” As we discuss, we will arrive at a reasonable definition of complex numbers. Q: Why is the imaginary unit represented by the letter i? Why can't you just write $- 1$? A: This is the first letter in the Latin word imaginarius (imaginary). It was proposed by Euler in 1777. Instead of i, it is incorrect to write $- 1$, since this is the designation for the set of roots of the equation $x^{2} = - 1$, which, in addition to i, has another root –i: $x^{2} + 1 = ( x - i )( x + i )$. By the way, it is on this unfortunate notation that primitive errors like

1 = 1 =

$( - 1 )^{2} =$

2

$- 1 = - 1$.

Q: Why are complex numbers often defined in literature as pairs of reals? This looks a little strange, especially when introducing multiplication using the formula $( a, b )( c, d ) = ( ac - bd, ad + bc )$. Why not just write a + bi? A: The approach with couples is a tribute to formalism, nothing more. Then they still switch to the understandable notation a + bi instead of ( a, b ). It’s just easier to define without further ado: couples and that’s it. But you're right, multiplying pairs looks crazy, and good books always motivate it. If you immediately write a + bi, then the question will arise, what is this plus and what is the multiplication of b by i. Still, you first need to define complex numbers as objects and only then introduce operations. Q: Is it really impossible to give a definition both strictly and clearly? A: It’s possible. Let's think of complex numbers as vectors in the plane: $C = R^{2}$. Vectors are the same pairs, and we know how to add and multiply them by real numbers (coordinatewise). Let's identify the vector (1, 0) with the number 1, and denote the vector (0, 1) by the letter i. Then ( a, b ) = a ( 1, 0 ) + b ( 0, 1 ) = a + bi

– decomposition of the vector according to basis 1, i. It remains to determine the multiplication of the basis vectors

⟦folio none⟧

KALEIDOSCOPE “QUANTA”

A periodic tiling of a plane is a covering of a plane with non-overlapping figures for which there exist two non-parallel vectors such that a shift on any of them transforms the covering into itself. If a periodic covering is formed by copies of the same polygon, then it is called parquet. Only three regular polygons - triangle, square and hexagon - are parquet. For other regular n-gons, the vertex angle is not a divisor of 360. Parquets of convex irregular polygons are much more complex. Obviously, the parquet can be folded, copying any triangle or any quadrangle. But no convex n-gon with n > 7 can be used to form a parquet. For n = 6, three types of convex parquet hexagons were found and it was proven that no others exist (for the ABCDEF hexagon, these types are characterized by a set of relationships for angles and sides; no restrictions are imposed on unmentioned angles and sides).

⟦column⟧

polygons, by parallel transfers of which you can get the entire parquet. The first five types were found by K. Reinhardt in 1918, and the last known type, the 15th, was found by C. Mann, J. McLeod, D. Von Derau in 2015. Types 14 and 15 are specified rigidly (up to similarity). The remaining types have degrees of freedom (for example, type 1 has five), changing which can change the appearance of the parquet quite dramatically. Moreover, some types of pentagons in their general form allow several tilings. But it also happens differently - this type has a subtype (without degrees of freedom or with fewer degrees of freedom than the main type), which can be used to tile a plane in several ways. Specifying the types of parquet polygons through the ratios for sides and angles is the most compact and traditional. Having analyzed it, we can give a more visual construction of each class, revealing the geometry of the free parameters. An interested reader can install a free encyclopedia program

When n = 5 the problem is not completely solved. Fifteen types of convex pentagons forming parquet have been discovered, but whether others exist and, if so, which ones, is unknown. The found types of ABCDE parquet pentagons with characterizing relationships are presented on the right page of the Kaleidoscope. The fundamental domain (chosen for symmetry reasons) is clearly marked - a set of the minimum possible number of http://www.jaapsch.net/tilings. In it, its author - J. Scherphuis - collected all the currently known periodic tilings (not only convex, but also non-convex) polygons. Tessellations with non-convex polygons and other problems on this topic were discussed in Kaleidoscope «Kvant» No. 2 for 2009. Material prepared by N. Andreev, M. Panov
