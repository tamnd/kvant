---
id: 1977-11-limanov-reshenie-zadach-olimpiadyi-a639b44f
issue: kvant_1977_11
year: 1977
number: "11"
title: Solving Olympiad problems
authors:
  - Лиманов Л. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 65
page_last: 66
page_labels: 63-64
tag: YRV0
lang: en
source: kvant_digital
extraction: vision
content_sha256: b2137730bee79a3b1a4aa4698ea16ef69b6982681c726040f85580c554c13063
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/19_limanov-reshenie-zadach-olimpiadyi-a639b44f.md
source_content_sha256: 01091850d89ed740f57603287da92b81b3436a468a998c964492597b38eb73f1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 63⟧

theorems. «Kvant» can provide you with more help with this.

The closing ceremony of the Olympics took place on April 19. The deputy representative of the jury, M.I. Bashmakov, read out the solution of the jury of the XI All-Union Mathematical Olympiad. So, based on the results of two days of states, it was decided to award 13 first, 24 second, 24 third prizes and honor 32 participants with honorable reviews of the first degree and honorable reviews of the second degree - 36 participants. We publish the names of the winners of the XI All-Union Olympiad on p. 72.

In addition, various organizations and enterprises in Estonia established special prizes (for the best result, for the most original solution, the best in resources, the representative of the most isolated corner of the Soviet Union, etc.), which were awarded to many schoolchildren. The special prize of the Jorral «Kvant» - a binder of the Jorral for 1976 with the author of the editor-in-chief, Academician I.K. Kikon - was received by an 8th grade student from Tallinn, Mark Levin (he participated in the competition outside the competition, and therefore he was not awarded any official place). Eight classics were also sent by subscription to the journal «Kvant» for 1978: Lyakhovets Andrey (Krasnodar), Khlebutin Sergey (Perm), Bernotas Andrius (Vilnius), Vlasov Vyacheslav (Kyiv), Irmatov Andar (Namangan UzSSR).

Based on the results of the Olympiad, a team was formed to participate in the 19th International Olympiad for Schoolchildren in Mathematics. The team included: A. Ambroladze (Tbilisi), A. Auzinsh (Riga), Y. Vinnishin (Kyiv), V. Galperin (Moscow), A. Kodryan (Rybnitsa), G. Rybnikov (Moscow), D. Flaass (Novosibirsk) and A. Churbanov (Moscow). The XIX International Olympiad was held in Belgrade (Yugoslavia). We will talk about this Olympiad in one of the next issues of the journal.

L. Limanov

Solution
tasks
olympids

This article examines three problems of the final type of the XI All-Union Mathematical Olympiad, which were not included in the Zhvant Problem Book. Solutions to the problems published in the Zhvant Problem Book will appear in accordance with the zhorral number next year. (For problem conditions, see pp. 58-61.)

8th grade. Problem 4.

Instead of removing chips, we will bet them, starting with one black chip. Let's add white chips to it so that each of them has a black neighbor (one or two). Then we will place several black chips so that each of them has a white neighbor and so that the “old” black chip does not have a white neighbor. On the next move, white chips are placed again, subject to these two conditions, etc.

Let us denote by $b_i$ the number of black chips placed after $i$ moves, and by $w_i$ the number of white ones. If black chips are placed on the $i+1$ move ($i$ is even), then $b_{i+1} = b_i + 2w_i$, $w_{i+1} = w_i$. If the chips are white ($i$ is even), then $b_{i+1} = b_i$, $w_{i+1} = w_i + 2b_i$; Each move we surround all the chips of one color with two chips of a different color. It is clear that it is impossible to assign a larger number.

The conditions are written down the position of the chips on the circle after the $i$th move in the form of a vector $\langle b_i; w_i \rangle$ and calculate several vectors:

$$\langle 1;0 \rangle \rightarrow \langle 1;2 \rangle \rightarrow \langle 5;2 \rangle \rightarrow \langle 5;12 \rangle \rightarrow \langle 29;12 \rangle \rightarrow \langle 29;70 \rangle \rightarrow \langle 169;70 \rangle \rightarrow \langle 169;408 \rangle \rightarrow \langle 985;408 \rangle.$$

Let us now make sure that in problem a) the answer is positive, and in problem b) the name of the number of moves is eight.

Indeed, after the fourth turn, $29+12=41$ chips will be exposed. When moving from $\langle 5;12 \rangle$ to $\langle 29;12 \rangle$, 24 chips are added. Of these, no more than $2 \times 5=10$ are the answer for fulfilling the second condition - they will separate the old black chips from the white ones. Let's call these features mandatory. Let's mark them

⟦folio 64⟧

Let us prove by induction on $i$ the following inequality:

$$\frac{1}{2^i} a_n - 2\varepsilon < a_{n+i} < \frac{1}{2^i} a_n + 2\varepsilon,$$

where $n$ is any number greater than $m$. Really,

$$\frac{1}{2^{i+1}} a_n - 2\varepsilon = \frac{1}{2} \left( \frac{1}{2^i} a_n - 2\varepsilon \right) -$$

$$-\varepsilon < \frac{1}{2} a_{n+i} - \varepsilon < a_{n+i+1} <$$

$$< \frac{1}{2} a_{n+i} + \varepsilon < \frac{1}{2} \left( \frac{1}{2^i} a_n + 2\varepsilon \right) + \varepsilon =$$

$$= \frac{1}{2^{i+1}} a_n + 2\varepsilon.$$

But for any $\varepsilon > 0$ one can specify a $i$ such that $\left| \frac{a_n}{2^i} \right| < \varepsilon$. It follows from this that for an arbitrary $\varepsilon > 0$ one can specify a $k$ such that for all $l > k$ the inequality $-3\varepsilon < a_l < 3\varepsilon$ holds. By the definition of a limit, this means that $\lim_{n \to \infty} a_n = 0$.

9th grade. Task 5.

We will assume that there are no free nodes on the boundary of the square. Let us prove that any system of broken lines that satisfies the conditions of the problem and this condition passes through four times the number of nodes.

Zanuterum nodes on the border of the square as shown in figure 2. It is easy to say that the broken line connecting points numbered $i$ and $j$ passes through $1+i-j+2l$ nodes, where the value of $l$ depends on the broken line. Let us now calculate the double number of nodes through which our broken lines pass. Since every point of the square, except the vertices, has a broken line, this number is equal to $4.99 + \sum i - \sum j + 2\sum l (i,j)$, where $l(i,j)$ is the value of $l$ for a broken line starting at point $i$ and ending at point $j$. It is easy to see that $\sum l(i,j)$ is even, since each term appears twice in it: $l(i,j) = l(j,i)$. Consequently, our system of broken lines passes through the number of nodes, and the total number of nodes that do not lie on the boundary of our sheet is $99^2$ - an odd number. Thus, at least one node is actually untraversed.
