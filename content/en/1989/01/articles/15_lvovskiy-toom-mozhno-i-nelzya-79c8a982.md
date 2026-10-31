---
id: 1989-1-lvovskiy-toom-mozhno-i-nelzya-79c8a982
issue: kvant_1989_1
year: 1989
number: "1"
title: It is possible and it is not possible
authors:
  - Львовский С. М.
  - Тоом А. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 54
page_last: 57
page_labels: 52-55
tag: ZKEY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 64e5f833ba5f18fb36a2f0eb4b4e8f575888e4bb99e9eb08c545fc4576abb5bb
prompt_sha256: draft-1
translated_from: content/ru/1989/01/articles/15_lvovskiy-toom-mozhno-i-nelzya-79c8a982.md
source_content_sha256: 9f503fe106f5e77a16a334c4ce3c86d3ca696edd4d9567a5cfaaba62fb0b0558
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

It is possible and it is not possible

Candidate of Physical and Mathematical Sciences
S. M. LVOVSKY,
Candidate of Physical and Mathematical Sciences
A. L. TOOM

School problem statements most often begin with words like “calculate” or “find.” However, in mathematics there are very often problems in which it is not necessary to calculate something, but to find out whether an object with a given property exists. The formulations of such problems usually begin with the words “is it possible...” or “does there exist...”. The answer to such questions must, of course, be justified. If we claim that something can be done, then it is enough to indicate a specific way to do it. If we claim that something cannot be done, then examples are no longer enough; we must come up with a proof. There is no general recipe for this type of evidence; in this article we will show you just some of the examples that can be used.

Here is the first example on the topic of “dos and don’ts.”

Task 1. For what natural numbers n is there a closed broken line of n links that intersects each of its links once? All intersections must be found inside the links, and not at the vertices; no three links should intersect at the same point.

Solution. First of all, we note that for some n such a broken line does not exist: for example, for n=1, n=2, n=3, n=4. On the other hand, for some n such a broken line can be found; for example, at figure 1 the required broken line is shown for n=6. Let us pay attention to the following properties of this broken line: its links form three pairs, and the links of each pair intersect with each other, and with other links

⟦folio 53⟧

do not intersect (at figure 1 each pair of links is drawn in a different color). This property follows from the very condition of the problem: if some broken line intersects each of its links once, then each link forms a pair with the link that intersects it. But in order for the links to be divided into pairs, their number must be even. So, we have proven that for odd $n$ the required broken line does not exist. It turns out that for all four, broken lines exist. Come up with a general way to construct such a broken line for every Thursday $n \geq 6$. figure 2 will help you with this.

Problem 2. Is there a natural number that, when multiplied by 2, becomes a square, and when multiplied by 4, becomes the fourth power of an integer?

Solution. Let's assume that such a number $m$ exists and factor it into prime factors. Actually, of its prime factors, we are only interested in twos; so we will write:

$$m = 2^k \cdot p,$$

where $p$ is odd. According to the first condition, the number

$$2m = 2^{k+1} \cdot p$$

the square of an integer, from which $k+1$ is even, and then $k$ is odd. According to the second condition, the number

$$4m = 2^{k+2} \cdot p$$

the fourth power of an integer, from which $k+2$ is divisible by 4. But if $k$ is odd, then $k+2$ is odd, and then cannot be divided by 4. The resulting contradiction shows that an exceptional number does not exist.

Fig. 1.

Problem 3. What is the maximum number of points that can be placed in a square on side 1 so that all distances between these points are at least 0.5? (“In a square》 means “inside or on the border of a square”).

This task is also one of the “can or can’t” tasks. Its solution must consist of two parts: proof that it is possible to arrange as many points as required, and that it is no longer possible to arrange more points. It is not difficult to understand how to arrange the ninth points in the required manner; put one point in the center of the square, four - at the vertices and four more - in the middle of the side (Fig. 3, a). The assumption arises that more than nine points cannot be positioned in the required manner. How is this proven? For example, this way of proof looks very attractive: consider the above distance of nine points (at the center, vertices and midpoints of the side) and then establish that another point added to these nine points will be at a distance of less than 0.5 from at least one of the first nine points. This statement is absolutely correct (for example, because circles of radius 0.5 with centers at the first nine points cover the entire square - Fig. 3, b), but, unfortunately, it does not provide a solution to our problem. In fact, where is the confidence that the only way to arrange the required nine points is figure 3, huh? What if nine points can be arranged somehow differently, so much so that ten more can be added to them?

⟦folio 54⟧

Fig. 3.

To prove that it is impossible to place more than nine points in a square in the required manner, use this technique. Divide our square into 9 equal squares with states of 1/3 (Fig. 4). If there are more than nine points in a large square, then at least two of them will fall into the same small square. The distance between any two points of a square obviously does not exceed the length of the diagonal of this square. But the diagonal of a square from side 1/3 is $\sqrt{2/3} \leq 0.5$. This means that it is impossible to arrange more than nine points in the required manner, and the answer to Problem 2 is nine points.

The consideration we used to solve Problem 2: “if more than 9 points are distributed over 9 squares, then at least two of these points will fall into one square” is often called the “Dirichlet principle” in honor of the late German mathematician P. G. Dirichlet (1805-1859).

In tasks 2 and 3, I prove the existence statement by constructing a specific example. In task 4 comes to act differently.

Problem 4. The sequence of numbers is constructed as follows. The first number in it is two. Each next number is equal to the sum of ten powers of the digits of the previous number. Prove that there are two identical numbers in this sequence.

Let's see what kind of numbers we get in this sequence. The second number is $2^{10}=1024$. The third number is $1^{10}+2^{10}+4^{10}=1+1024+1024^2=1049601$.

The fourth number is already so large that it becomes clear: “by hand” we will not find two identical numbers. Moreover, doubt arises whether it is even true that we are easy to prove? At first glance, the numbers are growing rapidly and no repeat is expected. However, let's not rush to conclusions; Instead of exact calculations of our numbers, let's look at how many digits there can be in their notation.

The fourth number is $1^{10}+4^{10}+9^{10}+6^{10}+1^{10}$, which is less than $10^{10}+10^{10}+10^{10}+10^{10}=5 \cdot 10^{10}$. However, $5 \cdot 10^{10}$ is an equally digitized number (it’s a five followed by ten zeros); This means that the fourth number has no more than the same digits. The fifth number is the sum of ten powers of the digits of the fourth number. Each of these ten powers is less than $10^{10}$, the total number of digits is no more than 11, which means that the fifth number is less than the twelve-digit number $11 \cdot 10^{10}$. It would become five, the fifth number contains no more than 12 digits. Reasoning similarly, we find that the sixth number is less than $12 \cdot 10^{10}$, and would again have no more than 12 digits. Therefore, using the same reasoning, we find that the record of the seventh, eighth and generally all subsequent numbers of our sequence contains no more than 12 digits. Since numbers that contain no more than 12 digits are a finite number, we will not be able to obtain numbers that are different from the previous ones, and someday we will encounter two identical numbers.

In conclusion, we offer you problems to solve independently (problems 1-12 constitute a task for

⟦folio 55⟧

seventh-graders who wanted to enter the All-Union Correspondence Mathematical Scale - see the story about this school on p. 65).

Zadcic

1. There are three solutions. The first solution contains 2% of substance A and 3% of substance B. The second solution contains 5% of substance A and 7% of substance B. The third solution contains 11% of substance A and 12.5% ​​of substance B.

Is it possible to mix these solutions in such a proportion that the resulting mixture contains 7.5% substance A and 7% substance B?

2. The numbers 1, 2, 3, 4, 5, 6, 7, 8, 9 are written in a row. Is it possible to dissolve the brackets and symbols of mathematical operations in such a way that an expression equal to zero is obtained?

3. The pioneer Seryozha came up with the following test for divisibility by 27: if the sum of the digits of a number is divisible by 27, then the number itself is divisible by 27. Is this test true?

4. Is it possible to cut a square into 1989 squares (not necessarily equal)?

5. The number 1989 was cubed and 3 was added to the result; the resulting number was again cubed and 3 was added to the result; the resulting number was again cubed, 3 was again added to the result, etc. The result was a sequence of numbers, each of which was 3 more than the cube of the previous one. Can it contain a number ending in 8?

6. Is there a natural number that, when multiplied by 2, becomes a square, when multiplied by 3, becomes a cube, when multiplied by 5, becomes the fifth power, and when multiplied by 7, becomes the seventh power of an integer?

7. Is there such a multi-digit number that the sum of the digits is divisible by 13 and the sum of the digits of a number one greater is also divisible by 13? If not, prove it; if yes, list all such numbers.

8. A prime number is a natural number that is greater than 2 and has no divisor other than itself and 1. It is required to place a prime number in each cell of a 4x4 square table so that in each row and each column the product of numbers is equal to 1989. Is it possible to do this?

9. Is it possible to dissolve the numbers in the cells of a rectangular table in such a way that the product of the numbers in each row is equal to two, and the product of the numbers in each column is equal to three?

10. Is it possible to arrange five different prims on a plane in such a way that each of them intersects the other three exactly?

11. The distance between points A and B is fifty kilometers. At noon, three friends set off from point A to point B. Each of them walks at a speed of 5 km/h. They have at their disposal a road bike that can be ridden at 10 km/h and a racing bike that can be ridden at 20 km/h. Each bike fits only one person; Bicycles can be left on the road without a guard. Will all three have time, using only these two bicycles, to add point B to six o'clock in the evening?

12. Is it possible to arrange points on plane 7 in such a way that the environments of any three of them can be found at least two, located at a distance of 1 cm?

13. 10 teams participated in the football tournament; each played one match with each other. According to the published tournament results, the seventh-place team scored 11 points, the eighth-place team scored 6 points, and the last-place team scored 4 points. Could this be so? (For a victory, a team receives 2 points, for a draw - 1 point, for a loss - 0 points. In case of equality of points scored, the number of goals scored and conceded is taken into account.)

14. A sequence of forty numbers is constructed as follows. The first number is equal to zero, the second is equal to one. Each number, except the first and second, is equal to the sum of some two of the previous numbers. Can a member equal to a million occur in such a sequence?

15. How many circles of radius 1 must be taken to cover the square on side 2?

16. It is required to transfer several pieces of marble with a total mass of 14 tons. The exact mass of each piece is unknown, but the mass of each is no more than 400 kg. How many vehicles with a carrying capacity of 1500 kg must be ordered in order to be able to increase this load?

17. In the country of Miggs, you can drive from any city to any one along one single road. When the roads pass through 4 cities of each, two roads pass through 3 cities of each, and each of the remaining roads contains 2 cities. The girl Ellie said that in total there are 11 cities and 35 roads in this country. Prove that she made a mistake in her calculations.

18. The circle is divided into n identical sectors, each of which contains a checker. In one move you can do the following: take any checkers and rearrange them: one - in the adjacent sector clockwise, the other - in the adjacent sector counterclockwise. For what n is it possible to collect all the checkers in one sector using such moves?

19. A square with a 1 m side of a drip in two colors. Prove that you can find three points of the same color that are the vertices of an equilateral triangle with a side of at least 30 cm.
