---
id: 1971-10-gik-shahmatno-matematicheskie-zametki-42e3e501
issue: kvant_1971_10
year: 1971
number: "10"
title: Chess and mathematics notes
authors:
  - Гик Е. Я.
rubric: raznoe
page_first: 51
page_last: 54
page_labels: 49-51
tag: PQBM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6a91ea52820f09145c18566ce6d744d464c7da25269fbfed31268822f745405d
prompt_sha256: draft-1
translated_from: content/ru/1971/10/articles/13_gik-shahmatno-matematicheskie-zametki-42e3e501.md
source_content_sha256: 3cbea591c1fb1ca09be3967fd4cc765c81d6db51c884abdc7ace6644524395e8
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 49⟧

Queen—sentinel

In the previous section of our notes*) we established that a knight can move around all squares of an 8x8 chessboard, raising only once on each of them.

The question of traversing an ordinary chessboard with other pieces is solved much more simply. For example, for Lada, such a route is depicted at figure 1. Here

Fig. 1.

The rook is added to its target, making 14 turns along the way. Prove that this number cannot be reduced.

The indicated path (by the way, it is also suitable for the queen and king) is not closed. However, we can

*) See «Kvant», No. 8, 9.

It is also possible to propose a closed route (Fig. 2). Here the rook is at

Fig. 2.

desires from the final field of their journey - a2 can return to the initial one - a1. See for yourself that on an odd-numbered board (for example, 7x7 or 9x9), a closed path for the fret no longer exists.

It is clear that for the bishop the problem in the general case is formulated incorrectly (the bishop can only move on squares of the same color), but if we limit ourselves to only white or black squares, then it can also be easily solved.

Now we move on to one of the most common materials -

mathematical problems on a chessboard. These problems involve various figure arrangements, which is why they are usually called combinatorial. Please, the most famous of them is the following “problem about eight queens”, posed in 1850 by the great German mathematician F. Gauss.

Look at the 8 queens on the chessboard

Fig. 3.

so that no two of them touch each other*).

figure 3 shows one of the possible

*) Of course, from a chess point of view, two pieces of the same color cannot threaten each other, but we get the traditional terminology.

⟦folio 50⟧

There are 92 possible solutions to the problem, in total there are 92 of them. It is also proven that all of them are obtained from 12 basic positions by using mirror reflection and rotating the board by 90°, 180° and 270°. For example, mirroring (relative to the dotted line) the position of the reduction, we obtain another position that sets us (Fig. 4) *).

It is curious that Gauss himself initially imagined that the problem allowed only 72 solutions, and doubted the correctness of the number 92. In ours, this problem and similar ones are solved in a few minutes. It is enough to compose several programs and enter them into the computer, and soon all 92 positions will be printed.

Let us formulate two questions that lead us, respectively, to two classes of various combinatorial problems.

*) This problem is solved in detail in the book by L. Ya. Okunev “Combinatorial problems on a chessboard” (ONTI NKTP USSR, 1936)

1. What is the maximum number of identical pieces (queens, rooks, knights, bishops and queens) that can be considered on the board so that no two of them cancel each other out?

2. What is the maximum number of identical pieces that can be considered on the board so that no two of them cancel each other out?

The first of these numbers in graph theory is called the internal stability number, and the second is the external stability number. These concepts are far from abstract, and play an important role in many mathematical problems. An example is the following well-known

Assignment about clocks. In the prison of the city N, you can see a sentry near each cell. Being at one of the cells, the sentry also sees what is happening in some of the others, from which corridors lead to this cell. What is the maximum number of sentries required to monitor all cameras?

If the chessboard is considered as a prison (may chess players forgive us such an analogy), and its fields are considered cells, and the verticals, horizontals and diagonals are corridors, then the “sentries” are most natural to appoint pieces that can lead the attack in any direction.

It turns out that 5 queens are fully capable of coping with the entire chess “prison” (Fig. 5). Essentially, we determined the number of external stability for queens equal to 5 (it is not difficult to show that four hours has not been reached). It has been proven that there are 4860 ways that can be considered

Fig. 5.

5 sentinel queens. By the way, in our example, the queens have another interesting property: they themselves do not cut off each other.

From the above it follows that in order for a lone enemy queen to appear (there are no kings on the board), it is enough to have 5 queens. However, it is known that in checkers 3-dampers can cope with one (if it is not on the “high road”), although they are not able to hold all the black squares of the board at the same time. It is interesting to find out whether it is possible to create an enemy queen with less than five queens.

⟦folio 51⟧

If you put 9 queens on the board, then at least two of them will be on the same vertical or horizontal, that is, they will threaten each other. Thus, the number of internal stability for queens is 8 (Fig. 3, 4), and the total number of suitable positions is 92.

We found the problems especially easy to solve for the rook—perhaps this reflects its straightforwardness. You must have rook sentries

Fig. 6.

8, it is enough to place them along any horizontal or vertical. It is also easy to show that the number of internal stability for a rook is 8, and has 8 corresponding locations! — number of permutations of 8 elements *) (n!=1·2·····n). The position at figure 6 satisfies the general requirements.

Prove that if the rooks are laced, that is, different from each other, then it is necessary to locate

*) See, for example, the article by N. Ya. Vilenkin “Combinatorics” («Kvant» No. 1, 1971).

there are already (8!)². On a board of size n×n, these numbers are respectively equal to n! and (n!)².

To cope with the entire board, it is enough to have the same number of bishops as rooks - 8 (Fig. 7). However, it is possible to place bishops on the board so that they do not threaten each other almost more than rooks - 14 (Fig. 8). To prove the distance, the diagonals go up from left to right (at figure 8 they are dotted), there are 15 such diagonals in total. On each of them there can be no more than one bishop, since the bishops should not threaten each other. Consequently, the total number of bishops does not exceed 15. It is also impossible to arrange exactly 15 bishops: the outermost of our diagonals will be made up of one single square. Thus, the required number is no more than 14. However, the solution is given in figure 8. Similar calculations show that on a board of size n×n it is possible to place no more than 2n - 2 bishops.

Prove that the number of admissible bishop arrangements on an arbitrary

Fig. 7.

Fig. 8.

board is equal to the square of a certain number.

Now let's move on to the horses. By placing 32 knights on one white or one black square, we will find an arrangement in which they do not threaten each other. Let us show that 32 is the number of internal stability for knights. To do this, we divide the board into 8 equal rectangles (Fig. 9). It is easy to notice that the horse, placed

⟦folio none⟧

A rectangle attacks exactly one square of the same rectangle, and for any two such knights the fields they attack are different. Since each rectangle has 8 squares, a maximum of 4 knights can be placed inside it without threatening each other, and the total number does not exceed $4 \times 8 = 32$. Prove that there are only two mentioned arrangements - the knights stand only on white or only on black squares.

The external stability number for knights is 12 (Fig. 10). Now let's deal with the kings. It is easy to check that it is impossible to place more than 16 kings that are not adjacent (that is, not threatening each other) (Fig. 11).

External stability number for kings

Fig. 9.

right 9 (Fig. 12). In each of the 9 selected rectangles, figure 12 has a square that can only be threatened by a king standing on the square of the same rectangle. Therefore, in order for all squares to be at risk, each of the 9 parts must have at least one king, the required number is 9.

Fig. 11.

Fig. 12.

Obviously, two pawns cannot threaten each other at the same time. However, if in question 1 (p. 50) the words “each other” are replaced with the words “at least one other” and the caves are allowed to stand on the first horizontal line, then questions 1 and 2 will become correct for the caves as well. The answer is the number 32, with the location of the pawns at Fig. 12.

Fig. 13.

Sunke 13 satisfies the general requirements.

The results of our research can be summarized by filling out the table (see page 51).

It is up to you to reproduce the missing evidence, find the number of corresponding locations and draw conclusions from the table. As scales for service tasks, we can recommend all those we have seen, but on a board of size $n \times n$*). Note that some of these scales are complex, while for others solutions have not yet been found. For example, the external stability number for queens is still unknown. In other words, the following problem has not been solved.

Problem. What is the smallest number of queens that can be placed on a chessboard of size $n \times n$ such that all of its free squares are threatened?

*) A number of such problems are discussed in the book by A. M. Yaglom and I. M. Yaglom “Non-elementary problems in an elementary presentation”, M., Fizmatgiz, 1954.
