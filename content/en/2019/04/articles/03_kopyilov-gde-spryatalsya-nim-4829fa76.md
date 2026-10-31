---
id: 2019-4-kopyilov-gde-spryatalsya-nim-4829fa76
issue: kvant_2019_4
year: 2019
number: "4"
title: Where did Nim hide?
authors:
  - Копылов И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 33
page_last: 40
page_labels: 34, 35, 36, 38
tag: DEB3
lang: en
source: kvant_digital
extraction: native
content_sha256: cdac046c35d9aa092d314d497241831acf8522e3e49ca69f269b09a138be40c1
prompt_sha256: draft-1
translated_from: content/ru/2019/04/articles/03_kopyilov-gde-spryatalsya-nim-4829fa76.md
source_content_sha256: 2f372bdb6788e254d9b7715d7c6e611d4bba5af76c2ae0ac2b30961d7636e3b0
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

MATHEMATICAL CIRCUIT OK

Where did Nim hide?

I.KOPYLOV

ARTICLE “PLUSES AND CONS AND GAME WITH NIM”

(see «Kvant» No. 7, 8 for 2018) the strategy of the game Nim was described, which plays a special role in game theory. The game of Nim is as follows. There are m piles, the number of stones in which is equal to $a_{1}, a_{2}$, … $, a_{m}$. Two people take turns walking; Each player, during his turn, chooses one of the piles and takes any non-zero number of stones from it. The one who takes the last stone wins. Many games come down to Nim. If the game manages to recognize Nim, then a strategy borrowed from Nim immediately appears for it. In this article we will reduce several different games to Nim. Game 1. Five chips are on the cells of a horizontal strip of 25 cells. For each move, you must move one of the chips to the left to any cell; jumping over other chips is allowed; several chips can be on one cell. The player wins, after whose move all 5 chips will be on the leftmost cell of the strip. The game obviously comes down to Nim with 5 piles of stones. Let's number the cells of the strip, starting from 0, from left to right (Fig.1). Then a chip standing on cell number n can be moved in 1 move to any of the cells 0, 1, ..., n 1, regardless of the location of the remaining chips. Similarly, in the Nim game, the number of stones in one of the piles per turn decreases down to 0. Therefore, to reduce to Nim, the chip on cell n should be replaced with a pile with n stones. Then the chip is on the leftmost square

⟦column⟧

is equivalent to an empty heap. The game ends when all the piles are empty, i.e. all the chips are collected on the cell numbered 0. So, if 5 chips are located on the cells numbered a, b, c, d and e, then the Nim-sum is compiled for the numbers a, b, c, d and e. Let us recall that the Nim-sum is calculated bit by bit as follows: The Nim-summed numbers are written in the binary system, and if there is an odd number of units in a given digit, then in the resulting sum in the corresponding digit we put 1, if it is even - 0. The Nim-sum of the numbers a, b, c, d, e is denoted a b c d e. With his turn, the player must reset the Nimsumma. Let's look at an example. Let the chips stand on squares 5, 10, 14, 16 and 22 stripes (see Fig.1). The calculation of the corresponding Nimsumma is given in figure 2.

⟦figure⟧

Fig. 2. Calculation of the Nim-sum to determine the move in game 1

So,

5  10  14  16  22

$= 101_{2}$  $1010_{2}$  $1110_{2}$  $10000_{2}$  $10110_{2} 111_{2} 7$.

The nim amount is different from 0. The player making the move must reset it to zero. The highest unit in the Nim sum is in the 2nd binary digit, if you count the digits from right to left, starting from zero. Units in the second digit are present in the recording of the quantities of stones in piles 1, 3 and 5. Therefore, in the example under consideration, the player has 3 options for a move: either leave $10_{2} 2$ stone in the first pile, i.e. move the piece with

⟦figure⟧

Fig. 1. Numbering of strip cells and arrangement of chips in the example

DOI: https://doi.org/10.4213/kvant20190405

(Continued on page 34)

⟦folio 34⟧

KVANT 2019/№4

cells 5 to cell 2, or leave $1001_{2} 9$ stones in the third pile, i.e. move the chip from cell 14 to cell 9, or leave $10001_{2} 17$ stones in the fifth pile, which means moving the chip from cell 22 to cell $17. Игра^{2.}$ The caterpillar consists of 20 links. Some caterpillar links are painted green, the rest are white. Two players take turns repainting the links: the green link is made white, and the white link is made green. During his turn, the player must repaint one of the green links white and can repaint another link located closer to the tail of the repainted one. The player wins, after whose move all the caterpillar links turn white. This game is a hidden Nim. Let's number the caterpillar links, starting with the tail. The tail link will receive the number 1, the head link – 20 (Fig.3). Green link

⟦column⟧

⟦figure⟧

Fig. 4. Calculation of the Nim-sum to determine the move in game 2

with 7 piles with 2, 5, 6, 9, 14, 16 and 19 stones. Since the corresponding Nim-sum is (Fig.4)

2  5  6  9  14  16  19

$= 10_{2}$  $101_{2}$  $110_{2}$  $1001_{2}$  $1110_{2}$ 

$10000_{2}$  $10011_{2}$ 

101 2

5 and there is a pile with 5 stones, then the player does -

⟦figure⟧

Fig. 3. Numbering of caterpillar links

we replace caterpillars with number k with a pile of k stones. During his move, the player recolors a green link with some number k and can recolor another link with a number less than k. If a player recolors only one link, then we consider that he has emptied a pile with k stones. If the second recolored link has number m (m < k) and was white before the player’s move, then we assume that the player took k – m stones from the pile with k stones and left m stones in it. And in the case when the second recolored link with number m was green and became white, then we will assume that the player left m stones in the pile with k stones. Since before there was already a pile with m stones, there are now two of them. And two identical piles contribute zero to the Nim sum. Therefore, further in the game, Nim can not consider them and exclude them from the game. Thus, this game comes down to Nim with the number of piles equal to the number of green caterpillar links. The number of stones in the pile coincides with the number of the corresponding green link. For example, at figure 3 the game with repainting the caterpillar links is equivalent to the Nim move; it is enough to reset a pile of 5 stones, and the Nim-sum of the remaining piles will become equal to 0. Therefore, the winning move from the state at figure 3 is to repaint the green link 5 white. $Игра^{3.}$ Two players take turns breaking a chocolate bar divided by grooves into 8 and 12 pieces. One of the tile particles is marked with a cross. With each of his moves, the player breaks a tile along one of the grooves and eats that part of the tile that does not contain a piece with a cross. The winner is the player whose move leaves only one piece of the chocolate bar with a cross. This game is also a veiled Him. The player has 4 options for a move: break the tile along the groove above the piece with a cross, to the right of the piece with a cross, below it, or to the left of it. If at the beginning of the game a piece with a cross is located, for example, as shown in figure 5, then there are 4 rows above the piece with a cross, 5 rows to the right of it, 3 rows below it, 6 rows to the left. A move in each of the four options reduces the number of rows in the corresponding direction.

⟦folio 35⟧

MATEM ATI CHES KY

⟦figure⟧

Fig. 5. View of a chocolate bar with a piece highlighted with a cross

Therefore the game is equivalent to Nim with 4 piles of stones. In the first pile the number of stones coincides, for example, with the number of rows above the piece with a cross, in the second - with the number of rows to the right of the piece with a cross, in the third - below and in the fourth - to the left of it. In the example at figure 5, at the beginning of the game there are 4, 5, 3 and 6 stones in piles. During his turn, the player selects a pile and reduces the number of stones in it. To determine the move, we compile a Nimsumma. In the example under consideration, the calculation of the Nim-sum is carried out on figure 6. We obtain 4 5 3 $6 100_{2}$ $101_{2}$ $11_{2}$ $110_{2}$

$100_{2} 4$. As can be seen from figure 6, the Nim sum is different from 0. To reset it, it is necessary to remove

⟦figure⟧

Fig. 6. Compiling the Nim-sum to determine the move in game 3

one unit in the most significant binary digit, i.e. remove 4 stones from one of piles 1, 2 or 4. In the game in question, the player must remove 4 rows either above, to the right or left of the square with a cross. Game 4. There is a chip on five cells of a horizontal strip of 25 cells. For each move, you are allowed to move any chip to the left to a free cell without jumping over other chips. The player who cannot make a move loses. Let's number the cells of the strip from left to right with numbers from 1 to 25. The chips on the strip will also be numbered from left to right. The player is not

KR UZH OK

⟦column⟧

can make a move when five chips occupy cells numbered 1 to 5. To find a strategy, let's first simplify the game. Let there be only one chip on the strip. Then the beginner wins by placing a chip on cell 1. If there are two chips on a strip, then the strategy is determined without much effort. The player should place chips on adjacent cells. The opponent will only be able to make a move with chip 1. The player, with his next move, moves chip 2 to the left so that the chips are again on adjacent cells. As a result, after several moves, the chips will end up on squares 1 and 2, and the opponent will not be able to make a move. Next, consider the case of a game with three chips on a strip. To build a strategy, we will use the rules for placing the “+” and “–” signs given in the article “Pros and cons and the game of Nim.” The state of the game is determined by 3 numbers - the numbers of cells with chips. Therefore, it is necessary to place signs in the cells of a three-dimensional table. The coordinates of cells $a_{1}, a_{2}, a_{3}$ satisfy the relations

$0 a_{1} a_{2} a_{3}$,

(1) where $a_{1}$ is the number of the cell with a chip $1, a_{2}$ – with a chip $2, a_{3}$ – with chip 3. As a result of the move of one of the players, one of the three coordinates decreases, and relation (1) remains in force. We will fill the table with signs in layers. In the bottom layer, where $a_{1} 1$, piece 1 cannot move. And for two chips we have already established that in the minus state the chips are placed in adjacent cells of the strip. This means that $a_{2} 1 a_{3}$, and in all cells with coordinates $1, a_{2}, a_{2} 1, 1 a_{2}$, there is a “–” sign, and in all other cells of the first layer there is a “+” sign. In the cells of the second layer of the table, where $a_{1} 2$, the minuses are in the cells with coordinates 2,3,5, 2,4,6, 2,5,7, …, i.e. in cells of the type $2, a_{2}, a_{2} 2, 2 a_{2}$. Filling the cells of the third layer with “+” and “–” signs, we notice that the minuses appear in cells with coordinates of the form $3, a_{2}, a_{2} 3, 3 a_{2}$. Looking at the filling of the first three layers of the table with minuses, we can assume that the “–” signs are in cells with coordinate

⟦folio 36⟧

KVANT 2019/№4

natami $a_{1}, a_{2}, a_{2} a_{1}, 0 a_{1} a_{2}$. Or, in another form, the coordinates $a_{1}, a_{2}, a_{3}$ of minus cells are related by the relation a 1

$a_{3} a_{2}$.

(2)

This conjecture is proven by mathematical induction on $a_{1}$. Let us rewrite relation (2) in the form

$a_{1} 0$ a 3 a 2

(3) and suppose that another cell with number 0 has been added to the strip on the left, on which there is a zero fiat chip. Then the distance in cells between the first and zero chips coincides with the distance in cells between the third and second chips. If the arrangement of chips satisfies relation (3), then any move of the opponent

they agree with the ratio

⟦column⟧

a 2 a 1

$a_{4} a_{3}$.

And finally, for 5 chips on a strip, we will again introduce a conditional fixed zero chip, which we will place on a conditional zero cell attached to the strip on the left. The game comes down to Nim with 3 piles of stones. We assume that the number of stones in the first pile is equal to the number of free cells between chips 0 and 1. The size of the second pile is determined by the number of free cells on the strip between chips 2 and 3. There are exactly as many stones in the third pile as there are free cells on the strip between the 4th and 5th chips. figure 7 shows an example of determining the sizes of three piles in the equivalent Nimes.

⟦figure⟧

Fig. 7. An example of determining the number of stones in game 4

will lead to its violation, and the player must restore the fulfillment of relation (3) with his response move. There is a correspondence between Nim and two piles of stones. The number of stones in the first pile coincides with the number of free cells between the zero and first chips, and in the second pile - between the second and third chips. In Nimes with two piles, the player must equalize the number of stones in the piles with each move. Unlike Nim, in this game the opponent can, by moving chip 2, increase the number of free cells between chips 2 and 3, which in the Nim game corresponds to increasing the number of stones in the second pile. In this case, the player must respond by moving chip 3 to the left, returning the previous number of free cells between the second and third chips. The case with 3 chips on a strip has been dealt with. Let the game now be played with 4 chips on a strip. Then the conditional chip introduced when considering the previous case receives embodiment. Let us denote by $a_{i}$ the number of the cell on which the i-th chip stands (i = 1, 2, 3, 4). By analogy with the previous case, the numbers of cells with chips for the minus state are satisfied

In the example, the numbers of stones in the piles are 4, 1 and 5. To win, the player must reset the corresponding Nim-sum for three piles with each of his moves. Moving odd-numbered chips reduces the number of stones in one of the piles. If the opponent moves a piece 2 or 4, say, k cells to the left, then in a pile of 2 or 3, respectively, the number of stones increases. In this case, the player must use his own move to restore the number of stones in the pile by moving the corresponding odd-numbered chip k cells to the left. In the example under consideration, the Nim-sum is 0 (Fig.8). Therefore, the player whose turn it is to move loses.

⟦figure⟧

Fig. 8. Calculation of the Nim-sum for 3 piles in game 4

Game 5. The cells of the strip of 10 cells are numbered from 1 to 10. On each

⟦folio 38⟧

KVANT 2019/№4

⟦figure⟧

Fig. 10. Compiling Nim sums for numbers in game 5

You should move one chip from cell 9, leaving three chips on it. The nim amount after such a move will become zero. Game 6. The game takes place with 4 broken lines. The number of links in a broken line does not exceed 20. Three broken lines are attached to a fixed base at one end, and the fourth - at both ends (Fig. 11). For

⟦figure⟧

Fig. 11. Example of the initial state of the game

Each move you are allowed to remove one link from any broken line. If after the move there are links torn from the base, then all of them are also removed. The player wins, after whose move the links of all broken lines will be removed. Let's reduce the game to Nim with 4 piles of stones. Let broken lines A, B and C be attached to the base with one end, and broken line D with two. Let us number the links of each broken line sequentially. For broken lines A, B and C, number 1 will receive a link attached to the base (Fig.11). Let us show that each of the broken lines A, B and C can be replaced by a pile, the number of stones in which is equal to the number of links in the corresponding broken line. Let the broken line A, for example, contain k links. When the i-th link of broken line A, 1 d i d k is removed, it remains with i –1 link with numbers from 1 to i –1. Thus, removing the i-th link is equivalent to leaving i –1 stones in the pile. We also replace the broken line D with some generalized pile of stones. Let it be broken

⟦column⟧

D initially contains m links. After removing one of its links, say link i, 1 d i d m, the broken line splits into 2 broken lines with i – 1 and m – i links, each of which is attached to the base at one end. Let's show that 2 new broken lines in the game can be replaced with one pile of stones in Nîmes. If there is an even number of links in broken line D, then after removing one link, the resulting two broken lines will have an unequal number of links, and the opponent has the opportunity to use his own move to equalize the number of links in the new broken lines. Two identical piles have the same binary representation and contribute zero to the Nimsum. We find that the generalized heap with which we want to replace the broken line D also makes a zero contribution to the Nim-sum, i.e. is empty. The difference between a generalized pile of stones and a simple one when playing Nim is that even when the generalized pile is empty, it is possible for a player to make a move that transfers it to a non-empty pile. In this case, the opponent nullifies it on his own. And again the player must make a move, and the generalized pile is empty. We returned to the state that already existed. After each move, the total number of links in the broken lines decreases, so it is impossible to return to the same state of the generalized pile an infinite number of times. Let us now consider the case when the broken line D has an odd number of links. Then, by removing the middle link, the player can get two broken lines with the same number of links, which give zero contribution to the Nimsumma. Let us show that when removing any other link of broken line D, the opponent can, after his next move, leave two broken lines whose contribution to the Nim-sum is the same as that of a pile with one stone. A broken line D, after removing one link, cannot split into two broken lines, the number of links in which differs by exactly 1. But then the opponent, by reducing the number of links in a broken line with a large number of links, can obtain in new broken lines numbers of links that are two consecutive numbers, say 2n and 2n + 1, where the smallest number 2n is even. The contribution of two such numbers to
