---
id: 1989-7-kurlyandchik-fomin-etyudyi-o-poluinvariante-6348dff1
issue: kvant_1989_7
year: 1989
number: "7"
title: Studies on semi-invariant
authors:
  - Курляндчик Л. Д.
  - Фомин Д. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 65
page_last: 70
page_labels: 63, 65, 66, 67, 68
tag: UBAD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 820d0cd0a06b377f57c3a8856b84399765ecce918824f65f1fbe58fcb3752680
prompt_sha256: draft-1
translated_from: content/ru/1989/07/articles/14_kurlyandchik-fomin-etyudyi-o-poluinvariante-6348dff1.md
source_content_sha256: 5b9e159b6e9345c931078de397b060477497384c8e1c6566555bcf0e5b184d7b
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 63⟧

Sketches
about semi-invariant

L. D. KURLYANDCHIK, D. V. FOMIN

If you want to combine business with pleasure, then stock up on a bag of conferences and play this game together with a friend. Place two piles of confers on the table, the first has 12 confers, and the second has 13. During each turn, each of you can either eat two confers from one pile, or move one confer from the first pile to the second. The one who cannot make a move loses.

If your resources allow you to play this wonderful game for a long time, then you will notice a strange pattern: the beginner always loses! However, the reason for this is easy to understand. The fact is that with each move, the difference between the number of conferences in the second and first piles changes by two. This means that the remainder from dividing this difference by 4 will change in a strictly defined way: 1, 3, 1, 3, 1, 3,... We see that with each move of the second player this remainder will be equal to trem. But the game stops only if the candies are over or only one candy remains, and in the second pile. This situation cannot arise during the second player's move.

It is very possible that you know the idea of ​​​​this reasoning, in particular, if your “reading experience” is long enough, you could come across similar reasoning in the country “Ponishk invariant” («Kvant», 1976, No. 2). Remember? An invariant is something that does not change. And here, just every two moves, the remainder does not change when divided by even differences in the numbers of conferences in groups. (This message applies, of course, to any other number of conferences.) However, our

⟦folio 65⟧

a picture consisting of $n$ straight lines and $n$ perpendiculars. Let's select two intersecting perpendiculars on it and apply our operation: replace these two perpendiculars with two others with a smaller sum of lengths. In the resulting picture we will again find two intersecting perpendiculars, again apply our operation to them, and so on. Then either at some step we will get a picture with pairwise disjoint perpendiculars, or in the end we will get a picture with the minimum possible sum of the lengths of the perpendiculars (since this sum can only take a finite number of values; why?). This picture is an exception: if two perpendiculars on it intersect, then, applying our operation again, we would get a picture with an even smaller sum of the lengths of the perpendiculars.

Let's analyze these two solutions. We acted in them according to one scheme: we introduced a certain quantity (in the first problem it is the sum of all the numbers in the table, and in the second it is the sum of the lengths of the perpendiculars) and an operation, as a result of which this quantity changed in a certain way: in the first problem it increased, and in the second it decreased. The decision is based on the fact that the entered value can take only a finite number of different values. Consequently, this operation can be applied only a finite number of times, and we will inevitably arrive at the situation required in the problem.

From this point of view, the second task is more difficult than the first, since in it we had to take into account not only the desired quantity, the change of which we must trace, but also the operation itself.

In addition, the second problem is an excellent example of how easy it is to get a false trace: the new perpendiculars $AA_2$ and $BB_2$ do not intersect, and therefore each trace is responsible for the number of intersection points of our $n$ perpendiculars, which, at first glance, always decreases with the described operation. However, this is not true (build an example accordingly).

Learning to come up with the necessary “operation-quantity” pair is no longer easy. This requires experience and intuition.

A quantity that changes monotically and takes on only a finite number of different values ​​will be called received.

The following problem can also be classified as well known.

Task 3. Prove that any 2$n$ points on the plane are the ends of $n$ intersecting segments.

Let us draw $n$ segments with ends at these points in an arbitrary manner. If no two of them intersect, then the requirement of the problem is satisfied. Otherwise, consider a pair of intersecting segments $AB$ and $CD$ (Fig.2). As an exception, it is natural to consider replacing the intersection of the segments $AB$ and $CD$ with the intersection of the segments $AC$ and $BD$.

It remains to find the resulting value - a quantity that behaves monotonically during this operation. Since the sum of the lengths of the diagonals $AB$ and $CD$ of the convex quadrilateral $ACBD$ is greater than

⟦folio 66⟧

the sum of the lengths of opposite sides AC and BD; the sum of the lengths of n segments can be taken as a half-varant. It is clear that this sum can take only a finite number of values. Reasoning in the same way as in the previous problem, we end up with a set of n segments with a minimum sum of length. It is easy to understand that no two segments intersect in it.

In task 3, in fact, at the beginning there was neither an operation nor a semi-warrant. However, once we selected the operation, choosing a half-varant was not difficult.

Problem 4. There are n numbers along the circle. If there are numbers a, b, c and d in a row and (a-d)(b-c)>0, then the numbers b and c are cut and swapped. Prove that after several steps we were not able to perform any such permutation.*)

Here the operation of replacing numbers is given. Despite the fact that it affects only two numbers, it is convenient to perceive this operation on the entire set of numbers, considering that the operation leaves all other numbers unchanged: after all, in accordance with our “philosophy of decision”, it is necessary to select a certain value depending on the entire set of numbers.

So, the path of consecutive numbers a, b, c and d is such that (a-d)(b-c)>0, i.e. ab+cd>ac+bd. When performing our operation, we passed from the quadruple a, b, c, d to the quadruple a, c, b, d, and we see that the sum of the products of neighboring numbers has decreased: ab+bc+cd>ac+cb+bd.

Now it is clear that the semivarant in this problem is the sum of pairwise products of neighboring numbers of the entire set. With this operation, the half-varant is reduced, and since it can only take on a finite number of values ​​(why?), our operation can only be applied a finite number of times.

We took the next problem from the book by V.V. Prasolov “Planetarium Problems” (Part 2, 21, 25).

Problem 5. The following operations are performed with a small polygon. If it lies on one side of the line AB, where A and B are non-adjacent vertices of the polygon, then one of the parts into which the contour of the polygon is divided by points A and B is centrally symmetrically reflected relative to the middle of the segment AB. Prove that after several such operations the polygon becomes convex.

So, the operation is given again - this is a polygon transformation. The semivarant, monotonically increasing during this operation, here we can clearly see that the sum of the products of neighboring numbers has decreased: ab+bc+cd>ac+cb+bd.

Now it is clear that the semivarant in this problem is the sum of pairwise products of neighboring numbers of the entire set. With this operation, the half-varant is reduced, and since it can only take on a finite number of values ​​(why?), our operation can only be applied a finite number of times.

The following problem was proposed by an eighth-classicist at the All-Union Olympiad in 1979. It was solved by only three participants.

Task 6. Each paramenta has no more than three enemies. Prove that the parliament can be divided into two chambers so that each

⟦folio 67⟧

a parliamentarian in the same chamber with him will have no more than one enemy.*)

Let's divide parliament into chambers in an arbitrary way. If each parlamentaria has no more than one enemy in the same chamber as him, then the requirement of the task is fulfilled. Otherwise, consider a parlamentaria $A$ that has at least two enemies in the same ward. As a polyvariant, consider the number of pairs of enemies located in one chamber. It is clear that by moving parlamentaria $A$ to another chamber, we reduce this number. All that remains is to produce the standard phrase: “A polyvarant can take only a finite number of values.”

The following problem was proposed at the Moscow City Olympics in 1964. It turned out to be so difficult that none of the Olympiad participants solved it.

Problem 7. When King Arthur meets two, 2N knights gather, and each of them has no more than $N-1$ enemies among them. Prove that Merlin, Arthur's advisor, can seat the knights at the Round Table in such a way that not one of them will sit next to his enemy.

We will seat the knights at the Round Table in an arbitrary manner. If it turns out that no two enemies are sitting next to each other, then the task requirement is fulfilled. Otherwise, consider the knight $A$ sitting to the left of his enemy $B$ (Fig. 4, a).

*) See also Problem M580 («Kvant», 1979, No. 8).

As in the previous problem, we consider the number of pairs of enemy neighbors as a polyvariant (this is suggested by the conditions of the problem themselves). We need to come up with an operation that reduces this number. This is the most difficult part of the decision.

Among the friends of knight $A$, you must find a knight $C$ such that his right neighbor $D$ is a friend of knight $B$ (otherwise the knight $B$ has more than $N-1$ enemies). Now let’s “expand” the entire section of the word from $B$ to $C$ (to the right of $B$, Fig. 4, b) in the “reverse” direction (Fig. 4, b). In this case, knight $B$ will become a neighbor of knight $D$, knight $C$ will become a neighbor of knight $A$. The remaining pairs of neighbors will not change. Therefore, the polyvarant actually decreases.

In problems involving polyvariant realities, the question arises about the time during which the process under consideration ends. We recommend that you analyze all the analyzed tasks from this point of view. You will find that this is usually not an easy question. We will give just one example.

Problem 8. $N$ numbers are written randomly on the board in a row, each of which is equal to $+1$ or $-1$. In one move you are allowed to change the sign of several consecutive numbers. In what is the smallest number of moves that can be completed to obtain a set of only units from the original set?

The operation is given to us, and as a polyvariant we consider the number of pairs of neighbors of different signs. When performing one operation of replacing characters, this polyvarant can change by no more than two.

Fig. 4.

⟦folio 68⟧

Let us now prove that from the set of numbers -1, +1, -1, +1, ... it is impossible to obtain the set +1, +1, +1, ... in less than [(N+1)/2] steps. ([x] denotes the integer part of the number x.) The distance of separately random and odd N. Let N=2k, i.e. [(N+1)/2]=k. Then at the beginning the result is equal to 2k - 1, and at the end it must be equal to zero. But it is impossible to add what is required in k—1 moves.

Let N=2k+1, i.e. [(N+1)/2]=k+1. In this case, the gain of the original set is equal to 2k, so in k-1 moves the original set cannot be completely converted into a set of only ones. Let us prove that this cannot be done in k moves. To do this, it is enough to replace that at least once the resulting value will change by no more than one (this will happen when the operation of replacing signs affects some of the extreme numbers -1).

It remains to show that in [(N+1)/2]moves one can obtain a set of only ones from any initial set. Let us select in the original set all groups in a row of numbers -1, there are no more than [(N+1)/2]. Now after adding, let's change the signs of the numbers of these groups.

Turning in conclusion to the original problem about candies, we note that in it the quantities 2a + b could be taken as the resulting problem, where a is the number of candies in the first pile, and b is the number of candies in the second pile.

At the wife's

1. There are 2N points on the given plane, no three of which lie on the same straight line. N of them are rendered in colorful color, the rest are in blue. Prove that these points can be connected by N disjoint segments, each of which will connect the extreme point with the blue. («Kvant», 1975, No. 1, problem M301.)

2. There are N points on a given plane, the non-tortic ones of which are connected by segments. It is known that no more than 11 segments extend from any point. Prove that these points can be expanded into four colors so that there are no more than N segments with one-point ends.

3. Several red and several blue dots are specified. Some of them are connected by segments. It is known that a point is special if more than half of the points connected to it have a color different from its color. If at least one particular point is selected, then any particular point is selected and repainted in a different color. Prove that after a finite number of balls there will be no singular point left. («Kvant», 1974, no. 8, problem M277; All-Basic Olympiad, 1974)

4. On each face of the cube there is a number written, and not all of these numbers are the same. Each of the written numbers is replaced by the arithmetic mean of the numbers written on four adjacent faces. Is it possible that after several such operations the original numbers will appear on all the grains?

5. N natural numbers are written around a circle. Between each two adjacent numbers their most common divisor is written. After this, the previous numbers are erased, and the same operation is performed with the remaining ones. Prove that after a few balls all the numbers on the circle will be equal. (Leningrad City Olympics, 1973.)

6. There are 10 numbers written on the board: one and nine zeros. You are allowed to choose any numbers and replace each with their arithmetic mean. What is the largest number that can appear in the place of ones after a series of such operations? (Leningrad City Olympics, 1984.)

7. On an endless checkered sheet of white paper, several squares are painted black. At time moments t=1, 2, 3, ..., simultaneous recoloring of all cells of the sheet is carried out according to the following rule: each cell K takes the color that most of the three cells had at the previous moment: the cell K itself and its neighbors to the right and above. Prove that after some time there will be no black cells left on the sheet. (All-Major Olympics, 1973.)

8. There are several guys standing in a circle, each of them has several candies. At the leader’s signal, everyone transfers half of their candies to the one standing on the right (if the number of candies is odd, then the leading transmitter adds one candy to him). This is repeated many times. Prove that someday all the guys have the same amount of candy. (Leningrad City Olympics, 1983.)

9. On one side of the endless corridor there is an infinite number of rooms, numbered in order by integers, and on each side there is a piano. A certain finite number of pinastics live in these rooms (several pinastics can live in one room). Every day, some two pinastics living in neighboring rooms - the k-th and (k+1)-th - come to the conclusion that they interfere with each other, and intersect in the corresponding (k-1)-th and (k+2)-th rooms. Prove that after a finite number of days these intersections will stop. («Kvant», 1984, No. 6, problem M870.)

10. In the library, N volumes of the Encyclopedia Britannica are arranged in random order on a shelf. The robot librarian does the following every minute: he takes an arbitrary volume that is not in its place and puts it in its place (i.e., if the volume number is k, then it places it k-th in a row). Prove that after some time all the volumes will remain in their place. (Leningrad City Olympics, 1987.)
