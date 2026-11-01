---
id: 1981-10-pereyaslavskiy-igra-opredelitel-8939c3ab
issue: kvant_1981_10
year: 1981
number: "10"
title: Game "Identifier"
authors:
  - Переяславский В. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 32
page_labels: 27-30
tag: HPFR
lang: en
source: kvant_digital
extraction: vision
content_sha256: b48fffdae5a90dcb631c8f1026c9172a9d9fd8235450629a59c6d43a82037aa7
prompt_sha256: draft-1
translated_from: content/ru/1981/10/articles/09_pereyaslavskiy-igra-opredelitel-8939c3ab.md
source_content_sha256: 2c53143abeefcfed535da769abfb31fe56f26fc4025815f5a05969ee00ffd533
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 27⟧

V. Pereyaslavsky

Game
"Definition"

Two versions of one game
In 1978, «Kvant», talking about the IX Festival of Young Mathematicians in Batumi (see No. 10), invited his readers to come up with a winning strategy for the following game:

Play by two. They take turns putting numbers from 1 to 9 into a 3x3 table (each number must be used). Once the table is filled, two sums are calculated: the sum of $S_1$ products by columns and the sum of $S_2$ products by rows. If $S_1 > S_2$, the beginning cerra is pulled out; if $S_1 < S_2$, the second cerrok is pulled out.

In 1971, this game in a slightly different form was popular among students of the Faculty of Mechanics and Mathematics of Moscow State University (and they learned about it from students of the University of Perm). This game was called “Definition” and looked like this:

Two iterate. They take turns putting numbers from 1 to 9 into a 3x3 table (each number must be used). Once the table is filled, two sums are calculated: the sum of $S_1$ products by columns and the sum of $S_2$ products by rows. If $S_1 > S_2$, the beginning cerra is pulled out; if $S_1 < S_2$, the second cerrok is pulled out.

Here, of course, we must oblige you that the determinant of the table $T$ (Fig. 1) is the number
$$d = x_1 x_5 x_9 + x_2 x_6 x_7 + x_3 x_4 x_8 - x_3 x_5 x_7 - x_1 x_6 x_8 - x_2 x_4 x_9.$$
We invite you to see for yourself that these two games are essentially the same. Next we will consider the option proposed in «Kvant».

Useful message
All games can be divided into simple and complex. Simple games are those that have

$$T = \begin{bmatrix}
x_1 & x_2 & x_3 \\
x_4 & x_5 & x_6 \\
x_7 & x_8 & x_9
\end{bmatrix}$$

Fig. 1.

⟦folio 28⟧

simple winning strategies, complex ones - all the rest. Apparently, the game "Identifier" is difficult. Complexity is an indispensable condition for the popularity of the game. For example, everyone plays chess and tic-tac-toe on a sheet of checkered paper with enthusiasm, but only younger schoolchildren play tic-tac-toe on a 3x3 board.

Let’s solve a problem that will help us play “Determinant”: we will find the smallest values ​​and apply to the topic its terms the inequality about the arithmetic mean and the geometric mean («Kvant», 1980, No. 3, p. 23):

$$\frac{x_1 x_2 x_3 + x_4 x_5 x_6 + x_7 x_8 x_9}{3} \geq \sqrt[3]{x_1 x_2 \cdot \dots \cdot x_9} = \sqrt[3]{9!} = \sqrt[3]{70 \cdot 72^2} > 71.$$

Hence $S > 213$ and, since $S$ is an integer, $S \geq 214$. But $2 \cdot 5 \cdot 7 + 1 \cdot 8 \cdot 9 + 3 \cdot 4 \cdot 6 = 70 + 72 + 72 = 214$; This means that the required smallest value is 214.

To find the smallest value of our sum, use the following lemma (proof!): if the numbers $a, b, c, d$ are positive, $ab = cd$ and $|a - b| > |c - d|$, then $a + b > c + d$.

Let's form a new sum $S'$ like this: leave the last term $x_7 x_8 x_9$ unchanged, make the first term $x'_1 x'_2 x'_3$ from the three smallest numbers of the set $\{x_1, x_2, \dots, x_6\}$, and the second term $x'_4 x'_5 x'_6$ from the remaining numbers of this set. Then by Lemma $S \leq S'$, and the equal sign will only be in the case when each of the numbers $x_1, x_2, x_3$ is greater (or less) than each of the numbers $x_4, x_5, x_6$. From this we obtain that the value of the sum $S$ will be the smallest if all the components of the first term are less than all the components of the second term, and those in turn are less than all the components of the third term. Thus, the required smallest is $1 \cdot 2 \cdot 3 + 4 \cdot 5 \cdot 6 + 7 \cdot 8 \cdot 9 = 6 + 120 + 504 = 630$.

To summarize: the sum $S$ takes on the smallest value when its terms are as close as possible (and therefore equal to approximately 71), and the largest value is when they are as different as possible. Hence the practical advice to the player: strive to ensure that the opponent’s terms are approximately the same (and equal to 71), and your own terms are as different as possible!

**Strategy “71” for the first player**

Let's say that after your first move, your opponent wrote his number in the same column or line with your number. Then we offer you the following strategy “71”:

For each filled row and each filled column of the table, we determine the number

$$m = \begin{cases} \frac{\Pi}{71}, \text{ если } \Pi \geq 72, \\ 71/\Pi, \text{ если } \Pi \leq 71, \end{cases}$$

where $\Pi$ is the product of the numbers written in a given row or given column.

With the next move, the beginning player must complete a row or column according to the following rule: if he completes a row, then with a number giving the minimum value $m$ for this row (that the product was as large as possible to 71), and if - a column, then with a number giving the maximum value $m$ for this column (that the product was as different as possible from 71).

Let us explain this with an example. For convenience of presentation, we number the cells of our table (Fig. 2) and write the game as a line of nine numbers with indices, where the index denotes the number of the cell,

**Fig. 2.**

⟦folio 29⟧

in which the given number is written on the corresponding move. Let’s make sure that in the game $3_55_81_24_66_47_72_98_19_3$ the player starting the game used the strategy “71” (the strategy does not impose a limited strategy on the first move).

After the first two moves (Fig. 3, a), the first player according to strategy must put in cell No. 2 a number that gives the maximum possible m. In this case, the maximum m can be either the move 1$_2$, in which the product of the numbers in the second column is 15, or the move 9$_2$, giving the product 135. Since 71/15 > 135/71, you need to put 1 in cell No. 2, which was done.

After the move 4$_6$ (Fig. 3,6) in cell No. 4 you need to put a number that gives a minimum of m, namely 6$_4$, etc.

Two special cases

1. If a tserajutsezo has the product $1 \times 2 \times 3$, or $1 \times 2 \times 4$, or $6 \times 8 \times 9$, or $7 \times 8 \times 9$, then it picks out regardless of how the rest of the numbers are located in the table.

Let us prove, for example, that when the table contains a column of numbers 1, 2, 4, the beginner wins. If, say, the table looks like figure 4, then

$$\frac{x_2x_5x_8+x_3x_6x_9}{2} \geq \sqrt{x_2x_5x_8x_3x_6x_9} = \sqrt{3 \cdot 5 \cdot 6 \cdot 7 \cdot 8 \cdot 9} > 212.$$

So, $S_1 \geq 1 \cdot 2 \cdot 4 + 425 = 433$.

On the other hand, the value of the sum $S_2$ is maximum when the numbers $x_2$ and $x_3$ are less than $x_5$ and $x_6$, and $x_5$ and $x_6$ are less than $x_8$ and $x_9$. Thus, $S_2 \leq 1 \cdot 3 \cdot 5 + 2 \cdot 6 \cdot 7 + 4 \cdot 8 \cdot 9 = 387$, that is, $S_1 > S_2$, as stated.

2. Otherwise, when playing, it is possible to use the idea of ​​​​"zugschang" - the absence of reasonable moves by the enemy. For example, in the situation depicted at figure 5, the beginner, at any move of the second player, can (and must) put the numbers 1, 2 in one column, and 8, 9 in the other. After calculating the different options, it is easy to check that this will ensure the winnings that he started.

Trying to bust

At first glance, “Determinant” does not seem very difficult: the opponents make only nine moves and for each move there are no more than nine options - let’s calculate all the options and choose the right one. The trouble is that there are too many different parties.

In fact, for the first move there are 81 options (one of nine numbers in one of nine cells); for the second move - 64 options, etc. (Fig. 6) - in total $9^2 \cdot 8^2 \cdot 7^2 \cdot \ldots 2^2 \cdot 1^2 = (9!)^2 \approx 1,3 \cdot 10^{11}$ different games. Of course, it is impossible to determine the result of the game using such a search, even with the help of a computer.

True, this search is too rough, and the estimate is too high: after all, our game has symmetry. For example, all first moves in different cells with the same number are equal; therefore, it is necessary to consider not 81, but only 9 options for the first move. Eight cells left for the second move can be divided into three classes so that moves of the same number into cells of the same class will be equal (at figure 7 cells of different classes are painted in different colors); therefore, it is necessary to consider not 64, but 8 \cdot 3 = 24 options for the second move. So we managed to reduce the upper estimate of the number of games to the number $9 \cdot 24 \cdot 7^2 \cdot 6^2 \cdot \ldots \cdot 2^2 \cdot 1^2 \approx$

⟦folio 30⟧

≈ 5 · 10^9, which, however, is still very large. We need a new idea that reduces the selection of options. I found such an idea.

How can a sage help?

Suppose that a sage appears who claims that by starting the game he will gain victory, and let this sage be so kind that he makes the same moves in the same positions. How many games do you need to play with the sage to check that he actually has the winnings?

The sage starts all games the same way; we must try playing with him all 24 options for the second move. At each position of the second move, the sage unambiguously makes a third move; we go through all 36 options for the fourth move, etc. (Fig. 8). In total, you need to play 24 · 6^2 · 4^2 · 2^2 = 55296 games testing the sage.

Having interacted with a sage for a month, you can be convinced of his win-win nature or prove the opposite. You can create and debug a computer program that tests the sage, which, however, will take the same month, but with the same program you can now test any strategy for “winningness.”

So, there is a checking program, but where is the sage? The author had to learn to play and, using the messages and strategies already expressed, gradually correcting the moves that did not provide a win for the beginner (they were detected using a checking program), “turn” into such a game.
