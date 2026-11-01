---
id: 1977-2-boltyanskiy-shest-zaytsev-v-pyati-kletkah-1a934450
issue: kvant_1977_2
year: 1977
number: "2"
title: Six rabbits in five cages
authors:
  - Болтянский В. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 19
page_last: 22
page_labels: 17, 20
tag: QPCJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: d436df6e69bb3a4f5bbf82af0c8fea23d968c4560a8081c2e3d9a0bb6ec8675e
prompt_sha256: draft-1
translated_from: content/ru/1977/02/articles/08_boltyanskiy-shest-zaytsev-v-pyati-kletkah-1a934450.md
source_content_sha256: cc21a037f3ab35e630da91693549245d43241e94aa8773413addcbe9c436c923
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 17⟧

Math circle

V. Boltyansky

Six rabbits in five cages

“Well, hares, wait a minute!”
Wolf

Agree that if you are allowed to place no more than one hare in each cell, then you will not be able to place six hares in five cells, and in general, for any natural n you will not be able to place n + 1 hares in n cells. We can say it another way: if n cells contain n + 1 or more hares, then we will find a cell containing at least two hares.

Let us denote the hares by the symbols p₁, ..., pₙ+1, and the cells by q₁, ..., qₙ. then each way to put hares into cells can be considered as a certain mapping (Fig. 1) of the set P = {p₁, ..., pₙ+1} into the set Q = {q₁, ..., qₙ}: a hare pᵢ ∈ P is associated (as its “image”) with the cell qᵢ ∈ Q in which this hare sits. Thus, the above statement about hares in cages has the following mathematical meaning: for any mapping of a set P containing n + 1 elements into a set Q containing n elements, there are two elements of the set P that have the same image.

This statement is called Dirichlet's principle*). It is fairly easy to prove using the method of mathematical induction. According to an unwritten tradition, mathematicians all over the world, when considering the Dirichlet principle, explain its meaning not in the language of sets and mappings and not with any other objects, namely with hares and cells.

The Dirichlet principle, despite its simplicity and greatness, is very often used in proving theorems and solving problems.

Example 1. Prove that if a line l, located in the plane of triangle ABC, does not pass through any

*) Peter Gustav Lejeune Dirichlet (1805-1859) - an outstanding German mathematician; He owns fundamental works in number theory and other areas of mathematics.

Fig. 1.

⟦folio 20⟧

How many next terms of the sequence will we find a number that is not prime, etc.

Example 6. Let $p$ and $q$ be natural numbers, and let the rational number $\frac{p}{q}$ be written as an infinite decimal. Let us prove that the model of this fraction will necessarily be periodic.

The proof of this fact (it is not considered in school) is easy to obtain using the Dirichlet reason. When dividing $p: q$ in a “column” manner, remainders from zero will always be obtained (otherwise the number $\frac{p}{q}$ would not be written as an infinite decimal fraction). Thus, each time the next digit of a quotient is found, the remainder will be one of the numbers 1, 2, ..., $q-1$). We will consider these possible values ​​of the remainders to be “cells”, so there are $q-1$ “cells” in total. “Hares” we will consider the remainders that are actually obtained after we have taken away the last significant digit of the dividend (Fig. 4). Let's consider the first $q$ “hares” (1 greater than the number of “cells”). Each “hare” ends up in some “cell” - each remainder is equal to one of the numbers 1, 2, ..., $q-1$. Due to Dirichlet reason, there are two “hares” that fall into the same “cage”. In other words, among the numbers 1, 2, ..., $q$ we can choose two numbers $i, j$ such that the $i$th and $j$th remainders (after we have removed the last significant digit
