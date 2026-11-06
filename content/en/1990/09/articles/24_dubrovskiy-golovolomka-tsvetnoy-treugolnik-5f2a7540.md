---
id: 1990-9-dubrovskiy-golovolomka-tsvetnoy-treugolnik-5f2a7540
issue: kvant_1990_9
year: 1990
number: "9"
title: Color triangle puzzle
authors:
  - Дубровский В. Н.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 71
page_last: 71
page_labels: "69"
lang: en
source: kvant_digital
extraction: vision
content_sha256: a2cdbb9da978c0234cd740fe4d82a53881a185e263351850d76223d4e6fdcaa3
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/24_dubrovskiy-golovolomka-tsvetnoy-treugolnik-5f2a7540.md
source_content_sha256: ddf071034688843cb3752183a95a92c1a0f4b921f87a501df9c469aa2e419064
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 69⟧

Puzzle "Colored Triangle"
(research problem)

On the 4th s. cover of the previous issue «Kvant» we proposed the following puzzle: on the nodes of a regular triangular grid in a triangle (with $n$ nodes on a side), place tiles of $n$ colors so that there are no unambiguous tiles on the grid lines parallel to the sides.

Figures 1 and 2 show two solutions to this puzzle for $n=5$. It is interesting that the division of 15 grid nodes into sets of unambiguous nodes in both cases is symmetrical relative to the vertical height of the triangle, and at figure 2 - also relative to two other heights, as well as relative to the rotation by $120^\circ$ around the center of the triangle.

You can get the color for figure 1 like this. Consider an (oblique) coordinate system with the origin at the green vertex of the triangle and the axes going along the sides, in which the red vertex has coordinates (4; 0), and the purple vertex has coordinates (0; 4). Then it turns out that the green color has nodes $(x; y)$, for which $x=y$, red - points for which $y=x$ when divided by 5 gives remainder 1, blue - points with remainder 2, etc. You can check that the same coloring method is suitable for any odd $n$. However, if $n$ is even, it does not work: the same colors fall on the same horizontal line.

Problem 1. Take some integer function $f(x)$ and divide the grid nodes into sets, in each of which the difference $f(x)$ will give the same remainder when divided by $n$. On each of the received sets we will place chips of a different color. Show that if $n$ is even, the “conditionality” will not fulfill the function $f(x)$ for any reason.

Moreover, for $n=4$ (as well as for $n=2$) our puzzle is not cut at all. Indeed, if the nodes at the base of the triangle are colored as in figure 3, then the central node can only be red or blue. In the first case, looking at the arrows, we will unambiguously determine the color of three more nodes and will then be forced to break the rules: two vertices of the triangle turn out to be red. The case of a cephalological central node is treated similarly.

Problem 2. Solve the puzzle for $n=6$ and $n=8$.

Problem 3*. At what four $n \geq 10$ does the Colored Triangle puzzle have a solution?

Another apparently very difficult question: how many solutions does the puzzle have depending on $n$? A similar question for the placement of chips on a straight head grid with the condition of horizontal and vertical spacing in the article by V. Shevelev “Latin straight head grids” («Kvant» No. 5 for this year). However, even the main problem, despite its long history, is far from being completely solved.

V. Dubrovsky
