---
id: 1985-9-gik-reytingi-e964936c
issue: kvant_1985_9
year: 1985
number: "9"
title: Ratings
authors:
  - Гик Е. Я.
rubric: shahmatnaya-stranichka
rubric_sub: Шахматы
page_first: 67
page_last: 67
tag: U9CN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 423b00c357e1c9469146b0553de7373301aa31b9a89d832af7c24c126db2dc96
prompt_sha256: draft-1
translated_from: content/ru/1985/09/articles/02_gik-reytingi-e964936c.md
source_content_sha256: c6c0aa3db3e8ca8ba732cca7654fbc4d1abfa65583ef8d750093809349ac3d14
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

RATINGS

Seven years ago, «Kvant» spoke in detail about ratings and provided their mathematical justification. At the request of the readers, we will once again dwell on this issue.

A rating or, in other words, an individual chess coefficient is a number that characterizes its strength at a given moment. Performance in the tournament affects the rating: if successful, it increases, if unsuccessful, it decreases.

When entering the “rated” tour for the first time, a chess player receives an initial rating of 2200. The rating of each participant in the tour after finishing Knov is determined by the formula

$$K_{нов} = K_{ст} + 10(N - N_{ож}),$$

where $K_{ст}$ is the “old” rating, $N_{ож}$ is the number of “expected” points, and $N$ is the number of points actually scored.

If two chess players play the same game, then the “expected” number of points $n_{ож}$ is given in the table compiled by the American mathematician Professor Elo. On the left side of the table is the difference in game ratings, and on the right side is the number of “points” that a player with a higher and a lower rating must correspond to.

In the case of a match where two chess players play m games, $N_{ож}$ is equal to the product $n_{ож} \times m$, rounded up to obtain. For example, if two chess players with ratings 2550 and 2500 play a match of 12 games, then $K_{6} - K_{м} = 50$, $n_{ож}.6 = 0,57$, after multiplying by 12 we get 6.84 and after rounding $N_{ож}.6 = 7$; respectively $N_{ож}.m = 5$.

In the case of a tour, you just need to add up all the “expected” numbers of points that a given player should score in a game with other participants in the tour, and round up

the received number before receiving. This will be the $N_{ож}$ of this player.

$$\begin{array}{c c c}
K_{6} - K_{м} & n_{ож}.6 & n_{ож}.m \\
0 - 3 & 0,50 & 0,50 \\
4 - 10 & 0,51 & 0,49 \\
11 - 17 & 0,52 & 0,48 \\
18 - 25 & 0,53 & 0,47 \\
26 - 32 & 0,54 & 0,46 \\
33 - 39 & 0,55 & 0,45 \\
40 - 46 & 0,56 & 0,44 \\
47 - 53 & 0,57 & 0,43 \\
54 - 61 & 0,58 & 0,42 \\
62 - 68 & 0,59 & 0,41 \\
69 - 76 & 0,60 & 0,40 \\
77 - 83 & 0,61 & 0,39 \\
84 - 91 & 0,62 & 0,38 \\
92 - 98 & 0,63 & 0,37 \\
99 - 106 & 0,64 & 0,36 \\
107 - 113 & 0,65 & 0,35 \\
114 - 121 & 0,66 & 0,34 \\
122 - 129 & 0,67 & 0,33 \\
130 - 137 & 0,68 & 0,32 \\
138 - 145 & 0,69 & 0,31 \\
146 - 153 & 0,70 & 0,30 \\
154 - 162 & 0,71 & 0,29 \\
163 - 170 & 0,72 & 0,28 \\
171 - 179 & 0,73 & 0,27 \\
180 - 188 & 0,74 & 0,26 \\
189 - 197 & 0,75 & 0,25 \\
198 - 206 & 0,76 & 0,24 \\
207 - 215 & 0,77 & 0,23 \\
216 - 225 & 0,78 & 0,22 \\
226 - 235 & 0,79 & 0,21 \\
236 - 245 & 0,80 & 0,20 \\
246 - 256 & 0,81 & 0,19 \\
257 - 267 & 0,82 & 0,18 \\
268 - 278 & 0,83 & 0,17 \\
279 - 290 & 0,84 & 0,16 \\
291 - 302 & 0,85 & 0,15 \\
303 - 315 & 0,86 & 0,14 \\
316 - 328 & 0,87 & 0,13 \\
329 - 344 & 0,88 & 0,12 \\
345 - 357 & 0,89 & 0,11 \\
358 - 374 & 0,90 & 0,10 \\
375 - 391 & 0,91 & 0,09 \\
392 - 411 & 0,92 & 0,08 \\
412 - 432 & 0,93 & 0,07 \\
433 - 456 & 0,94 & 0,06 \\
457 - 484 & 0,95 & 0,05 \\
485 - 517 & 0,96 & 0,04 \\
518 - 559 & 0,97 & 0,03 \\
560 - 619 & 0,98 & 0,02 \\
620 - 735 & 0,99 & 0,01 \\
cbыше 735 & 1,00 & 0,00
\end{array}$$

Let's make a few substitutions. Since $N_{ож}$ both for the match and for the tour are rounded until they are obtained, the numbers are always integers and end in 0 or 5. However, when calculating the ratings of Soviet chess, rounding is done to 0.1 points, and therefore the ratings turned out to be simply integers.

To calculate $N_{ож}$ in tours, for simplicity, the “tourist coefficient” $K_{т}$ is introduced, equal to the arithmetic mean rating $C_{ct}$ of all participants in the tour. After this, $N_{ож}$ for each chess player is found from the table below, where $K_{ct}$ – $K_{м}$ is equal to the difference between $K_{ct}$ and $K_{т}$ (you need to subtract the smaller one from the larger number), multiplying $n_{ож}$ by the number of games played by each participant, and the rout. Thus, we seem to consider that the tour participant plays a match with one “average” partner. In the process, due to the large number of tournaments that are now being held, and the thousands of chess players playing in them, this computer will still be used to calculate the ratings (both international and Soviet).

In the USSR, ratings and masters are now published once a quarter; as of April 1, 1985, ratings of the extra class (2600 and above) had five grandmasters: A. Karpov - 2717, G. Kasparov - 2700, A. Belyavsky - 2641, R. Vaganyan and L. Poluavsky - 2614.

Competition problems

17. Checkmate in 2 moves.

18. Checkmate in 8 moves.

The deadline for sending the solution is November 25, 1985 (with a note on the envelope “Chess competition «Kvant», tasks 17, 18”).
