---
id: 1982-9-kamyishko-pol-dirak-i-zadacha-o-treh-ryibakah-fe0a667b
issue: kvant_1982_9
year: 1982
number: "9"
title: Paul Dirac and the problem of the three fishermen
authors:
  - Камышко И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 33
page_last: 33
page_labels: "31"
tag: 7SRE
lang: en
source: kvant_digital
extraction: vision
content_sha256: ff603c3e12bfbbf6394963ed10cc8b9c15577e4fb0795f6312e5ab3184e3872f
prompt_sha256: draft-1
translated_from: content/ru/1982/09/articles/09_kamyishko-pol-dirak-i-zadacha-o-treh-ryibakah-fe0a667b.md
source_content_sha256: 7bf86d67d92aa8e611288dccdb8e722059b9434d29b889023a75cccbecad08a5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 31⟧

Most likely, it was precisely this episode from the life of Paul Dirac, rich in creative victories, that contributed to the emergence of one legend, which has ended many years ago in different versions according to popular science books.

He said that in his youth he was faced with the following task: Three fishermen were fishing on a dark night. Tired, they went to bed without dividing the catch. At dawn, one of them woke up and, not wanting to disturb his comrades, divided the fish into three equal parts; Having taken his part, he went home. During the division, one fish turned out to be extra and he threw it out into the sea. Then the second one woke up. Not knowing that the first one had already left with his share, he also divided the fish into three parts, took one of them for himself, and left, and he, like the first one, threw the extra fish he had into the sea. Finally, the third fisherman woke up. Not knowing what the first two had done, he did as they did, that is, he divided the fish into three parts, took a third for himself, and took the remaining fish from him into the sea, after which he went home. The question is, how many fish were caught?

Reply (attributed to Dirac): “About two fish were caught.” It's easy to check that everything is formally correct. The first fisherman, having discovered only two fish minutes (!), throws out one fish and privately takes one third of the remaining (-3) fish. The second and third fishermen will do exactly the same thing, each of whom will also fish for an incredible amount of time. And although, according to the famous physicist’s own testimony, this solution was told to him by mathematics professor J. Whitehead from Oxford*), it is possible to understand the authors of the “legend of Dirac and the negative fishes”. It is difficult to find a simpler and more elegant example that would as well illustrate the treeliness of the idea and the belief in the “shameful effectiveness of mathematics in the natural sciences” (as another Novel laureate, the American physicist Yu. Wigner, put it) - qualities that are a pillar of modern physics and physicists.

But the problem about the fishermen is lovable in itself. Let's try to solve it. Let's translate the conditions into equation language. Let $N = N_0$ be the number of all fish caught, $N_1$ the number of fish remaining after the first division, $N_2$ - after the second, $N_3$ - after the third. Then, obviously, $N_1 = \frac{2}{3}(N_0 - 1)$ and, in general, for $k = 0, 1, 2$
$$N_{k+1} = \frac{2}{3}(N_k - 1).$$

We need to find an integer $N$ such that both the numbers $N_1, N_2$ and $N_3$ are integers. We also require that they all be non-negative. Further, under this constraint, the problem is placed and has an infinite number of solutions. We will try to derive a general formula for the number $N$.

Let us abandon the non-negativity condition for now (!). Note that the problem allows for a solution, and only one, in which all $N_k$ are equal to the same number $D$. From (1) for the number $D$ we obtain the equation $D = \frac{2}{3}(D - 1)$, whence $D = -2$. This is the "Dirac solution". Now let $(N_k)$ be an arbitrary sequence satisfying relation (1). Let us consider the difference $N'_k$ of two solutions to the problem - $N_k$ and the Dirac solution: $N'_k = N_k - D = N_k + 2$. Since

$$N'_{k+1} = N_{k+1} - D = \frac{2}{3}(N_k - 1) - \frac{2}{3}(D - 1) = \frac{2}{3}(N_k - D) = \frac{2}{3}N'_k,$$

the sequence $(N'_k)$ is a geometric progression with value $\frac{2}{3}$. Hence,

$$N_k = N'_k - 2 = \left(\frac{2}{3}\right)^k N'_0 - 2 = \left(\frac{2}{3}\right)^k (N + 2) - 2.$$

(For the end see p. 62)
