---
id: 1977-12-schepochkina-dvazhdyi-ob-odnom-db170317
issue: kvant_1977_12
year: 1977
number: "12"
title: Twice about the same thing
authors:
  - Щепочкина И.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 47
page_last: 49
page_labels: 45-47
tag: XCJH
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2eb6ca75267b46ccbf29459f72331fdcb228d815ae31db9aa93d2c49d260c42b
prompt_sha256: draft-1
translated_from: content/ru/1977/12/articles/14_schepochkina-dvazhdyi-ob-odnom-db170317.md
source_content_sha256: a17d3d1551818724bf13c1c9836571f0c77253970031cd1f7dafaa30db6572f2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

Probably many of you have played lotto or at least heard about this game. We offer you some insight into it. As in the usual version, our main item is a bag with “barrels” on which numbers from 0 to 99 are written. The rules of the game are as follows. You are allowed to write any number of numbers from 0 to 99, each number no more than once. After this, one “barrel” is removed from the bag. If any of the numbers written to you has a first (or second) digit that matches the first (corresponding second) digit of the number drawn, then your number gets 250 points. The number that matches the one drawn gets 500 points. For example, if the number 95 is drawn, then it itself receives 500 points, numbers 45 and 91 receive 250 points each, and numbers 59 and 04 receive nothing (single-digit numbers - 0, 1, 2, ... - are written as two-digit numbers - 00, 01, 02, ...).

To better understand the rules, let's play. You have a piece of paper and a pen, I have a bag with “barrels”. For example, a couple of numbers on food. I take out 66. How many points did you score? How many models to recruit? Apparently, no more than 750. And what is the maximum number of numbers you need to write in order to be sure to type the number in writing?

Take your time, think. How much did you get? 10? Right. For example, you can write the numbers 00, 01, 02, 03, ..., 09, and then, no matter what number is taken out of the bag, its second digit coincides with the second digit of one of your numbers, which means you will get at least 250 points. And fewer numbers are not enough. After all, if you write less than ten numbers, you will find a number a that will not be the average of the digits of your numbers, and a number b that will not be the average of the digits of your numbers. And then if a “barrel” with the number ab is taken out of the bag, you won’t win anything.

Problem 1. What number was drawn from the bag if the set 07, 29, 45, 68, 84, 71, 32, 16, 53 received nothing?

Now the question is more difficult.

What is the maximum number of numbers that need to be written in order to be sure to type the number in writing?

Let's take a break from lotto for a minute and remember about the chessboard and the rook, which will be all squares located on the same horizontal or vertical with the field on which it stands. Tell me, what is the maximum number of rooks that can be considered on a chessboard without them being different?

⟦folio 46⟧

Anyone who is at least a little familiar with chess will immediately answer: of course, eight, for example, as on figure 1.

Then one more question: let there be 8 rooks placed on the board that are not mutually exclusive. How many times is which square of the board struck?

If the rooks are not apart from each other, then they are on different verticals and different horizontals, and then on each vertical and each horizontal there is one rook. Any square not occupied by rooks is therefore fought with two rooks (one vertically, the other horizontally).

What do lotto and chess have in common? But look. Let's write out all the numbers from 00 to 99 in a 10x10 square table:

| 00 | 01 | 02 | 09 |
| :--- | :--- | :--- | :--- |
| 10 | 11 | 12 | 19 |
| :--- | :--- | :--- | :--- |
| 90 | 91 | 92 | 99 |

We will say that the number $ab$ will be the number $cd$ if $ab$ gets points when $cd$ is taken out of the bag, that is, if $a=c$ or $b=d$. Let's look at our table. Each one has numbers that stand with it on the same horizontal or vertical line. We already know that if 10 numbers are different from each other (for example, 00, 11, 22, ..., 99), then any number from 0 to 99 will either match one of those 10 numbers or be the two chosen. In obonkh

Fig. 1.

cases our set receives 500 points. And you can’t score less than ten numbers and 250 points. So we answered the question about lotto. There is only one ambiguity left.

Problem 2. Is it necessary for 10 numbers to be different from each other in order for such a set to always result in 500 points?

This question is very important. So before reading further, check your answer on p. 60.

And now we can solve a more difficult problem - find how many total there are in a set of 10 numbers that probably get 500 points.

We already know that a set of 10 numbers has a certain number of squares, and each square has a certain number of points. We can use a simple algorithm to find the number of squares in the given table.

We already know that a set of 10 numbers has a certain number of squares, and each square has a certain number of points. We can use a simple algorithm to find the number of squares in the given table.

This problem is well known to mathematicians and even has its own name: it is called the permutation problem. To solve it, note that any of 10 different digits can be assigned to the number 0. You can assign numbers to the pair 0 and 1 like this: first we assign any of the 10 digits to the pair 0 and 1. Thus, we get 10 9 = 90 pairs of numbers, starting with 0 and 1, and so on. The answer to the problem question is 10! (read “10 factorials”).

Task 3 (control). How many ways can 8 identical rooks be placed on a chessboard so that they are not next to each other?

Let us now assume that we want to place rooks that do not belong to each other on a rotating chessboard. How many reviews will we see in this case?

⟦folio 47⟧

Fig. 2.

The tricky part of this problem is that when the dock rotates, we cannot distinguish this arrangement from a centrally symmetrical arrangement.

Task 4 (controllable and with a twist). Can we distinguish on a rotating chess dock those arrangements that on a stationary dock are obtained from each other by rotating 90° relative to the center of the dock?

Let us denote the number of centrally symmetric arrangements by $S$. Then the total number of rook placements on the turning dock can be expressed by the formula $S + \frac{8! - S}{2} = \frac{S + 8!}{2}$, and all we have to do is find $S$.

As usual, we have 8 ways to place a rook in the top rank. But if we placed a rook in the upper rank, then we will have to place a rook symmetrically to it in the lower rank. Then for the rook in the second rank from the top there are only 6 possibilities, in the third - 4, in the fourth - 2, after which the arrangement is determined. Thus, there are $8 \cdot 6 \cdot 4 \cdot 2 = 2^4 \cdot 4!$ symmetrical arrangements, and the total number of arrangements is $\frac{8! + 2^4 \cdot 4!}{2}$.

Task 5 (control). How many arrangements of rooks remembering each other's past can be seen on an unpainted turning dock?

Let us now have all the numbers from 1 to 64 written out in a row on our chess dock (in the top horizontal row, from left to right, numbers from 1 to 8, in the next row, from 9 to 16, and so on). What values ​​can the sum of the numbers written on the squares where the rooks stand (“rook sum”) take?

At the beginning of this article, the chess dock helped us solve the lado problem. Now it’s the other way around: Lodo will help you solve a difficult problem on the dock. Let each player receive a certain number of points before starting a lotto game, and for the opportunity to write a certain number, they must give as many points as this number is.

Task 6 (control). Which of the 10! There are no sets of numbers that are more profitable than each other and what is the required number of points?

Having solved this problem, you will actually calculate the “rook sum” on the dock $10 \times 10$, decimal notation of numbers will be convenient here.

On the dock $8 \times 8$ the entry associated with the number 8 will be more profitable. Namely, the dock with numbers can be represented as a “sum” of two boards (Fig. 2), and on each “summand” the rook sum does not depend on the arrangement of the rooks and is equal to

$$0 + 8 + 16 + \dots + 56 = 224$$

on the first term and

$$1 + 2 + 3 + \dots + 8 = 36$$

on the second term. This means that for any arrangement, remember each other’s rooks, the rook sum is 260.

Let's return to lotto.

Problem 7. You have enough points to write all the numbers from 00 to 99. One barrel was taken out of the bag. Will the number of points increase (compared to the original) or decrease?

Problem 8. Given a set of 10 numbers that are different from each other. Is it always possible to split the remaining 90 numbers into 9 sets of 10 different numbers?

And finally, two tasks on the dock. We will say that the numbers from 1 to 64 are written out on the chess dock in the “correct way” if for all rook formations the “rook sum” is the same.

Problem 9. Prove that there is at least $2 \cdot (8!)^2$ ways to write the numbers from 1 to 64 on the dock in the “correct way”.

Problem 10. What values ​​can the “rook sum” take if the numbers from 1 to 64 are written “in the correct way”?
