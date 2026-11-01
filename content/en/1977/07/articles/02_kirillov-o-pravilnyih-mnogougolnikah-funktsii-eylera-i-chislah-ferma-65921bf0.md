---
id: 1977-7-kirillov-o-pravilnyih-mnogougolnikah-funktsii-eylera-i-chislah-ferma-65921bf0
issue: kvant_1977_7
year: 1977
number: "7"
title: About regular polygons, Euler's function and Fermat numbers
authors:
  - Кириллов А. А.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2, 6, 7, 8
tag: JUAU
lang: en
source: kvant_digital
extraction: vision
content_sha256: bb4af3e6e6b1bb38a2aec81640a9c016d24a491ae52cb9ba0f0859e1578ae33e
prompt_sha256: draft-1
translated_from: content/ru/1977/07/articles/02_kirillov-o-pravilnyih-mnogougolnikah-funktsii-eylera-i-chislah-ferma-65921bf0.md
source_content_sha256: 6eb99ab39ff00f55b870785bac53290f5c30fb73691b476d8e4ae5249959fe44
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

1. Prologue

Problems on geometric constructions are one of the most popular in school mathematics. Almost every math club breaks down such problems. This is, of course, no coincidence. The history of geometric constructions goes back several thousand years, and the ancient Greeks already achieved great art here. An example is the Apollonius problem: construct a circle tangent to three given circles *).

Many people are probably aware of three significant problems of antiquity that turned out to be unsolvable: the square of the circle, the trisection of the el and the double of the cube**).

But perhaps the most beautiful one is the problem of constructing regular polygons. Strictly speaking, this is not one problem, but a whole series of problems: for each natural number n ≥ 3, you need to use a compass and a ruler to construct the correct n-number.

Is there any pattern in the distribution of “red” and “black” numbers? It turns out there is; but it is quite difficult to find. This pattern is of an arithmetic nature; to describe it, we will have to temporarily leave the geometric

*) See the article “Inversion and the Apollonius Problem” («Kvant», 1971, No. 8).

**) For the last two problems, see the article “Compass and Ruler” («Kvant», 1975, No. 6).

*) The method of constructing a regular seventeen-sided triangle with a compass and ruler was first discovered by K. F. Gauss in 1801. This method is described in the article “Gauss's Debut” («Kvant», 1971, No. 1).

⟦folio 6⟧

sleigh and three outside circles), and all these answers are equal if we formulate the problem as follows: construct a circle tangent to three given lines. The difference between an inscribed circle and an outer circle is based on the concept of “between” (or “inside”) and is beyond the understanding of our machine.

The analyzed examples also show that if a construction problem has several solutions, then the construction program gives all these solutions. This statement is also true in the general case.

An honorable example: the geometric construction of one of the roots of a quadratic equation automatically leads to the construction of the second root.

Thus, we come to the next prin and pu.

Every construction problem solved using a compass and straightedge has a 2' solution.

A rigorous proof of this statement is given by Galois theory and cannot be presented in this article. However, the statement itself looks very simple and could have been fully discovered by ancient mathematicians. The question arises, why was this discovery made only in the last century, although many confirming examples have been known for several millennia? (For example, the Apollonian problem mentioned above has 8 solutions.)

One of the possible reasons is the lack of modern, “machine” construction of the problem. Another reason is to consider each problem separately together with the goal of tasks of the same type (such as problems of constructing a regular n-gon for each n).

Perhaps this topic will attract the attention of historians of mathematics, and they will more usefully explain to us the reason for this “lost opportunity.”

4. Regular polygons

Let's return to our main task. We want to know when a regular n-gon can be constructed using a compass and straightedge. The reasoning in the previous paragraph suggests the idea of ​​looking at how many solutions this problem has. To get the answer, you need to clarify the construction task. Namely, you need

**Fig. 5.**

fix the size and position of a regular n-gon (otherwise, of course, the number of solutions will be infinite, provided that there is at least one solution). So, we will assume that our n-gon is inscribed in a given circle o with center O, and the fixed position A₀ of one of its vertices. It is required to determine the positions A₁, A₂, ..., Aₙ−1 of the remaining vertices. Of course, it is enough to find the position of point A₁ - plotting the successive arcs A₀A₁, we get points A₂, A₃, A₄, etc.

This problem is easiest to solve when n = 6. It is known that the side of a regular inscribed hexagon is equal to the radius of the given circle. Therefore, the “program” needs to look like this (Fig. 5):

1. Using a compass, construct a circle ω₁ of radius |OA₀| from point A₀.
2. Let us mark the point A₁ of intersection of the circle ω and ω₁.

We see that this program produces two different answers, but the corresponding hexagons A₀A₁′A₂′A₃′A₄′A₅′ and A₀A₁′A₂′A₃′A₄′A₅′ differ only in the vertex numbering order.

The same situation is observed in the case of n = 3 and n = 4. More interesting are the cases of n = 5 and n = 10. The method of constructing a regular pentagon is described in the article by A. Savin “How to draw a five-pointed star” («Kvant», 1976, No. 1). We will consider here the case n = 10.

⟦folio 7⟧

Fig. 6.

If the bisector $A_1B$ of the angle $OA_1A_0$ is drawn, then the resulting triangles $OA_1B$, $BA_1A_0$ will be equilateral (Fig. 6), and the triangles $OA_1A_0$ and $BA_1A_0$ will be similar.

We will consider the straight line $OA_0$ to be the number axis on which point $O$ corresponds to zero, and point $A_0$ to one. Let the point $B$ correspond to the number $x$. Then we get the equation:

$$\frac{x}{1-x} = \frac{1}{x} \text{ или } x^2 + x - 1 = 0.$$

Solving this equation, we find the point $B$. The required point $A_1$ is found as the point of intersection of the given circle $\omega$ with a circle with center at point $A_0$ and radius of length $x$. There are two such points - and we get two solutions: points $A'_1$ and $A''_1$ (Fig. 6).

But our quadratic equation has two roots: $x_1 = -\frac{1}{2} + \frac{\sqrt{5}}{2}$ and $x_2 = -\frac{1}{2} - \frac{\sqrt{5}}{2}$. The second root is disgusting and for this reason seems to be unsuitable. However, let’s not rush to “discard” this root, but let’s try to understand its geometric meaning.

Let us restore figure 6, assuming that the point $B$ is not to the right, but to the left of the point $O$. We get figure 7. This gives the desired point $A_1$ two more possible positions: $A''_1$ and $A'_1$.

So we come to four different possibilities for point $A_1$.

The result is two different decagons: convex and star-shaped, and on each of them two different vertex numberings are possible (see figure 6 and 7).

Note that from the “point of view” of a compass and ruler, a star-shaped decagon is no worse than a convex one.

An objection is possible: in a convex polygon, non-adjacent sides do not intersect, but in a stellate polygon, they do. But this objection disappears if we call the sides not the segment between two vertices (we have no concept of “between”!), but the entire straight line. Then the correct drawing of a “convex” decagon will have an appearance that is only different in size from the “stellated” one (Fig. 8).

A similar situation arises in the case of spotted heels. Here, too, there are 4 solutions leading to two different spots (Fig. 9, a, b) with two different numberings of the vertices on each.

⟦folio 8⟧

Now, without explicitly solving the problem of constructing an arbitrary regular $n$-gon, let’s try to establish how many different solutions it has. (Recall that we consider the circle $\omega$ and the point $A_0$ on it to be given.) Let $x$ denote the length of the arc $A_0A_1$. Point $A_1$ is a solution to the problem (from the circulatory point of view), if, by delaying arcs of length $x$ from point $A_0$ successively $n$ times, we return to the starting point $A_0$, but if we delay it less times, we will not return.

There is one last caveat. Otherwise, in the case of, for example, $n=6$, we would have to call a triangle traversed twice, or a diameter traversed three times, or even the point $A_0$ repeated six times, a “regular inscribed hexagon”.

In the language of arithmetic, taking the length of the entire circle to be one, our condition can be formulated as follows: the number $nx$ is an integer, and the numbers $x$, $2x$, $3x$, ..., $(n-1)$ $x$ are not integers. If $n=10$, then as $x$ you can take, for example, 1/10. But this is not the only possible choice. You can take $x$ also equal to 3/10, 7/10 or 9/10.

This corresponds to the four solutions that we previously found geometrically. Note that if we take the number 11/10 (or 13/10, 17/10, ...) as $x$, then we will not get new geometric solutions: the position of the point on the circle depends on the number $x = \frac{k}{n}$ itself, and on the remainder, which gives $k$ when divided by $n$.

It is clear that the irreducible fractions $\frac{m}{n}(m<n)$ and only they have the property that $k \cdot \frac{m}{n}$ falls into an integer (at the initial point of the circle) only at $k=n$. Thus, every number less than $n$ and combined with it by projection gives a solution to the problem of a regular $n$-gon, and we find that the number of different solutions to this problem is given by the Euler function (see section 2)! In particular,

$$\varphi(3) = \varphi(4) = \varphi(6) = 2,$$
$$\varphi(5) = \varphi(10) = 4,$$

which is consistent with the results obtained above geometrically.

Let us now recall that every solvable problem of construction using a compass and straightedge must have $2^l$ different solutions (see Section 3), we obtain a convenient necessary condition for the solvability of the problem of constructing a regular $n$-gon.

A regular $n$-gon allows the construction of a compass and a straightedge, which is $\varphi(n) = 2^l$ for some integer $l$.

(For example, it is impossible to construct a regular heptagon because the number $\varphi(7) = 6$ is not a power of two.)

We set out to explain the necessity of this condition. The fact that it is also sufficient is from
