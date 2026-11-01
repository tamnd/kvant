---
id: 1988-9-zadachi-b723210f
issue: kvant_1988_9
year: 1988
number: "9"
title: Tasks
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 53
page_last: 61
page_labels: 51, 53, 54, 56, 59
tag: RDP6
lang: en
source: kvant_digital
extraction: vision
content_sha256: 17037df7ce4b691f6e6520ef568c01c2fff87557d66db8104c2b9adb6440b905
prompt_sha256: draft-1
translated_from: content/ru/1988/09/articles/12_zadachi-b723210f.md
source_content_sha256: 7c91c7da2a6549b92936b354b5676d687de2ae8ec15352bcecd84daca1c1f459
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

Tasks

1. Is it possible to arrange ten different natural numbers in the circles of the star on figure so that the sums of the four numbers along each of the heels of the line are odd?

2. Six passengers on a bus without a conductor must pay 5 kopecks for tickets. But they only have coins of 10, 15 and 20 kopecks. Nevertheless, the passengers coped with the task. Show that the total number of coins they have is not less in everything. Will passengers be able to solve this problem if they have a total of eight coins?

3. Two consecutive two-digit numbers are added and the digits in their sum are rearranged. The result is the larger of the numbers being added. What numbers add up?

4. Determine the numerical value of the word TRANSPORTATION if identical letters are replaced by identical numbers, respectively, and different ones by different ones, and in such a way that the inequalities indicated at figure are satisfied.

5. Two parallelograms - red and blue - have a common vertex and one more vertex of each on the side of the other (see figure). Show that their areas are equal.

These tasks were proposed to us by: A. M. Domashenko, N. B. Vasilyev, Zhora Golovatenko from Moscow, M. P. Mochalov and V. V. Proizvolov.

⟦folio 53⟧

RULE OF EXTREME

Candidate of Physical and Mathematical Sciences
A. L. ROSENTHAL

If you want to learn how to solve mathematical problems, you need to try to master more or less general approaches, techniques and methods of mathematical reasoning. Let's consider one very general approach, which we will call *the rule of last resort*.

The rule of the extreme can be briefly expressed by the words “Consider the extreme!” This rule is a simple recommendation to consider an object that has some extreme, or, as mathematicians say, extreme properties. If the problem concerns a set of points on a line, then the rule “Consider the extreme!” advises us to focus our attention on the most extreme point of the set (the most left or the most right). If the problem involves a certain set of numbers, then the rule of extremes recommends considering the most or most of these numbers. Here are some examples.

Task 1. A certain set of points M is given on the plane such that each point from M is the midpoint of a segment connecting any pair of points in the same set M. Prove that the set M contains an infinite set of points.

It often happens that the keys to solving a problem are found by solving a simpler, similar problem. Therefore, before solving this problem, let's try to solve the following problem.

Task 2. A set of points M is given on a line such that each point from M is the midpoint of a segment connecting two other points from M. Prove that the set M is infinite.

Let us assume that the set M is finite. Let's apply the rule of last resort:

This article was first published in «Kvant» No. 8, 1976. (Editor's note)

if the set M is finite, then among its points there are extreme ones - the leftmost and the rightmost. Let's consider one of them, for example the leftmost one; let us denote it by the letter A. Point A is an extreme point and therefore cannot lie inside the segment connecting two other points of the set M; this means that it does not belong to M. The resulting contradiction proves that the set M cannot be finite.

Let us present another solution to this problem using the rule of extremes. Let us again assume that the set M is finite and consider the lengths of the segments connecting points in M. This set of numbers is finite. Let’s apply our rule to it in the form “Consider the most!” — consider the segment BC that is the longest. It is clear that there is no point from M outside the segment BC, otherwise there would be segments with large lengths. Thus, all points of the set M lie on the segment BC and, therefore, neither B nor C satisfy the conditions, that is, they do not belong to the set M. A contradiction.

Let us now return to Problem 1. Let us assume that the set M is finite. Let's apply the rule of last resort again. To do this, we fix the position of the plane and consider the leftmost point of the set M, and if there are several “leftmost” points, then we take the lowest of them. It is easy to see that this point, let us denote it by A, cannot lie inside a segment connecting two points of the set M. Indeed, if such a segment existed, then one of its ends would be located either to the left of point A, or on the same vertical line with A, but below it. Neither one nor the other can exist due to the choice of point A.

Here, as in Problem 2, there is also a solution based on considering pairwise distances between points of the set M. If the set M is finite, then there are a finite number of pairwise distances, and among

⟦folio 54⟧

of them, guided by the rule of extremes, you can find the most.

Let this be a consideration between points A and B. But point B is the midpoint of a certain segment CD, the ends of which, by condition, belong to the set M (Fig. 1). Then it is easy to prove that either AD or AC is greater than AB (do it yourself, take advantage of the fact that the median m drawn to one of the sides of the triangle is less than half the sum of the other two sides).

Problem 3. Natural numbers are written on the fields of an infinite chessboard so that each number is equal to the average of the arithmetic sum of neighboring numbers - top, bottom, right and left. Prove that all the numbers on the board are equal.

The rule of extremes in the form “Consider the name!” will help us solve this problem. Among the natural numbers written on the fields of the chessboard, a name inevitably exists. This is not difficult to verify. Let k be one of the given numbers. If among the numbers written on the board there is a unit, then it is the smallest number (there are no natural numbers less than ones). If there is no one on the board, let's see if there is a two there. If there is, then it is the smallest number, but if not, then we place a trey on the board, etc. In no more than k steps we will thus find the name number m.

Consider the field P on which it is written. Let us denote the numbers written in adjacent fields by the letters a, b, c and d. By condition m=(a+b+c+d)/4. Hence a+b+c+d=4m. Due to the choice of the number m, we have a≥m, b≥m, c≥m, d≥m. If at least one of these inequalities were constructed, then we have a+b+c+d>4m, which contradicts the conditions. So a=b=c=d=m.

Thus, if the number m is written on a certain field, then the number m is written on the neighboring fields. It follows that on the horizontal line containing the field P, only the numbers m are written. But any vertical intersects this horizontal, i.e. it contains the number m, and, therefore, all the numbers on the verticals are equal to m. Therefore, in general, all the numbers on the board are equal to m.

Problem 4. On a square chessboard of size n×n, rooks are placed in compliance with the following condition: if a certain square is free, then the total number of rooks standing on the same horizontal line with this field and on the same vertical with it is at least n. Prove that there are at least $\frac{n^2}{2}$ rooks on the board.

This task is difficult. However, the ability to apply the rules of extremes may exist as a Japanese solution. Namely, it is correct to call the thought to distance the one from the linear board - vertical and horizontal - on which there are fewer rooks. It may happen that there are several such lines, “equally loaded” with rooks. Then choose any of them. Let this line be horizontal (otherwise, rotate the board 90° and the verticals will become horizontal). We denote the number of rooks on this rank by k. If k≥$\frac{n}{2}$, then on each of the n ranks there are at least $\frac{n}{2}$ rooks, and in total there are at least $\frac{n^2}{2}$ rooks on the board.

Let now k<$\frac{n}{2}$. There are n-k free fields on the horizontal line under consideration, and each vertical passing through such a free field

⟦folio 56⟧

a circle passing through points A, B, C. It is the desired one, because any circle drawn through points A and B and some point C' of the “sickle” (Fig. 2) is smaller than the circle passing through points A, B, C (prove this yourself).

Problem 7. There are n straight lines (n≥3) on the plane. No two of them are parallel, No three intersect at one point. These straight lines cut the plane into parts. Prove that no matter which of the n straight lines we take, at least one of the parts of the plane adjacent to it is a triangle.

Let $l_1$ be one of the data points. Guided by the rule of extremes, from all the points of intersection of the remaining lines, we choose the one that is at the shortest distance from the line $l_1$. Let the lines $l_2$ and $l_3$ intersect at this point, let us denote it by the letter P. It is not difficult to prove (do it yourself) that the triangle formed by the lines $l_1$, $l_2$ and $l_3$ constitutes one part of the plane and, therefore, satisfies the conditions of the problem.

Problem 8. Prove that there is no quadruple of natural numbers x, y, z, u, satisfying the numbers $x^2+y^2=3(z^2+u^2)$.

Let us assume that such fours exist. Let's consider the one for which the value $x^2+y^2$ is minimal (if there are several quadruples for which this value is the same and minimal, let's consider one of them, any one). Let it be the four a, b, c, d. From equation $a^2+b^2=3(c^2+d^2)$ it is clear that $a^2+b^2$ is a multiple of trem. But it is easy to prove that $a^2+b^2$ is divisible by three if and only if both a and b are divisible by three, because the square of a number that is not divided by three gives a remainder of one when divided by three.

Therefore, $a=3m$, $b=3n$, whence
$$a^2+b^2=9m^2+9n^2=3(c^2+d^2).$$
Reducing the last equality by 3, we get:
$$c^2+d^2=3(m^2+n^2).$$
We found a quadruple of numbers c, d, m, n, satisfying the number of the given equation
nude, and for this foursome
$$c^2+d^2<a^2+b^2,$$
and this is impossible due to the choice of the four a, b, c, d.

Problem 9. There are n straight lines (n≥3) on the plane. Any two lines intersect and at least three of the given lines pass through each intersection point. Prove that all lines intersect at one point.

Let M be one of the points of intersection of the lines. Let's say she's not the only one. Then there is a line l of the given system that does not pass through M. The set of points of intersection of lines that do not lie on l is non-empty - it contains, for example, the point M. Consider the point of this set that is close to l (and if there are several points located at the minimum distance from l, then choose one of them, any), and get a contradiction.

Here is another similar task.

Problem 10. There are n points (n≥3) on the plane. It is known that on any straight line passing through 2 given points there is at least one more of these points. Prove that then all n points lie on the same line.

A development of the rule of extremes is the “rule of arrangement,” which sounds like this: “The arrangement of the elements of the set under study in some order: returning, descending, or some other!”

Problem 11. Seven mushroom pickers collected 100 mushrooms together, and no two collected the same number of mushrooms. Prove that there are mushroom pickers who have collected at least 50 mushrooms together.

Let’s create an “intersection table”, placing mushroom pickers in it in descending order of the number of mushrooms collected. It is clear that the mushroom pickers who took the first 3 places should be considered - they collected more mushrooms than any other three. Let's try to prove that they collected at least 50 mushrooms. If the mushroom picker who took 3rd place collected 16 mushrooms

⟦folio 59⟧

the position and speed of the body at some point in time and the nature of its movement are known; it is necessary to determine the position and speed of this body at some other moment in time. This is the key phrase! It “encrypts” practically everything cinematika, but also hides many “pitfalls”.

Let's start with the words: “the position and speed of the body at some point in time are known.” These words mean, firstly, that the report body and coordinate system are selected and, secondly, that the start of the time report is selected. In other words, the selected reporting system. And this is the most important element in describing any physical situation. After all, in order to watch a film, for example, you need a screen on which all the events of the film will unfold. Likewise, the reporting system is a kind of screen for physical events.

Let's move on. We have already used the words “character of movement” several times. As you know, the position of the body at any moment of time $t$ is given by its coordinates $x, y, z$, and the change in coordinates is the displacement vector of the body $\vec{s}$. The words “the nature of the movement is known” mean that the form of the function $\vec{s}(t)$ or, what is the same, the form of the function $x(t), y(t)$ and $z(t)$ is known.

There is a huge variety of types of movement in nature. Simple movements are described by simple functions: rectilinear uniform movement - by a linear function $x=x_0+vt$, or $\vec{s}(t)=\vec{v}t$; rectilinear equilibrium - by a square function $x=x_0+v_0t+at^2/2$, or $\vec{s}(t)=\vec{v}_0t+\vec{a}t^2/2$; oscillatory - harmonic function of sine (or cosine) $x=x_m\sin \omega t$, etc. And try to follow some point on the rim of a rolling wheel or a hypnast jumping from the crossbar, and you will see that much more complex functions are used to describe such movements. But in principle, this can always be done, and, what is very important, the method for solving the main cinematic problem is universal and does not depend on the type of movement.

Finally, the last phrase in the formulation of the problem: “to determine the position and speed of the body at some point in time.” The main problem here is that this final point in time is usually not clearly specified. It is very rarely stated directly at what exact moment in time you need to find the position and velocity of the body. In most cases, this moment is specified by some additional condition. (So, for example, in the case of Guidon’s single combat with the kite, the final moment of time is determined by the “meeting” of the arrow with the kite.) Using this condition, you need to find the moment of time at which it is fulfilled, and then substitute this time into the expressions for the displacement (coordinates) and speed of the body.

Having “deciphered” the content of the main problem of cinematography in this way, we actually formulated the algorithm for solving it:

1) Select a reporting system (figure is always preferred).
2) Determine the nature of the movement.
3) Write down the displacement and speed (in projections onto the corresponding coordinate axes) as functions of time; If there are many moving bodies in the task, then the equation of motion must be written down for each body separately.
4) Using additional information, determine the final point in time. Substitute this time into the equation for the quantities of interest to us - and the task is to solve.

Now let's return to Pushkin. Let Guidon count a little before releasing the arrow (and at the same time, let us do the same).

The initial information that Guidon has looks like this: the kite is directly above the princess at a height of $H$ (remember - “the swan is fighting, the kite is rushing over her”) and dives at her with a stone. Let's assume that the initial speed of the kite is zero, Guidon is on one cinematic, it depends on the type of movement.
