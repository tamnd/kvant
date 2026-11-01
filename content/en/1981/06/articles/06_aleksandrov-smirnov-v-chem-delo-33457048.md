---
id: 1981-6-aleksandrov-smirnov-v-chem-delo-33457048
issue: kvant_1981_6
year: 1981
number: "6"
title: What's the matter?
authors:
  - Александров Н.
  - Смирнов П.
rubric: smes
page_first: 12
page_last: 12
page_labels: "10"
tag: GS8N
lang: en
source: kvant_digital
extraction: vision
content_sha256: d6c5f50e57e565bc1b3b0177055e1abd4e84b3c00e2c2edbba52c2e9252a5091
prompt_sha256: draft-1
translated_from: content/ru/1981/06/articles/06_aleksandrov-smirnov-v-chem-delo-33457048.md
source_content_sha256: e09c0cb76c313e208a741a0483e3beddab736cd2ddc17e92ae4af7bb91d501be
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

the edges $r$ are connected in $G'$ by a simple chain - the remaining part of the contour), and the vertices of the graph $G'$ are the same as those of $G$. If $G'$ is not yet a tree, that is, $G'$ also has a contour (Fig. 11 b), then we can take an arbitrary edge $r_2$ of this contour and, discarding it, obtain a knitted graph $G''$ with the same vertices as $G$, etc. Since the number of edges is finite, this process should stay at some point; in other words, after throwing out some edge $r_k$ we get a connected graph $G^*$ containing all the vertices of the graph $G$ and no longer having a contour, that is, it is a tree. The graph $G^*$ is called the maximal tree of $G$, and the edges $r_1, r_2, ..., r_k$ that had to be discarded from $G$ to get the maximal tree $G^*$ are called bridges.

If $B$ is the number of vertices in the graph $G$, then the maximal tree $G^*$ also has $B$ vertices. According to (1), the graph $G^*$ has $B-1$ edges, and therefore the number of edges of the graph $G$ is equal to $B-1+k$ (in order to obtain $G$ from $G^*$, it is necessary to “return” $k$ discarded bridge edges). Hence,

$$\chi(G) = B - (B-1+k) = 1-k. \quad (2)$$

Since $k \ge 1$, we get $\chi(G) \leq 0$. Thus, taking into account (1), we see that for any connected graph $G$ the following relation holds true:

$$\chi(G) \leq 1,$$

where equality is achieved if and only if $G$ is a tree.

Further, according to (2), the number of jumpers is equal to

$$k = 1 - \chi(G).$$

What's the matter?

According to the “basic property of the antiderivative” (“Algebra and principles of analysis 9-10”, paragraph 57), if the arbitrary functions of two functions coincide, then these functions must differ by a constant. Arbitrary functions:

$$a) y_1 = \frac{1}{1-x^2}$$

$$n) y_2 = \frac{x^2}{1-x^2},$$

tasks

17. Prove that if the graph $G$ contains $l$ components, then $\chi(G) \leq l$. When is equality achieved?

18*. We will say that in the graph $G$ a system of currents is given if each edge is assigned a direction (indicated by an arrow) and some non-negative direction (tok), and the Kirchoff rule is fulfilled: for each vertex, the sum of the currents entering it is equal to the sum of the outgoing ones. Prove that if the graph is a tree, then it contains only a trival system of currents (all currents are equal to zero).

19. Let $G$ be a connected graph, $G^*$ its maximal tree, and $r_1, r_2, ..., r_k$ the bridges (that is, the edges of $G$ not contained in $G^*$). Prove that if currents on the edges $r_1, r_2, ..., r_k$ are arbitrarily specified, then they can be uniquely supplemented with currents on the remaining edges so as to obtain a system of currents in $G$.

Note. For each jumper $r_i$ there is a unit contour containing it and not containing other jumpers. If we pass along this circuit a current of the magnitude and direction as indicated on the jumper $r_i$, and then take the sum of all these “circuit currents”, then we will obtain the required system of currents on the graph $G$. If there were two different systems of currents coinciding on the jumpers, then their difference would be a nontrivial system of currents on the tree $G^*$.

So, an excursion into graph theory, carried out under the wing of Angell Topology, turns out to be useful for solving mathematical and even physical problems. We hope you enjoyed it and that you'll want to continue it. In the next issue of the journal we will focus on deeper issues of graph topology. But to study them, we will have to listen more carefully to the “devil of abstract algebra.”

What's the matter?

According to the “basic property of the antiderivative” (“Algebra and Principles of Analysis 9-10”, paragraph 57), if the arbitrary functions of two functions coincide, then these functions must differ by a constant. Arbitrary functions:

$$a) y_1 = \frac{1}{1-x^2}$$

$$n) y_2 = \frac{x^2}{1-x^2},$$

tasks

17. Prove that if the graph $G$ contains $l$ components, then $\chi(G) \leq l$. When is equality achieved?

18*. We will say that in the graph $G$ a system of currents is given if each edge is assigned a direction (indicated by an arrow) and some non-negative direction (tok), and the Kirchoff rule is fulfilled: for each vertex, the sum of the currents entering it is equal to the sum of the outgoing ones. Prove that if the graph is a tree, then it contains only a trival system of currents (all currents are equal to zero).

19. Let $G$ be a connected graph, $G^*$ its maximal tree, and $r_1, r_2, ..., r_k$ the bridges (that is, the edges of $G$ not contained in $G^*$). Prove that if currents on the edges $r_1, r_2, ..., r_k$ are arbitrarily specified, then they can be uniquely supplemented with currents on the remaining edges so as to obtain a system of currents in $G$.

Note. For each jumper $r_i$ there is a unit contour containing it and not containing other jumpers. If we pass along this circuit a current of the same magnitude and direction as indicated on the jumper $r_i$, and then take the sum of these “circuit currents”, then we will obtain the required system of currents on the graph $G$. If the system of currents coincided on the jumpers, then their difference would be a non-trivial system of currents on the tree $G^*$.

So, an excursion into graph theory, carried out under the wing of Angell Topology, turns out to be useful for solving mathematical and even physical problems. We hope you enjoyed it and that you'll want to continue it. In the next issue of the journal we will focus on deeper issues of graph topology. But to study them, we will have to listen more carefully to the “devil of abstract algebra.”

N. Alexandrov,
P. Smirnov
