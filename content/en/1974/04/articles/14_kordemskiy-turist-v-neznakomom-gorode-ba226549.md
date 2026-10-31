---
id: 1974-4-kordemskiy-turist-v-neznakomom-gorode-ba226549
issue: kvant_1974_4
year: 1974
number: "4"
title: Tourist in an unfamiliar city
authors:
  - Кордемский Б. А.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 57
page_last: 58
page_labels: 55-56
tag: WD5K
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6b0729553a727a2f3425ae35aaffe6b4774665f91625bd539c4e56d1b125dc61
prompt_sha256: draft-1
translated_from: content/ru/1974/04/articles/14_kordemskiy-turist-v-neznakomom-gorode-ba226549.md
source_content_sha256: 421d0adddfb92695034cc08ab938ab61400cdfb738444bdccfeb401335657305
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 55⟧

Tourist in an unfamiliar city
V. A. Kordemsky

Imagine a city whose streets are like checkered tetrads - some stretch from south to south, others from east to west. There is a tourist center in this city. A tourist located at point A needs to get to this camp site. But he does not have a map, and there are no signs in the city, and the tourist cannot ask the residents - he does not know the language. Every time he wants to randomly determine both the direction of movement and how many blocks he needs to go in this direction before changing it again. But how does it mean to “determine randomly”; How can we implement “randomness” in general?

Eureka! The tourist needs a set of so-called “random numbers”, combined in pairs. The absolute value of the first number will indicate how many blocks the tourist needs to walk in the horizontal direction (horizontal is naturally called the direction “east - west”, “west - east”; and vertical - “north - south”, “south - north”), and the sign of the number is the direction itself: east if flat, and west if minus. Likewise, the absolute value of the second number will indicate how many blocks you need to walk in the vertical direction, to the south if this number is negative, and to the north if it is positive.

But where do you get “random numbers”? They can be issued by a computer if you give it the appropriate program, but the tourist, of course, does not have a computer. But he has a newspaper with a table of winning lottery ticket numbers. The tourist randomly selects part of the table

Artist M. Zlatkovsky

tsy, then in the number of each ticket logerina takes the last two

31013 179 Camera 90
31019 110 25 rubles —
31026 060 25 rubles —
31030 199 50 rubles —
31031 115 Watch “Flight” 35
31045 026 100 rubles —
31047 101 Camera 15
31068 178 50 rubles —
31069 100 Watch “Flight” 35
31070 096 50 rubles —

⟦folio 56⟧

numbers and consider them as a pair. The result is the following set of pairs of random numbers: (7, 9), (1, 0), (6, 0), (9, 9), (1, 5), (2, 6), (0, 1), (7, 8), (0, 0), (9, 6). The downside to these numbers is that they all end up being positive. But this drawback is easy to correct: for example, subtract from each number of the resulting set of random numbers some fixed number, say 5. In this case, the pair (7, 9) will turn into a pair (2, 4), which means: “you need to go two blocks to the east, then four blocks to the north”; pair (1, 0) - into pair (-4, -5), that is, “four blocks to the west and five blocks to the south.” A set of such pairs already sets the route for the tourist. In this case, the “code” of the resulting random route line will be written as follows: (2, 4), (-4, -5), (1, -5), (4, 4), (-4, 0), (-3, 1), (-5, -4), (2, 3), (-5, -5), (4, 1).

Now the tourist can hit the road.

Note that the tourist may never get to the tour; however, it is enough for him to be in any of the neighborhoods neighboring it, since from there the road is already known to him.

The selected route is shown at figure; It’s easy to see that it accidentally turned out to be not very long, although far from the shortest: after all, the tourist’s route is only 15 $\frac{1}{2}$ blocks away, and he had to walk more than 66!

In this example, random numbers allow us to simulate real randomness, namely, randomness that allows a tourist to choose one direction or another. At the same time, however, for each link of the route line it was necessary to artificially introduce restrictions - no more than four blocks in the directions assigned to positive numbers (east and north), and no more than five blocks in the directions determined by negative numbers (south and west). And one more thing: by replacing the numbers 0, 1, 2, 3, 4, 5, 6, 7, 8, 9 with -5, -4, -3, -2, -1, 0, 1, 2, 3, 4, we “corrected” the random numbers so that the “negative” directions - south and west - turned out to be preferred (-5, -4, -3, -2, -1 - there are five out of ten) “positive” - north and east (four out of ten).

Mathematicians call this model of “randomness” “heavy”, but do not consider it unacceptable.

Problem. Let the tourist know that the tourist center is located in the southwest of the city. This means that, while maintaining the principle of randomness in choosing a direction, it is still more expedient to make the directions south and west more preferred. But these directions are given by negative numbers; therefore, in a set of single-digit random numbers, you need to have more negative than positive numbers. To fulfill this requirement, you can, for example, reduce all the numbers in the written set not by 5, but by 7. I wonder if the tourist will get to the base sooner than the first time? Make a new “code” and a diagram of its random route.

In our article, random numbers turned out to be useful: they helped the tourist find a tour. They also help in many other tasks. That's why we told you about them.
