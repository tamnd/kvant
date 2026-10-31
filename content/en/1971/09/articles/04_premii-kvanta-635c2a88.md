---
id: 1971-9-premii-kvanta-635c2a88
issue: kvant_1971_9
year: 1971
number: "9"
title: Awards «Kvant»
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 35
page_last: 40
page_labels: 35, 36, 38
tag: 9BN5
lang: en
source: kvant_digital
extraction: vision
content_sha256: 539c1bb5ed1c0804b4ca92183cfdff8e973b7e76f708b6bc28db586531b5c4e4
prompt_sha256: draft-1
translated_from: content/ru/1971/09/articles/04_premii-kvanta-635c2a88.md
source_content_sha256: 1515494e9543d7c0e7a59033c52e7f481928192ca1ea34f82447feb760db6840
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

The editors of the magazine received more than 2000 letters with solutions to problems placed in the “Problem Book «Kvant»” section. Among the authors of these letters, the editorial board selected schoolchildren who regularly sent particularly original and successful solutions. They are loaded with an annual subscription to the magazine «Kvant» for 1972.

Here are the names of the winner of our competition:

Dmitry Grigoriev - Leningrad, boarding school No. 45 at Leningrad State University;
Yuri Obolonkov - Voronezh, school No. 58;
Eduard Turkevich - Chernivtsi, school No. 9;
Mikhail Prager - Tomsk, school No. 51;
Arkady Chernyak - Minsk, school No. 50;
Leonid Braginsky - Frunze, school No. 61;
Viktor Krivitsky - village. Kletnoye, Borisvsky district, Minsk region;
Alexander Grigoryan - Baku, school No. 211;
Grigory Zaitsev - Gagra, school No. 2;
Ivan Grichik - David-Gorodok, Brest region, school No. 1;
Alexander Zhukov - Kirovsk, Khartsyzsky district, Donetsk region, school No. 11;
Anatoly Anishchenko - Sarapul, school No. 13 of the Udmurt Autonomous Soviet Socialist Republic;
Evgeny Gubarev - Moscow, school No. 144.

⟦folio 35⟧

To prove statement 1), we will indicate a strategy for the first player that does not depend on the moves of the second player and guarantees that the difference between the remaining two numbers will be at least 32. This strategy describes a very simple one: with each move, cross out numbers after one, that is, cross out the second, fourth, ... number from the remaining ones (we assume that the numbers are arranged in ascending order). then after the 1st move the difference between any adjacent of the remaining numbers will be at least 2, after the 2nd - at least 4, after the 3rd - at least 8, after the 4th - at least 16 and after the 5th - at least 32.

To prove statement 2), it is enough to indicate the strategy of the second player, which does not depend on the moves of the first and will allow him to win no more than 32. It is as follows. With his first move, he crosses out all numbers less than 512, or all numbers greater than 512 (it is clear that there are no more than 256 of either of them left). After this, the difference between the outermost remaining numbers will be no more than 512. Similarly, with the second move, he can ensure that all the remaining numbers will be in only one of the segments [0.256]; [256, 512]; [512, 768]; [768, 1024], that is, reduce the difference between the extreme numbers to at least 256. In the same way, on the 3rd move he can reduce this difference to 128, on the 4th to 64 and on the 5th to 32.

I will add a solution to this problem from Yu. Obolonkov from Voronezh and V. Luzey from Moscow.

Of course, it was similarly possible to prove that if a game consists of n moves and starts with the numbers 0, 1, 2, ... 2^n, then the “game price” is equal to 2^n. But a detailed study of such a game, starting with an arbitrary set of numbers (not necessarily an arithmetic progression) is a much more difficult task.

**M62**

Prove that for any odd number a there is a natural number b such that 2^b - 1 is divisible by a.

Here is the shortest proof.

Let's consider the numbers 2^0 - 1, 2^1 - 1, ..., 2^a - 1. There are (a+1) of these numbers. Some two of them give the same remainders when divided by a, because there are only a different such remainders (this reasoning is called “Dirichlet propill,” its applications are described in the article by A. Orlov in «Kvant» No. 7). Let, say, the numbers 2^k - 1 and 2^m - 1 give the same remainders when divided by a and k < m. Then the number (2^m - 1) - (2^k - 1) = 2^k (2^m - k - 1) is divisible by a and, since a is odd, 2^m - k - 1 is divisible by a.

A more general fact is proved in the same way: if natural numbers a and c are coprime, then there is a natural number b such that c^b - 1 is divisible by a. Many readers have noticed that the statement of the problem follows from the following Euler theorem*): for any natural numbers a and c, the number c^φ(a)+1 - c is divided by a, where φ(a) is the number of natural numbers less than a and relatively prime to it, and they even give a formula for calculating the “Euler function”

$$\varphi\left(p_1^{\alpha_1} p_2^{\alpha_2} \cdots p_r^{\alpha_r}\right) = \left(p_1^{\alpha_1} - p_1^{\alpha_1}-1\right) \times \left(p_2^{\alpha_2} - p_2^{\alpha_2}-1\right) \cdots \left(p_r^{\alpha_r} - p_r^{\alpha_r}-1\right).$$

Correct solutions were added by A. Chernyak from Minsk, E. Turkevich, Sh. Slepoy from Chernivtsi, G. Levin from Kuibyshev, N. Demidenko from the village of Kolbovka, Gomel region, A. Pukhalsky from Moscow, Yu. Semenok from the village of Mirny, Krasnodar Territory and other readers.

**M63**

Is it possible to lay out a square out of 18 tiles of size 1x2 so that there is not a single rectangle of the sides of the square and there is no overlap at the edges of the tiles? (For example, a tile arrangement like figure 2 would not work because there is an AB seam.)

Let's assume that we managed to lay out a 6x6 square with 1x2 tiles without a "seam". Then each of the ten straight lines cutting this square

*) See, for example, the book by I.M. Vinogradov “Fundamentals of Number Theory” GITTL, M., 1953 or another textbook on number theory.

⟦folio 36⟧

Fig. 2.
Fig. 3.
Fig. 4.
Fig. 5.

Rat on 1x1 squares, must intersect at least one 1x2 tile. It is not difficult to prove that each such straight line intersects the obligatory even number of bars. Indeed, it cuts off a 6×k straight line from a 6×6 square, consisting of an even number of 1×1 cells; this straight line contains a certain number of whole 1×2 tiles and some even number of 1×1 cells—halves of ingots intersected by a straight line (Fig. 3).

Not if each straight line intersects at least two ingots, then the total number of ingots must be at least 2·10=20, and there are only 18 of them.

Thus, we have proven that it is impossible to cut a 6x6 square into ingots in the required manner.

The correct solution to this problem was added by A. Kostyurin from the Moscow region, I. Kashanov from Ufa, V. Schwartz from Leningrad and others. Most of the attached letters discuss the general question: when can a straight m×n be cut into 1×2 ingots without seams. It is easy to prove that a straight line 2×n, 3×n and 4×n cannot be cut in this way. If m≥5, n≥5 and mn is even (the last condition, of course, is necessary), then in all cases, except for the 6×6 considered above, the required partition exists. To prove it, it is enough to come up with a partition of straight lines 5×6 and 6×8 and then that from a partition of a straight line m×n it is easy to obtain a partition of a straight line (m+2)×n (Fig. 4 and 5).

N. B. Vasiliev

F72

Why does day length change faster in March than in December?

The change in the length of the day is associated with the angle of inclination of the earth's axis to the plane of the earth's orbit around the sun (≈23.5°). If the earth's axis were perpendicular to the orbital plane, the length of the day would remain virtually unchanged.

The tilt of the axis in space does not change, and since the Earth rotates around the Sun, it is visible from the Sun in different ways (Fig. 6) - The Sun illuminates parts of the Earth’s surface at different times, and the length of the day is not constant. It is obvious that in December and June, when in the rural hemisphere the length of the day is minimal or maximum, respectively, and the northern stripe is inclined away from or towards the Sun, the position of the earth's axis relative to the Sun changes very slowly. Slow changes and long days. At the same time, in March and September, the position of the axis changes quickly - the length of the day also changes quickly.

It is interesting to write an approximate graph of the dependence of the length of the day on the time of year. Roughly, this is a sine wave (Fig. 7). The rate of change during the day, very quickly, is proportional to the tangent

⟦folio 38⟧

Well, the pressure exerted by the molecules of the dissolved substance. This pressure is called osmotic pressure. The condition for equilibrium of liquid in vessels is not equality of hydrostatic pressures on both sides of the partition, but equality, roughly speaking, of the pressure of solvent molecules.

The molecules of the dissolved substance behave like gas molecules. They strive to occupy as much volume as possible by moving the partition (they would succeed if the partition were movable). But since the partition is fixed, it is not the partition that will mix, but the level of the mixture.

The analogy between the surface of gas molecules and molecules of a dissolved substance is complete. If the solution is weak, then the molecules of the dissolved substance are farther from each other and the weak interact with each other - just like the molecules of an ideal gas (they interact with each other only by standing). Therefore, the osmotic pressure $p$ must be related to the volume of the solution $V$, the temperature $T$ and the number $n$ of moles of the dissolved substance by the same formula as the pressure of an ideal gas:

$$pV=nRT$$

(R is the gas constant).

This law was discovered and proven experimentally by Van't Hoffform. Osmotic pressure does not depend on the nature of the dissolved substance and is determined only by the concentration of the solution. For strong solutions (those with high concentrations), you can write an equation similar to the van der Waals equation for the realization of gas. If we have different substances in the solution, then, by analogy with gases, the osmotic pressure is equal to the sum of the osmotic partial pressures of the individual dissolved substances. A raster in a field of gravity will behave similarly to an ideal gas: the distribution of the number of molecules in height will be exactly the same. This allowed Perrin

“weigh” the atom (see the article by M.P. Bronstein “How the atom was weighed”, «Kvant» No. 2, 1970).

The energy for raising the liquid is taken from the thermal energy of the movement of particles of the dissolved substance. Just like a real gas, the “gas” of particles of a dissolved substance, expanding and doing work, cools. In this case, of course, the entire solution is cooled.

Osmotic pressure plays a very important role in the life of humans, animals and plants. The membranes of many organs are a semi-permeable partition - for example, the walls of blood vessels and intestines, damage to plant roots, and so on. It is osmotic pressure that determines the volume of substances.

This problem was correctly solved by many readers: V. Sokolov (village of Myshansk, Gomel region, VSSR), S. Araslanova (village of Nizhnevinko, Kumensky district, Kirov region), N. Fedin (Omsk), N. Kolenko (Bondar, Odessa region), N. Egorov (village of Maya, Mechinokangala district, YASSR), M. Kozlovsky (Moscow) region, Ukrainian SSR), M. Maksimenko (Balaklya, Kharkov region), A. Veretsada (Orekhov, Zaporozhye region, Ukrainian SSR), S. Ivakov (Moscow).

F74

Two capacitors are connected in series. The first has a mixture of $C_1$ and is designed for a maximum voltage of $U_1$, the second has a mixture of $C_2$ and is designed for a maximum voltage of $U_2$. To what voltage can this battery capacitors be connected?

Since the capacitors are connected, their charges are equal, and the mixture of the battery is $C = \frac{C_1C_2}{C_1 + C_2}$. If voltage $U$ is applied to a capacitor battery, then its charge will be equal to $q = CU = \frac{C_1C_2}{C_1 + C_2} U$. This charge should not
