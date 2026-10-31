---
id: 1976-8-rozental-pravilo-kraynego-34aa9399
issue: kvant_1976_8
year: 1976
number: "8"
title: The "extreme" rule
authors:
  - Розенталь А. Л.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 59
page_last: 63
page_labels: 57-61
tag: ZKB4
lang: en
source: kvant_digital
extraction: vision
content_sha256: c51df43b4c90bebc3040edf7f9f2fb1bcbb9cb03efbf8264ad052d0974a52764
prompt_sha256: draft-1
translated_from: content/ru/1976/08/articles/24_rozental-pravilo-kraynego-34aa9399.md
source_content_sha256: 30010037fab2aff571add9dea3fae07eaafecdf560a17c13e4b9e443162afc01
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 57⟧

If you want to learn how to solve mathematical problems, you need to try to master more or less general approaches, techniques and methods of mathematical reasoning. Let's look at one spring general approach, which we will call *the rule of “extreme”*.

The rule of "extreme" can be briefly expressed by the words "Unwind the extreme!" This rule is simply a recommendation to consider an object that has some “extreme”, or, as mathematicians say, extreme properties. If the problem concerns a set of points on a line, then the rule is “Look at the extreme!” advises us to focus our attention on the most extreme point of the set (the most left or the most right). If the problem involves a certain set of numbers, then the rule of “extreme” recommends considering the most or most of these numbers. Here are some examples.

Problem 1. A certain set of points M is given on the plane such that each point from M is the midpoint of a segment connecting any pair of points, or a set M. Prove that the set M contains an infinite set of points.

It often happens that the key to solving a problem is found by solving a simpler, similar problem. Therefore, before solving this problem, let's try to solve the following problem.

Problem 2. A set of points M is given on a line, assuming that each point from M is the midpoint of a segment connecting two other points of M; this means that it does not belong to M. The resulting contradiction proves that the set M cannot be finite.

Let us give another solution to this problem using the rule of “extreme”. Let us again assume that the set M is finite, and consider the lengths of the segments connecting points from M. This set of numbers is finite. Applicable

⟦folio 58⟧

Our rule to him is in the form: “Consider the most!” — consider the segment BC of the longest length. It is clear that there are no points from M outside the segment BC, otherwise there would be segments with large lengths. Thus, all points of the set M lie on the segment BC and, therefore, neither B nor C satisfy the conditions, that is, they do not belong to the set M. A contradiction.

Let us now return to Problem 1. Let us assume that the set M is finite. Let's apply the "extreme" rule again. To do this, we fix the position of the plane and consider the leyth point of the set M, and if there are several “leftmost” points, then we take the lowest of them. It is easy to see that this point, let us denote it by A, cannot lie inside the segment connecting two points of the set M. Indeed, if such a segment existed, then one of its ends would be either the left A or on the same vertical with the point A, but below it. Neither one nor the other can exist due to the choice of point A.

Here, as in Problem 2, there is also a solution based on the consideration of pairwise distances between points of the set M. If the set M is finite, then there is a finite number of pairwise distances, and among them, guided by the rule of the “extreme,” one can find the most. Let this be the distance between points A and B. But point B is the midpoint of a certain segment CD, the ends of which, by condition, belong to the set M (Fig. 1). Then it is easy to prove that either |AD| or |AC| more |AB| (do this yourself, take advantage of the fact that the median m drawn to one of the sides of the triangle is less than half the sum of the other two sides).

Problem 3. Namural numbers are written on the margins of an infinite chessboard so that each number is equal to the average argument number

The “extreme” rule in the form “Consider the most!” will help us solve this problem. Among the natural numbers written on the fields of the chessboard, the smallest ones inevitably exist. This is not difficult to verify. Let k be one of the given numbers. If among the numbers written on the board there is one, then it is the smallest number (there is no smallest number, less than one). If there is no one on the board, let's see if there is a two there. If there is, then it is the smallest number, but if not, then the bottom on the board is three, etc. In no more than k steps we will answer the smallest number m in this way. Consider the field P on which it is written. Let us denote the numbers written in adjacent fields by the letters a, b, c and d. By condition m=(a+b+c+d)/4. Hence a+b+c+d=4 m. Due to the choice of the number m, we have a≥m, b≥m, c≥m, d≥m. If at least one of these inequalities was strict, then we have a+b+c+d>4 m, which contradicts the conditions. So a=b=c=d=m.

Thus, if the number m is written on a certain field, then the number m is written on the neighboring fields. It follows that on the horizontal,

⟦folio 59⟧

containing the field $P$, only the numbers $m$ are written. But any vertical intersects this horizontal, that is, it contains the number $m$, and, therefore, all the numbers on the verticals are equal to $m$. This means that in general all the numbers on the board are equal to $m$.

Problem 4. On a square chessboard of size $n \times n$, the distances of the rooks are subject to the following condition: if a certain square is free, then the total number of rooks standing on the same horizontal line with this square and on the same vertical with it is not less than $n$. Prove that there are at least $n^2/2$ rooks on the board.

This task is difficult. However, skillful application of the rule of last resort can greatly facilitate the search for a solution. Namely, the rule of “extreme” suggests the idea of ​​​​distanced that of the $2n$ lines - verticals and horizontals - on which there are the fewest rooks. It can be said that there are several such lines, “equally loaded” with rooks. Then choose any of them. Let this line be a horizontal line (otherwise let’s put it on top of the board at $90^\circ$ - the verticals will become horizontal). The number of rooks on this rank is denoted by $k$. If $k \geq \frac{n}{2}$, then on each of the $n$ ranks there are at least $\frac{n}{2}$ rooks, and in total there are at least $\frac{n^2}{2}$ rooks on the board.

Let now $k < \frac{n}{2}$. At a distance of horizontals there are $n-k$ free squares, and each vertical that also passes through a free square contains, as can be seen from the condition, at least $n-k$ rooks, and all such verticals contain at least $(n-k)^2$ rooks. The remaining $k$ files contain at least $k$ rooks each (due to the choice of number $k$). There are at least $(n-k)^2+k^2$ rooks on the board. The remainder is to prove that $(n-k)^2+k^2 \geq \frac{n^2}{2}$. This can be done in different ways, here is one of them:

$$[(n-k)^2+k^2] - \frac{n^2}{2} = \frac{n^2}{2} - 2nk + 2k^2 = 2\left(\frac{n^2}{4} - nk + k^2\right) = 2\left(\frac{n}{2} - k\right)^2 \geq 0.$$

If $n$ is an even number, then we can find a distribution that satisfies the condition and contains exactly $\frac{n^2}{2}$ rooks - it is enough to place the rooks on all black squares (or on all white squares). If the number $n$ is odd, then $\frac{n^2}{2}$ rooks cannot be placed, observing the conditions of the problem, since the number $\frac{n^2}{2}$ is not an integer, but $\frac{n^2+1}{2}$ rooks can be placed: we place one rook on one of the corner squares, and the rest on squares of the same color.

The following problem is solved similarly.

Problem 5. Let $n^2$ non-negative numbers be arranged in the form of a table containing $n$ rows and $n$ columns. In this case, the following conditions are met: if a zero is written at some place in the table, then the sum of the numbers in the column and row containing this zero is not less than $n$. Prove that the sum of all $n^2$ numbers is at least $n^2/2$.

Problem 6. $n$ points are given on the plane. None of them lie on the same straight line. Prove that there exists a circle passing through the given points that does not contain an internal field or melon points.

Let's draw a circle through each three points. We get a non-negative circle (the non-negative ones can merge into one). It is required to prove that at least

⟦folio 60⟧

one of these circles does not contain any of these points inside itself. The “extreme” rule may suggest considering the largest circle (the circle with the largest radius), but in this case this does not give anything (it is enough to consider the configuration of the following points: 4 vertices of the square and its center; the smallest circle will be the one described around the square, but it does not satisfy the conditions). Let's do it differently. Let's try to solve a simpler problem, namely, we will look for a circle passing through two of these points and not containing the point inside itself. Let's measure the distances between each two given points and, using the “extreme” rule in the form “Consider the highest!”, take a pair of points $A$ and $B$, located at the furthest distance from each other. It is easy to verify that a circle constructed on the segment $AB$ as a diameter satisfies the condition: the remaining $(n-2)$ given points are distant from both $A$ and $B$ by at least $|AB|$, and therefore are located outside this circle. Now let's draw circles through the points $A$ and $B$ and through each of the remaining $(n-2)$ points. Among these circles, let’s choose the highest! This is what the rule tells us: “Consider the highest!” Let it be a circle passing through points $A$ and $B$ and a short point $C'$ of the “sickle” (Fig. 2), smaller than a circle passing through points $A$, $B$, $C$ (prove this yourself).

Problem 7. There are $n$ straight lines $(n \ge 3)$ on the plane. No two of them are parallel, and no two of them intersect at one point. These lines cut the plane into parts. Prove that no matter which of the $n$ straight lines we take, at least one of the parts of the plane direct to it is an overshoot.

Let $l_1$ be one of the given lines. Guided by the “extreme” rule, from the intersection points of the remaining lines, we choose the one that is at the greatest distance from the line $l_1$. Let at this point, denote it by the letter $P$, the lines $l_2$ and $l_3$ intersect. It is not difficult to prove (do it yourself) that the triangle formed by the lines $l_1$, $l_2$ and $l_3$ constitutes one part of the plane and therefore satisfies the condition.

Problem 8. Prove that there are no four natural numbers $x, y, z, u$ satisfying the equation $x^2 + y^2 = 3(z^2 + u^2)$.

Let us assume that such four exist. Let's consider the one for which the value $x^2 + y^2$ is minimal (if there are several four for which this value is the same and minimal, one of them is at a distance, any). Let it be four $a, b, c, d$. From equation $a^2 + b^2 = 3(c^2 + d^2)$ we see that $a^2 + b^2$ is a multiple of trem. But it is easy to prove that $a^2 + b^2$ is divisible by three if and only if $a$ and $b$ are divisible by three, because the square of a number that is not divisible by three gives a remainder of one when divided by three.

⟦folio 61⟧

Therefore, $a=3m, b=3n$, whence
$$a^2+b^2=9m^2+9n^2=3(c^2+d^2).$$
Reducing the last equality by 3, we get:
$$c^2+d^2=3(m^2+n^2).$$
We have found a quadruple of numbers $c, d, m, n$ that satisfies this equation, and for this quadruple
$$c^2+d^2<a^2+b^2,$$
and this is impossible due to the choice of the quadruple $a, b, c, d$.

Problem 9. There are $n$ lines ($n \ge 3$) on the plane. Any two lines intersect and through what point of intersection at least three of these lines pass. Prove that all lines intersect at one point.

Let $M$ be one of the points of intersection of the lines. Let's say she's not the only one. Then there is a line $l$ of the given system that does not pass through $M$. The set of points of intersection of lines not lying on $l$ is non-empty - it contains, for example, the point $M$. Unwind the point of this set that is close to $l$ (and if there are several points located at a minimum distance from $l$, then choose one of them, any one), and get a contradiction.

Here is another similar task.

Problem 10. $n$ points ($n \ge 3$) are given on the plane. It is known that on every line passing through 2 given points there is at least one more of the given points. Prove that all $n$ points of the model lie on the same line.

A development of the “extreme” rules is the “arrangement rule,” which sounds like this: “Arrange the elements of the set under study in ascending or descending order (or some other way)!”

Problem 11. Seven mushroom pickers collected 100 mushrooms together, and the two below did not collect the same number of mushrooms. Prove that there are three mushroom pickers who have collected at least 50 mushrooms together.

Let’s create a “leadership table”, placing mushroom pickers in it in descending order of the number of mushrooms collected. It is clear that the mushroom pickers who took the first 3 places should be considered - they collected more mushrooms than any other three. Let's try to prove that they collected at least 50 mushrooms. If the mushroom picker who took 3rd place collected 16 mushrooms or more, then in 2nd place is the mushroom picker who collected at least 17 mushrooms, and in first place is at least 18 mushrooms. Together they collected at least 16+17+18=51 mushrooms. If the mushroom picker who took 3rd place collected no more than 15 mushrooms, then the mushroom pickers who took places from 4th to 7th collected no more than 14+13+12+11=50 mushrooms. In this case, at least 50 mushrooms remain for the top three.
