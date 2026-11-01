---
id: 1980-3-bartenev-bluzhdayuschie-fishki-58200936
issue: kvant_1980_3
year: 1980
number: "3"
title: Wandering chips
authors:
  - Бартенев Ф. А.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 40
page_last: 41
page_labels: 38-39
tag: WTXB
lang: en
source: kvant_digital
extraction: vision
content_sha256: f2247818361d86b4c34cfd64f96a98ef1a2dc9ecc5354a3f4f45f224f9b64c28
prompt_sha256: draft-1
translated_from: content/ru/1980/03/articles/12_bartenev-bluzhdayuschie-fishki-58200936.md
source_content_sha256: 71c45beb26e1ca9c9e525991ee7be7835d086eccabeb1835bb89cba19a725d37
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

F. Bartenev

Wandering chips

We often assume that people spend most of their inventiveness on purposes, and therefore mathematical problems deserve attention not in themselves, but because they develop discovery.

Leibniz

Probably, many of the readers are familiar with the game “corners” on a chessboard. It is a prototype of a variety of games, entertainment, and tasks with interesting and honorable content. Next we will look at some of them.

As boards we will consider arbitrary rectangles, divided into congruent

Fig. 1.

Fig. 2.

ny squares (see figure). We will indicate the initial positions of the chips with black circles, and the final positions with dotted lines.

Each of the fields (cells) of the board has its own designation, its own “address”, its own “coordinates”, just like on a chessboard. For example, on figure 1 one of the chips is on the c2 square. Of course, usually these designations are not written in the margins of the board, but they are not difficult to identify, since figure is always indicated by the letter designations of the vertical and the number of the horizontal.

Now let's talk about the correct movements of chips. Each piece can move to any adjacent (horizontally or vertically) field. For example, a chip standing on the c2 square can go to one of the following squares: b2; d2; c3; c1. We will write the corresponding moves as follows:

c2—b2; c2—d2; c2—c3; c2—c1.

A piece can “jump” over its “neighbor” (in one of the indicated directions) to a free field. For example, on figure 1 the move d6-d8 is possible. In one move, a chip can even make several such buckles, and their directions can be different. So, on figure 1 chip from the d6 square can move by moving d6—f6—f8 to the f8 square or by d6—f6—h6 to the h6 square.

Example 1. figure 2 shows a 1x25 board, the position of three pieces is specified, and the position to which they need to be moved is indicated.

It turns out that the required movement can be accomplished in 33 moves: you need to move the entire configuration of chips as a single unit two squares to the right with the following three moves:

1. c1—d1;
2. a1—c1—e1;
3. b1—c1.

⟦folio 39⟧

Fig. 3.

Since the configuration needs to be moved 22 fields to the right, you can apply this technique 11 times, spending exactly 33 moves on all moves.

Task 1. On the same 1x25 board, four chips are placed (Fig. 3). Is it possible to carry out the corresponding movement in less than 33 moves?

Task 2. There is an infinite board whose width is 1. Show that it is always possible to place n chips on it (n≥3) so that, after making three moves, you can initially obtain a configuration of chips shifted two cells to the right.

We looked at several examples of moving pieces on a board whose width was equal to one. If we consider the movements of chips on a board of size $m \times n (m > 2, n > 2)$, it becomes possible to use more diverse techniques. Let's look at some examples.

Task 3. Is it possible to carry out the movement indicated on figure 4 in less than 40 moves?

Example 2. It is required to move each chip from the central part of the board (Fig. 5) to one of the corner fields.

It turns out that a given movement can be completed in 22 moves, for example, as follows:

1. d4—d6; 7. c8—b8;
2. d5—d7; 8. b8—a8;
3. d6—d8; 9. e8—f8;
4. d8—e8; 10. f8—g8;
5. d7—d8; 11. g8—h8;
6. d8—c8; 12. e5-e3, etc.

Here we are faced with the need to see the steps or stages into which it is desirable to divide the process of solving a problem. At the same time, we did not raise the question of determining the smallest number of moves required.
