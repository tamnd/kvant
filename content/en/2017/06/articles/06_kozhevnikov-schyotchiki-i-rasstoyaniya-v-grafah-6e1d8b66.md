---
id: 2017-6-kozhevnikov-schyotchiki-i-rasstoyaniya-v-grafah-6e1d8b66
issue: kvant_2017_6
year: 2017
number: "6"
title: Counters and distances in graphs
authors:
  - Кожевников П. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 40
page_last: 53
page_labels: 39, 40, 46
tag: 4WBW
lang: en
source: kvant_digital
extraction: native
content_sha256: 63af9241a57c35a7a2f93973127a5b84bcc87cb912529135ebcf57fb0398032b
prompt_sha256: draft-1
translated_from: content/ru/2017/06/articles/06_kozhevnikov-schyotchiki-i-rasstoyaniya-v-grafah-6e1d8b66.md
source_content_sha256: 1994cce5e01a3cecaffc09dccf06f0338f0872857a09c95c934f32e55e3e7fca
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

MATHEMATICAL CIRCLE

Counters and distances in graphs

P.KOZHEVNIKOV

IN THIS ARTICLE WE WILL DISCUSS SOME approaches to combinatorial problems of estimating the number of operations. Let's first consider the following tasks. Problem 1. On a plane, a checkered square 5 5 (Fig.1) was laid out using partitions (unit segments). What a mini

⟦column⟧

⟦figure⟧

Fig. 3

two adjacent cards (Fig.3). In what is the smallest number of moves you can always get a row of cards going from left to right in ascending order? The conditions of the problems are completely different, but they have a single structure: a certain operation is defined and the question is asked about the smallest number of such operations that must be performed in order to get from one position to another. To find approaches to solving problems, we first discuss a simpler problem with a similar logical structure. Simple task. The chip stands at point 7, 7 coordinate plane (Fig.4). For

⟦figure⟧

Fig. 1

How many partitions need to be removed so that each square can be exited to the outside (without crossing the partition)? Problem 2. Given a strip 1 20, in which each cell is either white or black. In one operation you can recolor the cells in any rectangle (Fig.2). For what

⟦figure⟧

Fig. 2

In the least number of operations you can surely make the entire strip white? Task 3. Ten cards with numbers from 1 to 10 were placed in a row in some order. You can change places in one move

⟦figure⟧

Fig. 4

In one move it can be moved 1 to the right, left, up or down. In what is the least number of moves that a piece can get to the origin? Of course, in 14: the starting cell is 7 horizontal and 7 vertical from the goal, so you will have to make at least 7 horizontal moves and at least 7 vertical (and of course, there are many ways to reach the goal in exactly 14 moves). One can argue differently. To each node of the first quadrant of the integer re-

⟦folio 39⟧

MATHEMATICAL

grid, we write down the sum of the coordinates, then the written numbers represent a kind of counter: when a chip is in a cell with the number k, it has k moves left to reach the goal. The counter could be installed without involving coordinates, simply moving from the goal “from the end”: we put the number 1 in the nodes from which you can reach the goal in one move (I “floor”), the number 2 in the nodes from which you can reach a certain node from the 1st floor in one move (II “floor”), etc.

Exercise 1. Nine pieces initially fill the upper right corner of the 3 3 chessboard. In one move, you can move one of the chips to an adjacent free cell. In what is the least number of moves that 3 3 can move the chips to the lower left corner?

But let's return to problems 1–3. Now, if we could also find a suitable counter that changes by 1 (or at least in some controlled way) when performing the operation... Then we would understand how far (in terms of the number of moves) we are from the goal, and perhaps we could complete the solution as quickly as in the Simple Problem. Let's try it! Discussion and solution of problem 1. We will consider the plane to be an “ocean” in which partitions have separated several scattered “reservoirs”. Let us pay attention to the fact that at the beginning we have many separate bodies of water, and at the end, according to the condition, there should be only one left (from any cell you can swim to the “ocean”). In this case, in one operation, two reservoirs adjacent to the partition merge into one. This means that the number of reservoirs in one operation is reduced by 1? This is almost true: sometimes two cells adjacent to the partition are cells of the same body of water (Fig.5). In this case, after the operation of removing the partition, the number of reservoirs will not change. In any case, in one

Fig. 5

CIRCLE

⟦column⟧

operation, the number of reservoirs is reduced by no more than 1. At the beginning we have 26 reservoirs (including the external “ocean”), at the end there must be one left, so the number of operations is at least 26 – 1 = 25. We invite the reader to give an example of removing exactly 25 partitions (as we now understand, in the optimal example it is enough to only avoid removing partitions between two cells of the same reservoir). Thus, the appropriate counter (minimum number of moves to the goal) in problem 1 is n – 1, where n is the number of reservoirs. Note that a reformulation of this problem has been discussed in «Kvant» and before - for example, in the article “Contact the Count” («Kvant» No. 4, 2014). In fact, in many problems of the mentioned article, counters “the number of areas (or pieces, or connected components in the graph)” appear. Discussion and solution to problem 2. Ultimately, all the cells of the strip should become white, so at first it may seem that the desired counter should be related to the number of black cells. But even if there are a lot of black cells, sometimes you can get by with just one repainting operation (for example, for a completely black stripe). The fact is that it is just as easy to “fight” with a block of consecutive black cells as with one black cell. But eliminating a large number of transitions between black and white blocks is not so easy. The key to the solution must be sought by looking at these blocks or transitions between black and white blocks. Let's take the “number of black blocks” counter. Having considered all possible cases of performing the repainting operation (when the boundaries of the rectangle to be repainted are inside a black or white block or fall between blocks; some cases are shown in figure 6), we make sure that the number of black blocks either does not change or changes by 1. The final number of black blocks must be 0, the initial number of black blocks can be 10 - as in the case of the “zebra” at figure 7. This means that if the initial coloring is “zebra”, then we will need to perform at least 10 operations.

⟦folio 40⟧

KVANT 2017/№6

⟦figure⟧

Fig. 6

⟦figure⟧

Fig. 7

On the other hand, it is clear that in any situation the initial number of black blocks is no more than 10. And we can simply take a black block with each successive operation and turn it into white. In no more than 10 operations we will get a white stripe.

Exercise 2. Come up with another reasoning that solves the problem using “partitions” between black and white blocks.

Discussion and solution of problem 3. It is intuitively clear that the most “inconvenient” situation is when the cards are initially in descending order: 10, 9, 8, ..., 1. You can first track the movement of each card. In order to arrive at the ascending order of 1, 2, ..., 10, card 1 (the same as card 10) needs to move 9 positions to the left (respectively, to the right), cards 2 and 9 - to 7 positions, cards 3 and 8 - to 5, cards 4 and 7 - to 3, cards 5 and 6 - to 1 position. In total, the total movement should be equal to 2(9 + 7 + 5 + + 3 + 1) = 50. In one move, two cards move by 1, so you need to make at least 50/2 = 25 moves. However, in order for each card to move exactly the specified number of units, movements in the “wrong” direction are not allowed. For example, to get to the leftmost position in 9 moves, card 1 must only move left. The same should be true for card 2: to get to the second place from the left in 7 moves, card 2 must only move to the left. But at the same time

⟦column⟧

These two conditions are impossible for cards 1 and 2. Indeed, in the initial situation card 1 is to the right of card 2, and in the final situation it is to the left. This means that on some move we will need to swap cards 1 and 2, and card 2 will move 1 to the right, i.e. will move in the “wrong” direction. It turns out that trying to enter a “total number of moves” counter leads to some estimate for the number of moves, but this estimate is inaccurate. But, understanding the situation, we realized that we would definitely make a move consisting of exchanging a specific pair of cards 1 and 2. Similarly, for any pair of cards m < n, for which in the initial situation card n is to the left of card m (such initially “wrong” pairs of cards are also called “disorders”), at some point there should have been a move consisting of exchanging cards m and n. This means that in order to get from position 10, 9, 8, ..., 1 to position 1, 2, ..., 10, each specific pair of cards must be exchanged. Thus, the required number of moves is not less than the number of pairs, i.e. no less than

10 9 2

45.

On the other hand, for any initial situation, 45 moves will be enough. For example, first we exchange card 1 with all the cards that are to the left of it, as a result of which it will end up in the leftmost place. Then we “move” card 2 to the left and move it to the second place on the left, etc. Each time we reduce the number of disturbances by 1, which means we will make no more than 45 moves to the final position 1, 2, ..., 10. (Of course, here we can estimate the number of moves without any disturbances: card 1 made no more than 9 moves, after that card 2 - no more than 8 moves, etc., finally, card 9 made no more than one move, for a total of no more than 9 + 8 + ... + 1 = = 45 moves.) Problem 3 is solved. The “number of unrest” counter helped here. This counter is already “accurate”: in one move it changes (increases or decreases) by exactly 1.

Exercise 3. Initially, 10 cards with numbers from 1 to 10 were placed in a row in the order 2, 4, 6, 8, 10, 1, 3, 5, 7, 9. In one move, you can swap two adjacent cards (as in task 3).

⟦folio 46⟧

KVANT 2017/№6

Grade 11 1. See Problem 1 for Grade 10. 2. Find the number of three-digit numbers, written as numbers from 0 to 9 inclusive, in which exactly two digits match. 3. A circle is inscribed in a quadrilateral ABCD with unequal sides AB and CD, which touches the sides AB, BC, CD and AD at points K, L, M and N, respectively. Prove that the lines AC, KL and MN have a common point. 4. Find what is the greatest power of the number 3 that divides the product of all natural numbers from 1 to 2017 inclusive. 5. Solve a system of two equations $x y^{2} 2$ and $x^{2} y 2. 6.$ For each value of a, find the largest value of the function f x a

1 sin 2 x a

3 cos 2 x equal to M a. Find what the smallest value of M a is.

PHYSICS DEPARTMENT

PHYSICS

7th grade

1. Use a ruler to measure the length, width and height of a solid box, such as a shoe box. Determine the area of ​​each surface and the volume of the box. Estimate the error of each of the measurements taken. 2. Measure your stride length. Using this “measure”, determine the length of the path you walk to school or bus stop. Estimate the error in determining the path. 3. A car travels the first half of the journey at a speed of $v_{1} = 70$ km/h, and the second half at a speed of $v_{2} = 30$ km/h. Determine the average speed along the entire path. 4. The opera is listened to by: a spectator sitting in the theater hall, and a radio listener located near the receiver. The microphone is installed in the orchestra. Speed ​​of sound v = 340 m/s. The speed of propagation of radio waves is $c 3 10^{8}$ m/s. At what distance $s_{1}$ from the orchestra should the spectator sit in order to hear simultaneously with the radio listener, if the latter is located at a distance of $s_{2} = = 7500$ km from the theater?

⟦column⟧

5. The elevator car descended from the eleventh floor of the building to the fifth, and then rose to the eighth floor. Assuming that the distances between floors are L = 4 m, determine the path and displacement of the cabin.

8th grade

1. See problem 1 for 7th grade. 2. The boat, moving with the current between two points, spent time $t_{1}$, and returning back, he spent time $t_{2}$. Speed ​​of the boat relative to the water v. Find the speed of the current. 3. Two trains long $L_{1} = 600$ m and $L_{2} = = 800$ m walk along parallel tracks in the same direction at speeds $v_{1} = = 54$ km/h and $v_{2} = 72$ m/h accordingly. How long do they pass each other? 4. Determine the tension force of the thread connecting two balls of volume $10 см^{3}$ each, if the top ball floats, half immersed in water (Fig.3). The lower ball is 3 times heavier than the upper one - Fig. 3 him. 5. A body of mass m, falling from a height H, rose again to a height h. What amount of heat Q was released when the body hit the surface?

9th grade

1. When a portion of frozen dumplings was thrown into a pan of boiling water, the water level in it rose to a height of $h_{1}$. After some time, the dumplings were cooked and floated - after which the water level rose another $h_{2}$. How many times is the density of frozen dumplings greater than the density of boiling water? Dumplings do not absorb water. 2. There are two identical rulers of size a b c 30 2.5 0.4 cm and a weight of known mass. It is necessary to determine the mass of the ruler. To do this, one ruler is installed vertically, and the second is laid out on the first so that the rulers form the letter T and the horizontal ruler does not fall (Fig.4). Then take a weight of known mass m and find the minimum distances $x_{1}$ and $x_{2}$ to the edges of the linear

⟦folio none⟧

ANSWERS, INSTRUCTIONS, SOLUTIONS

"QUANT" FOR JUNIOR SCHOOLCHILDREN

TASKS

(see «Kvant» No. 5)

1. 7 soldi. Change with three different coins is no less than 1 + 2 + 3 = 6 soldi. Since this money was not enough for ice cream, it costs no less than 7 soldi. Ice cream cannot cost more than 7 soldi, otherwise Pinocchio would have spent no less than 8 + 8 = 16 soldi for two ice creams, but he only had one coin, i.e. no more than 20 soldi, and then he would not be able to get 6 soldi in change. This means that ice cream can only cost 7 soldi. Indeed, then the process of paying for ice cream looked like this: 20 – 7 = 13; 13 – 7 = 6 = 1 + + 2 + 3. 2. Blue. The first color photo has 8 red edges, the second has 8 blue edges, and the third has 8 yellow edges. Since four cubes have a total of 6 ¥ 4 = 24 sides and 8 ¥ 3 = 24, then the first photo has all red faces, the second has all blue, and the third has all yellow. In the photograph of the parallelepiped, all four cubes are visible, and only one of them has one visible face, and each of the other three has at least two visible. In the first color photo there are two cubes that have only one red edge, which means the color you are looking for cannot be red. In the third color photo there is a cube that has no yellow faces, therefore the color you are looking for is not yellow. Thus, all visible faces of the cubes can only be blue. This is possible, since in the second color photo: 1) there is a cube with three blue faces that have a common vertex; 2) there are two cubes, each of which has two adjacent blue faces; 3) there is another cube with a blue side. Note that the condition of the problem allows us to determine how all the cubes are colored. There is a cube with three adjacent red and three adjacent blue sides, a cube with three adjacent red, two yellow and one blue side, and two identical cubes with three adjacent yellow, two blue and one red side. 3. Here are two possible examples:

7 6 5 3 5 6 9 2 + + + = 9, + + + = 7. 4 8 1 2 4 8 3 1

4. Yes, it can. Examples – at figure 1.

⟦column⟧

⟦figure⟧

Fig. 1

COMPETITION NAMED AFTER A.P. SAVINA

(see «Kvant» No. 4)

24. 182. If some quality of a fairy increased every day, then she could not become the same. This means that in order for the fairy not to change, it is necessary that each of its qualities deteriorate at least once or remain the same all the time. If there are at least 183 fairies, then in total they have 183 ◊ 2 = 366 qualities - this is more than the number of days in a year. But every day only one quality of one fairy worsens or remains the same. So this couldn't happen. Let's show that there could be 182 fairies. Then they have 364 qualities. Let there be a decrease in one of the qualities every day, a total of 365 decreases. 363 qualities will have one decrease per year and exactly as much as it increased over all other days. And the remaining quality will have two decreases, again exactly as much as it increased over the remaining 363 days. Then the fairies by the end of the year will be the same as they were at the beginning. 25. a) Yes; b) yes; c) no. a) Let us denote the vertices of the quadrilateral as A, B, C, D. Since AC is a chord of a circle, the perpendicular bisector to AC divides the circle in half. Let's construct a point E that is symmetrical to point D relative to the perpendicular bisector. Due to symmetry, point E will also lie on the boundary of the circle, as well as AD = CE and AE = BD. Then the quadrilateral ABCE is the desired one: it lies inside the circle and the lengths of its sides are the same as those of the original quadrilateral, but their order has changed. (In fact, we cut the quadrilateral along the diagonal AC, flipped the triangle ADC and joined it again into a quadrilateral.) Note that we only used the fact that AC is a chord of the circle.
