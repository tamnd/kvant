---
id: 1986-6-sistepskiy-programmirovanie-na-mikrokalkulyatore-igryi-293c51b3
issue: kvant_1986_6
year: 1986
number: "6"
title: 'Programming on a microcalculator: games'
authors:
  - Систепский Л. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 44
page_last: 45
page_labels: 42-43
tag: GDCK
lang: en
source: kvant_digital
extraction: vision
content_sha256: f76b21ed3bb7f53f7094592cacbfbb19e586ad18711588d891651008120adf52
prompt_sha256: draft-1
translated_from: content/ru/1986/06/articles/17_sistepskiy-programmirovanie-na-mikrokalkulyatore-igryi-293c51b3.md
source_content_sha256: 6ba947e60237a63557a03f85207d4060b7ff848f405e4e5b7a4190fe7f70cac7
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

Programming on a microcalculator: games

L. N. SISTEPSKY

The article is intended primarily for ninth-graders studying the fundamentals of information and computer technology and having access to a programmable microcalculator, but it will also be of interest to everyone who uses such a microcalculator.

During the school year, you learned to write programs in an algorithmic language. On the pages of the magazine «Kvant» we explained how to translate these programs into codes for a programmable microcalculator (see «Kvant», 1985, No. 2, 3). These skills allow you to use your cable to solve school math problems, such as finding the roots of algebraic equations.

This is not a matter for the future. And now, before the summer holidays, we invite you to take a break from math problems and play games using your programmable micro calculator.

Basshe game

From a pile containing $p$ items, such as matches, two players take turns taking a certain number of matches. You can take at least one and no more than $k$ matches at a time. The number $k$ (it is better to choose it much less than $p$) is set by the players in advance. The one who has to take the last match loses.

Enter the program given in Table 1 into the machine, first acquire a set of matches, travel with other items, and, carefully read the instructions, start the game. You can play with the machine one on one. After making sure that the machine is a strong partner, allow a friend to help and try to play together against the machine.

Instructions

1. Enter the B/O program.
2. 1 VP 7 P 7 1, 8 F 1/x P/8.
3. $p$ C/P $(p)$, $k$ C/P (0).
4. If the machine makes the first move, then C/P (the number of matches taken by the machine), enter your move C/P (the machine’s move) and again your move, etc.
5. If you want to make the first move, then enter the number of matches you took, C/P (return move of the machine), your move C/P (move of the machine), etc.
6. For a new game: B/O and go to step 3 of the instructions.
7. Tasks
1 (for a math lover). Given $p$ and $k$, find a winning strategy in the game Basshe.
2* (for programming enthusiasts). Try to decipher the machine's strategy.

Ballistic game

An image of a coordinate system on checkered paper, a bizarre landscape and two cities of Gulpians, at odds with each other (figure). Within each city, set a starting procedure and mark with dots the positions of the guns (cannons), from which the unreasonable residents of the enemy cities fire firecrackers at each other. Enter the program from Table 2 into the machine, press B/O, enter the data according to the instructions.

Table 1

00 P 0 40 24 F In 0
01 C/P 50 25 – 11
02 ↑ 0E 26 IP 1 61
03  1 01 27  /-/ 0L
04  + 10 28  × 12
05 P 1 41 29 IP 0 60
06  0 00 30  + 10
07 C/P 50 31 1 01
08  F x≠0 57 32  — 11
09  15 15 33  F x≠0 57
10  /-/ 0L 34 44 44
11 ↑ 0E 35 P 2 42
12 IP 0 60 36 /-/ 0L
13  + 10 37  ↑ 0E
14 P 0 40 38 IP 0 60
15 IP 0 60 39 + 10
16 1 01 40 P 0 40
17 - 11 41 IP 2 62
18 IP 1 61 42 BP 51
19  ÷ 13 43 07 07
20 IP 8 68 44 1 01
21 - 11 45 P 2 42
22 IP 7 67 46 BP 51
23  + 10 47 36 36

⟦folio 43⟧

Table 2

| | | | | | |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 00 | IP 3 | 63 | 34 | + | 10 |
| 01 | F sin | 1[ | 35 | P 0 | 40 |
| 02 | IP 2 | 62 | 36 | IP A | 6— |
| 03 | × | 12 | 37 | IP 3 | 63 |
| 04 | P 0 | 40 | 38 | + | 10 |
| 05 | IP 3 | 63 | 39 | P A | 4— |
| 06 | F cos | 1G | 40 | IP S | 6[ |
| 07 | IP 2 | 62 | 41 | IP 6 | 66 |
| 08 | × | 12 | 42 | — | 11 |
| 09 | IP 8 | 68 | 43 | P S | 4[ |
| 10 | × | 13 | 44 | IP 0 | 60 |
| 11 | P 3 | 43 | 45 | IP 9 | 69 |
| 12 | IP 0 | 60 | 46 | × | 12 |
| 13 | P 2 | 42 | 47 | IP 2 | 62 |
| 14 | IP 6 | 66 | 48 | + | 10 |
| 15 | F sin | 1[ | 49 | IP 0 | 60 |
| 16 | IP 5 | 65 | 50 | × | 12 |
| 17 | × | 12 | 51 | IP 1 | 61 |
| 18 | P 0 | 40 | 52 | + | 10 |
| 19 | IP 6 | 66 | 53 | P V | 4↓ |
| 20 | F cos | 1G | 54 | IP 0 | 60 |
| 21 | IP 5 | 65 | 55 | IP 9 | 69 |
| 22 | × | 12 | 56 | × | 12 |
| 23 | IP 8 | 68 | 57 | IP 5 | 65 |
| 24 | × | 12 | 58 | + | 10 |
| 25 | P 6 | 46 | 59 | IP 0 | 60 |
| 26 | IP 0 | 60 | 60 | × | 12 |
| 27 | P 5 | 45 | 61 | IP 4 | 64 |
| 28 | 0 | 00 | 62 | + | 10 |
| 29 | P 0 | 40 | 63 | P D | 4G |
| 30 | P V | 4↓ | 64 | C/P | 50 |
| 31 | P D | 4G | 65 | VP | 51 |
| 32 | IP 0 | 60 | 66 | 32 | 32 |
| 33 | IP 8 | 68 | | | |

Instructions

1. Enter the program. Move the angle measure switch to position Г (degrees), В/О;
2. Enter data:
   $Y_1$; P 1; $v_1$; P 2; $\alpha_1$; P 3; $Y_2$, P 4; $v_2$; P 5; $\alpha_2$; P 6; 1; P 8; 5; /—/; P 9; $X_1$; PA; $X_2$; PS.
3. S/P;
4. Results: IP A ($X_1$) IP B ($Y_1$) IP C ($X_2$) IP D ($Y_2$)
5. Continue to step 3 of the instructions.
The meaning of the data is as follows:
$Y_1$ — ordinatum of the first city’s cannon (on the left); $v_1$ is the initial speed of the firecracker flying out of this cannon;
$\alpha_1$ — sight angle of the first cannon (see figure) in degrees;
$Y_2$ — ordinatum of the cannon installed in the second city (on the right);
$v_2$ is the initial speed of the second gun firecracker;
$\alpha_2$ — sight angle of the second cannon (see figure) in degrees;

Start the program using the C/P key. The abscissa and ordinate of the cannon fired from the second city will be entered in registers A and B. By pressing C/P, you will get the positions of the clapper after another 1 second, etc. While the machine is being calculated, offset the positions of the clapper on the drawing. The winner is the one who (first) hits the opponent's old court.

In register 8 (see instructions) before the start of the game, 1 will be recorded. You can enter any number t, thereby changing the time interval between individual readings of the machine (you can interval the positions of the clapper not every second, but every 2 seconds or 0.5 seconds, etc.). Register 9 will contain the values ​​- g/2, where g is the magnitude of the free fall acceleration in m/sec². We set g=10. If the Gulepians live not on Earth, but on the Moon, then you need to choose g 6 times less. In short, you have a wide range of possibilities for fantasizing about the possible outrages of the Guleptians. Anyone who has a better understanding of the physics and conditions of motion will have a good opportunity to simulate the process of body motion in a gravitational field.
