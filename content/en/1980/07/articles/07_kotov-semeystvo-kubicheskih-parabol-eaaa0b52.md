---
id: 1980-7-kotov-semeystvo-kubicheskih-parabol-eaaa0b52
issue: kvant_1980_7
year: 1980
number: "7"
title: Family of cubic parabolas
authors:
  - Котов Ю. В.
rubric: raznoe
rubric_sub: Разное
page_first: 20
page_last: 20
page_labels: "18"
tag: 8QPV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 841711a56edb9f64cdddec47fbc9e67738c7b7f47cc8c58b112b5aee0401c6c4
prompt_sha256: draft-1
translated_from: content/ru/1980/07/articles/07_kotov-semeystvo-kubicheskih-parabol-eaaa0b52.md
source_content_sha256: 0c87d5cc85b5a22d9dac2c8e93dc5752aaf717863869c570b38a230e60eae553
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 18⟧

Family of cubic parabolas

Look at the second page of the cover - it shows a family of 169 cubic parabolas, forming a plum pattern, the “author” of which is a computer. This note will look at how such curves are used in practice.

In computer graphics, there will firstly be a need to draw smooth curved lines. Sometimes this must be done by determining the curves corresponding to a given equation. In other cases, the curve of the first replacement of its components Δx₃, Δy₃). As is known, the slope is equal to kᵢ = Δyᵢ/Δxᵢ. Thus, we need to draw each of the other four that make up the general curve according to four initial conditions (the position of two points and the slope of the tangents at two points). What type of curve should I choose for this? In an analytical sense, this should be a “four-parameter” curve, that is, roughly speaking, its equation should have 4 coefficients. To obtain a specific arc, it is necessary to determine the corresponding values ​​of these four coefficients and indicate the interval of change of the argument. Probably the simplest solution to our problem is the arc of a cubic parabola, or more precisely, part of the graph of a cubic polynomial:

y = A + B · x + C · x² + D · x³.

Knowing the coordinates of the starting and ending points, as well as the direction of the tangents at these points, it is easy to obtain a system of four equations for determining the coefficients A, B, C, D.

This simple method of constructing wave curves is universal. Points with vertical tangents are “inaccessible” to it. It is difficult to draw a closed or self-intersecting line, even if divided into a series of arcs. But, of course, mathematicians-programmers have many more cunning and advanced ways to construct various curves.

On our cover is a machine drawing of arcs of a cubic polynomial (figure rotated by 90°). Each of the 13 top points is connected by an arc to the 13 bottom points. At each of the 26 initial points, a tangent connection is specified. The arcs, intersecting, unexpectedly form a lace pattern with rows of “knots”. Think about why this happened. How are the horizontal lines containing “knots” located?
