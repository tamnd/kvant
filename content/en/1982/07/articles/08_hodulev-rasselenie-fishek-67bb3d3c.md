---
id: 1982-7-hodulev-rasselenie-fishek-67bb3d3c
issue: kvant_1982_7
year: 1982
number: "7"
title: Dispersal of chips
authors:
  - Ходулёв А. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 30
page_last: 33
page_labels: 28, 30, 31
tag: MQ6D
lang: en
source: kvant_digital
extraction: vision
content_sha256: cc49e53591cfabcf58388dce4b71906e247882fe64f07cec499a3a286c04fdcf
prompt_sha256: draft-1
translated_from: content/ru/1982/07/articles/08_hodulev-rasselenie-fishek-67bb3d3c.md
source_content_sha256: a7778d566a7024b55058230599e008f7c3f9fe4af5beeacfddabe7b478d247be
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

A. Khodulyev

Dispersal of chips

From the editor

This note is devoted to the following problem by M. Kontsevich (from No. 11 of 1981), recognized by readers as one of the best environments published in the Quantum Problem Book last year:

M715. The right angle is divided into cells. On some cells there are chips, and the arrangement of the chips can be transformed as follows: if for some chips the cell adjacent to the top and the cell adjacent to the right are free, then a chip is placed in these cells, and the old chip is removed. First, one chip is placed in the corner cell. Is it possible to free the corners of a) three, b) six, c) ten cells, shown in Figure 1, a, b, c, from the counters using several of the indicated transformations?

We also really liked this task - we found in it many features that would be shared in new materials sent to the journal: a visual formulation encouraging us to do an experiment and then build a general theory; an object of study characteristic of modern discrete and applied mathematics (a lattice filled with ones and zeros, local transition rules); natural appearance in the solution of a whole bunch of important mathematical concepts and constructions (invariant, infinite sum, embedding of a problem in some “extension” of it, finite algorithm, etc.). We strongly advise those who have not solved problem M715 to think about it for at least an hour before reading the article (“the main” figure 8 we deliberately sent to the end of the article). For the rest, who have already experienced this satisfaction, we propose to prove the unproven facts from the second part of the article, which sets out a small theory that allows us to study the solvability of the “Kontsevich game” in the most general case.

Solution to problem M715. Invariant

To determine the desired sequence of moves, it is convenient to use checkers and a regular chessboard. By placing a checker in the lower left corner and experimenting a little, it is easy to find a solution to problem a). In this problem, you can free the pink area, for example, as shown in figure 2 - in 4 moves (1,1), (2,1), (2,2), (1,2). (The move record indicates the coordinates of the cell from which a chip is removed when making a move. For example, a move (2,1) means that a chip is removed from the field (2,1), and new chips are placed on the fields (2,2) and (3,1).

Fig. 1.

⟦folio 30⟧

starting both of these rows together through $L$ - see Fig. 3, where $L$ is highlighted in blue) there will always be only one chip, each of which will contribute to the sum $s_{\text{кон}}$, not exceeding 1/8 (since they must be outside $B$). The sum of the numbers for the remaining chips must be less than $s(K \setminus B \setminus L) = 3/4$. Therefore, $s_{\text{кон}} < s(K \setminus B \setminus L) + 2 \cdot \frac{1}{8} = 1$, and this already contradicts the fact that $s_{\text{нач}} = 1$.

Tasks a), b), c) have been solved, but it is interesting to learn how to use any similar task. Is it possible, for example, to release the area $\Gamma$ shown in figure 4? Here $s(K \setminus \Gamma) = 1\frac{1}{2}$ and even taking into account the uniqueness of the chips in the first horizontal and vertical row, you can only get $s_{\text{кон}} < 1\frac{1}{8}$.

However, it was not possible to liberate this area.

We will now study problems of this type: first, tokens fill the set $H$; you need to free the set $F$ in several moves (here $H$ and $F$ are any finite sets of cells from $K$). Let's call it the liberation problem ($H, F$).

Generalized positions and moves

First of all, it is convenient to get rid of the prohibition on making a move from cell $(i, j)$ when it is free or when cells $(i, j+1)$, $(i+1, j)$ are occupied (given in the conditions of the rule problem

⟦folio 31⟧

prevents you from changing the order of moves, which is very confusing). But then we will have to broadly generalize the concept of position. We will now assume that in the cell $(i, j)$ there can be any integer number $A_{ij}$ of chips - not only positive, but also negative, and for each position $A$ only for a finite set of cells the number $A_{ij}$ is different from 0. A move (generalized) in such a position is a simultaneous replacement
$$A_{ij} \rightarrow A_{ij} - 1, A_{i+1,j} \rightarrow A_{i+1,j} + 1, A_{i+1,j} \rightarrow A_{i+1,j} + 1.$$
We will call the previous positions (in which $A_{ij}=1$ or $A_{ij}=0$) and moves normal.

figure 5 shows a move that results in a non-normal position from a normal position. At the bottom of figure 5 the same position is shown in a new, numerical notation.

The result of making a move from square $(i, j)$ is to subtract ones from $A_{ij}$ and add ones to $A_{i+1,j}$ and $A_{i,j+1}$; the result of several such subtractions and additions obviously does not depend on the order in which they are performed.

There is the following replacement fact, which allows us to use generalized moves to solve the problem we are interested in: if one normal position $P$ can be transferred to another normal position $Q$ by a sequence of arbitrary (possibly not normal) moves $\{d_1, d_2, \dots, d_n\}$, then $P$ can be transferred to $Q$ and some sequence of normal moves obtained by permuting the moves of this sequences. (Prove it!)

Next, together with the release problem $(H, F)$, we will consider the following “normalization problem”: given a position $A$, in which all are $A_{ij} \geq 0$, and some are $A_{ij}>1$; it takes several moves to bring it back to normal. To reduce the forward problem to the second, we form position $A_{ij}=H_{ij}+F_{ij}$ (let’s denote it $A=H+F$), in other words, to the chips $H$ we add another chip everywhere in $F$ - then in $F \cap H$ there will be two chips. It turns out that the release problem $(H, F)$ is equivalent to the normalization problem $H+F$. (Prove it!)

Solution to “problem d” (Fig. 4)

By adding one token at a time in the cells of the region $\Gamma$, we obtain the normalization problem shown in figure 6.

We recommend that you continue with further moves on the chessboard. General checkers will do - you won't get minus checkers. Looking at the position, we see that there are two counters on the $(1,1)$ square. One of them must be removed; this can only be done by moving $(1,1)$. This means that the move $(1,1)$ must be present in any solution, that is, it is a necessary move. We can assume that it is done first. Let's do it. We get the position shown in the second picture on figure 7. Further (necessary) moves are shown on the same figure. As a result of their execution, the original position reappeared (only moved one cell up and one cell to the right). It follows that the original problem d) is unsolvable (think about it!).

General algorithm

Using generalized moves and normalizations, we were able to disaggregate

Fig. 7. (For the ending, see p. 55.)
