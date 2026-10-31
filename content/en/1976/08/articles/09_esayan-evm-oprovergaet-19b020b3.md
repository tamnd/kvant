---
id: 1976-8-esayan-evm-oprovergaet-19b020b3
issue: kvant_1976_8
year: 1976
number: "8"
title: The computer refutes
authors:
  - Есаян А.
rubric: osnovnye-stati
page_first: 30
page_last: 30
page_labels: "28"
tag: DST1
lang: en
source: kvant_digital
extraction: vision
content_sha256: 81c03bf43c9604dd898cebc7afd4df889d369401a721e09860841aa56ae7b743
prompt_sha256: draft-1
translated_from: content/ru/1976/08/articles/09_esayan-evm-oprovergaet-19b020b3.md
source_content_sha256: 42e2d5cd4c0d1ae20a0215bc8a2af2813db26bad0b72ee02751394d32312a88e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

computer
refutes

The great mathematician L. Euler owns the following problem:

Go around all the squares of the chessboard with your knight, raising one square at a time in each square.

In 1823, Varisdorf, in the brochure “The simplest and most general solution to the problem of the knight’s move,” proposed the following rules for traversing the board:

On each move, the knight bets on the mask square from which the smallest number of moves can be made to the squares not yet covered. If there are several cell masks, you are allowed to select any of them.

Note that Warisdorff's rule is not an algorithm, since it does not always clearly indicate the knight's next move (see the second phrase of the rule).

For example, if a knight starts its movement from the square d4, the Warisdorff rule allows it to make its first move to any of the squares b3, b5, c2, e2 (Fig. 1). (However, if the knight begins its movement from square c2, then even on the first move, the Warisdorff rule clearly tells him where to go - to square a1!)

Varisdorf made the statement: no matter from which square the knight begins its movement, any path that satisfies his rules will ultimately lead to a complete circuit of the board (i.e., to the solution of Euler's problem). Until recently, it was not known whether this statement was true. Back in 1971, E. Ya. Gik wrote in «Kvant» (No. 9, p. 53) that Varisdorf’s statement “is always justified in practice..., although it is not confirmed theoretically.”

A program was compiled for the computer “Promin-2” to enumerate a certain set of horse paths. The first countermeasure was built in less than 1 minute. Having tried 6464 paths, the computer received countermeasures

Fig. 1.
Fig. 2.
