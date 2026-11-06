---
id: 1990-11-kiryuhin-rakov-iii-vsesoyuznaya-olimpiada-po-informatike-5263d701
issue: kvant_1990_11
year: 1990
number: "11"
title: III All-Union Olympiad in Informatics
authors:
  - Кирюхин В. М.
  - Раков С.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 67
page_last: 69
page_labels: 65-67
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1ebfb158365d3e3ef0e10be411b0dce17a2e2a9419644b624498036ef1dbc776
prompt_sha256: draft-1
translated_from: content/ru/1990/11/articles/26_kiryuhin-rakov-iii-vsesoyuznaya-olimpiada-po-informatike-5263d701.md
source_content_sha256: 41796d63964996ef54e462c6fc50e8dc378c031059ebeddf543d782bf512724e
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 65⟧

---
running_head:
folio:
---

III All-round
Olympics
in computer science

Candidate of Technical Sciences
V. KIRYUKHIN,
Candidate of Physical and Mathematical Sciences
S. RAKOV

It is gratifying that the Olympiad among schoolchildren in computer science has taken its rightful place among other Olympids. This year, the final stage of the III All-Olympics took place from April 18 to 25 in Ukraine in Kharkov. 87 schoolchildren from all union resource centers, as well as the cities of Moscow, Leningrad, the host city of the Olympiad Kharkov and the Ministry of Railways took part in the Olympiad.

At the organizational meeting of the Junior Olympics, which was headed by Academician of the Academy of Sciences of the Ukrainian SSR V.L. Rvachev, a fundamentally new decision was made to hold two rounds of the Olympics using computers. This decision caused the necessary assessment among team leaders. Some of them argued that the order of the rounds adopted at past Olympids (I round - theoretical, without the use of computers; 2nd round - practical, with their use) allows, on the one hand, to equalize the chances of winning for schoolchildren who have different access to a personal computer, and on the other hand, to select children who have good theoretical training, and do not quickly master the keys. However, the majority of team members and team leaders supported the decision. The main arguments were as follows:

— in the process of solving computer science problems, the stages of formalization, development of the best algorithm and its implementation on a personal computer are interconnected and inseparable from each other; Moreover, the development of an algorithm cannot be carried out without taking into account the capabilities of a specific computer;

— technical work on a computer is an integral part of solving a computer science problem;

— it is difficult to require schoolchildren to develop new algorithms based on server-side theoretical analysis of known algorithms; As for the assessments of the algorithms they propose, carrying out work using computers also implies the need for such an analysis;

- the level of All-Russian Olympids in computer science must correspond to international olympids, and if earlier the conduct of theoretical type, as well as the introduction in the country of non-computer education in computer science in high school, was associated with the lack of necessary computer technology, now the situation with personal computers has improved significantly, and each resource center has all the necessary conditions for preparing their teams, taking into account the above requirements;

— the introduction of computer rounds does not in any way limit the class of tasks offered at the Olympiad, since in this case there is a need for schoolchildren themselves to determine to what extent they should use a computer to obtain the required result;

— a significant increase in the level of objectivity of assessments through the use of computers when checking the solutions submitted by participants.

So, this year both tours were conducted using personal computers. However, as a computress, the Yuroi Olympidas made the following decision: when checking work in the first.type, the emphasis should be on evaluating the proposed algorithm for solving the problem, and in the second.type - on the implementation of the algorithm. These also determined the number of tasks offered on different tours. In particular, on

⟦folio 66⟧

---
running_head:
folio:
---

In the first round, two problems were proposed, in the second - one. Let us present the conditions of the problems.

First round
T 1.1. The circle is cut by a non-self-intersecting broken line, the coordinates of the vertices of which are given by the parameter of natural numbers $(X_1; Y_1), \dots, (X_k; Y_k)$. The first and last vertices lie on the border of the circle, and the rest are inside it. Determine whether it is possible to separate the two resulting parts of the circle (leaving the plane is not allowed).

P. Pankov
T 1.2. What is the minimum number of identical $(P, Q)$-knights required to control:
a) a limited chessboard of size $M \times N$ cells;
b) an infinite plane?
Notes 1. $(P, Q)$-knight is a figure that moves $P$ cells horizontally and $Q$ cells vertically or $P$ cells vertically and $Q$ cells horizontally in one move. For example, $(1, 2)$-knight is a common chess knight.

Note 2. A piece or group of pieces controls a field if each square of the field is accessible to at least one piece in one or more moves. For example, to control a standard board of size $8 \times 8$, two $(1, 1)$-knights are required.

Ya. Seidelman

Second round
T 2. Let us denote
$$S(N, a, b) = \sum_{k=1}^{N} \frac{k}{a^{[\log_b k]}},$$
Where
$$\sum_{k=1}^{N} x_k = x_1 + x_2 + \dots + x_N,$$
[$\log_b k$] means the integer part $\log_b k$, through $\log_b k$ denotes the number $z$ such that $b^z = k$.
You need to write a program that prints with as many correct decimal places as possible:
a) $S(100, 3, 2)$;
b) $S(100, 3, 1.9)$;
b. Prokoroye
Before each round, the student of the Olympiad selected the tasks of the package presented to the methodological commission for information of the State Education of the USSR. Readers of the magazine will be interested to know what the tasks of the reviewer are. These are the tasks.

Tasks for the first round
1. A palindrome is a sequence of certain characters that reads the same both from left to right and from right to left. Propose an algorithm that allows you to find a polydrome substring of maximum length in a given string.

B. Bardadym
2. Given a sequence of length $N$, consisting of ones and zeros. Determine the number of $M$-digit double numbers $(M \leqslant N)$ in the given sequence that are divisible by 21.

B. Bardadym
3. The vertices and sides of the $N$-gon are placed with natural numbers from 1 to $2N$. If the sums of the three numbers corresponding to each side are equal, then the $N$-gon is called matic. Required:
a) for a given natural $N$, form at least one magnetic $N$-gon;
b) for a given natural $N$, it is possible to form large numbers of magnetic $N$-gons.

A. Rakov

Tasks for the second round
1. The warehouse has the shape of a body of revolution. Its base lies on the plane $xOy$. Each link forms part of the conical surface. The mountain ends with a plateau. You need to write a program that calculates the shortest path from point $A$ at the base of a cliff to point $B$ on a plateau. The program should continue the route in response to the input:
point coordinates $A$ and $B$;
number of rings $N$;
welcome $R_i$ ($i=1, \dots, N$) at the foundation of each link;
lengths $L_i$ ($i=1, \dots, N$) of the generators of each link.

The radii $R_i$ strictly monotically decrease with increasing $i$. Perform matching: $L_i \geqslant R_i - R_{i+1}$, $i=1, 2, \dots, N$; $R_{N+1}=0$; $L_N=R_N$ (the $N$ link forms a plateau). For each link, it is indicated where the slope is directed - uphill or downhill - when moving towards the axis of the rock.

H. Krasovsky
2. Papa Carlo assembles Pinocchio's three-wheeled bicycle. Not to make round wheels, he sawed them out of trees in the form of polygons. Note that the rear wheels of the bicycle are rigidly fixed to the axle. Buratino took a bicycle and went to Malvina on a flat road.
For the initial position of the wheels, it is necessary to determine:
a) angular amplitude (in radians) of swing at ease of the axis of the rear wheels relative to the road;
b) how to rotate one rear wheel on the axle relative to the other so that the amplitude of this swing is minimal;
b) the angular amplitude of swing of the crossbar connecting the front axle with the middle of the rear axle, with ease at a value in which the rear axle with wheels is a structure symmetrical to a relative plane perpendicular to the axis in its middle.

Wheel polygons are specified by the coordinates of their vertices in any order. The distance between the rear wheels and the length of the crossbar mentioned in point (c) are also affected.

B. Prokoroe
It should be noted the merits of the Olympics restrictors, who ensured

⟦folio 67⟧

---
running_head:
folio:
---

schoolchildren with the necessary personal computers and programs. In particular, everyone who wished to work on an IBM PC was provided with these personal computers. The rest of the work is on Yamahas.

Each round of the Olympids was scored on the basis of 100 points. In this case, the first task of the first round was scored out of 40 points, and the second - out of 60.

Instructions for solving problems and evaluation criteria compiled by the authors of the problems are given at the end of the magazine.

After the members of the jury checked the problems of both rounds, they were analyzed by the authors, and then appeals were considered. At past Olympics, this process took place quite calmly. This year, under the influence of some team leaders, the review of appeals took on an avalanche-like character. Almost all the participants, trying to increase their grades at any cost, began to appeal to zhurni. A large number of appeals significantly contribute to the successful work of the commission. In order to prevent this from happening in the future, it is necessary to set out the evaluation criteria in sufficient detail when analyzing tasks.

Closing of the III All-Russian Olympiad according to the status information in the Palace of Pioneers named after. P. P. Postysheva. 6 schoolchildren received I degree diplomas (they scored 98-115 points), II degree diplomas - 11 (60-85 points), III degree diplomas - 14 schoolchildren (48-58 points).

Many schoolchildren were loaded with recognition from public, scientific organizations and methods of the Olympiad - HTTM "Ponsk". In particular, for the best solution to the first problem of the first round, the prize was given to Y. Zaitsev (Kyiv, school No. 57, 11th grade), T. Dokshtser (Leningrad, school No. 239, 11th grade) and L. Netrosvili (Tbilisi, school No. 25, 11th grade).

For the best solution to the second problem of the first round, the prize was given to G. Eskov (Leningrad, school No. 239, 11th grade). Behind the beam
