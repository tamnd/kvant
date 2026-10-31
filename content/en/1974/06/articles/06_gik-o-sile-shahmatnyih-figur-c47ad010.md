---
id: 1974-6-gik-o-sile-shahmatnyih-figur-c47ad010
issue: kvant_1974_6
year: 1974
number: "6"
title: About the power of chess pieces
authors:
  - Гик Е. Я.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 17
page_last: 18
page_labels: 15-16
tag: TE2D
lang: en
source: kvant_digital
extraction: vision
content_sha256: d18cbe426b5938b34a0bb4bae7479aea3353e95d0f1382602b69465ed8129b98
prompt_sha256: draft-1
translated_from: content/ru/1974/06/articles/06_gik-o-sile-shahmatnyih-figur-c47ad010.md
source_content_sha256: 4c374f256e469aab497174b3bcb54384e553cefeee53bbc99ede13704c713545
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 15⟧

About the power of chess pieces

E. Ya. Gik

If you know how to play chess, then you probably know that a minor piece (knight or bishop) can be safely given for three pawns, and a queen for two rooks; a knight and a pair of pawns compensate for the loss of a rook, etc. Of course, the true strength of a piece depends on the specific position: you can easily give examples when one pawn checkmates the enemy king, surrounded by all the army pieces. And yet it is clear that each piece in a chess game has some average strength. To compare the strengths of pieces, the strength of a pawn is generally taken as one, expressing through it the strengths of the remaining pieces. In textbooks, as a rule, the following scale is proposed:

$$F_{\pi} = 1, \quad F_K = F_C = 3, \quad F_{\pi} = 5, \quad F_{\phi} = 9$$

(we use $F_x$ to denote the strength of the figure $x$).

This scale is confirmed by numerous practices and experiences of chess players. However, there are also purely mathematical ways to determine the strengths of chess pieces. One of the most common methods is related to the mobility of figures. For example, the distance for the king's moves (Fig. 1) From each of the corner squares he can make 3 moves, from the non-corner fields of the extreme verticals and horizontals - 5 moves, finally, from the remaining fields of the board the king is able to move to any of the 8 neighboring fields. Summing up, we get the number of possible moves of the king on the chessboard; we denote this number by $S_{Kp}$:

$$S_{Kp} = 3.4 + 5.24 + 8.36 = 420.$$

From figure 2-6 the numbers $S_x$ are found for other figures:

$$S_{\phi} = 21.28 + 23.20 + 25.12 + 27.4 = 1456,$$

$$S_{\pi} = 14.64 = 896,$$

$$S_C = 7.28 + 9.20 + 11.12 + 13.4 = 560,$$

$$S_K = 2.4 + 3.8 + 4.20 + 6.16 + 8.16 = 336,$$

$$S_{\pi} = 2.10 + 3.32 + 4.6 = 140.$$

If we now divide $S_x$ - the number of possible moves of the piece $x$ - by $N_x$ - the number of squares on which this piece can stand, we get the average number of moves of a piece from one board. Izozem is the number $P_x$ by the mobility of the figure $x$:

$$P_x = \frac{S_x}{N_x}.$$

Obviously, $N_x = 64$ is for all pieces except the pawn, and $N_{\pi} = 48$. Using formula (*) we find:

$$P_{Kp} = 6,5625; \quad P_{\phi} = 22,75; \quad P_{\pi} = 14;$$

$$P_C = 8,75; \quad P_K = 5,25; \quad P_{\pi} = 2,5.$$

Let us assume that the strength of a figure is directly proportional to its mobility. Taking, as above, the strength of the pawn $F_{\pi}$ as one, we express the strengths of the remaining pieces through it using the formula

$$F_x = \frac{P_x}{P_{\pi}}.$$

The result is the following scale (values ​​rounded to

⟦folio 16⟧

tenths):
$$F_{\pi} = 1; \quad F_{Kp} = 2,6; \quad F_{\Phi} = 9,1;$$
$$F_{\lambda} = 5,6; \quad F_{C} = 3,5; \quad F_{K} = 2,1.$$

In the calculations, for simplicity, we did not take into account the possibility of castling, and for tails we also considered the diagonal moves that it makes when capturing. Figures 1-6 highlight the fields from which the corresponding piece can make the maximum number of moves. These squares are concentrated in the center, only the rook is equally “strong” on all squares of the board.

The king received a very low rating in the resulting scale, although in fact his “loss” is not worthwhile *). However, from the point of view of castling, the found estimate fully corresponds to reality. Our scale also has some discrepancies

*) When programming on a computer, a large number is usually chosen for the strength of the king, thereby emphasizing it exclusively.

with practice. Its main defect is the too great superiority of the distant pieces (queen, rook and bishop) over the knight. In chess, the actions of distant pieces are always limited by other pieces. We could take this circumstance into account when introducing correction factors, but for now we are interested. the idea itself, and we don’t dwell on the details.

The mathematical approach to assessing the strength of figures allows us to consider various generalizations. Imagine that you are playing chess with grafted pieces, but on an unusual board, for example, 50 × 50 in size. Based on intuition alone, it will be quite difficult for you to determine the relative strength of the pieces on this board. For example, it is clear that the bishop here is stronger than the knight, but by how much is difficult to say right away. Using the concept of castling introduced above, we can find completely reasonable values ​​for the strength of the pieces and at such
