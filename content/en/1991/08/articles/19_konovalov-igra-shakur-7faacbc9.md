---
id: 1991-8-konovalov-igra-shakur-7faacbc9
issue: kvant_1991_8
year: 1991
number: "8"
title: Shakur game
authors:
  - Коновалов С. П.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 72
page_last: 75
page_labels: 70-73
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9744ac5c2e1ad3392eba819366c1b407221d86e1e337a2d26b8d51abacce0d88
prompt_sha256: draft-1
translated_from: content/ru/1991/08/articles/19_konovalov-igra-shakur-7faacbc9.md
source_content_sha256: 22634e047f37376cb43e1dad5010138a3a4f6b7e14bd9c42f1e7a0f943882945
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 70⟧

---
running_head:
folio:
---

Shakur game
S. KONOVALOV

In one of the issues of the Quaenta chess page there were problems in which at some point the board turns. This changed the direction of movement of the pawns, and therefore led to a different position. A natural thought for mathematics arises: consider a version of the game in which transforming the chess space would be a real move. One implementation of this idea can be obtained on a Rubik's cube - a Rubik's chess cube, or, for short, a shakur.

The game will be superficial (in a geometric sense), the “board” consists of 54 cells. At each vertex of the cube there are three cells, so we will not be able to preserve the general Friday coloring and will consider the board to be one-pointed (white), and the pieces to be red and black (Fig. 1).

Let's revive the chess pieces (all except the pawns, which we haven't come across yet, since today we'll look at the simplest type of game - checkmate of the lone black king). A piece (king, queen, rook, bishop or knight) can move from square A to square B if on some development of the die the piece can go from A to B according to the general chess rules, but we will prohibit the bishop from moving from one square to another if they have a common side. We will make a similar exception for the diagonal moves of the queen, otherwise these pieces would be too powerful.

To make it easier for the reader to get used to the geometry of our chessboard, we recommend making a set of shakur pieces, consisting of a Rubik’s cube and sticker pieces made with adhesive tape.

Fig. 1.

Fig. 2.

⟦folio 71⟧

---
running_head:
folio:
---

The simplest moves (and, accordingly, developments) of the rook and the king (Fig. 2). In the future, in the drawings we will mark with dots the fields on the “visible” faces accessible to the figure.
For an elephant, if it does not occupy the central or corner square of a face, the broken fields form two diagonal meridians intersecting at two antipode poles. figure 3 shows two elephants located at such poles and having identical trajectories.
Problem 1. Draw the development of a cube to determine one move of the bishop $C_1$ from the position on figure 3.
The possibilities of a bishop located in the central or corner square of a face are shown at figure 4.
Problem 2. Check that in a few moves the bishop can get from any square of the board to any other. In what minimum number of moves can the bishop get from square 1 to square 2 (see Fig. 4)?
Task 3. Analyze the properties of the queen.
Even on the general board, the knights stand out for their insidious moves; on the dice, their moves are even more unexpected (see Fig. 5).
Note that in the described way it is possible to determine the moves of figures on the surface of a checkered cube with faces of size $n \times n$, and not just $3 \times 3$.

Fig. 4.
Fig. 5.
Fig. 3.
Fig. 6.

⟦folio 72⟧

---
running_head:
folio:
---

On such a board you can solve general problems with “active” movements of the pieces. For example, prove that the red king and rook can mate the lone black king; the final position could be the same as at figure 6.

It is curious that transferring to a rook, which is minimally sufficient to defeat a lone king on the general board, turns out to be sufficient on the die! Even more unexpected is that on the $3 \times 3$ cube you can come up with mating positions in which the kings on the strongest side involve two bishops, a bishop and a knight, two knights - again just like on the general board.

figure 7 shows the matte position; the symbol $\infty$ in a square of the board means that the bishop is on a distant anti-field square, and as we know, such a double bishop acts as if it is in the seen square. From figure 8 it is clear that, together with the red king, the invisible bishops cut off all the escape routes for the black king, and one of them also announces check - checkmate on the board.

Let us present without comment a few more mating positions.

In the position at figure 9 we will not be able to rotate the cube so that all the figures are on the visible faces. The red king is located on the invisible bottom edge of the cube, part of which is depicted as a scan.

It would be possible to continue to consider “exposing” chess moves

⟦folio 73⟧

---
running_head:
folio:
---

on the cube and solve the corresponding problems, but we have a different goal in this note - to use the range capabilities of the Rubik's cube.
Let us call two positions compatible if one can be obtained from the other by rotating the faces of the cube.
For example, the position depicted at figure 6 is compatible with the position at figure 10.
Now we can finally sort the conditions of the Shakur game: from a given arrangement of red and black pieces, we can obtain, by rotating the faces of the cube, a position compatible with it in which the black king would be checkmated on the board.
The solution to such a problem will consist of two parts: first you need to come up with a mating position, and then get it by making rotation moves.

Emphasizing that the pieces will only move with the board.
For those who want to come up with problems, we note that with a large number of black pieces, their role will be twofold: they can destroy the attacks of the red pieces, but they can also limit the mobility of their own black king.
As in a regular chess composition, it would be possible to introduce restrictions on the number of moves/rotations (“checkmate in two moves”), but we will not do this.
In conclusion, we offer readers four more problems (Fig. 11) with the same sketch task: find a win in the game Shakur, that is, mate the black king with rotations of the Rubik's cube (there are no figures on the invisible faces).

Task 4.

Task 5.

Fig. 11.

Task 6.

Task 7.
