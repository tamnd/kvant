---
id: 1974-6-bendukidze-figurnyie-chisla-559ab51a
issue: kvant_1974_6
year: 1974
number: "6"
title: Curly numbers
authors:
  - Бендукидзе А. Д.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 55
page_last: 57
page_labels: 53-55
tag: XG2D
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9e99f44818233e69bf476afa8aa5ab10b1e982dcaddda33ed8e8c600b938799c
prompt_sha256: draft-1
translated_from: content/ru/1974/06/articles/20_bendukidze-figurnyie-chisla-559ab51a.md
source_content_sha256: 7b3bab54703de40e49396065e461629ac921870b8361581516e1af80395b457d
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 53⟧

1
Here I have drawn three dots (Fig. 1).
I drew it in such a way that if you connect them in pairs, you get a regular (that is, equilateral) triangle (Fig. 2). However, taken points even without connecting create, so to speak, the “impression” of a triangle.

And if there are four points, can they be arranged in a similar way? It turns out - no; see for yourself. And five dots won't do either. But it is already possible to arrange six points in the required order (Fig. 3). In this case, a new “six-point” triangle is obtained from the “three-point” one by linearly doubling the latter; this causes the addition of new points (Fig. 4).

How many more points must be added in order for the “impression” of the triangle to be preserved? The answer is not difficult to find: four. The corresponding triangle - it is obtained by linearly increasing the original one by three times - is depicted at figure 5.

Continuing to add points, we will get more and more triangles. Namely, to the already existing ten points we will add five, then to the resulting fifteen we will add six more points, to them seven more, etc. (do figure yourself!).

Let's now try to figure out how many points you need to have so that you can create a “triangular configuration” from them.

In our examples, at first there were 3, 6, 10 points; then 15, 21, 28, . . .

These numbers, for obvious reasons, are called *triangular*. We want to find out what kind of triangular numbers there are. This is not difficult to do if you notice that

$$3 = 1 + 2$$
$$6 = 1 + 2 + 3$$
$$10 = 1 + 2 + 3 + 4$$
$$15 = 1 + 2 + 3 + 4 + 5$$

⟦folio 54⟧

The pattern according to which these numbers are compiled is striking. It can be proven that this pattern continues to apply. This means that if the $n$th triangular number is denoted by $T_n$ and we assume that $T_1 = 1$, then the following formula will be valid:

$$T_n = 1 + 2 + 3 + \dots + n.$$

It looks quite simple, but is clearly not suitable for calculation. To give it a more convenient form for calculation, note that on the right side of the equality the terms equidistant from the beginning and end add up to the same number, namely $n + 1$.

Now everything is very simple: we write our formula twice, in the second case the order of the terms is reversed:

$$T_n = 1 + 2 + 3 + \dots + (n - 2) + (n - 1) + n,$$

$$T_n = n + (n - 1) + (n - 2) + \dots + 3 + 2 + 1.$$

Let's add these two equalities in a “column”; then on the left side we get $2T_n$, and on the right side we get the number $n + 1$, taken $n$ times. So, $2T_n = n(n + 1)$, from where

$$T_n = \frac{1}{2}n(n + 1).$$

The calculation method used here gave us the opportunity to simplify a rather cumbersome expression.

In this regard, I would like to give a traditional story about a boy named Karl, who used this method to solve a similar problem.

“One day, a teacher at the elementary school that Karl attended, wanting to keep the kids occupied longer, offered them a difficult task: adding the numbers 1, 2, 3, etc. up to 100. The students got busy with calculations... Little Karl noticed that pairs of numbers 1 and 100, 2 and 99, 3 and 98, etc. add up to 101. Having calculated in his head that there are 50 such pairs, he wrote on his The answer on the slate board is 5050 and was given by the teacher. The teacher was very surprised...”

The future showed that the teacher should not have been surprised: little Karl later became the Great Karl Friedrich Gauss, the arbitrary “king of mathematicians” during his lifetime!

2

In addition to triangular numbers, there are also square, rectangular, six-integer numbers, etc. They are associated respectively with square, regular pentagon, regular hexagon, etc.

Let us denote the $n$th square number by $K_n$, and the $n$th pentagonal number by $\Pi_n$; Then

$$K_n = n^2, \quad \Pi_n = \frac{1}{2}n(3n - 1).$$

To obtain these equalities, you need which of the numbers $K_n$ and $\Pi_n$

⟦folio 55⟧

Fig. 7.

present it in the form of the corresponding sum (see Fig. 6 and 7) and apply the method of “pairing” terms already known to us. Do the calculations yourself.

Similarly, you can find expressions for hexagonal, heptagonal, etc. numbers. We will solve a more general problem - to find a formula for any $k$-coal number.

3

So let $F^{(k)}_n$ denote the $n$-th $k$-coal number. Let us consider the $k$-gon generating this number (see Fig. 8). Let's take one of the vertices of this polygon, for example, $A$, and draw all the diagonals from it. How many will there be? Let's do the math.

Vertex $A$ can be connected to each of the other $(k-1)$ vertices;

but when connecting $A$ with two adjacent vertices, we get not diagonals, but sides of the polygon. This means that diagonals are obtained by connecting $A$ with $(k-1)-2 = k-3$ vertices. This is the diagonal number.

By drawing diagonals from the vertex $A$, we divide the $k$-gon into $k-2$ triangles (see Fig. 9). Each of these triangles is associated with the $n$-th triangular number $T_n$. Knowing $T_n$, we can count the number of points in a given $k$-gon, that is, find a formula for $F^{(k)}_n$. In fact, there are $T_n$ points in each triangle, and $k-2$ triangles. Total - $(k-2)T_n$ points. In this case, we counted the points lying on the diagonals twice - after all, a diagonal is a side of two adjacent triangles.

Fig. 8.

Fig. 9.
