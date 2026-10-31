---
id: 1973-9-kordemskiy-krasochnaya-kombinatorika-746613d9
issue: kvant_1973_9
year: 1973
number: "9"
title: Colorful combinatorics
authors:
  - Кордемский Б. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 20
page_last: 24
page_labels: 18, 21, 22
tag: 1F03
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2e8e2f396fef013c6ac85f61098ab3a09608f08182db4081668458b371b2fcef
prompt_sha256: draft-1
translated_from: content/ru/1973/09/articles/04_kordemskiy-krasochnaya-kombinatorika-746613d9.md
source_content_sha256: 3f5d60d08789f4dba6d503eb8ae07aeec10f6cc4447fc3771d76377ddc7d52cb
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 18⟧

COLORFUL
COMBINATORICS
B.A. Korgemsky

The first classes of the “colorful combinatorial class” are memorable for each of us: on white paper - “orange sky”, “orange camel” and “orange mother”. Stepping over the threshold of this childish “orange” combinatorial geometry, mathematical fantasy introduced a palette of colors in the context of problems that were entertaining, but at the same time serious - problems about combinations of colors and coloring cards. And in some problems, a different use of colors turned out to be possible: coloring is an element of the solution, a twist that gives grace and brevity to reasoning.

As for combinatorial geometry, this is a young, developing branch of mathematics. Its methods and, in particular, coloring in combination with the so-called “parity principle” of the number of single-link parts of a figure can be useful in solving engineering problems of finding optimal ways to fit standard parts. Putting off a more detailed story about this for the future, let’s consider, “as a warm-up,” several busy combinators of “colorful” problems.

One piece of advice: following the text of the article, try every time to outdo the author in solving the proposed problems.

Two-color combination

Problem 1. Six points are located in space mak such that no three lie on the same line and no four belong to the same plane. All points are connected in pairs by segments: blue or red - at your discretion. The resulting configuration, containing 15 segments ($C_6^2 = 15$), also contains triangles. Is it possible to select the maximum distribution of colors for the segments such that not a single zone of a single-bar triangle would be formed?

Trials and attempts will lead you to a negative answer. It needs to be justified.

Solution. Let us choose an arbitrary one of the given six points and denote it by the letter A. Of the five segments converging at A, there are at least three of the same color, since we have only two colors; Let's mark three of these segments and assume for definiteness that they are red. Let's consider three segments connecting pairs of other ends of marked segments. None of the three segments under consideration should be red, so that a triangle does not arise, all sides of which are the same color. But then the last three segments are all blue and inevitably form a one-dimensional triangle.

Let's implement parquet

Problem 2. On figure 1 the covering (napkem) of the square $8 \times 8$ is shown with twenty-one flat minimos ($3 \times 1$) and one flat monomino ($1 \times 1$). Prove that the specified position of the block is “monomino”

⟦folio 21⟧

ferium cube. Can it pass through the centers of all the cups and end up in the central cube if the termite moves only parallel to the edges of the cube and passes through each cube once?

Another fake coin

“Again” - in the sense that, most likely, many of you are familiar with a series of problems about identifying a counterfeit coin from a given sample of coins of the same denomination and type using the specified number of weighing on cup scales without mushrooms. The author of these problems is unknown; Their solutions and research began to appear in mathematical journals in 1945.

Let us remind you that if there is no information about the counterfeit coin (whether it is heavier or lighter than the real one), then three weighings are enough to separate it from 12 given coins, but not enough to separate it from 13. But...

Problem 9. Suppose that in addition to 13 coins, among which there is one counterfeit one (it is unknown whether it is lighter or softer), we have at our disposal one fake coin,

and winding. Its coloring is as follows to describe it from the others, but without a noticeable change in its own weight. Show that in this case it is possible to select a counterfeit coin from 13 given ones using three weighings on a counterfeit scale without mushrooms.

Solved and e. We denote: 13 test coins by numbers 1-13, a colored real coin by a circle ●, the left and right cups of the scales corresponding to the letters L and P, equilibrium - L=P; the left pan of the scales L/R is lowered, the right pan of the scales is lowered - L/R.

It is convenient to present the diagram of possible events in a table (below).

Mathematical "catalyst"
The process of accelerating a chemical reaction with the help of an auxiliary substance - a catalyst that is not consumed during the reaction - is called kamaliz. Let us show with one example how coloring can be a kind of “catalysis” for solving a problem.

| First weigh-in | Second weigh-in | Third weighing | Fake coin |
| :--- | :--- | :--- | :--- |
| coins on cups | coins on cups | coins on cups | coins on cups |
| L=P | L(10; 11) P(12; ●) | L(13); P(●) | {L/R L/R L/R L/R } | 13; heavy 13; lay down 12; lay down 10; heavy 11; heavy 12; heavy 11; lay down 10; lay down |
| L/R | L(1, 2, 6, 7, 8) P(9, 10, 11, 12, ●) | L(3); P(4) L(1); P(2) L(6); P(7) | {L=R L/R L/R L/R } | 5; heavy 3; heavy 4; heavy 9; lay down 1; heavy 2; heavy 8; lay down 6; lay down 7; lay down |
| L/R | | | | |

Find out what's most important

⟦folio 22⟧

Fig. 9.

Problem 10. Determine what minimum number of coconuts can be collected by five sailors who landed on the island after a shipwreck, if they divided the nuts like this: the first of them harvested one martin nut and took $1/5$ part of the remaining nuts; powerfully, one after another, the remaining 4 sailors also accepted; After Emodo, for the sixth time, they harvested one nut from the martynika, and divided the rest equally among themselves.

In a slightly modified version, this problem is considered in the author’s article “This type of problem is more than 1600 years old” («Kvant» No. 4, 1973).

Algebraic solutions lead to a linear indeterminate equation with cumbersome coefficients, which, however, as shown in the mentioned article, is easily solved by the “modulo comparison” method. But anyone who is passionate about mathematics will probably return with satisfaction to this problem once again and, further exposition, will try to find a new model of reasoning, using additional yellow-colored nuts as a “catalyst” for solving the problem (to distinguish them from the original ones).

M. Gardner in the book “Mathematical Puzzles and Entertainment” (World, 1971) notes that “Coloring as a way to solve a problem was first introduced back in 1912 by Professor N. Anning. His task involved three people dividing apples among themselves” (see page 238). Next, M. Gardner shows how Anning's method can be applied to solving the coconut problem.

Unfortunately, this is where the book contains erroneous statements that may have arisen as a result of inaccurate translation.

Solution. The problem would be much easier to solve if it were not necessary to give the nuts to the monkey. By separating the $1/5$ portion of nuts from the heap six times, we would leave $4/5$, $(4/5)^2$, $(4/5)^3$, ..., $(4/5)^6$ nuts in the heap. The smallest number of nuts from which $(4/5)^6$ is an integer is $5^6$, because it must contain the polynomial five six times.

But we still need to give the nuts to the monkey, so even the original number of nuts should not be reduced by five. To make it divisible by five, add four yellow nuts to the pile. Let's see what happens.

So, we add four more yellow nuts to the pile of nuts collected by the sailors. We will divide this pile into five equal piles, and distribute the yellow nuts one at a time into four piles. Four sailors prepared a pile of yellow nuts, and one of them prepared a pile in which all the nuts were real. Let's take out one nut from the piles: from four - a yellow one, and from the last - a real one. The sailors will get an equal share of nuts, and the monkey will get a nut, and four yellow ones are left aside. Everything worked out according to the conditions of the task.

Now, according to the conditions, a bunch of four sailors together and add the remaining four nuts. According to the condition, this heap
