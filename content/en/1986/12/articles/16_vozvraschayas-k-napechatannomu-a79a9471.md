---
id: 1986-12-vozvraschayas-k-napechatannomu-a79a9471
issue: kvant_1986_12
year: 1986
number: "12"
title: Returning to print
rubric: smes
page_first: 52
page_last: 52
page_labels: "50"
tag: 06GS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8d9fea42b4ec467beec53c3ceedd0e53c96f44d8eb7e57bfc6076e7014fb9c8d
prompt_sha256: draft-1
translated_from: content/ru/1986/12/articles/16_vozvraschayas-k-napechatannomu-a79a9471.md
source_content_sha256: 5d4fb64adb941f29f817c147b7fa7c40d314691230080bc75f4c89110e8b136d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

Returning to print

The editors received several letters pointing out “errors in the algorithms” that readers saw in the article by V. A. Kaimin («Kvant», No. 10, p. 47). This gives us reason to dwell on an important question: which algorithms are considered correct?

We call an algorithm *correct* if it generates results strictly in accordance with the requirements (statement of the problem or description of the scenario) for any acceptable initial data. Accordingly, an algorithm contains errors if it is possible to specify such acceptable initial data that would produce a result that does not meet the specified requirements; or no results will be obtained at all. In the absence of a clear statement of the problem, it makes no sense to prepare for the presence of errors in algorithms or programs.

An example of an incorrect real algorithm can be found in the mentioned article: unfortunately, in the algorithm for calculating the area of ​​a ring (p. 48), after the line $S_2 := \pi \cdot r^2$ the line $S := S_1 - S_2$ is missing. In this regard, the editors apologize to readers.

Another thing is the approximate solution algorithm

equations $f(x) = 0$ (method of division by half, p. 50). The article (due to space limitations) does not provide a statement of the problem, so it is not legitimate to formally raise the question of the correctness of this algorithm. We note, however, that in the author’s production there was:

Requirement: $x_0$ - approximate solution;

Communication: $x_1 \leq x_0 \leq x_2$,
$|x_1 - x_2| < e$,
$f(x_1) \cdot f(x_2) \leq 0$.

For this setting, the given algorithm is correct. You can, of course, pose the problem differently, for example, require $|f(x_0)| < e$, and then a different algorithm is needed. Which formulation is better is another, purely mathematical question.
