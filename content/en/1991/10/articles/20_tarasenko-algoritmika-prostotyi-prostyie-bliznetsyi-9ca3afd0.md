---
id: 1991-10-tarasenko-algoritmika-prostotyi-prostyie-bliznetsyi-9ca3afd0
issue: kvant_1991_10
year: 1991
number: "10"
title: Algorithms of simplicity. Simple twins
authors:
  - Тарасенко Б.
rubric: raznoe
rubric_sub: Разное
page_first: 65
page_last: 67
page_labels: 63-65
lang: en
source: kvant_digital
extraction: vision
content_sha256: da066f07934cb80d97fba0c6e98a21a7502caa80e5af52d03a92159e0b8540a7
prompt_sha256: draft-1
translated_from: content/ru/1991/10/articles/20_tarasenko-algoritmika-prostotyi-prostyie-bliznetsyi-9ca3afd0.md
source_content_sha256: b3fb60818a8f5b13bdbee5e5989984c4b68d261c4f719dc4f7f21f411e7e838b
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 63⟧

---
running_head:
folio:
---

Algorithmika
simplicity
Simple twins
V. TARASENKO

It's not an easy question,
No more than one thing:
Everything is complicated and simple,
Count it out of your mind!

In nature, similarities are objects that are very similar to each other; excellent food is a noticeable “slightly”. In mathematics for prime numbers, this “slightly” is defined precisely, constantly and equal to two. Here are the first mathematical “doubles”: (3; 5), (5; 7), (11; 13), (17; 19), (29; 31), (41; 43), (59; 61), (71; 73), (101; 103), (107; 109) and so on. The pair of pairs (3; 5), (5; 7) is unique - it is the only one of the twins that has a common element (uniqueness is easy to prove using divisibility by three).

Are there many similar prime numbers?
In the first ten there are two pairs (and prime numbers are four), in the first hundred there are eight (with 25 prime numbers). There is a hypothesis that the set of pairs of identical prime numbers is infinite. This hypothesis has not yet been proven or disproved. However, close prime numbers are clearly less common than just prime numbers. But how much less often?

Do you feel that there is already in the air the specific two little goats from the famous cartoon, who knew how and wanted (for the benefit of practice!) to count everything? You got it. We really want to give you another software tool: an advanced counting generator of simple numerical blizzards.

The theme of closeness or even complete similarity arises more than once in it. The main goal is to find pairs of prime numbers, which means the program must check for primality twice. In such cases, song lyrics save booga by citing the fragment once and then referring to it with one word: “chorus.” For example:

There was a movement of robbers,
There was Kudeyar-ataman,
The robbers drank a lot
Blood of pure Christians.

Chorus:

Let us pray to the rich Lord,
We weighed the ancient one,
He told it to us in Solovki
Monk, pure Pitirim.

A lot of wealth was stolen
They lived in a dense forest.
Leader-Kudeyar from near Kyiv
He took out the beautiful girl.

Chorus

In programming, the "chorus" is called a subroutine. When accessed from the main program, this “chorus” is executed, and then control is transferred back to the main program. So we made the program in the form of a “song with a chorus” - a subroutine (steps 33-55). Its main part is formed by our serial programming tool No. 1, appropriately modified. The opportunity to make two other similar parts into another subroutine is provided by the reader. Here you can get so-called output subroutines - “chorus” to “chorus”, or you can make one extended subroutine. The expected gain from the operation is three command steps or more.

You can also win a step on the indication commands. The reader knows how. Otherwise, there are no fundamental innovations.

We have already done “sections by hundreds” after each power of ten for primes. Without further ado, let’s do the same for the twins. Here, after the power of ten, the number of pairs is indicated in parentheses, then

⟦folio 64⟧

---
running_head:
folio:
---

Program No. 5. Counting incremental generator of simple numerical blitzes

00 X→Π 6 46 /+ Transfer from PrX to Pr6 of the starting odd number
01 0 00 /+ Constant zero
02 C/Π 50 /+ Storp—zero indication, invitation to enter a number
03 F X=0 57 /+ Contents of PrX not equal to zero?
04 02 02 /+ NO, PrX=0, go to step 02 (barrier against zero input)
05 b→Π 4 44 /+ YES, a non-zero number is entered, sending it to Pr4
06 BP 51 /+ Unconditional jump
07 10 10 /+ per step 10
08 K P→X 6 G6 /+ Adding 1 to the test number in Pr6
09 K P→X 6 G6 /+ Adding 1 more to the tested number
10 PP 53 /+ Go to subroutine
11 33 33 /+ at address 33 to check the primality of odd. numbers
12 F X≠0 57 /+ Contents of PrX not equal to zero?
13 08 08 /+ NO, PrX=0, the number being tested is not prime, go to step 08
14 P→X 6 66 /+ YES, PrX≠0, the number being tested is prime, call it from Pr6 to PrX
15 X→Π a 4— /+ Fixing the first prime in PrA
16 K P→X 6 G6 /+ Adding 1 to the test number in Pr6
17 K P→X 6 G6 /+ Adding 1 more to the tested number
18 PP 53 /+ Go to subroutine
19 33 33 /+ at address 33 to check the primality of odd. numbers
20 F X≠0 57 /+ Contents of PrX not equal to zero?
21 08 08 /+ NO, PrX=0, the number being tested is not prime, go to step 08
22 P→X 6 66 /+ YES, PrX=0, the number being tested is prime, call it from Pr6 to PrX
23 X→Π b 4L /+ Fixing the second prime in PrB
24 P→X a 6— /+ Calling a younger neighbor from PrA to PrX
25 C/Π 50 /+ Storp—indication of the lowest number—closest
26 P→X b 6L /+ Calling a senior neighbor from PrB to PrX
27 C/Π 50 /+ Storp—indication of the highest number—closest
28 P→X 4 64 /+ Call in PrX the contents of the pair serial number counter
29 C/Π 50 /+ Storp—indication of the serial number of a pair of Blizzards
30 K P→X 4 G4 /+ Increment by 1 counter Pr4 of serial numbers
31 BP 51 /+ Unconditional jump
32 08 08 /+ per step 08
33 1 01 /+ Start of subroutine, constant 1
34 X→Π 5 45 /+ Zasylak 1 in Pr5=D, D is a divisor
35 K P→X 5 G5 /+ Adding 1 to counter Pr5
36 K P→X 5 G5 /+ Adding 1 more to the counter Pr5
37 P→X 6 66 /+ Calling the current test number in PrX AND from Pr6
38 P→X 5 65 /+ Calling the current divider D from Pr5 into PrX, AND goes to PrX
39 ÷ 13 /+ PART=I/D
40 b→Π 9 49 /+ Zasylaka PART in Pr9
41 K P→X 9 G9 /+ K=integer part of PART
42 P→X 6 66 /+ Call I in PrX
43 P→X 9 69 /+ Call K in PrX; And moves to PrY
44 P→X 5 65 /+ Call D in PrX; PrY=K; PrZ=AND
45 × 12 /+ D×K
46 - 11 /+ OST=I-K×D, remainder of division
47 F X≠0 57 /+ OST≠0?
48 55 55 /+ NO (i.e. OST=0), exit the subroutine with zero to step 55
49 P→X 9 69 /+ YES (i.e. OST≠0), integer output PART
50 P→X 5 65 /+ Call D from Pr5 to PrX
51 — 11 11 /+ PrX=PART—D
52 F X<0 5C /+ PART—D<0?
53 35 35 /+ NO, go to step 35 to the new value D
54 P→X 6 66 /+ YES (set D is exhausted), call AND in PrX
55 B/O 52 /+ Return to main program with zero or prime number

10⁰(8): (3; 5), (5; 7), (11; 13), (17; 19), (29; 31), (41; 43), (59; 61), (71; 73); (101; 103).

10¹(8): (11; 13), (17; 19), (29; 31), (41; 43), (59; 61), (71; 73), (1; 3), (7, 9); (137, 139).

⟦folio 65⟧

---
running_head:
folio:
---

10^2(7): (1; 3), (7; 9), (37; 39), (49; 51), (79; 81), (91; 93), (97; 99); (227; 229).

10^3(5): (19; 21), (31; 33), (49; 51), (61; 63), (91; 93); (151; 153).

10^4(4): (7; 9), (37; 39), (67; 69), (91; 93); (139; 141).

10^5(0): (151; 153).

10^6(1): (37; 39); (211; 213).

10^7(0): (139; 141).

10^8(1): (37; 39); (167; 169).

Let's move on directly to the program. It works on MK-61, it is suitable and all programs are compatible with the family. To start it, after entering the program into the PMC, you must manually perform the following operations.

Press the B/O key, dial the initial odd positive integer number, not less than 5. Then press the C/P key. A zero will appear on the indicator. This is an invitation to dial the initial value of the Blitz serial number counter. You can dial one. If you know exactly the serial number of the old pair of Blitzes, then dial the smaller of the Blitzes as the initial odd number, and then, after C/P and the appearance of zero, this known serial number.

Then press the C/P key, and when the secondary gun stops, the first of the twin numbers will appear on the indicator. After pressing the C/P key, the second one will appear, and after the next C/P, the relative serial number of this pair of twins will appear. New presses of the C/P key will lead to the appearance of new pairs of twins and so on.

(For the beginning, see p. 62)

4.5 hours, each task was worth 10 points. After the task number, the country that proposed it is indicated in parentheses.

First day

1 (Argentina). Let f be a function defined on the set of non-negative integers and satisfy the following two conditions:

1) if n = 2^i - 1 for i = 0,1,2,..., then f(n) = 0.
2) if n ≠ 2^i - 1 for i = 0,1,2,..., then f(n + 1) = f(n) - 1.
a) Show that for any integer n ≥ 0 there is an integer k ≥ 0 such that f(n) + n = 2^k - 1.
b) Find f(2^1990).

2 (Colombia). In triangle ABC, point I is the center of the circle drawn into it, and D, E and F are the tangent points of this circle from the sides BC, CA and AB, respectively. Let P be another point of intersection of line AD with the curved circle, and M be the midpoint of segment EF. Show that points P, I, M and D lie on the same circle or line.

3 (Spain). Let f(x) = (x + b)^2 - c be a polynomial for which b and c are integers. Show that

a) if p is a prime number, and c is divisible by p but not divisible by p^2, then for all integers n the number f(n) is not divisible by p^2,
b) if q is a prime number not equal to 2 such that c is not divisible by q and f(n) is divisible by q for some integer n, then for any integer r there is an integer n' such that f(n') is divisible by q'.

Second day

4 (Venezuela). Let AB be the diameter of circle c₁. Taking t touches this circle at point B. Let M be an arbitrary point on circle c₁, different from A and B. Let us construct a circle c₂ tangent to circle c₁ at point M and line t.

a) Find the point P of tangency of the circle c₂ with the line t, as well as the locus of the centers of the circles c₂ if the point M is a variable.

b) Show that there is a circle orthogonal to all circles c₂.

5 (Mexico). Let A and B be opposite vertices of a daughter of size n × n, divided into unit squares (n ≥ 1). In each of the squares a diagonal is drawn parallel to the line AB, as a result of which there must be 2n² equal triangles. The chip moves along the segments on this disk from A to B, and when passing the sides of the triangle, grain is placed in it. Each segment is passed no more than once. At the end of the path, it turned out that each of the 2n² triangles contains exactly 2 grains. At what values ​​of n is such a situation possible?

6 (Uruguay). Let f(x) be a third-degree polynomial with rational coefficients. Show that if the graph of the function f(x) touches the x-axis, then all three roots of the polynomial f(x) are rational.

The publication was prepared by A. Savin
