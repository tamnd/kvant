---
id: 1986-5-gik-beskonechnaya-doska-73084bdc
issue: kvant_1986_5
year: 1986
number: "5"
title: Endless board
authors:
  - Гик Е. Я.
rubric: shahmatnaya-stranichka
rubric_sub: Шахматы
page_first: 67
page_last: 67
tag: 4SQP
lang: en
source: kvant_digital
extraction: vision
content_sha256: b6b905fd397a2f25ace51e1688528ed3fc639bf246f4de354281c91dad235f1a
prompt_sha256: draft-1
translated_from: content/ru/1986/05/articles/01_gik-beskonechnaya-doska-73084bdc.md
source_content_sha256: 8cfa3a6c13b077ac766133c1e80f41168388850983ecca8d4bd114e26ea87ae9
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

ENDLESS BOARD

Today we will look at several chess-mathematical problems and puzzles on an unlimited board.

There are two white queens and a black king on an infinite board. Can White checkmate? If so, then in how many moves? Does this depend on the initial arrangement of the pieces?

Mat is placed no later than the fourth move for any initial arrangement of the pieces. First, one of the queens declares a check along the vertical line, and in response to the absence of the king on one of the adjacent lines, the second queen pinches the king on two vertical lines. If an ordinary board is considered as an unlimited fragment, then we can assume that approximately the following position arises: queens on squares c1 and f8, king on d4. Now any move of the king is followed by a horizontal check with checkmate on the next move, for example: 2... Ke4 3. Qs4+ and 4. Qff4×.

Now let's send the king to the endless board.

In how many different ways can the king travel between two arbitrary squares of an infinite board in the following number: 2... Ke4 3. Qf4+ and 4. Qff4×.

Let's choose one of the squares as the initial one, draw two diagonals through it, dividing the board into four right angles, and rotate the board so that the final square for the king is on top (in the next figure, one square is also offset by a circle).

Now three units are written into the adjacent fields with the king, and then on each field of the next horizontal line the sum of the numbers of those fields of the previous horizontal line from which the king can get to this field is placed. The numbers written on the margins of the board are the number of shortest routes for the king from the original square to the given one.

The resulting table is called a 3-arithmetic triangle; its properties are studied in detail in combinatorics. Of course, it would be possible to construct a numerical table on the entire plane at once, but it is clear that in the other three corners the picture will be completely repeated. On the other hand, if we are interested in the general principle and a specific answer for two given fields, we can limit ourselves to considering the rectangle marked off at figure by a dotted line, because, having left this rectangle, the king will no longer be able to travel the path between the selected fields in the shortest number of moves.

The next necessary problem on an infinite board was invented by the American mathematician S. Norton.

Can White win in the next position (the board is unlimited on both sides)?

At first glance, each task is impossible, since the black king of Ubet is on top or to the east. If the rook interferes with his movement, then the king approaches it, groans from his place, and one of the directions becomes open, and White’s king, it seems, is not in time to help. And yet White can mate the black king without even leaving the 9x11 rectangle! Here's how to solve this problem.

1. Le2! Kd4. After 1...
Kd3 2. Re11 Black only loses tempo compared to the main line. 2. Kb2 Kd5 3. Krs3 Kd6 4. Kd4 Kd7 5. Re11! Kd8 6. Ke5 Kd9 7. Kf6 Kd10. As if White's efforts were not increased by success, the rook must leave, freeing

way to the black king. However, White achieved an important goal - he moved the king to the right of the rook, and now both of their pieces are involved in the encirclement. 8. Lii11! Cre10. The king can only go east, but he won’t go far. 9. Kg7 Kf10 10. Kh8 Kg10 11. Ki9! That's it, the black king is cut off in both directions. The further game consists of simply mating a single king on a board of finite dimensions. From the solution of the problem it follows that on a board bounded on two sides, the king and rook can cope with the opponent’s lone king, regardless of the initial position of all three pieces.

Competition problems

9. White starts and gives mat in 2 moves.

10. White starts and gives a draw.

The deadline for sending the decision is July 20, 1986 with a note on the envelope “Chess competition “Kvata”, given 9, 10.”
