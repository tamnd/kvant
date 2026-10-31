---
id: 2008-1-zadachi-16-20-bbc0fc7c
issue: kvant_2008_1
year: 2008
number: "1"
title: Problems 16-20
rubric: konkurs-imeni-a-p-savina
page_first: 28
page_last: 30
page_labels: 26-28
tag: CMCQ
lang: en
source: kvant_digital
extraction: native
content_sha256: 40f11b66ca4b0a6781e44de23d470aced17d7f2ef1dabda0ccbed6ea8d26fb72
prompt_sha256: draft-1
translated_from: content/ru/2008/01/articles/05_zadachi-16-20-bbc0fc7c.md
source_content_sha256: 58b492895fef3671e5f3d4178b14be3c93054122944130550a2055fed53b38f2
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

KVANT 2008/№1

Competition named after A.P. Savin

"Math 6–8"

We are completing another competition on solving mathematical problems for students in grades 6–8. Send solutions to problems within a month after receiving this issue of the journal to the address: 119296 Moscow, Leninsky Prospekt, 64-A, «Kvant» (marked “Competition “Mathematics 6–8”). Be sure to include your name, class, and home address. As before, we welcome participation in the competition not only by individual schoolchildren, but also by mathematical clubs. We ask circle leaders to provide an email address or contact phone number. According to tradition, the winning clubs of the correspondence competition are invited to the final in-person tournament.

16. For what natural numbers n > 2 can we write the numbers from 1 to n in one line so that among any three numbers written in a row, one of them is not less than the sum of the other two? I. Akulich

⟦column⟧

19. The numerical sequence $f_{0}, f_{1}, f_{2}$, … is constructed as follows:

17. Find all natural powers of prime numbers that can be represented as the sum of two cubes of natural numbers. V. Senderov

Prove that all numbers in this sequence are integers. V. Letsko

18. Point D, lying inside the acute triangle ABC, is reflected symmetrically relative to its three sides AB, BC, CA. It turned out that the corresponding three new points $C_{1}, A_{1}, B_{1}$ lie on a circle circumscribed around triangle ABC. Then the points $A_{1}, B_{1}, C_{1}$ were left on the drawing, and everything else was erased. Reconstruct triangle ABC using these three points. S.Dvoryaninov

$f 0 =^{0}, f_{n} +_{1} =$

$3 f_{n} + 5 f_{n}^{2} + 4$

2

, n = 0, 1, 2, …

20. The natural numbers x and y are such that xy + 1 is the square of the integer. Prove that there is a natural number z such that the numbers yz + 1, zx + 1, as well as the number xy + yz + zx + 1 are squares of integers. V.Proizvolov

Ghost of Leonardo

I. AKULICH

Let no one who is not a mathematician read me.

Leonardo da Vinci. Scientific prose

HALF A MILLENNIUM SEPARATES US FROM THE GREAT LEONARD da Vinci, but humanity to this day is tirelessly searching for an answer to the question: who was he? Artist? Inventor? Philosopher? A genius far ahead of his time, or even a messenger of an alien intelligence? Evidence of the enduring interest in this Renaissance titan is the much-acclaimed book (and then film) The Da Vinci Code, as well as the fascinating computer game $игра^{1}$. She's straight-

1 See, for example, www.1980-games.com/us/reflexion-games/reflexion-others/026.php or www.1980-games.com/us/reflexion-games/reflexion-others/debout.php is still full of tasks, puzzles and other difficulties, which makes it extremely difficult, but also very interesting. One of the tasks of this game was the starting point of the story that we will now present. So, given a checkered square of size 5 × 5 cells, each cell of which can be either white or black (initially all cells are white, although this is unimportant). You are allowed to select any cell and at the same time recolor it and all the cells that have a common side with it (we will call them neighbors) in the opposite color. It is required to repaint all the cells of the square in the opposite color in several such operations. It is difficult to say whether Leonardo da Vinci himself had a hand in this task, but it is quite possible that he did. In

⟦folio 27⟧

anyway, it looks like it. Very much... but more on that later. Of course, many users of the computer game solved the puzzle “at random”, clicking the mouse on various cells at the behest of the soul. But we will try to approach the matter scientifically. To begin with, let's call repainting a cell (and simultaneously all its side neighbors) a move to that cell. Let us make a certain number of moves into some cells and achieve our goal by repainting all the cells of the square in the opposite color. Let's consider any cell. With each move into it itself or into any cell adjacent to it, it changes color. Therefore, if in the end the cell received the opposite color, the total number of moves to this cell and all the cells adjacent to it must be odd. In this case, the order of moves obviously does not matter at all - the sum (and especially the parity) does not change from rearranging the terms. Upon reflection, we can draw another, no less important conclusion: if at least two moves were made to any cell, then by reducing the number of moves to this cell by 2, we will come to the same result. The law of parity comes into play here too. But if so, then by reducing the number of moves to each cell by 2 as long as possible, we will bring the number of moves to each cell to one or none at all. In other words, if it is possible to achieve the desired result using a certain set of moves to some cells, then the same can be achieved by making no more than one move to each cell. This conclusion allows us to divide the cells into two categories: into which a move was made (the only one!) and into which a move was not made. Therefore, let's mark the cells in which we need to make a move, and think about what conditions the resulting configuration must satisfy. Note that each marked cell must be adjacent to an even number of marked cells (i.e., either none, or two, or four), and each unmarked cell must be adjacent to an odd number of marked cells (i.e., either one or three). Undoubtedly, most readers will agree with this without hesitation, but for those who doubt, we will explain in more detail. Consider any unmarked cell A. It is adjacent to an odd number of marked cells. Since when moving to any such neighboring cell, cell A will change color, then after all moves it will change color

M

Sh

⟦column⟧

Illustration by V. Ivanyuk

TO

an odd number of times, and eventually its color will become the opposite of the original one. Now consider any marked cell B. It is adjacent to an even number of marked cells. Since when moving to any such neighboring cell, cell B will change color, then after all moves to the adjacent marked cells it will change color an even number of times. Plus, it will change color once when moving to cell B itself. Thus, in the end its color will become the opposite of the original one. Well, we managed to transform the “dynamic” problem (where the cells change color every now and then) into a “static” version, where you just need to mark some squares of the board in a certain way: so that each marked square is adjacent to an even number of marked squares, and every unmarked square is adjacent to an odd number of marked squares. Let's get started. For the square 5 ѣ 5 there is a solution (Fig.1, marked cells are colored red). Using rotations and reflections, you can get three more solutions, but the interesting thing is that there are no other solutions! This alone suggests that the great Leonardo could have been involved in such a problem - after all, it intuitively seems that the solution should be “more symmetrical,” well, at least with respect to the vertical and horizontal axes. Of course, we will not limit ourselves to the square 5 ѣ 5, but will “touch” the squares n ѣ n for other n as well.

⟦folio 28⟧

KVANT 2008/№1

⟦figure⟧

Fig. 1

For small n this can be done without much difficulty. The easiest way to get the answer is for n = 1 - it's just a single marked cell. For n = 2 we have four shaded cells, and the solution is also unique. The value n = 3 gives a nice configuration, again unique (Fig.2).

⟦figure⟧

Fig. 2

An unexpected scattering of different configurations is generated by n = 4. There are five fundamentally different ways to mark cells (Fig.3).

⟦figure⟧

Fig. 3

The first two of them are “bifurcated” with the help of rotations and reflections, and the remaining three are “quadrupled”. In total, there are 16 ways. A very “outlier” result compared to the rest of the n.s already considered. Further, solutions up to n = 8 were still able to be selected manually (we note, by the way, that the problem for the square 8 x 8, i.e. the chessboard itself, was proposed in the “Mathematics 6–8” competition of the current academic year (problem 5) - so we solved it at the same time). At the same time, very attractive configurations with a high degree of symmetry (Fig.4) were discovered. Already at this stage, despite the successes achieved, vague gloomy forebodings appeared. Firstly, it was not possible to find any “general” ways to mark the cells in the required way. Attempts to use the results found for smaller n when searching for solutions for larger n also turned out to be unsuccessful. True, the configuration for n = 8, as is easy to see, is obtained as if by adding a “border” to the configuration

Fig. 4

⟦column⟧

radios for n = 6, but this success is too modest (and, to be honest, it was revealed in hindsight). What to do? We had to use the achievements of modern computing technology and instruct the computer to look for what other n cells could be marked (and at the same time count the number of ways to do this for each n). Having started vigorously, the computer only got to n = 28, because with further growth of n it begins to think for an ungodly long time. However, the analysis of the results turned out to be so striking that the assumption of da Vinci’s involvement in the problem under consideration only became stronger. Judge for yourself. First, the computer confirmed the uniqueness of the solution for n = 6, 7 and 8. Moreover, it turned out that the solution exists for all n considered, and for n = 10, 12, 13, 15, 18, 20, 21, 22, 25, 26, 27 and 28 it is unique. Consequently, it has symmetry with respect to all symmetry axes of the board itself (otherwise additional solutions would appear, obtained by rotations and reflections). Further, for n = 17 (as well as for the n = 5 we know) there are 4 solutions, for n = 14 and 24 there are 16 solutions, for n = 11 the number of solutions reaches 64, for n = 9 and 16 it is 256. And then there is a truly amazing rise: with n = 23 the number of solutions sharply “jumps” to 16384, and for n = 19 – to 65536. Note that each of the numbers appearing here (1, 4, 16, 64, 256, 16384 and 65536) is a non-negative integer power of four. At the same time, configurations are already appearing that have neither axial nor rotational symmetry (although some of their fragments may be symmetrical). For example, this is what one of the possible results looks like for a board 19 ѣ 19 (Fig.5). Some kind of phantasmagoria! These kinds of results are simply stunning, and it begins to seem that somewhere nearby, like an inaudible shadow, the ghost of Leonardo, risen from the depths of centuries, is passing by. Did he really have a presentiment of something like this (the lack of a computer for a genius, as you know, is not a hindrance)? One way or another, but then

Fig. 5
