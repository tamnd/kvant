---
id: 1982-7-dubrovskiy-algoritm-volshebnogo-kubika-0fa0f2b5
issue: kvant_1982_7
year: 1982
number: "7"
title: Magic cube algorithm
authors:
  - Дубровский В. Н.
rubric: osnovnye-stati
page_first: 24
page_last: 25
page_labels: 22-23
tag: 6OPT
lang: en
source: kvant_digital
extraction: vision
content_sha256: e13e74da8afc81b42c989226788aae73efc71dd0b10c59072bb30fdf158f3ddd
prompt_sha256: draft-1
translated_from: content/ru/1982/07/articles/05_dubrovskiy-algoritm-volshebnogo-kubika-0fa0f2b5.md
source_content_sha256: db5ce15733a30c5ce7ab94d089269a634e6b0218c1bd065bec12b3225155fab0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

V. Dubrovsky

Magic cube algorithm

It is not easy to cope with the “Hungarian magic cube” - the most popular puzzle of the 20th century. Therefore, impatient people, losing hope of success, often stop acquaintance with it, washing it into pieces. They say that after the appearance of the “cube” in Japan, the arbitrariness of labor even decreased, and in the USA this toy is now sold complete with a plastic hatchet: if you can’t solve it, break it!
«Kvant» applies to the Rubik's cube more capable and server-side, as evidenced by the article published below.

In this article we tell you how to solve the magic cube - the famous puzzle of E. Rubik*). Strictly speaking, we do not present here the solution algorithm (that is, a set of exact rules for bringing the coloring of all faces from arbitrary to single-linked) - such an algorithm was already published in «Kvant» (1980, No. 12, p. 17). Instead, we give a large list of useful combinations, indicating for each how to perform (the sequence of turns) and the result (which small cubes are presented and how). Of the various combinations leading to the same result, we tried to choose the shortest one. At the end of the article, we show that the magic cube can be brought to its initial state (with single-edge edges) in 79 turns or less.

*) If you do not have a copy of the cube, you can construct it, using the instructions in the stats of M. Evgraf in «Kvant» 1982, No. 3.

Operation designation

Let's designate each face of the magic cube: F (front), T (rear), B (top), H (bottom), Π (right), L (left) (see Fig.). A clockwise rotation of face X by n · 90° will be denoted by X^n, for example, rotations of the right face by 90°, 180°, 270° are written as Π, Π^2, Π^{-1}=Π^3. Thus, each operation (chain of rotations of faces) corresponds to “words” from the letters F, T, B, H, Π, L with degrees *), read and executed from left to right.

Designation of the result of the operation

We will write down in a single formula both the movement of small cups and the change in their orientation in space.

To record the movement of small cups, we renumber the corner cubes and the corresponding vertices with numbers from 1 to 8, the middle ones (and the corresponding edges) with numbers from 1 to 12 (see figure; records of all operations considered in the statistic refer to the numbering shown in this figure).

Let us assume that as a result of operation F the first corner cube moved to the place of the i_1st, the i_1st to the place of the i_2nd, etc. Each time a new number will appear in this chain and a moment will inevitably come when

*) A funny way to memorize such “words” is given in the article “Hungarian Cube” in the journal “Science and Life”, No. 3, 1981 (p. 131).

⟦folio 23⟧

the cube numbered $i_{n1}$ will return to the place of the first one (why?). Cubes 1, $i_1$, ..., $i_{n1}$ form a cycle in operation $F$, denoted $(1i_1 \dots i_{n1})$. If not all corner cubes have yet entered this cycle ($n_1 < 7$), then take any of the remaining ones (empty number $i_{n1+1}$) and repeat the same process - a second cycle $(i_{n1+1} \dots i_{n2})$ will appear. In the end, the record of corner cubes turns out to be decomposed into independent (that is, having no common elements) cycles: $(1i_1 \dots i_{n1}) \cdot (i_{n1+1} \dots i_{n2})$.

The situation is similar with medium cubes. We will write the corresponding cycles in square brackets; So, the notation [2 7 6] means that the second is middle and the cube goes to the seventh, the seventh to the sixth, the sixth to the second.

Let, as a result of some operation, the $i$th middle cube take the place of the $j$th one. It can be positioned in this place in two ways. If the direction of the arrow attached to its edge (see Fig. 1) turns out to be opposite to the direction of the arrow of the $j$ cube, then in accordance with the cycle we put a minus sign after the number $i$. The absence of a sign means that the directions of the arrows coincide. Thus, the entry $[2^{-7}+6^{-}]$ (or $[2^{-7}6^{-}]$, we usually omit “pluses” for middle cubes) means that the second middle cube moved into the seventh with opposite arrows, the seventh into the sixth with coinciding arrows, the sixth into the second with opposite arrows. The entry $[2^{-}]$ means that the second middle cube remained in place, but turned to $180^{\circ}$.

The corner cube can be positioned in a new place by rubbing in different ways. Accordingly, in the cycle entry after the number of this cube there will be a + sign, a - sign, or nothing will be written. the sign is not written if the horizontal face of a given corner cube remains horizontal after performing the operation. Otherwise, to bring this face to a horizontal position in a new place, we would have to rotate the cube around the diagonal by $120^{\circ}$. If the rotation should be done counterclockwise, put +, if clockwise, put -. Let's say the entries $(5^{+})$, $(5)$, $(5^{-})$ mean that the fifth cube remains in place, but is rotated by $120^{\circ}$, $0^{\circ}$, $240^{\circ}$ clockwise, respectively.

Explanations for the table (see p. 24)

When recording an operation, we will first write a sequence of rotations (a layer of letters F, T, V, N, P, L with degrees), then the sign ~, and then the results, written in the form of cycles with signs. Examples will help you master this recording system; check that $\Pi \sim (1^{+2}-3^{+4})$ [1234], $B^{-} \sim (1276)$ [2$-9-8-7^{-}]$,$\Phi^{2} \sim (15)$ (46) [16] [57], $\Pi\Phi \sim (1^{+2}-3^{-5}-6^{+})$ (4+) [1234567], $\Pi^{2}\Phi^{2} \sim (135)$ (264) [136] [24] [57].

The table lists 47 operations found in the game of cube, sometimes by trial and error, but mostly with the help of some rather interesting algebraic oddities that lack of space does not allow to reproduce here. Operations $C_{15}$ and $C_{19}$ are taken from the “Hungarian Secondary School Journal”, $C_{18}$ - from the above-mentioned article in “Science and Life”.

Algorithm diagram

First stage: assembly of the “column” $2 \times 2 \times 3$. Let us form a “column” the set of all small cubiks that do not lie in two adjacent faces of a large cubika, to determine F and P. To correctly arrange all cubiks in a “column” no special tricks are required. Let us give, for example, operations in which the 1st middle cube moves to the 8th place and in one case retains, and in the other changes its angle of rotation, with all the cubes of the “column”, except, of course, the 8th, remaining intact: $A_1 = \Pi TB^2 T^{-1}$, $A_2 = \Phi^{-1} TB T^{-1}$. This stage can be completed in approximately 25 moves.

Second stage: expansion of the middle cubes in the faces F and P. It is easy to show that for any sequence of turns the number of middle cubes whose arrow directions do not coincide with the “correct” (shown at figure) is always
