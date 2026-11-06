---
id: 1990-9-k-chitatelyam-zhurnala-2d8a5449
issue: kvant_1990_9
year: 1990
number: "9"
title: '[To the magazine readers]'
rubric: osnovnye-stati
page_first: 18
page_last: 18
page_labels: "16"
lang: en
source: kvant_digital
extraction: vision
content_sha256: 36eceb7db54b828b26983b1eb0dc7ac7498a7559bb35d2723a84dea0ab0e77d2
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/05_k-chitatelyam-zhurnala-2d8a5449.md
source_content_sha256: cc31f68fa2c2a8bf2804b3bd26f05cc6b50455775c3c375437baae8c90f0e4cb
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 16⟧

---
running_head:
folio:
---

depends on how high our requirements for expected winnings are. As above, we call a set of cards a $m$-system $D$ if, for any result of type $y$, at least one of these cards wins at least $m$ numbers. Consider “Sportloto - 6 out of 49”. The 6-system $D_0$ contains $C_{49}^6 = 13983816$ cards—all vectors from the set of $E_{29,6}$ double vectors of length 49 with six ones. In any 5-system $D_1$ there are 2 vectors $c_1$ and $c_2$ with $d(c_1, c_2) = 2$. In fact, any two vectors containing the same number of ones are at an even distance from each other. Pozny, if there are no vectors $c_1$ and $c_2$ such that $d(c_1, c_2) = 2$, then $\min_{c_1, c_2} d(c_1, c_2) = 4$, and there is a vector $y \in E_{29,6}$ such that the system vector close to it is from $y$ at a distance of 2. Then, if $y$ is a result of the type, in $D_1$ not there are cards with five winning numbers.

Exercise 14 (Hamming bound for vectors with the same number of ones).
a) Prove that the number of vectors from $E_{29,6}$ located at a distance $\leq 2s$ from a given vector $c \in E_{29,6}$ is equal to $M(s) = \sum_{i=0}^{s} C_6^i C_{43}^i = \sum_{i=6-s}^{6} C_6^i C_{43}^i$.
b) Prove that $|D_1|$ is the number of cards in the 5-system $D_1$ is not less than $[C_{49}^6 / M(1)] = 53992$ ([x] is the smallest integer greater than or equal to $x$).

Similarly, it is shown that any 4-system $D_2$ cannot contain less than 1014 cards, and any 3-system $D_3$ cannot contain less than 54 cards. For “Sportloto - 5 out of 36” $|D_1| \geq 2417, |D_2| \geq 79, |D_3| \geq 8$.

In conclusion, we give an example of a 2-system $D$ for the “Sportloto” min, in which you need to guess 6 out of 8 numbers:

$$
D = \begin{bmatrix}
1 & 1 & 1 & 1 & 1 & 0 & 0 \\
1 & 1 & 1 & 0 & 0 & 1 & 1 \\
1 & 1 & 0 & 0 & 1 & 1 & 1 \\
0 & 0 & 1 & 1 & 1 & 1 & 1
\end{bmatrix}
$$

Since any result of type $y$ contains two zeros, there is a vector $c \in D$ such that in some coordinate vectors $y$ and $c$ both contain a zero. Then the distance between $y$ and $c$ is at most two, i.e. $D$ is truly a 2-system. Let us show that there is no 2-system with a smaller number of vectors. Indeed, the three vectors together contain only six zeros, and even if they are all in different positions, there are still two positions left that do not contain a zero. By placing the zeros of the vector $y$ at these positions, we see that it is at a distance of 4 from each of the three vectors of the system. This means that the 2-system $D$ of length 8 is optimal.

Dear readers!

In the future, 1991, the magazine «Kvant», like its predecessor, will be distributed only by subscription. Unfortunately, at the time of signing this issue for publication, we do not know definitively how the rise in paper prices and the increase in printing costs and costs associated with delivering the magazine will affect the subscription price. However, in any case, we will write an article so that «Kvant» does not stand still, and next year new sections and materials offered to you will appear on its pages. We hope that he will have more variety and activities. In addition, we plan to increase the amount of materials available to a more limited extent at Soyuzpechat agencies, post offices and post offices. Journal index «Kvant» in Soyuzpechat catalogs 70465.
Editorial staff of the magazine «Kvant»
