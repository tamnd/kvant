---
id: 1973-7-toom-resheniya-zadach-vstupitelnoy-kontrolnoy-rabotyi-vzmsh-1973-goda-cd44a8dd
issue: kvant_1973_7
year: 1973
number: "7"
title: Solutions to the problems of the introductory test work of the VZMSH 1973
authors:
  - Тоом А. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 25
page_labels: 21-23
tag: KEAL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1c81b12d2bae2be046103e344dd56138fcfaff728b1dd454b6e979268b01c4be
prompt_sha256: draft-1
translated_from: content/ru/1973/07/articles/05_toom-resheniya-zadach-vstupitelnoy-kontrolnoy-rabotyi-vzmsh-1973-goda-cd44a8dd.md
source_content_sha256: 0b887c06c00b011c20ed2d4a9fe537f68f45d063e1937ea8f5844dae2ac7d5a8
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

Solutions to the problems of the introductory test work of the VZMSH 1973
A. L. Toom

In this issue we publish solutions to the most interesting problems from the introductory work at the VZMSH in 1973 (see «Kvant» No. 1, 1973, p. 49).

Problem 2. Are there any integers such as $(k+1)$-digit numbers? Let's denote its first digit by $x$, and the number remaining after crossing it out by $y$. Then the original number is $10^k x + y$. It coincides by condition with 57$y$:

$$10^k x = 56y.$$

Since 56 is divisible by 7, then $x$ is divisible by 7. But $x$ is a digit, so it is $x = 7$, and $y = 10^k/8$.

With $k \geq 3$ the number $y$ is an integer. By clicking $k = 3$, we get one of the possible answers:

$$10^k x + y = 7125.$$

Problem 5. There were 4 numbers written on the board. They were added in all possible ways in twos and got the following numerical sums: 2, 4, 9, 9, 14, 16. What numbers were written on the board?

Let us denote the smallest of the original numbers by $A$, the next largest by $B$, the next by $C$, and the largest by $D$. So, $A \geq B \geq C \geq D$. Then the following inequalities exist between their sums of two:

$$A + B \leq A + C \left\{ \begin{array}{l} \leq A + D \\ \leq B + C \end{array} \right\} B + D \leq$$

Using these inequalities, it is easy to unambiguously distribute the numerical values ​​given in the conditions between the sums, which is what has been done. From four of them the answer is found:

$$A = -1,5; \quad B = 3,5;$$

$$C = 5,5; \quad D = 10,5.$$

It is necessary to check that the remaining two amounts are also the same as stated in the conditions.

Problem 6. Is it possible to consider 9 numbers: 1, 2, 3, 4, 5, 6, 7, 8, 9 in a circle so that the sum of any three numbers in a row is divisible by 3 and is: a) greater than 9; b) more than 12?

a) It is possible. For example: 1, 9, 2, 7, 3, 5, 4, 6, 8.

b) It is impossible. Let the sum in each triple of adjacent numbers be at least 15. Then, since the sum of all

⟦folio 22⟧

The number of numbers from 1 to 9 is equal to 45, the sum in each triple is 15. But then the numbers spaced three places apart must be equal, which is impossible.

Problem 7. Triangle ABC, after turning near vertex A, took position $AB_1C_1$. Let us prove that if line AC bisects the segment $BB_1$, then line $AB_1$ bisects the segment $CC_1$.

Let us denote by $M$ the point of intersection of the lines $AC$ and $BB_1$. Two cases apart.

a) $M$ is the same as $A$. Then $A$ is the center of the segment $BB_1$, and therefore the rotation angle is $180^\circ$. But then $A$ is the center of the segment $CC_1$, and, of course, $AB_1$ bisects $CC_1$.

6) $M$ is not the same as $A$. Then $\triangle ABM = \triangle AB_1M$ on three sides. Therefore $MAB = MAB_1$.

If point $C$ lies on the same side of $A$ as point $M$, then angles $CAB$ and $CAB_1$ coincide with this angle. If point $C$ lies on the opposite side, then angles $CAB$ and $CAB_1$ are adjacent to it. In both cases

$$CAB_1 = CAB = C_1AB_1,$$
that is, $AB_1$ is the bissertis of the angle $A$ in $\triangle CAC_1$. Since it is equidistant, then $AB_1$ is also the median, which is what needed to be proven.

Problem 8. Imagine the number 203 as the sum of several positive sums max, so that the product of these sums can be 203.

The required numbers can even be taken as integers:

$$203 = 29 + 7 + 1 \dots + 1 = 167 \text{ раз} = 29 \cdot 7 \cdot 1 \dots 1. 167 \text{ раз}$$

(There are many other answers for non-integer numbers).

Problem 10. How many parts of the model can the plane be divided into by 4 different straight lines? We apply it for every case.

If all lines are parallel, then there are five parts. Let us prove that in all other cases there are at least eight parts. Let us draw such a large circle that all intersection points are inside it (see Fig. 1, where everything inside the circle is not drawn for clarity). Eight uncrossed circles emerge from it, into eight areas. Let us prove that all these areas belong to different parts. Let us assume that two regions belong to the same part (regions $A$ and $B$ on Fig. 1). Then the four loops that bound them belong to two parallel lines (see Fig. 1). But then some other line intersects them and still separates $A$ from $B$.

Let us now estimate the maximum possible number of parts. We will conduct the lines one by one. It’s easier to reason in general terms: let on a plane

⟦folio 23⟧

Fig. 3.

$n$ straight lines have already been carried out and we are conducting the $n + 1$th. Obviously, there are no more than $n$ intersection points on it, dividing it into no more than $n + 1$ pieces. Each piece divides some part into two. Thus, the number of parts increases by no more than $n + 1$. For one straight part there are always two, so for four there are no more straight parts

$$2 + 2 + 3 + 4 = 11.$$

So, there are either five parts, or at least eight and no more identical. The examples in figure 2 show that all of these cases are possible.

Notes. Other solutions are possible: one or another search of accounts. Our reasoning can easily be restored to the case of $n$ lines and allows us to prove that the number of parts is either equal to $n + 1$, or not less than $2n$ and not more than $\frac{1}{2} (n^2 + n + 2)$. However, for large $n$ not all numbers in this project are possible. (And which numbers are possible and which are not is not known).

Problem 11. In the morning Kolya and Olya decided to water the hydrogen. Kolya opened the tap, filled his watering can, and immediately after him Olya placed her watering can under the stream. Kolinaleika fills in 15 seconds, and Olina in 10 seconds. Having filled their watering can, each of the children can pour hydrogen without starting. Water falls from Kolinoilika in 60 seconds, and from Olina in 45 seconds. As soon as the milk tank turns out to be empty, each time we change it, we substitute it under a stream of water, and if at this moment we start the water with another, then we will prove until the tap is free, and immediately begin to fill the water tank. When a person doesn't pick up his leika. When the person does not draw water, it pours into a barrel standing under the tap. If no one took the water, the barrel would be filled in 15 minutes. How long will it take after turning on the tap to fill the barrel if Kolya and Olya have been pouring hydrogen all this time? Who will be the first to draw water after me, as water is drawn over the edge of a barrel?

This problem can be conveniently solved using a graph. Let's draw a schedule of Kohl's and Olya's actions. Filling the lungs will be denoted by removal, watering by red, waiting by black. It is convenient to take the scale as follows: there are 5 seconds in one cell. The beginning of the graph is shown at figure 3. If you complete the graph to the 50th cell, you will notice that the 48th cell essentially coincides with the 2nd (Kolya 5 s fills his lung, and Olya waits); The 49th coincides with the 3rd; 50th - from 4th and so on. Therefore, the actions of Kolya and Olya will be repeated periodically every 46 cells (230 s). The graph shows that during one period, water is poured into the barrel over 29 cells. Since 15 minutes corresponds to 180 cells, and 180 = $6 \cdot 29 + 6$, then 6 full periods and part of the seventh must pass until the barrel is filled.

Using the chart of the first period, we determine that this part is 11 cells. In total, until the barrel is filled, $6 \cdot 46 + 11 = 287$ cells will pass, that is, 23 minutes 55 seconds. Using the same graph, we see that Olya will be the first to fill the lung with water after filling it.
