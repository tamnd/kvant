---
id: 1980-8-vayntrob-luchshe-porovnu-ad14513e
issue: kvant_1980_8
year: 1980
number: "8"
title: Better - equally
authors:
  - Вайнтроб А. Ю.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 25
page_last: 27
page_labels: 23-25
tag: 2FU5
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7b73569ef8ae5854ade53cb1b65fc7149bb7d7e937a09a94e30117aa313b9c35
prompt_sha256: draft-1
translated_from: content/ru/1980/08/articles/11_vayntrob-luchshe-porovnu-ad14513e.md
source_content_sha256: 2eb27e22649831f3965918c80311a6c9e935bf28010b648e13915395bbb28bd4
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 23⟧

Better - equally

In various problems of analysis and applied mathematics, questions of this type arise:

Let the given two numbers v and p: 0 < v < p. Consider all possible (finite) sets of numbers $x_1, x_2, ..., x_k$ such that 0 < x_i ≤ v for any i = 1, 2, ..., k and the sum $\sum_{i=1}^{k} x_i$ of all numbers in the set is greater than p.

For each such set there is a number D such that 1) the sum S of certain numbers of the set (maybe, in particular, all) differs from p on D: |S−p| = D and 2) any other sum of certain numbers of the set differs from p by more than D.

For each set of this, the number D (“approximation error”) will be the largest?

As we will see, what we are looking for will be a set of identical numbers: “better - equally.”

Here we will look at several specific problems (including the difficult problem M583 from the Problem Book «Kvant») of the indicated type.

1. Consider sets of stones, the mass of each of which is no more than 2 kg, and the total mass of the set is more than 10 kg. From such a set, several stones are selected, the total mass of which differs from 10 kg by the number D that is possible for this set. What is the maximum value that the number D can take for all possible sets of stones?

(This problem was presented at the Moscow City Mathematical Optimization in 1979.)

It is clear that the number D for any set of stones will not exceed 2 kg, since the mass of any stone is not more than 2 kg. In addition, very much D cannot be equal to 2 kg. Therefore, in order to use with sets in which all the stones are the same, we replace that the most D is obtained in the case when the stones are still quite heavy, and up to 10 kg half a stone is not enough. Four stones differ from 10 kg by more than 2 kg, and for the heel of stones from the equation 5x = 10−x/2 we find x = 20/11, that is, D = 10/11.

Let us now prove that for any set D does not exceed 10/11, that is, we will show that from an arbitrary set of stones we can select several whose total mass differs from 10 kg by no more than 10/11.

We will select the stones one by one: first we will take the heaviest one, then the heaviest of the rest, and so on until the mass of the selected stones does not exceed 10 kg. If among those selected there is a stone weighing less than 20/11 kg, then either their total mass is less than (10+10/11) kg, or at the previous step (before the last stone was taken) we have a set with a mass greater than (10−10/11) kg (=10+10/11−20/11), but less than or equal to 10 kg.

So, the maximum value of D is 10/11, and this value is achieved on a set of identical stones.

Exercise 1. Show that in the general case the highest value of D is achieved on a set of identical stones, and this value is equal to p/(1−2·[1/2−p/v]) ([x] is the integer part of the number x).

2. Let us now solve problem M583 from Problem Book «Kvant». It differs from problem 1 by one additional constraint, a significant increase: it is known that the total mass of the set is 50 kg.

We already know that D does not exceed 10/11. However, in this case

⟦folio 24⟧

this estimate is not accurate, since the number 50 is not divisible by 20/11 (if the total mass of the set were not 50, but, say, 100 kg, then the answer would remain the same).

Considering all possible partitions of 50 kg into stones with equal masses, we are convinced that the largest value of $D$ for such sets is equal to $D_0 = 20/27$ kg. (This is achieved on a set of 27 stones of mass 50/27.) Our goal is to prove that $D_0$ is the exceptional greatest value of $D$. To do this, it is enough to show that an arbitrary set can be replaced by a set of stones of the same mass without reducing $D$ (the input $D$ for sets of identical stones does not exceed $D_0$).

Let's consider an arbitrary set. Let us select from it those stones whose total mass differs from 10 kg by the smallest possible number (that is, by $D$). Let us divide stones with a mass greater than $2D_0$ into two groups. The first group includes those of them that are among those selected (empty $a_1$, $a_2$, ..., $a_m$ their masses). The second group includes stones with masses $b_1$, $b_2$, ..., $b_n$ (large $2D_0$), not included in the selection. For brevity, we will sometimes write "stone $a_i$" (corresponding to $b_j$), meaning "a stone whose mass is $a_i$" (corresponding to $b_j$). Let $A$ be the sum of the masses of stones $a_i$ (sometimes $A$ will denote a set consisting of stones $a_1$, $a_2$, ..., $a_m$; the sums of masses $B$ and $C$ defined below can also be used to denote the corresponding sets), $B$ is the sum of the masses of the stones $b_i$, and $C$ is the sum of the masses of the remaining stones (that is, those whose mass does not exceed $2D_0$).

Let us now show that there is a set for which $a_1 = a_2 = ... = a_m = b_1 = ... = b_n$, $C = 0$, and the value $D$ is not less than the original one. This will mean that $D \leq D_0$, since for sets consisting of identical stones, $D$ does not exceed $D_0$. In this case, two cases are possible:

1. The total mass of the selected stones is 10-D.

To construct the required set, we will have to prove several auxiliary statements.

Lemma 1. All stones included in $C$ belong to the chosen ones (that is, $10—D = A+C$).

Indeed, if at least one of the stones included in $C$ is not selected, then by adding it to the selected ones, we will obtain several stones whose mass differs from 10 kg by no more than $2D_0—D<D$. And this contradicts the choice of the set in question.

Lemma 2. $a_i \geq b_j$ for any $i$ and $j$ ($1 \leq i \leq m$, $1 \leq j \leq n$).

Indeed, if some $i$ and $j$ satisfied the inequality $a_i < b_j$, then by adding it to the selected ones, we will obtain several stones whose mass differs from 10 kg by no more than $2D_0—D<D$. And this contradicts the optimality of the selected set.

Lemma 3. $b_j > C+2D_0$ for any $j$ ($1 \leq j \leq n$).

Let's remove all stones included in $C$ from the selected set and add stone $b_j$ there. If $A+b_j \leq 10—D$, then by adding stones from $C$ one at a time, we will at some point get a set whose mass is greater than 10-D (since $A+b_j+C > A+C=10—D$), but less than 10+D (since each time a stone is added with a mass not exceeding $2D_0<2D$). This means $A+b_j>10—D$, and therefore (due to the minimality of $D$) $A+b_j>10+D=A+C+2D>A+C+2D_0$, whence $b_j>C+2D_0$.

From Lemma 2 it follows that $a_i>C+2D_0$ for all $i$.

Lemma 4. If the sum of the masses $k$ of stones from $A$ and $l$ of stones from $B$ is less than 10+D, then $k+l \leq m$.

If this sum is less than 10+D, then, due to the minimality of $D$, it is less than or equal to 10—D. Let $k+l > m$. Replacing stones $b_j$ in this sum in turn with stones $a_i$ not included in it, we will eventually place the last of the stones $a_i$ and thus bring the sum to the value $A+b_j+...>A+C+2D_0>10+D_0$ (see Lemmas 1 and 3). Since everyone

⟦folio 25⟧

since we added a stone with mass no more than $2D_0$ ($a_i - b_j < 2D_0$), at some point this amount will be strictly between $10 - D$ and $10 + D$. Contradiction.

Let us finally prove that it is possible to construct a set consisting of stones of the same mass without reducing $D$.

Let's replace each of the stones $a_i$ ($i = 1, \dots, m$) with a stone with mass $a = A/m$, each of the stones $b_j$ ($j = 1, \dots, n$) with a stone with mass $b = B/n$, and leave the stones from $C$ unchanged. Let us show that for such a set the number $D$ has not decreased.

Let's assume that $D$ has decreased. Then for some $k$, $l$ and $C' < C$ the sum $ka + lb + C'$ lies strictly between $10 - D$ and $10 + D$. Let's take $k$ the lightest stones from $A$. The sum of their masses does not exceed $ka$ (why?). Similarly, the sum of the masses $l$ of the lightest stones from $B$ does not exceed $lb$. But $ka + lb < 10 + D$, therefore $k + l \leq m$ (see Lemma 4). In this case $10 - D = A + C = ma + C \geq ka + la + C' \geq ka + lb + C' > 10 - D$. Contradiction.

If $a > b$, then $b$ cannot be included in any sum that is equal to $10 - D$ (replacing $b$ with $a$, we obtain a contradiction). Therefore, we can read (give the exact meaning to these words!) to reduce all the stones of mass $a$, read to notify the stones of mass $b$, so that $C$ remains unchanged. This will result in a set that has more value $D$ than the original one. After doing this several times, we get a set that has $a = b$.

If there is $C > 0$ in this set, increase $a$ (the number of stones with mass $a$ is $m + n$) by $\varepsilon$, where $\varepsilon < C/(m + n)$; in this case, $C$ will decrease by $(m + n)\varepsilon$. But then $D$ will increase by $n \cdot \varepsilon$, which is what is required. After a few steps we get a set that has $a = b$ and $C = 0$.

Case I has been analyzed completely.

II. The total mass of the selected stones is $10 + D$.

This case can be viewed in much the same way. But it is easier to notice that if the selected dokot stones are the best approximation (for a given set) to 10 s and zbyt koM, then the remaining stones of the set give the best approximation with a disadvantage of 50-10 (that is, 40 kg in our problem). Since $D_0$ is still at least 2/4 kg (this is the only additional condition that was used in Case I), all the proven statements remain valid after replacing 10 with 40.

So, the solution problem. The largest possible value of $D$ turns out to be $D_0 = 20/27$ kg.

Note that our reasoning allows us to solve the following general problem: find the maximum of the smallest deviations from $p$ over all possible sets of stones with a mass not exceeding $v$ and a total mass $P$. We have proven that if there is a set for which $D > v/4$, then the maximum value $D$ must be sought among sets of identical stones.

Exercises

2. Prove that for $v = 2$ kg, $p = 10$ kg, $P \geq 24$ kg there is a set for which $D \geq v/4$.

3. Complete the solution to the problem in the general case.

Here is another problem on this topic: there are several of which are no more than 1 ton, and their total mass is 10 tons; What is the smallest number of three-tonners that can surely be used to enlarge these boxes?

The following exercises will help you solve this problem (and its generalization) (the first two of them resemble the problems already discussed):

4. Let the only constraint on the total mass of the boxes be the condition $P > 3$ t. What is the largest load $\Gamma$ that can certainly be increased on one tritonic?

5. What will be the answer in the previous problem if it is known that $P = 10$ t?

6. Let now the mass of each box does not exceed $v$, the total mass is equal to $P$ and we have at our disposal a machine with a carrying capacity of $p$. Let $\Gamma$ be the mass of the maximum load that we managed to load onto the car. Prove that the smallest value of $\Gamma$ is achieved when all the boxes have the same mass.

7. What is the smallest supply of $p$-tonks that must be available in order to be sure to transfer all the boxes from Exercise 6?

Try to find the possibility of theorems that confirm the principle “better is equal.”
