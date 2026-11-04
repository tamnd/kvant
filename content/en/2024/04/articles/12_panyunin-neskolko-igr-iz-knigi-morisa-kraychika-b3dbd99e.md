---
id: 2024-4-panyunin-neskolko-igr-iz-knigi-morisa-kraychika-b3dbd99e
issue: kvant_2024_4
year: 2024
number: "4"
title: Several games from the book by Maurice Krajcik
authors:
  - Панюнин Н. М.
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 34
page_last: 37
page_labels: 34-35
lang: en
source: kvant_digital
content_sha256: e1ed7d0cfcbf489ffd72351d1ccdd8548d33068a1dc92bcc83e99813396d0ffa
prompt_sha256: draft-1
translated_from: content/ru/2024/04/articles/12_panyunin-neskolko-igr-iz-knigi-morisa-kraychika-b3dbd99e.md
source_content_sha256: 08d0ba5b51d53244862e87633a86e0a17dd1e6f022e6ecc7b80b805c0caa353d
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

Several games
from the book by Maurice Krajcik

Maurice Krajcik's book Mathematical Fun contains more familiar games and puzzles that many students could play while passing the time during recess. This is a sea battle, and corners, and points. There are also once very popular games that, unfortunately, are forgotten by modern schoolchildren. For example, tags.

We advise the reader to consult the book. Indeed, in addition to descriptions of games, the history of their appearance is sometimes told there. And besides, you can find out what game the great Leibnitz played.

I already talk about some games on pages «Kvant». For example, “Lasker checkers” [1] or “yoga” [2]. Now we will tell you about four more, to play which you only need a piece of paper and a pencil.

1. Connecting the dots (joke game). An arbitrary set of points is offset on the plane. Two players take turns drawing lines (which can be curved). In one move, you can draw a line connecting two offset points; however, the line should not pass through other offset points. No point can be the endpoint of more than one line. No two points can be connected by more than one line. No two lines can intersect. The loser is the one who is the first to fail to draw a line that satisfies this condition.

You can consider a version of this game where it is allowed for points to be endpoints for several lines at once.

Exercise. Prove that this version of the game will also be a joke game, i.e. The outcome of the game does not depend on how the opponents play.

2. Cells in a line. The game is played on a square field of $n^2$ cells. Players take turns placing their own distinctive sign in each cell (for example, a cross and a cross). Whenever a player places the last square in a row of squares parallel to the side or diagonal of a large square, he is given a number of points equal to the number of squares in that row. The player with the highest total points wins.

For example, in the situation depicted in figure 1 (the subscripts indicate the move number), the crosses received three points for filling a three-cell diagonal on move four, and the crosses received two points for filling a two-cell diagonal on move five. On their next move, the regiments can immediately receive $3 + 2 = 5$ points.

3. Dots-cells. The playing field is a square of $(n+1)^2$ points. Two players take turns drawing horizontal or vertical lines connecting pairs of adjacent dots. If a player draws a quarter of the side of one of the $n^2$ small squares that can be formed on figure, they are considered to have captured that square. The player who has captured the square may draw another line in the same turn, so that the player's turn only ends when he draws a line that does not complete the square. The winner is the one who captured a large number of such squares.

On figure 2 the possibility is shown by the side showing the move number, and the color

⟦folio none⟧

for clarity, the segment shows the player who made the move). You can notice that after any next move of the first player, the second will be able to capture the square. This game is known in many countries under different names. Its rules were first published by the French mathematician Edouard Lucas back in 1889. 4. Frogs and toads. On 2n + 1 cells in a straight line $расположены^{n}$ frogs $и^{n}$ toads, between which there is one empty cell (Fig.3). Frogs on the left, toads on the right.

⟦figure⟧

Fig. 3

Frogs can only move to the right: either to an adjacent cell if it is empty, or to jump over one toad or one frog to an empty cell. Same for toads, but they only move to the left. The goal of the game is to swap frogs and toads. The moves do not have to alternate between frogs and toads. Problem 1. Prove that this puzzle game always has a solution. Find the number of moves. A generalization of this game suggests itself. What if we have m toads $и^{n}$ frogs? Problem 2. Prove that the generalized puzzle also has a solution and find the number of moves. How many solutions does this puzzle have? Let's denote a move with the letter Ш if it is a move to an adjacent cell, and with the letter P if it is a jump. Let's write down the sequence of moves leading to a win. For example, in the case of two toads and two frogs:

SHPSHPSHPSH

Note that the resulting string of moves is a palindrome [3]. Problem 3. Prove that this is true for an arbitrary number of toads and frogs. Problem 4. Is it true that the winning sequence of moves will also be a palindrome for $случая^{m} z^{n}$? Another generalization of this puzzle is the two-dimensional field (Fig.4). Now frogs can only move to the right or down, toads can only move to the left and up.

⟦column⟧

⟦figure⟧

Fig. 4

An amphibian can jump over its neighbor, provided that the square it lands on is empty. The goal of the puzzle is again to get the frogs and toads to switch places. Problem 5. Prove that a two-dimensional puzzle has a solution. There is another version of the game "Toads and Frogs", proposed by mathematician Richard Guy. In this game, the toads and frogs are again located in a straight line, but there can be many free cells, the allowed moves are the same, only this game must be won. The loser is the one who cannot make another move. Positions in such a game can be assigned values. Sometimes they are numbers familiar to us, and sometimes they are other, more complex entities. An attempt at a detailed analysis of such games unexpectedly leads to an interesting and complex theory. A detailed discussion can be found in the book [4] and collection [5].

Literature

1. Lasker checkers. – «Kvant», 1970, No. 4, p. 59. 2. Yoga game. – «Kvant», 1978, No. 9, p. 64. 3. https: www.cut-the-knot.org SimpleGames FrogsAndToads.shtml 4. E. R. Berlekamp, ​​J. H. Conway, R. K. Guy. Winning ways for your mathematical plays. Vol.1. – A K Peters/CRC Press, 2001. 5. J. Conway et al. The Man Who Played Maths. – M.: MTsNMO, 2023.

Material prepared by N. Panyunin

⟦folio 34⟧

---
running_head:
folio:
---

3 (5). If Vasya divides a pie or a piece of pie into two parts, he always makes them equal in mass. And if he divides parts into large numbers, he can make them whatever he wants, but they must all have different masses. After several such divisions, Vasya cut the pie into $N$ pieces. For each $N \geq 10$ could all parts be equal in mass? (You cannot combine parts.)
B.Frenkin

4 (5). Is it true that the sum of the internal dihedral angles at the base of a triangular pyramid is always the sum of the external ones?

A. Zaslavsky

5 (6). There are 45 schoolchildren in the math circle, non-technical friends. No matter how you divide them into threes, in some three everyone will be friends with each other. Prove that all schoolchildren can be divided into triplets so that in each triplet there are at least two others with each other.

M. Prasolov

Complex option
8-9 grades

1 (4). 12 children came to physical education class, all of different strengths. Fizuk divided them into two teams of 6 people 10 times, each time in a new way, and carried out the task of re-jigging the rope. Could it turn out that all 10 times the condition ended externally (i.e. the sums of the strengths of the children in the teams were equal)?

M. Evdokimov

2 (5). See problem M2790 “Problem book «Kvant»”.
3 (7). There is a pile of 100 stones. Two people play. The first one takes 1 stone, then the second one takes 1 or 2 stones, then the first one takes 1, 2 or 3 stones, then the second one takes 1, 2, 3 or 4 stones and so on. The one who takes the last stone wins. Who can ensure victory, no matter how his opponent plays?

L. Smirnova

4 (7). Petya wished for a positive irreducible fraction $x = \frac{m}{n}$. You can name a positive fraction $y$, less than 1, and Petya will name the numerator of an irreducible fraction equal to the sum $x + y$. How can you be sure to find out $x$ in two such actions?

M. Didin

5 (9). See problem M2792 “Problem book «Kvant»”.
6 (10). On the circumscribed circle of the triangle $ABC$ we marked the points $M$ and $N$ – the midpoints of each other $BAC$ and $CBA$, respectively, as well as the points $P$ and $Q$ – the midpoints of each other $BC$ and $AC$, respectively. Circle $\omega_1$ touches side $BC$ at point $A_1$ and extended sides $AC$ and $AB$. Circle $\omega_2$ touches side $AC$ at point $B_1$ and extended sides $BA$ and $BC$. It turned out that $A_1$ lies on the segment $NP$. Prove that $B_1$ lies on the segment $MQ$.

A. Doledenok

7 (12). Each of the 99 cards has a real number written on it. All 99 numbers are different, and their total sum is irrational. A stack of 99 cards is called *neydainoi* if for each $k$ from 1 to 99 the sum of the numbers on the $k$ top cards is irrational. Pet calculated how many ways the original cards could be put into an unsuccessful pile. What is the smallest value he could get?

A.Kushinr

10-11 grades

1 (4). Find all pairs of natural numbers $m$ and $n$ for which $m!! = n!$. (Double factorial $m!!$ is the product of all natural numbers not exceeding $m$ and having the same parity as $m$. For example, $5!! = 15$, $6!! = 48$.)
B.Frenkin

2 (6). A finite set of circles of radius 1 are placed in space. The circles can intersect each other, but do not pass through each other's centers. In the center of each circle there was a spotlight shining in all directions. Could it happen that any ray of light coming out from the center of any circle ends up in some other circle?

M. Alekseev

3 (7). See problem M2791 “Problem book «Kvant»”.
4 (8). Given two equal circles $\omega_1$ and $\omega_2$ with centers $O_1$ and $O_2$ (Fig. 3). On the segment $O_1O_2$ points $X$ and $Y$ are taken so that $O_1X = O_2Y$. Points

⟦folio 35⟧

---
running_head:
folio:
---

Fig. 3
A and B lie on $\omega_1$, and the line $AB$ passes through $X$. The points $C$ and $D$ lie on $\omega_2$, and the line $CD$ passes through $Y$. Prove that there is a circle tangent to the lines $AO_1$, $BO_1$, $CO_2$ and $DO_2$.

I. Kukhartsuk, A. Sokolov

5 (10). Given a polynomial of degree $n > 0$ with nonzero integer coefficients, each of which is its root. Prove that this polynomial cannot have any coefficients other than 1, -1 and -2.

L. Shamunov

6 (12). Koshey came up with a test for Ivan the Fool. He gave Ivan a magic pipe on which you can play only two notes - C and B. To pass the test, Ivan needs to play a 300-note melody of his choice. But before he begins to play, Koshey selects and declares forbidden one melody from a spot of notes, one from six notes, ..., one from 30 notes. If at any moment the last notes played form one of the forbidden melodies, the darling stops sounding. Will Ivan be able to pass the test, no matter what melodies the Koshas declare forbidden?

V. Klentsyn

7 (12). See problem M2796 “Problem «Kvant»”.

Oral round for 11th grade

1. Given a natural number $n$. Is it possible to represent the polynomial $x(x-1)...(x-n)$ as the sum of two cubes of polynomials with real coefficients?

B. Butyrin

2. See problem M2794 “Problem «Kvant»”.

3. Each cell of the table $N \times N$ contains a number. We will mark a cell as good if the sum of the numbers in the row containing this cell is no less than the sum of the numbers in the column containing this cell. Find the smallest possible number of good cells.

A. Glebov

4. See problem M2795 “Problem book «Kvant»”.

5. The inscribed sphere of a triangular paramid $SABC$ touches the base $ABC$ at the point $P$ and the lateral faces at the points $K$, $M$ and $N$. Straight lines $PK$, $PM$, $PN$ intersect the plane passing through the midpoints of the lateral edges of the paramid at points $K'$, $M'$, $N'$. Prove that line $SP$ passes through the circumcenter of triangle $K'M'N'$.

F. Ivlev

6. Vanya has two types of checkered paper: white and black. He expresses a piece from any paper and sticks it on a gray checkered board $45 \times 45$, doing this many times. What is the minimum number of pieces needed to be glued to “color” the squares of the board in a checkerboard pattern? (Each piece is a set of cells in which you can go from any cell to any other by moving from the cell to the adjacent one through their common side. You can stick pieces one on top of the other. All cells have size $1 \times 1$.)

T. Kazitsyana

The material was prepared by M. Alekseev, E. Bakaev, B. Butyrin, E. Veretennikov, A. Glebov, A. Gribalko, M. Didin, A. Doledenok, S. Doritsenko, A. Zaslavsky, F. Ivlev, T. Kazitsyana, V. Klentsyn, P. Kozhevnikov, I. Kukhartsuk, A. Kushir, M. Malkin, L. Mednikov, I. Mikhailov, M. Prasolov, A. Semenov, L. Smirnova, A. Sokolov, A. Tolpyu, B. Frenkin, A. Shapovalov, L. Shamunov, A. Yuran
