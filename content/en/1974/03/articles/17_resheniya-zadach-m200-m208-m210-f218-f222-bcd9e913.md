---
id: 1974-3-resheniya-zadach-m200-m208-m210-f218-f222-bcd9e913
issue: kvant_1974_3
year: 1974
number: "3"
title: Solutions to problems M200, M208—M210; F218—F222
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 42
page_labels: 36-40
tag: WCQM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 22821030321c9d5030a7654815f844941a6d02f46cc5a3e3d6330860b9e627d4
prompt_sha256: draft-1
translated_from: content/ru/1974/03/articles/17_resheniya-zadach-m200-m208-m210-f218-f222-bcd9e913.md
source_content_sha256: c4f50118948359cfc69fe24071de6923b1aa8f902b4304038452f30bef106944
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

Problem solutions
M200, M208-M210; F218-F222

M200. a) On figure 1 there are six points, which lie three on four lines. Prove that it is possible to map this set of six points onto itself mak in 24 different ways, so that each three points lying on one line are mapped to three points also lying on the same line.

6) On figure 2 two points lie three on four straight lines, and through each point there are three maximum values ​​of the “Pascal configuration”. In how many ways can the set of our ninth points be mapped onto itself mak, so that every triple point lying on one of the ninth lines is mapped onto a 同一 point.

Fig. 1.

Fig. 2.

Fig. 3.

triplet of a point that lies on a certain line from our configuration?

b) The same question for the Desargues configuration (of ten points and ten lines) shown in figure 3.

In paragraphs 6) and c) of the problem, a significant solution is to find the answer and how to justify it.

The answer can be obtained like this. Let us create a triangle of three points that do not lie on the same line and such that each two of them lie on the same line *), belonging, of course, to our configuration. It is easy to notice that if it is indicated which point goes into each vertex of a given triangle (these three points should also form a triangle), then the position of all other points is due to our condition - three points lying on the same line goes into three points lying on the same line - is determined uniquely in all three cases: a), 6), c).

Let us consider case c) as an example. Let, when displaying, points i, j, k move to points 1, 2 and 3, respectively. Then the point l that is connected by straight lines to each of the points i, j, k should go to point 4 - two points lying on the straight line should go to two points lying on the straight line - and to points 5, 6, . . . , 10 must cross the third point lying on the lines passing through the pairs of points i, j, k, l.

Posny in case a) there are indeed 24 different mappings: any of the six points can be mapped to the first vertex of the selected triangle, any of the four points lying on the same line with it can be mapped to the second, and the point of transition to the third vertex is uniquely determined. Total 6·4=24 mappings. Similarly, in paragraphs 6) and c) the answers are: 9·6·2=108 and 10·6·2=120 (here not one, but two points can go to the third vertex of the triangle). However, it is not easy to justify our calculations: in making them, we used the “equal rights” of all triangles. For example, it could turn out that there is no point l, to which points i, j, k are connected by straight lines, or that there are two such points. Although this equality appears to exist, it still needs to be proven. Of course, this can be done “any way”, taking in case a) 24 triangles, in case b) 108 triangles, and in case c) 120 triangles (we distinguish between triangles with different orders of vertices). But you can do it differently. Since to describe our configurations there is only which points lie on a given line and which lines pass through a given point - this information is necessary and sufficient to study mappings - we can define our configurations using a model: point to

*) The order of the points included in the triad exists.

⟦folio 37⟧

boron “straight”, “points” and indicate which points and straight incidentins. Point i and line j are incident if point i lies on line j or, what is the same, line j passes through point i. figure 4 shows several models of the same configuration.

We will build for each of the configurations a), 6), c) such models for which the equilateral triangles will be obvious.

Point a). Let's consider a tetrahedron - a regular triangular paramid - and its vertices as straight lines, and its edges as points. Let's say that point i is incident to line j if vertex j is incident to edge i. Check that the configuration model of point a) is obtained. The triangles in this model correspond to three edges that apply to one boundary, and our mapping corresponds to the rotations and symmetries of the tetrahedron. These transformations are shown in figure 5. Check that they take three points on the same line to three points on the same line. In this model, the equivalence of all triangles is very convenient.

Pascal configuration. Pascal's configuration model will be a little more convoluted. Consider a grid of regular triangles formed third by families of parallel lines (see Fig. 6). Let's make “points” and “lines” from lines and nodes of this mesh as follows. Let's draw all the parallel lines through three into one “straight line” and, similarly, all the nodes located on the straight lines through three will be combined into one “point”. On figure 6, the nodes included in the same “point” are lined identically, and the lines included in the same “straight” have the same color. “Point” and “straight” incidentins if the incidentins that constitute them are nodes and straight lines.

I'm more married. Make sure you get a Pascal configuration model.

The triangle in the model corresponds to the set of triangles shown in figure 7. It is easy to verify that rotations, parallel translations and symmetries of the plane, which transform the mesh into itself, are valid *) mappings. Therefore, the equivalence of all triangles is very useful - any triangle can be translated into any other using an admissible mapping.

I'm more married. Prove that there are no other admissible mappings.

Desargues configuration. We present the Desargues configuration as follows. Let's take a tetrahedron and mark the midpoints of its edges (see Fig. 8). The point is the vertex of the tetrahedron and the midpoint of its edges, and the straight lines are its edges and the midpoint of the edges lying in the same boundary. A prim-edge contains the vertices lying on it and its middle.

*) For brevity, this is what we will call mappings that satisfy the conditions of the problem.

⟦folio 38⟧

Fig. 9.

It's tighter. Make sure you get a model of the Desargues configuration.

Which triplets of points in our model are triangles? These are vertices lying on the same face, or a vertex and the midpoints of edges adjacent to it, or the midpoints of edges adjacent to one vertex (see Fig. 9).

Although from the point of view of the general tetrahedra transformations - rotations and symmetry (see Fig. 5) - these triangles are not equal, it is enough to add another transformation $T$ (it is shown in figure 10) to make sure that all triangles are equal and thereby the correct answer.

It's tighter. Make sure that repeats, symmetries, and the $T$ mapping are valid mappings. Specify all valid mappings.

Solution problem.

In conclusion, a few more questions for you to think about on your own. How many admissible mappings of our configurations are there that leave fixed:

a) a given point;
b) a given pair of points;
b) a given line (that is, a mapped permutation of points lying on a given line);
d) a given pair of lines, etc.

**M208. It is known that the difference between the largest and smallest real number**

$$x_1, x_2, x_3, \dots, x_{10}$$

correct 1. Which:
a) largest;
b) smallest
- may be the difference between the largest and smallest of 10 numbers

$$x_1, \frac{x_1+x_2}{2}, \frac{x_1+x_2+x_3}{3}, \dots, \frac{x_1+x_2+\cdots+x_{10}}{10}$$

What will be the answer if there are not 10 numbers, but n?

We will solve the problem immediately for $n$ numbers. Let us make a few preliminary remarks.

Let us denote by $y_k$ the number $\frac{x_1+x_2+\cdots+x_k}{k}$, where $k=1, 2, \dots, n$. If we add a certain number $a$ to all $x_i$, then instead of the numbers $y_i$ we get the numbers $y_i+a$. The maximum differences for the numbers $y_i$ and for the numbers $y_i+a$ are the same. Therefore, from the set $\{x_i\}$, using the selection approach $a$, we can go to a set $\{x_i'\}$ such that all $x_i' \geq 0$, the smallest $x_i$ are equal to zero, and the largest ones are equal to one. In what follows we will consider only such sets. Similarly, if you replace the numbers $x_i$ with $1-x_i$, then $y_i$ is replaced with $1-y_i$. Therefore, from the set $\{x_i\}$ one can go to the set $\{1-x_i\}$: the maximum differences between the numbers $y_i$ and the numbers $1-y_i$ are the same.

Let us now solve problem a). Let $y_k$ be the smallest and $y_l$ the largest of the numbers $\{y_i\}$. If $k < l$, then

$$y_l - y_k = \frac{ky_k}{l} + \frac{x_{k+1}+\cdots+x_l}{l} - y_k = \frac{x_{k+1}+\cdots+x_l}{l} - \frac{l-k}{l} y_k \leq \frac{x_{k+1}+\cdots+x_l}{l} \leq \frac{l-k}{l} = 1 - \frac{k}{l} \leq 1 - \frac{1}{n}.$$

If $l > k$, then $y_l - y_k = \frac{k-l}{k} y_l - \frac{y_{l+1}+\cdots+y_k}{k} \leq 1 - \frac{l}{k} \leq 1 - \frac{1}{n}$. Therefore, the maximum difference is no more than 1 – $\frac{1}{n}$. A set with such a difference is easy to indicate: $x_1 = 0, x_2 = x_3 = \dots = x_n = 1$.

Let's move on to solving problem 6). Let us estimate what the maximum difference is if the set contains $\{x_i\}$ $x_k = 1, x_l = 0$. We will assume that $k < l$ (if this is not the case, then we will move from the set $\{x_i\}$ to the set $\{1-x_i\}$).

If $k = 1$, then the difference is not less than $\frac{1}{n}$.

Indeed, then $y_1 = 1$, and $y_n = \frac{x_1+x_2+\cdots+x_n}{n} \leq \frac{n-1}{n}$, since all are $x_i < 1$, and one of them is equal to zero. Let $\Delta_1 = y_k - y_{k-1} = \frac{1}{k-1} - \frac{y_k}{k-1}, \Delta_2 = y_{l-1} - y_l = \frac{y_{l-1}}{l}$, and if $y_k \leq y_{l-1}$, then $\Delta_2 \geq \frac{y_k}{l}$.

⟦folio 39⟧

The largest of the numbers $\Delta_1$ and $\Delta_2$ is not less than $\frac{1}{k+l-1}$, since $1 \leqslant (k-1)\Delta_1 + l\Delta_2 \leqslant (k+l-1)M$, where $M = \max(\Delta_1, \Delta_2)$. If $y_k > y_{l-1}$, then consider the difference $\Delta_3 = y_k - y_l = y_k - y_{l-1} + \frac{y_{l-1}}{l}$. $\Delta_3 + (k-1)\Delta_1 = (l-1)(y_k - y_{l-1}) + 1 > 1$, from where max($\Delta_1, \Delta_3$) $\geqslant \frac{1}{k+l-1}$. So we have proven that the difference is not less than $\frac{1}{k+l-1}$. Therefore, for an arbitrary set it is no less than $\frac{1}{2(n-1)}$ ($l \leqslant n, k \leqslant n-1$). Such a difference can be realized: it is enough, for example, to consider the set $x_1 = x_2 = \dots = x_{n-2} = \frac{1}{2}$, $x_{n-1} = 1$, $x_n = 0$. So, our difference is $\frac{1}{2(n-1)}$

L. G. Limanov

**M209. For any triangle ABC you can calculate the maximum:**

$$S = \text{tg}^2 A/2 + \text{tg}^2 B/2 + \text{tg}^2 C/2.$$

Prove that

a) $S \leqslant 2$ for all acute and right triangles;

b) $S \geqslant 2$ for polygonal triangles with a core angle greater than or equal to 2 arcctg 4/3;

b) among triangles with a core angle $\varphi$ maxim that $\frac{\pi}{2} < \varphi < 2$ arcctg 4/3, there are $u$ maxim that $S > 2$, $u$ maxim that $S < 2$.

Let us present one of the shortest solutions, close to the one sent by S. Berko-laiko (Belgorod region) and A. Gritsoryan (Baku).

From the formula

$$\text{tg} \left( \frac{\pi}{2} - \frac{A}{2} - \frac{B}{2} \right) = \frac{1 - \text{tg} \frac{A}{2} \cdot \text{tg} \frac{B}{2}}{\text{tg} \frac{A}{2} + \text{tg} \frac{B}{2}}$$

it follows that positive numbers $x, y$ and $z$ can serve as tangents of polynomials $\Delta ABC$ if and only if $xy + yz + zx = 1$. (1)

Also, (1) allows, together with the sum $S = x^2 + y^2 + z^2$, to consider the simpler sum $T = x + y + z$: since $T^2 = S + 2$, then the conditions $S > 2$, $S = 2$ and $S < 2$ are equivalent to the conditions $T > 2$, $T = 2$ and $T < 2$, respectively.

The task thus comes down to the following.

Let $xy + yz + zx = 1$, $x + y + z = T$, $0 < x \leqslant z$, $0 < y \leqslant z$.

Then

a) $T \leqslant 2$ at $z \leqslant 1$;

b) $T \geqslant 2$ at $z \geqslant 4/3$;

b) for every $z$ between 1 and 4/3 there are $x, y$ such that $T < 2$ and $x, y$ such that $T > 2$.

Let us prove statement a), b) and c).

a) If $z \leqslant 1$, then $S = x^2 + y^2 + z^2 \leqslant xz + yz + z^2 < xy + yz + z^2 = 1 + z^2 \leqslant 2$, so both $S < 2$ and $T < 2$.

6) If $z = \frac{4}{3} + d$, $d \geqslant 0$, then $x + y \geqslant \frac{2}{3}$ -- d.

Let's prove this by contradiction: suppose that $x + y < \frac{2}{3} - d$.

Then

$$xy \leqslant \frac{(x+y)^2}{4} < \frac{1}{9} - \frac{d}{3} + \frac{d^2}{4},$$

$(x+y)z < \left(\frac{2}{3} - d\right)\left(\frac{4}{3} + d\right) = \frac{8}{9} - \frac{2d}{3} - d^2,$

So

$$1 = xy + (x+y)z < 1 - d - \frac{3d^2}{4} \leqslant 1.$$

The resulting contradiction proves that $x + y \geqslant \frac{2}{3} - d$, and $T = (x+y) + z \geqslant \frac{2}{3} - d + \frac{4}{3} + d = 2.$

b) Let now $1 < z < \frac{4}{3}$.

First, let's find $x$ and $y$ such that $T < 2$. Let's take $x = y$. According to identity (1) then $x = y = \sqrt{z^2 + 1} - z$, $T = 2\sqrt{z^2 + 1} - z$. Since $z < 4/3$, $4(z^2 + 1) < 4 + 4z + z^2$, $2\sqrt{z^2 + 1} < z + 2$, and therefore $T < 2$.

Sweeping. Returning to the original formulation of the problem, we see that for isosceles tipagonal triangles with type angle $\varphi < 2$ arcctg $4/3$ the sum is $S < 2$.

Now let's find $x$ and $y$ such that $T > 2$. Using identity (1), we write $T$ in the form $T = (x+y) + z = \frac{1 - xy}{z} + z$.

The sum $z + \frac{1}{z} > 2$, $T$ differs from it by the amounts $\frac{xy}{z}$. Since $y \leqslant z$, then $\frac{xy}{z} \leqslant x$.

This means that if we take $x < z + \frac{1}{z} - 2$, then $T$ turns out to be

⟦folio 40⟧

More than 2 is required. All that remains is to check that there are real $x$ and $y$ satisfying the conditions $0 < x \leq z$, $0 < y \leq z$,

$$xy + yz + zx = 1 \text{ и } x < z + \frac{1}{z} - 2. \quad (2)$$

Let us use the fact that $z > 1$ (note that for $z \leq 1$ such $x$ and $y$ do not exist - this follows, for example, from point a). According to (1) $y = \frac{1 - xz}{x + z}$. At $z > 1$ and at $0 < x < \frac{1}{z}$, obviously, $0 < y < 1$. So, for any $x > 0$ such that $x < \frac{1}{z}$ and $x < z + \frac{1}{z} - 2$, for $y = \frac{1 - xz}{x + z}$ conditions (2) are satisfied. Thus, at $1 < z < \frac{4}{3}$, if $0 < x < z + \frac{1}{z} - 2$ and $y = \frac{1 - xz}{x + z}$, then $T > 2$. Solution problem.

Geometric meaning. Let us construct three circles $\alpha$, $\beta$, and $\gamma$ with centers $A$, $B$ and $C$, which touch each other externally in pairs.

At $S < 2$, there is one circle $\delta$ which touches $\alpha$, $\beta$ and $\gamma$ externally, and one circle $\varepsilon$ which $\alpha$, $\beta$ and $\gamma$ touch internally.

At $S > 2$ two circles $\delta_1$ and $\delta_2$ touch $\alpha$, $\beta$ and $\gamma$ externally, in addition $\alpha$, $\beta$ and $\gamma$ touch internally.

The case $S = 2$ is transitional: one circle $\delta$ touches $\alpha$, $\beta$, $\gamma$ externally, in addition $\alpha$, $\beta$ and $\gamma$ touch internally.

The proof of these statements can be found in the article “Surprises” («Kvant», 1974, No. 1).

M. L. Gerver

M210. A sequence distance consisting of 3000 digits $1$ and $2$. In this sequence, you can swap any two adjacent lines of numbers. Two sequences are said to be equivalent if one of them can be transformed into the other by several maximal permutations. How many non-sliced ​​sequences are there?

Let's solve the problem for sequences of 3n digits. To avoid confusion, we will use Greek letters to denote sequences, and Latin letters to denote sequence elements. Let the sequence $\alpha$ consist of 3n digits

$$\{a_1, a_2, \dots, a_{3n}\}.$$

The scope of $\alpha$ into three sequences:

$$\alpha_1 = \{a_1, a_4, a_7, \dots, a_{3k+1}, \dots, a_{3(n-1)+1}\},$$

$$\alpha_2 = \{a_2, a_5, a_8, \dots, a_{3k+2}, \dots, a_{3(n-1)+2}\},$$

$$\alpha_3 = \{a_3, a_6, a_9, \dots, a_{3k}, \dots, a_{3n}\}.$$

We will call such a development standard. Each of the sequences $\alpha_1, \alpha_2, \alpha_3$ is a standard development of $n$ digits. Let $\beta$ be an arbitrary sequence. Let $|\beta|$ denote the number of ones in the sequence $\beta$.

Counting the number of non-equivalent sequences is based on the following theorem:

Theorem. Let $\alpha$ and $\beta$ be two sequences of length $3n$, $(\alpha_1, \alpha_2, \alpha_3)$ and $(\beta_1, \beta_2, \beta_3)$ their standard partitions.

In order for the sequences $\alpha$ and $\beta$ to be equivalent, it is necessary and sufficient that the sequences $\alpha_1$ and $\beta_1, \alpha_2$ and $\beta_2, \alpha_3$ and $\beta_3$ contain the same number of ones corresponding to the triple number $(|\alpha_1|, |\alpha_2|, |\alpha_3|)$. These numbers can take any value from 0 to $n$. Therefore, the number of non-equivalent sequences of length $3n$ is equal to the number of distinct ordered triples of integers from 0 to $n$. It is easy to see that the number of such triples is $(n + 1)^3$.

Proof of the theorem. Let us rearrange two sequences of numbers in the sequence $\alpha = \{a_1, a_2, \dots, a_{3n}\}$: $a_k, a_{k+1}, a_{k+2}$ and $a_{k+3}, a_{k+4}, a_{k+5}$. This permutation can be represented as follows: first the numbers $a_k$ and $a_{k+3}$ were placed, then the numbers $a_{k+1}$ and $a_{k+4}$ were placed, and finally the numbers $a_{k+2}$ and $a_{k+5}$ were placed. The numbers $a_k$ and $a_{k+3}$ are adjacent digits of the same sequence of standard development $\alpha$; the numbers $a_{k+1}$ and $a_{k+4}$ are the other, and the numbers $a_{k+2}$ and $a_{k+5}$ are the third. Thus, in each of the subsequences $\alpha_1, \alpha_2, \alpha_3$ of the standard development $\alpha$ we have rearranged two adjacent terms. This means that if the sequence $\beta$ is obtained from the sequence $\alpha$ by a finite number of permutations, that is, if the sequence $\alpha$ and $\beta$ are equivalent, then the subset $\beta_1, \beta_2, \beta_3$ of standard development $\beta$ is essentially a permutation
