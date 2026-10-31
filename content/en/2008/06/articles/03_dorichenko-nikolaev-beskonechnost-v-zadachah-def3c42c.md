---
id: 2008-6-dorichenko-nikolaev-beskonechnost-v-zadachah-def3c42c
issue: kvant_2008_6
year: 2008
number: "6"
title: Infinity in tasks
authors:
  - Дориченко С. А.
  - Николаев А.
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 34
page_last: 35
page_labels: "32"
tag: S4XL
lang: en
source: kvant_digital
extraction: native
content_sha256: 7edf293b764fe569f2aa541047d40d1b90fc45d19a5489206fb7309eb3de34f0
prompt_sha256: draft-1
translated_from: content/ru/2008/06/articles/03_dorichenko-nikolaev-beskonechnost-v-zadachah-def3c42c.md
source_content_sha256: ca947145897188eafbbf473130780494d74bcced8583527cc753ab01cb7760f8
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

Infinity in tasks

Each problem in this kaleidoscope deals in one way or another with something infinite (for example, a plane or a decimal fraction). Of course, you can come up with as many problems as you like that involve something infinite. We will limit ourselves to a very small number of topics, and in each we will give several beautiful examples.

Figures on a plane

1. Is it possible to cover a plane with an infinite number of squares, among which exactly two are identical? Squares cannot overlap.

Answer: yes, you can. Let's draw a square with side 1, add a square with side 1 to it on the left to get a rectangle 1 × 2, add a square with side 2 to this rectangle from below to get a rectangle 2 × 3, put a square with side 3 on the right and so on: we will fill the plane “in a spiral,” each time adding a square to the existing figure so that its side coincides with one of the sides of the figure. It is clear that any point on the plane will be covered by one of the squares. By the way, the lengths of the sides of these squares form the Fibonacci sequence 1, 1, 2, 3, 5, 8, 13, ... - it is described in detail in this issue of the magazine in the “Mathematics Circle” section. Consider a more difficult question: is it possible to cover a plane with an infinite number of non-overlapping squares, none of which are identical?

2. Is it possible to cover a plane with a finite number of a) interiors of parabolas; b) interiors of angles whose sum is less than 360 o?

Let us present the solution to point a). Answer: no. Let us assume that such parabolas exist. Note that the interior of a parabola intersects with a line along an infinite piece only if the line is parallel to the axis of the parabola. Let's draw a straight line that is not parallel to any of the axes of our parabolas (this is possible, since there are a finite number of them). Then each parabola will intersect this line along a segment, and since there will be a finite number of segments, even this line will not be covered.

Infinite graphs 3. Let it be known that humanity is immortal, and every person is mortal. The number of people in each generation is finite. Prove that there is an infinite chain of men starting with Adam (each next in the chain is the son of the previous one).

Let's build a picture like this. On the first floor we will place one point - it will represent Adam. We'll let you out of it

⟦column⟧

as many arrows as Adam had sons to the second floor (the ends of the arrows correspond to the sons of Adam). From each point—a person on the second floor—we will shoot arrows to the third floor (the arrows again correspond to the sons), and so on. We get a system of points and arrows from an infinite number of floors (since humanity is immortal), but on each floor there will be a finite number of points. It is clear that there is an infinite number of finite paths following arrows, starting at the first floor point. We must prove that there is an infinite path. We'll explain how to find it. The first point in it will be the first floor point. Since there are infinitely many paths leading from a point on the first floor, there is a point on the second floor through which there are infinitely many paths. This point will be the second on our journey. Let's consider all the paths passing through the selected two points - there are infinitely many of them, which means that on the third floor there is a point through which infinitely many of them pass. Let's choose her third. Each time we will be able to complete our path, increasing its length, and in the end we will get an endless path.

4. There is a language with a finite alphabet. A word in this language is any (finite or infinite) sequence of letters from the alphabet of this language. Some words (of finite length) in the language are obscene. Let's call a word absolutely decent if it contains no indecent subwords. It is known that there are absolutely decent words of any length. Prove that there is an infinitely long absolutely decent word.

Pursuit on the plane 5. The game takes place on the plane. Two players play: the first moves one wolf chip, the second moves 99 sheep chips. After the wolf's move, one of the sheep walks, then after the wolf's next move, one of the sheep walks again, etc. Both the wolf and the sheep move no more than one meter in any direction in one move. Is it true that for any initial position the wolf will catch at least one sheep (will end up at the same point with it)?

Answer: false. Let's draw 100 parallel lines on the plane so that the distance between adjacent lines is 3 meters. Let's place the sheep on different straight lines, each will then move only along its own straight line. Let's place the wolf on the hundredth straight line. Let us present an algorithm for the behavior of sheep, in which the distance from the wolf to any sheep before the wolf moves will always be more than a meter. If the distance from the wolf to each of the sheep is more than a meter, move any sheep (along its straight line) so that it moves away from the wolf. As soon as the wolf approaches one of the sheep at a distance of 1 meter or closer (there can be exactly one such sheep), we move the sheep along its straight line to one side by 1 meter so that the distance between it and the wolf becomes more than a meter.

⟦folio none⟧

6. The city is an endless checkered plane (lines are streets, squares are blocks). On one of the streets there is a policeman at the intersections every 100 blocks. There is a bandit somewhere in the city (his location is unknown, but he only moves along the streets). The goal of the police is to see the bandit. Does the police have an algorithm to surely achieve their goal? The maximum speeds of the police and the bandit are some finite, but unknown to us values ​​(the bandit’s speed may be greater than that of the police). The police can see along the streets in all directions for an infinite distance.

Let’s choose a coordinate system so that police officers stand on the street y = 0 at points (0; 0), (100; 0), (–100; 0), (200;0), (–200;0), etc. Let the policemen standing at points of the form (200k; 0), where $k = 0, \pm 1, \pm 2, K$, remain in place. Then the bandit will be inside a certain strip between the lines x = 200m and x = 200(m + 1); he will be able to move inside this strip, but will not be able to get out of it. Let the rest of the policemen (let's call them patrolmen) move along the street y = 0 in the direction of the point (0; 0) to the intersection closest to it, which none of the patrolmen has yet reached. Having reached the intersection (n; 0), the patrolman turns onto a perpendicular street and moves along it to point (n; n) and stops there. As a result, patrolmen will gradually occupy all intersections on the straight line y = x. Prove that by acting in this way, the police will be able to see the bandit after some time.

7*. In the city from the previous task, three policemen catch a thief (the location of the thief is unknown, but he only moves along the streets). The maximum speeds for the police and the thief are the same. A thief is considered caught if he happens to be on the same street as a policeman. How can the police catch a thief?

Infinite decimals

8. Prove that any real positive number can be represented as the sum of nine numbers, each of which consists of only the digits 0 and 8 in decimal form.

It's easy to represent any positive number as the sum of nine numbers, the notation of which consists of only zeros and ones (check). Now let's solve the original problem. Let us need to represent the number a. Let's first imagine the number a/8 as the sum of nine numbers, the entries of which consist only of zeros and ones, and then multiply each of these numbers by 8 - we get the required 9 numbers, the sum of which is equal to a.

9. Prove that in any infinite decimal fraction you can rearrange the digits in such a way that the resulting fraction becomes periodic (possibly with a pre-period).

If there are numbers in the notation of a fraction that appear in this notation a finite number of times, then we move them all to the beginning (we write them in a row immediately after the decimal point). The remaining numbers appear an infinite number of times. Let these be, for example, the numbers 2, 5, 7 and 8. Then you can move them sequentially to the beginning so that they go in the order 257825782578... The result is a periodic fraction.

Checkered Plane Robots A robot is a machine with a finite memory capable of executing a program of finite length. The robot has several flags. The robot can perform the following actions: – once in a cell, check whether there is a flag there; – move to one of the neighboring cells (on the plane - left, right, up, down); – check or uncheck the box where the robot is located. 10. A robot with two flags stands on one of the cells of an infinite checkered strip one cell wide. How should he proceed to bypass the entire strip, i.e. visit each of its cells at least once?

We place a flag in the cell, move to the left, and place a second flag in the cell. Next, we follow a very simple algorithm: move to the right until we reach the flag, remove the flag, move another cell to the right, put a flag and move left to the flag, move it one cell to the left and return to the beginning of the algorithm (move right to the flag, etc.).

11. How can a robot with four flags get around a checkered plane? Is it possible to get by with three checkboxes?

The algorithm “to go around the plane in a spiral”, alternating moves to the left, up, right and down, periodically increasing the length of the move by 1 cell, is not suitable: the robot will have to remember larger and larger numbers, and its memory is finite. Let's place four flags in the cells of the square 2 ѣ 2. Next we will “expand” the square, for example like this. We move the upper left flag to the left and up, go from this cell to the right, checking if there is a flag below us. If there is, we move it to the right and up, then from this cell we go down, checking if there is a flag to our left, and so on. As a result, we will go around the plane, moving “in a spiral.” It turns out that even three flags are enough (the hint is shown at figure).

12. Can a robot navigate a 3D checkered space with just three flags? 13. How can a robot bypass a checkered half-plane with only one flag? The boundary of the half-plane is a wall. Initially, the robot stands against the wall. The robot sees the wall when it gets close to it. 14. Two completely identical robots were landed on a plane. Each one has several checkboxes. The robot distinguishes its own flags from others. How can they meet? Their programs should be the same.

If the robots could have different programs, then organizing a meeting would be easy: one robot stands still, and the other walks around the plane using three flags. But the robots are made on the same assembly line, and their behavior programs are the same. Try to come up with a program that allows robots to meet using as few flags as possible.

⟦column⟧

The material was prepared by S. Dorichenko, A. Nikolaev
