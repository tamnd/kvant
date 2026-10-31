---
id: 1974-2-yaglom-zaplatyi-na-kaftane-5891fcec
issue: kvant_1974_2
year: 1974
number: "2"
title: Patches on the caftan
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 15
page_last: 23
page_labels: 13-21
tag: 9I0X
lang: en
source: kvant_digital
extraction: vision
content_sha256: e45fc05e0939819d292df993dbc8bf276c87bc51efa839c3081320f8ddef093e
prompt_sha256: draft-1
translated_from: content/ru/1974/02/articles/07_yaglom-zaplatyi-na-kaftane-5891fcec.md
source_content_sha256: 26639ebab021b0982afc8c989d048f1147a15cd113ab1f9474193c732c818c74
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

In No. 1 of the journal «Kvant» for this year the following problem by E. B. Dynkin was published:

**M185** *. On a cafman with area 1, 5 flames are placed, the area of ​​each of which is not less than $1/2$. Prove that you will find two flames whose common part area is not less than $1/5$.

We will analyze the solution to this problem and discuss some of its generalizations and variants *). Our presentation will be accompanied by tasks in which, in particular, individual details of the evidence will be noted; The numbers of the most difficult problems are marked with an asterisk.

We will denote both the caftan itself and its area (by convention equal to 1) by the letter $M$; we denote the patches on the caftan (and the areas of these patches) by $M_1$, $M_2$, $M_3$, $M_4$ and $M_5$, and, say, the promised part of the patches $M_1$ and $M_2$ (and the area of ​​this common part) by $M_{12}$; similarly, we denote the common part of the patches $M_1$, $M_2$ and $M_3$ (and its area) by $M_{123}$, etc. To the obstruction that, for example, by $M_1$ we denote both the patch (geometric function) and the area of this patch (number!), should not confuse us - from the text each time it will be clear in what sense we use the notation $M_1$.

**We begin to solve the problem**

From the fact that promising the fruit of all patches

$$M_1 + M_2 + M_3 + M_4 + M_5 \geq \frac{5}{2}$$

the large area $M = 1$ of the caftan, it follows that our plates overlap - and the task is to estimate the areas of their common parts (more precisely, to estimate the largest of the numbers $M_{12}$, $M_{13}, \dots, M_{45}$). We claim that

$$M - (M_1 + M_2 + M_3 + M_4 + M_5) + (M_{12} + M_{13} + M_{14} + \dots + M_{45}) \geq 0.$$ (1)

In fact, if the patches did not overlap, then there would be a non-negative difference $M - (M_1 + M_2 + M_3 + M_4 + M_5)$, equal to the area of ​​the part of the caftan not covered at all by the patches. But in fact, our plates intersect - and the sum $M_1 + M_2 + M_3 + M_4 + M_5$ turns out to be much greater than the total plot $S$ of the part of the caftan covered with plans (where, of course, $S \leq M = 1$): part $M_{12}$ of the caftan is taken into account in the sum $M_1 + M_2 + M_3 + M_4 + M_5$ twice, since it is included in the term $M_1$ and in the term $M_2$, part $M_{123}$ - three times, etc. Now try to prove that

$$S \geq \sum M_i - \sum M_{ij}.$$ (1')

*) A brief solution to this problem is given in «Kvant» No. 10, 1973.

⟦folio 14⟧

If you fail, read the next section of the stats, and then come back to this inequality.

From (1'), since $M \geq S$, inequality (1) follows.

Inequality (1) already allows us to estimate pairwise intersections of $M_{12}, M_{13}, \dots$ patches. Indeed, it follows that $(M_{12} + M_{13} + \dots + M_{45}) \geq \geq (M_1 + M_2 + M_3 + M_4 + M_5) - M \geq \geq \frac{5}{2} - 1 = \frac{3}{2}$.

And since the total number of pairwise intersections of patches $M_{ij}$ is equal to $C_5^2 = 10$, then the most of the numbers $M_{12}, M_{13}, \dots, M_{45}$ is no less than
$$\frac{3}{2}:10 = \frac{3}{20}.$$

The estimate we obtained, however, is x already the required estimate $\frac{1}{5} \left( = \frac{4}{20} \right)$.

Defeat

1. On the caftan of area 1 there are 9 patches of area $1/5$. Prove that you can find two patches whose common areas are at least $1/45$.

Included and excluded formula

Our estimate (1') for the area $S$ of the entire part of the caftan covered with plans is not accurate. Let's try to determine this area more accurately. The rule of the part of formula (1') will not include the area of ​​any part of the caftan covered by three plans at once: for example, $M_{123}$ will be included in the plus-sign terms $M_1, M_2, M_3$ and in the minus-sign terms $M_{12}, M_{13}, M_{23}$ - that is, we will completely follow from formula (1'). Therefore, a better estimate for $S$ can be the expression
$$\sum M_i - \sum M_{ij} + \sum M_{ijk}.$$
However, this value is not yet equal to $S$, since what part of the caftan $M$, covered with three planes at once, takes into account two

Yes: in fact, let’s say, the value $M_{1234}$ takes into account 8 terms $M_1, M_2, M_3, M_4; M_{123}, M_{124}, M_{134}, M_{234}$ of the last expression, included in it with a “plus” sign, and only 6 terms $M_{12}, M_{13}, M_{14}, M_{23}, M_{24}$ and $M_{34}$, included in this expression with a “minus” sign. Therefore, an approximation to the true value $S$ is the expression
$$\sum M_i - \sum M_{ij} + \sum M_{ijk} - \sum M_{ijkl},$$
which is already “almost equal” to $S$ - it exactly takes into account all sections of the caftan $M$, covered by plans of no more than four-hit plans, from the last expression “vinadem”: in fact, it is included in all terms of this expression, that is, both in 15 terms $M_1, M_2, M_3, M_4, M_5; M_{123}, M_{124}, \dots, M_{345}$, having a plus sign in front of them, and in 15 terms $M_{12}, M_{13}, \dots, M_{45}; M_{1234}, M_{1235}, M_{1245}, M_{1345}$ and $M_{2345}$, with a minus sign in front of them. Therefore, in order to obtain an exact expression for $S$, we must add the term $M_{12345}$ to the last sum. Here is the exact equality:
$$S = \sum M_i - \sum M_{ij} + \sum M_{ijk} - \sum M_{ijkl} + M_{12345}.$$
(here $i, j, k, l = 1, 2, 3, 4$ or 5). But the area σ of the part of the caftan not covered by any plan is equal to $M - S$; since $\sigma \geq 0$, we have $\sigma = M - \sum M_i + \sum M_{ij} - \sum M_{ijkl} + \sum M_{ijkl} - M_{12345} \geq 0.$

Formula (3) is obtained by sequentially excluding sections of the caftan $M$ by fatal plans and including those of them that turned out to be excluded by two criteria; it is sometimes called the included and excluded formula. This formula is used in many combinatorial considerations.

⟦folio 15⟧

The formula includes and excludes is also valid for a number of patches other than the heel. In the general case $n$ the patch formula includes and excludes, outwardly it takes on several bullets in its complexity, but in essence it has a completely transparent form:

$$\sigma = M - \sum M_{i_1} + \sum M_{i_1 i_2} - \sum M_{i_1 i_2 i_3} + \sum M_{i_1 i_2 i_3 i_4} - \dots + (-1)^{n-1} \sum M_{i_1 i_2 i_3 \dots i_{n-1}} + (-1)^n M_{123 \dots n} \geq 0$$

(here all indices $i_1, i_2, \dots, i_{n-1}$ can take any of the values ​​1, 2, 3, \dots, $n$, and for the intersection of $M_{i_1 i_2 \dots i_k}$ patches $M_{i_1} M_{i_2} \dots M_{ik}$ all values ​​$i_1, i_2, \dots, i_k$ are necessarily different).

Exercises
2. Prove formula (4) for $n = 6$.
3*. Prove formula (4).
4. Domponer is regularly visited by 220 schoolchildren. At homeponers there are six sports sections: athletics (l), volleyball (v), basketball (b), football (f), sambo section (s) and chess section (w). The number of participants in these sections is as follows: (l) - 30 people, (c) - 26 people, (b) - 32 people, (f) - 31 people, (c) - 28 people and (w) - 36 people. 53 schoolchildren attend several sections; of these, 24 schoolchildren attend three or more sections, 9 schoolchildren - at least four sections, and 3 schoolchildren - even five sections (the last three schoolchildren also include one eccentric who attends all six sports sections). How many of the schoolchildren attending Domponers do not participate in any sports section?

Solution to problem M185

We have seen that the “reduced” formula includes and excludes $M - \sum M_i + \sum M_{ij} \geq 0$ (1) does not give an accurate estimate of the value of interest to us max $M_{ij}$ (the largest of the value $M_{ij}$); therefore we will have to use the “complete” formula $M - \sum M_i + \sum M_{ij} - \sum M_{ijk} + \sum M_{ijkl} - M_{12345} \geq 0$. (3')

Let us now apply the includes and excludes formula (4) (where we now assume that $n = 4$) to the part $M_1$ of the caftan $M$, covered with its patches $M_{12}, M_{13}, M_{14}$ and $M_{15}$. We get

$$\sigma_1 = M_1 - \sum M_{1i} + \sum M_{1ij} - \sum M_{1ijk} + M_{12345} \geq 0,$$

where $\sigma_1$ is the part of patch $M_1$ not covered by other patches, and the numbers (or indices) $i, j, k$ run through all possible values ​​2, 3, 4 or 5. Similar inequalities can be written for sections $M_2, M_3, M_4$ and $M_5$ of the caftan:

$$\sigma_2 = M_2 - \sum M_{2i} + \sum M_{2ij} - \sum M_{2ijk} + M_{12345} \geq 0,$$

$$\sigma_5 = M_5 - \sum M_{5i} + \sum M_{5ij} - \sum M_{5ijk} + M_{12345} \geq 0.$$

Adding up the 5 inequalities obtained in this way, corresponding to the sections $M_1, M_2, \dots, M_5$ of the caftan, we obtain (check this):

$$\sum M_i - 2 \sum M_{ij} + 3 \sum M_{ijk} - 4 \sum M_{ijkl} + 5 M_{12345} \geq 0.$$ (5)

Let us now find a combination of inequalities (3') and (5) in which the sum $\sum M_{ijk}$ of “triple overlapped patches” is missing. Obviously, for this it is enough to add to (3') inequality (5) multiplied by $1/3$. We get the following inequality

$$M - \frac{2}{3} \sum M_i + \frac{1}{3} \sum M_{ij} - \frac{1}{3} \sum M_{ijkl} + \frac{2}{3} M_{12345} \geq 0.$$ (6)

It also follows from this that

$$M - \frac{2}{3} \sum M_i + \frac{1}{3} \sum M_{ij} \geq 0.$$ (7)

Indeed, part $M_{12345}$ of the caftan is included in each of its parts $M_{ijkl}$, due to which $\sum M_{ijkl} > 5M_{12345}$, and

⟦folio 16⟧

Formulation of the general task;
case of two layers

On a cafman M of area 1 there are n layers $M_1, M_2, \dots, M_n$, the area adb of each of which is not less than the number $\alpha$ known to us; it is required to estimate the area adb of most of the intersections of $M_{ij}$ layers.

In other words, for each configuration of $n$ layers on a caftan, we find the maximum $M_{ij}$, and then find the minimum of this maximum $M_{ij}$ over all possible configurations of layers*). This kind of “minimax” (that is, related to finding the minimum of certain maxima) problems play a very important role in modern mathematics.

The required number min max $M_{ij}$ depends, of course, on the given number $\alpha$, that is, it is a function of $\alpha$; since it also depends on the number $n$ of layers, we denote this function by $f_n(\alpha)$ (where, very conveniently, $0 \leqslant \alpha \leqslant 1$, and $n \geqslant 2$). The solution to Problem M185 reduces to proving the equality

$$f_5\left(\frac{1}{2}\right) = \frac{1}{5};$$

the general problem requires specifying a formula expressing $f_n(\alpha)$ in terms of $\alpha$ and $n$.

In order to understand what kind of answer we can expect in this general problem, we start with the (very simple!) case $n = 2$. So, we believe that on a caftan M of area 1 there are two layers $M_1$ and $M_2$, the area adb of each of which is not less than $\alpha$; we need to indicate the smallest possible area $f_2(\alpha)$ of intersection $M_{12}$ of these two layers.

It is clear that if $\alpha \leqslant 1/2$, then patches can occur at all intersections (Fig. 2, a); if $\alpha \geqslant 1/2$, then the smallest possible area $f_2(\alpha)$ of intersection

*) We assume that such a minimum exists, although this is far from very convenient.

⟦folio 17⟧

M$_{12}$ patches is equal to $2\alpha - 1$ (Fig. 2, b). Thus,

$$f_2(\alpha) = \begin{cases}
0 & \text{при } 0 \leqslant \alpha \leqslant 1/2, \\
2\alpha - 1 & \text{при } 1/2 \leqslant \alpha \leqslant 1,
\end{cases}$$

- that is, the graph of the function $y = f_2(\alpha)$ is a broken line (Fig. 3). This circumstance is called a broken line.

Exercise
5. Describe the function $y = f_3(\alpha)$.
Direction e: consider three sectors $M_1, M_2$ and $M_3$ of the circle $M$, the symmetry axes $l_1, l_2$ and $l_3$ of which in pairs form angles in $120^\circ$, and the central angles (measured in fractions of a full angle!) are equal to $\alpha$; start with small values ​​of $\alpha$ (Fig. 4) and see what happens as you increase $\alpha$ all the way up to $\alpha = 1$.

Case of heel patches
Let us now turn to the original case of 5 patches $M_1, M_2, M_3, M_4$

Fig. 3.

Fig. 4.

2 «Kvant» № 2

⟦folio 18⟧

be equal to 0, and all $M_{ij}$ must have the same value $\frac{1}{2}\alpha - \frac{1}{10}$. But if all $M_{ijk} = 0$, then each patch of area $\alpha$ (for example, patch $M_1$) “patches on patch” $M_{12}, M_{13}, M_{14}$ and $M_{15}$ areas $\frac{1}{2}\alpha - \frac{1}{10}$ must cover without overlapping, which is only possible if $4\left(\frac{1}{2}\alpha - \frac{1}{10}\right) \leq \alpha$ and, therefore, $\alpha \leq \frac{2}{5}$ (compare with analysis above the case of transforming the functions $f_5(\alpha)$ into 0).

Thus, we were able to continue the graph of the function $y = f_5(\alpha)$:

$$f_5(\alpha) = \frac{1}{2}\alpha - \frac{1}{10}$$ at $\frac{1}{5} \leq \alpha \leq \frac{2}{5}$.

Next, we will have to turn to inequality (7) (p. 15), which was the main tool for solving problem M185. From this inequality it follows that

$$\sum M_{ij} \geq 2\sum M_i - 3M \geq 2(5\alpha) - 3 = 10\alpha - 3,$$

where

$$f_5(\alpha) \geq \frac{1}{10}(10\alpha - 3) = \alpha - \frac{3}{10}.$$

Inequality (10) is satisfied for all $\alpha$ (i.e., the graph of the function $y = f_5(\alpha)$ lies entirely above the straight line $y = \alpha - \frac{3}{10}$; Fig. 7); however, it turns into equality only at $\frac{2}{5} \leq \alpha \leq \frac{3}{5}$ (see Exercise 6,a).

Next, we will have to apply the formula of inclusions and exclusions not only to the region $M_i$ of the caftan, but also to the regions $M_{ij}$ and $M_{ijh}$. Thus, applying this formula to the caftan $M_{12}$, covered with the third pays $M_{123}, M_{124}$ and $M_{125}$, we obtain

$$\sigma_{12} = M_{12} - \sum M_{12i} + \sum M_{12ij} - M_{12345} \geq 0.$$

Writing out 10 similar inequalities corresponding to 10 intersections of $M_{ij}$ patches, and then adding them all up, we get (check this!) that

$$\sum M_{ijh} - 4\sum M_{ijkl} + 10M_{12345} \geq 0.$$

⟦folio 19⟧

Fig. 8.

Now we have four inequalities (3′), (5), (11) and (12) relating the same quantities $M$, $\sum M_i$, $\sum M_{ij}$, $\sum M_{ijk}$, $\sum M_{ijkl}$ and $M_{12345}$.

Adding inequalities (3′); (5) multiplied by $1/2$; (11) multiplied by $1/6$, we arrive at the inequality

$$M - \frac{1}{2} \sum M_i + \frac{1}{6} \sum M_{ij} - \frac{1}{6} M_{12345} \geq 0,$$

(13)

from which both the term $\sum M_{ijk}$ and the term $\sum M_{ijkl}$ have dropped out. From (13), it obviously follows that even more

$$M - \frac{1}{2} \sum M_i + \frac{1}{6} \sum M_{ij} \geq 0$$

and, therefore,

$$\sum M_{ij} \geq 3 \sum M_i - 6M \geq 3(5\alpha) - 6,$$

where

$$f_5(\alpha) \geq \frac{1}{10}(15\alpha - 6) = \frac{3}{2}\alpha - \frac{3}{5}.$$

(14)

Thus, the graph of the function $y = f_5(\alpha)$ lies not below the straight line $y = \frac{3}{2}\alpha - \frac{3}{5}$ (Fig. 8).

Similarly, adding inequalities (3′); (5) multiplied by $3/5$;

(11) multiplied by $3/10$; (12), multiplied by $1/10$, we obtain the inequality

$$M - \frac{2}{5} \sum M_i + \frac{1}{10} \sum M_{ij} \geq 0,$$

(15)

from which all terms except $M$, $\sum M_i$ and $\sum M_{ij}$ have dropped out. From (15), it obviously follows that

$$\sum M_{ij} \geq 4 \sum M_i - 10M \geq 4(5\alpha) - 10 = 20\alpha - 10$$

and, therefore,

$$f_5(\alpha) \geq \frac{1}{10}(20\alpha - 10) = 2\alpha - 1.$$

Thus, the graph of the function $y = f_5(\alpha)$ lies not below the straight line $y = \frac{3}{2}\alpha - \frac{3}{5}$ (Fig. 8).

Exercises

6. Prove that

a) $f_5(\alpha) = \alpha - \frac{3}{10}$ at $2/5 \leq \alpha \leq 3/5$;

b) $f_5(\alpha) = \frac{3}{2}\alpha - \frac{3}{5}$ at $3/5 \leq \alpha \leq 4/5$;

b) $f_5(\alpha) = 2\alpha - 1$ at $4/5 \leq \alpha \leq 1$.

7. Describe the function

a) $f_4(\alpha)$; b) $f_6(\alpha)$.

⟦folio 20⟧

Case $n$ patches

This case is treated similarly to the case $n = 5$; Let us briefly outline the corresponding reasoning.

First of all, it is clear that in order for the $n$ patches $M_1, M_2, \dots, M_n$, the area of ​​each of which is not less than $\alpha$, not to overlap, it is necessary that their total area $\sum M_i \geq n\alpha$ does not exceed the area $M = 1$ of the caftan; That's why

$$f_n(\alpha) = 0 \text{ при } 0 \leq \alpha \leq \frac{1}{n}.$$

Next, consider the main inequality (4) (the included and excluded formula, p. 15). From this inequality it follows that

$$M - \sum M_i + \sum M_{ij} \geq 0 \tag{16}$$

(Why?); and, therefore,

$$\sum M_{ij} \geq \sum M_i - M \geq n\alpha - 1.$$

And since the total number of “pairwise intersections of patches” $M_{ij}$ in the general case is equal to the number $C_n^2 = \frac{n(n-1)}{2}$ of correspondences from $n$ by 2, then

$$f_n(\alpha) \geq \frac{1}{n(n-1)/2} (n\alpha - 1) = \frac{2}{n-1} \alpha - \frac{2}{n(n-1)}. \tag{17}$$

In this case, inequality (17) can turn into equality only if it turns into equality (16), that is, if in the included and excluded formula (4) all terms following $\sum M_{ij}$ turn to 0 (and if, in addition, all patches $M_i$ have an area $\alpha$ and completely cover the caftan $M$). But in this case, $n - 1$ of “pairwise patch intersections” $M_{12}, M_{13}, \dots, M_{1n}$ cover patch $M_1$ without overlapping (since all are $M_{ij} = 0$). And since in this case everything

$$M_{1i} = \frac{2}{n-1} \alpha - \frac{2}{n(n-1)},$$

That

$$(n - 1) \left[ \frac{2}{n-1} \alpha - \frac{2}{n(n-1)} \right] \leq \alpha,$$

and therefore $\alpha \leq \frac{2}{n}$ (and, of course, $\alpha \geq \frac{1}{n}$).

Next, we will have to apply the included and excluded formula to the patches $M_i$ (instead of the entire caftan $M$), to their intersections $M_{ij}, M_{ijh}$, etc. Let us apply, for example, this formula to the patch $M_1$, covered with “second-order patches” $M_{12}, M_{13}, \dots, M_{1n}$:

$$M_1 - \sum M_{1i} + \sum M_{1i1} i_2 - \sum M_{1i1} i_2 i_3 + \dots + (-1)^{n-2} \sum M_{1i1} i_2 \dots i_{n-2} + (-1)^{n-1} M_{123} \dots n \geq 0$$

(where $i_1, i_2, \dots, i_{n-2} = 2, 3, \dots, n$).

Adding $n$ of such inequalities corresponding to patches $M_1, M_2, \dots, M_n$, we obtain the inequality

$$\sum M_i - 2 \sum M_{i1} i_2 + 3 \sum M_{i1} i_2 i_3 - \dots + (-1)^{n-2}(n-1) \sum M_{i1} i_2 \dots i_{n-1} + (-1)^{n-1} n M_{123} \dots n \geq 0 \tag{18}$$

(cf. inequality (5) on p. 15). From inequalities (4) and (18) it is not difficult to use the term $\sum M_{i1} i_2 i_3$ - for this it is enough to add (4) with multiplication by 1/3 by inequality (18):

$$M - \frac{2}{3} \sum M_{i1} + \frac{1}{3} \sum M_{i1} i_2 - \frac{1}{3} \sum M_{i1} i_2 i_3 i_4 + \dots + (-1)^{n-1} \frac{n-3}{3} \times M_{123} \dots n \geq 0. \tag{19}$$

From (19) it follows that

$$M - \frac{2}{3} \sum M_{i1} + \frac{1}{3} \sum M_{i1} i_2 \geq 0 \tag{19a}$$

and, therefore,

$$\sum M_{i1} i_2 \geq 2 \sum M_{i1} - 3 M \geq 2 (n\alpha) - 3 = 2n\alpha - 3.$$

Thus,

$$f_n(\alpha) \geq \frac{1}{n(n-1)} (2n\alpha - 3) =$$

⟦folio 21⟧

$$\frac{4}{n-1} \alpha - \frac{6}{n(n-1)},$$

Moreover, equality (20) turns into only at $\frac{2}{n} \leqslant \alpha \leqslant \frac{3}{n}$ (see Exercise 8).

Continuing to do the same as above, we will finally find

$$f_n(\alpha) = 2 \frac{r-1}{n-1} \alpha - \frac{r(r-1)}{n(n-1)}$$

at $\frac{r-1}{n} \leqslant \alpha \leqslant \frac{r}{n}$, $r=1, 2, \ldots, n$.

Exercises

8. Prove that (20) becomes equality only for $\frac{2}{n} \leqslant \alpha \leqslant \frac{3}{n}$.

9*. Prove that $f_n(\alpha) = \frac{6}{n-1} \alpha - \frac{12}{n(n-1)}$ for $\frac{3}{n} \leqslant \alpha \leqslant \frac{4}{n}$.

10*. Prove equality (21).

Additional Notes

1. Of course, even the “general” formulas (21) are far from exhausting the scope of this note; it can be continued quite further.

2°. "Patch leveling" method. Problem M185 received quite a lot of solutions in letters from readers «Kvant»; Some readers also formulated the idea of ​​$n$ patches of area, no less than $\alpha$ on the caftan of area 1. However, only V. Khonin from the city of Pervouralsk, in his very interesting letter, managed to completely solve this “general” problem and find formulas essentially equivalent to formulas (21). At the same time, the path that V. Khonin followed is fundamentally different from the one developed in this note. Khonin proceeds essentially from figure 1, depicting the “optimal” covering of a caftan with five patches: from this figure it is clear that in the most favorable situation all parts of the caftan are covered with either two or three patches, with all intersections of $M_{ij}$ patches (where $i$ and $j=1, 2, \ldots, 5$) and all intersections of $M_{ijh}$ are equal to each other.

Based on this, Khonin develops a unique procedure for “re-cutting” patches in order to equalize their areas and the areas of their intersections, in which, excluding the values ​​of max $M_{ij}$ does not increase all the time; In this way he proves that in the general case their “optimal” location (which we arrive at in the process of constructing the “alignment” of patches) will be close to figure 1, which allows him to find formulas (21). At the same time, the method proposed by V. Khonin for solving the problem is very promising in the case of more complex problems.

While preparing the article for publication, the editor received a note from A. Makarevich, a 9th grade student from Lvov, in which an approach to solving problem M185 and its generalized solution, similar to that proposed by V. Khonin, was developed. Unfortunately, due to lack of space we cannot publish this interesting note.

3°. About the methods of “linear programming”. Figure 9 shows that the solution to the “general” problem is reduced to solving a system of linear inequalities relating the value $y (=f_n(\alpha))$ to the number $\alpha$. Questions related to the solution of a system of linear inequalities play an important role in modern applications of mathematical methods to economic problems; To solve them, special methods have been developed - the so-called “linear programming methods” *). In 1968, linear programming methods were used to solve a “general” problem by a student at Moscow University, Sergei Pirogov, and he managed not only to prove formula (21), but also to solve more problems.

*) See, for example, the popular book: S. Gass, Journey to the Land of Linear Programming, M., “Mir”, 1973; see also chap. 13 excellent books: A. Kofman, R. Faure, Let's Do Operations Research, M., "Mir", 1966.
