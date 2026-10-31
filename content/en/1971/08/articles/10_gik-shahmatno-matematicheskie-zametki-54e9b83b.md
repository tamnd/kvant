---
id: 1971-8-gik-shahmatno-matematicheskie-zametki-54e9b83b
issue: kvant_1971_8
year: 1971
number: "8"
title: Chess and mathematics notes
authors:
  - Гик Е. Я.
rubric: raznoe
page_first: 57
page_last: 61
page_labels: 55, 56, 58, 59
tag: 5YQG
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8736a72bd2ac28151513dbc3b8122d1959bb64bee89e26ee00befa7e150ca30e
prompt_sha256: draft-1
translated_from: content/ru/1971/08/articles/10_gik-shahmatno-matematicheskie-zametki-54e9b83b.md
source_content_sha256: 54703c62a6750c12f932c42b48a915f0132dfad6e35cbb323b668bc39cf7967c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 55⟧

Chess and mathematics have quite a lot of common ground. Our notes will focus mainly on mathematical problems on the chessboard.

Flipping through books with such attractive titles as “Mathematical Kaleidoscope”, “In the World of Mysteries and Wonders”, “Fun and Entertaining Numbers and Pieces”, you probably noticed that each of them contains many problems about the pieces on the chessboard.

Otherwise, these are puzzles that any knowledgeable person can cope with; more often than not, this requires certain mathematical experience and knowledge. Such problems can be found not only in popular books, they are regularly presented in mathematical circles, at Olympiads, and are often found in professional mathematical literature. In short, there are many mathematical problems, both simple and complex, with different chess content.

The purpose of these maths is precisely to try to systematize these problems to some extent and at least briefly talk about the most interesting of them.

We hope that you are familiar with the moves of chess pieces, although we warn you in advance that no special skill in playing chess is required.

Perhaps some of you will decide that mathematicians have gone completely crazy and, while doing their work, have fun by arranging pieces on the board (it would be better if they just played chess!).

However, the work of mathematicians in this direction has its own meaning. The fact is that to solve a number of important mathematical problems, a chessboard and pieces are very convenient to use as a model.

It is no coincidence that chess terms can be found in the literature on game theory, cybernetics, graph theory, combinatorics, number theory, and programming.

Let's give one example. What was promised by the international concept of “rook” and the purely mathematical “polynomial”? Nevertheless

⟦folio 56⟧

American mathematician D. Riordan in his book “Introduction to Combinatorial Analysis” (Moscow, IL, 1963) uses the term “rook polynomial!” What causes this?

It turns out that a large class of combinatorial problems comes down to determining the number of placements on a chessboard of a given number of rooks that do not threaten each other (no pair of rooks should be on the same vertical or horizontal). And when considering even more complex problems, the polynomial plays a significant role

$$R(x) = r_0 + r_1x + \dots + r_kx^k + \dots + r_nx^n,$$

where $r_k$ is the number of placements on the exchange board $n \times n$ of $k$ rooks ($k=0, 1, 2, \dots$) not threatening each other. This polynomial was called the rook polynomial by Riordan; as we see, this name is completely justified.

Note that a bottomless sea of ​​tasks and problems will arise when it comes to creating a machine, a chess toy (or rather, a program for it).

Tens and hundreds of special articles, books, discussions and even dissertations are devoted to this fashionable topic these days, and we will not dwell on it in detail.

From the Shah of Persia to the present day

Our conversation naturally begins with a consideration of the properties of the chessboard, without yet arranging the pieces on it.

Of course, each of you has heard the famous legend about the origin of chess. The sage who invented them demanded from the Persian Shah, who really liked the game, as much grains of wheat as would be needed to cover all the cells of a chessboard, if one grain was placed on its first cell, and on each subsequent cell twice as much as on the previous one (Fig. 1).

Fig. 1.

It turned out that there was not enough wheat for this, stored only in the barns of the Persian Shah, but also in all the barns of the world. The sage humbly demanded

$$1 + 2 + 2^2 + 2^3 + \dots + 2^{63} = 2^{64} - 1$$

grains This number is written in twenty digits and exceeds 18 quintillunes ($2^{10} = 1024 \approx 10^3$). Of course, there is little connection here with mathematics; rather, the result obtained symbolically illustrates the vast mathematical possibilities hidden in the chessboard.

Please, the most favorite property of a chessboard is that the shortest distance on it does not necessarily change in a straight line. For example, the geometric distance from square a1 to square h8 is greater than to a8, and the king needs exactly 7 moves for any of these transitions. For mathematicians who deal with a wide variety of distances (metrics), this is a common matter.

The pointing property is particularly effective in the meaning of this Reti (Fig. 2).

It seems completely incredible that in this position the white king is able to catch up with the black wheat.

Fig. 2. R. Reti, 1921
Draw.

However, this becomes possible if he

⟦folio 58⟧

therefore there is no necessary covering!
Some problems require you to cut a chessboard in such a way that certain conditions are met. We will not dwell on such problems now.
Sometimes, together with general chess, their various appearances associated with the transformation of the chessboard will be considered.

A)
b)
b)
V)

Pris. 5.
a) Cylindrical chessboard without vertical p.
b) Torondal chessboard.
c) A conical chessboard is obtained by gluing the vertical a to the eighth horizontal.

Moreover, these transformations are fully mathematical in nature. Most often this is done in chess problems. In «Kvant» (see No. 5, 1970) we already talked about cylindrical and torondal chess. It is interesting to consider a cylindrical board with one vertical cut out (Fig. 5a). On such a board the bishop is placed like a chameleon: it turns from light-squared to black-squared and vice versa!
Of course, the cylinder and torus (Fig. 5b) are far from the only ones

surfaces that can be glued together from a chessboard. There are also many tricks in conical chess (Fig. 5c).

It is easy to give examples of chess problems that can be solved

Fig. 6. Checkmate in one move.

on one of the mentioned boards and do not dare on others. For example, the task “checkmate in one move” on figure 6 looks ridiculous. However, on a cylindrical board that is bent by vertical a and h, it can be done: 1. h3-h4 checkmate! Squares b4 and b6 are held here by the knight, a6 and b5 are held by the bishop, and the black king is not allowed onto the h-line by his white opponent. Note that with a white pawn on h2 there is no longer mate, since after 1. h2-h4 Black takes on the pass *): 1...a4:h3.

However, even on a cylindrical board it is possible to

*) Capture for passing - capturing a non-hiding (say, black) pawn that has advanced from its initial position two squares and has become horizontally adjacent to the white pawn. In this case, the opponent's pawn (black) is removed as if it had advanced one square.

⟦folio 59⟧

Not everything that is possible on a regular one is available. For example, in order to mate the opponent’s lone king with a king and a rook, it is not enough to pin him on the a or h line, you also need to drive him to the first or eighth rank, and on a cylindrical board this is impossible. On a toroidal board, as is easy to see, even the queen cannot cope with the opponent’s “naked” king.

Here's another funny example (Fig. 7). Here, mat in two moves is given both on a regular and on a cylindrical board, but on each of them in its own way.

Fig. 7. Checkmate in two moves.

On a regular board everything is very simple:
1. La5 : a6 Npb1 - c1
2. La6—a1 mat.

On the cylindrical one, after the move 1. Ra5: a6, the rook loses to the answer 1... h7: a6! On the other hand, if the rook moves away from a5, then Black will advance the a6 pawn and there is no checkmate. Resolves 1. La5—a5!! — the rook goes around the circle and returns to the original square!

The rest is clear: 1...Kpb1—c1—2. La5—a1 mat.

We invite you to come up with similar examples on toroidal and conical boards yourself.

Among the Yugoslav chess problems of distribution are the so-called project chess on an infinite chess board

Fig. 8. Spherical chessboard. From the additional outer field (red) surrounding the entire board, you can enter the board anywhere and in any direction (vertically, horizontally or diagonally). For example, a rook on an empty board can move the enemy across all squares in one move (passing 7 times through the outer square).

Board with four additional fields. On a folded board with one additional field, spherical chess is obtained (Fig. 8). However, a detailed study of the chess game on the resulting boards is not included in our plans.

At the end of this section, we offer you several problems to solve on your own; the answers to them will appear in the next issue.

1. Prove that a 10x10 100-square board cannot be completely covered without overlaps with figures, an example of which is given in figure 9.

Fig. 9. Fig. 10.

2. A typical domino consists of two squares. Let's create a "trimino" figure made up of three squares (Fig. 10). If a chessboard is covered with twenty-one triminoes, then one square remains free. What could it be?

3. 12 squares (Fig. 11) are cut from an 8x9 board. Prove that the remaining part cannot be covered with triminoes.

Fig. 11.

4. Let the board have an odd number of fields (for example, its size is 7x9). The fields on the common side are completely adjacent. Let's place a pawn on each square of the board, then collect these pawns and place them on the board again.

a) Can each pawn now end up on a square adjacent to the one it occupied during the first placement?

6) Suppose that during the secondary arrangement, the pawns occupying equal left corners remain in place, and the pawns that stood next to each other during the first arrangement still stand next to each other. Could any pawn change its position?
