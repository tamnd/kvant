---
id: 1973-10-yaglom-otsenki-uglov-dffa4527
issue: kvant_1973_10
year: 1973
number: "10"
title: Angle estimates
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 32
page_last: 36
page_labels: 30, 31, 32, 34
tag: PB76
lang: en
source: kvant_digital
extraction: vision
content_sha256: b00c3c03bc865876bbd64fe0b729f17a7aa243d81d6a9ff6d7c5f1c8e9d9d02d
prompt_sha256: draft-1
translated_from: content/ru/1973/10/articles/08_yaglom-otsenki-uglov-dffa4527.md
source_content_sha256: a8b0d3a1ad58c0cdc98227e272e685ad6c9e72ec356455b91731866c3eb25b89
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

I. M. Yaelom Estimates of angles

Our starting point will be the following non-empty but respectable problem 1. Let $A, B, C$ be three arbitrary (non-coinciding) points on the plane; we denote the elements of the triangle $ABC$ (moche, $\angle BAC, \angle ABC$ and $\angle ACB$) by $\alpha$, $\beta$ and $\gamma$. Let $\alpha \geq \gamma \geq \beta$. What meanings do $\alpha$, $\gamma$ and $\beta$ take?

This problem well illustrates the topic of this article: it discusses the following (in general, not yet solved!)

The main problem. On the data plane $n$ points $A_1, A_2, \dots, A_n$. Let us denote by $\alpha_1, \alpha_2, \dots, \alpha_N$ the angles of the triangles formed by these points *). Let $\alpha_1 \geq \alpha_2 \geq \dots \geq \alpha_N$. What meanings should my $\alpha_1, \alpha_2, \dots, \alpha_N$ take?

To imagine what we might encounter when solving the main problem, let’s solve problem 1.

Solution to problem 1

Since $\alpha + \beta + \gamma = 180^\circ = 3 \cdot 60^\circ$, then the most of the three angles of a triangle cannot be less than $60^\circ$, and

*) The number $N$, of course, depends on $n$. It's not hard to see that

$$N = 3C_n^3 = 3 \frac{n(n-1)(n-2)}{1 \cdot 2 \cdot 3} = \frac{n(n-1)(n-2)}{2},$$

where $C_n^3$ is the number of combinations of $n$ by 3, but we don’t need this formula.

⟦folio 31⟧

If we need to be sharp, then $\gamma < 90^\circ$ (the case when three points lie on the same line will not save the situation, since in this case $\alpha = 180^\circ$, $\beta = 0^\circ$, $\gamma = 0^\circ$). However, $\gamma$ can be as close to $90^\circ$ (at figure 3 the smallest angle $\beta = \angle BAC$ is very small, and $\angle ABC = \angle ACB \approx 90^\circ$). Thus,

$$60^\circ \leq \alpha \leq 180^\circ, \quad 0^\circ \leq \gamma < 90^\circ, \quad 0^\circ \leq \beta \leq 60^\circ.$$

To verify the solution to Problem 1*, we still need to prove that $\alpha$ can take on more values ​​within $60^\circ \leq \alpha \leq 180^\circ$ (and similarly for angles $\beta$ and $\gamma$). However, this part of the solution is very simple - it coincides with the construction of a triangle $ABC$, in which the largest angle $\alpha$ (or the “average” angle $\gamma$, or the smallest angle $\beta$) has a given value, chosen within the specified limits; You can easily do this yourself.

Discussion of the solution to problem 1

First of all, let's change the notation. The conditions are to denote the vertices of a triangle by $A_1, A_2, A_3$, and its angles by $\alpha_1, \alpha_2, \alpha_3$. The largest of the angles $\alpha_1, \alpha_2, \alpha_3$ can be denoted as follows:

$$\alpha = \max_i \alpha_i,$$

and the smallest of the angles $\alpha_1, \alpha_2, \alpha_3$ is like this:

$$\beta = \min_i \alpha_i,$$

and $i = 1, 2, 3.$

max is an abbreviation of the Latin word *maximum* - “maximum”, that is, the greatest. The sign $i$ under.max shows that $i$ is changing, that is, a set of values ​​$\alpha_i$ is given (here - $\alpha_1, \alpha_2, \alpha_3$), of which we take the largest (and not, say, the largest of the generally possible angles of the triangle $A_1A_2A_3$ - in

*) We present here a detailed solution to problem 1. Instructions for solving other problems are placed at the end of the magazine (but don’t look there - try to solve the problem yourself first). Star marks more difficult tasks; A simple sign next to the problem number will indicate that the author does not know the solution (which does not mean that this problem is difficult; think about this problem too).

in this case we will write max $\alpha$. Zakmak max $\Delta A_1A_2A_3$ is usually used for the largest of a finite number (here - of three). For the largest of an infinite number of quantities, you can also use the max sign, but this is dangerous - here it is also necessary to prove that this largest quantity exists (see below).

min is an abbreviation of the Latin word *minimum* - “minimum”, that is, the greatest.

In Problem 1, I have no difficulty in determining the largest possible value $\alpha$, that is

$$\max \alpha = \max \max \alpha_i = 180^\circ,$$

$$\Delta A_1A_2A_3 \quad \Delta A_1A_2A_3 \quad i$$

and the smallest possible value $\beta$, that is

$$\min \beta = \min \min \alpha_i = 0^\circ.$$

Of greatest interest here is the smallest possible value of $\alpha$, that is

$$\min \alpha = \min \max \alpha_i = 60^\circ,$$

$$\Delta A_1A_2A_3 \quad \Delta A_1A_2A_3 \quad i$$

The formulation of such “minimax” problems is typical for modern “pure” and (especially!) applied mathematics.

A significant part of Problem 1 also consists of estimating the largest possible value of $\gamma$ (the smallest is easy to find: from figure 2 it follows that min $\gamma = 0^\circ$). However, here we are in for a shame: it turns out that the desired maximum value $\gamma$ does not exist: the angle $\gamma$ can be as close as $90^\circ$, but it never turns out to be equal to $90^\circ$. Mathematicians then say that $90^\circ$ is the (mon) supremum of $\gamma$:

$$\sup \gamma = 90^\circ.$$

sup is an abbreviation of the Latin word *supremum* - “supremum”, that is, higher. The notation sup $x_i = \xi$ means that $x_i \leq \xi$ for any $i$, but $x_i$ can be any angle

⟦folio 32⟧

close to ξ, that is, ξ is the smallest number, no less than any $x_i$. It can be shown that if the quantities $x_i$ are bounded from above, that is, there is at least one upper bound of the quantity, then among these upper bounds there is a smallest (one), that is, sup $x_i$ exists.

The notation inf $x_i$ is used similarly. Inf is an abbreviation of the Latin word infimum - “infimum”, that is, lower.

inf $x_i$ is a powerful low edge, that is, the largest number not exceeding any $x_i$. In cases where this does not cause difficulty in reading, we will not write $i$, $\Delta A_1 A_2 A_3$, etc. under the signs sup, inf, max, min.

It is not difficult to understand what this sorpiriz is connected with. It is clear that the values ​​max $\alpha_i$ and min $\alpha_i$ exist - after all, from the three angles $\alpha_1$, $\alpha_2$ and $\alpha_3$ one can always choose the largest and smallest. And the number of tracks $\{A_1, A_2, A_3\}$ points on the plane is infinite. And here we can no longer guarantee that there will be a track that corresponds to the largest value of the angle $\gamma$. After all, we can move from one track of points to another, which corresponds to a larger value of the angle $\gamma$, as many times as necessary, and each time it may turn out that there is still a track left that is better than the previous one.

In principle, none of the values sup $\alpha$, sup $\beta$, sup $\gamma$, inf $\alpha$, inf $\beta$, inf $\gamma$ is sufficiently necessary - and we should regard it as luck that the values sup $\alpha = 180^\circ$, sup $\beta = 60^\circ$, inf $\alpha = 60^\circ$ and inf $\beta = 0^\circ$ are achieved, that is, that max $\alpha$, max $\beta$, min $\alpha$ and min $\beta$ exist. For value $\gamma$, as we have seen, inf $\gamma = 0^\circ$ is achieved, but sup $\gamma = 90^\circ$ is not.

Similarly, for the quantity $\frac{1}{n}$, where $n$ is a natural number, sup $\frac{1}{n} = 1$ is achieved (at $n = 1$), but inf $\frac{1}{n} = 0$ is not; Thus, the quantity $\frac{1}{n}$ has a maximum and no minimum.

Let us finally consider the question of which specific tracks of the point $P_3 = \{A_1, A_2, A_3\}$ (or $\{A, B, C\}$) the maximum or minimum values ​​of $\alpha$, $\beta$ and $\gamma$ are achieved. It is easy to see that min $\alpha$ and (at the same time) max $\beta$ are achieved for a single triple of points - for the vertices of the regular triangle $ABC$ (see Fig. 1), of course, up to replacing the triangle $ABC$ with a similar one, which, however, does not change any of its angles. max $\gamma$, as we already know, does not exist at all. And the values ​​max $\alpha$, min $\beta$ and min $\gamma$ are realized by an infinite number of different (further dissimilar) triples of points, since the middle point on figure 2 can be located anywhere on the segment connecting two other points.

Now we will move on to other tasks.

Task 2. a) Let $P_4 = \{A, B, C, D\}$ be an arbitrary system of four points on the plane; we denote the values ​​of the smallest of the 12 angles defined by empirim and mochikas by $\beta$. Prove that $0^\circ \leq \beta \leq 45^\circ$.

b) Let $P_5$ be an arbitrary system of four points on the plane; We denote the smallest of the angles defined by the empiric and mochikas by $\beta$. Prove that $0^\circ \leq \beta \leq 36^\circ$.

c) Let $P_6$ be an arbitrary system of four points on the plane; We denote the smallest of the angles defined by the empiric and mochikas by $\beta$. Prove that $0^\circ \leq \beta \leq 30^\circ$.

For which systems of four, heel and six points on the plane are the largest and smallest values ​​of the angle $\beta$ achieved?

Beginning of solving problem 2. Let us assume that the points under consideration are driven into the ground

⟦folio 34⟧

This result is the same as for systems of 7 points (maybe here also inf α = 120°, u min α does not exist).

Let us turn again to the “general” system $P_n = \{A_1, A_2, \dots, A_n\}$ of $n$ points on the plane that appears in the main problem; We denote the most angles defined by these points by $\alpha$, and the most by $\beta$. Since, obviously, the most possible value of $\alpha$ is equal to 180°, and the most possible value of $\beta$ is 0°, then the task of estimating the angles $\alpha$ and $\beta$ is to find sûр $\beta$ (we denote this value by $\beta$ or the plane; it, of course, depends on $n$, - by $\beta(n)$) and inf $\alpha$ (we denote this value by $\alpha$ or $\alpha(n)$). Find several values ​​of $\beta(n)$:

$$\beta(n) = \frac{180^\circ}{n},$$

and this value is always achievable (see problem 3). However, the problem of finding the value $\alpha(n)$ is not so simple and has not yet been solved in general form. Problems 4 and 5 state that $\alpha(4) = 90^\circ$, $\alpha(5) = 108^\circ$ and $\alpha(6) = \alpha(7) = \alpha(8) = 120^\circ$; in this case, the values ​​$\alpha(4), \alpha(5)$ and $\alpha(6)$ have been achieved, but the values ​​$\alpha(7)$ and $\alpha(8)$ have not been achieved.

The problem of determining the value $\alpha(n)$ was first posed by the American geometer L. Blumenthal; its solution was carried out by the Hungarian mathematicians P. Erdős*) and G. Szekeres. P. Erdős proposed that for all $n \geq 6$ $\alpha(n) = \frac{k-1}{k} \cdot 180^\circ$, where $2^{k-1} \leq n \leq 2^k$, and that this value $\alpha(n)$ is achieved only for $n = 6$. However, it has only been proven so far that

$$\alpha(2^k) = \frac{k-1}{k} \cdot 180^\circ$$ at $k \geq 2$

*) Pál Erdős is a prominent modern Hungarian mathematician. Erdős owns many striking results in various fields of mathematics (number theory, mathematical analysis, probability theory, geometry, etc.); As a result of his activities, the number of hitherto unsolved problems only increased, but he posed more new problems than he solved old ones.

and what if $2^{k-1} < n < 2^k$ (where $k \geq 3$), then $\frac{k-1}{k} \cdot 180^\circ \geq \alpha(n) > \frac{k-2}{k-1} \cdot 180^\circ$ (the latter estimate can even be slightly strengthened).

Let us now turn to the rest of the angles involved in the problem.

Problem 6. Let $P_4$ be an arbitrary system of four points on the plane; $\alpha = \alpha^{(1)}$ and $\alpha^{(2)}$ are the two largest of the nine angles specified by these points, $a = \beta = \beta^{(1)}$ and $\beta^{(2)}$ are the two smallest angles; at the same time $\alpha^{(1)} \geq \alpha^{(2)}$, $\beta^{(1)} \leq \beta^{(2)}$. Prove that

a) $72^\circ \leq \alpha^{(2)} \leq 180^\circ$;
b) $0^\circ \leq \beta^{(2)} \leq 45^\circ$.

For which point systems are the largest and smallest values ​​of $\alpha^{(2)}$ and $\beta^{(2)}$ realized?

Problem 7. Prove that for all $n \geq 2$ max $\alpha(i) = 180^\circ$ for $1 \leq i \leq \frac{n(n-1)(n-2)}{6}$,

$$u \min \alpha^{(i)} = 0^\circ$$ at $P_n$

$$\frac{n(n-1)(n-2)}{6} < j \leq N = \frac{n(n-1)(n-2)}{2}$$

Thus, the question of estimates of all $N$ angles $\alpha^{(i)}$ indicates the determination of the value inf $\alpha^{(i)}$, where

$$1 \leq i \leq \frac{n(n-1)(n-2)}{6}$$

(inf $\alpha^{(i)}$ can be denoted by the symbol $\alpha^{(i)}(n)$) and sup $\beta^{(i)}$ when

$$1 \leq j \leq \frac{n(n-1)(n-2)}{3}$$

*) Note that $\frac{n(n-1)(n-2)}{6} + \frac{n(n-1)(n-2)}{3} = \frac{n(n-1)(n-2)}{2} = N$. Let us also point out that the number of quantities $\beta^{(i)}$ to be determined is always twice the number of intersubordinate numbers $\alpha^{(i)}$, for example: 2 and 1 for $n = 3$, 8 and 4 for $n = 4$, etc.
