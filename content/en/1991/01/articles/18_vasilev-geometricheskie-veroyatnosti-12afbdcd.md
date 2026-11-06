---
id: 1991-1-vasilev-geometricheskie-veroyatnosti-12afbdcd
issue: kvant_1991_1
year: 1991
number: "1"
title: Geometric probabilities
authors:
  - Васильев Н. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 49
page_last: 54
page_labels: 47-52
lang: en
source: kvant_digital
extraction: vision
content_sha256: 91494c88f7834bab8d2e0b7c775fc83f970366365e9d574056c3c67ce20ecfdd
prompt_sha256: draft-1
translated_from: content/ru/1991/01/articles/18_vasilev-geometricheskie-veroyatnosti-12afbdcd.md
source_content_sha256: 013ea86c3d5467df1f0f3b53adf98eaa0c2b296c1c11f842701fda64c8dd6445
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 47⟧

---
running_head:
folio:
---

Mathematical circles

Geometric probabilities

Candidate of Physical and Mathematical Sciences
N. VASILBEV

In this article, we will not be concerned with defining the basic concepts of probability theory, but will get acquainted with some problems where we can calculate the probabilities of a symmetry message, as well as a visual representation of its own using coordinates on a plane.

In this case, we will deal not only with problems where there is a finite number of equally possible options, but also with those where there are an infinite number of options. Here are two of them.

Problem about the meeting. The two Prigels agreed to meet on Mayakovsky Square from 12 to 13 hours. Each

One comes at some random moment in time, waits 15 minutes for the other and leaves. What is the probability that they will meet?

Problem about an acute triangle. Three points are randomly selected on the circle. What is the probability that a triangle with vertices at these points is acute?

But we will still teach from simpler, more finite examples.

Throwing the dice

The most convenient tool for the first acquaintance with probabilities is a dice: a cube whose faces are numbered 1, 2, ..., 6.

Since the die is perfectly symmetrical, we consider all six possible options to have the same probability. Let's say the probability of rolling a six is ​​1/6, the probability that a number not less than 3 is rolled is 4/6=2/3, the probability that an odd number is rolled

⟦folio 48⟧

---
running_head:
folio:
---

kov, is equal to 1/2. (Compliance with the society of “favorable outcomes” - shown in red in Figures 1 a, 6, e.)

If you don’t have a dice at hand, you can just as easily roll hexagonal pencils on the table, with the numbers 1, 2, ..., 6 written on the sides. It’s easy to imagine pencils not with 6, but with any number n of side edges.

So, the path we have is a tool that provides n equally possible options. By definition, we assume that the probability of each of these options being realized is equal to 1/n, and the probability of each property A, consisting of k options, is equal to k/n.

With n=6, of course, it is easy to simply list all the options, depicting them on figure. But when the number of options n is large, some rules for calculating probability come to the rescue.

We will denote the probability of owning A by p(A). Our meeting is simply a certain subset of the set E of all possible options, with p(E)=1. For a thrown dice, the set E consists of six elements 1, 2, ..., 6. The simplest relationships between probabilities arise from the relationship between the set, or more precisely, the number of elements in them.

The probability of a property $\bar{A}$ complementary to A (it includes all elements of E not included in A) is equal to

$$p(\bar{A}) = 1 - p(A).$$

(1)

For example, if A consists of numbers from 1 to 6 divisible by 3, then $\bar{A}$ is a number not divisible by 3; $p(A) = 1/3$, $p(\bar{A}) = 1 - 1/3 = 2/3$ (Fig. 1, 2).

Union $A \cup B$ is an event consisting in the fact that at least one of two events occurred: A or B. If events A and B are incompatible, that is, two sets A and B do not intersect, then

$$p(A \cup B) = p(A) + p(B).$$

(2)

If events A and B are compatible, that is, there is a non-empty intersection AB, then

$$p(A \cup B) = p(A) + p(B) - p(AB).$$

(3)

(The intersection of two sets A and B - an event consisting in the fact that A and B are performed simultaneously - we denote, as is customary in probability theory, simply AB.)

Repeated tests

Let's imagine that the dice were thrown twice (or that the dice were thrown at once); these are two independent tests.

Problem 1. What is the probability that on the first roll you will get at least 5 points, and on the second roll you will get at least 4?

Now the set E is the set of all pairs (x, y), where x and y are numbers from 1 to 6 (x means the number of points rolled on the first die, y on the second). All pairs (x, y) are equally probable, their number is 6·6=36. It is convenient to represent them in the form of a 6x6 square: a cell with coordinates x and y represents a pair (x, y) (Fig. 2). From them it is necessary to select those cells that satisfy the conditions of the problem: $x \leq 5$, $y \leq 4$. They will fill a straight line of 2x3 cells. So, among 6 6 pairs, 2 3 are chosen, so the desired probability is equal to

$$\frac{2 \cdot 3}{6 \cdot 6} = \frac{6}{36} = \frac{1}{6}.$$

In general, if event A is determined by the result of the first trial, and B - by the second trial (that is, A is a certain set of columns)

⟦folio 49⟧

---
running_head:
folio:
---

and $B$ are some set of strings),
then the probability of simultaneous execution of $A$ and $B$ is equal to
$$p(AB) = p(A) \cdot p(B).$$
In this case, the events $A$ and $B$ are called independent. The product rule (4) can also be used for a large number of independent trials. For example, the probability of getting a five or a six on each of three dice rolls is $(1/3)^3 = 1/27$.

Let us now consider two examples where the child also deals with two trials, i.e. $E$ is a set of pairs $(x, y)$, but the event of interest to us depends on $x$ and $y$ in a more complex way, so that the “independence” condition is no longer satisfied.

Problem 2. What is the probability that at least one of two dice rolls will result in at least 5 points?

The matching pairs are marked at figure 3, so the desired probability is $20/36 = 5/9$.

Note that we can think differently: find the additional probability that no more than 4 points will appear on both the first and second throws. This can already be done using the product rule: $(2/3) \times (2/3) = 4/9$, so the desired probability is equal to $1 - \frac{4}{9} = \frac{5}{9}$.

Problem 3. What is the probability that the number of points obtained in two tosses differs by no more than 1?

The required pairs are marked on figure 4, these are 6 cells along the diagonal $x=y$ and 5 on two adjacent parallel lines. The required probability is $16/36 = 4/9$.

Random numbers and points:
uniform distribution

Now we will talk about random points on a segment, on a circle, in a square... How are probabilities determined in this case? What “events” can be considered?

Let's roll round pencils on the table - a cylinder. Let its surface be yellow, but some strip (or several strips) of width $\alpha$ are covered in red (Fig. 5); What is the probability that the pencils will be left on the red line rather than the yellow line? (Here $\alpha$ is the angle being changed, say, in degrees.)

Let's imagine a similar problem about pencils with a large number of faces $n$, of which $k$ are covered in red. Then the desired probability will be equal to the ratio $k/n$. For a round pencil, the set of “elementary events” $E$ is a circle, and the probability of each individual element - the probability of remaining on one specific line - is equal to 0; but the probability of the event “stopping on one of the red lines” is naturally considered equal to the ratio $\alpha/360^\circ$.

In the same way, speaking about a random point on a segment (or on a circle) of length $L$, we will assume that the probability of its falling into any segment

⟦folio 50⟧

---
running_head:
folio:
---

The arc (or arc) of length $d$ is equal to $d/L$. In accordance with rule (1), we also assume that the probability of falling into one of the given (non-intersecting) segments of total length $d$ is equal to $d/L$. For example, the probability that the first digit after the decimal point of a random number on the interval [0; 1] is a prime number, i.e. one of the digits 2, 3, 5 and 7 (Fig. 6), equals $4/10 = 2/5$.

In the same way, when talking about a random point in a square or other figure of area $S$, we will assume that the probability of its occurrence in each region of area $s$ is equal to $s/S$. Note that rules (1), (2) and (3) are satisfied for both the lengths on the segment and the area of ​​the figure.

It is remarkable that, choosing independently of each other two numbers $x$ and $y$ on the interval [0; 1], we can assume that $(x, y)$ are the coordinates of a random point in a unit square: by analogy with the product formula (4), the probability of a point $(x, y)$ falling into a rectangle from the side $a$ and $b$, parallel to the axes $Ox$ and $Oy$, is equal to the product $ab$, i.e. the area of this rectangular.

For example, the probability that a random number chosen on the interval [0; 1], located at a distance of no more than 0.1 from the middle of the segment, is equal to 0.2 (such points cover the segment from 0.4 to 0.6). If $x$ and $y$ are two random numbers on the interval [0; 1], the probability that both of them are no more than 0.1 away from the middle is equal to $0,2^2 = 0,04$, and the probability that at least one of them is no more than 0.1 away from the middle is 0.36 (Fig. 7); this probability can be found by adding up the areas of the rectangles that make up the “cross”, or you can, by moving to “additional events”, using the formula $(1 - 0,8^2)$.

Now we can solve the meeting problem formed at the beginning of the article. Let's clarify it as follows. We will assume that each of the friends arrives at some random moment chosen on the interval [0; 45] (during the first 45 minutes of the conditional hour) waits for another 15 minutes; Thus, they will meet if the difference between their moments $x$ and $y$ (modulo) does not exceed 15.

Let us depict on the square $0 \leq x \leq 45$, $0 \leq y \leq 45$ the set of points $(x, y)$, in which $|x - y| \leq 15$ - it is bounded by straight lines $y - x = 15$ and $y - x = -15$, parallel to the diagonal $x = y$ (Fig. 8). The area of ​​this set is equal to $45^2 - 30^2$ (the two white triangles together form a square with side 30), and the desired probability is equal to its ratio to the area of ​​the entire square $45 \times 45$:

$$1 - \frac{30^2}{45^2} = 1 - \left(\frac{2}{3}\right)^2 = \frac{5}{9}.$$

Let's solve another problem about the random point $(x, y)$.

Problem 4. Find the probability $p = p(a)$ that the sum $x + y$, where $x, y$ are random numbers on the interval [0; 1], greater than the given number $a$.

The equation $x + y = a$ defines a line parallel to the diagonal $x + y = 1$ of the square. The required probability is the area of ​​the part of the square lying above this line. (For $a > 1$ it is a triangle, for $a < 1$ it is a heel, and it is easier to calculate the additional area.) The answer is written as follows:

$$p = \begin{cases} (2 - a)^2 / 2 \text{ при } a \geq 1, \\ 1 - a^2 / 2 \text{ при } a \leq 1. \end{cases}$$

⟦folio 51⟧

---
running_head:
folio:
---

Symmetry messages.
Points on a circle

Note that for $a=1$ in the previous problem the answer is $p=1/2$.
(The correspondence points $(x, y)$ lie above the diagonal.) It can be guessed immediately, without the figure pattern on the square: if $x, y$ are numbers randomly chosen on the interval [0; 1], then condition $x+y \leq 1$ can be written as $x \leq 1-y$ and read as follows: “x is closer to 0 than $y$ to 1.” It is clear that the additional condition is obtained simply by replacing $x$ with $y$ and has the same plausibility: after all, the roles of $x$ and $y$, as well as the ends of the segment of a perfect equilateral line.

Here's another example.

Problem 5. On the interval [0; 1] case, three numbers are selected. What is the probability that $a$ chosen as the last number is the most? b) are the numbers in ascending order?

Here, decide not about two, but about three numbers $x, y, z$. The triples $(x, y, z)$ could be considered as the coordinates of a point in a cube and the volumes of the required sets could be calculated. But this is not needed. After all, it is clear that all 6 options for the arrangement of three numbers: $x<y<z, y<x<z, x<z<y, y<z<x, z<x<y, z<y<x$ are completely equal in probability, and have the same probability of 1/6. Thus, the answer to question 6) is 1/6, and to question a) 1/3 (the first two options answer it).

Let us now solve the problem of an acute triangle, formulated at the beginning of the article. It is clear that with any rotation of the circle, the probabilities of events and the conditions of “sharpness” are preserved; so we can assume that one of the three selected vertices $A, B, C$—say, $C$—is fixed, and the other two are already chosen at random. We will set their positions of magnitude each $CA=\alpha, CB=\beta$, counting counterclockwise. Let's change the angles in radians, then the pair $(\alpha, \beta)$ is a point in the square $0<\alpha<2\pi, 0<\beta<2\pi$. According to the theorem that the magnitude of the inscribed angle changes by the positive arc between its sides, the angles of the triangle $ABC$ are equal to $\pi-\beta/2, \alpha/2$ and $(\beta-\alpha)/2$ (we assume that $\beta>\alpha$ (Fig. 9); the case $\alpha>\beta$ is completely similar - $\alpha$ and $\beta$ change roles). The points $(\alpha, \beta)$ in triangle $\alpha<\beta<2\pi$, for which all three angles $A, B, C$ are less than $\pi/2$, i.e. $\beta>\pi, \alpha<\pi$ and $\beta-\alpha<\pi$, fill the interior of the smaller triangle, formed by the midlines of the larger one (Fig. 10). The situation in the lower triangle $\beta<\alpha<2\pi$ is symmetrical with respect to the diagonal $\alpha=\beta$ of the square. Therefore, the required confidence is 1/4.

This problem has other amazing and beautiful solutions that allow you to solve a similar problem for the $n$ point (see problem 9 at the end); we learned it from the physicist V.V. Fok and the mathematician Yu.V. Chekanov.

We will look for additional confidence that the three points $A, B, C$ are the vertices of an obtuse triangle.

For each point $M$ of the circle, consider the point $M'$ diametrically opposite to it and obtain a circle for which $M'$ serves as the midpoint of the arc. The triple $A, B, C$ is “obtuse” if and only if the semicircles corresponding to the points $A, B$ and $C$ are re-

⟦folio 52⟧

---
running_head:
folio:
---

cut along a certain sector (Fig. 11). (For each OD radius in the selected sector, all angles DOA, DOB, DOC are tula; such an OD radius exists if A, B, C lie on the same semicircle or, equivalently, form an “obtuse” triangle.)

We will select random points in two stages. First, we randomly mark three pairs of diametrically opposite points and draw for each pair the diameter with respect to which it is symmetrical. And then in each pair we independently select (with a probability of 1/2) one of the points. Let us prove that from 8 options for choosing points, exactly 6 will result in an “obtuse” track A, B, C. In fact, three diameters divide the circle into 6 sectors, and each sector can be obtained as the intersection of three specific semicircles corresponding to a certain choice of points A, B, C. So, the probability of obtaining an “obtuse” track is equal to 6/8 = 3/4, which means the additional probability is equal to 1/4.

Buffon's problem

We are accustomed to the fact that confidence is always a fraction with small integers in the numerator and denominator. But in conclusion, we present two problems where the number π appears in the answer. The first one is almost very inda.

Problem 6. A dot is randomly thrown onto a large sheet of checkered paper on the side of cell 1. What is the probability that it will be on

Fig. 11.

distance less than 1/2 from the center of some cell?

It is enough to consider one cell. Points located at a distance of no more than 1/2 from its center fill a circle of area π/4. This is the answer: the required probability (the ratio of the area of ​​the circle to the area of ​​the cell) is equal to π/4.

Problem 7 (Buffon's problem on the needle)

THE PLANE IS LINED INTO STRIPES OF WIDTH 1. A whole (segment) of length 1 is thrown onto it. What is the probability that the whole will cross one of the lines?

This problem has a surprising answer: 2/π. Where does π come from if in the conditions there is no talk of either a circle or distances?

Let us briefly outline one of the solutions. The position of the needle (if we don’t talk about mixing it along the lines, which doesn’t really play a role) is determined by two parameters: the distance y of the end of the needle from the upper edge of the strip in which it hit 0<y<1, and the angle α of the needle with the straight line perpendicular to the lines (Fig. 12, a). We can assume, according to symmetry messages, that α<π/2. The condition under which the needle crosses the edge of the strip: y<cos α. So, among the points (α, y) in the straight line 0<α<π/2, 0<y<1 we must select the lines y=cos α (Fig. 12, b) lying below and find the ratio of the area S of the resulting figure to the area of ​​the straight line (π/2). For those who are familiar with the understandable interval (they study it in high school), this problem is not difficult: ∫_{0}^{\pi/2} cos α dα=1. But you can get the answer based on an analogy from mechanics. Let's imagine a point, uniformly with unit speed, passing arcs AB in 1/4 circle of radius 1 (Fig. 12, s). When point M is at position α on the arc (0<α<π/2), the speed of its projection M' onto the radius OB is exactly cos α. So figure 12, b is a graph of the speed of point M', and the area S under the graph is equal to the projection of the path, i.e. S=OB=1.
