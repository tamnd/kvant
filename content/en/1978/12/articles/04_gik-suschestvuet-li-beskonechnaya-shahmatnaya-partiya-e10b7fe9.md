---
id: 1978-12-gik-suschestvuet-li-beskonechnaya-shahmatnaya-partiya-e10b7fe9
issue: kvant_1978_12
year: 1978
number: "12"
title: Is there an infinite chess game?
authors:
  - Гик Е. Я.
rubric: osnovnye-stati
page_first: 12
page_last: 13
page_labels: 10-11
tag: AEVL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 285e0cdeba4a6718e300f80288de6e6c0968db9c3987708b1839f7efd8ba48e2
prompt_sha256: draft-1
translated_from: content/ru/1978/12/articles/04_gik-suschestvuet-li-beskonechnaya-shahmatnaya-partiya-e10b7fe9.md
source_content_sha256: 230471072843a064cc0ccb39b7634df4eb3119824562b33fa54894c0dfc78820
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

E. Gik

Is there an endless chess game?

The new rules for holding a World Chess Championship match, in principle, allow for a situation in which the match can continue indefinitely or until one or all participants are completely exhausted.

Can a chess game itself last indefinitely?

If a checkmate position has arisen on the board, then it is clear that no matter how long the game lasts before this position occurs, it will end in a finite number of moves. Thus, the resulting game cannot be infinite. In a drawn position, the game could continue indefinitely if there were no special clauses in the rules of chess.

Let us recall the well-known rule of chess in a chess game: if the same position appears on the board three or more times, then at that moment you have the right to demand a draw. Saying that one position should be on the same side and the internal influence of the position should also be the same (this applies to castling and taking pawns “on the aisle”).

We will assume that with a threefold repetition of the position, a draw occurs automatically. Then from the finite number of chess positions it follows that the duration of a chess game is limited from above. Let us denote the number of different positions on the board by A.

Exercise 1. Find some upper bound for A.

It is clear that then no game can last more than 3A moves (by move we mean two

⟦folio 11⟧

half-move - white and black). Indeed, during this time at least one position will be repeated three times (if it is the same side’s turn), and if the game has not ended earlier, then the referee will record a draw in the game together. Consequently, under our assumption (which is not in the chess code!), the rule of repeating a position three times excludes an endless game.

Let us now assume that there is nothing real when repeating not the same position three times, but the same series of moves in a row. Let us show that under this condition an infinite chess game can exist, that is, there is a game in which no series of moves is repeated three times in a row.

Let's consider the simplest case, when only kings move on the board. Moreover, we will allow each of them to maneuver on only three fields! Let the white king move in the lower left corner - along squares a1, a2, b1, and the black king in the upper right - along squares h8, h7, g8 and there are no other pieces on the board. Let us denote the clockwise move of each king by 1, and the counterclockwise move by 2. If the initial position of the queen is fixed, then each of their movements corresponds to a limited sequence of ones and twos. The converse is also true: any sequence of ones and twos defines a certain movement of the queens. If, for example, the kings are on the corner squares (white - on a1, black - on h8), then the sequence 12 21 21 12 21 12 corresponds to the following moves: 1. Kr a1-a2 (the first member of the sequence 1 - the white king goes clockwise) 1 ... Kr h8 - g8 (the second term 2 - the black king moves counterclockwise) 2. Kr a2-a1 Kr g8 - h8 3. Kr a1 - b1 Kr h8 - h7. 4. Kr b1 - a1 Kr h7 - h8 5. Kr a1 - b1 Kr h8 - h7 6. Kr b1 - a1 Kr h7 - h8.

Thus, in the language of mathematics, our task can be formulated as follows: to prove that there exists an infinite sequence consisting of the numbers 1 and 2, in which there are no three identical adjacent numbers. In the book by A. M. and I. M. Yaglomov *) it is proven that there are arbitrarily specific sequences consisting of the numbers 1 and 2, in which there are no identical adjacent numbers. Consequently, there is an infinite game in which no series of moves occurs three times in a row.

Let us now indicate the rules of the chess code that exclude the existence of an infinite game.

This is, firstly, the “fifty-move rule”: if for 50 moves in a row not a single piece has been captured on the board and not a single pawn has made a move, then the game is considered a draw. Secondly, the game is considered a draw if a position has arisen on the board in which winning is impossible (king against the king, king against the king and a minor piece, king and bishop against the king and bishop of the “same color”).

*) A. M. Yaglom, I. M. Yaglom. Non-elementary tasks in an elementary presentation. M., Gostekhidat, 1954. Problem 1236).
**) «Kvant», 1975, № 9.
