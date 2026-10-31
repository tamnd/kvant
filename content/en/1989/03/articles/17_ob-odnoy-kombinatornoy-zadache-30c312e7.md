---
id: 1989-3-ob-odnoy-kombinatornoy-zadache-30c312e7
issue: kvant_1989_3
year: 1989
number: "3"
title: '[About one combinatorial problem]'
rubric: nam-pishut
page_first: 60
page_last: 60
page_labels: "58"
tag: 0BFY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 857b3915fdd1bdc4a75c5cca51470d87bb6bb755bd256250298765e8162dd2c1
prompt_sha256: draft-1
translated_from: content/ru/1989/03/articles/17_ob-odnoy-kombinatornoy-zadache-30c312e7.md
source_content_sha256: 0a793875bf713c05843b63525dab796d2e0d51cd293ae80da3e5631b925a85fc
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 58⟧

For example, that the point $Q$ also lies on this circle. Triangles $T_1SQ$ and $CQA$ are similar. Therefore $\frac{ST_1}{AC} = \frac{T_1Q}{QA}$, but $AC = QA$ (see statement 8). Therefore $ST_1 = T_1Q = r$.

Exercise 2. Prove the following statements:

17. Point $K$ (see Fig. 3) is the orthometer of triangle $CPQ$.
18. Lines $PS$, $RQ$ and $CH$ intersect at point $K$.
19. $RT = KS = SQ$; $RP = RK = TS$.
20. $RS = CT$.
21. Points $A, R, S, B$ lie on the same circle; points $A, P, T, C$ lie on the same circle. The points $B, Q, T, C$ also lie on the same circle.

A few more matches

22. $AT_1 \cdot BT_1 = S_{ABC}$.

Naimput

Many readers are familiar with the classic formula for the number of combinations of $n$ elements taken by $k$:

$$C_k^n = \frac{n!}{k!(n-k)!}.$$

In particular, there are $C_k^n$ ways to select $k$ different numbers from the set $(1, 2, 3, ..., n)$. L. I. Plyukfelder from Novokuznets asked the question: in how many ways can one choose $k$ numbers from the set pa (1, 2, 3, ..., $n$) so that the absolute difference of any two chosen numbers is not less than $p$?

Let's denote this number by $C_k^n(p)$. The formula found by L. I. Plyukfelder has the form:

$$C_k^n(p) = \frac{(n+k-pk+p-1)!}{k!(n-pk+p-1)!}$$

(if for some $n, k, p$ a negative number appears in the denominator, then the required calculation does not exist).

For $p=1$, formula (2), as one would expect, turns into (1), and for $p=0$ into the formula:

$$C_k^n(0) = \frac{(n+k-1)!}{k!(n-1)!}.$$

The number $C_k^n(0)$ is naturally taken as the number of ways of choosing $k$ not necessarily different elements from the data $n$; for this number, formula (3) gives the correct result.

The proof of formula (2) can be verified by induction; We suggest you do this yourself.
