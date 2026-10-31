---
id: 1975-8-yaglom-o-zadache-rado-9b3c83f2
issue: kvant_1975_8
year: 1975
number: "8"
title: About the Rado problem
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 42
page_last: 47
page_labels: 40-45
tag: OZQ8
lang: en
source: kvant_digital
extraction: publisher
content_sha256: 89f27905dccfbe27838e05d22d48ff893640efa8c220f3b39453c6d652a5bb01
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/08_yaglom-o-zadache-rado-9b3c83f2.md
source_content_sha256: d827a06e94f6300ac7e7b1c5142857d314ffa5be328ae38e4df959920b951498
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦figure⟧

## About the Rado problem

In «Kvant» No. 5 for 1975, in the section “Quantum Problem Book”, problem M321 (author A.V. Brailov) was published. Let us recall its condition.

There is a rectangular table of area 1. Prove that for any $\eps\gt0$ one can specify a system of rectangular napkins covering this table (the edges of the napkins are parallel to the edges of the table), such that any of its subsystems consisting of non-overlapping napkins has an area less than $\eps$.

This note describes different variations of the "non-overlapping napkin systems" problem. Some of them have a whole history, others are quite simple and can be solved with the help of one idea, like ordinary “Olympiad” problems.

Apparently, a hypothetical (and related only to mathematics, and not to biology) example of living creatures for which the external world is a two-dimensional plane, and not three-dimensional space, belongs to the famous German naturalist and mathematician G. Helmholtz: these are water striders - “water spiders”, the sliding movements of which along the surface of the water can be seen in any stagnant body of water. Helmholtz’s “water striders” are just as unable to imagine the “three-dimensional” world we are accustomed to, just as a person cannot imagine “four-dimensional space.”

We will start with an even more primitive external world than that of water striders: with a one-dimensional analogue of problem M321. Even in such a “light” version, it by no means becomes meaningless.

### Cut coatings

Now we have both “tables” and “napkins” - not rectangles, but straight segments. We are interested in this

Statement. Let a segment $o$ of length 1 (“table”) and a number $\eps\gt0$ be given. Then we can specify a system of segments (“napkins”) covering the “table” $o$ such that any subsystem of non-overlapping segments (non-overlapping “napkins”) has a total length less than $\eps$.

Is this Statement true or false?

Let us first test the simplest “napkin” systems. At figure 1, *a* the “table” is covered with three “napkins” of length $\dfrac13$. From these, you can choose a subsystem of two non-overlapping “napkins” with a total length of $\dfrac23$. (You can, of course, choose a subsystem from one “napkin”, but the length of such a subsystem is less.) So, if $\eps\gt\dfrac23$, then our statement is true: we have indicated a system of segments such that any of its subsystems consisting of disjoint segments has a total length not greater than $\dfrac23$, i.e. less than $\eps$.

Exercise 1. Prove that for $\eps\gt\dfrac12$ the Statement is also true. (Construct a corresponding covering of the “table” segment $o$ with smaller “napkin” segments.)

It is clear that each example of a system of segments $K$ guarantees the validity of our statement only for $\eps\gt d_k$, where $d_k$ is some positive number depending on this system $K$. So, for example, on figure 1, *a* $d_k=\dfrac23$; on figure 1, *b* $d_k=\dfrac35$. In general, $d_k$ is the greatest length of the subsystem $K'\subset K$, consisting of disjoint segments. It is clear that the smaller $\eps$, the more difficult it is to construct an example. It may happen that for $\eps$ greater than some $\eps$ our Statement is true, but for smaller $\eps$ it is no longer true. Let us prove that for the one-dimensional version of our problem this is exactly the case.

At $\eps=\dfrac13$ The statement is false.

In other words, *no "napkin" system can serve as the required example for $\eps=\dfrac13$, i.e., any "napkin" system contains a subsystem of non-overlapping "napkins" covering a portion of the "table" $o$ of length $\dfrac13$* $\Big($ or more $\dfrac13\Big)$.

⟦figure⟧
Fig. 1

⟦figure⟧
Fig. 2

Let some system of segments $K$ covering the segment $o$ of length 1 be given. Let us choose the largest segment from $K$ and denote it $i_1$. Let us now remove from the system $K$ all segments of the covering that intersect with the selected segment $i_1$ (they cover a segment of length no more than $3|i_1|$, where $|i|$ is the length of the segment $i$). From the remaining coverage segments, we again select the largest (we denote it $i_2$) and discard all those segments that intersect with $i_2$ (they cover a segment of length no more than $3|i_2|$), etc., until we have exhausted all coverage segments. The chosen subsystem of disjoint segments $i_1$, $i_2$, $\ldots$ is such that $$
3|i_1|+3|i_2|+\ldots\ge1,
$$
since the segments of length $3|i_1|$, $3|i_2|$, $\ldots$ in total cover the entire given system $K$ and, therefore, the entire segment $o$ of length 1. Therefore, the sum of lengths $|i_1|+|i_2|+\ldots$ is not less than $\dfrac13$.

figure 2 shows the process of selecting such a subsystem $\{i_1,i_2,i_3\}$ for a system of seven segments.

Exercise 2.

1. Prove that from any system of “napkins” covering the “table” one can choose a subsystem of “napkins” that also covers the “table” and such that no point of the “table” is covered by more than two “napkins”.
2. Prove that for $\eps=\dfrac12$ the statement is false.

Exercise 3. Prove that if the “table” is still a segment of length 1, and the “napkins” can also be “holey,” i.e., each “napkin” can consist of one or more segments, then the Statement formulated at the beginning of this paragraph is true for all $\eps\gt0$.

By solving exercises 1 and 2, you will prove the following fact:

Theorem 1. *Let the “table” and “napkins” be segments, the length of the “table” is equal to $1$.*

1. From any system of “napkins” covering the “table”, one can select a subsystem of non-overlapping “napkins” with a total length of at least $\dfrac12$.
2. If $\eps\gt\dfrac12$, then it is always possible to specify a system of “napkins” such that any of its subsystems of non-overlapping “napkins” has length less than $\eps$.

In other words, *The statement is true for $\eps\gt\dfrac12$ and false for* $\eps\le\dfrac12$.

Exercise 4. Prove a similar theorem for the “table” - a circle of length 1, and the “napkins” - the arcs of this circle.

### Square napkins

In 1928, the famous Hungarian mathematician Tibor Rado (T. Radó) reported in a letter to the editor of the leading Polish mathematical journal Fundamenta Mathematicae, the head of the Polish mathematical school, Waclaw Sierpinski, that he could not solve an apparently simple geometric problem related to the theory of functions of several variables. Having outlined the considerations and results known to us about covering a segment by segments, T. Rado raises the question of obtaining similar estimates for a “two-dimensional” problem in which the “napkins” are *squares* (of different sizes), and the “table” is, say, a *square* (or *rectangle*) of area 1, and the edges of the napkins are parallel to the edges of the table (Fig. 3).

⟦figure⟧
Fig. 3

So, the difference between Rado’s problem and problem M321 (Brailov) is only in the form of “napkins”: in M321 they can be any rectangles, but in Rado’s they can only be squares. But this “small” difference, as often happens, completely changes the matter.

The method by which we extracted a subsystem of length at least $\dfrac13$ from a system of segments covering a segment of length 1 also works in the two-dimensional case. With his help, T. Rado proved this fact.

Theorem 2. *From any covering of a flat “table” of area 1 with square “napkins” one can choose a covering with non-overlapping “napkins” whose sum of areas is not less than $\dfrac19$.*

Exercise 5.

1. Prove Theorem 2.
2. Come up with an example showing that in the formulation of Theorem 2 the number $\dfrac19$ cannot be replaced by the number $\dfrac14$.

Thus, in the Rado problem (unlike the Brailov problem) there also exists some critical value $\eps_0$ such that

at $\eps\gt\eps_0$, true

Statement 1. We can specify an example of a “napkin” system such that any subsystem of non-overlapping “napkins” has a total area less than $\eps$,

and for $\eps\lt\eps_0$ it is true

Statement 2. From any system of “napkins” one can choose a subsystem of non-overlapping “napkins” with a total area of ​​at least $\eps$.

Of course, we always consider the area of ​​the “table” to be equal to 1.

T. Rado was able to prove that for the critical value $\eps_0$ the following estimates are true:
$$
\dfrac19\le\eps_0\le\dfrac14,\tag1
$$
but I was sure that in fact it was $\eps_0=\dfrac14$.

He proposed to prove this equality in a letter to Waclaw Sierpinski.

However, neither Sierpinski nor other mathematicians succeeded in doing this, although many took on Rado’s problem. And only 55 years later, in 1973, it became clear why. It turns out that T. Rado's hypothesis is simply wrong! A sensational note by the Hungarian mathematician M. Ajtai appeared in the Bulletin of the Polish Academy of Sciences, in which it was quite simply shown that with squares of only two different sizes it is possible to cover a rectangle of area 1 in such a way that it is impossible to choose from them a disjoint subsystem of area $\dfrac14$ or larger. It is now known that $$
\dfrac1{8{,}6}\lt\eps_0\lt\dfrac14;\tag2
$$
the left inequality was the result of successive refinements of inequality (1) by T. Rado, the last of which belongs to the Leningrad geometer V. A. Zalgaller (apparently, it is also not final, being much closer to the “rough” result of Theorem 2 than to the hypothetical estimate of T. Rado).

The most beautiful and simple solution to a special case of the Rado problem is when all the “napkins” are squares of the same size. In this case, the critical value $\eps_0$ turns out to be really equal to $\dfrac14$. This result was proven back in 1940 by the young Leningrad mathematician A. S. Sokolin (and later, independently of him, by many others, and in several different ways).

### Blichfeld's theorem and Sokolin's result

Let us first prove such a pleasant theorem, one of the variants of which was devoted to the second cover page «Kvant», 1973, No. 10.

Blichfeld's theorem. *If the area of ​​a figure located on a sheet of checkered paper is greater than $n-1$ (where $n$ is an integer; the side of the cell is taken as $1$), then this figure can be moved by parallel transfer to such a position that it covers at least $n$ grid nodes. (Nodes are points where lines intersect, dividing the plane into square cells.)*

Proof. Let's cut a sheet of checkered paper into separate cells and collect together, in a stack, all those cells that can accommodate at least part of the figure (from figure 4, *a* we move to figure 4, *b*). Since the sum of the areas of the pieces of our figure is greater than $n-1$, then some points in the stack will be covered by at least $n$ pieces of the figure. Let's pierce one of these points with a needle; There will be a puncture mark on each piece. If we now place the stacked cells on the plane in the same order (of course, we assume that the cells were combined by parallel transfer), then the punctures will be located “in the correct way” - at the vertices of the new grid of squares with side 1 (Fig. 4, *c*). It remains to move the figure in parallel so that these punctures align with the nodes (Fig. 4, *d*).

⟦figure⟧
Fig. 4

Exercise 6. Prove that if the area of ​​a figure is less than $n+1$, then it can be moved so that it touches no more than $n$ grid nodes ($n$ is an integer).

Using Blichfeld's theorem, we obtain the result we need.

Theorem 3. *If a system of congruent squares with mutually parallel sides covers a figure of area $S$, then from it we can select a subsystem of disjoint squares (without common internal points) with each other, the sum of areas of which is not less than $\dfrac S4$.*

What kind of figure the squares cover does not matter here, as well as in the Rado problem. Only its area is important.

Proof. We deliberately formulated the theorem somewhat differently than the previous ones (the area of ​​the “table” is now $S$, not 1) in order to be able to choose a different unit of length. We will assume that the side length of each “napkin” is equal to $\dfrac12$. According to Blichfeld's theorem, we can place our figure (area $S$) on checkered paper (with side square 1) so that it covers $n\ge S$ grid nodes. Let's leave one “napkin” covering each of these $n$ nodes. It is clear that the selected “napkins” cannot overlap each other, and their total area is equal to
$$
\dfrac14n\ge\dfrac S4.
$$
Sokolin's theorem has been proven.

### Variants of the Rado problem

Another famous Hungarian mathematician, R. Rado, spent the most effort on T. Rado's problem. In 1950, 1951, 1968 he published three extensive articles in English journals: “Several Theorems on Coverings,” I-III, entirely inspired by T. Rado’s problem (so we had reason to call the article “On the Rado Problem” without indicating the initial). We list only some results and unsolved issues related to this problem.

For the problem of the triangular “table” $\mathrm{T}$ and similar triangular “napkins” (with correspondingly parallel sides), we managed to obtain some estimates for $\eps_0$; in particular, for covering $\mathrm{T}$ by congruent (and parallel) triangles (an analogue of Sokolin’s result), we can specify the critical value $\eps_0$ exactly: $\eps_0=\dfrac16$. (Of course, in this problem we can always talk about a “table” shaped like a regular triangle.)

Some estimates were also obtained for round “napkins” (of the same and different sizes), and for other types of “napkins” similar to each other.

Exercise 7. Prove that if all “napkins” are similar to a given figure $\Phi$ (which they cover), then there exists $\eps_0\gt0$ such that from any covering of a “table” of area 1 we can select a subsystem of non-overlapping “napkins” with a total area of ​​at least $\eps_0$ ($\eps_0$, of course, depends on the shape $\Phi$).

Thus, here the critical value $\eps_0$ is always positive, in contrast to Brailov’s problem, in which $\eps_0=0$ (where the “napkins” are rectangles, not necessarily similar to each other!).

Other generalizations of the Rado problem were also considered, for example: what is the largest total area that the total area of ​​two subsystems can have, in each of which the “napkins” do not overlap each other; what are the estimates for the spatial analogues of the Rado problem - but in all these directions only partial results and rather rough estimates have been obtained.

Exercise 8.

1. For the spatial analogue of the Rado problem (on covering a cube with cubes), prove the inequalities
$$
\dfrac1{27}\lt\eps_0\le\dfrac18.\tag3
$$
2. Formulate and prove an analogue of Theorem 3 for this case.

A number of problems close to Rado’s problem (including those proposed above as exercises), along with their solutions, can be found in the latest issues of the “Mathematics Circle Library” and “Physics and Mathematics School Library” series:

D. O. Shklyarsky et al., “Geometric estimates and problems from combinatorial geometry”, M., Nauka, 1974, series of problems 3;

N. B. Vasiliev et al., “Mathematical competitions; geometry", M., Nauka, 1974, problems 7.6-7.9.
