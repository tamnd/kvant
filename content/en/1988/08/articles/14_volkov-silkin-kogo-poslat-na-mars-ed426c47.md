---
id: 1988-8-volkov-silkin-kogo-poslat-na-mars-ed426c47
issue: kvant_1988_8
year: 1988
number: "8"
title: Who should we send to Mars?
authors:
  - Волков М. В.
  - Силкин Н. Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 53
page_last: 58
page_labels: 51, 53, 54, 55, 56
tag: LO25
lang: en
source: kvant_digital
extraction: vision
content_sha256: dd28849efe4e9c243c4851e98e84d17d59e84c7a75ff59d65507f10271d84fe1
prompt_sha256: draft-1
translated_from: content/ru/1988/08/articles/14_volkov-silkin-kogo-poslat-na-mars-ed426c47.md
source_content_sha256: 8f8a47d60488102aceff40acc22606322dd71172d293b911eb2e8e85923bac86
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

Who's next for Mars?

Candidate of Physical and Mathematical Sciences
M. V. VOLKOV, N. N. SILKIN

This article brings us back to the topic discussed in the article by M. Gardner in the fourth issue of «Kvant» - to “colored graphs” and Ramsey theory. Here he talks about several typical problems of this theory and, in particular, the solution to problem M1099 is given (its condition was also placed in No. 4, 1988), general methods of estimation in such problems and their applications are discussed.

Basics of Mechanical Diplomacy

While making his next space journey, Gromozeka, a space explorer with extensive experience, discovered an unfamiliar planetary system. He set a course for it and soon “landed” on the third planet from the central star. Having become alert, Gromozeka saw an aborigine nearby and headed towards him. The expected conversation ensued, from which Gromozeka learned that there were 9 planets in Ukh-ty (that, it turned out, was the name of the system), and all of them were inhabited.

“Before,” said the native Gromozeke, “all our planets lived together.” But after Veselchak and Glot visited here, some planets broke off diplomatic relations. True, among any four planets, some two are still friends with each other, but this is not enough: after all, only the united forces of three planets can resist the invasion of marsupial hippos that threatens us!

“Curse the robbers,” exclaimed Gromozeka. “However, not all is lost!” In your system there are three planets that are pairwise friends with each other and, therefore, can unite!

⟦folio 53⟧

figure, or, as they are called in mathematics, graphs. More precisely, a collection of points and lines connecting them is called a graph if 1) each line connects two points; 2) any two points are connected by at most one line. In this case, points are usually called vertices of the graph, and lines are called edges of the graph. See figure 4 for one example of a graph. The vertices $A, B, C, D$ on this figure are connected in pairs by edges. Vertices are also said to form a complete subgraph. But among the vertices $E, F, G, H$, not one is connected by an edge to another of the same vertices. Such vertices constitute an empty subgraph.

Now the problem about six planets can be formulated as follows: any graph with six vertices contains either a complete subgraph with three vertices or an empty subgraph with three vertices. What Gromozeka proved about the Ukh-Ty planetary system essentially means that any graph with nine vertices contains either a complete subgraph with three vertices or an empty subgraph with four vertices. Then it is natural to ask: what minimum number $p$ should be taken so that any graph with $p$ vertices contains either a complete subgraph with three vertices or an empty subgraph with fifth vertices. But let’s not rush to answer it, because then the following question will arise: what minimum number $q$ must be taken so that any graph with $q$ vertices contains either a complete subgraph with three vertices, any empty subgraph with six vertices, etc. Let’s try to better generalize our problem in order to immediately answer all such questions.

So, let's look at the general situation right away. Let $m$ and $n$ be natural numbers greater than 1. Let $r(m, n)$ denote the minimal number with the property that any graph with at least $r(m, n)$ vertices contains either a complete subgraph with three vertices, any empty subgraph with six vertices, etc. Let’s try to better generalize our problem in order to immediately answer all such questions.

*) A demanding reader will say: “There is no guarantee that such a number exists,” and he will be right. But from further reasoning it follows not only the estimate of the number $r(m, n)$, but also its existence.

⟦folio 54⟧

Case two. The number of vertices connected by an edge to vertex $X$ is less than $r(m-1, n)$. But then at least $r(m, n-1)$ vertices are not connected to $X$. Among these vertices, either $m$ vertices form a complete subgraph, or $n-1$ vertices form an empty subgraph (and together with $X$ vertex, an empty subgraph with $n$ vertices is obtained).

Let's see how inequality (1) is applied. Let us calculate, for example, the number $r(3; 3)$. From formulas $r(2, n)=n$ and $r(m, 2)=m$ and from inequality (1) we obtain that $r(3, 3) \leqslant r(2, 3)+r(3, 2)=3+3=6$. So we have proven that in any graph with six vertices there is either a complete or an empty subgraph with three vertices, but now from general considerations. It is easy to give an example of a graph with five vertices, in which there is neither an empty nor a complete subgraph with three vertices (Fig. 5). Therefore the number $r(3; 3)$ is 6.

What we know and what we don't know

How accurate is inequality (1)? Let's try to use it to get Gromozeki's approval. We have:

$$r(3, 4) \leqslant r(2, 4)+r(3, 3)=4+6=10.$$

Misfire! After all, Gromozeka proved that $r(3, 4) \leqslant 9!$ It turns out that if the numbers $r(m-1, n)$ and $r(m, n-1)$ are even, then the inequality is true

$$r(m, n) \leqslant r(m-1, n)+r(m, n-1)-1.$$

It is proved in the same way as (1), you only need to take into account that a graph with $r(m-1, n)+r(m, n-1)-1$ vertices, in which each vertex is connected exactly to $r(m-1, n)-1$ vertices, does not exist.

Exercise 4. Prove inequality (2).

Note that inequality (2) can be given this convenient form: if $r(m-1, n) \leqslant A$ and $r(m, n-1) \leqslant B$, where $A$ and $B$ are even numbers, then $r(m, n) \leqslant A+B-1$.

Obtaining inequality (2), Gromozeki’s statement can be proven in one line:

$$r(3, 4) \leqslant r(2, 4)+r(3, 3)-1=4+6-1=9.$$

figure 6 shows a graph with eight vertices, in which there is neither a complete subgraph with three vertices, nor an empty subgraph with four vertices. Therefore the number $r(3, 4)$ is 9.

We have already noted that for $m$ and $n$ greater than 2, the exact formula for the number $r(m, n)$ is unknown. Moreover, the exact value of this number is known only for some small $m$ and $n$.

We provide a table in which, please, all known on the plate are collected

Today's information about the meanings of $r(m, n)$. (The value of $r(9, 3)=36=r(3, 9)$ was found quite recently using a computer. But the exact value of the number $r(3, 8)$ is still known.)

It is easy to notice that this table is symmetrical relative to one of the diagonals. This is not accidental: for all $m$ and $n$ the formula $r(m, n)=r(n, m)$ is true.

Exercise 5. Prove this formula.

Now we're ready to start

Solution to problem M1099

In the detachment preparing to receive Mars, there are 6,783 cosmonauts,

⟦folio 55⟧

What is known is that among any four of them, three can be selected to make up a complex experiment for the last module. Prove that it is possible to select 5 astronauts, any three of which form a complex crew.

The reader is probably already convinced of the usefulness of generalizations. Let us now abstract from the specific data of the M1099 problem and consider it “in general.”

Let $m$ and $n$ be natural numbers greater than 2. Let us denote by $R(m, n)$ the minimum number with the property that in any squad of $R(m, n)$ cosmonauts one can choose either $m$ an integer, or $3$ of which form a complex crew, or $n$ an integer, none of which $3$ do not form a complex carriage. The reader may expect us to reformulate this problem in graph language and extract relevant information from previous results. But this time he will be wrong. The numbers $R(m, n)$ are not directly related to graphs, although they have some relation to the numbers $r(m, n)$.

First of all, we can understand that for all $m$ and $n$ the equalities are true:

$$R(3, n) = n, \quad R(m, 3) = m, \quad R(m, n) = R(n, m),$$

similar to the equalities noted above for the numbers $r(m, n)$.

Exercise 6. Justify these equalities.

Since there is a similarity between the numbers $R(m, n)$ and $r(m, n)$, we can expect that the numbers $R(m, n)$ can be estimated using the numbers $R(m-1, n)$ and $R(m, n-1)$ in the same way as we estimated the numbers $r(m, n)$, using inequality (1). Indeed, the inequality is true

$$R(m, n) \leq r(R(m-1, n), R(m, n-1)) + 1. \quad (3)$$

His proof is similar to the proof of inequality (1). We need to prove that in any squad of $r(R(m-1, n), R(m, n-1)) + 1$ cosmonauts there will be either $m$ an integer, among which either is complex, or $n$ an integer, none

⟦folio 56⟧

$$R(5, 4) \leq r(R(4, 4), R(5, 3)) + 1.$$
The number $R(5, 3)$ is 5, and to estimate $R(4, 4)$ we apply (3) again:
$$R(4, 4) \leq r(R(3, 4), R(4, 3)) + 1 = r(4, 4) + 1.$$
The number $r(4, 4)$ can be estimated using (1). We get
$$r(4, 4) \leq r(3, 4) + r(4, 3) = 9 + 9 = 18.$$
(In fact, as the table shows, 18 is the exact value of $r(4, 4)$.) So, $R(4, 4) \leq 19$, and $R(5, 4) \leq r(19, 5) + 1$. It remains to estimate the number $r(19, 5)$. This can be done by repeatedly applying inequalities (1) and (2):
$$r(5, 3) \leq r(4, 3) + r(5, 2) = 9 + 5 = 14,$$
$$r(6, 3) \leq 14 + 6 - 1 = 19,$$
$$r(7, 3) \leq 19 + 7 = 26,$$
$$r(8, 3) \leq 26 + 8 - 1 = 33,$$
etc., up to $r(19, 3)$; it turns out $r(19, 3) \leq 182$.
Then we write:
$$r(4, 4) \leq r(3, 4) + r(4, 3) = 9 + 9 = 18,$$
$$r(5, 4) \leq 18 + 14 - 1 = 31,$$
$$r(6, 4) \leq 31 + 19 = 50,$$
... ...
$$r(19, 4) \leq 1249;$$
$$r(5, 5) \leq r(4, 5) + r(5, 4) = 31 + 31 = 62,$$
$$r(6, 5) \leq 62 + 50 - 1 = 111,$$
... ...
$$r(19, 5) \leq 6782.$$
Therefore, $R(5, 4) \leq 6783$.
The estimate $R(5, 4) \leq 6783$ is not accurate. If we use the values ​​of the numbers $r(m, n)$ from the previously given table, then, arguing in a completely similar way, we can obtain a significantly better estimate: $R(5, 4) \leq 6337$. The authors were able to prove that $R(5, 4) \leq 6242$, but they do not know whether this estimate will be accurate.

**Ramsey's Theorema**

Starting with simple messages, we discovered that they are consequences of some general laws: inequalities (1) and (3). These patterns allowed us to solve problem M1099. But it turned out that they themselves are just partial cases of an even more general result obtained in 1930 by the English logician F. Ramsey (1903-1930). In order to formulate Ramsey’s theorem, let’s imagine that not 5, but $m$ people need to be sent on a flight to Mars, of which not 3, but $s$ should be disembarked, which constitute a complex crew for the landing model. Let us denote by $R(s; m, n)$ the minimum number of cosmos from which we can choose $m$ such people such that any $s$ of them form a complex experiment. It is clear that for $s=3$ the number $R(s; m, n)$ coincides with the number $R(m, n)$; it is also easy to report that at $s=2$ this number is equal to the number $r(m, n)$.

Exercise 7. Check that $R(1; m, n) = m + n - 1$.

Let us now pose the question: for any s does the number $R(s; m, n)$ exist? And if it exists, how is it found? Ramsey's Theorem answers these questions. The number $R(s; m, n)$ exists for any s and for any m≥s and n≥s. This can be estimated using the inequality

$$R(s; m, n) \leq R(s - 1);$$
$$R(s; m - 1, n), R(s; m, n - 1)) + 1.$$

Inequality (4) is very similar to inequality (3). It proves essentially the same thing. You just need to consider not pairs of spaces, but an ekppage of $s-1$ spaces. It is clear that inequalities (1) and (3) are partial cases of inequality (4) for $s=2$ (you need to take into account Exercise 7) and $s=3$ of the corresponding one. Ramsey's theorem has many applications in various fields of mathematics: in mathematical logic and number theory, in algebra and combinatorics, in geometry and even in programming. These applications are a separate discussion, but here, as an example of how Ramsey’s theorem is applied, we present only one elegant result, which belongs to the generation of mathematics by P. Erdős and D. Szekeres.

Erdős-Szekeres Theorema. For any natural number
